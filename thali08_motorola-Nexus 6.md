#### Test 625481240f1d9b8_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
03-21 16:45:57.574   820   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,--------- beginning of main
03-21 16:45:57.589   820   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-21 16:45:57.630   278   296 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (308 us)
03-21 16:45:57.903  3237  3237 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 16:45:57.907  3237  3237 D AndroidRuntime: CheckJNI is OFF
03-21 16:45:58.031  3237  3237 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 16:45:58.040   820  1403 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 16:45:58.058   820  1403 V WindowManager: addAppToken: AppWindowToken{71182c1 token=Token{4e067a8 ActivityRecord{8fc3cb u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-21 16:45:58.066   820   859 V WindowManager: Adding window Window{3c5e83c0 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2e6cf0b6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-21 16:45:58.068  3237  3237 D AndroidRuntime: Shutting down VM
03-21 16:45:58.074  1551  1551 I HotwordDetector: Closing mic
03-21 16:45:58.075  1551  1782 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@4a4c1b1
03-21 16:45:58.130   357  1808 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-21 16:45:58.134   357  1808 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-21 16:45:58.154   357  1040 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-21 16:45:58.155  1551  1796 I HotwordRecognitionRnr: Stopping hotword detection.
03-21 16:45:58.156  1551  1804 I HotwordRecognitionRnr: Hotword detection finished
03-21 16:45:58.165   820   839 I ActivityManager: Start proc 3254:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-21 16:45:58.204   820   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-21 16:45:58.205   820   820 V ActivityManager: Display changed displayId=0
03-21 16:45:58.210   278   278 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-21 16:45:58.210   278   278 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-21 16:45:58.220   820   839 I ActivityManager: Killing 2865:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,03-21 16:45:58.325   820   839 I ActivityManager: Killing 2693:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-21 16:45:58.370   870   870 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-21 16:45:58.370   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-21 16:45:58.411   870   870 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-21 16:45:58.411   870   870 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-21 16:45:58.484   278   318 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-21 16:45:58.486   278   278 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-21 16:45:58.486   820  1055 D SurfaceControl: Excessive delay in setPowerMode(): 282ms
,03-21 16:45:58.541   820   861 I DreamManagerService: Entering dreamland.
,03-21 16:45:58.543   820   861 I PowerManagerService: Dozing...
,03-21 16:45:58.546   820   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-21 16:45:58.556   357  1390 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-21 16:45:58.556   357  1390 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-21 16:45:58.560   820  1021 E WifiStateMachine: cancelDelayedScan -> 16
,03-21 16:45:58.564   820  1021 E native  : do suspend false
,03-21 16:45:58.585   820  1243 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660187923
03-21 16:45:58.585   820  1243 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-21 16:45:58.599  3254  3254 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 16:45:58.609  3254  3254 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3795-3796)
03-21 16:45:58.609  3254  3254 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 16:45:58.624  3254  3254 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34be2f8e}
,03-21 16:45:58.625  3254  3254 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 16:45:58.625  3254  3254 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 16:45:58.636  3254  3254 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 16:45:58.637  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 16:45:58.638  3254  3254 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 16:45:58.647  3254  3280 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-21 16:45:58.657  3254  3254 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 16:45:58.663  3254  3254 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 16:45:58.663  3254  3254 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 16:45:58.663  3254  3254 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 16:45:58.674   820  1021 E WifiStateMachine: cancelDelayedScan -> 18
,03-21 16:45:58.717   820   858 D BluetoothManagerService: Message: 20
03-21 16:45:58.717   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7781d8f:true
,03-21 16:45:58.724   820  1021 E native  : do suspend true
,03-21 16:45:58.726   357  1390 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-21 16:45:58.726   357  1390 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-21 16:45:58.747  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:45:58.754  3254  3254 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 16:45:58.766  3254  3254 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-21 16:45:58.766   820  1021 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-21 16:45:58.770  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 16:45:58.770  3254  3254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:45:58.825  3254  3304 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 16:45:58.829  3254  3254 D Atlas   : Validating map...
,03-21 16:45:58.840   820  1273 V WindowManager: Adding window Window{3f61887f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3c5e83c0 u0 Starting com.test.thalitest})
,03-21 16:45:58.842  3254  3289 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-21 16:45:58.951   820  1705 I art     : Explicit concurrent mark sweep GC freed 43116(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.832ms total 87.499ms
,03-21 16:45:58.979  3254  3304 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 16:45:58.985  3254  3304 D OpenGLRenderer: Enabling debug mode 0
,03-21 16:45:59.059   820   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +965ms
,03-21 16:45:59.064  1226  1226 I Keyboard.Facilitator: onFinishInput()
,03-21 16:45:59.072  3254  3254 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3254
,03-21 16:45:59.084  3254  3254 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 16:45:59.210  3254  3254 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-21 16:45:59.340  3254  3305 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580524544
,03-21 16:45:59.343  3254  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 16:45:59.343  3254  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 16:45:59.343  3254  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 16:45:59.343  3254  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 16:45:59.343  3254  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 16:45:59.343  3254  3305 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14691bab added. We now have 1 listener(s)
,03-21 16:45:59.344   820  1273 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 16:45:59.346  3254  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-21 16:45:59.347  3254  3305 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-21 16:45:59.347  3254  3305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 16:45:59.348  3254  3305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
,03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 16:45:59.350  3254  3305 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8254bc6 added. We now have 1 listener(s)
03-21 16:45:59.350  3254  3305 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 16:45:59.354   820  1022 D WifiService: New client listening to asynchronous messages
,03-21 16:45:59.356  3254  3305 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 16:45:59.362  3254  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-21 16:45:59.362  3254  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-21 16:45:59.363  3254  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 16:45:59.363  3254  3305 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 16:45:59.372  3254  3305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:45:59.373   820  1272 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 16:45:59.374  3254  3305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-21 16:45:59.378  3254  3305 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-21 16:45:59.378  3254  3305 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 16:45:59.378  3254  3305 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 16:45:59.378  3254  3305 I io.jxcore.node.LifeCycleMonitor: start: OK
03-21 16:45:59.379  3254  3254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 16:45:59.402   870   870 I kickstart: STATUS: Received file 'm9kefs1'
03-21 16:45:59.402   870   870 I kickstart: STATUS: 950272 bytes transferred in 0.990551 seconds
03-21 16:45:59.402   870   870 I kickstart: STATUS: Successfully downloaded files from target 
03-21 16:45:59.402   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
03-21 16:45:59.402  3254  3254 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 16:45:59.407   870   870 I kickstart: STATUS: Sahara protocol completed
,03-21 16:46:00.025   820  1021 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-21 16:46:00.058  3254  3312 W jxcore-log: Initializing JXcore engine
,03-21 16:46:00.058  3254  3312 W jxcore-log: JXcore engine is ready
,03-21 16:46:00.090  3312  3312 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10547]" dev="sockfs" ino=10547 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 16:46:00.090  3312  3312 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 16:46:00.090  3312  3312 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11596]" dev="sockfs" ino=11596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-21 16:46:00.090  3312  3312 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20112]" dev="sockfs" ino=20112 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-21 16:46:00.104  3254  3312 W jxcore-log: Starting JXcore engine
,03-21 16:46:00.182  3254  3312 W jxcore-log: Platform android
03-21 16:46:00.182  3254  3312 W jxcore-log: 
,03-21 16:46:00.182  3254  3312 W jxcore-log: Process ARCH arm
03-21 16:46:00.182  3254  3312 W jxcore-log: 
,03-21 16:46:00.401  3254  3312 I jxcore-log: JXcore Cordova bridge is ready!
03-21 16:46:00.401  3254  3312 I jxcore-log: 
,03-21 16:46:00.401  3254  3312 W jxcore-log: JXcore engine is started
,03-21 16:46:00.407  3254  3305 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 16:46:00.410  3254  3254 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 16:46:00.502  1471  1471 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:00.529  1471  1496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
03-21 16:46:00.529  1471  1496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:00.529  1471  1496 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:00.529  1471  1496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:00.533  1471  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:00.554  2734  2734 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-21 16:46:00.554  2734  2734 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-21 16:46:00.555  2734  2734 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-21 16:46:01.118  1198  1198 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
,03-21 16:46:01.538  1198  1198 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-21 16:46:01.578  1198  1198 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-21 16:46:01.578  1198  1198 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-21 16:46:01.610   820  1021 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-21 16:46:01.610   820  1021 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 16:46:01.612   820  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-21 16:46:01.622   820  1021 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 16:46:01.627   353   811 D CommandListener: Setting iface cfg
,03-21 16:46:01.634   820  1021 E WifiStateMachine: Start Dhcp Watchdog 1
,03-21 16:46:01.644   820  1021 E WifiStateMachine:  WifiLinkLayerStats: 
03-21 16:46:01.644   820  1021 E WifiStateMachine:  my bss beacon rx: 1
03-21 16:46:01.644   820  1021 E WifiStateMachine:  RSSI mgmt: -40
03-21 16:46:01.644   820  1021 E WifiStateMachine:  BE :  rx=0 tx=4 lost=0 retries=0
03-21 16:46:01.644   820  1021 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-21 16:46:01.644   820  1021 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-21 16:46:01.644   820  1021 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-21 16:46:01.644   820  1021 E WifiStateMachine:  on_time : 0 tx_time=60 rx_time=73 scan_time=0
,03-21 16:46:01.736   820  1021 E native  : do suspend false
,03-21 16:46:01.745   820  1021 E WifiStateMachine: scanCount==0 - aborting
,03-21 16:46:01.987  3315  3315 I dhcpcd  : version 5.5.6 starting
,03-21 16:46:02.090  3315  3315 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-21 16:46:02.213  3315  3315 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-21 16:46:02.362  3315  3315 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-21 16:46:02.771   820  1021 E native  : do suspend true
,03-21 16:46:02.809   820  1023 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,03-21 16:46:02.813   820  1023 D ConnectivityService: Adding iface wlan0 to network 100
,03-21 16:46:02.818   820  1021 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-21 16:46:02.842   820  1023 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-21 16:46:02.843   820  1023 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-21 16:46:02.844   820  1023 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-21 16:46:02.845   820  1023 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-21 16:46:02.846   820  1023 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-21 16:46:02.852   820  1023 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100],
,03-21 16:46:02.856   820  1023 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-21 16:46:02.856   820  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-21 16:46:02.856   820  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
,03-21 16:46:02.857   820  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler },
03-21 16:46:02.857   820  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-21 16:46:02.861   820  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 16:46:02.861   820  1023 D ConnectivityService:    accepting network in place of null
,03-21 16:46:02.863   820  1023 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-21 16:46:02.863   820  1023 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-21 16:46:02.866   820  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100],
03-21 16:46:02.867  1076  1497 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-21 16:46:02.867   820  1023 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-21 16:46:02.867   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-21 16:46:02.868   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,03-21 16:46:02.870   820   858 D Tethering: MasterInitialState.processMessage what=3
,03-21 16:46:02.874   820  1105 V BackupManagerService: Scheduling immediate backup pass
,03-21 16:46:02.877   820   820 V BackupManagerService: Running a backup pass
,03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:02.881  3254  3254 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 16:46:02.881  3254  3254 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-21 16:46:02.882  2918  2918 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-21 16:46:02.887  2918  2918 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-21 16:46:02.889   820  1054 V BackupManagerService: clearing pending backups
,03-21 16:46:02.895   820  1054 V PerformBackupTask: Beginning backup of 14 targets
,03-21 16:46:02.901   820  1054 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-21 16:46:02.908   820  1054 V BackupServiceBinder: doBackup() invoked
,03-21 16:46:02.911   820  1054 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-21 16:46:02.926   820  1054 I BackupRestoreController: Getting widget state for user: 0
,03-21 16:46:02.927   820  1272 I ActivityManager: Start proc 3355:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-21 16:46:02.944  1274  1299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-21 16:46:02.944  1274  1299 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-21 16:46:02.944   820   853 D TelephonyManager: getDataEnabled: retVal=false
,03-21 16:46:02.954   820   853 E GpsLocationProvider: No APN found to select.
,03-21 16:46:02.971  1857  1874 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-21 16:46:02.973  1857  1874 V GmsBackupTransport: starting performBackup for @pm@
,03-21 16:46:02.977  1857  1874 V GmsBackupTransport: performBackup done for @pm@
,03-21 16:46:02.992  1471  1471 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:02.994   820  1247 D AlarmManagerService: Setting time of day to sec=1458575162
03-21 16:46:02.973   820  1247 W AlarmManagerService: Unable to set rtc to 1458575162: Invalid argument
,03-21 16:46:02.991  1471  1495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-21 16:46:02.991  1471  1495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:02.991  1471  1495 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:02.991  1471  1495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:03.001  1471  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:03.041  1471  1495 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 16:46:03.041  1471  1495 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 16:46:03.041  1471  1495 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 16:46:03.041  1471  1495 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 16:46:03.041  1471  1495 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 16:46:03.041  1471  1495 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 16:46:03.041  1471  1495 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 16:46:03.045  1857  1872 W GmsBackupTransport: Error sending final backup to server: 
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 16:46:03.045  1857  1872 W GmsBackupTransport: 	... 1 more
,03-21 16:46:03.047   820  1054 D BackupManagerService: Now staging backup of com.google.android.talk
,03-21 16:46:03.080  1810  3375 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-21 16:46:03.080   820  1054 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-21 16:46:03.083   820  1054 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-21 16:46:03.089   820  1054 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-21 16:46:03.092   820  1054 D BackupManagerService: Now staging backup of com.google.android.gm
03-21 16:46:03.093  1810  3391 W DriveInitializer: Background init thread started
,03-21 16:46:03.100   820  1054 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-21 16:46:03.105   820  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Mar 2016 15:46:03 GMT], X-Android-Received-Millis=[1458575163105], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458575163047]}
03-21 16:46:03.105   820  3313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-21 16:46:03.106   820  1023 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-21 16:46:03.106   820  1023 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-21 16:46:03.106   820  1023 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 16:46:03.106   820  1023 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-21 16:46:03.106   820  1023 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-21 16:46:03.106  1076  1497 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-21 16:46:03.106   820  1023 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-21 16:46:03.115   820  1054 D BackupManagerService: Now staging backup of com.android.nfc
,03-21 16:46:03.118  1810  3392 W DriveInitializer: Awaiting to be initialized
,03-21 16:46:03.119   820  1054 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-21 16:46:03.125   820  1054 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
03-21 16:46:03.126   820  1054 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-21 16:46:03.132   820  1054 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-21 16:46:03.137   820  1054 D BackupManagerService: Now staging backup of com.android.vending
,03-21 16:46:03.139   820  1054 D BackupManagerService: Now staging backup of android
,03-21 16:46:03.141   820  1054 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-21 16:46:03.144  1857  1874 I GmsBackupTransport: Next backup will happen in 43199899 millis.
,03-21 16:46:03.146   820  1054 I BackupManagerService: Backup pass finished.
,03-21 16:46:03.150   820  1273 I ActivityManager: Start proc 3395:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-21 16:46:03.160   369   369 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 9.913ms
,03-21 16:46:03.175  3395  3395 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-21 16:46:03.178   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 16.623ms
,03-21 16:46:03.187  3395  3395 D SprintDMHelper: simOperator:  IMSI: null
03-21 16:46:03.187  3395  3395 D SprintDMReceiver: Not Sprint UICC, don't do anything.
03-21 16:46:03.188   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 9.380ms
,03-21 16:46:03.190  1810  1810 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-21 16:46:03.195  1810  1810 D SystemUpdateService: onCreate
,03-21 16:46:03.198  1810  1810 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-21 16:46:03.297  1810  3415 I SystemUpdateService: active receiver: enabled
,03-21 16:46:03.324  1810  3415 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-21 16:46:03.325  1810  3415 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
,03-21 16:46:03.325  1810  3415 I SystemUpdateService: now status is 0 (complete)
03-21 16:46:03.325  1810  3415 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-21 16:46:03.326  1810  3415 I SystemUpdateService: file has been verified
03-21 16:46:03.326  1810  3415 I SystemUpdateService: OTA package size = 25802302
,03-21 16:46:03.329  1810  3415 I SystemUpdateService: showing system update notification
,03-21 16:46:03.336   820   820 I ValidateNoPeople: skipping global notification
,03-21 16:46:03.348  1471  1471 I art     : Explicit concurrent mark sweep GC freed 19490(1006KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 804us total 25.317ms
,03-21 16:46:03.360  1471  1496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 16:46:03.360  1471  1496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:03.360  1471  1496 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:03.360  1471  1496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:03.362  1471  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:03.374  3074  3390 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 16:46:03.374  3074  3390 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jdm.a(PG:82)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jcs.o(PG:406)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jcn.a(PG:1379)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jcs.i(PG:143)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at blb.a(PG:3937)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at czp.a(PG:18188)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at czp.a(PG:9081)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at czq.run(PG:1686)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:03.374  3074  3390 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jdj.a(PG:4091)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jdj.a(PG:1125)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jdm.a(PG:77)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	... 12 more
03-21 16:46:03.374  3074  3390 E HttpOperation: Caused by: faj: BadAuthentication
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at fal.a(PG:38)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	at jdj.a(PG:4089)
03-21 16:46:03.374  3074  3390 E HttpOperation: 	... 14 more
,03-21 16:46:03.392  1810  3391 W DriveInitializer: Background init thread ended
03-21 16:46:03.404   820   853 I ActivityManager: Start proc 3429:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-21 16:46:03.426  1471  2570 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 16:46:03.426  1471  2570 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:03.427  1471  2570 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:03.427  1471  2570 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:03.430  1471  2570 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:03.440  3074  3390 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 16:46:03.440  3074  3390 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jdm.a(PG:82)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jcs.o(PG:406)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jcn.a(PG:1379)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jcs.i(PG:143)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at hec.a(PG:42)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at hee.a(PG:102)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at czr.a(PG:65)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at kka.a(PG:108)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at czp.a(PG:19176)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at czp.a(PG:9081)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at czq.run(PG:1686)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:03.440  3074  3390 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jdj.a(PG:4091)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jdj.a(PG:1125)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jdm.a(PG:77)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	... 15 more
03-21 16:46:03.440  3074  3390 E HttpOperation: Caused by: faj: BadAuthentication
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at fal.a(PG:38)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	at jdj.a(PG:4089)
03-21 16:46:03.440  3074  3390 E HttpOperation: 	... 17 more
03-21 16:46:03.440  3074  3390 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 16:46:03.440  3074  3390 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at hec.a(PG:42)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at hee.a(PG:102)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at czr.a(PG:65)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at kka.a(PG:108)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	... 15 more
03-21 16:46:03.440  3074  3390 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at fal.a(PG:38)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 16:46:03.440  3074  3390 E ExperimentLoader: 	... 17 more
03-21 16:46:03.470  1810  1810 D SystemUpdateService: onDestroy
,03-21 16:46:03.502  1810  3449 I iu.SyncManager: SYNC; picasa accounts
,03-21 16:46:03.516  1810  1810 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-21 16:46:03.518  1810  1810 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-21 16:46:03.523  1810  3449 I iu.UploadsManager: num queued entries: 0
,03-21 16:46:03.525  1810  3449 I iu.UploadsManager: num updated entries: 0
03-21 16:46:03.525  1810  3449 I iu.SyncManager: NEXT; no task
,03-21 16:46:03.539   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 39348, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-21 16:46:03.540   820  1705 I ActivityManager: Killing 2896:com.android.settings/1000 (adj 15): empty #17
,03-21 16:46:03.785  1810  1810 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-21 16:46:03.787  1810  1810 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-21 16:46:03.835   820   853 I ActivityManager: Start proc 3454:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-21 16:46:03.883   820  1272 I ActivityManager: Start proc 3474:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-21 16:46:03.892  1471  3452 D GCM     : Connected
,03-21 16:46:03.955  1471  3452 D GCM     : Message class com.google.f.a.a.p
,03-21 16:46:04.003  3474  3474 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-21 16:46:04.003  3474  3474 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 16:46:04.003  3474  3474 I GAv4    :   adb logcat -s GAv4
,03-21 16:46:04.004  3429  3494 V KeepSync: Connecting to GoogleApiClient
,03-21 16:46:04.019  3474  3474 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 16:46:04.041  3474  3474 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 16:46:04.057  3474  3503 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 16:46:04.062  1810  3501 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 16:46:04.067  1810  3501 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 16:46:04.093  1471  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-21 16:46:04.093  1471  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:04.093  1471  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:04.093  1471  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:04.096  1471  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: Handling authorization failure
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 16:46:04.122  1810  3501 E ClientConnectionOperation: 	... 7 more
,03-21 16:46:04.127  3142  3471 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-21 16:46:04.131  3429  3494 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-21 16:46:04.132  3429  3494 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-21 16:46:04.135  3429  3494 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-21 16:46:04.136  3429  3494 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 16:46:04.169   820  1413 I art     : Explicit concurrent mark sweep GC freed 50569(2MB) AllocSpace objects, 7(153KB) LOS objects, 32% free, 33MB/49MB, paused 1.532ms total 56.174ms
,03-21 16:46:04.218  3474  3474 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 16:46:04.242  3474  3474 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9450-9451)
,03-21 16:46:04.242  3474  3474 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 16:46:04.253  3474  3474 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c2a7d4d}
,03-21 16:46:04.254  3474  3474 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 16:46:04.254  3474  3474 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 16:46:04.269  3474  3474 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 16:46:04.269  3474  3474 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 16:46:04.270  3474  3474 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 16:46:04.281  1471  1496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-21 16:46:04.282  1471  1496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:04.282  1471  1496 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:04.282  1471  1496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:04.287  1471  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:04.295  3474  3474 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 16:46:04.300  3474  3474 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 16:46:04.300  3474  3474 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 16:46:04.300  3474  3474 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 16:46:04.301  3454  3454 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 16:46:04.307  3454  3454 I BooksApp: Created application version: 3.6.8 (30608)
,03-21 16:46:04.316  3429  3494 E KeepSync: IOException
03-21 16:46:04.316  3429  3494 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 16:46:04.316  3429  3494 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 16:46:04.316  3429  3494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 16:46:04.316  3429  3494 E KeepSync: 	... 10 more
03-21 16:46:04.316  3429  3494 W KeepSync: Sync result 2
,03-21 16:46:04.322   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39353, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 16:46:04.324   820  1272 I ActivityManager: Killing 2452:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-21 16:46:04.354  1471  1730 I art     : Explicit concurrent mark sweep GC freed 14419(835KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 888us total 19.420ms
,03-21 16:46:04.359  3474  3538 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-21 16:46:04.566  3474  3474 I NSApplication: Starting up...
,03-21 16:46:04.613   820  1371 I ActivityManager: Start proc 3546:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
03-21 16:46:04.614   820  1371 I ActivityManager: Killing 2980:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-21 16:46:04.785  3454  3544 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 16:46:04.971   820  1243 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1078]: failed status = eLOC_CLIENT_SUCCESS, inject_pos_ind.status = eQMI_LOC_GENERAL_FAILURE_V02, part num = 58, ind.partNum = 0
,03-21 16:46:04.983  3454  3572 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 16:46:05.053  1471  1495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 16:46:05.053  1471  1495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:05.053  1471  1495 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:05.053  1471  1495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:05.056  1471  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:05.099  1471  1496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-21 16:46:05.099  1471  1496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:05.099  1471  1496 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:05.099  1471  1496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-21 16:46:05.103  1471  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:05.111  3454  3572 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 16:46:05.112  3454  3544 E BooksSync: Soft error
03-21 16:46:05.112  3454  3544 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 16:46:05.112  3454  3544 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 16:46:05.112  3454  3544 E BooksSync: Sync error
03-21 16:46:05.112  3454  3544 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 16:46:05.112  3454  3544 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-21 16:46:05.112  3454  3544 I BooksSync: Finished books sync
,03-21 16:46:05.115   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39354, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 16:46:05.118   820  3564 I ActivityManager: Killing 3029:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-21 16:46:05.171   820  3564 I ActivityManager: Killing 3000:com.android.musicfx/u0a18 (adj 15): empty #18
,03-21 16:46:05.379   820  3564 E libprocessgroup: failed to kill 1 processes for processgroup 3000
,03-21 16:46:05.385   820  1105 I ActivityManager: Killing 1419:android.process.acore/u0a5 (adj 15): empty #17
,03-21 16:46:05.666   820  3564 I ActivityManager: Start proc 3577:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-21 16:46:06.502   820   839 I ActivityManager: Killing 2795:com.google.android.gm/u0a78 (adj 15): empty #17
,03-21 16:46:06.818   820  3565 I ActivityManager: Start proc 3595:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-21 16:46:06.849  3595  3595 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458575166849
03-21 16:46:06.849  3595  3595 D         : TimeServiceNative: User Time to be set is 1458575166849
03-21 16:46:06.849  3595  3595 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-21 16:46:06.849  3595  3595 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-21 16:46:06.849  3595  3595 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458575166849
03-21 16:46:06.849  3595  3595 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-21 16:46:06.849   372   886 D QC-time-services: Daemon: Connection accepted:time_genoff
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458575166849
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458575166849, operation = 0
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/7/70 11:57:51
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:Value read from RTC seconds = 18878271000
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:new time 1458575166849 
,03-21 16:46:06.850   372  3612 D QC-time-services: Daemon: delta 1439696895849 genoff 1439696895849 
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696895849 to memory
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-21 16:46:06.850   372  3612 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 16:46:06.852   372  3612 D QC-time-services: Updating the TOD offset
03-21 16:46:06.852   372  3612 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696895849 to memory
03-21 16:46:06.852   372  3612 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-21 16:46:06.852   372  3612 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 16:46:06.854  3595  3595 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-21 16:46:06.854   372  3612 E QC-time-services: Daemon:Update to modem bit set
,03-21 16:46:06.854   372  3612 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-21 16:46:06.855   372  3612 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142610366849
,03-21 16:46:06.910   820  1705 I ActivityManager: Start proc 3614:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-21 16:46:06.916   820  3565 I ActivityManager: Killing 1888:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-21 16:46:06.924   372   886 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-21 16:46:06.929   372   881 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-21 16:46:07.175  3614  3614 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 16:46:07.175  3614  3614 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 16:46:07.175  3614  3614 I GAv4    :   adb logcat -s GAv4
,03-21 16:46:07.193  3614  3614 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 16:46:07.206  3614  3614 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 16:46:07.226  3614  3633 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 16:46:07.256   820  1705 I ActivityManager: Killing 3114:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-21 16:46:07.483   820  1022 D WifiService: New client listening to asynchronous messages
,03-21 16:46:07.486  1810  1810 V Herrevad: NQAS connected
,03-21 16:46:07.504  3142  3142 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 16:46:07.504  3142  3142 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 16:46:07.546   820  3564 I ActivityManager: Start proc 3641:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-21 16:46:07.602  3641  3641 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 16:46:07.646   820  1272 I art     : Explicit concurrent mark sweep GC freed 20861(939KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.715ms total 61.195ms
,03-21 16:46:07.652  3641  3641 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2c5c389(com.android.providers.calendar.CalendarProvider2@34be2f8e)
,03-21 16:46:07.715  1471  1495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-21 16:46:07.715  1471  1495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:07.716  1471  1495 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:07.716  1471  1495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:07.718  1471  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:07.725  3142  3658 E Babel   : UserRecoverableAuthException.
03-21 16:46:07.725  3142  3658 E Babel   : eei: BadAuthentication
03-21 16:46:07.725  3142  3658 E Babel   : 	at eeg.a(Unknown Source)
03-21 16:46:07.725  3142  3658 E Babel   : 	at eeg.a(Unknown Source)
03-21 16:46:07.725  3142  3658 E Babel   : 	at eeg.a(Unknown Source)
03-21 16:46:07.725  3142  3658 E Babel   : 	at g.a(Unknown Source)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cae.a(SourceFile:3089)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cae.a(SourceFile:1131)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cws.a(SourceFile:4333)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cws.a(SourceFile:1419)
03-21 16:46:07.725  3142  3658 E Babel   : 	at crl.a(SourceFile:492)
03-21 16:46:07.725  3142  3658 E Babel   : 	at crl.a(SourceFile:1468)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cas.b(SourceFile:106)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cap.d(SourceFile:335)
03-21 16:46:07.725  3142  3658 E Babel   : 	at caq.run(SourceFile:81)
03-21 16:46:07.725  3142  3658 E Babel   : Error getting auth token
03-21 16:46:07.725  3142  3658 E Babel   : dvm
03-21 16:46:07.725  3142  3658 E Babel   : 	at g.a(Unknown Source)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cae.a(SourceFile:3089)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cae.a(SourceFile:1131)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cws.a(SourceFile:4333)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cws.a(SourceFile:1419)
03-21 16:46:07.725  3142  3658 E Babel   : 	at crl.a(SourceFile:492)
03-21 16:46:07.725  3142  3658 E Babel   : 	at crl.a(SourceFile:1468)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cas.b(SourceFile:106)
03-21 16:46:07.725  3142  3658 E Babel   : 	at cap.d(SourceFile:335)
03-21 16:46:07.725  3142  3658 E Babel   : 	at caq.run(SourceFile:81)
,03-21 16:46:07.727  3142  3658 E Babel   : Account registration failed 1-Redacted-21
,03-21 16:46:07.728  3142  3658 E Babel   : cyp: null -- null
03-21 16:46:07.728  3142  3658 E Babel   : 	at cae.a(SourceFile:3121)
03-21 16:46:07.728  3142  3658 E Babel   : 	at cae.a(SourceFile:1131)
03-21 16:46:07.728  3142  3658 E Babel   : 	at cws.a(SourceFile:4333)
03-21 16:46:07.728  3142  3658 E Babel   : 	at cws.a(SourceFile:1419)
03-21 16:46:07.728  3142  3658 E Babel   : 	at crl.a(SourceFile:492)
03-21 16:46:07.728  3142  3658 E Babel   : 	at crl.a(SourceFile:1468)
03-21 16:46:07.728  3142  3658 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 16:46:07.728  3142  3658 E Babel   : 	at cas.b(SourceFile:106)
03-21 16:46:07.728  3142  3658 E Babel   : 	at cap.d(SourceFile:335)
03-21 16:46:07.728  3142  3658 E Babel   : 	at caq.run(SourceFile:81)
,03-21 16:46:07.736  3142  3658 I art     : Note: end time exceeds epoch: 
,03-21 16:46:07.746  1471  1496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-21 16:46:07.746  1471  1496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 16:46:07.746  1471  1496 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:07.746  1471  1496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:07.749  1471  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:07.758  1471  1496 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 16:46:07.770  3142  3667 E Babel   : Unexpected exception while authenticating.
,03-21 16:46:07.771  3142  3667 E Babel   : eej: User intervention required. Notification has been pushed.
03-21 16:46:07.771  3142  3667 E Babel   : ,	at eeg.b(Unknown Source)
03-21 16:46:07.771  3142  3667 E Babel   : 	at eeg.b(Unknown Source)
03-21 16:46:07.771  3142  3667 E Babel   : 	at g.a(Unknown Source)
03-21 16:46:07.771  3142  3667 E Babel   : 	at cae.b(SourceFile:1146)
03-21 16:46:07.771  3142  3667 E Babel   : 	at dcg.run(SourceFile:5617)
03-21 16:46:07.771  3142  3667 E Babel   : ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:07.771  3142  3667 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:07.771  3142  3667 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-21 16:46:08.021  3641  3668 E SQLiteLog: (284) automatic index on view_events(_id)
,03-21 16:46:08.717  3641  3641 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-21 16:46:08.718  3641  3641 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 16:46:09.311  3454  3528 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 16:46:10.367  3254  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:10.367  3254  3312 I jxcore-log: 
,03-21 16:46:10.370  3254  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:10.370  3254  3312 I jxcore-log: 
,03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:10.377  3254  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:10.383  3254  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:10.388  3254  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:10.388  3254  3312 I jxcore-log: 
,03-21 16:46:10.395  3254  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:10.395  3254  3312 I jxcore-log: 
,03-21 16:46:10.956  3254  3312 I jxcore-log: Unit Test app is loaded
03-21 16:46:10.956  3254  3312 I jxcore-log: 
,03-21 16:46:10.961  3254  3312 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-21 16:46:10.961  3254  3312 I jxcore-log: 
,03-21 16:46:10.971  3254  3312 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-21 16:46:10.974  3254  3312 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 16:46:10.974  3254  3312 I jxcore-log: 
,03-21 16:46:10.976  3254  3312 I jxcore-log: My device name is: motorola-Nexus 6
03-21 16:46:10.976  3254  3312 I jxcore-log: 
,03-21 16:46:10.982  3254  3254 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 16:46:11.715  1471  1471 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:11.809  1471  1471 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 16:46:11.883  3355  3678 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 16:46:11.908  1471  2570 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-21 16:46:11.909  1471  2570 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:11.909  1471  2570 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:11.909  1471  2570 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:11.911  1471  2570 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:11.921  3355  3678 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 16:46:11.922  3355  3678 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 16:46:11.981  1471  3684 I VacuumService: Vacuum at: now=1458575171981 tag=VacuumService
,03-21 16:46:12.462  1471  3685 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 16:46:12.511  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:12.518  1471  3679 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,03-21 16:46:12.990  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:13.238  1471  3685 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 16:46:13.239  1471  3685 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 16:46:13.239  1471  3685 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:13.239  1471  3685 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:13.249  1471  3685 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:13.334  1471  3685 I art     : Explicit concurrent mark sweep GC freed 44531(2MB) AllocSpace objects, 7(417KB) LOS objects, 37% free, 26MB/42MB, paused 1.543ms total 61.967ms
,03-21 16:46:13.408  1471  3685 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 16:46:13.408  1471  3685 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 16:46:13.408  1471  3685 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 16:46:13.627  1471  3685 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 16:46:13.627  1471  3685 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:13.627  1471  3685 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:13.627  1471  3685 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:13.633  1471  3685 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 16:46:13.683  1471  3685 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 16:46:13.683  1471  3685 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 16:46:13.683  1471  3685 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 16:46:14.007  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:14.204  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:14.416  2734  2749 D Finsky  : [249] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-21 16:46:14.437  1471  1471 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:14.476  1471  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 16:46:14.476  1471  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:14.476  1471  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 16:46:14.476  1471  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:14.479  1471  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:14.482  1471  3685 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 16:46:14.482  1471  3685 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:14.482  1471  3685 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:14.483  1471  3685 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:14.486  1471  3685 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:14.496  2734  2749 D Finsky  : [249] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-21 16:46:14.511  1471  3685 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 16:46:14.511  1471  3685 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 16:46:14.511  1471  3685 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 16:46:14.908  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:15.044  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:15.046  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 16:46:15.046  3254  3312 I jxcore-log: 
,03-21 16:46:15.189  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:15.353  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:15.398  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
03-21 16:46:15.398  3254  3312 I jxcore-log: 
,03-21 16:46:15.411  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
03-21 16:46:15.411  3254  3312 I jxcore-log: 
,03-21 16:46:15.416  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 16:46:15.416  3254  3312 I jxcore-log: 
,03-21 16:46:15.454  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 16:46:15.454  3254  3312 I jxcore-log: 
,03-21 16:46:15.470  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 16:46:15.470  3254  3312 I jxcore-log: 
,03-21 16:46:15.475  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 16:46:15.475  3254  3312 I jxcore-log: 
,03-21 16:46:15.527  1471  3685 W Uploader:  no longer exists, so no auth token.
,03-21 16:46:15.781  1471  3685 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 16:46:15.781  1471  3685 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:15.781  1471  3685 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:15.781  1471  3685 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:15.787  1471  3685 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:15.817  1471  3685 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 16:46:15.817  1471  3685 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 16:46:15.817  1471  3685 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 16:46:15.984  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:16.125  1471  3685 W Uploader: No account for auth token provided
,03-21 16:46:16.325  1471  3685 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 16:46:16.325  1471  3685 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:16.326  1471  3685 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:16.326  1471  3685 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:16.335  1471  3685 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-21 16:46:16.404  1471  3685 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 16:46:16.404  1471  3685 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 16:46:16.404  1471  3685 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 16:46:17.534  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 16:46:17.534  3254  3312 I jxcore-log: 
,03-21 16:46:17.552  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-21 16:46:17.552  3254  3312 I jxcore-log: 
,03-21 16:46:17.561  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-21 16:46:17.561  3254  3312 I jxcore-log: 
,03-21 16:46:17.683  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-21 16:46:17.683  3254  3312 I jxcore-log: 
,03-21 16:46:17.737  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-21 16:46:17.737  3254  3312 I jxcore-log: 
,03-21 16:46:17.882   820  1705 I ActivityManager: Killing 2918:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-21 16:46:17.906  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
03-21 16:46:17.906  3254  3312 I jxcore-log: 
,03-21 16:46:17.912  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-21 16:46:17.912  3254  3312 I jxcore-log: 
,03-21 16:46:17.919  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-21 16:46:17.919  3254  3312 I jxcore-log: 
,03-21 16:46:17.944  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-21 16:46:17.944  3254  3312 I jxcore-log: 
,03-21 16:46:17.964  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-21 16:46:17.964  3254  3312 I jxcore-log: 
,03-21 16:46:18.086  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-21 16:46:18.086  3254  3312 I jxcore-log: 
,03-21 16:46:18.101  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-21 16:46:18.101  3254  3312 I jxcore-log: 
,03-21 16:46:18.136  3254  3312 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,03-21 16:46:18.136  3254  3312 I jxcore-log: 
,03-21 16:46:20.829  1471  1471 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:20.892  1471  1495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-21 16:46:20.893  1471  1495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 16:46:20.893  1471  1495 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 16:46:20.894  1471  1495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 16:46:20.905  1471  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:46:20.947  2734  2734 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-21 16:46:20.948  2734  2734 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-21 16:46:20.949  2734  2734 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-21 16:46:21.925  2156  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 16:46:22.942   820  3374 D GpsLocationProvider: NTP server returned: 1458575162973 (Mon Mar 21 16:46:02 GMT+01:00 2016) reference: 168181 certainty: 20 system time offset: -19969,
,03-21 16:46:26.855  3254  3312 I jxcore-log: --= Surplus to requirements =--
03-21 16:46:26.855  3254  3312 I jxcore-log: 
03-21 16:46:26.855  3254  3312 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 16:46:26.855  3254  3312 I jxcore-log: 
,03-21 16:46:27.129  3703  3703 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 16:46:27.132  3703  3703 D AndroidRuntime: CheckJNI is OFF
,03-21 16:46:27.248  3703  3703 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 16:46:27.262   820   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-21 16:46:27.262   820   854 I ActivityManager: Killing 3254:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-21 16:46:27.333   820   864 W PackageSettings: Skipping PackageSetting{bc5106a com.example.hello/10273} due to missing metadata
,03-21 16:46:27.456   820  1413 I WindowState: WIN DEATH: Window{3f61887f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-21 16:46:27.457   820  1022 D WifiService: Client connection lost with reason: 4
,03-21 16:46:27.475   820   854 E libprocessgroup: failed to kill 1 processes for processgroup 3254,
03-21 16:46:27.475   820   854 W ActivityManager: Force removing ActivityRecord{8fc3cb u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-21 16:46:27.500   820   820 V ActivityManager: Display changed displayId=0
,03-21 16:46:27.511   820   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-21 16:46:27.524   820  1371 W ActivityManager: Spurious death for ProcessRecord{20d2222b 3254:com.test.thalitest/u0a95}, curProc for 3254: null
03-21 16:46:27.528  1226  1226 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-21 16:46:27.531  2963  2963 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-21 16:46:27.538  1226  3717 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 16:46:27.554   820  1011 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 16:46:27.556  1226  3717 I Decoder : createOrResetDecoder
,03-21 16:46:27.569   820   854 I ActivityManager: Start proc 3718:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
03-21 16:46:27.570   820  1056 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-21 16:46:27.575  1076  1076 I art     : Explicit concurrent mark sweep GC freed 16285(727KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 60MB/76MB, paused 1.169ms total 43.821ms
,03-21 16:46:27.619  1471  1471 I ConfigService: onCreate
,03-21 16:46:27.631   820   820 I art     : Explicit concurrent mark sweep GC freed 36164(2MB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.632ms total 106.679ms
,03-21 16:46:27.632   820  1273 I art     : WaitForGcToComplete blocked for 78.652ms for cause Explicit
,03-21 16:46:27.634  1551  1551 I art     : Explicit concurrent mark sweep GC freed 2478(175KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 849us total 119.130ms
,03-21 16:46:27.636  1226  3717 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 16:46:27.674  3718  3740 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 16:46:27.679  1226  3717 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-21 16:46:27.681  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 16:46:27.681  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-21 16:46:27.698   820  1273 I art     : Explicit concurrent mark sweep GC freed 4378(227KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 8.873ms total 62.905ms
,03-21 16:46:27.699   820   864 I art     : WaitForGcToComplete blocked for 162.869ms for cause Explicit
,03-21 16:46:27.702   820   838 I ActivityManager: Start proc 3742:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-21 16:46:27.705  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 16:46:27.705  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-21 16:46:27.705  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 16:46:27.705  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-21 16:46:27.706  1226  3717 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-21 16:46:27.706  1226  3717 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-21 16:46:27.706  1226  3717 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 16:46:27.706  1226  3717 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-21 16:46:27.706  1226  3717 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 16:46:27.706  1226  3717 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-21 16:46:27.718   820  1272 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3254 uid 10095
,03-21 16:46:27.720  1226  1226 I Keyboard.Facilitator: onFinishInput()
,03-21 16:46:27.749  3718  3738 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-21 16:46:27.757   820   820 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 16:46:27.757   820   820 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 16:46:27.764   820  1272 I ActivityManager: Start proc 3761:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-21 16:46:27.775  1300  1300 I art     : Explicit concurrent mark sweep GC freed 4975(363KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 798us total 22.259ms
,03-21 16:46:27.776  1551  1551 W LocationOracleImpl: Best location was null
,03-21 16:46:27.782   369   369 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 398us total 13.522ms
,03-21 16:46:27.794  1551  3780 I HotwordRecognitionRnr: Starting hotword detection.
,03-21 16:46:27.796  1551  3781 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@2ef580aa
,03-21 16:46:27.797   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 9.993ms
,03-21 16:46:27.803   357  3783 I AudioFlinger: AudioFlinger's thread 0xb2003000 ready to run
,03-21 16:46:27.806   357  1040 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-21 16:46:27.807  1551  3781 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@2ef580aa
,03-21 16:46:27.810   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 216us total 12.698ms
,03-21 16:46:27.816   357  3783 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-21 16:46:27.816   357  3783 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-21 16:46:27.816   357  3783 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-21 16:46:27.816   357  3783 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-21 16:46:27.824   357  3783 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-21 16:46:27.837  1300  1300 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-21 16:46:27.837  1300  1300 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-21 16:46:27.846  3761  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-21 16:46:27.858  1471  1471 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-21 16:46:27.858  1471  1471 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-21 16:46:27.873   820  1371 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@19c842f0}
,03-21 16:46:27.877  1810  1849 I art     : Explicit concurrent mark sweep GC freed 17737(1171KB) AllocSpace objects, 14(224KB) LOS objects, 35% free, 29MB/45MB, paused 2.630ms total 44.576ms
,03-21 16:46:27.878   820  1021 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.00 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-21 16:46:27.883   820  1272 I ActivityManager: Killing 3395:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-21 16:46:27.898  1551  1551 I HotwordWorker: onReady
,03-21 16:46:27.905   820   864 I art     : Explicit concurrent mark sweep GC freed 7322(326KB) AllocSpace objects, 6(661KB) LOS objects, 32% free, 33MB/49MB, paused 2.039ms total 201.932ms
,03-21 16:46:27.936   820  1243 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660187923
03-21 16:46:27.936   820  1243 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-21 16:46:27.958  3703  3703 I art     : System.exit called, status: 0
03-21 16:46:27.958  3703  3703 I AndroidRuntime: VM exiting with result code 0.
,03-21 16:46:27.995  1810  3796 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-21 16:46:27.997  1810  3796 D AccountUtils: Clearing selected account for com.test.thalitest
,03-21 16:46:28.022   820   864 I ActivityManager: Start proc 3798:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-21 16:46:28.024  1810  1810 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-21 16:46:28.024  1810  1810 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-21 16:46:28.030  1810  1810 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-21 16:46:28.030  1810  1810 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-21 16:46:28.032  1810  3796 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-21 16:46:28.061   820   839 I ActivityManager: Start proc 3820:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,03-21 16:46:28.065  1810  3811 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-21 16:46:28.065  1810  3811 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-21 16:46:28.065  1810  3811 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-21 16:46:28.065  1810  3811 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-21 16:46:28.066  1551  3829 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-21 16:46:28.072  1300  1300 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2355ac1 new=com.google.android.velvet.VelvetApplication@2355ac1
,03-21 16:46:28.084  1810  3811 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-21 16:46:28.084  1810  3811 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-21 16:46:28.085  1810  3811 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-21 16:46:28.092  1810  3811 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-21 16:46:28.092  1810  3811 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-21 16:46:28.095  1810  3811 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,03-21 16:46:28.096  1810  3811 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-21 16:46:28.096  1810  3811 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-21 16:46:28.096  1810  3811 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-21 16:46:28.112   820  1105 I ActivityManager: Start proc 3841:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-21 16:46:28.117   820  1105 I ActivityManager: Killing 3474:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-21 16:46:28.124  3820  3820 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 16:46:28.125  3820  3820 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 16:46:28.144  3820  3820 I MultiDex: VM with version 2.1.0 has multidex support
03-21 16:46:28.145  3820  3820 I MultiDex: install
03-21 16:46:28.145  3820  3820 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 16:46:28.235  1551  3829 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: Exception thrown from onTableChanged
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.content.ContentResolver.update(ContentResolver.java:1333)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.os.Looper.loop(Looper.java:135)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
03-21 16:46:28.238  1551  3829 E AppDataSearchHel,per: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
03-21 16:46:28.238  1551  3829 E AppDataSearchHelper: 	... 16 more
03-21 16:46:28.238  1551  3829 W AppDataSearchHelper: Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
03-21 16:46:28.239  1551  3829 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
03-21 16:46:28.243  1810  1810 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
03-21 16:46:28.244  1810  2529 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
03-21 16:46:28.246  1810  1810 I ConfigFetchService: service connected
03-21 16:46:28.252  1810  3859 I PeopleContactsSync: CP2 sync disabled
03-21 16:46:28.255  1810  3830 W BaseAppContext: Using Auth Proxy for data requests.
03-21 16:46:28.257  3820  3820 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-21 16:46:28.261  1810  1833 I Icing   : doRemovePackageData com.test.thalitest
03-21 16:46:28.263  1810  3830 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 16:46:28.271  1810  3830 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:28.271  1810  3830 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: Runtime exception while performing operation
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.datab,ase.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:28.271  1810  3830 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:46:28.272  1810  3830 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: Can't write: system_app_wtf
03-21 16:46:28.278   820  3861 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 16:46:28.278   820  3861 E DropBoxManagerService: 	... 5 more
03-21 16:46:28.288  3820  3820 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: Failed to open lock file
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 16:46:28.297  3820  3863 W NativeLibraryUtils: 	... 3 more
03-21 16:46:28.301   820   839 I ActivityManager: Killing 3546:com.android.chrome/u0a40 (adj 15): empty #17

```
