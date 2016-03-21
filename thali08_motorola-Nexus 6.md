#### Test 625481246a7d362_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-21 15:50:46.111  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:46.199  1316  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 15:50:46.200  1316  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:46.200  1316  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:46.200  1316  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-21 15:50:46.211  1316  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 15:50:46.254  2753  2753 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-21 15:50:46.255  2753  2753 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-21 15:50:46.256  2753  2753 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
03-21 15:50:46.418  3270  3270 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 15:50:46.422  3270  3270 D AndroidRuntime: CheckJNI is OFF
03-21 15:50:46.550  3270  3270 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-21 15:50:46.556   823   838 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 15:50:46.582   823   838 V WindowManager: addAppToken: AppWindowToken{f1da468 token=Token{283cfb8b ActivityRecord{18e27d5a u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-21 15:50:46.597  1498  1796 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@384124c9
03-21 15:50:46.597  1498  1498 I HotwordDetector: Closing mic
03-21 15:50:46.601   823   859 V WindowManager: Adding window Window{28175103 u0 Starting com.test.thalitest} at 2 of 7 (after Window{36f9e5e4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-21 15:50:46.602  3270  3270 D AndroidRuntime: Shutting down VM
03-21 15:50:46.652   823  1434 I ActivityManager: Start proc 3285:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-21 15:50:46.656   359  1802 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-21 15:50:46.660   359  1802 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-21 15:50:46.667   359  1019 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-21 15:50:46.670  1498  1798 I HotwordRecognitionRnr: Stopping hotword detection.
03-21 15:50:46.670  1498  1799 I HotwordRecognitionRnr: Hotword detection finished
03-21 15:50:46.717   823  1099 I ActivityManager: Killing 2915:com.android.settings/1000 (adj 15): empty #17
03-21 15:50:46.764   823  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660773651
03-21 15:50:46.764   823  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-21 15:50:46.770   823  1099 I ActivityManager: Killing 2882:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-21 15:50:46.850   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-21 15:50:46.850   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-21 15:50:46.891   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-21 15:50:46.892   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-21 15:50:46.942  3285  3285 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 15:50:46.954  3285  3285 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2524-2526)
03-21 15:50:46.954  3285  3285 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 15:50:46.994  3285  3285 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1700ba08}
,03-21 15:50:46.995  3285  3285 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 15:50:46.996  3285  3285 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 15:50:47.019  3285  3285 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 15:50:47.020  3285  3285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:47.021  3285  3285 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 15:50:47.037  3285  3309 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-21 15:50:47.044  3285  3285 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 15:50:47.054  3285  3285 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 15:50:47.054  3285  3285 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-21 15:50:47.054  3285  3285 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 15:50:47.161   823   858 D BluetoothManagerService: Message: 20
03-21 15:50:47.161   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c1921b0:true
,03-21 15:50:47.200  3285  3285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:47.214  3285  3285 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 15:50:47.227  3285  3285 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-21 15:50:47.232  3285  3285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 15:50:47.232  3285  3285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:47.281  3285  3332 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 15:50:47.285  3285  3285 D Atlas   : Validating map...
,03-21 15:50:47.291   823  1392 V WindowManager: Adding window Window{3e5056e0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{28175103 u0 Starting com.test.thalitest})
,03-21 15:50:47.293  3285  3319 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-21 15:50:47.334  3285  3332 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 15:50:47.340  3285  3332 D OpenGLRenderer: Enabling debug mode 0
,03-21 15:50:47.418   823   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +820ms
,03-21 15:50:47.424  1219  1219 I Keyboard.Facilitator: onFinishInput()
,03-21 15:50:47.448  3285  3285 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3285
,03-21 15:50:47.472   823   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-21 15:50:47.484   823   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 15:50:47.509   279   293 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (169 us)
,03-21 15:50:47.593  3285  3285 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 15:50:47.717  3285  3334 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1573507840
,03-21 15:50:47.722  3285  3334 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 15:50:47.722  3285  3334 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 15:50:47.722  3285  3334 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 15:50:47.722  3285  3334 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 15:50:47.722  3285  3334 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 15:50:47.722  3285  3334 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab5d5b2 added. We now have 1 listener(s)
,03-21 15:50:47.722   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 15:50:47.724  3285  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-21 15:50:47.725  3285  3334 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-21 15:50:47.725  3285  3334 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 15:50:47.725  3285  3334 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-21 15:50:47.727  3285  3334 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6cf6b9 added. We now have 1 listener(s)
,03-21 15:50:47.728  3285  3334 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-21 15:50:47.730   823  1021 D WifiService: New client listening to asynchronous messages
,03-21 15:50:47.732  3285  3334 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 15:50:47.733  3285  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-21 15:50:47.733  3285  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 15:50:47.733  3285  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 15:50:47.733  3285  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 15:50:47.735  3285  3334 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:50:47.735   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 15:50:47.736  3285  3334 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-21 15:50:47.739  3285  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-21 15:50:47.739  3285  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 15:50:47.739  3285  3334 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 15:50:47.740  3285  3334 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 15:50:47.796  3285  3285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 15:50:47.797  3285  3285 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 15:50:47.877   871   871 I kickstart: STATUS: Received file 'm9kefs2'
03-21 15:50:47.877   871   871 I kickstart: STATUS: 950272 bytes transferred in 0.984879 seconds
03-21 15:50:47.877   871   871 I kickstart: STATUS: Successfully downloaded files from target 
03-21 15:50:47.877   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-21 15:50:47.881   871   871 I kickstart: STATUS: Sahara protocol completed
,03-21 15:50:48.081   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-21 15:50:48.081   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-21 15:50:48.081   823   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-21 15:50:48.083   823   823 V ActivityManager: Display changed displayId=0
,03-21 15:50:48.343   279   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-21 15:50:48.345   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-21 15:50:48.345   823  1041 D SurfaceControl: Excessive delay in setPowerMode(): 264ms
,03-21 15:50:48.348   823   861 I DreamManagerService: Entering dreamland.
03-21 15:50:48.348   823   861 I PowerManagerService: Dozing...
03-21 15:50:48.349   823   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-21 15:50:48.369   359  1028 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-21 15:50:48.369   359  1028 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-21 15:50:48.379   823  1014 E WifiStateMachine: cancelDelayedScan -> 16
,03-21 15:50:48.381   823  1014 E native  : do suspend false
,03-21 15:50:48.404  1219  1219 I Keyboard.Facilitator: onFinishInput()
,03-21 15:50:48.406   359  1020 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-21 15:50:48.406   359  1020 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-21 15:50:48.414   823  1014 E WifiStateMachine: cancelDelayedScan -> 18
,03-21 15:50:48.454   823   856 I art     : Explicit concurrent mark sweep GC freed 44685(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.463ms total 82.099ms
,03-21 15:50:48.461   823  1014 E native  : do suspend true
,03-21 15:50:48.530  3285  3344 W jxcore-log: Initializing JXcore engine
03-21 15:50:48.530  3285  3344 W jxcore-log: JXcore engine is ready
,03-21 15:50:48.550  3344  3344 W Thread-349: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12918]" dev="sockfs" ino=12918 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 15:50:48.550  3344  3344 W Thread-349: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 15:50:48.550  3344  3344 W Thread-349: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10736]" dev="sockfs" ino=10736 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-21 15:50:48.550  3344  3344 W Thread-349: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21814]" dev="sockfs" ino=21814 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-21 15:50:48.575  3285  3344 W jxcore-log: Starting JXcore engine
,03-21 15:50:48.583   823  1014 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-21 15:50:48.648  3285  3344 W jxcore-log: Platform android
03-21 15:50:48.648  3285  3344 W jxcore-log: 
03-21 15:50:48.649  3285  3344 W jxcore-log: Process ARCH arm
03-21 15:50:48.649  3285  3344 W jxcore-log: 
03-21 15:50:48.650   823  1014 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-21 15:50:48.834  3285  3344 I jxcore-log: JXcore Cordova bridge is ready!
03-21 15:50:48.834  3285  3344 I jxcore-log: 
03-21 15:50:48.834  3285  3344 W jxcore-log: JXcore engine is started
,03-21 15:50:48.846  3285  3334 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 15:50:48.851  3285  3285 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 15:50:50.945  1146  1146 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-21 15:50:51.370  1146  1146 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-21 15:50:51.412  1146  1146 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-21 15:50:51.412  1146  1146 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-21 15:50:51.433   823  1014 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-21 15:50:51.433   823  1014 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 15:50:51.434   823  1022 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-21 15:50:51.437   823  1014 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 15:50:51.441   355   799 D CommandListener: Setting iface cfg
,03-21 15:50:51.444   823  1014 E WifiStateMachine: Start Dhcp Watchdog 1
,03-21 15:50:51.446   823  1014 E WifiStateMachine:  WifiLinkLayerStats: 
03-21 15:50:51.446   823  1014 E WifiStateMachine:  my bss beacon rx: 1
03-21 15:50:51.446   823  1014 E WifiStateMachine:  RSSI mgmt: -39
03-21 15:50:51.446   823  1014 E WifiStateMachine:  BE :  rx=0 tx=2 lost=0 retries=0
03-21 15:50:51.446   823  1014 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-21 15:50:51.446   823  1014 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-21 15:50:51.446   823  1014 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-21 15:50:51.446   823  1014 E WifiStateMachine:  on_time : 0 tx_time=63 rx_time=111 scan_time=0
,03-21 15:50:51.536   823  1014 E native  : do suspend false
,03-21 15:50:51.544   823  1014 E WifiStateMachine: scanCount==0 - aborting
,03-21 15:50:51.778  3352  3352 I dhcpcd  : version 5.5.6 starting
,03-21 15:50:51.829  3352  3352 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-21 15:50:51.878  3352  3352 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-21 15:50:51.938  3352  3352 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-21 15:50:52.364   823  1014 E native  : do suspend true
,03-21 15:50:52.408   823  1022 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,03-21 15:50:52.412   823  1022 D ConnectivityService: Adding iface wlan0 to network 100
,03-21 15:50:52.422   823  1014 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-21 15:50:52.437   823  1022 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-21 15:50:52.437   823  1022 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-21 15:50:52.439   823  1022 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-21 15:50:52.441   823  1022 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-21 15:50:52.443   823  1022 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-21 15:50:52.451   823  1022 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-21 15:50:52.454   823  1022 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-21 15:50:52.455   823  3350 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-21 15:50:52.455   823  3350 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
,03-21 15:50:52.455   823  3350 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-21 15:50:52.455   823  3350 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-21 15:50:52.459   823  1022 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 15:50:52.459   823  1022 D ConnectivityService:    accepting network in place of null
,03-21 15:50:52.460   823  1022 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-21 15:50:52.462   823  1022 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-21 15:50:52.464   823  1022 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-21 15:50:52.465   823  1022 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-21 15:50:52.465   823  1022 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-21 15:50:52.465  1062  1566 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-21 15:50:52.465   823  1022 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-21 15:50:52.468   823   858 D Tethering: MasterInitialState.processMessage what=3
,03-21 15:50:52.471   823   838 V BackupManagerService: Scheduling immediate backup pass,
,03-21 15:50:52.474   823   823 V BackupManagerService: Running a backup pass,
03-21 15:50:52.474   823  1040 V BackupManagerService: clearing pending backups
,03-21 15:50:52.483  1498  1498 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
03-21 15:50:52.484  2935  2935 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:50:52.491  3285  3285 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 15:50:52.491  3285  3285 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-21 15:50:52.491  2935  2935 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-21 15:50:52.493  1274  1642 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-21 15:50:52.493  1274  1642 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-21 15:50:52.494   823   853 D TelephonyManager: getDataEnabled: retVal=false
,03-21 15:50:52.496   823  1040 V PerformBackupTask: Beginning backup of 14 targets
,03-21 15:50:52.502   823  1040 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-21 15:50:52.506   823  1040 V BackupServiceBinder: doBackup() invoked
,03-21 15:50:52.508   823  1040 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-21 15:50:52.522   823  1040 I BackupRestoreController: Getting widget state for user: 0
,03-21 15:50:52.539   823  1393 I ActivityManager: Start proc 3392:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-21 15:50:52.541   823   853 E GpsLocationProvider: No APN found to select.
,03-21 15:50:52.554   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 327us total 14.087ms
,03-21 15:50:52.569   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 311us total 14.343ms
,03-21 15:50:52.591   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 21.223ms
,03-21 15:50:52.597   823  1250 D AlarmManagerService: Setting time of day to sec=1458571853
03-21 15:50:53.211   823  1250 W AlarmManagerService: Unable to set rtc to 1458571853: Invalid argument
,03-21 15:50:53.228  1831  1846 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-21 15:50:53.230  1831  1846 V GmsBackupTransport: starting performBackup for @pm@
,03-21 15:50:53.236  1831  1846 V GmsBackupTransport: performBackup done for @pm@
,03-21 15:50:53.242   823  3412 D GpsLocationProvider: NTP server returned: 1458571853256 (Mon Mar 21 15:50:53 GMT+01:00 2016) reference: 168201 certainty: 22 system time offset: 15
,03-21 15:50:53.243  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:53.271  1316  1914 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-21 15:50:53.271  1316  1914 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:53.271  1316  1914 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:53.271  1316  1914 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:53.275  1316  1914 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:53.300  1804  3417 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-21 15:50:53.317  1316  1914 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 15:50:53.317  1316  1914 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 15:50:53.317  1316  1914 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 15:50:53.317  1316  1914 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 15:50:53.317  1316  1914 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 15:50:53.317  1316  1914 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 15:50:53.317  1316  1914 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 15:50:53.319  1831  1870 W GmsBackupTransport: Error sending final backup to server: 
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 15:50:53.319  1831  1870 W GmsBackupTransport: 	... 1 more
,03-21 15:50:53.321   823  3350 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Mar 2016 14:50:53 GMT], X-Android-Received-Millis=[1458571853321], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458571853264]}
03-21 15:50:53.322   823  3350 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-21 15:50:53.322   823  1022 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-21 15:50:53.322   823  1022 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-21 15:50:53.322   823  1022 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 15:50:53.322   823  1022 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-21 15:50:53.322   823  1022 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-21 15:50:53.323   823  1022 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-21 15:50:53.323  1062  1566 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-21 15:50:53.326   823  1040 D BackupManagerService: Now staging backup of com.google.android.talk
03-21 15:50:53.335   823  1040 D BackupManagerService: Now staging backup of com.google.android.dialer
03-21 15:50:53.338   823  1040 D BackupManagerService: Now staging backup of com.android.providers.settings
03-21 15:50:53.340   823  1040 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
03-21 15:50:53.342   823  1040 D BackupManagerService: Now staging backup of com.google.android.gm
03-21 15:50:53.343  1804  3429 W DriveInitializer: Background init thread started
03-21 15:50:53.346   823  1040 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
03-21 15:50:53.348   823  1040 D BackupManagerService: Now staging backup of com.android.nfc
03-21 15:50:53.354   823  1040 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
03-21 15:50:53.356   823  1040 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-21 15:50:53.359   823  1040 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
03-21 15:50:53.365   823  1040 D BackupManagerService: Now staging backup of com.google.android.calendar
03-21 15:50:53.368   823  1040 D BackupManagerService: Now staging backup of com.android.vending
03-21 15:50:53.370   823  1040 D BackupManagerService: Now staging backup of android
03-21 15:50:53.373   823  1040 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
03-21 15:50:53.382   823   839 I ActivityManager: Start proc 3432:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
03-21 15:50:53.387  1831  1848 I GmsBackupTransport: Next backup will happen in 43199931 millis.
03-21 15:50:53.392  1804  3430 W DriveInitializer: Awaiting to be initialized
,03-21 15:50:53.410   823  1040 I BackupManagerService: Backup pass finished.
,03-21 15:50:53.417  3432  3432 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-21 15:50:53.444  1316  1346 I art     : Explicit concurrent mark sweep GC freed 22645(1173KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.140ms total 22.094ms
,03-21 15:50:53.466  3432  3432 D SprintDMHelper: simOperator:  IMSI: null
03-21 15:50:53.466  3432  3432 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-21 15:50:53.469  1804  1804 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-21 15:50:53.471  1804  1804 D SystemUpdateService: onCreate
,03-21 15:50:53.474  1804  1804 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-21 15:50:53.498  1804  3429 W DriveInitializer: Background init thread ended
,03-21 15:50:53.499  1316  1916 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 15:50:53.499  1316  1916 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:53.499  1316  1916 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:53.499  1316  1916 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:53.503  1316  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:53.507  1804  3452 I SystemUpdateService: active receiver: enabled
,03-21 15:50:53.516  1804  3452 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-21 15:50:53.521  3084  3427 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 15:50:53.521  3084  3427 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jdm.a(PG:82)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jcs.o(PG:406)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jcn.a(PG:1379)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jcs.i(PG:143)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at blb.a(PG:3937)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at czp.a(PG:18188)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at czp.a(PG:9081)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at czq.run(PG:1686)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 15:50:53.521  3084  3427 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jdj.a(PG:4091)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jdj.a(PG:1125)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jdm.a(PG:77)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	... 12 more
03-21 15:50:53.521  3084  3427 E HttpOperation: Caused by: faj: BadAuthentication
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at fal.a(PG:38)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	at jdj.a(PG:4089)
03-21 15:50:53.521  3084  3427 E HttpOperation: 	... 14 more
,03-21 15:50:53.538  1804  3452 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
,03-21 15:50:53.538  1804  3452 I SystemUpdateService: now status is 0 (complete)
03-21 15:50:53.538  1804  3452 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-21 15:50:53.538  1804  3452 I SystemUpdateService: file has been verified
,03-21 15:50:53.539  1804  3452 I SystemUpdateService: OTA package size = 25802302
,03-21 15:50:53.542  1804  3452 I SystemUpdateService: showing system update notification
,03-21 15:50:53.549   823   823 I ValidateNoPeople: skipping global notification
,03-21 15:50:53.591  1804  1804 D SystemUpdateService: onDestroy
,03-21 15:50:53.642   823   853 I ActivityManager: Start proc 3467:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-21 15:50:53.662  1316  1346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 15:50:53.662  1316  1346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:53.662  1316  1346 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:53.663  1316  1346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-21 15:50:53.666  1316  1346 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:53.677  1804  3485 I iu.SyncManager: SYNC; picasa accounts
03-21 15:50:53.677  3084  3427 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 15:50:53.677  3084  3427 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jdm.a(PG:82)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jcs.o(PG:406)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jcn.a(PG:1379)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jcs.i(PG:143)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at hec.a(PG:42)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at hee.a(PG:102)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at czr.a(PG:65)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at kka.a(PG:108)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at czp.a(PG:19176)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at czp.a(PG:9081)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at czq.run(PG:1686)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 15:50:53.677  3084  3427 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jdj.a(PG:4091)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jdj.a(PG:1125)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jdm.a(PG:77)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	... 15 more
03-21 15:50:53.677  3084  3427 E HttpOperation: Caused by: faj: BadAuthentication
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at fal.a(PG:38)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	at jdj.a(PG:4089)
03-21 15:50:53.677  3084  3427 E HttpOperation: 	... 17 more
,03-21 15:50:53.677  3084  3427 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 15:50:53.677  3084  3427 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at hec.a(PG:42)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at hee.a(PG:102)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at czr.a(PG:65)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at kka.a(PG:108)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jdj.a(PG:1125)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	... 15 more
03-21 15:50:53.677  3084  3427 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at fal.a(PG:38)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 15:50:53.677  3084  3427 E ExperimentLoader: 	... 17 more
,03-21 15:50:53.690  1804  1804 D NetworkLogImpl: Loaded NetworkSpeedPredictor
03-21 15:50:53.695  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
03-21 15:50:53.698  1804  3485 I iu.UploadsManager: num queued entries: 0
03-21 15:50:53.698  1804  3485 I iu.UploadsManager: num updated entries: 0
03-21 15:50:53.700  1804  3485 I iu.SyncManager: NEXT; no task
,03-21 15:50:53.727  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-21 15:50:53.728  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-21 15:50:53.750   823  1392 I ActivityManager: Start proc 3494:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-21 15:50:53.780   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38479, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 15:50:53.780   823  1434 I ActivityManager: Killing 2449:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-21 15:50:53.890  3170  3491 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-21 15:50:53.891   823   853 I ActivityManager: Start proc 3515:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-21 15:50:53.901   823   839 I ActivityManager: Killing 2998:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-21 15:50:53.909  3494  3494 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-21 15:50:53.909  3494  3494 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 15:50:53.909  3494  3494 I GAv4    :   adb logcat -s GAv4
,03-21 15:50:53.972  1316  3489 D GCM     : Connected
,03-21 15:50:54.021  3494  3494 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 15:50:54.044  1316  3489 D GCM     : Message class com.google.f.a.a.p
,03-21 15:50:54.077  3494  3494 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 15:50:54.081  3494  3535 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 15:50:54.133  3467  3539 V KeepSync: Connecting to GoogleApiClient
,03-21 15:50:54.186  1804  3542 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 15:50:54.194  1804  3542 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 15:50:54.212  1316  1721 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-21 15:50:54.212  1316  1721 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:54.212  1316  1721 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:54.213  1316  1721 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:54.216  1316  1721 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: Handling authorization failure
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 15:50:54.228  1804  3542 E ClientConnectionOperation: 	... 7 more
,03-21 15:50:54.231  3467  3539 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-21 15:50:54.232  3467  3539 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-21 15:50:54.243  3467  3539 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-21 15:50:54.243  3467  3539 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 15:50:54.266  3494  3494 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 15:50:54.284  3494  3494 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9238-9243)
03-21 15:50:54.284  3494  3494 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 15:50:54.287  3494  3494 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3422d14f}
03-21 15:50:54.287  3494  3494 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 15:50:54.288  3494  3494 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 15:50:54.306  3494  3494 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 15:50:54.306  3494  3494 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 15:50:54.307  3494  3494 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 15:50:54.319  3494  3494 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 15:50:54.326  3494  3494 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 15:50:54.326  3494  3494 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 15:50:54.326  3494  3494 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 15:50:54.335  1316  1346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-21 15:50:54.335  1316  1346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:54.335  1316  1346 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:54.335  1316  1346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:54.347  1316  1721 I art     : Explicit concurrent mark sweep GC freed 14554(845KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 1.038ms total 22.900ms
,03-21 15:50:54.354  1316  1346 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:54.389  3494  3575 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-21 15:50:54.410   823   839 I art     : Explicit concurrent mark sweep GC freed 52969(2MB) AllocSpace objects, 7(152KB) LOS objects, 32% free, 33MB/49MB, paused 1.006ms total 49.303ms
,03-21 15:50:54.443  3494  3494 I NSApplication: Starting up...
,03-21 15:50:54.444  3515  3515 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 15:50:54.451  3515  3515 I BooksApp: Created application version: 3.6.8 (30608)
,03-21 15:50:54.480   823  1434 I ActivityManager: Start proc 3582:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-21 15:50:54.484  3467  3539 E KeepSync: IOException
03-21 15:50:54.484  3467  3539 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 15:50:54.484  3467  3539 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 15:50:54.484  3467  3539 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 15:50:54.484  3467  3539 E KeepSync: 	... 10 more
03-21 15:50:54.484  3467  3539 W KeepSync: Sync result 2
,03-21 15:50:54.499   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38485, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 15:50:54.499   823  1295 I ActivityManager: Killing 3018:com.android.musicfx/u0a18 (adj 15): empty #17
,03-21 15:50:54.677  3515  3600 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 15:50:54.854  3515  3611 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 15:50:54.916   823  1295 I ActivityManager: Start proc 3613:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-21 15:50:54.917   823  1295 I ActivityManager: Killing 3045:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-21 15:50:55.070  1316  1916 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 15:50:55.071  1316  1916 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 15:50:55.071  1316  1916 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 15:50:55.071  1316  1916 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:55.076  1316  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:55.148  1316  1721 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 15:50:55.148  1316  1721 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:55.148  1316  1721 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 15:50:55.148  1316  1721 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:55.152  1316  1721 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:55.162  3515  3611 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 15:50:55.163  3515  3600 E BooksSync: Soft error
03-21 15:50:55.163  3515  3600 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 15:50:55.163  3515  3600 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 15:50:55.163  3515  3600 E BooksSync: Sync error
03-21 15:50:55.163  3515  3600 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 15:50:55.163  3515  3600 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 15:50:55.163  3515  3600 I BooksSync: Finished books sync
,03-21 15:50:55.168   823  1295 I ActivityManager: Killing 2812:com.google.android.gm/u0a78 (adj 15): empty #17
,03-21 15:50:55.170   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38486, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 15:50:55.376   823  1295 I ActivityManager: Killing 2791:com.google.android.gms:car/u0a11 (adj 15): empty #18
,03-21 15:50:55.939   823  1435 I ActivityManager: Killing 1408:android.process.acore/u0a5 (adj 15): empty #17
,03-21 15:50:56.130   823  1263 I ActivityManager: Start proc 3631:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-21 15:50:56.166  3631  3631 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458571856166
03-21 15:50:56.166  3631  3631 D         : TimeServiceNative: User Time to be set is 1458571856166
03-21 15:50:56.166  3631  3631 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-21 15:50:56.166  3631  3631 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-21 15:50:56.166  3631  3631 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458571856166
03-21 15:50:56.166   374   883 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-21 15:50:56.167  3631  3631 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458571856166
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458571856166, operation = 0
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/7/70 11:2:40
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:Value read from RTC seconds = 18874960000
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:new time 1458571856166 
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon: delta 1439696896166 genoff 1439696896166 
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896166 to memory
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-21 15:50:56.167   374  3648 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 15:50:56.169   374  3648 D QC-time-services: Updating the TOD offset
03-21 15:50:56.169   374  3648 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896166 to memory
03-21 15:50:56.169   374  3648 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-21 15:50:56.169   374  3648 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 15:50:56.170   374  3648 E QC-time-services: Daemon:Update to modem bit set
03-21 15:50:56.170   374  3648 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-21 15:50:56.170   374  3648 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142607056166
03-21 15:50:56.171  3631  3631 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-21 15:50:56.239   374   883 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-21 15:50:56.245   374   877 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-21 15:50:56.286   823  1263 I ActivityManager: Start proc 3650:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-21 15:50:56.301   823  1254 I ActivityManager: Killing 3144:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-21 15:50:56.574  3650  3650 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 15:50:56.574  3650  3650 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 15:50:56.574  3650  3650 I GAv4    :   adb logcat -s GAv4
,03-21 15:50:56.592  3650  3650 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 15:50:56.606  3650  3650 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 15:50:56.620  3650  3669 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 15:50:56.707   823  1294 I ActivityManager: Killing 3124:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-21 15:50:56.965  1804  1804 V Herrevad: NQAS connected
,03-21 15:50:56.976  3170  3170 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 15:50:56.976  3170  3170 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 15:50:57.016  1804  1819 I art     : Explicit concurrent mark sweep GC freed 14577(1134KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.756ms total 47.443ms
,03-21 15:50:57.050   823  1263 I ActivityManager: Start proc 3679:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-21 15:50:57.058   823  1021 D WifiService: New client listening to asynchronous messages
,03-21 15:50:57.075  3679  3679 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 15:50:57.112  3679  3679 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1a4e63ab(com.android.providers.calendar.CalendarProvider2@1700ba08)
,03-21 15:50:57.201  1316  1916 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-21 15:50:57.201  1316  1916 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 15:50:57.201  1316  1916 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:57.201  1316  1916 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:57.206  1316  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:57.263   823  1295 I art     : Explicit concurrent mark sweep GC freed 21036(941KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.477ms total 47.389ms
,03-21 15:50:57.283  3170  3674 E Babel   : UserRecoverableAuthException.
03-21 15:50:57.283  3170  3674 E Babel   : eei: BadAuthentication
03-21 15:50:57.283  3170  3674 E Babel   : 	at eeg.a(Unknown Source)
03-21 15:50:57.283  3170  3674 E Babel   : 	at eeg.a(Unknown Source)
03-21 15:50:57.283  3170  3674 E Babel   : 	at eeg.a(Unknown Source)
03-21 15:50:57.283  3170  3674 E Babel   : 	at g.a(Unknown Source)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cae.a(SourceFile:3089)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cae.a(SourceFile:1131)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cws.a(SourceFile:4333)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cws.a(SourceFile:1419)
03-21 15:50:57.283  3170  3674 E Babel   : 	at crl.a(SourceFile:492)
03-21 15:50:57.283  3170  3674 E Babel   : 	at crl.a(SourceFile:1468)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cas.b(SourceFile:106)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cap.d(SourceFile:335)
03-21 15:50:57.283  3170  3674 E Babel   : 	at caq.run(SourceFile:81)
03-21 15:50:57.283  3170  3674 E Babel   : Error getting auth token
03-21 15:50:57.283  3170  3674 E Babel   : dvm
03-21 15:50:57.283  3170  3674 E Babel   : 	at g.a(Unknown Source)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cae.a(SourceFile:3089)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cae.a(SourceFile:1131)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cws.a(SourceFile:4333)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cws.a(SourceFile:1419)
03-21 15:50:57.283  3170  3674 E Babel   : 	at crl.a(SourceFile:492)
03-21 15:50:57.283  3170  3674 E Babel   : 	at crl.a(SourceFile:1468)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cas.b(SourceFile:106)
03-21 15:50:57.283  3170  3674 E Babel   : 	at cap.d(SourceFile:335)
03-21 15:50:57.283  3170  3674 E Babel   : 	at caq.run(SourceFile:81)
,03-21 15:50:57.293  3170  3674 E Babel   : Account registration failed 1-Redacted-21
,03-21 15:50:57.294  3170  3674 E Babel   : cyp: null -- null
03-21 15:50:57.294  3170  3674 E Babel   : 	at cae.a(SourceFile:3121)
03-21 15:50:57.294  3170  3674 E Babel   : 	at cae.a(SourceFile:1131)
03-21 15:50:57.294  3170  3674 E Babel   : 	at cws.a(SourceFile:4333)
03-21 15:50:57.294  3170  3674 E Babel   : 	at cws.a(SourceFile:1419)
03-21 15:50:57.294  3170  3674 E Babel   : 	at crl.a(SourceFile:492)
03-21 15:50:57.294  3170  3674 E Babel   : 	at crl.a(SourceFile:1468)
03-21 15:50:57.294  3170  3674 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 15:50:57.294  3170  3674 E Babel   : 	at cas.b(SourceFile:106)
03-21 15:50:57.294  3170  3674 E Babel   : 	at cap.d(SourceFile:335)
03-21 15:50:57.294  3170  3674 E Babel   : 	at caq.run(SourceFile:81)
,03-21 15:50:57.302  3170  3674 I art     : Note: end time exceeds epoch: 
,03-21 15:50:57.317  1316  1916 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-21 15:50:57.317  1316  1916 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:50:57.317  1316  1916 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:50:57.317  1316  1916 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:50:57.320  1316  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:57.330  1316  1916 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 15:50:57.343  3170  3705 E Babel   : Unexpected exception while authenticating.
,03-21 15:50:57.343  3170  3705 E Babel   : eej: User intervention required. Notification has been pushed.
03-21 15:50:57.343  3170  3705 E Babel   : 	at eeg.b(Unknown Source)
03-21 15:50:57.343  3170  3705 E Babel   : 	at eeg.b(Unknown Source)
03-21 15:50:57.343  3170  3705 E Babel   : 	at g.a(Unknown Source)
03-21 15:50:57.343  3170  3705 E Babel   : 	at cae.b(SourceFile:1146)
03-21 15:50:57.343  3170  3705 E Babel   : 	at dcg.run(SourceFile:5617)
03-21 15:50:57.343  3170  3705 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 15:50:57.343  3170  3705 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 15:50:57.343  3170  3705 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-21 15:50:58.190  3679  3679 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-21 15:50:58.191  3679  3679 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 15:50:58.286  3679  3709 E SQLiteLog: (284) automatic index on view_events(_id)
,03-21 15:50:59.459  3515  3578 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 15:50:59.541  3285  3344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:50:59.541  3285  3344 I jxcore-log: 
03-21 15:50:59.544  3285  3344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:50:59.544  3285  3344 I jxcore-log: 
,03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:50:59.552  3285  3344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:50:59.557  3285  3344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:50:59.559  3285  3344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:50:59.559  3285  3344 I jxcore-log: ,
03-21 15:50:59.561  3285  3344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-21 15:50:59.561  3285  3344 I jxcore-log: 
,03-21 15:51:00.089  3285  3344 I jxcore-log: Unit Test app is loaded
03-21 15:51:00.089  3285  3344 I jxcore-log: 
,03-21 15:51:00.095  3285  3344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:00.095  3285  3344 I jxcore-log: 
,03-21 15:51:00.103  3285  3344 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
03-21 15:51:00.105  3285  3344 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 15:51:00.105  3285  3344 I jxcore-log: 
03-21 15:51:00.107  3285  3344 I jxcore-log: My device name is: motorola-Nexus 6
03-21 15:51:00.107  3285  3344 I jxcore-log: 
,03-21 15:51:00.120  3285  3285 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 15:51:00.554  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:00.637  3392  3715 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 15:51:00.659  1316  3716 I VacuumService: Vacuum at: now=1458571860659 tag=VacuumService
,03-21 15:51:00.703  1316  1346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-21 15:51:00.703  1316  1346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:00.703  1316  1346 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:00.703  1316  1346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:00.707  1316  1346 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:00.757  3392  3715 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 15:51:00.758  3392  3715 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 15:51:00.901  1316  1914 I art     : Explicit concurrent mark sweep GC freed 24985(1512KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.655ms total 66.011ms
,03-21 15:51:00.934  1316  3717 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 15:51:00.950  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:01.398  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:01.571  1316  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 15:51:01.571  1316  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:01.571  1316  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:01.571  1316  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:01.574  1316  3717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 15:51:01.633  1316  3717 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 15:51:01.633  1316  3717 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 15:51:01.633  1316  3717 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 15:51:01.845  1316  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 15:51:01.846  1316  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:01.846  1316  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 15:51:01.846  1316  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:01.859  1316  3717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 15:51:01.940  1316  3717 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 15:51:01.940  1316  3717 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 15:51:01.940  1316  3717 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 15:51:02.084  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:02.184  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:02.293  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:02.443  1316  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 15:51:02.443  1316  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:02.443  1316  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 15:51:02.443  1316  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:02.449  1316  3717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:02.487  1316  3717 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 15:51:02.487  1316  3717 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 15:51:02.487  1316  3717 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 15:51:02.654  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:02.869  1316  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 15:51:02.869  1316  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:02.869  1316  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:02.869  1316  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:02.874  1316  3717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:02.914  1316  3717 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 15:51:02.914  1316  3717 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 15:51:02.914  1316  3717 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 15:51:03.059  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:03.172  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:03.305  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:03.314   823  1295 I ActivityManager: Killing 2753:com.android.vending/u0a19 (adj 15): empty #17
,03-21 15:51:03.564  1316  3717 W Uploader:  no longer exists, so no auth token.
,03-21 15:51:03.673  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:03.793  1316  3717 W Uploader: No account for auth token provided
,03-21 15:51:03.954  1316  3717 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 15:51:03.955  1316  3717 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:03.955  1316  3717 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:03.955  1316  3717 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:03.964  1316  3717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:04.018  1316  3717 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 15:51:04.018  1316  3717 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 15:51:04.018  1316  3717 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 15:51:04.171  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 15:51:04.171  3285  3344 I jxcore-log: 
,03-21 15:51:04.570  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 15:51:04.570  3285  3344 I jxcore-log: 
,03-21 15:51:04.586  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,03-21 15:51:04.586  3285  3344 I jxcore-log: 
,03-21 15:51:04.593  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 15:51:04.593  3285  3344 I jxcore-log: 
,03-21 15:51:04.601   823  1294 I ActivityManager: Start proc 3720:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-21 15:51:04.633  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 15:51:04.633  3285  3344 I jxcore-log: 
,03-21 15:51:04.650  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 15:51:04.650  3285  3344 I jxcore-log: 
,03-21 15:51:04.655  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 15:51:04.655  3285  3344 I jxcore-log: 
,03-21 15:51:04.764  3720  3720 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 15:51:04.850  3720  3720 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-21 15:51:04.934   823  1294 I ActivityManager: Start proc 3756:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-21 15:51:04.950   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 336us total 15.941ms
,03-21 15:51:04.961  3720  3720 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 15:51:04.965   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 336us total 14.036ms
,03-21 15:51:04.972  3720  3720 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 15:51:04.982   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 340us total 13.980ms
,03-21 15:51:04.993  3756  3756 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 15:51:04.993  3756  3756 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 15:51:05.004   823  1434 I ActivityManager: Killing 2935:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-21 15:51:05.008  3720  3735 D Finsky  : [379] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-21 15:51:05.019  3756  3756 I MultiDex: VM with version 2.1.0 has multidex support
03-21 15:51:05.019  3756  3756 I MultiDex: install
03-21 15:51:05.019  3756  3756 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 15:51:05.239  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:05.249  3720  3720 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-21 15:51:05.250  3720  3720 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-21 15:51:05.262  3720  3720 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-21 15:51:05.263  3756  3756 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 15:51:05.273  1316  1721 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 15:51:05.273  1316  1721 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:05.273  1316  1721 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:05.273  1316  1721 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:05.277  1316  1721 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:05.289  3720  3720 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-21 15:51:05.293  3720  3735 D Finsky  : [379] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-21 15:51:05.314  3756  3756 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 15:51:05.318  1316  2112 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 15:51:05.323  1316  1316 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 15:51:05.327  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 15:51:05.380   823  1099 I ActivityManager: Start proc 3785:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-21 15:51:05.400  1804  3802 D LocationInitializer: Restart initialization of location
,03-21 15:51:05.410  3785  3785 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 15:51:05.410  3785  3785 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 15:51:05.449  3785  3785 I MultiDex: VM with version 2.1.0 has multidex support
03-21 15:51:05.449  3785  3785 I MultiDex: install
03-21 15:51:05.449  3785  3785 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 15:51:05.465  3785  3785 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 15:51:05.497  3785  3785 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 15:51:05.501  1316  2534 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 15:51:05.503  1316  1316 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 15:51:05.508  3785  3785 D WearableService: callingUid 10011, callindPid: 3785
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: Install did not work
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-21 15:51:05.509  3785  3806 W NativeLibraryUtils: 	... 4 more
03-21 15:51:05.509  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 15:51:05.528  1804  3807 D LocationInitializer: Restart initialization of location
,03-21 15:51:05.533  1831  2106 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 15:51:05.536  1831  2106 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 15:51:05.650  3720  3720 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-21 15:51:05.864  3720  3720 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-21 15:51:05.893  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:05.971   823   838 I art     : Explicit concurrent mark sweep GC freed 23995(1138KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.818ms total 63.354ms
,03-21 15:51:06.019  1316  1916 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 15:51:06.019  1316  1916 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:06.019  1316  1916 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:06.019  1316  1916 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:06.022  1316  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.042  3720  3720 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 15:51:06.056  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.104  1316  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 15:51:06.104  1316  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:06.104  1316  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:06.104  1316  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:06.112  1316  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.159  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.210  1316  1721 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-21 15:51:06.210  1316  1721 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-21 15:51:06.211  1316  1721 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 15:51:06.211  1316  1721 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-21 15:51:06.219  1316  1721 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.279  3720  3720 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 15:51:06.590  1316  1316 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.626  1316  1914 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-21 15:51:06.626  1316  1914 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:06.626  1316  1914 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:06.627  1316  1914 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:06.631  1316  1914 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.650  3720  3720 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 15:51:06.656  3720  3720 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-21 15:51:06.667  3720  3720 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-21 15:51:06.673  3720  3720 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,03-21 15:51:06.689  1316  1914 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-21 15:51:06.690  1316  1914 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 15:51:06.690  1316  1914 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 15:51:06.690  1316  1914 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 15:51:06.694  1316  1914 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:51:06.696  1831  1847 D DeviceConnectionService: client connected with version: 7571000
,03-21 15:51:06.717  3720  3720 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-21 15:51:06.717  3720  3720 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-21 15:51:06.718  3720  3720 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-21 15:51:06.780  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 15:51:06.780  3285  3344 I jxcore-log: 
,03-21 15:51:06.796  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,03-21 15:51:06.796  3285  3344 I jxcore-log: 
,03-21 15:51:06.804  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
,03-21 15:51:06.804  3285  3344 I jxcore-log: 
,03-21 15:51:06.921  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,03-21 15:51:06.921  3285  3344 I jxcore-log: 
,03-21 15:51:06.981  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
,03-21 15:51:06.981  3285  3344 I jxcore-log: 
,03-21 15:51:07.118  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
,03-21 15:51:07.118  3285  3344 I jxcore-log: 
,03-21 15:51:07.124  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
,03-21 15:51:07.124  3285  3344 I jxcore-log: 
,03-21 15:51:07.131  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,03-21 15:51:07.131  3285  3344 I jxcore-log: 
,03-21 15:51:07.153  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,03-21 15:51:07.153  3285  3344 I jxcore-log: 
,03-21 15:51:07.175  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,03-21 15:51:07.175  3285  3344 I jxcore-log: 
,03-21 15:51:07.278  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
,03-21 15:51:07.278  3285  3344 I jxcore-log: 
,03-21 15:51:07.285  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,03-21 15:51:07.285  3285  3344 I jxcore-log: 
,03-21 15:51:07.311  3285  3344 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,03-21 15:51:07.311  3285  3344 I jxcore-log: 
,03-21 15:51:07.803  3285  3344 I jxcore-log: --= Surplus to requirements =--
03-21 15:51:07.803  3285  3344 I jxcore-log: 
03-21 15:51:07.803  3285  3344 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 15:51:07.803  3285  3344 I jxcore-log: 
,03-21 15:51:08.077  3827  3827 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 15:51:08.080  3827  3827 D AndroidRuntime: CheckJNI is OFF
,03-21 15:51:08.196  3827  3827 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 15:51:08.209   823   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-21 15:51:08.209   823   854 I ActivityManager: Killing 3285:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-21 15:51:08.295   823   864 W PackageSettings: Skipping PackageSetting{2016204 com.example.hello/10273} due to missing metadata
,03-21 15:51:08.353   823  1294 I WindowState: WIN DEATH: Window{3e5056e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-21 15:51:08.371   823  1021 D WifiService: Client connection lost with reason: 4
,03-21 15:51:08.422   823   854 W ActivityManager: Force removing ActivityRecord{18e27d5a u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-21 15:51:08.439   823   823 V ActivityManager: Display changed displayId=0
,03-21 15:51:08.458   823   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-21 15:51:08.473   823  1435 W ActivityManager: Spurious death for ProcessRecord{21eaeaf0 3285:com.test.thalitest/u0a95}, curProc for 3285: null
03-21 15:51:08.473   823  1042 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-21 15:51:08.495  1219  1219 I Keyboard.Facilitator: resetDictionaries() : en_US
03-21 15:51:08.496   823   998 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 15:51:08.501  2981  2981 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-21 15:51:08.521  1219  3842 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 15:51:08.522  1219  3842 I Decoder : createOrResetDecoder
,03-21 15:51:08.537   823  1392 I ActivityManager: Start proc 3843:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-21 15:51:08.541  1498  1498 I art     : Explicit concurrent mark sweep GC freed 1856(145KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 1.298ms total 71.724ms
,03-21 15:51:08.550  1062  1062 I art     : Explicit concurrent mark sweep GC freed 48257(2022KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 1.967ms total 63.218ms
,03-21 15:51:08.579  1316  3814 I art     : Explicit concurrent mark sweep GC freed 56095(3MB) AllocSpace objects, 11(1064KB) LOS objects, 36% free, 27MB/43MB, paused 1.278ms total 33.134ms
03-21 15:51:08.579  1316  1316 I ConfigService: onCreate
,03-21 15:51:08.596   823   839 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3285 uid 10095
,03-21 15:51:08.599  1219  1219 I Keyboard.Facilitator: onFinishInput()
,03-21 15:51:08.605   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 15:51:08.605   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 15:51:08.616  1219  3842 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 15:51:08.631  1498  1498 W LocationOracleImpl: Best location was null
,03-21 15:51:08.641  1219  3842 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-21 15:51:08.642  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 15:51:08.642  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-21 15:51:08.643   823   864 I art     : Explicit concurrent mark sweep GC freed 23400(1913KB) AllocSpace objects, 9(709KB) LOS objects, 32% free, 33MB/49MB, paused 1.930ms total 159.857ms
,03-21 15:51:08.645  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 15:51:08.645  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-21 15:51:08.645  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 15:51:08.646  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-21 15:51:08.647  1219  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-21 15:51:08.647  1219  3842 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-21 15:51:08.647  1219  3842 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 15:51:08.647  1219  3842 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-21 15:51:08.647  1219  3842 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 15:51:08.647  1219  3842 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-21 15:51:08.657  1297  1297 I art     : Explicit concurrent mark sweep GC freed 4956(362KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 990us total 31.697ms
,03-21 15:51:08.664  1498  3868 I HotwordRecognitionRnr: Starting hotword detection.
03-21 15:51:08.665  1498  3869 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@3fc74955
,03-21 15:51:08.666   359  3872 I AudioFlinger: AudioFlinger's thread 0xb40b5000 ready to run
,03-21 15:51:08.680   359  1019 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-21 15:51:08.681  1498  3869 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@3fc74955
,03-21 15:51:08.689  3827  3827 I art     : System.exit called, status: 0
03-21 15:51:08.689  3827  3827 I AndroidRuntime: VM exiting with result code 0.
,03-21 15:51:08.691   359  3872 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-21 15:51:08.691   359  3872 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-21 15:51:08.691   359  3872 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-21 15:51:08.691   359  3872 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-21 15:51:08.694  3843  3876 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 15:51:08.697   359  3872 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-21 15:51:08.749  3843  3862 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-21 15:51:08.753   823   864 I ActivityManager: Start proc 3878:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-21 15:51:08.771  1498  1498 I HotwordWorker: onReady
,03-21 15:51:08.782   823  1392 I ActivityManager: Start proc 3896:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-21 15:51:08.807   823  1263 I ActivityManager: Killing 3432:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-21 15:51:08.815  1297  1297 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-21 15:51:08.815  1297  1297 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-21 15:51:08.827  3843  3862 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
03-21 15:51:08.828  3843  3862 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-21 15:51:08.828  3843  3862 E AndroidRuntime: Process: android.process.acore, PID: 3843
03-21 15:51:08.828  3843  3862 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-21 15:51:08.828  3843  3862 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 15:51:08.867   823  3917 E DropBoxManagerService: Can't write: system_app_crash
03-21 15:51:08.867   823  3917 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:08.867   823  3917 E DropBoxManagerService: 	... 5 more
,03-21 15:51:08.893   823  1294 I ActivityManager: Start proc 3920:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-21 15:51:08.910   823  3937 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-21 15:51:08.910   823   854 D Atlas   : Validating map...
,03-21 15:51:08.915   823  1389 I ActivityManager: Killing 3494:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-21 15:51:09.057   823  3937 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 15:51:09.067   823  3937 D OpenGLRenderer: Enabling debug mode 0
,03-21 15:51:09.071   823  1099 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@b2749a0}
,03-21 15:51:09.077  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-21 15:51:09.081   823  1014 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-21 15:51:09.088  1316  1316 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-21 15:51:09.088  1316  1316 D AndroidRuntime: Shutting down VM
,03-21 15:51:09.089  1316  1316 E AndroidRuntime: FATAL EXCEPTION: main
03-21 15:51:09.089  1316  1316 E AndroidRuntime: Process: com.google.process.gapps, PID: 1316
03-21 15:51:09.089  1316  1316 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-21 15:51:09.089  1316  1316 E AndroidRuntime: 	... 9 more
,03-21 15:51:09.093   823  3942 E DropBoxManagerService: Can't write: system_app_crash
03-21 15:51:09.093   823  3942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:09.093   823  3942 E DropBoxManagerService: 	... 5 more
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-21 15:51:09.115  3920  3940 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-21 15:51:09.115  3920  3940 E AndroidRuntime: Process: com.android.keychain, PID: 3920
03-21 15:51:09.115  3920  3940 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-21 15:51:09.115  3920  3940 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: Can't write: system_app_crash
03-21 15:51:09.118   823  3944 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:09.118   823  3944 E DropBoxManagerService: 	... 5 more
,03-21 15:51:09.171   823  1245 E QMI_FW  : xport_send: Sendto failed for port 4608
,03-21 15:51:09.171   823  1245 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-21 15:51:09.171   823  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660773651
03-21 15:51:09.171   823  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-21 15:51:09.211   279   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
03-21 15:51:09.228  1498  1498 I HotwordDetector: Closing mic
03-21 15:51:09.228  1498  1796 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3fc74955

```
