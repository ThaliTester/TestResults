#### Test 63848581b00dd7c_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-23 13:05:42.852  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-23 13:05:42.928  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-23 13:05:42.929  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:42.929  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:42.929  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-23 13:05:42.943  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-23 13:05:42.971  2743  2743 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-23 13:05:42.972  2743  2743 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-23 13:05:42.973  2743  2743 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
03-23 13:05:43.123  3263  3263 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-23 13:05:43.127  3263  3263 D AndroidRuntime: CheckJNI is OFF
03-23 13:05:43.246  3263  3263 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-23 13:05:43.251   822   838 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-23 13:05:43.257   822   838 V WindowManager: addAppToken: AppWindowToken{194a1645 token=Token{3700c6bc ActivityRecord{c10a2af u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-23 13:05:43.267   822   861 V WindowManager: Adding window Window{25a13154 u0 Starting com.test.thalitest} at 2 of 7 (after Window{21575fc7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-23 13:05:43.273  3263  3263 D AndroidRuntime: Shutting down VM
03-23 13:05:43.274  1513  1513 I HotwordDetector: Closing mic
03-23 13:05:43.274  1513  1765 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@23d77f6a
03-23 13:05:43.336   358  1771 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-23 13:05:43.339   358  1771 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-23 13:05:43.346   822  1412 I ActivityManager: Start proc 3277:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-23 13:05:43.352   358  1021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-23 13:05:43.354  1513  1767 I HotwordRecognitionRnr: Stopping hotword detection.
03-23 13:05:43.354  1513  1768 I HotwordRecognitionRnr: Hotword detection finished
03-23 13:05:43.408   822  1100 I ActivityManager: Killing 2867:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,03-23 13:05:43.484   822  1251 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659176211
03-23 13:05:43.484   822  1251 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-23 13:05:43.513   822  1100 I ActivityManager: Killing 2701:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
03-23 13:05:43.565   877   877 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-23 13:05:43.566   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_lock
03-23 13:05:43.608   877   877 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-23 13:05:43.608   877   877 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
03-23 13:05:43.706  3277  3277 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-23 13:05:43.722  3277  3277 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1938-1942)
03-23 13:05:43.722  3277  3277 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-23 13:05:43.745  3277  3277 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {45a1ad}
03-23 13:05:43.746  3277  3277 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-23 13:05:43.747  3277  3277 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-23 13:05:43.758  3277  3277 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-23 13:05:43.758  3277  3277 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-23 13:05:43.759  3277  3277 E SysUtils: ApplicationContext is null in ApplicationStatus
03-23 13:05:43.767  3277  3302 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
03-23 13:05:43.772  3277  3277 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-23 13:05:43.777  3277  3277 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-23 13:05:43.778  3277  3277 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-23 13:05:43.778  3277  3277 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-23 13:05:43.880   822   860 D BluetoothManagerService: Message: 20
03-23 13:05:43.882   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8dbeb6d:true
03-23 13:05:43.918  3277  3277 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-23 13:05:43.927  3277  3277 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-23 13:05:43.937  3277  3277 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-23 13:05:43.942  3277  3277 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-23 13:05:43.942  3277  3277 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-23 13:05:44.024  3277  3325 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-23 13:05:44.028  3277  3277 D Atlas   : Validating map...
03-23 13:05:44.040   822  1413 V WindowManager: Adding window Window{32db89dd u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{25a13154 u0 Starting com.test.thalitest})
03-23 13:05:44.044  3277  3312 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-23 13:05:44.092  3277  3325 I OpenGLRenderer: Initialized EGL, version 1.4
03-23 13:05:44.105  3277  3325 D OpenGLRenderer: Enabling debug mode 0
03-23 13:05:44.179   822   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +907ms
03-23 13:05:44.200  1233  1233 I Keyboard.Facilitator: onFinishInput()
03-23 13:05:44.233   822   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
03-23 13:05:44.236  3277  3277 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3277
03-23 13:05:44.240   822   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-23 13:05:44.280   259  1487 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (252 us)
03-23 13:05:44.382  3277  3277 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-23 13:05:44.530  3277  3327 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1577632512
,03-23 13:05:44.534  3277  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-23 13:05:44.534  3277  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-23 13:05:44.534  3277  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-23 13:05:44.534  3277  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-23 13:05:44.534  3277  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-23 13:05:44.534  3277  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c41728e added. We now have 1 listener(s)
,03-23 13:05:44.535   822  1357 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:05:44.538  3277  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-23 13:05:44.539  3277  3327 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,03-23 13:05:44.540  3277  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-23 13:05:44.540  3277  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
,03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-23 13:05:44.544  3277  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20c06e45 added. We now have 1 listener(s)
03-23 13:05:44.544  3277  3327 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-23 13:05:44.550   822  1024 D WifiService: New client listening to asynchronous messages,
,03-23 13:05:44.552  3277  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-23 13:05:44.556  3277  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-23 13:05:44.556  3277  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-23 13:05:44.557  3277  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-23 13:05:44.557  3277  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-23 13:05:44.563  3277  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:05:44.564   822  1346 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:05:44.565  3277  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-23 13:05:44.572  3277  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-23 13:05:44.573  3277  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-23 13:05:44.573  3277  3327 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-23 13:05:44.574  3277  3277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-23 13:05:44.574  3277  3327 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-23 13:05:44.590   877   877 I kickstart: STATUS: Received file 'm9kefs1'
03-23 13:05:44.590   877   877 I kickstart: STATUS: 950272 bytes transferred in 0.981786 seconds
03-23 13:05:44.590   877   877 I kickstart: STATUS: Successfully downloaded files from target 
03-23 13:05:44.590   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-23 13:05:44.594   877   877 I kickstart: STATUS: Sahara protocol completed
,03-23 13:05:44.618  3277  3277 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-23 13:05:44.853   822   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-23 13:05:44.854   822   822 V ActivityManager: Display changed displayId=0
03-23 13:05:44.855   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-23 13:05:44.855   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-23 13:05:45.130   259   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-23 13:05:45.132   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-23 13:05:45.132   822  1043 D SurfaceControl: Excessive delay in setPowerMode(): 278ms
,03-23 13:05:45.134   822   863 I DreamManagerService: Entering dreamland.
,03-23 13:05:45.135   822   863 I PowerManagerService: Dozing...
03-23 13:05:45.136   822   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-23 13:05:45.148   358   358 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-23 13:05:45.148   358   358 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-23 13:05:45.158   822  1023 E WifiStateMachine: cancelDelayedScan -> 16
,03-23 13:05:45.161   822  1023 E native  : do suspend false
,03-23 13:05:45.232   822  1412 I art     : Explicit concurrent mark sweep GC freed 40556(2039KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.213ms total 55.200ms
,03-23 13:05:45.262  1233  1233 I Keyboard.Facilitator: onFinishInput()
,03-23 13:05:45.272   822  1023 E WifiStateMachine: cancelDelayedScan -> 18
,03-23 13:05:45.316   358  1030 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-23 13:05:45.316   358  1030 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
03-23 13:05:45.318   822  1023 E native  : do suspend true
,03-23 13:05:45.362   822  1023 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-23 13:05:45.380  3277  3337 W jxcore-log: Initializing JXcore engine
03-23 13:05:45.380  3277  3337 W jxcore-log: JXcore engine is ready
,03-23 13:05:45.404  3337  3337 W Thread-349: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12576]" dev="sockfs" ino=12576 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-23 13:05:45.404  3337  3337 W Thread-349: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-23 13:05:45.404  3337  3337 W Thread-349: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10613]" dev="sockfs" ino=10613 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-23 13:05:45.404  3337  3337 W Thread-349: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21644]" dev="sockfs" ino=21644 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-23 13:05:45.425  3277  3337 W jxcore-log: Starting JXcore engine,
,03-23 13:05:45.501  3277  3337 W jxcore-log: Platform android,
03-23 13:05:45.501  3277  3337 W jxcore-log: 
03-23 13:05:45.501  3277  3337 W jxcore-log: Process ARCH arm,
03-23 13:05:45.501  3277  3337 W jxcore-log: 
,03-23 13:05:45.694  3277  3337 I jxcore-log: JXcore Cordova bridge is ready!,
03-23 13:05:45.694  3277  3337 I jxcore-log: 
,03-23 13:05:45.694  3277  3337 W jxcore-log: JXcore engine is started
,03-23 13:05:45.703  3277  3327 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-23 13:05:45.707  3277  3277 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-23 13:05:45.954   822  1023 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-23 13:05:47.723  1128  1128 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-23 13:05:48.149  1128  1128 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-23 13:05:48.186  1128  1128 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-23 13:05:48.187  1128  1128 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-23 13:05:48.213   822  1023 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-23 13:05:48.214   822  1025 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-23 13:05:48.214   822  1023 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-23 13:05:48.216   822  1023 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-23 13:05:48.219   354   801 D CommandListener: Setting iface cfg
,03-23 13:05:48.222   822  1023 E WifiStateMachine: Start Dhcp Watchdog 1
,03-23 13:05:48.225   822  1023 E WifiStateMachine:  WifiLinkLayerStats: 
03-23 13:05:48.225   822  1023 E WifiStateMachine:  my bss beacon rx: 1
03-23 13:05:48.225   822  1023 E WifiStateMachine:  RSSI mgmt: -39
03-23 13:05:48.225   822  1023 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-23 13:05:48.225   822  1023 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-23 13:05:48.225   822  1023 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-23 13:05:48.225   822  1023 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-23 13:05:48.225   822  1023 E WifiStateMachine:  on_time : 0 tx_time=62 rx_time=110 scan_time=0
,03-23 13:05:48.311   822  1023 E native  : do suspend false
,03-23 13:05:48.318   822  1023 E WifiStateMachine: scanCount==0 - aborting
,03-23 13:05:48.537  3343  3343 I dhcpcd  : version 5.5.6 starting
,03-23 13:05:48.588  3343  3343 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-23 13:05:48.702  3343  3343 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-23 13:05:48.810  3343  3343 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-23 13:05:49.129   822  1023 E native  : do suspend true
,03-23 13:05:49.178   822  1023 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
03-23 13:05:49.179   822  1025 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-23 13:05:49.184   822  1025 D ConnectivityService: Adding iface wlan0 to network 100
,03-23 13:05:49.202   822  1025 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-23 13:05:49.202   822  1025 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-23 13:05:49.204   822  1025 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
03-23 13:05:49.204   822  1025 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
03-23 13:05:49.205   822  1025 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
03-23 13:05:49.212   822  1025 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-23 13:05:49.214   822  1025 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-23 13:05:49.215   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-23 13:05:49.215   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-23 13:05:49.215   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-23 13:05:49.215   822  1025 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-23 13:05:49.215   822  1025 D ConnectivityService:    accepting network in place of null
,03-23 13:05:49.216   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700",
03-23 13:05:49.216   822  1025 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-23 13:05:49.217   822  1025 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
03-23 13:05:49.219   822  1025 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-23 13:05:49.222  1065  1538 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-23 13:05:49.222   822  1025 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-23 13:05:49.222   822  1025 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-23 13:05:49.222   822  1025 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-23 13:05:49.226   822   860 D Tethering: MasterInitialState.processMessage what=3
,03-23 13:05:49.231   822  1100 V BackupManagerService: Scheduling immediate backup pass
,03-23 13:05:49.233   822   822 V BackupManagerService: Running a backup pass
,03-23 13:05:49.235   822  1042 V BackupManagerService: clearing pending backups
,03-23 13:05:49.237  1513  1513 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:05:49.239  3277  3277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-23 13:05:49.239  3277  3277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-23 13:05:49.240  2923  2923 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-23 13:05:49.244   822  1042 V PerformBackupTask: Beginning backup of 14 targets
,03-23 13:05:49.247   822  1042 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-23 13:05:49.250  2923  2923 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-23 13:05:49.256   822  1042 V BackupServiceBinder: doBackup() invoked
,03-23 13:05:49.267   822  1042 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-23 13:05:49.271  1317  1344 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-23 13:05:49.271  1317  1344 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-23 13:05:49.272   822   855 D TelephonyManager: getDataEnabled: retVal=false
,03-23 13:05:49.285   822  1042 I BackupRestoreController: Getting widget state for user: 0
,03-23 13:05:49.296   822   837 I ActivityManager: Start proc 3384:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-23 13:05:49.309   370   370 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 204us total 12.051ms
,03-23 13:05:49.319   370   370 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.379ms
,03-23 13:05:49.329   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 8.994ms
,03-23 13:05:49.336   822   855 E GpsLocationProvider: No APN found to select.
,03-23 13:05:49.358  1807  1837 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-23 13:05:49.360  1807  1837 V GmsBackupTransport: starting performBackup for @pm@
,03-23 13:05:49.366   822  1275 D AlarmManagerService: Setting time of day to sec=1458734749
03-23 13:05:49.686   822  1275 W AlarmManagerService: Unable to set rtc to 1458734749: Invalid argument
,03-23 13:05:49.689   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Mar 2016 12:05:49 GMT], X-Android-Received-Millis=[1458734749688], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458734749340]}
03-23 13:05:49.689   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-23 13:05:49.689   822  1025 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-23 13:05:49.689   822  1025 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-23 13:05:49.689   822  1025 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-23 13:05:49.690   822  1025 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-23 13:05:49.690   822  1025 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-23 13:05:49.690   822  1025 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-23 13:05:49.691  1065  1538 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-23 13:05:49.696  1807  1837 V GmsBackupTransport: performBackup done for @pm@
,03-23 13:05:49.723  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:49.736   822  3404 D GpsLocationProvider: NTP server returned: 1458734749738 (Wed Mar 23 13:05:49 GMT+01:00 2016) reference: 167637 certainty: 33 system time offset: 2
,03-23 13:05:49.749  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-23 13:05:49.749  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:49.749  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:49.749  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:49.752  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:49.765  1773  3421 W DriveInitializer: Background init thread started
,03-23 13:05:49.778  1261  1283 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-23 13:05:49.778  1261  1283 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-23 13:05:49.778  1261  1283 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-23 13:05:49.778  1261  1283 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-23 13:05:49.778  1261  1283 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-23 13:05:49.778  1261  1283 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-23 13:05:49.778  1261  1283 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-23 13:05:49.785  1773  3403 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-23 13:05:49.794   822  1413 I ActivityManager: Start proc 3423:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-23 13:05:49.801  1773  3422 W DriveInitializer: Awaiting to be initialized
,03-23 13:05:49.809  1807  1870 W GmsBackupTransport: Error sending final backup to server: 
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-23 13:05:49.809  1807  1870 W GmsBackupTransport: 	... 1 more
,03-23 13:05:49.811   822  1042 D BackupManagerService: Now staging backup of com.google.android.talk
,03-23 13:05:49.822   822  1042 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-23 13:05:49.829   822  1042 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-23 13:05:49.832   822  1042 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-23 13:05:49.834   822  1042 D BackupManagerService: Now staging backup of com.google.android.gm
,03-23 13:05:49.839   822  1042 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-23 13:05:49.844  3423  3423 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-23 13:05:49.850  3423  3423 D SprintDMHelper: simOperator:  IMSI: null
03-23 13:05:49.850  3423  3423 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-23 13:05:49.852  1773  1773 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-23 13:05:49.853   822  1042 D BackupManagerService: Now staging backup of com.android.nfc
,03-23 13:05:49.855  1773  1773 D SystemUpdateService: onCreate
,03-23 13:05:49.858   822  1042 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-23 13:05:49.860  1773  1773 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-23 13:05:49.860   822  1042 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-23 13:05:49.871   822  1042 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-23 13:05:49.873   822  1042 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-23 13:05:49.883   822  1042 D BackupManagerService: Now staging backup of com.android.vending
,03-23 13:05:49.886  1773  3444 I SystemUpdateService: active receiver: enabled
,03-23 13:05:49.890   822  1042 D BackupManagerService: Now staging backup of android
,03-23 13:05:49.899   822  1042 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-23 13:05:49.903  1773  3444 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-23 13:05:49.909  1773  3444 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
03-23 13:05:49.909  1773  3444 I SystemUpdateService: now status is 0 (complete)
03-23 13:05:49.909  1773  3444 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
,03-23 13:05:49.909  1773  3444 I SystemUpdateService: file has been verified
03-23 13:05:49.909  1773  3444 I SystemUpdateService: OTA package size = 25802302
03-23 13:05:49.910  1807  1824 I GmsBackupTransport: Next backup will happen in 43199891 millis.
,03-23 13:05:49.915   822  1042 I BackupManagerService: Backup pass finished.
,03-23 13:05:49.916  1773  3444 I SystemUpdateService: showing system update notification
,03-23 13:05:49.924   822   822 I ValidateNoPeople: skipping global notification
,03-23 13:05:49.940  1773  3421 W DriveInitializer: Background init thread ended
,03-23 13:05:49.979  1261  1842 I art     : Explicit concurrent mark sweep GC freed 17805(928KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.142ms total 26.169ms
,03-23 13:05:49.994  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-23 13:05:49.994  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:49.994  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:49.994  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:49.997  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:50.010  3106  3419 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-23 13:05:50.010  3106  3419 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jdm.a(PG:82)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jcs.o(PG:406)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jcn.a(PG:1379)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jcs.i(PG:143)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at blb.a(PG:3937)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at czp.a(PG:18188)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at czp.a(PG:9081)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at czq.run(PG:1686)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:05:50.010  3106  3419 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jdj.a(PG:4091)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jdj.a(PG:1125)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jdm.a(PG:77)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	... 12 more
03-23 13:05:50.010  3106  3419 E HttpOperation: Caused by: faj: BadAuthentication
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at fal.a(PG:38)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	at jdj.a(PG:4089)
03-23 13:05:50.010  3106  3419 E HttpOperation: 	... 14 more
,03-23 13:05:50.070   822   855 I ActivityManager: Start proc 3459:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-23 13:05:50.082  1773  1773 D SystemUpdateService: onDestroy
,03-23 13:05:50.091  1261  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-23 13:05:50.092  1261  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:50.092  1261  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:50.092  1261  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:50.094  1261  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:50.096  1773  3476 I iu.SyncManager: SYNC; picasa accounts
,03-23 13:05:50.104  1773  1773 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-23 13:05:50.104  3106  3419 E HttpOperation: [getmobileexperiments] Unexpected exception
03-23 13:05:50.104  3106  3419 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jdm.a(PG:82)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jcs.o(PG:406)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jcn.a(PG:1379)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jcs.i(PG:143)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at hec.a(PG:42)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at hee.a(PG:102)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at czr.a(PG:65)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at kka.a(PG:108)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at czp.a(PG:19176)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at czp.a(PG:9081)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at czq.run(PG:1686)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:05:50.104  3106  3419 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jdj.a(PG:4091)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jdj.a(PG:1125)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jdm.a(PG:77)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	... 15 more
03-23 13:05:50.104  3106  3419 E HttpOperation: Caused by: faj: BadAuthentication
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at fal.a(PG:38)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	at jdj.a(PG:4089)
03-23 13:05:50.104  3106  3419 E HttpOperation: 	... 17 more
03-23 13:05:50.104  3106  3419 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-23 13:05:50.104  3106  3419 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jdm.a(PG:82)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jcs.o(PG:406)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jcn.a(PG:1379)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jcs.i(PG:143)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at hec.a(PG:42)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at hee.a(PG:102)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at czr.a(PG:65)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at kka.a(PG:108)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at czp.a(PG:19176)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at czp.a(PG:9081)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at czq.run(PG:1686)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jdj.a(PG:4091)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jdm.a(PG:77)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	... 15 more
03-23 13:05:50.104  3106  3419 E ExperimentLoader: Caused by: faj: BadAuthentication
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at fal.a(PG:38)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	at jdj.a(PG:4089)
03-23 13:05:50.104  3106  3419 E ExperimentLoader: 	... 17 more
03-23 13:05:50.107  1773  1773 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
03-23 13:05:50.131  1773  1773 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-23 13:05:50.132  1773  3476 I iu.UploadsManager: num queued entries: 0
03-23 13:05:50.132  1773  1773 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
03-23 13:05:50.132  1773  3476 I iu.UploadsManager: num updated entries: 0
,03-23 13:05:50.141  1773  3476 I iu.SyncManager: NEXT; no task
,03-23 13:05:50.170   822  1391 I ActivityManager: Start proc 3483:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-23 13:05:50.258  3483  3483 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-23 13:05:50.258  3483  3483 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-23 13:05:50.258  3483  3483 I GAv4    :   adb logcat -s GAv4
,03-23 13:05:50.272  3483  3483 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-23 13:05:50.275   822   837 I ActivityManager: Killing 2904:com.android.settings/1000 (adj 15): empty #17
,03-23 13:05:50.276   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 38147, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:05:50.286  3483  3483 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-23 13:05:50.297  3483  3507 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-23 13:05:50.357  3152  3479 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-23 13:05:50.383   822  1412 I ActivityManager: Killing 2440:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-23 13:05:50.390  1261  3492 D GCM     : Connected
,03-23 13:05:50.497  1261  3492 D GCM     : Message class com.google.f.a.a.p
,03-23 13:05:50.539   822   855 I ActivityManager: Start proc 3511:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-23 13:05:50.590  3459  3459 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-23 13:05:50.597  3459  3459 I BooksApp: Created application version: 3.6.8 (30608)
,03-23 13:05:50.708  3459  3545 I BooksSync: Starting books sync for 61035162, extras: ade
,03-23 13:05:50.726  3483  3483 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-23 13:05:50.739  3483  3483 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8637-8640)
,03-23 13:05:50.739  3483  3483 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-23 13:05:50.742  3483  3483 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {194d2dd8}
,03-23 13:05:50.743  3483  3483 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-23 13:05:50.743  3483  3483 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-23 13:05:50.751  3483  3483 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-23 13:05:50.751  3483  3483 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-23 13:05:50.752  3483  3483 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-23 13:05:50.763  3483  3483 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-23 13:05:50.767  3483  3483 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-23 13:05:50.767  3483  3483 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-23 13:05:50.767  3483  3483 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-23 13:05:50.787  3511  3552 V KeepSync: Connecting to GoogleApiClient
,03-23 13:05:50.806  3483  3567 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-23 13:05:50.850   822  1357 I art     : Explicit concurrent mark sweep GC freed 53479(2MB) AllocSpace objects, 7(152KB) LOS objects, 32% free, 33MB/49MB, paused 1.551ms total 50.443ms
,03-23 13:05:50.876  3483  3483 I NSApplication: Starting up...
,03-23 13:05:50.899  3459  3576 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-23 13:05:50.910   822  1412 I ActivityManager: Start proc 3577:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-23 13:05:50.925  1773  3572 W BaseAppContext: Using Auth Proxy for data requests.
,03-23 13:05:50.932  1773  3572 W BaseAppContext: Using Auth Proxy for data requests.
,03-23 13:05:50.962  1261  1261 I art     : Explicit concurrent mark sweep GC freed 11018(630KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 685us total 19.643ms
,03-23 13:05:50.973  1261  1842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-23 13:05:50.973  1261  1842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:50.973  1261  1842 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:05:50.973  1261  1842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:50.979  1261  1842 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:50.981  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-23 13:05:50.981  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:50.981  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:50.981  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:50.985  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: Handling authorization failure
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-23 13:05:50.994  1773  3572 E ClientConnectionOperation: 	... 7 more
,03-23 13:05:51.003  3511  3552 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-23 13:05:51.004  3511  3552 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:05:51.008  3511  3552 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-23 13:05:51.009  3511  3552 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:05:51.031  1261  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-23 13:05:51.031  1261  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:51.031  1261  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:05:51.032  1261  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:51.034  1261  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:51.044  3459  3576 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:05:51.045  3459  3545 E BooksSync: Soft error
03-23 13:05:51.045  3459  3545 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:05:51.045  3459  3545 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-23 13:05:51.045  3459  3545 E BooksSync: Sync error
03-23 13:05:51.045  3459  3545 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:05:51.045  3459  3545 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-23 13:05:51.045  3459  3545 I BooksSync: Finished books sync
,03-23 13:05:51.050   822  1357 I ActivityManager: Killing 3014:com.google.android.partnersetup/u0a16 (adj 15): empty #17
03-23 13:05:51.050   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38153, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:05:51.196  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-23 13:05:51.197  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:51.197  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:51.197  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:51.202  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:51.241  3511  3552 E KeepSync: IOException
03-23 13:05:51.241  3511  3552 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-23 13:05:51.241  3511  3552 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-23 13:05:51.241  3511  3552 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-23 13:05:51.241  3511  3552 E KeepSync: 	... 10 more
03-23 13:05:51.241  3511  3552 W KeepSync: Sync result 2
,03-23 13:05:51.250   822  1313 I ActivityManager: Killing 3034:com.android.musicfx/u0a18 (adj 15): empty #17
,03-23 13:05:51.255   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38153, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:05:51.436   822  1412 I ActivityManager: Start proc 3604:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-23 13:05:51.437   822  1412 I ActivityManager: Killing 3062:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-23 13:05:51.665   822   837 I ActivityManager: Killing 2994:android.process.acore/u0a5 (adj 15): empty #17
,03-23 13:05:52.432   822  1412 I ActivityManager: Killing 2802:com.google.android.gm/u0a78 (adj 15): empty #17
,03-23 13:05:52.783   822  1346 I ActivityManager: Start proc 3622:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-23 13:05:52.810  1773  1773 V Herrevad: NQAS connected
,03-23 13:05:52.820   822  1024 D WifiService: New client listening to asynchronous messages
,03-23 13:05:52.838  3622  3622 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458734752838
03-23 13:05:52.838  3622  3622 D         : TimeServiceNative: User Time to be set is 1458734752838
03-23 13:05:52.838  3622  3622 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-23 13:05:52.838  3622  3622 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-23 13:05:52.838  3622  3622 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458734752838
03-23 13:05:52.839   373   880 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-23 13:05:52.839  3622  3622 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-23 13:05:52.840   373  3641 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458734752838
03-23 13:05:52.840   373  3641 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458734752838, operation = 0
03-23 13:05:52.840   373  3641 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/9/70 8:17:36
03-23 13:05:52.841   373  3641 D QC-time-services: Daemon:Value read from RTC seconds = 19037856000
03-23 13:05:52.841   373  3641 D QC-time-services: Daemon:new time 1458734752838 
03-23 13:05:52.841   373  3641 D QC-time-services: Daemon: delta 1439696896838 genoff 1439696896838 
03-23 13:05:52.841   373  3641 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896838 to memory
03-23 13:05:52.841   373  3641 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-23 13:05:52.841   373  3641 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-23 13:05:52.851   373  3641 D QC-time-services: Updating the TOD offset
03-23 13:05:52.851   373  3641 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896838 to memory
03-23 13:05:52.851   373  3641 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-23 13:05:52.851   373  3641 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-23 13:05:52.853   373  3641 E QC-time-services: Daemon:Update to modem bit set
03-23 13:05:52.853   373  3641 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-23 13:05:52.853   373  3641 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142769952838
,03-23 13:05:52.854  3622  3622 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-23 13:05:52.903  1773  1945 I art     : Explicit concurrent mark sweep GC freed 14417(1121KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.684ms total 50.261ms
,03-23 13:05:52.921   373   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-23 13:05:52.927   373   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-23 13:05:52.981   822  1313 I ActivityManager: Start proc 3643:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-23 13:05:53.051  3643  3643 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-23 13:05:53.051  3643  3643 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-23 13:05:53.051  3643  3643 I GAv4    :   adb logcat -s GAv4
,03-23 13:05:53.065  3643  3643 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-23 13:05:53.075  3643  3643 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-23 13:05:53.080  3643  3663 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-23 13:05:53.108   822  1161 I ActivityManager: Killing 1848:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-23 13:05:53.292  3152  3152 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-23 13:05:53.292  3152  3152 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-23 13:05:53.455  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-23 13:05:53.455  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:53.455  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:53.455  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:53.458  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:53.467  3152  3671 E Babel   : UserRecoverableAuthException.
,03-23 13:05:53.467  3152  3671 E Babel   : eei: BadAuthentication
03-23 13:05:53.467  3152  3671 E Babel   : 	at eeg.a(Unknown Source)
03-23 13:05:53.467  3152  3671 E Babel   : 	at eeg.a(Unknown Source)
03-23 13:05:53.467  3152  3671 E Babel   : 	at eeg.a(Unknown Source)
03-23 13:05:53.467  3152  3671 E Babel   : 	at g.a(Unknown Source)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cae.a(SourceFile:3089)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cae.a(SourceFile:1131)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cws.a(SourceFile:4333)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cws.a(SourceFile:1419)
03-23 13:05:53.467  3152  3671 E Babel   : 	at crl.a(SourceFile:492)
03-23 13:05:53.467  3152  3671 E Babel   : 	at crl.a(SourceFile:1468)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cqu.a(SourceFile:4416)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cas.b(SourceFile:106)
03-23 13:05:53.467  3152  3671 E Babel   : 	at cap.d(SourceFile:335)
03-23 13:05:53.467  3152  3671 E Babel   : 	at caq.run(SourceFile:81)
03-23 13:05:53.467  3152  3671 E Babel   : Error getting auth token
,03-23 13:05:53.468  3152  3671 E Babel   : dvm
03-23 13:05:53.468  3152  3671 E Babel   : 	at g.a(Unknown Source)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cae.a(SourceFile:3089)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cae.a(SourceFile:1131)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cws.a(SourceFile:4333)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cws.a(SourceFile:1419)
03-23 13:05:53.468  3152  3671 E Babel   : 	at crl.a(SourceFile:492)
03-23 13:05:53.468  3152  3671 E Babel   : 	at crl.a(SourceFile:1468)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cqu.a(SourceFile:4416)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cas.b(SourceFile:106)
03-23 13:05:53.468  3152  3671 E Babel   : 	at cap.d(SourceFile:335)
03-23 13:05:53.468  3152  3671 E Babel   : 	at caq.run(SourceFile:81)
,03-23 13:05:53.470  3152  3671 E Babel   : Account registration failed 1-Redacted-21
03-23 13:05:53.470  3152  3671 E Babel   : cyp: null -- null
03-23 13:05:53.470  3152  3671 E Babel   : 	at cae.a(SourceFile:3121)
03-23 13:05:53.470  3152  3671 E Babel   : 	at cae.a(SourceFile:1131)
03-23 13:05:53.470  3152  3671 E Babel   : 	at cws.a(SourceFile:4333)
03-23 13:05:53.470  3152  3671 E Babel   : 	at cws.a(SourceFile:1419)
03-23 13:05:53.470  3152  3671 E Babel   : 	at crl.a(SourceFile:492)
03-23 13:05:53.470  3152  3671 E Babel   : 	at crl.a(SourceFile:1468)
03-23 13:05:53.470  3152  3671 E Babel   : 	at cqu.a(SourceFile:4416)
03-23 13:05:53.470  3152  3671 E Babel   : 	at cas.b(SourceFile:106)
03-23 13:05:53.470  3152  3671 E Babel   : 	at cap.d(SourceFile:335)
03-23 13:05:53.470  3152  3671 E Babel   : 	at caq.run(SourceFile:81)
,03-23 13:05:53.484  3152  3671 I art     : Note: end time exceeds epoch: 
,03-23 13:05:53.492  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-23 13:05:53.492  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:53.492  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:53.492  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:53.496  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:53.507  1261  1284 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-23 13:05:53.526  3152  3677 E Babel   : Unexpected exception while authenticating.
03-23 13:05:53.526  3152  3677 E Babel   : eej: User intervention required. Notification has been pushed.
03-23 13:05:53.526  3152  3677 E Babel   : 	at eeg.b(Unknown Source)
03-23 13:05:53.526  3152  3677 E Babel   : 	at eeg.b(Unknown Source)
03-23 13:05:53.526  3152  3677 E Babel   : 	at g.a(Unknown Source)
03-23 13:05:53.526  3152  3677 E Babel   : 	at cae.b(SourceFile:1146)
03-23 13:05:53.526  3152  3677 E Babel   : 	at dcg.run(SourceFile:5617)
03-23 13:05:53.526  3152  3677 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:05:53.526  3152  3677 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:05:53.526  3152  3677 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-23 13:05:53.572   822   822 I art     : Explicit concurrent mark sweep GC freed 21439(962KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.395ms total 49.696ms
,03-23 13:05:54.490  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:54.565  1261  3684 I VacuumService: Vacuum at: now=1458734754565 tag=VacuumService
,03-23 13:05:54.660  3384  3683 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,03-23 13:05:54.690  1261  1842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-23 13:05:54.690  1261  1842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:54.690  1261  1842 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:54.690  1261  1842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:54.697  1261  1842 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:54.717  3384  3683 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-23 13:05:54.720  3384  3683 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-23 13:05:54.789  1261  3686 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-23 13:05:54.806  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:55.367  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:55.593  1261  3686 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-23 13:05:55.594  1261  3686 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:55.594  1261  3686 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:05:55.594  1261  3686 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:55.602  1261  3686 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:55.617  3459  3531 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-23 13:05:55.650  1261  3686 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-23 13:05:55.650  1261  3686 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-23 13:05:55.650  1261  3686 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-23 13:05:55.964  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:55.970  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:05:55.970  3277  3337 I jxcore-log: 
,03-23 13:05:55.972  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:05:55.972  3277  3337 I jxcore-log: 
,03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:05:55.982  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:05:55.993  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-23 13:05:55.995  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:05:55.995  3277  3337 I jxcore-log: 
03-23 13:05:55.997  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:05:55.997  3277  3337 I jxcore-log: 
,03-23 13:05:56.104  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:56.316  1261  3686 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-23 13:05:56.316  1261  3686 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:56.316  1261  3686 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:05:56.316  1261  3686 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:56.320  1261  3686 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:56.347  1261  3686 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-23 13:05:56.347  1261  3686 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-23 13:05:56.347  1261  3686 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-23 13:05:56.459  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:56.617  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:56.643  3277  3337 I jxcore-log: Unit Test app is loaded,
03-23 13:05:56.643  3277  3337 I jxcore-log: 
,03-23 13:05:56.648  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-23 13:05:56.648  3277  3337 I jxcore-log: 
,03-23 13:05:56.657  3277  3277 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-23 13:05:56.659  3277  3337 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-23 13:05:56.661  3277  3337 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-23 13:05:56.661  3277  3337 I jxcore-log: 
03-23 13:05:56.662  3277  3337 I jxcore-log: My device name is: motorola-Nexus 6
03-23 13:05:56.662  3277  3337 I jxcore-log: 
,03-23 13:05:56.731  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:56.899  1261  3686 W Uploader:  no longer exists, so no auth token.
,03-23 13:05:57.101  1261  1261 I art     : Explicit concurrent mark sweep GC freed 46630(2MB) AllocSpace objects, 1(39KB) LOS objects, 36% free, 27MB/43MB, paused 2.108ms total 61.197ms
,03-23 13:05:57.124  1261  3686 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-23 13:05:57.124  1261  3686 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:57.124  1261  3686 I GLSUser : [GLSUser] Extracting token using key: Auth,
,03-23 13:05:57.124  1261  3686 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:57.130  1261  3686 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:57.158  1261  3686 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-23 13:05:57.158  1261  3686 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-23 13:05:57.158  1261  3686 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-23 13:05:57.338  1261  3686 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-23 13:05:57.338  1261  3686 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:05:57.338  1261  3686 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-23 13:05:57.338  1261  3686 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:57.349  1261  3686 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:57.417  1261  3686 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-23 13:05:57.417  1261  3686 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-23 13:05:57.417  1261  3686 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-23 13:05:57.556  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:57.665  1261  3686 W Uploader: No account for auth token provided
,03-23 13:05:57.816  1261  3686 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-23 13:05:57.817  1261  3686 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-23 13:05:57.817  1261  3686 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:05:57.817  1261  3686 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:05:57.822  1261  3686 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:05:57.854  1261  3686 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
,03-23 13:05:57.854  1261  3686 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-23 13:05:57.854  1261  3686 E Uploader: 	,at com.google.android.gms.auth.p.d(SourceFile:599)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-23 13:05:57.854  1261  3686 E Uploader: 	,at com.google.android.gms.auth.p.b(SourceFile:477)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-23 13:05:57.854  1261  3686 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,03-23 13:05:58.540   822   837 I ActivityManager: Killing 2743:com.android.vending/u0a19 (adj 15): empty #17
,03-23 13:06:00.597  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-23 13:06:00.597  3277  3337 I jxcore-log: 
,03-23 13:06:00.724   822  1413 I ActivityManager: Start proc 3691:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-23 13:06:00.885  3691  3691 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-23 13:06:00.957  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-23 13:06:00.957  3277  3337 I jxcore-log: 
,03-23 13:06:00.970  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-23 13:06:00.970  3277  3337 I jxcore-log: 
,03-23 13:06:00.974  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
,03-23 13:06:00.974  3277  3337 I jxcore-log: 
,03-23 13:06:00.983  3691  3691 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-23 13:06:01.013  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-23 13:06:01.013  3277  3337 I jxcore-log: 
,03-23 13:06:01.029  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-23 13:06:01.029  3277  3337 I jxcore-log: 
,03-23 13:06:01.033  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-23 13:06:01.033  3277  3337 I jxcore-log: 
,03-23 13:06:01.086   822   837 I ActivityManager: Start proc 3727:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-23 13:06:01.124  3691  3691 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-23 13:06:01.129  3691  3691 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-23 13:06:01.131  3727  3727 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-23 13:06:01.131  3727  3727 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-23 13:06:01.171   822  1161 I ActivityManager: Killing 2923:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-23 13:06:01.175  3727  3727 I MultiDex: VM with version 2.1.0 has multidex support
03-23 13:06:01.175  3727  3727 I MultiDex: install
03-23 13:06:01.175  3727  3727 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-23 13:06:01.178  3691  3707 D Finsky  : [375] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-23 13:06:01.284  3691  3691 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-23 13:06:01.285  3691  3691 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-23 13:06:01.294  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:01.296  3691  3691 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-23 13:06:01.313  3691  3691 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-23 13:06:01.320  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-23 13:06:01.320  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:01.321  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:01.321  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:01.321  3727  3727 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-23 13:06:01.324  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:01.336  3691  3707 D Finsky  : [375] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-23 13:06:01.361  3727  3727 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-23 13:06:01.366  1261  2110 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-23 13:06:01.371  1261  1261 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-23 13:06:01.375  1773  1773 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-23 13:06:01.417   822  1391 I ActivityManager: Start proc 3755:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-23 13:06:01.427   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.439ms total 10.529ms
,03-23 13:06:01.439   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 10.196ms
,03-23 13:06:01.449   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.967ms
,03-23 13:06:01.460  1773  3764 D LocationInitializer: Restart initialization of location
,03-23 13:06:01.469  3755  3755 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-23 13:06:01.469  3755  3755 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-23 13:06:01.492  3755  3755 I MultiDex: VM with version 2.1.0 has multidex support
03-23 13:06:01.492  3755  3755 I MultiDex: install
03-23 13:06:01.492  3755  3755 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-23 13:06:01.513  3755  3755 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-23 13:06:01.543  3755  3755 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-23 13:06:01.547  1261  2113 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-23 13:06:01.549  1261  1261 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-23 13:06:01.553  1773  1773 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-23 13:06:01.559  3755  3755 D WearableService: callingUid 10011, callindPid: 3755
,03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: Install did not work
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-23 13:06:01.563  3755  3777 W NativeLibraryUtils: 	... 4 more
,03-23 13:06:01.568  1773  3778 D LocationInitializer: Restart initialization of location
,03-23 13:06:01.575  1807  2072 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-23 13:06:01.580  1807  2072 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-23 13:06:01.693  3691  3691 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-23 13:06:02.005  3691  3691 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-23 13:06:02.026  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.058  1261  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-23 13:06:02.058  1261  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-23 13:06:02.058  1261  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:02.058  1261  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:02.062  1261  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.079  3691  3691 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-23 13:06:02.100  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.175   822   822 I art     : Explicit concurrent mark sweep GC freed 23611(1109KB) AllocSpace objects, 4(346KB) LOS objects, 31% free, 34MB/50MB, paused 1.349ms total 62.887ms
,03-23 13:06:02.215  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-23 13:06:02.215  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:02.215  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:02.215  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:02.219  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.259  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.350  1261  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-23 13:06:02.350  1261  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:02.350  1261  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:02.350  1261  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:02.354  1261  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.398  3691  3691 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-23 13:06:02.674  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.738  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-23 13:06:02.739  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:02.739  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-23 13:06:02.739  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:02.754  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:02.788  3691  3691 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,03-23 13:06:02.795  3691  3691 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,03-23 13:06:02.816  3691  3691 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-23 13:06:02.824  3691  3691 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2),
,03-23 13:06:02.849  1807  1837 D DeviceConnectionService: client connected with version: 7571000
,03-23 13:06:03.259  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-23 13:06:03.259  3277  3337 I jxcore-log: 
,03-23 13:06:03.276  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-23 13:06:03.276  3277  3337 I jxcore-log: 
,03-23 13:06:03.284  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-23 13:06:03.284  3277  3337 I jxcore-log: 
,03-23 13:06:03.407  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-23 13:06:03.407  3277  3337 I jxcore-log: 
,03-23 13:06:03.461  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-23 13:06:03.461  3277  3337 I jxcore-log: 
,03-23 13:06:03.595  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-23 13:06:03.595  3277  3337 I jxcore-log: 
,03-23 13:06:03.600  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-23 13:06:03.600  3277  3337 I jxcore-log: 
,03-23 13:06:03.606  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-23 13:06:03.606  3277  3337 I jxcore-log: 
,03-23 13:06:03.626  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-23 13:06:03.626  3277  3337 I jxcore-log: 
,03-23 13:06:03.644  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-23 13:06:03.644  3277  3337 I jxcore-log: 
,03-23 13:06:03.743  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-23 13:06:03.743  3277  3337 I jxcore-log: 
,03-23 13:06:03.748  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-23 13:06:03.748  3277  3337 I jxcore-log: 
,03-23 13:06:03.774  3277  3337 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-23 13:06:03.774  3277  3337 I jxcore-log: 
,03-23 13:06:04.819  3277  3337 I jxcore-log: TAP version 13
03-23 13:06:04.819  3277  3337 I jxcore-log: 
,03-23 13:06:04.822  3277  3337 I jxcore-log: # setup
03-23 13:06:04.822  3277  3337 I jxcore-log: 
,03-23 13:06:05.097  3277  3337 I jxcore-log: # 1. calling createNativeListener directly rejects
03-23 13:06:05.097  3277  3337 I jxcore-log: 
,03-23 13:06:05.266  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:05.266  3277  3337 I jxcore-log: 
,03-23 13:06:05.271  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 41577
03-23 13:06:05.271  3277  3337 I jxcore-log: 
,03-23 13:06:05.278  3277  3337 I jxcore-log: ok 1 Should throw
03-23 13:06:05.278  3277  3337 I jxcore-log: 
,03-23 13:06:05.280  3277  3337 I jxcore-log: # teardown
03-23 13:06:05.280  3277  3337 I jxcore-log: 
,03-23 13:06:05.430  3277  3337 I jxcore-log: # setup
03-23 13:06:05.430  3277  3337 I jxcore-log: 
,03-23 13:06:05.558  3277  3337 I jxcore-log: # 2. emits incomingConnectionState
03-23 13:06:05.558  3277  3337 I jxcore-log: 
,03-23 13:06:05.688  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:05.688  3277  3337 I jxcore-log: 
,03-23 13:06:05.692  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 39421
03-23 13:06:05.692  3277  3337 I jxcore-log: 
,03-23 13:06:05.711  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-23 13:06:05.711  3277  3337 I jxcore-log: 
,03-23 13:06:05.720  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-23 13:06:05.720  3277  3337 I jxcore-log: 
,03-23 13:06:05.729  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
,03-23 13:06:05.729  3277  3337 I jxcore-log: 
,03-23 13:06:05.734  3277  3337 I jxcore-log: ok 2 initial connection state should be CONNECTED
,03-23 13:06:05.734  3277  3337 I jxcore-log: 
,03-23 13:06:05.753  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:05.753  3277  3337 I jxcore-log: 
,03-23 13:06:05.754  3277  3337 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-23 13:06:05.754  3277  3337 I jxcore-log: 
,03-23 13:06:05.762  3277  3337 I jxcore-log: # teardown
03-23 13:06:05.762  3277  3337 I jxcore-log: 
,03-23 13:06:05.887  3277  3337 I jxcore-log: # setup
03-23 13:06:05.887  3277  3337 I jxcore-log: 
,03-23 13:06:06.020  3277  3337 I jxcore-log: # 3. emits routerPortConnectionFailed
03-23 13:06:06.020  3277  3337 I jxcore-log: 
,03-23 13:06:06.187  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:06.187  3277  3337 I jxcore-log: 
,03-23 13:06:06.191  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 51467
03-23 13:06:06.191  3277  3337 I jxcore-log: 
,03-23 13:06:06.196  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:06.196  3277  3337 I jxcore-log: 
,03-23 13:06:06.197  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:06.197  3277  3337 I jxcore-log: 
,03-23 13:06:06.199  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:06.199  3277  3337 I jxcore-log: 
,03-23 13:06:06.225  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-23 13:06:06.225  3277  3337 I jxcore-log: 
,03-23 13:06:06.228  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-23 13:06:06.228  3277  3337 I jxcore-log: 
,03-23 13:06:06.230  3277  3337 I jxcore-log: DEBUG createNativeListener: 
,03-23 13:06:06.230  3277  3337 I jxcore-log: 
,03-23 13:06:06.231  3277  3337 I jxcore-log: ok 4 tried to connect to right port
03-23 13:06:06.231  3277  3337 I jxcore-log: 
,03-23 13:06:06.232  3277  3337 I jxcore-log: ok 5 failed due to refused connection
03-23 13:06:06.232  3277  3337 I jxcore-log: 
03-23 13:06:06.233  3277  3337 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-23 13:06:06.233  3277  3337 I jxcore-log: 
03-23 13:06:06.238  3277  3337 I jxcore-log: # teardown
03-23 13:06:06.238  3277  3337 I jxcore-log: 
,03-23 13:06:06.239  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:06.239  3277  3337 I jxcore-log: 
,03-23 13:06:06.397  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:06.397  3277  3337 I jxcore-log: 
,03-23 13:06:06.402  3277  3337 I jxcore-log: # setup
03-23 13:06:06.402  3277  3337 I jxcore-log: 
,03-23 13:06:06.403  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:06.403  3277  3337 I jxcore-log: 
,03-23 13:06:06.496  3277  3337 I jxcore-log: # 4. native server connections all up
03-23 13:06:06.496  3277  3337 I jxcore-log: 
,03-23 13:06:06.600   822   838 I ActivityManager: Killing 3423:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-23 13:06:06.692  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:06.692  3277  3337 I jxcore-log: 
,03-23 13:06:06.702  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 51528
03-23 13:06:06.702  3277  3337 I jxcore-log: 
,03-23 13:06:06.718  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-23 13:06:06.718  3277  3337 I jxcore-log: 
,03-23 13:06:06.721  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-23 13:06:06.721  3277  3337 I jxcore-log: 
,03-23 13:06:06.725  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
,03-23 13:06:06.725  3277  3337 I jxcore-log: 
,03-23 13:06:06.755  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-23 13:06:06.755  3277  3337 I jxcore-log: 
,03-23 13:06:06.758  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-23 13:06:06.758  3277  3337 I jxcore-log: 
,03-23 13:06:06.762  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-23 13:06:06.762  3277  3337 I jxcore-log: 
03-23 13:06:06.764  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:06.764  3277  3337 I jxcore-log: 
,03-23 13:06:06.787  3277  3337 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-23 13:06:06.787  3277  3337 I jxcore-log: 
,03-23 13:06:06.787  3277  3337 I jxcore-log: ok 8 Send/recvd #1 should be same
03-23 13:06:06.787  3277  3337 I jxcore-log: 
,03-23 13:06:06.790  3277  3337 I jxcore-log: ok 9 Send/recvd #2 should be equal length,
03-23 13:06:06.790  3277  3337 I jxcore-log: 
03-23 13:06:06.790  3277  3337 I jxcore-log: ok 10 Send/recvd #2 should be same
03-23 13:06:06.790  3277  3337 I jxcore-log: 
,03-23 13:06:06.793  3277  3337 I jxcore-log: ok 11 Should be exactly 2 client sockets,
03-23 13:06:06.793  3277  3337 I jxcore-log: 
,03-23 13:06:06.801  3277  3337 I jxcore-log: # teardown,
03-23 13:06:06.801  3277  3337 I jxcore-log: 
,03-23 13:06:06.825   822  1391 I ActivityManager: Killing 3483:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-23 13:06:06.948  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:06.948  3277  3337 I jxcore-log: 
,03-23 13:06:06.952  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:06.952  3277  3337 I jxcore-log: 
,03-23 13:06:06.955  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:06.955  3277  3337 I jxcore-log: 
,03-23 13:06:06.960  3277  3337 I jxcore-log: # setup
03-23 13:06:06.960  3277  3337 I jxcore-log: 
,03-23 13:06:06.962  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:06.962  3277  3337 I jxcore-log: 
,03-23 13:06:07.140  3277  3337 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-23 13:06:07.140  3277  3337 I jxcore-log: 
,03-23 13:06:07.254  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:07.254  3277  3337 I jxcore-log: 
,03-23 13:06:07.262  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 34318
03-23 13:06:07.262  3277  3337 I jxcore-log: 
,03-23 13:06:07.267  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:07.267  3277  3337 I jxcore-log: 
,03-23 13:06:07.268  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:07.268  3277  3337 I jxcore-log: 
,03-23 13:06:07.270  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:07.270  3277  3337 I jxcore-log: 
,03-23 13:06:07.283  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:07.283  3277  3337 I jxcore-log: ,
,03-23 13:06:07.286  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:07.286  3277  3337 I jxcore-log: 
,03-23 13:06:07.299  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:07.299  3277  3337 I jxcore-log: 
,03-23 13:06:07.313  3277  3337 I jxcore-log: ok 12 socket shouldn't close until after stream
03-23 13:06:07.313  3277  3337 I jxcore-log: 
,03-23 13:06:07.313  3277  3337 I jxcore-log: ok 13 incoming remains open
03-23 13:06:07.313  3277  3337 I jxcore-log: 
,03-23 13:06:07.320  3277  3337 I jxcore-log: # teardown
03-23 13:06:07.320  3277  3337 I jxcore-log: 
,03-23 13:06:07.472  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:07.472  3277  3337 I jxcore-log: 
,03-23 13:06:07.483  3277  3337 I jxcore-log: # setup,
03-23 13:06:07.483  3277  3337 I jxcore-log: 
03-23 13:06:07.484  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:07.484  3277  3337 I jxcore-log: 
,03-23 13:06:07.623  3277  3337 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-23 13:06:07.623  3277  3337 I jxcore-log: 
,03-23 13:06:07.747  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:07.747  3277  3337 I jxcore-log: 
,03-23 13:06:07.757  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 54358
03-23 13:06:07.757  3277  3337 I jxcore-log: 
,03-23 13:06:07.766  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:07.766  3277  3337 I jxcore-log: 
,03-23 13:06:07.767  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:07.767  3277  3337 I jxcore-log: 
,03-23 13:06:07.769  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:07.769  3277  3337 I jxcore-log: 
,03-23 13:06:07.780  3277  3337 I jxcore-log: ok 14 we should not have gotten an error
03-23 13:06:07.780  3277  3337 I jxcore-log: 
,03-23 13:06:07.787  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:07.787  3277  3337 I jxcore-log: 
,03-23 13:06:07.792  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:07.792  3277  3337 I jxcore-log: 
,03-23 13:06:07.804  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:07.804  3277  3337 I jxcore-log: 
,03-23 13:06:07.806  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:07.806  3277  3337 I jxcore-log: 
,03-23 13:06:07.815  3277  3337 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-23 13:06:07.815  3277  3337 I jxcore-log: 
,03-23 13:06:07.815  3277  3337 I jxcore-log: ok 16 incoming is cleaned up
03-23 13:06:07.815  3277  3337 I jxcore-log: 
,03-23 13:06:07.822  3277  3337 I jxcore-log: # teardown
03-23 13:06:07.822  3277  3337 I jxcore-log: 
,03-23 13:06:07.963  3277  3337 I jxcore-log: # setup
03-23 13:06:07.963  3277  3337 I jxcore-log: 
,03-23 13:06:08.121  3277  3337 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-23 13:06:08.121  3277  3337 I jxcore-log: 
,03-23 13:06:08.340  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:08.340  3277  3337 I jxcore-log: 
,03-23 13:06:08.344  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 44814
03-23 13:06:08.344  3277  3337 I jxcore-log: 
,03-23 13:06:08.353  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:08.353  3277  3337 I jxcore-log: 
,03-23 13:06:08.357  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:08.357  3277  3337 I jxcore-log: 
,03-23 13:06:08.364  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:08.364  3277  3337 I jxcore-log: 
,03-23 13:06:08.386  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:08.386  3277  3337 I jxcore-log: 
,03-23 13:06:08.388  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-23 13:06:08.388  3277  3337 I jxcore-log: 
,03-23 13:06:08.402  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:08.402  3277  3337 I jxcore-log: 
,03-23 13:06:08.412  3277  3337 I jxcore-log: ok 17 stream was closed
03-23 13:06:08.412  3277  3337 I jxcore-log: 
,03-23 13:06:08.413  3277  3337 I jxcore-log: ok 18 incoming should survive
03-23 13:06:08.413  3277  3337 I jxcore-log: 
,03-23 13:06:08.413  3277  3337 I jxcore-log: ok 19 mux should have no streams
03-23 13:06:08.413  3277  3337 I jxcore-log: 
,03-23 13:06:08.421  3277  3337 I jxcore-log: # teardown
03-23 13:06:08.421  3277  3337 I jxcore-log: 
,03-23 13:06:08.548  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:08.548  3277  3337 I jxcore-log: 
,03-23 13:06:08.562  3277  3337 I jxcore-log: # setup
03-23 13:06:08.562  3277  3337 I jxcore-log: 
,03-23 13:06:08.563  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:08.563  3277  3337 I jxcore-log: 
,03-23 13:06:08.761  3277  3337 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-23 13:06:08.761  3277  3337 I jxcore-log: 
,03-23 13:06:08.865  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:08.865  3277  3337 I jxcore-log: 
,03-23 13:06:08.875  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 43264
03-23 13:06:08.875  3277  3337 I jxcore-log: 
,03-23 13:06:08.884  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:08.884  3277  3337 I jxcore-log: 
,03-23 13:06:08.886  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:08.886  3277  3337 I jxcore-log: 
,03-23 13:06:08.887  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:08.887  3277  3337 I jxcore-log: 
,03-23 13:06:08.897  3277  3337 I jxcore-log: ok 20 we should not have gotten an error
03-23 13:06:08.897  3277  3337 I jxcore-log: 
,03-23 13:06:08.903  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:08.903  3277  3337 I jxcore-log: 
,03-23 13:06:08.906  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:08.906  3277  3337 I jxcore-log: 
,03-23 13:06:08.916  3277  3337 I jxcore-log: ok 21 Buffers are identical
03-23 13:06:08.916  3277  3337 I jxcore-log: 
,03-23 13:06:08.918  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:08.918  3277  3337 I jxcore-log: 
,03-23 13:06:08.922  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:08.922  3277  3337 I jxcore-log: 
,03-23 13:06:08.926  3277  3337 I jxcore-log: ok 22 native server is nulled out
03-23 13:06:08.926  3277  3337 I jxcore-log: 
,03-23 13:06:08.926  3277  3337 I jxcore-log: ok 23 native server should be closed
03-23 13:06:08.926  3277  3337 I jxcore-log: 
03-23 13:06:08.927  3277  3337 I jxcore-log: ok 24 incoming has been removed
03-23 13:06:08.927  3277  3337 I jxcore-log: 
,03-23 13:06:08.927  3277  3337 I jxcore-log: ok 25 Incoming should be done
03-23 13:06:08.927  3277  3337 I jxcore-log: 
03-23 13:06:08.927  3277  3337 I jxcore-log: ok 26 The mux object should be closed
03-23 13:06:08.927  3277  3337 I jxcore-log: 
03-23 13:06:08.928  3277  3337 I jxcore-log: ok 27 The mux stream should be closed
03-23 13:06:08.928  3277  3337 I jxcore-log: 
,03-23 13:06:08.929  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:08.929  3277  3337 I jxcore-log: 
,03-23 13:06:08.946  3277  3337 I jxcore-log: # teardown
03-23 13:06:08.946  3277  3337 I jxcore-log: 
,03-23 13:06:09.061  3277  3337 I jxcore-log: # setup
03-23 13:06:09.061  3277  3337 I jxcore-log: 
,03-23 13:06:09.198  3277  3337 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-23 13:06:09.198  3277  3337 I jxcore-log: 
,03-23 13:06:09.341  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
,03-23 13:06:09.341  3277  3337 I jxcore-log: 
,03-23 13:06:09.351  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 44748
03-23 13:06:09.351  3277  3337 I jxcore-log: 
,03-23 13:06:09.373  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.373  3277  3337 I jxcore-log: 
,03-23 13:06:09.374  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.374  3277  3337 I jxcore-log: 
03-23 13:06:09.375  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.375  3277  3337 I jxcore-log: 
,03-23 13:06:09.379  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.379  3277  3337 I jxcore-log: 
,03-23 13:06:09.379  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.379  3277  3337 I jxcore-log: 
,03-23 13:06:09.381  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.381  3277  3337 I jxcore-log: 
03-23 13:06:09.384  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.384  3277  3337 I jxcore-log: 
,03-23 13:06:09.385  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.385  3277  3337 I jxcore-log: 
,03-23 13:06:09.386  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.386  3277  3337 I jxcore-log: 
,03-23 13:06:09.390  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.390  3277  3337 I jxcore-log: 
,03-23 13:06:09.391  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.391  3277  3337 I jxcore-log: 
,03-23 13:06:09.392  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.392  3277  3337 I jxcore-log: 
03-23 13:06:09.396  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.396  3277  3337 I jxcore-log: 
03-23 13:06:09.397  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.397  3277  3337 I jxcore-log: 
03-23 13:06:09.398  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.398  3277  3337 I jxcore-log: 
,03-23 13:06:09.401  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.401  3277  3337 I jxcore-log: 
,03-23 13:06:09.402  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.402  3277  3337 I jxcore-log: 
03-23 13:06:09.403  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.403  3277  3337 I jxcore-log: 
,03-23 13:06:09.406  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.406  3277  3337 I jxcore-log: 
03-23 13:06:09.411  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.411  3277  3337 I jxcore-log: 
,03-23 13:06:09.413  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.413  3277  3337 I jxcore-log: 
,03-23 13:06:09.415  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.415  3277  3337 I jxcore-log: 
03-23 13:06:09.416  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.416  3277  3337 I jxcore-log: 
,03-23 13:06:09.417  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.417  3277  3337 I jxcore-log: 
,03-23 13:06:09.419  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-23 13:06:09.419  3277  3337 I jxcore-log: 
03-23 13:06:09.420  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.420  3277  3337 I jxcore-log: 
,03-23 13:06:09.421  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.421  3277  3337 I jxcore-log: 
03-23 13:06:09.423  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:09.423  3277  3337 I jxcore-log: 
03-23 13:06:09.423  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:09.423  3277  3337 I jxcore-log: 
,03-23 13:06:09.424  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:09.424  3277  3337 I jxcore-log: 
,03-23 13:06:09.511  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-23 13:06:09.511  3277  3337 I jxcore-log: ,
03-23 13:06:09.514  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-23 13:06:09.514  3277  3337 I jxcore-log: 
03-23 13:06:09.517  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-23 13:06:09.517  3277  3337 I jxcore-log: 
03-23 13:06:09.519  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.519  3277  3337 I jxcore-log: 
,03-23 13:06:09.521  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.521  3277  3337 I jxcore-log: 
,03-23 13:06:09.523  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.523  3277  3337 I jxcore-log: 
,03-23 13:06:09.525  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.525  3277  3337 I jxcore-log: 
,03-23 13:06:09.527  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.527  3277  3337 I jxcore-log: 
,03-23 13:06:09.529  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.529  3277  3337 I jxcore-log: 
,03-23 13:06:09.531  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.531  3277  3337 I jxcore-log: 
,03-23 13:06:09.533  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.533  3277  3337 I jxcore-log: 
,03-23 13:06:09.535  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.535  3277  3337 I jxcore-log: 
,03-23 13:06:09.536  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.536  3277  3337 I jxcore-log: 
,03-23 13:06:09.538  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.538  3277  3337 I jxcore-log: 
,03-23 13:06:09.539  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.539  3277  3337 I jxcore-log: 
,03-23 13:06:09.541  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.541  3277  3337 I jxcore-log: 
,03-23 13:06:09.543  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.543  3277  3337 I jxcore-log: 
,03-23 13:06:09.545  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.545  3277  3337 I jxcore-log: 
,03-23 13:06:09.547  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.547  3277  3337 I jxcore-log: 
,03-23 13:06:09.548  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.548  3277  3337 I jxcore-log: 
,03-23 13:06:09.553  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.553  3277  3337 I jxcore-log: 
,03-23 13:06:09.557  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.557  3277  3337 I jxcore-log: 
,03-23 13:06:09.562  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.562  3277  3337 I jxcore-log: 
,03-23 13:06:09.567  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.567  3277  3337 I jxcore-log: 
,03-23 13:06:09.571  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.571  3277  3337 I jxcore-log: 
,03-23 13:06:09.573  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.573  3277  3337 I jxcore-log: 
,03-23 13:06:09.574  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.574  3277  3337 I jxcore-log: 
,03-23 13:06:09.576  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.576  3277  3337 I jxcore-log: 
,03-23 13:06:09.577  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.577  3277  3337 I jxcore-log: 
,03-23 13:06:09.579  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.579  3277  3337 I jxcore-log: 
,03-23 13:06:09.580  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.580  3277  3337 I jxcore-log: 
,03-23 13:06:09.583  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.583  3277  3337 I jxcore-log: 
,03-23 13:06:09.585  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.585  3277  3337 I jxcore-log: 
,03-23 13:06:09.589  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-23 13:06:09.589  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.589  3277  3337 I jxcore-log: 
,03-23 13:06:09.591  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.591  3277  3337 I jxcore-log: 
,03-23 13:06:09.593  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.593  3277  3337 I jxcore-log: 
,03-23 13:06:09.594  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.594  3277  3337 I jxcore-log: 
,03-23 13:06:09.596  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.596  3277  3337 I jxcore-log: 
,03-23 13:06:09.597  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.597  3277  3337 I jxcore-log: 
,03-23 13:06:09.599  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.599  3277  3337 I jxcore-log: 
,03-23 13:06:09.601  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.601  3277  3337 I jxcore-log: 
,03-23 13:06:09.603  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.603  3277  3337 I jxcore-log: 
,03-23 13:06:09.605  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.605  3277  3337 I jxcore-log: 
,03-23 13:06:09.607  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.607  3277  3337 I jxcore-log: 
,03-23 13:06:09.608  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.608  3277  3337 I jxcore-log: 
,03-23 13:06:09.610  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.610  3277  3337 I jxcore-log: 
,03-23 13:06:09.612  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.612  3277  3337 I jxcore-log: 
,03-23 13:06:09.613  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.613  3277  3337 I jxcore-log: 
,03-23 13:06:09.622  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.622  3277  3337 I jxcore-log: 
,03-23 13:06:09.623  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.623  3277  3337 I jxcore-log: 
,03-23 13:06:09.625  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.625  3277  3337 I jxcore-log: 
,03-23 13:06:09.626  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.626  3277  3337 I jxcore-log: 
,03-23 13:06:09.627  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.627  3277  3337 I jxcore-log: 
,03-23 13:06:09.629  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.629  3277  3337 I jxcore-log: 
,03-23 13:06:09.630  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.630  3277  3337 I jxcore-log: 
,03-23 13:06:09.632  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.632  3277  3337 I jxcore-log: 
,03-23 13:06:09.634  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.634  3277  3337 I jxcore-log: 
,03-23 13:06:09.636  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.636  3277  3337 I jxcore-log: 
,03-23 13:06:09.638  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.638  3277  3337 I jxcore-log: 
,03-23 13:06:09.639  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.639  3277  3337 I jxcore-log: 
,03-23 13:06:09.640  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.640  3277  3337 I jxcore-log: 
,03-23 13:06:09.642  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.642  3277  3337 I jxcore-log: 
,03-23 13:06:09.643  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.643  3277  3337 I jxcore-log: 
,03-23 13:06:09.644  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.644  3277  3337 I jxcore-log: 
,03-23 13:06:09.646  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.646  3277  3337 I jxcore-log: 
,03-23 13:06:09.647  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.647  3277  3337 I jxcore-log: 
,03-23 13:06:09.649  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.649  3277  3337 I jxcore-log: 
,03-23 13:06:09.650  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.650  3277  3337 I jxcore-log: 
,03-23 13:06:09.651  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.651  3277  3337 I jxcore-log: 
,03-23 13:06:09.652  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.652  3277  3337 I jxcore-log: 
,03-23 13:06:09.653  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.653  3277  3337 I jxcore-log: 
,03-23 13:06:09.655  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.655  3277  3337 I jxcore-log: 
,03-23 13:06:09.656  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.656  3277  3337 I jxcore-log: 
,03-23 13:06:09.657  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.657  3277  3337 I jxcore-log: 
,03-23 13:06:09.658  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.658  3277  3337 I jxcore-log: 
,03-23 13:06:09.660  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.660  3277  3337 I jxcore-log: 
,03-23 13:06:09.661  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.661  3277  3337 I jxcore-log: 
,03-23 13:06:09.662  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.662  3277  3337 I jxcore-log: 
,03-23 13:06:09.663  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:09.663  3277  3337 I jxcore-log: 
,03-23 13:06:09.665  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:09.665  3277  3337 I jxcore-log: 
,03-23 13:06:09.740  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.740  3277  3337 I jxcore-log: 
,03-23 13:06:09.742  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.742  3277  3337 I jxcore-log: 
03-23 13:06:09.743  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.743  3277  3337 I jxcore-log: 
,03-23 13:06:09.744  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.744  3277  3337 I jxcore-log: 
,03-23 13:06:09.746  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.746  3277  3337 I jxcore-log: 
,03-23 13:06:09.747  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.747  3277  3337 I jxcore-log: 
,03-23 13:06:09.748  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.748  3277  3337 I jxcore-log: 
,03-23 13:06:09.749  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.749  3277  3337 I jxcore-log: 
,03-23 13:06:09.750  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.750  3277  3337 I jxcore-log: 
,03-23 13:06:09.751  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.751  3277  3337 I jxcore-log: 
,03-23 13:06:09.753  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.753  3277  3337 I jxcore-log: 
,03-23 13:06:09.754  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.754  3277  3337 I jxcore-log: 
,03-23 13:06:09.755  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.755  3277  3337 I jxcore-log: 
,03-23 13:06:09.756  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.756  3277  3337 I jxcore-log: 
,03-23 13:06:09.758  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.758  3277  3337 I jxcore-log: 
03-23 13:06:09.759  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.759  3277  3337 I jxcore-log: 
,03-23 13:06:09.760  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.760  3277  3337 I jxcore-log: 
,03-23 13:06:09.761  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.761  3277  3337 I jxcore-log: 
,03-23 13:06:09.762  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.762  3277  3337 I jxcore-log: 
,03-23 13:06:09.763  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.763  3277  3337 I jxcore-log: 
,03-23 13:06:09.764  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.764  3277  3337 I jxcore-log: 
,03-23 13:06:09.764  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.764  3277  3337 I jxcore-log: 
,03-23 13:06:09.765  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.765  3277  3337 I jxcore-log: 
,03-23 13:06:09.766  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.766  3277  3337 I jxcore-log: 
03-23 13:06:09.767  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.767  3277  3337 I jxcore-log: 
03-23 13:06:09.768  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.768  3277  3337 I jxcore-log: 
03-23 13:06:09.769  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.769  3277  3337 I jxcore-log: 
,03-23 13:06:09.770  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.770  3277  3337 I jxcore-log: 
03-23 13:06:09.770  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.770  3277  3337 I jxcore-log: 
03-23 13:06:09.772  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.772  3277  3337 I jxcore-log: 
,03-23 13:06:09.773  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.773  3277  3337 I jxcore-log: 
03-23 13:06:09.773  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.773  3277  3337 I jxcore-log: 
03-23 13:06:09.774  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.774  3277  3337 I jxcore-log: 
,03-23 13:06:09.775  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.775  3277  3337 I jxcore-log: 
03-23 13:06:09.775  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.775  3277  3337 I jxcore-log: 
03-23 13:06:09.776  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.776  3277  3337 I jxcore-log: 
,03-23 13:06:09.777  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.777  3277  3337 I jxcore-log: 
03-23 13:06:09.778  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.778  3277  3337 I jxcore-log: 
03-23 13:06:09.778  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.778  3277  3337 I jxcore-log: 
,03-23 13:06:09.780  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.780  3277  3337 I jxcore-log: 
03-23 13:06:09.780  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.780  3277  3337 I jxcore-log: 
03-23 13:06:09.781  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.781  3277  3337 I jxcore-log: 
,03-23 13:06:09.782  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.782  3277  3337 I jxcore-log: 
03-23 13:06:09.783  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.783  3277  3337 I jxcore-log: 
03-23 13:06:09.784  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.784  3277  3337 I jxcore-log: 
,03-23 13:06:09.784  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.784  3277  3337 I jxcore-log: 
03-23 13:06:09.785  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.785  3277  3337 I jxcore-log: 
03-23 13:06:09.786  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.786  3277  3337 I jxcore-log: 
,03-23 13:06:09.787  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:09.787  3277  3337 I jxcore-log: 
03-23 13:06:09.787  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:09.787  3277  3337 I jxcore-log: 
03-23 13:06:09.791  3277  3337 I jxcore-log: ok 28 native server is nulled out
03-23 13:06:09.791  3277  3337 I jxcore-log: 
,03-23 13:06:09.791  3277  3337 I jxcore-log: ok 29 native server should be closed
03-23 13:06:09.791  3277  3337 I jxcore-log: 
03-23 13:06:09.791  3277  3337 I jxcore-log: ok 30 incoming has been removed
03-23 13:06:09.791  3277  3337 I jxcore-log: 
03-23 13:06:09.792  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.792  3277  3337 I jxcore-log: 
,03-23 13:06:09.793  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.793  3277  3337 I jxcore-log: 
03-23 13:06:09.794  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.794  3277  3337 I jxcore-log: 
03-23 13:06:09.794  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.794  3277  3337 I jxcore-log: 
,03-23 13:06:09.794  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.794  3277  3337 I jxcore-log: 
03-23 13:06:09.795  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.795  3277  3337 I jxcore-log: 
03-23 13:06:09.795  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.795  3277  3337 I jxcore-log: 
03-23 13:06:09.795  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.795  3277  3337 I jxcore-log: 
,03-23 13:06:09.796  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.796  3277  3337 I jxcore-log: 
03-23 13:06:09.796  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:09.796  3277  3337 I jxcore-log: 
,03-23 13:06:09.898  3277  3337 I jxcore-log: # teardown
03-23 13:06:09.898  3277  3337 I jxcore-log: 
,03-23 13:06:10.030  3277  3337 I jxcore-log: # setup
03-23 13:06:10.030  3277  3337 I jxcore-log: 
,03-23 13:06:10.156  3277  3337 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-23 13:06:10.156  3277  3337 I jxcore-log: 
,03-23 13:06:10.273  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:10.273  3277  3337 I jxcore-log: 
,03-23 13:06:10.281  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 50791
03-23 13:06:10.281  3277  3337 I jxcore-log: 
,03-23 13:06:10.287  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:06:10.287  3277  3337 I jxcore-log: 
,03-23 13:06:10.288  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:10.288  3277  3337 I jxcore-log: 
,03-23 13:06:10.289  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:10.289  3277  3337 I jxcore-log: 
,03-23 13:06:10.297  3277  3337 I jxcore-log: ok 31 we should not have gotten an error
03-23 13:06:10.297  3277  3337 I jxcore-log: 
,03-23 13:06:10.301  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:10.301  3277  3337 I jxcore-log: 
,03-23 13:06:10.303  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:10.303  3277  3337 I jxcore-log: 
,03-23 13:06:10.310  3277  3337 I jxcore-log: ok 32 Buffers are identical
03-23 13:06:10.310  3277  3337 I jxcore-log: 
,03-23 13:06:10.311  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:10.311  3277  3337 I jxcore-log: 
,03-23 13:06:10.313  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:10.313  3277  3337 I jxcore-log: 
,03-23 13:06:10.324  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:10.324  3277  3337 I jxcore-log: 
,03-23 13:06:10.325  3277  3337 I jxcore-log: ok 33 server should be fine
03-23 13:06:10.325  3277  3337 I jxcore-log: 
,03-23 13:06:10.326  3277  3337 I jxcore-log: ok 34 server should be open
03-23 13:06:10.326  3277  3337 I jxcore-log: 
03-23 13:06:10.326  3277  3337 I jxcore-log: ok 35 incoming has been removed
03-23 13:06:10.326  3277  3337 I jxcore-log: 
03-23 13:06:10.327  3277  3337 I jxcore-log: ok 36 The mux object should be closed
03-23 13:06:10.327  3277  3337 I jxcore-log: 
,03-23 13:06:10.327  3277  3337 I jxcore-log: ok 37 The mux stream should be closed
03-23 13:06:10.327  3277  3337 I jxcore-log: 
,03-23 13:06:10.334  3277  3337 I jxcore-log: # teardown
03-23 13:06:10.334  3277  3337 I jxcore-log: 
,03-23 13:06:10.503  3277  3337 I jxcore-log: # setup
03-23 13:06:10.503  3277  3337 I jxcore-log: 
,03-23 13:06:10.656  3277  3337 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-23 13:06:10.656  3277  3337 I jxcore-log: 
,03-23 13:06:10.818  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:10.818  3277  3337 I jxcore-log: 
,03-23 13:06:10.823  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 40662
03-23 13:06:10.823  3277  3337 I jxcore-log: 
,03-23 13:06:10.828  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-23 13:06:10.828  3277  3337 I jxcore-log: 
03-23 13:06:10.830  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:06:10.830  3277  3337 I jxcore-log: 
,03-23 13:06:10.831  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:06:10.831  3277  3337 I jxcore-log: 
,03-23 13:06:10.837  3277  3337 I jxcore-log: ok 38 we should not have gotten an error
03-23 13:06:10.837  3277  3337 I jxcore-log: 
,03-23 13:06:10.841  3277  3337 I jxcore-log: DEBUG createNativeListener: new stream: 
03-23 13:06:10.841  3277  3337 I jxcore-log: 
,03-23 13:06:10.843  3277  3337 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-23 13:06:10.843  3277  3337 I jxcore-log: 
,03-23 13:06:10.849  3277  3337 I jxcore-log: ok 39 Buffers are identical
03-23 13:06:10.849  3277  3337 I jxcore-log: 
,03-23 13:06:10.854  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-23 13:06:10.854  3277  3337 I jxcore-log: 
,03-23 13:06:10.855  3277  3337 I jxcore-log: DEBUG createNativeListener: stream close:
03-23 13:06:10.855  3277  3337 I jxcore-log: 
,03-23 13:06:10.856  3277  3337 I jxcore-log: DEBUG createNativeListener: mux close
03-23 13:06:10.856  3277  3337 I jxcore-log: 
,03-23 13:06:10.861  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:06:10.861  3277  3337 I jxcore-log: 
,03-23 13:06:10.861  3277  3337 I jxcore-log: ok 40 server should be fine
03-23 13:06:10.861  3277  3337 I jxcore-log: 
,03-23 13:06:10.862  3277  3337 I jxcore-log: ok 41 server should be open
03-23 13:06:10.862  3277  3337 I jxcore-log: 
03-23 13:06:10.862  3277  3337 I jxcore-log: ok 42 incoming has been removed
03-23 13:06:10.862  3277  3337 I jxcore-log: 
03-23 13:06:10.862  3277  3337 I jxcore-log: ok 43 The mux object should be closed
03-23 13:06:10.862  3277  3337 I jxcore-log: 
,03-23 13:06:10.863  3277  3337 I jxcore-log: ok 44 The mux stream should be closed
03-23 13:06:10.863  3277  3337 I jxcore-log: 
,03-23 13:06:10.871  3277  3337 I jxcore-log: # teardown
03-23 13:06:10.871  3277  3337 I jxcore-log: 
,03-23 13:06:11.122  3277  3337 I jxcore-log: # setup
03-23 13:06:11.122  3277  3337 I jxcore-log: 
,03-23 13:06:11.230  3277  3337 I jxcore-log: # 12. closeAll can close even when connections open
03-23 13:06:11.230  3277  3337 I jxcore-log: 
,03-23 13:06:11.372  3277  3337 I jxcore-log: ok 45 not possible to connect to the server anymore
03-23 13:06:11.372  3277  3337 I jxcore-log: 
,03-23 13:06:11.377  3277  3337 I jxcore-log: # teardown
03-23 13:06:11.377  3277  3337 I jxcore-log: 
,03-23 13:06:11.492  3277  3337 I jxcore-log: # setup
03-23 13:06:11.492  3277  3337 I jxcore-log: 
,03-23 13:06:11.648  3277  3337 I jxcore-log: # 13. closeAll with promise
03-23 13:06:11.648  3277  3337 I jxcore-log: 
,03-23 13:06:11.843  3277  3337 I jxcore-log: ok 46 not possible to connect to the server anymore
03-23 13:06:11.843  3277  3337 I jxcore-log: 
,03-23 13:06:11.851  3277  3337 I jxcore-log: # teardown
,03-23 13:06:11.851  3277  3337 I jxcore-log: 
,03-23 13:06:11.973  3277  3337 I jxcore-log: # setup
03-23 13:06:11.973  3277  3337 I jxcore-log: 
,03-23 13:06:12.118  3277  3337 I jxcore-log: # 14. multiplex can send data
03-23 13:06:12.118  3277  3337 I jxcore-log: 
,03-23 13:06:12.253  3277  3337 I jxcore-log: ok 47 String should be length:200
03-23 13:06:12.253  3277  3337 I jxcore-log: 
,03-23 13:06:12.262  3277  3337 I jxcore-log: # teardown
03-23 13:06:12.262  3277  3337 I jxcore-log: 
,03-23 13:06:12.388  3277  3337 I jxcore-log: # setup
03-23 13:06:12.388  3277  3337 I jxcore-log: 
,03-23 13:06:12.531  3277  3337 I jxcore-log: # 15. enqueue and run in order
03-23 13:06:12.531  3277  3337 I jxcore-log: 
,03-23 13:06:12.789  3277  3337 I jxcore-log: ok 48 firstPromise setTimeout
03-23 13:06:12.789  3277  3337 I jxcore-log: 
,03-23 13:06:12.795  3277  3337 I jxcore-log: ok 49 firstPromise result
03-23 13:06:12.795  3277  3337 I jxcore-log: 
,03-23 13:06:12.798  3277  3337 I jxcore-log: ok 50 firstPromise testValue
03-23 13:06:12.798  3277  3337 I jxcore-log: 
,03-23 13:06:12.904  3277  3337 I jxcore-log: ok 51 secondPromise setTimeout
03-23 13:06:12.904  3277  3337 I jxcore-log: 
,03-23 13:06:12.910  3277  3337 I jxcore-log: ok 52 secondPromise result
03-23 13:06:12.910  3277  3337 I jxcore-log: 
,03-23 13:06:12.912  3277  3337 I jxcore-log: ok 53 secondPromise testValue
03-23 13:06:12.912  3277  3337 I jxcore-log: 
,03-23 13:06:12.918  3277  3337 I jxcore-log: ok 54 thirdPromise in promise
03-23 13:06:12.918  3277  3337 I jxcore-log: 
,03-23 13:06:12.923  3277  3337 I jxcore-log: ok 55 thirdPromise result
03-23 13:06:12.923  3277  3337 I jxcore-log: 
,03-23 13:06:12.926  3277  3337 I jxcore-log: ok 56 thirdPromise testValue
03-23 13:06:12.926  3277  3337 I jxcore-log: 
,03-23 13:06:12.940  3277  3337 I jxcore-log: # teardown
,03-23 13:06:12.940  3277  3337 I jxcore-log: 
,03-23 13:06:13.083  3277  3337 I jxcore-log: # setup
03-23 13:06:13.083  3277  3337 I jxcore-log: 
,03-23 13:06:13.213  3277  3337 I jxcore-log: # 16. enqueueAtTop and run backwards
03-23 13:06:13.213  3277  3337 I jxcore-log: 
,03-23 13:06:13.394  3277  3337 I jxcore-log: ok 57 thirdPromise - first to run
03-23 13:06:13.394  3277  3337 I jxcore-log: 
,03-23 13:06:13.395  3277  3337 I jxcore-log: ok 58 thirdPromise - in resolve
03-23 13:06:13.395  3277  3337 I jxcore-log: 
,03-23 13:06:13.397  3277  3337 I jxcore-log: ok 59 secondPromise - second to run
03-23 13:06:13.397  3277  3337 I jxcore-log: 
,03-23 13:06:13.398  3277  3337 I jxcore-log: ok 60 secondPromise - in catch
03-23 13:06:13.398  3277  3337 I jxcore-log: 
03-23 13:06:13.398  3277  3337 I jxcore-log: ok 61 firstPromise - third to run
03-23 13:06:13.398  3277  3337 I jxcore-log: 
,03-23 13:06:13.399  3277  3337 I jxcore-log: ok 62 firstPromise - in then
03-23 13:06:13.399  3277  3337 I jxcore-log: 
,03-23 13:06:13.400  3277  3337 I jxcore-log: ok 63 testing promises
03-23 13:06:13.400  3277  3337 I jxcore-log: 
03-23 13:06:13.402  3277  3337 I jxcore-log: # teardown
03-23 13:06:13.402  3277  3337 I jxcore-log: 
,03-23 13:06:13.607  3277  3337 I jxcore-log: # setup
03-23 13:06:13.607  3277  3337 I jxcore-log: ,
,03-23 13:06:13.732  3277  3337 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-23 13:06:13.732  3277  3337 I jxcore-log: 
,03-23 13:06:13.975  3277  3337 I jxcore-log: ok 64 fourth
03-23 13:06:13.975  3277  3337 I jxcore-log: 
,03-23 13:06:13.976  3277  3337 I jxcore-log: ok 65 fourth
03-23 13:06:13.976  3277  3337 I jxcore-log: 
03-23 13:06:13.977  3277  3337 I jxcore-log: ok 66 second
03-23 13:06:13.977  3277  3337 I jxcore-log: 
,03-23 13:06:13.978  3277  3337 I jxcore-log: ok 67 secondPromise - in then
03-23 13:06:13.978  3277  3337 I jxcore-log: 
,03-23 13:06:14.081  3277  3337 I jxcore-log: ok 68 first
03-23 13:06:14.081  3277  3337 I jxcore-log: 
,03-23 13:06:14.084  3277  3337 I jxcore-log: ok 69 firstPromise - in catch,
03-23 13:06:14.084  3277  3337 I jxcore-log: 
03-23 13:06:14.086  3277  3337 I jxcore-log: ok 70 third
03-23 13:06:14.086  3277  3337 I jxcore-log: 
,03-23 13:06:14.088  3277  3337 I jxcore-log: ok 71 thirdPromise - in then
03-23 13:06:14.088  3277  3337 I jxcore-log: 
03-23 13:06:14.091  3277  3337 I jxcore-log: ok 72 testingPromises
03-23 13:06:14.091  3277  3337 I jxcore-log: 
,03-23 13:06:14.111  3277  3337 I jxcore-log: # teardown
03-23 13:06:14.111  3277  3337 I jxcore-log: 
,03-23 13:06:14.232  3277  3337 I jxcore-log: # setup
03-23 13:06:14.232  3277  3337 I jxcore-log: ,
,03-23 13:06:14.403  3277  3337 I jxcore-log: # 18. queues handled independently
03-23 13:06:14.403  3277  3337 I jxcore-log: 
,03-23 13:06:14.637  3277  3337 I jxcore-log: ok 73 all short operations completed before the long resolves
03-23 13:06:14.637  3277  3337 I jxcore-log: 
,03-23 13:06:14.641  3277  3337 I jxcore-log: # teardown
03-23 13:06:14.641  3277  3337 I jxcore-log: 
,03-23 13:06:15.145  3277  3337 I jxcore-log: # setup
03-23 13:06:15.145  3277  3337 I jxcore-log: 
,03-23 13:06:15.393  3277  3337 I jxcore-log: # 19. basic
03-23 13:06:15.393  3277  3337 I jxcore-log: 
,03-23 13:06:15.854  3277  3337 I jxcore-log: ok 74 sane
03-23 13:06:15.854  3277  3337 I jxcore-log: 
,03-23 13:06:15.860  3277  3337 I jxcore-log: # teardown
03-23 13:06:15.860  3277  3337 I jxcore-log: 
,03-23 13:06:16.017  3277  3337 I jxcore-log: # setup
03-23 13:06:16.017  3277  3337 I jxcore-log: 
,03-23 13:06:16.178  3277  3337 I jxcore-log: # 20. another
03-23 13:06:16.178  3277  3337 I jxcore-log: 
,03-23 13:06:16.348  3277  3337 I jxcore-log: ok 75 sane
03-23 13:06:16.348  3277  3337 I jxcore-log: 
,03-23 13:06:16.355  3277  3337 I jxcore-log: # teardown
03-23 13:06:16.355  3277  3337 I jxcore-log: 
,03-23 13:06:16.500  3277  3337 I jxcore-log: # setup
03-23 13:06:16.500  3277  3337 I jxcore-log: ,
,03-23 13:06:16.676  3277  3337 I jxcore-log: # 21. can pass data in setup
03-23 13:06:16.676  3277  3337 I jxcore-log: 
,03-23 13:06:16.862  3277  3337 I jxcore-log: ok 76 test participant has uuid
03-23 13:06:16.862  3277  3337 I jxcore-log: 
,03-23 13:06:16.864  3277  3337 I jxcore-log: ok 77 participant data matches
03-23 13:06:16.864  3277  3337 I jxcore-log: 
,03-23 13:06:16.866  3277  3337 I jxcore-log: ok 78 test participant has uuid
03-23 13:06:16.866  3277  3337 I jxcore-log: 
03-23 13:06:16.867  3277  3337 I jxcore-log: ok 79 participant data matches
03-23 13:06:16.867  3277  3337 I jxcore-log: 
,03-23 13:06:16.868  3277  3337 I jxcore-log: ok 80 test participant has uuid
03-23 13:06:16.868  3277  3337 I jxcore-log: 
,03-23 13:06:16.870  3277  3337 I jxcore-log: ok 81 participant data matches
03-23 13:06:16.870  3277  3337 I jxcore-log: 
,03-23 13:06:16.872  3277  3337 I jxcore-log: # teardown
03-23 13:06:16.872  3277  3337 I jxcore-log: 
,03-23 13:06:17.024  3277  3337 I jxcore-log: # setup
03-23 13:06:17.024  3277  3337 I jxcore-log: 
,03-23 13:06:17.191  3277  3337 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-23 13:06:17.191  3277  3337 I jxcore-log: 
,03-23 13:06:17.437  3277  3337 I jxcore-log: ok 82 specific error should be returned
03-23 13:06:17.437  3277  3337 I jxcore-log: 
,03-23 13:06:17.443  3277  3337 I jxcore-log: # teardown
03-23 13:06:17.443  3277  3337 I jxcore-log: 
,03-23 13:06:17.568  3277  3337 I jxcore-log: ok 83 error should be null
03-23 13:06:17.568  3277  3337 I jxcore-log: 
,03-23 13:06:17.570  3277  3337 I jxcore-log: ok 84 error should be null
03-23 13:06:17.570  3277  3337 I jxcore-log: 
,03-23 13:06:17.572  3277  3337 I jxcore-log: # setup
03-23 13:06:17.572  3277  3337 I jxcore-log: 
,03-23 13:06:17.718  3277  3337 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-23 13:06:17.718  3277  3337 I jxcore-log: 
,03-23 13:06:18.321  3277  3337 I jxcore-log: ok 85 specific error should be returned
03-23 13:06:18.321  3277  3337 I jxcore-log: 
,03-23 13:06:18.327  3277  3337 I jxcore-log: # teardown
03-23 13:06:18.327  3277  3337 I jxcore-log: ,
,03-23 13:06:18.477  3277  3337 I jxcore-log: ok 86 error should be null
03-23 13:06:18.477  3277  3337 I jxcore-log: 
,03-23 13:06:18.479  3277  3337 I jxcore-log: ok 87 error should be null
03-23 13:06:18.479  3277  3337 I jxcore-log: 
,03-23 13:06:18.485  3277  3337 I jxcore-log: # setup
03-23 13:06:18.485  3277  3337 I jxcore-log: 
,03-23 13:06:19.448  3277  3337 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-23 13:06:19.448  3277  3337 I jxcore-log: 
,03-23 13:06:19.735  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:19.735  3277  3337 I jxcore-log: 
,03-23 13:06:19.736  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 57336
03-23 13:06:19.736  3277  3337 I jxcore-log: 
,03-23 13:06:19.739  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:19.740  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:19.740  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:19.743  3277  3337 I jxcore-log: ok 88 error should be null
03-23 13:06:19.743  3277  3337 I jxcore-log: 
,03-23 13:06:19.744  3277  3337 I jxcore-log: ok 89 error should be null
03-23 13:06:19.744  3277  3337 I jxcore-log: 
03-23 13:06:19.745  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:19.745  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:19.745  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:19.748  3277  3337 I jxcore-log: ok 90 error should be null
03-23 13:06:19.748  3277  3337 I jxcore-log: 
,03-23 13:06:19.748  3277  3337 I jxcore-log: ok 91 error should be null
03-23 13:06:19.748  3277  3337 I jxcore-log: 
,03-23 13:06:19.752  3277  3337 I jxcore-log: # teardown
03-23 13:06:19.752  3277  3337 I jxcore-log: 
,03-23 13:06:20.015  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:20.016  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:06:20.016  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:20.023  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:20.023  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:20.023  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:20.027  3277  3337 I jxcore-log: ok 92 error should be null
03-23 13:06:20.027  3277  3337 I jxcore-log: 
,03-23 13:06:20.028  3277  3337 I jxcore-log: ok 93 error should be null
03-23 13:06:20.028  3277  3337 I jxcore-log: 
,03-23 13:06:20.034  3277  3337 I jxcore-log: # setup
03-23 13:06:20.034  3277  3337 I jxcore-log: 
,03-23 13:06:20.264  3277  3337 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-23 13:06:20.264  3277  3337 I jxcore-log: ,
,03-23 13:06:20.790  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:20.790  3277  3337 I jxcore-log: 
,03-23 13:06:20.792  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 55040
03-23 13:06:20.792  3277  3337 I jxcore-log: 
,03-23 13:06:20.802  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-23 13:06:20.802  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:20.802  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-23 13:06:20.803  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-23 13:06:20.803  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:20.803  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:06:20.811  3277  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-23 13:06:20.812   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:20.821  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:06:20.828  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-23 13:06:20.829  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:20.829  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:06:20.829  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:20.842  2152  2216 D BtGatt.GattService: registerClient() - UUID=d7304b28-2f24-41a8-a795-b76062112d1a
,03-23 13:06:20.843  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=d7304b28-2f24-41a8-a795-b76062112d1a, clientIf=5
,03-23 13:06:20.845  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:20.846  2152  2169 D BtGatt.GattService: start scan with filters
,03-23 13:06:20.849  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:06:20.850  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:20.850  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:20.850  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-23 13:06:20.850  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:06:20.850  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:20.851  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:20.851  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:20.851   822  1313 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:20.854  2152  2225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@db6bce2
,03-23 13:06:20.860  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:20.860  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:20.861  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:20.862  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:20.862  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:20.863  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:20.867  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:06:20.867  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:20.870  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:20.870  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:20.871  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:06:20.871  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:06:20.874  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:20.874  3277  3337 I jxcore-log: 
03-23 13:06:20.875  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-23 13:06:20.875  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:20.877  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:20.877  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:20.877  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:20.877  3277  3337 I jxcore-log: 
,03-23 13:06:20.881  3277  3337 I jxcore-log: ok 94 error should be null
03-23 13:06:20.881  3277  3337 I jxcore-log: 
,03-23 13:06:20.881  3277  3337 I jxcore-log: ok 95 error should be null
03-23 13:06:20.881  3277  3337 I jxcore-log: 
,03-23 13:06:20.887  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-23 13:06:20.887  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:20.887  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:20.887  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:20.888  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:20.890  3277  3337 I jxcore-log: ok 96 error should be null
03-23 13:06:20.890  3277  3337 I jxcore-log: 
03-23 13:06:20.890  3277  3337 I jxcore-log: ok 97 error should be null
03-23 13:06:20.890  3277  3337 I jxcore-log: 
03-23 13:06:20.895  3277  3337 I jxcore-log: # teardown
03-23 13:06:20.895  3277  3337 I jxcore-log: 
,03-23 13:06:21.080  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:06:21.080  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:21.080  3277  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-23 13:06:21.080  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:21.080  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:21.080  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-23 13:06:21.080  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:21.081  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:06:21.081  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:21.085  2152  2169 D BtGatt.GattService: stopScan() - queue size =1,
,03-23 13:06:21.087  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:21.089  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:21.089  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-23 13:06:21.089  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:21.089  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-23 13:06:21.089  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-23 13:06:21.089  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:21.090  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:21.090  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.090  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:06:21.091  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:21.091  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:06:21.091  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:21.093  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:21.093  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:21.093  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:21.093  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.093  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:21.093  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:21.093  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:21.093  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:06:21.095  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:06:21.096  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.096  3277  3337 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-23 13:06:21.096  3277  3337 I jxcore-log: 
03-23 13:06:21.105  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:06:21.105   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:21.113  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:06:21.114  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:06:21.114  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:21.120  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-23 13:06:21.120  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:21.121  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:21.121  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:21.122  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:06:21.122  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:21.122  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:21.123  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:21.123  3277  3337 I jxcore-log: 
,03-23 13:06:21.124  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-23 13:06:21.124  3277  3337 I jxcore-log: 
03-23 13:06:21.128  3277  3337 I jxcore-log: ok 98 error should be null
03-23 13:06:21.128  3277  3337 I jxcore-log: 
03-23 13:06:21.128  3277  3337 I jxcore-log: ok 99 error should be null
03-23 13:06:21.128  3277  3337 I jxcore-log: 
03-23 13:06:21.133  3277  3337 I jxcore-log: # setup
03-23 13:06:21.133  3277  3337 I jxcore-log: 
,03-23 13:06:21.306  3277  3337 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-23 13:06:21.306  3277  3337 I jxcore-log: 
,03-23 13:06:21.391  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:21.391  3277  3337 I jxcore-log: 
,03-23 13:06:21.393  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 34887
03-23 13:06:21.393  3277  3337 I jxcore-log: 
,03-23 13:06:21.409  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 34887, start advertisements: true
,03-23 13:06:21.409  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:21.409  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:21.409  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:21.413  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-23 13:06:21.413  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:06:21.413  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-23 13:06:21.413  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:21.417  2152  2168 D BtGatt.GattService: registerClient() - UUID=7621f3d3-9f6a-4132-b764-517db07d4cca
,03-23 13:06:21.417  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=7621f3d3-9f6a-4132-b764-517db07d4cca, clientIf=5,
03-23 13:06:21.418  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:21.418  2152  2169 D BtGatt.GattService: start scan with filters
,03-23 13:06:21.420  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:21.421  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:21.422  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:21.422  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:06:21.422  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-23 13:06:21.422  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:06:21.422  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:06:21.422  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:21.423  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:21.423  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:06:21.423  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.424  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:21.425  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:21.425  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:21.425  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:21.425  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:06:21.428  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:21.428  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.429  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-23 13:06:21.429  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.433  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:21.433  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:21.433  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:06:21.439  2152  2216 D BtGatt.GattService: registerClient() - UUID=ec83ce47-5f5c-400d-a726-a3a186a196af
,03-23 13:06:21.440  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=ec83ce47-5f5c-400d-a726-a3a186a196af, clientIf=6
03-23 13:06:21.440  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:06:21.443  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:06:21.447  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:21.450  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-23 13:06:21.452  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-23 13:06:21.454  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:06:21.454  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:21.455   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:21.458  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:21.458  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-23 13:06:21.458  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:06:21.458  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:21.459  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:06:21.461  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:06:21.461  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:06:21.461  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:06:21.462  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:21.463  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:06:21.463  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:21.463  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:06:21.463  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:21.464  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-23 13:06:21.464  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:21.464  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:21.464  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:06:21.464  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:21.464  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:06:21.465  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:21.466  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:21.466   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:21.468  3277  3798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:06:21.480  3277  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:06:21.483  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:21.483  3277  3337 I jxcore-log: 
,03-23 13:06:21.484  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:21.484  3277  3337 I jxcore-log: 
,03-23 13:06:21.485  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:06:21.485  3277  3337 I jxcore-log: 
,03-23 13:06:21.487  3277  3337 I jxcore-log: ok 100 error should be null
03-23 13:06:21.487  3277  3337 I jxcore-log: 
03-23 13:06:21.487  3277  3337 I jxcore-log: ok 101 error should be null
03-23 13:06:21.487  3277  3337 I jxcore-log: 
,03-23 13:06:21.496  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 34887, start advertisements: true
,03-23 13:06:21.496  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:21.496  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:06:21.496  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:06:21.497  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:21.507  3277  3337 I jxcore-log: ok 102 error should be null
03-23 13:06:21.507  3277  3337 I jxcore-log: 
,03-23 13:06:21.507  3277  3337 I jxcore-log: ok 103 error should be null
03-23 13:06:21.507  3277  3337 I jxcore-log: 
,03-23 13:06:21.513  3277  3337 I jxcore-log: # teardown,
03-23 13:06:21.513  3277  3337 I jxcore-log: 
,03-23 13:06:21.933  2152  2152 D BtGatt.ScanManager: awakened up at time 199834
,03-23 13:06:21.935  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:21.946  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3,
03-23 13:06:21.946  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:21.947  2152  2214 D BtGatt.GattService: current time is 199848035286
,03-23 13:06:21.947  2152  2214 D BtGatt.GattService: Batch record : [116, 48, 92, 85, -93, 106, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -61, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-23 13:06:21.949  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-23 13:06:21.953  2152  2214 D BtGatt.GattService: ScanRecord : []
03-23 13:06:21.954  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:06:21.965  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-23 13:06:21.968  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-23 13:06:21.970  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-23 13:06:21.971  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-23 13:06:21.980  3277  3337 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-23 13:06:21.980  3277  3337 I jxcore-log: 
,03-23 13:06:21.994  3277  3337 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-23 13:06:21.994  3277  3337 I jxcore-log: 
,03-23 13:06:22.003  3277  3337 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-23 13:06:22.003  3277  3337 I jxcore-log: 
,03-23 13:06:22.006  3277  3337 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-23 13:06:22.006  3277  3337 I jxcore-log: 
,03-23 13:06:22.122  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:22.123  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-23 13:06:22.123  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:06:22.123  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:06:22.123  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-23 13:06:22.124  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:06:22.124  3277  3798 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:06:22.124  3277  3798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-23 13:06:22.124  3277  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-23 13:06:22.125  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-23 13:06:22.125  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:22.125  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:22.125  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-23 13:06:22.125  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:22.126  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:06:22.126  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:22.126  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:06:22.127  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:22.129  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:22.130  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:22.130  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:22.130  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-23 13:06:22.130  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:06:22.130  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:06:22.130  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:22.130  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:06:22.132  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:22.132  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:22.132  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:22.132  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:06:22.133  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:22.135  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:22.135  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:22.136  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:22.137  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:06:22.137  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:06:22.138  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:22.139  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:22.139  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:06:22.139  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:06:22.139  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:06:22.139  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:06:22.139  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:22.139  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-23 13:06:22.139  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:22.140  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:22.140  3277  3337 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-23 13:06:22.140  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:22.141  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:22.141  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:22.141  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:06:22.142  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-23 13:06:22.142  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:22.142  2152  2214 D BtGatt.GattService: current time is 200043521328
03-23 13:06:22.142  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:06:22.143  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:22.150  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-23 13:06:22.151   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:22.155  3277  3337 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-23 13:06:22.155  3277  3337 I jxcore-log: 
,03-23 13:06:22.161  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:06:22.161  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:06:22.162  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:22.164  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-23 13:06:22.164  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:22.164  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:22.164  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:22.165  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:22.165  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:22.165  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:22.166  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:22.166  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:06:22.167  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:06:22.167  3277  3337 I jxcore-log: 
03-23 13:06:22.168  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:22.168  3277  3337 I jxcore-log: 
,03-23 13:06:22.168  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:22.168  3277  3337 I jxcore-log: 
,03-23 13:06:22.174  3277  3337 I jxcore-log: ok 104 error should be null
03-23 13:06:22.174  3277  3337 I jxcore-log: 
,03-23 13:06:22.175  3277  3337 I jxcore-log: ok 105 error should be null
03-23 13:06:22.175  3277  3337 I jxcore-log: 
03-23 13:06:22.181  3277  3337 I jxcore-log: # setup
03-23 13:06:22.181  3277  3337 I jxcore-log: 
,03-23 13:06:22.252  3277  3337 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
03-23 13:06:22.252  3277  3337 I jxcore-log: 
,03-23 13:06:22.424  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:22.424  3277  3337 I jxcore-log: 
,03-23 13:06:22.426  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 36193
03-23 13:06:22.426  3277  3337 I jxcore-log: 
,03-23 13:06:22.431  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:22.431  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:06:22.431  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:22.435  3277  3337 I jxcore-log: ok 106 error should be null
,03-23 13:06:22.435  3277  3337 I jxcore-log: 
03-23 13:06:22.435  3277  3337 I jxcore-log: ok 107 error should be null
03-23 13:06:22.435  3277  3337 I jxcore-log: 
,03-23 13:06:22.438  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:06:22.438  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:22.438  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-23 13:06:22.440  3277  3337 I jxcore-log: ok 108 error should be null
,03-23 13:06:22.440  3277  3337 I jxcore-log: 
03-23 13:06:22.440  3277  3337 I jxcore-log: ok 109 error should be null
03-23 13:06:22.440  3277  3337 I jxcore-log: 
,03-23 13:06:22.446  3277  3337 I jxcore-log: # teardown
03-23 13:06:22.446  3277  3337 I jxcore-log: 
,03-23 13:06:22.613  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:22.613  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-23 13:06:22.613  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:22.620  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-23 13:06:22.620  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-23 13:06:22.620  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-23 13:06:22.625  3277  3337 I jxcore-log: ok 110 error should be null
03-23 13:06:22.625  3277  3337 I jxcore-log: 
,03-23 13:06:22.626  3277  3337 I jxcore-log: ok 111 error should be null
03-23 13:06:22.626  3277  3337 I jxcore-log: 
,03-23 13:06:22.631  3277  3337 I jxcore-log: # setup
,03-23 13:06:22.631  3277  3337 I jxcore-log: 
,03-23 13:06:22.747  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:22.750  3277  3337 I jxcore-log: # 28. #start should fail if called twice in a row
03-23 13:06:22.750  3277  3337 I jxcore-log: 
,03-23 13:06:22.796  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-23 13:06:22.796  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:22.796  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:06:22.796  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:22.804  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:22.832  3691  3691 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-23 13:06:22.835  3691  3691 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-23 13:06:22.837  3691  3691 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-23 13:06:22.881  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:06:22.881  3277  3337 I jxcore-log: 
03-23 13:06:22.882  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 52730
03-23 13:06:22.882  3277  3337 I jxcore-log: 
03-23 13:06:22.884  3277  3337 I jxcore-log: ok 112 first call should succeed
03-23 13:06:22.884  3277  3337 I jxcore-log: 
03-23 13:06:22.884  3277  3337 I jxcore-log: ok 113 first call should succeed
03-23 13:06:22.884  3277  3337 I jxcore-log: 
03-23 13:06:22.886  3277  3337 I jxcore-log: ok 114 specific error should be returned
03-23 13:06:22.886  3277  3337 I jxcore-log: 
03-23 13:06:22.887  3277  3337 I jxcore-log: # teardown
03-23 13:06:22.887  3277  3337 I jxcore-log: 
,03-23 13:06:23.064  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:06:23.064  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:23.065  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:23.070  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:23.070  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:23.070  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:23.076  3277  3337 I jxcore-log: ok 115 error should be null
03-23 13:06:23.076  3277  3337 I jxcore-log: 
,03-23 13:06:23.076  3277  3337 I jxcore-log: ok 116 error should be null
03-23 13:06:23.076  3277  3337 I jxcore-log: 
,03-23 13:06:23.081  3277  3337 I jxcore-log: # setup
03-23 13:06:23.081  3277  3337 I jxcore-log: 
,03-23 13:06:23.225  3277  3337 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-23 13:06:23.225  3277  3337 I jxcore-log: 
,03-23 13:06:23.381  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
,03-23 13:06:23.381  3277  3337 I jxcore-log: 
,03-23 13:06:23.383  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 60225
03-23 13:06:23.383  3277  3337 I jxcore-log: 
,03-23 13:06:23.392  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 34887, start advertisements: false
,03-23 13:06:23.392  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:23.392  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:23.392  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-23 13:06:23.398  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:06:23.398  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:23.398  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:23.403  2152  2216 D BtGatt.GattService: registerClient() - UUID=5a814098-e0c0-4429-916b-18209c57d53c,
03-23 13:06:23.404  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=5a814098-e0c0-4429-916b-18209c57d53c, clientIf=5
,03-23 13:06:23.404  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:23.405  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:06:23.406  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:23.406  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:23.406  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-23 13:06:23.407  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:06:23.407  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:06:23.407  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:23.407  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:06:23.407  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-23 13:06:23.408   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:23.410  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:23.410  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:23.411  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:23.411  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:06:23.411  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:23.411  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:23.416  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:06:23.416  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:23.416  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:23.416  3277  3337 I jxcore-log: 
,03-23 13:06:23.417  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:23.417  3277  3337 I jxcore-log: 
03-23 13:06:23.418  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-23 13:06:23.418  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:23.418  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:23.418  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:06:23.422  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:23.422  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-23 13:06:23.423  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:23.423  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:23.431  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 60225, start advertisements: true
,03-23 13:06:23.431  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:23.432  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:23.432  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:23.436  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-23 13:06:23.436  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-23 13:06:23.436  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:06:23.436  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:23.436  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:23.437  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:23.437  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:23.437  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:06:23.442  2152  2216 D BtGatt.GattService: registerClient() - UUID=a3404473-9a21-46fa-a785-123586712d63
,03-23 13:06:23.443  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=a3404473-9a21-46fa-a785-123586712d63, clientIf=6
03-23 13:06:23.443  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:06:23.445  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:06:23.449  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:23.453  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:06:23.456  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:23.457  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:23.457  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-23 13:06:23.457  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:23.457  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:23.457  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-23 13:06:23.457  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:23.457  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:06:23.458   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:23.462  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:06:23.462  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:23.462  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:23.462  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:06:23.463  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:23.464  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-23 13:06:23.464  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:06:23.464  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-23 13:06:23.464  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:06:23.465  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:23.465  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-23 13:06:23.465  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:23.465  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:06:23.466   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:23.467  3277  3799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-23 13:06:23.470  3277  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:06:23.484  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:06:23.484  3277  3337 I jxcore-log: 
,03-23 13:06:23.492  3277  3337 I jxcore-log: ok 117 called only once
03-23 13:06:23.492  3277  3337 I jxcore-log: 
,03-23 13:06:23.493  3277  3337 I jxcore-log: ok 118 discovery state matches
03-23 13:06:23.493  3277  3337 I jxcore-log: 
,03-23 13:06:23.493  3277  3337 I jxcore-log: ok 119 advertising state matches
03-23 13:06:23.493  3277  3337 I jxcore-log: 
,03-23 13:06:23.502  3277  3337 I jxcore-log: # teardown
03-23 13:06:23.502  3277  3337 I jxcore-log: 
,03-23 13:06:24.431  2152  2152 D BtGatt.ScanManager: awakened up at time 202332,
03-23 13:06:24.433  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:24.441  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-23 13:06:24.441  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-23 13:06:24.441  2152  2214 D BtGatt.GattService: current time is 202342475650
03-23 13:06:24.441  2152  2214 D BtGatt.GattService: Batch record : [-49, 39, -22, -118, 3, 113, 1, -128, -79, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -107, 19, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-23 13:06:24.442  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:24.443  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0],
03-23 13:06:24.443  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:24.445  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-23 13:06:24.445  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-23 13:06:24.445  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-23 13:06:24.446  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-23 13:06:24.448  3277  3337 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-23 13:06:24.448  3277  3337 I jxcore-log: 
,03-23 13:06:24.453  3277  3337 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-23 13:06:24.453  3277  3337 I jxcore-log: 
,03-23 13:06:24.454  3277  3337 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-23 13:06:24.454  3277  3337 I jxcore-log: 
,03-23 13:06:24.457  3277  3337 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-23 13:06:24.457  3277  3337 I jxcore-log: 
,03-23 13:06:24.850  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-23 13:06:25.457  2152  2152 D BtGatt.ScanManager: awakened up at time 203358
,03-23 13:06:25.459  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:25.471  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-23 13:06:25.471  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:25.472  2152  2214 D BtGatt.GattService: current time is 203372907160,
03-23 13:06:25.472  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:06:25.472  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:25.475  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-23 13:06:26.023  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:26.023  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-23 13:06:26.024  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:06:26.024  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:06:26.024  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:06:26.025  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:06:26.025  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:26.025  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:26.025  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-23 13:06:26.025  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:26.025  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:06:26.025  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-23 13:06:26.027  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:26.028  3277  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:06:26.028  3277  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:06:26.028  3277  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-23 13:06:26.029  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-23 13:06:26.030  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:26.030  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:26.030  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:26.030  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:26.030  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:26.031  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:26.031  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:06:26.031  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:06:26.031  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:26.031  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:06:26.034  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:26.034  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:26.035  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:26.035  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:26.036  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:26.037  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:06:26.037  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:26.040  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:06:26.040  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:06:26.042  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-23 13:06:26.043  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:26.043  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:26.043  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:06:26.043  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:06:26.043  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:06:26.043  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:26.043  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:06:26.043  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:26.044  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:26.044  3277  3337 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-23 13:06:26.044  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:26.044  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:26.044  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:26.045  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:06:26.053  3277  3337 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-23 13:06:26.053  3277  3337 I jxcore-log: 
,03-23 13:06:26.054  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:06:26.055   822  1357 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:26.059  3277  3337 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-23 13:06:26.059  3277  3337 I jxcore-log: 
,03-23 13:06:26.060  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:06:26.061  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:06:26.062  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:26.066  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-23 13:06:26.066  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-23 13:06:26.066  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:06:26.066  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:06:26.066  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:06:26.067  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-23 13:06:26.067  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:26.068  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-23 13:06:26.069  3277  3337 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-23 13:06:26.069  3277  3337 I jxcore-log: 
,03-23 13:06:26.071  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:06:26.071  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:26.071  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:26.072  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:06:26.072  3277  3337 I jxcore-log: 
03-23 13:06:26.073  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:26.073  3277  3337 I jxcore-log: 
,03-23 13:06:26.074  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:26.074  3277  3337 I jxcore-log: 
03-23 13:06:26.078  3277  3337 I jxcore-log: ok 120 error should be null
03-23 13:06:26.078  3277  3337 I jxcore-log: 
,03-23 13:06:26.079  3277  3337 I jxcore-log: ok 121 error should be null
03-23 13:06:26.079  3277  3337 I jxcore-log: 
,03-23 13:06:26.084  3277  3337 I jxcore-log: # setup
03-23 13:06:26.084  3277  3337 I jxcore-log: 
,03-23 13:06:26.561  3277  3337 I jxcore-log: # 30. does not send duplicate availability changes
03-23 13:06:26.561  3277  3337 I jxcore-log: 
,03-23 13:06:28.179  3384  3801 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-23 13:06:28.252  1261  1842 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-23 13:06:28.253  1261  1842 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:28.253  1261  1842 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:28.253  1261  1842 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:28.263  1261  1842 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:28.301  3384  3801 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	,at com.a.a.a.k.get(SourceFile:97)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-23 13:06:28.304  3384  3801 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-23 13:06:29.169  3277  3337 I jxcore-log: ok 122 should be called once
03-23 13:06:29.169  3277  3337 I jxcore-log: 
,03-23 13:06:29.171  3277  3337 I jxcore-log: ok 123 should not have been called more than once
03-23 13:06:29.171  3277  3337 I jxcore-log: 
,03-23 13:06:29.174  3277  3337 I jxcore-log: # teardown
03-23 13:06:29.174  3277  3337 I jxcore-log: 
,03-23 13:06:29.742  3277  3337 I jxcore-log: ok 124 error should be null
03-23 13:06:29.742  3277  3337 I jxcore-log: 
,03-23 13:06:29.743  3277  3337 I jxcore-log: ok 125 error should be null
03-23 13:06:29.743  3277  3337 I jxcore-log: 
,03-23 13:06:29.746  3277  3337 I jxcore-log: # setup
03-23 13:06:29.746  3277  3337 I jxcore-log: 
,03-23 13:06:29.975  3277  3337 I jxcore-log: # 31. can get the network status
03-23 13:06:29.975  3277  3337 I jxcore-log: 
,03-23 13:06:30.097  3277  3337 I jxcore-log: ok 126 network status should have certain non-empty properties
03-23 13:06:30.097  3277  3337 I jxcore-log: 
,03-23 13:06:30.102  3277  3337 I jxcore-log: # teardown
03-23 13:06:30.102  3277  3337 I jxcore-log: 
,03-23 13:06:30.230  3277  3337 I jxcore-log: ok 127 error should be null
03-23 13:06:30.230  3277  3337 I jxcore-log: 
,03-23 13:06:30.231  3277  3337 I jxcore-log: ok 128 error should be null
03-23 13:06:30.231  3277  3337 I jxcore-log: 
,03-23 13:06:30.240  3277  3337 I jxcore-log: # setup
03-23 13:06:30.240  3277  3337 I jxcore-log: 
,03-23 13:06:30.335  3277  3337 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-23 13:06:30.335  3277  3337 I jxcore-log: 
,03-23 13:06:30.526  3277  3337 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-23 13:06:30.526  3277  3337 I jxcore-log: 
,03-23 13:06:30.551  3277  3337 I jxcore-log: ok 129 host address should match
03-23 13:06:30.551  3277  3337 I jxcore-log: 
,03-23 13:06:30.551  3277  3337 I jxcore-log: ok 130 port should match
03-23 13:06:30.551  3277  3337 I jxcore-log: 
,03-23 13:06:32.529  3277  3337 I jxcore-log: ok 131 host address should be null
03-23 13:06:32.529  3277  3337 I jxcore-log: 
,03-23 13:06:32.531  3277  3337 I jxcore-log: ok 132 port should should be null
03-23 13:06:32.531  3277  3337 I jxcore-log: 
,03-23 13:06:32.554  3277  3337 I jxcore-log: # teardown
03-23 13:06:32.554  3277  3337 I jxcore-log: 
,03-23 13:06:32.671  3277  3337 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-23 13:06:32.671  3277  3337 I jxcore-log: 
,03-23 13:06:32.674  3277  3337 I jxcore-log: ok 133 error should be null
03-23 13:06:32.674  3277  3337 I jxcore-log: 
,03-23 13:06:32.674  3277  3337 I jxcore-log: ok 134 error should be null
03-23 13:06:32.674  3277  3337 I jxcore-log: 
,03-23 13:06:32.677  3277  3337 I jxcore-log: # setup
03-23 13:06:32.677  3277  3337 I jxcore-log: 
,03-23 13:06:32.803  3277  3337 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-23 13:06:32.803  3277  3337 I jxcore-log: 
,03-23 13:06:32.950  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 60225, start advertisements: false
03-23 13:06:32.950  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:32.950  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-23 13:06:32.951  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-23 13:06:32.958  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:32.959  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:06:32.959  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:32.968  2152  2169 D BtGatt.GattService: registerClient() - UUID=9201a3cf-5c53-43d4-afef-3585efb7f0ae
03-23 13:06:32.969  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=9201a3cf-5c53-43d4-afef-3585efb7f0ae, clientIf=5
,03-23 13:06:32.970  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:32.971  2152  2216 D BtGatt.GattService: start scan with filters
03-23 13:06:32.973  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:32.974  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:32.974  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:32.975  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:06:32.975  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:06:32.975  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-23 13:06:32.975  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:32.975  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:32.976   822   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:32.987  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:32.987  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:32.988  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:32.988  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:32.988  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:06:32.988  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:32.993  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:32.993  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:32.996  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:32.997  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:32.996  3277  3337 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error,
03-23 13:06:32.996  3277  3337 I jxcore-log: 
,03-23 13:06:32.997  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:06:32.997  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:33.001  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-23 13:06:33.001  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:33.001  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-23 13:06:33.001  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:33.001  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:33.001  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.003  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:33.004  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.004  2152  2216 D BtGatt.GattService: stopScan() - queue size =1,
03-23 13:06:33.006  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:33.006  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:06:33.006  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:33.006  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:33.006  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-23 13:06:33.006  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-23 13:06:33.006  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:33.007  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:33.007  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-23 13:06:33.007  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:33.007  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:33.007  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.008  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:06:33.008  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:33.008  3277  3337 I jxcore-log: 
03-23 13:06:33.009  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:33.009  3277  3337 I jxcore-log: 
03-23 13:06:33.011  3277  3337 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error,
03-23 13:06:33.011  3277  3337 I jxcore-log: 
03-23 13:06:33.012  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:06:33.012  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.012  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:33.014  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:06:33.014  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:33.021  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:33.021  3277  3337 I jxcore-log: 
03-23 13:06:33.022  3277  3337 I jxcore-log: # teardown
,03-23 13:06:33.022  3277  3337 I jxcore-log: 
,03-23 13:06:33.201  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:33.201  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:33.201  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:33.207  3277  3337 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-23 13:06:33.207  3277  3337 I jxcore-log: 
,03-23 13:06:33.209  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:33.209  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:33.210  3277  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-23 13:06:33.210  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:33.210  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-23 13:06:33.210  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:06:33.210  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:33.211  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:06:33.214  3277  3337 D BluetoothLeScanner: could not find callback wrapper
03-23 13:06:33.214  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:06:33.217  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:06:33.217  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:06:33.217  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:33.219  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:33.220  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:33.220  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:33.220  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:33.221  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:06:33.235  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:06:33.236   822  1391 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:33.253  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:06:33.256  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:06:33.256  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:33.266  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:33.266  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:33.266  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:06:33.271  3277  3337 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
03-23 13:06:33.271  3277  3337 I jxcore-log: 
,03-23 13:06:33.295  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:33.295  3277  3337 I jxcore-log: 
,03-23 13:06:33.297  3277  3337 I jxcore-log: # setup
03-23 13:06:33.297  3277  3337 I jxcore-log: 
,03-23 13:06:33.388  3277  3337 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error
03-23 13:06:33.388  3277  3337 I jxcore-log: 
,03-23 13:06:33.550  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 60225, start advertisements: false
,03-23 13:06:33.550  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:33.550  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:33.550  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-23 13:06:33.560  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:06:33.561  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:33.561  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:33.571  2152  2168 D BtGatt.GattService: registerClient() - UUID=62d8c64c-477d-4b3c-8057-f3e3eeabc563
,03-23 13:06:33.572  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=62d8c64c-477d-4b3c-8057-f3e3eeabc563, clientIf=5
,03-23 13:06:33.573  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:33.574  2152  2216 D BtGatt.GattService: start scan with filters
,03-23 13:06:33.578  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-23 13:06:33.578  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:33.578  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-23 13:06:33.578  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:33.578  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:06:33.579  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:06:33.579  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:33.580  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:33.581   822  1313 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:33.585  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:33.585  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.588  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:33.588  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.589  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:33.589  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:06:33.592  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:33.593  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:33.594  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:33.594  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-23 13:06:33.595  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:33.595  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:33.596  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:06:33.596  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:33.596  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:33.597  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:33.604  3277  3337 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-23 13:06:33.604  3277  3337 I jxcore-log: 
,03-23 13:06:33.610  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 60225, start advertisements: false,
03-23 13:06:33.610  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:33.610  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-23 13:06:33.611  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:06:33.612  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:33.614  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:33.614  3277  3337 I jxcore-log: 
,03-23 13:06:33.617  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:33.617  3277  3337 I jxcore-log: 
,03-23 13:06:33.620  3277  3337 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-23 13:06:33.620  3277  3337 I jxcore-log: 
,03-23 13:06:33.632  3277  3337 I jxcore-log: # teardown
03-23 13:06:33.632  3277  3337 I jxcore-log: 
,03-23 13:06:34.087  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:06:34.087  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:34.088  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-23 13:06:34.088  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:34.093  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:34.101  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-23 13:06:34.102  2152  2152 D BtGatt.ScanManager: awakened up at time 212003
03-23 13:06:34.103  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:34.103  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:34.103  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:34.104  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:34.104  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:34.104  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:34.104  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-23 13:06:34.104  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-23 13:06:34.105  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:34.105  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:34.106  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:34.106  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:34.107  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:34.107  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:34.107  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:34.109  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-23 13:06:34.109  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:34.112  3277  3337 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
,03-23 13:06:34.112  3277  3337 I jxcore-log: 
,03-23 13:06:34.113  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-23 13:06:34.113  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:06:34.113  3277  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-23 13:06:34.114  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-23 13:06:34.114  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:34.114  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-23 13:06:34.114  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:34.114  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-23 13:06:34.116  3277  3337 D BluetoothLeScanner: could not find callback wrapper
,03-23 13:06:34.116  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:34.118  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:34.118  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-23 13:06:34.118  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:34.119  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-23 13:06:34.120  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:34.120  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:34.120  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-23 13:06:34.120  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:06:34.125  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:34.125  3277  3337 I jxcore-log: 
03-23 13:06:34.130  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:06:34.130   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:34.136  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:06:34.137  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:34.137  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:34.140  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-23 13:06:34.140  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:34.140  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:06:34.144  3277  3337 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown,
03-23 13:06:34.144  3277  3337 I jxcore-log: 
,03-23 13:06:34.151  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:34.151  3277  3337 I jxcore-log: ,
03-23 13:06:34.152  3277  3337 I jxcore-log: # setup
03-23 13:06:34.152  3277  3337 I jxcore-log: 
,03-23 13:06:34.270  3277  3337 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-23 13:06:34.270  3277  3337 I jxcore-log: 
,03-23 13:06:34.914  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-23 13:06:34.915  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:34.915  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:34.915  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:34.924  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-23 13:06:34.924  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:34.924  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:34.924  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:34.933  2152  2168 D BtGatt.GattService: registerClient() - UUID=d6fe3ec1-ce8b-43d7-85a7-f26189a1f93f
,03-23 13:06:34.934  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=d6fe3ec1-ce8b-43d7-85a7-f26189a1f93f, clientIf=5
03-23 13:06:34.935  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:06:34.936  2152  2216 D BtGatt.GattService: start scan with filters,
03-23 13:06:34.938  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:34.939  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:06:34.940  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:06:34.940  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:06:34.940  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-23 13:06:34.940  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:34.940  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:06:34.940  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:06:34.941  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:34.941  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:34.941  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:34.942  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:34.942  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:06:34.946  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:34.946  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:34.948  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:34.949  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:34.949  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:06:34.949  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:34.953  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:34.953  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:34.956  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:34.956  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:34.962  2152  2169 D BtGatt.GattService: registerClient() - UUID=9a7981da-9a96-45a6-b7e7-f20f5990ed96
03-23 13:06:34.962  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=9a7981da-9a96-45a6-b7e7-f20f5990ed96, clientIf=6,
03-23 13:06:34.963  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:06:34.964  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:06:34.969  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:34.973  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-23 13:06:34.976  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:34.977  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:34.977  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-23 13:06:34.977   822  1100 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:34.982  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:34.982  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:34.982  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:06:34.982  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:34.983  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:06:34.983  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:06:34.984  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-23 13:06:34.984  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:06:34.985  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-23 13:06:34.985  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-23 13:06:34.985  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-23 13:06:34.985  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:06:34.985  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:34.985   822  1161 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:34.986  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:06:34.986  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:06:34.986  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:34.986  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:06:34.986  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:34.987  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:06:34.987  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:06:34.987  3277  3803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:06:34.988  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:34.991  3277  3803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-23 13:06:34.992  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:34.992  3277  3337 I jxcore-log: 
03-23 13:06:34.995  3277  3337 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-23 13:06:34.995  3277  3337 I jxcore-log: 
,03-23 13:06:34.997  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:06:34.997  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-23 13:06:34.997  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:06:34.998  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:06:34.998  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:06:34.998  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-23 13:06:34.998  3277  3803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:06:34.998  3277  3803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:06:34.998  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:34.998  3277  3803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:06:34.999  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-23 13:06:34.999  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:06:34.999  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-23 13:06:34.998  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:34.999  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:06:34.999  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:34.999  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-23 13:06:34.999  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-23 13:06:35.004  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:35.006  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:35.007  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:35.007  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:35.007  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:06:35.007  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:06:35.008  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:35.008  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:35.008  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:06:35.008  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-23 13:06:35.008  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:06:35.008  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-23 13:06:35.010  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:06:35.010  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:35.010  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:35.011  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:35.011  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:35.013  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-23 13:06:35.013  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:35.013  2152  2214 D BtGatt.GattService: current time is 212914873146,
03-23 13:06:35.014  2152  2214 D BtGatt.GattService: Batch record : [-53, 46, -91, 10, 9, 102, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-23 13:06:35.014  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:35.015  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-23 13:06:35.015  2152  2214 D BtGatt.GattService: Client app is not null!,
,03-23 13:06:35.017  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:35.018  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:35.018  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-23 13:06:35.018  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-23 13:06:35.018  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:06:35.018  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:06:35.018  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:35.019  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-23 13:06:35.019  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:35.020  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:35.020  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:35.020  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-23 13:06:35.020  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:35.020  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:35.020  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-23 13:06:35.020  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:06:35.021  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:35.021  3277  3337 I jxcore-log: 
03-23 13:06:35.024  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-23 13:06:35.024  3277  3337 I jxcore-log: 
03-23 13:06:35.025  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-23 13:06:35.026  3277  3337 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-23 13:06:35.026  3277  3337 I jxcore-log: 
03-23 13:06:35.026   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-23 13:06:35.031  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:06:35.032  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:35.032  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:35.034  3277  3337 I jxcore-log: # teardown
03-23 13:06:35.034  3277  3337 I jxcore-log: 
03-23 13:06:35.035  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:06:35.035  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-23 13:06:35.035  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:35.036  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:06:35.036  3277  3337 I jxcore-log: 
,03-23 13:06:35.037  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:35.037  3277  3337 I jxcore-log: 
03-23 13:06:35.038  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:35.038  3277  3337 I jxcore-log: 
,03-23 13:06:35.150  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:35.150  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:06:35.150  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:35.154  3277  3337 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-23 13:06:35.154  3277  3337 I jxcore-log: 
,03-23 13:06:35.155  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-23 13:06:35.155  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:35.155  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-23 13:06:35.158  3277  3337 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-23 13:06:35.158  3277  3337 I jxcore-log: 
,03-23 13:06:35.171  3277  3337 I jxcore-log: # setup
,03-23 13:06:35.171  3277  3337 I jxcore-log: 
,03-23 13:06:35.303  3277  3337 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,03-23 13:06:35.303  3277  3337 I jxcore-log: 
,03-23 13:06:35.374  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-23 13:06:35.374  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:35.374  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:35.374  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:35.381  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-23 13:06:35.381  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:35.381  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:35.381  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:35.387  2152  2168 D BtGatt.GattService: registerClient() - UUID=1688972c-6bf9-4e49-8590-2033962e1786,
,03-23 13:06:35.388  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=1688972c-6bf9-4e49-8590-2033962e1786, clientIf=5,
03-23 13:06:35.388  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:06:35.389  2152  2169 D BtGatt.GattService: start scan with filters
,03-23 13:06:35.391  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-23 13:06:35.391  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:35.391  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:06:35.391  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-23 13:06:35.396  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-23 13:06:35.397  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:35.397  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:06:35.397  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:06:35.398  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:35.398  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:35.399  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:35.399  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:35.400  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:35.400  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:35.400  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:06:35.402  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:35.402  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:35.402  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:35.402  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:06:35.405  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:35.405  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:35.407  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:35.407  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:35.411  2152  2216 D BtGatt.GattService: registerClient() - UUID=5ed73fda-4e34-489e-abda-25e51632a295
,03-23 13:06:35.411  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=5ed73fda-4e34-489e-abda-25e51632a295, clientIf=6
03-23 13:06:35.412  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:06:35.412  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:06:35.415  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising,
,03-23 13:06:35.417  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-23 13:06:35.420  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-23 13:06:35.421  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:06:35.421  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:35.421   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:35.424  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-23 13:06:35.424  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:35.424  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:06:35.424  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:35.425  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:06:35.425  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:06:35.425  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:06:35.425  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-23 13:06:35.425  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-23 13:06:35.426  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-23 13:06:35.426  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:35.426  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-23 13:06:35.426  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:35.426  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:06:35.426  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:35.426  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:35.426  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-23 13:06:35.426  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:35.426  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:06:35.426  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:06:35.426  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:35.428   822   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:35.429  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-23 13:06:35.429  3277  3337 I jxcore-log: 
03-23 13:06:35.430  3277  3337 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-23 13:06:35.430  3277  3337 I jxcore-log: 
03-23 13:06:35.431  3277  3804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:06:35.434  3277  3804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-23 13:06:35.436  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-23 13:06:35.436  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:06:35.436  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:06:35.436  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:06:35.436  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:35.437  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:35.437  3277  3337 I jxcore-log: 
03-23 13:06:35.438  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:06:35.438  3277  3337 I jxcore-log: 
,03-23 13:06:35.440  3277  3337 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-23 13:06:35.440  3277  3337 I jxcore-log: 
,03-23 13:06:35.446  3277  3337 I jxcore-log: # teardown
03-23 13:06:35.446  3277  3337 I jxcore-log: 
,03-23 13:06:35.841  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:06:35.842  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-23 13:06:35.842  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-23 13:06:35.842  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:35.847  2152  2168 D BtGatt.GattService: stopScan() - queue size =1,
,03-23 13:06:35.850  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:06:35.851  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-23 13:06:35.851  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:35.851  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:06:35.852  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:35.852  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:06:35.852  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:35.853  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-23 13:06:35.853  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:06:35.853  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:06:35.853  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:35.854  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-23 13:06:35.854  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:06:35.855  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:35.855  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:35.856  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:35.860  3277  3337 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-23 13:06:35.860  3277  3337 I jxcore-log: 
03-23 13:06:35.861  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-23 13:06:35.861  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:35.861  2152  2214 D BtGatt.GattService: current time is 213762463666
03-23 13:06:35.861  2152  2214 D BtGatt.GattService: Batch record : [-8, -101, 103, -8, -115, 67, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -46, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:06:35.862  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-23 13:06:35.863  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:35.865  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:06:35.866  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-23 13:06:35.866  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-23 13:06:35.866  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:06:35.866  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:06:35.868  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-23 13:06:35.868  3277  3804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:06:35.868  3277  3804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:06:35.868  3277  3804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:06:35.869  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-23 13:06:35.870  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:35.870  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:35.870  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-23 13:06:35.870  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-23 13:06:35.871  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-23 13:06:35.871  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-23 13:06:35.871  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-23 13:06:35.874  3277  3337 D BluetoothLeScanner: could not find callback wrapper
,03-23 13:06:35.874  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:06:35.874  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-23 13:06:35.877  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:35.878  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:35.882  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:06:35.882  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:06:35.883  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:35.884  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:06:35.884  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:35.884  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:06:35.885  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:06:35.885  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:06:35.885  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:35.885  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-23 13:06:35.885  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:35.886  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:35.886  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:35.886  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:35.886  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:35.887  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:35.887  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:35.887  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:06:35.894  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-23 13:06:35.894  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:06:35.894  3277  3337 I jxcore-log: 
,03-23 13:06:35.895   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:35.896  3277  3337 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-23 13:06:35.896  3277  3337 I jxcore-log: 
,03-23 13:06:35.901  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:06:35.902  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:35.902  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:35.903  3277  3337 I jxcore-log: # setup
03-23 13:06:35.903  3277  3337 I jxcore-log: ,
03-23 13:06:35.906  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-23 13:06:35.906  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:35.908  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-23 13:06:35.908  3277  3337 I jxcore-log: 
,03-23 13:06:35.910  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:35.910  3277  3337 I jxcore-log: 
,03-23 13:06:36.448  3277  3337 I jxcore-log: # 37. peerAvailabilityChange is called
03-23 13:06:36.448  3277  3337 I jxcore-log: 
,03-23 13:06:36.695  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
03-23 13:06:36.695  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:06:36.695  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:36.695  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:36.703  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-23 13:06:36.703  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:36.703  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:06:36.703  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:36.713  2152  2168 D BtGatt.GattService: registerClient() - UUID=1092c354-0088-485f-b22e-393c3649f9ce
,03-23 13:06:36.714  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=1092c354-0088-485f-b22e-393c3649f9ce, clientIf=5
,03-23 13:06:36.715  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:36.715  2152  2169 D BtGatt.GattService: start scan with filters
,03-23 13:06:36.719  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:36.720  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:36.720  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:06:36.721  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:06:36.721  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:06:36.721  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:06:36.721  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:36.722  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:06:36.722  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:36.722  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:36.722  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:36.723  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:36.723  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:06:36.728  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:36.728  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:36.731  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:36.731  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:36.732  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:36.732  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:36.735  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-23 13:06:36.735  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:36.737  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:36.738  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:36.739  2152  2216 D BtGatt.GattService: registerClient() - UUID=841683d3-f642-4bd1-875b-1873d05aa1b8
03-23 13:06:36.740  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=841683d3-f642-4bd1-875b-1873d05aa1b8, clientIf=6
,03-23 13:06:36.741  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:06:36.742  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:06:36.748  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:36.751  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:06:36.754  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:36.756  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:36.756  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:36.757   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:36.764  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:36.765  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:36.765  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:06:36.765  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:36.766  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:06:36.766  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:06:36.766  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:06:36.767  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:06:36.767  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:36.767  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:36.768   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:36.768  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:06:36.768  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:36.768  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:06:36.768  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:36.768  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:06:36.768  3277  3805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-23 13:06:36.769  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:36.769  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:36.769  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:06:36.769  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:36.770  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-23 13:06:36.770  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:06:36.773  3277  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:06:36.790  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-23 13:06:36.790  3277  3337 I jxcore-log: 
,03-23 13:06:36.801  3277  3337 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error,
03-23 13:06:36.801  3277  3337 I jxcore-log: 
,03-23 13:06:36.805  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-23 13:06:36.805  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:36.805  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-23 13:06:36.805  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:06:36.805  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:06:36.807  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:36.807  3277  3337 I jxcore-log: 
03-23 13:06:36.808  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:06:36.808  3277  3337 I jxcore-log: 
03-23 13:06:36.809  3277  3337 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-23 13:06:36.809  3277  3337 I jxcore-log: 
,03-23 13:06:37.744  2152  2152 D BtGatt.ScanManager: awakened up at time 215645
,03-23 13:06:37.747  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:37.756  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-23 13:06:37.756  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:37.757  2152  2214 D BtGatt.GattService: current time is 215657926947
03-23 13:06:37.757  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -75, 72, -76, 101, -39, 89, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -103, 4, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0]
03-23 13:06:37.757  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:06:37.758  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:37.759  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-23 13:06:37.761  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-23 13:06:37.761  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-23 13:06:37.761  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-23 13:06:37.762  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-23 13:06:37.764  3277  3337 I jxcore-log: ok 153 peers must be an array
03-23 13:06:37.764  3277  3337 I jxcore-log: 
03-23 13:06:37.764  3277  3337 I jxcore-log: ok 154 peers must not be zero-length
03-23 13:06:37.764  3277  3337 I jxcore-log: 
03-23 13:06:37.764  3277  3337 I jxcore-log: ok 155 peer must have peerIdentifier
03-23 13:06:37.764  3277  3337 I jxcore-log: 
03-23 13:06:37.765  3277  3337 I jxcore-log: ok 156 peerIdentifier must be a string
03-23 13:06:37.765  3277  3337 I jxcore-log: 
03-23 13:06:37.765  3277  3337 I jxcore-log: ok 157 peer must have peerAvailable
03-23 13:06:37.765  3277  3337 I jxcore-log: 
03-23 13:06:37.765  3277  3337 I jxcore-log: ok 158 peer must have pleaseConnect
03-23 13:06:37.765  3277  3337 I jxcore-log: 
,03-23 13:06:37.774  3277  3337 I jxcore-log: # teardown
03-23 13:06:37.774  3277  3337 I jxcore-log: 
,03-23 13:06:38.771  2152  2152 D BtGatt.ScanManager: awakened up at time 216672
,03-23 13:06:38.773  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:38.785  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-23 13:06:38.785  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:38.785  2152  2214 D BtGatt.GattService: current time is 216686543457
03-23 13:06:38.785  2152  2214 D BtGatt.GattService: Batch record : [-75, 72, -76, 101, -39, 89, 1, -128, -79, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -61, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-23 13:06:38.786  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-23 13:06:38.787  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:06:38.790  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-23 13:06:38.791  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-23 13:06:38.807  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:06:38.808  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-23 13:06:38.808  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-23 13:06:38.808  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:38.812  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:38.812  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:06:38.813  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:38.813  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:38.813  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:38.813  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-23 13:06:38.813  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:06:38.813  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:38.814  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:06:38.814  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-23 13:06:38.814  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:38.816  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:38.816  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:38.816  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:38.816  3277  3337 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-23 13:06:38.816  3277  3337 I jxcore-log: 
03-23 13:06:38.817  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:06:38.817  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-23 13:06:38.817  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-23 13:06:38.817  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:06:38.817  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:06:38.818  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:38.818  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:38.818  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-23 13:06:38.819  3277  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:06:38.819  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:38.819  3277  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:06:38.819  3277  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:06:38.819  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-23 13:06:38.819  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:38.820  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-23 13:06:38.820  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:06:38.820  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:38.820  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-23 13:06:38.820  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:06:38.821  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:06:38.821  3277  3337 D BluetoothLeScanner: could not find callback wrapper
,03-23 13:06:38.821  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:38.821  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:06:38.821  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:38.825  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-23 13:06:38.825  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:38.828  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:06:38.828  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:06:38.829  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:38.830  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:38.830  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:06:38.830  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-23 13:06:38.830  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-23 13:06:38.831  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-23 13:06:38.831  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:38.831  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:06:38.831  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:38.832  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:38.832  3277  3337 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-23 13:06:38.832  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:38.833  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:38.833  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:38.833  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:06:38.838  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:06:38.838  3277  3337 I jxcore-log: 
03-23 13:06:38.839  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-23 13:06:38.840   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:38.844  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-23 13:06:38.845  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:38.845  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:38.848  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-23 13:06:38.848  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:38.848  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:38.848  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:38.848  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:38.849  3277  3337 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown,
03-23 13:06:38.849  3277  3337 I jxcore-log: 
,03-23 13:06:38.856  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:38.856  3277  3337 I jxcore-log: 
03-23 13:06:38.856  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:38.856  3277  3337 I jxcore-log: 
,03-23 13:06:38.857  3277  3337 I jxcore-log: # setup
03-23 13:06:38.857  3277  3337 I jxcore-log: 
,03-23 13:06:39.070  3277  3337 I jxcore-log: # 38. Can connect to a remote peer
03-23 13:06:39.070  3277  3337 I jxcore-log: ,
,03-23 13:06:39.236  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 52144, start advertisements: true,
03-23 13:06:39.236  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:39.236  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:39.236  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:39.241  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-23 13:06:39.241  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:39.241  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:39.241  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:06:39.247  2152  2168 D BtGatt.GattService: registerClient() - UUID=c0edd1e1-765c-402c-90e6-e853792e3180
,03-23 13:06:39.248  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=c0edd1e1-765c-402c-90e6-e853792e3180, clientIf=5
03-23 13:06:39.248  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:39.249  2152  2169 D BtGatt.GattService: start scan with filters
,03-23 13:06:39.251  2152  2225 D BtGatt.ScanManager: handling starting scan,
03-23 13:06:39.251  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-23 13:06:39.251  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:39.252  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:06:39.252  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:06:39.252  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:39.252  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-23 13:06:39.253  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:39.253  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:39.253  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-23 13:06:39.253  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:06:39.253  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:39.254  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:39.254  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:39.254  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:06:39.255  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:39.255  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:39.255  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:06:39.255  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:39.258  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-23 13:06:39.258  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:39.260  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:39.260  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:39.262  2152  2216 D BtGatt.GattService: registerClient() - UUID=83a3c335-03bc-424f-8466-45b19e80b47e
03-23 13:06:39.263  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=83a3c335-03bc-424f-8466-45b19e80b47e, clientIf=6,
03-23 13:06:39.263  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:06:39.264  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-23 13:06:39.270  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:39.273  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:06:39.275  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-23 13:06:39.276  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:39.276  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:39.276   822  1391 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:39.279  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:39.280  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:39.280  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-23 13:06:39.280  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:39.280  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-23 13:06:39.281  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-23 13:06:39.281  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:06:39.281  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:06:39.281  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK,
,03-23 13:06:39.281  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:39.281  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:06:39.281  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:39.282  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-23 13:06:39.282  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:39.282  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:06:39.282  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:39.282  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:39.282  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-23 13:06:39.282  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:39.283  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:39.283  3277  3337 I jxcore-log: 
,03-23 13:06:39.283  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:06:39.283  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:39.285  3277  3337 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
,03-23 13:06:39.285  3277  3337 I jxcore-log: 
03-23 13:06:39.290  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 52144, start advertisements: false
03-23 13:06:39.290  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:06:39.290  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-23 13:06:39.290  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:06:39.290  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:39.290   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:06:39.291  3277  3806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:06:39.294  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:39.294  3277  3337 I jxcore-log: 
,03-23 13:06:39.295  3277  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:06:39.296  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:06:39.296  3277  3337 I jxcore-log: 
,03-23 13:06:39.299  3277  3337 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-23 13:06:39.299  3277  3337 I jxcore-log: 
,03-23 13:06:39.800  2152  2152 D BtGatt.ScanManager: awakened up at time 217701
,03-23 13:06:39.803  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:39.813  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-23 13:06:39.813  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:39.813  2152  2214 D BtGatt.GattService: current time is 217714658040
,03-23 13:06:39.814  2152  2214 D BtGatt.GattService: Batch record : [81, -84, 23, -61, -22, 116, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:06:39.814  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:39.815  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:39.818  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-23 13:06:39.818  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-23 13:06:39.819  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-23 13:06:39.820  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-23 13:06:39.828  3277  3337 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-23 13:06:39.828  3277  3337 I jxcore-log: 
,03-23 13:06:39.840  3277  3337 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-23 13:06:39.840  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:06:39.844  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-23 13:06:39.846  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-23 13:06:39.846  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-23 13:06:39.847  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-23 13:06:39.847  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-23 13:06:39.847  3277  3337 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-23 13:06:39.850  3277  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 356)
03-23 13:06:39.850  3277  3807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:06:39.853  3277  3337 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-23 13:06:39.853  3277  3337 I jxcore-log: 
03-23 13:06:39.854  2152  2216 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-23 13:06:41.714  2152  2226 W bt-btif : info:x10
03-23 13:06:41.714  2152  2214 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-23 13:06:41.714  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL,
,03-23 13:06:41.784  2152  2226 W bt-sdp  : process_service_search_attr_rsp
,03-23 13:06:42.899  2152  2214 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-23 13:06:42.908  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-23 13:06:42.908  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-23 13:06:42.914  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,03-23 13:06:42.914  2152  2215 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-23 13:06:42.935  2152  2226 W bt-btif : info:x10
03-23 13:06:42.935  2152  2214 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-23 13:06:42.936  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-23 13:06:43.009   822   856 I ActivityManager: Start proc 3809:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-23 13:06:43.125   822   860 D BluetoothManagerService: Message: 20
,03-23 13:06:43.126   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c11d253:true
,03-23 13:06:43.129   822  1412 I ActivityManager: Killing 3577:com.android.chrome/u0a40 (adj 15): empty #17
03-23 13:06:43.130  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-23 13:06:43.131  2152  2215 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-23 13:06:43.243  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-23 13:06:43.244  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-23 13:06:43.344  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-23 13:06:43.444  2152  2215 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-23 13:06:44.818  2152  2152 D BtGatt.ScanManager: awakened up at time 222719
,03-23 13:06:44.820  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:44.825  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-23 13:06:44.825  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:44.825  2152  2214 D BtGatt.GattService: current time is 222726772465
03-23 13:06:44.826  2152  2214 D BtGatt.GattService: Batch record : [81, -84, 23, -61, -22, 116, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:06:44.826  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:44.827  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:06:44.832  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-23 13:06:44.832  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-23 13:06:45.622  1233  1489 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-23 13:06:45.622  1233  1489 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-23 13:06:45.660  1261  1261 I ConfigService: onCreate
,03-23 13:06:47.716  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-23 13:06:47.765  2152  2226 W bt-btif : info:x10,
03-23 13:06:47.766  2152  2214 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-23 13:06:47.766  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-23 13:06:48.024  2152  2214 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-23 13:06:48.030  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-23 13:06:48.031  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-23 13:06:48.035  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-23 13:06:48.036  2152  2215 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-23 13:06:48.135  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-23 13:06:48.135  2152  2215 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-23 13:06:48.138  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-23 13:06:48.149  2152  2215 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-23 13:06:48.175  2152  2226 W bt-btif : new conn_srvc id:26, app_id:255
03-23 13:06:48.175  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-23 13:06:48.175  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-23 13:06:48.176  3277  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-23 13:06:48.178  3277  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 357)
,03-23 13:06:48.179  3277  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-23 13:06:48.179   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:48.182  3277  3831 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 357),
,03-23 13:06:48.182  3277  3806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-23 13:06:48.186  3277  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:06:48.188  3277  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 357)
,03-23 13:06:48.191  3277  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-23 13:06:48.191  3277  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 357)
,03-23 13:06:48.191  3277  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 357
03-23 13:06:48.191  3277  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 357)
,03-23 13:06:48.191  3277  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-23 13:06:48.192  3277  3831 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 357)
03-23 13:06:48.193  3277  3277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-23 13:06:48.193  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-23 13:06:48.194  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-23 13:06:48.196  3277  3277 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-23 13:06:48.196  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-23 13:06:48.197  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:06:48.197  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:06:48.197  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:06:48.197  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:06:48.197  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:06:48.197  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:06:48.201  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-23 13:06:48.202  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-23 13:06:48.207  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:06:48.207  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:06:48.209  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:48.210  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:48.210  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:48.210  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:06:48.210  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:06:48.211  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:48.211  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:48.211  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:48.212  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:48.212  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:06:48.220  2152  2168 D BtGatt.GattService: registerClient() - UUID=f92508db-cb5c-46e0-bcbe-cb8b06b2dc68
,03-23 13:06:48.220  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=f92508db-cb5c-46e0-bcbe-cb8b06b2dc68, clientIf=6,
03-23 13:06:48.221  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:06:48.223  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:06:48.228  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:48.232  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:06:48.234  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:48.235  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:48.236  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:48.237  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:06:48.237  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:48.237  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:48.237  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:48.237  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:48.237  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:48.238  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:06:48.239  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:48.239  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.240  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:48.241  2152  2216 D BtGatt.GattService: registerClient() - UUID=33090cc4-09ba-4381-90c3-322ecb6f71f1
03-23 13:06:48.241  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:48.241  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.241  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=33090cc4-09ba-4381-90c3-322ecb6f71f1, clientIf=5
03-23 13:06:48.242  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:48.242  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:48.242  2152  2168 D BtGatt.GattService: start scan with filters
,03-23 13:06:48.244  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:06:48.244  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:06:48.245  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-23 13:06:48.245  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.245  2152  2214 D BtGatt.GattService: current time is 226146517724
03-23 13:06:48.245  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 44, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 81, -84, 23, -61, -22, 116, 1, -128, -73, 43, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-23 13:06:48.246  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:48.246  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:48.247  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:48.247  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-23 13:06:48.249  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-23 13:06:48.249  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:06:48.250  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:48.251  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:06:48.251  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:06:48.251  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:06:48.251  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:06:48.251  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-23 13:06:48.251  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:06:48.251  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:48.251  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:48.251  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:06:48.252  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:06:48.254  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:48.254  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.255  2152  2169 D BtGatt.GattService: registerClient() - UUID=b94f72eb-6fb1-467f-bff5-a1f45cac4751
,03-23 13:06:48.255  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:48.255  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.255  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:48.256  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:48.256  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=b94f72eb-6fb1-467f-bff5-a1f45cac4751, clientIf=6
03-23 13:06:48.256  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:06:48.257  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:48.258  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.258  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-23 13:06:48.259  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:48.259  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.261  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:48.264  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:06:48.266  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:48.267  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:48.268  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:06:48.269  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-23 13:06:48.269  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:48.269  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:48.269  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:06:48.269  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:48.269  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:48.269  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:06:48.270  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:48.270  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.270  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:48.272  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:48.272  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:48.273  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:48.273  2152  2168 D BtGatt.GattService: registerClient() - UUID=c4d8382d-0587-48a1-b0b6-3f38da3926e9
03-23 13:06:48.273  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=c4d8382d-0587-48a1-b0b6-3f38da3926e9, clientIf=5
,03-23 13:06:48.274  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-23 13:06:48.274  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:06:48.274  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:48.274  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:06:48.277  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:06:48.277  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:06:48.277  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:48.279  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:48.280  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:06:48.280  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.281  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:48.281  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:48.281  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:48.281  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:48.281  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:48.283  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-23 13:06:48.283  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.284  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-23 13:06:48.284  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:06:48.285  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:48.286  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:06:48.286  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:06:48.286  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:06:48.286  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:06:48.286  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:48.286  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:48.286  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-23 13:06:48.286  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.286  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:48.287  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:06:48.287  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:06:48.290  2152  2168 D BtGatt.GattService: registerClient() - UUID=65f946b5-098e-4668-a39f-0215c63bd3ac
03-23 13:06:48.291  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=65f946b5-098e-4668-a39f-0215c63bd3ac, clientIf=6
03-23 13:06:48.291  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:06:48.292  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-23 13:06:48.294  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:06:48.297  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:06:48.299  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:48.300  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:06:48.301  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:06:48.302  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:48.302  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:48.302  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:06:48.302  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:48.302  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:48.302  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:06:48.302  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:06:48.303  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:48.303  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:48.303  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:48.305  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:48.305  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.305  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:48.306  2152  2169 D BtGatt.GattService: registerClient() - UUID=1fbd8b1a-89cb-411a-8d9e-e1fdf046a24a
,03-23 13:06:48.307  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=1fbd8b1a-89cb-411a-8d9e-e1fdf046a24a, clientIf=5
,03-23 13:06:48.307  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:06:48.307  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-23 13:06:48.307  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.307  2152  2216 D BtGatt.GattService: start scan with filters
03-23 13:06:48.307  2152  2214 D BtGatt.GattService: current time is 226208601422
03-23 13:06:48.307  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -56, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:06:48.308  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:06:48.309  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:06:48.309  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:06:48.310  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-23 13:06:48.310  3277  3277 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-23 13:06:48.310  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:06:48.310  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:48.310  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:06:48.310  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:06:48.310  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-23 13:06:48.311  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:48.311  3277  3832 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 358)
,03-23 13:06:48.313  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:06:48.313  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.314  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:48.314  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:48.314  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:06:48.314  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:06:48.316  3277  3832 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 52144,
03-23 13:06:48.316  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:48.316  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:48.318  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-23 13:06:48.318  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:48.320  3277  3832 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-23 13:06:48.321  3277  3832 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-23 13:06:48.321  3277  3832 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-23 13:06:48.323  3277  3834 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 359, name: Sender),
03-23 13:06:48.323  3277  3832 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 358)
03-23 13:06:48.323  3277  3832 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 358)
03-23 13:06:48.324  3277  3835 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 360, name: Receiver)
,03-23 13:06:49.720  1261  1658 I art     : Explicit concurrent mark sweep GC freed 39757(2MB) AllocSpace objects, 15(1577KB) LOS objects, 37% free, 26MB/42MB, paused 1.403ms total 37.591ms
,03-23 13:06:49.740  3511  3838 V KeepSync: Connecting to GoogleApiClient
,03-23 13:06:49.784  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-23 13:06:49.784  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:49.784  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:49.784  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:49.788  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:49.799  3106  3837 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-23 13:06:49.799  3106  3837 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jdm.a(PG:82)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jcs.o(PG:406)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jcn.a(PG:1379)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jcs.i(PG:143)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at blb.a(PG:3937)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at czp.a(PG:18188)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at czp.a(PG:9081)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at czq.run(PG:1686)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:06:49.799  3106  3837 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jdj.a(PG:4091)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jdj.a(PG:1125)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jdm.a(PG:77)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	... 12 more
03-23 13:06:49.799  3106  3837 E HttpOperation: Caused by: faj: BadAuthentication
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at fal.a(PG:38)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	at jdj.a(PG:4089)
03-23 13:06:49.799  3106  3837 E HttpOperation: 	... 14 more
,03-23 13:06:49.803  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
03-23 13:06:49.803  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:49.803  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-23 13:06:49.803  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:49.809  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: Handling authorization failure
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-23 13:06:49.826  1773  3840 E ClientConnectionOperation: 	... 7 more
,03-23 13:06:49.829  3511  3838 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-23 13:06:49.830  3511  3838 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:06:49.839  3511  3838 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-23 13:06:49.840  3511  3838 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:06:49.840  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-23 13:06:49.841  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:49.841  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:49.841  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:49.844  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:49.855  3106  3837 E HttpOperation: [getmobileexperiments] Unexpected exception
03-23 13:06:49.855  3106  3837 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jdm.a(PG:82)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jcs.o(PG:406)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jcn.a(PG:1379)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jcs.i(PG:143)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at hec.a(PG:42)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at hee.a(PG:102)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at czr.a(PG:65)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at kka.a(PG:108)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at czp.a(PG:19176)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at czp.a(PG:9081)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at czq.run(PG:1686)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:06:49.855  3106  3837 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jdj.a(PG:4091)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jdj.a(PG:1125)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jdm.a(PG:77)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	... 15 more
03-23 13:06:49.855  3106  3837 E HttpOperation: Caused by: faj: BadAuthentication
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at fal.a(PG:38),
03-23 13:06:49.855  3106  3837 E HttpOperation: 	at jdj.a(PG:4089)
03-23 13:06:49.855  3106  3837 E HttpOperation: 	... 17 more
03-23 13:06:49.855  3106  3837 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-23 13:06:49.855  3106  3837 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jdm.a(PG:82)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jcs.o(PG:406)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jcn.a(PG:1379)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jcs.i(PG:143)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at hec.a(PG:42)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at hee.a(PG:102)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at czr.a(PG:65)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	,at kka.a(PG:108)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at czp.a(PG:19176)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at czp.a(PG:9081)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at czq.run(PG:1686)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jdj.a(PG:4091)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jdj.a(PG:1125)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jdm.a(PG:77)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	... 15 more
03-23 13:06:49.855  3106  3837 E ExperimentLoader: Caused by: faj: BadAuthentication
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at fal.a(PG:38)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	at jdj.a(PG:4089)
03-23 13:06:49.855  3106  3837 E ExperimentLoader: 	... 17 more
,03-23 13:06:49.886  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-23 13:06:49.886  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:49.886  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:49.886  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:49.890  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:49.926  3511  3838 E KeepSync: IOException
03-23 13:06:49.926  3511  3838 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-23 13:06:49.926  3511  3838 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-23 13:06:49.926  3511  3838 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-23 13:06:49.926  3511  3838 E KeepSync: 	... 10 more
03-23 13:06:49.926  3511  3838 W KeepSync: Sync result 2
,03-23 13:06:49.932   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 199399, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:06:49.968   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 198989, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:06:49.996   822   822 I art     : Explicit concurrent mark sweep GC freed 30718(1454KB) AllocSpace objects, 8(599KB) LOS objects, 32% free, 33MB/49MB, paused 1.270ms total 53.161ms
,03-23 13:06:50.001  3459  3843 I BooksSync: Starting books sync for 61035162, extras: ade
,03-23 13:06:50.023  3459  3844 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-23 13:06:50.048  1261  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-23 13:06:50.048  1261  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-23 13:06:50.048  1261  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:06:50.048  1261  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:50.051  1261  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:50.129  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-23 13:06:50.129  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:06:50.129  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:06:50.129  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:06:50.136  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:06:50.152  3459  3844 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-23 13:06:50.154  3459  3843 E BooksSync: Soft error
03-23 13:06:50.154  3459  3843 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:06:50.154  3459  3843 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-23 13:06:50.154  3459  3843 E BooksSync: Sync error
03-23 13:06:50.154  3459  3843 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:06:50.154  3459  3843 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-23 13:06:50.154  3459  3843 I BooksSync: Finished books sync
,03-23 13:06:50.160   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200282, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:06:50.744  1261  1261 I ConfigService: onDestroy
,03-23 13:06:51.740  2152  2226 W bt-btif : new conn_srvc id:26, app_id:255,
03-23 13:06:51.740  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-23 13:06:51.740  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-23 13:06:51.741  3277  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-23 13:06:51.741  3277  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 361)
,03-23 13:06:51.742  3277  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:06:51.743   822  1391 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:51.746  3277  3806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-23 13:06:51.747  3277  3845 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 361)
,03-23 13:06:51.752  3277  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-23 13:06:51.808  2152  2226 W bt-btif : new conn_srvc id:26, app_id:1,
03-23 13:06:51.808  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-23 13:06:51.808  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-23 13:06:51.808  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-23 13:06:51.810  3277  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 356)
03-23 13:06:51.810  3277  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 356)
,03-23 13:06:51.811  3277  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 362)
03-23 13:06:51.811  3277  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 362)
03-23 13:06:51.812  3277  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 356)
,03-23 13:06:51.814  3277  3846 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 362)
,03-23 13:06:52.014  3277  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 361)
,03-23 13:06:52.018  3277  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:06:52.019  3277  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 361)
03-23 13:06:52.019  3277  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 361
03-23 13:06:52.020  3277  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 361)
03-23 13:06:52.020  3277  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:06:52.021  3277  3277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:06:52.022  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-23 13:06:52.022  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-23 13:06:52.023  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-23 13:06:52.023  3277  3277 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-23 13:06:52.024  3277  3845 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 361)
03-23 13:06:52.026  3277  3847 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 363)
,03-23 13:06:52.034  3277  3847 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 52144
,03-23 13:06:52.034  3277  3847 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-23 13:06:52.034  3277  3847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-23 13:06:52.035  3277  3847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-23 13:06:52.038  3277  3849 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Sender)
,03-23 13:06:52.038  3277  3847 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 363)
03-23 13:06:52.038  3277  3847 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 363)
,03-23 13:06:52.043  3277  3850 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Receiver)
,03-23 13:06:52.080  3277  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 362)
,03-23 13:06:52.084  3277  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:06:52.084  3277  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 356)
,03-23 13:06:52.084  3277  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 356)
,03-23 13:06:52.085  3277  3846 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 362)
,03-23 13:06:52.085  3277  3277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-23 13:06:52.086  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:06:52.086  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-23 13:06:52.088  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-23 13:06:52.089  3277  3277 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-23 13:06:52.091  3277  3851 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 366)
,03-23 13:06:52.093  3277  3851 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45159
,03-23 13:06:52.093  3277  3851 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-23 13:06:52.094  3277  3851 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 45159 (peer ID: E0:DB:10:14:E2:C0)
,03-23 13:06:52.094  3277  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-23 13:06:52.101  3277  3337 I jxcore-log: INFO testThaliMobileNative: 
03-23 13:06:52.101  3277  3337 I jxcore-log: 
,03-23 13:06:52.101  3277  3337 I jxcore-log: ok 163 Must have listeningPort
03-23 13:06:52.101  3277  3337 I jxcore-log: 
03-23 13:06:52.102  3277  3337 I jxcore-log: ok 164 listeningPort must be a number
03-23 13:06:52.102  3277  3337 I jxcore-log: 
,03-23 13:06:52.102  3277  3337 I jxcore-log: ok 165 Connection must have clientPort
03-23 13:06:52.102  3277  3337 I jxcore-log: 
03-23 13:06:52.103  3277  3337 I jxcore-log: ok 166 clientPort must be a number
03-23 13:06:52.103  3277  3337 I jxcore-log: 
,03-23 13:06:52.103  3277  3337 I jxcore-log: ok 167 Connection must have serverPort
03-23 13:06:52.103  3277  3337 I jxcore-log: 
03-23 13:06:52.103  3277  3337 I jxcore-log: ok 168 serverPort must be a number
03-23 13:06:52.103  3277  3337 I jxcore-log: 
03-23 13:06:52.104  3277  3337 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-23 13:06:52.104  3277  3337 I jxcore-log: 
,03-23 13:06:52.104  3277  3337 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-23 13:06:52.104  3277  3337 I jxcore-log: 
,03-23 13:06:52.110  3277  3337 I jxcore-log: # teardown
03-23 13:06:52.110  3277  3337 I jxcore-log: 
,03-23 13:06:52.847  2152  2390 W bt-btif : invalid rfc slot id: 10
,03-23 13:06:52.898  2152  2390 W bt-btif : invalid rfc slot id: 12
,03-23 13:06:52.899  3277  3850 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
03-23 13:06:52.899  3277  3850 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,03-23 13:06:52.900  3277  3850 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-23 13:06:52.900  3277  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 363
03-23 13:06:52.900  3277  3850 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 363)
03-23 13:06:52.900  3277  3850 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-23 13:06:52.901  3277  3850 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-23 13:06:52.902  3277  3850 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-23 13:06:52.902  3277  3850 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-23 13:06:52.903  3277  3850 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364
03-23 13:06:52.903  3277  3850 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 363)
03-23 13:06:52.904  3277  3849 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Sender): Socket closed,
03-23 13:06:52.905  3277  3849 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Sender)
03-23 13:06:52.907  3277  3850 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 363)
,03-23 13:06:52.908  3277  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,03-23 13:06:52.911  3277  3850 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Receiver)
,03-23 13:06:52.927  3277  3337 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
,03-23 13:06:52.927  3277  3337 I jxcore-log: 
,03-23 13:06:52.928  3277  3337 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-23 13:06:52.928  3277  3337 I jxcore-log: 
,03-23 13:06:53.323  2152  2152 D BtGatt.ScanManager: awakened up at time 231223,
,03-23 13:06:53.324  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:06:53.329  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-23 13:06:53.330  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:53.330  2152  2214 D BtGatt.GattService: current time is 231231426159
03-23 13:06:53.330  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 62, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -108, 81, 95, -9, -21, 104, 1, -128, -93, 80, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -102, 73, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-23 13:06:53.331  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:53.332  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:53.333  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-23 13:06:53.336  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-23 13:06:53.336  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-23 13:06:53.450  2152  2390 W bt-btif : invalid rfc slot id: 9
03-23 13:06:53.450  3277  3835 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Receiver): bt socket closed, read return: -1
,03-23 13:06:53.451  3277  3835 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,03-23 13:06:53.451  3277  3835 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-23 13:06:53.451  3277  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 358
03-23 13:06:53.451  3277  3835 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
,03-23 13:06:53.452  3277  3835 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-23 13:06:53.452  3277  3835 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-23 13:06:53.452  3277  3835 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 360
03-23 13:06:53.452  3277  3835 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-23 13:06:53.452  3277  3835 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 359
,03-23 13:06:53.452  3277  3835 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 358)
03-23 13:06:53.453  3277  3835 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 358)
03-23 13:06:53.453  3277  3834 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Sender): Socket closed
03-23 13:06:53.453  3277  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-23 13:06:53.453  3277  3834 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 359, name: Sender)
03-23 13:06:53.454  3277  3835 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 360, name: Receiver)
,03-23 13:06:53.466  3277  3337 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-23 13:06:53.466  3277  3337 I jxcore-log: 
,03-23 13:06:53.468  3277  3337 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-23 13:06:53.468  3277  3337 I jxcore-log: 
,03-23 13:06:53.645  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:06:53.645  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-23 13:06:53.645  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,03-23 13:06:53.645  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:06:53.650  2152  2169 D BtGatt.GattService: stopScan() - queue size =1,
03-23 13:06:53.651  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:06:53.651  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:53.652  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:06:53.652  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:06:53.652  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:06:53.652  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:06:53.652  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:53.652  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:06:53.652  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-23 13:06:53.652  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:53.654  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:06:53.654  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:53.654  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:06:53.655  3277  3337 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-23 13:06:53.655  3277  3337 I jxcore-log: 
,03-23 13:06:53.656  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:06:53.656  3277  3337 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-23 13:06:53.656  3277  3337 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 366)
03-23 13:06:53.656  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 366)
,03-23 13:06:53.656  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:06:53.657  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:53.657  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-23 13:06:53.657  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 366)
,03-23 13:06:53.657  3277  3337 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 366)
03-23 13:06:53.657  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:06:53.657  3277  3851 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 366)
03-23 13:06:53.658  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-23 13:06:53.658  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:06:53.658  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:06:53.658  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:06:53.659  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:06:53.659  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:53.662  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:06:53.662  3277  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:06:53.662  3277  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:06:53.663  3277  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:06:53.663  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-23 13:06:53.663  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:06:53.663  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:06:53.663  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-23 13:06:53.663  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:06:53.663  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:06:53.663  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:06:53.664  3277  3337 D BluetoothLeScanner: could not find callback wrapper
03-23 13:06:53.665  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:06:53.665  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:06:53.667  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:06:53.668  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:06:53.671  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:06:53.671  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:06:53.672  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:06:53.672  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:06:53.672  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:06:53.672  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:06:53.673  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:06:53.673  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:06:53.673  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:53.673  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:06:53.673  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:06:53.673  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:06:53.673  3277  3337 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-23 13:06:53.674  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:06:53.674  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:06:53.674  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:06:53.674  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:06:53.677  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:06:53.677  3277  3337 I jxcore-log: 
,03-23 13:06:53.681  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:06:53.682   822  1346 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:53.692  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-23 13:06:53.694  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:53.694  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:06:53.698  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-23 13:06:53.698  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:06:53.698  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:53.699  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:06:53.699  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:06:53.700  3277  3337 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown
03-23 13:06:53.700  3277  3337 I jxcore-log: 
,03-23 13:06:53.705  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:53.705  3277  3337 I jxcore-log: 
,03-23 13:06:53.706  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:06:53.706  3277  3337 I jxcore-log: 
,03-23 13:06:53.707  3277  3337 I jxcore-log: # setup
03-23 13:06:53.707  3277  3337 I jxcore-log: 
,03-23 13:06:53.767  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,03-23 13:06:53.842  3277  3337 I jxcore-log: # 39. Can shift large amounts of data
03-23 13:06:53.842  3277  3337 I jxcore-log: 
,03-23 13:06:54.254  2152  2226 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
03-23 13:06:54.254  2152  2226 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x46
,03-23 13:06:54.259  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 38094, start advertisements: true
03-23 13:06:54.259  3277  3337 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-23 13:06:54.259  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:54.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:06:54.261  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:06:54.261  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:06:54.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:06:54.271  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-23 13:06:54.271  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:06:54.271  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:06:54.271  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-23 13:06:54.280  2152  2168 D BtGatt.GattService: registerClient() - UUID=12e1523c-26f9-4715-8489-f0d9b9173c6d,
03-23 13:06:54.281  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=12e1523c-26f9-4715-8489-f0d9b9173c6d, clientIf=5
03-23 13:06:54.285  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:06:54.285  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:06:54.287  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:06:54.288  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-23 13:06:54.288  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:06:54.288  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:06:54.288  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-23 13:06:54.288  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:54.288  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:06:54.289  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:06:54.289  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:06:54.289  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-23 13:06:54.289  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:06:54.290  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-23 13:06:54.290  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:54.290  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:06:54.290  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:06:54.290  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:06:54.290  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:54.290  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:06:54.290  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:06:54.292  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:06:54.292  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:06:54.293  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:06:54.293  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:54.295  2152  2216 D BtGatt.GattService: registerClient() - UUID=66142ab5-328c-44ec-9100-3037e2752c3d
,03-23 13:06:54.295  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=66142ab5-328c-44ec-9100-3037e2752c3d, clientIf=6
03-23 13:06:54.296  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:06:54.297  2152  2224 D BtGatt.AdvertiseManager: message : 0,
,03-23 13:06:54.310  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising,
,03-23 13:06:54.312  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-23 13:06:54.314  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:06:54.314  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:06:54.314  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:06:54.315   822  1357 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:54.318  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:06:54.318  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:06:54.318  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:06:54.318  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:06:54.319  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-23 13:06:54.319  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:06:54.319  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-23 13:06:54.319  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:06:54.320  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:54.320  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-23 13:06:54.320  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-23 13:06:54.320  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:06:54.320  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:06:54.321  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:06:54.321   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:06:54.321  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:06:54.321  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:06:54.321  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:06:54.321  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:06:54.321  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:06:54.322  3277  3853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-23 13:06:54.322  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:06:54.322  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:06:54.322  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:54.322  3277  3337 I jxcore-log: 
03-23 13:06:54.324  3277  3337 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-23 13:06:54.324  3277  3337 I jxcore-log: 
03-23 13:06:54.324  3277  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-23 13:06:54.326  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 38094, start advertisements: false
,03-23 13:06:54.326  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:06:54.326  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-23 13:06:54.327  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:06:54.327  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:06:54.328  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:06:54.328  3277  3337 I jxcore-log: 
03-23 13:06:54.328  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:06:54.328  3277  3337 I jxcore-log: 
,03-23 13:06:54.329  3277  3337 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error
03-23 13:06:54.329  3277  3337 I jxcore-log: 
,03-23 13:06:55.879  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2f1aeb4 rs_disc_pending=0
03-23 13:06:55.879  2152  2226 W bt-btif : bta_dm_check_av:0
,03-23 13:06:55.879  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-23 13:06:56.920  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-23 13:06:56.926  2152  2152 D BluetoothMapService: onReceive
,03-23 13:06:56.952   822   860 D BluetoothManagerService: Message: 20
,03-23 13:06:56.953   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e2e5814:true
,03-23 13:06:56.971  1513  1513 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-23 13:06:56.974  1513  1513 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-23 13:06:57.861  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2f1b07c rs_disc_pending=0
,03-23 13:06:57.861  2152  2226 W bt-btif : bta_dm_check_av:0
,03-23 13:06:57.862  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-23 13:06:57.995  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-23 13:06:58.002  2152  2152 D BluetoothMapService: onReceive,
,03-23 13:06:58.032  1513  1513 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-23 13:06:58.036  1513  1513 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-23 13:06:58.916  2152  2152 D BtGatt.ScanManager: awakened up at time 236817
,03-23 13:06:58.920  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-23 13:06:58.931  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
03-23 13:06:58.931  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:06:58.932  2152  2214 D BtGatt.GattService: current time is 236833206209
,03-23 13:06:58.932  2152  2214 D BtGatt.GattService: Batch record : [-36, 116, -107, -72, -27, 124, 1, -128, -73, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -107, 65, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, -127, -59, 40, 32, -73, -32, 1, -128, -76, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -17, -10, -17, 31, -7, 120, 1, -128, -73, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 9, -31, 43, 90, -6, 65, 1, -128, -87, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-23 13:06:58.933  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:06:58.934  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-23 13:06:58.934  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:06:58.935  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-23 13:06:58.936  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-23 13:06:58.939  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-23 13:06:58.940  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-23 13:06:58.940  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-23 13:06:58.941  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-23 13:06:58.941  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-23 13:06:58.942  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-23 13:06:58.958  3277  3337 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-23 13:06:58.958  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
03-23 13:06:58.961  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-23 13:06:58.961  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
03-23 13:06:58.961  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-23 13:06:58.962  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-23 13:06:58.962  3277  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 368)
03-23 13:06:58.963  3277  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:06:58.963  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-23 13:06:58.963  3277  3337 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-23 13:06:58.967  2152  2169 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-23 13:07:00.634  2152  2226 W bt-btif : info:x10
03-23 13:07:00.634  2152  2214 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 2205
,03-23 13:07:00.662  1513  1513 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-23 13:07:00.666  1513  1513 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-23 13:07:00.860  2152  2226 W bt-sdp  : process_service_search_attr_rsp
,03-23 13:07:01.122  2152  2214 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-23 13:07:01.129  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
03-23 13:07:01.130  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
03-23 13:07:01.132  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-23 13:07:01.133  2152  2215 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-23 13:07:01.256  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-23 13:07:01.257  2152  2215 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-23 13:07:01.260  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-23 13:07:01.280  2152  2215 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-23 13:07:01.361  2152  2226 W bt-btif : new conn_srvc id:26, app_id:1
03-23 13:07:01.361  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-23 13:07:01.361  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-23 13:07:01.362  3277  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 368)
03-23 13:07:01.362  3277  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 368)
03-23 13:07:01.363  3277  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 369)
03-23 13:07:01.363  3277  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 369)
03-23 13:07:01.363  3277  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 368)
,03-23 13:07:01.366  3277  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 369)
,03-23 13:07:01.381  3277  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 369)
,03-23 13:07:01.385  3277  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-23 13:07:01.385  3277  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 368)
03-23 13:07:01.385  3277  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 368)
03-23 13:07:01.386  3277  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 369)
,03-23 13:07:01.386  3277  3277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-23 13:07:01.386  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-23 13:07:01.386  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-23 13:07:01.387  3277  3277 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
,03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:07:01.387  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:07:01.393  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:01.395  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:01.400  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:01.400  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:07:01.405  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-23 13:07:01.409  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-23 13:07:01.409  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:07:01.409  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:07:01.409  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:07:01.410  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-23 13:07:01.410  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-23 13:07:01.410  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:01.410  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:01.410  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-23 13:07:01.417  2152  2169 D BtGatt.GattService: registerClient() - UUID=7a49aaba-8786-4c59-8205-cf237516aa52,
03-23 13:07:01.418  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=7a49aaba-8786-4c59-8205-cf237516aa52, clientIf=6
,03-23 13:07:01.418  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:07:01.420  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:01.424  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:01.428  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:01.431  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:01.432  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-23 13:07:01.434  2152  2169 D BtGatt.GattService: stopScan() - queue size =1,
,03-23 13:07:01.436  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:01.436  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:01.436  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:07:01.436  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:01.436  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:01.436  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:01.437  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:07:01.437  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:01.437  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.437  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:01.439  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:07:01.439  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.440  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:01.441  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:01.441  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.444  2152  2168 D BtGatt.GattService: registerClient() - UUID=29056876-a104-4b52-97df-96377ab76f66
03-23 13:07:01.444  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=29056876-a104-4b52-97df-96377ab76f66, clientIf=5
03-23 13:07:01.445  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:07:01.445  2152  2216 D BtGatt.GattService: start scan with filters
,03-23 13:07:01.446  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:07:01.447  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:01.448  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:01.450  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:01.451  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:01.452  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:01.452  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.454  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:01.454  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:07:01.455  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:01.456  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-23 13:07:01.456  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:07:01.456  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:07:01.456  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:01.457  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:01.457  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.457  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:01.457  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:01.457  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:07:01.457  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:01.457  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:01.457  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:01.457  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:01.459  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:01.459  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.461  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:01.461  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:01.465  2152  2216 D BtGatt.GattService: registerClient() - UUID=186e390f-abec-407d-b951-cfb20323dfac
,03-23 13:07:01.465  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=186e390f-abec-407d-b951-cfb20323dfac, clientIf=6
,03-23 13:07:01.466  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:01.467  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:01.473  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:01.476  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:01.479  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:01.480  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:01.482  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:07:01.483  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:01.484  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-23 13:07:01.484  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:01.484  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.484  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:01.484  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:01.484  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:01.484  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:01.484  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:01.484  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:07:01.487  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:01.488  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:01.488  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:01.489  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:01.489  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-23 13:07:01.490  2152  2169 D BtGatt.GattService: registerClient() - UUID=367c28fb-27b7-4d35-85a6-17b5df649295
03-23 13:07:01.491  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=367c28fb-27b7-4d35-85a6-17b5df649295, clientIf=5
03-23 13:07:01.492  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:01.493  2152  2216 D BtGatt.GattService: start scan with filters
03-23 13:07:01.494  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:07:01.494  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:07:01.497  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:01.498  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:01.498  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:01.500  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:01.501  2152  2214 D BtGatt.GattService: Client app is not null!,
,03-23 13:07:01.502  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:01.502  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:07:01.502  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.503  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:07:01.503  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:07:01.503  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-23 13:07:01.503  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:01.503  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:01.503  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-23 13:07:01.503  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:01.503  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:07:01.503  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:01.504  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-23 13:07:01.504  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.504  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:07:01.504  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:01.506  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-23 13:07:01.506  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.507  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-23 13:07:01.507  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:01.508  2152  2216 D BtGatt.GattService: registerClient() - UUID=5d62f4d2-3691-4462-9d55-9b980e907746
03-23 13:07:01.509  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=5d62f4d2-3691-4462-9d55-9b980e907746, clientIf=6
,03-23 13:07:01.509  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:01.510  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-23 13:07:01.514  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:01.516  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-23 13:07:01.519  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-23 13:07:01.519  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:01.521  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:01.522  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:01.523  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:07:01.523  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:07:01.523  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:01.523  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:07:01.523  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:01.523  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:01.524  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:01.524  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.525  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:01.527  2152  2168 D BtGatt.GattService: registerClient() - UUID=2d57fda4-06dd-4e75-9c63-27aa74042101
03-23 13:07:01.528  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:01.528  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:01.528  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=2d57fda4-06dd-4e75-9c63-27aa74042101, clientIf=5
03-23 13:07:01.528  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:01.528  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:01.529  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:07:01.529  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:01.529  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.529  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:01.529  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:07:01.530  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-23 13:07:01.530  3277  3277 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-23 13:07:01.530  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-23 13:07:01.530  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:07:01.530  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:07:01.530  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:01.530  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:01.531  3277  3856 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 370)
03-23 13:07:01.531  3277  3856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50076
03-23 13:07:01.531  3277  3856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-23 13:07:01.531  3277  3856 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 50076 (peer ID: F8:95:C7:87:3C:51)
03-23 13:07:01.531  3277  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-23 13:07:01.534  3277  3337 I jxcore-log: INFO testThaliMobileNative: 
03-23 13:07:01.534  3277  3337 I jxcore-log: 
03-23 13:07:01.535  3277  3337 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-23 13:07:01.535  3277  3337 I jxcore-log: 
03-23 13:07:01.536  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:01.538  3277  3856 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 50076,
03-23 13:07:01.538  3277  3856 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-23 13:07:01.538  3277  3856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-23 13:07:01.539  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:01.539  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.539  3277  3856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-23 13:07:01.540  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:01.540  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:01.540  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:01.540  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:01.541  3277  3857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 371, name: Sender)
03-23 13:07:01.542  3277  3856 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 370)
,03-23 13:07:01.542  3277  3856 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 370)
03-23 13:07:01.542  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-23 13:07:01.542  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:01.543  3277  3858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 372, name: Receiver)
03-23 13:07:01.543  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:01.543  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:01.545  3277  3337 I jxcore-log: INFO testThaliMobileNative: forwardSend,
03-23 13:07:01.545  3277  3337 I jxcore-log: 
,03-23 13:07:01.675  3277  3337 I jxcore-log: INFO testThaliMobileNative: forwardData
03-23 13:07:01.675  3277  3337 I jxcore-log: 
,03-23 13:07:01.744  3277  3337 I jxcore-log: INFO testThaliMobileNative: forwardData
03-23 13:07:01.744  3277  3337 I jxcore-log: 
,03-23 13:07:01.816  3277  3337 I jxcore-log: INFO testThaliMobileNative: forwardData
03-23 13:07:01.816  3277  3337 I jxcore-log: 
,03-23 13:07:01.887  3277  3337 I jxcore-log: INFO testThaliMobileNative: forwardData
03-23 13:07:01.887  3277  3337 I jxcore-log: 
,03-23 13:07:01.959  3277  3337 I jxcore-log: INFO testThaliMobileNative: forwardData
03-23 13:07:01.959  3277  3337 I jxcore-log: 
,03-23 13:07:01.965  3277  3337 I jxcore-log: ok 175 received should match sent forward
03-23 13:07:01.965  3277  3337 I jxcore-log: 
,03-23 13:07:01.980  3277  3337 I jxcore-log: # teardown
03-23 13:07:01.980  3277  3337 I jxcore-log: 
,03-23 13:07:02.263  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:07:02.263  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-23 13:07:02.263  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-23 13:07:02.263  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:07:02.268  2152  2168 D BtGatt.GattService: stopScan() - queue size =1,
,03-23 13:07:02.270  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:02.271  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:07:02.271  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-23 13:07:02.271  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:02.272  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:02.272  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:02.273  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-23 13:07:02.273  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:07:02.273  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-23 13:07:02.273  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:02.273  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:02.274  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-23 13:07:02.274  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:02.275  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:07:02.275  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:02.275  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:02.277  3277  3337 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-23 13:07:02.277  3277  3337 I jxcore-log: 
03-23 13:07:02.278  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-23 13:07:02.278  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:02.278  2152  2214 D BtGatt.GattService: current time is 240179695531
03-23 13:07:02.278  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-23 13:07:02.279  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:07:02.279  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:07:02.279  3277  3337 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-23 13:07:02.279  3277  3337 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 370)
,03-23 13:07:02.280  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 370)
03-23 13:07:02.280  3277  3858 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
,03-23 13:07:02.280  3277  3858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 372, name: Receiver)
03-23 13:07:02.282  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-23 13:07:02.282  3277  3337 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
,03-23 13:07:02.282  3277  3337 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 372
03-23 13:07:02.282  3277  3337 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-23 13:07:02.282  3277  3337 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 371
03-23 13:07:02.282  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 370)
,03-23 13:07:02.283  3277  3857 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Sender): Socket closed
,03-23 13:07:02.283  3277  3857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 371, name: Sender)
,03-23 13:07:02.285  3277  3337 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 370)
03-23 13:07:02.285  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-23 13:07:02.285  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:07:02.285  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:07:02.285  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-23 13:07:02.286  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:07:02.286  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:07:02.286  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:07:02.287  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:07:02.287  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-23 13:07:02.287  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:07:02.287  3277  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:07:02.287  3277  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:07:02.287  3277  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:07:02.288  3277  3337 D BluetoothLeScanner: could not find callback wrapper
03-23 13:07:02.288  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:02.288  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-23 13:07:02.290  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:02.291  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:02.294  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:02.294  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:07:02.295  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-23 13:07:02.296  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:02.296  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:02.296  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:07:02.296  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:07:02.296  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:07:02.296  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:02.296  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:07:02.296  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-23 13:07:02.297  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:02.297  3277  3337 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-23 13:07:02.297  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-23 13:07:02.298  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:07:02.298  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:02.298  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:07:02.299  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:07:02.299  3277  3337 I jxcore-log: 
,03-23 13:07:02.306  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:07:02.307   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:02.317  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-23 13:07:02.318  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-23 13:07:02.319  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:02.324  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-23 13:07:02.324  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:07:02.324  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:02.324  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:02.324  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:02.325  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-23 13:07:02.325  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-23 13:07:02.326  3277  3337 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-23 13:07:02.326  3277  3337 I jxcore-log: 
,03-23 13:07:02.334  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:02.334  3277  3337 I jxcore-log: 
,03-23 13:07:02.336  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:02.336  3277  3337 I jxcore-log: 
,03-23 13:07:02.338  3277  3337 I jxcore-log: # setup
03-23 13:07:02.338  3277  3337 I jxcore-log: 
,03-23 13:07:02.366  2152  2226 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,03-23 13:07:03.414  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:03.414  3277  3337 I jxcore-log: 
,03-23 13:07:03.420  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:03.420  3277  3337 I jxcore-log: 
,03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:03.427  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-23 13:07:03.431  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:03.436  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-23 13:07:03.436  3277  3337 I jxcore-log: ,
,03-23 13:07:03.440  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:03.440  3277  3337 I jxcore-log: 
,03-23 13:07:03.447  3277  3337 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-23 13:07:03.447  3277  3337 I jxcore-log: 
,03-23 13:07:03.450  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-23 13:07:03.450  3277  3337 I jxcore-log: 
,03-23 13:07:03.584  3277  3337 I jxcore-log: ok 178 specific error should be returned
03-23 13:07:03.584  3277  3337 I jxcore-log: 
,03-23 13:07:03.590  3277  3337 I jxcore-log: # teardown
03-23 13:07:03.590  3277  3337 I jxcore-log: 
,03-23 13:07:03.805  3277  3337 I jxcore-log: # setup
03-23 13:07:03.805  3277  3337 I jxcore-log: 
,03-23 13:07:03.977  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:03.977  3277  3337 I jxcore-log: 
,03-23 13:07:03.982  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:03.982  3277  3337 I jxcore-log: 
,03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:03.996  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,03-23 13:07:04.002  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:04.005  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-23 13:07:04.005  3277  3337 I jxcore-log: 
,03-23 13:07:04.009  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-23 13:07:04.009  3277  3337 I jxcore-log: 
,03-23 13:07:04.015  3277  3337 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
,03-23 13:07:04.015  3277  3337 I jxcore-log: 
,03-23 13:07:04.019  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-23 13:07:04.019  3277  3337 I jxcore-log: 
,03-23 13:07:04.239  3277  3337 I jxcore-log: ok 179 specific error should be returned
03-23 13:07:04.239  3277  3337 I jxcore-log: 
,03-23 13:07:04.241  3277  3337 I jxcore-log: # teardown
03-23 13:07:04.241  3277  3337 I jxcore-log: 
,03-23 13:07:04.466  3277  3337 I jxcore-log: # setup
03-23 13:07:04.466  3277  3337 I jxcore-log: 
,03-23 13:07:04.567  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:04.567  3277  3337 I jxcore-log: 
,03-23 13:07:04.570  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:04.570  3277  3337 I jxcore-log: 
,03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:04.578  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:04.582  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:04.583  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:04.583  3277  3337 I jxcore-log: 
,03-23 13:07:04.585  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:04.585  3277  3337 I jxcore-log: 
,03-23 13:07:04.587  3277  3337 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
03-23 13:07:04.587  3277  3337 I jxcore-log: 
03-23 13:07:04.589  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:04.589  3277  3337 I jxcore-log: 
,03-23 13:07:04.716  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:04.716  3277  3337 I jxcore-log: 
,03-23 13:07:04.718  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 48636
03-23 13:07:04.718  3277  3337 I jxcore-log: 
,03-23 13:07:04.720  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:04.720  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:04.720  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:04.724  3277  3337 I jxcore-log: ok 180 no errors
03-23 13:07:04.724  3277  3337 I jxcore-log: 
,03-23 13:07:04.725  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:04.725  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:04.725  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:04.726  3277  3337 I jxcore-log: ok 181 still no errors
03-23 13:07:04.726  3277  3337 I jxcore-log: 
,03-23 13:07:04.732  3277  3337 I jxcore-log: # teardown
03-23 13:07:04.732  3277  3337 I jxcore-log: 
,03-23 13:07:04.839  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:04.839  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:04.840  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:04.843  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:04.843  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-23 13:07:04.843  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:04.857  3277  3337 I jxcore-log: # setup
03-23 13:07:04.857  3277  3337 I jxcore-log: 
,03-23 13:07:05.027  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:05.027  3277  3337 I jxcore-log: 
,03-23 13:07:05.030  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:05.030  3277  3337 I jxcore-log: 
,03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:05.038  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:05.041  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:05.043  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:05.043  3277  3337 I jxcore-log: 
,03-23 13:07:05.044  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:05.044  3277  3337 I jxcore-log: 
03-23 13:07:05.047  3277  3337 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
03-23 13:07:05.047  3277  3337 I jxcore-log: 
03-23 13:07:05.049  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:05.049  3277  3337 I jxcore-log: 
,03-23 13:07:05.249  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:05.249  3277  3337 I jxcore-log: 
,03-23 13:07:05.252  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 48706
03-23 13:07:05.252  3277  3337 I jxcore-log: 
,03-23 13:07:05.258  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 38094, start advertisements: false
,03-23 13:07:05.258  3277  3337 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-23 13:07:05.258  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:05.260  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:05.261  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:07:05.261  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:07:05.261  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-23 13:07:05.269  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:05.270  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:05.270  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:07:05.279  2152  2169 D BtGatt.GattService: registerClient() - UUID=212f4eca-8a28-4f1c-9af6-72e63b766c41
,03-23 13:07:05.280  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=212f4eca-8a28-4f1c-9af6-72e63b766c41, clientIf=5
03-23 13:07:05.281  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:07:05.283  2152  2168 D BtGatt.GattService: start scan with filters,
03-23 13:07:05.285  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:05.285  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:05.285  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:05.285  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:07:05.285  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:07:05.285  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:05.286  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:07:05.286  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:05.287  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:07:05.287  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:05.288  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:05.288  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:05.288  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:05.289  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:05.289   822   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:05.290  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:05.290  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:05.291  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-23 13:07:05.291  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:05.299  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-23 13:07:05.299  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:07:05.300  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:05.300  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:07:05.300  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-23 13:07:05.300  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:07:05.306  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-23 13:07:05.306  3277  3337 I jxcore-log: 
,03-23 13:07:05.308  3277  3337 I jxcore-log: ok 182 no errors,
03-23 13:07:05.308  3277  3337 I jxcore-log: 
,03-23 13:07:05.312  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 38094, start advertisements: false,
03-23 13:07:05.312  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:07:05.312  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-23 13:07:05.312  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:07:05.312  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:05.314  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:05.314  3277  3337 I jxcore-log: 
,03-23 13:07:05.315  3277  3337 I jxcore-log: ok 183 still no errors,
03-23 13:07:05.315  3277  3337 I jxcore-log: 
,03-23 13:07:05.320  3277  3337 I jxcore-log: # teardown,
03-23 13:07:05.320  3277  3337 I jxcore-log: 
,03-23 13:07:05.718  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-23 13:07:05.719  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:07:05.719  3277  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-23 13:07:05.720  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:07:05.720  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:07:05.720  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:07:05.720  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-23 13:07:05.720  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:07:05.720  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-23 13:07:05.722  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:05.724  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:05.724  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:05.725  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-23 13:07:05.725  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:07:05.725  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-23 13:07:05.725  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-23 13:07:05.725  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-23 13:07:05.725  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:05.725  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:05.725  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:05.728  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:05.728  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-23 13:07:05.728  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:07:05.729  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:05.729  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:05.730  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:07:05.730  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:05.730  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:07:05.730  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:07:05.730  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:05.730  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:05.732  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:05.732  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:05.745  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:07:05.746   822   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:05.757  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:07:05.759  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:07:05.759  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:05.764  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-23 13:07:05.764  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:07:05.764  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:07:05.764  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:05.765  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-23 13:07:05.765  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-23 13:07:05.765  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:05.766  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:05.766  3277  3337 I jxcore-log: 
,03-23 13:07:05.767  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-23 13:07:05.767  3277  3337 I jxcore-log: 
,03-23 13:07:05.776  3277  3337 I jxcore-log: # setup
03-23 13:07:05.776  3277  3337 I jxcore-log: 
,03-23 13:07:05.906  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:05.906  3277  3337 I jxcore-log: 
,03-23 13:07:05.912  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:05.912  3277  3337 I jxcore-log: 
,03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:05.924  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:05.928  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:05.930  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:05.930  3277  3337 I jxcore-log: 
,03-23 13:07:05.932  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:05.932  3277  3337 I jxcore-log: 
,03-23 13:07:05.936  3277  3337 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
03-23 13:07:05.936  3277  3337 I jxcore-log: 
,03-23 13:07:05.938  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:05.938  3277  3337 I jxcore-log: 
,03-23 13:07:06.184  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:06.184  3277  3337 I jxcore-log: 
,03-23 13:07:06.186  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 52251
03-23 13:07:06.186  3277  3337 I jxcore-log: 
,03-23 13:07:06.193  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 52251, start advertisements: true
,03-23 13:07:06.193  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:07:06.193  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:07:06.193  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:07:06.198  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-23 13:07:06.198  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-23 13:07:06.198  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:06.198  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:07:06.205  2152  2169 D BtGatt.GattService: registerClient() - UUID=110e6859-dcc2-43fd-b4cf-66900207e20d
,03-23 13:07:06.206  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=110e6859-dcc2-43fd-b4cf-66900207e20d, clientIf=5
03-23 13:07:06.206  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:07:06.207  2152  2216 D BtGatt.GattService: start scan with filters
,03-23 13:07:06.209  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:06.211  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:06.211  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:07:06.211  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-23 13:07:06.211  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:07:06.211  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:06.212  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:06.212  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-23 13:07:06.212  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:06.212  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:06.212  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:06.212  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:06.212  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:06.213  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:07:06.213  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:06.214  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:06.214  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:06.215  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:06.215  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:06.217  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-23 13:07:06.217  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:06.218  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:06.218  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:06.223  2152  2168 D BtGatt.GattService: registerClient() - UUID=fac4073f-015b-4b20-a3c7-01fbf8c5391b
,03-23 13:07:06.223  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=fac4073f-015b-4b20-a3c7-01fbf8c5391b, clientIf=6
,03-23 13:07:06.224  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:07:06.227  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:06.232  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:06.235  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:06.238  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:06.239  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:06.239  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:07:06.240   822  1346 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:06.243  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:07:06.244  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:07:06.244  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:07:06.244  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:07:06.245  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:07:06.245  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-23 13:07:06.245  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:07:06.245  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-23 13:07:06.245  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:06.246  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-23 13:07:06.246  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:06.246  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:07:06.246  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:07:06.246  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:07:06.247  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:07:06.247  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:06.247  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:07:06.247  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:07:06.247  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:06.247  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:07:06.248  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-23 13:07:06.248  3277  3337 I jxcore-log: 
03-23 13:07:06.248  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:06.248   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:07:06.251  3277  3862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-23 13:07:06.251  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:06.251  3277  3337 I jxcore-log: 
,03-23 13:07:06.255  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:07:06.255  3277  3337 I jxcore-log: 
03-23 13:07:06.255  3277  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-23 13:07:06.256  3277  3337 I jxcore-log: ok 184 no errors
03-23 13:07:06.256  3277  3337 I jxcore-log: 
,03-23 13:07:06.262  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 52251, start advertisements: true
,03-23 13:07:06.263  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:07:06.263  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:07:06.263  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:07:06.263  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:07:06.265  3277  3337 I jxcore-log: ok 185 still no errors
03-23 13:07:06.265  3277  3337 I jxcore-log: 
,03-23 13:07:06.272  3277  3337 I jxcore-log: # teardown
03-23 13:07:06.272  3277  3337 I jxcore-log: 
,03-23 13:07:06.357  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-23 13:07:06.366  2152  2152 D BluetoothMapService: onReceive
,03-23 13:07:06.398  1513  1513 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-23 13:07:06.406  1513  1513 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-23 13:07:06.636  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-23 13:07:06.693  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:07:06.693  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-23 13:07:06.693  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:07:06.693  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:07:06.693  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:07:06.694  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-23 13:07:06.694  3277  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-23 13:07:06.694  3277  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:07:06.694  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:07:06.694  3277  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-23 13:07:06.694  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:07:06.694  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:07:06.694  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:07:06.694  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:07:06.694  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:07:06.695  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-23 13:07:06.695  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-23 13:07:06.699  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:06.701  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:06.702  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:06.702  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:06.702  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:06.702  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:06.702  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:06.703  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:07:06.703  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-23 13:07:06.703  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:07:06.703  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:07:06.703  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:07:06.705  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:06.705  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:06.705  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:06.706  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:06.706  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-23 13:07:06.708  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-23 13:07:06.708  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:06.708  2152  2214 D BtGatt.GattService: current time is 244609159227
03-23 13:07:06.708  2152  2214 D BtGatt.GattService: Batch record : [11, 6, 42, -99, 22, 94, 1, -128, -62, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -46, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-23 13:07:06.708  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-23 13:07:06.708  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:07:06.709  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:06.709  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:07:06.710  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:06.711  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:06.711  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:07:06.711  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:07:06.711  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:07:06.711  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:07:06.712  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:06.712  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:07:06.712  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-23 13:07:06.712  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:06.712  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:06.713  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:07:06.713  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 13:07:06.713  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:07:06.719  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-23 13:07:06.720   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:07:06.725  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:07:06.726  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:06.726  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:06.730  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-23 13:07:06.730  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:06.730  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:06.730  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:06.731  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-23 13:07:06.731  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:06.731  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:07:06.732  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-23 13:07:06.732  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:07:06.734  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:07:06.734  3277  3337 I jxcore-log: 
,03-23 13:07:06.736  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:06.736  3277  3337 I jxcore-log: 
,03-23 13:07:06.737  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-23 13:07:06.737  3277  3337 I jxcore-log: 
,03-23 13:07:06.748  3277  3337 I jxcore-log: # setup
,03-23 13:07:06.748  3277  3337 I jxcore-log: 
,03-23 13:07:06.935  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:06.935  3277  3337 I jxcore-log: ,
,03-23 13:07:06.942  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-23 13:07:06.942  3277  3337 I jxcore-log: 
,03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:06.955  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:06.959  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-23 13:07:06.963  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-23 13:07:06.963  3277  3337 I jxcore-log: 
,03-23 13:07:06.966  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-23 13:07:06.966  3277  3337 I jxcore-log: 
,03-23 13:07:06.973  3277  3337 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times
,03-23 13:07:06.973  3277  3337 I jxcore-log: 
,03-23 13:07:06.977  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-23 13:07:06.977  3277  3337 I jxcore-log: 
,03-23 13:07:07.229  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:07.229  3277  3337 I jxcore-log: 
,03-23 13:07:07.231  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 45708,
03-23 13:07:07.231  3277  3337 I jxcore-log: 
03-23 13:07:07.233  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:07:07.233  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:07:07.233  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:07.235  3277  3337 I jxcore-log: ok 186 no errors
03-23 13:07:07.235  3277  3337 I jxcore-log: 
03-23 13:07:07.236  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:07.236  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:07.236  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:07.238  3277  3337 I jxcore-log: ok 187 still no errors
03-23 13:07:07.238  3277  3337 I jxcore-log: 
,03-23 13:07:07.243  3277  3337 I jxcore-log: # teardown
03-23 13:07:07.243  3277  3337 I jxcore-log: 
,03-23 13:07:07.352  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:07.352  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:07.352  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:07.357  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:07:07.357  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-23 13:07:07.357  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:07.374  3277  3337 I jxcore-log: # setup
03-23 13:07:07.374  3277  3337 I jxcore-log: 
,03-23 13:07:07.478  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:07.478  3277  3337 I jxcore-log: 
,03-23 13:07:07.483  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:07.483  3277  3337 I jxcore-log: 
,03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
,03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:07.496  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:07.501  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:07.505  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:07.505  3277  3337 I jxcore-log: 
,03-23 13:07:07.510  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:07.510  3277  3337 I jxcore-log: 
,03-23 13:07:07.517  3277  3337 I jxcore-log: # 46. can get the network status before starting
03-23 13:07:07.517  3277  3337 I jxcore-log: 
,03-23 13:07:07.522  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:07.522  3277  3337 I jxcore-log: 
,03-23 13:07:07.702  3277  3337 I jxcore-log: ok 188 network status should have certain non-empty properties
03-23 13:07:07.702  3277  3337 I jxcore-log: 
,03-23 13:07:07.710  3277  3337 I jxcore-log: # teardown
03-23 13:07:07.710  3277  3337 I jxcore-log: 
,03-23 13:07:07.851  3277  3337 I jxcore-log: # setup
03-23 13:07:07.851  3277  3337 I jxcore-log: 
,03-23 13:07:07.946  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:07.946  3277  3337 I jxcore-log: 
,03-23 13:07:07.950  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:07.950  3277  3337 I jxcore-log: 
,03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:07.959  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:07.964  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:07.965  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:07.965  3277  3337 I jxcore-log: 
03-23 13:07:07.967  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:07.967  3277  3337 I jxcore-log: 
,03-23 13:07:07.969  3277  3337 I jxcore-log: # 47. error returned with bad router
03-23 13:07:07.969  3277  3337 I jxcore-log: 
,03-23 13:07:07.971  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:07.971  3277  3337 I jxcore-log: 
,03-23 13:07:08.066  3277  3337 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-23 13:07:08.066  3277  3337 I jxcore-log: 
03-23 13:07:08.068  3277  3337 I jxcore-log: ok 189 specific error expected
03-23 13:07:08.068  3277  3337 I jxcore-log: 
,03-23 13:07:08.072  3277  3337 I jxcore-log: # teardown
03-23 13:07:08.072  3277  3337 I jxcore-log: 
,03-23 13:07:08.201  3277  3337 I jxcore-log: # setup
03-23 13:07:08.201  3277  3337 I jxcore-log: 
,03-23 13:07:08.312  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:08.312  3277  3337 I jxcore-log: 
,03-23 13:07:08.316  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-23 13:07:08.316  3277  3337 I jxcore-log: 
,03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:08.330  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:08.335  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:08.338  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:08.338  3277  3337 I jxcore-log: 
,03-23 13:07:08.342  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:08.342  3277  3337 I jxcore-log: 
03-23 13:07:08.348  3277  3337 I jxcore-log: # 48. all services are stopped when we call stop
03-23 13:07:08.348  3277  3337 I jxcore-log: 
,03-23 13:07:08.351  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:08.351  3277  3337 I jxcore-log: 
,03-23 13:07:08.497  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:08.497  3277  3337 I jxcore-log: 
,03-23 13:07:08.499  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 46013
03-23 13:07:08.499  3277  3337 I jxcore-log: 
,03-23 13:07:08.506  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 52251, start advertisements: false,
03-23 13:07:08.506  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:07:08.506  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-23 13:07:08.506  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-23 13:07:08.510  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:07:08.510  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:08.510  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:07:08.514  2152  2169 D BtGatt.GattService: registerClient() - UUID=4efe1f9a-ff61-4bb6-aff2-897807737899,
03-23 13:07:08.514  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=4efe1f9a-ff61-4bb6-aff2-897807737899, clientIf=5
,03-23 13:07:08.515  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-23 13:07:08.515  2152  2168 D BtGatt.GattService: start scan with filters
,03-23 13:07:08.517  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:08.517  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:08.517  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:07:08.517  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:07:08.517  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:07:08.517  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:07:08.517  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:07:08.517   822  1346 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:08.518  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:08.523  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-23 13:07:08.523  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:08.525  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:07:08.525  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:08.525  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:08.525  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:07:08.525  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:07:08.525  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:07:08.526  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:08.526  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:07:08.526  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:08.526  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:07:08.528  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:08.528  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:08.529  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-23 13:07:08.529  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:08.532  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:08.532  3277  3337 I jxcore-log: 
03-23 13:07:08.535  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:08.535  3277  3337 I jxcore-log: 
,03-23 13:07:08.541  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 46013, start advertisements: true
03-23 13:07:08.541  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:07:08.542  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-23 13:07:08.542  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:07:08.545  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-23 13:07:08.545  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-23 13:07:08.545  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:08.546  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:08.546  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:08.546  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:08.547  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:08.547  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:07:08.551  2152  2168 D BtGatt.GattService: registerClient() - UUID=b6713034-d3b1-489e-8856-5b22ab219f2d
,03-23 13:07:08.551  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=b6713034-d3b1-489e-8856-5b22ab219f2d, clientIf=6
03-23 13:07:08.552  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:07:08.553  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:08.556  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:08.560  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:08.562  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:08.563  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
,03-23 13:07:08.563  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:07:08.563  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-23 13:07:08.564  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:07:08.564  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-23 13:07:08.564  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:07:08.564   822   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:08.564  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:07:08.566  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:08.566  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-23 13:07:08.566  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:07:08.566  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:08.567  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-23 13:07:08.567  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:07:08.568  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:07:08.568  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:07:08.568  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:07:08.568  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK,
03-23 13:07:08.568  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:07:08.568  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:08.568  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:07:08.571   822  1346 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-23 13:07:08.572  3277  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:07:08.574  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:07:08.574  3277  3337 I jxcore-log: ,
03-23 13:07:08.575  3277  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:07:08.585  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-23 13:07:08.585  3277  3337 I jxcore-log: 
,03-23 13:07:08.590  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-23 13:07:08.590  3277  3337 I jxcore-log: 
,03-23 13:07:08.592  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:07:08.592  3277  3337 I jxcore-log: 
,03-23 13:07:08.595  3277  3337 I jxcore-log: ok 190 connection to servers manager should succeed after starting,
03-23 13:07:08.595  3277  3337 I jxcore-log: 
,03-23 13:07:08.605  3277  3337 I jxcore-log: ok 191 connection to router server should succeed after starting,
03-23 13:07:08.605  3277  3337 I jxcore-log: 
,03-23 13:07:08.606  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:08.606  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything,
03-23 13:07:08.606  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:07:08.606  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:07:08.606  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-23 13:07:08.607  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:07:08.607  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-23 13:07:08.607  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:07:08.607  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:07:08.607  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-23 13:07:08.607  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:07:08.607  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-23 13:07:08.607  3277  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-23 13:07:08.607  3277  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:07:08.607  3277  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:07:08.608  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:08.610  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:08.610  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:07:08.610  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:08.610  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:07:08.610  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:07:08.610  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:07:08.610  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:08.610  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:07:08.611  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:08.611  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:08.611  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:08.612  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:08.613  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:08.615  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:08.615  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:08.615  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:08.616  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:08.616  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:08.617  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:08.617  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:07:08.618  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:08.618  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:07:08.618  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:07:08.618  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-23 13:07:08.618  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:08.618  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:07:08.618  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-23 13:07:08.619  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:08.619  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:08.619  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:07:08.619  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:08.619  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:07:08.621  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-23 13:07:08.621  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:08.621  2152  2214 D BtGatt.GattService: current time is 246522142664
,03-23 13:07:08.621  2152  2214 D BtGatt.GattService: Batch record : [-90, -79, 8, 1, 115, 110, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-23 13:07:08.621  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:07:08.625  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-23 13:07:08.626   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:08.630  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:07:08.630  3277  3337 I jxcore-log: 
,03-23 13:07:08.632  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:07:08.632  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:08.632  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:08.636  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-23 13:07:08.636  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:07:08.636  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:08.636  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:08.636  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:08.636  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:08.636  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:08.637  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-23 13:07:08.639  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:07:08.639  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:08.639  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:08.640  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:07:08.640  3277  3337 I jxcore-log: 
,03-23 13:07:08.641  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:08.641  3277  3337 I jxcore-log: 
,03-23 13:07:08.643  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:08.643  3277  3337 I jxcore-log: 
,03-23 13:07:08.648  3277  3337 I jxcore-log: ok 192 is stopped after calling stop
03-23 13:07:08.648  3277  3337 I jxcore-log: 
,03-23 13:07:08.653  3277  3337 I jxcore-log: ok 193 connection to servers manager should fail after stopping
03-23 13:07:08.653  3277  3337 I jxcore-log: 
,03-23 13:07:08.658  3277  3337 I jxcore-log: ok 194 connection to router server should fail after stopping
03-23 13:07:08.658  3277  3337 I jxcore-log: 
,03-23 13:07:08.663  3277  3337 I jxcore-log: # teardown
03-23 13:07:08.663  3277  3337 I jxcore-log: 
,03-23 13:07:09.117  3277  3337 I jxcore-log: # setup
03-23 13:07:09.117  3277  3337 I jxcore-log: ,
,03-23 13:07:09.262  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:09.262  3277  3337 I jxcore-log: 
,03-23 13:07:09.267  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:09.267  3277  3337 I jxcore-log: 
,03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:09.276  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:09.279  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:09.281  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:09.281  3277  3337 I jxcore-log: 
,03-23 13:07:09.283  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:09.283  3277  3337 I jxcore-log: 
,03-23 13:07:09.286  3277  3337 I jxcore-log: # 49. make sure terminateConnection is properly hooked up
03-23 13:07:09.286  3277  3337 I jxcore-log: 
,03-23 13:07:09.288  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:09.288  3277  3337 I jxcore-log: 
,03-23 13:07:09.600  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-23 13:07:10.352  3277  3337 I jxcore-log: ok 195 called with right arguments
03-23 13:07:10.352  3277  3337 I jxcore-log: 
,03-23 13:07:10.354  3277  3337 I jxcore-log: # teardown
03-23 13:07:10.354  3277  3337 I jxcore-log: 
,03-23 13:07:11.586  3277  3337 I jxcore-log: # setup
03-23 13:07:11.586  3277  3337 I jxcore-log: 
,03-23 13:07:11.772  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:11.772  3277  3337 I jxcore-log: 
,03-23 13:07:11.775  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:11.775  3277  3337 I jxcore-log: 
,03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:11.785  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:11.789  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:11.792  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:11.792  3277  3337 I jxcore-log: 
,03-23 13:07:11.796  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:11.796  3277  3337 I jxcore-log: 
,03-23 13:07:11.802  3277  3337 I jxcore-log: # 50. make sure terminateListener is properly hooked up
03-23 13:07:11.802  3277  3337 I jxcore-log: 
,03-23 13:07:11.806  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:11.806  3277  3337 I jxcore-log: 
,03-23 13:07:12.030  3277  3337 I jxcore-log: ok 196 called with right arguments,
03-23 13:07:12.030  3277  3337 I jxcore-log: 
03-23 13:07:12.033  3277  3337 I jxcore-log: # teardown
03-23 13:07:12.033  3277  3337 I jxcore-log: 
,03-23 13:07:12.145  3277  3337 I jxcore-log: # setup
03-23 13:07:12.145  3277  3337 I jxcore-log: ,
,03-23 13:07:12.270  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:12.270  3277  3337 I jxcore-log: 
,03-23 13:07:12.272  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:12.272  3277  3337 I jxcore-log: 
,03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:12.280  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:12.285  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-23 13:07:12.286  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:12.286  3277  3337 I jxcore-log: 
03-23 13:07:12.288  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:12.288  3277  3337 I jxcore-log: 
,03-23 13:07:12.291  3277  3337 I jxcore-log: # 51. make sure we actually call kill connections properly
03-23 13:07:12.291  3277  3337 I jxcore-log: 
,03-23 13:07:12.293  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:12.293  3277  3337 I jxcore-log: 
,03-23 13:07:12.441  3277  3337 I jxcore-log: ok 197 specific error expected
03-23 13:07:12.441  3277  3337 I jxcore-log: 
,03-23 13:07:12.446  3277  3337 I jxcore-log: # teardown
03-23 13:07:12.446  3277  3337 I jxcore-log: 
,03-23 13:07:12.560  3277  3337 I jxcore-log: # setup
03-23 13:07:12.560  3277  3337 I jxcore-log: 
,03-23 13:07:12.703  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-23 13:07:12.703  3277  3337 I jxcore-log: 
,03-23 13:07:12.708  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:12.708  3277  3337 I jxcore-log: 
,03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:12.717  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:12.721  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:12.722  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:12.722  3277  3337 I jxcore-log: 
,03-23 13:07:12.724  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:12.724  3277  3337 I jxcore-log: 
,03-23 13:07:12.727  3277  3337 I jxcore-log: # 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-23 13:07:12.727  3277  3337 I jxcore-log: 
,03-23 13:07:12.729  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:12.729  3277  3337 I jxcore-log: 
,03-23 13:07:12.862  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:12.862  3277  3337 I jxcore-log: 
,03-23 13:07:12.864  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 54740
03-23 13:07:12.864  3277  3337 I jxcore-log: 
,03-23 13:07:12.871  3277  3337 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51759,"error":{}}
03-23 13:07:12.871  3277  3337 I jxcore-log: 
,03-23 13:07:12.877  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:12.877  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:12.877  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:07:12.879  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-23 13:07:12.879  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:12.879  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:12.883  3277  3337 I jxcore-log: ok 198 failure reason is as expected
03-23 13:07:12.883  3277  3337 I jxcore-log: 
,03-23 13:07:12.884  3277  3337 I jxcore-log: ok 199 error description is as expected
03-23 13:07:12.884  3277  3337 I jxcore-log: 
03-23 13:07:12.884  3277  3337 I jxcore-log: ok 200 must be stopped
03-23 13:07:12.884  3277  3337 I jxcore-log: 
,03-23 13:07:12.892  3277  3337 I jxcore-log: # teardown
03-23 13:07:12.892  3277  3337 I jxcore-log: 
,03-23 13:07:12.998  3277  3337 I jxcore-log: # setup
03-23 13:07:12.998  3277  3337 I jxcore-log: 
,03-23 13:07:13.154  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:13.154  3277  3337 I jxcore-log: 
,03-23 13:07:13.158  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:13.158  3277  3337 I jxcore-log: 
,03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:13.168  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:13.172  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:13.173  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:13.173  3277  3337 I jxcore-log: 
,03-23 13:07:13.175  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:13.175  3277  3337 I jxcore-log: 
,03-23 13:07:13.178  3277  3337 I jxcore-log: # 53. We repeat failedConnection event when we get it from thaliTcpServersManager
03-23 13:07:13.178  3277  3337 I jxcore-log: 
,03-23 13:07:13.179  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:13.179  3277  3337 I jxcore-log: 
,03-23 13:07:13.366  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:13.366  3277  3337 I jxcore-log: ,
03-23 13:07:13.368  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 44752
03-23 13:07:13.368  3277  3337 I jxcore-log: 
,03-23 13:07:13.371  3277  3337 I jxcore-log: ok 201 peerIdentifier matches
03-23 13:07:13.371  3277  3337 I jxcore-log: 
,03-23 13:07:13.372  3277  3337 I jxcore-log: ok 202 error description matches
03-23 13:07:13.372  3277  3337 I jxcore-log: 
,03-23 13:07:13.375  3277  3337 I jxcore-log: # teardown
03-23 13:07:13.375  3277  3337 I jxcore-log: 
,03-23 13:07:13.541  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:07:13.541  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:13.541  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:13.542  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:13.542  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:13.542  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:13.551  3277  3337 I jxcore-log: # setup
03-23 13:07:13.551  3277  3337 I jxcore-log: 
,03-23 13:07:13.677  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:13.677  3277  3337 I jxcore-log: 
,03-23 13:07:13.680  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-23 13:07:13.680  3277  3337 I jxcore-log: 
,03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:13.688  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:13.691  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:13.693  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 13:07:13.693  3277  3337 I jxcore-log: 
,03-23 13:07:13.694  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 13:07:13.694  3277  3337 I jxcore-log: 
,03-23 13:07:13.697  3277  3337 I jxcore-log: # 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,03-23 13:07:13.697  3277  3337 I jxcore-log: 
03-23 13:07:13.699  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 13:07:13.699  3277  3337 I jxcore-log: 
,03-23 13:07:13.823  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:13.823  3277  3337 I jxcore-log: 
,03-23 13:07:13.825  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 54323
03-23 13:07:13.825  3277  3337 I jxcore-log: 
,03-23 13:07:13.830  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 46013, start advertisements: false,
,03-23 13:07:13.830  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,03-23 13:07:13.831  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,03-23 13:07:13.831  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-23 13:07:13.835  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:07:13.835  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:07:13.835  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:13.840  2152  2216 D BtGatt.GattService: registerClient() - UUID=8280df97-f378-43d1-b89e-3fa25348084c
,03-23 13:07:13.840  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=8280df97-f378-43d1-b89e-3fa25348084c, clientIf=5
03-23 13:07:13.841  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:13.841  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:07:13.843  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:13.843  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:13.843  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:07:13.843  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:07:13.843  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:13.843  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:07:13.843  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:13.843  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:13.844   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:13.853  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-23 13:07:13.853  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.855  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,03-23 13:07:13.855  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.855  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:07:13.855  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:07:13.857  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:07:13.857  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-23 13:07:13.857  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
,03-23 13:07:13.857  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-23 13:07:13.858  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:07:13.858  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:13.858  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-23 13:07:13.859  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:07:13.860  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-23 13:07:13.860  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:13.863  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-23 13:07:13.863  3277  3337 I jxcore-log: 
,03-23 13:07:13.867  3277  3337 I jxcore-log: ok 203 discoveryActive matches
03-23 13:07:13.867  3277  3337 I jxcore-log: ,
03-23 13:07:13.868  3277  3337 I jxcore-log: ok 204 advertisingActive matches
,03-23 13:07:13.868  3277  3337 I jxcore-log: 
03-23 13:07:13.871  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-23 13:07:13.871  3277  3337 I jxcore-log: 
,03-23 13:07:13.883  3277  3337 I jxcore-log: not ok 205 discoveryActive matches,
03-23 13:07:13.883  3277  3337 I jxcore-log: 
03-23 13:07:13.883  3277  3337 I jxcore-log:   ---
03-23 13:07:13.883  3277  3337 I jxcore-log: 
03-23 13:07:13.883  3277  3337 I jxcore-log:     operator: equal
03-23 13:07:13.883  3277  3337 I jxcore-log: 
03-23 13:07:13.883  3277  3337 I jxcore-log:     expected: false
03-23 13:07:13.883  3277  3337 I jxcore-log: 
03-23 13:07:13.883  3277  3337 I jxcore-log:     actual:   true,
03-23 13:07:13.883  3277  3337 I jxcore-log: 
03-23 13:07:13.884  3277  3337 I jxcore-log:   ...
03-23 13:07:13.884  3277  3337 I jxcore-log: 
,03-23 13:07:13.884  3277  3337 I jxcore-log: ok 206 advertisingActive matches
03-23 13:07:13.884  3277  3337 I jxcore-log: 
,03-23 13:07:13.886  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-23 13:07:13.886  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:13.886  3277  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-23 13:07:13.886  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:07:13.886  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:07:13.886  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-23 13:07:13.886  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:07:13.887  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-23 13:07:13.887  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-23 13:07:13.889  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:13.890  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:13.891  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:13.891  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:13.891  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-23 13:07:13.891  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-23 13:07:13.891  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-23 13:07:13.891  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:13.891  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:13.891  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.892  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:13.892  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:13.892  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:07:13.892  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-23 13:07:13.893  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:13.893  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:13.893  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:13.893  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:13.893  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-23 13:07:13.895  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-23 13:07:13.895  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:13.895  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:13.896  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-23 13:07:13.896  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.902  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:07:13.902   822  1391 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:13.912  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:07:13.913  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-23 13:07:13.913  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:13.917  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:13.917  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-23 13:07:13.917  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:13.917  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:13.919  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:13.919  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:13.919  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:13.922  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:13.922  3277  3337 I jxcore-log: 
,03-23 13:07:13.923  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:13.923  3277  3337 I jxcore-log: 
,03-23 13:07:13.935  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:13.935  3277  3337 I jxcore-log: 
,03-23 13:07:13.938  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 48358
03-23 13:07:13.938  3277  3337 I jxcore-log: 
,03-23 13:07:13.944  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 48358, start advertisements: true
,03-23 13:07:13.944  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:07:13.944  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-23 13:07:13.944  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:07:13.949  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-23 13:07:13.949  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:13.949  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:13.949  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-23 13:07:13.955  2152  2169 D BtGatt.GattService: registerClient() - UUID=25c26e7f-6594-4d68-a21c-1572cb11842b
03-23 13:07:13.955  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=25c26e7f-6594-4d68-a21c-1572cb11842b, clientIf=5
,03-23 13:07:13.956  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:13.956  2152  2216 D BtGatt.GattService: start scan with filters
03-23 13:07:13.957  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:13.957  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:07:13.957  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-23 13:07:13.957  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:07:13.957  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-23 13:07:13.957  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:13.957  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:13.957  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:07:13.958  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:13.958  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:13.958  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:13.958  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:07:13.958  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:13.961  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:13.961  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.964  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:13.964  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.964  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:13.964  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:07:13.967  2152  2169 D BtGatt.GattService: registerClient() - UUID=17afed94-696b-4c1c-acca-22a6dc5f3ec8
03-23 13:07:13.967  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=17afed94-696b-4c1c-acca-22a6dc5f3ec8, clientIf=6
03-23 13:07:13.968  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-23 13:07:13.968  3277  3293 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:13.968  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:13.970  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:13.970  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:13.970  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:13.975  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:13.979  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:13.982  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-23 13:07:13.983  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:07:13.983  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-23 13:07:13.983   822  1346 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:13.988  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-23 13:07:13.989  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:07:13.989  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:07:13.989  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:13.990  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-23 13:07:13.990  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:07:13.990  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-23 13:07:13.990  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-23 13:07:13.990  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-23 13:07:13.991  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:13.991  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:07:13.991  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:07:13.991  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:07:13.991  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
03-23 13:07:13.991  3277  3277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:13.991  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:07:13.991  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:07:13.991  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:13.991  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-23 13:07:13.991  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:13.992  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:13.993   822  1161 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:07:13.995  3277  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:07:13.996  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:13.996  3277  3337 I jxcore-log: 
,03-23 13:07:14.000  3277  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:07:14.003  3277  3337 I jxcore-log: not ok 207 discoveryActive matches
03-23 13:07:14.003  3277  3337 I jxcore-log: 
,03-23 13:07:14.003  3277  3337 I jxcore-log:   ---
03-23 13:07:14.003  3277  3337 I jxcore-log: 
03-23 13:07:14.003  3277  3337 I jxcore-log:     operator: equal
03-23 13:07:14.003  3277  3337 I jxcore-log: 
03-23 13:07:14.003  3277  3337 I jxcore-log:     expected: false
03-23 13:07:14.003  3277  3337 I jxcore-log: 
,03-23 13:07:14.003  3277  3337 I jxcore-log:     actual:   true
03-23 13:07:14.003  3277  3337 I jxcore-log: 
03-23 13:07:14.004  3277  3337 I jxcore-log:   ...
03-23 13:07:14.004  3277  3337 I jxcore-log: 
,03-23 13:07:14.007  3277  3337 I jxcore-log: not ok 208 advertisingActive matches
03-23 13:07:14.007  3277  3337 I jxcore-log: 
03-23 13:07:14.007  3277  3337 I jxcore-log:   ---
03-23 13:07:14.007  3277  3337 I jxcore-log: 
03-23 13:07:14.007  3277  3337 I jxcore-log:     operator: equal
03-23 13:07:14.007  3277  3337 I jxcore-log: 
03-23 13:07:14.007  3277  3337 I jxcore-log:     expected: true
03-23 13:07:14.007  3277  3337 I jxcore-log: 
,03-23 13:07:14.008  3277  3337 I jxcore-log:     actual:   false
03-23 13:07:14.008  3277  3337 I jxcore-log: 
03-23 13:07:14.008  3277  3337 I jxcore-log:   ...
03-23 13:07:14.008  3277  3337 I jxcore-log: 
,03-23 13:07:14.010  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:14.010  3277  3337 I jxcore-log: 
,03-23 13:07:14.014  3277  3337 I jxcore-log: not ok 209 discoveryActive matches
03-23 13:07:14.014  3277  3337 I jxcore-log: 
03-23 13:07:14.015  3277  3337 I jxcore-log:   ---
03-23 13:07:14.015  3277  3337 I jxcore-log: 
,03-23 13:07:14.015  3277  3337 I jxcore-log:     operator: equal
03-23 13:07:14.015  3277  3337 I jxcore-log: 
03-23 13:07:14.015  3277  3337 I jxcore-log:     expected: false
03-23 13:07:14.015  3277  3337 I jxcore-log: 
03-23 13:07:14.015  3277  3337 I jxcore-log:     actual:   true
03-23 13:07:14.015  3277  3337 I jxcore-log: 
03-23 13:07:14.015  3277  3337 I jxcore-log:   ...
03-23 13:07:14.015  3277  3337 I jxcore-log: ,
03-23 13:07:14.015  3277  3337 I jxcore-log: ok 210 advertisingActive matches
03-23 13:07:14.015  3277  3337 I jxcore-log: 
03-23 13:07:14.017  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:07:14.017  3277  3337 I jxcore-log: 
03-23 13:07:14.018  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:14.018  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-23 13:07:14.018  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-23 13:07:14.018  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:07:14.018  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-23 13:07:14.018  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:07:14.018  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:07:14.018  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-23 13:07:14.019  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:07:14.019  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-23 13:07:14.019  3277  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:07:14.019  3277  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:07:14.019  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:07:14.019  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-23 13:07:14.019  3277  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:07:14.021  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:14.022  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:14.022  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:14.022  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:14.022  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:07:14.022  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:07:14.022  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-23 13:07:14.022  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:14.022  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:07:14.024  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:14.024  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:14.024  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:14.025  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:14.025  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:14.028  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:07:14.028  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:14.028  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:14.030  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:14.030  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:14.031  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:14.032  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:14.032  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:14.032  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:07:14.032  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:14.032  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:07:14.032  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:07:14.032  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:07:14.032  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-23 13:07:14.035  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:07:14.036  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:07:14.037  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:14.037  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:14.038  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:07:14.038  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:14.038  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:07:14.044  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:07:14.045   822  1413 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:14.050  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:07:14.051  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:14.052  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:14.056  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-23 13:07:14.056  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-23 13:07:14.056  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-23 13:07:14.057  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:14.057  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:14.057  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:14.057  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:14.058  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-23 13:07:14.060  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:14.061  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-23 13:07:14.061  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-23 13:07:14.063  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-23 13:07:14.063  3277  3337 I jxcore-log: 
03-23 13:07:14.065  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:14.065  3277  3337 I jxcore-log: 
03-23 13:07:14.067  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:14.067  3277  3337 I jxcore-log: 
,03-23 13:07:14.084  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:14.084  3277  3337 I jxcore-log: 
,03-23 13:07:14.086  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 46373
03-23 13:07:14.086  3277  3337 I jxcore-log: 
,03-23 13:07:14.093  3277  3337 I jxcore-log: # teardown
03-23 13:07:14.093  3277  3337 I jxcore-log: 
,03-23 13:07:14.638  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-23 13:07:14.639  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:14.640  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:14.641  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-23 13:07:14.641  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:14.641  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-23 13:07:14.652  3277  3337 I jxcore-log: # setup
,03-23 13:07:14.652  3277  3337 I jxcore-log: 
,03-23 13:07:14.749  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 13:07:14.749  3277  3337 I jxcore-log: 
,03-23 13:07:14.756  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 13:07:14.756  3277  3337 I jxcore-log: 
,03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 13:07:14.766  3277  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 13:07:14.770  3277  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 13:07:14.772  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-23 13:07:14.772  3277  3337 I jxcore-log: 
,03-23 13:07:14.775  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-23 13:07:14.775  3277  3337 I jxcore-log: 
,03-23 13:07:14.780  3277  3337 I jxcore-log: # 55. can do HTTP requests between peers
,03-23 13:07:14.780  3277  3337 I jxcore-log: 
,03-23 13:07:14.782  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-23 13:07:14.782  3277  3337 I jxcore-log: 
,03-23 13:07:14.915  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:07:14.915  3277  3337 I jxcore-log: 
,03-23 13:07:14.928  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 34861
03-23 13:07:14.928  3277  3337 I jxcore-log: 
,03-23 13:07:14.934  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 48358, start advertisements: false
,03-23 13:07:14.934  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-23 13:07:14.934  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:07:14.934  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-23 13:07:14.938  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:07:14.938  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:14.938  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-23 13:07:14.942  2152  2216 D BtGatt.GattService: registerClient() - UUID=7610baa2-9b59-4400-8092-c7d634aa5e68
,03-23 13:07:14.943  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=7610baa2-9b59-4400-8092-c7d634aa5e68, clientIf=5
,03-23 13:07:14.943  3277  3293 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:07:14.943  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:07:14.944  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-23 13:07:14.944  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-23 13:07:14.944  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-23 13:07:14.944  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-23 13:07:14.945  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:14.945  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:14.945  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-23 13:07:14.945  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-23 13:07:14.946   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:07:14.949  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-23 13:07:14.949  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-23 13:07:14.949  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:14.950  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-23 13:07:14.950  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:14.950  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-23 13:07:14.954  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:14.954  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:14.954  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:14.954  3277  3337 I jxcore-log: 
,03-23 13:07:14.955  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-23 13:07:14.955  3277  3337 I jxcore-log: 
03-23 13:07:14.955  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-23 13:07:14.955  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:14.956  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:14.956  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:14.959  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:14.959  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:14.961  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:14.961  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:14.963  3277  3337 I io.jxcore.node.ConnectionHelper: start: Port number: 34861, start advertisements: true
03-23 13:07:14.963  3277  3337 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-23 13:07:14.963  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-23 13:07:14.963  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-23 13:07:14.967  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-23 13:07:14.967  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-23 13:07:14.967  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:14.967  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:14.968  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-23 13:07:14.968  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:14.968  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:14.968  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:07:14.975  2152  2216 D BtGatt.GattService: registerClient() - UUID=6663432c-359e-4db7-8c96-ddfff7765698
03-23 13:07:14.975  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=6663432c-359e-4db7-8c96-ddfff7765698, clientIf=6
,03-23 13:07:14.975  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:07:14.977  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:14.982  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:14.986  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:14.988  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:14.991  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-23 13:07:14.991  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:07:14.991  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-23 13:07:14.991  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:07:14.991  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-23 13:07:14.991  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-23 13:07:14.992  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-23 13:07:14.992   822  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:07:14.997  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:14.997  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-23 13:07:14.997  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-23 13:07:14.997  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:14.997  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-23 13:07:15.000  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-23 13:07:15.000  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-23 13:07:15.001  3277  3337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-23 13:07:15.001  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-23 13:07:15.001  3277  3337 I io.jxcore.node.ConnectionHelper: start: OK
03-23 13:07:15.001  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-23 13:07:15.001  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-23 13:07:15.002  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-23 13:07:15.006  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-23 13:07:15.006  3277  3337 I jxcore-log: 
,03-23 13:07:15.007   822  1412 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-23 13:07:15.010  3277  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-23 13:07:15.013  3277  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-23 13:07:15.970  2152  2152 D BtGatt.ScanManager: awakened up at time 253871
,03-23 13:07:15.972  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:15.980  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-23 13:07:15.980  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:15.981  2152  2214 D BtGatt.GattService: current time is 253881936620
03-23 13:07:15.981  2152  2214 D BtGatt.GattService: Batch record : [119, 63, -3, -90, 84, 94, 1, -128, -81, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, -44, -106, -22, -38, 116, 0, -128, -106, 4, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-23 13:07:15.981  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:07:15.982  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:07:15.983  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-23 13:07:15.985  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-23 13:07:15.985  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-23 13:07:15.985  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-23 13:07:15.985  3277  3277 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-23 13:07:15.988  3277  3337 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-23 13:07:15.988  3277  3337 I jxcore-log: 
,03-23 13:07:15.990  3277  3337 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
,03-23 13:07:15.990  3277  3337 I jxcore-log: ,
,03-23 13:07:15.993  3277  3337 I jxcore-log: ok 211 found a peer! {"peerIdentifier":"E0:DB:10:14:E2:C0","portNumber":39645,"hostAddress":"127.0.0.1"},
03-23 13:07:15.993  3277  3337 I jxcore-log: ,
03-23 13:07:15.998  3277  3337 I jxcore-log: DEBUG createPeerListener: createPeerListener,
03-23 13:07:15.998  3277  3337 I jxcore-log: 
,03-23 13:07:16.003  3277  3337 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
,03-23 13:07:16.003  3277  3337 I jxcore-log: 
03-23 13:07:16.007  3277  3337 I jxcore-log: DEBUG createPeerListener: first connection
03-23 13:07:16.007  3277  3337 I jxcore-log: 
,03-23 13:07:16.013  3277  3337 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-23 13:07:16.013  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-23 13:07:16.014  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-23 13:07:16.014  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-23 13:07:16.014  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-23 13:07:16.014  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-23 13:07:16.014  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-23 13:07:16.014  3277  3337 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-23 13:07:16.015  3277  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 377)
03-23 13:07:16.015  3277  3869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-23 13:07:16.016  2152  2168 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-23 13:07:17.970  2152  2226 W bt-btif : info:x10
03-23 13:07:17.970  2152  2214 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,03-23 13:07:18.008  1513  1513 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-23 13:07:18.014  1513  1513 I BluetoothClassifier: Bluetooth Device Name: Note4-1,
,03-23 13:07:18.038  2152  2226 W bt-sdp  : process_service_search_attr_rsp
,03-23 13:07:18.859  2152  2226 W bt-btif : new conn_srvc id:26, app_id:1
03-23 13:07:18.859  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-23 13:07:18.859  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-23 13:07:18.860  3277  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 377)
03-23 13:07:18.860  3277  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 377)
,03-23 13:07:18.866  3277  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 378)
,03-23 13:07:18.866  3277  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 378)
03-23 13:07:18.866  3277  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 377)
,03-23 13:07:18.872  3277  3871 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 378)
,03-23 13:07:19.133  3277  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 378)
03-23 13:07:19.136  3277  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-23 13:07:19.136  3277  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 377)
03-23 13:07:19.137  3277  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 377)
,03-23 13:07:19.137  3277  3871 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 378)
,03-23 13:07:19.137  3277  3277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0],
03-23 13:07:19.137  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-23 13:07:19.138  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-23 13:07:19.138  3277  3277 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-23 13:07:19.138  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-23 13:07:19.139  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:19.139  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:19.139  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:07:19.139  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:07:19.139  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:07:19.139  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:07:19.145  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:19.146  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:19.151  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:19.151  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:07:19.153  2152  3870 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-23 13:07:19.154  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:07:19.154  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:19.155  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false,
03-23 13:07:19.155  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:07:19.155  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,03-23 13:07:19.155  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:19.156  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-23 13:07:19.156  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:19.156  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:19.166  2152  3870 D BtGatt.GattService: registerClient() - UUID=a6ca50ba-7392-485d-b60e-6a6a8e248e7e
,03-23 13:07:19.167  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=a6ca50ba-7392-485d-b60e-6a6a8e248e7e, clientIf=6
03-23 13:07:19.167  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:19.168  2152  2224 D BtGatt.AdvertiseManager: message : 0,
,03-23 13:07:19.175  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:19.178  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:19.181  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:19.182  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:19.184  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:07:19.187  2152  3870 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:19.187  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:07:19.187  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:19.187  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:19.187  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:07:19.187  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:07:19.187  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:19.188  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:19.188  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.188  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:19.190  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:19.190  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.190  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:19.192  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-23 13:07:19.192  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.193  2152  2214 D BtGatt.GattService: current time is 257094034014
03-23 13:07:19.193  2152  2214 D BtGatt.GattService: Batch record : [119, 63, -3, -90, 84, 94, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -56, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-23 13:07:19.193  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-23 13:07:19.193  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-23 13:07:19.194  2152  3870 D BtGatt.GattService: registerClient() - UUID=f61067b4-503c-43f5-931a-7e33374a1d6a
,03-23 13:07:19.194  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=f61067b4-503c-43f5-931a-7e33374a1d6a, clientIf=5
03-23 13:07:19.195  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-23 13:07:19.195  2152  2168 D BtGatt.GattService: start scan with filters
03-23 13:07:19.199  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:19.199  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2,
03-23 13:07:19.199  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:19.205  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:19.205  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:19.205  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.206  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-23 13:07:19.206  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.206  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:19.206  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:19.206  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:19.208  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:19.208  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.210  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:19.210  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.213  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-23 13:07:19.213  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:19.214  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:19.214  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:19.214  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:07:19.214  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-23 13:07:19.214  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:19.214  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:19.215  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:19.215  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:19.215  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:19.215  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:07:19.218  2152  2168 D BtGatt.GattService: registerClient() - UUID=fd0dd89c-3f6e-4000-bb71-4eb6f76f77f1
,03-23 13:07:19.219  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=fd0dd89c-3f6e-4000-bb71-4eb6f76f77f1, clientIf=6
,03-23 13:07:19.219  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-23 13:07:19.220  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-23 13:07:19.222  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising,
,03-23 13:07:19.225  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:19.227  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:19.228  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:19.229  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:07:19.230  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:19.231  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:07:19.231  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-23 13:07:19.231  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:19.231  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:19.231  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-23 13:07:19.231  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:19.231  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:19.231  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.232  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-23 13:07:19.234  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:19.234  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.234  2152  2168 D BtGatt.GattService: registerClient() - UUID=524ae75e-bbe4-4d6a-a870-95487e77041d
03-23 13:07:19.234  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:19.234  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=524ae75e-bbe4-4d6a-a870-95487e77041d, clientIf=5
03-23 13:07:19.234  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:19.235  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:07:19.235  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:19.235  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.236  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:07:19.236  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:19.240  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:19.240  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-23 13:07:19.241  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:19.242  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:19.242  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-23 13:07:19.244  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-23 13:07:19.244  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.244  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:19.244  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:19.244  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-23 13:07:19.244  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:19.245  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:19.245  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:07:19.245  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:07:19.246  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:07:19.246  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:19.246  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-23 13:07:19.246  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:19.246  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:19.246  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:19.246  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:07:19.247  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:19.247  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.249  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:19.249  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.250  2152  2168 D BtGatt.GattService: registerClient() - UUID=d5651a88-10e4-4af5-ae41-3561b7007e7f
03-23 13:07:19.250  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=d5651a88-10e4-4af5-ae41-3561b7007e7f, clientIf=6
03-23 13:07:19.250  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:19.251  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:19.254  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:19.256  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:19.258  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:19.259  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:19.260  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:07:19.261  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:19.261  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-23 13:07:19.261  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:19.261  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:19.262  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:19.262  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-23 13:07:19.262  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:19.262  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-23 13:07:19.262  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.262  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:19.265  2152  3870 D BtGatt.GattService: registerClient() - UUID=08ecac10-f47c-46aa-a06c-961aa683cd04
03-23 13:07:19.265  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:07:19.265  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.265  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:19.265  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=08ecac10-f47c-46aa-a06c-961aa683cd04, clientIf=5
,03-23 13:07:19.266  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:19.266  2152  2169 D BtGatt.GattService: start scan with filters
03-23 13:07:19.266  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:19.266  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.266  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:19.267  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:19.267  3277  3277 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-23 13:07:19.267  3277  3277 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1,
03-23 13:07:19.267  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:19.267  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-23 13:07:19.267  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:07:19.267  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:19.267  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-23 13:07:19.268  3277  3872 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 379)
03-23 13:07:19.269  3277  3872 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37965
03-23 13:07:19.269  3277  3872 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-23 13:07:19.269  3277  3872 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 37965 (peer ID: E0:DB:10:14:E2:C0)
03-23 13:07:19.270  3277  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-23 13:07:19.270  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-23 13:07:19.272  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:19.272  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.273  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:19.273  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:19.273  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:07:19.273  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:19.275  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:19.275  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.275  3277  3337 I jxcore-log: DEBUG createPeerListener: forward connection
03-23 13:07:19.275  3277  3337 I jxcore-log: 
03-23 13:07:19.276  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:19.276  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:19.282  3277  3872 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 37965
,03-23 13:07:19.282  3277  3872 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-23 13:07:19.282  3277  3872 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-23 13:07:19.282  3277  3872 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-23 13:07:19.283  3277  3873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 380, name: Sender)
,03-23 13:07:19.283  3277  3872 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 379)
03-23 13:07:19.283  3277  3872 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 379)
03-23 13:07:19.284  3277  3874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 381, name: Receiver)
,03-23 13:07:19.725  3277  3337 I jxcore-log: DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
03-23 13:07:19.725  3277  3337 I jxcore-log: 
,03-23 13:07:19.735  3277  3337 I jxcore-log: ok 212 server should return 200
03-23 13:07:19.735  3277  3337 I jxcore-log: 
,03-23 13:07:19.739  3277  3337 I jxcore-log: ok 213 response body should match testData
03-23 13:07:19.739  3277  3337 I jxcore-log: 
,03-23 13:07:19.749  3277  3337 I jxcore-log: # teardown
03-23 13:07:19.749  3277  3337 I jxcore-log: 
,03-23 13:07:20.972  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-23 13:07:24.280  2152  2152 D BtGatt.ScanManager: awakened up at time 262181,
03-23 13:07:24.282  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-23 13:07:24.292  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-23 13:07:24.292  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:24.688  2152  2226 W bt-btif : dm_pm_timer expires,
03-23 13:07:24.688  2152  2226 W bt-btif : dm_pm_timer expires 0
,03-23 13:07:24.688  2152  2226 W bt-btif : proc dm_pm_timer expires,
,03-23 13:07:24.806  2152  2152 D BtGatt.ScanManager: awakened up at time 262707,
03-23 13:07:24.808  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:24.816  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:24.816  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:25.011  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-23 13:07:25.832  2152  2152 D BtGatt.ScanManager: awakened up at time 263733
,03-23 13:07:25.834  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:25.841  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:25.841  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:26.857  2152  2152 D BtGatt.ScanManager: awakened up at time 264758
03-23 13:07:26.860  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:26.865  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:26.865  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:27.880  2152  2152 D BtGatt.ScanManager: awakened up at time 265781
,03-23 13:07:27.881  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:27.886  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:27.887  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:28.386  3384  3876 V GoogleAuthProtoRequest: [343] a.<init>: mAccountName set to: thalitester@gmail.com
,03-23 13:07:28.460  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-23 13:07:28.461  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:07:28.461  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:07:28.461  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:07:28.471  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:07:28.502  3384  3876 W ExperimentUpdateService: [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-23 13:07:28.503  3384  3876 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-23 13:07:28.525  2152  2152 D BtGatt.ScanManager: awakened up at time 266426
,03-23 13:07:28.527  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:28.531  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:28.531  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:29.039  2152  2152 D BtGatt.ScanManager: awakened up at time 266939,
03-23 13:07:29.040  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:29.050  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:29.050  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:30.066  2152  2152 D BtGatt.ScanManager: awakened up at time 267967,
03-23 13:07:30.067  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:30.074  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:30.074  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:31.090  2152  2152 D BtGatt.ScanManager: awakened up at time 268991
,03-23 13:07:31.092  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-23 13:07:31.100  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:31.100  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:32.115  2152  2152 D BtGatt.ScanManager: awakened up at time 270016
,03-23 13:07:32.117  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:32.126  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:32.127  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:33.142  2152  2152 D BtGatt.ScanManager: awakened up at time 271043
,03-23 13:07:33.143  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:33.150  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:33.150  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:34.165  2152  2152 D BtGatt.ScanManager: awakened up at time 272066
,03-23 13:07:34.166  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:34.174  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-23 13:07:34.175  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:34.711  3277  3277 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up,
03-23 13:07:34.711  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-23 13:07:34.712  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:34.712  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:34.712  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:07:34.712  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-23 13:07:34.712  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:07:34.712  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-23 13:07:34.717  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-23 13:07:34.718  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-23 13:07:34.724  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:34.724  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:34.726  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-23 13:07:34.727  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-23 13:07:34.727  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:34.728  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-23 13:07:34.728  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-23 13:07:34.728  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:34.728  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:34.729  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:34.729  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:34.730  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:34.737  2152  2169 D BtGatt.GattService: registerClient() - UUID=f6e16c2c-10f9-4a62-9e32-c7940c72dae3
,03-23 13:07:34.737  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=f6e16c2c-10f9-4a62-9e32-c7940c72dae3, clientIf=6
03-23 13:07:34.737  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:34.739  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:34.742  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:34.745  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:34.748  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-23 13:07:34.749  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-23 13:07:34.750  2152  3870 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:34.752  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:34.752  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-23 13:07:34.752  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:34.752  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.752  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:34.753  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:34.753  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:34.753  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-23 13:07:34.753  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:34.753  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:34.754  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:34.754  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.755  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:34.756  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:34.756  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:34.759  2152  2169 D BtGatt.GattService: registerClient() - UUID=8221b81e-9d6a-4976-a6fe-d92378ba5df6
03-23 13:07:34.760  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=8221b81e-9d6a-4976-a6fe-d92378ba5df6, clientIf=5
03-23 13:07:34.760  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-23 13:07:34.760  2152  2216 D BtGatt.GattService: start scan with filters
03-23 13:07:34.761  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:34.761  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-23 13:07:34.761  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:34.764  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:34.765  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-23 13:07:34.765  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:34.765  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.767  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:34.767  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.767  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-23 13:07:34.767  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-23 13:07:34.770  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:34.770  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:34.771  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:34.771  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:34.772  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:34.772  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:34.772  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:07:34.772  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:07:34.772  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:34.773  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-23 13:07:34.773  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:34.773  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:34.773  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:34.773  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.773  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:34.773  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-23 13:07:34.778  2152  2169 D BtGatt.GattService: registerClient() - UUID=9177cd43-6964-43f7-9745-a494e06d0dce
03-23 13:07:34.779  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=9177cd43-6964-43f7-9745-a494e06d0dce, clientIf=6
,03-23 13:07:34.779  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:34.780  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-23 13:07:34.783  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-23 13:07:34.786  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-23 13:07:34.789  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-23 13:07:34.790  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:07:34.792  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:34.793  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:34.794  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:34.794  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.794  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:34.794  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:34.794  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:34.794  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:34.794  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:34.794  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:34.794  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:34.796  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:34.796  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.797  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:34.798  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:34.798  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.800  2152  2169 D BtGatt.GattService: registerClient() - UUID=2ada7fd0-3042-49ff-9b4f-e422a6c4ea83
03-23 13:07:34.800  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=2ada7fd0-3042-49ff-9b4f-e422a6c4ea83, clientIf=5
03-23 13:07:34.801  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:34.801  2152  2216 D BtGatt.GattService: start scan with filters
03-23 13:07:34.803  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-23 13:07:34.803  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-23 13:07:34.803  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-23 13:07:34.805  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:34.805  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.806  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:34.807  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:34.807  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.807  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:34.807  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:34.807  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:34.809  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:34.809  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.811  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:34.811  2152  2214 D BtGatt.GattService: Client app is not null!
03-23 13:07:34.813  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-23 13:07:34.813  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-23 13:07:34.813  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-23 13:07:34.813  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-23 13:07:34.813  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-23 13:07:34.813  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-23 13:07:34.814  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-23 13:07:34.814  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:34.814  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:34.814  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.814  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-23 13:07:34.814  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-23 13:07:34.822  2152  2216 D BtGatt.GattService: registerClient() - UUID=2b0689eb-9d7b-4fc1-9f12-f206f5725c96
03-23 13:07:34.822  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=2b0689eb-9d7b-4fc1-9f12-f206f5725c96, clientIf=6
03-23 13:07:34.822  3277  3294 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-23 13:07:34.824  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-23 13:07:34.826  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
03-23 13:07:34.829  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-23 13:07:34.832  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-23 13:07:34.833  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-23 13:07:34.834  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
03-23 13:07:34.835  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
03-23 13:07:34.835  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:34.836  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:34.836  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:34.836  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-23 13:07:34.836  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-23 13:07:34.836  3277  3277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-23 13:07:34.837  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:34.837  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.837  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-23 13:07:34.839  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-23 13:07:34.839  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.839  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-23 13:07:34.840  2152  2216 D BtGatt.GattService: registerClient() - UUID=f3eba939-9d74-4e06-a6fb-a0f246b73f28
03-23 13:07:34.840  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=f3eba939-9d74-4e06-a6fb-a0f246b73f28, clientIf=5
03-23 13:07:34.840  3277  3294 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-23 13:07:34.840  2152  3870 D BtGatt.GattService: start scan with filters
03-23 13:07:34.841  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:34.841  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.844  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-23 13:07:34.844  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-23 13:07:34.844  2152  2225 D BtGatt.ScanManager: handling starting scan
03-23 13:07:34.844  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:34.844  3277  3277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-23 13:07:34.844  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-23 13:07:34.844  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:34.844  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-23 13:07:34.846  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-23 13:07:34.846  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.847  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-23 13:07:34.847  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.847  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-23 13:07:34.848  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-23 13:07:34.850  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-23 13:07:34.850  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:34.851  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-23 13:07:34.851  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:35.355  2152  2152 D BtGatt.ScanManager: awakened up at time 273256
,03-23 13:07:35.357  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:35.420  2152  2226 I art     : Explicit concurrent mark sweep GC freed 30493(1700KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 22MB/37MB, paused 1.555ms total 58.989ms
,03-23 13:07:35.426  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-23 13:07:35.426  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:35.426  2152  2214 D BtGatt.GattService: current time is 273327804112
03-23 13:07:35.426  2152  2214 D BtGatt.GattService: Batch record : [119, 63, -3, -90, 84, 94, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:07:35.427  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-23 13:07:35.427  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:07:35.430  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-23 13:07:35.431  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-23 13:07:36.440  2152  2152 D BtGatt.ScanManager: awakened up at time 274341
,03-23 13:07:36.442  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:36.451  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-23 13:07:36.451  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:36.451  2152  2214 D BtGatt.GattService: current time is 274352821091
,03-23 13:07:36.452  2152  2214 D BtGatt.GattService: Batch record : [119, 63, -3, -90, 84, 94, 1, -128, -79, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-23 13:07:36.452  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-23 13:07:36.453  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-23 13:07:36.456  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-23 13:07:36.456  3277  3277 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-23 13:07:36.572  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-23 13:07:36.572  3277  3337 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-23 13:07:36.573  3277  3337 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 379)
03-23 13:07:36.573  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 379)
,03-23 13:07:36.573  3277  3874 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Receiver): bt socket closed, read return: -1
03-23 13:07:36.574  3277  3874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 381, name: Receiver)
03-23 13:07:36.579  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-23 13:07:36.579  3277  3337 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-23 13:07:36.579  3277  3337 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 381
03-23 13:07:36.580  3277  3337 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-23 13:07:36.580  3277  3337 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 380
03-23 13:07:36.580  3277  3337 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 379)
,03-23 13:07:36.581  3277  3873 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Sender): Socket closed
03-23 13:07:36.581  3277  3873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 380, name: Sender)
03-23 13:07:36.581  3277  3337 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 379)
03-23 13:07:36.582  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-23 13:07:36.582  3277  3337 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-23 13:07:36.582  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-23 13:07:36.582  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-23 13:07:36.583  3277  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-23 13:07:36.584  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-23 13:07:36.584  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-23 13:07:36.584  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-23 13:07:36.584  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-23 13:07:36.584  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-23 13:07:36.584  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-23 13:07:36.584  3277  3868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-23 13:07:36.584  3277  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-23 13:07:36.585  3277  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-23 13:07:36.587  2152  3870 D BtGatt.GattService: stopScan() - queue size =1
,03-23 13:07:36.591  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-23 13:07:36.591  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-23 13:07:36.591  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-23 13:07:36.591  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-23 13:07:36.592  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-23 13:07:36.592  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-23 13:07:36.592  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:36.592  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-23 13:07:36.594  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-23 13:07:36.594  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:36.595  2152  2225 D BtGatt.ScanManager: stopping BLe Batch,
03-23 13:07:36.595  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-23 13:07:36.596  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-23 13:07:36.597  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-23 13:07:36.597  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-23 13:07:36.597  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-23 13:07:36.600  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-23 13:07:36.600  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-23 13:07:36.601  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-23 13:07:36.601  2152  2214 D BtGatt.GattService: Client app is not null!
,03-23 13:07:36.603  2152  3870 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-23 13:07:36.604  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-23 13:07:36.604  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-23 13:07:36.604  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-23 13:07:36.604  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-23 13:07:36.604  3277  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-23 13:07:36.604  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-23 13:07:36.604  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-23 13:07:36.604  3277  3337 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-23 13:07:36.606  3277  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-23 13:07:36.606  3277  3337 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-23 13:07:36.606  3277  3337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:36.606  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-23 13:07:36.606  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-23 13:07:36.606  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-23 13:07:36.614  3277  3277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-23 13:07:36.614   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 13:07:36.623  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-23 13:07:36.623  3277  3277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-23 13:07:36.623  3277  3277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-23 13:07:36.627  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-23 13:07:36.627  3277  3277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-23 13:07:36.627  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-23 13:07:36.627  3277  3277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-23 13:07:36.627  3277  3277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-23 13:07:36.627  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-23 13:07:36.627  3277  3277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-23 13:07:36.627  3277  3277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-23 13:07:36.629  3277  3337 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-23 13:07:36.629  3277  3337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-23 13:07:36.629  3277  3337 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-23 13:07:36.632  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-23 13:07:36.632  3277  3337 I jxcore-log: 
,03-23 13:07:36.634  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-23 13:07:36.634  3277  3337 I jxcore-log: 
,03-23 13:07:36.635  3277  3337 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-23 13:07:36.635  3277  3337 I jxcore-log: 
,03-23 13:07:36.645  3277  3337 I jxcore-log: # setup
,03-23 13:07:36.645  3277  3337 I jxcore-log: 
,03-23 13:07:36.836  2152  2226 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,03-23 13:07:36.837  3277  3337 I jxcore-log: # 56. Test BEACONS_RETRIEVED_AND_PARSED locally
03-23 13:07:36.837  3277  3337 I jxcore-log: 
,03-23 13:07:38.683  3277  3337 I jxcore-log: ok 214 peerIdentifier should be hello,
03-23 13:07:38.683  3277  3337 I jxcore-log: ,
03-23 13:07:38.683  3277  3337 I jxcore-log: ok 215 Response should be BEACONS_RETRIEVED_AND_PARSED
03-23 13:07:38.683  3277  3337 I jxcore-log: 
03-23 13:07:38.684  3277  3337 I jxcore-log: ok 216 good beacon
03-23 13:07:38.684  3277  3337 I jxcore-log: 
03-23 13:07:38.685  3277  3337 I jxcore-log: ok 217 good preAmble,
03-23 13:07:38.685  3277  3337 I jxcore-log: 
03-23 13:07:38.685  3277  3337 I jxcore-log: ok 218 public keys match!
,03-23 13:07:38.685  3277  3337 I jxcore-log: 
03-23 13:07:38.687  3277  3337 I jxcore-log: ok 219 must return null after successful call
03-23 13:07:38.687  3277  3337 I jxcore-log: 
,03-23 13:07:38.714  3277  3337 I jxcore-log: # teardown
,03-23 13:07:38.714  3277  3337 I jxcore-log: 
,03-23 13:07:38.944  3277  3337 I jxcore-log: # setup
03-23 13:07:38.944  3277  3337 I jxcore-log: 
,03-23 13:07:39.234  3277  3337 I jxcore-log: # 57. Test HTTP_BAD_RESPONSE locally
03-23 13:07:39.234  3277  3337 I jxcore-log: 
,03-23 13:07:39.410  3277  3337 I jxcore-log: ok 220 Response should be HTTP_BAD_RESPONSE
03-23 13:07:39.410  3277  3337 I jxcore-log: 
,03-23 13:07:39.412  3277  3337 I jxcore-log: ok 221 must return null after successful call
03-23 13:07:39.412  3277  3337 I jxcore-log: 
,03-23 13:07:39.421  3277  3337 I jxcore-log: # teardown
03-23 13:07:39.421  3277  3337 I jxcore-log: 
,03-23 13:07:40.067  3277  3337 I jxcore-log: # setup
03-23 13:07:40.067  3277  3337 I jxcore-log: 
,03-23 13:07:40.285  3277  3337 I jxcore-log: # 58. Test NETWORK_PROBLEM locally,
03-23 13:07:40.285  3277  3337 I jxcore-log: 
,03-23 13:07:41.534  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-23 13:07:41.544  2152  2152 D BluetoothMapService: onReceive
,03-23 13:07:41.574  1513  1513 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
03-23 13:07:41.578  1513  1513 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-23 13:07:43.203  3277  3337 I jxcore-log: ok 222 Response should be NETWORK_PROBLEM
03-23 13:07:43.203  3277  3337 I jxcore-log: 
,03-23 13:07:43.212  3277  3337 I jxcore-log: ok 223 reject reason should be: Could not establish TCP connection
,03-23 13:07:43.212  3277  3337 I jxcore-log: 
,03-23 13:07:43.227  3277  3337 I jxcore-log: # teardown
,03-23 13:07:43.227  3277  3337 I jxcore-log: 
,03-23 13:07:43.331  3277  3337 I jxcore-log: # setup
03-23 13:07:43.331  3277  3337 I jxcore-log: 
,03-23 13:07:44.343  3277  3337 I jxcore-log: # 59. Test timeout locally
,03-23 13:07:44.343  3277  3337 I jxcore-log: 
,03-23 13:07:45.570  3277  3337 I jxcore-log: ok 224 Should be NETWORK_PROBLEM caused by timeout
03-23 13:07:45.570  3277  3337 I jxcore-log: ,
,03-23 13:07:45.573  3277  3337 I jxcore-log: ok 225 reject reason should be Could not establish TCP connection
03-23 13:07:45.573  3277  3337 I jxcore-log: 
,03-23 13:07:45.581  3277  3337 I jxcore-log: # teardown,
03-23 13:07:45.581  3277  3337 I jxcore-log: 
,03-23 13:07:46.691  3277  3337 I jxcore-log: # setup
03-23 13:07:46.691  3277  3337 I jxcore-log: 
,03-23 13:07:47.007  3277  3337 I jxcore-log: # 60. Call the start two times,
03-23 13:07:47.007  3277  3337 I jxcore-log: 
,03-23 13:07:47.172  3277  3337 I jxcore-log: ok 226 Call start once
03-23 13:07:47.172  3277  3337 I jxcore-log: 
,03-23 13:07:47.240  3277  3337 I jxcore-log: ok 227 Response should be BEACONS_RETRIEVED_AND_PARSED
03-23 13:07:47.240  3277  3337 I jxcore-log: 
,03-23 13:07:47.241  3277  3337 I jxcore-log: ok 228 must return null after successful call.
03-23 13:07:47.241  3277  3337 I jxcore-log: 
,03-23 13:07:47.250  3277  3337 I jxcore-log: # teardown
03-23 13:07:47.250  3277  3337 I jxcore-log: 
,03-23 13:07:47.330  3277  3337 I jxcore-log: # setup
03-23 13:07:47.330  3277  3337 I jxcore-log: 
,03-23 13:07:47.564  3277  3337 I jxcore-log: # 61. Call the kill before calling the start
03-23 13:07:47.564  3277  3337 I jxcore-log: 
,03-23 13:07:47.733  3277  3337 I jxcore-log: ok 229 Should be Killed
03-23 13:07:47.733  3277  3337 I jxcore-log: 
,03-23 13:07:47.741  3277  3337 I jxcore-log: ok 230 Start after killed
03-23 13:07:47.741  3277  3337 I jxcore-log: 
,03-23 13:07:47.747  3277  3337 I jxcore-log: # teardown
03-23 13:07:47.747  3277  3337 I jxcore-log: 
,03-23 13:07:47.956  3277  3337 I jxcore-log: # setup,
03-23 13:07:47.956  3277  3337 I jxcore-log: 
,03-23 13:07:48.181  3277  3337 I jxcore-log: # 62. Call the kill immediately after the start
03-23 13:07:48.181  3277  3337 I jxcore-log: 
,03-23 13:07:48.271  3277  3337 I jxcore-log: ok 231 Should be KILLED
03-23 13:07:48.271  3277  3337 I jxcore-log: 
,03-23 13:07:48.272  3277  3337 I jxcore-log: ok 232 must return null after successful kill
03-23 13:07:48.272  3277  3337 I jxcore-log: 
,03-23 13:07:48.277  3277  3337 I jxcore-log: # teardown
03-23 13:07:48.277  3277  3337 I jxcore-log: 
,03-23 13:07:48.481  3277  3337 I jxcore-log: # setup
03-23 13:07:48.481  3277  3337 I jxcore-log: 
,03-23 13:07:48.674  3277  3337 I jxcore-log: # 63. Call the kill while waiting a response from the server
03-23 13:07:48.674  3277  3337 I jxcore-log: 
,03-23 13:07:50.480  3511  3882 V KeepSync: Connecting to GoogleApiClient
,03-23 13:07:50.640  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-23 13:07:50.641  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:07:50.641  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-23 13:07:50.641  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:07:50.651  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: Handling authorization failure,
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178),
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30),
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	,at com.google.android.gms.common.server.o.a(SourceFile:319)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-23 13:07:50.689  1773  3884 E ClientConnectionOperation: 	... 7 more
03-23 13:07:50.698  3511  3882 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-23 13:07:50.709  3511  3882 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:07:50.715  3511  3882 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:07:50.716  3511  3882 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-23 13:07:50.792  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-23 13:07:50.795  3277  3337 I jxcore-log: ok 233 Should be KILLED
,03-23 13:07:50.795  3277  3337 I jxcore-log: 
,03-23 13:07:50.796  3277  3337 I jxcore-log: ok 234 must return null after successful kill
03-23 13:07:50.796  3277  3337 I jxcore-log: 
03-23 13:07:50.797  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-23 13:07:50.797  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:07:50.797  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:07:50.805  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:07:50.812  3277  3337 I jxcore-log: # teardown
,03-23 13:07:50.812  3277  3337 I jxcore-log: 
,03-23 13:07:50.860  3511  3882 E KeepSync: IOException
03-23 13:07:50.860  3511  3882 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858),
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
,03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-23 13:07:50.860  3511  3882 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
,03-23 13:07:50.860  3511  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-23 13:07:50.860  3511  3882 E KeepSync: 	... 10 more
03-23 13:07:50.860  3511  3882 W KeepSync: Sync result 2
03-23 13:07:50.865   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 288319, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:07:50.931  3277  3337 I jxcore-log: # setup
,03-23 13:07:50.931  3277  3337 I jxcore-log: 
,03-23 13:07:51.124  3277  3337 I jxcore-log: # 64. Test to exceed the max content size locally,
03-23 13:07:51.124  3277  3337 I jxcore-log: 
,03-23 13:07:51.295  3277  3337 I jxcore-log: ok 235 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-23 13:07:51.295  3277  3337 I jxcore-log: 
,03-23 13:07:51.300  3277  3337 I jxcore-log: ok 236 must return null after successful call
03-23 13:07:51.300  3277  3337 I jxcore-log: 
,03-23 13:07:51.309  3277  3337 I jxcore-log: # teardown,
03-23 13:07:51.309  3277  3337 I jxcore-log: 
,03-23 13:07:51.444  3277  3337 I jxcore-log: # setup
03-23 13:07:51.444  3277  3337 I jxcore-log: 
,03-23 13:07:51.644  3277  3337 I jxcore-log: # 65. Close the server socket while the client is waiting a response from the server. Local test.
03-23 13:07:51.644  3277  3337 I jxcore-log: 
,03-23 13:07:53.821  3277  3337 I jxcore-log: ok 237 Should be NETWORK_PROBLEM caused closing server socket
03-23 13:07:53.821  3277  3337 I jxcore-log: 
,03-23 13:07:53.823  3277  3337 I jxcore-log: ok 238 Should be Could not establish TCP connection
03-23 13:07:53.823  3277  3337 I jxcore-log: 
,03-23 13:07:53.830  3277  3337 I jxcore-log: # teardown
03-23 13:07:53.830  3277  3337 I jxcore-log: 
,03-23 13:07:53.963  3277  3337 I jxcore-log: # setup
,03-23 13:07:53.963  3277  3337 I jxcore-log: 
,03-23 13:07:54.198  3277  3337 I jxcore-log: # 66. Close the client socket while the client is waiting a response from the server. Local test.
03-23 13:07:54.198  3277  3337 I jxcore-log: 
,03-23 13:07:56.421  3277  3337 I jxcore-log: ok 239 Should be NETWORK_PROBLEM caused closing client socket
03-23 13:07:56.421  3277  3337 I jxcore-log: 
,03-23 13:07:56.428  3277  3337 I jxcore-log: ok 240 Should be Could not establish TCP connection
03-23 13:07:56.428  3277  3337 I jxcore-log: 
,03-23 13:07:56.439  3277  3337 I jxcore-log: # teardown
03-23 13:07:56.439  3277  3337 I jxcore-log: 
,03-23 13:07:56.633  3277  3337 I jxcore-log: # setup
03-23 13:07:56.633  3277  3337 I jxcore-log: 
,03-23 13:07:56.771  3277  3337 I jxcore-log: # 67. #generatePreambleAndBeacons bad args,
03-23 13:07:56.771  3277  3337 I jxcore-log: 
,03-23 13:07:56.968  3277  3337 I jxcore-log: ok 241 publicKeysToNotify cannot be null
03-23 13:07:56.968  3277  3337 I jxcore-log: 
,03-23 13:07:56.971  3277  3337 I jxcore-log: ok 242 ecdh for local device cannot be null
03-23 13:07:56.971  3277  3337 I jxcore-log: 
,03-23 13:07:56.974  3277  3337 I jxcore-log: ok 243 milliseconds cannot be less than 0
03-23 13:07:56.974  3277  3337 I jxcore-log: 
,03-23 13:07:56.975  3277  3337 I jxcore-log: ok 244 milliseconds cannot be 0
03-23 13:07:56.975  3277  3337 I jxcore-log: 
,03-23 13:07:56.977  3277  3337 I jxcore-log: ok 245 milliseconds cannot be greater than one_day
03-23 13:07:56.977  3277  3337 I jxcore-log: 
,03-23 13:07:56.980  3277  3337 I jxcore-log: # teardown
03-23 13:07:56.980  3277  3337 I jxcore-log: 
,03-23 13:07:57.241  3277  3337 I jxcore-log: # setup
03-23 13:07:57.241  3277  3337 I jxcore-log: 
,03-23 13:07:57.412  3277  3337 I jxcore-log: # 68. #generatePreambleAndBeacons empty keys to notify
03-23 13:07:57.412  3277  3337 I jxcore-log: 
,03-23 13:07:57.620  3277  3337 I jxcore-log: ok 246 should be equal
03-23 13:07:57.620  3277  3337 I jxcore-log: 
,03-23 13:07:57.624  3277  3337 I jxcore-log: # teardown
,03-23 13:07:57.624  3277  3337 I jxcore-log: 
,03-23 13:07:57.772  3277  3337 I jxcore-log: # setup
,03-23 13:07:57.772  3277  3337 I jxcore-log: 
,03-23 13:07:57.892  3277  3337 I jxcore-log: # 69. #generatePreambleAndBeacons multiple keys to notify
,03-23 13:07:57.892  3277  3337 I jxcore-log: 
,03-23 13:07:58.296  3277  3337 I jxcore-log: ok 247 should be equal
,03-23 13:07:58.296  3277  3337 I jxcore-log: 
03-23 13:07:58.297  3277  3337 I jxcore-log: ok 248 should be equal
03-23 13:07:58.297  3277  3337 I jxcore-log: 
03-23 13:07:58.297  3277  3337 I jxcore-log: ok 249 (unnamed assert)
03-23 13:07:58.297  3277  3337 I jxcore-log: 
,03-23 13:07:58.297  3277  3337 I jxcore-log: ok 250 should be equal
03-23 13:07:58.297  3277  3337 I jxcore-log: 
,03-23 13:07:58.301  3277  3337 I jxcore-log: # teardown
03-23 13:07:58.301  3277  3337 I jxcore-log: 
,03-23 13:07:58.441  3277  3337 I jxcore-log: # setup
,03-23 13:07:58.441  3277  3337 I jxcore-log: 
,03-23 13:07:58.689  3277  3337 I jxcore-log: # 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-23 13:07:58.689  3277  3337 I jxcore-log: 
,03-23 13:07:58.851  3277  3337 I jxcore-log: ok 251 should throw
03-23 13:07:58.851  3277  3337 I jxcore-log: 
,03-23 13:07:58.854  3277  3337 I jxcore-log: # teardown
03-23 13:07:58.854  3277  3337 I jxcore-log: 
,03-23 13:07:59.001  3277  3337 I jxcore-log: # setup
03-23 13:07:59.001  3277  3337 I jxcore-log: 
,03-23 13:07:59.094  3277  3337 I jxcore-log: # 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-23 13:07:59.094  3277  3337 I jxcore-log: 
,03-23 13:07:59.211  3277  3337 I jxcore-log: ok 252 Preamble expiration must be a 64 bit integer
03-23 13:07:59.211  3277  3337 I jxcore-log: 
,03-23 13:07:59.214  3277  3337 I jxcore-log: # teardown
03-23 13:07:59.214  3277  3337 I jxcore-log: 
,03-23 13:07:59.342  3277  3337 I jxcore-log: # setup
03-23 13:07:59.342  3277  3337 I jxcore-log: 
,03-23 13:07:59.518  3277  3337 I jxcore-log: # 72. #parseBeacons expiration out of range lower
03-23 13:07:59.518  3277  3337 I jxcore-log: 
,03-23 13:07:59.701  3277  3337 I jxcore-log: ok 253 Expiration out of range
03-23 13:07:59.701  3277  3337 I jxcore-log: 
,03-23 13:07:59.704  3277  3337 I jxcore-log: # teardown
03-23 13:07:59.704  3277  3337 I jxcore-log: 
,03-23 13:07:59.776  3277  3337 I jxcore-log: # setup
03-23 13:07:59.776  3277  3337 I jxcore-log: 
,03-23 13:07:59.926  3277  3337 I jxcore-log: # 73. #parseBeacons expiration out of range lower
03-23 13:07:59.926  3277  3337 I jxcore-log: 
,03-23 13:08:00.093  3277  3337 I jxcore-log: ok 254 Expiration out of range
03-23 13:08:00.093  3277  3337 I jxcore-log: 
,03-23 13:08:00.105  3277  3337 I jxcore-log: # teardown
03-23 13:08:00.105  3277  3337 I jxcore-log: 
,03-23 13:08:00.211  3277  3337 I jxcore-log: # setup
03-23 13:08:00.211  3277  3337 I jxcore-log: 
,03-23 13:08:00.325  3277  3337 I jxcore-log: # 74. #parseBeacons no beacons returns null
03-23 13:08:00.325  3277  3337 I jxcore-log: 
,03-23 13:08:00.465  3277  3337 I jxcore-log: ok 255 should be equal
03-23 13:08:00.465  3277  3337 I jxcore-log: 
,03-23 13:08:00.468  3277  3337 I jxcore-log: # teardown
03-23 13:08:00.468  3277  3337 I jxcore-log: 
,03-23 13:08:00.551  3277  3337 I jxcore-log: # setup
03-23 13:08:00.551  3277  3337 I jxcore-log: 
,03-23 13:08:00.647  3277  3337 I jxcore-log: # 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-23 13:08:00.647  3277  3337 I jxcore-log: 
,03-23 13:08:00.841  3277  3337 I jxcore-log: ok 256 Malformed encrypted beacon key ID
03-23 13:08:00.841  3277  3337 I jxcore-log: 
,03-23 13:08:00.844  3277  3337 I jxcore-log: # teardown
03-23 13:08:00.844  3277  3337 I jxcore-log: 
,03-23 13:08:00.976  3277  3337 I jxcore-log: # setup
03-23 13:08:00.976  3277  3337 I jxcore-log: 
,03-23 13:08:01.078  3277  3337 I jxcore-log: # 76. #parseBeacons addressBookCallback fails decrypt
03-23 13:08:01.078  3277  3337 I jxcore-log: 
,03-23 13:08:01.312  3277  3337 I jxcore-log: ok 257 should be equal
03-23 13:08:01.312  3277  3337 I jxcore-log: 
,03-23 13:08:01.314  3277  3337 I jxcore-log: # teardown
03-23 13:08:01.314  3277  3337 I jxcore-log: 
,03-23 13:08:01.443  3277  3337 I jxcore-log: # setup
03-23 13:08:01.443  3277  3337 I jxcore-log: 
,03-23 13:08:01.631  3277  3337 I jxcore-log: # 77. #parseBeacons addressBookCallback returns no matches
03-23 13:08:01.631  3277  3337 I jxcore-log: 
,03-23 13:08:01.998  3277  3337 I jxcore-log: ok 258 should be equal
03-23 13:08:01.998  3277  3337 I jxcore-log: 
03-23 13:08:01.999  3277  3337 I jxcore-log: ok 259 should be equal
03-23 13:08:01.999  3277  3337 I jxcore-log: 
,03-23 13:08:02.001  3277  3337 I jxcore-log: # teardown
03-23 13:08:02.001  3277  3337 I jxcore-log: 
,03-23 13:08:02.697  3277  3337 I jxcore-log: # setup
03-23 13:08:02.697  3277  3337 I jxcore-log: 
,03-23 13:08:05.023  3277  3337 I jxcore-log: # 78. #parseBeacons addressBookCallback returns spurious match
03-23 13:08:05.023  3277  3337 I jxcore-log: 
,03-23 13:08:05.371  3277  3337 I jxcore-log: ok 260 should be equal
03-23 13:08:05.371  3277  3337 I jxcore-log: 
03-23 13:08:05.371  3277  3337 I jxcore-log: ok 261 should be equal
03-23 13:08:05.371  3277  3337 I jxcore-log: 
,03-23 13:08:05.374  3277  3337 I jxcore-log: # teardown,
03-23 13:08:05.374  3277  3337 I jxcore-log: 
,03-23 13:08:06.974  3277  3337 I jxcore-log: # setup
03-23 13:08:06.974  3277  3337 I jxcore-log: 
,03-23 13:08:07.162  3277  3337 I jxcore-log: # 79. #parseBeacons addressBookCallback returns public key,
,03-23 13:08:07.162  3277  3337 I jxcore-log: 
,03-23 13:08:07.793  3277  3337 I jxcore-log: ok 262 right number of calls to address book,
03-23 13:08:07.793  3277  3337 I jxcore-log: 
,03-23 13:08:07.795  3277  3337 I jxcore-log: ok 263 good preAmble
03-23 13:08:07.795  3277  3337 I jxcore-log: 
03-23 13:08:07.795  3277  3337 I jxcore-log: ok 264 good unencryptedKeyId
03-23 13:08:07.795  3277  3337 I jxcore-log: 
,03-23 13:08:07.795  3277  3337 I jxcore-log: ok 265 good beacon
03-23 13:08:07.795  3277  3337 I jxcore-log: 
03-23 13:08:07.797  3277  3337 I jxcore-log: # teardown
03-23 13:08:07.797  3277  3337 I jxcore-log: 
,03-23 13:08:07.980  3277  3337 I jxcore-log: # setup
,03-23 13:08:07.980  3277  3337 I jxcore-log: 
,03-23 13:08:08.105  3277  3337 I jxcore-log: # 80. validate generatePskIdentityField,
03-23 13:08:08.105  3277  3337 I jxcore-log: 
,03-23 13:08:08.216  3277  3337 I jxcore-log: ok 266 decoded buffers match
03-23 13:08:08.216  3277  3337 I jxcore-log: 
,03-23 13:08:08.222  3277  3337 I jxcore-log: # teardown
03-23 13:08:08.222  3277  3337 I jxcore-log: 
,03-23 13:08:08.329  3277  3337 I jxcore-log: # setup
03-23 13:08:08.329  3277  3337 I jxcore-log: 
,03-23 13:08:08.572  3277  3337 I jxcore-log: # 81. validate generatePskSecret
03-23 13:08:08.572  3277  3337 I jxcore-log: 
,03-23 13:08:08.724  3277  3337 I jxcore-log: ok 267 secrets match
03-23 13:08:08.724  3277  3337 I jxcore-log: 
,03-23 13:08:08.726  3277  3337 I jxcore-log: # teardown
03-23 13:08:08.726  3277  3337 I jxcore-log: 
,03-23 13:08:08.832  3277  3337 I jxcore-log: # setup
03-23 13:08:08.832  3277  3337 I jxcore-log: 
,03-23 13:08:09.022  3277  3337 I jxcore-log: # 82. Start and stop ThaliNotificationServer
03-23 13:08:09.022  3277  3337 I jxcore-log: 
,03-23 13:08:09.174  3277  3337 I jxcore-log: ok 268 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-23 13:08:09.174  3277  3337 I jxcore-log: 
,03-23 13:08:09.175  3277  3337 I jxcore-log: ok 269 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-23 13:08:09.175  3277  3337 I jxcore-log: 
03-23 13:08:09.176  3277  3337 I jxcore-log: # teardown
03-23 13:08:09.176  3277  3337 I jxcore-log: 
,03-23 13:08:09.296  3277  3337 I jxcore-log: # setup
03-23 13:08:09.296  3277  3337 I jxcore-log: 
,03-23 13:08:09.426  3277  3337 I jxcore-log: # 83. Pass an empty array to ThaliNotificationServer.start
03-23 13:08:09.426  3277  3337 I jxcore-log: 
,03-23 13:08:09.554  3277  3337 I jxcore-log: ok 270 StartUpdateAdvertisingAndListening should not be called
03-23 13:08:09.554  3277  3337 I jxcore-log: 
,03-23 13:08:09.569  3277  3337 I jxcore-log: ok 271 ThaliMobile.StopAdvertisingAndListening should be called once
03-23 13:08:09.569  3277  3337 I jxcore-log: 
,03-23 13:08:09.612  3277  3337 I jxcore-log: ok 272 no error
03-23 13:08:09.612  3277  3337 I jxcore-log: 
,03-23 13:08:09.612  3277  3337 I jxcore-log: ok 273 should be 204
03-23 13:08:09.612  3277  3337 I jxcore-log: 
03-23 13:08:09.617  3277  3337 I jxcore-log: # teardown
03-23 13:08:09.617  3277  3337 I jxcore-log: 
,03-23 13:08:09.744  3277  3337 I jxcore-log: # setup
03-23 13:08:09.744  3277  3337 I jxcore-log: 
,03-23 13:08:09.884  3277  3337 I jxcore-log: # 84. Pass a string to ThaliNotificationServer.start
03-23 13:08:09.884  3277  3337 I jxcore-log: 
,03-23 13:08:09.980  3277  3337 I jxcore-log: ok 274 StartUpdateAdvertisingAndListening should not be called
03-23 13:08:09.980  3277  3337 I jxcore-log: 
,03-23 13:08:09.982  3277  3337 I jxcore-log: # teardown
03-23 13:08:09.982  3277  3337 I jxcore-log: 
,03-23 13:08:10.062  3277  3337 I jxcore-log: # setup
03-23 13:08:10.062  3277  3337 I jxcore-log: 
,03-23 13:08:10.191  3277  3337 I jxcore-log: # 85. Pass an empty parameter to ThaliNotificationServer.start
03-23 13:08:10.191  3277  3337 I jxcore-log: 
,03-23 13:08:10.284  3277  3337 I jxcore-log: ok 275 StartUpdateAdvertisingAndListening should not be called
03-23 13:08:10.284  3277  3337 I jxcore-log: 
,03-23 13:08:10.286  3277  3337 I jxcore-log: # teardown
03-23 13:08:10.286  3277  3337 I jxcore-log: 
,03-23 13:08:10.378  3277  3337 I jxcore-log: # setup
03-23 13:08:10.378  3277  3337 I jxcore-log: 
,03-23 13:08:10.506  3277  3337 I jxcore-log: # 86. Make an HTTP request to /NotificationBeacons
03-23 13:08:10.506  3277  3337 I jxcore-log: 
,03-23 13:08:10.728  3277  3337 I jxcore-log: ok 276 no error
03-23 13:08:10.728  3277  3337 I jxcore-log: 
,03-23 13:08:10.728  3277  3337 I jxcore-log: ok 277 should be 200
03-23 13:08:10.728  3277  3337 I jxcore-log: 
03-23 13:08:10.729  3277  3337 I jxcore-log: ok 278 should be equal
03-23 13:08:10.729  3277  3337 I jxcore-log: 
03-23 13:08:10.729  3277  3337 I jxcore-log: ok 279 should be equal
03-23 13:08:10.729  3277  3337 I jxcore-log: 
,03-23 13:08:10.745  3277  3337 I jxcore-log: ok 280 (unnamed assert)
03-23 13:08:10.745  3277  3337 I jxcore-log: 
,03-23 13:08:10.772  3277  3337 I jxcore-log: ok 281 no error
03-23 13:08:10.772  3277  3337 I jxcore-log: 
,03-23 13:08:10.772  3277  3337 I jxcore-log: ok 282 should be 204
03-23 13:08:10.772  3277  3337 I jxcore-log: 
,03-23 13:08:10.777  3277  3337 I jxcore-log: # teardown
03-23 13:08:10.777  3277  3337 I jxcore-log: 
,03-23 13:08:10.931  3277  3337 I jxcore-log: # setup
03-23 13:08:10.931  3277  3337 I jxcore-log: 
,03-23 13:08:11.520  3277  3337 I jxcore-log: # 87. Make an HTTP request to /NotificationBeacons (no keys)
03-23 13:08:11.520  3277  3337 I jxcore-log: 
,03-23 13:08:11.655  3277  3337 I jxcore-log: ok 283 error should be null
03-23 13:08:11.655  3277  3337 I jxcore-log: 
,03-23 13:08:11.656  3277  3337 I jxcore-log: ok 284 should be 204
03-23 13:08:11.656  3277  3337 I jxcore-log: 
,03-23 13:08:11.662  3277  3337 I jxcore-log: # teardown
03-23 13:08:11.662  3277  3337 I jxcore-log: 
,03-23 13:08:12.191  3277  3337 I jxcore-log: # setup
03-23 13:08:12.191  3277  3337 I jxcore-log: ,
,03-23 13:08:12.324  3277  3337 I jxcore-log: # 88. Make an HTTP request to /NotificationBeaconsbefore calling start
03-23 13:08:12.324  3277  3337 I jxcore-log: 
,03-23 13:08:12.463  3277  3337 I jxcore-log: ok 285 should be 404
03-23 13:08:12.463  3277  3337 I jxcore-log: 
,03-23 13:08:12.469  3277  3337 I jxcore-log: # teardown
03-23 13:08:12.469  3277  3337 I jxcore-log: 
,03-23 13:08:12.562  3277  3337 I jxcore-log: # setup
03-23 13:08:12.562  3277  3337 I jxcore-log: ,
,03-23 13:08:12.664  3277  3337 I jxcore-log: # 89. #testThaliPeerAction - test getters
03-23 13:08:12.664  3277  3337 I jxcore-log: 
,03-23 13:08:12.764  3277  3337 I jxcore-log: ok 286 getPeerIdentifier
03-23 13:08:12.764  3277  3337 I jxcore-log: 
,03-23 13:08:12.765  3277  3337 I jxcore-log: ok 287 getConnectionType
03-23 13:08:12.765  3277  3337 I jxcore-log: 
03-23 13:08:12.767  3277  3337 I jxcore-log: ok 288 getActionType
03-23 13:08:12.767  3277  3337 I jxcore-log: 
,03-23 13:08:12.769  3277  3337 I jxcore-log: ok 289 getActionState
03-23 13:08:12.769  3277  3337 I jxcore-log: 
,03-23 13:08:12.776  3277  3337 I jxcore-log: # teardown
03-23 13:08:12.776  3277  3337 I jxcore-log: 
,03-23 13:08:12.891  3277  3337 I jxcore-log: # setup
03-23 13:08:12.891  3277  3337 I jxcore-log: 
,03-23 13:08:13.102  3277  3337 I jxcore-log: # 90. #testThaliPeerAction - start and kill
03-23 13:08:13.102  3277  3337 I jxcore-log: 
,03-23 13:08:13.262  3277  3337 I jxcore-log: ok 290 initial state
03-23 13:08:13.262  3277  3337 I jxcore-log: 
,03-23 13:08:13.266  3277  3337 I jxcore-log: ok 291 after start
03-23 13:08:13.266  3277  3337 I jxcore-log: 
03-23 13:08:13.267  3277  3337 I jxcore-log: ok 292 after kill
03-23 13:08:13.267  3277  3337 I jxcore-log: 
,03-23 13:08:13.272  3277  3337 I jxcore-log: # teardown
03-23 13:08:13.272  3277  3337 I jxcore-log: 
,03-23 13:08:13.392  3277  3337 I jxcore-log: # setup
03-23 13:08:13.392  3277  3337 I jxcore-log: 
,03-23 13:08:13.741  3277  3337 I jxcore-log: # 91. #testThaliPeerAction - double start
03-23 13:08:13.741  3277  3337 I jxcore-log: 
,03-23 13:08:13.872  3277  3337 I jxcore-log: ok 293 should be equal
03-23 13:08:13.872  3277  3337 I jxcore-log: 
,03-23 13:08:13.874  3277  3337 I jxcore-log: # teardown
03-23 13:08:13.874  3277  3337 I jxcore-log: 
,03-23 13:08:14.181  3277  3337 I jxcore-log: # setup
03-23 13:08:14.181  3277  3337 I jxcore-log: 
,03-23 13:08:14.443  3277  3337 I jxcore-log: # 92. #testThaliPeerAction - start after kill
03-23 13:08:14.443  3277  3337 I jxcore-log: 
,03-23 13:08:14.580  3277  3337 I jxcore-log: ok 294 clean kill
03-23 13:08:14.580  3277  3337 I jxcore-log: 
,03-23 13:08:14.587  3277  3337 I jxcore-log: ok 295 should be equal
03-23 13:08:14.587  3277  3337 I jxcore-log: 
,03-23 13:08:14.592  3277  3337 I jxcore-log: # teardown
03-23 13:08:14.592  3277  3337 I jxcore-log: 
,03-23 13:08:14.731  3277  3337 I jxcore-log: # setup
03-23 13:08:14.731  3277  3337 I jxcore-log: 
,03-23 13:08:14.862  3277  3337 I jxcore-log: # 93. #testThaliPeerAction - make sure ids are unique
03-23 13:08:14.862  3277  3337 I jxcore-log: 
,03-23 13:08:14.983  3277  3337 I jxcore-log: ok 296 should not be equal
03-23 13:08:14.983  3277  3337 I jxcore-log: 
,03-23 13:08:14.991  3277  3337 I jxcore-log: # teardown
03-23 13:08:14.991  3277  3337 I jxcore-log: 
,03-23 13:08:15.086  3277  3337 I jxcore-log: # setup
03-23 13:08:15.086  3277  3337 I jxcore-log: ,
,03-23 13:08:15.236  3277  3337 I jxcore-log: # 94. Test PeerConnectionInformation basics
03-23 13:08:15.236  3277  3337 I jxcore-log: 
,03-23 13:08:15.338  3277  3337 I jxcore-log: ok 297 getHostAddress works,
,03-23 13:08:15.338  3277  3337 I jxcore-log: ,
,03-23 13:08:15.339  3277  3337 I jxcore-log: ok 298 getPortNumber works,
,03-23 13:08:15.339  3277  3337 I jxcore-log: 
03-23 13:08:15.341  3277  3337 I jxcore-log: ok 299 getSuggestedTCPTimeout works
03-23 13:08:15.341  3277  3337 I jxcore-log: 
03-23 13:08:15.350  3277  3337 I jxcore-log: # teardown
03-23 13:08:15.350  3277  3337 I jxcore-log: 
,03-23 13:08:15.476  3277  3337 I jxcore-log: # setup
03-23 13:08:15.476  3277  3337 I jxcore-log: 
,03-23 13:08:15.598  3277  3337 I jxcore-log: # 95. Test PeerDictionary basic functionality
03-23 13:08:15.598  3277  3337 I jxcore-log: 
,03-23 13:08:15.744  3277  3337 I jxcore-log: ok 300 Entry counter must be 1
03-23 13:08:15.744  3277  3337 I jxcore-log: 
,03-23 13:08:15.744  3277  3337 I jxcore-log: ok 301 Size must be 1
03-23 13:08:15.744  3277  3337 I jxcore-log: 
03-23 13:08:15.745  3277  3337 I jxcore-log: ok 302 Entry counter must be 2
,03-23 13:08:15.745  3277  3337 I jxcore-log: 
03-23 13:08:15.745  3277  3337 I jxcore-log: ok 303 Size must be 2
03-23 13:08:15.745  3277  3337 I jxcore-log: 
,03-23 13:08:15.752  3277  3337 I jxcore-log: ok 304 Entry2 should not be found
,03-23 13:08:15.752  3277  3337 I jxcore-log: 
03-23 13:08:15.753  3277  3337 I jxcore-log: ok 305 Size must be 1
03-23 13:08:15.753  3277  3337 I jxcore-log: 
,03-23 13:08:15.753  3277  3337 I jxcore-log: ok 306 Size must be 0
03-23 13:08:15.753  3277  3337 I jxcore-log: 
,03-23 13:08:15.758  3277  3337 I jxcore-log: ok 307 entry not found must be thrown
03-23 13:08:15.758  3277  3337 I jxcore-log: 
,03-23 13:08:15.762  3277  3337 I jxcore-log: # teardown
03-23 13:08:15.762  3277  3337 I jxcore-log: 
,03-23 13:08:15.881  3277  3337 I jxcore-log: # setup
03-23 13:08:15.881  3277  3337 I jxcore-log: 
,03-23 13:08:15.989  3277  3337 I jxcore-log: # 96. Test PeerDictionary with multiple entries.
03-23 13:08:15.989  3277  3337 I jxcore-log: 
,03-23 13:08:16.851  3277  3337 I jxcore-log: ok 308 Size must be100
03-23 13:08:16.851  3277  3337 I jxcore-log: 
,03-23 13:08:16.854  3277  3337 I jxcore-log: ok 309 Entries between 20 and MAXSIZE + 20 should exist
03-23 13:08:16.854  3277  3337 I jxcore-log: 
,03-23 13:08:17.567  3277  3337 I jxcore-log: ok 310 WAITING state entry should not be removed
03-23 13:08:17.567  3277  3337 I jxcore-log: 
,03-23 13:08:17.570  3277  3337 I jxcore-log: # teardown
03-23 13:08:17.570  3277  3337 I jxcore-log: 
,03-23 13:08:17.711  3277  3337 I jxcore-log: # setup
03-23 13:08:17.711  3277  3337 I jxcore-log: 
,03-23 13:08:17.860  3277  3337 I jxcore-log: # 97. RESOLVED entries are removed before WAITING state entry.
03-23 13:08:17.860  3277  3337 I jxcore-log: 
,03-23 13:08:18.670  3277  3337 I jxcore-log: ok 311 Entries between 6 and MAXSIZE + 4 should exist,
03-23 13:08:18.670  3277  3337 I jxcore-log: 
03-23 13:08:18.670  3277  3337 I jxcore-log: ok 312 Size should be MAXSIZE
03-23 13:08:18.670  3277  3337 I jxcore-log: 
03-23 13:08:18.670  3277  3337 I jxcore-log: ok 313 Size should be MAXSIZE+6
03-23 13:08:18.670  3277  3337 I jxcore-log: 
03-23 13:08:18.672  3277  3337 I jxcore-log: # teardown,
03-23 13:08:18.672  3277  3337 I jxcore-log: 
,03-23 13:08:18.814  3277  3337 I jxcore-log: # setup,
03-23 13:08:18.814  3277  3337 I jxcore-log: 
,03-23 13:08:18.943  3277  3337 I jxcore-log: # 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.,
03-23 13:08:18.943  3277  3337 I jxcore-log: 
,03-23 13:08:19.758  3277  3337 I jxcore-log: ok 314 WAITING state entry should not be removed
03-23 13:08:19.758  3277  3337 I jxcore-log: 
,03-23 13:08:19.759  3277  3337 I jxcore-log: ok 315 Waiting entries between 6 and MAXSIZE + 4 should exist
03-23 13:08:19.759  3277  3337 I jxcore-log: 
03-23 13:08:19.759  3277  3337 I jxcore-log: ok 316 Size should be MAXSIZE,
03-23 13:08:19.759  3277  3337 I jxcore-log: 
03-23 13:08:19.760  3277  3337 I jxcore-log: ok 317 entryCounter should be MAXSIZE+6
03-23 13:08:19.760  3277  3337 I jxcore-log: 
,03-23 13:08:19.762  3277  3337 I jxcore-log: # teardown,
03-23 13:08:19.762  3277  3337 I jxcore-log: 
,03-23 13:08:19.868  3277  3337 I jxcore-log: # setup
03-23 13:08:19.868  3277  3337 I jxcore-log: 
,03-23 13:08:19.980  3277  3337 I jxcore-log: # 99. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-23 13:08:19.980  3277  3337 I jxcore-log: 
,03-23 13:08:20.489  3459  3896 I BooksSync: Starting books sync for 61035162, extras: ade
,03-23 13:08:20.509  3459  3897 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-23 13:08:20.537  1261  1284 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-23 13:08:20.537  1261  1284 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:08:20.537  1261  1284 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:08:20.537  1261  1284 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:08:20.541  1261  1284 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:08:20.546  1261  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-23 13:08:20.546  1261  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:08:20.546  1261  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:08:20.546  1261  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:08:20.550  1261  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:08:20.563  3106  3895 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-23 13:08:20.563  3106  3895 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jdm.a(PG:82)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jcs.o(PG:406)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jcn.a(PG:1379)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jcs.i(PG:143)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at blb.a(PG:3937)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at czp.a(PG:18188)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at czp.a(PG:9081)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at czq.run(PG:1686)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:08:20.563  3106  3895 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jdj.a(PG:4091)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jdj.a(PG:1125)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jdm.a(PG:77)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	... 12 more
03-23 13:08:20.563  3106  3895 E HttpOperation: Caused by: faj: BadAuthentication
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at fal.a(PG:38)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	at jdj.a(PG:4089)
03-23 13:08:20.563  3106  3895 E HttpOperation: 	... 14 more
,03-23 13:08:20.593  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-23 13:08:20.593  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:08:20.593  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:08:20.593  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:08:20.595  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 13:08:20.599  1261  1283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
03-23 13:08:20.599  1261  1283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-23 13:08:20.599  1261  1283 I GLSUser : [GLSUser] Extracting token using key: Auth
03-23 13:08:20.599  1261  1283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-23 13:08:20.604  1261  1283 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-23 13:08:20.612  3459  3897 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:08:20.612  3106  3895 E HttpOperation: [getmobileexperiments] Unexpected exception
03-23 13:08:20.612  3106  3895 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jdm.a(PG:82)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jcs.o(PG:406)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jcn.a(PG:1379)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jcs.i(PG:143)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at hec.a(PG:42)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at hee.a(PG:102)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at czr.a(PG:65)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at kka.a(PG:108)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at czp.a(PG:19176)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at czp.a(PG:9081)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at czq.run(PG:1686)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:08:20.612  3106  3895 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jdj.a(PG:4091)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jdj.a(PG:1125)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jdm.a(PG:77)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	... 15 more
03-23 13:08:20.612  3106  3895 E HttpOperation: Caused by: faj: BadAuthentication
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at fal.a(PG:38)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	at jdj.a(PG:4089)
03-23 13:08:20.612  3106  3895 E HttpOperation: 	... 17 more
03-23 13:08:20.612  3459  3896 E BooksSync: Soft error
03-23 13:08:20.612  3459  3896 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:08:20.612  3459  3896 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-23 13:08:20.612  3459  3896 E BooksSync: Sync error
03-23 13:08:20.612  3459  3896 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-23 13:08:20.612  3459  3896 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-23 13:08:20.612  3459  3896 I BooksSync: Finished books sync
03-23 13:08:20.612  3106  3895 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-23 13:08:20.612  3106  3895 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jdm.a(PG:82)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jcs.o(PG:406)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jcn.a(PG:1379)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jcs.i(PG:143)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at hec.a(PG:42)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at hee.a(PG:102)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at czr.a(PG:65)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at kka.a(PG:108)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at czp.a(PG:19176)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at czp.a(PG:9081)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at czq.run(PG:1686)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at java.util.concurrent,.Executors$RunnableAdapter.call(Executors.java:422)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jdj.a(PG:4091)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jdj.a(PG:1125)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jdm.a(PG:77)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	... 15 more
03-23 13:08:20.612  3106  3895 E ExperimentLoader: Caused by: faj: BadAuthentication
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at fal.a(PG:38)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	at jdj.a(PG:4089)
03-23 13:08:20.612  3106  3895 E ExperimentLoader: 	... 17 more
,03-23 13:08:20.620   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 290723, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:08:20.699   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 289493, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-23 13:08:20.835  3277  3337 I jxcore-log: ok 318 Kill should be called once
,03-23 13:08:20.835  3277  3337 I jxcore-log: 
03-23 13:08:20.835  3277  3337 I jxcore-log: ok 319 Size should be 100
03-23 13:08:20.835  3277  3337 I jxcore-log: 
,03-23 13:08:20.838  3277  3337 I jxcore-log: # teardown,
03-23 13:08:20.838  3277  3337 I jxcore-log: 
,03-23 13:08:20.971  3277  3337 I jxcore-log: # setup,
03-23 13:08:20.971  3277  3337 I jxcore-log: 
,03-23 13:08:21.202  3277  3337 I jxcore-log: # 100. #ThaliPeerPoolInterface - bad enqueues,
03-23 13:08:21.202  3277  3337 I jxcore-log: 
,03-23 13:08:21.321  3277  3337 I jxcore-log: ok 320 null arg
03-23 13:08:21.321  3277  3337 I jxcore-log: 
,03-23 13:08:21.322  3277  3337 I jxcore-log: ok 321 wrong arg type
03-23 13:08:21.322  3277  3337 I jxcore-log: 
,03-23 13:08:21.324  3277  3337 I jxcore-log: ok 322 wrong state
03-23 13:08:21.324  3277  3337 I jxcore-log: 
,03-23 13:08:21.327  3277  3337 I jxcore-log: # teardown
03-23 13:08:21.327  3277  3337 I jxcore-log: 
,03-23 13:08:21.457  3277  3337 I jxcore-log: # setup
03-23 13:08:21.457  3277  3337 I jxcore-log: 
,03-23 13:08:21.610  3277  3337 I jxcore-log: # 101. #ThaliPeerPoolInterface - do not allow same object type
03-23 13:08:21.610  3277  3337 I jxcore-log: 
,03-23 13:08:21.738  3277  3337 I jxcore-log: ok 323 good enqueue
03-23 13:08:21.738  3277  3337 I jxcore-log: 
,03-23 13:08:21.742  3277  3337 I jxcore-log: ok 324 should be equal
03-23 13:08:21.742  3277  3337 I jxcore-log: 
,03-23 13:08:21.744  3277  3337 I jxcore-log: # teardown
03-23 13:08:21.744  3277  3337 I jxcore-log: 
,03-23 13:08:21.942  3277  3337 I jxcore-log: # setup
03-23 13:08:21.942  3277  3337 I jxcore-log: 
,03-23 13:08:22.242  3277  3337 I jxcore-log: # 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-23 13:08:22.242  3277  3337 I jxcore-log: 
,03-23 13:08:22.422  3277  3337 I jxcore-log: ok 325 good enqueue
03-23 13:08:22.422  3277  3337 I jxcore-log: 
,03-23 13:08:22.422  3277  3337 I jxcore-log: ok 326 2nd good enqueue
03-23 13:08:22.422  3277  3337 I jxcore-log: 
,03-23 13:08:22.423  3277  3337 I jxcore-log: ok 327 we are in the pool
03-23 13:08:22.423  3277  3337 I jxcore-log: 
03-23 13:08:22.426  3277  3337 I jxcore-log: ok 328 We are out of the pool
03-23 13:08:22.426  3277  3337 I jxcore-log: 
03-23 13:08:22.426  3277  3337 I jxcore-log: ok 329 Action was killed
03-23 13:08:22.426  3277  3337 I jxcore-log: 
03-23 13:08:22.427  3277  3337 I jxcore-log: ok 330 The original kill was called too
03-23 13:08:22.427  3277  3337 I jxcore-log: 
,03-23 13:08:22.427  3277  3337 I jxcore-log: ok 331 second item is still in queue
03-23 13:08:22.427  3277  3337 I jxcore-log: 
03-23 13:08:22.430  3277  3337 I jxcore-log: # teardown
03-23 13:08:22.430  3277  3337 I jxcore-log: 
,03-23 13:08:22.760  3277  3337 I jxcore-log: # setup,
03-23 13:08:22.760  3277  3337 I jxcore-log: 
,03-23 13:08:24.615  3277  3337 I jxcore-log: # 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent,
03-23 13:08:24.615  3277  3337 I jxcore-log: 
,03-23 13:08:24.794  3277  3337 I jxcore-log: ok 332 good enqueue,
03-23 13:08:24.794  3277  3337 I jxcore-log: 
,03-23 13:08:24.796  3277  3337 I jxcore-log: ok 333 first kill
03-23 13:08:24.796  3277  3337 I jxcore-log: 
,03-23 13:08:24.798  3277  3337 I jxcore-log: ok 334 second NOOP kill
03-23 13:08:24.798  3277  3337 I jxcore-log: 
,03-23 13:08:24.803  3277  3337 I jxcore-log: # teardown
03-23 13:08:24.803  3277  3337 I jxcore-log: 
,03-23 13:08:25.519  3277  3337 I jxcore-log: # setup
03-23 13:08:25.519  3277  3337 I jxcore-log: 
,03-23 13:08:26.020  3277  3337 I jxcore-log: # 104. compareBufferArrays
03-23 13:08:26.020  3277  3337 I jxcore-log: 
,03-23 13:08:26.153  3277  3337 I jxcore-log: ok 335 should throw
03-23 13:08:26.153  3277  3337 I jxcore-log: 
,03-23 13:08:26.154  3277  3337 I jxcore-log: ok 336 should throw
03-23 13:08:26.154  3277  3337 I jxcore-log: 
03-23 13:08:26.155  3277  3337 I jxcore-log: ok 337 (unnamed assert)
03-23 13:08:26.155  3277  3337 I jxcore-log: 
03-23 13:08:26.155  3277  3337 I jxcore-log: ok 338 (unnamed assert)
03-23 13:08:26.155  3277  3337 I jxcore-log: 
03-23 13:08:26.156  3277  3337 I jxcore-log: ok 339 (unnamed assert)
03-23 13:08:26.156  3277  3337 I jxcore-log: 
,03-23 13:08:26.156  3277  3337 I jxcore-log: ok 340 (unnamed assert)
03-23 13:08:26.156  3277  3337 I jxcore-log: 
03-23 13:08:26.157  3277  3337 I jxcore-log: ok 341 (unnamed assert)
03-23 13:08:26.157  3277  3337 I jxcore-log: 
03-23 13:08:26.160  3277  3337 I jxcore-log: # teardown
03-23 13:08:26.160  3277  3337 I jxcore-log: 
,03-23 13:08:26.727  3277  3337 I jxcore-log: # setup
03-23 13:08:26.727  3277  3337 I jxcore-log: 
,03-23 13:08:26.831  3277  3337 I jxcore-log: # 105. Call start twice and get error
03-23 13:08:26.831  3277  3337 I jxcore-log: 
,03-23 13:08:26.962  3277  3337 I jxcore-log: ok 342 should throw
03-23 13:08:26.962  3277  3337 I jxcore-log: 
,03-23 13:08:26.971  3277  3337 I jxcore-log: # teardown
03-23 13:08:26.971  3277  3337 I jxcore-log: 
,03-23 13:08:27.078  3277  3337 I jxcore-log: # setup
03-23 13:08:27.078  3277  3337 I jxcore-log: 
,03-23 13:08:27.211  3277  3337 I jxcore-log: # 106. Start and make sure it runs
03-23 13:08:27.211  3277  3337 I jxcore-log: 
,03-23 13:08:27.370  3277  3337 I jxcore-log: # teardown
03-23 13:08:27.370  3277  3337 I jxcore-log: 
,03-23 13:08:27.556  3277  3337 I jxcore-log: # setup
03-23 13:08:27.556  3277  3337 I jxcore-log: 
,03-23 13:08:27.691  3277  3337 I jxcore-log: # 107. Make sure getTimeWhenRun is right after start
03-23 13:08:27.691  3277  3337 I jxcore-log: 
,03-23 13:08:27.807  3277  3337 I jxcore-log: ok 343 (unnamed assert)
03-23 13:08:27.807  3277  3337 I jxcore-log: 
,03-23 13:08:27.812  3277  3337 I jxcore-log: # teardown
03-23 13:08:27.812  3277  3337 I jxcore-log: 
,03-23 13:08:28.000  3277  3337 I jxcore-log: # setup
03-23 13:08:28.000  3277  3337 I jxcore-log: 
,03-23 13:08:28.176  3277  3337 I jxcore-log: # 108. Make sure getTimeWhenRun is -1 after function is called
03-23 13:08:28.176  3277  3337 I jxcore-log: 
,03-23 13:08:28.297  3277  3337 I jxcore-log: ok 344 should be equal
03-23 13:08:28.297  3277  3337 I jxcore-log: 
,03-23 13:08:28.312  3277  3337 I jxcore-log: # teardown
03-23 13:08:28.312  3277  3337 I jxcore-log: 
,03-23 13:08:28.412  3277  3337 I jxcore-log: # setup
03-23 13:08:28.412  3277  3337 I jxcore-log: 
,03-23 13:08:28.525  3277  3337 I jxcore-log: # 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-23 13:08:28.525  3277  3337 I jxcore-log: 
,03-23 13:08:28.664  3277  3337 I jxcore-log: ok 345 should be equal
03-23 13:08:28.664  3277  3337 I jxcore-log: 
,03-23 13:08:28.666  3277  3337 I jxcore-log: ok 346 should be equal
03-23 13:08:28.666  3277  3337 I jxcore-log: 
,03-23 13:08:28.671  3277  3337 I jxcore-log: ok 347 should throw,
03-23 13:08:28.671  3277  3337 I jxcore-log: 
03-23 13:08:28.674  3277  3337 I jxcore-log: # teardown
03-23 13:08:28.674  3277  3337 I jxcore-log: 
,03-23 13:08:28.791  3277  3337 I jxcore-log: # setup
03-23 13:08:28.791  3277  3337 I jxcore-log: 
,03-23 13:08:28.934  3277  3337 I jxcore-log: # 110. Test TransientState
03-23 13:08:28.934  3277  3337 I jxcore-log: 
,03-23 13:08:29.058  3277  3337 I jxcore-log: ok 348 should throw
03-23 13:08:29.058  3277  3337 I jxcore-log: 
,03-23 13:08:29.064  3277  3337 I jxcore-log: ok 349 should throw
03-23 13:08:29.064  3277  3337 I jxcore-log: 
,03-23 13:08:29.066  3277  3337 I jxcore-log: ok 350 should be equal
03-23 13:08:29.066  3277  3337 I jxcore-log: 
,03-23 13:08:29.068  3277  3337 I jxcore-log: ok 351 should be equal
03-23 13:08:29.068  3277  3337 I jxcore-log: 
,03-23 13:08:29.070  3277  3337 I jxcore-log: ok 352 should be equal
03-23 13:08:29.070  3277  3337 I jxcore-log: 
,03-23 13:08:29.071  3277  3337 I jxcore-log: ok 353 should be equal
03-23 13:08:29.071  3277  3337 I jxcore-log: 
,03-23 13:08:29.071  3277  3337 I jxcore-log: ok 354 (unnamed assert)
03-23 13:08:29.071  3277  3337 I jxcore-log: 
03-23 13:08:29.072  3277  3337 I jxcore-log: ok 355 (unnamed assert)
03-23 13:08:29.072  3277  3337 I jxcore-log: 
03-23 13:08:29.074  3277  3337 I jxcore-log: # teardown
03-23 13:08:29.074  3277  3337 I jxcore-log: 
,03-23 13:08:29.193  3277  3337 I jxcore-log: # setup
03-23 13:08:29.193  3277  3337 I jxcore-log: 
,03-23 13:08:29.318  3277  3337 I jxcore-log: # 111. No peers and empty database
03-23 13:08:29.318  3277  3337 I jxcore-log: 
,03-23 13:08:29.563  3277  3337 I jxcore-log: ok 356 verify failed
03-23 13:08:29.563  3277  3337 I jxcore-log: 
,03-23 13:08:29.563  3277  3337 I jxcore-log: ok 357 constructor called once
03-23 13:08:29.563  3277  3337 I jxcore-log: 
03-23 13:08:29.565  3277  3337 I jxcore-log: ok 358 constructor called with right args
03-23 13:08:29.565  3277  3337 I jxcore-log: 
03-23 13:08:29.565  3277  3337 I jxcore-log: ok 359 match start arg
03-23 13:08:29.565  3277  3337 I jxcore-log: 
,03-23 13:08:29.566  3277  3337 I jxcore-log: ok 360 start called once
03-23 13:08:29.566  3277  3337 I jxcore-log: 
03-23 13:08:29.566  3277  3337 I jxcore-log: ok 361 stop called once,
03-23 13:08:29.566  3277  3337 I jxcore-log: 
03-23 13:08:29.566  3277  3337 I jxcore-log: ok 362 stop after start
03-23 13:08:29.566  3277  3337 I jxcore-log: 
,03-23 13:08:29.571  3277  3337 I jxcore-log: # teardown
03-23 13:08:29.571  3277  3337 I jxcore-log: 
,03-23 13:08:29.726  3277  3337 I jxcore-log: # setup
03-23 13:08:29.726  3277  3337 I jxcore-log: 
,03-23 13:08:29.828  3277  3337 I jxcore-log: # 112. One peer and empty DB,
03-23 13:08:29.828  3277  3337 I jxcore-log: 
,03-23 13:08:30.147  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:30.147  3277  3337 I jxcore-log: 
,03-23 13:08:30.150  3277  3337 I jxcore-log: ok 363 verify failed,
03-23 13:08:30.150  3277  3337 I jxcore-log: 
03-23 13:08:30.150  3277  3337 I jxcore-log: ok 364 constructor called once
03-23 13:08:30.150  3277  3337 I jxcore-log: 
03-23 13:08:30.151  3277  3337 I jxcore-log: ok 365 constructor called with right args
03-23 13:08:30.151  3277  3337 I jxcore-log: 
,03-23 13:08:30.152  3277  3337 I jxcore-log: ok 366 match start arg
03-23 13:08:30.152  3277  3337 I jxcore-log: 
,03-23 13:08:30.152  3277  3337 I jxcore-log: ok 367 start called once
03-23 13:08:30.152  3277  3337 I jxcore-log: 
03-23 13:08:30.152  3277  3337 I jxcore-log: ok 368 stop called once
03-23 13:08:30.152  3277  3337 I jxcore-log: 
03-23 13:08:30.152  3277  3337 I jxcore-log: ok 369 stop after start
03-23 13:08:30.152  3277  3337 I jxcore-log: 
,03-23 13:08:30.157  3277  3337 I jxcore-log: # teardown
03-23 13:08:30.157  3277  3337 I jxcore-log: 
,03-23 13:08:30.291  3277  3337 I jxcore-log: # setup,
03-23 13:08:30.291  3277  3337 I jxcore-log: 
,03-23 13:08:30.835  3277  3337 I jxcore-log: # 113. One peer with _Local set behind current seq
03-23 13:08:30.835  3277  3337 I jxcore-log: 
,03-23 13:08:31.143  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:31.143  3277  3337 I jxcore-log: 
,03-23 13:08:31.144  3277  3337 I jxcore-log: ok 370 verify failed
03-23 13:08:31.144  3277  3337 I jxcore-log: 
03-23 13:08:31.145  3277  3337 I jxcore-log: ok 371 constructor called once
03-23 13:08:31.145  3277  3337 I jxcore-log: 
,03-23 13:08:31.146  3277  3337 I jxcore-log: ok 372 constructor called with right args
03-23 13:08:31.146  3277  3337 I jxcore-log: 
,03-23 13:08:31.147  3277  3337 I jxcore-log: ok 373 match start arg
03-23 13:08:31.147  3277  3337 I jxcore-log: 
03-23 13:08:31.147  3277  3337 I jxcore-log: ok 374 start called once
03-23 13:08:31.147  3277  3337 I jxcore-log: 
03-23 13:08:31.147  3277  3337 I jxcore-log: ok 375 stop called once
03-23 13:08:31.147  3277  3337 I jxcore-log: 
03-23 13:08:31.148  3277  3337 I jxcore-log: ok 376 stop after start
03-23 13:08:31.148  3277  3337 I jxcore-log: 
,03-23 13:08:31.153  3277  3337 I jxcore-log: # teardown
03-23 13:08:31.153  3277  3337 I jxcore-log: 
,03-23 13:08:31.221  3277  3337 I jxcore-log: # setup
03-23 13:08:31.221  3277  3337 I jxcore-log: 
,03-23 13:08:31.351  3277  3337 I jxcore-log: # 114. One peer with _Local set equal to current seq
03-23 13:08:31.351  3277  3337 I jxcore-log: 
,03-23 13:08:31.682  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:31.682  3277  3337 I jxcore-log: 
,03-23 13:08:31.683  3277  3337 I jxcore-log: ok 377 verify failed
03-23 13:08:31.683  3277  3337 I jxcore-log: 
,03-23 13:08:31.684  3277  3337 I jxcore-log: ok 378 constructor called once
03-23 13:08:31.684  3277  3337 I jxcore-log: 
,03-23 13:08:31.684  3277  3337 I jxcore-log: ok 379 constructor called with right args
03-23 13:08:31.684  3277  3337 I jxcore-log: 
,03-23 13:08:31.685  3277  3337 I jxcore-log: ok 380 match start arg
03-23 13:08:31.685  3277  3337 I jxcore-log: 
03-23 13:08:31.685  3277  3337 I jxcore-log: ok 381 start called once
03-23 13:08:31.685  3277  3337 I jxcore-log: 
,03-23 13:08:31.685  3277  3337 I jxcore-log: ok 382 stop called once
03-23 13:08:31.685  3277  3337 I jxcore-log: 
03-23 13:08:31.686  3277  3337 I jxcore-log: ok 383 stop after start
03-23 13:08:31.686  3277  3337 I jxcore-log: 
,03-23 13:08:31.691  3277  3337 I jxcore-log: # teardown
03-23 13:08:31.691  3277  3337 I jxcore-log: 
,03-23 13:08:31.797  3277  3337 I jxcore-log: # setup
03-23 13:08:31.797  3277  3337 I jxcore-log: 
,03-23 13:08:31.910  3277  3337 I jxcore-log: # 115. One peer with _Local set ahead of current seq (and no this should not happen)
,03-23 13:08:31.910  3277  3337 I jxcore-log: 
,03-23 13:08:32.193  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:32.193  3277  3337 I jxcore-log: 
03-23 13:08:32.194  3277  3337 I jxcore-log: ok 384 verify failed
03-23 13:08:32.194  3277  3337 I jxcore-log: 
03-23 13:08:32.194  3277  3337 I jxcore-log: ok 385 constructor called once
03-23 13:08:32.194  3277  3337 I jxcore-log: 
03-23 13:08:32.195  3277  3337 I jxcore-log: ok 386 constructor called with right args
03-23 13:08:32.195  3277  3337 I jxcore-log: 
03-23 13:08:32.195  3277  3337 I jxcore-log: ok 387 match start arg
03-23 13:08:32.195  3277  3337 I jxcore-log: 
03-23 13:08:32.195  3277  3337 I jxcore-log: ok 388 start called once
03-23 13:08:32.195  3277  3337 I jxcore-log: 
03-23 13:08:32.195  3277  3337 I jxcore-log: ok 389 stop called once
03-23 13:08:32.195  3277  3337 I jxcore-log: 
03-23 13:08:32.196  3277  3337 I jxcore-log: ok 390 stop after start
03-23 13:08:32.196  3277  3337 I jxcore-log: 
,03-23 13:08:32.201  3277  3337 I jxcore-log: # teardown
03-23 13:08:32.201  3277  3337 I jxcore-log: 
,03-23 13:08:32.367  3277  3337 I jxcore-log: # setup
03-23 13:08:32.367  3277  3337 I jxcore-log: 
,03-23 13:08:32.506  3277  3337 I jxcore-log: # 116. Three peers, one not in DB, one behind and one ahead
03-23 13:08:32.506  3277  3337 I jxcore-log: 
,03-23 13:08:32.881  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:32.881  3277  3337 I jxcore-log: 
,03-23 13:08:32.885  3277  3337 I jxcore-log: ok 391 verify failed
03-23 13:08:32.885  3277  3337 I jxcore-log: 
,03-23 13:08:32.886  3277  3337 I jxcore-log: ok 392 constructor called once
03-23 13:08:32.886  3277  3337 I jxcore-log: 
03-23 13:08:32.886  3277  3337 I jxcore-log: ok 393 constructor called with right args
03-23 13:08:32.886  3277  3337 I jxcore-log: 
,03-23 13:08:32.887  3277  3337 I jxcore-log: ok 394 match start arg
03-23 13:08:32.887  3277  3337 I jxcore-log: 
03-23 13:08:32.887  3277  3337 I jxcore-log: ok 395 start called once
03-23 13:08:32.887  3277  3337 I jxcore-log: 
03-23 13:08:32.888  3277  3337 I jxcore-log: ok 396 stop called once
03-23 13:08:32.888  3277  3337 I jxcore-log: 
,03-23 13:08:32.888  3277  3337 I jxcore-log: ok 397 stop after start
03-23 13:08:32.888  3277  3337 I jxcore-log: 
,03-23 13:08:32.894  3277  3337 I jxcore-log: # teardown
03-23 13:08:32.894  3277  3337 I jxcore-log: 
,03-23 13:08:33.010  3277  3337 I jxcore-log: # setup
03-23 13:08:33.010  3277  3337 I jxcore-log: 
,03-23 13:08:33.287  3277  3337 I jxcore-log: # 117. More than maximum peers, make sure we only send maximum allowed
03-23 13:08:33.287  3277  3337 I jxcore-log: 
,03-23 13:08:33.993  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:33.993  3277  3337 I jxcore-log: 
,03-23 13:08:33.995  3277  3337 I jxcore-log: ok 398 verify failed
03-23 13:08:33.995  3277  3337 I jxcore-log: 
03-23 13:08:33.995  3277  3337 I jxcore-log: ok 399 constructor called once
03-23 13:08:33.995  3277  3337 I jxcore-log: 
,03-23 13:08:33.996  3277  3337 I jxcore-log: ok 400 constructor called with right args
03-23 13:08:33.996  3277  3337 I jxcore-log: 
,03-23 13:08:33.996  3277  3337 I jxcore-log: ok 401 match start arg
03-23 13:08:33.996  3277  3337 I jxcore-log: 
,03-23 13:08:33.997  3277  3337 I jxcore-log: ok 402 start called once
03-23 13:08:33.997  3277  3337 I jxcore-log: 
03-23 13:08:33.997  3277  3337 I jxcore-log: ok 403 stop called once
03-23 13:08:33.997  3277  3337 I jxcore-log: 
03-23 13:08:33.997  3277  3337 I jxcore-log: ok 404 stop after start
03-23 13:08:33.997  3277  3337 I jxcore-log: 
,03-23 13:08:34.002  3277  3337 I jxcore-log: # teardown
03-23 13:08:34.002  3277  3337 I jxcore-log: 
,03-23 13:08:34.330  3277  3337 I jxcore-log: # setup
03-23 13:08:34.330  3277  3337 I jxcore-log: 
,03-23 13:08:34.696  3277  3337 I jxcore-log: # 118. two peers with empty DB, update the doc
03-23 13:08:34.696  3277  3337 I jxcore-log: 
,03-23 13:08:35.134  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:35.134  3277  3337 I jxcore-log: 
,03-23 13:08:35.172  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:35.172  3277  3337 I jxcore-log: 
,03-23 13:08:35.173  3277  3337 I jxcore-log: ok 405 verify failed
03-23 13:08:35.173  3277  3337 I jxcore-log: 
,03-23 13:08:35.174  3277  3337 I jxcore-log: ok 406 constructor called once
03-23 13:08:35.174  3277  3337 I jxcore-log: 
03-23 13:08:35.174  3277  3337 I jxcore-log: ok 407 constructor called with right args
03-23 13:08:35.174  3277  3337 I jxcore-log: 
,03-23 13:08:35.175  3277  3337 I jxcore-log: ok 408 last start before stop
03-23 13:08:35.175  3277  3337 I jxcore-log: 
03-23 13:08:35.175  3277  3337 I jxcore-log: ok 409 empty first start
03-23 13:08:35.175  3277  3337 I jxcore-log: 
03-23 13:08:35.176  3277  3337 I jxcore-log: ok 410 full second start
03-23 13:08:35.176  3277  3337 I jxcore-log: 
03-23 13:08:35.177  3277  3337 I jxcore-log: ok 411 only 2 timers
03-23 13:08:35.177  3277  3337 I jxcore-log: 
,03-23 13:08:35.181  3277  3337 I jxcore-log: # teardown
03-23 13:08:35.181  3277  3337 I jxcore-log: 
,03-23 13:08:35.330  3277  3337 I jxcore-log: # setup
,03-23 13:08:35.330  3277  3337 I jxcore-log: 
,03-23 13:08:35.847  3277  3337 I jxcore-log: # 119. add doc and make sure tokens refresh when they expire,
03-23 13:08:35.847  3277  3337 I jxcore-log: 
,03-23 13:08:37.948  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-23 13:08:37.948  3277  3337 I jxcore-log: 
,03-23 13:08:38.060  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:38.060  3277  3337 I jxcore-log: ,
,03-23 13:08:38.155  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:38.155  3277  3337 I jxcore-log: 
,03-23 13:08:38.158  3277  3337 I jxcore-log: ok 412 verify failed
03-23 13:08:38.158  3277  3337 I jxcore-log: 
,03-23 13:08:38.158  3277  3337 I jxcore-log: ok 413 constructor called once,
03-23 13:08:38.158  3277  3337 I jxcore-log: 
03-23 13:08:38.159  3277  3337 I jxcore-log: ok 414 constructor called with right args
03-23 13:08:38.159  3277  3337 I jxcore-log: 
03-23 13:08:38.159  3277  3337 I jxcore-log: ok 415 start before stop
03-23 13:08:38.159  3277  3337 I jxcore-log: 
03-23 13:08:38.160  3277  3337 I jxcore-log: ok 416 We got at least 3 calls to start
03-23 13:08:38.160  3277  3337 I jxcore-log: 
,03-23 13:08:38.160  3277  3337 I jxcore-log: ok 417 at least 3
03-23 13:08:38.160  3277  3337 I jxcore-log: 
03-23 13:08:38.160  3277  3337 I jxcore-log: ok 418 default 1
03-23 13:08:38.160  3277  3337 I jxcore-log: 
03-23 13:08:38.160  3277  3337 I jxcore-log: ok 419 1 run
03-23 13:08:38.160  3277  3337 I jxcore-log: 
03-23 13:08:38.161  3277  3337 I jxcore-log: ok 420 default 2
03-23 13:08:38.161  3277  3337 I jxcore-log: 
,03-23 13:08:38.161  3277  3337 I jxcore-log: ok 421 2 run
03-23 13:08:38.161  3277  3337 I jxcore-log: 
03-23 13:08:38.161  3277  3337 I jxcore-log: ok 422 default 3
03-23 13:08:38.161  3277  3337 I jxcore-log: 
03-23 13:08:38.165  3277  3337 I jxcore-log: # teardown
03-23 13:08:38.165  3277  3337 I jxcore-log: 
,03-23 13:08:39.006  3277  3337 I jxcore-log: # setup
03-23 13:08:39.006  3277  3337 I jxcore-log: 
,03-23 13:08:40.147  3277  3337 I jxcore-log: # 120. start and stop and start and stop
03-23 13:08:40.147  3277  3337 I jxcore-log: 
,03-23 13:08:43.072  3277  3337 I jxcore-log: ok 423 start out null
03-23 13:08:43.072  3277  3337 I jxcore-log: 
,03-23 13:08:43.092  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:43.092  3277  3337 I jxcore-log: 
,03-23 13:08:43.093  3277  3337 I jxcore-log: ok 424 back to null
03-23 13:08:43.093  3277  3337 I jxcore-log: 
,03-23 13:08:43.115  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:43.115  3277  3337 I jxcore-log: 
,03-23 13:08:43.116  3277  3337 I jxcore-log: ok 425 still null
03-23 13:08:43.116  3277  3337 I jxcore-log: 
03-23 13:08:43.117  3277  3337 I jxcore-log: ok 426 verify failed,
03-23 13:08:43.117  3277  3337 I jxcore-log: 
,03-23 13:08:43.118  3277  3337 I jxcore-log: ok 427 constructor called once
03-23 13:08:43.118  3277  3337 I jxcore-log: 
03-23 13:08:43.118  3277  3337 I jxcore-log: ok 428 constructor called with right args
03-23 13:08:43.118  3277  3337 I jxcore-log: ,
03-23 13:08:43.118  3277  3337 I jxcore-log: ok 429 first start before first stop
03-23 13:08:43.118  3277  3337 I jxcore-log: 
,03-23 13:08:43.119  3277  3337 I jxcore-log: ok 430 first stop before second start
03-23 13:08:43.119  3277  3337 I jxcore-log: 
03-23 13:08:43.119  3277  3337 I jxcore-log: ok 431 second start before second stop
03-23 13:08:43.119  3277  3337 I jxcore-log: 
03-23 13:08:43.128  3277  3337 I jxcore-log: # teardown
03-23 13:08:43.128  3277  3337 I jxcore-log: 
,03-23 13:08:43.660  3277  3337 I jxcore-log: # setup,
03-23 13:08:43.660  3277  3337 I jxcore-log: 
,03-23 13:08:44.624  3277  3337 I jxcore-log: # 121. two identical starts in a row
03-23 13:08:44.624  3277  3337 I jxcore-log: 
,03-23 13:08:44.974  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:44.974  3277  3337 I jxcore-log: 
,03-23 13:08:44.978  3277  3337 I jxcore-log: ok 432 verify failed
03-23 13:08:44.978  3277  3337 I jxcore-log: 
,03-23 13:08:44.979  3277  3337 I jxcore-log: ok 433 constructor called once
03-23 13:08:44.979  3277  3337 I jxcore-log: 
,03-23 13:08:44.980  3277  3337 I jxcore-log: ok 434 constructor called with right args,
03-23 13:08:44.980  3277  3337 I jxcore-log: 
03-23 13:08:44.981  3277  3337 I jxcore-log: ok 435 (unnamed assert)
03-23 13:08:44.981  3277  3337 I jxcore-log: 
03-23 13:08:44.985  3277  3337 I jxcore-log: # teardown
03-23 13:08:44.985  3277  3337 I jxcore-log: 
,03-23 13:08:45.377  3277  3337 I jxcore-log: # setup
03-23 13:08:45.377  3277  3337 I jxcore-log: 
,03-23 13:08:45.877  3277  3337 I jxcore-log: # 122. two different starts in a row
03-23 13:08:45.877  3277  3337 I jxcore-log: 
,03-23 13:08:46.342  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:46.342  3277  3337 I jxcore-log: 
,03-23 13:08:46.349  3277  3337 I jxcore-log: ok 436 verify failed
03-23 13:08:46.349  3277  3337 I jxcore-log: 
03-23 13:08:46.349  3277  3337 I jxcore-log: ok 437 constructor called once
03-23 13:08:46.349  3277  3337 I jxcore-log: 
,03-23 13:08:46.350  3277  3337 I jxcore-log: ok 438 constructor called with right args
03-23 13:08:46.350  3277  3337 I jxcore-log: 
03-23 13:08:46.350  3277  3337 I jxcore-log: ok 439 (unnamed assert)
03-23 13:08:46.350  3277  3337 I jxcore-log: 
,03-23 13:08:46.350  3277  3337 I jxcore-log: ok 440 (unnamed assert)
03-23 13:08:46.350  3277  3337 I jxcore-log: 
,03-23 13:08:46.355  3277  3337 I jxcore-log: # teardown
03-23 13:08:46.355  3277  3337 I jxcore-log: 
,03-23 13:08:47.858  3277  3337 I jxcore-log: # setup,
03-23 13:08:47.858  3277  3337 I jxcore-log: 
,03-23 13:08:49.069  3277  3337 I jxcore-log: # 123. two stops and a start and two stops
03-23 13:08:49.069  3277  3337 I jxcore-log: 
,03-23 13:08:50.396  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:50.396  3277  3337 I jxcore-log: 
,03-23 13:08:50.400  3277  3337 I jxcore-log: ok 441 verify failed
03-23 13:08:50.400  3277  3337 I jxcore-log: 
,03-23 13:08:50.400  3277  3337 I jxcore-log: ok 442 constructor called once
03-23 13:08:50.400  3277  3337 I jxcore-log: 
,03-23 13:08:50.401  3277  3337 I jxcore-log: ok 443 constructor called with right args
03-23 13:08:50.401  3277  3337 I jxcore-log: 
03-23 13:08:50.401  3277  3337 I jxcore-log: ok 444 start before stop
03-23 13:08:50.401  3277  3337 I jxcore-log: 
03-23 13:08:50.405  3277  3337 I jxcore-log: # teardown
03-23 13:08:50.405  3277  3337 I jxcore-log: 
,03-23 13:08:51.408  3277  3337 I jxcore-log: # setup
03-23 13:08:51.408  3277  3337 I jxcore-log: 
,03-23 13:08:51.517  3277  3337 I jxcore-log: # 124. we properly enqueue requests so no then needed
03-23 13:08:51.517  3277  3337 I jxcore-log: 
,03-23 13:08:52.341  3277  3337 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-23 13:08:52.341  3277  3337 I jxcore-log: 
,03-23 13:08:52.343  3277  3337 I jxcore-log: ok 445 verify failed
,03-23 13:08:52.343  3277  3337 I jxcore-log: 
03-23 13:08:52.343  3277  3337 I jxcore-log: ok 446 constructor called once
,03-23 13:08:52.343  3277  3337 I jxcore-log: 
03-23 13:08:52.344  3277  3337 I jxcore-log: ok 447 constructor called with right args
03-23 13:08:52.344  3277  3337 I jxcore-log: 
,03-23 13:08:52.345  3277  3337 I jxcore-log: ok 448 start before stop
03-23 13:08:52.345  3277  3337 I jxcore-log: 
,03-23 13:08:52.351  3277  3337 I jxcore-log: # teardown
03-23 13:08:52.351  3277  3337 I jxcore-log: ,
,03-23 13:08:52.523  3277  3337 I jxcore-log: # setup,
03-23 13:08:52.523  3277  3337 I jxcore-log: 
,03-23 13:08:53.970  3277  3337 I jxcore-log: # 125. test calculateSeqPointKeyId
03-23 13:08:53.970  3277  3337 I jxcore-log: 
,03-23 13:08:54.184  3277  3337 I jxcore-log: ok 449 should be equal
03-23 13:08:54.184  3277  3337 I jxcore-log: 
,03-23 13:08:54.185  3277  3337 I jxcore-log: ok 450 should be equal
03-23 13:08:54.185  3277  3337 I jxcore-log: 
,03-23 13:08:54.187  3277  3337 I jxcore-log: # teardown
03-23 13:08:54.187  3277  3337 I jxcore-log: 
,03-23 13:08:55.093  3277  3337 I jxcore-log: # setup
03-23 13:08:55.093  3277  3337 I jxcore-log: 
,03-23 13:08:55.711  3277  3337 I jxcore-log: # 126. can create servers manager
03-23 13:08:55.711  3277  3337 I jxcore-log: 
,03-23 13:08:55.875  3277  3337 I jxcore-log: ok 451 serversManager must not be null
03-23 13:08:55.875  3277  3337 I jxcore-log: 
,03-23 13:08:55.877  3277  3337 I jxcore-log: ok 452 serversManager must be an object
03-23 13:08:55.877  3277  3337 I jxcore-log: 
,03-23 13:08:55.884  3277  3337 I jxcore-log: # teardown
03-23 13:08:55.884  3277  3337 I jxcore-log: 
,03-23 13:08:56.734  3277  3337 I jxcore-log: # setup
03-23 13:08:56.734  3277  3337 I jxcore-log: 
,03-23 13:08:56.900  3277  3337 I jxcore-log: # 127. calling stop without start causes error
03-23 13:08:56.900  3277  3337 I jxcore-log: 
,03-23 13:08:57.563  3277  3337 I jxcore-log: ok 453 We need to call start first
03-23 13:08:57.563  3277  3337 I jxcore-log: 
,03-23 13:08:57.570  3277  3337 I jxcore-log: # teardown
03-23 13:08:57.570  3277  3337 I jxcore-log: 
,03-23 13:08:57.757  3277  3337 I jxcore-log: # setup
03-23 13:08:57.757  3277  3337 I jxcore-log: ,
,03-23 13:08:58.371  3277  3337 I jxcore-log: # 128. can start/stop servers manager
03-23 13:08:58.371  3277  3337 I jxcore-log: 
,03-23 13:08:58.538  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:08:58.538  3277  3337 I jxcore-log: 
,03-23 13:08:58.548  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 59669
03-23 13:08:58.548  3277  3337 I jxcore-log: 
,03-23 13:08:58.551  3277  3337 I jxcore-log: ok 454 port must be in range
03-23 13:08:58.551  3277  3337 I jxcore-log: 
,03-23 13:08:58.553  3277  3337 I jxcore-log: # teardown
03-23 13:08:58.553  3277  3337 I jxcore-log: 
,03-23 13:08:58.715  3277  3337 I jxcore-log: # setup
03-23 13:08:58.715  3277  3337 I jxcore-log: 
,03-23 13:08:58.831  3277  3337 I jxcore-log: # 129. starting twice resolves with listening port
03-23 13:08:58.831  3277  3337 I jxcore-log: 
,03-23 13:08:58.992  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:08:58.992  3277  3337 I jxcore-log: 
,03-23 13:08:59.001  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 51153
03-23 13:08:59.001  3277  3337 I jxcore-log: 
,03-23 13:08:59.007  3277  3337 I jxcore-log: ok 455 second start should return same port
03-23 13:08:59.007  3277  3337 I jxcore-log: 
,03-23 13:08:59.012  3277  3337 I jxcore-log: # teardown
03-23 13:08:59.012  3277  3337 I jxcore-log: 
,03-23 13:08:59.168  3277  3337 I jxcore-log: # setup
03-23 13:08:59.168  3277  3337 I jxcore-log: 
,03-23 13:08:59.287  3277  3337 I jxcore-log: # 130. terminateIncomingConnection will terminate a connection
03-23 13:08:59.287  3277  3337 I jxcore-log: 
,03-23 13:08:59.512  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:08:59.512  3277  3337 I jxcore-log: 
,03-23 13:08:59.515  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 46772
03-23 13:08:59.515  3277  3337 I jxcore-log: 
,03-23 13:08:59.521  3277  3337 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-23 13:08:59.521  3277  3337 I jxcore-log: 
,03-23 13:08:59.522  3277  3337 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-23 13:08:59.522  3277  3337 I jxcore-log: 
03-23 13:08:59.524  3277  3337 I jxcore-log: DEBUG createNativeListener: new mux
03-23 13:08:59.524  3277  3337 I jxcore-log: 
,03-23 13:08:59.527  3277  3337 I jxcore-log: ok 456 we should be connected
03-23 13:08:59.527  3277  3337 I jxcore-log: 
,03-23 13:08:59.531  3277  3337 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-23 13:08:59.531  3277  3337 I jxcore-log: 
,03-23 13:08:59.531  3277  3337 I jxcore-log: ok 457 now we are disconnected
03-23 13:08:59.531  3277  3337 I jxcore-log: 
,03-23 13:08:59.546  3277  3337 I jxcore-log: # teardown
03-23 13:08:59.546  3277  3337 I jxcore-log: 
,03-23 13:08:59.711  3277  3337 I jxcore-log: # setup
03-23 13:08:59.711  3277  3337 I jxcore-log: 
,03-23 13:08:59.810  3277  3337 I jxcore-log: # 131. terminate an Outgoing connection will terminate the server
03-23 13:08:59.810  3277  3337 I jxcore-log: 
,03-23 13:08:59.940  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:08:59.940  3277  3337 I jxcore-log: 
,03-23 13:08:59.948  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 34135
03-23 13:08:59.948  3277  3337 I jxcore-log: 
,03-23 13:08:59.952  3277  3337 I jxcore-log: # teardown
03-23 13:08:59.952  3277  3337 I jxcore-log: 
,03-23 13:09:00.111  3277  3337 I jxcore-log: # setup
03-23 13:09:00.111  3277  3337 I jxcore-log: 
,03-23 13:09:00.253  3277  3337 I jxcore-log: # 132. terminate an Outgoing connection with wrong arguments is not harmful
03-23 13:09:00.253  3277  3337 I jxcore-log: 
,03-23 13:09:00.378  3277  3337 I jxcore-log: DEBUG createNativeListener: creating native server
03-23 13:09:00.378  3277  3337 I jxcore-log: 
,03-23 13:09:00.387  3277  3337 I jxcore-log: DEBUG createNativeListener: listening 34819
03-23 13:09:00.387  3277  3337 I jxcore-log: 
,03-23 13:09:00.392  3277  3337 I jxcore-log: # teardown
03-23 13:09:00.392  3277  3337 I jxcore-log: 
,03-23 13:09:00.565  3277  3337 I jxcore-log: # setup
03-23 13:09:00.565  3277  3337 I jxcore-log: 
,03-23 13:09:00.745  3277  3337 I jxcore-log: ok 458 should be in started state
03-23 13:09:00.745  3277  3337 I jxcore-log: 
,03-23 13:09:00.751  3277  3337 I jxcore-log: # 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-23 13:09:00.751  3277  3337 I jxcore-log: 
,03-23 13:09:00.964  3277  3337 I jxcore-log: ok 459 peer identifier should match
03-23 13:09:00.964  3277  3337 I jxcore-log: 
,03-23 13:09:00.964  3277  3337 I jxcore-log: ok 460 host address should match
03-23 13:09:00.964  3277  3337 I jxcore-log: 
03-23 13:09:00.965  3277  3337 I jxcore-log: ok 461 port should match
03-23 13:09:00.965  3277  3337 I jxcore-log: 
,03-23 13:09:00.972  3277  3337 I jxcore-log: ok 462 host address should be null
03-23 13:09:00.972  3277  3337 I jxcore-log: 
,03-23 13:09:00.973  3277  3337 I jxcore-log: ok 463 port should should be null
03-23 13:09:00.973  3277  3337 I jxcore-log: 
,03-23 13:09:00.988  3277  3337 I jxcore-log: # teardown
03-23 13:09:00.988  3277  3337 I jxcore-log: 
,03-23 13:09:01.079  3277  3337 I jxcore-log: ok 464 should not be in started state
,03-23 13:09:01.079  3277  3337 I jxcore-log: 
,03-23 13:09:01.083  3277  3337 I jxcore-log: # setup
03-23 13:09:01.083  3277  3337 I jxcore-log: 
,03-23 13:09:01.257  3277  3337 I jxcore-log: ok 465 should be in started state
03-23 13:09:01.257  3277  3337 I jxcore-log: 
,03-23 13:09:01.262  3277  3337 I jxcore-log: # 134. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-23 13:09:01.262  3277  3337 I jxcore-log: 
,03-23 13:09:01.450  3277  3337 I jxcore-log: ok 466 USN should have changed from the first one
03-23 13:09:01.450  3277  3337 I jxcore-log: 
,03-23 13:09:01.458  3277  3337 I jxcore-log: ok 467 when receiving the second byebye, the first USN should be already set
03-23 13:09:01.458  3277  3337 I jxcore-log: 
,03-23 13:09:01.465  3277  3337 I jxcore-log: # teardown
03-23 13:09:01.465  3277  3337 I jxcore-log: 
,03-23 13:09:01.642  3277  3337 I jxcore-log: ok 468 should not be in started state
,03-23 13:09:01.642  3277  3337 I jxcore-log: 
,03-23 13:09:01.644  3277  3337 I jxcore-log: # setup
03-23 13:09:01.644  3277  3337 I jxcore-log: 
,03-23 13:09:01.748  3277  3337 I jxcore-log: ok 469 should be in started state
03-23 13:09:01.748  3277  3337 I jxcore-log: 
,03-23 13:09:01.755  3277  3337 I jxcore-log: # 135. messages with invalid location or USN should be ignored
03-23 13:09:01.755  3277  3337 I jxcore-log: 
,03-23 13:09:01.837  3277  3337 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000,
03-23 13:09:01.837  3277  3337 I jxcore-log: 
03-23 13:09:01.840  3277  3337 I jxcore-log: ok 470 should not have emitted with invalid port
03-23 13:09:01.840  3277  3337 I jxcore-log: 
,03-23 13:09:01.843  3277  3337 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-23 13:09:01.843  3277  3337 I jxcore-log: 
,03-23 13:09:01.843  3277  3337 I jxcore-log: ok 471 should not have emitted with invalid USN
03-23 13:09:01.843  3277  3337 I jxcore-log: 
,03-23 13:09:01.846  3277  3337 I jxcore-log: # teardown
03-23 13:09:01.846  3277  3337 I jxcore-log: 
,03-23 13:09:01.961  3277  3337 I jxcore-log: ok 472 should not be in started state
03-23 13:09:01.961  3277  3337 I jxcore-log: 
,03-23 13:09:01.963  3277  3337 I jxcore-log: # setup
03-23 13:09:01.963  3277  3337 I jxcore-log: 
,03-23 13:09:02.067  3277  3337 I jxcore-log: ok 473 should be in started state
03-23 13:09:02.067  3277  3337 I jxcore-log: 
,03-23 13:09:02.073  3277  3337 I jxcore-log: # 136. verify that Thali-specific messages are filtered correctly
03-23 13:09:02.073  3277  3337 I jxcore-log: 
,03-23 13:09:02.220  3277  3337 I jxcore-log: ok 474 irrelevant messages should be ignored
03-23 13:09:02.220  3277  3337 I jxcore-log: 
,03-23 13:09:02.221  3277  3337 I jxcore-log: ok 475 relevant messages should not be ignored
03-23 13:09:02.221  3277  3337 I jxcore-log: 
03-23 13:09:02.222  3277  3337 I jxcore-log: ok 476 messages from this device should be ignored
03-23 13:09:02.222  3277  3337 I jxcore-log: 
03-23 13:09:02.225  3277  3337 I jxcore-log: # teardown
03-23 13:09:02.225  3277  3337 I jxcore-log: 
,03-23 13:09:02.389  3277  3337 I jxcore-log: ok 477 should not be in started state
03-23 13:09:02.389  3277  3337 I jxcore-log: 
,03-23 13:09:02.396  3277  3337 I jxcore-log: # setup
03-23 13:09:02.396  3277  3337 I jxcore-log: 
,03-23 13:09:02.542  3277  3337 I jxcore-log: ok 478 should be in started state
03-23 13:09:02.542  3277  3337 I jxcore-log: 
,03-23 13:09:02.544  3277  3337 I jxcore-log: # 137. #startListeningForAdvertisements should fail if start not called
03-23 13:09:02.544  3277  3337 I jxcore-log: 
,03-23 13:09:02.697  3277  3337 I jxcore-log: ok 479 specific error should be returned
03-23 13:09:02.697  3277  3337 I jxcore-log: 
,03-23 13:09:02.702  3277  3337 I jxcore-log: # teardown
03-23 13:09:02.702  3277  3337 I jxcore-log: 
,03-23 13:09:02.861  3277  3337 I jxcore-log: ok 480 should not be in started state
03-23 13:09:02.861  3277  3337 I jxcore-log: 
,03-23 13:09:02.863  3277  3337 I jxcore-log: # setup
03-23 13:09:02.863  3277  3337 I jxcore-log: 
,03-23 13:09:03.001  3277  3337 I jxcore-log: ok 481 should be in started state
03-23 13:09:03.001  3277  3337 I jxcore-log: 
,03-23 13:09:03.003  3277  3337 I jxcore-log: # 138. #startUpdateAdvertisingAndListening should fail if start not called
03-23 13:09:03.003  3277  3337 I jxcore-log: 
,03-23 13:09:03.182  3277  3337 I jxcore-log: ok 482 specific error should be returned
03-23 13:09:03.182  3277  3337 I jxcore-log: 
03-23 13:09:03.184  3277  3337 I jxcore-log: # teardown
03-23 13:09:03.184  3277  3337 I jxcore-log: 
,03-23 13:09:03.347  3277  3337 I jxcore-log: ok 483 should not be in started state
03-23 13:09:03.347  3277  3337 I jxcore-log: 
,03-23 13:09:03.353  3277  3337 I jxcore-log: # setup
03-23 13:09:03.353  3277  3337 I jxcore-log: 
,03-23 13:09:03.472  3277  3337 I jxcore-log: ok 484 should be in started state
03-23 13:09:03.472  3277  3337 I jxcore-log: 
,03-23 13:09:03.480  3277  3337 I jxcore-log: # 139. #start should fail if called twice in a row
03-23 13:09:03.480  3277  3337 I jxcore-log: 
,03-23 13:09:03.637  3277  3337 I jxcore-log: ok 485 specific error should be received
03-23 13:09:03.637  3277  3337 I jxcore-log: 
,03-23 13:09:03.642  3277  3337 I jxcore-log: # teardown
03-23 13:09:03.642  3277  3337 I jxcore-log: 
,03-23 13:09:03.757  3277  3337 I jxcore-log: ok 486 should not be in started state
03-23 13:09:03.757  3277  3337 I jxcore-log: 
,03-23 13:09:03.762  3277  3337 I jxcore-log: # setup
03-23 13:09:03.762  3277  3337 I jxcore-log: 
,03-23 13:09:03.901  3277  3337 I jxcore-log: ok 487 should be in started state
03-23 13:09:03.901  3277  3337 I jxcore-log: 
,03-23 13:09:03.903  3277  3337 I jxcore-log: # 140. should not be started after stop is called
03-23 13:09:03.903  3277  3337 I jxcore-log: 
,03-23 13:09:03.997  3277  3337 I jxcore-log: ok 488 should not be started
,03-23 13:09:03.997  3277  3337 I jxcore-log: 
03-23 13:09:03.998  3277  3337 I jxcore-log: ok 489 should not be listening
03-23 13:09:03.998  3277  3337 I jxcore-log: 
03-23 13:09:04.000  3277  3337 I jxcore-log: ok 490 should not target listening
03-23 13:09:04.000  3277  3337 I jxcore-log: 
,03-23 13:09:04.001  3277  3337 I jxcore-log: ok 491 should not be advertising
03-23 13:09:04.001  3277  3337 I jxcore-log: 
03-23 13:09:04.001  3277  3337 I jxcore-log: ok 492 should not target advertising
03-23 13:09:04.001  3277  3337 I jxcore-log: 
,03-23 13:09:04.003  3277  3337 I jxcore-log: # teardown
03-23 13:09:04.003  3277  3337 I jxcore-log: 
,03-23 13:09:04.114  3277  3337 I jxcore-log: ok 493 should not be in started state
03-23 13:09:04.114  3277  3337 I jxcore-log: 
,03-23 13:09:04.121  3277  3337 I jxcore-log: # setup
03-23 13:09:04.121  3277  3337 I jxcore-log: 
,03-23 13:09:04.253  3277  3337 I jxcore-log: ok 494 should be in started state
03-23 13:09:04.253  3277  3337 I jxcore-log: 
,03-23 13:09:04.261  3277  3337 I jxcore-log: # 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-23 13:09:04.261  3277  3337 I jxcore-log: 
,03-23 13:09:04.413  3277  3337 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-23 13:09:04.413  3277  3337 I jxcore-log: 
,03-23 13:09:04.416  3277  3337 I jxcore-log: ok 495 specific error should be received
03-23 13:09:04.416  3277  3337 I jxcore-log: 
,03-23 13:09:04.418  3277  3337 I jxcore-log: # teardown
03-23 13:09:04.418  3277  3337 I jxcore-log: 
,03-23 13:09:04.522  3277  3337 I jxcore-log: ok 496 should not be in started state
03-23 13:09:04.522  3277  3337 I jxcore-log: 
,03-23 13:09:04.524  3277  3337 I jxcore-log: # setup
03-23 13:09:04.524  3277  3337 I jxcore-log: 
,03-23 13:09:04.661  3277  3337 I jxcore-log: ok 497 should be in started state
03-23 13:09:04.661  3277  3337 I jxcore-log: ,
03-23 13:09:04.663  3277  3337 I jxcore-log: # 142. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-23 13:09:04.663  3277  3337 I jxcore-log: 
,03-23 13:09:04.807  3277  3337 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-23 13:09:04.807  3277  3337 I jxcore-log: ,
,03-23 13:09:04.810  3277  3337 I jxcore-log: ok 498 specific error expected
03-23 13:09:04.810  3277  3337 I jxcore-log: 
03-23 13:09:04.813  3277  3337 I jxcore-log: # teardown
03-23 13:09:04.813  3277  3337 I jxcore-log: 
,03-23 13:09:04.937  3277  3337 I jxcore-log: ok 499 should not be in started state
03-23 13:09:04.937  3277  3337 I jxcore-log: 
,03-23 13:09:04.942  3277  3337 I jxcore-log: # setup
03-23 13:09:04.942  3277  3337 I jxcore-log: 
,03-23 13:09:05.090  3277  3337 I jxcore-log: ok 500 should be in started state
03-23 13:09:05.090  3277  3337 I jxcore-log: 
,03-23 13:09:05.098  3277  3337 I jxcore-log: # 143. #startUpdateAdvertisingAndListening should start hosting given router object
03-23 13:09:05.098  3277  3337 I jxcore-log: 
,03-23 13:09:05.308  3277  3337 I jxcore-log: ok 501 server should respond with code 200
03-23 13:09:05.308  3277  3337 I jxcore-log: 
,03-23 13:09:05.313  3277  3337 I jxcore-log: # teardown
03-23 13:09:05.313  3277  3337 I jxcore-log: 
,03-23 13:09:05.454  3277  3337 I jxcore-log: ok 502 should not be in started state
,03-23 13:09:05.454  3277  3337 I jxcore-log: 
,03-23 13:09:05.461  3277  3337 I jxcore-log: # setup
03-23 13:09:05.461  3277  3337 I jxcore-log: ,
,03-23 13:09:05.632  3277  3337 I jxcore-log: ok 503 should be in started state
,03-23 13:09:05.632  3277  3337 I jxcore-log: 
,03-23 13:09:05.635  3277  3337 I jxcore-log: # 144. #stop can be called multiple times in a row
,03-23 13:09:05.635  3277  3337 I jxcore-log: 
,03-23 13:09:05.772  3277  3337 I jxcore-log: ok 504 should be in stopped state
,03-23 13:09:05.772  3277  3337 I jxcore-log: 
03-23 13:09:05.774  3277  3337 I jxcore-log: ok 505 should still be in stopped state
03-23 13:09:05.774  3277  3337 I jxcore-log: 
03-23 13:09:05.775  3277  3337 I jxcore-log: # teardown
03-23 13:09:05.775  3277  3337 I jxcore-log: ,
,03-23 13:09:05.993  3277  3337 I jxcore-log: ok 506 should not be in started state,
03-23 13:09:05.993  3277  3337 I jxcore-log: 
,03-23 13:09:05.998  3277  3337 I jxcore-log: # setup
,03-23 13:09:05.998  3277  3337 I jxcore-log: 
,03-23 13:09:06.267  3277  3337 I jxcore-log: ok 507 should be in started state
03-23 13:09:06.267  3277  3337 I jxcore-log: 
,03-23 13:09:06.273  3277  3337 I jxcore-log: # 145. #startListeningForAdvertisements can be called multiple times in a row,
03-23 13:09:06.273  3277  3337 I jxcore-log: 
,03-23 13:09:06.416  3277  3337 I jxcore-log: ok 508 should be in listening state
03-23 13:09:06.416  3277  3337 I jxcore-log: 
,03-23 13:09:06.417  3277  3337 I jxcore-log: ok 509 should still be in listening state
03-23 13:09:06.417  3277  3337 I jxcore-log: 
,03-23 13:09:06.421  3277  3337 I jxcore-log: # teardown
03-23 13:09:06.421  3277  3337 I jxcore-log: 
,03-23 13:09:06.554  3277  3337 I jxcore-log: ok 510 should not be in started state
03-23 13:09:06.554  3277  3337 I jxcore-log: 
,03-23 13:09:06.556  3277  3337 I jxcore-log: # setup
03-23 13:09:06.556  3277  3337 I jxcore-log: 
,03-23 13:09:06.774  3277  3337 I jxcore-log: ok 511 should be in started state
03-23 13:09:06.774  3277  3337 I jxcore-log: 
03-23 13:09:06.776  3277  3337 I jxcore-log: # 146. #stopListeningForAdvertisements can be called multiple times in a row
03-23 13:09:06.776  3277  3337 I jxcore-log: 
,03-23 13:09:06.942  3277  3337 I jxcore-log: ok 512 should not be in listening state
03-23 13:09:06.942  3277  3337 I jxcore-log: 
03-23 13:09:06.947  3277  3337 I jxcore-log: ok 513 should still not be in listening state
03-23 13:09:06.947  3277  3337 I jxcore-log: 
,03-23 13:09:06.952  3277  3337 I jxcore-log: # teardown,
03-23 13:09:06.952  3277  3337 I jxcore-log: 
,03-23 13:09:07.131  3277  3337 I jxcore-log: ok 514 should not be in started state
03-23 13:09:07.131  3277  3337 I jxcore-log: 
,03-23 13:09:07.133  3277  3337 I jxcore-log: # setup
03-23 13:09:07.133  3277  3337 I jxcore-log: 
,03-23 13:09:07.251  3277  3337 I jxcore-log: ok 515 should be in started state
03-23 13:09:07.251  3277  3337 I jxcore-log: 
,03-23 13:09:07.253  3277  3337 I jxcore-log: # 147. #stopAdvertisingAndListening can be called multiple times in a row
03-23 13:09:07.253  3277  3337 I jxcore-log: 
,03-23 13:09:07.371  3277  3337 I jxcore-log: ok 516 should not be in advertising state
03-23 13:09:07.371  3277  3337 I jxcore-log: 
,03-23 13:09:07.372  3277  3337 I jxcore-log: ok 517 should still not be in advertising state,
03-23 13:09:07.372  3277  3337 I jxcore-log: 
,03-23 13:09:07.375  3277  3337 I jxcore-log: # teardown
,03-23 13:09:07.375  3277  3337 I jxcore-log: 
,03-23 13:09:07.504  3277  3337 I jxcore-log: ok 518 should not be in started state,
03-23 13:09:07.504  3277  3337 I jxcore-log: 
03-23 13:09:07.511  3277  3337 I jxcore-log: # setup
03-23 13:09:07.511  3277  3337 I jxcore-log: 
,03-23 13:09:07.611  3277  3337 I jxcore-log: ok 519 should be in started state,
03-23 13:09:07.611  3277  3337 I jxcore-log: 
03-23 13:09:07.613  3277  3337 I jxcore-log: # 148. functions are run from a queue in the right order,
03-23 13:09:07.613  3277  3337 I jxcore-log: 
,03-23 13:09:07.774  3277  3337 I jxcore-log: ok 520 call order must match
,03-23 13:09:07.774  3277  3337 I jxcore-log: 
,03-23 13:09:07.781  3277  3337 I jxcore-log: # teardown
03-23 13:09:07.781  3277  3337 I jxcore-log: ,
,03-23 13:09:07.868  3277  3337 I jxcore-log: ok 521 should not be in started state
,03-23 13:09:07.868  3277  3337 I jxcore-log: 
,03-23 13:09:07.873  3277  3337 I jxcore-log: # setup
,03-23 13:09:07.873  3277  3337 I jxcore-log: 
,03-23 13:09:08.055  3277  3337 I jxcore-log: # 149. #ThaliPeerPoolDefault - single action
03-23 13:09:08.055  3277  3337 I jxcore-log: ,
,03-23 13:09:08.171  3277  3337 I jxcore-log: ok 522 is an agent,
03-23 13:09:08.171  3277  3337 I jxcore-log: 
,03-23 13:09:08.172  3277  3337 I jxcore-log: ok 523 enqueue is fine
03-23 13:09:08.172  3277  3337 I jxcore-log: 
,03-23 13:09:08.174  3277  3337 I jxcore-log: ok 524 Everything should be off the queue
03-23 13:09:08.174  3277  3337 I jxcore-log: 
,03-23 13:09:08.177  3277  3337 I jxcore-log: # teardown
03-23 13:09:08.177  3277  3337 I jxcore-log: 
,03-23 13:09:08.304  3277  3337 I jxcore-log: # setup
03-23 13:09:08.304  3277  3337 I jxcore-log: 
,03-23 13:09:08.420  3277  3337 I jxcore-log: # 150. #ThaliPeerPoolDefault - multiple actions
03-23 13:09:08.420  3277  3337 I jxcore-log: 
,03-23 13:09:08.588  3277  3337 I jxcore-log: ok 525 is an agent
03-23 13:09:08.588  3277  3337 I jxcore-log: 
,03-23 13:09:08.591  3277  3337 I jxcore-log: ok 526 first enqueue is fine
03-23 13:09:08.591  3277  3337 I jxcore-log: 
,03-23 13:09:08.593  3277  3337 I jxcore-log: ok 527 is an agent
03-23 13:09:08.593  3277  3337 I jxcore-log: 
,03-23 13:09:08.594  3277  3337 I jxcore-log: ok 528 second enqueue is fine
03-23 13:09:08.594  3277  3337 I jxcore-log: 
03-23 13:09:08.598  3277  3337 I jxcore-log: ok 529 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-23 13:09:08.598  3277  3337 I jxcore-log: 
03-23 13:09:08.598  3277  3337 I jxcore-log: ok 530 Queue is empty
03-23 13:09:08.598  3277  3337 I jxcore-log: 
,03-23 13:09:08.601  3277  3337 I jxcore-log: # teardown
03-23 13:09:08.601  3277  3337 I jxcore-log: 
,03-23 13:09:08.889  3277  3337 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-23 13:09:08.889  3277  3337 I jxcore-log: 
,03-23 13:09:09.202  3906  3906 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-23 13:09:09.205  3906  3906 D AndroidRuntime: CheckJNI is OFF
,03-23 13:09:09.320  3906  3906 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-23 13:09:09.330   822   856 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-23 13:09:09.331   822   856 I ActivityManager: Killing 3277:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-23 13:09:09.422   822  1391 I WindowState: WIN DEATH: Window{32db89dd u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-23 13:09:09.424   822  1024 D WifiService: Client connection lost with reason: 4
,03-23 13:09:09.434   822   866 W PackageSettings: Skipping PackageSetting{d2eb9fe com.example.hello/10273} due to missing metadata
,03-23 13:09:09.445   822   856 W ActivityManager: Force removing ActivityRecord{c10a2af u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-23 13:09:09.460   822   822 V ActivityManager: Display changed displayId=0
,03-23 13:09:09.468   822  1313 W ActivityManager: Spurious death for ProcessRecord{30e698f6 3277:com.test.thalitest/u0a95}, curProc for 3277: null
03-23 13:09:09.468   822   866 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-23 13:09:09.487  1233  1233 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-23 13:09:09.496   822  1001 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-23 13:09:09.500   822  1044 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-23 13:09:09.509  2976  2976 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-23 13:09:09.512  1233  3921 I Keyboard.Facilitator.DecoderInitializer: run()
,03-23 13:09:09.535  1065  1065 I art     : Explicit concurrent mark sweep GC freed 51778(2MB) AllocSpace objects, 0(0B) LOS objects, 14% free, 91MB/107MB, paused 10.081ms total 61.973ms
,03-23 13:09:09.543   822   822 I art     : Explicit concurrent mark sweep GC freed 46214(2MB) AllocSpace objects, 7(206KB) LOS objects, 31% free, 34MB/50MB, paused 2.448ms total 70.341ms
03-23 13:09:09.543   822  1357 I art     : WaitForGcToComplete blocked for 57.841ms for cause Explicit
,03-23 13:09:09.570  1513  1513 I art     : Explicit concurrent mark sweep GC freed 10889(533KB) AllocSpace objects, 2(32KB) LOS objects, 22% free, 27MB/35MB, paused 378us total 99.832ms
,03-23 13:09:09.598   822  1357 I art     : Explicit concurrent mark sweep GC freed 5039(481KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.416ms total 54.843ms
,03-23 13:09:09.600  1233  3921 I Decoder : createOrResetDecoder
,03-23 13:09:09.601   822   866 I art     : WaitForGcToComplete blocked for 81.547ms for cause Explicit
,03-23 13:09:09.637   822   822 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-23 13:09:09.637   822   822 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-23 13:09:09.639   822   838 I ActivityManager: Start proc 3923:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-23 13:09:09.642  1261  1261 I ConfigService: onCreate
,03-23 13:09:09.646  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-23 13:09:09.654   822   838 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3277 uid 10095
,03-23 13:09:09.658  1233  1233 I Keyboard.Facilitator: onFinishInput()
,03-23 13:09:09.661  1233  3921 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-23 13:09:09.689  1233  3921 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-23 13:09:09.690  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-23 13:09:09.690  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-23 13:09:09.694  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-23 13:09:09.705  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-23 13:09:09.705  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-23 13:09:09.705  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-23 13:09:09.711  1513  1513 W LocationOracleImpl: Best location was null
,03-23 13:09:09.723   822   866 I art     : Explicit concurrent mark sweep GC freed 4963(238KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.143ms total 105.647ms
,03-23 13:09:09.727  1347  1347 I art     : Explicit concurrent mark sweep GC freed 4966(363KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 571us total 31.537ms
,03-23 13:09:09.729  1513  3949 I HotwordRecognitionRnr: Starting hotword detection.
,03-23 13:09:09.731  1513  3950 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@35b58b8f
03-23 13:09:09.731  1233  3921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-23 13:09:09.731  1233  3921 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-23 13:09:09.731  1233  3921 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-23 13:09:09.732  1233  3921 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,03-23 13:09:09.732  1233  3921 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-23 13:09:09.732  1233  3921 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-23 13:09:09.736   358  3952 I AudioFlinger: AudioFlinger's thread 0xb4037000 ready to run
,03-23 13:09:09.738   358  1021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-23 13:09:09.739  1513  3950 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@35b58b8f
,03-23 13:09:09.748   358  3952 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-23 13:09:09.748   358  3952 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-23 13:09:09.748   358  3952 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-23 13:09:09.748   358  3952 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-23 13:09:09.756   358  3952 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-23 13:09:09.770  3923  3956 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-23 13:09:09.786   822   838 I ActivityManager: Start proc 3958:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-23 13:09:09.793  1347  1347 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-23 13:09:09.794  1347  1347 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-23 13:09:09.816  3906  3906 I art     : System.exit called, status: 0
03-23 13:09:09.816  3906  3906 I AndroidRuntime: VM exiting with result code 0.
,03-23 13:09:09.825  3923  3945 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-23 13:09:09.830  1513  1513 I HotwordWorker: onReady
,03-23 13:09:09.845   822   866 I ActivityManager: Start proc 3981:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-23 13:09:09.872   822  1100 I ActivityManager: Start proc 3998:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-23 13:09:09.888   822  1100 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@94dfc77}
,03-23 13:09:09.890   822  1023 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-23 13:09:09.905   822  1346 I ActivityManager: Killing 3622:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-23 13:09:09.909   822  1023 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=591.62 rxSuccessRate=714.25 targetRoamBSSID=any RSSI=-127
,03-23 13:09:09.920  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-23 13:09:09.950   822  1251 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659176211
03-23 13:09:09.950   822  1251 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-23 13:09:10.022  1261  1261 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,03-23 13:09:10.023  1261  1261 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
03-23 13:09:10.024  1261  1261 E AndroidRuntime: FATAL EXCEPTION: main
03-23 13:09:10.024  1261  1261 E AndroidRuntime: Process: com.google.process.gapps, PID: 1261
03-23 13:09:10.024  1261  1261 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-23 13:09:10.024  1261  1261 E AndroidRuntime: 	... 9 more
,03-23 13:09:10.031   822  4021 E DropBoxManagerService: Can't write: system_app_crash
03-23 13:09:10.031   822  4021 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-23 13:09:10.031   822  4021 E DropBoxManagerService: 	... 5 more
,03-23 13:09:10.040  3998  4019 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-23 13:09:10.040  3998  4019 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-23 13:09:10.040  3998  4019 E AndroidRuntime: Process: com.android.keychain, PID: 3998
03-23 13:09:10.040  3998  4019 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.ja,va:791)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-23 13:09:10.040  3998  4019 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-23 13:09:10.043  3923  3945 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
03-23 13:09:10.044  3923  3945 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-23 13:09:10.044  3923  3945 E AndroidRuntime: Process: android.process.acore, PID: 3923
03-23 13:09:10.044  3923  3945 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-23 13:09:10.044  3923  3945 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-23 13:09:10.049   822  4024 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-23 13:09:10.049   822   856 D Atlas   : Validating map...
03-23 13:09:10.057   822  4026 E DropBoxManagerService: Can't write: system_app_crash
03-23 13:09:10.057   822  4026 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-23 13:09:10.057   822  4026 E DropBoxManagerService: 	... 5 more
03-23 13:09:10.059   822  4025 E DropBoxManagerService: Can't write: system_app_crash
03-23 13:09:10.059   822  4025 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-23 13:09:10.059   822  4025 E DropBoxManagerService: 	... 5 more
,03-23 13:09:10.106   822  4024 I OpenGLRenderer: Initialized EGL, version 1.4
03-23 13:09:10.112   822  4024 D OpenGLRenderer: Enabling debug mode 0
,03-23 13:09:10.322  1513  1513 I HotwordDetector: Closing mic
,03-23 13:09:10.322  1513  1765 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@35b58b8f
,03-23 13:09:10.345  1513  4030 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-23 13:09:10.361   822  1161 I ActivityManager: Killing 3604:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-23 13:09:10.376   358  3952 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-23 13:09:10.377   358  3952 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-23 13:09:10.383   358  1021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-23 13:09:10.386  1513  3949 I HotwordRecognitionRnr: Hotword detection finished
,03-23 13:09:10.387  1513  1767 I HotwordRecognitionRnr: Stopping hotword detection.
,03-23 13:09:10.467   822  1161 I ActivityManager: Killing 3643:com.google.android.deskclock/u0a44 (adj 15): empty #18
,03-23 13:09:10.744  1233  3921 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-23 13:09:10.744  1233  3921 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-23 13:09:10.773  1233  3921 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-23 13:09:10.773  1233  3921 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-23 13:09:10.802  1233  3921 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-23 13:09:10.802  1233  3921 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-23 13:09:10.802  1233  3921 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-23 13:09:10.802  1233  3921 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-23 13:09:11.607   822  1412 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@94dfc77}
,03-23 13:09:14.771  1513  4038 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-23 13:09:15.206   822  1251 E QMI_FW  : xport_send: Sendto failed for port 4608
03-23 13:09:15.206   822  1251 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-23 13:09:15.206   822  1251 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659176211
03-23 13:09:15.207   822  1251 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-23 13:09:15.212   259   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
