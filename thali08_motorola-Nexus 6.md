#### Test 6391070405f2a33_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-24 15:29:11.267  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 15:29:11.359  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 15:29:11.359  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:11.360  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:11.360  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 15:29:11.371  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 15:29:11.392  2732  2732 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 15:29:11.393  2732  2732 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 15:29:11.393  2732  2732 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 15:29:11.988  3240  3240 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 15:29:11.991  3240  3240 D AndroidRuntime: CheckJNI is OFF
03-24 15:29:12.115  3240  3240 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 15:29:12.120   822  1213 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 15:29:12.152   822  1213 V WindowManager: addAppToken: AppWindowToken{3cb649d6 token=Token{15d039f1 ActivityRecord{29f7bd98 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 15:29:12.159  3240  3240 D AndroidRuntime: Shutting down VM
03-24 15:29:12.159   822   861 V WindowManager: Adding window Window{237b3629 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3ac29f80 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 15:29:12.162  1500  1500 I HotwordDetector: Closing mic
03-24 15:29:12.163  1500  1764 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@296a8c8a
03-24 15:29:12.215   822  1623 I ActivityManager: Start proc 3254:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 15:29:12.241   358  1770 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 15:29:12.242   358  1770 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 15:29:12.249   358  1018 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 15:29:12.253  1500  1766 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 15:29:12.253  1500  1767 I HotwordRecognitionRnr: Hotword detection finished
03-24 15:29:12.266   822   840 I ActivityManager: Killing 2862:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-24 15:29:12.319   822   840 I ActivityManager: Killing 2690:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-24 15:29:12.504  3254  3254 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 15:29:12.521  3254  3254 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1956-1959)
,03-24 15:29:12.521  3254  3254 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 15:29:12.535   822  1623 I art     : Explicit concurrent mark sweep GC freed 42988(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.831ms total 81.360ms
03-24 15:29:12.535   822  1255 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658418451
03-24 15:29:12.535   822  1255 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 15:29:12.542  3254  3254 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a27b34d}
,03-24 15:29:12.543  3254  3254 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 15:29:12.544  3254  3254 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 15:29:12.555  3254  3254 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 15:29:12.556  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:12.556  3254  3254 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 15:29:12.562  3254  3278 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 15:29:12.567  3254  3254 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-24 15:29:12.571  3254  3254 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 15:29:12.571  3254  3254 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 15:29:12.571  3254  3254 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 15:29:12.620   877   877 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 15:29:12.620   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 15:29:12.636   822   860 D BluetoothManagerService: Message: 20
,03-24 15:29:12.636   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19ee5e:true
,03-24 15:29:12.662   877   877 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-24 15:29:12.662   877   877 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 15:29:12.671  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 15:29:12.679  3254  3254 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 15:29:12.692  3254  3254 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 15:29:12.698  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:12.698  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 15:29:12.768  3254  3301 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 15:29:12.773  3254  3254 D Atlas   : Validating map...
,03-24 15:29:12.787   822  1213 V WindowManager: Adding window Window{3b4cab0e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{237b3629 u0 Starting com.test.thalitest})
,03-24 15:29:12.790  3254  3288 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 15:29:12.830  3254  3301 I OpenGLRenderer: Initialized EGL, version 1.4,
,03-24 15:29:12.844  3254  3301 D OpenGLRenderer: Enabling debug mode 0
,03-24 15:29:12.962  1238  1238 I Keyboard.Facilitator: onFinishInput()
03-24 15:29:12.962   822   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +801ms
,03-24 15:29:12.967   822   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-24 15:29:12.981   822   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,03-24 15:29:13.018   260  3304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (175 us)
,03-24 15:29:13.042  3254  3254 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3254
,03-24 15:29:13.150  3254  3254 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 15:29:13.304  3254  3303 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580504064
,03-24 15:29:13.309  3254  3303 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 15:29:13.309  3254  3303 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 15:29:13.309  3254  3303 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 15:29:13.309  3254  3303 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 15:29:13.309  3254  3303 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 15:29:13.309  3254  3303 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0cb5ae added. We now have 1 listener(s)
03-24 15:29:13.310   822  1190 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:29:13.314  3254  3303 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-24 15:29:13.317  3254  3303 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 15:29:13.318  3254  3303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 15:29:13.318  3254  3303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 15:29:13.323  3254  3303 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26263e5 added. We now have 1 listener(s)
03-24 15:29:13.323  3254  3303 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 15:29:13.328   822  1025 D WifiService: New client listening to asynchronous messages
,03-24 15:29:13.331  3254  3303 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 15:29:13.334  3254  3303 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 15:29:13.334  3254  3303 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-24 15:29:13.334  3254  3303 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 15:29:13.334  3254  3303 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 15:29:13.339  3254  3303 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:29:13.340   822  1216 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:29:13.342  3254  3303 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 15:29:13.348  3254  3303 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 15:29:13.348  3254  3303 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 15:29:13.348  3254  3303 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-24 15:29:13.349  3254  3254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 15:29:13.350  3254  3303 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 15:29:13.384  3254  3254 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 15:29:13.560   260   260 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-24 15:29:13.560   260   260 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-24 15:29:13.560   822   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-24 15:29:13.561   822   822 V ActivityManager: Display changed displayId=0
,03-24 15:29:13.657   877   877 I kickstart: STATUS: Received file 'm9kefs2'
03-24 15:29:13.657   877   877 I kickstart: STATUS: 950272 bytes transferred in 0.994822 seconds
03-24 15:29:13.657   877   877 I kickstart: STATUS: Successfully downloaded files from target 
03-24 15:29:13.657   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 15:29:13.660   877   877 I kickstart: STATUS: Sahara protocol completed,
,03-24 15:29:13.812   260   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 15:29:13.815   260   260 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-24 15:29:13.815   822  1044 D SurfaceControl: Excessive delay in setPowerMode(): 255ms
03-24 15:29:13.821   822   863 I DreamManagerService: Entering dreamland.
,03-24 15:29:13.826   822   863 I PowerManagerService: Dozing...
,03-24 15:29:13.827   822   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 15:29:13.835   358  1412 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-24 15:29:13.836   358  1412 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-24 15:29:13.842   822  1024 E WifiStateMachine: cancelDelayedScan -> 16
,03-24 15:29:13.849   822  1024 E native  : do suspend false
,03-24 15:29:13.885  1238  1238 I Keyboard.Facilitator: onFinishInput()
,03-24 15:29:13.891   822  1024 E WifiStateMachine: cancelDelayedScan -> 18
,03-24 15:29:13.936   822  1024 E native  : do suspend true
,03-24 15:29:14.008   358  1032 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 15:29:14.008   358  1032 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 15:29:14.022  3254  3314 W jxcore-log: Initializing JXcore engine
03-24 15:29:14.022  3254  3314 W jxcore-log: JXcore engine is ready
,03-24 15:29:14.046   822  1024 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-24 15:29:14.059  3314  3314 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9667]" dev="sockfs" ino=9667 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 15:29:14.059  3314  3314 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-24 15:29:14.059  3314  3314 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10792]" dev="sockfs" ino=10792 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 15:29:14.059  3314  3314 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20086]" dev="sockfs" ino=20086 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
03-24 15:29:14.077  3254  3314 W jxcore-log: Starting JXcore engine
,03-24 15:29:14.151  3254  3314 W jxcore-log: Platform android
03-24 15:29:14.151  3254  3314 W jxcore-log: 
,03-24 15:29:14.151  3254  3314 W jxcore-log: Process ARCH arm
03-24 15:29:14.151  3254  3314 W jxcore-log: 
,03-24 15:29:14.349  3254  3314 I jxcore-log: JXcore Cordova bridge is ready!
,03-24 15:29:14.349  3254  3314 I jxcore-log: 
03-24 15:29:14.349  3254  3314 W jxcore-log: JXcore engine is started
,03-24 15:29:14.366  3254  3303 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 15:29:14.370  3254  3254 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 15:29:14.515   822  1024 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-24 15:29:16.402  1132  1132 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
,03-24 15:29:16.833  1132  1132 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 15:29:16.868  1132  1132 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-24 15:29:16.868  1132  1132 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 15:29:16.892   822  1024 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-24 15:29:16.892   822  1024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
03-24 15:29:16.894   822  1026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 15:29:16.900   822  1024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 15:29:16.910   354   813 D CommandListener: Setting iface cfg
,03-24 15:29:16.918   822  1024 E WifiStateMachine: Start Dhcp Watchdog 1
,03-24 15:29:16.924   822  1024 E WifiStateMachine:  WifiLinkLayerStats: 
,03-24 15:29:16.924   822  1024 E WifiStateMachine:  my bss beacon rx: 1
03-24 15:29:16.924   822  1024 E WifiStateMachine:  RSSI mgmt: -43
03-24 15:29:16.924   822  1024 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-24 15:29:16.924   822  1024 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 15:29:16.924   822  1024 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 15:29:16.924   822  1024 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 15:29:16.924   822  1024 E WifiStateMachine:  on_time : 0 tx_time=63 rx_time=113 scan_time=0
,03-24 15:29:17.028   822  1024 E native  : do suspend false
,03-24 15:29:17.043   822  1024 E WifiStateMachine: scanCount==0 - aborting
,03-24 15:29:17.304  3320  3320 I dhcpcd  : version 5.5.6 starting
,03-24 15:29:17.357  3320  3320 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 15:29:17.470  3320  3320 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-24 15:29:17.502  3320  3320 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-24 15:29:17.863   822  1024 E native  : do suspend true
,03-24 15:29:17.903   822  1026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,03-24 15:29:17.908   822  1026 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 15:29:17.909   822  1024 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 15:29:17.941   822  1026 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-24 15:29:17.941   822  1026 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-24 15:29:17.944   822  1026 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 15:29:17.946   822  1026 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 15:29:17.948   822  1026 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 15:29:17.962   822  1026 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 15:29:17.969   822  1026 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-24 15:29:17.969   822  3318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-24 15:29:17.969   822  3318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
,03-24 15:29:17.969   822  3318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-24 15:29:17.970   822  3318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 15:29:17.971   822  1026 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 15:29:17.971   822  1026 D ConnectivityService:    accepting network in place of null
,03-24 15:29:17.972   822  1026 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
03-24 15:29:17.973   822  1026 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 15:29:17.976   822  1026 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100],
03-24 15:29:17.977  1068  1547 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 15:29:17.977   822  1026 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 15:29:17.977   822  1026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-24 15:29:17.978   822  1026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,03-24 15:29:17.981   822   860 D Tethering: MasterInitialState.processMessage what=3
,03-24 15:29:17.984   822  1106 V BackupManagerService: Scheduling immediate backup pass
03-24 15:29:17.986   822   822 V BackupManagerService: Running a backup pass
,03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:29:17.989  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 15:29:17.989  3254  3254 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-24 15:29:17.991  2918  2918 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-24 15:29:17.993   822  1043 V BackupManagerService: clearing pending backups
,03-24 15:29:18.003   822  1043 V PerformBackupTask: Beginning backup of 14 targets
,03-24 15:29:18.007  2918  2918 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
03-24 15:29:18.009   822  1043 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 15:29:18.019   822  1043 V BackupServiceBinder: doBackup() invoked
,03-24 15:29:18.021   822  1043 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 15:29:18.037  1283  2948 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 15:29:18.037  1283  2948 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-24 15:29:18.038   822   855 D TelephonyManager: getDataEnabled: retVal=false
,03-24 15:29:18.048   822  1043 I BackupRestoreController: Getting widget state for user: 0
,03-24 15:29:18.062   822  1216 I ActivityManager: Start proc 3361:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 15:29:18.091   822   855 E GpsLocationProvider: No APN found to select.
,03-24 15:29:18.132   822  1259 D AlarmManagerService: Setting time of day to sec=1458829758
03-24 15:29:18.077   822  1259 W AlarmManagerService: Unable to set rtc to 1458829758: Invalid argument
,03-24 15:29:18.100   822  3381 D GpsLocationProvider: NTP server returned: 1458829758118 (Thu Mar 24 15:29:18 GMT+01:00 2016) reference: 167592 certainty: 26 system time offset: 19
,03-24 15:29:18.128   822  3318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 14:29:17 GMT], X-Android-Received-Millis=[1458829758128], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458829758102]}
03-24 15:29:18.129   822  3318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 15:29:18.129   822  1026 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 15:29:18.129   822  1026 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 15:29:18.129   822  1026 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 15:29:18.129   822  1026 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 15:29:18.129   822  1026 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 15:29:18.129   822  1026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 15:29:18.130  1068  1547 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 15:29:18.135  1808  1825 W GmsBackupTransport: Unknown package in backup request: @pm@
03-24 15:29:18.135  1808  1825 V GmsBackupTransport: starting performBackup for @pm@
,03-24 15:29:18.139  1772  3397 W DriveInitializer: Background init thread started
,03-24 15:29:18.143  1808  1825 V GmsBackupTransport: performBackup done for @pm@
,03-24 15:29:18.151  1772  3398 W DriveInitializer: Awaiting to be initialized
,03-24 15:29:18.156  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:18.161  1772  3380 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 15:29:18.187   822  1213 I ActivityManager: Start proc 3399:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 15:29:18.197   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 8.662ms
,03-24 15:29:18.207   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 10.117ms
,03-24 15:29:18.217   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 8.791ms
,03-24 15:29:18.225  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 15:29:18.225  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:18.226  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:18.226  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:18.229  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:18.258  3399  3399 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
03-24 15:29:18.259  3361  3409 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:29:18.272  1321  1908 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:29:18.272  1321  1908 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:29:18.272  1321  1908 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:29:18.272  1321  1908 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 15:29:18.272  1321  1908 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 15:29:18.272  1321  1908 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 15:29:18.272  1321  1908 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 15:29:18.293  1808  1871 W GmsBackupTransport: Error sending final backup to server: 
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 15:29:18.293  1808  1871 W GmsBackupTransport: 	... 1 more
,03-24 15:29:18.294   822  1043 D BackupManagerService: Now staging backup of com.google.android.talk,
03-24 15:29:18.295  3399  3399 D SprintDMHelper: simOperator:  IMSI: null
03-24 15:29:18.295  3399  3399 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-24 15:29:18.303  1321  1617 I art     : Explicit concurrent mark sweep GC freed 18690(960KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.130ms total 47.960ms
,03-24 15:29:18.312   822  1043 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-24 15:29:18.323   822  1043 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 15:29:18.331   822  1043 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 15:29:18.341   822  1043 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 15:29:18.343   822  1043 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 15:29:18.349   822  1043 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 15:29:18.351   822  1043 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 15:29:18.353  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:29:18.354  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:18.354  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:18.354  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:18.356  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:18.358   822  1043 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 15:29:18.361   822  1043 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 15:29:18.368   822  1043 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 15:29:18.369  1772  1772 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 15:29:18.372   822  1043 D BackupManagerService: Now staging backup of com.android.vending
,03-24 15:29:18.374   822  1043 D BackupManagerService: Now staging backup of android
,03-24 15:29:18.380  1772  3397 W DriveInitializer: Background init thread ended
,03-24 15:29:18.385   822  1043 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
03-24 15:29:18.386  1772  1772 D SystemUpdateService: onCreate
,03-24 15:29:18.389  1772  1772 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 15:29:18.396  1808  1825 I GmsBackupTransport: Next backup will happen in 43199879 millis.
,03-24 15:29:18.402   822  1043 I BackupManagerService: Backup pass finished.
,03-24 15:29:18.404  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:29:18.404  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:18.404  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:18.404  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:18.408  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 15:29:18.408  3361  3409 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:29:18.409  3361  3409 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:29:18.423  1772  3428 I SystemUpdateService: active receiver: enabled
,03-24 15:29:18.428  1772  3428 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-24 15:29:18.436  1772  3428 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 15:29:18.436  1772  3428 I SystemUpdateService: now status is 0 (complete)
03-24 15:29:18.436  1772  3428 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 15:29:18.436  1772  3428 I SystemUpdateService: file has been verified
03-24 15:29:18.436  1772  3428 I SystemUpdateService: OTA package size = 25802302
,03-24 15:29:18.439  1772  3428 I SystemUpdateService: showing system update notification
,03-24 15:29:18.459  1772  3433 I iu.SyncManager: SYNC; picasa accounts
,03-24 15:29:18.463  1772  1772 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-24 15:29:18.467   822   822 I ValidateNoPeople: skipping global notification
,03-24 15:29:18.472  3361  3434 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:29:18.474  1772  1772 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-24 15:29:18.483  1772  3433 I iu.UploadsManager: num queued entries: 0
,03-24 15:29:18.484  1772  3433 I iu.UploadsManager: num updated entries: 0
03-24 15:29:18.485  1772  3433 I iu.SyncManager: NEXT; no task
,03-24 15:29:18.513   822   855 I ActivityManager: Start proc 3436:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 15:29:18.522  1772  1772 D SystemUpdateService: onDestroy
,03-24 15:29:18.535  3078  3395 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:29:18.535  3078  3395 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:29:18.535  3078  3395 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	... 12 more
03-24 15:29:18.535  3078  3395 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at fal.a(PG:38)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:29:18.535  3078  3395 E HttpOperation: 	... 14 more
,03-24 15:29:18.536  1772  1772 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-24 15:29:18.538  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 15:29:18.539  1772  1772 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-24 15:29:18.584   822  1623 I art     : Explicit concurrent mark sweep GC freed 51762(2MB) AllocSpace objects, 6(137KB) LOS objects, 32% free, 33MB/49MB, paused 1.259ms total 54.606ms
,03-24 15:29:18.614  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 15:29:18.614  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:18.614  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:18.614  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:18.624   822  1624 I ActivityManager: Start proc 3461:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 15:29:18.653  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:29:18.653  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:18.653  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:18.653  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:18.657  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:18.662  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:18.669  3078  3395 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:29:18.669  3078  3395 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at hec.a(PG:42)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at hee.a(PG:102)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at czr.a(PG:65)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at kka.a(PG:108)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:29:18.669  3078  3395 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	... 15 more
03-24 15:29:18.669  3078  3395 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at fal.a(PG:38)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:29:18.669  3078  3395 E HttpOperation: 	... 17 more
03-24 15:29:18.669  3078  3395 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:29:18.669  3078  3395 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	... 15 more
03-24 15:29:18.669  3078  3395 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:29:18.669  3078  3395 E ExperimentLoader: 	... 17 more
03-24 15:29:18.699  3361  3434 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:29:18.700  3361  3434 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:29:18.764   822  2340 I ActivityManager: Killing 2898:com.android.settings/1000 (adj 15): empty #17
03-24 15:29:18.764   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 37813, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:29:18.834  3132  3458 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 15:29:19.001   822  2340 I ActivityManager: Killing 2444:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 15:29:19.017  3461  3461 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 15:29:19.017  3461  3461 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 15:29:19.017  3461  3461 I GAv4    :   adb logcat -s GAv4
,03-24 15:29:19.140  1321  3488 D GCM     : Connected
,03-24 15:29:19.219  3461  3461 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:29:19.238  1321  3488 D GCM     : Message class com.google.f.a.a.p
,03-24 15:29:19.255  3461  3461 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:29:19.265  3461  3491 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:29:19.280   822   855 I ActivityManager: Start proc 3492:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 15:29:19.355  1321  3511 I VacuumService: Vacuum at: now=1458829759355 tag=VacuumService
,03-24 15:29:19.359  3436  3510 V KeepSync: Connecting to GoogleApiClient
03-24 15:29:19.362  1321  3512 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 15:29:19.372  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:19.454  1321  1617 I art     : Explicit concurrent mark sweep GC freed 23730(1346KB) AllocSpace objects, 4(252KB) LOS objects, 38% free, 25MB/41MB, paused 934us total 23.335ms
,03-24 15:29:19.470  1772  3515 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 15:29:19.475  1772  3515 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 15:29:19.498  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 15:29:19.498  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:19.498  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:19.498  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:19.501  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: Handling authorization failure
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:29:19.514  1772  3515 E ClientConnectionOperation: 	... 7 more
,03-24 15:29:19.517  3436  3510 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 15:29:19.518  3436  3510 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 15:29:19.519  3461  3461 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-24 15:29:19.521  3436  3510 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 15:29:19.521  3436  3510 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:29:19.531  3461  3461 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9021-9024)
03-24 15:29:19.531  3461  3461 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 15:29:19.540  3461  3461 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15401ff8}
03-24 15:29:19.541  3461  3461 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 15:29:19.541  3461  3461 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 15:29:19.548  3461  3461 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 15:29:19.549  3461  3461 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:29:19.550  3461  3461 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 15:29:19.564  3461  3461 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 15:29:19.568  3461  3461 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 15:29:19.568  3461  3461 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 15:29:19.568  3461  3461 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 15:29:19.639  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 15:29:19.639  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:19.639  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:19.639  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:19.641  3461  3546 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 15:29:19.644  3461  3461 I NSApplication: Starting up...
,03-24 15:29:19.669   822  1293 I ActivityManager: Start proc 3552:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 15:29:19.684  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:19.735  3436  3510 E KeepSync: IOException
03-24 15:29:19.735  3436  3510 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:29:19.735  3436  3510 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:29:19.735  3436  3510 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:29:19.735  3436  3510 E KeepSync: 	... 10 more
03-24 15:29:19.735  3436  3510 W KeepSync: Sync result 2
,03-24 15:29:19.736  3492  3492 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-24 15:29:19.744  3492  3492 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 15:29:19.751   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37818, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:29:19.756   822  1190 I ActivityManager: Killing 2985:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 15:29:19.872  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:19.946  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:19.958  3492  3575 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:29:20.049  1321  3512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 15:29:20.049  1321  3512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:20.049  1321  3512 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:20.049  1321  3512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:20.052  1321  3512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:20.071  1321  3512 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:29:20.071  1321  3512 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:29:20.071  1321  3512 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:29:20.088   822  1190 I ActivityManager: Start proc 3584:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
03-24 15:29:20.088   822  1190 I ActivityManager: Killing 3005:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 15:29:20.112  3492  3603 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:29:20.379  1321  3512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 15:29:20.379  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:29:20.379  1321  3512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:20.379  1321  3512 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:20.380  1321  3512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 15:29:20.380  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:20.380  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:20.380  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:20.384  1321  3512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:20.386  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:20.455   822  1106 I art     : Explicit concurrent mark sweep GC freed 24042(1093KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.767ms total 67.634ms
,03-24 15:29:20.487  1321  3512 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:29:20.487  1321  3512 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:29:20.487  1321  3512 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:29:20.508  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 15:29:20.509  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:20.509  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:20.509  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:20.512  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:20.521  3492  3603 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:29:20.523  3492  3575 E BooksSync: Soft error
03-24 15:29:20.523  3492  3575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:29:20.523  3492  3575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:29:20.523  3492  3575 E BooksSync: Sync error
03-24 15:29:20.523  3492  3575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:29:20.523  3492  3575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:29:20.523  3492  3575 I BooksSync: Finished books sync
,03-24 15:29:20.528   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37818, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:29:20.529   822  2340 I ActivityManager: Killing 1390:android.process.acore/u0a5 (adj 15): empty #17
,03-24 15:29:20.583   822  2340 I ActivityManager: Killing 3036:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,03-24 15:29:20.804  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:20.975  1321  3512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 15:29:20.975  1321  3512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:20.975  1321  3512 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:20.975  1321  3512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:20.980  1321  3512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:21.008  1321  3512 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:29:21.008  1321  3512 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:29:21.008  1321  3512 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:29:21.044   822  1213 I ActivityManager: Killing 2794:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 15:29:21.287  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:21.328   822  1106 I ActivityManager: Start proc 3610:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 15:29:21.400  3610  3610 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458829761400
03-24 15:29:21.400  3610  3610 D         : TimeServiceNative: User Time to be set is 1458829761400
03-24 15:29:21.400  3610  3610 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 15:29:21.400  3610  3610 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 15:29:21.400  3610  3610 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458829761400
03-24 15:29:21.400  3610  3610 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 15:29:21.400   373   880 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-24 15:29:21.401   373  3627 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458829761400
,03-24 15:29:21.404   373  3627 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458829761400, operation = 0
,03-24 15:29:21.404   373  3627 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 10:41:3
,03-24 15:29:21.406   373  3627 D QC-time-services: Daemon:Value read from RTC seconds = 19132863000
,03-24 15:29:21.408   373  3627 D QC-time-services: Daemon:new time 1458829761400 
,03-24 15:29:21.409   373  3627 D QC-time-services: Daemon: delta 1439696898400 genoff 1439696898400 ,
03-24 15:29:21.409   373  3627 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696898400 to memory
03-24 15:29:21.409   373  3627 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 15:29:21.409   373  3627 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 15:29:21.414   373  3627 D QC-time-services: Updating the TOD offset
03-24 15:29:21.415   373  3627 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696898400 to memory
03-24 15:29:21.415   373  3627 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 15:29:21.415   373  3627 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 15:29:21.418   373  3627 E QC-time-services: Daemon:Update to modem bit set
03-24 15:29:21.418   373  3627 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 15:29:21.418  3610  3610 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-24 15:29:21.418   373  3627 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142864961400
,03-24 15:29:21.461  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:21.489   373   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 15:29:21.495   373   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-24 15:29:21.540   822  1293 I ActivityManager: Start proc 3629:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 15:29:21.569   822  1213 I ActivityManager: Killing 1879:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 15:29:21.707  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:21.749  3629  3629 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 15:29:21.749  3629  3629 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 15:29:21.749  3629  3629 I GAv4    :   adb logcat -s GAv4
,03-24 15:29:21.761  3629  3629 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,03-24 15:29:21.773  3629  3629 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:29:21.787  3629  3648 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:29:21.905  1772  1772 V Herrevad: NQAS connected
,03-24 15:29:21.913  1321  3512 W Uploader:  no longer exists, so no auth token.
,03-24 15:29:21.925  3132  3132 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-24 15:29:21.925  3132  3132 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:29:21.954  1772  1788 I art     : Explicit concurrent mark sweep GC freed 15656(1211KB) AllocSpace objects, 18(288KB) LOS objects, 35% free, 28MB/44MB, paused 1.139ms total 47.243ms
,03-24 15:29:21.966   822  1025 D WifiService: New client listening to asynchronous messages
,03-24 15:29:22.019  1321  3512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 15:29:22.019  1321  3512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:22.019  1321  3512 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:22.019  1321  3512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:22.022  1321  3512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:22.042  1321  3512 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:29:22.042  1321  3512 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:29:22.042  1321  3512 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:29:22.083  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 15:29:22.083  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:22.083  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:22.083  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:22.086  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:22.094  3132  3654 E Babel   : UserRecoverableAuthException.
,03-24 15:29:22.095  3132  3654 E Babel   : eei: BadAuthentication
03-24 15:29:22.095  3132  3654 E Babel   : 	at eeg.a(Unknown Source)
03-24 15:29:22.095  3132  3654 E Babel   : 	at eeg.a(Unknown Source)
03-24 15:29:22.095  3132  3654 E Babel   : 	at eeg.a(Unknown Source)
03-24 15:29:22.095  3132  3654 E Babel   : 	at g.a(Unknown Source)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cae.a(SourceFile:3089)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-24 15:29:22.095  3132  3654 E Babel   : 	at crl.a(SourceFile:492)
03-24 15:29:22.095  3132  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cas.b(SourceFile:106)
03-24 15:29:22.095  3132  3654 E Babel   : 	at cap.d(SourceFile:335)
03-24 15:29:22.095  3132  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-24 15:29:22.096  3132  3654 E Babel   : Error getting auth token
03-24 15:29:22.097  3132  3654 E Babel   : dvm
03-24 15:29:22.097  3132  3654 E Babel   : 	at g.a(Unknown Source)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cae.a(SourceFile:3089)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-24 15:29:22.097  3132  3654 E Babel   : 	at crl.a(SourceFile:492)
03-24 15:29:22.097  3132  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cas.b(SourceFile:106)
03-24 15:29:22.097  3132  3654 E Babel   : 	at cap.d(SourceFile:335)
03-24 15:29:22.097  3132  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-24 15:29:22.101  3132  3654 E Babel   : Account registration failed 1-Redacted-21
,03-24 15:29:22.102  3132  3654 E Babel   : cyp: null -- null
03-24 15:29:22.102  3132  3654 E Babel   : 	at cae.a(SourceFile:3121)
03-24 15:29:22.102  3132  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-24 15:29:22.102  3132  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-24 15:29:22.102  3132  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-24 15:29:22.102  3132  3654 E Babel   : 	at crl.a(SourceFile:492)
03-24 15:29:22.102  3132  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-24 15:29:22.102  3132  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 15:29:22.102  3132  3654 E Babel   : 	at cas.b(SourceFile:106)
03-24 15:29:22.102  3132  3654 E Babel   : 	at cap.d(SourceFile:335)
03-24 15:29:22.102  3132  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-24 15:29:22.118  3132  3654 I art     : Note: end time exceeds epoch: 
03-24 15:29:22.127  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 15:29:22.128  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:22.128  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:22.128  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 15:29:22.131  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:22.139  1321  1909 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 15:29:22.153  3132  3664 E Babel   : Unexpected exception while authenticating.
03-24 15:29:22.154  1321  3512 W Uploader: No account for auth token provided
,03-24 15:29:22.156  3132  3664 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 15:29:22.156  3132  3664 E Babel   : 	at eeg.b(Unknown Source)
03-24 15:29:22.156  3132  3664 E Babel   : 	at eeg.b(Unknown Source)
03-24 15:29:22.156  3132  3664 E Babel   : 	at g.a(Unknown Source)
03-24 15:29:22.156  3132  3664 E Babel   : 	at cae.b(SourceFile:1146)
03-24 15:29:22.156  3132  3664 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 15:29:22.156  3132  3664 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:29:22.156  3132  3664 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:29:22.156  3132  3664 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 15:29:23.197  1321  1907 I art     : Explicit concurrent mark sweep GC freed 42822(2MB) AllocSpace objects, 2(149KB) LOS objects, 36% free, 27MB/43MB, paused 979us total 31.857ms
,03-24 15:29:24.518  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:29:24.518  3254  3314 I jxcore-log: 
,03-24 15:29:24.521  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:29:24.521  3254  3314 I jxcore-log: 
,03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:29:24.529  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:29:24.531  3254  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:29:24.533  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:29:24.533  3254  3314 I jxcore-log: 
,03-24 15:29:24.535  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:29:24.535  3254  3314 I jxcore-log: 
,03-24 15:29:24.749  3492  3571 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 15:29:25.064  3254  3314 I jxcore-log: Unit Test app is loaded
03-24 15:29:25.064  3254  3314 I jxcore-log: 
,03-24 15:29:25.070  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:29:25.070  3254  3314 I jxcore-log: 
,03-24 15:29:25.079  3254  3314 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 15:29:25.081  3254  3314 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 15:29:25.081  3254  3314 I jxcore-log: 
,03-24 15:29:25.083  3254  3314 I jxcore-log: My device name is: motorola-Nexus 6
03-24 15:29:25.083  3254  3314 I jxcore-log: 
,03-24 15:29:25.095  3254  3254 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 15:29:27.172   822  1216 I ActivityManager: Killing 2732:com.android.vending/u0a19 (adj 15): empty #17
,03-24 15:29:28.911  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 15:29:28.911  3254  3314 I jxcore-log: 
,03-24 15:29:29.252  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 15:29:29.252  3254  3314 I jxcore-log: 
,03-24 15:29:29.265  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,03-24 15:29:29.265  3254  3314 I jxcore-log: 
,03-24 15:29:29.270  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
,03-24 15:29:29.270  3254  3314 I jxcore-log: 
,03-24 15:29:29.309  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
,03-24 15:29:29.309  3254  3314 I jxcore-log: 
,03-24 15:29:29.326  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,03-24 15:29:29.326  3254  3314 I jxcore-log: 
,03-24 15:29:29.331  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
,03-24 15:29:29.331  3254  3314 I jxcore-log: 
,03-24 15:29:29.867   822   841 I ActivityManager: Start proc 3672:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-24 15:29:30.032  3672  3672 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-24 15:29:30.127  3672  3672 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-24 15:29:30.208   822  1623 I ActivityManager: Start proc 3708:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-24 15:29:30.222  3672  3672 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-24 15:29:30.225  3672  3672 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-24 15:29:30.263  3708  3708 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 15:29:30.263  3708  3708 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:29:30.274   822  1623 I ActivityManager: Killing 2918:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 15:29:30.279  3672  3687 D Finsky  : [369] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 15:29:30.297  3708  3708 I MultiDex: VM with version 2.1.0 has multidex support
03-24 15:29:30.297  3708  3708 I MultiDex: install
03-24 15:29:30.297  3708  3708 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 15:29:30.392  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:30.397  3672  3672 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-24 15:29:30.397  3672  3672 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-24 15:29:30.403  3672  3672 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-24 15:29:30.418  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 15:29:30.418  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:30.418  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:30.418  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:30.422  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:30.432  3672  3672 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-24 15:29:30.435  3672  3687 D Finsky  : [369] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 15:29:30.456   822  2340 I art     : Explicit concurrent mark sweep GC freed 19246(893KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.256ms total 69.764ms
,03-24 15:29:30.468  3708  3708 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-24 15:29:30.511  3708  3708 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 15:29:30.516  1321  2108 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-24 15:29:30.530  1321  1321 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 15:29:30.534  1772  1772 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-24 15:29:30.577   822   840 I ActivityManager: Start proc 3739:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-24 15:29:30.587  1772  3749 D LocationInitializer: Restart initialization of location
,03-24 15:29:30.608  3739  3739 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 15:29:30.608  3739  3739 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:29:30.641  3739  3739 I MultiDex: VM with version 2.1.0 has multidex support
03-24 15:29:30.641  3739  3739 I MultiDex: install
03-24 15:29:30.641  3739  3739 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 15:29:30.660  3739  3739 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-24 15:29:30.698  3739  3739 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 15:29:30.706  1321  1321 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 15:29:30.707  1321  2112 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-24 15:29:30.710  1772  1772 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-24 15:29:30.715  3739  3739 D WearableService: callingUid 10011, callindPid: 3739
,03-24 15:29:30.727  1772  3762 D LocationInitializer: Restart initialization of location
,03-24 15:29:30.741  1808  2071 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-24 15:29:30.744  1808  2071 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-24 15:29:30.834  3672  3672 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-24 15:29:31.143  3672  3672 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-24 15:29:31.178  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.207  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 15:29:31.208  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:31.208  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:31.208  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:31.214  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.233  3672  3672 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 15:29:31.242  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.262  1321  3605 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:29:31.262  1321  3605 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:31.262  1321  3605 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:31.262  1321  3605 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:31.266  1321  3605 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.285  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.305  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:29:31.305  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:31.305  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:31.305  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:31.309  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.321  3672  3672 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 15:29:31.449  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 15:29:31.449  3254  3314 I jxcore-log: 
,03-24 15:29:31.474  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 15:29:31.474  3254  3314 I jxcore-log: 
,03-24 15:29:31.480  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.482  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 15:29:31.482  3254  3314 I jxcore-log: 
,03-24 15:29:31.525  1321  3605 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:29:31.525  1321  3605 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:29:31.525  1321  3605 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:31.526  1321  3605 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:31.534  1321  3605 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:31.566  3672  3672 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 15:29:31.569  3672  3672 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-24 15:29:31.582  3672  3672 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-24 15:29:31.586  3672  3672 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 275 minutes (failures=4)
,03-24 15:29:31.609  1808  1900 D DeviceConnectionService: client connected with version: 7571000,
,03-24 15:29:31.618  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 15:29:31.618  3254  3314 I jxcore-log: 
,03-24 15:29:31.670  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-24 15:29:31.670  3254  3314 I jxcore-log: 
,03-24 15:29:31.714  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
03-24 15:29:31.714  3254  3314 I jxcore-log: ,
,03-24 15:29:31.850  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 15:29:31.850  3254  3314 I jxcore-log: 
,03-24 15:29:31.855  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 15:29:31.855  3254  3314 I jxcore-log: 
,03-24 15:29:31.861  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 15:29:31.861  3254  3314 I jxcore-log: ,
,03-24 15:29:31.878  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 15:29:31.878  3254  3314 I jxcore-log: 
,03-24 15:29:31.897  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 15:29:31.897  3254  3314 I jxcore-log: 
,03-24 15:29:31.996  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 15:29:31.996  3254  3314 I jxcore-log: 
,03-24 15:29:32.002  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 15:29:32.002  3254  3314 I jxcore-log: 
,03-24 15:29:32.028  3254  3314 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 15:29:32.028  3254  3314 I jxcore-log: 
,03-24 15:29:33.212  3254  3314 I jxcore-log: TAP version 13
03-24 15:29:33.212  3254  3314 I jxcore-log: 
,03-24 15:29:33.215  3254  3314 I jxcore-log: # setup,
,03-24 15:29:33.215  3254  3314 I jxcore-log: 
,03-24 15:29:33.340  3254  3314 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 15:29:33.340  3254  3314 I jxcore-log: 
,03-24 15:29:33.836  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:33.836  3254  3314 I jxcore-log: 
,03-24 15:29:33.841  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 44848,
03-24 15:29:33.841  3254  3314 I jxcore-log: ,
,03-24 15:29:33.848  3254  3314 I jxcore-log: ok 1 Should throw
03-24 15:29:33.848  3254  3314 I jxcore-log: 
,03-24 15:29:33.851  3254  3314 I jxcore-log: # teardown
03-24 15:29:33.851  3254  3314 I jxcore-log: 
,03-24 15:29:34.094  3254  3314 I jxcore-log: # setup
03-24 15:29:34.094  3254  3314 I jxcore-log: 
,03-24 15:29:34.653  3254  3314 I jxcore-log: # 2. emits incomingConnectionState
03-24 15:29:34.653  3254  3314 I jxcore-log: 
,03-24 15:29:34.855  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:29:34.855  3254  3314 I jxcore-log: 
,03-24 15:29:34.859  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 37854,
03-24 15:29:34.859  3254  3314 I jxcore-log: 
,03-24 15:29:34.868  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 15:29:34.868  3254  3314 I jxcore-log: ,
,03-24 15:29:34.872  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:34.872  3254  3314 I jxcore-log: 
,03-24 15:29:34.881  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:34.881  3254  3314 I jxcore-log: 
,03-24 15:29:34.886  3254  3314 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 15:29:34.886  3254  3314 I jxcore-log: 
,03-24 15:29:34.900  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:34.900  3254  3314 I jxcore-log: 
,03-24 15:29:34.901  3254  3314 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 15:29:34.901  3254  3314 I jxcore-log: 
,03-24 15:29:34.908  3254  3314 I jxcore-log: # teardown
03-24 15:29:34.908  3254  3314 I jxcore-log: 
,03-24 15:29:35.031  3254  3314 I jxcore-log: # setup
03-24 15:29:35.031  3254  3314 I jxcore-log: 
,03-24 15:29:35.138  3254  3314 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 15:29:35.138  3254  3314 I jxcore-log: 
,03-24 15:29:35.261  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:35.261  3254  3314 I jxcore-log: 
,03-24 15:29:35.263  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 53223
03-24 15:29:35.263  3254  3314 I jxcore-log: 
,03-24 15:29:35.269  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:35.269  3254  3314 I jxcore-log: 
,03-24 15:29:35.271  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:35.271  3254  3314 I jxcore-log: 
,03-24 15:29:35.272  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:35.272  3254  3314 I jxcore-log: 
,03-24 15:29:35.298  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:35.298  3254  3314 I jxcore-log: 
,03-24 15:29:35.301  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:35.301  3254  3314 I jxcore-log: 
,03-24 15:29:35.306  3254  3314 I jxcore-log: DEBUG createNativeListener: 
03-24 15:29:35.306  3254  3314 I jxcore-log: 
,03-24 15:29:35.307  3254  3314 I jxcore-log: ok 4 tried to connect to right port
03-24 15:29:35.307  3254  3314 I jxcore-log: 
03-24 15:29:35.308  3254  3314 I jxcore-log: ok 5 failed due to refused connection
03-24 15:29:35.308  3254  3314 I jxcore-log: 
03-24 15:29:35.309  3254  3314 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 15:29:35.309  3254  3314 I jxcore-log: 
,03-24 15:29:35.313  3254  3314 I jxcore-log: # teardown
03-24 15:29:35.313  3254  3314 I jxcore-log: 
,03-24 15:29:35.315  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:35.315  3254  3314 I jxcore-log: 
,03-24 15:29:35.474  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:35.474  3254  3314 I jxcore-log: 
,03-24 15:29:35.479  3254  3314 I jxcore-log: # setup
03-24 15:29:35.479  3254  3314 I jxcore-log: 
,03-24 15:29:35.480  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 15:29:35.480  3254  3314 I jxcore-log: 
,03-24 15:29:35.703  3254  3314 I jxcore-log: # 4. native server connections all up
03-24 15:29:35.703  3254  3314 I jxcore-log: 
,03-24 15:29:35.759   822  1624 I ActivityManager: Killing 3399:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-24 15:29:35.838  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:35.838  3254  3314 I jxcore-log: 
,03-24 15:29:35.847  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 37715
03-24 15:29:35.847  3254  3314 I jxcore-log: 
,03-24 15:29:35.862  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:35.862  3254  3314 I jxcore-log: 
,03-24 15:29:35.865  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:35.865  3254  3314 I jxcore-log: 
,03-24 15:29:35.870  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:29:35.870  3254  3314 I jxcore-log: 
,03-24 15:29:35.901  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:35.901  3254  3314 I jxcore-log: 
,03-24 15:29:35.904  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:35.904  3254  3314 I jxcore-log: 
,03-24 15:29:35.907  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:35.907  3254  3314 I jxcore-log: 
,03-24 15:29:35.910  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:35.910  3254  3314 I jxcore-log: 
,03-24 15:29:35.932  3254  3314 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 15:29:35.932  3254  3314 I jxcore-log: 
,03-24 15:29:35.933  3254  3314 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 15:29:35.933  3254  3314 I jxcore-log: 
,03-24 15:29:35.935  3254  3314 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 15:29:35.935  3254  3314 I jxcore-log: 
03-24 15:29:35.935  3254  3314 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 15:29:35.935  3254  3314 I jxcore-log: 
,03-24 15:29:35.946  3254  3314 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 15:29:35.946  3254  3314 I jxcore-log: 
,03-24 15:29:35.955  3254  3314 I jxcore-log: # teardown
03-24 15:29:35.955  3254  3314 I jxcore-log: 
,03-24 15:29:36.054  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.054  3254  3314 I jxcore-log: 
,03-24 15:29:36.060  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.060  3254  3314 I jxcore-log: 
,03-24 15:29:36.062  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:36.062  3254  3314 I jxcore-log: 
,03-24 15:29:36.066  3254  3314 I jxcore-log: # setup
03-24 15:29:36.066  3254  3314 I jxcore-log: 
,03-24 15:29:36.068  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:36.068  3254  3314 I jxcore-log: 
,03-24 15:29:36.201   822  1624 I ActivityManager: Killing 3461:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 15:29:36.232  3254  3314 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 15:29:36.232  3254  3314 I jxcore-log: 
,03-24 15:29:36.359  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:36.359  3254  3314 I jxcore-log: 
,03-24 15:29:36.369  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 33336,
03-24 15:29:36.369  3254  3314 I jxcore-log: 
,03-24 15:29:36.379  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:36.379  3254  3314 I jxcore-log: 
,03-24 15:29:36.382  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:36.382  3254  3314 I jxcore-log: 
,03-24 15:29:36.386  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:36.386  3254  3314 I jxcore-log: 
,03-24 15:29:36.413  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:36.413  3254  3314 I jxcore-log: 
,03-24 15:29:36.415  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:36.415  3254  3314 I jxcore-log: 
,03-24 15:29:36.429  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.429  3254  3314 I jxcore-log: 
,03-24 15:29:36.442  3254  3314 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 15:29:36.442  3254  3314 I jxcore-log: 
,03-24 15:29:36.443  3254  3314 I jxcore-log: ok 13 incoming remains open
03-24 15:29:36.443  3254  3314 I jxcore-log: 
,03-24 15:29:36.449  3254  3314 I jxcore-log: # teardown
03-24 15:29:36.449  3254  3314 I jxcore-log: 
,03-24 15:29:36.570  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:36.570  3254  3314 I jxcore-log: 
,03-24 15:29:36.575  3254  3314 I jxcore-log: # setup
03-24 15:29:36.575  3254  3314 I jxcore-log: 
,03-24 15:29:36.577  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:36.577  3254  3314 I jxcore-log: 
,03-24 15:29:36.668  3254  3314 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 15:29:36.668  3254  3314 I jxcore-log: 
,03-24 15:29:36.796  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:36.796  3254  3314 I jxcore-log: 
,03-24 15:29:36.805  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 57861
03-24 15:29:36.805  3254  3314 I jxcore-log: 
,03-24 15:29:36.813  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:36.813  3254  3314 I jxcore-log: 
,03-24 15:29:36.814  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:36.814  3254  3314 I jxcore-log: 
,03-24 15:29:36.816  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:36.816  3254  3314 I jxcore-log: 
,03-24 15:29:36.826  3254  3314 I jxcore-log: ok 14 we should not have gotten an error
03-24 15:29:36.826  3254  3314 I jxcore-log: 
,03-24 15:29:36.831  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:36.831  3254  3314 I jxcore-log: 
,03-24 15:29:36.836  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:36.836  3254  3314 I jxcore-log: 
,03-24 15:29:36.846  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:36.846  3254  3314 I jxcore-log: 
,03-24 15:29:36.849  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:36.849  3254  3314 I jxcore-log: 
,03-24 15:29:36.857  3254  3314 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 15:29:36.857  3254  3314 I jxcore-log: 
,03-24 15:29:36.857  3254  3314 I jxcore-log: ok 16 incoming is cleaned up
03-24 15:29:36.857  3254  3314 I jxcore-log: 
,03-24 15:29:36.862  3254  3314 I jxcore-log: # teardown
03-24 15:29:36.862  3254  3314 I jxcore-log: 
,03-24 15:29:37.202  3254  3314 I jxcore-log: # setup
,03-24 15:29:37.202  3254  3314 I jxcore-log: 
,03-24 15:29:37.509  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:29:37.650  3254  3314 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
,03-24 15:29:37.650  3254  3314 I jxcore-log: 
,03-24 15:29:38.061  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:29:39.160  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 15:29:39.160  3254  3314 I jxcore-log: 
,03-24 15:29:39.164  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 33194
03-24 15:29:39.164  3254  3314 I jxcore-log: 
,03-24 15:29:39.169  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:39.169  3254  3314 I jxcore-log: 
,03-24 15:29:39.171  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-24 15:29:39.171  3254  3314 I jxcore-log: 
,03-24 15:29:39.175  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:29:39.175  3254  3314 I jxcore-log: 
,03-24 15:29:39.188  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:39.188  3254  3314 I jxcore-log: ,
,03-24 15:29:39.192  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 15:29:39.192  3254  3314 I jxcore-log: 
,03-24 15:29:39.207  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:29:39.207  3254  3314 I jxcore-log: 
,03-24 15:29:39.217  3254  3314 I jxcore-log: ok 17 stream was closed
03-24 15:29:39.217  3254  3314 I jxcore-log: ,
03-24 15:29:39.217  3254  3314 I jxcore-log: ok 18 incoming should survive
,03-24 15:29:39.217  3254  3314 I jxcore-log: 
03-24 15:29:39.218  3254  3314 I jxcore-log: ok 19 mux should have no streams
03-24 15:29:39.218  3254  3314 I jxcore-log: 
,03-24 15:29:39.226  3254  3314 I jxcore-log: # teardown
,03-24 15:29:39.226  3254  3314 I jxcore-log: 
,03-24 15:29:39.799  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 15:29:39.799  3254  3314 I jxcore-log: 
,03-24 15:29:39.807  3254  3314 I jxcore-log: # setup
,03-24 15:29:39.807  3254  3314 I jxcore-log: 
,03-24 15:29:39.809  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:39.809  3254  3314 I jxcore-log: ,
,03-24 15:29:43.284  3254  3314 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 15:29:43.284  3254  3314 I jxcore-log: 
,03-24 15:29:44.315  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:29:44.315  3254  3314 I jxcore-log: 
,03-24 15:29:44.323  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 38334
,03-24 15:29:44.323  3254  3314 I jxcore-log: 
,03-24 15:29:44.330  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:29:44.330  3254  3314 I jxcore-log: 
,03-24 15:29:44.331  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:44.331  3254  3314 I jxcore-log: 
,03-24 15:29:44.334  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:29:44.334  3254  3314 I jxcore-log: 
,03-24 15:29:44.345  3254  3314 I jxcore-log: ok 20 we should not have gotten an error
,03-24 15:29:44.345  3254  3314 I jxcore-log: 
,03-24 15:29:44.352  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 15:29:44.352  3254  3314 I jxcore-log: 
,03-24 15:29:44.356  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:44.356  3254  3314 I jxcore-log: 
,03-24 15:29:44.366  3254  3314 I jxcore-log: ok 21 Buffers are identical,
03-24 15:29:44.366  3254  3314 I jxcore-log: 
,03-24 15:29:44.368  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:44.368  3254  3314 I jxcore-log: 
,03-24 15:29:44.372  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:44.372  3254  3314 I jxcore-log: 
,03-24 15:29:44.375  3254  3314 I jxcore-log: ok 22 native server is nulled out
03-24 15:29:44.375  3254  3314 I jxcore-log: 
,03-24 15:29:44.375  3254  3314 I jxcore-log: ok 23 native server should be closed
03-24 15:29:44.375  3254  3314 I jxcore-log: 
,03-24 15:29:44.375  3254  3314 I jxcore-log: ok 24 incoming has been removed
03-24 15:29:44.375  3254  3314 I jxcore-log: 
03-24 15:29:44.376  3254  3314 I jxcore-log: ok 25 Incoming should be done
03-24 15:29:44.376  3254  3314 I jxcore-log: 
,03-24 15:29:44.376  3254  3314 I jxcore-log: ok 26 The mux object should be closed
03-24 15:29:44.376  3254  3314 I jxcore-log: 
03-24 15:29:44.376  3254  3314 I jxcore-log: ok 27 The mux stream should be closed
03-24 15:29:44.376  3254  3314 I jxcore-log: 
,03-24 15:29:44.378  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:44.378  3254  3314 I jxcore-log: 
,03-24 15:29:44.392  3254  3314 I jxcore-log: # teardown
03-24 15:29:44.392  3254  3314 I jxcore-log: 
,03-24 15:29:45.075  3254  3314 I jxcore-log: # setup
03-24 15:29:45.075  3254  3314 I jxcore-log: 
,03-24 15:29:48.714  3254  3314 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 15:29:48.714  3254  3314 I jxcore-log: 
,03-24 15:29:51.450  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:29:51.450  3254  3314 I jxcore-log: 
,03-24 15:29:51.461  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 58762
03-24 15:29:51.461  3254  3314 I jxcore-log: 
,03-24 15:29:51.479  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.479  3254  3314 I jxcore-log: 
,03-24 15:29:51.480  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.480  3254  3314 I jxcore-log: 
,03-24 15:29:51.482  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.482  3254  3314 I jxcore-log: 
,03-24 15:29:51.485  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.485  3254  3314 I jxcore-log: 
,03-24 15:29:51.486  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.486  3254  3314 I jxcore-log: 
,03-24 15:29:51.487  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.487  3254  3314 I jxcore-log: 
,03-24 15:29:51.490  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.490  3254  3314 I jxcore-log: 
,03-24 15:29:51.491  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.491  3254  3314 I jxcore-log: 
,03-24 15:29:51.492  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.492  3254  3314 I jxcore-log: 
,03-24 15:29:51.496  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.496  3254  3314 I jxcore-log: 
,03-24 15:29:51.498  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.498  3254  3314 I jxcore-log: 
,03-24 15:29:51.499  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.499  3254  3314 I jxcore-log: 
,03-24 15:29:51.504  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.504  3254  3314 I jxcore-log: 
,03-24 15:29:51.505  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.505  3254  3314 I jxcore-log: 
,03-24 15:29:51.506  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.506  3254  3314 I jxcore-log: 
,03-24 15:29:51.508  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.508  3254  3314 I jxcore-log: 
,03-24 15:29:51.509  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.509  3254  3314 I jxcore-log: 
,03-24 15:29:51.510  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.510  3254  3314 I jxcore-log: 
,03-24 15:29:51.512  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.512  3254  3314 I jxcore-log: 
,03-24 15:29:51.512  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.512  3254  3314 I jxcore-log: 
03-24 15:29:51.513  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.513  3254  3314 I jxcore-log: 
03-24 15:29:51.514  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:29:51.514  3254  3314 I jxcore-log: 
03-24 15:29:51.515  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.515  3254  3314 I jxcore-log: 
03-24 15:29:51.516  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.516  3254  3314 I jxcore-log: 
03-24 15:29:51.518  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.518  3254  3314 I jxcore-log: 
,03-24 15:29:51.518  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.518  3254  3314 I jxcore-log: 
03-24 15:29:51.519  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.519  3254  3314 I jxcore-log: 
03-24 15:29:51.521  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:29:51.521  3254  3314 I jxcore-log: 
,03-24 15:29:51.521  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:29:51.521  3254  3314 I jxcore-log: 
03-24 15:29:51.522  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:29:51.522  3254  3314 I jxcore-log: 
,03-24 15:29:51.608  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.608  3254  3314 I jxcore-log: 
,03-24 15:29:51.611  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.611  3254  3314 I jxcore-log: 
,03-24 15:29:51.613  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.613  3254  3314 I jxcore-log: 
,03-24 15:29:51.615  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.615  3254  3314 I jxcore-log: 
,03-24 15:29:51.616  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.616  3254  3314 I jxcore-log: 
,03-24 15:29:51.618  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.618  3254  3314 I jxcore-log: 
,03-24 15:29:51.620  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.620  3254  3314 I jxcore-log: 
,03-24 15:29:51.621  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.621  3254  3314 I jxcore-log: 
,03-24 15:29:51.624  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 15:29:51.624  3254  3314 I jxcore-log: 
03-24 15:29:51.625  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.625  3254  3314 I jxcore-log: 
,03-24 15:29:51.627  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.627  3254  3314 I jxcore-log: 
,03-24 15:29:51.628  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.628  3254  3314 I jxcore-log: 
03-24 15:29:51.629  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.629  3254  3314 I jxcore-log: 
,03-24 15:29:51.631  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.631  3254  3314 I jxcore-log: 
,03-24 15:29:51.632  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.632  3254  3314 I jxcore-log: 
,03-24 15:29:51.633  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.633  3254  3314 I jxcore-log: 
,03-24 15:29:51.635  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.635  3254  3314 I jxcore-log: 
,03-24 15:29:51.636  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.636  3254  3314 I jxcore-log: 
,03-24 15:29:51.638  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.638  3254  3314 I jxcore-log: 
,03-24 15:29:51.639  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.639  3254  3314 I jxcore-log: 
,03-24 15:29:51.643  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.643  3254  3314 I jxcore-log: 
,03-24 15:29:51.644  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.644  3254  3314 I jxcore-log: 
,03-24 15:29:51.646  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.646  3254  3314 I jxcore-log: 
,03-24 15:29:51.647  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.647  3254  3314 I jxcore-log: 
,03-24 15:29:51.649  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.649  3254  3314 I jxcore-log: 
,03-24 15:29:51.651  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.651  3254  3314 I jxcore-log: 
,03-24 15:29:51.652  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.652  3254  3314 I jxcore-log: 
,03-24 15:29:51.653  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.653  3254  3314 I jxcore-log: 
,03-24 15:29:51.654  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.654  3254  3314 I jxcore-log: 
03-24 15:29:51.655  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.655  3254  3314 I jxcore-log: 
,03-24 15:29:51.657  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.657  3254  3314 I jxcore-log: 
03-24 15:29:51.658  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.658  3254  3314 I jxcore-log: 
,03-24 15:29:51.660  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.660  3254  3314 I jxcore-log: 
,03-24 15:29:51.661  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.661  3254  3314 I jxcore-log: 
,03-24 15:29:51.662  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.662  3254  3314 I jxcore-log: 
,03-24 15:29:51.664  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.664  3254  3314 I jxcore-log: 
,03-24 15:29:51.665  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.665  3254  3314 I jxcore-log: 
,03-24 15:29:51.666  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.666  3254  3314 I jxcore-log: 
03-24 15:29:51.667  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.667  3254  3314 I jxcore-log: 
,03-24 15:29:51.668  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.668  3254  3314 I jxcore-log: 
,03-24 15:29:51.670  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.670  3254  3314 I jxcore-log: 
,03-24 15:29:51.671  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.671  3254  3314 I jxcore-log: 
,03-24 15:29:51.672  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.672  3254  3314 I jxcore-log: 
,03-24 15:29:51.674  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.674  3254  3314 I jxcore-log: 
,03-24 15:29:51.675  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.675  3254  3314 I jxcore-log: 
,03-24 15:29:51.676  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.676  3254  3314 I jxcore-log: 
03-24 15:29:51.677  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.677  3254  3314 I jxcore-log: 
,03-24 15:29:51.684  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.684  3254  3314 I jxcore-log: 
,03-24 15:29:51.686  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 15:29:51.686  3254  3314 I jxcore-log: 
03-24 15:29:51.687  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.687  3254  3314 I jxcore-log: 
,03-24 15:29:51.688  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.688  3254  3314 I jxcore-log: 
,03-24 15:29:51.690  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.690  3254  3314 I jxcore-log: 
,03-24 15:29:51.691  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.691  3254  3314 I jxcore-log: 
,03-24 15:29:51.692  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.692  3254  3314 I jxcore-log: 
03-24 15:29:51.693  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.693  3254  3314 I jxcore-log: 
,03-24 15:29:51.694  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.694  3254  3314 I jxcore-log: 
,03-24 15:29:51.695  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.695  3254  3314 I jxcore-log: 
,03-24 15:29:51.698  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.698  3254  3314 I jxcore-log: 
,03-24 15:29:51.699  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.699  3254  3314 I jxcore-log: 
,03-24 15:29:51.700  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.700  3254  3314 I jxcore-log: 
,03-24 15:29:51.701  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.701  3254  3314 I jxcore-log: 
03-24 15:29:51.703  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.703  3254  3314 I jxcore-log: 
03-24 15:29:51.703  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.703  3254  3314 I jxcore-log: 
,03-24 15:29:51.705  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.705  3254  3314 I jxcore-log: 
,03-24 15:29:51.706  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.706  3254  3314 I jxcore-log: 
,03-24 15:29:51.708  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.708  3254  3314 I jxcore-log: 
,03-24 15:29:51.709  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.709  3254  3314 I jxcore-log: 
,03-24 15:29:51.710  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.710  3254  3314 I jxcore-log: 
,03-24 15:29:51.711  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.711  3254  3314 I jxcore-log: 
,03-24 15:29:51.712  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.712  3254  3314 I jxcore-log: 
,03-24 15:29:51.713  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.713  3254  3314 I jxcore-log: 
,03-24 15:29:51.715  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.715  3254  3314 I jxcore-log: 
,03-24 15:29:51.716  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.716  3254  3314 I jxcore-log: 
,03-24 15:29:51.718  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.718  3254  3314 I jxcore-log: 
,03-24 15:29:51.719  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.719  3254  3314 I jxcore-log: 
,03-24 15:29:51.720  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.720  3254  3314 I jxcore-log: 
,03-24 15:29:51.721  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.721  3254  3314 I jxcore-log: 
,03-24 15:29:51.722  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.722  3254  3314 I jxcore-log: 
,03-24 15:29:51.723  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:29:51.723  3254  3314 I jxcore-log: 
,03-24 15:29:51.724  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:29:51.724  3254  3314 I jxcore-log: 
,03-24 15:29:51.796  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.796  3254  3314 I jxcore-log: 
,03-24 15:29:51.798  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.798  3254  3314 I jxcore-log: 
,03-24 15:29:51.799  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.799  3254  3314 I jxcore-log: 
,03-24 15:29:51.801  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.801  3254  3314 I jxcore-log: 
,03-24 15:29:51.802  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.802  3254  3314 I jxcore-log: 
,03-24 15:29:51.803  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.803  3254  3314 I jxcore-log: 
,03-24 15:29:51.804  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.804  3254  3314 I jxcore-log: 
03-24 15:29:51.805  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.805  3254  3314 I jxcore-log: 
,03-24 15:29:51.806  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 15:29:51.806  3254  3314 I jxcore-log: 
03-24 15:29:51.807  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.807  3254  3314 I jxcore-log: 
,03-24 15:29:51.810  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 15:29:51.810  3254  3314 I jxcore-log: 
03-24 15:29:51.811  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.811  3254  3314 I jxcore-log: 
,03-24 15:29:51.812  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.812  3254  3314 I jxcore-log: 
03-24 15:29:51.812  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.812  3254  3314 I jxcore-log: 
,03-24 15:29:51.814  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.814  3254  3314 I jxcore-log: 
,03-24 15:29:51.815  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.815  3254  3314 I jxcore-log: 
03-24 15:29:51.816  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.816  3254  3314 I jxcore-log: 
,03-24 15:29:51.817  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.817  3254  3314 I jxcore-log: 
03-24 15:29:51.818  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:29:51.818  3254  3314 I jxcore-log: 
03-24 15:29:51.819  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.819  3254  3314 I jxcore-log: 
,03-24 15:29:51.820  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.820  3254  3314 I jxcore-log: 
,03-24 15:29:51.820  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.820  3254  3314 I jxcore-log: 
03-24 15:29:51.821  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.821  3254  3314 I jxcore-log: ,
03-24 15:29:51.822  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.822  3254  3314 I jxcore-log: 
,03-24 15:29:51.823  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.823  3254  3314 I jxcore-log: 
,03-24 15:29:51.824  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.824  3254  3314 I jxcore-log: 
,03-24 15:29:51.825  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.825  3254  3314 I jxcore-log: 
,03-24 15:29:51.826  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.826  3254  3314 I jxcore-log: 
03-24 15:29:51.827  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.827  3254  3314 I jxcore-log: 
,03-24 15:29:51.828  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.828  3254  3314 I jxcore-log: 
,03-24 15:29:51.829  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.829  3254  3314 I jxcore-log: 
,03-24 15:29:51.830  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.830  3254  3314 I jxcore-log: 
,03-24 15:29:51.830  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.830  3254  3314 I jxcore-log: 
03-24 15:29:51.831  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.831  3254  3314 I jxcore-log: 
,03-24 15:29:51.832  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.832  3254  3314 I jxcore-log: 
,03-24 15:29:51.833  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.833  3254  3314 I jxcore-log: 
,03-24 15:29:51.834  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.834  3254  3314 I jxcore-log: 
03-24 15:29:51.835  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.835  3254  3314 I jxcore-log: 
,03-24 15:29:51.835  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.835  3254  3314 I jxcore-log: 
,03-24 15:29:51.836  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.836  3254  3314 I jxcore-log: 
,03-24 15:29:51.837  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.837  3254  3314 I jxcore-log: 
,03-24 15:29:51.838  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.838  3254  3314 I jxcore-log: ,
03-24 15:29:51.839  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:29:51.839  3254  3314 I jxcore-log: 
03-24 15:29:51.840  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:29:51.840  3254  3314 I jxcore-log: 
03-24 15:29:51.841  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close,
03-24 15:29:51.841  3254  3314 I jxcore-log: 
,03-24 15:29:51.842  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.842  3254  3314 I jxcore-log: 
,03-24 15:29:51.842  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.842  3254  3314 I jxcore-log: 
,03-24 15:29:51.843  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.843  3254  3314 I jxcore-log: 
,03-24 15:29:51.844  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:29:51.844  3254  3314 I jxcore-log: 
,03-24 15:29:51.845  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:29:51.845  3254  3314 I jxcore-log: 
,03-24 15:29:51.848  3254  3314 I jxcore-log: ok 28 native server is nulled out
,03-24 15:29:51.848  3254  3314 I jxcore-log: 
,03-24 15:29:51.848  3254  3314 I jxcore-log: ok 29 native server should be closed
,03-24 15:29:51.848  3254  3314 I jxcore-log: 
03-24 15:29:51.849  3254  3314 I jxcore-log: ok 30 incoming has been removed
03-24 15:29:51.849  3254  3314 I jxcore-log: 
,03-24 15:29:51.850  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.850  3254  3314 I jxcore-log: 
03-24 15:29:51.850  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 15:29:51.850  3254  3314 I jxcore-log: 
03-24 15:29:51.851  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.851  3254  3314 I jxcore-log: 
,03-24 15:29:51.851  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.851  3254  3314 I jxcore-log: 
03-24 15:29:51.851  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 15:29:51.851  3254  3314 I jxcore-log: 
03-24 15:29:51.852  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.852  3254  3314 I jxcore-log: 
,03-24 15:29:51.852  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.852  3254  3314 I jxcore-log: 
03-24 15:29:51.852  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.852  3254  3314 I jxcore-log: ,
03-24 15:29:51.853  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:29:51.853  3254  3314 I jxcore-log: 
03-24 15:29:51.853  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 15:29:51.853  3254  3314 I jxcore-log: 
,03-24 15:29:51.954  3254  3314 I jxcore-log: # teardown
03-24 15:29:51.954  3254  3314 I jxcore-log: 
,03-24 15:29:52.357  3361  3783 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:29:52.368  3361  3784 V GoogleAuthProtoRequest: [338] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:29:52.417  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:29:52.417  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:52.417  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:52.417  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 15:29:52.417  1321  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:29:52.417  1321  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:52.417  1321  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:29:52.419  1321  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:52.422  1321  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:52.423  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:52.435  3361  3783 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:29:52.435  3361  3784 W ExperimentUpdateService: [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:29:52.436  3361  3784 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:29:52.437  3361  3783 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:29:52.526  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:52.554  1321  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 15:29:52.554  1321  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:29:52.554  1321  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:29:52.554  1321  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:29:52.561  1321  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:29:52.586  3672  3672 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 15:29:52.588  3672  3672 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 15:29:52.589  3672  3672 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 15:29:57.622  3254  3314 I jxcore-log: # setup
03-24 15:29:57.622  3254  3314 I jxcore-log: 
,03-24 15:30:05.012   822  2340 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1099564e}
,03-24 15:30:05.036   822  1623 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1099564e}
,03-24 15:30:05.490  3254  3314 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 15:30:05.490  3254  3314 I jxcore-log: 
,03-24 15:30:13.871  1238  1480 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-24 15:30:13.871  1238  1480 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 15:30:13.900  1321  1321 I ConfigService: onCreate
,03-24 15:30:15.922  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:15.922  3254  3314 I jxcore-log: 
,03-24 15:30:15.936  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 33415,
03-24 15:30:15.936  3254  3314 I jxcore-log: 
,03-24 15:30:15.943  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:30:15.943  3254  3314 I jxcore-log: 
,03-24 15:30:15.945  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:30:15.945  3254  3314 I jxcore-log: 
03-24 15:30:15.946  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:30:15.946  3254  3314 I jxcore-log: 
,03-24 15:30:15.954  3254  3314 I jxcore-log: ok 31 we should not have gotten an error
03-24 15:30:15.954  3254  3314 I jxcore-log: 
,03-24 15:30:15.957  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:30:15.957  3254  3314 I jxcore-log: 
,03-24 15:30:15.962  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:30:15.962  3254  3314 I jxcore-log: 
,03-24 15:30:15.976  3254  3314 I jxcore-log: ok 32 Buffers are identical
03-24 15:30:15.976  3254  3314 I jxcore-log: 
,03-24 15:30:15.978  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:30:15.978  3254  3314 I jxcore-log: 
,03-24 15:30:15.983  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:30:15.983  3254  3314 I jxcore-log: 
,03-24 15:30:16.002  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:30:16.002  3254  3314 I jxcore-log: 
,03-24 15:30:16.003  3254  3314 I jxcore-log: ok 33 server should be fine
03-24 15:30:16.003  3254  3314 I jxcore-log: 
,03-24 15:30:16.003  3254  3314 I jxcore-log: ok 34 server should be open
03-24 15:30:16.003  3254  3314 I jxcore-log: 
03-24 15:30:16.003  3254  3314 I jxcore-log: ok 35 incoming has been removed
03-24 15:30:16.003  3254  3314 I jxcore-log: 
03-24 15:30:16.004  3254  3314 I jxcore-log: ok 36 The mux object should be closed
03-24 15:30:16.004  3254  3314 I jxcore-log: 
,03-24 15:30:16.004  3254  3314 I jxcore-log: ok 37 The mux stream should be closed
03-24 15:30:16.004  3254  3314 I jxcore-log: 
,03-24 15:30:16.012  3254  3314 I jxcore-log: # teardown
03-24 15:30:16.012  3254  3314 I jxcore-log: 
,03-24 15:30:16.229  3254  3314 I jxcore-log: # setup
03-24 15:30:16.229  3254  3314 I jxcore-log: 
,03-24 15:30:18.119  1321  1909 I art     : Explicit concurrent mark sweep GC freed 37207(1942KB) AllocSpace objects, 18(1984KB) LOS objects, 37% free, 26MB/42MB, paused 1.408ms total 55.665ms
,03-24 15:30:18.142  3436  3793 V KeepSync: Connecting to GoogleApiClient
,03-24 15:30:18.212  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:30:18.212  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:30:18.212  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:30:18.212  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:18.215  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:18.226  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 15:30:18.226  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:30:18.227  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:30:18.227  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:18.233  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:18.235  3078  3792 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:30:18.235  3078  3792 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:30:18.235  3078  3792 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	... 12 more
03-24 15:30:18.235  3078  3792 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at fal.a(PG:38)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:30:18.235  3078  3792 E HttpOperation: 	... 14 more
,03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: Handling authorization failure
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:30:18.262  1772  3796 E ClientConnectionOperation: 	... 7 more
,03-24 15:30:18.265  3436  3793 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 15:30:18.267  3436  3793 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:30:18.272  3436  3793 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:30:18.272  3436  3793 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:30:18.337   822  1190 I art     : Explicit concurrent mark sweep GC freed 27899(1304KB) AllocSpace objects, 5(551KB) LOS objects, 32% free, 33MB/49MB, paused 1.905ms total 71.940ms
,03-24 15:30:18.371  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 15:30:18.371  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:30:18.371  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:30:18.372  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:18.375  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:18.385  3078  3792 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:30:18.385  3078  3792 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at hec.a(PG:42)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at hee.a(PG:102)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at czr.a(PG:65)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at kka.a(PG:108)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:30:18.385  3078  3792 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	... 15 more
03-24 15:30:18.385  3078  3792 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at fal.a(PG:38)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:30:18.385  3078  3792 E HttpOperation: 	... 17 more
,03-24 15:30:18.386  3078  3792 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:30:18.386  3078  3792 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: ,	at czr.a(PG:65)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	... 15 more
03-24 15:30:18.386  3078  37,92 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:30:18.386  3078  3792 E ExperimentLoader: 	... 17 more
,03-24 15:30:18.411  1321  3605 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 15:30:18.411  1321  3605 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:30:18.411  1321  3605 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:30:18.411  1321  3605 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:18.415  1321  3605 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:18.451  3436  3793 E KeepSync: IOException
03-24 15:30:18.451  3436  3793 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:30:18.451  3436  3793 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:30:18.451  3436  3793 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:30:18.451  3436  3793 E KeepSync: 	... 10 more
03-24 15:30:18.451  3436  3793 W KeepSync: Sync result 2
,03-24 15:30:18.461   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 199377, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:30:18.502  3254  3314 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up,
03-24 15:30:18.502  3254  3314 I jxcore-log: 
03-24 15:30:18.502   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 198990, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:30:18.513  3492  3800 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:30:18.543  3492  3801 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:30:18.583  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:30:18.583  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:30:18.583  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:30:18.583  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:18.590  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:18.715  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:30:18.715  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:30:18.715  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:30:18.716  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:18.721  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:18.743  3492  3801 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:30:18.745  3492  3800 E BooksSync: Soft error
03-24 15:30:18.745  3492  3800 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:30:18.745  3492  3800 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:30:18.745  3492  3800 E BooksSync: Sync error
03-24 15:30:18.745  3492  3800 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:30:18.745  3492  3800 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:30:18.746  3492  3800 I BooksSync: Finished books sync
,03-24 15:30:18.763   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201605, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 15:30:18.788  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:18.788  3254  3314 I jxcore-log: 
,03-24 15:30:18.792  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 37618,
03-24 15:30:18.792  3254  3314 I jxcore-log: 
,03-24 15:30:18.798  3254  3314 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:30:18.798  3254  3314 I jxcore-log: 
,03-24 15:30:18.800  3254  3314 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:30:18.800  3254  3314 I jxcore-log: 
,03-24 15:30:18.801  3254  3314 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:30:18.801  3254  3314 I jxcore-log: 
,03-24 15:30:18.809  3254  3314 I jxcore-log: ok 38 we should not have gotten an error
03-24 15:30:18.809  3254  3314 I jxcore-log: 
,03-24 15:30:18.813  3254  3314 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:30:18.813  3254  3314 I jxcore-log: 
,03-24 15:30:18.815  3254  3314 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:30:18.815  3254  3314 I jxcore-log: 
,03-24 15:30:18.822  3254  3314 I jxcore-log: ok 39 Buffers are identical
03-24 15:30:18.822  3254  3314 I jxcore-log: 
,03-24 15:30:18.826  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 15:30:18.826  3254  3314 I jxcore-log: 
,03-24 15:30:18.827  3254  3314 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:30:18.827  3254  3314 I jxcore-log: 
,03-24 15:30:18.830  3254  3314 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:30:18.830  3254  3314 I jxcore-log: 
,03-24 15:30:18.835  3254  3314 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:30:18.835  3254  3314 I jxcore-log: 
,03-24 15:30:18.835  3254  3314 I jxcore-log: ok 40 server should be fine
03-24 15:30:18.835  3254  3314 I jxcore-log: 
03-24 15:30:18.836  3254  3314 I jxcore-log: ok 41 server should be open
03-24 15:30:18.836  3254  3314 I jxcore-log: 
03-24 15:30:18.836  3254  3314 I jxcore-log: ok 42 incoming has been removed
03-24 15:30:18.836  3254  3314 I jxcore-log: 
,03-24 15:30:18.837  3254  3314 I jxcore-log: ok 43 The mux object should be closed
03-24 15:30:18.837  3254  3314 I jxcore-log: 
03-24 15:30:18.837  3254  3314 I jxcore-log: ok 44 The mux stream should be closed
03-24 15:30:18.837  3254  3314 I jxcore-log: 
,03-24 15:30:18.848  3254  3314 I jxcore-log: # teardown
03-24 15:30:18.848  3254  3314 I jxcore-log: 
,03-24 15:30:18.975  1321  1321 I ConfigService: onDestroy
,03-24 15:30:19.013  3254  3314 I jxcore-log: # setup
03-24 15:30:19.013  3254  3314 I jxcore-log: 
,03-24 15:30:19.177  3254  3314 I jxcore-log: # 12. closeAll can close even when connections open
03-24 15:30:19.177  3254  3314 I jxcore-log: 
,03-24 15:30:19.461  3254  3314 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 15:30:19.461  3254  3314 I jxcore-log: 
,03-24 15:30:19.466  3254  3314 I jxcore-log: # teardown
03-24 15:30:19.466  3254  3314 I jxcore-log: 
,03-24 15:30:19.603  3254  3314 I jxcore-log: # setup
03-24 15:30:19.603  3254  3314 I jxcore-log: 
,03-24 15:30:19.813  3254  3314 I jxcore-log: # 13. closeAll with promise
03-24 15:30:19.813  3254  3314 I jxcore-log: 
,03-24 15:30:19.946  3254  3314 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 15:30:19.946  3254  3314 I jxcore-log: 
,03-24 15:30:19.951  3254  3314 I jxcore-log: # teardown
03-24 15:30:19.951  3254  3314 I jxcore-log: 
,03-24 15:30:20.078  3254  3314 I jxcore-log: # setup
03-24 15:30:20.078  3254  3314 I jxcore-log: 
,03-24 15:30:20.196  3254  3314 I jxcore-log: # 14. multiplex can send data
03-24 15:30:20.196  3254  3314 I jxcore-log: 
,03-24 15:30:20.417  3254  3314 I jxcore-log: ok 47 String should be length:200
03-24 15:30:20.417  3254  3314 I jxcore-log: 
,03-24 15:30:20.427  3254  3314 I jxcore-log: # teardown
03-24 15:30:20.427  3254  3314 I jxcore-log: 
,03-24 15:30:20.525  3254  3314 I jxcore-log: # setup
03-24 15:30:20.525  3254  3314 I jxcore-log: 
,03-24 15:30:20.682  3254  3314 I jxcore-log: # 15. enqueue and run in order
03-24 15:30:20.682  3254  3314 I jxcore-log: 
,03-24 15:30:20.893  3254  3314 I jxcore-log: ok 48 firstPromise setTimeout
03-24 15:30:20.893  3254  3314 I jxcore-log: 
,03-24 15:30:20.896  3254  3314 I jxcore-log: ok 49 firstPromise result
03-24 15:30:20.896  3254  3314 I jxcore-log: 
,03-24 15:30:20.897  3254  3314 I jxcore-log: ok 50 firstPromise testValue
03-24 15:30:20.897  3254  3314 I jxcore-log: 
,03-24 15:30:21.001  3254  3314 I jxcore-log: ok 51 secondPromise setTimeout
03-24 15:30:21.001  3254  3314 I jxcore-log: 
,03-24 15:30:21.005  3254  3314 I jxcore-log: ok 52 secondPromise result
03-24 15:30:21.005  3254  3314 I jxcore-log: 
,03-24 15:30:21.007  3254  3314 I jxcore-log: ok 53 secondPromise testValue
03-24 15:30:21.007  3254  3314 I jxcore-log: 
,03-24 15:30:21.009  3254  3314 I jxcore-log: ok 54 thirdPromise in promise
03-24 15:30:21.009  3254  3314 I jxcore-log: 
,03-24 15:30:21.012  3254  3314 I jxcore-log: ok 55 thirdPromise result
03-24 15:30:21.012  3254  3314 I jxcore-log: 
,03-24 15:30:21.014  3254  3314 I jxcore-log: ok 56 thirdPromise testValue
03-24 15:30:21.014  3254  3314 I jxcore-log: 
,03-24 15:30:21.022  3254  3314 I jxcore-log: # teardown
03-24 15:30:21.022  3254  3314 I jxcore-log: 
,03-24 15:30:21.184  3254  3314 I jxcore-log: # setup
03-24 15:30:21.184  3254  3314 I jxcore-log: 
,03-24 15:30:21.449  3254  3314 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 15:30:21.449  3254  3314 I jxcore-log: 
,03-24 15:30:21.595  3254  3314 I jxcore-log: ok 57 thirdPromise - first to run
03-24 15:30:21.595  3254  3314 I jxcore-log: 
,03-24 15:30:21.598  3254  3314 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 15:30:21.598  3254  3314 I jxcore-log: 
,03-24 15:30:21.603  3254  3314 I jxcore-log: ok 59 secondPromise - second to run
03-24 15:30:21.603  3254  3314 I jxcore-log: 
,03-24 15:30:21.605  3254  3314 I jxcore-log: ok 60 secondPromise - in catch
03-24 15:30:21.605  3254  3314 I jxcore-log: 
,03-24 15:30:21.608  3254  3314 I jxcore-log: ok 61 firstPromise - third to run
03-24 15:30:21.608  3254  3314 I jxcore-log: 
,03-24 15:30:21.609  3254  3314 I jxcore-log: ok 62 firstPromise - in then
03-24 15:30:21.609  3254  3314 I jxcore-log: 
,03-24 15:30:21.610  3254  3314 I jxcore-log: ok 63 testing promises
03-24 15:30:21.610  3254  3314 I jxcore-log: 
,03-24 15:30:21.612  3254  3314 I jxcore-log: # teardown
03-24 15:30:21.612  3254  3314 I jxcore-log: 
,03-24 15:30:21.752  3254  3314 I jxcore-log: # setup
03-24 15:30:21.752  3254  3314 I jxcore-log: 
,03-24 15:30:21.893  3254  3314 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 15:30:21.893  3254  3314 I jxcore-log: 
,03-24 15:30:22.053  3254  3314 I jxcore-log: ok 64 fourth
03-24 15:30:22.053  3254  3314 I jxcore-log: 
,03-24 15:30:22.056  3254  3314 I jxcore-log: ok 65 fourth
03-24 15:30:22.056  3254  3314 I jxcore-log: 
,03-24 15:30:22.059  3254  3314 I jxcore-log: ok 66 second
03-24 15:30:22.059  3254  3314 I jxcore-log: 
,03-24 15:30:22.062  3254  3314 I jxcore-log: ok 67 secondPromise - in then
03-24 15:30:22.062  3254  3314 I jxcore-log: 
,03-24 15:30:22.181  3254  3314 I jxcore-log: ok 68 first
03-24 15:30:22.181  3254  3314 I jxcore-log: 
,03-24 15:30:22.183  3254  3314 I jxcore-log: ok 69 firstPromise - in catch
03-24 15:30:22.183  3254  3314 I jxcore-log: 
,03-24 15:30:22.185  3254  3314 I jxcore-log: ok 70 third
03-24 15:30:22.185  3254  3314 I jxcore-log: 
,03-24 15:30:22.188  3254  3314 I jxcore-log: ok 71 thirdPromise - in then
03-24 15:30:22.188  3254  3314 I jxcore-log: 
,03-24 15:30:22.189  3254  3314 I jxcore-log: ok 72 testingPromises
03-24 15:30:22.189  3254  3314 I jxcore-log: 
,03-24 15:30:22.194  3254  3314 I jxcore-log: # teardown
03-24 15:30:22.194  3254  3314 I jxcore-log: 
,03-24 15:30:22.293  3254  3314 I jxcore-log: # setup
03-24 15:30:22.293  3254  3314 I jxcore-log: 
,03-24 15:30:22.428  3254  3314 I jxcore-log: # 18. queues handled independently
03-24 15:30:22.428  3254  3314 I jxcore-log: 
,03-24 15:30:22.620  3254  3314 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 15:30:22.620  3254  3314 I jxcore-log: 
,03-24 15:30:22.624  3254  3314 I jxcore-log: # teardown
03-24 15:30:22.624  3254  3314 I jxcore-log: 
,03-24 15:30:22.751  3254  3314 I jxcore-log: # setup
03-24 15:30:22.751  3254  3314 I jxcore-log: 
,03-24 15:30:22.861  3254  3314 I jxcore-log: # 19. basic
03-24 15:30:22.861  3254  3314 I jxcore-log: 
,03-24 15:30:22.976  3254  3314 I jxcore-log: ok 74 sane
03-24 15:30:22.976  3254  3314 I jxcore-log: 
,03-24 15:30:22.983  3254  3314 I jxcore-log: # teardown
03-24 15:30:22.983  3254  3314 I jxcore-log: 
,03-24 15:30:23.095  3254  3314 I jxcore-log: # setup
03-24 15:30:23.095  3254  3314 I jxcore-log: 
,03-24 15:30:23.237  3254  3314 I jxcore-log: # 20. another
03-24 15:30:23.237  3254  3314 I jxcore-log: 
,03-24 15:30:23.406  3254  3314 I jxcore-log: ok 75 sane
03-24 15:30:23.406  3254  3314 I jxcore-log: 
,03-24 15:30:23.412  3254  3314 I jxcore-log: # teardown
03-24 15:30:23.412  3254  3314 I jxcore-log: 
,03-24 15:30:23.573  3254  3314 I jxcore-log: # setup
03-24 15:30:23.573  3254  3314 I jxcore-log: 
,03-24 15:30:23.782  3254  3314 I jxcore-log: # 21. can pass data in setup
03-24 15:30:23.782  3254  3314 I jxcore-log: 
,03-24 15:30:23.984  3254  3314 I jxcore-log: ok 76 test participant has uuid
03-24 15:30:23.984  3254  3314 I jxcore-log: 
,03-24 15:30:23.986  3254  3314 I jxcore-log: ok 77 participant data matches
03-24 15:30:23.986  3254  3314 I jxcore-log: 
03-24 15:30:23.988  3254  3314 I jxcore-log: ok 78 test participant has uuid
03-24 15:30:23.988  3254  3314 I jxcore-log: 
,03-24 15:30:23.988  3254  3314 I jxcore-log: ok 79 participant data matches
03-24 15:30:23.988  3254  3314 I jxcore-log: 
,03-24 15:30:23.989  3254  3314 I jxcore-log: ok 80 test participant has uuid
03-24 15:30:23.989  3254  3314 I jxcore-log: 
03-24 15:30:23.989  3254  3314 I jxcore-log: ok 81 participant data matches
03-24 15:30:23.989  3254  3314 I jxcore-log: 
03-24 15:30:23.991  3254  3314 I jxcore-log: # teardown
03-24 15:30:23.991  3254  3314 I jxcore-log: 
,03-24 15:30:24.132  3254  3314 I jxcore-log: # setup
03-24 15:30:24.132  3254  3314 I jxcore-log: 
,03-24 15:30:24.251  3254  3314 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 15:30:24.251  3254  3314 I jxcore-log: 
,03-24 15:30:24.378  3254  3314 I jxcore-log: ok 82 specific error should be returned
03-24 15:30:24.378  3254  3314 I jxcore-log: 
,03-24 15:30:24.383  3254  3314 I jxcore-log: # teardown
03-24 15:30:24.383  3254  3314 I jxcore-log: 
,03-24 15:30:24.530  3254  3314 I jxcore-log: ok 83 error should be null
03-24 15:30:24.530  3254  3314 I jxcore-log: 
,03-24 15:30:24.531  3254  3314 I jxcore-log: ok 84 error should be null
03-24 15:30:24.531  3254  3314 I jxcore-log: 
,03-24 15:30:24.533  3254  3314 I jxcore-log: # setup
03-24 15:30:24.533  3254  3314 I jxcore-log: 
,03-24 15:30:24.668  3254  3314 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:30:24.668  3254  3314 I jxcore-log: 
,03-24 15:30:24.909  3254  3314 I jxcore-log: ok 85 specific error should be returned
03-24 15:30:24.909  3254  3314 I jxcore-log: 
,03-24 15:30:24.912  3254  3314 I jxcore-log: # teardown
03-24 15:30:24.912  3254  3314 I jxcore-log: 
,03-24 15:30:25.049  3254  3314 I jxcore-log: ok 86 error should be null
03-24 15:30:25.049  3254  3314 I jxcore-log: 
,03-24 15:30:25.049  3254  3314 I jxcore-log: ok 87 error should be null
03-24 15:30:25.049  3254  3314 I jxcore-log: 
03-24 15:30:25.051  3254  3314 I jxcore-log: # setup
03-24 15:30:25.051  3254  3314 I jxcore-log: 
,03-24 15:30:25.150  3254  3314 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-24 15:30:25.150  3254  3314 I jxcore-log: 
,03-24 15:30:25.358  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:25.358  3254  3314 I jxcore-log: 
,03-24 15:30:25.359  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 41242
03-24 15:30:25.359  3254  3314 I jxcore-log: 
03-24 15:30:25.362  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:25.362  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:25.362  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.368  3254  3314 I jxcore-log: ok 88 error should be null
03-24 15:30:25.368  3254  3314 I jxcore-log: 
,03-24 15:30:25.368  3254  3314 I jxcore-log: ok 89 error should be null
03-24 15:30:25.368  3254  3314 I jxcore-log: 
03-24 15:30:25.369  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:25.369  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:25.369  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.371  3254  3314 I jxcore-log: ok 90 error should be null
03-24 15:30:25.371  3254  3314 I jxcore-log: 
03-24 15:30:25.371  3254  3314 I jxcore-log: ok 91 error should be null
03-24 15:30:25.371  3254  3314 I jxcore-log: 
,03-24 15:30:25.375  3254  3314 I jxcore-log: # teardown,
03-24 15:30:25.375  3254  3314 I jxcore-log: 
,03-24 15:30:25.570  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:25.570  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:25.570  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:25.574  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:25.574  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:25.574  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 15:30:25.579  3254  3314 I jxcore-log: ok 92 error should be null
03-24 15:30:25.579  3254  3314 I jxcore-log: 
03-24 15:30:25.579  3254  3314 I jxcore-log: ok 93 error should be null
03-24 15:30:25.579  3254  3314 I jxcore-log: 
,03-24 15:30:25.587  3254  3314 I jxcore-log: # setup
03-24 15:30:25.587  3254  3314 I jxcore-log: 
,03-24 15:30:25.714  3254  3314 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 15:30:25.714  3254  3314 I jxcore-log: 
,03-24 15:30:25.899  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:25.899  3254  3314 I jxcore-log: 
,03-24 15:30:25.901  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 48723
03-24 15:30:25.901  3254  3314 I jxcore-log: 
,03-24 15:30:25.911  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 15:30:25.911  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:25.912  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:25.912  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 15:30:25.912  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:25.912  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:25.920  3254  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:25.921   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:25.930  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:25.947  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:25.947  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:25.948  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:25.951  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:25.971  2152  2168 D BtGatt.GattService: registerClient() - UUID=d37cf62d-c47d-4f98-a5a6-b0d54f916039,
03-24 15:30:25.974  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=d37cf62d-c47d-4f98-a5a6-b0d54f916039, clientIf=5
,03-24 15:30:25.977  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:30:25.980  2152  2218 D BtGatt.GattService: start scan with filters,
,03-24 15:30:25.987  2152  2227 D BtGatt.ScanManager: handling starting scan
,03-24 15:30:25.988  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 15:30:25.989  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:30:25.989  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 15:30:25.989  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:25.989  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:25.990  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:25.990  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:25.990  2152  2227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616fe02
,03-24 15:30:25.991   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:25.995  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:25.995  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:25.996  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:30:25.996  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:25.997  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:25.997  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:26.002  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 15:30:26.002  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:26.004  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:26.004  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:26.005  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan,
,03-24 15:30:26.005  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:26.007  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:26.007  3254  3314 I jxcore-log: 
03-24 15:30:26.007  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:30:26.007  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:26.008  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 15:30:26.009  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 15:30:26.009  3254  3314 I jxcore-log: 
03-24 15:30:26.009  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:26.011  3254  3314 I jxcore-log: ok 94 error should be null
03-24 15:30:26.011  3254  3314 I jxcore-log: 
03-24 15:30:26.011  3254  3314 I jxcore-log: ok 95 error should be null
03-24 15:30:26.011  3254  3314 I jxcore-log: 
,03-24 15:30:26.017  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
,03-24 15:30:26.017  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:26.017  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:30:26.017  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:26.017  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:26.019  3254  3314 I jxcore-log: ok 96 error should be null,
03-24 15:30:26.019  3254  3314 I jxcore-log: 
03-24 15:30:26.020  3254  3314 I jxcore-log: ok 97 error should be null
03-24 15:30:26.020  3254  3314 I jxcore-log: 
03-24 15:30:26.026  3254  3314 I jxcore-log: # teardown,
03-24 15:30:26.026  3254  3314 I jxcore-log: 
,03-24 15:30:27.035  2152  2152 D BtGatt.ScanManager: awakened up at time 236528,
03-24 15:30:27.039  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 15:30:27.047  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:27.047  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:27.070  1772  3803 I EventLogService: Opted in for usage reporting
,03-24 15:30:27.071  1772  3803 I EventLogService: Aggregate from 1458828001555 (log), 1458828001555 (data)
,03-24 15:30:27.144  1772  3803 W EventLogAggregator: Unknown tag: snet_gcore
03-24 15:30:27.144  1772  3803 W EventLogAggregator: Unknown tag: snet_launch_service
,03-24 15:30:27.211  1772  3803 I ServiceDumpSys: dumping service [account]
,03-24 15:30:27.552  2152  2152 D BtGatt.ScanManager: awakened up at time 237045
,03-24 15:30:27.554  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:27.556  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 15:30:27.557  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:27.802  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 15:30:27.802  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:27.802  3254  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:30:27.802  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:27.802  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:27.802  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:27.802  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:27.803  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:27.803  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:30:27.805  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:27.807  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:27.807  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:27.808  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:27.809  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:27.811  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:27.811  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:27.811  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:27.811  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 15:30:27.811  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:30:27.811  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:27.811  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:27.811  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:27.812  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:27.814  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 15:30:27.814  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:27.814  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:27.814  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:27.814  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:27.817  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:27.817  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:27.818  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:27.818  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:27.818  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:27.827  3254  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:27.827  3254  3314 I jxcore-log: 
03-24 15:30:27.827  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:30:27.828   822  1213 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:27.835  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 15:30:27.836  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:27.836  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:27.841  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:30:27.841  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:27.841  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:27.841  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:27.844  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:27.845  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-24 15:30:27.845  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:27.850  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 15:30:27.850  3254  3314 I jxcore-log: 
,03-24 15:30:27.854  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 15:30:27.854  3254  3314 I jxcore-log: 
,03-24 15:30:27.863  3254  3314 I jxcore-log: ok 98 error should be null
03-24 15:30:27.863  3254  3314 I jxcore-log: 
,03-24 15:30:27.863  3254  3314 I jxcore-log: ok 99 error should be null
03-24 15:30:27.863  3254  3314 I jxcore-log: 
,03-24 15:30:27.872  3254  3314 I jxcore-log: # setup
,03-24 15:30:27.872  3254  3314 I jxcore-log: 
,03-24 15:30:28.008  3254  3314 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 15:30:28.008  3254  3314 I jxcore-log: 
,03-24 15:30:29.655  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:29.655  3254  3314 I jxcore-log: 
,03-24 15:30:29.659  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 41524
,03-24 15:30:29.659  3254  3314 I jxcore-log: 
,03-24 15:30:29.675  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41524, start advertisements: true,
03-24 15:30:29.675  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:29.675  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:29.675  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:29.681  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:29.681  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:29.682  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:29.682  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-24 15:30:29.688  2152  2218 D BtGatt.GattService: registerClient() - UUID=318accaa-ff0e-4117-a61d-251823684c58
,03-24 15:30:29.689  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=318accaa-ff0e-4117-a61d-251823684c58, clientIf=5
03-24 15:30:29.690  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:29.690  2152  2168 D BtGatt.GattService: start scan with filters
,03-24 15:30:29.691  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:29.691  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:29.691  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 15:30:29.691  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:30:29.691  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:29.691  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:29.692  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:29.692  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:29.692  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:29.693  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:29.694  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:29.694  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:29.694  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:29.701  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:30:29.701  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:29.701  2152  2168 D BtGatt.GattService: registerClient() - UUID=c3057dd3-b6b0-4b21-8c83-565bb0fb1084
,03-24 15:30:29.702  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=c3057dd3-b6b0-4b21-8c83-565bb0fb1084, clientIf=6
03-24 15:30:29.702  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:30:29.705  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 15:30:29.705  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:29.705  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:29.705  2152  2226 D BtGatt.AdvertiseManager: message : 0,
03-24 15:30:29.705  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:29.709  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:29.709  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:29.711  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:30:29.711  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:29.715  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:29.719  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:29.723  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 15:30:29.724  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:29.725  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:29.726   822  1190 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:29.732  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:29.733  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:29.733  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:29.733  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:29.734  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:29.736  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 15:30:29.736  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:29.736  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:30:29.736  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:29.736  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:29.737  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 15:30:29.737  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:30:29.737  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:29.737  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:29.738  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 15:30:29.738  3254  3254 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:29.738  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:29.738  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 15:30:29.738  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:29.738  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:29.739  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:29.746   822  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 15:30:29.749  3254  3805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:29.754  3254  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:29.758  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 15:30:29.758  3254  3314 I jxcore-log: 
03-24 15:30:29.761  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:29.761  3254  3314 I jxcore-log: 
03-24 15:30:29.763  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 15:30:29.763  3254  3314 I jxcore-log: 
03-24 15:30:29.768  3254  3314 I jxcore-log: ok 100 error should be null
03-24 15:30:29.768  3254  3314 I jxcore-log: 
,03-24 15:30:29.769  3254  3314 I jxcore-log: ok 101 error should be null
,03-24 15:30:29.769  3254  3314 I jxcore-log: 
,03-24 15:30:29.784  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41524, start advertisements: true
,03-24 15:30:29.784  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:29.784  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-24 15:30:29.785  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:29.785  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:29.795  3254  3314 I jxcore-log: ok 102 error should be null
,03-24 15:30:29.795  3254  3314 I jxcore-log: 
03-24 15:30:29.795  3254  3314 I jxcore-log: ok 103 error should be null
03-24 15:30:29.795  3254  3314 I jxcore-log: 
,03-24 15:30:29.802  3254  3314 I jxcore-log: # teardown
,03-24 15:30:29.802  3254  3314 I jxcore-log: 
,03-24 15:30:29.951  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:29.952  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:29.952  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:29.952  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:29.952  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:29.952  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:30:29.952  3254  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:30:29.952  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:29.952  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:29.952  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:29.952  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:29.952  3254  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:29.952  3254  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:29.952  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:29.952  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:29.957  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:29.959  2152  2218 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:29.960  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:29.960  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:30:29.960  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:29.960  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:29.960  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:29.960  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:29.960  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:29.960  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:29.960  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:29.960  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:29.963  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:29.963  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:29.963  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:29.965  2152  2226 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:29.966  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:30:29.966  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-24 15:30:29.966  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:29.967  2152  2214 D BtGatt.GattService: current time is 239460117458
03-24 15:30:29.967  2152  2214 D BtGatt.GattService: Batch record : [-28, -44, -106, -22, -38, 116, 0, -128, -105, 5, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 21, -77, -72, 111, -120, 91, 1, -128, -79, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:30:29.967  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-24 15:30:29.968  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:29.969  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:29.971  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:29.971  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:29.972  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:29.974  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:29.974  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:29.974  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:30:29.974  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:29.974  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:29.974  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:29.974  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 15:30:29.975  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:30:29.976  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:29.976  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:29.976  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:29.976  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:29.977  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:29.986  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:30:29.986   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:29.988  3254  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:29.988  3254  3314 I jxcore-log: 
,03-24 15:30:29.995  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:29.996  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:29.996  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:30.002  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:30.002  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:30.002  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:30.002  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:30.002  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:30.003  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:30.003  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:30.003  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:30:30.005  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:30.006  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:30.006  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.008  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 15:30:30.008  3254  3314 I jxcore-log: 
03-24 15:30:30.012  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:30.012  3254  3314 I jxcore-log: 
03-24 15:30:30.014  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:30.014  3254  3314 I jxcore-log: 
,03-24 15:30:30.024  3254  3314 I jxcore-log: ok 104 error should be null
,03-24 15:30:30.024  3254  3314 I jxcore-log: 
03-24 15:30:30.026  3254  3314 I jxcore-log: ok 105 error should be null
03-24 15:30:30.026  3254  3314 I jxcore-log: 
,03-24 15:30:30.032  3254  3314 I jxcore-log: # setup
03-24 15:30:30.032  3254  3314 I jxcore-log: 
,03-24 15:30:30.359  3254  3314 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
,03-24 15:30:30.359  3254  3314 I jxcore-log: 
,03-24 15:30:30.545  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:30:30.545  3254  3314 I jxcore-log: 
,03-24 15:30:30.549  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 60529
,03-24 15:30:30.549  3254  3314 I jxcore-log: 
,03-24 15:30:30.554  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:30.554  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:30.554  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.558  3254  3314 I jxcore-log: ok 106 error should be null
03-24 15:30:30.558  3254  3314 I jxcore-log: ,
03-24 15:30:30.559  3254  3314 I jxcore-log: ok 107 error should be null
03-24 15:30:30.559  3254  3314 I jxcore-log: 
,03-24 15:30:30.563  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:30.563  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:30.563  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:30.564  3254  3314 I jxcore-log: ok 108 error should be null,
03-24 15:30:30.564  3254  3314 I jxcore-log: 
03-24 15:30:30.565  3254  3314 I jxcore-log: ok 109 error should be null
,03-24 15:30:30.565  3254  3314 I jxcore-log: 
,03-24 15:30:30.574  3254  3314 I jxcore-log: # teardown
,03-24 15:30:30.574  3254  3314 I jxcore-log: 
,03-24 15:30:30.700  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:30:30.700  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:30.700  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.703  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:30.703  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:30.703  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:30.709  3254  3314 I jxcore-log: ok 110 error should be null
03-24 15:30:30.709  3254  3314 I jxcore-log: 
,03-24 15:30:30.711  3254  3314 I jxcore-log: ok 111 error should be null
03-24 15:30:30.711  3254  3314 I jxcore-log: 
,03-24 15:30:30.717  3254  3314 I jxcore-log: # setup
03-24 15:30:30.717  3254  3314 I jxcore-log: 
,03-24 15:30:30.898  3254  3314 I jxcore-log: # 28. #start should fail if called twice in a row
03-24 15:30:30.898  3254  3314 I jxcore-log: 
,03-24 15:30:31.046  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:30:31.046  3254  3314 I jxcore-log: 
,03-24 15:30:31.048  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 40507
03-24 15:30:31.048  3254  3314 I jxcore-log: 
,03-24 15:30:31.050  3254  3314 I jxcore-log: ok 112 first call should succeed
,03-24 15:30:31.050  3254  3314 I jxcore-log: 
,03-24 15:30:31.051  3254  3314 I jxcore-log: ok 113 first call should succeed
,03-24 15:30:31.051  3254  3314 I jxcore-log: 
03-24 15:30:31.053  3254  3314 I jxcore-log: ok 114 specific error should be returned
03-24 15:30:31.053  3254  3314 I jxcore-log: 
,03-24 15:30:31.055  3254  3314 I jxcore-log: # teardown
03-24 15:30:31.055  3254  3314 I jxcore-log: 
,03-24 15:30:31.219  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:31.219  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:31.219  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:31.221  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:31.221  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:30:31.221  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:31.226  3254  3314 I jxcore-log: ok 115 error should be null
03-24 15:30:31.226  3254  3314 I jxcore-log: 
03-24 15:30:31.226  3254  3314 I jxcore-log: ok 116 error should be null
03-24 15:30:31.226  3254  3314 I jxcore-log: 
,03-24 15:30:31.232  3254  3314 I jxcore-log: # setup
03-24 15:30:31.232  3254  3314 I jxcore-log: 
,03-24 15:30:31.322  3254  3314 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 15:30:31.322  3254  3314 I jxcore-log: 
,03-24 15:30:31.490  3254  3314 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:30:31.490  3254  3314 I jxcore-log: 
,03-24 15:30:31.492  3254  3314 I jxcore-log: DEBUG createNativeListener: listening 34493
03-24 15:30:31.492  3254  3314 I jxcore-log: 
,03-24 15:30:31.503  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 41524, start advertisements: false
,03-24 15:30:31.503  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:31.504  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:31.504  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:30:31.511  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:31.511  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:31.511  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:31.518  2152  2169 D BtGatt.GattService: registerClient() - UUID=3c760113-ca41-471d-8ec3-570f1aad0deb
03-24 15:30:31.519  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=3c760113-ca41-471d-8ec3-570f1aad0deb, clientIf=5
,03-24 15:30:31.519  3254  3272 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:30:31.520  2152  2168 D BtGatt.GattService: start scan with filters
03-24 15:30:31.522  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:30:31.522  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:30:31.522  2152  2227 D BtGatt.ScanManager: handling starting scan,
03-24 15:30:31.522  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:31.522  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:31.523  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:31.523  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:31.523  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:31.524   822  1213 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:31.532  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 15:30:31.533  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:31.536  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 15:30:31.536  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:31.536  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:31.536  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:31.538  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:31.538  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:31.538  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:31.538  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:31.538  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:31.539  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:31.540  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:30:31.540  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:31.542  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:30:31.542  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:31.544  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:31.544  3254  3314 I jxcore-log: 
03-24 15:30:31.546  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:31.546  3254  3314 I jxcore-log: 
,03-24 15:30:31.558  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 34493, start advertisements: true
03-24 15:30:31.559  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:31.559  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:31.559  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:31.563  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:30:31.563  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 15:30:31.563  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:31.563  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:31.564  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:31.564  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:31.564  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:31.564  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:31.569  2152  2168 D BtGatt.GattService: registerClient() - UUID=86ecc284-2e68-41f6-b16d-364dcfffd602
,03-24 15:30:31.570  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=86ecc284-2e68-41f6-b16d-364dcfffd602, clientIf=6
,03-24 15:30:31.570  3254  3270 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:31.571  2152  2226 D BtGatt.AdvertiseManager: message : 0,
03-24 15:30:31.576  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:30:31.579  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:31.582  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 15:30:31.583  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 15:30:31.583  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:31.583  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:31.583  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:31.583  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:31.583  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 15:30:31.584  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:31.584   822  1293 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:31.587  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:31.587  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:31.588  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:30:31.588  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:31.588  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:30:31.589  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:31.589  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:31.589  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 15:30:31.589  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:31.589  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:31.589  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:31.589  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:31.590  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-24 15:30:31.592   822  1190 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:31.594  3254  3806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:31.599  3254  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:31.601  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 15:30:31.601  3254  3314 I jxcore-log: 
,03-24 15:30:31.608  3254  3314 I jxcore-log: ok 117 called only once
,03-24 15:30:31.608  3254  3314 I jxcore-log: 
,03-24 15:30:31.608  3254  3314 I jxcore-log: ok 118 discovery state matches
03-24 15:30:31.608  3254  3314 I jxcore-log: ,
03-24 15:30:31.609  3254  3314 I jxcore-log: ok 119 advertising state matches
03-24 15:30:31.609  3254  3314 I jxcore-log: 
,03-24 15:30:31.619  3254  3314 I jxcore-log: # teardown
,03-24 15:30:31.619  3254  3314 I jxcore-log: 
,03-24 15:30:32.231  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:32.231  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:32.231  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:32.231  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:32.231  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:32.231  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:30:32.231  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:32.231  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:32.231  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:32.231  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:32.232  3254  3806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:32.232  3254  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:32.232  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:32.232  3254  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:32.232  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:30:32.235  2152  2218 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:32.238  2152  2218 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:32.238  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:32.238  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:32.238  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:32.239  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:32.239  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:32.239  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:30:32.239  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:32.240  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:32.240  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:30:32.240  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:30:32.242  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 15:30:32.242  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:32.243  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:32.244  2152  2226 D BtGatt.AdvertiseManager: message : 1,
,03-24 15:30:32.245  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6,
,03-24 15:30:32.246  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-24 15:30:32.246  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:32.246  2152  2214 D BtGatt.GattService: current time is 241739818603
03-24 15:30:32.246  2152  2214 D BtGatt.GattService: Batch record : [71, -128, 19, 2, 85, 67, 1, -128, -81, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, -44, -106, -22, -38, 116, 0, -128, -105, 10, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0],
03-24 15:30:32.247  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:32.247  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:32.247  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-24 15:30:32.250  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:32.251  2152  2214 D BtGatt.GattService: Client app is not null!
,03-24 15:30:32.252  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:32.252  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:32.252  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:32.252  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:30:32.252  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:32.252  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:32.252  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:32.252  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:32.253  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:32.254  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:32.254  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:32.254  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:32.254  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:32.254  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:32.261  3254  3314 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 15:30:32.261  3254  3314 I jxcore-log: 
03-24 15:30:32.262  3254  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:32.262  3254  3314 I jxcore-log: 
,03-24 15:30:32.267  3254  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:30:32.267  3254  3314 I jxcore-log: 
,03-24 15:30:32.273  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:32.273   822  2340 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:32.281  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:32.282  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:32.282  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:32.285  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:30:32.285  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 15:30:32.285  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:32.285  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:32.286  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:32.286  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:32.286  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:32.286  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:30:32.287  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:32.287  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:32.287  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:32.289  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:32.289  3254  3314 I jxcore-log: 
03-24 15:30:32.289  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:32.289  3254  3314 I jxcore-log: 
03-24 15:30:32.290  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:32.290  3254  3314 I jxcore-log: 
03-24 15:30:32.294  3254  3314 I jxcore-log: ok 120 error should be null
03-24 15:30:32.294  3254  3314 I jxcore-log: 
03-24 15:30:32.294  3254  3314 I jxcore-log: ok 121 error should be null
03-24 15:30:32.294  3254  3314 I jxcore-log: 
,03-24 15:30:32.300  3254  3314 I jxcore-log: # setup
03-24 15:30:32.300  3254  3314 I jxcore-log: 
,03-24 15:30:32.417  3254  3314 I jxcore-log: # 30. does not send duplicate availability changes
03-24 15:30:32.417  3254  3314 I jxcore-log: 
,03-24 15:30:32.622  3254  3314 I jxcore-log: ok 122 should be called once
03-24 15:30:32.622  3254  3314 I jxcore-log: 
,03-24 15:30:32.624  3254  3314 I jxcore-log: ok 123 should not have been called more than once
03-24 15:30:32.624  3254  3314 I jxcore-log: 
,03-24 15:30:32.626  3254  3314 I jxcore-log: # teardown
03-24 15:30:32.626  3254  3314 I jxcore-log: 
,03-24 15:30:32.732  3254  3314 I jxcore-log: ok 124 error should be null
03-24 15:30:32.732  3254  3314 I jxcore-log: 
,03-24 15:30:32.734  3254  3314 I jxcore-log: ok 125 error should be null
03-24 15:30:32.734  3254  3314 I jxcore-log: 
,03-24 15:30:32.738  3254  3314 I jxcore-log: # setup
03-24 15:30:32.738  3254  3314 I jxcore-log: 
,03-24 15:30:32.902  3254  3314 I jxcore-log: # 31. can get the network status
03-24 15:30:32.902  3254  3314 I jxcore-log: 
,03-24 15:30:32.999  3254  3314 I jxcore-log: ok 126 network status should have certain non-empty properties
03-24 15:30:32.999  3254  3314 I jxcore-log: 
,03-24 15:30:33.001  3254  3314 I jxcore-log: # teardown
03-24 15:30:33.001  3254  3314 I jxcore-log: 
,03-24 15:30:33.173  3254  3314 I jxcore-log: ok 127 error should be null
03-24 15:30:33.173  3254  3314 I jxcore-log: 
,03-24 15:30:33.175  3254  3314 I jxcore-log: ok 128 error should be null
03-24 15:30:33.175  3254  3314 I jxcore-log: 
03-24 15:30:33.179  3254  3314 I jxcore-log: # setup
03-24 15:30:33.179  3254  3314 I jxcore-log: 
,03-24 15:30:33.316  3254  3314 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 15:30:33.316  3254  3314 I jxcore-log: 
,03-24 15:30:33.450  3254  3314 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 15:30:33.450  3254  3314 I jxcore-log: 
,03-24 15:30:33.474  3254  3314 I jxcore-log: ok 129 host address should match
03-24 15:30:33.474  3254  3314 I jxcore-log: 
,03-24 15:30:33.475  3254  3314 I jxcore-log: ok 130 port should match
03-24 15:30:33.475  3254  3314 I jxcore-log: 
,03-24 15:30:35.457  3254  3314 I jxcore-log: ok 131 host address should be null
03-24 15:30:35.457  3254  3314 I jxcore-log: 
,03-24 15:30:35.458  3254  3314 I jxcore-log: ok 132 port should should be null
03-24 15:30:35.458  3254  3314 I jxcore-log: 
,03-24 15:30:35.480  3254  3314 I jxcore-log: # teardown,
03-24 15:30:35.480  3254  3314 I jxcore-log: 
,03-24 15:30:35.581  3254  3314 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 15:30:35.581  3254  3314 I jxcore-log: 
03-24 15:30:35.583  3254  3314 I jxcore-log: ok 133 error should be null
03-24 15:30:35.583  3254  3314 I jxcore-log: 
,03-24 15:30:35.584  3254  3314 I jxcore-log: ok 134 error should be null
03-24 15:30:35.584  3254  3314 I jxcore-log: 
,03-24 15:30:35.586  3254  3314 I jxcore-log: # setup
03-24 15:30:35.586  3254  3314 I jxcore-log: 
,03-24 15:30:35.693  3254  3314 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 15:30:35.693  3254  3314 I jxcore-log: 
,03-24 15:30:35.823  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 34493, start advertisements: false
,03-24 15:30:35.823  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:35.823  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:30:35.823  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:30:35.831  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:35.831  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:35.831  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:35.840  2152  2218 D BtGatt.GattService: registerClient() - UUID=ee1b9156-5f8a-42b1-a0ea-8aa15625b5da
03-24 15:30:35.841  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=ee1b9156-5f8a-42b1-a0ea-8aa15625b5da, clientIf=5
03-24 15:30:35.842  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:30:35.844  2152  2169 D BtGatt.GattService: start scan with filters
,03-24 15:30:35.846  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:30:35.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:35.847  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:35.847  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:35.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:30:35.847  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:35.847  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:35.848  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:35.849   822  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:35.858  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 15:30:35.858  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:35.861  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:35.861  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:35.861  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:30:35.861  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:35.862  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:35.862  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:35.863  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:35.863  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:35.863  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:35.864  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:35.867  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 15:30:35.867  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:35.868  3254  3314 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
03-24 15:30:35.868  3254  3314 I jxcore-log: 
,03-24 15:30:35.869  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:35.869  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:35.871  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:35.872  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:35.873  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
03-24 15:30:35.873  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:30:35.877  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:35.878  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:35.879  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:35.879  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:35.879  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:35.879  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 15:30:35.880  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:30:35.880  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:35.880  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:35.880  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:35.880  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:35.881  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:35.881  3254  3314 I jxcore-log: 
03-24 15:30:35.881  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:35.881  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:35.882  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:35.883  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:35.883  3254  3314 I jxcore-log: 
03-24 15:30:35.884  3254  3314 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 15:30:35.884  3254  3314 I jxcore-log: 
03-24 15:30:35.885  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:35.885  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:35.885  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:35.887  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:35.887  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:35.891  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:35.891  3254  3314 I jxcore-log: 
03-24 15:30:35.893  3254  3314 I jxcore-log: # teardown,
03-24 15:30:35.893  3254  3314 I jxcore-log: 
,03-24 15:30:35.993  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:30:35.994  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:35.994  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:35.998  3254  3314 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown,
03-24 15:30:35.998  3254  3314 I jxcore-log: 
03-24 15:30:35.999  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 15:30:35.999  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:35.999  3254  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:30:35.999  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:35.999  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:35.999  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:35.999  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:35.999  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:36.001  3254  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 15:30:36.001  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:36.003  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:36.003  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:36.003  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:36.004  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:36.004  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:36.004  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:36.004  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:36.004  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:36.014  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:36.015   822  1216 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:36.022  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:36.023  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:36.024  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:36.030  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:36.030  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:36.030  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:36.033  3254  3314 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:36.033  3254  3314 I jxcore-log: 
,03-24 15:30:36.053  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:36.053  3254  3314 I jxcore-log: 
,03-24 15:30:36.055  3254  3314 I jxcore-log: # setup
03-24 15:30:36.055  3254  3314 I jxcore-log: 
,03-24 15:30:36.179  3254  3314 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error
03-24 15:30:36.179  3254  3314 I jxcore-log: 
,03-24 15:30:36.291  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 34493, start advertisements: false
,03-24 15:30:36.291  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:36.291  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:36.291  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:30:36.297  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:36.297  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:36.297  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:36.303  2152  2218 D BtGatt.GattService: registerClient() - UUID=76a22e12-5370-4c6d-ab79-2b791bb9127d
,03-24 15:30:36.303  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=76a22e12-5370-4c6d-ab79-2b791bb9127d, clientIf=5
03-24 15:30:36.304  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:36.305  2152  2217 D BtGatt.GattService: start scan with filters
,03-24 15:30:36.307  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:36.307  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:30:36.307  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:36.307  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:36.307  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:36.308  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:36.308  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:36.308  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 15:30:36.309  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:30:36.309  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:36.309   822  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 15:30:36.311  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:36.311  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.311  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:36.311  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:36.313  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:36.313  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:36.313  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:36.313  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:36.314  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:36.314  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:36.315  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:36.315  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.317  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:36.317  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.318  3254  3314 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-24 15:30:36.318  3254  3314 I jxcore-log: 
,03-24 15:30:36.328  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 34493, start advertisements: false
,03-24 15:30:36.328  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:36.328  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:30:36.328  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:36.329  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 15:30:36.330  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:36.330  3254  3314 I jxcore-log: 
,03-24 15:30:36.332  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:36.332  3254  3314 I jxcore-log: 
,03-24 15:30:36.335  3254  3314 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
,03-24 15:30:36.335  3254  3314 I jxcore-log: 
,03-24 15:30:36.341  3254  3314 I jxcore-log: # teardown
,03-24 15:30:36.341  3254  3314 I jxcore-log: 
,03-24 15:30:36.584  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:30:36.585  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:36.585  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:36.585  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:36.588  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:36.591  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:30:36.591  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:36.591  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:36.591  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 15:30:36.591  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:36.592  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:36.592  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:36.592  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:30:36.592  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:30:36.592  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:36.593  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:30:36.594  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:30:36.594  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:36.595  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:36.595  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.595  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:36.595  3254  3314 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:36.595  3254  3314 I jxcore-log: 
03-24 15:30:36.596  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:36.596  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:36.596  3254  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:30:36.596  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:36.597  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:36.597  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:36.597  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 15:30:36.597  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:36.597  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.597  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:36.598  3254  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 15:30:36.598  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:36.599  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:36.599  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:36.599  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:36.599  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:36.599  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:36.600  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:36.600  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:36.600  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:36.601  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:36.601  3254  3314 I jxcore-log: 
03-24 15:30:36.610  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:30:36.611   822  2340 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:36.622  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:36.623  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:36.623  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:36.627  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:36.627  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:36.627  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:36.629  3254  3314 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:36.629  3254  3314 I jxcore-log: 
,03-24 15:30:36.636  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:36.636  3254  3314 I jxcore-log: 
,03-24 15:30:36.639  3254  3314 I jxcore-log: # setup
,03-24 15:30:36.639  3254  3314 I jxcore-log: 
,03-24 15:30:36.752  3254  3314 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-24 15:30:36.752  3254  3314 I jxcore-log: 
,03-24 15:30:36.902  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 15:30:36.903  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:36.903  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:36.903  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:36.912  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:36.912  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:36.912  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:36.912  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:36.921  2152  2168 D BtGatt.GattService: registerClient() - UUID=99527fc7-64bc-4904-ae8c-95baab5b25c8
,03-24 15:30:36.922  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=99527fc7-64bc-4904-ae8c-95baab5b25c8, clientIf=5
,03-24 15:30:36.923  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:30:36.924  2152  2217 D BtGatt.GattService: start scan with filters
,03-24 15:30:36.927  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:36.928  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:30:36.929  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:30:36.930  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:36.930  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:36.930  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:36.937  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:36.937  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.938  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:36.938  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-24 15:30:36.938  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:36.938  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:36.938  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:36.939  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:36.939  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:36.939  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:30:36.939  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.940  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:36.940  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:36.942  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:30:36.942  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 15:30:36.944  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:36.944  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:36.947  2152  2217 D BtGatt.GattService: registerClient() - UUID=e0b7bf92-b367-4c7a-af59-e5e7176f5c00
03-24 15:30:36.948  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=e0b7bf92-b367-4c7a-af59-e5e7176f5c00, clientIf=6
,03-24 15:30:36.948  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:36.950  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:36.955  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:36.959  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:36.962  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:30:36.963  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:36.963  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:36.963   822  1623 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:36.967  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:36.967  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:36.967  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:36.967  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:36.968  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:36.969  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:30:36.970  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:36.970  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:36.970  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:36.971  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 15:30:36.971  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:36.971  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:36.971  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:36.971  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:36.971  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:36.971  3254  3254 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:30:36.972  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:36.972  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:36.972  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:36.972  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:36.972  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:36.972   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:36.973  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:36.973  3254  3314 I jxcore-log: 
03-24 15:30:36.975  3254  3808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:36.975  3254  3314 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:36.975  3254  3314 I jxcore-log: 
03-24 15:30:36.976  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:30:36.976  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:30:36.976  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:36.976  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:36.976  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:36.976  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:36.976  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:36.976  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:36.976  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 15:30:36.976  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:36.976  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:36.976  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:36.978  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:36.980  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:36.980  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:30:36.981  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 15:30:36.981  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:36.981  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:30:36.981  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:36.981  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:36.981  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:36.981  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:36.981  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:36.981  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:36.982  3254  3808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:36.982  3254  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:36.982  3254  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:36.983  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:36.984  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:36.984  2152  2226 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:36.984  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:36.985  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:30:36.985  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:36.985  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:36.989  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 15:30:36.989  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:36.990  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:36.991  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:36.991  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:36.991  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:30:36.991  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 15:30:36.992  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:36.992  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:30:36.992  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:36.992  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:36.993  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:30:36.993  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:36.994  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:36.994  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:36.994  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:37.001  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:37.001  3254  3314 I jxcore-log: 
03-24 15:30:37.003  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:37.003  3254  3314 I jxcore-log: 
,03-24 15:30:37.008  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-24 15:30:37.008   822  1624 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 15:30:37.014  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:37.015  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:37.015  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-24 15:30:37.018  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 15:30:37.018  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:30:37.018  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:37.018  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 15:30:37.018  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:37.018  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:37.018  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 15:30:37.018  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:37.019  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-24 15:30:37.020  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:37.020  3254  3314 I jxcore-log: 
03-24 15:30:37.021  3254  3314 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 15:30:37.021  3254  3314 I jxcore-log: 
,03-24 15:30:37.027  3254  3314 I jxcore-log: # teardown
03-24 15:30:37.027  3254  3314 I jxcore-log: 
03-24 15:30:37.029  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 15:30:37.029  3254  3314 I jxcore-log: 
03-24 15:30:37.029  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:37.029  3254  3314 I jxcore-log: 
,03-24 15:30:37.823  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:30:37.824  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:30:37.824  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:37.828  3254  3314 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:37.828  3254  3314 I jxcore-log: 
03-24 15:30:37.829  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:37.829  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:37.829  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:37.830  3254  3314 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:37.830  3254  3314 I jxcore-log: 
,03-24 15:30:37.835  3254  3314 I jxcore-log: # setup
03-24 15:30:37.835  3254  3314 I jxcore-log: 
,03-24 15:30:37.989  3254  3314 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 15:30:37.989  3254  3314 I jxcore-log: 
,03-24 15:30:38.217  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:30:38.279  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:30:38.279  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:38.279  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:38.279  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:38.283  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:30:38.283  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:38.283  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:38.284  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:38.289  2152  2168 D BtGatt.GattService: registerClient() - UUID=ce7ea5c3-b4f4-4f16-aa45-89fb8037e7a9
,03-24 15:30:38.289  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=ce7ea5c3-b4f4-4f16-aa45-89fb8037e7a9, clientIf=5
03-24 15:30:38.290  3254  3272 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 15:30:38.290  2152  2217 D BtGatt.GattService: start scan with filters
,03-24 15:30:38.291  2152  2227 D BtGatt.ScanManager: handling starting scan,
,03-24 15:30:38.293  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 15:30:38.293  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:38.293  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:38.293  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:30:38.293  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:38.293  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:38.294  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:30:38.294  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:38.294  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-24 15:30:38.294  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:38.295  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:38.295  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:38.296  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:38.296  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.298  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:38.298  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.299  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:38.299  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:38.301  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:30:38.301  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.303  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:38.303  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.305  2152  2217 D BtGatt.GattService: registerClient() - UUID=bc63bece-ee61-4805-aaa9-0518151c8f37
03-24 15:30:38.306  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=bc63bece-ee61-4805-aaa9-0518151c8f37, clientIf=6
03-24 15:30:38.306  3254  3270 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:38.309  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:38.312  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:38.315  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:38.317  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:30:38.318  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:38.318  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:38.319   822  1216 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:38.325  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:38.326  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:38.326  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:38.326  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:38.328  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:30:38.328  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:30:38.328  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:38.328  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:38.330  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:38.330  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 15:30:38.331   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:38.331  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:38.331  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:38.331  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 15:30:38.331  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:38.332  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:38.332  3254  3254 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:38.332  3254  3810 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:38.332  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:38.332  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:38.332  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:38.332  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:38.333  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:38.334  3254  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:38.344  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:38.344  3254  3314 I jxcore-log: 
,03-24 15:30:38.349  3254  3314 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:38.349  3254  3314 I jxcore-log: 
,03-24 15:30:38.356  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-24 15:30:38.356  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:38.356  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:38.356  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:38.356  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:38.361  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 15:30:38.361  3254  3314 I jxcore-log: 
03-24 15:30:38.363  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:38.363  3254  3314 I jxcore-log: 
03-24 15:30:38.366  3254  3314 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-24 15:30:38.366  3254  3314 I jxcore-log: 
,03-24 15:30:38.377  3254  3314 I jxcore-log: # teardown
,03-24 15:30:38.377  3254  3314 I jxcore-log: 
,03-24 15:30:38.618  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:38.619  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:30:38.619  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:38.619  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:30:38.622  2152  2218 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:38.625  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:38.625  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.625  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:38.627  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:38.627  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.627  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:38.628  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:38.629  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:38.629  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 15:30:38.629  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:38.629  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:38.630  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 15:30:38.630  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:38.630  2152  2214 D BtGatt.GattService: current time is 248123848132
03-24 15:30:38.630  2152  2214 D BtGatt.GattService: Batch record : [99, 110, -100, -53, 77, 88, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:30:38.630  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:38.631  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:38.632  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 15:30:38.632  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:38.632  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:38.633  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:30:38.633  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:38.637  3254  3314 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:38.637  3254  3314 I jxcore-log: 
,03-24 15:30:38.638  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:30:38.638  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:38.638  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:30:38.638  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:38.638  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:38.639  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:30:38.639  3254  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:38.639  3254  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:38.639  3254  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 15:30:38.639  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:30:38.639  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:30:38.640  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:38.640  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:38.640  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:38.640  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:38.640  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:30:38.640  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:38.641  3254  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 15:30:38.641  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:38.641  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:30:38.642  2152  2226 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:38.642  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:30:38.645  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 15:30:38.645  2152  2214 D BtGatt.GattService: Client app is not null!
,03-24 15:30:38.645  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:38.646  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:38.646  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:38.646  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:30:38.646  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:38.646  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:38.646  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:38.646  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:38.646  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:30:38.647  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:38.647  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:38.647  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:38.648  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:38.648  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:38.648  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:38.648  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:38.651  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:38.651   822  1190 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:38.653  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:38.653  3254  3314 I jxcore-log: 
,03-24 15:30:38.655  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:38.655  3254  3314 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:38.655  3254  3314 I jxcore-log: 
03-24 15:30:38.656  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:38.656  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:38.658  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:38.658  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:38.661  3254  3314 I jxcore-log: # setup
03-24 15:30:38.661  3254  3314 I jxcore-log: 
,03-24 15:30:38.662  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:38.662  3254  3314 I jxcore-log: 
,03-24 15:30:38.663  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:38.663  3254  3314 I jxcore-log: 
,03-24 15:30:38.846  3254  3314 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 15:30:38.846  3254  3314 I jxcore-log: 
,03-24 15:30:38.979  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:30:38.979  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:38.979  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:38.979  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:30:38.986  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:38.986  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:38.986  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:30:38.987  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:38.995  2152  2168 D BtGatt.GattService: registerClient() - UUID=0a36a834-fc1c-4fdc-b4dc-b2bee186cce7,
03-24 15:30:38.996  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=0a36a834-fc1c-4fdc-b4dc-b2bee186cce7, clientIf=5
03-24 15:30:38.997  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:38.998  2152  2217 D BtGatt.GattService: start scan with filters
,03-24 15:30:39.000  2152  2227 D BtGatt.ScanManager: handling starting scan
,03-24 15:30:39.000  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:39.001  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:30:39.002  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 15:30:39.002  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:39.002  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:39.002  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 15:30:39.002  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:39.004  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:39.005  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:39.006  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 15:30:39.006  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:39.007  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:39.007  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:39.008  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:39.008  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:39.008  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:39.009  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:39.009  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:39.011  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:39.011  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:39.013  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:30:39.013  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:39.020  2152  2217 D BtGatt.GattService: registerClient() - UUID=0cc48717-b2c8-41a2-8c0b-b176d44679bf
,03-24 15:30:39.020  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=0cc48717-b2c8-41a2-8c0b-b176d44679bf, clientIf=6
03-24 15:30:39.021  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:39.023  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:39.028  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:39.032  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:39.035  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:30:39.036  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:39.036  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:30:39.037   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:39.042  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:39.043  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:30:39.043  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:30:39.043  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:39.044  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:39.044  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:39.045  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 15:30:39.045  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:39.046  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:39.046  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:39.046  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:30:39.046  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:39.047  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:39.047   822  1624 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:39.047  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:39.047  3254  3254 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:39.047  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:39.047  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:39.047  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:39.047  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:39.048  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:39.048  3254  3811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:39.049  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:39.051  3254  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:30:39.053  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:39.053  3254  3314 I jxcore-log: 
03-24 15:30:39.056  3254  3314 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
03-24 15:30:39.056  3254  3314 I jxcore-log: 
,03-24 15:30:39.061  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-24 15:30:39.061  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:30:39.061  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:30:39.061  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:30:39.062  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:39.063  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:39.063  3254  3314 I jxcore-log: 
,03-24 15:30:39.064  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:39.064  3254  3314 I jxcore-log: 
03-24 15:30:39.065  3254  3314 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-24 15:30:39.065  3254  3314 I jxcore-log: 
,03-24 15:30:39.518  2152  2152 D BtGatt.ScanManager: awakened up at time 249011
,03-24 15:30:39.519  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:39.529  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 15:30:39.529  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:39.529  2152  2214 D BtGatt.GattService: current time is 249022551361
03-24 15:30:39.529  2152  2214 D BtGatt.GattService: Batch record : [0, 18, -103, 31, -124, 86, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:30:39.530  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:30:39.536  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 15:30:39.536  3254  3254 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:30:39.543  3254  3314 I jxcore-log: ok 153 peers must be an array
,03-24 15:30:39.543  3254  3314 I jxcore-log: 
03-24 15:30:39.544  3254  3314 I jxcore-log: ok 154 peers must not be zero-length
03-24 15:30:39.544  3254  3314 I jxcore-log: 
03-24 15:30:39.545  3254  3314 I jxcore-log: ok 155 peer must have peerIdentifier
,03-24 15:30:39.545  3254  3314 I jxcore-log: 
03-24 15:30:39.547  3254  3314 I jxcore-log: ok 156 peerIdentifier must be a string
03-24 15:30:39.547  3254  3314 I jxcore-log: 
,03-24 15:30:39.550  3254  3314 I jxcore-log: ok 157 peer must have peerAvailable
03-24 15:30:39.550  3254  3314 I jxcore-log: ,
03-24 15:30:39.551  3254  3314 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 15:30:39.551  3254  3314 I jxcore-log: 
,03-24 15:30:39.560  3254  3314 I jxcore-log: # teardown
03-24 15:30:39.560  3254  3314 I jxcore-log: 
,03-24 15:30:40.500  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:30:40.500  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:30:40.500  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 15:30:40.500  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:30:40.502  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:40.504  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 15:30:40.504  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:40.505  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:30:40.505  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:40.505  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:40.505  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:40.505  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:40.505  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:40.505  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:40.505  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:30:40.506  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:40.506  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:30:40.506  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:40.507  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:40.507  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:40.508  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:40.510  3254  3314 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:40.510  3254  3314 I jxcore-log: 
03-24 15:30:40.510  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
03-24 15:30:40.511  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:40.511  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:30:40.511  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:40.511  2152  2214 D BtGatt.GattService: current time is 250004426204
03-24 15:30:40.511  2152  2214 D BtGatt.GattService: Batch record : [0, 18, -103, 31, -124, 86, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-24 15:30:40.512  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:40.514  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:40.514  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:40.514  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:30:40.514  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:30:40.514  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:40.514  3254  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:30:40.514  3254  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:40.514  3254  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:40.514  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:30:40.514  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 15:30:40.514  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:40.515  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:30:40.515  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:30:40.515  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:30:40.516  3254  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 15:30:40.517  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:40.517  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:30:40.519  2152  2226 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:40.519  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:30:40.522  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:40.523  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:40.524  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:40.525  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:40.525  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:40.525  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:30:40.525  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:40.525  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:30:40.525  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:40.525  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:40.525  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:30:40.526  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:40.526  3254  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:30:40.526  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:40.526  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:40.526  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:40.526  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:30:40.528  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:40.528  3254  3314 I jxcore-log: 
,03-24 15:30:40.537  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:40.538   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:40.549  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:40.550  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:40.551  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:40.557  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:30:40.557  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:40.557  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:40.557  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:40.557  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:30:40.558  3254  3314 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:40.558  3254  3314 I jxcore-log: 
,03-24 15:30:40.563  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:40.563  3254  3314 I jxcore-log: 
,03-24 15:30:40.564  3254  3314 I jxcore-log: # setup
03-24 15:30:40.564  3254  3314 I jxcore-log: 
,03-24 15:30:40.566  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:40.566  3254  3314 I jxcore-log: 
,03-24 15:30:40.700  3254  3314 I jxcore-log: # 38. Can connect to a remote peer
03-24 15:30:40.700  3254  3314 I jxcore-log: 
,03-24 15:30:40.812  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 54339, start advertisements: true
,03-24 15:30:40.812  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:40.812  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:40.812  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true,
,03-24 15:30:40.818  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:30:40.818  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:40.818  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:40.818  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:40.824  2152  2218 D BtGatt.GattService: registerClient() - UUID=6fb73a64-5aba-4a76-905f-c1986827e365
,03-24 15:30:40.825  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=6fb73a64-5aba-4a76-905f-c1986827e365, clientIf=5
,03-24 15:30:40.825  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:30:40.827  2152  2168 D BtGatt.GattService: start scan with filters,
,03-24 15:30:40.829  2152  2227 D BtGatt.ScanManager: handling starting scan,
,03-24 15:30:40.830  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 15:30:40.830  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 15:30:40.830  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:40.831  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:40.831  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:40.831  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:40.831  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:40.831  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:40.831  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:40.832  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:40.832  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:40.832  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:40.837  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 15:30:40.837  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:40.840  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:30:40.840  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:40.840  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:40.840  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:40.843  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:30:40.844  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:40.844  2152  2168 D BtGatt.GattService: registerClient() - UUID=63609854-2f39-4a40-bbd7-8124d2eca7bb
03-24 15:30:40.845  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=63609854-2f39-4a40-bbd7-8124d2eca7bb, clientIf=6
03-24 15:30:40.846  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-24 15:30:40.846  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:30:40.846  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:40.848  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:40.853  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:40.858  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:40.861  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 15:30:40.862  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:40.862  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:40.863   822  2340 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:40.869  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:30:40.869  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:40.869  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:30:40.869  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:30:40.871  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:30:40.871  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:40.872  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:40.872  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:30:40.872  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:40.872  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:40.872  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:40.872  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:40.873  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:40.873  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:40.873  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:40.873  3254  3254 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:40.873  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:40.873  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:40.873  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:40.874  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:40.874  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:40.874   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:40.875  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:40.875  3254  3314 I jxcore-log: 
03-24 15:30:40.875  3254  3814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:40.879  3254  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:30:40.882  3254  3314 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:40.882  3254  3314 I jxcore-log: 
,03-24 15:30:40.889  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 54339, start advertisements: false
03-24 15:30:40.889  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:40.889  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:30:40.889  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:40.890  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:40.892  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:40.892  3254  3314 I jxcore-log: 
03-24 15:30:40.909  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:40.909  3254  3314 I jxcore-log: 
03-24 15:30:40.910  3254  3314 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-24 15:30:40.910  3254  3314 I jxcore-log: 
,03-24 15:30:41.853  2152  2152 D BtGatt.ScanManager: awakened up at time 251346
,03-24 15:30:41.858  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:41.867  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:30:41.867  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:41.867  2152  2214 D BtGatt.GattService: current time is 251360951568,
03-24 15:30:41.868  2152  2214 D BtGatt.GattService: Batch record : [-121, -19, 4, -125, -7, 78, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:30:41.868  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:30:41.869  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:41.872  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 15:30:41.873  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 15:30:41.874  3254  3254 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 15:30:41.874  3254  3254 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 15:30:41.879  3254  3314 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 15:30:41.879  3254  3314 I jxcore-log: 
,03-24 15:30:41.885  3254  3314 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 15:30:41.885  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:30:41.889  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0,
03-24 15:30:41.889  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 15:30:41.889  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 15:30:41.890  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-24 15:30:41.890  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
,03-24 15:30:41.890  3254  3314 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 15:30:41.891  3254  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 351)
,03-24 15:30:41.892  3254  3815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:41.892  3254  3314 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 15:30:41.892  3254  3314 I jxcore-log: 
,03-24 15:30:41.894  2152  2217 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,03-24 15:30:45.421  2152  2228 W bt-btif : info:x10,
03-24 15:30:45.421  2152  2214 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 15:30:45.422  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 15:30:45.464  2152  2228 W bt-sdp  : process_service_search_attr_rsp
,03-24 15:30:45.603  2152  2214 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-24 15:30:45.612  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
03-24 15:30:45.613  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 15:30:45.617  2152  2216 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,03-24 15:30:45.618  2152  2216 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 15:30:45.652  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-24 15:30:45.653  2152  2216 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 15:30:45.710   822   856 I ActivityManager: Start proc 3817:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
03-24 15:30:45.711  2152  2216 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 15:30:45.730   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 414us total 18.179ms
,03-24 15:30:45.734  2152  2228 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:30:45.734  2152  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:30:45.734  2152  2228 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 15:30:45.735  3254  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-24 15:30:45.736  3254  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 351)
,03-24 15:30:45.741  3254  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 352)
03-24 15:30:45.741  3254  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 352)
03-24 15:30:45.741  3254  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 351)
03-24 15:30:45.742  3254  3834 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 352)
03-24 15:30:45.742  2152  2216 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 15:30:45.751   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 354us total 19.932ms
,03-24 15:30:45.754  3254  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 352)
03-24 15:30:45.755  3254  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:30:45.755  3254  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-24 15:30:45.755  3254  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-24 15:30:45.756  3254  3254 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:30:45.756  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:30:45.756  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 15:30:45.757  3254  3254 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 15:30:45.757  3254  3834 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 352)
03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:45.757  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:45.759  2152  2226 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:45.760  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:30:45.762  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:45.762  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:45.763  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:45.763  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:45.763  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.763  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:45.763  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:45.763  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:45.763  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:45.763  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.764  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.764  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:30:45.768  2152  2169 D BtGatt.GattService: registerClient() - UUID=16c2d62c-8a50-4519-80f0-11ba6c95d45c
03-24 15:30:45.768  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=16c2d62c-8a50-4519-80f0-11ba6c95d45c, clientIf=6
03-24 15:30:45.769  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:45.770  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:45.772  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:45.772   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 350us total 20.154ms
,03-24 15:30:45.774  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:45.777  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:30:45.778  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:45.779  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:45.780  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 15:30:45.780  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:45.781  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:45.781  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:45.781  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:45.781  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.781  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:45.781  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:30:45.781  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:45.781  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:45.783  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:45.783  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.783  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:45.785  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3,
03-24 15:30:45.785  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.785  2152  2214 D BtGatt.GattService: current time is 255278777140
03-24 15:30:45.785  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -121, -19, 4, -125, -7, 78, 1, -128, -72, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -109, 60, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0]
03-24 15:30:45.785  2152  2169 D BtGatt.GattService: registerClient() - UUID=1a8f646d-8331-45ab-9236-8c899afa4e81
03-24 15:30:45.785  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:45.786  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:45.786  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-24 15:30:45.786  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=1a8f646d-8331-45ab-9236-8c899afa4e81, clientIf=5
03-24 15:30:45.786  3254  3272 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:45.787  2152  2217 D BtGatt.GattService: start scan with filters
,03-24 15:30:45.787  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:45.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
03-24 15:30:45.789  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:45.789  2152  2226 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:45.789  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:30:45.790  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:45.790  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.791  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:45.791  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:45.792  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:45.792  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:30:45.792  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:30:45.792  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:45.792  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:45.792  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:45.792  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:45.792  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.792  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.792  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:45.793  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:45.794  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:45.794  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:45.794  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:45.796  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:30:45.796  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.796  2152  2217 D BtGatt.GattService: registerClient() - UUID=be353c53-2d24-4fa5-8b22-843d0b6d1284
,03-24 15:30:45.796  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=be353c53-2d24-4fa5-8b22-843d0b6d1284, clientIf=6
03-24 15:30:45.796  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:30:45.797  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:45.797  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.797  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:45.799  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:45.801  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:45.804  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:30:45.804  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:45.805  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:45.806  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:30:45.806  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:45.806  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.806  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:45.806  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:45.806  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:45.806  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:45.806  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:45.807  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.807  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:45.809  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 15:30:45.809  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.809  2152  2217 D BtGatt.GattService: registerClient() - UUID=6546b29d-7e77-40fe-bd3c-bb5ae835e7ea
03-24 15:30:45.809  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:45.809  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=6546b29d-7e77-40fe-bd3c-bb5ae835e7ea, clientIf=5
03-24 15:30:45.810   822   860 D BluetoothManagerService: Message: 20
03-24 15:30:45.810  3254  3272 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:45.810   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3354f0a3:true
03-24 15:30:45.810  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 15:30:45.810  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.810  2152  2168 D BtGatt.GattService: start scan with filters
03-24 15:30:45.811  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:45.811  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:45.814  2152  2226 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:45.814  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:45.814  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:30:45.815   822  1216 I ActivityManager: Killing 3552:com.android.chrome/u0a40 (adj 15): empty #17
03-24 15:30:45.816  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:45.816  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:45.816  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:45.817  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:45.817  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:30:45.817  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:45.817  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:45.817  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:45.817  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:45.817  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:30:45.817  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:45.817  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:45.818  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:45.818  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:45.819  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:45.819  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.819  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:45.819  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:30:45.821  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:45.821  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.821  2152  2217 D BtGatt.GattService: registerClient() - UUID=5d307499-827a-4a4c-a659-07f3d69ac456
,03-24 15:30:45.822  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=5d307499-827a-4a4c-a659-07f3d69ac456, clientIf=6
03-24 15:30:45.822  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:45.822  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.822  3254  3272 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:45.823  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:45.824  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:45.826  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:45.829  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:30:45.829  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:45.830  2152  2217 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:45.831  2152  2218 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:45.831  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:30:45.831  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:45.831  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:45.831  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.831  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:45.831  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:45.832  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:45.832  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:45.832  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:30:45.834  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:45.834  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.834  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:45.834  2152  2218 D BtGatt.GattService: registerClient() - UUID=c35a39c1-39d3-459a-8ebc-85e2f8deb4e1
03-24 15:30:45.835  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=c35a39c1-39d3-459a-8ebc-85e2f8deb4e1, clientIf=5
03-24 15:30:45.835  3254  3272 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:45.835  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:45.835  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.836  2152  2168 D BtGatt.GattService: start scan with filters
,03-24 15:30:45.836  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:45.836  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:45.837  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 15:30:45.837  3254  3254 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:30:45.837  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:45.837  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:45.837  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:45.837  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:45.837  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:45.837  3254  3837 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 353)
,03-24 15:30:45.837  2152  2227 D BtGatt.ScanManager: handling starting scan
,03-24 15:30:45.839  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:45.839  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.839  3254  3837 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44842
03-24 15:30:45.839  3254  3837 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:30:45.839  3254  3837 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 44842 (peer ID: E0:DB:10:14:E2:C0)
03-24 15:30:45.840  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:45.840  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.840  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:30:45.840  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:45.840  3254  3837 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-24 15:30:45.841  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:45.841  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:45.842  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:45.842  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:45.842  3254  3314 I jxcore-log: INFO testThaliMobileNative: 
03-24 15:30:45.842  3254  3314 I jxcore-log: 
,03-24 15:30:45.843  3254  3314 I jxcore-log: ok 163 Must have listeningPort
03-24 15:30:45.843  3254  3314 I jxcore-log: 
,03-24 15:30:45.843  3254  3314 I jxcore-log: ok 164 listeningPort must be a number
03-24 15:30:45.843  3254  3314 I jxcore-log: 
03-24 15:30:45.843  3254  3314 I jxcore-log: ok 165 Connection must have clientPort
03-24 15:30:45.843  3254  3314 I jxcore-log: 
03-24 15:30:45.843  3254  3314 I jxcore-log: ok 166 clientPort must be a number
03-24 15:30:45.843  3254  3314 I jxcore-log: 
03-24 15:30:45.844  3254  3314 I jxcore-log: ok 167 Connection must have serverPort
03-24 15:30:45.844  3254  3314 I jxcore-log: 
03-24 15:30:45.844  3254  3314 I jxcore-log: ok 168 serverPort must be a number
03-24 15:30:45.844  3254  3314 I jxcore-log: 
03-24 15:30:45.844  3254  3314 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 15:30:45.844  3254  3314 I jxcore-log: 
03-24 15:30:45.844  3254  3314 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-24 15:30:45.844  3254  3314 I jxcore-log: 
03-24 15:30:45.848  3254  3314 I jxcore-log: # teardown
03-24 15:30:45.848  3254  3314 I jxcore-log: 
,03-24 15:30:48.374  2152  2359 W bt-btif : invalid rfc slot id: 10
,03-24 15:30:50.845  2152  2152 D BtGatt.ScanManager: awakened up at time 260338
,03-24 15:30:50.847  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:50.851  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:30:50.851  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:50.852  2152  2214 D BtGatt.GattService: current time is 260345305367
,03-24 15:30:50.852  2152  2214 D BtGatt.GattService: Batch record : [-121, -19, 4, -125, -7, 78, 1, -128, -79, 70, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -71, 92, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:30:50.853  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:50.853  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:50.855  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 15:30:50.855  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 15:30:51.161  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:30:51.161  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:30:51.161  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:30:51.161  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:30:51.164  2152  2217 D BtGatt.GattService: stopScan() - queue size =1,
03-24 15:30:51.165  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:30:51.166  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:51.166  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:30:51.166  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:30:51.166  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:30:51.166  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:30:51.166  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:51.167  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:30:51.167  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:51.168  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:30:51.168  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:51.168  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:30:51.168  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:51.170  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-24 15:30:51.170  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:51.170  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:51.171  3254  3314 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:30:51.171  3254  3314 I jxcore-log: 
03-24 15:30:51.171  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:30:51.172  3254  3314 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:30:51.172  3254  3314 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 353)
,03-24 15:30:51.172  3254  3314 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 353)
03-24 15:30:51.173  3254  3314 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:30:51.173  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:51.173  3254  3314 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 353)
03-24 15:30:51.173  3254  3314 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 353)
03-24 15:30:51.173  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:51.174  3254  3837 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 353)
03-24 15:30:51.175  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:30:51.175  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:30:51.175  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:30:51.175  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:30:51.175  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:30:51.176  3254  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:30:51.176  3254  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:30:51.176  3254  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:30:51.176  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:30:51.177  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:30:51.177  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 15:30:51.177  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:30:51.177  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:30:51.177  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:30:51.177  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:30:51.177  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:30:51.180  3254  3314 D BluetoothLeScanner: could not find callback wrapper
,03-24 15:30:51.180  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:51.180  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-24 15:30:51.183  2152  2226 D BtGatt.AdvertiseManager: message : 1,
03-24 15:30:51.184  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:30:51.187  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:51.187  2152  2214 D BtGatt.GattService: Client app is not null!
,03-24 15:30:51.188  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:51.189  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:51.189  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-24 15:30:51.190  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:30:51.190  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:30:51.190  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:30:51.190  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:30:51.190  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:30:51.190  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:30:51.192  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:30:51.192  3254  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:30:51.192  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 15:30:51.192  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:30:51.192  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:30:51.192  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:30:51.192  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:51.192  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:30:51.197  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:30:51.197  3254  3314 I jxcore-log: 
03-24 15:30:51.203  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:30:51.203   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:30:51.205  3254  3314 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:30:51.205  3254  3314 I jxcore-log: 
,03-24 15:30:51.209  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:30:51.210  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:51.210  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:30:51.215  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:30:51.216  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:30:51.217  3254  3314 I jxcore-log: # setup
03-24 15:30:51.217  3254  3314 I jxcore-log: 
,03-24 15:30:51.220  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 15:30:51.220  3254  3314 I jxcore-log: 
03-24 15:30:51.221  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:30:51.221  3254  3314 I jxcore-log: 
,03-24 15:30:51.301  3254  3314 I jxcore-log: # 39. Can shift large amounts of data
03-24 15:30:51.301  3254  3314 I jxcore-log: 
,03-24 15:30:51.424  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:30:51.725  2152  2228 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 15:30:51.731  2152  2152 D BluetoothMapService: onReceive
,03-24 15:30:51.754   822   860 D BluetoothManagerService: Message: 20
03-24 15:30:51.754   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2418c5cc:true
,03-24 15:30:51.778  1500  1500 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:30:51.784  1500  1500 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:30:52.504  3361  3840 V GoogleAuthProtoRequest: [339] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:30:52.560  3361  3841 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:30:52.642  1321  3605 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 15:30:52.643  1321  3605 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:30:52.643  1321  3605 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:30:52.644  1321  3605 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:52.651  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 15:30:52.657  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:30:52.657  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:30:52.659  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:30:52.663  1321  3605 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:52.674  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:30:52.696  3361  3841 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97),
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	,at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167),
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:30:52.697  3361  3840 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	,at com.a.a.a.k.get(SourceFile:97)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source),
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:30:52.697  3361  3841 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:30:52.846  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 51811, start advertisements: true
03-24 15:30:52.846  3254  3314 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:52.846  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:52.847  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:52.847  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:52.847  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 15:30:52.850  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:30:52.850  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:52.850  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:52.850  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:52.852  2152  2217 D BtGatt.GattService: registerClient() - UUID=ef52841e-275b-47f7-beda-53926294d8f9
03-24 15:30:52.853  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=ef52841e-275b-47f7-beda-53926294d8f9, clientIf=5
03-24 15:30:52.853  3254  3272 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:52.854  2152  2218 D BtGatt.GattService: start scan with filters
03-24 15:30:52.854  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:52.854  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:52.854  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:52.855  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:30:52.855  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:30:52.855  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:52.855  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:52.855  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:52.855  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:30:52.855  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:52.856  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:52.856  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:52.856  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:52.870  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:52.870  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:52.870  2152  2218 D BtGatt.GattService: registerClient() - UUID=1fbfb2ee-cd30-482a-87d5-28efcc75ce58
03-24 15:30:52.870  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=1fbfb2ee-cd30-482a-87d5-28efcc75ce58, clientIf=6
03-24 15:30:52.870  3254  3270 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:30:52.871  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:52.871  2152  2226 D BtGatt.AdvertiseManager: message : 0
03-24 15:30:52.871  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:52.872  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:52.872  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:52.873  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
03-24 15:30:52.874  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:52.874  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:52.876  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-24 15:30:52.876  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:52.877  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:52.879  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 15:30:52.880  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:52.880  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:30:52.881   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:52.882  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:52.882  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:30:52.882  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:30:52.882  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:30:52.883  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:30:52.883  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:30:52.883  3254  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:30:52.883  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:30:52.883  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:30:52.883  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:30:52.883  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:52.883  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:52.883  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:52.883  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:30:52.883  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:30:52.883  3254  3254 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:52.883  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:30:52.883  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:30:52.883  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:30:52.884  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:30:52.884  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:30:52.884   822  1213 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:52.884  3254  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:52.885  3254  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:30:52.886  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:52.886  3254  3314 I jxcore-log: 
03-24 15:30:52.889  3254  3314 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 15:30:52.889  3254  3314 I jxcore-log: 
03-24 15:30:52.891  3254  3314 I io.jxcore.node.ConnectionHelper: start: Port number: 51811, start advertisements: false
03-24 15:30:52.891  3254  3314 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:30:52.891  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:30:52.891  3254  3314 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:30:52.891  3254  3314 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:30:52.891  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:30:52.891  3254  3314 I jxcore-log: 
03-24 15:30:52.892  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:30:52.892  3254  3314 I jxcore-log: 
03-24 15:30:52.893  3254  3314 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error
03-24 15:30:52.893  3254  3314 I jxcore-log: 
,03-24 15:30:53.886  2152  2152 D BtGatt.ScanManager: awakened up at time 263379
03-24 15:30:53.887  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:30:53.894  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3,
03-24 15:30:53.895  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 15:30:53.895  2152  2214 D BtGatt.GattService: current time is 263388455730
03-24 15:30:53.895  2152  2214 D BtGatt.GattService: Batch record : [17, -94, 76, -115, 109, 94, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, -44, -106, -22, -38, 116, 0, -128, -104, 1, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-24 15:30:53.897  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:30:53.898  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:30:53.901  2152  2214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0],
,03-24 15:30:53.904  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1,
03-24 15:30:53.905  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 15:30:53.906  3254  3254 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: ,
,03-24 15:30:53.907  3254  3254 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:30:53.914  3254  3314 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 15:30:53.914  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:30:53.917  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 15:30:53.917  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-24 15:30:53.917  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 15:30:53.917  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-24 15:30:53.917  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 15:30:53.917  3254  3314 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 15:30:53.919  3254  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 355)
03-24 15:30:53.920  3254  3843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:30:53.923  2152  2168 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 15:30:56.082  2152  2228 W bt-btif : info:x10,
03-24 15:30:56.082  2152  2214 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 15:30:56.112  1500  1500 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:30:56.117  1500  1500 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:30:56.168  2152  2228 W bt-sdp  : process_service_search_attr_rsp
,03-24 15:30:58.359  2152  2228 W bt-btif : info:x10
03-24 15:30:58.359  2152  2214 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-24 15:30:58.360  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 15:30:58.567  2152  2214 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,03-24 15:30:58.575  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-24 15:30:58.575  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c,
,03-24 15:30:58.582  2152  2216 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-24 15:30:58.583  2152  2216 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 15:30:58.680  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 15:30:58.681  2152  2216 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
03-24 15:30:58.684  2152  2216 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 15:30:58.701  2152  2216 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 15:30:58.729  2152  2228 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 15:30:58.729  2152  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:30:58.729  2152  2228 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:30:58.729  3254  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 15:30:58.730  3254  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 356)
,03-24 15:30:58.730  3254  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:30:58.730   822  1293 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:30:58.731  3254  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:30:58.734  3254  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:30:58.736  3254  3844 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 356)
,03-24 15:30:58.743  3254  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 356)
,03-24 15:30:58.747  3254  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 15:30:58.749  3254  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 356)
03-24 15:30:58.749  3254  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 356
03-24 15:30:58.750  3254  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 356)
03-24 15:30:58.750  3254  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:30:58.751  3254  3844 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 356)
03-24 15:30:58.751  3254  3254 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-24 15:30:58.751  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 15:30:58.751  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 15:30:58.753  3254  3254 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:58.753  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:30:58.760  2152  2226 D BtGatt.AdvertiseManager: message : 1,
03-24 15:30:58.761  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:30:58.765  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:58.765  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:58.768  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:58.768  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:58.768  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:58.768  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:30:58.768  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:58.768  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:58.769  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:58.769  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:58.769  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:58.769  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:58.773  2152  2169 D BtGatt.GattService: registerClient() - UUID=e7835129-5f40-4e81-ab43-eef13eaf6101
03-24 15:30:58.773  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=e7835129-5f40-4e81-ab43-eef13eaf6101, clientIf=6
03-24 15:30:58.774  3254  3270 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:30:58.775  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:58.778  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:58.781  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:58.783  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:30:58.784  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:30:58.785  2152  2217 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:30:58.786  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:30:58.787  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:30:58.787  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.787  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:30:58.787  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:58.787  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:58.787  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:58.788  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:58.788  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:58.788  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:58.789  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 15:30:58.789  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.789  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:58.791  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:30:58.791  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.792  2152  2214 D BtGatt.GattService: current time is 268285192603
,03-24 15:30:58.792  2152  2214 D BtGatt.GattService: Batch record : [17, -94, 76, -115, 109, 94, 1, -128, -73, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 65, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 15:30:58.792  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:30:58.792  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:58.794  2152  2217 D BtGatt.GattService: registerClient() - UUID=94e8f605-861d-46fd-b484-3ecaea73f8c4
03-24 15:30:58.794  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=94e8f605-861d-46fd-b484-3ecaea73f8c4, clientIf=5,
03-24 15:30:58.795  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:58.795  2152  2218 D BtGatt.GattService: start scan with filters
03-24 15:30:58.796  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:58.796  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:58.796  2152  2227 D BtGatt.ScanManager: handling starting scan
,03-24 15:30:58.796  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 15:30:58.797  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:58.797  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:58.797  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:58.797  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:58.797  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:30:58.797  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:30:58.799  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:58.799  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.801  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:58.801  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.801  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:58.801  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:58.801  2152  2226 D BtGatt.AdvertiseManager: message : 1
03-24 15:30:58.802  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:30:58.803  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:58.803  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.804  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:30:58.804  2152  2214 D BtGatt.GattService: Client app is not null!
,03-24 15:30:58.807  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 15:30:58.807  2152  2217 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:30:58.807  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.807  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:58.807  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:30:58.807  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:58.807  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-24 15:30:58.808  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:58.808  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:58.808  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:58.808  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:58.808  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-24 15:30:58.811  2152  2168 D BtGatt.GattService: registerClient() - UUID=c012acef-2d9f-48e0-987a-1370e162198a
03-24 15:30:58.811  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=c012acef-2d9f-48e0-987a-1370e162198a, clientIf=6,
03-24 15:30:58.812  3254  3270 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:30:58.812  2152  2226 D BtGatt.AdvertiseManager: message : 0
,03-24 15:30:58.815  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:58.817  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:58.819  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:30:58.819  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:30:58.820  2152  2217 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:58.821  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:30:58.821  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:58.821  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:58.821  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:58.821  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:58.821  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:58.822  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:30:58.822  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.822  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:58.822  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:58.825  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:58.825  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:58.825  2152  2168 D BtGatt.GattService: registerClient() - UUID=22cfe887-e2d5-47f2-9efe-9ca4e34ab4b2
,03-24 15:30:58.825  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=22cfe887-e2d5-47f2-9efe-9ca4e34ab4b2, clientIf=5
03-24 15:30:58.825  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:58.825  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:58.825  2152  2218 D BtGatt.GattService: start scan with filters
03-24 15:30:58.826  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:30:58.826  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:30:58.826  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 15:30:58.827  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.827  2152  2214 D BtGatt.GattService: current time is 268320225780
03-24 15:30:58.827  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:30:58.827  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:30:58.829  2152  2226 D BtGatt.AdvertiseManager: message : 1
,03-24 15:30:58.830  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:30:58.832  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 15:30:58.832  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:30:58.832  2152  2227 D BtGatt.ScanManager: handling starting scan
03-24 15:30:58.833  2152  2218 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:30:58.833  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:30:58.833  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 15:30:58.833  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:30:58.833  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:30:58.833  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:30:58.833  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:30:58.834  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:58.834  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:30:58.834  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:30:58.835  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:30:58.835  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.836  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:58.836  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:58.836  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:58.836  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:58.838  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:58.838  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.838  2152  2218 D BtGatt.GattService: registerClient() - UUID=fbc29770-2a5b-48b7-bb4a-efbc42ac89c1
,03-24 15:30:58.838  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=fbc29770-2a5b-48b7-bb4a-efbc42ac89c1, clientIf=6
03-24 15:30:58.838  3254  3270 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:30:58.839  2152  2226 D BtGatt.AdvertiseManager: message : 0
03-24 15:30:58.840  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:58.840  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:58.843  2152  2226 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:30:58.845  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:30:58.847  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:30:58.847  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-24 15:30:58.849  2152  2168 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:30:58.849  2152  2218 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:30:58.850  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:30:58.850  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:30:58.850  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:30:58.850  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:30:58.850  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:30:58.850  3254  3254 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:30:58.850  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:30:58.850  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.850  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:30:58.853  2152  2218 D BtGatt.GattService: registerClient() - UUID=32b939b8-359c-4da4-8088-68886bb83b87
03-24 15:30:58.853  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:30:58.853  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:58.853  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=32b939b8-359c-4da4-8088-68886bb83b87, clientIf=5
03-24 15:30:58.854  3254  3270 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:30:58.854  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:30:58.854  2152  2169 D BtGatt.GattService: start scan with filters
,03-24 15:30:58.855  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:30:58.855  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:30:58.855  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:30:58.855  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.855  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-24 15:30:58.855  3254  3254 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:30:58.855  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:58.855  3254  3254 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:30:58.855  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:30:58.855  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:58.855  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:30:58.856  3254  3845 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 357)
,03-24 15:30:58.858  2152  2227 D BtGatt.ScanManager: handling starting scan
,03-24 15:30:58.859  3254  3845 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 51811
03-24 15:30:58.860  3254  3845 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:30:58.860  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:30:58.860  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.861  3254  3845 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:30:58.861  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:30:58.861  3254  3845 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:30:58.861  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:30:58.861  2152  2227 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:30:58.861  2152  2227 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:30:58.863  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:30:58.863  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.863  3254  3847 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 358, name: Sender)
03-24 15:30:58.863  3254  3845 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 357)
03-24 15:30:58.863  3254  3845 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 357)
03-24 15:30:58.864  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:30:58.864  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:30:58.864  3254  3848 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 359, name: Receiver)
,03-24 15:31:02.084  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:31:03.187  2152  2228 W bt-btif : new conn_srvc id:26, app_id:255
03-24 15:31:03.187  2152  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:31:03.187  2152  2228 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:31:03.188  3254  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 15:31:03.189  3254  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 360)
03-24 15:31:03.190  3254  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:31:03.191   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:31:03.196  3254  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:31:03.197  3254  3850 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 360)
,03-24 15:31:03.201  3254  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:31:03.222  2152  2228 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:31:03.222  2152  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-24 15:31:03.222  2152  2228 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:31:03.222  2152  2228 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:31:03.222  3254  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 355)
03-24 15:31:03.223  3254  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 355)
,03-24 15:31:03.224  3254  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 361)
03-24 15:31:03.224  3254  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 361)
03-24 15:31:03.224  3254  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 355)
,03-24 15:31:03.230  3254  3851 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 361)
,03-24 15:31:03.238  3254  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 360)
,03-24 15:31:03.243  3254  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:31:03.243  3254  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 360)
03-24 15:31:03.244  3254  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 360
03-24 15:31:03.244  3254  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 360)
,03-24 15:31:03.245  3254  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:31:03.245  3254  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 361)
,03-24 15:31:03.249  3254  3254 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:31:03.249  3254  3850 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 360)
03-24 15:31:03.250  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:31:03.250  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 15:31:03.251  3254  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:31:03.251  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 15:31:03.251  3254  3254 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 15:31:03.251  3254  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 355)
03-24 15:31:03.251  3254  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 355)
03-24 15:31:03.252  3254  3851 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 361)
03-24 15:31:03.252  3254  3254 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:31:03.252  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:31:03.252  3254  3254 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 15:31:03.254  3254  3254 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 15:31:03.254  3254  3254 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
03-24 15:31:03.257  3254  3852 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 362)
,03-24 15:31:03.259  3254  3853 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 363)
03-24 15:31:03.261  3254  3853 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45649
03-24 15:31:03.261  3254  3853 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:31:03.261  3254  3853 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 45649 (peer ID: E0:DB:10:14:E2:C0)
,03-24 15:31:03.262  3254  3853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 15:31:03.264  3254  3314 I jxcore-log: INFO testThaliMobileNative: 
03-24 15:31:03.264  3254  3314 I jxcore-log: 
,03-24 15:31:03.264  3254  3852 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 51811
03-24 15:31:03.264  3254  3852 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:31:03.265  3254  3314 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 15:31:03.265  3254  3314 I jxcore-log: 
03-24 15:31:03.265  3254  3852 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.265  3254  3852 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.266  3254  3852 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 362)
03-24 15:31:03.266  3254  3852 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 362)
,03-24 15:31:03.270  3254  3853 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 45649
03-24 15:31:03.270  3254  3853 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:31:03.271  3254  3853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.271  3254  3855 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Sender)
,03-24 15:31:03.273  3254  3856 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Receiver)
,03-24 15:31:03.273  3254  3853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:31:03.273  3254  3853 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 363)
03-24 15:31:03.273  3254  3853 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 363)
,03-24 15:31:03.276  3254  3857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Sender)
,03-24 15:31:03.278  3254  3858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 367, name: Receiver)
,03-24 15:31:03.287  3254  3314 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 15:31:03.287  3254  3314 I jxcore-log: 
,03-24 15:31:03.834  3254  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:03.834  3254  3314 I jxcore-log: 
,03-24 15:31:03.871  2152  2152 D BtGatt.ScanManager: awakened up at time 273364
,03-24 15:31:03.873  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:31:03.876  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 15:31:03.876  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:31:03.967  3254  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:03.967  3254  3314 I jxcore-log: 
,03-24 15:31:03.972  3254  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:03.972  3254  3314 I jxcore-log: 
,03-24 15:31:04.042  3254  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.042  3254  3314 I jxcore-log: 
,03-24 15:31:04.106  3254  3314 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:31:04.106  3254  3314 I jxcore-log: 
,03-24 15:31:04.108  3254  3314 I jxcore-log: ok 175 received should match sent forward
03-24 15:31:04.108  3254  3314 I jxcore-log: 
,03-24 15:31:04.123  3254  3314 I jxcore-log: # teardown
03-24 15:31:04.123  3254  3314 I jxcore-log: 
,03-24 15:31:05.473  3254  3847 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 358, thread name: Sender)
,03-24 15:31:05.474  3254  3847 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 15:31:05.474  3254  3847 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-24 15:31:05.474  3254  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 357
03-24 15:31:05.474  3254  3855 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 364, thread name: Sender)
03-24 15:31:05.474  3254  3847 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 357)
03-24 15:31:05.474  3254  3855 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 15:31:05.474  3254  3855 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-24 15:31:05.475  3254  3847 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:31:05.476  3254  3848 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Receiver): bt socket closed, read return: -1
03-24 15:31:05.476  3254  3848 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 359, name: Receiver)
03-24 15:31:05.478  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:31:05.478  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only,
,03-24 15:31:05.478  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:31:05.478  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:31:05.481  3254  3847 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 15:31:05.481  3254  3847 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 359
03-24 15:31:05.481  3254  3847 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 15:31:05.481  3254  3847 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 358
03-24 15:31:05.481  3254  3847 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 357)
03-24 15:31:05.482  2152  2217 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:31:05.483  3254  3847 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 357)
03-24 15:31:05.483  3254  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-24 15:31:05.484  3254  3847 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 358, name: Sender)
03-24 15:31:05.486  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:31:05.487  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:31:05.487  3254  3855 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 362
03-24 15:31:05.487  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:31:05.487  3254  3855 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 362)
03-24 15:31:05.488  2152  2227 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:31:05.488  3254  3855 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:31:05.489  3254  3855 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 15:31:05.489  3254  3856 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
03-24 15:31:05.489  3254  3855 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-24 15:31:05.489  3254  3856 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Receiver)
03-24 15:31:05.489  3254  3855 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 15:31:05.489  3254  3855 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364
03-24 15:31:05.489  3254  3855 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 362)
03-24 15:31:05.489  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:31:05.489  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:05.490  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:31:05.490  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:31:05.490  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:31:05.490  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:31:05.490  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:31:05.491  3254  3855 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 362)
03-24 15:31:05.491  2152  2227 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:31:05.492  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:31:05.492  3254  3855 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 15:31:05.492  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:31:05.492  3254  3855 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Sender)
03-24 15:31:05.493  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:31:05.493  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:31:05.492  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:31:05.493  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:31:05.499  3254  3314 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 15:31:05.499  3254  3314 I jxcore-log: 
,03-24 15:31:05.501  3254  3314 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 15:31:05.501  3254  3314 I jxcore-log: 
03-24 15:31:05.504  3254  3314 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:31:05.504  3254  3314 I jxcore-log: 
03-24 15:31:05.506  3254  3314 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:31:05.506  3254  3314 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:31:05.506  3254  3314 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 363)
03-24 15:31:05.507  3254  3314 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 363)
03-24 15:31:05.508  3254  3858 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 367, thread name: Receiver): bt socket closed, read return: -1
,03-24 15:31:05.508  3254  3858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 367, name: Receiver)
03-24 15:31:05.509  3254  3314 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:31:05.510  3254  3314 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 15:31:05.510  3254  3314 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 367
,03-24 15:31:05.510  3254  3314 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 15:31:05.510  3254  3314 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
03-24 15:31:05.510  3254  3314 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 363)
03-24 15:31:05.510  3254  3857 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Sender): Socket closed
03-24 15:31:05.510  3254  3857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Sender)
03-24 15:31:05.511  3254  3314 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 363)
03-24 15:31:05.511  3254  3314 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:31:05.511  3254  3314 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:31:05.511  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:31:05.511  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:31:05.511  3254  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:31:05.511  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:31:05.511  3254  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:31:05.511  3254  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:31:05.511  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:31:05.511  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:31:05.511  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:31:05.511  3254  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:31:05.511  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:31:05.512  3254  3314 D BluetoothLeScanner: could not find callback wrapper
03-24 15:31:05.512  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:31:05.512  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:31:05.515  2152  2226 D BtGatt.AdvertiseManager: message : 1
03-24 15:31:05.515  2152  2226 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:31:05.518  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 15:31:05.518  2152  2214 D BtGatt.GattService: Client app is not null!
03-24 15:31:05.518  2152  2168 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:31:05.519  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:31:05.519  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:31:05.519  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:31:05.519  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:31:05.519  3254  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:31:05.519  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:31:05.519  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:31:05.519  3254  3314 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:31:05.520  3254  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:31:05.520  3254  3314 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:31:05.520  3254  3314 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:31:05.521  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:31:05.521  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:31:05.521  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:31:05.524  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:31:05.524  3254  3314 I jxcore-log: 
,03-24 15:31:05.526  3254  3254 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:31:05.526   822  1213 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:31:05.532  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:31:05.532  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:05.532  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:31:05.533  3254  3254 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:31:05.533  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:31:05.537  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:31:05.537  3254  3254 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:31:05.537  3254  3254 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:31:05.537  3254  3254 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:31:05.537  3254  3254 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:31:05.539  3254  3314 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:31:05.539  3254  3314 I jxcore-log: 
,03-24 15:31:05.544  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:31:05.544  3254  3314 I jxcore-log: 
03-24 15:31:05.544  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:31:05.544  3254  3314 I jxcore-log: 
03-24 15:31:05.545  3254  3314 I jxcore-log: # setup
03-24 15:31:05.545  3254  3314 I jxcore-log: 
,03-24 15:31:05.601  2152  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
03-24 15:31:05.601  2152  2228 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 15:31:05.856  2152  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,03-24 15:31:05.856  2152  2228 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 15:31:05.858  2152  2228 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-24 15:31:07.238  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:31:07.238  3254  3314 I jxcore-log: 
,03-24 15:31:07.240  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:31:07.240  3254  3314 I jxcore-log: 
,03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:31:07.247  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,03-24 15:31:07.252  3254  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:31:07.254  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:31:07.254  3254  3314 I jxcore-log: 
,03-24 15:31:07.256  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:31:07.256  3254  3314 I jxcore-log: 
,03-24 15:31:07.260  3254  3314 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-24 15:31:07.260  3254  3314 I jxcore-log: 
,03-24 15:31:07.262  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:31:07.262  3254  3314 I jxcore-log: 
,03-24 15:31:11.015  3254  3314 I jxcore-log: ok 178 specific error should be returned
03-24 15:31:11.015  3254  3314 I jxcore-log: 
,03-24 15:31:11.019  3254  3314 I jxcore-log: # teardown
03-24 15:31:11.019  3254  3314 I jxcore-log: 
,03-24 15:31:11.589  2152  2228 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 15:31:11.596  2152  2152 D BluetoothMapService: onReceive
,03-24 15:31:11.604  2152  2228 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-24 15:31:11.615  2152  2152 D BluetoothMapService: onReceive
,03-24 15:31:11.622  1500  1500 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:31:11.625  1500  1500 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 15:31:11.668  1500  1500 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:31:11.671  1500  1500 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:31:12.465  2152  2228 W bt-btif : dm_pm_timer expires
,03-24 15:31:12.465  2152  2228 W bt-btif : dm_pm_timer expires 0
03-24 15:31:12.466  2152  2228 W bt-btif : proc dm_pm_timer expires
,03-24 15:31:15.626  3254  3314 I jxcore-log: # setup
03-24 15:31:15.626  3254  3314 I jxcore-log: 
,03-24 15:31:18.900  3436  3861 V KeepSync: Connecting to GoogleApiClient
,03-24 15:31:18.991  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 15:31:18.992  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:31:18.992  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:31:18.992  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:31:18.998  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: Handling authorization failure
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:31:19.016  1772  3862 E ClientConnectionOperation: 	... 7 more
,03-24 15:31:19.019  3436  3861 V KeepSync: GoogleApiClient failed to connect with error code: 4,
,03-24 15:31:19.021  3436  3861 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
03-24 15:31:19.027  3436  3861 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 15:31:19.028  3436  3861 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:31:19.141  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 15:31:19.142  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:31:19.142  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:31:19.142  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:31:19.155  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:31:19.224  3436  3861 E KeepSync: IOException
03-24 15:31:19.224  3436  3861 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:31:19.224  3436  3861 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:31:19.224  3436  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:31:19.224  3436  3861 E KeepSync: 	... 10 more
03-24 15:31:19.224  3436  3861 W KeepSync: Sync result 2
,03-24 15:31:19.243   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 288220, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:31:19.590  3254  3254 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 15:31:19.591  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2,
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:31:19.592  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:31:19.593  3254  3254 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:31:19.594  3254  3254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:31:24.604  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:31:24.604  3254  3314 I jxcore-log: 
,03-24 15:31:24.609  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:31:24.609  3254  3314 I jxcore-log: 
,03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:31:24.618  3254  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:31:24.622  3254  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-24 15:31:24.626  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 15:31:24.626  3254  3314 I jxcore-log: 
,03-24 15:31:24.630  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 15:31:24.630  3254  3314 I jxcore-log: 
,03-24 15:31:24.636  3254  3314 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:31:24.636  3254  3314 I jxcore-log: 
,03-24 15:31:24.638  3254  3314 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:31:24.638  3254  3314 I jxcore-log: 
,03-24 15:31:38.377  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:31:40.021  3254  3314 I jxcore-log: ok 179 specific error should be returned
03-24 15:31:40.021  3254  3314 I jxcore-log: 
03-24 15:31:40.023  3254  3314 I jxcore-log: # teardown
03-24 15:31:40.023  3254  3314 I jxcore-log: 
,03-24 15:31:48.808  3492  3873 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:31:48.883   822  1106 I art     : Explicit concurrent mark sweep GC freed 34123(1660KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.451ms total 71.700ms
,03-24 15:31:48.923  3492  3876 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:31:48.944  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:31:48.944  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:31:48.944  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:31:48.944  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:31:48.944  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:31:48.944  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 15:31:48.944  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:31:48.944  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:31:48.948  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 15:31:48.948  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:31:48.959  3078  3872 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:31:48.959  3078  3872 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:31:48.959  3078  3872 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	... 12 more
03-24 15:31:48.959  3078  3872 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at fal.a(PG:38)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:31:48.959  3078  3872 E HttpOperation: 	... 14 more
,03-24 15:31:48.994  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 15:31:48.994  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:31:48.994  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:31:48.995  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:31:48.997  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:31:49.002  1321  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:31:49.002  1321  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:31:49.002  1321  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:31:49.002  1321  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:31:49.005  1321  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:31:49.009  3078  3872 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:31:49.009  3078  3872 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at hec.a(PG:42)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at hee.a(PG:102)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at czr.a(PG:65)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at kka.a(PG:108)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:31:49.009  3078  3872 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	... 15 more
03-24 15:31:49.009  3078  3872 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at fal.a(PG:38)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:31:49.009  3078  3872 E HttpOperation: 	... 17 more
,03-24 15:31:49.009  3078  3872 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:31:49.009  3078  3872 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jcn.a(PG:1379)
,03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at czq.run(PG:1686)
,03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	... 15 more
03-24 15:31:49.009  3078  38,72 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:31:49.009  3078  3872 E ExperimentLoader: 	... 17 more
,03-24 15:31:49.016  3492  3876 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:31:49.017  3492  3873 E BooksSync: Soft error
03-24 15:31:49.017  3492  3873 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:31:49.017  3492  3873 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:31:49.018  3492  3873 E BooksSync: Sync error
03-24 15:31:49.018  3492  3873 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:31:49.018  3492  3873 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:31:49.018  3492  3873 I BooksSync: Finished books sync
,03-24 15:31:49.023   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 291424, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:31:49.099   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 289462, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:31:54.129   822  2340 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@96ea4a7}
,03-24 15:31:54.136   822  1024 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 15:31:55.835   822   840 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@96ea4a7}
,03-24 15:31:55.898   822  1255 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 15:31:55.970   877   877 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-24 15:31:55.971   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 15:31:56.012   877   877 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-24 15:31:56.012   877   877 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 15:31:56.986   877   877 I kickstart: STATUS: Received file 'm9kefs1'
,03-24 15:31:56.987   877   877 I kickstart: STATUS: 950272 bytes transferred in 0.973994 seconds
03-24 15:31:56.987   877   877 I kickstart: STATUS: Successfully downloaded files from target 
03-24 15:31:56.988   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 15:31:56.992   877   877 I kickstart: STATUS: Sahara protocol completed
,03-24 15:32:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:32:54.224  3361  3889 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:32:54.330  3361  3890 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:32:54.451  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 15:32:54.451  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:32:54.452  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:32:54.452  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:32:54.456  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:32:54.459  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:32:54.459  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:32:54.460  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:32:54.460  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:32:54.466  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:32:54.471  3361  3890 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:32:54.499  1321  1321 I art     : Explicit concurrent mark sweep GC freed 51880(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 990us total 26.749ms
,03-24 15:32:54.520  3361  3889 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:32:54.521  3361  3889 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:33:19.836  3436  3896 V KeepSync: Connecting to GoogleApiClient
,03-24 15:33:19.915  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 15:33:19.915  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:33:19.915  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:33:19.915  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:33:19.923  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: Handling authorization failure
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:33:19.953  1772  3897 E ClientConnectionOperation: 	... 7 more
,03-24 15:33:19.957  3436  3896 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 15:33:19.962  3436  3896 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:33:19.979  3436  3896 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 15:33:19.980  3436  3896 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:33:20.069  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 15:33:20.070  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:33:20.070  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:33:20.070  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:33:20.083  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:33:20.183  3436  3896 E KeepSync: IOException
03-24 15:33:20.183  3436  3896 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:33:20.183  3436  3896 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:33:20.183  3436  3896 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:33:20.183  3436  3896 E KeepSync: 	... 10 more
03-24 15:33:20.184  3436  3896 W KeepSync: Sync result 2
,03-24 15:33:20.194   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 409269, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:33:24.659   822  2340 I ActivityManager: Start proc 3902:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,03-24 15:33:24.792  3902  3919 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 15:33:24.792  3902  3919 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:33:24.826  3902  3919 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-24 15:33:24.920  3902  3919 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 15:33:24.936  3931  3931 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads652552733.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads652552733.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-24 15:33:24.936  3902  3902 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-24 15:33:24.975  3931  3931 I dex2oat : dex2oat took 38.885ms (threads: 4) arena alloc=133KB java alloc=12KB native alloc=964KB free=7MB
,03-24 15:33:25.123  3902  3902 W InstanceID/Rpc: Found 10011
,03-24 15:33:25.217   822  1190 I ActivityManager: Killing 3610:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-24 15:33:37.503  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:33:38.696  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:34:19.922  3492  4003 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:34:19.965  3492  4004 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:34:20.033   822   841 I art     : Explicit concurrent mark sweep GC freed 34268(1534KB) AllocSpace objects, 7(394KB) LOS objects, 32% free, 33MB/49MB, paused 1.602ms total 67.784ms
,03-24 15:34:20.094  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:34:20.094  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:34:20.094  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:34:20.094  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:34:20.096  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 15:34:20.097  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:34:20.097  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:34:20.097  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:34:20.098  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:34:20.103  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:34:20.111  3078  4002 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:34:20.111  3078  4002 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:34:20.111  3078  4002 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	... 12 more
03-24 15:34:20.111  3078  4002 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at fal.a(PG:38)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:34:20.111  3078  4002 E HttpOperation: 	... 14 more
,03-24 15:34:20.145  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 15:34:20.145  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:34:20.146  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:34:20.146  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:34:20.150  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:34:20.162  3078  4002 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:34:20.162  3078  4002 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at hec.a(PG:42)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at hee.a(PG:102)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at czr.a(PG:65)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at kka.a(PG:108)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:34:20.162  3078  4002 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	... 15 more
03-24 15:34:20.162  3078  4002 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at fal.a(PG:38)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:34:20.162  3078  4002 E HttpOperation: 	... 17 more
,03-24 15:34:20.163  3078  4002 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:34:20.163  3078  4002 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	... 15 more
03-24 15:34:20.163  3078  4002 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:34:20.163  3078  4002 E ExperimentLoader: 	... 17 more
,03-24 15:34:20.173  1321  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:34:20.173  1321  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:34:20.173  1321  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:34:20.173  1321  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:34:20.177  1321  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:34:20.186  3492  4004 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:34:20.188  3492  4003 E BooksSync: Soft error
03-24 15:34:20.188  3492  4003 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:34:20.188  3492  4003 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:34:20.188  3492  4003 E BooksSync: Sync error
03-24 15:34:20.188  3492  4003 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:34:20.188  3492  4003 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:34:20.188  3492  4003 I BooksSync: Finished books sync
,03-24 15:34:20.195   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 444853, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:34:20.252   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 441525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:34:30.153  1321  1321 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:34:30.217  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:34:30.217  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:34:30.217  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:34:30.218  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:34:30.229  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:34:30.301  1321  1351 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:34:30.301  1321  1351 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:34:30.301  1321  1351 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:34:30.301  1321  1351 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 15:34:30.301  1321  1351 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 15:34:30.301  1321  1351 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 15:34:30.301  1321  1351 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 15:34:30.308  3672  3706 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:34:30.308  3672  3706 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 15:34:30.308  3672  3706 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 15:34:30.308  3672  3706 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 15:34:30.308  3672  3706 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 15:34:30.308  3672  3706 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 15:34:30.308  3672  3706 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 15:34:30.338  3672  3706 W System  : Ignoring header User-Agent because its value was null.
,03-24 15:34:37.501  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:35:37.501  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:36:37.501  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:36:39.177  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:37:00.371  3361  4033 V GoogleAuthProtoRequest: [343] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:37:00.390  3361  4034 V GoogleAuthProtoRequest: [344] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:37:00.489  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 15:37:00.490  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:37:00.490  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:37:00.490  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:37:00.498  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:37:00.517  1321  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 15:37:00.518  1321  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:37:00.518  1321  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:37:00.518  1321  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:37:00.532  1321  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:37:00.536  3361  4034 W ExperimentUpdateService: [344] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: [344] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:37:00.538  3361  4034 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:37:00.572  3361  4033 W ExperimentUpdateService: [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:37:00.573  3361  4033 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:37:21.385  3436  4040 V KeepSync: Connecting to GoogleApiClient
,03-24 15:37:21.478  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 15:37:21.479  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:37:21.479  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:37:21.479  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:37:21.489  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: Handling authorization failure
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:37:21.526  1772  4041 E ClientConnectionOperation: 	... 7 more
,03-24 15:37:21.533  3436  4040 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 15:37:21.539  3436  4040 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:37:21.549  3436  4040 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:37:21.550  3436  4040 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:37:21.627  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 15:37:21.627  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:37:21.627  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:37:21.627  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:37:21.633  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:37:21.693  3436  4040 E KeepSync: IOException
03-24 15:37:21.693  3436  4040 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:37:21.693  3436  4040 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:37:21.693  3436  4040 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:37:21.693  3436  4040 E KeepSync: 	... 10 more
03-24 15:37:21.693  3436  4040 W KeepSync: Sync result 2
,03-24 15:37:21.702   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 650751, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:37:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:37:39.337  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:38:26.325  1321  1617 I art     : Explicit concurrent mark sweep GC freed 53402(2MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 1.548ms total 44.565ms
,03-24 15:38:26.369  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 15:38:26.369  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:38:26.370  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:38:26.370  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:38:26.374  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:38:26.396  3078  4062 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:38:26.396  3078  4062 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:38:26.396  3078  4062 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	... 12 more
03-24 15:38:26.396  3078  4062 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at fal.a(PG:38)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:38:26.396  3078  4062 E HttpOperation: 	... 14 more
,03-24 15:38:26.480  1321  1909 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:38:26.480  1321  1909 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:38:26.480  1321  1909 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:38:26.480  1321  1909 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:38:26.484  1321  1909 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:38:26.499  3078  4062 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:38:26.499  3078  4062 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at hec.a(PG:42)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at hee.a(PG:102)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at czr.a(PG:65)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at kka.a(PG:108)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:38:26.499  3078  4062 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	... 15 more
03-24 15:38:26.499  3078  4062 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at fal.a(PG:38)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:38:26.499  3078  4062 E HttpOperation: 	... 17 more
03-24 15:38:26.499  3078  4062 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:38:26.499  3078  4062 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	... 15 more
03-24 15:38:26.499  3078  4062 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:38:26.499  3078  4062 E ExperimentLoader: 	... 17 more
,03-24 15:38:26.602   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 715609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:38:37.501  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:38:56.330  3492  4072 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:38:56.356  3492  4073 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:38:56.419  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 15:38:56.419  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:38:56.420  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:38:56.420  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:38:56.431  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:38:56.536   822   840 I art     : Explicit concurrent mark sweep GC freed 39498(1762KB) AllocSpace objects, 9(332KB) LOS objects, 32% free, 33MB/49MB, paused 2.415ms total 95.412ms
,03-24 15:38:56.614  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:38:56.614  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:38:56.614  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:38:56.614  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:38:56.618  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:38:56.628  3492  4073 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:38:56.629  3492  4072 E BooksSync: Soft error
03-24 15:38:56.629  3492  4072 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:38:56.629  3492  4072 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:38:56.629  3492  4072 E BooksSync: Sync error
03-24 15:38:56.629  3492  4072 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:38:56.629  3492  4072 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:38:56.630  3492  4072 I BooksSync: Finished books sync
,03-24 15:38:56.634   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 722360, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:39:37.504  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:39:39.659  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:40:37.504  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:40:39.818  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:41:37.503  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:41:39.979  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:42:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:43:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:45:10.170  3361  4140 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:45:10.184  1321  3488 D GCM     : Message class com.google.f.a.a.i
,03-24 15:45:10.298  3361  4141 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:45:10.423  1321  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:45:10.423  1321  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:45:10.423  1321  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:45:10.423  1321  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:45:10.427  1321  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:45:10.433  1321  1351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:45:10.433  1321  1351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:45:10.433  1321  1351 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:45:10.433  1321  1351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:45:10.437  1321  1351 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:45:10.449  3361  4140 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:45:10.450  3361  4140 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:45:10.455  3361  4141 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:45:23.881  3436  4146 V KeepSync: Connecting to GoogleApiClient
,03-24 15:45:23.984  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 15:45:23.984  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:45:23.984  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:45:23.985  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:45:23.993  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: Handling authorization failure
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:45:24.022  1772  4147 E ClientConnectionOperation: 	... 7 more
,03-24 15:45:24.027  3436  4146 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 15:45:24.032  3436  4146 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:45:24.049  3436  4146 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 15:45:24.050  3436  4146 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:45:24.115  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 15:45:24.115  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:45:24.115  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:45:24.116  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:45:24.124  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:45:24.209  3436  4146 E KeepSync: IOException
03-24 15:45:24.209  3436  4146 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:45:24.209  3436  4146 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:45:24.209  3436  4146 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:45:24.209  3436  4146 E KeepSync: 	... 10 more
03-24 15:45:24.209  3436  4146 W KeepSync: Sync result 2
,03-24 15:45:24.217   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1133324, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:45:37.501  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:45:40.617  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:45:58.915  2152  2228 W bt-btm  : Stopping oneshot timer
,03-24 15:46:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:46:38.549  1321  1907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:46:38.550  1321  1907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:46:38.550  1321  1907 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:46:38.550  1321  1907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:46:38.558  1321  1907 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:46:38.576  3078  4164 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:46:38.576  3078  4164 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:46:38.576  3078  4164 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	... 12 more
03-24 15:46:38.576  3078  4164 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at fal.a(PG:38)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:46:38.576  3078  4164 E HttpOperation: 	... 14 more
,03-24 15:46:38.650  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:46:38.650  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:46:38.650  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:46:38.650  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:46:38.658  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:46:38.686  3078  4164 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:46:38.686  3078  4164 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at hec.a(PG:42)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at hee.a(PG:102)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at czr.a(PG:65)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at kka.a(PG:108)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:46:38.686  3078  4164 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	... 15 more
03-24 15:46:38.686  3078  4164 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at fal.a(PG:38)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:46:38.686  3078  4164 E HttpOperation: 	... 17 more
,03-24 15:46:38.688  3078  4164 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:46:38.688  3078  4164 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	... 15 more
03-24 15:46:38.688  3078  4164 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:46:38.688  3078  4164 E ExperimentLoader: 	... 17 more
,03-24 15:46:38.834   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1207824, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:46:40.777  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:47:01.841   822   855 I UsageStatsService: User[0] Flushing usage stats to disk
,03-24 15:47:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:47:38.583  3492  4176 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:47:38.600  3492  4177 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:47:38.636  1321  1617 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:47:38.636  1321  1617 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:47:38.636  1321  1617 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:47:38.636  1321  1617 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:47:38.642  1321  1617 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:47:38.711  1321  1617 I art     : Explicit concurrent mark sweep GC freed 68217(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 27MB/43MB, paused 1.577ms total 55.303ms
,03-24 15:47:38.769  1321  1618 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:47:38.770  1321  1618 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:47:38.770  1321  1618 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:47:38.770  1321  1618 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:47:38.772  1321  1618 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:47:38.870   822  2340 I art     : Explicit concurrent mark sweep GC freed 44200(2MB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.763ms total 93.264ms
,03-24 15:47:38.911  3492  4177 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:47:38.914  3492  4176 E BooksSync: Soft error
03-24 15:47:38.914  3492  4176 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:47:38.914  3492  4176 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:47:38.914  3492  4176 E BooksSync: Sync error
03-24 15:47:38.914  3492  4176 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:47:38.914  3492  4176 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:47:38.914  3492  4176 I BooksSync: Finished books sync
,03-24 15:47:38.918   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1251471, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:48:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:48:41.098  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:49:37.501  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:49:41.257  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:50:37.503  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:50:41.419  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:51:37.503  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:52:37.502  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:52:41.738  2152  2219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
