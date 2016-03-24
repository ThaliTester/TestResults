#### Test 64065450860dd96_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-24 18:26:12.345  1263  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 18:26:12.443  1263  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 18:26:12.444  1263  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:12.445  1263  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:12.445  1263  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 18:26:12.456  1263  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 18:26:12.555   822  1487 I art     : Explicit concurrent mark sweep GC freed 44938(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.358ms total 81.765ms
03-24 18:26:12.627  2739  2739 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 18:26:12.627  2739  2739 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 18:26:12.627  2739  2739 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
03-24 18:26:12.674  3235  3235 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 18:26:12.676  3235  3235 D AndroidRuntime: CheckJNI is OFF
03-24 18:26:12.781  3235  3235 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 18:26:12.785   822  1282 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 18:26:12.792   822  1282 V WindowManager: addAppToken: AppWindowToken{28905737 token=Token{26388c36 ActivityRecord{8289d1 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 18:26:12.795  3235  3235 D AndroidRuntime: Shutting down VM
03-24 18:26:12.810  1518  1518 I HotwordDetector: Closing mic
03-24 18:26:12.810  1518  1807 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2a3de9b6
03-24 18:26:12.817   822   861 V WindowManager: Adding window Window{3128ec0e u0 Starting com.test.thalitest} at 2 of 7 (after Window{2e5f2c37 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 18:26:12.834   822   838 I ActivityManager: Start proc 3251:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 18:26:12.874   359  1813 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 18:26:12.875   359  1813 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 18:26:12.879   359  1037 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 18:26:12.888  1518  1810 I HotwordRecognitionRnr: Hotword detection finished
03-24 18:26:12.889  1518  1809 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 18:26:12.904   822  1282 I ActivityManager: Killing 2868:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,03-24 18:26:13.112   822  1282 I ActivityManager: Killing 2697:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-24 18:26:13.201   822   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-24 18:26:13.212   822   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 18:26:13.291   260   278 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (395 us)
,03-24 18:26:13.319  3251  3251 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 18:26:13.341  3251  3251 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5282-5287)
03-24 18:26:13.341  3251  3251 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 18:26:13.347   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658045715
03-24 18:26:13.347   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 18:26:13.366  3251  3251 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7f3bc4f}
03-24 18:26:13.367  3251  3251 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 18:26:13.367  3251  3251 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 18:26:13.380  3251  3251 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 18:26:13.380  3251  3251 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 18:26:13.381  3251  3251 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 18:26:13.396  3251  3280 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 18:26:13.404  3251  3251 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 18:26:13.411  3251  3251 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 18:26:13.412  3251  3251 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 18:26:13.412  3251  3251 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 18:26:13.432   872   872 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-24 18:26:13.432   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 18:26:13.474   872   872 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-24 18:26:13.474   872   872 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 18:26:13.513   822   860 D BluetoothManagerService: Message: 20
03-24 18:26:13.514   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e591eca:true
,03-24 18:26:13.543  3251  3251 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 18:26:13.551  3251  3251 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 18:26:13.567  3251  3251 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 18:26:13.575  3251  3251 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 18:26:13.575  3251  3251 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 18:26:13.641  3251  3304 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 18:26:13.644  3251  3251 D Atlas   : Validating map...
,03-24 18:26:13.650   822  1340 V WindowManager: Adding window Window{4dece7a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3128ec0e u0 Starting com.test.thalitest})
,03-24 18:26:13.652  3251  3291 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 18:26:13.685  3251  3304 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 18:26:13.690  3251  3304 D OpenGLRenderer: Enabling debug mode 0
,03-24 18:26:13.787   822   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +983ms
,03-24 18:26:13.796  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-24 18:26:13.871  3251  3251 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3251
,03-24 18:26:13.875   822   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-24 18:26:13.875   822   822 V ActivityManager: Display changed displayId=0
03-24 18:26:13.875   260   260 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-24 18:26:13.876   260   260 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 18:26:13.969  3251  3251 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 18:26:14.106  3251  3306 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580518912
,03-24 18:26:14.111  3251  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
03-24 18:26:14.111  3251  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 18:26:14.111  3251  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 18:26:14.111  3251  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
,03-24 18:26:14.111  3251  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 18:26:14.111  3251  3306 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e9b028 added. We now have 1 listener(s)
,03-24 18:26:14.111   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:26:14.113  3251  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-24 18:26:14.114  3251  3306 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:26:14.114  3251  3306 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 18:26:14.114  3251  3306 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500,
03-24 18:26:14.117  3251  3306 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c231427 added. We now have 1 listener(s),
03-24 18:26:14.117  3251  3306 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 18:26:14.137   822  1019 D WifiService: New client listening to asynchronous messages
,03-24 18:26:14.141   260   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 18:26:14.142  3251  3306 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 18:26:14.143   260   260 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-24 18:26:14.143   822  1053 D SurfaceControl: Excessive delay in setPowerMode(): 269ms
,03-24 18:26:14.145  3251  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 18:26:14.145  3251  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-24 18:26:14.145  3251  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 18:26:14.145  3251  3306 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 18:26:14.148   822   863 I DreamManagerService: Entering dreamland.
03-24 18:26:14.149  3251  3306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:26:14.149   359  1038 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-24 18:26:14.149   359  1038 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
03-24 18:26:14.149   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:26:14.150   822   863 I PowerManagerService: Dozing...
03-24 18:26:14.151   822   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 18:26:14.153   822  1018 E WifiStateMachine: cancelDelayedScan -> 17
03-24 18:26:14.154  3251  3306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 18:26:14.156   822  1018 E native  : do suspend false
,03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 18:26:14.160  3251  3306 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 18:26:14.160  3251  3306 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 18:26:14.160  3251  3306 D io.jxcore.node.ConnectivityMonitor: start: OK
03-24 18:26:14.160  3251  3306 I io.jxcore.node.LifeCycleMonitor: start: OK
03-24 18:26:14.164  3251  3251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 18:26:14.188  3251  3251 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 18:26:14.202  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-24 18:26:14.206   822  1018 E WifiStateMachine: cancelDelayedScan -> 19
,03-24 18:26:14.218   822  1018 E native  : do suspend true
,03-24 18:26:14.331   359  1039 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 18:26:14.331   359  1039 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 18:26:14.361   822  1018 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,03-24 18:26:14.465   872   872 I kickstart: STATUS: Received file 'm9kefs1'
03-24 18:26:14.465   872   872 I kickstart: STATUS: 950272 bytes transferred in 0.990790 seconds
,03-24 18:26:14.465   872   872 I kickstart: STATUS: Successfully downloaded files from target 
03-24 18:26:14.465   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 18:26:14.468   872   872 I kickstart: STATUS: Sahara protocol completed
,03-24 18:26:14.791  3251  3316 W jxcore-log: Initializing JXcore engine
,03-24 18:26:14.791  3251  3316 W jxcore-log: JXcore engine is ready
,03-24 18:26:14.818  3316  3316 W Thread-346: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11548]" dev="sockfs" ino=11548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 18:26:14.818  3316  3316 W Thread-346: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-24 18:26:14.818  3316  3316 W Thread-346: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10626]" dev="sockfs" ino=10626 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 18:26:14.818  3316  3316 W Thread-346: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21141]" dev="sockfs" ino=21141 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-24 18:26:14.841  3251  3316 W jxcore-log: Starting JXcore engine,
,03-24 18:26:14.917  3251  3316 W jxcore-log: Platform android,
03-24 18:26:14.917  3251  3316 W jxcore-log: 
03-24 18:26:14.917  3251  3316 W jxcore-log: Process ARCH arm
03-24 18:26:14.917  3251  3316 W jxcore-log: 
,03-24 18:26:15.109  3251  3316 I jxcore-log: JXcore Cordova bridge is ready!
03-24 18:26:15.109  3251  3316 I jxcore-log: 
,03-24 18:26:15.110  3251  3316 W jxcore-log: JXcore engine is started
,03-24 18:26:15.125  3251  3306 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 18:26:15.130  3251  3251 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,03-24 18:26:15.362  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 18:26:15.362  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:16.364  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 18:26:16.364  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:17.366  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 18:26:17.366  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:18.367  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 18:26:18.368  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:19.369  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 18:26:19.370  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:20.371  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 18:26:20.371  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:21.373  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 18:26:21.374  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:22.376  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 18:26:22.376  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:23.378  1156  1156 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 18:26:23.378  1156  1156 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 18:26:23.779   822  1018 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,03-24 18:26:24.192  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:26:24.192  3251  3316 I jxcore-log: 
,03-24 18:26:24.195  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:26:24.195  3251  3316 I jxcore-log: 
,03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 18:26:24.200  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
03-24 18:26:24.202  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-24 18:26:24.204  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 18:26:24.204  3251  3316 I jxcore-log: 
,03-24 18:26:24.206  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:26:24.206  3251  3316 I jxcore-log: ,
,03-24 18:26:24.722  3251  3316 I jxcore-log: Unit Test app is loaded
,03-24 18:26:24.722  3251  3316 I jxcore-log: 
,03-24 18:26:24.727  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,03-24 18:26:24.727  3251  3316 I jxcore-log: 
,03-24 18:26:24.743  3251  3316 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 18:26:24.746  3251  3316 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 18:26:24.746  3251  3316 I jxcore-log: 
03-24 18:26:24.747  3251  3316 I jxcore-log: My device name is: motorola-Nexus 6
03-24 18:26:24.747  3251  3316 I jxcore-log: 
,03-24 18:26:24.760  3251  3251 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 18:26:25.404  1156  1156 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
,03-24 18:26:25.862  1156  1156 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 18:26:25.900  1156  1156 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-24 18:26:25.901  1156  1156 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 18:26:25.915   822  1018 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-24 18:26:25.915   822  1018 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-24 18:26:25.915   822  1020 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 18:26:25.921   822  1018 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 18:26:25.927   355   800 D CommandListener: Setting iface cfg,
03-24 18:26:25.930   822  1018 E WifiStateMachine: Start Dhcp Watchdog 1
,03-24 18:26:25.933   822  1018 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 18:26:25.933   822  1018 E WifiStateMachine:  my bss beacon rx: 1
03-24 18:26:25.933   822  1018 E WifiStateMachine:  RSSI mgmt: -39
03-24 18:26:25.933   822  1018 E WifiStateMachine:  BE :  rx=0 tx=2 lost=0 retries=0
03-24 18:26:25.933   822  1018 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 18:26:25.933   822  1018 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 18:26:25.933   822  1018 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 18:26:25.933   822  1018 E WifiStateMachine:  on_time : 0 tx_time=64 rx_time=84 scan_time=0
,03-24 18:26:26.024   822  1018 E native  : do suspend false
,03-24 18:26:26.037   822  1018 E WifiStateMachine: scanCount==0 - aborting
,03-24 18:26:26.286  3322  3322 I dhcpcd  : version 5.5.6 starting
,03-24 18:26:26.399  3322  3322 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 18:26:26.497  3322  3322 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-24 18:26:26.643  3322  3322 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds,
,03-24 18:26:27.059   822  1018 E native  : do suspend true
,03-24 18:26:27.103   822  1020 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-24 18:26:27.105   822  1020 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 18:26:27.110   822  1018 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 18:26:27.122   822  1020 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-24 18:26:27.122   822  1020 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-24 18:26:27.124   822  1020 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 18:26:27.125   822  1020 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
03-24 18:26:27.126   822  1020 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 18:26:27.133   822  1020 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 18:26:27.137   822  1020 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-24 18:26:27.137   822  3320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-24 18:26:27.137   822  3320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-24 18:26:27.137   822  3320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-24 18:26:27.137   822  3320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 18:26:27.137   822  1020 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 18:26:27.138   822  1020 D ConnectivityService:    accepting network in place of null
,03-24 18:26:27.139   822  1020 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-24 18:26:27.140   822  1020 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 18:26:27.144   822  1020 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-24 18:26:27.145  1076  1556 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 18:26:27.145   822  1020 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 18:26:27.145   822  1020 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-24 18:26:27.147   822  1020 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-24 18:26:27.148   822   860 D Tethering: MasterInitialState.processMessage what=3
,03-24 18:26:27.157   822  1282 V BackupManagerService: Scheduling immediate backup pass
,03-24 18:26:27.161  2924  2924 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-24 18:26:27.161  1359  1386 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 18:26:27.161  1359  1386 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:26:27.162  3251  3251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:26:27.163   822   855 D TelephonyManager: getDataEnabled: retVal=false
,03-24 18:26:27.164  3251  3251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:26:27.169  2924  2924 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
03-24 18:26:27.170   822   822 V BackupManagerService: Running a backup pass
03-24 18:26:27.171   822  1052 V BackupManagerService: clearing pending backups
,03-24 18:26:27.179   822  1052 V PerformBackupTask: Beginning backup of 14 targets
,03-24 18:26:27.184   822   855 E GpsLocationProvider: No APN found to select.
,03-24 18:26:27.186   822  1052 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 18:26:27.197   822  1052 V BackupServiceBinder: doBackup() invoked
,03-24 18:26:27.208   822  1052 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 18:26:27.218   822  1371 I ActivityManager: Start proc 3365:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 18:26:27.248   822  1052 I BackupRestoreController: Getting widget state for user: 0
,03-24 18:26:27.267   822  1295 D AlarmManagerService: Setting time of day to sec=1458840387
03-24 18:26:27.830   822  1295 W AlarmManagerService: Unable to set rtc to 1458840387: Invalid argument
,03-24 18:26:27.868  1845  1861 W GmsBackupTransport: Unknown package in backup request: @pm@
03-24 18:26:27.869  1845  1861 V GmsBackupTransport: starting performBackup for @pm@
,03-24 18:26:27.879  1845  1861 V GmsBackupTransport: performBackup done for @pm@
,03-24 18:26:27.897   822  3320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 17:26:27 GMT], X-Android-Received-Millis=[1458840387897], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458840387253]}
,03-24 18:26:27.899  1263  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 18:26:27.899   822  1020 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 18:26:27.899   822  3320 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 18:26:27.899   822  1020 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 18:26:27.899   822  1020 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-24 18:26:27.899   822  1020 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 18:26:27.899   822  1020 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 18:26:27.899  1076  1556 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 18:26:27.900   822  1020 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 18:26:27.922   822  1427 I ActivityManager: Start proc 3394:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 18:26:27.932   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 343us total 10.147ms
,03-24 18:26:27.945   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 512us total 11.543ms
,03-24 18:26:27.950  1263  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,03-24 18:26:27.951   822  3412 D GpsLocationProvider: NTP server returned: 1458840387829 (Thu Mar 24 18:26:27 GMT+01:00 2016) reference: 179216 certainty: 33 system time offset: -121
,03-24 18:26:27.951  1263  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:27.951  1263  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:27.951  1263  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:27.956  1263  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:27.966   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 19.461ms
,03-24 18:26:27.990  1263  1281 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:27.990  1263  1281 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:27.990  1263  1281 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:27.990  1263  1281 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 18:26:27.990  1263  1281 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 18:26:27.990  1263  1281 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 18:26:27.990  1263  1281 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 18:26:28.009  1845  1860 W GmsBackupTransport: Error sending final backup to server: 
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 18:26:28.009  1845  1860 W GmsBackupTransport: 	... 1 more
,03-24 18:26:28.010   822  1052 D BackupManagerService: Now staging backup of com.google.android.talk
,03-24 18:26:28.014  3394  3394 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 18:26:28.019   822  1052 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-24 18:26:28.023  3394  3394 D SprintDMHelper: simOperator:  IMSI: null
,03-24 18:26:28.023  3394  3394 D SprintDMReceiver: Not Sprint UICC, don't do anything.
03-24 18:26:28.024   822  1052 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 18:26:28.026   822  1052 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 18:26:28.028   822  1052 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 18:26:28.030   822  1052 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 18:26:28.032   822  1052 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 18:26:28.034   822  1052 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 18:26:28.035   822  1052 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
03-24 18:26:28.037   822  1052 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
03-24 18:26:28.038   822  1052 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 18:26:28.040  1263  1729 I art     : Explicit concurrent mark sweep GC freed 24851(1338KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.126ms total 25.199ms
,03-24 18:26:28.048   822  1052 D BackupManagerService: Now staging backup of com.android.vending
,03-24 18:26:28.052   822  1052 D BackupManagerService: Now staging backup of android
,03-24 18:26:28.057   822  1052 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 18:26:28.063  1845  1901 I GmsBackupTransport: Next backup will happen in 43199933 millis.
03-24 18:26:28.063  1815  3420 W DriveInitializer: Background init thread started
,03-24 18:26:28.066   822  1052 I BackupManagerService: Backup pass finished.
,03-24 18:26:28.067  1815  3414 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 18:26:28.069  1815  1815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 18:26:28.073  1815  1815 D SystemUpdateService: onCreate
03-24 18:26:28.075  1815  1815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 18:26:28.082  1815  3422 I SystemUpdateService: active receiver: enabled
03-24 18:26:28.084  1815  3422 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-24 18:26:28.087  1815  3421 W DriveInitializer: Awaiting to be initialized
,03-24 18:26:28.089  1815  3422 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 18:26:28.089  1815  3422 I SystemUpdateService: now status is 0 (complete)
03-24 18:26:28.089  1815  3422 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 18:26:28.089  1815  3422 I SystemUpdateService: file has been verified
03-24 18:26:28.089  1815  3422 I SystemUpdateService: OTA package size = 25802302
,03-24 18:26:28.091  1815  3422 I SystemUpdateService: showing system update notification
,03-24 18:26:28.099   822   822 I ValidateNoPeople: skipping global notification
,03-24 18:26:28.122  1815  1815 D SystemUpdateService: onDestroy
,03-24 18:26:28.141  1815  3432 I iu.SyncManager: SYNC; picasa accounts
,03-24 18:26:28.153  1815  1815 D NetworkLogImpl: Loaded NetworkSpeedPredictor
03-24 18:26:28.154  1815  1815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-24 18:26:28.158  1263  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
03-24 18:26:28.158  1263  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:28.158  1263  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:28.158  1263  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:28.162  1263  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:28.172  1815  3427 I GcmGroups: Failed to subscribe to group.
03-24 18:26:28.172  1815  3427 I GcmGroups: com.google.android.gms.auth.ad: BadAuthentication
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at android.os.Looper.loop(Looper.java:135)
03-24 18:26:28.172  1815  3427 I GcmGroups: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 18:26:28.175  1815  3427 I GcmGroups: Groups upload failed, retrying in 24000:00:00
,03-24 18:26:28.182  1815  3432 I iu.UploadsManager: num queued entries: 0
03-24 18:26:28.182  1815  3432 I iu.UploadsManager: num updated entries: 0
,03-24 18:26:28.183  1815  3432 I iu.SyncManager: NEXT; no task
,03-24 18:26:28.205  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 18:26:28.205  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:28.205  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:28.205  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:28.208  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:28.260  1815  3420 W DriveInitializer: Background init thread ended
,03-24 18:26:28.274   822  1114 I art     : Explicit concurrent mark sweep GC freed 53193(2MB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.495ms total 57.758ms
,03-24 18:26:28.281  3088  3416 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 18:26:28.281  3088  3416 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jdm.a(PG:82)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jcs.o(PG:406)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jcn.a(PG:1379)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jcs.i(PG:143)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at blb.a(PG:3937)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at czp.a(PG:18188)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at czp.a(PG:9081)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at czq.run(PG:1686)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:26:28.281  3088  3416 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jdj.a(PG:4091)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jdj.a(PG:1125)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jdm.a(PG:77)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	... 12 more
03-24 18:26:28.281  3088  3416 E HttpOperation: Caused by: faj: BadAuthentication
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at fal.a(PG:38)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	at jdj.a(PG:4089)
03-24 18:26:28.281  3088  3416 E HttpOperation: 	... 14 more
,03-24 18:26:28.296   822   855 I ActivityManager: Start proc 3442:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
03-24 18:26:28.320  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 18:26:28.320  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:28.320  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:28.320  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:28.324  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:28.333  3088  3416 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 18:26:28.333  3088  3416 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jdm.a(PG:82)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jcs.o(PG:406)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jcn.a(PG:1379)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jcs.i(PG:143)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at hec.a(PG:42)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at hee.a(PG:102)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at czr.a(PG:65)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at kka.a(PG:108)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at czp.a(PG:19176)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at czp.a(PG:9081)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at czq.run(PG:1686)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:26:28.333  3088  3416 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jdj.a(PG:4091)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jdj.a(PG:1125)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jdm.a(PG:77)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	... 15 more
03-24 18:26:28.333  3088  3416 E HttpOperation: Caused by: faj: BadAuthentication
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at fal.a(PG:38)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	at jdj.a(PG:4089)
03-24 18:26:28.333  3088  3416 E HttpOperation: 	... 17 more
03-24 18:26:28.333  1815  1815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-24 18:26:28.333  3088  3416 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 18:26:28.333  3088  3416 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at hec.a(PG:42)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at hee.a(PG:102)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at czr.a(PG:65)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at kka.a(PG:108)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	... 15 more
03-24 18:26:28.333  3088  3416 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at fal.a(PG:38)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 18:26:28.333  3088  3416 E ExperimentLoader: 	... 17 more
03-24 18:26:28.347  1815  1815 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-24 18:26:28.379   822   837 I ActivityManager: Start proc 3465:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 18:26:28.451   822  1428 I ActivityManager: Killing 2976:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 18:26:28.452   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 39795, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:26:28.599   822   855 I ActivityManager: Start proc 3487:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 18:26:28.621  3465  3465 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 18:26:28.621  3465  3465 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 18:26:28.621  3465  3465 I GAv4    :   adb logcat -s GAv4
03-24 18:26:28.622  1263  3474 D GCM     : Connected
,03-24 18:26:28.623  2664  3461 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 18:26:28.627   822  1371 I ActivityManager: Killing 2997:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 18:26:28.740  3465  3465 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 18:26:28.755  3465  3465 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 18:26:28.756  1263  3474 D GCM     : Message class com.google.f.a.a.p
,03-24 18:26:28.765  3465  3507 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-24 18:26:28.765  1263  1730 I art     : Explicit concurrent mark sweep GC freed 13698(775KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 1.155ms total 25.077ms
,03-24 18:26:28.823  3442  3512 V KeepSync: Connecting to GoogleApiClient
,03-24 18:26:28.869  1815  3525 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 18:26:28.874  1815  3525 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 18:26:28.891  1263  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 18:26:28.891  1263  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:28.891  1263  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:28.891  1263  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:28.896  1263  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: Handling authorization failure
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 18:26:28.908  1815  3525 E ClientConnectionOperation: 	... 7 more
,03-24 18:26:28.911  3442  3512 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 18:26:28.912  3442  3512 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 18:26:28.916  3442  3512 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 18:26:28.918  3442  3512 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 18:26:28.978  3465  3465 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 18:26:28.991  3465  3465 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 371-375)
,03-24 18:26:28.992  3465  3465 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 18:26:28.996  3465  3465 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a773522}
03-24 18:26:28.996  3465  3465 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 18:26:28.996  3465  3465 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 18:26:29.005  3465  3465 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 18:26:29.005  3465  3465 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 18:26:29.008  3465  3465 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 18:26:29.030  3465  3465 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 18:26:29.035  3465  3465 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 18:26:29.035  3465  3465 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 18:26:29.035  3465  3465 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 18:26:29.040  3487  3487 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-24 18:26:29.041  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 18:26:29.041  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:29.041  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:29.041  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:29.045  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:29.048  3487  3487 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 18:26:29.094  3465  3549 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 18:26:29.100  3465  3465 I NSApplication: Starting up...
,03-24 18:26:29.113  3442  3512 E KeepSync: IOException
03-24 18:26:29.113  3442  3512 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 18:26:29.113  3442  3512 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 18:26:29.113  3442  3512 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 18:26:29.113  3442  3512 E KeepSync: 	... 10 more
03-24 18:26:29.113  3442  3512 W KeepSync: Sync result 2
,03-24 18:26:29.137   822  1282 I ActivityManager: Start proc 3556:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 18:26:29.142   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39801, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:26:29.142   822  1282 I ActivityManager: Killing 3047:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-24 18:26:29.149  3487  3542 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 18:26:29.502  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 18:26:29.502  3251  3316 I jxcore-log: 
,03-24 18:26:29.561  3487  3578 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 18:26:29.658  1263  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 18:26:29.658  1263  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:29.658  1263  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:29.658  1263  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:29.662  1263  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:29.731  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 18:26:29.732  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:29.732  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:29.732  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:29.737  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:29.756   822  1285 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1078]: failed status = eLOC_CLIENT_SUCCESS, inject_pos_ind.status = eQMI_LOC_INVALID_PARAMETER_V02, part num = 59, ind.partNum = 0
,03-24 18:26:29.764  3487  3578 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 18:26:29.766  3487  3542 E BooksSync: Soft error
03-24 18:26:29.766  3487  3542 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:26:29.766  3487  3542 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 18:26:29.766  3487  3542 E BooksSync: Sync error
03-24 18:26:29.766  3487  3542 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:26:29.766  3487  3542 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 18:26:29.766  3487  3542 I BooksSync: Finished books sync
,03-24 18:26:29.772   822   837 I ActivityManager: Killing 2454:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 18:26:29.773   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39802, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:26:29.877   822   837 I ActivityManager: Killing 2902:com.android.settings/1000 (adj 15): empty #18
,03-24 18:26:29.886  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 18:26:29.886  3251  3316 I jxcore-log: 
,03-24 18:26:29.897  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 18:26:29.897  3251  3316 I jxcore-log: 
,03-24 18:26:29.901  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 18:26:29.901  3251  3316 I jxcore-log: 
,03-24 18:26:29.937  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 18:26:29.937  3251  3316 I jxcore-log: 
,03-24 18:26:29.952  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 18:26:29.952  3251  3316 I jxcore-log: 
,03-24 18:26:29.956  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 18:26:29.956  3251  3316 I jxcore-log: 
,03-24 18:26:30.154   822  1114 I ActivityManager: Start proc 3583:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-24 18:26:30.157   822  1114 I ActivityManager: Killing 1462:android.process.acore/u0a5 (adj 15): empty #17
,03-24 18:26:31.140   822  1340 I ActivityManager: Killing 2804:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 18:26:31.425   822  1487 I ActivityManager: Start proc 3601:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 18:26:31.477  3601  3601 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458840391477
03-24 18:26:31.477  3601  3601 D         : TimeServiceNative: User Time to be set is 1458840391477
03-24 18:26:31.477  3601  3601 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 18:26:31.477  3601  3601 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 18:26:31.478  3601  3601 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458840391477
03-24 18:26:31.478  3601  3601 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 18:26:31.478   374   875 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458840391477
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458840391477, operation = 0
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 13:38:14
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:Value read from RTC seconds = 19143494000
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:new time 1458840391477 
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon: delta 1439696897477 genoff 1439696897477 
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897477 to memory
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 18:26:31.479   374  3619 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 18:26:31.481   822  1371 I art     : Explicit concurrent mark sweep GC freed 24738(1167KB) AllocSpace objects, 6(232KB) LOS objects, 32% free, 33MB/49MB, paused 1.373ms total 71.087ms
03-24 18:26:31.483  1263  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:31.486   374  3619 D QC-time-services: Updating the TOD offset
03-24 18:26:31.486   374  3619 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897477 to memory
03-24 18:26:31.486   374  3619 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 18:26:31.486   374  3619 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 18:26:31.491   374  3619 E QC-time-services: Daemon:Update to modem bit set
,03-24 18:26:31.491   374  3619 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 18:26:31.491   374  3619 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142875591477
03-24 18:26:31.491  3601  3601 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-24 18:26:31.559   374   875 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 18:26:31.565   374   873 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-24 18:26:31.588   822   837 I ActivityManager: Start proc 3622:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 18:26:31.609  1263  3638 I VacuumService: Vacuum at: now=1458840391609 tag=VacuumService
,03-24 18:26:31.641  3365  3620 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 18:26:31.651  3622  3622 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 18:26:31.651  3622  3622 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 18:26:31.651  3622  3622 I GAv4    :   adb logcat -s GAv4
,03-24 18:26:31.663  3622  3622 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 18:26:31.673  3622  3622 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 18:26:31.679  3622  3642 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 18:26:31.716   822   837 I ActivityManager: Killing 3017:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
03-24 18:26:31.716  1263  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 18:26:31.717  1263  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:31.717  1263  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 18:26:31.717  1263  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:31.829  1263  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:31.909  3365  3620 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 18:26:31.910  3365  3620 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 18:26:31.924   822   838 I ActivityManager: Killing 3137:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-24 18:26:32.047  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 18:26:32.047  3251  3316 I jxcore-log: 
,03-24 18:26:32.056  1815  1815 V Herrevad: NQAS connected
,03-24 18:26:32.065  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 18:26:32.065  3251  3316 I jxcore-log: 
,03-24 18:26:32.077  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-24 18:26:32.077  3251  3316 I jxcore-log: 
,03-24 18:26:32.117  1815  1831 I art     : Explicit concurrent mark sweep GC freed 16131(1251KB) AllocSpace objects, 19(304KB) LOS objects, 35% free, 28MB/44MB, paused 1.642ms total 54.286ms
,03-24 18:26:32.127  3365  3646 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 18:26:32.141   822  1019 D WifiService: New client listening to asynchronous messages
,03-24 18:26:32.157  1263  2121 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,03-24 18:26:32.158  1263  3648 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 18:26:32.175  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:32.200  1263  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 18:26:32.201  1263  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:32.201  1263  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:32.201  1263  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:32.215   822  1110 I ActivityManager: Start proc 3655:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-24 18:26:32.240  3655  3655 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-24 18:26:32.241  1263  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:32.258  3365  3646 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 18:26:32.259  3365  3646 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 18:26:32.289  3655  3655 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@249476ae(com.android.providers.calendar.CalendarProvider2@7f3bc4f)
,03-24 18:26:32.313  1263  1729 I art     : Explicit concurrent mark sweep GC freed 25736(1439KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 966us total 23.421ms
,03-24 18:26:32.357  1263  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 18:26:32.357  1263  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:32.357  1263  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:32.357  1263  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:32.360  1263  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:32.367  2664  3654 E Babel   : UserRecoverableAuthException.
03-24 18:26:32.368  2664  3654 E Babel   : eei: BadAuthentication
03-24 18:26:32.368  2664  3654 E Babel   : 	at eeg.a(Unknown Source)
03-24 18:26:32.368  2664  3654 E Babel   : 	at eeg.a(Unknown Source)
03-24 18:26:32.368  2664  3654 E Babel   : 	at eeg.a(Unknown Source)
03-24 18:26:32.368  2664  3654 E Babel   : 	at g.a(Unknown Source)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cae.a(SourceFile:3089)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-24 18:26:32.368  2664  3654 E Babel   : 	at crl.a(SourceFile:492)
03-24 18:26:32.368  2664  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cas.b(SourceFile:106)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cap.d(SourceFile:335)
03-24 18:26:32.368  2664  3654 E Babel   : 	at caq.run(SourceFile:81)
03-24 18:26:32.368  2664  3654 E Babel   : Error getting auth token
03-24 18:26:32.368  2664  3654 E Babel   : dvm
03-24 18:26:32.368  2664  3654 E Babel   : 	at g.a(Unknown Source)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cae.a(SourceFile:3089)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-24 18:26:32.368  2664  3654 E Babel   : 	at crl.a(SourceFile:492)
03-24 18:26:32.368  2664  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cas.b(SourceFile:106)
03-24 18:26:32.368  2664  3654 E Babel   : 	at cap.d(SourceFile:335)
03-24 18:26:32.368  2664  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-24 18:26:32.370  2664  3654 E Babel   : Account registration failed 1-Redacted-21
03-24 18:26:32.370  2664  3654 E Babel   : cyp: null -- null
03-24 18:26:32.370  2664  3654 E Babel   : 	at cae.a(SourceFile:3121)
03-24 18:26:32.370  2664  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-24 18:26:32.370  2664  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-24 18:26:32.370  2664  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-24 18:26:32.370  2664  3654 E Babel   : 	at crl.a(SourceFile:492)
03-24 18:26:32.370  2664  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-24 18:26:32.370  2664  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 18:26:32.370  2664  3654 E Babel   : 	at cas.b(SourceFile:106)
03-24 18:26:32.370  2664  3654 E Babel   : 	at cap.d(SourceFile:335)
03-24 18:26:32.370  2664  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-24 18:26:32.373  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 18:26:32.373  3251  3316 I jxcore-log: 
,03-24 18:26:32.377  2664  3654 I art     : Note: end time exceeds epoch: 
,03-24 18:26:32.391  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-24 18:26:32.391  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:32.391  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:32.391  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:32.394  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:32.403  1263  1729 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 18:26:32.416  2664  3682 E Babel   : Unexpected exception while authenticating.
,03-24 18:26:32.416  2664  3682 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 18:26:32.416  2664  3682 E Babel   : 	at eeg.b(Unknown Source)
03-24 18:26:32.416  2664  3682 E Babel   : 	at eeg.b(Unknown Source)
03-24 18:26:32.416  2664  3682 E Babel   : 	at g.a(Unknown Source)
03-24 18:26:32.416  2664  3682 E Babel   : 	at cae.b(SourceFile:1146)
03-24 18:26:32.416  2664  3682 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 18:26:32.416  2664  3682 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:26:32.416  2664  3682 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:26:32.416  2664  3682 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 18:26:32.445  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 18:26:32.445  3251  3316 I jxcore-log: 
,03-24 18:26:32.496  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-24 18:26:32.496  3251  3316 I jxcore-log: 
03-24 18:26:32.501  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 18:26:32.501  3251  3316 I jxcore-log: 
,03-24 18:26:32.511  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 18:26:32.511  3251  3316 I jxcore-log: 
,03-24 18:26:32.516  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 18:26:32.516  3251  3316 I jxcore-log: 
,03-24 18:26:32.521  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 18:26:32.521  3251  3316 I jxcore-log: 
,03-24 18:26:32.537  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 18:26:32.537  3251  3316 I jxcore-log: 
,03-24 18:26:32.556  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 18:26:32.556  3251  3316 I jxcore-log: 
,03-24 18:26:32.641  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 18:26:32.641  3251  3316 I jxcore-log: 
,03-24 18:26:32.647  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 18:26:32.647  3251  3316 I jxcore-log: 
,03-24 18:26:32.674  3251  3316 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 18:26:32.674  3251  3316 I jxcore-log: 
,03-24 18:26:32.733  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:32.749  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:26:32.749  3251  3316 I jxcore-log: 
,03-24 18:26:32.839  1263  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:32.856  3655  3685 E SQLiteLog: (284) automatic index on view_events(_id)
,03-24 18:26:32.860  1263  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 18:26:32.860  1263  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:32.860  1263  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:32.860  1263  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:32.863  1263  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:32.873  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:32.875  2739  2739 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 18:26:32.876  2739  2739 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 18:26:32.876  2739  2739 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 18:26:33.030  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:33.160  1263  3648 W Uploader: No account for auth token provided,
,03-24 18:26:33.351  3655  3655 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-24 18:26:33.352  3655  3655 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-24 18:26:33.398  1263  3648 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 18:26:33.398  1263  3648 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:33.398  1263  3648 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:33.398  1263  3648 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:33.408  1263  3648 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:33.522  1263  3648 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 18:26:33.522  1263  3648 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 18:26:33.522  1263  3648 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 18:26:33.675  1263  3648 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 18:26:33.675  1263  3648 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:33.675  1263  3648 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:33.675  1263  3648 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:33.678  1263  3648 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 18:26:33.732   822  1487 I art     : Explicit concurrent mark sweep GC freed 18322(843KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.346ms total 50.444ms
,03-24 18:26:33.758  1263  3648 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 18:26:33.758  1263  3648 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 18:26:33.758  1263  3648 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 18:26:33.843  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:34.015  3251  3316 I jxcore-log: TAP version 13
03-24 18:26:34.015  3251  3316 I jxcore-log: 
03-24 18:26:34.015  1263  3648 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 18:26:34.015  1263  3648 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:34.015  1263  3648 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:34.015  1263  3648 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:34.018  3251  3316 I jxcore-log: # setup
03-24 18:26:34.018  3251  3316 I jxcore-log: 
,03-24 18:26:34.024  1263  3648 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:34.040  3487  3539 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 18:26:34.056  1263  3648 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 18:26:34.056  1263  3648 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 18:26:34.056  1263  3648 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 18:26:34.145  3251  3316 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 18:26:34.145  3251  3316 I jxcore-log: 
,03-24 18:26:34.340  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:34.521  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:34.733  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:34.862  1263  3648 W Uploader:  no longer exists, so no auth token.
,03-24 18:26:34.994  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:34.994  3251  3316 I jxcore-log: 
,03-24 18:26:35.000  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 58089
03-24 18:26:35.000  3251  3316 I jxcore-log: 
,03-24 18:26:35.007  3251  3316 I jxcore-log: ok 1 Should throw
03-24 18:26:35.007  3251  3316 I jxcore-log: 
,03-24 18:26:35.009  3251  3316 I jxcore-log: # teardown
03-24 18:26:35.009  3251  3316 I jxcore-log: 
,03-24 18:26:35.082  1263  3648 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 18:26:35.083  1263  3648 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:35.083  1263  3648 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 18:26:35.083  1263  3648 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:35.096  1263  3648 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:35.182  1263  3648 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 18:26:35.182  1263  3648 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 18:26:35.182  1263  3648 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 18:26:35.234  3251  3316 I jxcore-log: # setup
,03-24 18:26:35.234  3251  3316 I jxcore-log: 
,03-24 18:26:35.396  1263  3648 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 18:26:35.397  1263  3648 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:35.397  1263  3648 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:35.397  1263  3648 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:35.404  1263  3648 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:35.462  1263  3648 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 18:26:35.462  1263  3648 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:35.462  1263  3648 E Uploader: 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477),
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 18:26:35.462  1263  3648 E Uploader: ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
,03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 18:26:35.462  1263  3648 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 18:26:35.594  3251  3316 I jxcore-log: # 2. emits incomingConnectionState
,03-24 18:26:35.594  3251  3316 I jxcore-log: 
,03-24 18:26:35.658  1263  3648 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 18:26:35.658  1263  3648 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:35.658  1263  3648 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:35.658  1263  3648 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:35.669  1263  3648 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:35.737  1263  3648 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 18:26:35.737  1263  3648 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 18:26:35.737  1263  3648 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 18:26:35.757  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:35.757  3251  3316 I jxcore-log: 
,03-24 18:26:35.761  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 47876
03-24 18:26:35.761  3251  3316 I jxcore-log: 
,03-24 18:26:35.769  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:35.769  3251  3316 I jxcore-log: 
,03-24 18:26:35.772  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:35.772  3251  3316 I jxcore-log: 
,03-24 18:26:35.780  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:35.780  3251  3316 I jxcore-log: 
,03-24 18:26:35.785  3251  3316 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 18:26:35.785  3251  3316 I jxcore-log: 
,03-24 18:26:35.799  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:35.799  3251  3316 I jxcore-log: 
03-24 18:26:35.800  3251  3316 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 18:26:35.800  3251  3316 I jxcore-log: 
,03-24 18:26:35.807  3251  3316 I jxcore-log: # teardown
03-24 18:26:35.807  3251  3316 I jxcore-log: 
,03-24 18:26:35.947  1263  3648 W Uploader: No account for auth token provided
,03-24 18:26:36.003  3251  3316 I jxcore-log: # setup
03-24 18:26:36.003  3251  3316 I jxcore-log: 
,03-24 18:26:36.080  2162  2226 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 18:26:36.140  3251  3316 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 18:26:36.140  3251  3316 I jxcore-log: 
,03-24 18:26:36.293  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:36.293  3251  3316 I jxcore-log: 
,03-24 18:26:36.296  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 35592
03-24 18:26:36.296  3251  3316 I jxcore-log: 
,03-24 18:26:36.302  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 18:26:36.302  3251  3316 I jxcore-log: 
03-24 18:26:36.303  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:36.303  3251  3316 I jxcore-log: 
,03-24 18:26:36.305  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:36.305  3251  3316 I jxcore-log: 
,03-24 18:26:36.332  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:36.332  3251  3316 I jxcore-log: 
,03-24 18:26:36.334  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:36.334  3251  3316 I jxcore-log: 
,03-24 18:26:36.338  3251  3316 I jxcore-log: DEBUG createNativeListener: 
03-24 18:26:36.338  3251  3316 I jxcore-log: 
,03-24 18:26:36.339  3251  3316 I jxcore-log: ok 4 tried to connect to right port
03-24 18:26:36.339  3251  3316 I jxcore-log: 
03-24 18:26:36.340  3251  3316 I jxcore-log: ok 5 failed due to refused connection
03-24 18:26:36.340  3251  3316 I jxcore-log: 
,03-24 18:26:36.340  3251  3316 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 18:26:36.340  3251  3316 I jxcore-log: 
,03-24 18:26:36.344  3251  3316 I jxcore-log: # teardown
03-24 18:26:36.344  3251  3316 I jxcore-log: 
03-24 18:26:36.345  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:36.345  3251  3316 I jxcore-log: 
,03-24 18:26:38.482   822  1371 I ActivityManager: Killing 1518:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-24 18:26:38.514   822  1019 D WifiService: Client connection lost with reason: 4
,03-24 18:26:39.126  2739  2754 D Finsky  : [249] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 18:26:39.141  1263  1263 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:39.200  1263  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 18:26:39.201  1263  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:26:39.201  1263  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:26:39.201  1263  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:26:39.218  1263  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:26:39.264  2739  2754 D Finsky  : [249] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 18:26:40.782  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:40.782  3251  3316 I jxcore-log: 
,03-24 18:26:40.789  3251  3316 I jxcore-log: # setup
03-24 18:26:40.789  3251  3316 I jxcore-log: 
03-24 18:26:40.790  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:40.790  3251  3316 I jxcore-log: 
,03-24 18:26:41.398  3251  3316 I jxcore-log: # 4. native server connections all up
03-24 18:26:41.398  3251  3316 I jxcore-log: 
,03-24 18:26:42.582  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:42.582  3251  3316 I jxcore-log: 
,03-24 18:26:42.590  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 40588
03-24 18:26:42.590  3251  3316 I jxcore-log: 
,03-24 18:26:42.596  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:42.596  3251  3316 I jxcore-log: 
,03-24 18:26:42.597  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:42.597  3251  3316 I jxcore-log: 
03-24 18:26:42.599  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:42.599  3251  3316 I jxcore-log: 
,03-24 18:26:42.625  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:42.625  3251  3316 I jxcore-log: 
,03-24 18:26:42.629  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:42.629  3251  3316 I jxcore-log: 
,03-24 18:26:42.632  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:42.632  3251  3316 I jxcore-log: 
,03-24 18:26:42.634  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:42.634  3251  3316 I jxcore-log: ,
,03-24 18:26:42.654  3251  3316 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 18:26:42.654  3251  3316 I jxcore-log: 
,03-24 18:26:42.654  3251  3316 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 18:26:42.654  3251  3316 I jxcore-log: 
,03-24 18:26:42.663  3251  3316 I jxcore-log: ok 9 Send/recvd #2 should be equal length,
03-24 18:26:42.663  3251  3316 I jxcore-log: 
03-24 18:26:42.664  3251  3316 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 18:26:42.664  3251  3316 I jxcore-log: 
03-24 18:26:42.667  3251  3316 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 18:26:42.667  3251  3316 I jxcore-log: 
,03-24 18:26:42.672  3251  3316 I jxcore-log: # teardown
03-24 18:26:42.672  3251  3316 I jxcore-log: 
,03-24 18:26:44.413  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:44.413  3251  3316 I jxcore-log: 
,03-24 18:26:44.420  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:44.420  3251  3316 I jxcore-log: 
,03-24 18:26:44.422  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:44.422  3251  3316 I jxcore-log: 
,03-24 18:26:44.426  3251  3316 I jxcore-log: # setup
03-24 18:26:44.426  3251  3316 I jxcore-log: 
,03-24 18:26:44.427  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:44.427  3251  3316 I jxcore-log: 
,03-24 18:26:44.988  3251  3316 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 18:26:44.988  3251  3316 I jxcore-log: 
,03-24 18:26:45.442  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:45.442  3251  3316 I jxcore-log: 
,03-24 18:26:45.449  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 38374
03-24 18:26:45.449  3251  3316 I jxcore-log: 
,03-24 18:26:45.454  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:45.454  3251  3316 I jxcore-log: 
,03-24 18:26:45.456  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:45.456  3251  3316 I jxcore-log: 
,03-24 18:26:45.457  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:45.457  3251  3316 I jxcore-log: 
,03-24 18:26:45.470  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:45.470  3251  3316 I jxcore-log: 
,03-24 18:26:45.472  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:45.472  3251  3316 I jxcore-log: 
,03-24 18:26:45.486  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:45.486  3251  3316 I jxcore-log: 
,03-24 18:26:45.500  3251  3316 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 18:26:45.500  3251  3316 I jxcore-log: 
,03-24 18:26:45.500  3251  3316 I jxcore-log: ok 13 incoming remains open
03-24 18:26:45.500  3251  3316 I jxcore-log: 
,03-24 18:26:45.507  3251  3316 I jxcore-log: # teardown
03-24 18:26:45.507  3251  3316 I jxcore-log: 
,03-24 18:26:47.625  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:47.625  3251  3316 I jxcore-log: 
,03-24 18:26:47.633  3251  3316 I jxcore-log: # setup
03-24 18:26:47.633  3251  3316 I jxcore-log: 
,03-24 18:26:47.635  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:47.635  3251  3316 I jxcore-log: 
,03-24 18:26:47.775  3251  3316 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 18:26:47.775  3251  3316 I jxcore-log: 
,03-24 18:26:50.564  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:50.564  3251  3316 I jxcore-log: 
,03-24 18:26:50.570  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 33339
03-24 18:26:50.570  3251  3316 I jxcore-log: 
,03-24 18:26:50.576  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:50.576  3251  3316 I jxcore-log: 
,03-24 18:26:50.578  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:50.578  3251  3316 I jxcore-log: 
,03-24 18:26:50.579  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:50.579  3251  3316 I jxcore-log: 
,03-24 18:26:50.590  3251  3316 I jxcore-log: ok 14 we should not have gotten an error
03-24 18:26:50.590  3251  3316 I jxcore-log: 
,03-24 18:26:50.595  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:50.595  3251  3316 I jxcore-log: 
,03-24 18:26:50.601  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:50.601  3251  3316 I jxcore-log: 
,03-24 18:26:50.611  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:50.611  3251  3316 I jxcore-log: 
,03-24 18:26:50.614  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:50.614  3251  3316 I jxcore-log: 
,03-24 18:26:50.622  3251  3316 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 18:26:50.622  3251  3316 I jxcore-log: 
,03-24 18:26:50.623  3251  3316 I jxcore-log: ok 16 incoming is cleaned up
03-24 18:26:50.623  3251  3316 I jxcore-log: 
,03-24 18:26:50.629  3251  3316 I jxcore-log: # teardown
03-24 18:26:50.629  3251  3316 I jxcore-log: 
,03-24 18:26:51.552  3251  3316 I jxcore-log: # setup
03-24 18:26:51.552  3251  3316 I jxcore-log: 
,03-24 18:26:52.689  3251  3316 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 18:26:52.689  3251  3316 I jxcore-log: 
,03-24 18:26:54.177  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:54.177  3251  3316 I jxcore-log: 
,03-24 18:26:54.187  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 54842
03-24 18:26:54.187  3251  3316 I jxcore-log: 
,03-24 18:26:54.193  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:54.193  3251  3316 I jxcore-log: 
,03-24 18:26:54.194  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:54.194  3251  3316 I jxcore-log: 
03-24 18:26:54.197  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:54.197  3251  3316 I jxcore-log: 
,03-24 18:26:54.209  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:54.209  3251  3316 I jxcore-log: 
,03-24 18:26:54.211  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:54.211  3251  3316 I jxcore-log: 
,03-24 18:26:54.225  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:54.225  3251  3316 I jxcore-log: 
,03-24 18:26:54.234  3251  3316 I jxcore-log: ok 17 stream was closed
03-24 18:26:54.234  3251  3316 I jxcore-log: 
,03-24 18:26:54.234  3251  3316 I jxcore-log: ok 18 incoming should survive
03-24 18:26:54.234  3251  3316 I jxcore-log: 
03-24 18:26:54.235  3251  3316 I jxcore-log: ok 19 mux should have no streams
03-24 18:26:54.235  3251  3316 I jxcore-log: 
,03-24 18:26:54.242  3251  3316 I jxcore-log: # teardown
03-24 18:26:54.242  3251  3316 I jxcore-log: 
,03-24 18:26:54.361  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:54.361  3251  3316 I jxcore-log: 
,03-24 18:26:54.371  3251  3316 I jxcore-log: # setup
03-24 18:26:54.371  3251  3316 I jxcore-log: 
,03-24 18:26:54.372  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:54.372  3251  3316 I jxcore-log: 
,03-24 18:26:54.512  3251  3316 I jxcore-log: # 8. native server - closing the whole server cleans everything up
,03-24 18:26:54.512  3251  3316 I jxcore-log: 
,03-24 18:26:54.618  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:54.618  3251  3316 I jxcore-log: 
,03-24 18:26:54.628  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 39978
03-24 18:26:54.628  3251  3316 I jxcore-log: 
,03-24 18:26:54.638  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:54.638  3251  3316 I jxcore-log: 
,03-24 18:26:54.641  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:54.641  3251  3316 I jxcore-log: 
03-24 18:26:54.644  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:54.644  3251  3316 I jxcore-log: 
,03-24 18:26:54.669  3251  3316 I jxcore-log: ok 20 we should not have gotten an error
03-24 18:26:54.669  3251  3316 I jxcore-log: 
,03-24 18:26:54.675  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:54.675  3251  3316 I jxcore-log: 
,03-24 18:26:54.679  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:54.679  3251  3316 I jxcore-log: 
,03-24 18:26:54.689  3251  3316 I jxcore-log: ok 21 Buffers are identical
03-24 18:26:54.689  3251  3316 I jxcore-log: 
,03-24 18:26:54.691  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:54.691  3251  3316 I jxcore-log: 
03-24 18:26:54.695  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:54.695  3251  3316 I jxcore-log: 
,03-24 18:26:54.698  3251  3316 I jxcore-log: ok 22 native server is nulled out
03-24 18:26:54.698  3251  3316 I jxcore-log: 
03-24 18:26:54.699  3251  3316 I jxcore-log: ok 23 native server should be closed
03-24 18:26:54.699  3251  3316 I jxcore-log: 
,03-24 18:26:54.699  3251  3316 I jxcore-log: ok 24 incoming has been removed
03-24 18:26:54.699  3251  3316 I jxcore-log: 
03-24 18:26:54.700  3251  3316 I jxcore-log: ok 25 Incoming should be done
03-24 18:26:54.700  3251  3316 I jxcore-log: 
,03-24 18:26:54.700  3251  3316 I jxcore-log: ok 26 The mux object should be closed
03-24 18:26:54.700  3251  3316 I jxcore-log: 
03-24 18:26:54.700  3251  3316 I jxcore-log: ok 27 The mux stream should be closed
03-24 18:26:54.700  3251  3316 I jxcore-log: 
03-24 18:26:54.701  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:54.701  3251  3316 I jxcore-log: 
,03-24 18:26:54.717  3251  3316 I jxcore-log: # teardown
03-24 18:26:54.717  3251  3316 I jxcore-log: 
,03-24 18:26:54.828  3251  3316 I jxcore-log: # setup
03-24 18:26:54.828  3251  3316 I jxcore-log: 
,03-24 18:26:54.951  3251  3316 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 18:26:54.951  3251  3316 I jxcore-log: 
,03-24 18:26:55.088  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:55.088  3251  3316 I jxcore-log: 
,03-24 18:26:55.091  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 36630
03-24 18:26:55.091  3251  3316 I jxcore-log: 
,03-24 18:26:55.112  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.112  3251  3316 I jxcore-log: 
,03-24 18:26:55.113  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.113  3251  3316 I jxcore-log: 
03-24 18:26:55.114  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux,
03-24 18:26:55.114  3251  3316 I jxcore-log: 
03-24 18:26:55.118  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.118  3251  3316 I jxcore-log: ,
03-24 18:26:55.118  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.118  3251  3316 I jxcore-log: 
03-24 18:26:55.120  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.120  3251  3316 I jxcore-log: 
,03-24 18:26:55.123  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 18:26:55.123  3251  3316 I jxcore-log: 
03-24 18:26:55.124  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.124  3251  3316 I jxcore-log: 
,03-24 18:26:55.129  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.129  3251  3316 I jxcore-log: 
,03-24 18:26:55.133  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 18:26:55.133  3251  3316 I jxcore-log: 
,03-24 18:26:55.134  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.134  3251  3316 I jxcore-log: 
03-24 18:26:55.135  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.135  3251  3316 I jxcore-log: 
,03-24 18:26:55.138  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.138  3251  3316 I jxcore-log: 
,03-24 18:26:55.138  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.138  3251  3316 I jxcore-log: 
03-24 18:26:55.139  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.139  3251  3316 I jxcore-log: 
03-24 18:26:55.141  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.141  3251  3316 I jxcore-log: 
,03-24 18:26:55.142  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.142  3251  3316 I jxcore-log: 
03-24 18:26:55.143  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.143  3251  3316 I jxcore-log: 
03-24 18:26:55.144  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.144  3251  3316 I jxcore-log: 
03-24 18:26:55.145  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.145  3251  3316 I jxcore-log: 
03-24 18:26:55.146  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.146  3251  3316 I jxcore-log: 
,03-24 18:26:55.148  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.148  3251  3316 I jxcore-log: 
,03-24 18:26:55.149  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.149  3251  3316 I jxcore-log: 
03-24 18:26:55.150  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.150  3251  3316 I jxcore-log: 
,03-24 18:26:55.152  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.152  3251  3316 I jxcore-log: 
,03-24 18:26:55.152  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.152  3251  3316 I jxcore-log: 
,03-24 18:26:55.153  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.153  3251  3316 I jxcore-log: 
,03-24 18:26:55.155  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.155  3251  3316 I jxcore-log: 
03-24 18:26:55.155  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.155  3251  3316 I jxcore-log: 
,03-24 18:26:55.156  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.156  3251  3316 I jxcore-log: 
,03-24 18:26:55.245  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.245  3251  3316 I jxcore-log: 
,03-24 18:26:55.247  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.247  3251  3316 I jxcore-log: 
,03-24 18:26:55.250  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.250  3251  3316 I jxcore-log: 
,03-24 18:26:55.251  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.251  3251  3316 I jxcore-log: 
,03-24 18:26:55.253  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.253  3251  3316 I jxcore-log: 
,03-24 18:26:55.254  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.254  3251  3316 I jxcore-log: 
,03-24 18:26:55.256  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.256  3251  3316 I jxcore-log: 
,03-24 18:26:55.258  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.258  3251  3316 I jxcore-log: 
,03-24 18:26:55.260  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.260  3251  3316 I jxcore-log: 
,03-24 18:26:55.262  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.262  3251  3316 I jxcore-log: 
,03-24 18:26:55.263  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.263  3251  3316 I jxcore-log: 
,03-24 18:26:55.265  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.265  3251  3316 I jxcore-log: 
,03-24 18:26:55.266  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.266  3251  3316 I jxcore-log: 
,03-24 18:26:55.268  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.268  3251  3316 I jxcore-log: 
,03-24 18:26:55.269  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.269  3251  3316 I jxcore-log: 
,03-24 18:26:55.270  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.270  3251  3316 I jxcore-log: 
,03-24 18:26:55.272  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.272  3251  3316 I jxcore-log: 
,03-24 18:26:55.274  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.274  3251  3316 I jxcore-log: 
,03-24 18:26:55.275  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.275  3251  3316 I jxcore-log: 
,03-24 18:26:55.280  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.280  3251  3316 I jxcore-log: 
,03-24 18:26:55.281  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.281  3251  3316 I jxcore-log: 
03-24 18:26:55.283  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.283  3251  3316 I jxcore-log: 
,03-24 18:26:55.284  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.284  3251  3316 I jxcore-log: 
,03-24 18:26:55.286  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.286  3251  3316 I jxcore-log: 
,03-24 18:26:55.288  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.288  3251  3316 I jxcore-log: 
,03-24 18:26:55.290  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.290  3251  3316 I jxcore-log: 
,03-24 18:26:55.291  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.291  3251  3316 I jxcore-log: 
,03-24 18:26:55.293  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.293  3251  3316 I jxcore-log: 
,03-24 18:26:55.294  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.294  3251  3316 I jxcore-log: 
,03-24 18:26:55.295  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.295  3251  3316 I jxcore-log: 
03-24 18:26:55.296  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.296  3251  3316 I jxcore-log: 
,03-24 18:26:55.298  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.298  3251  3316 I jxcore-log: 
,03-24 18:26:55.300  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.300  3251  3316 I jxcore-log: 
,03-24 18:26:55.302  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.302  3251  3316 I jxcore-log: 
,03-24 18:26:55.303  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.303  3251  3316 I jxcore-log: 
,03-24 18:26:55.304  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.304  3251  3316 I jxcore-log: 
,03-24 18:26:55.305  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.305  3251  3316 I jxcore-log: 
03-24 18:26:55.306  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.306  3251  3316 I jxcore-log: 
,03-24 18:26:55.307  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.307  3251  3316 I jxcore-log: 
,03-24 18:26:55.309  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.309  3251  3316 I jxcore-log: 
,03-24 18:26:55.311  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.311  3251  3316 I jxcore-log: 
,03-24 18:26:55.312  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.312  3251  3316 I jxcore-log: 
,03-24 18:26:55.313  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.313  3251  3316 I jxcore-log: 
,03-24 18:26:55.315  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.315  3251  3316 I jxcore-log: 
,03-24 18:26:55.316  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.316  3251  3316 I jxcore-log: 
03-24 18:26:55.317  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.317  3251  3316 I jxcore-log: 
,03-24 18:26:55.318  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.318  3251  3316 I jxcore-log: 
,03-24 18:26:55.320  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.320  3251  3316 I jxcore-log: 
,03-24 18:26:55.328  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.328  3251  3316 I jxcore-log: 
,03-24 18:26:55.329  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.329  3251  3316 I jxcore-log: 
,03-24 18:26:55.330  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.330  3251  3316 I jxcore-log: 
,03-24 18:26:55.332  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.332  3251  3316 I jxcore-log: 
,03-24 18:26:55.333  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.333  3251  3316 I jxcore-log: 
03-24 18:26:55.334  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.334  3251  3316 I jxcore-log: 
,03-24 18:26:55.335  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.335  3251  3316 I jxcore-log: 
,03-24 18:26:55.336  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.336  3251  3316 I jxcore-log: 
,03-24 18:26:55.339  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.339  3251  3316 I jxcore-log: 
,03-24 18:26:55.341  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.341  3251  3316 I jxcore-log: 
,03-24 18:26:55.342  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.342  3251  3316 I jxcore-log: 
,03-24 18:26:55.343  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.343  3251  3316 I jxcore-log: 
,03-24 18:26:55.344  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.344  3251  3316 I jxcore-log: 
03-24 18:26:55.346  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.346  3251  3316 I jxcore-log: 
,03-24 18:26:55.347  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.347  3251  3316 I jxcore-log: 
,03-24 18:26:55.348  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.348  3251  3316 I jxcore-log: 
,03-24 18:26:55.350  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.350  3251  3316 I jxcore-log: 
,03-24 18:26:55.351  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.351  3251  3316 I jxcore-log: 
,03-24 18:26:55.353  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.353  3251  3316 I jxcore-log: 
,03-24 18:26:55.354  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.354  3251  3316 I jxcore-log: 
,03-24 18:26:55.355  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.355  3251  3316 I jxcore-log: 
03-24 18:26:55.357  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.357  3251  3316 I jxcore-log: 
,03-24 18:26:55.358  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.358  3251  3316 I jxcore-log: 
,03-24 18:26:55.359  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.359  3251  3316 I jxcore-log: 
,03-24 18:26:55.361  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.361  3251  3316 I jxcore-log: 
,03-24 18:26:55.362  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.362  3251  3316 I jxcore-log: 
,03-24 18:26:55.363  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.363  3251  3316 I jxcore-log: 
,03-24 18:26:55.365  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.365  3251  3316 I jxcore-log: 
03-24 18:26:55.366  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.366  3251  3316 I jxcore-log: 
,03-24 18:26:55.367  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.367  3251  3316 I jxcore-log: 
,03-24 18:26:55.368  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.368  3251  3316 I jxcore-log: 
,03-24 18:26:55.370  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:55.370  3251  3316 I jxcore-log: 
,03-24 18:26:55.447  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.447  3251  3316 I jxcore-log: 
,03-24 18:26:55.449  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.449  3251  3316 I jxcore-log: 
,03-24 18:26:55.450  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.450  3251  3316 I jxcore-log: 
,03-24 18:26:55.451  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.451  3251  3316 I jxcore-log: 
03-24 18:26:55.452  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.452  3251  3316 I jxcore-log: 
,03-24 18:26:55.453  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.453  3251  3316 I jxcore-log: 
,03-24 18:26:55.454  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.454  3251  3316 I jxcore-log: 
,03-24 18:26:55.455  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.455  3251  3316 I jxcore-log: 
03-24 18:26:55.456  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.456  3251  3316 I jxcore-log: 
,03-24 18:26:55.457  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.457  3251  3316 I jxcore-log: 
,03-24 18:26:55.460  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.460  3251  3316 I jxcore-log: 
,03-24 18:26:55.461  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.461  3251  3316 I jxcore-log: 
03-24 18:26:55.462  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.462  3251  3316 I jxcore-log: 
,03-24 18:26:55.463  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.463  3251  3316 I jxcore-log: 
,03-24 18:26:55.464  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.464  3251  3316 I jxcore-log: 
,03-24 18:26:55.465  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.465  3251  3316 I jxcore-log: 
03-24 18:26:55.467  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.467  3251  3316 I jxcore-log: 
,03-24 18:26:55.467  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.467  3251  3316 I jxcore-log: 
03-24 18:26:55.468  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.468  3251  3316 I jxcore-log: 
,03-24 18:26:55.469  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.469  3251  3316 I jxcore-log: 
,03-24 18:26:55.470  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.470  3251  3316 I jxcore-log: 
,03-24 18:26:55.471  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.471  3251  3316 I jxcore-log: 
,03-24 18:26:55.472  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.472  3251  3316 I jxcore-log: 
,03-24 18:26:55.473  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.473  3251  3316 I jxcore-log: 
03-24 18:26:55.474  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.474  3251  3316 I jxcore-log: 
,03-24 18:26:55.475  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.475  3251  3316 I jxcore-log: 
,03-24 18:26:55.476  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.476  3251  3316 I jxcore-log: 
,03-24 18:26:55.477  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.477  3251  3316 I jxcore-log: 
,03-24 18:26:55.478  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.478  3251  3316 I jxcore-log: 
,03-24 18:26:55.479  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.479  3251  3316 I jxcore-log: 
,03-24 18:26:55.480  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.480  3251  3316 I jxcore-log: 
,03-24 18:26:55.481  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.481  3251  3316 I jxcore-log: 
,03-24 18:26:55.481  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.481  3251  3316 I jxcore-log: 
,03-24 18:26:55.482  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.482  3251  3316 I jxcore-log: 
03-24 18:26:55.483  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.483  3251  3316 I jxcore-log: 
,03-24 18:26:55.484  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.484  3251  3316 I jxcore-log: 
03-24 18:26:55.485  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.485  3251  3316 I jxcore-log: 
03-24 18:26:55.485  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.485  3251  3316 I jxcore-log: 
03-24 18:26:55.486  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.486  3251  3316 I jxcore-log: 
03-24 18:26:55.487  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.487  3251  3316 I jxcore-log: 
,03-24 18:26:55.488  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.488  3251  3316 I jxcore-log: 
03-24 18:26:55.489  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.489  3251  3316 I jxcore-log: 
,03-24 18:26:55.490  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.490  3251  3316 I jxcore-log: 
03-24 18:26:55.490  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.490  3251  3316 I jxcore-log: 
03-24 18:26:55.491  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.491  3251  3316 I jxcore-log: 
03-24 18:26:55.492  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.492  3251  3316 I jxcore-log: 
03-24 18:26:55.493  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.493  3251  3316 I jxcore-log: 
03-24 18:26:55.493  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.493  3251  3316 I jxcore-log: 
03-24 18:26:55.494  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:55.494  3251  3316 I jxcore-log: 
03-24 18:26:55.495  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:55.495  3251  3316 I jxcore-log: 
03-24 18:26:55.498  3251  3316 I jxcore-log: ok 28 native server is nulled out
03-24 18:26:55.498  3251  3316 I jxcore-log: 
,03-24 18:26:55.499  3251  3316 I jxcore-log: ok 29 native server should be closed
03-24 18:26:55.499  3251  3316 I jxcore-log: 
03-24 18:26:55.499  3251  3316 I jxcore-log: ok 30 incoming has been removed
03-24 18:26:55.499  3251  3316 I jxcore-log: 
03-24 18:26:55.500  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.500  3251  3316 I jxcore-log: 
,03-24 18:26:55.501  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.501  3251  3316 I jxcore-log: 
03-24 18:26:55.501  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.501  3251  3316 I jxcore-log: 
03-24 18:26:55.502  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.502  3251  3316 I jxcore-log: 
03-24 18:26:55.502  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.502  3251  3316 I jxcore-log: 
,03-24 18:26:55.502  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.502  3251  3316 I jxcore-log: 
03-24 18:26:55.503  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.503  3251  3316 I jxcore-log: 
03-24 18:26:55.503  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.503  3251  3316 I jxcore-log: 
,03-24 18:26:55.503  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.503  3251  3316 I jxcore-log: 
03-24 18:26:55.504  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:55.504  3251  3316 I jxcore-log: 
,03-24 18:26:55.610  3251  3316 I jxcore-log: # teardown
03-24 18:26:55.610  3251  3316 I jxcore-log: 
,03-24 18:26:55.658  3251  3316 I jxcore-log: # setup
03-24 18:26:55.658  3251  3316 I jxcore-log: 
,03-24 18:26:55.819  3251  3316 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 18:26:55.819  3251  3316 I jxcore-log: 
,03-24 18:26:55.974  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:55.974  3251  3316 I jxcore-log: 
,03-24 18:26:55.980  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 53243
03-24 18:26:55.980  3251  3316 I jxcore-log: 
,03-24 18:26:55.985  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:55.985  3251  3316 I jxcore-log: 
,03-24 18:26:55.986  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:55.986  3251  3316 I jxcore-log: 
03-24 18:26:55.988  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:55.988  3251  3316 I jxcore-log: 
,03-24 18:26:55.995  3251  3316 I jxcore-log: ok 31 we should not have gotten an error
03-24 18:26:55.995  3251  3316 I jxcore-log: 
,03-24 18:26:55.999  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:55.999  3251  3316 I jxcore-log: 
,03-24 18:26:56.001  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:56.001  3251  3316 I jxcore-log: 
,03-24 18:26:56.009  3251  3316 I jxcore-log: ok 32 Buffers are identical
03-24 18:26:56.009  3251  3316 I jxcore-log: 
,03-24 18:26:56.010  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:56.010  3251  3316 I jxcore-log: 
,03-24 18:26:56.011  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:56.011  3251  3316 I jxcore-log: 
,03-24 18:26:56.023  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:56.023  3251  3316 I jxcore-log: 
,03-24 18:26:56.024  3251  3316 I jxcore-log: ok 33 server should be fine
03-24 18:26:56.024  3251  3316 I jxcore-log: 
,03-24 18:26:56.024  3251  3316 I jxcore-log: ok 34 server should be open
03-24 18:26:56.024  3251  3316 I jxcore-log: 
03-24 18:26:56.025  3251  3316 I jxcore-log: ok 35 incoming has been removed
03-24 18:26:56.025  3251  3316 I jxcore-log: 
,03-24 18:26:56.025  3251  3316 I jxcore-log: ok 36 The mux object should be closed
03-24 18:26:56.025  3251  3316 I jxcore-log: 
,03-24 18:26:56.025  3251  3316 I jxcore-log: ok 37 The mux stream should be closed
03-24 18:26:56.025  3251  3316 I jxcore-log: 
,03-24 18:26:56.033  3251  3316 I jxcore-log: # teardown
03-24 18:26:56.033  3251  3316 I jxcore-log: 
,03-24 18:26:56.199  3251  3316 I jxcore-log: # setup
03-24 18:26:56.199  3251  3316 I jxcore-log: 
,03-24 18:26:56.395  3251  3316 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-24 18:26:56.395  3251  3316 I jxcore-log: 
,03-24 18:26:56.593  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:26:56.593  3251  3316 I jxcore-log: 
,03-24 18:26:56.600  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 50933
03-24 18:26:56.600  3251  3316 I jxcore-log: 
,03-24 18:26:56.605  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:26:56.605  3251  3316 I jxcore-log: 
,03-24 18:26:56.606  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:26:56.606  3251  3316 I jxcore-log: 
,03-24 18:26:56.608  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:26:56.608  3251  3316 I jxcore-log: 
,03-24 18:26:56.614  3251  3316 I jxcore-log: ok 38 we should not have gotten an error
03-24 18:26:56.614  3251  3316 I jxcore-log: ,
,03-24 18:26:56.618  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:26:56.618  3251  3316 I jxcore-log: 
,03-24 18:26:56.620  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:26:56.620  3251  3316 I jxcore-log: 
,03-24 18:26:56.627  3251  3316 I jxcore-log: ok 39 Buffers are identical
03-24 18:26:56.627  3251  3316 I jxcore-log: 
,03-24 18:26:56.631  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 18:26:56.631  3251  3316 I jxcore-log: 
,03-24 18:26:56.633  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:26:56.633  3251  3316 I jxcore-log: 
,03-24 18:26:56.634  3251  3316 I jxcore-log: DEBUG createNativeListener: mux close
03-24 18:26:56.634  3251  3316 I jxcore-log: 
,03-24 18:26:56.639  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:26:56.639  3251  3316 I jxcore-log: 
,03-24 18:26:56.640  3251  3316 I jxcore-log: ok 40 server should be fine
03-24 18:26:56.640  3251  3316 I jxcore-log: 
,03-24 18:26:56.640  3251  3316 I jxcore-log: ok 41 server should be open
03-24 18:26:56.640  3251  3316 I jxcore-log: 
,03-24 18:26:56.641  3251  3316 I jxcore-log: ok 42 incoming has been removed
03-24 18:26:56.641  3251  3316 I jxcore-log: 
03-24 18:26:56.641  3251  3316 I jxcore-log: ok 43 The mux object should be closed
03-24 18:26:56.641  3251  3316 I jxcore-log: 
03-24 18:26:56.641  3251  3316 I jxcore-log: ok 44 The mux stream should be closed
03-24 18:26:56.641  3251  3316 I jxcore-log: 
,03-24 18:26:56.650  3251  3316 I jxcore-log: # teardown
03-24 18:26:56.650  3251  3316 I jxcore-log: 
,03-24 18:26:56.778  3251  3316 I jxcore-log: # setup
03-24 18:26:56.778  3251  3316 I jxcore-log: 
,03-24 18:26:56.891  3251  3316 I jxcore-log: # 12. closeAll can close even when connections open
03-24 18:26:56.891  3251  3316 I jxcore-log: 
,03-24 18:26:57.004  3251  3316 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 18:26:57.004  3251  3316 I jxcore-log: 
,03-24 18:26:57.009  3251  3316 I jxcore-log: # teardown
03-24 18:26:57.009  3251  3316 I jxcore-log: 
,03-24 18:26:57.098  3251  3316 I jxcore-log: # setup
03-24 18:26:57.098  3251  3316 I jxcore-log: 
,03-24 18:26:57.203  3251  3316 I jxcore-log: # 13. closeAll with promise
03-24 18:26:57.203  3251  3316 I jxcore-log: 
,03-24 18:26:57.364  3251  3316 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 18:26:57.364  3251  3316 I jxcore-log: 
,03-24 18:26:57.369  3251  3316 I jxcore-log: # teardown
03-24 18:26:57.369  3251  3316 I jxcore-log: 
,03-24 18:26:57.445  3251  3316 I jxcore-log: # setup
03-24 18:26:57.445  3251  3316 I jxcore-log: 
,03-24 18:26:57.594  3251  3316 I jxcore-log: # 14. multiplex can send data
03-24 18:26:57.594  3251  3316 I jxcore-log: 
,03-24 18:26:57.720  3251  3316 I jxcore-log: ok 47 String should be length:200
03-24 18:26:57.720  3251  3316 I jxcore-log: 
,03-24 18:26:57.729  3251  3316 I jxcore-log: # teardown
03-24 18:26:57.729  3251  3316 I jxcore-log: 
,03-24 18:26:57.852  3251  3316 I jxcore-log: # setup
03-24 18:26:57.852  3251  3316 I jxcore-log: 
,03-24 18:26:58.030  3251  3316 I jxcore-log: # 15. enqueue and run in order
03-24 18:26:58.030  3251  3316 I jxcore-log: 
,03-24 18:26:58.211  3251  3316 I jxcore-log: ok 48 firstPromise setTimeout
03-24 18:26:58.211  3251  3316 I jxcore-log: 
,03-24 18:26:58.213  3251  3316 I jxcore-log: ok 49 firstPromise result
03-24 18:26:58.213  3251  3316 I jxcore-log: 
,03-24 18:26:58.215  3251  3316 I jxcore-log: ok 50 firstPromise testValue
03-24 18:26:58.215  3251  3316 I jxcore-log: 
,03-24 18:26:58.318  3251  3316 I jxcore-log: ok 51 secondPromise setTimeout
03-24 18:26:58.318  3251  3316 I jxcore-log: 
,03-24 18:26:58.322  3251  3316 I jxcore-log: ok 52 secondPromise result
03-24 18:26:58.322  3251  3316 I jxcore-log: 
,03-24 18:26:58.324  3251  3316 I jxcore-log: ok 53 secondPromise testValue
03-24 18:26:58.324  3251  3316 I jxcore-log: 
,03-24 18:26:58.326  3251  3316 I jxcore-log: ok 54 thirdPromise in promise
03-24 18:26:58.326  3251  3316 I jxcore-log: 
,03-24 18:26:58.329  3251  3316 I jxcore-log: ok 55 thirdPromise result
03-24 18:26:58.329  3251  3316 I jxcore-log: 
,03-24 18:26:58.331  3251  3316 I jxcore-log: ok 56 thirdPromise testValue
03-24 18:26:58.331  3251  3316 I jxcore-log: 
,03-24 18:26:58.340  3251  3316 I jxcore-log: # teardown
03-24 18:26:58.340  3251  3316 I jxcore-log: 
,03-24 18:26:58.460  3251  3316 I jxcore-log: # setup
03-24 18:26:58.460  3251  3316 I jxcore-log: 
,03-24 18:26:58.552  3251  3316 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 18:26:58.552  3251  3316 I jxcore-log: 
,03-24 18:26:58.688  3251  3316 I jxcore-log: ok 57 thirdPromise - first to run
03-24 18:26:58.688  3251  3316 I jxcore-log: 
,03-24 18:26:58.691  3251  3316 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 18:26:58.691  3251  3316 I jxcore-log: 
,03-24 18:26:58.696  3251  3316 I jxcore-log: ok 59 secondPromise - second to run
03-24 18:26:58.696  3251  3316 I jxcore-log: 
,03-24 18:26:58.698  3251  3316 I jxcore-log: ok 60 secondPromise - in catch
03-24 18:26:58.698  3251  3316 I jxcore-log: 
,03-24 18:26:58.699  3251  3316 I jxcore-log: ok 61 firstPromise - third to run
03-24 18:26:58.699  3251  3316 I jxcore-log: 
,03-24 18:26:58.699  3251  3316 I jxcore-log: ok 62 firstPromise - in then
03-24 18:26:58.699  3251  3316 I jxcore-log: 
03-24 18:26:58.700  3251  3316 I jxcore-log: ok 63 testing promises
03-24 18:26:58.700  3251  3316 I jxcore-log: 
03-24 18:26:58.702  3251  3316 I jxcore-log: # teardown
03-24 18:26:58.702  3251  3316 I jxcore-log: 
,03-24 18:26:59.048  2162  2226 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 18:26:59.362  3251  3316 I jxcore-log: # setup
03-24 18:26:59.362  3251  3316 I jxcore-log: 
,03-24 18:26:59.509  3251  3316 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 18:26:59.509  3251  3316 I jxcore-log: 
,03-24 18:26:59.759  3251  3316 I jxcore-log: ok 64 fourth
03-24 18:26:59.759  3251  3316 I jxcore-log: 
,03-24 18:26:59.762  3251  3316 I jxcore-log: ok 65 fourth
03-24 18:26:59.762  3251  3316 I jxcore-log: 
03-24 18:26:59.765  3251  3316 I jxcore-log: ok 66 second
03-24 18:26:59.765  3251  3316 I jxcore-log: 
,03-24 18:26:59.768  3251  3316 I jxcore-log: ok 67 secondPromise - in then
03-24 18:26:59.768  3251  3316 I jxcore-log: 
,03-24 18:26:59.871  3251  3316 I jxcore-log: ok 68 first
03-24 18:26:59.871  3251  3316 I jxcore-log: 
,03-24 18:26:59.874  3251  3316 I jxcore-log: ok 69 firstPromise - in catch
03-24 18:26:59.874  3251  3316 I jxcore-log: 
03-24 18:26:59.876  3251  3316 I jxcore-log: ok 70 third
03-24 18:26:59.876  3251  3316 I jxcore-log: 
,03-24 18:26:59.879  3251  3316 I jxcore-log: ok 71 thirdPromise - in then
03-24 18:26:59.879  3251  3316 I jxcore-log: 
,03-24 18:26:59.881  3251  3316 I jxcore-log: ok 72 testingPromises
03-24 18:26:59.881  3251  3316 I jxcore-log: 
,03-24 18:26:59.890  3251  3316 I jxcore-log: # teardown
03-24 18:26:59.890  3251  3316 I jxcore-log: 
,03-24 18:27:00.010  3251  3316 I jxcore-log: # setup
03-24 18:27:00.010  3251  3316 I jxcore-log: ,
,03-24 18:27:00.108  3251  3316 I jxcore-log: # 18. queues handled independently
03-24 18:27:00.108  3251  3316 I jxcore-log: 
,03-24 18:27:00.249  3251  3316 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 18:27:00.249  3251  3316 I jxcore-log: 
,03-24 18:27:00.260  3251  3316 I jxcore-log: # teardown
03-24 18:27:00.260  3251  3316 I jxcore-log: 
,03-24 18:27:00.353  3251  3316 I jxcore-log: # setup
03-24 18:27:00.353  3251  3316 I jxcore-log: 
,03-24 18:27:00.458  3251  3316 I jxcore-log: # 19. basic
03-24 18:27:00.458  3251  3316 I jxcore-log: 
,03-24 18:27:00.563  3251  3316 I jxcore-log: ok 74 sane,
03-24 18:27:00.563  3251  3316 I jxcore-log: 
,03-24 18:27:00.570  3251  3316 I jxcore-log: # teardown,
03-24 18:27:00.570  3251  3316 I jxcore-log: 
,03-24 18:27:00.773  3251  3316 I jxcore-log: # setup,
03-24 18:27:00.773  3251  3316 I jxcore-log: 
,03-24 18:27:00.901  3251  3316 I jxcore-log: # 20. another
03-24 18:27:00.901  3251  3316 I jxcore-log: 
,03-24 18:27:01.024  3251  3316 I jxcore-log: ok 75 sane
03-24 18:27:01.024  3251  3316 I jxcore-log: 
,03-24 18:27:01.029  3251  3316 I jxcore-log: # teardown
03-24 18:27:01.029  3251  3316 I jxcore-log: 
,03-24 18:27:01.224  3251  3316 I jxcore-log: # setup
03-24 18:27:01.224  3251  3316 I jxcore-log: 
,03-24 18:27:01.322  3251  3316 I jxcore-log: # 21. can pass data in setup
03-24 18:27:01.322  3251  3316 I jxcore-log: 
,03-24 18:27:01.448  3251  3316 I jxcore-log: ok 76 test participant has uuid
03-24 18:27:01.448  3251  3316 I jxcore-log: 
,03-24 18:27:01.450  3251  3316 I jxcore-log: ok 77 participant data matches
03-24 18:27:01.450  3251  3316 I jxcore-log: 
,03-24 18:27:01.454  3251  3316 I jxcore-log: ok 78 test participant has uuid
03-24 18:27:01.454  3251  3316 I jxcore-log: 
,03-24 18:27:01.456  3251  3316 I jxcore-log: ok 79 participant data matches
03-24 18:27:01.456  3251  3316 I jxcore-log: 
,03-24 18:27:01.459  3251  3316 I jxcore-log: ok 80 test participant has uuid
03-24 18:27:01.459  3251  3316 I jxcore-log: 
,03-24 18:27:01.461  3251  3316 I jxcore-log: ok 81 participant data matches
03-24 18:27:01.461  3251  3316 I jxcore-log: 
,03-24 18:27:01.468  3251  3316 I jxcore-log: # teardown
03-24 18:27:01.468  3251  3316 I jxcore-log: 
,03-24 18:27:01.555  3251  3316 I jxcore-log: # setup
03-24 18:27:01.555  3251  3316 I jxcore-log: 
,03-24 18:27:01.649  3251  3316 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 18:27:01.649  3251  3316 I jxcore-log: 
,03-24 18:27:01.809  3251  3316 I jxcore-log: ok 82 specific error should be returned
03-24 18:27:01.809  3251  3316 I jxcore-log: 
,03-24 18:27:01.810  3251  3316 I jxcore-log: # teardown
03-24 18:27:01.810  3251  3316 I jxcore-log: 
,03-24 18:27:01.951  3251  3316 I jxcore-log: ok 83 error should be null
03-24 18:27:01.951  3251  3316 I jxcore-log: 
,03-24 18:27:01.952  3251  3316 I jxcore-log: ok 84 error should be null
03-24 18:27:01.952  3251  3316 I jxcore-log: 
03-24 18:27:01.953  3251  3316 I jxcore-log: # setup
03-24 18:27:01.953  3251  3316 I jxcore-log: 
,03-24 18:27:02.423  3251  3316 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 18:27:02.423  3251  3316 I jxcore-log: ,
,03-24 18:27:03.812  3251  3316 I jxcore-log: ok 85 specific error should be returned
03-24 18:27:03.812  3251  3316 I jxcore-log: 
,03-24 18:27:03.816  3251  3316 I jxcore-log: # teardown
03-24 18:27:03.816  3251  3316 I jxcore-log: 
,03-24 18:27:03.988  3251  3316 I jxcore-log: ok 86 error should be null
03-24 18:27:03.988  3251  3316 I jxcore-log: 
,03-24 18:27:03.989  3251  3316 I jxcore-log: ok 87 error should be null
03-24 18:27:03.989  3251  3316 I jxcore-log: 
03-24 18:27:03.991  3251  3316 I jxcore-log: # setup
03-24 18:27:03.991  3251  3316 I jxcore-log: 
,03-24 18:27:06.095  3251  3316 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-24 18:27:06.095  3251  3316 I jxcore-log: 
,03-24 18:27:06.199  3365  3703 V GoogleAuthProtoRequest: [338] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 18:27:06.267  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 18:27:06.267  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:27:06.267  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:27:06.267  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:06.275  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:06.301  3365  3703 W ExperimentUpdateService: [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 18:27:06.302  3365  3703 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110),
,03-24 18:27:07.477  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:27:07.477  3251  3316 I jxcore-log: 
03-24 18:27:07.478  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 38868
03-24 18:27:07.478  3251  3316 I jxcore-log: 
03-24 18:27:07.481  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:07.481  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:07.481  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:07.485  3251  3316 I jxcore-log: ok 88 error should be null,
03-24 18:27:07.485  3251  3316 I jxcore-log: 
03-24 18:27:07.485  3251  3316 I jxcore-log: ok 89 error should be null
03-24 18:27:07.485  3251  3316 I jxcore-log: 
,03-24 18:27:07.488  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:27:07.488  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:27:07.488  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:07.490  3251  3316 I jxcore-log: ok 90 error should be null
03-24 18:27:07.490  3251  3316 I jxcore-log: 
,03-24 18:27:07.491  3251  3316 I jxcore-log: ok 91 error should be null
03-24 18:27:07.491  3251  3316 I jxcore-log: 
,03-24 18:27:07.496  3251  3316 I jxcore-log: # teardown,
03-24 18:27:07.496  3251  3316 I jxcore-log: 
,03-24 18:27:09.679  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:09.679  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:09.679  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:09.688  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:09.688  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:09.689  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:09.693  3251  3316 I jxcore-log: ok 92 error should be null
03-24 18:27:09.693  3251  3316 I jxcore-log: 
03-24 18:27:09.694  3251  3316 I jxcore-log: ok 93 error should be null
03-24 18:27:09.694  3251  3316 I jxcore-log: 
,03-24 18:27:09.701  3251  3316 I jxcore-log: # setup
03-24 18:27:09.701  3251  3316 I jxcore-log: 
,03-24 18:27:11.210  3251  3316 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 18:27:11.210  3251  3316 I jxcore-log: 
,03-24 18:27:14.805  1244  1512 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-24 18:27:14.805  1244  1512 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 18:27:14.843  1263  1263 I ConfigService: onCreate
,03-24 18:27:19.238  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:27:19.238  3251  3316 I jxcore-log: 
,03-24 18:27:19.240  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 41552
03-24 18:27:19.240  3251  3316 I jxcore-log: 
,03-24 18:27:19.251  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
03-24 18:27:19.251  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:19.251  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:19.251  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:27:19.251  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:19.251  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:27:19.259  3251  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:27:19.260   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:19.267  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 18:27:19.273  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:27:19.273  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:27:19.273  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:19.274  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:19.281  2162  2182 D BtGatt.GattService: registerClient() - UUID=b3cf04fa-c5c3-4d39-91c3-cd0ed2180328
,03-24 18:27:19.282  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=b3cf04fa-c5c3-4d39-91c3-cd0ed2180328, clientIf=5
03-24 18:27:19.283  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:27:19.284  2162  2181 D BtGatt.GattService: start scan with filters,
03-24 18:27:19.286  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:27:19.286  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:27:19.286  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 18:27:19.286  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:19.286  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:27:19.286  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:19.286  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:19.287  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:27:19.287   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:19.291  2162  2234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a416fdc
,03-24 18:27:19.293  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:19.293  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:19.294  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:19.294  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:19.294  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:19.295  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:19.302  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 18:27:19.302  3251  3316 I jxcore-log: 
03-24 18:27:19.303  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:19.303  3251  3316 I jxcore-log: 
,03-24 18:27:19.305  3251  3316 I jxcore-log: ok 94 error should be null
03-24 18:27:19.305  3251  3316 I jxcore-log: 
03-24 18:27:19.305  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 18:27:19.306  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:19.306  3251  3316 I jxcore-log: ok 95 error should be null
03-24 18:27:19.306  3251  3316 I jxcore-log: 
,03-24 18:27:19.309  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:27:19.309  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:19.311  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 18:27:19.311  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:19.312  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
03-24 18:27:19.312  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:19.312  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:19.312  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:19.312  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:19.313  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:19.313  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:19.315  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:27:19.315  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:19.316  3251  3316 I jxcore-log: ok 96 error should be null
03-24 18:27:19.316  3251  3316 I jxcore-log: 
,03-24 18:27:19.317  3251  3316 I jxcore-log: ok 97 error should be null
03-24 18:27:19.317  3251  3316 I jxcore-log: 
,03-24 18:27:19.324  3251  3316 I jxcore-log: # teardown
,03-24 18:27:19.324  3251  3316 I jxcore-log: 
,03-24 18:27:19.923  1263  1263 I ConfigService: onDestroy
,03-24 18:27:20.316  2162  2162 D BtGatt.ScanManager: awakened up at time 231699
,03-24 18:27:20.318  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:20.327  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 18:27:20.327  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:21.342  2162  2162 D BtGatt.ScanManager: awakened up at time 232726
,03-24 18:27:21.345  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:21.352  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:27:21.352  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:22.367  2162  2162 D BtGatt.ScanManager: awakened up at time 233751
03-24 18:27:22.368  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:22.375  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:27:22.375  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:22.538  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:22.538  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:22.538  3251  3316 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 18:27:22.538  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:22.538  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:27:22.538  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:27:22.538  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:22.539  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 18:27:22.539  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:27:22.542  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:27:22.543  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:27:22.544  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:22.544  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:22.544  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:27:22.544  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 18:27:22.544  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 18:27:22.544  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:27:22.545  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:27:22.545  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:22.545  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:27:22.547  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:27:22.547  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:27:22.547  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:27:22.547  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:27:22.548  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:22.548  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:22.548  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:27:22.547  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:22.548  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:27:22.549  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 18:27:22.549  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:27:22.552  3251  3316 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 18:27:22.552  3251  3316 I jxcore-log: 
03-24 18:27:22.553  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:27:22.553  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:22.567  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:27:22.567   822  1114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:22.574  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 18:27:22.575  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:27:22.575  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:22.581  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 18:27:22.581  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:22.581  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:27:22.581  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:22.582  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:27:22.582  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:22.582  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:22.584  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 18:27:22.584  3251  3316 I jxcore-log: 
03-24 18:27:22.584  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:22.584  3251  3316 I jxcore-log: 
,03-24 18:27:22.588  3251  3316 I jxcore-log: ok 98 error should be null
,03-24 18:27:22.588  3251  3316 I jxcore-log: 
,03-24 18:27:22.589  3251  3316 I jxcore-log: ok 99 error should be null
,03-24 18:27:22.589  3251  3316 I jxcore-log: 
03-24 18:27:22.594  3251  3316 I jxcore-log: # setup
03-24 18:27:22.594  3251  3316 I jxcore-log: 
,03-24 18:27:27.898  3487  3710 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 18:27:27.963  3487  3711 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 18:27:28.037  1263  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 18:27:28.037  1263  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:27:28.037  1263  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:27:28.037  1263  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:28.042  1263  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:28.045  1263  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 18:27:28.046  1263  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:27:28.046  1263  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 18:27:28.046  1263  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:28.058  1263  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:28.082  3088  3709 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 18:27:28.082  3088  3709 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jdm.a(PG:82)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jcs.o(PG:406)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jcn.a(PG:1379)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jcs.i(PG:143)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at blb.a(PG:3937)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at czp.a(PG:18188)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at czp.a(PG:9081)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at czq.run(PG:1686)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:27:28.082  3088  3709 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jdj.a(PG:4091)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jdj.a(PG:1125)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jdm.a(PG:77)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	... 12 more
03-24 18:27:28.082  3088  3709 E HttpOperation: Caused by: faj: BadAuthentication
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at fal.a(PG:38)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	at jdj.a(PG:4089)
03-24 18:27:28.082  3088  3709 E HttpOperation: 	... 14 more
,03-24 18:27:28.131  1263  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 18:27:28.131  1263  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:27:28.131  1263  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:27:28.131  1263  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:28.139  1263  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:28.153  3088  3709 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 18:27:28.153  3088  3709 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jdm.a(PG:82)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jcs.o(PG:406)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jcn.a(PG:1379)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jcs.i(PG:143)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at hec.a(PG:42)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at hee.a(PG:102)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at czr.a(PG:65)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at kka.a(PG:108)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at czp.a(PG:19176)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at czp.a(PG:9081)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at czq.run(PG:1686)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:27:28.153  3088  3709 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jdj.a(PG:4091)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jdj.a(PG:1125)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jdm.a(PG:77)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	... 15 more
03-24 18:27:28.153  3088  3709 E HttpOperation: Caused by: faj: BadAuthentication
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at fal.a(PG:38)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	at jdj.a(PG:4089)
03-24 18:27:28.153  3088  3709 E HttpOperation: 	... 17 more
,03-24 18:27:28.154  3088  3709 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 18:27:28.154  3088  3709 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at hec.a(PG:42)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at hee.a(PG:102)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at czr.a(PG:65)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at kka.a(PG:108)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	... 15 more
03-24 18:27:28.154  3088  3709 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at fal.a(PG:38)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 18:27:28.154  3088  3709 E ExperimentLoader: 	... 17 more
,03-24 18:27:28.155  1263  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 18:27:28.155  1263  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:27:28.155  1263  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:27:28.156  1263  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:28.160  1263  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:28.173  3487  3711 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 18:27:28.174  3487  3710 E BooksSync: Soft error
03-24 18:27:28.174  3487  3710 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:27:28.174  3487  3710 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 18:27:28.174  3487  3710 E BooksSync: Sync error
03-24 18:27:28.174  3487  3710 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:27:28.174  3487  3710 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 18:27:28.174  3487  3710 I BooksSync: Finished books sync
,03-24 18:27:28.181   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212496, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:27:28.237  3442  3713 V KeepSync: Connecting to GoogleApiClient
,03-24 18:27:28.274   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 210823, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:27:28.301  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 18:27:28.302  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 18:27:28.302  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:27:28.302  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:28.307  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: Handling authorization failure
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 18:27:28.328  1815  3715 E ClientConnectionOperation: 	... 7 more
,03-24 18:27:28.332  3442  3713 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 18:27:28.338  3442  3713 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 18:27:28.348  3442  3713 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 18:27:28.348  3442  3713 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 18:27:28.433  1263  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 18:27:28.434  1263  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:27:28.434  1263  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:27:28.434  1263  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:27:28.443  1263  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:27:28.524  3442  3713 E KeepSync: IOException
03-24 18:27:28.524  3442  3713 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 18:27:28.524  3442  3713 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 18:27:28.524  3442  3713 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 18:27:28.524  3442  3713 E KeepSync: 	... 10 more
03-24 18:27:28.524  3442  3713 W KeepSync: Sync result 2
,03-24 18:27:28.538   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 212782, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:27:33.044  3251  3316 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 18:27:33.044  3251  3316 I jxcore-log: 
,03-24 18:27:34.577  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:27:34.577  3251  3316 I jxcore-log: 
,03-24 18:27:34.580  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 58355
,03-24 18:27:34.580  3251  3316 I jxcore-log: 
,03-24 18:27:34.596  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 58355, start advertisements: true
03-24 18:27:34.596  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:34.596  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:34.596  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:27:34.601  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 18:27:34.601  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:27:34.601  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 18:27:34.601  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:34.608  2162  2369 D BtGatt.GattService: registerClient() - UUID=c73070d3-055c-4a66-9555-1ccc6a171326
,03-24 18:27:34.608  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=c73070d3-055c-4a66-9555-1ccc6a171326, clientIf=5
03-24 18:27:34.609  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:27:34.610  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:27:34.611  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:27:34.611  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:27:34.612  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:34.612  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:27:34.612  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:34.612  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:34.613  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:34.613  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:27:34.613  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 18:27:34.614  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 18:27:34.617  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:27:34.617  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:34.618  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:27:34.628  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 18:27:34.628  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:34.630  2162  2181 D BtGatt.GattService: registerClient() - UUID=b9af6d75-9101-47d3-ae94-1badbe84679e
03-24 18:27:34.630  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:34.630  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:34.631  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=b9af6d75-9101-47d3-ae94-1badbe84679e, clientIf=6,
03-24 18:27:34.631  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:27:34.631  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:34.632  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-24 18:27:34.634  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:34.634  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:34.636  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:27:34.636  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:34.639  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:27:34.644  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 18:27:34.648  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:27:34.651  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:27:34.653  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-24 18:27:34.653  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:34.654   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 18:27:34.662  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:34.662  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:34.662  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:27:34.662  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 18:27:34.664  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 18:27:34.666  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:27:34.666  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:27:34.666  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:27:34.667  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:34.667  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 18:27:34.667  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:27:34.667  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:27:34.668  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:27:34.668  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:27:34.668  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 18:27:34.668  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:27:34.669  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:34.669  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:27:34.669  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:34.669  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 18:27:34.669  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:34.677   822  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:34.681  3251  3718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:27:34.687  3251  3718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:27:34.690  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:34.690  3251  3316 I jxcore-log: 
,03-24 18:27:34.692  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:34.692  3251  3316 I jxcore-log: 
,03-24 18:27:34.693  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:27:34.693  3251  3316 I jxcore-log: 
,03-24 18:27:34.694  3251  3316 I jxcore-log: ok 100 error should be null
03-24 18:27:34.694  3251  3316 I jxcore-log: 
03-24 18:27:34.695  3251  3316 I jxcore-log: ok 101 error should be null
,03-24 18:27:34.695  3251  3316 I jxcore-log: 
,03-24 18:27:34.703  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 58355, start advertisements: true,
03-24 18:27:34.703  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:34.703  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:27:34.703  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:34.703  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:34.712  3251  3316 I jxcore-log: ok 102 error should be null
,03-24 18:27:34.712  3251  3316 I jxcore-log: 
03-24 18:27:34.712  3251  3316 I jxcore-log: ok 103 error should be null
03-24 18:27:34.712  3251  3316 I jxcore-log: 
,03-24 18:27:34.719  3251  3316 I jxcore-log: # teardown
03-24 18:27:34.719  3251  3316 I jxcore-log: 
,03-24 18:27:35.028  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:27:35.028  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 18:27:35.028  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:27:35.028  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:27:35.029  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
03-24 18:27:35.029  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:27:35.029  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:35.029  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:27:35.029  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 18:27:35.029  3251  3718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:27:35.029  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 18:27:35.029  3251  3718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:27:35.030  3251  3718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:27:35.030  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:27:35.030  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:27:35.033  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:27:35.034  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:27:35.035  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:27:35.035  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:35.035  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:27:35.036  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 18:27:35.036  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:35.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:27:35.036  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 18:27:35.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 18:27:35.037  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 18:27:35.037  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:27:35.038  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:35.038  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:35.038  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:27:35.040  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:27:35.041  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:27:35.042  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:27:35.042  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:35.042  2162  2224 D BtGatt.GattService: current time is 246426123290
03-24 18:27:35.042  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 102, 111, -3, 18, -72, 107, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 18:27:35.043  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:27:35.044  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:27:35.047  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:27:35.047  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:27:35.049  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:27:35.050  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:27:35.051  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:35.051  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:27:35.051  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:27:35.051  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:27:35.052  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:35.052  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:27:35.052  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:27:35.054  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:27:35.054  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:27:35.054  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:27:35.054  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:35.055  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:27:35.064  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:27:35.065   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:35.068  3251  3316 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 18:27:35.068  3251  3316 I jxcore-log: 
,03-24 18:27:35.078  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 18:27:35.079  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:27:35.080  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:35.091  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 18:27:35.091  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:27:35.092  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 18:27:35.092  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 18:27:35.092  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:35.092  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:35.093  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:35.093  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:35.093  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:27:35.093  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:35.093  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 18:27:35.094  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 18:27:35.094  3251  3316 I jxcore-log: 
03-24 18:27:35.095  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:35.095  3251  3316 I jxcore-log: 
03-24 18:27:35.097  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:35.097  3251  3316 I jxcore-log: 
,03-24 18:27:35.103  3251  3316 I jxcore-log: ok 104 error should be null
,03-24 18:27:35.103  3251  3316 I jxcore-log: 
03-24 18:27:35.104  3251  3316 I jxcore-log: ok 105 error should be null
03-24 18:27:35.104  3251  3316 I jxcore-log: ,
,03-24 18:27:35.112  3251  3316 I jxcore-log: # setup
,03-24 18:27:35.112  3251  3316 I jxcore-log: 
,03-24 18:27:35.283  3251  3316 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
03-24 18:27:35.283  3251  3316 I jxcore-log: 
,03-24 18:27:35.479  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:27:35.479  3251  3316 I jxcore-log: 
,03-24 18:27:35.481  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 41725
03-24 18:27:35.481  3251  3316 I jxcore-log: 
,03-24 18:27:35.485  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:27:35.485  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:35.486  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:35.488  3251  3316 I jxcore-log: ok 106 error should be null
03-24 18:27:35.488  3251  3316 I jxcore-log: 
,03-24 18:27:35.489  3251  3316 I jxcore-log: ok 107 error should be null,
03-24 18:27:35.489  3251  3316 I jxcore-log: 
03-24 18:27:35.491  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:35.491  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:35.491  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:35.494  3251  3316 I jxcore-log: ok 108 error should be null
03-24 18:27:35.494  3251  3316 I jxcore-log: 
03-24 18:27:35.494  3251  3316 I jxcore-log: ok 109 error should be null
03-24 18:27:35.494  3251  3316 I jxcore-log: 
03-24 18:27:35.500  3251  3316 I jxcore-log: # teardown
03-24 18:27:35.500  3251  3316 I jxcore-log: 
,03-24 18:27:36.078  2162  2226 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 18:27:37.088  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:37.088  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 18:27:37.088  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:37.090  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:37.090  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:27:37.090  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:37.094  3251  3316 I jxcore-log: ok 110 error should be null
03-24 18:27:37.094  3251  3316 I jxcore-log: 
,03-24 18:27:37.094  3251  3316 I jxcore-log: ok 111 error should be null
03-24 18:27:37.094  3251  3316 I jxcore-log: 
,03-24 18:27:37.100  3251  3316 I jxcore-log: # setup
03-24 18:27:37.100  3251  3316 I jxcore-log: 
,03-24 18:27:37.272  3251  3316 I jxcore-log: # 28. #start should fail if called twice in a row
03-24 18:27:37.272  3251  3316 I jxcore-log: 
,03-24 18:27:38.674  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:27:38.674  3251  3316 I jxcore-log: ,
03-24 18:27:38.676  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 33663
03-24 18:27:38.676  3251  3316 I jxcore-log: 
,03-24 18:27:38.678  3251  3316 I jxcore-log: ok 112 first call should succeed
03-24 18:27:38.678  3251  3316 I jxcore-log: 
,03-24 18:27:38.678  3251  3316 I jxcore-log: ok 113 first call should succeed
03-24 18:27:38.678  3251  3316 I jxcore-log: 
,03-24 18:27:38.681  3251  3316 I jxcore-log: ok 114 specific error should be returned
03-24 18:27:38.681  3251  3316 I jxcore-log: 
03-24 18:27:38.683  3251  3316 I jxcore-log: # teardown
03-24 18:27:38.683  3251  3316 I jxcore-log: 
,03-24 18:27:39.970  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-24 18:27:39.970  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,03-24 18:27:39.970  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 18:27:39.973  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 18:27:39.973  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-24 18:27:39.973  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 18:27:39.977  3251  3316 I jxcore-log: ok 115 error should be null
,03-24 18:27:39.977  3251  3316 I jxcore-log: 
,03-24 18:27:39.978  3251  3316 I jxcore-log: ok 116 error should be null,
03-24 18:27:39.978  3251  3316 I jxcore-log: 
,03-24 18:27:39.983  3251  3316 I jxcore-log: # setup
,03-24 18:27:39.983  3251  3316 I jxcore-log: 
,03-24 18:27:40.203  3251  3316 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
,03-24 18:27:40.203  3251  3316 I jxcore-log: 
,03-24 18:27:41.554  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:27:41.554  3251  3316 I jxcore-log: 
,03-24 18:27:41.557  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 53586
03-24 18:27:41.557  3251  3316 I jxcore-log: 
,03-24 18:27:41.568  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 58355, start advertisements: false
,03-24 18:27:41.568  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:41.569  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:41.569  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:27:41.576  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 18:27:41.576  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:41.577  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:41.585  2162  2181 D BtGatt.GattService: registerClient() - UUID=288b4e11-edb6-43a9-9b07-5243e34e32db
,03-24 18:27:41.585  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=288b4e11-edb6-43a9-9b07-5243e34e32db, clientIf=5
03-24 18:27:41.586  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:27:41.586  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:27:41.589  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:27:41.589  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 18:27:41.589  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:27:41.589  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:41.589  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:41.589  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:41.589  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:41.590  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:27:41.591   822  1340 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:41.599  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 18:27:41.599  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:41.599  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:41.599  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:41.600  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:41.600  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:41.608  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:41.608  3251  3316 I jxcore-log: 
03-24 18:27:41.609  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:41.609  3251  3316 I jxcore-log: 
,03-24 18:27:41.621  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53586, start advertisements: true
,03-24 18:27:41.622  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:41.622  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:41.622  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:27:41.630  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 18:27:41.630  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 18:27:41.630  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:27:41.630  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:27:41.631  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:27:41.631  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:41.631  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:41.631  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:27:41.639  2162  2369 D BtGatt.GattService: registerClient() - UUID=e0e3c017-1d9d-47d1-acd2-ccfcf20353b5
,03-24 18:27:41.692   822  1114 I art     : Explicit concurrent mark sweep GC freed 30756(1371KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 3.374ms total 92.703ms,
,03-24 18:27:41.698  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=e0e3c017-1d9d-47d1-acd2-ccfcf20353b5, clientIf=6
,03-24 18:27:41.706  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:27:41.706  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:41.707  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:27:41.709  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:41.709  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:41.709  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:27:41.709  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:41.712  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:41.712  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:41.713  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:27:41.714  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:41.718  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:27:41.738  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:27:41.742  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:27:41.744  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:27:41.745  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:27:41.745  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:27:41.745  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:41.745  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:27:41.745  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:27:41.745  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:27:41.745  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:27:41.745   822  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:41.746  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:27:41.747  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:41.747  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 18:27:41.747  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:41.747  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:41.747  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 18:27:41.747  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 18:27:41.747  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:27:41.747  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:27:41.747  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:41.747  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:27:41.747  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:41.748  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:27:41.748   822  1114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:41.749  3251  3721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:27:41.751  3251  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:27:41.753  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:27:41.753  3251  3316 I jxcore-log: 
03-24 18:27:41.756  3251  3316 I jxcore-log: ok 117 called only once
03-24 18:27:41.756  3251  3316 I jxcore-log: 
03-24 18:27:41.756  3251  3316 I jxcore-log: ok 118 discovery state matches
03-24 18:27:41.756  3251  3316 I jxcore-log: 
03-24 18:27:41.757  3251  3316 I jxcore-log: ok 119 advertising state matches
03-24 18:27:41.757  3251  3316 I jxcore-log: 
03-24 18:27:41.762  3251  3316 I jxcore-log: # teardown
03-24 18:27:41.762  3251  3316 I jxcore-log: 
,03-24 18:27:42.059  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:27:42.059  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 18:27:42.059  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:27:42.059  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:27:42.059  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:27:42.060  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:27:42.060  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:42.060  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 18:27:42.060  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:27:42.060  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:42.060  3251  3721 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:27:42.060  3251  3721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 18:27:42.061  3251  3721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:27:42.061  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:27:42.061  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:27:42.064  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:27:42.066  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:27:42.067  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:42.067  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:42.067  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:27:42.067  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:27:42.067  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 18:27:42.067  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:27:42.067  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 18:27:42.068  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:27:42.069  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:42.069  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:27:42.069  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:27:42.070  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:27:42.072  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:42.072  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:42.073  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:27:42.074  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:27:42.074  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:27:42.075  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:27:42.076  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:27:42.076  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:42.076  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:27:42.076  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:27:42.076  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:27:42.076  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:42.076  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:27:42.076  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:27:42.077  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:27:42.077  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:42.078  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:27:42.078  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:42.078  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:27:42.082  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 18:27:42.082  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:42.082  2162  2224 D BtGatt.GattService: current time is 253466323756
03-24 18:27:42.082  2162  2224 D BtGatt.GattService: Batch record : [-85, 117, -69, -72, 56, 97, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:27:42.082  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:27:42.082  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:27:42.089  3251  3316 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 18:27:42.089  3251  3316 I jxcore-log: 
03-24 18:27:42.089  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:27:42.089  3251  3316 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 18:27:42.089  3251  3316 I jxcore-log: 
03-24 18:27:42.090   822  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:42.094  3251  3316 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 18:27:42.094  3251  3316 I jxcore-log: 
,03-24 18:27:42.102  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 18:27:42.103  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:27:42.104  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:42.109  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 18:27:42.109  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:27:42.109  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:27:42.110  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:42.110  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:42.110  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:42.110  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:42.111  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 18:27:42.113  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:42.113  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:42.113  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:42.116  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:27:42.116  3251  3316 I jxcore-log: 
,03-24 18:27:42.119  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:42.119  3251  3316 I jxcore-log: 
,03-24 18:27:42.121  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:42.121  3251  3316 I jxcore-log: 
,03-24 18:27:42.131  3251  3316 I jxcore-log: ok 120 error should be null
03-24 18:27:42.131  3251  3316 I jxcore-log: 
,03-24 18:27:42.133  3251  3316 I jxcore-log: ok 121 error should be null
03-24 18:27:42.133  3251  3316 I jxcore-log: 
,03-24 18:27:42.141  3251  3316 I jxcore-log: # setup
03-24 18:27:42.141  3251  3316 I jxcore-log: 
,03-24 18:27:42.367  3251  3316 I jxcore-log: # 30. does not send duplicate availability changes
03-24 18:27:42.367  3251  3316 I jxcore-log: 
,03-24 18:27:42.501  3251  3316 I jxcore-log: ok 122 should be called once
03-24 18:27:42.501  3251  3316 I jxcore-log: 
,03-24 18:27:42.502  3251  3316 I jxcore-log: ok 123 should not have been called more than once
,03-24 18:27:42.502  3251  3316 I jxcore-log: 
03-24 18:27:42.504  3251  3316 I jxcore-log: # teardown
03-24 18:27:42.504  3251  3316 I jxcore-log: 
,03-24 18:27:42.658  3251  3316 I jxcore-log: ok 124 error should be null
03-24 18:27:42.658  3251  3316 I jxcore-log: 
,03-24 18:27:42.658  3251  3316 I jxcore-log: ok 125 error should be null
03-24 18:27:42.658  3251  3316 I jxcore-log: 
03-24 18:27:42.660  3251  3316 I jxcore-log: # setup
03-24 18:27:42.660  3251  3316 I jxcore-log: 
,03-24 18:27:42.825  3251  3316 I jxcore-log: # 31. can get the network status
03-24 18:27:42.825  3251  3316 I jxcore-log: 
,03-24 18:27:42.957  3251  3316 I jxcore-log: ok 126 network status should have certain non-empty properties,
03-24 18:27:42.957  3251  3316 I jxcore-log: 
03-24 18:27:42.959  3251  3316 I jxcore-log: # teardown,
03-24 18:27:42.959  3251  3316 I jxcore-log: 
,03-24 18:27:43.146  3251  3316 I jxcore-log: ok 127 error should be null,
03-24 18:27:43.146  3251  3316 I jxcore-log: 
03-24 18:27:43.148  3251  3316 I jxcore-log: ok 128 error should be null
,03-24 18:27:43.148  3251  3316 I jxcore-log: 
03-24 18:27:43.155  3251  3316 I jxcore-log: # setup
,03-24 18:27:43.155  3251  3316 I jxcore-log: 
,03-24 18:27:43.278  3251  3316 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 18:27:43.278  3251  3316 I jxcore-log: 
,03-24 18:27:43.482  3251  3316 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined,
03-24 18:27:43.482  3251  3316 I jxcore-log: 
,03-24 18:27:43.504  3251  3316 I jxcore-log: ok 129 host address should match
03-24 18:27:43.504  3251  3316 I jxcore-log: 
,03-24 18:27:43.505  3251  3316 I jxcore-log: ok 130 port should match
03-24 18:27:43.505  3251  3316 I jxcore-log: 
,03-24 18:27:45.481  3251  3316 I jxcore-log: ok 131 host address should be null,
03-24 18:27:45.481  3251  3316 I jxcore-log: 
03-24 18:27:45.482  3251  3316 I jxcore-log: ok 132 port should should be null
03-24 18:27:45.482  3251  3316 I jxcore-log: 
,03-24 18:27:45.500  3251  3316 I jxcore-log: # teardown
03-24 18:27:45.500  3251  3316 I jxcore-log: 
,03-24 18:27:45.770  3251  3316 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 18:27:45.770  3251  3316 I jxcore-log: 
,03-24 18:27:45.775  3251  3316 I jxcore-log: ok 133 error should be null
03-24 18:27:45.775  3251  3316 I jxcore-log: 
,03-24 18:27:45.777  3251  3316 I jxcore-log: ok 134 error should be null
03-24 18:27:45.777  3251  3316 I jxcore-log: 
03-24 18:27:45.779  3251  3316 I jxcore-log: # setup
03-24 18:27:45.779  3251  3316 I jxcore-log: 
,03-24 18:27:46.017  3251  3316 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 18:27:46.017  3251  3316 I jxcore-log: 
,03-24 18:27:46.158  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53586, start advertisements: false
,03-24 18:27:46.158  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:46.158  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:46.158  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:27:46.168  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 18:27:46.168  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:46.168  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:46.179  2162  2369 D BtGatt.GattService: registerClient() - UUID=ab545fa1-854d-41d9-af3c-19cafb7d0394
,03-24 18:27:46.180  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=ab545fa1-854d-41d9-af3c-19cafb7d0394, clientIf=5
,03-24 18:27:46.180  3251  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:27:46.181  2162  2181 D BtGatt.GattService: start scan with filters
,03-24 18:27:46.185  2162  2234 D BtGatt.ScanManager: handling starting scan,
03-24 18:27:46.185  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:27:46.185  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 18:27:46.186  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:46.186  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:46.186  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:46.186  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:46.187  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:46.188   822  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:46.195  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:27:46.195  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:46.198  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:46.198  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:46.199  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 18:27:46.199  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:27:46.203  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:46.204  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:46.205  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:46.205  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:46.205  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:46.205  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:46.206  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:46.206  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:46.207  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:27:46.207  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:46.213  3251  3316 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
,03-24 18:27:46.213  3251  3316 I jxcore-log: 
,03-24 18:27:46.215  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:27:46.215  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:46.215  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
03-24 18:27:46.215  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:27:46.219  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:27:46.221  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:27:46.221  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:46.221  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:46.221  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 18:27:46.221  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 18:27:46.221  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 18:27:46.221  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 18:27:46.221  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:46.222  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:46.222  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:27:46.222  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:46.223  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:27:46.223  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:46.225  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 18:27:46.225  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:46.225  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:27:46.226  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 18:27:46.226  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:46.227  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:46.227  3251  3316 I jxcore-log: 
,03-24 18:27:46.228  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:46.228  3251  3316 I jxcore-log: 
03-24 18:27:46.229  3251  3316 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 18:27:46.229  3251  3316 I jxcore-log: 
,03-24 18:27:46.235  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:46.235  3251  3316 I jxcore-log: 
03-24 18:27:46.237  3251  3316 I jxcore-log: # teardown
03-24 18:27:46.237  3251  3316 I jxcore-log: ,
,03-24 18:27:46.619  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:27:46.619  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:46.619  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:46.628  3251  3316 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-24 18:27:46.628  3251  3316 I jxcore-log: 
,03-24 18:27:46.629  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:27:46.631  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 18:27:46.632  3251  3316 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 18:27:46.632  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:46.632  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:27:46.632  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 18:27:46.632  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:46.632  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:27:46.635  3251  3316 D BluetoothLeScanner: could not find callback wrapper
,03-24 18:27:46.635  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:46.637  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:27:46.637  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 18:27:46.638  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:27:46.639  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 18:27:46.639  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:46.639  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-24 18:27:46.639  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:46.639  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:27:46.648  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:27:46.648   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:46.655  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 18:27:46.656  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:27:46.656  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:46.660  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 18:27:46.660  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:46.660  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:27:46.662  3251  3316 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
,03-24 18:27:46.662  3251  3316 I jxcore-log: 
,03-24 18:27:46.672  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:46.672  3251  3316 I jxcore-log: ,
,03-24 18:27:46.674  3251  3316 I jxcore-log: # setup
03-24 18:27:46.674  3251  3316 I jxcore-log: 
,03-24 18:27:46.810  3251  3316 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error,
03-24 18:27:46.810  3251  3316 I jxcore-log: 
,03-24 18:27:47.061  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53586, start advertisements: false
,03-24 18:27:47.062  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:47.063  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:47.063  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:27:47.073  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:27:47.073  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 18:27:47.074  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:47.083  2162  2182 D BtGatt.GattService: registerClient() - UUID=a94c9796-1c54-422d-b4b0-8cf140f5ddd3
,03-24 18:27:47.084  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=a94c9796-1c54-422d-b4b0-8cf140f5ddd3, clientIf=5
,03-24 18:27:47.085  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:27:47.087  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:27:47.089  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:27:47.089  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:27:47.090  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:27:47.090  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:47.090  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:47.090  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:47.090  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:47.091  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:27:47.091   822  1114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:47.096  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:27:47.096  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:47.099  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:47.099  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:47.100  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:27:47.100  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:47.103  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:47.103  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 18:27:47.104  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:47.104  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:47.105  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:47.105  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:47.105  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:47.107  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:47.108  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:27:47.108  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:47.113  3251  3316 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-24 18:27:47.113  3251  3316 I jxcore-log: 
,03-24 18:27:47.118  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53586, start advertisements: false
,03-24 18:27:47.118  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:47.118  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:27:47.118  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:47.119  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:47.121  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:47.121  3251  3316 I jxcore-log: 
,03-24 18:27:47.123  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:47.123  3251  3316 I jxcore-log: 
,03-24 18:27:47.125  3251  3316 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-24 18:27:47.125  3251  3316 I jxcore-log: 
,03-24 18:27:47.137  3251  3316 I jxcore-log: # teardown
03-24 18:27:47.137  3251  3316 I jxcore-log: 
,03-24 18:27:47.497  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:47.498  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:27:47.498  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 18:27:47.498  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:27:47.503  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:27:47.507  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:27:47.510  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 18:27:47.511  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:27:47.511  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:27:47.511  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 18:27:47.511  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 18:27:47.511  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:47.511  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 18:27:47.511  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:47.511  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:47.512  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:27:47.512  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:27:47.512  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:27:47.515  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:47.515  3251  3316 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-24 18:27:47.515  3251  3316 I jxcore-log: 
,03-24 18:27:47.515  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:47.515  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:47.517  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:47.517  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:47.517  3251  3316 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
03-24 18:27:47.517  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:47.517  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 18:27:47.517  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:27:47.517  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:47.517  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 18:27:47.517  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:47.518  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 18:27:47.536  3251  3316 D BluetoothLeScanner: could not find callback wrapper
,03-24 18:27:47.536  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:47.537  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:27:47.537  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:27:47.537  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:27:47.538  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 18:27:47.539  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 18:27:47.539  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:27:47.539  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:47.539  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-24 18:27:47.543  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 18:27:47.543  3251  3316 I jxcore-log: 
,03-24 18:27:47.547  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:27:47.547   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:47.553  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 18:27:47.553  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:27:47.554  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:47.558  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:27:47.558  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:47.558  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:27:47.560  3251  3316 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown,
03-24 18:27:47.560  3251  3316 I jxcore-log: 
,03-24 18:27:47.566  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 18:27:47.566  3251  3316 I jxcore-log: 
,03-24 18:27:47.569  3251  3316 I jxcore-log: # setup
,03-24 18:27:47.569  3251  3316 I jxcore-log: 
,03-24 18:27:48.872  3251  3316 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-24 18:27:48.872  3251  3316 I jxcore-log: 
,03-24 18:27:50.600  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 18:27:50.600  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:50.600  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:50.600  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:27:50.608  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 18:27:50.608  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:27:50.608  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:50.609  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:50.617  2162  2181 D BtGatt.GattService: registerClient() - UUID=44f35dde-ddc2-4b7f-a898-65e039e937bc
,03-24 18:27:50.617  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=44f35dde-ddc2-4b7f-a898-65e039e937bc, clientIf=5
03-24 18:27:50.618  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:27:50.620  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:27:50.622  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:27:50.623  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:27:50.623  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 18:27:50.625  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 18:27:50.625  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:50.625  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:50.625  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 18:27:50.625  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:27:50.625  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:27:50.626  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:50.627  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:50.627  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:50.627  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:27:50.632  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:27:50.632  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:50.635  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:50.635  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:50.635  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 18:27:50.635  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:50.638  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:50.639  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:50.639  2162  2369 D BtGatt.GattService: registerClient() - UUID=f18dd94d-38a7-4fba-b0c0-ee9ff3ebfacb
03-24 18:27:50.640  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=f18dd94d-38a7-4fba-b0c0-ee9ff3ebfacb, clientIf=6
03-24 18:27:50.641  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:27:50.641  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:50.641  3251  3266 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:27:50.643  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:27:50.649  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:27:50.654  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 18:27:50.658  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 18:27:50.659  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:27:50.659  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 18:27:50.661   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:50.669  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-24 18:27:50.669  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:50.669  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:27:50.669  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:50.671  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 18:27:50.672  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,03-24 18:27:50.672  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 18:27:50.672  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:27:50.673  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:50.673  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 18:27:50.673  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:27:50.673  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:27:50.673  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:27:50.674  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 18:27:50.674  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:27:50.674  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:27:50.674  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:50.674  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 18:27:50.674  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:50.675   822  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:50.675  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:27:50.675  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:27:50.677  3251  3723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:27:50.679  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:50.679  3251  3316 I jxcore-log: 
03-24 18:27:50.682  3251  3723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:27:50.686  3251  3316 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-24 18:27:50.686  3251  3316 I jxcore-log: 
03-24 18:27:50.688  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:50.689  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 18:27:50.689  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 18:27:50.689  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:27:50.689  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
03-24 18:27:50.689  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:27:50.689  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 18:27:50.690  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 18:27:50.690  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 18:27:50.690  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:50.690  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:27:50.690  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:27:50.691  3251  3723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:27:50.691  3251  3723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:27:50.691  3251  3723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:27:50.693  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:27:50.697  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:27:50.697  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:50.697  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:27:50.698  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:27:50.699  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:50.699  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:50.699  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 18:27:50.699  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:27:50.699  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 18:27:50.699  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:27:50.699  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:27:50.701  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:50.701  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:50.701  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:50.702  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:27:50.702  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:27:50.704  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 18:27:50.704  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:50.704  2162  2224 D BtGatt.GattService: current time is 262088787867
03-24 18:27:50.705  2162  2224 D BtGatt.GattService: Batch record : [-38, -30, 37, 108, -88, 90, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:27:50.705  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:27:50.707  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 18:27:50.707  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:27:50.708  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 18:27:50.708  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:27:50.708  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:27:50.708  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 18:27:50.708  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:27:50.708  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:27:50.709  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:50.709  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:27:50.709  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:27:50.709  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 18:27:50.709  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:50.709  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:27:50.710  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:50.710  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:27:50.711  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:50.711  3251  3316 I jxcore-log: 
03-24 18:27:50.712  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:27:50.712  3251  3316 I jxcore-log: 
,03-24 18:27:50.716  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:27:50.716   822  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:50.721  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:27:50.722  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 18:27:50.722  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:50.725  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 18:27:50.725  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 18:27:50.725  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:27:50.725  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:50.725  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:50.726  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:27:50.726  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:50.726  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 18:27:50.728  3251  3316 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 18:27:50.728  3251  3316 I jxcore-log: 
,03-24 18:27:50.738  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:27:50.738  3251  3316 I jxcore-log: 
,03-24 18:27:50.740  3251  3316 I jxcore-log: # teardown
03-24 18:27:50.740  3251  3316 I jxcore-log: 
,03-24 18:27:50.743  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:50.743  3251  3316 I jxcore-log: 
,03-24 18:27:50.745  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:50.745  3251  3316 I jxcore-log: 
,03-24 18:27:51.349  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:27:51.349  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:27:51.349  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:51.357  3251  3316 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 18:27:51.357  3251  3316 I jxcore-log: 
,03-24 18:27:51.359  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:27:51.359  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:51.359  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:51.363  3251  3316 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-24 18:27:51.363  3251  3316 I jxcore-log: 
,03-24 18:27:51.370  3251  3316 I jxcore-log: # setup
03-24 18:27:51.370  3251  3316 I jxcore-log: 
,03-24 18:27:51.631  3251  3316 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,03-24 18:27:51.631  3251  3316 I jxcore-log: 
,03-24 18:27:53.204  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 18:27:53.204  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:53.204  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:53.205  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:27:53.212  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 18:27:53.212  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:27:53.212  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:53.212  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:53.220  2162  2182 D BtGatt.GattService: registerClient() - UUID=8cf946cc-1f4d-4987-94e8-38885c98ee20,
03-24 18:27:53.220  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=8cf946cc-1f4d-4987-94e8-38885c98ee20, clientIf=5
03-24 18:27:53.221  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:27:53.222  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:27:53.223  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:27:53.223  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:27:53.224  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:53.224  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:53.224  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:27:53.224  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:53.224  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 18:27:53.224  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:53.224  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:27:53.227  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:27:53.227  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:53.228  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 18:27:53.228  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:27:53.235  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:27:53.235  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:53.238  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:53.238  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:53.238  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:27:53.238  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:53.239  2162  2181 D BtGatt.GattService: registerClient() - UUID=9667a923-24e0-41b5-8c01-c11790919eae
03-24 18:27:53.239  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=9667a923-24e0-41b5-8c01-c11790919eae, clientIf=6
03-24 18:27:53.240  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:27:53.242  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:27:53.243  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:53.243  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:53.246  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:27:53.247  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:53.250  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:27:53.255  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:27:53.259  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:27:53.259  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:27:53.260  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:53.260   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:53.263  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:53.263  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:53.263  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:27:53.263  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 18:27:53.264  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:27:53.264  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 18:27:53.264  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:27:53.264  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:27:53.265  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:53.265  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:53.265  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:27:53.265  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 18:27:53.265  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:27:53.265  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:27:53.265  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 18:27:53.265  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:27:53.265  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:53.265  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 18:27:53.265  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:53.266  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:27:53.266  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:53.267  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:53.267  3251  3316 I jxcore-log: 
03-24 18:27:53.268  3251  3316 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-24 18:27:53.268  3251  3316 I jxcore-log: 
03-24 18:27:53.269   822  1340 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:53.272  3251  3725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:27:53.274  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-24 18:27:53.274  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:53.274  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:27:53.274  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:53.274  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:53.278  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:53.278  3251  3316 I jxcore-log: 
03-24 18:27:53.279  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:27:53.279  3251  3316 I jxcore-log: 
03-24 18:27:53.281  3251  3316 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-24 18:27:53.281  3251  3316 I jxcore-log: 
03-24 18:27:53.286  3251  3725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:27:53.288  3251  3316 I jxcore-log: # teardown
03-24 18:27:53.288  3251  3316 I jxcore-log: 
,03-24 18:27:53.950  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:27:53.951  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:27:53.951  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 18:27:53.951  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:27:53.956  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:27:53.959  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:27:53.960  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:53.960  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:27:53.960  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:27:53.960  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:27:53.961  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:27:53.961  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:53.961  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 18:27:53.961  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:27:53.961  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:27:53.963  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 18:27:53.965  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:27:53.965  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:53.965  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:53.966  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:53.967  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:53.970  3251  3316 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 18:27:53.970  3251  3316 I jxcore-log: 
03-24 18:27:53.970  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:27:53.970  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:53.971  2162  2224 D BtGatt.GattService: current time is 265355046720
03-24 18:27:53.971  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:27:53.971  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -56, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -114, 74, -6, 8, -12, 108, 1, -128, -56, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:27:53.971  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-24 18:27:53.971  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:27:53.971  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:27:53.971  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:27:53.972  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:27:53.972  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:27:53.974  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:27:53.974  3251  3725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:27:53.974  3251  3725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 18:27:53.975  3251  3725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:27:53.975  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 18:27:53.976  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:53.976  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 18:27:53.976  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:27:53.976  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:27:53.976  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:53.976  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 18:27:53.976  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 18:27:53.978  3251  3316 D BluetoothLeScanner: could not find callback wrapper
03-24 18:27:53.978  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:53.978  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 18:27:53.981  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:27:53.982  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 18:27:53.986  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 18:27:53.986  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:27:53.988  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:27:53.989  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:27:53.989  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:27:53.990  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:27:53.990  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:27:53.990  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:27:53.990  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:53.990  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:27:53.990  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:27:53.992  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 18:27:53.992  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:27:53.992  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:53.993  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:53.993  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:27:53.993  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:53.993  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:27:53.995  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:27:53.995  3251  3316 I jxcore-log: 
03-24 18:27:53.999  3251  3316 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-24 18:27:53.999  3251  3316 I jxcore-log: 
,03-24 18:27:54.001  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:27:54.002   822  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:54.010  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:27:54.011  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:27:54.011  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:54.016  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:27:54.016  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:54.017  3251  3316 I jxcore-log: # setup
03-24 18:27:54.017  3251  3316 I jxcore-log: 
03-24 18:27:54.020  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:54.020  3251  3316 I jxcore-log: 
,03-24 18:27:54.021  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:54.021  3251  3316 I jxcore-log: 
,03-24 18:27:54.260  3251  3316 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 18:27:54.260  3251  3316 I jxcore-log: 
,03-24 18:27:54.434  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 18:27:54.434  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:54.434  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:54.434  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:27:54.441  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 18:27:54.441  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:27:54.442  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:54.442  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:54.450  2162  2182 D BtGatt.GattService: registerClient() - UUID=3f37d7e0-1c13-4791-a46f-e9ecbf1a9ef3,
03-24 18:27:54.450  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=3f37d7e0-1c13-4791-a46f-e9ecbf1a9ef3, clientIf=5
,03-24 18:27:54.451  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:27:54.452  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:27:54.455  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:27:54.455  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 18:27:54.455  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:27:54.455  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:54.455  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 18:27:54.455  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:27:54.456  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:54.456  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 18:27:54.457  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 18:27:54.458  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:27:54.460  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:54.461  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:27:54.461  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:27:54.464  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 18:27:54.464  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:54.466  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:54.467  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:54.467  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 18:27:54.467  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:54.470  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:54.470  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:54.472  2162  2181 D BtGatt.GattService: registerClient() - UUID=a45ee732-c41b-485a-a1f6-29fea4ca8e5d
,03-24 18:27:54.472  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=a45ee732-c41b-485a-a1f6-29fea4ca8e5d, clientIf=6
03-24 18:27:54.473  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:27:54.473  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:54.473  3251  3266 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:27:54.476  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:27:54.481  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:27:54.485  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:27:54.488  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:27:54.489  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:27:54.489  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 18:27:54.490   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:54.497  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:54.497  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:54.497  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:27:54.497  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 18:27:54.499  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:27:54.499  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:27:54.499  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:27:54.500  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-24 18:27:54.500  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:54.500  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:54.500  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:27:54.500  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:27:54.500  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:27:54.501  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:27:54.501  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:27:54.501  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:54.501  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:54.501  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:27:54.501  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:54.501  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:27:54.501  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:54.503  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:54.503  3251  3316 I jxcore-log: 
03-24 18:27:54.503   822  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:54.504  3251  3316 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
03-24 18:27:54.504  3251  3316 I jxcore-log: 
03-24 18:27:54.507  3251  3726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:27:54.510  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-24 18:27:54.510  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:54.510  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 18:27:54.510  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:27:54.510  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:54.511  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 18:27:54.511  3251  3316 I jxcore-log: 
03-24 18:27:54.513  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:27:54.513  3251  3316 I jxcore-log: 
03-24 18:27:54.514  3251  3726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 18:27:54.514  3251  3316 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-24 18:27:54.514  3251  3316 I jxcore-log: 
,03-24 18:27:55.481  2162  2162 D BtGatt.ScanManager: awakened up at time 266864
,03-24 18:27:55.483  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:55.491  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 18:27:55.491  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:55.491  2162  2224 D BtGatt.GattService: current time is 266875663490
,03-24 18:27:55.492  2162  2224 D BtGatt.GattService: Batch record : [68, -73, -126, -65, 49, 71, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:27:55.492  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:27:55.493  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:27:55.498  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 18:27:55.499  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 18:27:55.499  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 18:27:55.499  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 18:27:55.503  3251  3316 I jxcore-log: ok 153 peers must be an array
03-24 18:27:55.503  3251  3316 I jxcore-log: 
,03-24 18:27:55.504  3251  3316 I jxcore-log: ok 154 peers must not be zero-length
03-24 18:27:55.504  3251  3316 I jxcore-log: 
,03-24 18:27:55.506  3251  3316 I jxcore-log: ok 155 peer must have peerIdentifier,
03-24 18:27:55.506  3251  3316 I jxcore-log: 
,03-24 18:27:55.507  3251  3316 I jxcore-log: ok 156 peerIdentifier must be a string
03-24 18:27:55.507  3251  3316 I jxcore-log: 
,03-24 18:27:55.508  3251  3316 I jxcore-log: ok 157 peer must have peerAvailable
03-24 18:27:55.508  3251  3316 I jxcore-log: 
,03-24 18:27:55.510  3251  3316 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 18:27:55.510  3251  3316 I jxcore-log: 
,03-24 18:27:55.520  3251  3316 I jxcore-log: # teardown,
03-24 18:27:55.520  3251  3316 I jxcore-log: 
,03-24 18:27:56.137  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:27:56.137  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:27:56.138  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 18:27:56.138  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:27:56.141  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:27:56.143  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:27:56.143  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:27:56.143  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:56.144  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:27:56.144  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 18:27:56.144  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:27:56.144  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:27:56.144  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 18:27:56.145  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 18:27:56.145  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:27:56.145  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 18:27:56.145  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:27:56.145  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:27:56.147  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:27:56.147  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 18:27:56.147  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-24 18:27:56.150  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:27:56.150  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:56.150  2162  2224 D BtGatt.GattService: current time is 267534851980
,03-24 18:27:56.151  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 68, -73, -126, -65, 49, 71, 1, -128, -78, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:27:56.151  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:27:56.152  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 18:27:56.154  3251  3316 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 18:27:56.154  3251  3316 I jxcore-log: 
03-24 18:27:56.155  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:27:56.155  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 18:27:56.155  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:27:56.155  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 18:27:56.156  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:27:56.156  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:27:56.156  3251  3726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:27:56.156  3251  3726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:27:56.156  3251  3726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:27:56.156  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:27:56.157  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:27:56.157  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:27:56.157  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:27:56.157  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:27:56.157  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 18:27:56.157  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:27:56.160  3251  3316 D BluetoothLeScanner: could not find callback wrapper
03-24 18:27:56.160  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:27:56.160  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:27:56.162  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:27:56.163  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:27:56.166  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:27:56.166  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:27:56.167  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 18:27:56.169  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:27:56.169  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:27:56.169  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 18:27:56.169  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:27:56.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:27:56.170  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:27:56.170  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 18:27:56.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:27:56.171  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:27:56.172  3251  3316 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 18:27:56.172  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:27:56.172  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:56.172  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:56.172  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:27:56.176  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:27:56.176  3251  3316 I jxcore-log: 
,03-24 18:27:56.179  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 18:27:56.180   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:56.185  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 18:27:56.187  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:27:56.187  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:27:56.190  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 18:27:56.190  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:27:56.190  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:56.190  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:27:56.191  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 18:27:56.192  3251  3316 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
03-24 18:27:56.192  3251  3316 I jxcore-log: 
,03-24 18:27:56.197  3251  3316 I jxcore-log: # setup
,03-24 18:27:56.197  3251  3316 I jxcore-log: 
,03-24 18:27:56.199  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:56.199  3251  3316 I jxcore-log: 
03-24 18:27:56.200  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:27:56.200  3251  3316 I jxcore-log: 
,03-24 18:27:56.318  3251  3316 I jxcore-log: # 38. Can connect to a remote peer
03-24 18:27:56.318  3251  3316 I jxcore-log: 
,03-24 18:27:56.462  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 32870, start advertisements: true
03-24 18:27:56.462  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:56.462  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:27:56.462  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:27:56.468  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 18:27:56.468  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 18:27:56.468  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:27:56.468  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:27:56.472  2162  2182 D BtGatt.GattService: registerClient() - UUID=4091ba30-2e94-4af6-9030-1121d914774f
03-24 18:27:56.472  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=4091ba30-2e94-4af6-9030-1121d914774f, clientIf=5
03-24 18:27:56.473  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:27:56.473  2162  2181 D BtGatt.GattService: start scan with filters
03-24 18:27:56.474  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:27:56.475  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:27:56.475  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:27:56.475  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:27:56.475  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:56.475  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:27:56.475  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:27:56.475  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:27:56.475  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:56.475  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:27:56.475  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:27:56.476  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:27:56.476  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:27:56.480  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:27:56.480  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:56.482  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:27:56.482  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:56.483  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:27:56.483  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:27:56.484  2162  2369 D BtGatt.GattService: registerClient() - UUID=a3ad11a0-a263-4f77-8042-9d65dce2547b
03-24 18:27:56.485  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=a3ad11a0-a263-4f77-8042-9d65dce2547b, clientIf=6
,03-24 18:27:56.485  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:27:56.487  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:27:56.487  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:56.487  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:27:56.489  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:27:56.489  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:27:56.491  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:27:56.495  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:27:56.500  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 18:27:56.500  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:27:56.501  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:27:56.502   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:27:56.506  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:27:56.506  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:27:56.506  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:27:56.506  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:27:56.507  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:27:56.508  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:27:56.508  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 18:27:56.508  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:27:56.508  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:27:56.508  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 18:27:56.509  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:27:56.509  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 18:27:56.509  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:27:56.509  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:27:56.509  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:27:56.509  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:56.510  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:27:56.510  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:27:56.510  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:27:56.510  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:27:56.510  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:27:56.512   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:27:56.513  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:56.513  3251  3316 I jxcore-log: 
03-24 18:27:56.514  3251  3729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:27:56.516  3251  3316 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
03-24 18:27:56.516  3251  3316 I jxcore-log: 
,03-24 18:27:56.520  3251  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:27:56.521  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 32870, start advertisements: false
,03-24 18:27:56.521  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:27:56.521  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 18:27:56.521  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:27:56.521  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:27:56.532  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:27:56.532  3251  3316 I jxcore-log: 
,03-24 18:27:56.538  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:27:56.538  3251  3316 I jxcore-log: 
,03-24 18:27:56.539  3251  3316 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-24 18:27:56.539  3251  3316 I jxcore-log: 
,03-24 18:27:57.506  2162  2162 D BtGatt.ScanManager: awakened up at time 268890
03-24 18:27:57.508  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:27:57.518  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 18:27:57.518  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:27:57.519  2162  2224 D BtGatt.GattService: current time is 268903195833
03-24 18:27:57.519  2162  2224 D BtGatt.GattService: Batch record : [-7, -27, 51, -25, -22, 64, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:27:57.520  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:27:57.521  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:27:57.524  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 18:27:57.524  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 18:27:57.525  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 18:27:57.526  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 18:27:57.530  3251  3316 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 18:27:57.530  3251  3316 I jxcore-log: 
,03-24 18:27:57.544  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 18:27:57.544  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:27:57.551  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
03-24 18:27:57.552  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-24 18:27:57.553  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 18:27:57.554  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-24 18:27:57.554  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 18:27:57.554  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 18:27:57.557  3251  3730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 353)
03-24 18:27:57.557  3251  3730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:27:57.559  3251  3316 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 18:27:57.559  3251  3316 I jxcore-log: 
,03-24 18:27:57.561  2162  2369 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 18:27:59.208  2162  2226 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 18:28:00.454  2162  2235 W bt-btif : No ag scb for peer addr
,03-24 18:28:00.482  2162  2235 W bt-btif : info:x10
03-24 18:28:00.482  2162  2224 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-24 18:28:00.482  2162  2224 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 18:28:00.515  2162  2235 W bt-sdp  : process_service_search_attr_rsp
,03-24 18:28:00.685  2162  2235 W bt-rfcomm: PORT_StartCnf failed result:5
,03-24 18:28:00.685  2162  2366 W bt-btif : invalid rfc slot id: 10
03-24 18:28:00.685  2162  2224 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-24 18:28:00.686  3251  3730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
03-24 18:28:00.687  3251  3730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 353)
03-24 18:28:00.687  3251  3730 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
03-24 18:28:00.688  3251  3251 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> E0:DB:10:14:E2:C0]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,03-24 18:28:00.689  3251  3251 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> E0:DB:10:14:E2:C0], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,03-24 18:28:00.689  2162  2224 E bt-btif : check_cod: remote_cod = 0x5a020c
03-24 18:28:00.689  2162  2224 I BluetoothBondStateMachine: No record of the device:null
03-24 18:28:00.689  2162  2224 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 9 Address: E0:DB:10:14:E2:C0 newState: 0
03-24 18:28:00.689  3251  3251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 18:28:00.689  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
03-24 18:28:00.690  2162  2225 E BluetoothBondStateMachine: In stable state, received invalid newState: 10
03-24 18:28:00.690  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,03-24 18:28:00.693  3251  3730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 353,
,03-24 18:28:00.693  3251  3730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 353,
03-24 18:28:00.694  3251  3730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 353)
03-24 18:28:00.695  3251  3731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 353
03-24 18:28:00.695  3251  3731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 353)
03-24 18:28:00.695  3251  3731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 353)
,03-24 18:28:00.699  3251  3316 I jxcore-log: INFO testThaliMobileNative: Connect returned an error: Connection to peer [<no peer name> E0:DB:10:14:E2:C0] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 18:28:00.699  3251  3316 I jxcore-log: 
,03-24 18:28:00.700  3251  3316 I jxcore-log: INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
03-24 18:28:00.700  3251  3316 I jxcore-log: 
,03-24 18:28:00.766  2162  2235 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-24 18:28:00.767  2162  2235 E bt-btm  : Device not in IRK list
,03-24 18:28:00.767  2162  2235 E bt-btif : Do not find the bg connection mask for the remote device
03-24 18:28:00.767  2162  2224 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 18:28:01.535  2162  2162 D BtGatt.ScanManager: awakened up at time 272919,
03-24 18:28:01.538  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:01.549  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-24 18:28:01.549  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:01.549  2162  2224 D BtGatt.GattService: current time is 272933608071
03-24 18:28:01.550  2162  2224 D BtGatt.GattService: Batch record : [-7, -27, 51, -25, -22, 64, 1, -128, -72, 27, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 27, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:28:01.550  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:28:01.551  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:01.554  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 18:28:01.555  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2,
,03-24 18:28:02.568  2162  2162 D BtGatt.ScanManager: awakened up at time 273952
,03-24 18:28:02.570  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:02.578  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 18:28:02.578  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:03.594  2162  2162 D BtGatt.ScanManager: awakened up at time 274977
,03-24 18:28:03.596  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:03.605  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 18:28:03.605  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:03.605  2162  2224 D BtGatt.GattService: current time is 274989699268
03-24 18:28:03.606  2162  2224 D BtGatt.GattService: Batch record : [-28, 4, -70, -71, 59, 93, 1, -128, -97, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -67, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 18:28:03.607  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:28:03.607  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:28:03.610  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 18:28:03.611  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 18:28:03.713  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 18:28:03.713  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:03.718  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-24 18:28:03.718  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
03-24 18:28:03.719  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 18:28:03.719  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
,03-24 18:28:03.719  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 18:28:03.719  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 18:28:03.722  3251  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 355)
03-24 18:28:03.723  3251  3733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
03-24 18:28:03.723  3251  3733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:28:03.728  2162  2369 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 18:28:04.487  2162  2235 W bt-btif : info:x10,
03-24 18:28:04.487  2162  2224 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-24 18:28:04.488  2162  2224 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 18:28:04.659  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcaeb4 rs_disc_pending=0
,03-24 18:28:04.660  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:04.660  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:04.717  2162  2235 W bt-sdp  : process_service_search_attr_rsp,
,03-24 18:28:04.837  2162  2224 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-24 18:28:04.846  2162  2224 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-24 18:28:04.847  2162  2224 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 18:28:04.850  2162  2225 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-24 18:28:04.851  2162  2225 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 18:28:04.897  2162  2224 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-24 18:28:04.897  2162  2225 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 18:28:04.932   822   856 I ActivityManager: Start proc 3734:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-24 18:28:04.935  2162  2225 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 18:28:04.956  2162  2225 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 18:28:04.997   822   860 D BluetoothManagerService: Message: 20
03-24 18:28:04.997   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38a04abe:true
,03-24 18:28:05.001   822  1427 I ActivityManager: Killing 2924:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 18:28:05.209   822  1427 E libprocessgroup: failed to kill 1 processes for processgroup 2924
,03-24 18:28:06.403  1263  1263 I art     : Explicit concurrent mark sweep GC freed 63031(3MB) AllocSpace objects, 7(688KB) LOS objects, 36% free, 28MB/44MB, paused 1.965ms total 58.873ms
,03-24 18:28:06.424  3365  3755 V GoogleAuthProtoRequest: [339] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 18:28:06.499  1263  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 18:28:06.499  1263  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:28:06.499  1263  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 18:28:06.499  1263  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:28:06.506  1263  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 18:28:06.525  3365  3755 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 18:28:06.569  2162  2162 D BtGatt.ScanManager: awakened up at time 277953
,03-24 18:28:06.570  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:06.572  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:06.572  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:10.489  2162  2222 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 18:28:11.575  2162  2162 D BtGatt.ScanManager: awakened up at time 282959
,03-24 18:28:11.576  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:11.580  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 18:28:11.580  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:11.580  2162  2224 D BtGatt.GattService: current time is 282964636818
03-24 18:28:11.580  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -72, 93, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:28:11.581  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:28:11.583  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 18:28:13.745  2162  2235 W bt-btif : new conn_srvc id:26, app_id:255
03-24 18:28:13.745  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 18:28:13.746  2162  2235 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 18:28:13.747  3251  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 18:28:13.750  3251  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 356)
03-24 18:28:13.751  2162  2235 W bt-btif : new conn_srvc id:26, app_id:1
03-24 18:28:13.751  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-24 18:28:13.751  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 18:28:13.752  3251  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 355)
03-24 18:28:13.752  3251  3758 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 356)
,03-24 18:28:13.752  2162  2235 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 18:28:13.752  3251  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 355)
03-24 18:28:13.752  3251  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 18:28:13.753  3251  3733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 357)
03-24 18:28:13.753  3251  3733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 357)
,03-24 18:28:13.754  3251  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 355)
,03-24 18:28:13.754   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:13.757  3251  3729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:13.759  3251  3759 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 357)
03-24 18:28:13.763  3251  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:13.780  3251  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 356),
,03-24 18:28:13.781  3251  3759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 357)
,03-24 18:28:13.783  3251  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:13.783  3251  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 356)
03-24 18:28:13.783  3251  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 356
,03-24 18:28:13.784  3251  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 356)
03-24 18:28:13.784  3251  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:13.784  3251  3759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:13.784  3251  3759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 355)
03-24 18:28:13.784  3251  3758 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 356)
03-24 18:28:13.785  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:13.785  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:13.785  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 18:28:13.786  3251  3759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 355),
,03-24 18:28:13.786  3251  3759 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 357),
,03-24 18:28:13.787  3251  3251 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings,
,03-24 18:28:13.788  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
,03-24 18:28:13.789  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-24 18:28:13.789  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:13.789  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:13.789  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:13.789  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:13.789  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:13.793  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:13.794  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:13.798  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:13.798  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:28:13.800  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:13.801  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:13.801  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:13.801  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:13.801  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:13.802  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 18:28:13.802  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:13.802  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:13.803  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:13.803  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:28:13.809  2162  2369 D BtGatt.GattService: registerClient() - UUID=ef1c9c06-18d1-4bf8-bb03-e0ebf68dd63a
,03-24 18:28:13.810  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=ef1c9c06-18d1-4bf8-bb03-e0ebf68dd63a, clientIf=6
,03-24 18:28:13.810  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:13.811  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:13.813  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:13.815  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:13.818  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:13.818  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:13.819  2162  2369 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:13.820  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:13.821  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:13.821  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.821  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:13.821  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 18:28:13.821  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:13.821  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:13.821  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:13.821  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:13.821  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:13.822  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:13.822  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.822  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:13.824  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 18:28:13.824  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.824  2162  2224 D BtGatt.GattService: current time is 285208771765
03-24 18:28:13.824  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -79, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, 4, -70, -71, 59, 93, 1, -128, -85, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:28:13.825  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:13.825  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:28:13.825  2162  2181 D BtGatt.GattService: registerClient() - UUID=74b878ab-60f2-4eda-a504-749e5ee4d6a2
,03-24 18:28:13.825  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=74b878ab-60f2-4eda-a504-749e5ee4d6a2, clientIf=5
03-24 18:28:13.826  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:13.826  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:28:13.827  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:13.827  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:13.829  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:28:13.830  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 18:28:13.833  2162  2234 D BtGatt.ScanManager: handling starting scan,
,03-24 18:28:13.834  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:13.834  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:13.835  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 18:28:13.836  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:13.836  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:13.836  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:13.836  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 18:28:13.836  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:13.836  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:13.836  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:13.837  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:13.837  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:13.838  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:13.837  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:13.838  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.838  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:13.838  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:13.838  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:13.840  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 18:28:13.840  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.841  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:13.841  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.842  2162  2369 D BtGatt.GattService: registerClient() - UUID=57ddb668-9906-445d-9e69-a7e57d4e8a2e
03-24 18:28:13.842  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=57ddb668-9906-445d-9e69-a7e57d4e8a2e, clientIf=6
,03-24 18:28:13.842  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:13.843  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:13.846  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:13.848  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:13.850  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:13.851  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:13.852  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:13.853  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:13.853  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:13.853  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:13.853  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:28:13.853  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:13.853  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:13.853  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:13.853  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.853  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:13.853  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:13.856  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:13.856  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:13.856  2162  2369 D BtGatt.GattService: registerClient() - UUID=ab1f3974-c9f4-4c08-828c-e0da44fe8a87
,03-24 18:28:13.856  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:13.857  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=ab1f3974-c9f4-4c08-828c-e0da44fe8a87, clientIf=5
03-24 18:28:13.857  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:13.857  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:28:13.857  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:13.857  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:13.859  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:13.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 18:28:13.863  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:13.864  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 18:28:13.865  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:28:13.865  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:13.865  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:13.867  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:13.867  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:13.867  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 18:28:13.867  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-24 18:28:13.867  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:13.867  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:13.867  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:13.867  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:13.867  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.868  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:13.868  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:13.868  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-24 18:28:13.869  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:13.869  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.869  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:13.869  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:13.871  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:13.871  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:13.871  2162  2181 D BtGatt.GattService: registerClient() - UUID=7c601dc1-d347-4919-8d09-7acc4f19921c
,03-24 18:28:13.871  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=7c601dc1-d347-4919-8d09-7acc4f19921c, clientIf=6
03-24 18:28:13.872  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:13.872  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:13.872  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.873  2162  2233 D BtGatt.AdvertiseManager: message : 0
03-24 18:28:13.875  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:13.878  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:13.880  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 18:28:13.881  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:13.882  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:13.883  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:28:13.883  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:13.883  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:28:13.883  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:13.883  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:13.883  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:13.883  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:13.884  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:13.884  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.884  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:28:13.885  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 18:28:13.885  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.886  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:13.886  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:13.886  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.887  2162  2369 D BtGatt.GattService: registerClient() - UUID=68a5648c-f3e9-485a-b10e-4b95fb708711
03-24 18:28:13.887  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=68a5648c-f3e9-485a-b10e-4b95fb708711, clientIf=5
03-24 18:28:13.887  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:13.888  2162  2181 D BtGatt.GattService: start scan with filters
,03-24 18:28:13.888  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:13.888  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:13.889  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 18:28:13.889  3251  3251 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 18:28:13.889  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:13.889  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:13.889  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:13.889  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:28:13.889  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:28:13.889  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:13.889  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:13.889  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 18:28:13.890  3251  3760 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 358)
,03-24 18:28:13.890  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 18:28:13.890  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,03-24 18:28:13.890  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
03-24 18:28:13.890  3251  3251 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 18:28:13.894  3251  3761 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 359)
,03-24 18:28:13.895  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:13.896  3251  3761 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57427
03-24 18:28:13.896  3251  3761 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-24 18:28:13.896  3251  3761 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 57427 (peer ID: E0:DB:10:14:E2:C0)
03-24 18:28:13.896  3251  3761 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 18:28:13.897  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:13.897  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:13.898  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:13.898  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.898  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:13.898  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:13.898  3251  3760 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 32870,
03-24 18:28:13.899  3251  3760 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 18:28:13.899  3251  3760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 18:28:13.899  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:13.899  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:13.900  3251  3760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 18:28:13.900  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:28:13.900  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:13.903  3251  3316 I jxcore-log: INFO testThaliMobileNative: ,
03-24 18:28:13.903  3251  3316 I jxcore-log: 
03-24 18:28:13.903  3251  3760 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 358)
,03-24 18:28:13.903  3251  3760 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 358)
03-24 18:28:13.903  3251  3763 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 360, name: Sender)
03-24 18:28:13.903  3251  3316 I jxcore-log: ok 163 Must have listeningPort
03-24 18:28:13.903  3251  3316 I jxcore-log: 
03-24 18:28:13.904  3251  3316 I jxcore-log: ok 164 listeningPort must be a number
03-24 18:28:13.904  3251  3316 I jxcore-log: 
,03-24 18:28:13.904  3251  3316 I jxcore-log: ok 165 Connection must have clientPort
03-24 18:28:13.904  3251  3316 I jxcore-log: 
03-24 18:28:13.905  3251  3316 I jxcore-log: ok 166 clientPort must be a number
03-24 18:28:13.905  3251  3316 I jxcore-log: 
03-24 18:28:13.905  3251  3764 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 361, name: Receiver)
03-24 18:28:13.905  3251  3316 I jxcore-log: ok 167 Connection must have serverPort
03-24 18:28:13.905  3251  3316 I jxcore-log: 
,03-24 18:28:13.905  3251  3316 I jxcore-log: ok 168 serverPort must be a number
03-24 18:28:13.905  3251  3316 I jxcore-log: 
03-24 18:28:13.906  3251  3316 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 18:28:13.906  3251  3316 I jxcore-log: 
,03-24 18:28:13.907  3251  3316 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-24 18:28:13.907  3251  3316 I jxcore-log: 
,03-24 18:28:13.912  3251  3316 I jxcore-log: # teardown
03-24 18:28:13.912  3251  3316 I jxcore-log: 
,03-24 18:28:14.125  2162  2366 W bt-btif : invalid rfc slot id: 11
,03-24 18:28:14.131  3251  3763 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 360, thread name: Sender)
,03-24 18:28:14.131  3251  3763 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 18:28:14.131  3251  3763 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-24 18:28:14.132  3251  3763 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 358
03-24 18:28:14.132  3251  3763 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
,03-24 18:28:14.132  3251  3763 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 18:28:14.132  3251  3763 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 18:28:14.132  3251  3763 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 361
03-24 18:28:14.133  3251  3763 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-24 18:28:14.133  3251  3763 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 360
03-24 18:28:14.133  3251  3764 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 361, thread name: Receiver): bt socket closed, read return: -1
,03-24 18:28:14.133  3251  3763 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 358)
03-24 18:28:14.134  3251  3763 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 358)
03-24 18:28:14.134  3251  3763 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-24 18:28:14.135  3251  3764 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 361, name: Receiver)
03-24 18:28:14.135  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:14.135  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:28:14.136  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 18:28:14.136  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:28:14.136  3251  3763 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 360, name: Sender)
03-24 18:28:14.140  2162  2369 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:28:14.142  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:28:14.144  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 18:28:14.144  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:14.144  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:14.144  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:28:14.144  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:14.145  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:14.146  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:28:14.147  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 18:28:14.147  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:14.147  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:14.147  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:28:14.147  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:28:14.149  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:14.149  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:14.150  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:14.154  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:28:14.154  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:14.154  2162  2224 D BtGatt.GattService: current time is 285538438119
,03-24 18:28:14.154  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -76, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, 4, -70, -71, 59, 93, 1, -128, -87, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:28:14.155  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:14.155  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 18:28:14.158  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 18:28:14.158  3251  3316 I jxcore-log: 
03-24 18:28:14.160  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 18:28:14.160  3251  3316 I jxcore-log: 
,03-24 18:28:14.162  3251  3316 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 18:28:14.162  3251  3316 I jxcore-log: 
,03-24 18:28:14.163  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 18:28:14.164  3251  3316 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:14.164  3251  3316 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 359)
03-24 18:28:14.164  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 359)
03-24 18:28:14.164  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 18:28:14.164  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 359),
03-24 18:28:14.164  3251  3316 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 359)
03-24 18:28:14.165  3251  3761 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 359)
03-24 18:28:14.166  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 18:28:14.166  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:28:14.166  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 18:28:14.166  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:28:14.167  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:28:14.167  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:28:14.167  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:14.167  3251  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 18:28:14.167  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:28:14.167  3251  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:28:14.167  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:14.167  3251  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:28:14.167  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:14.168  3251  3316 D BluetoothLeScanner: could not find callback wrapper
03-24 18:28:14.168  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 18:28:14.168  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:28:14.169  2162  2233 D BtGatt.AdvertiseManager: message : 1,
03-24 18:28:14.170  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:14.172  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 18:28:14.172  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:14.173  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:14.173  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:14.173  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:14.173  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:28:14.173  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 18:28:14.173  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:28:14.173  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:14.173  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:14.173  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:28:14.174  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:14.174  3251  3316 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 18:28:14.174  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:14.174  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:14.174  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:14.174  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:28:14.179  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:28:14.179  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:28:14.179  3251  3316 I jxcore-log: 
03-24 18:28:14.179   822  1340 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:14.184  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 18:28:14.185  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:14.185  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:14.188  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 18:28:14.188  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:28:14.188  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:14.188  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:14.188  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:14.188  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:14.189  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 18:28:14.191  3251  3316 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown,
03-24 18:28:14.191  3251  3316 I jxcore-log: 
,03-24 18:28:14.204  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 18:28:14.204  3251  3316 I jxcore-log: 
,03-24 18:28:14.206  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 18:28:14.206  3251  3316 I jxcore-log: 
,03-24 18:28:14.209  3251  3316 I jxcore-log: # setup,
03-24 18:28:14.209  3251  3316 I jxcore-log: 
,03-24 18:28:14.367  2162  2235 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND,
,03-24 18:28:14.367  2162  2235 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-24 18:28:14.587  3251  3316 I jxcore-log: # 39. Can shift large amounts of data,
03-24 18:28:14.587  3251  3316 I jxcore-log: 
,03-24 18:28:15.487  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 47139, start advertisements: true,
03-24 18:28:15.487  3251  3316 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setSca,nSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:15.487  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:15.487  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:15.487  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 18:28:15.492  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 18:28:15.492  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:15.492  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:15.493  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:15.503  2162  2182 D BtGatt.GattService: registerClient() - UUID=57980c0c-4f20-45dd-82d2-a8b39dc5c54d
03-24 18:28:15.503  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=57980c0c-4f20-45dd-82d2-a8b39dc5c54d, clientIf=5
,03-24 18:28:15.504  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:28:15.506  2162  2181 D BtGatt.GattService: start scan with filters
,03-24 18:28:15.508  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:15.508  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:15.508  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:15.508  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:28:15.508  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 18:28:15.508  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:15.508  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:15.508  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
,03-24 18:28:15.508  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 18:28:15.508  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:15.508  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:15.508  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:15.508  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:15.512  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:15.512  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 18:28:15.515  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:28:15.515  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:15.515  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:15.515  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 18:28:15.516  2162  2369 D BtGatt.GattService: registerClient() - UUID=df1e7659-5569-4463-8c10-8872255d3cde
,03-24 18:28:15.517  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=df1e7659-5569-4463-8c10-8872255d3cde, clientIf=6
03-24 18:28:15.517  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-24 18:28:15.518  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 18:28:15.518  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:15.519  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:15.519  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:15.519  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:15.538  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 18:28:15.539  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 18:28:15.542  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 18:28:15.542  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:15.542  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:15.542   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:15.544  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 18:28:15.544  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:15.544  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:28:15.544  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:15.545  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 18:28:15.545  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:28:15.545  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:28:15.545  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:28:15.545  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:15.545  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 18:28:15.546  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:15.546  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 18:28:15.546  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:28:15.546  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:28:15.546  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 18:28:15.546  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:15.546  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:15.546  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:15.546  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:15.546  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 18:28:15.546  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:15.547   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:15.548  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:15.548  3251  3316 I jxcore-log: 
03-24 18:28:15.548  3251  3765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:28:15.549  3251  3316 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 18:28:15.549  3251  3316 I jxcore-log: 
03-24 18:28:15.550  3251  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:15.552  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 47139, start advertisements: false
03-24 18:28:15.552  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 18:28:15.552  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 18:28:15.552  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:15.552  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:15.553  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:15.553  3251  3316 I jxcore-log: 
,03-24 18:28:15.554  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:28:15.554  3251  3316 I jxcore-log: 
,03-24 18:28:15.555  3251  3316 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error
03-24 18:28:15.555  3251  3316 I jxcore-log: 
,03-24 18:28:17.493  2162  2235 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 18:28:17.493  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 18:28:17.493  2162  2235 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 18:28:17.494  3251  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 18:28:17.495  3251  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 363)
03-24 18:28:17.496  3251  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 18:28:17.497   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:17.501  3251  3765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:28:17.502  3251  3766 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 363)
03-24 18:28:17.507  3251  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:17.708  3251  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 363)
,03-24 18:28:17.712  3251  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:17.713  3251  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 363),
03-24 18:28:17.713  3251  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 363
03-24 18:28:17.713  3251  3766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 363)
,03-24 18:28:17.713  3251  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:17.714  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:17.715  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:17.716  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 18:28:17.716  3251  3251 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 18:28:17.716  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 18:28:17.717  3251  3766 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 363)
03-24 18:28:17.718  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:17.718  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:17.718  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:17.718  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:17.718  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:17.718  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 18:28:17.723  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:28:17.724  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 18:28:17.730  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:17.730  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:17.732  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 18:28:17.734  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:17.734  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:28:17.734  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:17.734  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:17.734  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:17.735  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:17.737  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:17.737  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:17.737  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:28:17.748  2162  2181 D BtGatt.GattService: registerClient() - UUID=7469145f-f6d8-4dc5-bd4a-cf08c4e82c36
,03-24 18:28:17.748  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=7469145f-f6d8-4dc5-bd4a-cf08c4e82c36, clientIf=6
,03-24 18:28:17.750  3251  3266 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 18:28:17.752  2162  2233 D BtGatt.AdvertiseManager: message : 0,
,03-24 18:28:17.756  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:17.760  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:17.763  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 18:28:17.764  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:17.767  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:17.768  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:17.769  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:17.769  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-24 18:28:17.769  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:28:17.769  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:17.770  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:17.770  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:17.770  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.770  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 18:28:17.770  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:28:17.772  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:17.772  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.772  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:17.776  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:28:17.776  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.776  2162  2224 D BtGatt.GattService: current time is 289160679836
03-24 18:28:17.777  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -79, -35, 76, -33, 106, 72, 1, -128, -72, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 18:28:17.777  2162  2369 D BtGatt.GattService: registerClient() - UUID=32d26bc3-e32a-406f-bd6e-b29c00dfb401
03-24 18:28:17.777  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
,03-24 18:28:17.778  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:28:17.778  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=32d26bc3-e32a-406f-bd6e-b29c00dfb401, clientIf=5
03-24 18:28:17.779  3251  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 18:28:17.779  2162  2181 D BtGatt.GattService: start scan with filters
03-24 18:28:17.780  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:17.781  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 18:28:17.782  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:17.784  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:17.785  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:17.785  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.786  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:17.788  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:17.788  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.788  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 18:28:17.788  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:17.790  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:17.790  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:17.791  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:17.792  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:17.792  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 18:28:17.792  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:17.792  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:17.792  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-24 18:28:17.793  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:17.793  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:17.793  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.793  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:17.793  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 18:28:17.793  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:17.795  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:17.795  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.800  2162  2369 D BtGatt.GattService: registerClient() - UUID=785a5d88-1597-4210-bf48-85fba1573fd3
,03-24 18:28:17.801  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=785a5d88-1597-4210-bf48-85fba1573fd3, clientIf=6
03-24 18:28:17.801  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:17.802  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:17.806  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:17.810  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:17.812  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:17.812  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:17.814  2162  2369 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:17.815  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:17.816  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:17.816  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.816  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:17.816  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:17.816  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:17.816  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:17.817  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:17.817  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 18:28:17.817  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:17.820  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:17.820  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.820  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:17.821  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:17.821  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.823  2162  2181 D BtGatt.GattService: registerClient() - UUID=667cd62f-09bd-402c-b1fc-1fca27468785
03-24 18:28:17.823  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=667cd62f-09bd-402c-b1fc-1fca27468785, clientIf=5
,03-24 18:28:17.824  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:17.824  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:28:17.825  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:17.825  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 18:28:17.825  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0,
,03-24 18:28:17.826  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:17.826  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:17.826  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:17.826  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:17.826  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:17.826  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:17.827  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:17.829  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:17.829  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.830  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:17.831  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:28:17.831  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.831  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:17.831  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:17.831  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6,
03-24 18:28:17.833  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:17.833  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.835  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 18:28:17.835  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:28:17.836  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:17.837  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:17.837  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 18:28:17.837  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:17.837  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:17.837  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:17.838  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.838  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:17.838  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:17.838  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:17.838  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:17.838  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:28:17.843  2162  2181 D BtGatt.GattService: registerClient() - UUID=1ae629c6-7bf8-4ac0-8dc6-954afe4033dd
,03-24 18:28:17.843  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=1ae629c6-7bf8-4ac0-8dc6-954afe4033dd, clientIf=6
03-24 18:28:17.844  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 18:28:17.845  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:17.850  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 18:28:17.853  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:17.855  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:17.855  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:17.857  2162  2181 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:17.858  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:28:17.859  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:17.859  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.859  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:17.860  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:17.860  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:17.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:17.860  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:17.860  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 18:28:17.860  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:17.864  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:17.864  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.864  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:17.866  2162  2369 D BtGatt.GattService: registerClient() - UUID=357814d9-bf50-4859-afd1-1a9d7842ddc0
,03-24 18:28:17.866  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=357814d9-bf50-4859-afd1-1a9d7842ddc0, clientIf=5
,03-24 18:28:17.867  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 18:28:17.867  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.867  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:28:17.867  2162  2224 D BtGatt.GattService: current time is 289251250201
,03-24 18:28:17.867  2162  2224 D BtGatt.GattService: Batch record : [-79, -35, 76, -33, 106, 72, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 18:28:17.867  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-24 18:28:17.868  2162  2181 D BtGatt.GattService: start scan with filters,
03-24 18:28:17.868  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:17.868  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:17.869  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 18:28:17.869  3251  3251 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-24 18:28:17.869  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 18:28:17.869  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:28:17.869  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 18:28:17.869  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 18:28:17.869  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:28:17.869  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:28:17.870  3251  3767 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 364)
,03-24 18:28:17.872  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:17.873  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 18:28:17.874  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.875  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:28:17.875  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:17.876  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 18:28:17.876  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:17.876  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 18:28:17.877  3251  3316 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID E0:DB:10:14:E2:C0, but will connect anyway...
03-24 18:28:17.877  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:17.878  3251  3767 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47139
03-24 18:28:17.878  3251  3767 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 18:28:17.878  3251  3767 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 18:28:17.878  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:17.878  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.879  3251  3767 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 18:28:17.879  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:17.879  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:17.879  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 18:28:17.879  3251  3767 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 364)
03-24 18:28:17.880  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 18:28:17.880  3251  3767 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 364)
03-24 18:28:17.880  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 18:28:17.880  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
,03-24 18:28:17.880  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 18:28:17.880  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 18:28:17.884  3251  3769 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Sender)
03-24 18:28:17.884  3251  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 367)
03-24 18:28:17.884  3251  3771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:28:17.886  2162  2369 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 18:28:17.886  3251  3770 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Receiver)
,03-24 18:28:18.188  2162  2235 W bt-sdp  : process_service_search_attr_rsp
,03-24 18:28:18.675  2162  2235 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 18:28:18.675  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 18:28:18.675  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1,
03-24 18:28:18.675  2162  2235 W bt-btif : bta_dm_pm_ssr:2, lat:1200,
03-24 18:28:18.676  3251  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
03-24 18:28:18.677  3251  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 367)
03-24 18:28:18.678  3251  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 368)
03-24 18:28:18.678  3251  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 368)
,03-24 18:28:18.678  3251  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 367)
03-24 18:28:18.683  3251  3772 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 368)
,03-24 18:28:19.100  3251  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 368)
,03-24 18:28:19.104  3251  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0],
,03-24 18:28:19.104  3251  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
,03-24 18:28:19.105  3251  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367),
03-24 18:28:19.105  3251  3772 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 368)
03-24 18:28:19.105  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:19.105  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:19.106  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1,
03-24 18:28:19.107  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 18:28:19.107  3251  3251 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 18:28:19.109  3251  3773 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 369)
03-24 18:28:19.110  3251  3773 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56183
03-24 18:28:19.110  3251  3773 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 18:28:19.111  3251  3773 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 56183 (peer ID: E0:DB:10:14:E2:C0)
03-24 18:28:19.111  3251  3773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-24 18:28:19.116  3251  3316 I jxcore-log: INFO testThaliMobileNative: ,
03-24 18:28:19.116  3251  3316 I jxcore-log: 
,03-24 18:28:19.118  3251  3316 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 18:28:19.118  3251  3316 I jxcore-log: 
,03-24 18:28:19.124  3251  3773 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 56183
,03-24 18:28:19.124  3251  3773 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 18:28:19.125  3251  3773 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 18:28:19.125  3251  3773 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 18:28:19.125  3251  3773 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 369)
,03-24 18:28:19.126  3251  3773 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 369)
,03-24 18:28:19.128  3251  3774 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 370, name: Sender)
,03-24 18:28:19.129  3251  3775 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 371, name: Receiver)
,03-24 18:28:19.135  3251  3316 I jxcore-log: INFO testThaliMobileNative: forwardSend,
03-24 18:28:19.135  3251  3316 I jxcore-log: 
,03-24 18:28:19.269  3251  3316 I jxcore-log: INFO testThaliMobileNative: forwardData
,03-24 18:28:19.269  3251  3316 I jxcore-log: 
,03-24 18:28:19.316  3251  3316 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 18:28:19.316  3251  3316 I jxcore-log: 
,03-24 18:28:19.461  3251  3316 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 18:28:19.461  3251  3316 I jxcore-log: 
,03-24 18:28:19.469  3251  3316 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 18:28:19.469  3251  3316 I jxcore-log: 
,03-24 18:28:19.528  3251  3316 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 18:28:19.528  3251  3316 I jxcore-log: 
,03-24 18:28:19.530  3251  3316 I jxcore-log: ok 175 received should match sent forward
03-24 18:28:19.530  3251  3316 I jxcore-log: 
,03-24 18:28:19.545  3251  3316 I jxcore-log: # teardown
03-24 18:28:19.545  3251  3316 I jxcore-log: 
,03-24 18:28:22.588  3251  3769 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 365, thread name: Sender)
,03-24 18:28:22.588  3251  3769 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 18:28:22.589  3251  3769 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-24 18:28:22.589  3251  3769 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 364
03-24 18:28:22.589  3251  3769 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 364)
,03-24 18:28:22.589  3251  3769 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 18:28:22.589  3251  3769 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 18:28:22.589  3251  3769 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
,03-24 18:28:22.590  3251  3769 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-24 18:28:22.590  3251  3770 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
03-24 18:28:22.590  3251  3769 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-24 18:28:22.590  3251  3770 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Receiver)
03-24 18:28:22.590  3251  3769 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 364)
,03-24 18:28:22.591  3251  3769 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 364)
03-24 18:28:22.591  3251  3769 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 18:28:22.592  3251  3769 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Sender)
,03-24 18:28:22.598  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 18:28:22.598  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:28:22.598  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 18:28:22.598  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:28:22.600  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:28:22.601  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:22.602  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:22.602  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:28:22.602  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:28:22.602  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 18:28:22.602  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-24 18:28:22.602  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:22.602  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-24 18:28:22.603  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 18:28:22.603  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:22.605  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 18:28:22.605  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 18:28:22.605  3251  3316 I jxcore-log: 
03-24 18:28:22.605  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:22.605  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:22.605  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 18:28:22.605  3251  3316 I jxcore-log: 
03-24 18:28:22.607  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:22.607  3251  3316 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown,
03-24 18:28:22.607  3251  3316 I jxcore-log: 
03-24 18:28:22.607  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:22.607  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:22.608  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:28:22.608  3251  3316 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:22.608  3251  3316 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 369)
03-24 18:28:22.608  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 369)
03-24 18:28:22.608  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 18:28:22.608  3251  3316 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 18:28:22.608  3251  3316 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 371
03-24 18:28:22.608  3251  3316 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 18:28:22.608  3251  3316 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 370
03-24 18:28:22.608  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 369)
03-24 18:28:22.608  3251  3316 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 369)
03-24 18:28:22.608  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 18:28:22.608  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:28:22.609  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 18:28:22.609  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:28:22.609  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:28:22.609  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:28:22.609  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 18:28:22.609  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:28:22.609  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:22.609  3251  3774 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Sender): Socket closed
03-24 18:28:22.609  3251  3774 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 370, name: Sender)
03-24 18:28:22.609  3251  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:28:22.609  3251  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:28:22.609  3251  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:28:22.610  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:28:22.610  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:22.610  3251  3775 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Receiver): bt socket closed, read return: -1
03-24 18:28:22.610  2162  2224 D BtGatt.GattService: current time is 293994539053
03-24 18:28:22.610  3251  3775 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 371, name: Receiver)
,03-24 18:28:22.610  2162  2224 D BtGatt.GattService: Batch record : [-79, -35, 76, -33, 106, 72, 1, -128, -78, 61, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -72, 63, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:28:22.611  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:22.611  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 18:28:22.611  3251  3316 D BluetoothLeScanner: could not find callback wrapper
03-24 18:28:22.611  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:22.612  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:28:22.612  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:22.613  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:22.613  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:22.616  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:22.616  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:22.617  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:22.618  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:22.618  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-24 18:28:22.618  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:28:22.618  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:28:22.618  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:28:22.618  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:22.618  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:22.618  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:28:22.619  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:22.619  3251  3316 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 18:28:22.619  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:22.619  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:28:22.619  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:22.619  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:28:22.622  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:28:22.622  3251  3316 I jxcore-log: 
03-24 18:28:22.627  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 18:28:22.627   822  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:22.631  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:22.632  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 18:28:22.632  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 18:28:22.632  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:28:22.632  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:22.635  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 18:28:22.635  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:22.635  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:28:22.635  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:22.635  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 18:28:22.638  3251  3316 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown,
03-24 18:28:22.638  3251  3316 I jxcore-log: 
,03-24 18:28:22.647  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 18:28:22.647  3251  3316 I jxcore-log: 
,03-24 18:28:22.648  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:22.648  3251  3316 I jxcore-log: 
,03-24 18:28:22.650  3251  3316 I jxcore-log: # setup
03-24 18:28:22.650  3251  3316 I jxcore-log: 
,03-24 18:28:22.719  2162  2235 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND,
,03-24 18:28:22.720  2162  2235 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-24 18:28:22.735  2162  2235 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-24 18:28:22.959  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:22.959  3251  3316 I jxcore-log: 
,03-24 18:28:22.967  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 18:28:22.967  3251  3316 I jxcore-log: 
,03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:22.976  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:22.980  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:22.983  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:22.983  3251  3316 I jxcore-log: 
,03-24 18:28:22.987  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:22.987  3251  3316 I jxcore-log: 
,03-24 18:28:22.993  3251  3316 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-24 18:28:22.993  3251  3316 I jxcore-log: 
,03-24 18:28:22.998  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:22.998  3251  3316 I jxcore-log: 
,03-24 18:28:25.967  3251  3316 I jxcore-log: ok 178 specific error should be returned
03-24 18:28:25.967  3251  3316 I jxcore-log: 
,03-24 18:28:25.969  3251  3316 I jxcore-log: # teardown
03-24 18:28:25.969  3251  3316 I jxcore-log: 
,03-24 18:28:26.064  3251  3316 I jxcore-log: # setup
03-24 18:28:26.064  3251  3316 I jxcore-log: 
,03-24 18:28:26.530  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:26.530  3251  3316 I jxcore-log: 
,03-24 18:28:26.534  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:26.534  3251  3316 I jxcore-log: 
,03-24 18:28:26.543  2162  2235 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:26.547  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 18:28:26.549  2162  2162 D BluetoothMapService: onReceive
,03-24 18:28:26.558  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:26.564  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:26.564  3251  3316 I jxcore-log: 
,03-24 18:28:26.568  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:26.568  3251  3316 I jxcore-log: 
03-24 18:28:26.571  3251  3316 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
03-24 18:28:26.571  3251  3316 I jxcore-log: 
,03-24 18:28:26.573  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:26.573  3251  3316 I jxcore-log: 
,03-24 18:28:26.618   822  1282 I ActivityManager: Start proc 3777:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-24 18:28:26.765   822   860 D BluetoothManagerService: Message: 20
03-24 18:28:26.765   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75de69c:true
,03-24 18:28:26.779  3777  3777 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 18:28:26.977   822  1282 I ActivityManager: Start proc 3803:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-24 18:28:26.986  3777  3777 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 18:28:26.991   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 330us total 14.435ms
,03-24 18:28:26.995   822  1371 I ActivityManager: Killing 3465:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 18:28:27.006   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 331us total 13.924ms
,03-24 18:28:27.019   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 13.061ms
,03-24 18:28:27.101   822  1371 I ActivityManager: Killing 3394:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,03-24 18:28:27.188  3251  3316 I jxcore-log: ok 179 specific error should be returned
03-24 18:28:27.188  3251  3316 I jxcore-log: 
,03-24 18:28:27.190  3251  3316 I jxcore-log: # teardown
03-24 18:28:27.190  3251  3316 I jxcore-log: 
,03-24 18:28:27.302  3251  3316 I jxcore-log: # setup
03-24 18:28:27.302  3251  3316 I jxcore-log: 
,03-24 18:28:27.809  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:27.809  3251  3316 I jxcore-log: 
,03-24 18:28:27.813  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:27.813  3251  3316 I jxcore-log: 
,03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:27.825  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:27.830  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:27.834  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:27.834  3251  3316 I jxcore-log: 
,03-24 18:28:27.838  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 18:28:27.838  3251  3316 I jxcore-log: 
,03-24 18:28:27.843  3251  3316 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
,03-24 18:28:27.843  3251  3316 I jxcore-log: 
,03-24 18:28:27.847  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:27.847  3251  3316 I jxcore-log: 
,03-24 18:28:28.734  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:28.734  3251  3316 I jxcore-log: 
,03-24 18:28:28.737  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 60687
03-24 18:28:28.737  3251  3316 I jxcore-log: 
,03-24 18:28:28.738  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:28.739  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:28:28.739  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:28.741  3251  3316 I jxcore-log: ok 180 no errors
03-24 18:28:28.741  3251  3316 I jxcore-log: 
03-24 18:28:28.742  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:28.742  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:28:28.742  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:28.745  3251  3316 I jxcore-log: ok 181 still no errors
03-24 18:28:28.745  3251  3316 I jxcore-log: 
,03-24 18:28:28.752  3251  3316 I jxcore-log: # teardown
03-24 18:28:28.752  3251  3316 I jxcore-log: 
,03-24 18:28:28.899  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:28.899  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 18:28:28.899  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:28.904  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:28.904  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:28.904  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:28.915  3251  3316 I jxcore-log: # setup
03-24 18:28:28.915  3251  3316 I jxcore-log: 
,03-24 18:28:29.065  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:29.065  3251  3316 I jxcore-log: 
,03-24 18:28:29.068  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:29.068  3251  3316 I jxcore-log: 
,03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:29.077  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 18:28:29.080  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:29.081  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:29.081  3251  3316 I jxcore-log: 
,03-24 18:28:29.083  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:29.083  3251  3316 I jxcore-log: 
,03-24 18:28:29.086  3251  3316 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
03-24 18:28:29.086  3251  3316 I jxcore-log: 
03-24 18:28:29.088  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:29.088  3251  3316 I jxcore-log: 
,03-24 18:28:29.357  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:29.357  3251  3316 I jxcore-log: 
,03-24 18:28:29.359  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 45195
03-24 18:28:29.359  3251  3316 I jxcore-log: 
,03-24 18:28:29.365  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 47139, start advertisements: false,
03-24 18:28:29.365  3251  3316 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2,
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false,
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:29.365  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:29.365  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 18:28:29.366  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:29.366  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 18:28:29.373  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:29.373  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:29.373  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:29.383  2162  2182 D BtGatt.GattService: registerClient() - UUID=55ea0cad-68f5-40f9-924f-02b5719b9b50
,03-24 18:28:29.384  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=55ea0cad-68f5-40f9-924f-02b5719b9b50, clientIf=5
03-24 18:28:29.384  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:29.384  2162  2369 D BtGatt.GattService: start scan with filters
03-24 18:28:29.385  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:29.385  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:29.385  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:29.385  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:28:29.386  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:29.386  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:29.387  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:29.387  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 18:28:29.390   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:29.393  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:29.393  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:29.395  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:29.395  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:29.396  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:29.396  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:29.398  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:29.398  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:29.399  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:29.399  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:28:29.400  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:29.400  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:29.400  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:29.400  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:29.400  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:29.400  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:28:29.403  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:29.403  3251  3316 I jxcore-log: 
,03-24 18:28:29.404  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:29.404  3251  3316 I jxcore-log: 
,03-24 18:28:29.406  3251  3316 I jxcore-log: ok 182 no errors
03-24 18:28:29.406  3251  3316 I jxcore-log: 
,03-24 18:28:29.411  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 47139, start advertisements: false
,03-24 18:28:29.411  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:29.411  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:29.411  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:29.412  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:29.416  3251  3316 I jxcore-log: ok 183 still no errors
03-24 18:28:29.416  3251  3316 I jxcore-log: 
,03-24 18:28:29.427  3251  3316 I jxcore-log: # teardown
03-24 18:28:29.427  3251  3316 I jxcore-log: 
,03-24 18:28:29.844  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:29.844  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:29.844  3251  3316 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 18:28:29.845  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 18:28:29.845  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:29.845  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:28:29.845  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 18:28:29.845  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 18:28:29.845  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:28:29.850  2162  2369 D BtGatt.GattService: stopScan() - queue size =1,
03-24 18:28:29.852  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:29.853  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 18:28:29.853  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:29.853  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 18:28:29.854  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 18:28:29.854  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
03-24 18:28:29.854  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:28:29.855  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 18:28:29.855  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:29.856  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:29.858  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:29.859  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 18:28:29.859  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:29.859  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:29.860  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:28:29.860  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:29.862  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:29.862  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:29.862  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:29.862  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:28:29.863  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:28:29.863  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:29.863  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:28:29.879  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:28:29.880   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 18:28:29.891  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 18:28:29.893  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 18:28:29.893  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:29.899  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-24 18:28:29.899  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 18:28:29.899  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:29.900  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:28:29.902  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:28:29.903  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:29.903  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:29.905  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:29.905  3251  3316 I jxcore-log: 
,03-24 18:28:29.907  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:29.907  3251  3316 I jxcore-log: 
,03-24 18:28:29.928  3251  3316 I jxcore-log: # setup
03-24 18:28:29.928  3251  3316 I jxcore-log: 
,03-24 18:28:30.083  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-24 18:28:30.083  3251  3316 I jxcore-log: 
,03-24 18:28:30.087  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:30.087  3251  3316 I jxcore-log: 
,03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:30.097  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:30.100  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:30.103  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 18:28:30.103  3251  3316 I jxcore-log: 
,03-24 18:28:30.107  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 18:28:30.107  3251  3316 I jxcore-log: 
,03-24 18:28:30.114  3251  3316 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
,03-24 18:28:30.114  3251  3316 I jxcore-log: 
,03-24 18:28:30.117  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 18:28:30.117  3251  3316 I jxcore-log: 
,03-24 18:28:30.255  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:30.255  3251  3316 I jxcore-log: 
03-24 18:28:30.257  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 46708
03-24 18:28:30.257  3251  3316 I jxcore-log: 
,03-24 18:28:30.264  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 46708, start advertisements: true
03-24 18:28:30.265  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 18:28:30.265  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:30.265  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:28:30.275  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 18:28:30.275  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:30.275  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 18:28:30.275  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:30.279  2162  2182 D BtGatt.GattService: registerClient() - UUID=4ef1b748-6611-417a-a275-d81650959c5b
,03-24 18:28:30.280  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=4ef1b748-6611-417a-a275-d81650959c5b, clientIf=5
03-24 18:28:30.280  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:30.281  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:28:30.281  2162  2234 D BtGatt.ScanManager: handling starting scan,
03-24 18:28:30.284  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:30.284  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:30.284  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:30.284  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 18:28:30.284  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:30.285  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:30.285  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:30.285  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:30.285  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:30.286  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:30.286  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:30.286  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:30.286  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:30.286  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:30.289  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:30.289  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:30.289  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:30.289  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:30.290  2162  2181 D BtGatt.GattService: registerClient() - UUID=dae9aec2-5046-4281-a21b-5bfc42d3c4f7
03-24 18:28:30.290  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=dae9aec2-5046-4281-a21b-5bfc42d3c4f7, clientIf=6
03-24 18:28:30.291  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 18:28:30.292  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:30.292  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:30.293  2162  2233 D BtGatt.AdvertiseManager: message : 0
03-24 18:28:30.293  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:28:30.293  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:30.295  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:30.298  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:30.300  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:30.301  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:30.301  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:30.301   822   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:30.304  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:28:30.304  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:30.304  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:28:30.304  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:30.305  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 18:28:30.306  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:28:30.306  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-24 18:28:30.306  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:28:30.306  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:30.307  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:30.307   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 18:28:30.307  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:30.307  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:28:30.307  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:28:30.307  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:28:30.307  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:30.307  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 18:28:30.307  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:30.307  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:30.307  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-24 18:28:30.307  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:30.306  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:30.308  3251  3823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:30.310  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:30.310  3251  3316 I jxcore-log: 
03-24 18:28:30.311  3251  3823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:30.313  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:30.313  3251  3316 I jxcore-log: 
,03-24 18:28:30.314  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:28:30.314  3251  3316 I jxcore-log: 
03-24 18:28:30.315  3251  3316 I jxcore-log: ok 184 no errors
03-24 18:28:30.315  3251  3316 I jxcore-log: 
,03-24 18:28:30.326  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 46708, start advertisements: true
03-24 18:28:30.327  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:30.327  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:30.327  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:30.327  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:30.329  3251  3316 I jxcore-log: ok 185 still no errors
03-24 18:28:30.329  3251  3316 I jxcore-log: 
03-24 18:28:30.334  3251  3316 I jxcore-log: # teardown
03-24 18:28:30.334  3251  3316 I jxcore-log: 
,03-24 18:28:30.474  1263  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 18:28:30.474  1263  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 18:28:30.474  1263  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:28:30.474  1263  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:28:30.487  1263  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:28:30.521  3088  3825 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 18:28:30.521  3088  3825 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jdm.a(PG:82)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jcs.o(PG:406)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jcn.a(PG:1379)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jcs.i(PG:143)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at blb.a(PG:3937)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at czp.a(PG:18188)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at czp.a(PG:9081)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at czq.run(PG:1686)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:28:30.521  3088  3825 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jdj.a(PG:4091)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jdj.a(PG:1125)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jdm.a(PG:77)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	... 12 more
03-24 18:28:30.521  3088  3825 E HttpOperation: Caused by: faj: BadAuthentication
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at fal.a(PG:38)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	at jdj.a(PG:4089)
03-24 18:28:30.521  3088  3825 E HttpOperation: 	... 14 more
,03-24 18:28:30.606  1263  1281 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 18:28:30.606  1263  1281 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 18:28:30.606  1263  1281 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 18:28:30.606  1263  1281 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:28:30.614  1263  1281 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:28:30.641  3088  3825 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 18:28:30.641  3088  3825 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jdm.a(PG:82)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jcs.o(PG:406)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jcn.a(PG:1379)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jcs.i(PG:143)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at hec.a(PG:42)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at hee.a(PG:102)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at czr.a(PG:65)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at kka.a(PG:108)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at czp.a(PG:19176)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at czp.a(PG:9081)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at czq.run(PG:1686)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:28:30.641  3088  3825 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jdj.a(PG:4091)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jdj.a(PG:1125)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jdm.a(PG:77)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	... 15 more
03-24 18:28:30.641  3088  3825 E HttpOperation: Caused by: faj: BadAuthentication
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at fal.a(PG:38)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	at jdj.a(PG:4089)
03-24 18:28:30.641  3088  3825 E HttpOperation: 	... 17 more
,03-24 18:28:30.641  3088  3825 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 18:28:30.641  3088  3825 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at hec.a(PG:42)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at hee.a(PG:102)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at czr.a(PG:65)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at kka.a(PG:108)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	,at czp.a(PG:19176)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: ,	at jdm.a(PG:77)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	... 15 more
03-24 18:28:30.641  3088  3825 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at fal.a(PG:38)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 18:28:30.641  3088  3825 E ExperimentLoader: 	... 17 more
,03-24 18:28:30.762   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 301632, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:28:30.796  2162  2162 D BtGatt.ScanManager: awakened up at time 302180
03-24 18:28:30.798  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:30.808  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 18:28:30.808  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 18:28:30.808  2162  2224 D BtGatt.GattService: current time is 302192721654,
03-24 18:28:30.809  2162  2224 D BtGatt.GattService: Batch record : [-49, 34, -56, -28, 59, 109, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:28:30.809  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 18:28:30.810  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:30.814  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 18:28:30.815  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2,
03-24 18:28:30.816  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 18:28:30.818  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 18:28:30.826  3251  3316 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 18:28:30.826  3251  3316 I jxcore-log: 
,03-24 18:28:30.838  3251  3316 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 18:28:30.838  3251  3316 I jxcore-log: 
,03-24 18:28:30.841  3251  3316 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 18:28:30.841  3251  3316 I jxcore-log: 
,03-24 18:28:30.844  3251  3316 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 18:28:30.844  3251  3316 I jxcore-log: 
,03-24 18:28:30.944  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:30.944  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 18:28:30.944  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 18:28:30.944  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:28:30.945  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:28:30.946  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 18:28:30.946  3251  3823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 18:28:30.946  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:28:30.946  3251  3823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:28:30.946  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:30.946  3251  3823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:28:30.946  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-24 18:28:30.946  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:30.947  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:30.947  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 18:28:30.947  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 18:28:30.947  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:28:30.951  2162  2369 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:28:30.953  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:30.954  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:30.955  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:30.955  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:30.955  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 18:28:30.955  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:28:30.955  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:30.955  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:28:30.957  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 18:28:30.957  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:30.957  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:28:30.958  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:30.959  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:30.959  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:30.959  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:30.959  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:30.962  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:30.962  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:30.963  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:30.963  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:30.963  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:30.963  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:28:30.963  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:28:30.963  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 18:28:30.964  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:30.964  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:30.964  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:28:30.964  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 18:28:30.964  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:30.964  2162  2224 D BtGatt.GattService: current time is 302348729623
03-24 18:28:30.964  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:28:30.965  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:30.968  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 18:28:30.968  3251  3316 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 18:28:30.968  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:30.968  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:28:30.969  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:30.969  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 18:28:30.977  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:28:30.978   822  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:30.982  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 18:28:30.983  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:30.983  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:30.986  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 18:28:30.986  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:30.986  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 18:28:30.986  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:30.986  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:30.986  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-24 18:28:30.987  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:28:30.987  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:30.987  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:30.989  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:28:30.989  3251  3316 I jxcore-log: 
03-24 18:28:30.990  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:30.990  3251  3316 I jxcore-log: 
,03-24 18:28:30.990  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:30.990  3251  3316 I jxcore-log: 
,03-24 18:28:31.001  3251  3316 I jxcore-log: # setup
,03-24 18:28:31.001  3251  3316 I jxcore-log: 
,03-24 18:28:31.154  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:31.154  3251  3316 I jxcore-log: 
,03-24 18:28:31.157  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:31.157  3251  3316 I jxcore-log: ,
,03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:31.164  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:31.166  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:31.168  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:31.168  3251  3316 I jxcore-log: 
03-24 18:28:31.170  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:31.170  3251  3316 I jxcore-log: 
,03-24 18:28:31.173  3251  3316 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times
03-24 18:28:31.173  3251  3316 I jxcore-log: 
03-24 18:28:31.175  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:31.175  3251  3316 I jxcore-log: 
,03-24 18:28:31.316  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:31.316  3251  3316 I jxcore-log: 
,03-24 18:28:31.319  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 40687
03-24 18:28:31.319  3251  3316 I jxcore-log: 
,03-24 18:28:31.321  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 18:28:31.321  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:31.321  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:31.324  3251  3316 I jxcore-log: ok 186 no errors,
03-24 18:28:31.324  3251  3316 I jxcore-log: 
03-24 18:28:31.325  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:28:31.325  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:31.325  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:31.327  3251  3316 I jxcore-log: ok 187 still no errors
03-24 18:28:31.327  3251  3316 I jxcore-log: 
,03-24 18:28:31.333  3251  3316 I jxcore-log: # teardown
03-24 18:28:31.333  3251  3316 I jxcore-log: 
,03-24 18:28:31.431  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:31.431  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:31.431  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:31.435  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:28:31.437  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:31.437  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:31.446  3251  3316 I jxcore-log: # setup
03-24 18:28:31.446  3251  3316 I jxcore-log: 
,03-24 18:28:31.574  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 18:28:31.574  3251  3316 I jxcore-log: 
,03-24 18:28:31.577  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 18:28:31.577  3251  3316 I jxcore-log: 
,03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
,03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:31.582  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 18:28:31.585  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:31.587  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:31.587  3251  3316 I jxcore-log: 
03-24 18:28:31.588  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:31.588  3251  3316 I jxcore-log: ,
,03-24 18:28:31.592  3251  3316 I jxcore-log: # 46. can get the network status before starting
03-24 18:28:31.592  3251  3316 I jxcore-log: 
03-24 18:28:31.593  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:31.593  3251  3316 I jxcore-log: 
,03-24 18:28:31.783  3251  3316 I jxcore-log: ok 188 network status should have certain non-empty properties
03-24 18:28:31.783  3251  3316 I jxcore-log: 
,03-24 18:28:31.791  3251  3316 I jxcore-log: # teardown
03-24 18:28:31.791  3251  3316 I jxcore-log: 
,03-24 18:28:31.991  3251  3316 I jxcore-log: # setup
03-24 18:28:31.991  3251  3316 I jxcore-log: 
,03-24 18:28:32.228  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:32.228  3251  3316 I jxcore-log: 
,03-24 18:28:32.232  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:32.232  3251  3316 I jxcore-log: 
,03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:32.244  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:32.247  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:32.248  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:32.248  3251  3316 I jxcore-log: 
,03-24 18:28:32.252  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:32.252  3251  3316 I jxcore-log: 
,03-24 18:28:32.255  3251  3316 I jxcore-log: # 47. error returned with bad router
03-24 18:28:32.255  3251  3316 I jxcore-log: 
,03-24 18:28:32.258  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:32.258  3251  3316 I jxcore-log: 
,03-24 18:28:32.441  3251  3316 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 18:28:32.441  3251  3316 I jxcore-log: 
,03-24 18:28:32.443  3251  3316 I jxcore-log: ok 189 specific error expected
03-24 18:28:32.443  3251  3316 I jxcore-log: 
03-24 18:28:32.445  3251  3316 I jxcore-log: # teardown
03-24 18:28:32.445  3251  3316 I jxcore-log: 
,03-24 18:28:32.572  3251  3316 I jxcore-log: # setup
03-24 18:28:32.572  3251  3316 I jxcore-log: 
,03-24 18:28:32.727  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:32.727  3251  3316 I jxcore-log: 
,03-24 18:28:32.731  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:32.731  3251  3316 I jxcore-log: 
,03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:32.742  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:32.745  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:32.747  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:32.747  3251  3316 I jxcore-log: 
,03-24 18:28:32.749  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:32.749  3251  3316 I jxcore-log: 
,03-24 18:28:32.752  3251  3316 I jxcore-log: # 48. all services are stopped when we call stop
03-24 18:28:32.752  3251  3316 I jxcore-log: 
,03-24 18:28:32.754  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:32.754  3251  3316 I jxcore-log: 
,03-24 18:28:32.922  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:32.922  3251  3316 I jxcore-log: 
,03-24 18:28:32.925  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 53590
03-24 18:28:32.925  3251  3316 I jxcore-log: 
,03-24 18:28:32.931  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 46708, start advertisements: false
,03-24 18:28:32.931  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:32.931  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:32.931  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:28:32.935  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 18:28:32.935  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:32.935  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:32.940  2162  2181 D BtGatt.GattService: registerClient() - UUID=cea96777-9c84-49ca-8d54-e828c0f645fb
,03-24 18:28:32.940  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=cea96777-9c84-49ca-8d54-e828c0f645fb, clientIf=5
03-24 18:28:32.941  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:28:32.941  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:28:32.943  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:32.943  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:32.943  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:32.943  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:32.943  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:28:32.943  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:32.944  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:32.944  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:32.944   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:32.947  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 18:28:32.947  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:32.947  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:32.947  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:32.947  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:32.948  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:32.950  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:32.950  3251  3316 I jxcore-log: 
03-24 18:28:32.951  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:32.951  3251  3316 I jxcore-log: 
03-24 18:28:32.952  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:32.952  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:32.956  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:32.956  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:32.956  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:32.956  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:32.959  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53590, start advertisements: true
03-24 18:28:32.959  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 18:28:32.959  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:32.959  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 18:28:32.960  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:32.960  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:32.962  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:32.962  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:32.966  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 18:28:32.966  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 18:28:32.966  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 18:28:32.967  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:32.967  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:32.967  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:32.967  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:32.968  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:28:32.973  2162  2182 D BtGatt.GattService: registerClient() - UUID=7c1c5f4e-3951-40ac-b778-5a38e6d9658c
,03-24 18:28:32.974  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=7c1c5f4e-3951-40ac-b778-5a38e6d9658c, clientIf=6
03-24 18:28:32.974  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 18:28:32.977  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:32.983  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:32.987  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:32.990  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:32.991  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:32.992  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-24 18:28:32.992  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:32.992  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:32.992  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:28:32.992  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:28:32.992  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:28:32.993   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:33.000  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:28:33.000  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:33.000  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:33.000  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 18:28:33.001  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:33.002  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:28:33.002  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:28:33.002  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 18:28:33.002  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:28:33.003  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:33.003  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:33.003  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:28:33.004  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:33.008   822  1114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:33.008  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:28:33.008  3251  3316 I jxcore-log: 
,03-24 18:28:33.012  3251  3828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:28:33.017  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:28:33.017  3251  3316 I jxcore-log: 
,03-24 18:28:33.019  3251  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 18:28:33.019  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:28:33.019  3251  3316 I jxcore-log: 
,03-24 18:28:33.021  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:28:33.021  3251  3316 I jxcore-log: 
,03-24 18:28:33.025  3251  3316 I jxcore-log: ok 190 connection to servers manager should succeed after starting
03-24 18:28:33.025  3251  3316 I jxcore-log: 
,03-24 18:28:33.034  3251  3316 I jxcore-log: ok 191 connection to router server should succeed after starting
03-24 18:28:33.034  3251  3316 I jxcore-log: 
,03-24 18:28:33.036  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:33.036  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 18:28:33.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:28:33.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:28:33.036  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 18:28:33.037  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:28:33.037  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:28:33.037  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:33.037  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 18:28:33.037  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:33.037  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:33.037  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:28:33.037  3251  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 18:28:33.037  3251  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:28:33.037  3251  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:28:33.039  2162  2369 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:33.040  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:33.040  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:33.041  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:33.041  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 18:28:33.041  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:28:33.041  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 18:28:33.041  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:33.041  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:28:33.041  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 18:28:33.041  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:33.042  2162  2234 D BtGatt.ScanManager: stopping BLe Batch,
03-24 18:28:33.043  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:28:33.044  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:33.045  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:33.045  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:33.046  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:33.047  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:33.047  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:33.048  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 18:28:33.049  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:33.049  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:33.049  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 18:28:33.049  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:28:33.049  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:28:33.050  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:33.050  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:33.050  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:28:33.051  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:33.051  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:33.052  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:28:33.052  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:33.052  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:28:33.053  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 18:28:33.053  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:33.053  2162  2224 D BtGatt.GattService: current time is 304437144830
03-24 18:28:33.053  2162  2224 D BtGatt.GattService: Batch record : [108, 32, 89, 28, 68, 91, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:28:33.053  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:28:33.058  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:28:33.058   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:33.063  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 18:28:33.063  3251  3316 I jxcore-log: 
,03-24 18:28:33.063  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:33.063  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:33.063  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:33.066  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 18:28:33.066  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:28:33.066  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 18:28:33.066  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:33.066  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:33.067  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 18:28:33.067  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:33.067  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 18:28:33.072  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:28:33.072  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:33.072  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:33.074  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:28:33.074  3251  3316 I jxcore-log: 
,03-24 18:28:33.076  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:33.076  3251  3316 I jxcore-log: 
,03-24 18:28:33.078  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:33.078  3251  3316 I jxcore-log: 
,03-24 18:28:33.082  3251  3316 I jxcore-log: ok 192 is stopped after calling stop
03-24 18:28:33.082  3251  3316 I jxcore-log: 
,03-24 18:28:33.088  3251  3316 I jxcore-log: ok 193 connection to servers manager should fail after stopping
03-24 18:28:33.088  3251  3316 I jxcore-log: 
,03-24 18:28:33.093  3251  3316 I jxcore-log: ok 194 connection to router server should fail after stopping
03-24 18:28:33.093  3251  3316 I jxcore-log: 
,03-24 18:28:33.099  3251  3316 I jxcore-log: # teardown
03-24 18:28:33.099  3251  3316 I jxcore-log: 
,03-24 18:28:33.357  3251  3316 I jxcore-log: # setup
03-24 18:28:33.357  3251  3316 I jxcore-log: 
,03-24 18:28:33.540  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:33.540  3251  3316 I jxcore-log: 
,03-24 18:28:33.544  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:33.544  3251  3316 I jxcore-log: 
,03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:33.557  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:33.561  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:33.563  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:33.563  3251  3316 I jxcore-log: 
,03-24 18:28:33.564  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:33.564  3251  3316 I jxcore-log: 
,03-24 18:28:33.567  3251  3316 I jxcore-log: # 49. make sure terminateConnection is properly hooked up
03-24 18:28:33.567  3251  3316 I jxcore-log: 
,03-24 18:28:33.569  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:33.569  3251  3316 I jxcore-log: 
,03-24 18:28:33.714  3251  3316 I jxcore-log: ok 195 called with right arguments
,03-24 18:28:33.714  3251  3316 I jxcore-log: 
,03-24 18:28:33.718  3251  3316 I jxcore-log: # teardown
03-24 18:28:33.718  3251  3316 I jxcore-log: 
,03-24 18:28:33.854  3251  3316 I jxcore-log: # setup
03-24 18:28:33.854  3251  3316 I jxcore-log: 
,03-24 18:28:34.015  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:34.015  3251  3316 I jxcore-log: 
,03-24 18:28:34.018  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:34.018  3251  3316 I jxcore-log: 
,03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:34.026  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:34.029  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:34.032  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:34.032  3251  3316 I jxcore-log: 
,03-24 18:28:34.033  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:34.033  3251  3316 I jxcore-log: 
,03-24 18:28:34.043  3251  3316 I jxcore-log: # 50. make sure terminateListener is properly hooked up
03-24 18:28:34.043  3251  3316 I jxcore-log: 
,03-24 18:28:34.044  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:34.044  3251  3316 I jxcore-log: 
,03-24 18:28:34.178  3251  3316 I jxcore-log: ok 196 called with right arguments
03-24 18:28:34.178  3251  3316 I jxcore-log: 
,03-24 18:28:34.180  3251  3316 I jxcore-log: # teardown
03-24 18:28:34.180  3251  3316 I jxcore-log: 
,03-24 18:28:34.360  3251  3316 I jxcore-log: # setup
03-24 18:28:34.360  3251  3316 I jxcore-log: 
,03-24 18:28:34.497  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:34.497  3251  3316 I jxcore-log: 
,03-24 18:28:34.498  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:34.498  3251  3316 I jxcore-log: 
,03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:34.506  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:34.510  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:34.512  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:34.512  3251  3316 I jxcore-log: 
,03-24 18:28:34.514  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:34.514  3251  3316 I jxcore-log: 
03-24 18:28:34.517  3251  3316 I jxcore-log: # 51. make sure we actually call kill connections properly
03-24 18:28:34.517  3251  3316 I jxcore-log: 
,03-24 18:28:34.519  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:34.519  3251  3316 I jxcore-log: 
,03-24 18:28:34.702  3251  3316 I jxcore-log: ok 197 specific error expected
03-24 18:28:34.702  3251  3316 I jxcore-log: 
,03-24 18:28:34.704  3251  3316 I jxcore-log: # teardown
03-24 18:28:34.704  3251  3316 I jxcore-log: 
,03-24 18:28:34.840  3251  3316 I jxcore-log: # setup
03-24 18:28:34.840  3251  3316 I jxcore-log: 
,03-24 18:28:34.959  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:34.959  3251  3316 I jxcore-log: 
,03-24 18:28:34.960  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:34.960  3251  3316 I jxcore-log: 
,03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:34.968  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:34.971  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:34.974  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:34.974  3251  3316 I jxcore-log: 
,03-24 18:28:34.975  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:34.975  3251  3316 I jxcore-log: 
,03-24 18:28:34.979  3251  3316 I jxcore-log: # 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 18:28:34.979  3251  3316 I jxcore-log: 
,03-24 18:28:34.981  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:34.981  3251  3316 I jxcore-log: 
,03-24 18:28:35.104  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:35.104  3251  3316 I jxcore-log: 
,03-24 18:28:35.106  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 33790
03-24 18:28:35.106  3251  3316 I jxcore-log: 
,03-24 18:28:35.110  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50479,"error":{}}
03-24 18:28:35.110  3251  3316 I jxcore-log: 
,03-24 18:28:35.111  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:28:35.112  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 18:28:35.112  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:35.113  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:28:35.113  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:35.113  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:35.125  3251  3316 I jxcore-log: ok 198 failure reason is as expected
03-24 18:28:35.125  3251  3316 I jxcore-log: ,
03-24 18:28:35.126  3251  3316 I jxcore-log: ok 199 error description is as expected
,03-24 18:28:35.126  3251  3316 I jxcore-log: 
03-24 18:28:35.126  3251  3316 I jxcore-log: ok 200 must be stopped
03-24 18:28:35.126  3251  3316 I jxcore-log: 
,03-24 18:28:35.135  3251  3316 I jxcore-log: # teardown
,03-24 18:28:35.135  3251  3316 I jxcore-log: 
,03-24 18:28:35.223  3251  3316 I jxcore-log: # setup
03-24 18:28:35.223  3251  3316 I jxcore-log: ,
,03-24 18:28:35.352  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:35.352  3251  3316 I jxcore-log: 
,03-24 18:28:35.357  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:35.357  3251  3316 I jxcore-log: 
,03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
03-24 18:28:35.371  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:35.378  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:35.382  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:35.382  3251  3316 I jxcore-log: 
03-24 18:28:35.387  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:35.387  3251  3316 I jxcore-log: 
,03-24 18:28:35.390  3251  3316 I jxcore-log: # 53. We repeat failedConnection event when we get it from thaliTcpServersManager
03-24 18:28:35.390  3251  3316 I jxcore-log: 
,03-24 18:28:35.391  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:35.391  3251  3316 I jxcore-log: 
,03-24 18:28:35.491  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:35.491  3251  3316 I jxcore-log: 
,03-24 18:28:35.493  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 32812
03-24 18:28:35.493  3251  3316 I jxcore-log: 
,03-24 18:28:35.497  3251  3316 I jxcore-log: ok 201 peerIdentifier matches
03-24 18:28:35.497  3251  3316 I jxcore-log: 
,03-24 18:28:35.497  3251  3316 I jxcore-log: ok 202 error description matches
03-24 18:28:35.497  3251  3316 I jxcore-log: 
,03-24 18:28:35.500  3251  3316 I jxcore-log: # teardown
03-24 18:28:35.500  3251  3316 I jxcore-log: 
,03-24 18:28:35.773  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:35.774  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:35.774  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:35.777  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:35.777  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:28:35.777  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:35.793  3251  3316 I jxcore-log: # setup
03-24 18:28:35.793  3251  3316 I jxcore-log: 
,03-24 18:28:35.917  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:35.917  3251  3316 I jxcore-log: 
,03-24 18:28:35.921  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:35.921  3251  3316 I jxcore-log: 
,03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:35.935  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:35.941  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:35.944  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:35.944  3251  3316 I jxcore-log: 
,03-24 18:28:35.947  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:35.947  3251  3316 I jxcore-log: 
,03-24 18:28:35.953  3251  3316 I jxcore-log: # 54. we successfully receive and replay discoveryAdvertisingStateUpdate
03-24 18:28:35.953  3251  3316 I jxcore-log: 
,03-24 18:28:35.957  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:35.957  3251  3316 I jxcore-log: 
,03-24 18:28:36.055  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:36.055  3251  3316 I jxcore-log: 
,03-24 18:28:36.057  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 34791
03-24 18:28:36.057  3251  3316 I jxcore-log: 
,03-24 18:28:36.063  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53590, start advertisements: false,
03-24 18:28:36.063  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:36.063  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:36.063  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:28:36.068  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 18:28:36.068  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:36.068  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:36.073  2162  2226 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 18:28:36.078  2162  2182 D BtGatt.GattService: registerClient() - UUID=eb3146cb-78ab-4dab-a1a3-460953082106
,03-24 18:28:36.079  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=eb3146cb-78ab-4dab-a1a3-460953082106, clientIf=5
03-24 18:28:36.079  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:28:36.082  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:28:36.083  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:36.083  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 18:28:36.083  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:36.083  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:28:36.083  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:28:36.083  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:36.084  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:36.087   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:36.088  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:28:36.092  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:28:36.092  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:36.092  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:36.092  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 18:28:36.092  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:36.093  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:36.094  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:36.094  3251  3316 I jxcore-log: 
03-24 18:28:36.095  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:36.096  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:36.096  3251  3316 I jxcore-log: ok 203 discoveryActive matches
03-24 18:28:36.096  3251  3316 I jxcore-log: 
,03-24 18:28:36.097  3251  3316 I jxcore-log: ok 204 advertisingActive matches
03-24 18:28:36.097  3251  3316 I jxcore-log: 
03-24 18:28:36.098  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:28:36.098  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.098  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:36.098  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:36.099  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:28:36.099  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:36.099  3251  3316 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 18:28:36.099  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-24 18:28:36.099  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:36.099  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:28:36.099  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:36.100  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:36.100  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:28:36.101  2162  2369 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:28:36.102  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:36.102  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:36.102  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:36.102  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:36.102  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:36.102  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:28:36.103  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 18:28:36.103  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 18:28:36.103  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:28:36.103  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:36.104  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.104  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:36.104  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:36.104  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:28:36.105  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:36.105  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:28:36.105  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:36.106  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:36.106  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:28:36.112  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 18:28:36.113  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.113  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:36.113  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:36.113  3251  3316 I jxcore-log: 
03-24 18:28:36.114  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:28:36.114   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:36.115  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:36.116  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.116  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:36.118  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:36.118  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:36.123  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 18:28:36.124  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:36.124  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:36.127  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 18:28:36.127  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:36.127  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:36.127  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:36.128  3251  3316 I jxcore-log: not ok 205 discoveryActive matches
03-24 18:28:36.128  3251  3316 I jxcore-log: 
03-24 18:28:36.128  3251  3316 I jxcore-log:   ---
03-24 18:28:36.128  3251  3316 I jxcore-log: 
,03-24 18:28:36.128  3251  3316 I jxcore-log:     operator: equal
03-24 18:28:36.128  3251  3316 I jxcore-log: 
03-24 18:28:36.129  3251  3316 I jxcore-log:     expected: false
03-24 18:28:36.129  3251  3316 I jxcore-log: 
03-24 18:28:36.129  3251  3316 I jxcore-log:     actual:   true
03-24 18:28:36.129  3251  3316 I jxcore-log: 
,03-24 18:28:36.129  3251  3316 I jxcore-log:   ...
03-24 18:28:36.129  3251  3316 I jxcore-log: 
03-24 18:28:36.129  3251  3316 I jxcore-log: ok 206 advertisingActive matches
03-24 18:28:36.129  3251  3316 I jxcore-log: 
,03-24 18:28:36.131  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 18:28:36.131  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:36.131  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:36.132  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:36.132  3251  3316 I jxcore-log: 
,03-24 18:28:36.133  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:36.133  3251  3316 I jxcore-log: 
,03-24 18:28:36.143  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:36.143  3251  3316 I jxcore-log: 
,03-24 18:28:36.145  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 33751
03-24 18:28:36.145  3251  3316 I jxcore-log: 
,03-24 18:28:36.148  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 33751, start advertisements: true
,03-24 18:28:36.148  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:36.148  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:36.148  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:28:36.150  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 18:28:36.151  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:36.151  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:36.151  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:36.153  2162  2182 D BtGatt.GattService: registerClient() - UUID=0f056e0b-a5ef-42fc-94d6-d7a7e0fb88f1,
03-24 18:28:36.153  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=0f056e0b-a5ef-42fc-94d6-d7a7e0fb88f1, clientIf=5
03-24 18:28:36.153  3251  3269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:36.153  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:28:36.154  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:36.154  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:36.154  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:36.154  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:36.154  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 18:28:36.154  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:36.154  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:36.154  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:36.154  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:36.154  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:36.155  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:36.155  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:36.155  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:36.156  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 18:28:36.156  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.157  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:36.157  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.157  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:36.157  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:36.158  2162  2181 D BtGatt.GattService: registerClient() - UUID=ccfd4ce5-8f9d-4cef-b667-a39e88f8336d
03-24 18:28:36.158  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=ccfd4ce5-8f9d-4cef-b667-a39e88f8336d, clientIf=6
03-24 18:28:36.158  3251  3266 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 18:28:36.159  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:36.159  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.159  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:36.161  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:36.161  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:36.162  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:36.164  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:36.167  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:36.167  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:36.167  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:36.168   822  1371 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:36.170  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:28:36.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:36.170  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:28:36.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:36.171  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:28:36.171  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:28:36.171  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:28:36.171  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 18:28:36.172  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 18:28:36.172  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:28:36.172  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:36.172  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 18:28:36.172  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 18:28:36.172  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 18:28:36.172  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:36.172  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:36.172  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:36.172  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:36.172  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 18:28:36.172  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:36.173   822  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:36.173  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:36.174  3251  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 18:28:36.174  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:36.174  3251  3316 I jxcore-log: 
03-24 18:28:36.176  3251  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 18:28:36.179  3251  3316 I jxcore-log: not ok 207 discoveryActive matches
03-24 18:28:36.179  3251  3316 I jxcore-log: 
03-24 18:28:36.179  3251  3316 I jxcore-log:   ---
03-24 18:28:36.179  3251  3316 I jxcore-log: 
03-24 18:28:36.179  3251  3316 I jxcore-log:     operator: equal
03-24 18:28:36.179  3251  3316 I jxcore-log: 
03-24 18:28:36.179  3251  3316 I jxcore-log:     expected: false
03-24 18:28:36.179  3251  3316 I jxcore-log: 
,03-24 18:28:36.179  3251  3316 I jxcore-log:     actual:   true
03-24 18:28:36.179  3251  3316 I jxcore-log: 
03-24 18:28:36.179  3251  3316 I jxcore-log:   ...
03-24 18:28:36.179  3251  3316 I jxcore-log: 
03-24 18:28:36.182  3251  3316 I jxcore-log: not ok 208 advertisingActive matches
03-24 18:28:36.182  3251  3316 I jxcore-log: 
03-24 18:28:36.182  3251  3316 I jxcore-log:   ---
03-24 18:28:36.182  3251  3316 I jxcore-log: 
03-24 18:28:36.182  3251  3316 I jxcore-log:     operator: equal
03-24 18:28:36.182  3251  3316 I jxcore-log: 
,03-24 18:28:36.182  3251  3316 I jxcore-log:     expected: true
03-24 18:28:36.182  3251  3316 I jxcore-log: 
03-24 18:28:36.182  3251  3316 I jxcore-log:     actual:   false
03-24 18:28:36.182  3251  3316 I jxcore-log: 
,03-24 18:28:36.182  3251  3316 I jxcore-log:   ...
03-24 18:28:36.182  3251  3316 I jxcore-log: 
03-24 18:28:36.184  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:36.184  3251  3316 I jxcore-log: 
03-24 18:28:36.188  3251  3316 I jxcore-log: not ok 209 discoveryActive matches
03-24 18:28:36.188  3251  3316 I jxcore-log: 
03-24 18:28:36.188  3251  3316 I jxcore-log:   ---
03-24 18:28:36.188  3251  3316 I jxcore-log: 
03-24 18:28:36.188  3251  3316 I jxcore-log:     operator: equal
03-24 18:28:36.188  3251  3316 I jxcore-log: 
03-24 18:28:36.188  3251  3316 I jxcore-log:     expected: false
03-24 18:28:36.188  3251  3316 I jxcore-log: 
,03-24 18:28:36.188  3251  3316 I jxcore-log:     actual:   true
03-24 18:28:36.188  3251  3316 I jxcore-log: 
03-24 18:28:36.188  3251  3316 I jxcore-log:   ...
03-24 18:28:36.188  3251  3316 I jxcore-log: 
03-24 18:28:36.189  3251  3316 I jxcore-log: ok 210 advertisingActive matches
03-24 18:28:36.189  3251  3316 I jxcore-log: 
03-24 18:28:36.190  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:28:36.190  3251  3316 I jxcore-log: 
03-24 18:28:36.191  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:28:36.191  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 18:28:36.191  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 18:28:36.191  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:28:36.191  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 18:28:36.192  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:28:36.192  3251  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 18:28:36.192  3251  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:28:36.192  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 18:28:36.192  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:36.192  3251  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:28:36.192  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:28:36.192  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:36.192  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 18:28:36.192  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:28:36.192  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 18:28:36.192  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:36.193  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:28:36.194  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:28:36.195  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:36.195  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 18:28:36.195  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:36.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:28:36.195  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 18:28:36.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 18:28:36.195  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 18:28:36.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:28:36.195  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:36.195  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.196  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:36.197  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:36.197  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:36.199  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:36.199  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.199  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:36.200  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:36.200  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:36.201  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:36.201  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:36.201  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:36.201  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:28:36.201  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 18:28:36.201  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 18:28:36.201  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:36.202  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:36.202  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 18:28:36.202  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 18:28:36.202  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:36.203  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:36.203  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:36.203  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:36.203  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:36.203  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:28:36.203  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:36.203  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:28:36.207  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:36.207  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 18:28:36.207  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:36.208  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 18:28:36.208   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:36.213  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:36.214  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:36.214  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:36.218  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:36.218  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:36.218  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:28:36.219  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 18:28:36.219  3251  3316 I jxcore-log: 
,03-24 18:28:36.220  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:36.220  3251  3316 I jxcore-log: 
,03-24 18:28:36.221  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:36.221  3251  3316 I jxcore-log: 
,03-24 18:28:36.233  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:36.233  3251  3316 I jxcore-log: 
,03-24 18:28:36.236  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 34529
03-24 18:28:36.236  3251  3316 I jxcore-log: 
,03-24 18:28:36.244  3251  3316 I jxcore-log: # teardown
03-24 18:28:36.244  3251  3316 I jxcore-log: 
,03-24 18:28:39.275  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 18:28:39.275  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:39.276  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:39.280  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:39.280  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:39.280  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:39.294  3251  3316 I jxcore-log: # setup
03-24 18:28:39.294  3251  3316 I jxcore-log: 
,03-24 18:28:39.398  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 18:28:39.398  3251  3316 I jxcore-log: 
,03-24 18:28:39.403  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 18:28:39.403  3251  3316 I jxcore-log: 
,03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 18:28:39.413  3251  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 18:28:39.416  3251  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 18:28:39.417  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 18:28:39.417  3251  3316 I jxcore-log: 
,03-24 18:28:39.419  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 18:28:39.419  3251  3316 I jxcore-log: 
,03-24 18:28:39.422  3251  3316 I jxcore-log: # 55. can do HTTP requests between peers
03-24 18:28:39.422  3251  3316 I jxcore-log: 
,03-24 18:28:39.423  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 18:28:39.423  3251  3316 I jxcore-log: 
,03-24 18:28:40.112  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 18:28:40.112  3251  3316 I jxcore-log: 
,03-24 18:28:40.115  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 53787,
,03-24 18:28:40.115  3251  3316 I jxcore-log: 
,03-24 18:28:40.122  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 33751, start advertisements: false
03-24 18:28:40.122  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:40.122  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:40.122  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 18:28:40.126  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 18:28:40.126  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:40.126  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:40.130  2162  2181 D BtGatt.GattService: registerClient() - UUID=f40088da-0449-4186-bc29-9bc91ba32fd4
,03-24 18:28:40.131  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=f40088da-0449-4186-bc29-9bc91ba32fd4, clientIf=5
,03-24 18:28:40.131  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 18:28:40.132  2162  2182 D BtGatt.GattService: start scan with filters
03-24 18:28:40.133  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:40.135  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:40.135  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:40.135  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:40.135  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 18:28:40.135  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:28:40.136  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:40.137  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 18:28:40.137   822  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:40.141  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:40.141  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:40.144  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:28:40.144  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:40.144  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:40.144  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 18:28:40.144  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:40.144  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:40.145  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 18:28:40.145  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:40.145  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-24 18:28:40.145  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:40.148  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:40.148  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:40.150  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:40.150  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 18:28:40.158  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 18:28:40.158  3251  3316 I jxcore-log: 
03-24 18:28:40.160  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 18:28:40.160  3251  3316 I jxcore-log: 
,03-24 18:28:40.166  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 53787, start advertisements: true,
03-24 18:28:40.166  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:40.166  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:40.166  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 18:28:40.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 18:28:40.170  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 18:28:40.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:40.170  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 18:28:40.170  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:40.171  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:40.171  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:40.171  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 18:28:40.175  2162  2369 D BtGatt.GattService: registerClient() - UUID=1ce9d61c-6192-44aa-8a4b-56d35e36ad0a,
03-24 18:28:40.176  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=1ce9d61c-6192-44aa-8a4b-56d35e36ad0a, clientIf=6
,03-24 18:28:40.176  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:40.178  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:40.181  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:40.184  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 18:28:40.187  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 18:28:40.187  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 18:28:40.187  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:40.188  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 18:28:40.188  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:40.188  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:28:40.188  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING],
03-24 18:28:40.188  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:28:40.188   822  1114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:40.191  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:40.191  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 18:28:40.192  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 18:28:40.192  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 18:28:40.192  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 18:28:40.193  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:28:40.193  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 18:28:40.193  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:28:40.193  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 18:28:40.194  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:40.194  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:40.194  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 18:28:40.195  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:40.196   822  1110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:40.198  3251  3831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:40.198  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 18:28:40.198  3251  3316 I jxcore-log: 
,03-24 18:28:40.201  3251  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:41.155  2162  2162 D BtGatt.ScanManager: awakened up at time 312538
03-24 18:28:41.157  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:41.164  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:28:41.164  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:41.164  2162  2224 D BtGatt.GattService: current time is 312548768421
,03-24 18:28:41.165  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 45, -73, -54, -120, 47, 104, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:28:41.165  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:41.166  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 18:28:41.167  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 18:28:41.167  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-24 18:28:41.168  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 18:28:41.168  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 18:28:41.170  3251  3316 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 18:28:41.170  3251  3316 I jxcore-log: 
,03-24 18:28:41.173  3251  3316 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 18:28:41.173  3251  3316 I jxcore-log: 
03-24 18:28:41.175  3251  3316 I jxcore-log: ok 211 found a peer! {"peerIdentifier":"F8:95:C7:87:3C:51","portNumber":56917,"hostAddress":"127.0.0.1"}
03-24 18:28:41.175  3251  3316 I jxcore-log: 
,03-24 18:28:41.181  3251  3316 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 18:28:41.181  3251  3316 I jxcore-log: 
,03-24 18:28:41.186  3251  3316 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 18:28:41.186  3251  3316 I jxcore-log: 
,03-24 18:28:41.190  3251  3316 I jxcore-log: DEBUG createPeerListener: first connection
03-24 18:28:41.190  3251  3316 I jxcore-log: 
,03-24 18:28:41.194  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-24 18:28:41.194  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 18:28:41.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-24 18:28:41.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 18:28:41.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 18:28:41.195  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
,03-24 18:28:41.195  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-24 18:28:41.195  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-24 18:28:41.196  3251  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 376),
03-24 18:28:41.196  3251  3832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:41.198  2162  2181 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 18:28:44.221  2162  2235 W bt-btif : info:x10
03-24 18:28:44.222  2162  2224 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 18:28:44.251  3777  3777 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 18:28:44.257  3777  3777 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 18:28:44.415  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcaeb4 rs_disc_pending=0
03-24 18:28:44.415  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:44.415  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:45.742  2162  2235 W bt-btif : info:x10,
03-24 18:28:45.743  2162  2224 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 18:28:45.743  2162  2224 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 18:28:45.747  2162  2235 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 18:28:45.747  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 18:28:45.747  2162  2235 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 18:28:45.747  3251  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 18:28:45.748  3251  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 377)
03-24 18:28:45.749  3251  3831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 18:28:45.750   822  1114 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:45.753  3251  3834 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 377)
,03-24 18:28:45.755  3251  3831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:45.761  3251  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:46.143  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcaeb4 rs_disc_pending=1
,03-24 18:28:46.143  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:46.144  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:46.164  2162  2235 W bt-sdp  : process_service_search_attr_rsp
,03-24 18:28:46.171  2162  2162 D BtGatt.ScanManager: awakened up at time 317554,
03-24 18:28:46.172  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:46.177  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 18:28:46.177  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.177  2162  2224 D BtGatt.GattService: current time is 317561577950
03-24 18:28:46.178  2162  2224 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 55, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 45, -73, -54, -120, 47, 104, 1, -128, -72, 55, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 18:28:46.178  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 18:28:46.179  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 18:28:46.182  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 18:28:46.183  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 18:28:46.223  3251  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 377)
,03-24 18:28:46.226  3251  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:46.227  3251  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 377),
,03-24 18:28:46.227  3251  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 377
03-24 18:28:46.227  3251  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 377)
03-24 18:28:46.227  3251  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0],
03-24 18:28:46.228  3251  3834 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 377)
03-24 18:28:46.228  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:46.228  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 18:28:46.228  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 18:28:46.229  3251  3251 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
,03-24 18:28:46.229  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:46.234  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:46.235  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 18:28:46.241  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 18:28:46.241  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:46.243  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:46.244  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-24 18:28:46.245  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:46.245  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:46.245  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:46.246  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:46.246  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
,03-24 18:28:46.248  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-24 18:28:46.248  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:46.248  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:46.258  2162  2369 D BtGatt.GattService: registerClient() - UUID=fcfba34b-229d-4e24-b3fe-615de0a4ffb4,
03-24 18:28:46.259  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=fcfba34b-229d-4e24-b3fe-615de0a4ffb4, clientIf=6
,03-24 18:28:46.259  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
,03-24 18:28:46.261  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:46.266  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 18:28:46.269  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 18:28:46.272  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 18:28:46.272  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:46.274  2162  2369 D BtGatt.GattService: stopScan() - queue size =1,
03-24 18:28:46.275  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 18:28:46.276  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.276  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
,03-24 18:28:46.276  2162  2182 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 18:28:46.277  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 18:28:46.277  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:46.277  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:46.277  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:46.277  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:46.277  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 18:28:46.278  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 18:28:46.278  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.278  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:46.279  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:46.279  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:46.285  2162  2181 D BtGatt.GattService: registerClient() - UUID=f03eb72f-3234-4c04-99f1-f1349295e77e
,03-24 18:28:46.285  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=f03eb72f-3234-4c04-99f1-f1349295e77e, clientIf=5
,03-24 18:28:46.286  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:46.286  2162  2369 D BtGatt.GattService: start scan with filters
03-24 18:28:46.287  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:46.287  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:46.287  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 18:28:46.289  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:28:46.290  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:46.291  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:46.291  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.292  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:46.293  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.293  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:46.293  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:46.294  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 18:28:46.294  2162  2224 D BtGatt.GattService: Client app is not null!
03-24 18:28:46.295  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:46.295  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 18:28:46.295  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 18:28:46.295  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:46.295  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 18:28:46.296  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:46.296  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:46.296  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:46.296  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:46.296  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:46.297  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:46.297  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:46.300  2162  2182 D BtGatt.GattService: registerClient() - UUID=0da6c222-0e7c-43bb-b634-a3712e20ed2f
,03-24 18:28:46.300  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:46.300  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.300  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=0da6c222-0e7c-43bb-b634-a3712e20ed2f, clientIf=6
03-24 18:28:46.301  3251  3269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:46.301  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:46.304  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:46.306  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:46.308  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:46.309  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 18:28:46.310  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:46.311  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:46.311  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:46.311  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:28:46.311  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 18:28:46.311  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:46.311  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 18:28:46.311  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 18:28:46.312  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:46.312  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 18:28:46.312  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:46.314  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 18:28:46.314  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.314  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:46.314  2162  2181 D BtGatt.GattService: registerClient() - UUID=ba450889-d12f-45f6-9e05-dd6c3298e5f2
03-24 18:28:46.314  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:46.314  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:46.315  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=ba450889-d12f-45f6-9e05-dd6c3298e5f2, clientIf=5
03-24 18:28:46.315  3251  3268 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:46.315  2162  2182 D BtGatt.GattService: start scan with filters
03-24 18:28:46.316  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:46.316  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:46.319  2162  2233 D BtGatt.AdvertiseManager: message : 1
03-24 18:28:46.319  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:28:46.319  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:46.321  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:46.321  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:46.323  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:28:46.323  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:28:46.324  2162  2369 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:46.324  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:46.324  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 18:28:46.324  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:46.324  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:46.324  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 18:28:46.324  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:46.325  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:46.325  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:46.325  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.325  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 18:28:46.325  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:46.325  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:46.325  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:46.327  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:46.327  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.328  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 18:28:46.328  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.329  2162  2182 D BtGatt.GattService: registerClient() - UUID=e00a4754-15e9-4c69-9cb1-97cba661b4b6
03-24 18:28:46.329  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=e00a4754-15e9-4c69-9cb1-97cba661b4b6, clientIf=6
03-24 18:28:46.330  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:46.331  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:46.333  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:46.336  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:46.338  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 18:28:46.339  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:46.340  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:46.341  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:46.341  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:46.341  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:46.342  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:28:46.342  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:46.342  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 18:28:46.342  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:46.342  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:46.342  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:46.342  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 18:28:46.343  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:28:46.344  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.344  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 18:28:46.345  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:46.345  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.346  2162  2369 D BtGatt.GattService: registerClient() - UUID=3aa738ed-c022-4ca0-8aae-3a0a7cbd3552
03-24 18:28:46.346  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=3aa738ed-c022-4ca0-8aae-3a0a7cbd3552, clientIf=5
03-24 18:28:46.347  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 18:28:46.347  2162  2182 D BtGatt.GattService: start scan with filters
,03-24 18:28:46.348  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:46.348  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:46.348  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 18:28:46.348  3251  3251 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 18:28:46.348  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:46.348  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:46.348  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 18:28:46.349  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:46.349  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 18:28:46.349  3251  3835 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 378)
,03-24 18:28:46.350  2162  2234 D BtGatt.ScanManager: handling starting scan
03-24 18:28:46.351  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 18:28:46.351  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.352  3251  3835 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 53787
03-24 18:28:46.352  3251  3835 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 18:28:46.352  3251  3835 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes,
03-24 18:28:46.352  3251  3835 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 18:28:46.352  3251  3835 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 378)
03-24 18:28:46.352  3251  3835 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 378)
03-24 18:28:46.353  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 18:28:46.353  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 18:28:46.353  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:46.353  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 18:28:46.354  3251  3838 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 380, name: Receiver)
03-24 18:28:46.354  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:46.354  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.354  3251  3316 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 18:28:46.354  3251  3316 I jxcore-log: 
03-24 18:28:46.355  3251  3837 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 379, name: Sender)
,03-24 18:28:46.356  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:46.356  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:46.357  3251  3316 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 18:28:46.357  3251  3316 I jxcore-log: 
,03-24 18:28:46.359  3251  3316 I jxcore-log: DEBUG createNativeListener: new mux
03-24 18:28:46.359  3251  3316 I jxcore-log: 
,03-24 18:28:46.647  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcb07c rs_disc_pending=1
,03-24 18:28:46.648  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:46.648  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:47.022  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcaeb4 rs_disc_pending=0
,03-24 18:28:47.022  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:47.022  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:47.101  3251  3316 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 18:28:47.101  3251  3316 I jxcore-log: 
,03-24 18:28:47.109  3251  3316 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 18:28:47.109  3251  3316 I jxcore-log: 
,03-24 18:28:47.226  3251  3316 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 18:28:47.226  3251  3316 I jxcore-log: 
,03-24 18:28:47.452  2162  2366 W bt-btif : invalid rfc slot id: 21
,03-24 18:28:47.453  3251  3838 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Receiver): bt socket closed, read return: -1
03-24 18:28:47.453  3251  3838 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-24 18:28:47.453  3251  3838 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,03-24 18:28:47.453  3251  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 378
03-24 18:28:47.454  3251  3838 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 378)
03-24 18:28:47.454  3251  3838 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 18:28:47.454  3251  3838 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 18:28:47.454  3251  3838 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 380
03-24 18:28:47.454  3251  3838 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 18:28:47.454  3251  3838 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 379
,03-24 18:28:47.454  3251  3838 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 378)
03-24 18:28:47.455  3251  3837 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Sender): Socket closed
03-24 18:28:47.455  3251  3837 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 379, name: Sender)
03-24 18:28:47.458  3251  3838 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 378)
03-24 18:28:47.458  3251  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-24 18:28:47.458  3251  3838 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 380, name: Receiver)
,03-24 18:28:47.474  3251  3316 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 18:28:47.474  3251  3316 I jxcore-log: 
,03-24 18:28:47.477  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 18:28:47.477  3251  3316 I jxcore-log: 
03-24 18:28:47.478  3251  3316 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed for port [object Object] but we are listening on 53787
03-24 18:28:47.478  3251  3316 I jxcore-log: 
,03-24 18:28:47.793  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcaeb4 rs_disc_pending=1
,03-24 18:28:47.793  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:47.794  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:47.917  2162  2235 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,03-24 18:28:47.917  2162  2235 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x4c
,03-24 18:28:48.136  2162  2224 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 18:28:48.143  2162  2224 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-24 18:28:48.143  2162  2224 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 18:28:48.155  2162  2225 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-24 18:28:48.155  2162  2225 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 18:28:48.344  2162  2224 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 18:28:48.344  2162  2225 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 18:28:48.348  2162  2225 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 18:28:48.366  2162  2225 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 18:28:48.484  2162  2235 W bt-btif : new conn_srvc id:26, app_id:1,
03-24 18:28:48.484  2162  2235 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 18:28:48.484  2162  2235 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 18:28:48.485  3251  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 376)
,03-24 18:28:48.485  3251  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 376)
03-24 18:28:48.487  3251  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 381)
03-24 18:28:48.487  3251  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 381)
03-24 18:28:48.487  3251  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 376)
,03-24 18:28:48.490  3251  3839 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 381)
,03-24 18:28:48.504  3251  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 381)
,03-24 18:28:48.507  3251  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-24 18:28:48.508  3251  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 376)
03-24 18:28:48.508  3251  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 376)
,03-24 18:28:48.508  3251  3839 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 381)
03-24 18:28:48.508  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 18:28:48.509  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 18:28:48.509  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 18:28:48.510  3251  3251 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 18:28:48.510  3251  3251 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 18:28:48.512  3251  3840 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 382)
,03-24 18:28:48.513  3251  3840 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60450
03-24 18:28:48.513  3251  3840 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 18:28:48.513  3251  3840 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 60450 (peer ID: F8:95:C7:87:3C:51)
03-24 18:28:48.514  3251  3840 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-24 18:28:48.520  3251  3316 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 18:28:48.520  3251  3316 I jxcore-log: 
,03-24 18:28:48.529  3251  3840 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 60450
,03-24 18:28:48.529  3251  3840 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 18:28:48.529  3251  3840 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 18:28:48.530  3251  3840 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 18:28:48.532  3251  3841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 383, name: Sender)
03-24 18:28:48.533  3251  3840 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 382)
03-24 18:28:48.533  3251  3840 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 382)
,03-24 18:28:48.540  3251  3842 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 384, name: Receiver)
,03-24 18:28:48.647  3251  3316 I jxcore-log: DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
03-24 18:28:48.647  3251  3316 I jxcore-log: 
,03-24 18:28:48.660  3251  3316 I jxcore-log: ok 212 server should return 200
03-24 18:28:48.660  3251  3316 I jxcore-log: 
,03-24 18:28:48.663  3251  3316 I jxcore-log: ok 213 response body should match testData
03-24 18:28:48.663  3251  3316 I jxcore-log: 
,03-24 18:28:48.669  3251  3316 I jxcore-log: # teardown
03-24 18:28:48.669  3251  3316 I jxcore-log: 
,03-24 18:28:49.149  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcb07c rs_disc_pending=0
,03-24 18:28:49.149  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:49.149  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:49.191  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 18:28:49.192  3251  3316 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 18:28:49.192  3251  3316 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 382)
03-24 18:28:49.192  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 382)
,03-24 18:28:49.193  3251  3842 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 384, thread name: Receiver): bt socket closed, read return: -1
03-24 18:28:49.193  3251  3842 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 384, name: Receiver)
03-24 18:28:49.194  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 18:28:49.194  3251  3316 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 18:28:49.194  3251  3316 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 384
03-24 18:28:49.194  3251  3316 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,03-24 18:28:49.195  3251  3316 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 383
03-24 18:28:49.195  3251  3316 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 382)
03-24 18:28:49.195  3251  3841 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 383, thread name: Sender): Socket closed
,03-24 18:28:49.196  3251  3841 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 383, name: Sender)
03-24 18:28:49.196  3251  3316 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 382)
03-24 18:28:49.197  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 18:28:49.197  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 18:28:49.197  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 18:28:49.197  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 18:28:49.208  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-24 18:28:49.208  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 18:28:49.208  3251  3831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 18:28:49.208  3251  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 18:28:49.208  3251  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 18:28:49.209  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 18:28:49.209  3251  3251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 18:28:49.209  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 18:28:49.209  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 18:28:49.209  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 18:28:49.210  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 18:28:49.210  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 18:28:49.210  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 18:28:49.216  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
,03-24 18:28:49.219  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 18:28:49.219  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:28:49.219  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:49.220  2162  2234 D BtGatt.ScanManager: stopping BLe Batch,
03-24 18:28:49.220  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 18:28:49.221  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:49.221  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 18:28:49.221  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 18:28:49.221  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 18:28:49.221  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 18:28:49.221  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 18:28:49.223  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 18:28:49.223  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:49.223  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 18:28:49.225  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:28:49.225  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:28:49.225  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:49.225  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 18:28:49.229  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 18:28:49.229  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:28:49.230  2162  2181 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:28:49.231  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 18:28:49.231  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 18:28:49.231  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 18:28:49.231  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 18:28:49.232  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 18:28:49.232  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:49.232  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 18:28:49.232  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 18:28:49.234  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 18:28:49.234  3251  3316 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 18:28:49.234  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 18:28:49.234  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 18:28:49.235  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:49.235  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 18:28:49.235  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:49.235  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 18:28:49.237  3251  3316 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 18:28:49.237  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 18:28:49.237  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 18:28:49.248  3251  3251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 18:28:49.248   822   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:49.253  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 18:28:49.253  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:49.253  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 18:28:49.256  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 18:28:49.257  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 18:28:49.257  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 18:28:49.259  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-24 18:28:49.259  3251  3316 I jxcore-log: 
03-24 18:28:49.259  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:49.259  3251  3316 I jxcore-log: 
,03-24 18:28:49.260  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 18:28:49.260  3251  3316 I jxcore-log: 
,03-24 18:28:49.271  3251  3316 I jxcore-log: # setup
03-24 18:28:49.271  3251  3316 I jxcore-log: 
,03-24 18:28:49.878  3251  3316 I jxcore-log: # 56. Client to server request locally
03-24 18:28:49.878  3251  3316 I jxcore-log: 
,03-24 18:28:49.969  2162  2235 E bt-btm  : tBTM_SEC_DEV:0xa2fcb07c rs_disc_pending=1
,03-24 18:28:49.969  2162  2235 W bt-btif : bta_dm_check_av:0
03-24 18:28:49.969  2162  2224 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 18:28:50.051  3251  3316 I jxcore-log: startUpdateAdvertisingAndListening
03-24 18:28:50.051  3251  3316 I jxcore-log: 
,03-24 18:28:50.052  3251  3316 I jxcore-log: _peerAvailabilityChanged,
03-24 18:28:50.052  3251  3316 I jxcore-log: 
03-24 18:28:50.052  3251  3316 I jxcore-log: peerIdentifier:id123
03-24 18:28:50.052  3251  3316 I jxcore-log: 
,03-24 18:28:50.052  3251  3316 I jxcore-log: connectionType:tcp
03-24 18:28:50.052  3251  3316 I jxcore-log: 
03-24 18:28:50.053  3251  3316 I jxcore-log: hostAddress:127.0.0.1
03-24 18:28:50.053  3251  3316 I jxcore-log: 
,03-24 18:28:50.053  3251  3316 I jxcore-log: portNumber:36428
03-24 18:28:50.053  3251  3316 I jxcore-log: 
03-24 18:28:50.053  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:28:50.053  3251  3316 I jxcore-log: 
,03-24 18:28:50.099  3251  3316 I jxcore-log: ok 214 Host address must match
03-24 18:28:50.099  3251  3316 I jxcore-log: 
,03-24 18:28:50.100  3251  3316 I jxcore-log: ok 215 suggestedTCPTimeout must match
03-24 18:28:50.100  3251  3316 I jxcore-log: 
03-24 18:28:50.100  3251  3316 I jxcore-log: ok 216 connectionType must match
03-24 18:28:50.100  3251  3316 I jxcore-log: 
03-24 18:28:50.100  3251  3316 I jxcore-log: ok 217 portNumber must match
03-24 18:28:50.100  3251  3316 I jxcore-log: 
,03-24 18:28:50.102  3251  3316 I jxcore-log: stopAdvertisingAndListening
03-24 18:28:50.102  3251  3316 I jxcore-log: 
,03-24 18:28:50.110  3251  3316 I jxcore-log: # teardown
03-24 18:28:50.110  3251  3316 I jxcore-log: 
,03-24 18:28:50.182  2162  2235 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,03-24 18:28:50.652  3251  3316 I jxcore-log: # setup
03-24 18:28:50.652  3251  3316 I jxcore-log: 
,03-24 18:28:50.799  3251  3316 I jxcore-log: # 57. Client to server request coordinated
03-24 18:28:50.799  3251  3316 I jxcore-log: 
,03-24 18:28:50.976  3251  3316 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 18:28:50.976  3251  3316 I jxcore-log: 
,03-24 18:28:50.979  3251  3316 I jxcore-log: DEBUG createNativeListener: listening 35552
03-24 18:28:50.979  3251  3316 I jxcore-log: 
,03-24 18:28:51.035  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 35552, start advertisements: true
03-24 18:28:51.035  3251  3316 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:51.035  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2,
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 18:28:51.036  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 18:28:51.036  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:51.036  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 18:28:51.045  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 18:28:51.045  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 18:28:51.045  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 18:28:51.045  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 18:28:51.056  2162  2182 D BtGatt.GattService: registerClient() - UUID=bc1e1161-c849-42a4-adc7-4778e83b5619,
03-24 18:28:51.057  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=bc1e1161-c849-42a4-adc7-4778e83b5619, clientIf=5
03-24 18:28:51.058  3251  3266 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 18:28:51.058  2162  2369 D BtGatt.GattService: start scan with filters
,03-24 18:28:51.059  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 18:28:51.059  2162  2234 D BtGatt.ScanManager: handling starting scan
,03-24 18:28:51.060  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 18:28:51.060  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 18:28:51.060  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 18:28:51.060  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 18:28:51.060  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 18:28:51.060  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 18:28:51.061  2162  2224 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 18:28:51.061  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:51.061  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 18:28:51.062  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 18:28:51.062  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 18:28:51.062  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:51.062  2162  2234 D BtGatt.ScanManager: Starting BLE batch scan
03-24 18:28:51.062  2162  2234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 18:28:51.062  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:51.063  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 18:28:51.063  3251  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 18:28:51.063  2162  2224 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 18:28:51.063  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:51.064  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 18:28:51.064  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:51.072  2162  2181 D BtGatt.GattService: registerClient() - UUID=0d66fe54-4a2d-4184-8628-f5a4261a979e
,03-24 18:28:51.072  2162  2224 D BtGatt.GattService: onClientRegistered() - UUID=0d66fe54-4a2d-4184-8628-f5a4261a979e, clientIf=6
03-24 18:28:51.072  3251  3268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 18:28:51.073  2162  2233 D BtGatt.AdvertiseManager: message : 0
,03-24 18:28:51.075  2162  2233 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 18:28:51.077  2162  2224 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 18:28:51.080  2162  2224 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 18:28:51.080  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 18:28:51.080  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 18:28:51.086   822  1487 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 18:28:51.088  3251  3316 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 18:28:51.088  3251  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 18:28:51.088  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-24 18:28:51.088  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 18:28:51.089  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 18:28:51.089  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 18:28:51.089  3251  3316 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 18:28:51.089  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 18:28:51.089  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
03-24 18:28:51.089  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 18:28:51.090  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 18:28:51.090  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 18:28:51.090  3251  3251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 18:28:51.090   822  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 18:28:51.090  3251  3251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 18:28:51.090  3251  3251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 18:28:51.091  3251  3251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:51.091  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 18:28:51.091  3251  3251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 18:28:51.091  3251  3251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 18:28:51.091  3251  3843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:51.091  3251  3251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 18:28:51.092  3251  3251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 18:28:51.094  3251  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 18:28:51.098  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:51.098  3251  3316 I jxcore-log: 
,03-24 18:28:51.099  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 18:28:51.099  3251  3316 I jxcore-log: 
03-24 18:28:51.100  3251  3316 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 18:28:51.100  3251  3316 I jxcore-log: 
,03-24 18:28:51.105  3251  3316 I io.jxcore.node.ConnectionHelper: start: Port number: 35552, start advertisements: false
03-24 18:28:51.105  3251  3316 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 18:28:51.105  3251  3316 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 18:28:51.105  3251  3316 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 18:28:51.105  3251  3316 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 18:28:51.109  3251  3316 I jxcore-log: startListeningForAdvertisements
03-24 18:28:51.109  3251  3316 I jxcore-log: 
,03-24 18:28:51.532  2162  2235 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 18:28:51.538  2162  2162 D BluetoothMapService: onReceive
,03-24 18:28:51.572  3777  3777 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 18:28:51.578  3777  3777 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 18:28:51.962  3251  3316 I jxcore-log: _peerAvailabilityChanged
03-24 18:28:51.962  3251  3316 I jxcore-log: 
03-24 18:28:51.962  3251  3316 I jxcore-log: peerIdentifier:dummy
03-24 18:28:51.962  3251  3316 I jxcore-log: 
,03-24 18:28:51.962  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:28:51.962  3251  3316 I jxcore-log: 
03-24 18:28:51.963  3251  3316 I jxcore-log: hostAddress:null
03-24 18:28:51.963  3251  3316 I jxcore-log: 
03-24 18:28:51.963  3251  3316 I jxcore-log: portNumber:null
03-24 18:28:51.963  3251  3316 I jxcore-log: 
03-24 18:28:51.963  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:28:51.963  3251  3316 I jxcore-log: 
,03-24 18:28:53.224  2162  2222 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 18:28:54.545  2162  2235 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 18:28:54.555  2162  2162 D BluetoothMapService: onReceive,
,03-24 18:28:54.575  3777  3777 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 18:28:54.578  3777  3777 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 18:28:55.417  2162  2162 D BtGatt.ScanManager: awakened up at time 326801
03-24 18:28:55.419  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:55.428  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 18:28:55.428  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:28:55.428  2162  2224 D BtGatt.GattService: current time is 326812830499
03-24 18:28:55.429  2162  2224 D BtGatt.GattService: Batch record : [85, 12, -73, -105, -34, 115, 1, -128, -72, 68, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 54, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 18:28:55.429  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 18:28:55.430  2162  2224 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 18:28:55.433  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 18:28:55.433  3251  3251 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 18:28:55.434  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 18:28:55.434  3251  3251 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 18:28:55.443  3251  3316 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 18:28:55.443  3251  3316 I jxcore-log: 
,03-24 18:28:55.453  3251  3316 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 18:28:55.453  3251  3316 I jxcore-log: 
,03-24 18:28:55.457  3251  3316 I jxcore-log: _peerAvailabilityChanged,
03-24 18:28:55.457  3251  3316 I jxcore-log: 
03-24 18:28:55.457  3251  3316 I jxcore-log: peerIdentifier:E0:DB:10:14:E2:C0
03-24 18:28:55.457  3251  3316 I jxcore-log: 
,03-24 18:28:55.457  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:28:55.457  3251  3316 I jxcore-log: 
03-24 18:28:55.457  3251  3316 I jxcore-log: hostAddress:null
03-24 18:28:55.457  3251  3316 I jxcore-log: 
03-24 18:28:55.457  3251  3316 I jxcore-log: portNumber:null
03-24 18:28:55.457  3251  3316 I jxcore-log: 
,03-24 18:28:55.457  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:28:55.457  3251  3316 I jxcore-log: 
03-24 18:28:55.457  3251  3316 I jxcore-log: _peerAvailabilityChanged
03-24 18:28:55.457  3251  3316 I jxcore-log: 
03-24 18:28:55.457  3251  3316 I jxcore-log: peerIdentifier:E0:DB:10:14:E2:C0
03-24 18:28:55.457  3251  3316 I jxcore-log: 
03-24 18:28:55.457  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:28:55.457  3251  3316 I jxcore-log: 
,03-24 18:28:55.458  3251  3316 I jxcore-log: hostAddress:127.0.0.1
03-24 18:28:55.458  3251  3316 I jxcore-log: 
03-24 18:28:55.458  3251  3316 I jxcore-log: portNumber:52246
03-24 18:28:55.458  3251  3316 I jxcore-log: 
03-24 18:28:55.458  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:28:55.458  3251  3316 I jxcore-log: ,
03-24 18:28:55.465  3251  3316 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 18:28:55.465  3251  3316 I jxcore-log: 
,03-24 18:28:55.472  3251  3316 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 18:28:55.472  3251  3316 I jxcore-log: 
,03-24 18:28:55.478  3251  3316 I jxcore-log: _peerAvailabilityChanged
03-24 18:28:55.478  3251  3316 I jxcore-log: 
03-24 18:28:55.478  3251  3316 I jxcore-log: peerIdentifier:F8:95:C7:87:3C:51
03-24 18:28:55.478  3251  3316 I jxcore-log: 
03-24 18:28:55.478  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:28:55.478  3251  3316 I jxcore-log: 
,03-24 18:28:55.478  3251  3316 I jxcore-log: hostAddress:null
03-24 18:28:55.478  3251  3316 I jxcore-log: 
03-24 18:28:55.478  3251  3316 I jxcore-log: portNumber:null
03-24 18:28:55.478  3251  3316 I jxcore-log: 
03-24 18:28:55.478  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:28:55.478  3251  3316 I jxcore-log: 
03-24 18:28:55.479  3251  3316 I jxcore-log: _peerAvailabilityChanged
03-24 18:28:55.479  3251  3316 I jxcore-log: 
,03-24 18:28:55.479  3251  3316 I jxcore-log: peerIdentifier:F8:95:C7:87:3C:51
03-24 18:28:55.479  3251  3316 I jxcore-log: 
03-24 18:28:55.481  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:28:55.481  3251  3316 I jxcore-log: 
03-24 18:28:55.481  3251  3316 I jxcore-log: hostAddress:127.0.0.1
03-24 18:28:55.481  3251  3316 I jxcore-log: 
03-24 18:28:55.481  3251  3316 I jxcore-log: portNumber:40918
03-24 18:28:55.481  3251  3316 I jxcore-log: 
,03-24 18:28:55.481  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:28:55.481  3251  3316 I jxcore-log: 
,03-24 18:28:55.490  3251  3316 I jxcore-log: DEBUG createPeerListener: first connection
03-24 18:28:55.490  3251  3316 I jxcore-log: 
,03-24 18:28:55.499  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 18:28:55.499  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 18:28:55.503  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 18:28:55.503  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
03-24 18:28:55.503  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 18:28:55.504  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
,03-24 18:28:55.504  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 18:28:55.504  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 18:28:55.506  3251  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 386)
03-24 18:28:55.506  3251  3845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:55.509  2162  2369 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 18:28:55.516  3251  3316 I jxcore-log: DEBUG createPeerListener: first connection
03-24 18:28:55.516  3251  3316 I jxcore-log: ,
,03-24 18:28:55.521  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51,
03-24 18:28:55.521  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
03-24 18:28:55.522  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,03-24 18:28:55.522  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 18:28:55.522  3251  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 18:28:55.523  3251  3316 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-24 18:28:55.523  3251  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,03-24 18:28:55.523  3251  3316 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-24 18:28:55.525  3251  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 387)
,03-24 18:28:55.525  3251  3846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 18:28:55.528  2162  2181 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 18:28:55.535   822   838 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22fb4adf},
,03-24 18:28:55.540   822  1018 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 18:28:57.210  2162  2162 D BtGatt.ScanManager: awakened up at time 328594
,03-24 18:28:57.211  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:28:57.212   822  1282 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22fb4adf}
03-24 18:28:57.213  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 18:28:57.213  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:28:57.259   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 18:28:59.365  2162  2226 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 18:29:00.332  3487  3849 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 18:29:00.361  3487  3851 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 18:29:00.363  3442  3850 V KeepSync: Connecting to GoogleApiClient
,03-24 18:29:00.470   822  1114 I art     : Explicit concurrent mark sweep GC freed 30792(1521KB) AllocSpace objects, 8(787KB) LOS objects, 32% free, 33MB/49MB, paused 2.079ms total 80.443ms
,03-24 18:29:00.526  1263  3720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 18:29:00.526  1263  3720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:29:00.526  1263  3720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:29:00.527  1263  3720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:29:00.532  1263  3720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:29:00.561  1263  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 18:29:00.562  1263  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:29:00.562  1263  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:29:00.562  1263  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:29:00.567  1263  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: Handling authorization failure
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 18:29:00.581  1815  3853 E ClientConnectionOperation: 	... 7 more
,03-24 18:29:00.583  3442  3850 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 18:29:00.595  3442  3850 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 18:29:00.601  3442  3850 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 18:29:00.602  3442  3850 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 18:29:00.622  1263  1280 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 18:29:00.622  1263  1280 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:29:00.622  1263  1280 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:29:00.622  1263  1280 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 18:29:00.625  1263  1280 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:29:00.633  2162  2235 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,03-24 18:29:00.633  2162  2235 E bt-btif : DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
03-24 18:29:00.633  2162  2366 W bt-btif : invalid rfc slot id: 26
03-24 18:29:00.633  3251  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 386)
03-24 18:29:00.633  3251  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 386)
03-24 18:29:00.633  3251  3845 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 386)
03-24 18:29:00.633  3251  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 386
03-24 18:29:00.633  3251  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 386
03-24 18:29:00.633  3251  3251 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> E0:DB:10:14:E2:C0]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 18:29:00.633  3251  3251 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> E0:DB:10:14:E2:C0], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 18:29:00.633  3251  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
03-24 18:29:00.633  3251  3251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 18:29:00.633  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
03-24 18:29:00.634  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
03-24 18:29:00.636  3487  3851 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:29:00.636  3251  3316 I jxcore-log: WARN createPeerListener: 
03-24 18:29:00.636  3251  3316 I jxcore-log: 
03-24 18:29:00.636  3487  3849 E BooksSync: Soft error
03-24 18:29:00.636  3487  3849 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:29:00.636  3487  3849 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 18:29:00.636  3251  3316 I jxcore-log: DEBUG createPeerListener: failedConnection
03-24 18:29:00.636  3251  3316 I jxcore-log: 
03-24 18:29:00.636  3487  3849 E BooksSync: Sync error
03-24 18:29:00.636  3487  3849 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 18:29:00.636  3487  3849 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 18:29:00.636  3251  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
03-24 18:29:00.637  3487  3849 I BooksSync: Finished books sync
03-24 18:29:00.637  3251  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
03-24 18:29:00.637  3251  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
03-24 18:29:00.638  3251  3316 I jxcore-log: _peerAvailabilityChanged
03-24 18:29:00.638  3251  3316 I jxcore-log: 
03-24 18:29:00.638  3251  3316 I jxcore-log: peerIdentifier:E0:DB:10:14:E2:C0
03-24 18:29:00.638  3251  3316 I jx,core-log: 
03-24 18:29:00.638  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:29:00.638  3251  3316 I jxcore-log: 
03-24 18:29:00.638  3251  3316 I jxcore-log: hostAddress:null
03-24 18:29:00.638  3251  3316 I jxcore-log: 
03-24 18:29:00.638  3251  3316 I jxcore-log: portNumber:null
03-24 18:29:00.638  3251  3316 I jxcore-log: 
03-24 18:29:00.638  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:29:00.638  3251  3316 I jxcore-log: 
03-24 18:29:00.640  3251  3316 I jxcore-log: _peerAvailabilityChanged
03-24 18:29:00.640  3251  3316 I jxcore-log: 
03-24 18:29:00.640  3251  3316 I jxcore-log: peerIdentifier:E0:DB:10:14:E2:C0
03-24 18:29:00.640  3251  3316 I jxcore-log: 
03-24 18:29:00.640  3251  3316 I jxcore-log: connectionType:AndroidBluetooth
03-24 18:29:00.640  3251  3316 I jxcore-log: 
03-24 18:29:00.640  3251  3316 I jxcore-log: hostAddress:null
03-24 18:29:00.640  3251  3316 I jxcore-log: 
03-24 18:29:00.640  3251  3316 I jxcore-log: portNumber:null
03-24 18:29:00.640  3251  3316 I jxcore-log: 
03-24 18:29:00.640  3251  3316 I jxcore-log: _peerAvailabilityChanged - end
03-24 18:29:00.640  3251  3316 I jxcore-log: 
03-24 18:29:00.644   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302243, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-24 18:29:00.645  3251  3316 I jxcore-log: DEBUG createPeerListener: failed incoming connection because of mux promise failure: Connection to peer [<no peer name> E0:DB:10:14:E2:C0] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 18:29:00.645  3251  3316 I jxcore-log: 
03-24 18:29:00.673  1263  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 18:29:00.673  1263  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 18:29:00.673  1263  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 18:29:00.673  1263  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 18:29:00.678  1263  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 18:29:00.708  3442  3850 E KeepSync: IOException
03-24 18:29:00.708  3442  3850 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 18:29:00.708  3442  3850 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 18:29:00.708  3442  3850 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 18:29:00.708  3442  3850 E KeepSync: 	... 10 more
03-24 18:29:00.708  3442  3850 W KeepSync: Sync result 2
,03-24 18:29:00.713   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 304434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 18:29:02.222  2162  2162 D BtGatt.ScanManager: awakened up at time 333606
,03-24 18:29:02.224  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:29:02.226  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 18:29:02.226  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:29:05.495  3251  3316 I jxcore-log: Uncaught Promise Rejection: {}
03-24 18:29:05.495  3251  3316 I jxcore-log: 
,03-24 18:29:05.501  3251  3316 E jxcore-log: Trace: [Error: Could not establish TCP connection]
03-24 18:29:05.501  3251  3316 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-24 18:29:05.501  3251  3316 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-24 18:29:05.501  3251  3316 E jxcore-log:     at emit@events.js:98:1
,03-24 18:29:05.501  3251  3316 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-24 18:29:05.501  3251  3316 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-24 18:29:05.501  3251  3316 E jxcore-log:     at $0a@node.js:917:1
03-24 18:29:05.501  3251  3316 E jxcore-log: 
03-24 18:29:05.501  3251  3316 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-24 18:29:05.501  3251  3316 I jxcore-log: 
,03-24 18:29:05.762  2162  2235 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
,03-24 18:29:05.762  2162  2235 E bt-btif : DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,03-24 18:29:05.763  2162  2366 W bt-btif : invalid rfc slot id: 27
,03-24 18:29:05.764  3251  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 387)
,03-24 18:29:05.764  3251  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 387)
03-24 18:29:05.764  3251  3846 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 387)
03-24 18:29:05.764  3251  3251 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> F8:95:C7:87:3C:51]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 18:29:05.764  3251  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 387
,03-24 18:29:05.764  3251  3251 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> F8:95:C7:87:3C:51], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-24 18:29:05.764  3251  3251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 18:29:05.764  3251  3251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
03-24 18:29:05.764  3251  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 387
03-24 18:29:05.764  3251  3251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
03-24 18:29:05.765  3251  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 387)
03-24 18:29:05.771  3251  3316 I jxcore-log: WARN createPeerListener: 
03-24 18:29:05.771  3251  3316 I jxcore-log: 
03-24 18:29:05.772  3251  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 387
03-24 18:29:05.772  3251  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 387)
03-24 18:29:05.772  3251  3316 I jxcore-log: DEBUG createPeerListener: failedConnection
03-24 18:29:05.772  3251  3316 I jxcore-log: 
03-24 18:29:05.773  3251  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 387)
,03-24 18:29:05.793  3858  3858 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-24 18:29:05.796  3858  3858 D AndroidRuntime: CheckJNI is OFF
,03-24 18:29:05.936  3858  3858 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 18:29:05.949   822   856 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-24 18:29:05.950   822   856 I ActivityManager: Killing 3251:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-24 18:29:06.025   822   866 W PackageSettings: Skipping PackageSetting{32b1c3fb com.example.hello/10273} due to missing metadata
,03-24 18:29:06.128  2162  2369 D BtGatt.GattService: Binder is dead - unregistering client (6)!
03-24 18:29:06.128  2162  2182 D BtGatt.GattService: Binder is dead - unregistering client (5)!
,03-24 18:29:06.137   822  1428 I WindowState: WIN DEATH: Window{4dece7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-24 18:29:06.141   822  1019 D WifiService: Client connection lost with reason: 4
,03-24 18:29:06.145  2162  2233 D BtGatt.AdvertiseManager: message : 1
,03-24 18:29:06.147  2162  2182 D BtGatt.GattService: stopScan() - queue size =1
03-24 18:29:06.147  2162  2233 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 18:29:06.152  2162  2233 D BtGatt.AdvertiseManager: app died - unregistering client : 6
,03-24 18:29:06.153  2162  2224 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 18:29:06.153  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:29:06.153  2162  2234 D BtGatt.ScanManager: stopping BLe Batch
03-24 18:29:06.154  2162  2224 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 18:29:06.154  2162  2224 D BtGatt.GattService: Client app is not null!
,03-24 18:29:06.154  2162  2224 E BluetoothServiceJni: An exception was thrown by callback 'btgattc_multiadv_disable_cb'.
03-24 18:29:06.155  2162  2233 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 18:29:06.155  2162  2224 E BluetoothServiceJni: android.os.DeadObjectException
03-24 18:29:06.155  2162  2224 E BluetoothServiceJni: 	at android.os.BinderProxy.transactNative(Native Method)
03-24 18:29:06.155  2162  2224 E BluetoothServiceJni: 	at android.os.BinderProxy.transact(Binder.java:496)
03-24 18:29:06.155  2162  2224 E BluetoothServiceJni: 	at android.bluetooth.IBluetoothGattCallback$Stub$Proxy.onMultiAdvertiseCallback(IBluetoothGattCallback.java:874)
03-24 18:29:06.155  2162  2224 E BluetoothServiceJni: 	at com.android.bluetooth.gatt.GattService.onAdvertiseInstanceDisabled(GattService.java:1233)
,03-24 18:29:06.158   822   856 E libprocessgroup: failed to kill 1 processes for processgroup 3251
03-24 18:29:06.158   822   856 W ActivityManager: Force removing ActivityRecord{8289d1 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-24 18:29:06.160  2162  2224 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 18:29:06.161  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 18:29:06.161  2162  2234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 18:29:06.163  2162  2224 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 18:29:06.163  2162  2224 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 18:29:06.168  2162  2234 D BtGatt.ScanManager: app died, unregister client - 5
,03-24 18:29:06.168   822   822 V ActivityManager: Display changed displayId=0
03-24 18:29:06.169  2162  2234 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 18:29:06.176   822   866 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-24 18:29:06.186   822   837 W ActivityManager: Spurious death for ProcessRecord{28d04a66 3251:com.test.thalitest/u0a95}, curProc for 3251: null
,03-24 18:29:06.189  1244  1244 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 18:29:06.192  1244  3874 I Keyboard.Facilitator.DecoderInitializer: run()
,03-24 18:29:06.194  1244  3874 I Decoder : createOrResetDecoder
,03-24 18:29:06.199   822  1009 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-24 18:29:06.201   822  1054 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-24 18:29:06.203  2955  2955 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-24 18:29:06.227  1076  1076 I art     : Explicit concurrent mark sweep GC freed 53485(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 954us total 40.464ms
,03-24 18:29:06.238   822   837 I ActivityManager: Start proc 3875:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-24 18:29:06.243  1263  1263 I ConfigService: onCreate
,03-24 18:29:06.263   822   822 I art     : Explicit concurrent mark sweep GC freed 18246(1431KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 2.238ms total 79.644ms
,03-24 18:29:06.269   822   866 I art     : WaitForGcToComplete blocked for 46.531ms for cause Explicit
,03-24 18:29:06.281  1244  3874 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 18:29:06.289   822  1428 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3251 uid 10095
,03-24 18:29:06.290  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-24 18:29:06.315  1244  3874 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-24 18:29:06.320  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 18:29:06.320  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 18:29:06.341   822   822 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 18:29:06.341   822   822 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 18:29:06.345  1397  1397 I art     : Explicit concurrent mark sweep GC freed 4964(362KB) AllocSpace objects, 10(1188KB) LOS objects, 31% free, 35MB/51MB, paused 1.277ms total 21.747ms
,03-24 18:29:06.353  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,03-24 18:29:06.355  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-24 18:29:06.357  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-24 18:29:06.357  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-24 18:29:06.360  1244  3874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-24 18:29:06.360  1244  3874 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-24 18:29:06.360  1244  3874 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-24 18:29:06.360  1244  3874 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-24 18:29:06.360  1244  3874 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-24 18:29:06.360  1244  3874 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 18:29:06.377  1397  1397 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-24 18:29:06.377  1397  1397 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 18:29:06.409  3875  3909 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 18:29:06.413   822   837 I ActivityManager: Start proc 3910:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-24 18:29:06.423   822   866 I art     : Explicit concurrent mark sweep GC freed 7829(570KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 4.471ms total 150.464ms
,03-24 18:29:06.457  3875  3906 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-24 18:29:06.476   822  1427 I ActivityManager: Start proc 3931:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 18:29:06.481   822  1371 I ActivityManager: Killing 3556:com.android.chrome/u0a40 (adj 15): empty #17
,03-24 18:29:06.493  3858  3858 I art     : System.exit called, status: 0
03-24 18:29:06.493  3858  3858 I AndroidRuntime: VM exiting with result code 0.
,03-24 18:29:06.607  3777  3777 W LocationOracleImpl: Best location was null
,03-24 18:29:06.612  3777  3777 I VS.Container: create_recognizer
,03-24 18:29:06.619  3931  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-24 18:29:06.633   822   866 I ActivityManager: Start proc 3954:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-24 18:29:06.660  1263  1263 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-24 18:29:06.661  1263  1263 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
03-24 18:29:06.662  1263  1263 E AndroidRuntime: FATAL EXCEPTION: main
03-24 18:29:06.662  1263  1263 E AndroidRuntime: Process: com.google.process.gapps, PID: 1263
03-24 18:29:06.662  1263  1263 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-24 18:29:06.662  1263  1263 E AndroidRuntime: 	... 9 more
,03-24 18:29:06.660  3777  3964 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 18:29:06.670  3875  3906 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
03-24 18:29:06.671  3875  3906 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-24 18:29:06.671  3875  3906 E AndroidRuntime: Process: android.process.acore, PID: 3875
03-24 18:29:06.671  3875  3906 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 18:29:06.671  3875  3906 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 18:29:06.684  3777  3900 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:29:06.684  3777  3900 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 18:29:06.684   822  3973 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-24 18:29:06.684  3777  3900 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 18:29:06.685   822   856 D Atlas   : Validating map...
03-24 18:29:06.686  3777  3900 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
,03-24 18:29:06.687   822  3967 E DropBoxManagerService: Can't write: system_app_crash
03-24 18:29:06.687   822  3967 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 18:29:06.687   822  3967 E DropBoxManagerService: 	... 5 more
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.o,s.Looper.loop(Looper.java:135)
03-24 18:29:06.690  3931  3962 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-24 18:29:06.690  3931  3962 E AndroidRuntime: Process: com.android.keychain, PID: 3931
03-24 18:29:06.690  3931  3962 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 18:29:06.690  3931  3962 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: Can't write: system_app_crash
03-24 18:29:06.700   822  3984 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 18:29:06.700   822  3984 E DropBoxManagerService: 	... 5 more
03-24 18:29:06.706   822  3983 E DropBoxManagerService: Can't write: system_app_crash
03-24 18:29:06.706   822  3983 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 18:29:06.706   822  3983 E DropBoxManagerService: 	... 5 more
03-24 18:29:06.708  3777  3986 I HotwordRecognitionRnr: Starting hotword detection.
03-24 18:29:06.712  3777  3987 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@1311cde
03-24 18:29:06.720   359  3990 I AudioFlinger: AudioFlinger's thread 0xb4d67000 ready to run
03-24 18:29:06.724   359  1037 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 18:29:06.726  3777  3987 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@1311cde
,03-24 18:29:06.736   359  3990 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-24 18:29:06.736   359  3990 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-24 18:29:06.736   359  3990 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-24 18:29:06.736   359  3990 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
03-24 18:29:06.743   359  3990 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
03-24 18:29:06.759   822  3973 I OpenGLRenderer: Initialized EGL, version 1.4
03-24 18:29:06.765   822  3973 D OpenGLRenderer: Enabling debug mode 0
,03-24 18:29:06.827  3777  3777 I HotwordWorker: onReady
,03-24 18:29:06.843  3777  3997 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 18:29:06.851  1815  1909 W Icing   : Received bad json for section weights override -- ignoring.
03-24 18:29:06.851  1815  1909 W Icing   : Received bad json for corpus context scoring override -- ignoring.
03-24 18:29:06.851  1815  1909 W Icing   : Received bad json for section weights override -- ignoring.
03-24 18:29:06.851  1815  1909 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-24 18:29:06.856  3777  3953 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-24 18:29:06.856  3777  3953 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 18:29:06.861  3777  3998 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 18:29:06.880  3777  3999 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
03-24 18:29:06.880  3777  3953 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-24 18:29:06.880  3777  3953 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 18:29:06.960  3777  3777 I HotwordDetector: Closing mic
03-24 18:29:06.960  3777  3963 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1311cde
,03-24 18:29:06.976   822  1285 E QMI_FW  : xport_send: Sendto failed for port 4352
03-24 18:29:06.976   822  1285 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-24 18:29:06.976   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658045715
03-24 18:29:06.976   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 18:29:06.990  3777  4001 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 18:29:07.007   822  1285 E QMI_FW  : xport_send: Sendto failed for port 4352
03-24 18:29:07.007   822  1285 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-24 18:29:07.007   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658045715
03-24 18:29:07.007   822  1285 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 18:29:07.013  3777  3777 W TRUiThreadExecutor: Task does not implement UiTask: com.google.common.g.a.p@3401b33
,03-24 18:29:07.023   822  1282 I ActivityManager: Killing 3601:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-24 18:29:07.026   359  3990 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-24 18:29:07.026   359  3990 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-24 18:29:07.030   260   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 18:29:07.032   359  1037 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 18:29:07.035  3777  3986 I HotwordRecognitionRnr: Hotword detection finished
03-24 18:29:07.036  3777  3972 I HotwordRecognitionRnr: Stopping hotword detection.

```
