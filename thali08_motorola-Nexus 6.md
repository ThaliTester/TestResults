#### Test 64613803adf70b9_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-31 16:29:05.738  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:05.840  1131  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 16:29:05.840  1131  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:05.840  1131  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:05.841  1131  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 16:29:05.853  1131  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 16:29:05.891  2749  2749 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 16:29:05.892  2749  2749 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 16:29:05.892  2749  2749 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
03-31 16:29:06.018  3252  3252 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 16:29:06.021  3252  3252 D AndroidRuntime: CheckJNI is OFF
03-31 16:29:06.137  3252  3252 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 16:29:06.142   823  1151 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 16:29:06.166   823  1151 V WindowManager: addAppToken: AppWindowToken{18110928 token=Token{2c7ffb4b ActivityRecord{19d6a41a u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-31 16:29:06.175   823   859 V WindowManager: Adding window Window{1a4288c3 u0 Starting com.test.thalitest} at 2 of 7 (after Window{383a7786 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 16:29:06.182  3252  3252 D AndroidRuntime: Shutting down VM
03-31 16:29:06.193  1541  1541 I HotwordDetector: Closing mic
03-31 16:29:06.194  1541  1769 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1aa7cf24
03-31 16:29:06.273   358  1775 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 16:29:06.274   358  1775 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 16:29:06.280   823  1338 I ActivityManager: Start proc 3266:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-31 16:29:06.281   358  1028 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 16:29:06.286  1541  1772 I HotwordRecognitionRnr: Hotword detection finished
03-31 16:29:06.287  1541  1771 I HotwordRecognitionRnr: Stopping hotword detection.
03-31 16:29:06.344   823  1019 I ActivityManager: Killing 2913:com.android.settings/1000 (adj 15): empty #17
,03-31 16:29:06.413   823  1287 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660384531
,03-31 16:29:06.413   823  1287 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 16:29:06.451   823  1019 I ActivityManager: Killing 2879:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-31 16:29:06.498   875   875 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 16:29:06.499   875   875 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 16:29:06.540   875   875 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
03-31 16:29:06.540   875   875 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-31 16:29:06.634  3266  3266 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000),
,03-31 16:29:06.649  3266  3266 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2493-2497)
,03-31 16:29:06.649  3266  3266 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 16:29:06.683  3266  3266 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3127214f},
,03-31 16:29:06.684  3266  3266 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-31 16:29:06.684  3266  3266 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,03-31 16:29:06.697  3266  3266 I BrowserStartupController: Initializing chromium process, singleProcess=true,
03-31 16:29:06.698  3266  3266 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 16:29:06.699  3266  3266 E SysUtils: ApplicationContext is null in ApplicationStatus,
,03-31 16:29:06.706  3266  3291 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-31 16:29:06.718  3266  3266 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 16:29:06.724  3266  3266 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 16:29:06.724  3266  3266 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 16:29:06.724  3266  3266 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 16:29:06.778   823   858 D BluetoothManagerService: Message: 20
03-31 16:29:06.778   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a50e70:true
,03-31 16:29:06.814  3266  3266 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 16:29:06.827  3266  3266 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 16:29:06.844  3266  3266 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-31 16:29:06.856  3266  3266 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
03-31 16:29:06.856  3266  3266 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-31 16:29:06.909  3266  3313 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 16:29:06.912  3266  3266 D Atlas   : Validating map...
,03-31 16:29:06.918   823  1676 V WindowManager: Adding window Window{110f3a0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1a4288c3 u0 Starting com.test.thalitest})
,03-31 16:29:06.920  3266  3300 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-31 16:29:06.981  3266  3313 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 16:29:07.000  3266  3313 D OpenGLRenderer: Enabling debug mode 0
,03-31 16:29:07.097   823   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +890ms
,03-31 16:29:07.103  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-31 16:29:07.213  3266  3266 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3266
,03-31 16:29:07.324   823   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-31 16:29:07.343   823   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,03-31 16:29:07.352  3266  3266 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 16:29:07.381   258   283 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
,03-31 16:29:07.488  3266  3315 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576322048
,03-31 16:29:07.493  3266  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 16:29:07.493  3266  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 16:29:07.493  3266  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 16:29:07.493  3266  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 16:29:07.493  3266  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-31 16:29:07.493  3266  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d6d4128 added. We now have 1 listener(s)
03-31 16:29:07.493   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:29:07.496  3266  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-31 16:29:07.498  3266  3315 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:29:07.499  3266  3315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 16:29:07.499  3266  3315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 16:29:07.501  3266  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a49927 added. We now have 1 listener(s)
03-31 16:29:07.501  3266  3315 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 16:29:07.506   823  1035 D WifiService: New client listening to asynchronous messages
,03-31 16:29:07.509  3266  3315 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-31 16:29:07.512  3266  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 16:29:07.512  3266  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 16:29:07.513  3266  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-31 16:29:07.513  3266  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 16:29:07.516  3266  3315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-31 16:29:07.517   823  1341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:29:07.518  3266  3315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-31 16:29:07.523  3266  3315 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-31 16:29:07.523  3266  3315 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 16:29:07.523  3266  3315 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 16:29:07.525  3266  3266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 16:29:07.526  3266  3315 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 16:29:07.539   875   875 I kickstart: STATUS: Received file 'm9kefs2'
03-31 16:29:07.539   875   875 I kickstart: STATUS: 950272 bytes transferred in 0.998802 seconds
03-31 16:29:07.539   875   875 I kickstart: STATUS: Successfully downloaded files from target 
03-31 16:29:07.540   875   875 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 16:29:07.544   875   875 I kickstart: STATUS: Sahara protocol completed
,03-31 16:29:07.560  3266  3266 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 16:29:07.935   823   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-31 16:29:07.941   823   823 V ActivityManager: Display changed displayId=0
,03-31 16:29:07.943   258   258 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-31 16:29:07.943   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-31 16:29:08.208   258   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-31 16:29:08.210   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-31 16:29:08.210   823  1055 D SurfaceControl: Excessive delay in setPowerMode(): 275ms,
,03-31 16:29:08.219   823   861 I DreamManagerService: Entering dreamland.
03-31 16:29:08.220   823   861 I PowerManagerService: Dozing...
03-31 16:29:08.220   823   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-31 16:29:08.223   358  1042 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-31 16:29:08.223   358  1042 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-31 16:29:08.228   823  1034 E WifiStateMachine: cancelDelayedScan -> 16,
,03-31 16:29:08.233   823  1034 E native  : do suspend false,
,03-31 16:29:08.305   823   842 I art     : Explicit concurrent mark sweep GC freed 41478(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.204ms total 52.276ms
,03-31 16:29:08.352  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-31 16:29:08.355  3266  3326 W jxcore-log: Initializing JXcore engine
03-31 16:29:08.355  3266  3326 W jxcore-log: JXcore engine is ready
,03-31 16:29:08.356   823  1034 E WifiStateMachine: cancelDelayedScan -> 18
,03-31 16:29:08.401   823  1034 E native  : do suspend true
,03-31 16:29:08.399  3326  3326 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13005]" dev="sockfs" ino=13005 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 16:29:08.399  3326  3326 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-31 16:29:08.399  3326  3326 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10916]" dev="sockfs" ino=10916 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
03-31 16:29:08.399  3326  3326 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19416]" dev="sockfs" ino=19416 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-31 16:29:08.403   358  1041 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-31 16:29:08.403   358  1041 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-31 16:29:08.412  3266  3326 W jxcore-log: Starting JXcore engine
,03-31 16:29:08.431   823  1034 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-31 16:29:08.501  3266  3326 W jxcore-log: Platform android
03-31 16:29:08.501  3266  3326 W jxcore-log: 
03-31 16:29:08.501  3266  3326 W jxcore-log: Process ARCH arm
03-31 16:29:08.501  3266  3326 W jxcore-log: 
,03-31 16:29:08.551   823  1034 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-31 16:29:08.726  3266  3326 I jxcore-log: JXcore Cordova bridge is ready!
03-31 16:29:08.726  3266  3326 I jxcore-log: 
03-31 16:29:08.726  3266  3326 W jxcore-log: JXcore engine is started
,03-31 16:29:08.739  3266  3315 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 16:29:08.745  3266  3266 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 16:29:10.789  1057  1057 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-31 16:29:11.208  1057  1057 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-31 16:29:11.254  1057  1057 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-31 16:29:11.254  1057  1057 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-31 16:29:11.283   823  1034 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-31 16:29:11.283   823  1034 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-31 16:29:11.285   823  1036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-31 16:29:11.289   823  1034 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 16:29:11.300   354   799 D CommandListener: Setting iface cfg,
,03-31 16:29:11.306   823  1034 E WifiStateMachine: Start Dhcp Watchdog 1
,03-31 16:29:11.309   823  1034 E WifiStateMachine:  WifiLinkLayerStats: 
03-31 16:29:11.309   823  1034 E WifiStateMachine:  my bss beacon rx: 1,
03-31 16:29:11.309   823  1034 E WifiStateMachine:  RSSI mgmt: -40
03-31 16:29:11.309   823  1034 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
,03-31 16:29:11.309   823  1034 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-31 16:29:11.309   823  1034 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-31 16:29:11.309   823  1034 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-31 16:29:11.309   823  1034 E WifiStateMachine:  on_time : 0 tx_time=63 rx_time=82 scan_time=0
,03-31 16:29:11.403   823  1034 E native  : do suspend false
03-31 16:29:11.410   823  1034 E WifiStateMachine: scanCount==0 - aborting
,03-31 16:29:11.647  3332  3332 I dhcpcd  : version 5.5.6 starting
,03-31 16:29:11.777  3332  3332 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-31 16:29:11.903  3332  3332 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-31 16:29:12.013  3332  3332 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-31 16:29:12.426   823  1034 E native  : do suspend true
,03-31 16:29:12.482   823  1036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-31 16:29:12.484   823  1036 D ConnectivityService: Adding iface wlan0 to network 100
,03-31 16:29:12.485   823  1034 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-31 16:29:12.510   823  1036 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-31 16:29:12.510   823  1036 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-31 16:29:12.512   823  1036 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-31 16:29:12.513   823  1036 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-31 16:29:12.514   823  1036 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-31 16:29:12.521   823  1036 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-31 16:29:12.524   823  1036 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-31 16:29:12.525   823  3330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-31 16:29:12.525   823  3330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-31 16:29:12.525   823  3330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-31 16:29:12.526   823  1036 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 16:29:12.526   823  1036 D ConnectivityService:    accepting network in place of null
03-31 16:29:12.526   823  3330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-31 16:29:12.527   823  1036 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-31 16:29:12.529   823  1036 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576,
,03-31 16:29:12.532   823  1036 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-31 16:29:12.533   823  1036 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-31 16:29:12.533  1093  1464 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 16:29:12.533   823  1036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-31 16:29:12.533   823  1036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-31 16:29:12.536   823   858 D Tethering: MasterInitialState.processMessage what=3
,03-31 16:29:12.542   823   842 V BackupManagerService: Scheduling immediate backup pass
03-31 16:29:12.544  2934  2934 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-31 16:29:12.546  1541  1541 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-31 16:29:12.548   823   823 V BackupManagerService: Running a backup pass
,03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:29:12.549  3266  3266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 16:29:12.549  3266  3266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-31 16:29:12.552   823  1054 V BackupManagerService: clearing pending backups
,03-31 16:29:12.554  2934  2934 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-31 16:29:12.559   823  1054 V PerformBackupTask: Beginning backup of 14 targets
,03-31 16:29:12.567   823  1054 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-31 16:29:12.573   823  1054 V BackupServiceBinder: doBackup() invoked
,03-31 16:29:12.592   823  1054 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-31 16:29:12.603   823   842 I ActivityManager: Start proc 3373:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-31 16:29:12.609   823  1054 I BackupRestoreController: Getting widget state for user: 0
,03-31 16:29:12.620  1343  1364 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-31 16:29:12.620  1343  1364 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-31 16:29:12.621   823   853 D TelephonyManager: getDataEnabled: retVal=false
,03-31 16:29:12.634   823   853 E GpsLocationProvider: No APN found to select.
,03-31 16:29:12.696   823  1298 D AlarmManagerService: Setting time of day to sec=1459434552
03-31 16:29:12.836   823  1298 W AlarmManagerService: Unable to set rtc to 1459434552: Invalid argument
,03-31 16:29:12.840  1820  1914 W GmsBackupTransport: Unknown package in backup request: @pm@
03-31 16:29:12.840  1820  1914 V GmsBackupTransport: starting performBackup for @pm@
,03-31 16:29:12.866  1820  1914 V GmsBackupTransport: performBackup done for @pm@
,03-31 16:29:12.867   823  3394 D GpsLocationProvider: NTP server returned: 1459434552863 (Thu Mar 31 16:29:12 GMT+02:00 2016) reference: 168576 certainty: 35 system time offset: -4
,03-31 16:29:12.868  1779  3408 W DriveInitializer: Background init thread started
,03-31 16:29:12.879  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:12.886  1779  3409 W DriveInitializer: Awaiting to be initialized
,03-31 16:29:12.908   823  1342 I ActivityManager: Start proc 3411:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-31 16:29:12.919   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 286us total 10.163ms
,03-31 16:29:12.931   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 11.390ms
,03-31 16:29:12.933   823  3330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 31 Mar 2016 14:29:12 GMT], X-Android-Received-Millis=[1459434552933], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459434552854]}
03-31 16:29:12.934   823  3330 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
,03-31 16:29:12.934   823  1036 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-31 16:29:12.934   823  1036 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-31 16:29:12.934   823  1036 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 16:29:12.934   823  1036 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-31 16:29:12.934   823  1036 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-31 16:29:12.935  1093  1464 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 16:29:12.935   823  1036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-31 16:29:12.945   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 13.880ms
,03-31 16:29:12.961  1131  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-31 16:29:12.961  1131  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:12.961  1131  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:12.962  1131  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:12.966  1131  1147 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:12.992  1131  1147 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 16:29:12.992  1131  1147 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 16:29:12.992  1131  1147 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 16:29:12.992  1131  1147 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 16:29:12.992  1131  1147 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 16:29:12.992  1131  1147 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 16:29:12.992  1131  1147 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 16:29:12.994  3411  3411 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-31 16:29:12.998  1820  1914 W GmsBackupTransport: Error sending final backup to server: 
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 16:29:12.998  1820  1914 W GmsBackupTransport: 	... 1 more
,03-31 16:29:13.002   823  1054 D BackupManagerService: Now staging backup of com.google.android.talk
,03-31 16:29:13.027   823  1054 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-31 16:29:13.030  3411  3411 D SprintDMHelper: simOperator:  IMSI: null
03-31 16:29:13.030  3411  3411 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-31 16:29:13.034   823  1054 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-31 16:29:13.034  1779  1779 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-31 16:29:13.039   823  1054 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-31 16:29:13.042  1779  1779 D SystemUpdateService: onCreate
,03-31 16:29:13.044   823  1054 D BackupManagerService: Now staging backup of com.google.android.gm
,03-31 16:29:13.045  1779  1779 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-31 16:29:13.047  1779  3432 I SystemUpdateService: active receiver: enabled
,03-31 16:29:13.048   823  1054 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-31 16:29:13.050  1779  3432 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-31 16:29:13.063   823  1054 D BackupManagerService: Now staging backup of com.android.nfc
,03-31 16:29:13.066   823  1054 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-31 16:29:13.069   823  1054 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-31 16:29:13.071   823  1054 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
03-31 16:29:13.071  1779  3432 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-31 16:29:13.071  1779  3432 I SystemUpdateService: now status is 0 (complete)
03-31 16:29:13.071  1779  3432 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-31 16:29:13.071  1779  3432 I SystemUpdateService: file has been verified
,03-31 16:29:13.072  1779  3432 I SystemUpdateService: OTA package size = 25802302
,03-31 16:29:13.075   823  1054 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-31 16:29:13.080   823  1054 D BackupManagerService: Now staging backup of com.android.vending
,03-31 16:29:13.083   823  1054 D BackupManagerService: Now staging backup of android
,03-31 16:29:13.087   823  1054 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-31 16:29:13.094  1779  3432 I SystemUpdateService: showing system update notification
,03-31 16:29:13.096  1820  1879 I GmsBackupTransport: Next backup will happen in 43199898 millis.
,03-31 16:29:13.099   823  1054 I BackupManagerService: Backup pass finished.
,03-31 16:29:13.105   823   823 I ValidateNoPeople: skipping global notification
,03-31 16:29:13.116  1131  1883 I art     : Explicit concurrent mark sweep GC freed 18498(959KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 768us total 24.898ms
,03-31 16:29:13.128  1779  3408 W DriveInitializer: Background init thread ended
,03-31 16:29:13.132  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 16:29:13.132  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:13.132  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 16:29:13.132  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:13.135  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:13.146  3090  3407 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 16:29:13.146  3090  3407 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jdm.a(PG:82)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jcs.o(PG:406)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jcn.a(PG:1379)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jcs.i(PG:143)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at blb.a(PG:3937)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at czp.a(PG:18188)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at czp.a(PG:9081)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at czq.run(PG:1686)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:13.146  3090  3407 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jdj.a(PG:4091)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jdj.a(PG:1125)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jdm.a(PG:77)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	... 12 more
03-31 16:29:13.146  3090  3407 E HttpOperation: Caused by: faj: BadAuthentication
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at fal.a(PG:38)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	at jdj.a(PG:4089)
03-31 16:29:13.146  3090  3407 E HttpOperation: 	... 14 more
,03-31 16:29:13.182   823   853 I ActivityManager: Start proc 3446:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-31 16:29:13.184  1779  1779 D SystemUpdateService: onDestroy
,03-31 16:29:13.209  1131  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 16:29:13.210  1131  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:13.210  1131  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:13.210  1131  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:13.213  1131  1147 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:13.223  3090  3407 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 16:29:13.223  3090  3407 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jdm.a(PG:82)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jcs.o(PG:406)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jcn.a(PG:1379)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jcs.i(PG:143)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at hec.a(PG:42)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at hee.a(PG:102)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at czr.a(PG:65)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at kka.a(PG:108)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at czp.a(PG:19176)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at czp.a(PG:9081)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at czq.run(PG:1686)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:13.223  3090  3407 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jdj.a(PG:4091)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jdj.a(PG:1125)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jdm.a(PG:77)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	... 15 more
03-31 16:29:13.223  3090  3407 E HttpOperation: Caused by: faj: BadAuthentication
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at fal.a(PG:38)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	at jdj.a(PG:4089)
03-31 16:29:13.223  3090  3407 E HttpOperation: 	... 17 more
03-31 16:29:13.224  3090  3407 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 16:29:13.224  3090  3407 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at hec.a(PG:42)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at hee.a(PG:102)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at czr.a(PG:65)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at kka.a(PG:108)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	... 15 more
03-31 16:29:13.224  3090  3407 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at fal.a(PG:38)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 16:29:13.224  3090  3407 E ExperimentLoader: 	... 17 more
,03-31 16:29:13.267  1779  3467 I iu.SyncManager: SYNC; picasa accounts
,03-31 16:29:13.276  1779  1779 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-31 16:29:13.278  1779  1779 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-31 16:29:13.292  1779  3467 I iu.UploadsManager: num queued entries: 0
03-31 16:29:13.292  1779  3467 I iu.UploadsManager: num updated entries: 0
03-31 16:29:13.293  1779  3467 I iu.SyncManager: NEXT; no task
,03-31 16:29:13.300  1779  1779 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-31 16:29:13.302  1779  1779 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-31 16:29:13.324   823  1338 I ActivityManager: Start proc 3472:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-31 16:29:13.345   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 38551, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
03-31 16:29:13.345   823   841 I ActivityManager: Killing 2450:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-31 16:29:13.593  3148  3469 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-31 16:29:13.596   823  2128 I ActivityManager: Killing 3002:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-31 16:29:13.779   823   853 I ActivityManager: Start proc 3494:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-31 16:29:13.812  3472  3472 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-31 16:29:13.812  3472  3472 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 16:29:13.812  3472  3472 I GAv4    :   adb logcat -s GAv4
,03-31 16:29:13.822  1131  3490 D GCM     : Connected
,03-31 16:29:13.835  3472  3472 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:29:13.843  1131  3490 D GCM     : Message class com.google.f.a.a.p
,03-31 16:29:13.850  3472  3472 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:29:13.860  3472  3518 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:29:13.877  3446  3517 V KeepSync: Connecting to GoogleApiClient
,03-31 16:29:13.926  1779  3521 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 16:29:13.943  1779  3521 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 16:29:13.960  1131  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 16:29:13.960  1131  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:13.960  1131  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:13.960  1131  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:13.963  1131  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: Handling authorization failure
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 16:29:13.976  1779  3521 E ClientConnectionOperation: 	... 7 more
,03-31 16:29:13.978  3446  3517 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-31 16:29:13.979  3446  3517 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 16:29:13.987  3446  3517 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 16:29:13.987  3446  3517 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 16:29:14.044  3472  3472 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 16:29:14.058  3472  3472 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9764-9767)
03-31 16:29:14.058  3472  3472 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 16:29:14.064  3472  3472 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {40a7e22}
,03-31 16:29:14.066  3472  3472 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 16:29:14.066  3472  3472 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 16:29:14.076  1131  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 16:29:14.076  1131  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:14.076  1131  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:14.076  1131  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:14.079  1131  1147 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 16:29:14.080  3472  3472 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 16:29:14.081  3472  3472 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 16:29:14.082  3472  3472 E SysUtils: ApplicationContext is null in ApplicationStatus
03-31 16:29:14.096  3472  3472 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-31 16:29:14.102  3472  3472 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 16:29:14.102  3472  3472 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 16:29:14.102  3472  3472 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 16:29:14.143   823   841 I art     : Explicit concurrent mark sweep GC freed 51674(2MB) AllocSpace objects, 6(136KB) LOS objects, 32% free, 33MB/49MB, paused 1.868ms total 60.085ms
,03-31 16:29:14.172  3472  3551 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-31 16:29:14.181  3446  3517 E KeepSync: IOException
03-31 16:29:14.181  3446  3517 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 16:29:14.181  3446  3517 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 16:29:14.181  3446  3517 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 16:29:14.181  3446  3517 E KeepSync: 	... 10 more
03-31 16:29:14.181  3446  3517 W KeepSync: Sync result 2
,03-31 16:29:14.192   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 16:29:14.194  3472  3472 I NSApplication: Starting up...
,03-31 16:29:14.220   823   841 I ActivityManager: Start proc 3559:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-31 16:29:14.221   823   841 I ActivityManager: Killing 3022:com.android.musicfx/u0a18 (adj 15): empty #17
,03-31 16:29:14.415  3494  3494 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 16:29:14.473  1131  1149 I art     : Explicit concurrent mark sweep GC freed 14885(856KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 2.457ms total 36.032ms
,03-31 16:29:14.483  3494  3494 I BooksApp: Created application version: 3.6.8 (30608)
,03-31 16:29:14.553  3494  3581 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 16:29:14.695  3494  3589 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 16:29:14.733   823  1019 I ActivityManager: Start proc 3591:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-31 16:29:14.733   823  1019 I ActivityManager: Killing 3053:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-31 16:29:14.866  1131  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 16:29:14.866  1131  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:14.866  1131  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:14.866  1131  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:14.870  1131  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:14.920  1131  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 16:29:14.920  1131  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:14.920  1131  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:14.920  1131  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:14.924  1131  1147 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:14.935  3494  3589 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 16:29:14.938  3494  3581 E BooksSync: Soft error
03-31 16:29:14.938  3494  3581 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 16:29:14.938  3494  3581 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 16:29:14.938  3494  3581 E BooksSync: Sync error
03-31 16:29:14.938  3494  3581 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 16:29:14.938  3494  3581 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 16:29:14.938  3494  3581 I BooksSync: Finished books sync
,03-31 16:29:14.944   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 16:29:14.946   823   842 I ActivityManager: Killing 1413:android.process.acore/u0a5 (adj 15): empty #17
,03-31 16:29:15.051   823   842 I ActivityManager: Killing 2791:com.google.android.gms:car/u0a11 (adj 15): empty #18
,03-31 16:29:15.525   823  1342 I ActivityManager: Killing 2812:com.google.android.gm/u0a78 (adj 15): empty #17
,03-31 16:29:15.845   823  1338 I ActivityManager: Start proc 3610:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-31 16:29:15.904  3610  3610 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459434555904
03-31 16:29:15.904  3610  3610 D         : TimeServiceNative: User Time to be set is 1459434555904
03-31 16:29:15.904  3610  3610 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 16:29:15.904  3610  3610 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-31 16:29:15.904  3610  3610 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459434555904
03-31 16:29:15.904  3610  3610 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-31 16:29:15.904   373   879 D QC-time-services: Daemon: Connection accepted:time_genoff
03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459434555904
03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459434555904, operation = 0
,03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/17/70 10:40:54,
03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:Value read from RTC seconds = 19737654000
,03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:new time 1459434555904 
,03-31 16:29:15.905   373  3627 D QC-time-services: Daemon: delta 1439696901904 genoff 1439696901904 
03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901904 to memory
03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-31 16:29:15.905   373  3627 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 16:29:15.910   373  3627 D QC-time-services: Updating the TOD offset
,03-31 16:29:15.910   373  3627 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901904 to memory
03-31 16:29:15.910   373  3627 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,03-31 16:29:15.910   373  3627 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 16:29:15.913   373  3627 E QC-time-services: Daemon:Update to modem bit set,
03-31 16:29:15.913   373  3627 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,03-31 16:29:15.913   373  3627 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143469755904
03-31 16:29:15.913  3610  3610 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0,
,03-31 16:29:15.983   373   879 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-31 16:29:15.988   373   877 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-31 16:29:16.036   823  1342 I ActivityManager: Start proc 3629:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-31 16:29:16.046   823  1338 I ActivityManager: Killing 1889:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-31 16:29:16.206  3629  3629 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 16:29:16.206  3629  3629 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 16:29:16.206  3629  3629 I GAv4    :   adb logcat -s GAv4
,03-31 16:29:16.240  3629  3629 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:29:16.254  3629  3629 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:29:16.264  3629  3648 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:29:16.313   823  1341 I ActivityManager: Killing 3123:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-31 16:29:16.538  1779  1779 V Herrevad: NQAS connected
,03-31 16:29:16.548  3148  3148 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:29:16.548  3148  3148 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 16:29:16.602   823  2591 I ActivityManager: Start proc 3659:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-31 16:29:16.613  1779  3653 I art     : Explicit concurrent mark sweep GC freed 14866(1098KB) AllocSpace objects, 13(208KB) LOS objects, 35% free, 28MB/44MB, paused 2.101ms total 52.935ms
03-31 16:29:16.614   823  1035 D WifiService: New client listening to asynchronous messages
,03-31 16:29:16.633  3659  3659 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 16:29:16.661  3659  3659 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@10924fae(com.android.providers.calendar.CalendarProvider2@3127214f)
,03-31 16:29:16.755   823  1341 I art     : Explicit concurrent mark sweep GC freed 18631(858KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.774ms total 46.136ms
,03-31 16:29:16.766  1131  1883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-31 16:29:16.767  1131  1883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:16.767  1131  1883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:16.767  1131  1883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:16.770  1131  1883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:16.778  3148  3655 E Babel   : UserRecoverableAuthException.
,03-31 16:29:16.779  3148  3655 E Babel   : eei: BadAuthentication
03-31 16:29:16.779  3148  3655 E Babel   : 	at eeg.a(Unknown Source)
03-31 16:29:16.779  3148  3655 E Babel   : 	at eeg.a(Unknown Source)
03-31 16:29:16.779  3148  3655 E Babel   : 	at eeg.a(Unknown Source)
03-31 16:29:16.779  3148  3655 E Babel   : 	at g.a(Unknown Source)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cae.a(SourceFile:3089)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cae.a(SourceFile:1131)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cws.a(SourceFile:4333)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cws.a(SourceFile:1419)
03-31 16:29:16.779  3148  3655 E Babel   : 	at crl.a(SourceFile:492)
03-31 16:29:16.779  3148  3655 E Babel   : 	at crl.a(SourceFile:1468)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cas.b(SourceFile:106)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cap.d(SourceFile:335)
03-31 16:29:16.779  3148  3655 E Babel   : 	at caq.run(SourceFile:81)
03-31 16:29:16.779  3148  3655 E Babel   : Error getting auth token
,03-31 16:29:16.779  3148  3655 E Babel   : dvm
03-31 16:29:16.779  3148  3655 E Babel   : 	at g.a(Unknown Source)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cae.a(SourceFile:3089)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cae.a(SourceFile:1131)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cws.a(SourceFile:4333)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cws.a(SourceFile:1419)
03-31 16:29:16.779  3148  3655 E Babel   : 	at crl.a(SourceFile:492)
03-31 16:29:16.779  3148  3655 E Babel   : 	at crl.a(SourceFile:1468)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cas.b(SourceFile:106)
03-31 16:29:16.779  3148  3655 E Babel   : 	at cap.d(SourceFile:335)
03-31 16:29:16.779  3148  3655 E Babel   : 	at caq.run(SourceFile:81)
,03-31 16:29:16.782  3148  3655 E Babel   : Account registration failed 1-Redacted-21
03-31 16:29:16.783  3148  3655 E Babel   : cyp: null -- null
03-31 16:29:16.783  3148  3655 E Babel   : 	at cae.a(SourceFile:3121)
03-31 16:29:16.783  3148  3655 E Babel   : 	at cae.a(SourceFile:1131)
03-31 16:29:16.783  3148  3655 E Babel   : 	at cws.a(SourceFile:4333)
03-31 16:29:16.783  3148  3655 E Babel   : 	at cws.a(SourceFile:1419)
03-31 16:29:16.783  3148  3655 E Babel   : 	at crl.a(SourceFile:492)
03-31 16:29:16.783  3148  3655 E Babel   : 	at crl.a(SourceFile:1468)
03-31 16:29:16.783  3148  3655 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 16:29:16.783  3148  3655 E Babel   : 	at cas.b(SourceFile:106)
03-31 16:29:16.783  3148  3655 E Babel   : 	at cap.d(SourceFile:335)
03-31 16:29:16.783  3148  3655 E Babel   : 	at caq.run(SourceFile:81)
,03-31 16:29:16.800  3148  3655 I art     : Note: end time exceeds epoch: 
,03-31 16:29:16.803  1131  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-31 16:29:16.803  1131  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:16.803  1131  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:16.803  1131  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:16.806  1131  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:16.819  1131  1705 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 16:29:16.835  3148  3686 E Babel   : Unexpected exception while authenticating.
03-31 16:29:16.836  3148  3686 E Babel   : eej: User intervention required. Notification has been pushed.
03-31 16:29:16.836  3148  3686 E Babel   : 	at eeg.b(Unknown Source)
03-31 16:29:16.836  3148  3686 E Babel   : 	at eeg.b(Unknown Source)
03-31 16:29:16.836  3148  3686 E Babel   : 	at g.a(Unknown Source)
03-31 16:29:16.836  3148  3686 E Babel   : 	at cae.b(SourceFile:1146)
03-31 16:29:16.836  3148  3686 E Babel   : 	at dcg.run(SourceFile:5617)
03-31 16:29:16.836  3148  3686 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:16.836  3148  3686 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:16.836  3148  3686 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:29:16.847  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:16.922  1131  3692 I VacuumService: Vacuum at: now=1459434556922 tag=VacuumService
,03-31 16:29:16.978  1131  3693 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 16:29:17.000  1131  3693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 16:29:17.000  1131  3693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:17.000  1131  3693 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:17.000  1131  3693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:17.003  1131  3693 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:17.022  1131  3693 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 16:29:17.022  1131  3693 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 16:29:17.022  1131  3693 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 16:29:17.058  3373  3691 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 16:29:17.091  1131  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 16:29:17.091  1131  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:17.091  1131  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:17.091  1131  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:17.097  1131  1147 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:17.120  3373  3691 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 16:29:17.125  3373  3691 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 16:29:17.516  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:17.701  3659  3659 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-31 16:29:17.702  3659  3659 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 16:29:17.713  1131  3693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 16:29:17.714  1131  3693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:17.714  1131  3693 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 16:29:17.714  1131  3693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:17.727  1131  3693 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:17.798  1131  1149 I art     : Explicit concurrent mark sweep GC freed 36494(2MB) AllocSpace objects, 5(385KB) LOS objects, 37% free, 26MB/42MB, paused 1.799ms total 55.831ms
,03-31 16:29:17.843  1131  3693 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 16:29:17.843  1131  3693 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 16:29:17.843  1131  3693 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 16:29:17.856  3659  3698 E SQLiteLog: (284) automatic index on view_events(_id)
,03-31 16:29:18.035  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:18.215  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:18.445  1131  3693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 16:29:18.446  1131  3693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:18.446  1131  3693 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:18.446  1131  3693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 16:29:18.451  1131  3693 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:18.494  1131  3693 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 16:29:18.494  1131  3693 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 16:29:18.494  1131  3693 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 16:29:18.638  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:18.807  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:18.860  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:29:18.860  3266  3326 I jxcore-log: 
,03-31 16:29:18.863  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:29:18.863  3266  3326 I jxcore-log: 
,03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:29:18.883  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:29:18.885  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 16:29:18.889  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 16:29:18.889  3266  3326 I jxcore-log: 
03-31 16:29:18.891  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:29:18.891  3266  3326 I jxcore-log: 
,03-31 16:29:18.945  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:19.053  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:19.270  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:19.420  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:19.438  3494  3576 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 16:29:19.441  3266  3326 I jxcore-log: Unit Test app is loaded
03-31 16:29:19.441  3266  3326 I jxcore-log: 
,03-31 16:29:19.446  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:29:19.446  3266  3326 I jxcore-log: 
,03-31 16:29:19.450  3266  3326 I jxcore-log: My device name is: motorola-Nexus 6
03-31 16:29:19.450  3266  3326 I jxcore-log: 
,03-31 16:29:19.450  3266  3266 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 16:29:19.452  3266  3326 I jxcore-log: WARN testUtils: myNameCallback not set!
03-31 16:29:19.452  3266  3326 I jxcore-log: 
,03-31 16:29:19.539  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:19.696  1131  3693 W Uploader:  no longer exists, so no auth token.
,03-31 16:29:19.913  1131  3693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 16:29:19.914  1131  3693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:19.914  1131  3693 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:19.914  1131  3693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:19.918  1131  3693 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:19.943  1131  3693 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 16:29:19.943  1131  3693 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 16:29:19.943  1131  3693 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 16:29:20.063  1131  3693 W Uploader: No account for auth token provided
,03-31 16:29:20.259  1131  3693 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 16:29:20.259  1131  3693 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:20.259  1131  3693 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 16:29:20.259  1131  3693 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:20.276  1131  3693 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:20.325  1131  3693 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 16:29:20.325  1131  3693 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 16:29:20.325  1131  3693 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 16:29:22.914   823   841 I ActivityManager: Killing 2749:com.android.vending/u0a19 (adj 15): empty #17
,03-31 16:29:23.377  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 16:29:23.377  3266  3326 I jxcore-log: 
,03-31 16:29:23.717  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
,03-31 16:29:23.717  3266  3326 I jxcore-log: 
,03-31 16:29:23.730  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 16:29:23.730  3266  3326 I jxcore-log: 
,03-31 16:29:23.735  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 16:29:23.735  3266  3326 I jxcore-log: 
,03-31 16:29:23.773  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 16:29:23.773  3266  3326 I jxcore-log: 
,03-31 16:29:23.789  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 16:29:23.789  3266  3326 I jxcore-log: 
,03-31 16:29:23.794  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 16:29:23.794  3266  3326 I jxcore-log: 
,03-31 16:29:24.615   823  1019 I ActivityManager: Start proc 3701:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-31 16:29:24.768  3701  3701 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-31 16:29:24.861  3701  3701 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-31 16:29:24.944   823  1342 I ActivityManager: Start proc 3737:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-31 16:29:24.959  3701  3701 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 16:29:24.963  3701  3701 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 16:29:25.002  3737  3737 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:29:25.003  3737  3737 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 16:29:25.007   823  2591 I ActivityManager: Killing 2934:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-31 16:29:25.010  3701  3716 D Finsky  : [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-31 16:29:25.028  3737  3737 I MultiDex: VM with version 2.1.0 has multidex support
,03-31 16:29:25.028  3737  3737 I MultiDex: install
03-31 16:29:25.028  3737  3737 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 16:29:25.131  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:25.132  3701  3701 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-31 16:29:25.133  3701  3701 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-31 16:29:25.140  3701  3701 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-31 16:29:25.173  3701  3701 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-31 16:29:25.178  3737  3737 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 16:29:25.184  1131  1148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 16:29:25.184  1131  1148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:25.184  1131  1148 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:25.184  1131  1148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:25.187  1131  1148 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:25.199  3701  3716 D Finsky  : [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-31 16:29:25.219  3737  3737 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 16:29:25.222  1131  2118 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 16:29:25.226  1131  1131 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 16:29:25.231  1779  1779 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 16:29:25.272   823   842 I ActivityManager: Start proc 3765:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-31 16:29:25.283   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 11.185ms
,03-31 16:29:25.290  1779  3780 D LocationInitializer: Restart initialization of location
,03-31 16:29:25.293   370   370 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 243us total 9.853ms
,03-31 16:29:25.304   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 10.251ms
,03-31 16:29:25.312  3765  3765 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:29:25.312  3765  3765 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 16:29:25.344  3765  3765 I MultiDex: VM with version 2.1.0 has multidex support
03-31 16:29:25.344  3765  3765 I MultiDex: install
03-31 16:29:25.344  3765  3765 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 16:29:25.359  3765  3765 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 16:29:25.389  3765  3765 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 16:29:25.394  1131  2122 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 16:29:25.396  1131  1131 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 16:29:25.401  1779  1779 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 16:29:25.410  3765  3765 D WearableService: callingUid 10011, callindPid: 3765
,03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: Install did not work
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-31 16:29:25.412  3765  3786 W NativeLibraryUtils: 	... 4 more
,03-31 16:29:25.461   823  1338 I art     : Explicit concurrent mark sweep GC freed 23160(1063KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 929us total 49.380ms
,03-31 16:29:25.473  1779  3788 D LocationInitializer: Restart initialization of location
,03-31 16:29:25.474  1820  2081 E MDM     : [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 16:29:25.477  1820  2081 E MDM     : [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 16:29:25.543  3701  3701 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-31 16:29:25.817  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 16:29:25.817  3266  3326 I jxcore-log: 
,03-31 16:29:25.834  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-31 16:29:25.834  3266  3326 I jxcore-log: 
,03-31 16:29:25.842  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
03-31 16:29:25.842  3266  3326 I jxcore-log: 
,03-31 16:29:25.877  3701  3701 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-31 16:29:25.904  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:25.949  1131  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 16:29:25.949  1131  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:25.949  1131  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:25.949  1131  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:25.955  1131  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:25.971  3701  3701 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 16:29:25.981  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.000  1131  1149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 16:29:26.000  1131  1149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:26.000  1131  1149 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:26.000  1131  1149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:26.004  1131  1149 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.126  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 16:29:26.126  3266  3326 I jxcore-log: 
,03-31 16:29:26.198  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 16:29:26.198  3266  3326 I jxcore-log: 
,03-31 16:29:26.255  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 16:29:26.255  3266  3326 I jxcore-log: 
,03-31 16:29:26.262  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 16:29:26.262  3266  3326 I jxcore-log: 
,03-31 16:29:26.273  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 16:29:26.273  3266  3326 I jxcore-log: 
,03-31 16:29:26.279  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 16:29:26.279  3266  3326 I jxcore-log: 
,03-31 16:29:26.285  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 16:29:26.285  3266  3326 I jxcore-log: 
03-31 16:29:26.285  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.301  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
03-31 16:29:26.301  3266  3326 I jxcore-log: 
,03-31 16:29:26.320  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 16:29:26.320  3266  3326 I jxcore-log: 
,03-31 16:29:26.352  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 16:29:26.352  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:26.352  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:26.352  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:26.362  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.373  3701  3701 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 16:29:26.374  3701  3701 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 16:29:26.374  3701  3701 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-31 16:29:26.395  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 16:29:26.395  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:26.395  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:26.395  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:26.399  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.408  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 16:29:26.408  3266  3326 I jxcore-log: 
,03-31 16:29:26.411  3701  3701 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 16:29:26.414  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 16:29:26.414  3266  3326 I jxcore-log: 
,03-31 16:29:26.439  3266  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 16:29:26.439  3266  3326 I jxcore-log: 
,03-31 16:29:26.446  3266  3326 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 16:29:26.447  3266  3326 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
,03-31 16:29:26.447  3266  3326 I jxcore-log: 
,03-31 16:29:26.606  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.631  1131  1149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 16:29:26.631  1131  1149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:26.631  1131  1149 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:26.631  1131  1149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:26.636  1131  1149 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:26.659  3701  3701 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 16:29:26.663  3701  3701 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-31 16:29:26.674  3701  3701 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 16:29:26.679  3701  3701 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,03-31 16:29:26.700  1820  1912 D DeviceConnectionService: client connected with version: 7571000
,03-31 16:29:27.614  3266  3326 I jxcore-log: TAP version 13
03-31 16:29:27.614  3266  3326 I jxcore-log: 
,03-31 16:29:27.618  3266  3326 I jxcore-log: # setup,
03-31 16:29:27.618  3266  3326 I jxcore-log: 
,03-31 16:29:27.945  3266  3326 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 16:29:27.945  3266  3326 I jxcore-log: 
,03-31 16:29:28.221  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 16:29:28.221  3266  3326 I jxcore-log: 
,03-31 16:29:28.227  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 46824
03-31 16:29:28.227  3266  3326 I jxcore-log: 
,03-31 16:29:28.233  3266  3326 I jxcore-log: ok 1 Should throw
03-31 16:29:28.233  3266  3326 I jxcore-log: 
,03-31 16:29:28.236  3266  3326 I jxcore-log: # teardown
03-31 16:29:28.236  3266  3326 I jxcore-log: 
,03-31 16:29:28.382  3266  3326 I jxcore-log: # setup
03-31 16:29:28.382  3266  3326 I jxcore-log: 
,03-31 16:29:28.548  3266  3326 I jxcore-log: # 2. emits incomingConnectionState
03-31 16:29:28.548  3266  3326 I jxcore-log: 
,03-31 16:29:28.699  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:28.699  3266  3326 I jxcore-log: 
,03-31 16:29:28.705  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 38687
03-31 16:29:28.705  3266  3326 I jxcore-log: 
,03-31 16:29:28.715  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:28.715  3266  3326 I jxcore-log: 
,03-31 16:29:28.718  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:28.718  3266  3326 I jxcore-log: 
,03-31 16:29:28.728  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:28.728  3266  3326 I jxcore-log: 
,03-31 16:29:28.734  3266  3326 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 16:29:28.734  3266  3326 I jxcore-log: 
,03-31 16:29:28.748  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:28.748  3266  3326 I jxcore-log: 
,03-31 16:29:28.749  3266  3326 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 16:29:28.749  3266  3326 I jxcore-log: 
,03-31 16:29:28.761  3266  3326 I jxcore-log: # teardown
03-31 16:29:28.761  3266  3326 I jxcore-log: 
,03-31 16:29:28.880  3266  3326 I jxcore-log: # setup
03-31 16:29:28.880  3266  3326 I jxcore-log: 
,03-31 16:29:29.174  3266  3326 I jxcore-log: # 3. emits routerPortConnectionFailed
03-31 16:29:29.174  3266  3326 I jxcore-log: 
,03-31 16:29:29.446  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:29.446  3266  3326 I jxcore-log: 
03-31 16:29:29.448  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 50034
03-31 16:29:29.448  3266  3326 I jxcore-log: 
,03-31 16:29:29.459  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:29.459  3266  3326 I jxcore-log: 
,03-31 16:29:29.463  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:29.463  3266  3326 I jxcore-log: 
,03-31 16:29:29.468  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:29.468  3266  3326 I jxcore-log: 
,03-31 16:29:29.498  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:29.498  3266  3326 I jxcore-log: 
,03-31 16:29:29.501  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:29.501  3266  3326 I jxcore-log: 
,03-31 16:29:29.510  3266  3326 I jxcore-log: DEBUG createNativeListener: 
03-31 16:29:29.510  3266  3326 I jxcore-log: 
,03-31 16:29:29.514  3266  3326 I jxcore-log: ok 4 tried to connect to right port
03-31 16:29:29.514  3266  3326 I jxcore-log: 
,03-31 16:29:29.516  3266  3326 I jxcore-log: ok 5 failed due to refused connection
03-31 16:29:29.516  3266  3326 I jxcore-log: 
,03-31 16:29:29.518  3266  3326 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
,03-31 16:29:29.518  3266  3326 I jxcore-log: 
,03-31 16:29:29.532  3266  3326 I jxcore-log: # teardown
03-31 16:29:29.532  3266  3326 I jxcore-log: ,
,03-31 16:29:29.534  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:29.534  3266  3326 I jxcore-log: 
,03-31 16:29:29.659  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:29.659  3266  3326 I jxcore-log: 
,03-31 16:29:29.665  3266  3326 I jxcore-log: # setup
03-31 16:29:29.665  3266  3326 I jxcore-log: 
,03-31 16:29:29.666  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:29.666  3266  3326 I jxcore-log: 
,03-31 16:29:29.879  3266  3326 I jxcore-log: # 4. native server connections all up
03-31 16:29:29.879  3266  3326 I jxcore-log: 
,03-31 16:29:30.062  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:30.062  3266  3326 I jxcore-log: 
03-31 16:29:30.070  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 45032
03-31 16:29:30.070  3266  3326 I jxcore-log: 
,03-31 16:29:30.080  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:30.080  3266  3326 I jxcore-log: 
,03-31 16:29:30.082  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:30.082  3266  3326 I jxcore-log: 
03-31 16:29:30.084  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:30.084  3266  3326 I jxcore-log: 
,03-31 16:29:30.107  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:30.107  3266  3326 I jxcore-log: 
,03-31 16:29:30.109  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:30.109  3266  3326 I jxcore-log: 
,03-31 16:29:30.113  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:30.113  3266  3326 I jxcore-log: 
,03-31 16:29:30.115  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:30.115  3266  3326 I jxcore-log: 
,03-31 16:29:30.144  3266  3326 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 16:29:30.144  3266  3326 I jxcore-log: 
,03-31 16:29:30.144  3266  3326 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 16:29:30.144  3266  3326 I jxcore-log: 
03-31 16:29:30.147  3266  3326 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 16:29:30.147  3266  3326 I jxcore-log: 
03-31 16:29:30.147  3266  3326 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 16:29:30.147  3266  3326 I jxcore-log: 
03-31 16:29:30.150  3266  3326 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-31 16:29:30.150  3266  3326 I jxcore-log: 
,03-31 16:29:30.158  3266  3326 I jxcore-log: # teardown
03-31 16:29:30.158  3266  3326 I jxcore-log: 
,03-31 16:29:30.376  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 16:29:30.376  3266  3326 I jxcore-log: 
03-31 16:29:30.378  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:30.378  3266  3326 I jxcore-log: 
03-31 16:29:30.380  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:30.380  3266  3326 I jxcore-log: 
,03-31 16:29:30.386  3266  3326 I jxcore-log: # setup
,03-31 16:29:30.386  3266  3326 I jxcore-log: 
,03-31 16:29:30.388  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:30.388  3266  3326 I jxcore-log: ,
,03-31 16:29:30.495   823   841 I ActivityManager: Killing 3411:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-31 16:29:30.675  3266  3326 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 16:29:30.675  3266  3326 I jxcore-log: 
,03-31 16:29:30.878  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:30.878  3266  3326 I jxcore-log: 
,03-31 16:29:30.884  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 38341,
03-31 16:29:30.884  3266  3326 I jxcore-log: 
,03-31 16:29:30.890  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:30.890  3266  3326 I jxcore-log: ,
03-31 16:29:30.891  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:30.891  3266  3326 I jxcore-log: 
,03-31 16:29:30.893  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:30.893  3266  3326 I jxcore-log: 
,03-31 16:29:30.905  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:30.905  3266  3326 I jxcore-log: 
,03-31 16:29:30.908  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:30.908  3266  3326 I jxcore-log: 
,03-31 16:29:30.922  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 16:29:30.922  3266  3326 I jxcore-log: 
,03-31 16:29:30.935   823  2128 I ActivityManager: Killing 3472:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-31 16:29:30.939  3266  3326 I jxcore-log: ok 12 socket shouldn't close until after stream
03-31 16:29:30.939  3266  3326 I jxcore-log: 
03-31 16:29:30.940  3266  3326 I jxcore-log: ok 13 incoming remains open
03-31 16:29:30.940  3266  3326 I jxcore-log: 
,03-31 16:29:30.946  3266  3326 I jxcore-log: # teardown,
03-31 16:29:30.946  3266  3326 I jxcore-log: 
,03-31 16:29:31.243  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:31.243  3266  3326 I jxcore-log: 
03-31 16:29:31.247  3266  3326 I jxcore-log: # setup
03-31 16:29:31.247  3266  3326 I jxcore-log: 
03-31 16:29:31.248  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:31.248  3266  3326 I jxcore-log: 
,03-31 16:29:31.743  2164  2229 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 16:29:31.966  3266  3326 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-31 16:29:31.966  3266  3326 I jxcore-log: 
,03-31 16:29:32.396  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:32.396  3266  3326 I jxcore-log: 
,03-31 16:29:32.404  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 44604,
03-31 16:29:32.404  3266  3326 I jxcore-log: 
,03-31 16:29:32.409  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:32.409  3266  3326 I jxcore-log: 
,03-31 16:29:32.411  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:32.411  3266  3326 I jxcore-log: 
03-31 16:29:32.412  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:32.412  3266  3326 I jxcore-log: 
,03-31 16:29:32.422  3266  3326 I jxcore-log: ok 14 we should not have gotten an error,
03-31 16:29:32.422  3266  3326 I jxcore-log: 
,03-31 16:29:32.427  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:32.427  3266  3326 I jxcore-log: 
,03-31 16:29:32.432  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:32.432  3266  3326 I jxcore-log: ,
,03-31 16:29:32.443  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:32.443  3266  3326 I jxcore-log: 
,03-31 16:29:32.446  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-31 16:29:32.446  3266  3326 I jxcore-log: 
,03-31 16:29:32.454  3266  3326 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-31 16:29:32.454  3266  3326 I jxcore-log: 
,03-31 16:29:32.454  3266  3326 I jxcore-log: ok 16 incoming is cleaned up
03-31 16:29:32.454  3266  3326 I jxcore-log: ,
03-31 16:29:32.459  3266  3326 I jxcore-log: # teardown
03-31 16:29:32.459  3266  3326 I jxcore-log: 
,03-31 16:29:32.947  3266  3326 I jxcore-log: # setup,
03-31 16:29:32.947  3266  3326 I jxcore-log: 
,03-31 16:29:33.714  3266  3326 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 16:29:33.714  3266  3326 I jxcore-log: 
,03-31 16:29:34.598  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:34.598  3266  3326 I jxcore-log: 
,03-31 16:29:34.604  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 50128
03-31 16:29:34.604  3266  3326 I jxcore-log: 
,03-31 16:29:34.610  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:34.610  3266  3326 I jxcore-log: 
,03-31 16:29:34.611  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:34.611  3266  3326 I jxcore-log: 
,03-31 16:29:34.614  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:34.614  3266  3326 I jxcore-log: 
,03-31 16:29:34.625  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:34.625  3266  3326 I jxcore-log: 
,03-31 16:29:34.628  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:34.628  3266  3326 I jxcore-log: 
,03-31 16:29:34.641  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:34.641  3266  3326 I jxcore-log: 
,03-31 16:29:34.651  3266  3326 I jxcore-log: ok 17 stream was closed
03-31 16:29:34.651  3266  3326 I jxcore-log: 
,03-31 16:29:34.651  3266  3326 I jxcore-log: ok 18 incoming should survive
03-31 16:29:34.651  3266  3326 I jxcore-log: 
,03-31 16:29:34.652  3266  3326 I jxcore-log: ok 19 mux should have no streams
03-31 16:29:34.652  3266  3326 I jxcore-log: 
,03-31 16:29:34.659  3266  3326 I jxcore-log: # teardown
03-31 16:29:34.659  3266  3326 I jxcore-log: 
,03-31 16:29:35.720  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:35.720  3266  3326 I jxcore-log: 
,03-31 16:29:35.728  3266  3326 I jxcore-log: # setup
03-31 16:29:35.728  3266  3326 I jxcore-log: 
,03-31 16:29:35.729  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:35.729  3266  3326 I jxcore-log: 
,03-31 16:29:37.088  3266  3326 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-31 16:29:37.088  3266  3326 I jxcore-log: 
,03-31 16:29:38.205  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:38.205  3266  3326 I jxcore-log: 
,03-31 16:29:38.215  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 60477
03-31 16:29:38.215  3266  3326 I jxcore-log: 
,03-31 16:29:38.226  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:38.226  3266  3326 I jxcore-log: 
,03-31 16:29:38.227  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:38.227  3266  3326 I jxcore-log: 
,03-31 16:29:38.228  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:38.228  3266  3326 I jxcore-log: 
,03-31 16:29:38.238  3266  3326 I jxcore-log: ok 20 we should not have gotten an error
03-31 16:29:38.238  3266  3326 I jxcore-log: 
,03-31 16:29:38.245  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:38.245  3266  3326 I jxcore-log: 
,03-31 16:29:38.247  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:38.247  3266  3326 I jxcore-log: 
,03-31 16:29:38.257  3266  3326 I jxcore-log: ok 21 Buffers are identical
03-31 16:29:38.257  3266  3326 I jxcore-log: 
,03-31 16:29:38.259  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:38.259  3266  3326 I jxcore-log: 
,03-31 16:29:38.264  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:38.264  3266  3326 I jxcore-log: 
,03-31 16:29:38.267  3266  3326 I jxcore-log: ok 22 native server is nulled out
03-31 16:29:38.267  3266  3326 I jxcore-log: 
,03-31 16:29:38.267  3266  3326 I jxcore-log: ok 23 native server should be closed,
03-31 16:29:38.267  3266  3326 I jxcore-log: 
03-31 16:29:38.268  3266  3326 I jxcore-log: ok 24 incoming has been removed
03-31 16:29:38.268  3266  3326 I jxcore-log: 
03-31 16:29:38.268  3266  3326 I jxcore-log: ok 25 Incoming should be done
03-31 16:29:38.268  3266  3326 I jxcore-log: 
,03-31 16:29:38.268  3266  3326 I jxcore-log: ok 26 The mux object should be closed
03-31 16:29:38.268  3266  3326 I jxcore-log: 
03-31 16:29:38.268  3266  3326 I jxcore-log: ok 27 The mux stream should be closed
03-31 16:29:38.268  3266  3326 I jxcore-log: 
03-31 16:29:38.269  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:38.269  3266  3326 I jxcore-log: 
,03-31 16:29:38.284  3266  3326 I jxcore-log: # teardown
03-31 16:29:38.284  3266  3326 I jxcore-log: 
,03-31 16:29:39.449  3266  3326 I jxcore-log: # setup
03-31 16:29:39.449  3266  3326 I jxcore-log: 
,03-31 16:29:40.183  3266  3326 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-31 16:29:40.183  3266  3326 I jxcore-log: 
,03-31 16:29:41.722  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:41.812  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 16:29:41.812  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 16:29:41.813  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:41.813  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:41.826  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:41.923  1131  1706 I art     : Explicit concurrent mark sweep GC freed 50280(2MB) AllocSpace objects, 10(1028KB) LOS objects, 37% free, 27MB/43MB, paused 1.428ms total 65.437ms
,03-31 16:29:41.926  3701  3701 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 16:29:41.926  3701  3701 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 16:29:41.927  3701  3701 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-31 16:29:43.488  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:43.488  3266  3326 I jxcore-log: 
,03-31 16:29:43.494  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 47348
03-31 16:29:43.494  3266  3326 I jxcore-log: 
,03-31 16:29:43.513  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.513  3266  3326 I jxcore-log: 
,03-31 16:29:43.514  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.514  3266  3326 I jxcore-log: 
03-31 16:29:43.516  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.516  3266  3326 I jxcore-log: 
,03-31 16:29:43.519  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.519  3266  3326 I jxcore-log: 
,03-31 16:29:43.520  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.520  3266  3326 I jxcore-log: 
,03-31 16:29:43.522  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.522  3266  3326 I jxcore-log: 
,03-31 16:29:43.528  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.528  3266  3326 I jxcore-log: 
03-31 16:29:43.529  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.529  3266  3326 I jxcore-log: 
,03-31 16:29:43.530  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.530  3266  3326 I jxcore-log: 
,03-31 16:29:43.533  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.533  3266  3326 I jxcore-log: 
,03-31 16:29:43.534  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.534  3266  3326 I jxcore-log: 
03-31 16:29:43.535  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.535  3266  3326 I jxcore-log: 
,03-31 16:29:43.538  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.538  3266  3326 I jxcore-log: 
,03-31 16:29:43.538  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.538  3266  3326 I jxcore-log: 
,03-31 16:29:43.540  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.540  3266  3326 I jxcore-log: 
03-31 16:29:43.542  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.542  3266  3326 I jxcore-log: 
03-31 16:29:43.543  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.543  3266  3326 I jxcore-log: 
,03-31 16:29:43.543  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.543  3266  3326 I jxcore-log: 
,03-31 16:29:43.545  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.545  3266  3326 I jxcore-log: 
,03-31 16:29:43.546  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.546  3266  3326 I jxcore-log: 
03-31 16:29:43.546  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.546  3266  3326 I jxcore-log: 
,03-31 16:29:43.548  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.548  3266  3326 I jxcore-log: 
,03-31 16:29:43.549  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.549  3266  3326 I jxcore-log: 
03-31 16:29:43.549  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.549  3266  3326 I jxcore-log: 
03-31 16:29:43.551  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.551  3266  3326 I jxcore-log: 
,03-31 16:29:43.552  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.552  3266  3326 I jxcore-log: 
03-31 16:29:43.552  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.552  3266  3326 I jxcore-log: 
03-31 16:29:43.554  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:43.554  3266  3326 I jxcore-log: 
03-31 16:29:43.555  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:43.555  3266  3326 I jxcore-log: 
,03-31 16:29:43.555  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:43.555  3266  3326 I jxcore-log: 
,03-31 16:29:43.676  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.676  3266  3326 I jxcore-log: 
,03-31 16:29:43.679  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.679  3266  3326 I jxcore-log: 
,03-31 16:29:43.681  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.681  3266  3326 I jxcore-log: 
,03-31 16:29:43.683  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.683  3266  3326 I jxcore-log: 
,03-31 16:29:43.685  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.685  3266  3326 I jxcore-log: 
,03-31 16:29:43.686  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.686  3266  3326 I jxcore-log: 
,03-31 16:29:43.689  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.689  3266  3326 I jxcore-log: 
,03-31 16:29:43.691  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.691  3266  3326 I jxcore-log: 
,03-31 16:29:43.694  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.694  3266  3326 I jxcore-log: 
,03-31 16:29:43.696  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.696  3266  3326 I jxcore-log: 
,03-31 16:29:43.697  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.697  3266  3326 I jxcore-log: 
,03-31 16:29:43.699  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.699  3266  3326 I jxcore-log: 
,03-31 16:29:43.700  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.700  3266  3326 I jxcore-log: 
,03-31 16:29:43.702  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.702  3266  3326 I jxcore-log: 
,03-31 16:29:43.703  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.703  3266  3326 I jxcore-log: 
,03-31 16:29:43.705  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.705  3266  3326 I jxcore-log: 
,03-31 16:29:43.707  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.707  3266  3326 I jxcore-log: 
,03-31 16:29:43.709  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.709  3266  3326 I jxcore-log: 
,03-31 16:29:43.710  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.710  3266  3326 I jxcore-log: 
,03-31 16:29:43.715  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.715  3266  3326 I jxcore-log: 
,03-31 16:29:43.717  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.717  3266  3326 I jxcore-log: 
,03-31 16:29:43.719  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.719  3266  3326 I jxcore-log: 
,03-31 16:29:43.720  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.720  3266  3326 I jxcore-log: 
,03-31 16:29:43.723  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.723  3266  3326 I jxcore-log: 
,03-31 16:29:43.725  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.725  3266  3326 I jxcore-log: 
,03-31 16:29:43.726  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.726  3266  3326 I jxcore-log: 
,03-31 16:29:43.728  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.728  3266  3326 I jxcore-log: 
,03-31 16:29:43.729  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.729  3266  3326 I jxcore-log: 
,03-31 16:29:43.730  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.730  3266  3326 I jxcore-log: 
,03-31 16:29:43.732  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.732  3266  3326 I jxcore-log: 
,03-31 16:29:43.733  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.733  3266  3326 I jxcore-log: 
,03-31 16:29:43.735  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.735  3266  3326 I jxcore-log: 
,03-31 16:29:43.737  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.737  3266  3326 I jxcore-log: 
,03-31 16:29:43.738  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.738  3266  3326 I jxcore-log: 
,03-31 16:29:43.740  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.740  3266  3326 I jxcore-log: 
,03-31 16:29:43.741  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.741  3266  3326 I jxcore-log: 
,03-31 16:29:43.742  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.742  3266  3326 I jxcore-log: 
,03-31 16:29:43.744  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.744  3266  3326 I jxcore-log: 
,03-31 16:29:43.745  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.745  3266  3326 I jxcore-log: 
,03-31 16:29:43.747  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.747  3266  3326 I jxcore-log: 
,03-31 16:29:43.749  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.749  3266  3326 I jxcore-log: 
03-31 16:29:43.750  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.750  3266  3326 I jxcore-log: 
,03-31 16:29:43.752  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.752  3266  3326 I jxcore-log: 
,03-31 16:29:43.754  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.754  3266  3326 I jxcore-log: 
,03-31 16:29:43.755  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.755  3266  3326 I jxcore-log: 
,03-31 16:29:43.757  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.757  3266  3326 I jxcore-log: 
,03-31 16:29:43.764  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.764  3266  3326 I jxcore-log: 
,03-31 16:29:43.766  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.766  3266  3326 I jxcore-log: 
,03-31 16:29:43.768  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.768  3266  3326 I jxcore-log: 
,03-31 16:29:43.770  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.770  3266  3326 I jxcore-log: 
,03-31 16:29:43.771  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.771  3266  3326 I jxcore-log: 
,03-31 16:29:43.773  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.773  3266  3326 I jxcore-log: 
,03-31 16:29:43.774  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.774  3266  3326 I jxcore-log: 
,03-31 16:29:43.775  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.775  3266  3326 I jxcore-log: 
,03-31 16:29:43.776  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.776  3266  3326 I jxcore-log: 
,03-31 16:29:43.778  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.778  3266  3326 I jxcore-log: 
,03-31 16:29:43.781  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.781  3266  3326 I jxcore-log: 
,03-31 16:29:43.783  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.783  3266  3326 I jxcore-log: 
,03-31 16:29:43.784  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.784  3266  3326 I jxcore-log: 
,03-31 16:29:43.786  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.786  3266  3326 I jxcore-log: 
,03-31 16:29:43.787  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.787  3266  3326 I jxcore-log: 
,03-31 16:29:43.788  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.788  3266  3326 I jxcore-log: 
,03-31 16:29:43.790  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.790  3266  3326 I jxcore-log: 
,03-31 16:29:43.791  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.791  3266  3326 I jxcore-log: 
,03-31 16:29:43.793  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.793  3266  3326 I jxcore-log: 
,03-31 16:29:43.795  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.795  3266  3326 I jxcore-log: 
,03-31 16:29:43.796  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.796  3266  3326 I jxcore-log: 
,03-31 16:29:43.798  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.798  3266  3326 I jxcore-log: 
,03-31 16:29:43.799  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.799  3266  3326 I jxcore-log: 
,03-31 16:29:43.801  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.801  3266  3326 I jxcore-log: 
,03-31 16:29:43.802  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.802  3266  3326 I jxcore-log: 
,03-31 16:29:43.803  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.803  3266  3326 I jxcore-log: 
,03-31 16:29:43.805  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.805  3266  3326 I jxcore-log: 
,03-31 16:29:43.807  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.807  3266  3326 I jxcore-log: 
,03-31 16:29:43.808  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.808  3266  3326 I jxcore-log: 
,03-31 16:29:43.810  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.810  3266  3326 I jxcore-log: 
03-31 16:29:43.811  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.811  3266  3326 I jxcore-log: 
,03-31 16:29:43.813  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.813  3266  3326 I jxcore-log: 
,03-31 16:29:43.814  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:43.814  3266  3326 I jxcore-log: 
,03-31 16:29:43.815  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:43.815  3266  3326 I jxcore-log: 
,03-31 16:29:43.891  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.891  3266  3326 I jxcore-log: 
,03-31 16:29:43.893  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.893  3266  3326 I jxcore-log: 
,03-31 16:29:43.894  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.894  3266  3326 I jxcore-log: 
,03-31 16:29:43.896  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.896  3266  3326 I jxcore-log: 
,03-31 16:29:43.897  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.897  3266  3326 I jxcore-log: 
,03-31 16:29:43.899  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.899  3266  3326 I jxcore-log: 
,03-31 16:29:43.900  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.900  3266  3326 I jxcore-log: 
,03-31 16:29:43.901  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.901  3266  3326 I jxcore-log: 
,03-31 16:29:43.902  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.902  3266  3326 I jxcore-log: 
03-31 16:29:43.903  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.903  3266  3326 I jxcore-log: 
,03-31 16:29:43.906  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 16:29:43.906  3266  3326 I jxcore-log: 
03-31 16:29:43.907  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.907  3266  3326 I jxcore-log: 
,03-31 16:29:43.908  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.908  3266  3326 I jxcore-log: 
,03-31 16:29:43.908  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.908  3266  3326 I jxcore-log: 
03-31 16:29:43.910  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.910  3266  3326 I jxcore-log: 
,03-31 16:29:43.911  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.911  3266  3326 I jxcore-log: 
03-31 16:29:43.912  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.912  3266  3326 I jxcore-log: 
,03-31 16:29:43.913  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.913  3266  3326 I jxcore-log: 
,03-31 16:29:43.914  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.914  3266  3326 I jxcore-log: 
03-31 16:29:43.915  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.915  3266  3326 I jxcore-log: 
,03-31 16:29:43.916  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.916  3266  3326 I jxcore-log: 
,03-31 16:29:43.917  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.917  3266  3326 I jxcore-log: 
03-31 16:29:43.918  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.918  3266  3326 I jxcore-log: 
,03-31 16:29:43.919  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.919  3266  3326 I jxcore-log: 
,03-31 16:29:43.921  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.921  3266  3326 I jxcore-log: 
03-31 16:29:43.922  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.922  3266  3326 I jxcore-log: 
,03-31 16:29:43.923  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.923  3266  3326 I jxcore-log: 
,03-31 16:29:43.924  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.924  3266  3326 I jxcore-log: 
03-31 16:29:43.925  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.925  3266  3326 I jxcore-log: 
,03-31 16:29:43.926  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.926  3266  3326 I jxcore-log: 
,03-31 16:29:43.928  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.928  3266  3326 I jxcore-log: 
03-31 16:29:43.929  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.929  3266  3326 I jxcore-log: 
,03-31 16:29:43.930  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.930  3266  3326 I jxcore-log: 
,03-31 16:29:43.930  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.930  3266  3326 I jxcore-log: 
03-31 16:29:43.932  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.932  3266  3326 I jxcore-log: 
,03-31 16:29:43.933  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.933  3266  3326 I jxcore-log: 
,03-31 16:29:43.934  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.934  3266  3326 I jxcore-log: 
03-31 16:29:43.935  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.935  3266  3326 I jxcore-log: 
,03-31 16:29:43.936  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.936  3266  3326 I jxcore-log: 
,03-31 16:29:43.937  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.937  3266  3326 I jxcore-log: 
03-31 16:29:43.938  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.938  3266  3326 I jxcore-log: 
03-31 16:29:43.939  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.939  3266  3326 I jxcore-log: 
,03-31 16:29:43.940  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.940  3266  3326 I jxcore-log: 
03-31 16:29:43.940  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.940  3266  3326 I jxcore-log: 
,03-31 16:29:43.942  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.942  3266  3326 I jxcore-log: 
,03-31 16:29:43.943  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.943  3266  3326 I jxcore-log: 
,03-31 16:29:43.944  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.944  3266  3326 I jxcore-log: 
,03-31 16:29:43.946  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.946  3266  3326 I jxcore-log: 
,03-31 16:29:43.947  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:43.947  3266  3326 I jxcore-log: 
,03-31 16:29:43.948  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:43.948  3266  3326 I jxcore-log: 
,03-31 16:29:43.952  3266  3326 I jxcore-log: ok 28 native server is nulled out
03-31 16:29:43.952  3266  3326 I jxcore-log: 
,03-31 16:29:43.952  3266  3326 I jxcore-log: ok 29 native server should be closed
03-31 16:29:43.952  3266  3326 I jxcore-log: 
,03-31 16:29:43.952  3266  3326 I jxcore-log: ok 30 incoming has been removed
03-31 16:29:43.952  3266  3326 I jxcore-log: 
03-31 16:29:43.954  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.954  3266  3326 I jxcore-log: 
,03-31 16:29:43.955  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.955  3266  3326 I jxcore-log: 
,03-31 16:29:43.956  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.956  3266  3326 I jxcore-log: 
03-31 16:29:43.956  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.956  3266  3326 I jxcore-log: 
,03-31 16:29:43.957  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.957  3266  3326 I jxcore-log: 
03-31 16:29:43.957  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.957  3266  3326 I jxcore-log: 
,03-31 16:29:43.958  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.958  3266  3326 I jxcore-log: 
03-31 16:29:43.958  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.958  3266  3326 I jxcore-log: 
,03-31 16:29:43.959  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.959  3266  3326 I jxcore-log: 
03-31 16:29:43.959  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:43.959  3266  3326 I jxcore-log: 
,03-31 16:29:44.061  3266  3326 I jxcore-log: # teardown
03-31 16:29:44.061  3266  3326 I jxcore-log: 
,03-31 16:29:44.637  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 16:29:44.638  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:29:44.638  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:29:44.638  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:44.652  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:44.699  3090  3812 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 16:29:44.699  3090  3812 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jdm.a(PG:82)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jcs.o(PG:406)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jcn.a(PG:1379)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jcs.i(PG:143)
03-31 16:29:44.699  3090  3812 E HttpOperation: ,	at blb.a(PG:3937)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at czp.a(PG:18188)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at czp.a(PG:9081)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at czq.run(PG:1686)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,03-31 16:29:44.699  3090  3812 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:44.699  3090  3812 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jdj.a(PG:4091)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jdj.a(PG:1125)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jdm.a(PG:77)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	... 12 more
,03-31 16:29:44.699  3090  3812 E HttpOperation: Caused by: faj: BadAuthentication
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at fal.a(PG:38)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	at jdj.a(PG:4089)
03-31 16:29:44.699  3090  3812 E HttpOperation: 	... 14 more
,03-31 16:29:44.764  1131  1148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 16:29:44.765  1131  1148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 16:29:44.765  1131  1148 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 16:29:44.765  1131  1148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:29:44.772  1131  1148 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:29:44.801  3090  3812 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 16:29:44.801  3090  3812 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jdm.a(PG:82)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jcs.o(PG:406)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jcn.a(PG:1379)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jcs.i(PG:143)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at hec.a(PG:42)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at hee.a(PG:102)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at czr.a(PG:65)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at kka.a(PG:108)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at czp.a(PG:19176)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at czp.a(PG:9081)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at czq.run(PG:1686)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:44.801  3090  3812 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jdj.a(PG:4091)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jdj.a(PG:1125)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jdm.a(PG:77)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	... 15 more
03-31 16:29:44.801  3090  3812 E HttpOperation: Caused by: faj: BadAuthentication
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at fal.a(PG:38)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	at jdj.a(PG:4089)
03-31 16:29:44.801  3090  3812 E HttpOperation: 	... 17 more
03-31 16:29:44.803  3090  3812 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 16:29:44.803  3090  3812 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at hec.a(PG:42)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at hee.a(PG:102)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at czr.a(PG:65)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at kka.a(PG:108)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	... 15 more
03-31 16:29:44.803  3090  3812 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at fal.a(PG:38)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 16:29:44.803  3090  3812 E ExperimentLoader: 	... 17 more
,03-31 16:29:44.964   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 200112, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 16:29:45.119  2164  2229 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 16:29:45.485  3266  3326 I jxcore-log: # setup
03-31 16:29:45.485  3266  3326 I jxcore-log: 
,03-31 16:29:46.948  3266  3326 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
,03-31 16:29:46.948  3266  3326 I jxcore-log: 
,03-31 16:29:49.022  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:49.022  3266  3326 I jxcore-log: 
,03-31 16:29:49.027  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 45635
03-31 16:29:49.027  3266  3326 I jxcore-log: 
,03-31 16:29:49.033  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:29:49.033  3266  3326 I jxcore-log: 
,03-31 16:29:49.034  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:49.034  3266  3326 I jxcore-log: 
,03-31 16:29:49.035  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:29:49.035  3266  3326 I jxcore-log: 
,03-31 16:29:49.043  3266  3326 I jxcore-log: ok 31 we should not have gotten an error
03-31 16:29:49.043  3266  3326 I jxcore-log: 
,03-31 16:29:49.046  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 16:29:49.046  3266  3326 I jxcore-log: 
,03-31 16:29:49.049  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:49.049  3266  3326 I jxcore-log: 
,03-31 16:29:49.056  3266  3326 I jxcore-log: ok 32 Buffers are identical
03-31 16:29:49.056  3266  3326 I jxcore-log: 
,03-31 16:29:49.056  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:49.056  3266  3326 I jxcore-log: 
,03-31 16:29:49.058  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:49.058  3266  3326 I jxcore-log: 
,03-31 16:29:49.069  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 16:29:49.069  3266  3326 I jxcore-log: 
,03-31 16:29:49.070  3266  3326 I jxcore-log: ok 33 server should be fine
03-31 16:29:49.070  3266  3326 I jxcore-log: 
03-31 16:29:49.071  3266  3326 I jxcore-log: ok 34 server should be open
03-31 16:29:49.071  3266  3326 I jxcore-log: 
,03-31 16:29:49.071  3266  3326 I jxcore-log: ok 35 incoming has been removed
03-31 16:29:49.071  3266  3326 I jxcore-log: 
,03-31 16:29:49.071  3266  3326 I jxcore-log: ok 36 The mux object should be closed
03-31 16:29:49.071  3266  3326 I jxcore-log: 
03-31 16:29:49.072  3266  3326 I jxcore-log: ok 37 The mux stream should be closed
03-31 16:29:49.072  3266  3326 I jxcore-log: 
,03-31 16:29:49.078  3266  3326 I jxcore-log: # teardown
03-31 16:29:49.078  3266  3326 I jxcore-log: 
,03-31 16:29:49.723  3266  3326 I jxcore-log: # setup
03-31 16:29:49.723  3266  3326 I jxcore-log: 
,03-31 16:29:49.832  3266  3326 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 16:29:49.832  3266  3326 I jxcore-log: 
,03-31 16:29:51.929  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:29:51.929  3266  3326 I jxcore-log: 
,03-31 16:29:51.938  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 48501
03-31 16:29:51.938  3266  3326 I jxcore-log: 
,03-31 16:29:51.947  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-31 16:29:51.947  3266  3326 I jxcore-log: 
03-31 16:29:51.950  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:29:51.950  3266  3326 I jxcore-log: 
,03-31 16:29:51.953  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
,03-31 16:29:51.953  3266  3326 I jxcore-log: 
,03-31 16:29:51.964  3266  3326 I jxcore-log: ok 38 we should not have gotten an error
,03-31 16:29:51.964  3266  3326 I jxcore-log: 
,03-31 16:29:51.968  3266  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-31 16:29:51.968  3266  3326 I jxcore-log: 
,03-31 16:29:51.971  3266  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 16:29:51.971  3266  3326 I jxcore-log: 
,03-31 16:29:51.978  3266  3326 I jxcore-log: ok 39 Buffers are identical
03-31 16:29:51.978  3266  3326 I jxcore-log: 
,03-31 16:29:51.982  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 16:29:51.982  3266  3326 I jxcore-log: 
,03-31 16:29:51.983  3266  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 16:29:51.983  3266  3326 I jxcore-log: 
,03-31 16:29:51.985  3266  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 16:29:51.985  3266  3326 I jxcore-log: 
,03-31 16:29:51.990  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-31 16:29:51.990  3266  3326 I jxcore-log: 
,03-31 16:29:51.991  3266  3326 I jxcore-log: ok 40 server should be fine
03-31 16:29:51.991  3266  3326 I jxcore-log: 
03-31 16:29:51.991  3266  3326 I jxcore-log: ok 41 server should be open
03-31 16:29:51.991  3266  3326 I jxcore-log: 
,03-31 16:29:51.992  3266  3326 I jxcore-log: ok 42 incoming has been removed
03-31 16:29:51.992  3266  3326 I jxcore-log: 
03-31 16:29:51.992  3266  3326 I jxcore-log: ok 43 The mux object should be closed
03-31 16:29:51.992  3266  3326 I jxcore-log: 
,03-31 16:29:51.993  3266  3326 I jxcore-log: ok 44 The mux stream should be closed
03-31 16:29:51.993  3266  3326 I jxcore-log: 
,03-31 16:29:52.001  3266  3326 I jxcore-log: # teardown
03-31 16:29:52.001  3266  3326 I jxcore-log: 
,03-31 16:29:57.231  3266  3326 I jxcore-log: # setup
03-31 16:29:57.231  3266  3326 I jxcore-log: 
,03-31 16:29:57.430  3266  3326 I jxcore-log: # 12. closeAll can close even when connections open
03-31 16:29:57.430  3266  3326 I jxcore-log: 
,03-31 16:29:58.091  3266  3326 I jxcore-log: ok 45 not possible to connect to the server anymore
03-31 16:29:58.091  3266  3326 I jxcore-log: 
03-31 16:29:58.096  3266  3326 I jxcore-log: # teardown
03-31 16:29:58.096  3266  3326 I jxcore-log: 
,03-31 16:29:58.272  3266  3326 I jxcore-log: # setup
03-31 16:29:58.272  3266  3326 I jxcore-log: 
,03-31 16:29:58.558  3266  3326 I jxcore-log: # 13. closeAll with promise
03-31 16:29:58.558  3266  3326 I jxcore-log: 
,03-31 16:29:58.729  3266  3326 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 16:29:58.729  3266  3326 I jxcore-log: 
,03-31 16:29:58.734  3266  3326 I jxcore-log: # teardown
03-31 16:29:58.734  3266  3326 I jxcore-log: 
,03-31 16:29:58.875  3266  3326 I jxcore-log: # setup
03-31 16:29:58.875  3266  3326 I jxcore-log: 
,03-31 16:29:59.004  3266  3326 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 16:29:59.004  3266  3326 I jxcore-log: 
,03-31 16:29:59.164  3266  3326 I jxcore-log: ok 47 Got the right error
03-31 16:29:59.164  3266  3326 I jxcore-log: 
03-31 16:29:59.165  3266  3326 I jxcore-log: # teardown
03-31 16:29:59.165  3266  3326 I jxcore-log: 
,03-31 16:29:59.347  3266  3326 I jxcore-log: # setup
03-31 16:29:59.347  3266  3326 I jxcore-log: 
,03-31 16:29:59.493  3266  3326 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-31 16:29:59.493  3266  3326 I jxcore-log: 
,03-31 16:29:59.647  3266  3326 I jxcore-log: # teardown
03-31 16:29:59.647  3266  3326 I jxcore-log: 
,03-31 16:29:59.826  3266  3326 I jxcore-log: # setup
03-31 16:29:59.826  3266  3326 I jxcore-log: 
,03-31 16:29:59.954  3266  3326 I jxcore-log: # 16. multiplex can send data
03-31 16:29:59.954  3266  3326 I jxcore-log: 
,03-31 16:30:00.104  3266  3326 I jxcore-log: ok 48 String should be length:200
03-31 16:30:00.104  3266  3326 I jxcore-log: 
,03-31 16:30:00.113  3266  3326 I jxcore-log: # teardown
03-31 16:30:00.113  3266  3326 I jxcore-log: 
,03-31 16:30:00.247  3266  3326 I jxcore-log: # setup
03-31 16:30:00.247  3266  3326 I jxcore-log: 
,03-31 16:30:00.377  3266  3326 I jxcore-log: # 17. enqueue and run in order
03-31 16:30:00.377  3266  3326 I jxcore-log: 
,03-31 16:30:00.615  3266  3326 I jxcore-log: ok 49 firstPromise setTimeout,
03-31 16:30:00.615  3266  3326 I jxcore-log: 
,03-31 16:30:00.619  3266  3326 I jxcore-log: ok 50 firstPromise result
03-31 16:30:00.619  3266  3326 I jxcore-log: 
,03-31 16:30:00.623  3266  3326 I jxcore-log: ok 51 firstPromise testValue
03-31 16:30:00.623  3266  3326 I jxcore-log: 
,03-31 16:30:00.727  3266  3326 I jxcore-log: ok 52 secondPromise setTimeout
03-31 16:30:00.727  3266  3326 I jxcore-log: 
,03-31 16:30:00.733  3266  3326 I jxcore-log: ok 53 secondPromise result
03-31 16:30:00.733  3266  3326 I jxcore-log: 
,03-31 16:30:00.734  3266  3326 I jxcore-log: ok 54 secondPromise testValue
03-31 16:30:00.734  3266  3326 I jxcore-log: 
,03-31 16:30:00.739  3266  3326 I jxcore-log: ok 55 thirdPromise in promise
03-31 16:30:00.739  3266  3326 I jxcore-log: 
,03-31 16:30:00.743  3266  3326 I jxcore-log: ok 56 thirdPromise result
03-31 16:30:00.743  3266  3326 I jxcore-log: 
,03-31 16:30:00.745  3266  3326 I jxcore-log: ok 57 thirdPromise testValue
03-31 16:30:00.745  3266  3326 I jxcore-log: 
,03-31 16:30:00.755  3266  3326 I jxcore-log: # teardown
03-31 16:30:00.755  3266  3326 I jxcore-log: 
,03-31 16:30:01.045  3266  3326 I jxcore-log: # setup
03-31 16:30:01.045  3266  3326 I jxcore-log: 
,03-31 16:30:01.123  3266  3326 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 16:30:01.123  3266  3326 I jxcore-log: 
,03-31 16:30:01.225  3266  3326 I jxcore-log: ok 58 thirdPromise - first to run,
03-31 16:30:01.225  3266  3326 I jxcore-log: 
03-31 16:30:01.226  3266  3326 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 16:30:01.226  3266  3326 I jxcore-log: 
03-31 16:30:01.226  3266  3326 I jxcore-log: ok 60 secondPromise - second to run
03-31 16:30:01.226  3266  3326 I jxcore-log: 
03-31 16:30:01.227  3266  3326 I jxcore-log: ok 61 secondPromise - in catch
03-31 16:30:01.227  3266  3326 I jxcore-log: 
03-31 16:30:01.227  3266  3326 I jxcore-log: ok 62 firstPromise - third to run
03-31 16:30:01.227  3266  3326 I jxcore-log: 
03-31 16:30:01.227  3266  3326 I jxcore-log: ok 63 firstPromise - in then
03-31 16:30:01.227  3266  3326 I jxcore-log: 
03-31 16:30:01.228  3266  3326 I jxcore-log: ok 64 testing promises
03-31 16:30:01.228  3266  3326 I jxcore-log: 
03-31 16:30:01.230  3266  3326 I jxcore-log: # teardown
03-31 16:30:01.230  3266  3326 I jxcore-log: 
,03-31 16:30:01.462  3266  3326 I jxcore-log: # setup
03-31 16:30:01.462  3266  3326 I jxcore-log: 
,03-31 16:30:01.610  3266  3326 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 16:30:01.610  3266  3326 I jxcore-log: 
,03-31 16:30:01.758  3266  3326 I jxcore-log: ok 65 fourth
03-31 16:30:01.758  3266  3326 I jxcore-log: ,
,03-31 16:30:01.762  3266  3326 I jxcore-log: ok 66 fourth
03-31 16:30:01.762  3266  3326 I jxcore-log: 
,03-31 16:30:01.763  3266  3326 I jxcore-log: ok 67 second
03-31 16:30:01.763  3266  3326 I jxcore-log: 
,03-31 16:30:01.764  3266  3326 I jxcore-log: ok 68 secondPromise - in then
03-31 16:30:01.764  3266  3326 I jxcore-log: 
,03-31 16:30:01.867  3266  3326 I jxcore-log: ok 69 first
03-31 16:30:01.867  3266  3326 I jxcore-log: 
03-31 16:30:01.870  3266  3326 I jxcore-log: ok 70 firstPromise - in catch
03-31 16:30:01.870  3266  3326 I jxcore-log: 
,03-31 16:30:01.872  3266  3326 I jxcore-log: ok 71 third
03-31 16:30:01.872  3266  3326 I jxcore-log: 
,03-31 16:30:01.875  3266  3326 I jxcore-log: ok 72 thirdPromise - in then
03-31 16:30:01.875  3266  3326 I jxcore-log: 
,03-31 16:30:01.877  3266  3326 I jxcore-log: ok 73 testingPromises
03-31 16:30:01.877  3266  3326 I jxcore-log: 
,03-31 16:30:01.889  3266  3326 I jxcore-log: # teardown
03-31 16:30:01.889  3266  3326 I jxcore-log: 
,03-31 16:30:02.012  3373  3816 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 16:30:02.027  3266  3326 I jxcore-log: # setup
03-31 16:30:02.027  3266  3326 I jxcore-log: 
,03-31 16:30:02.062  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 16:30:02.063  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:02.063  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:02.063  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:02.087  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:02.100  3373  3816 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 16:30:02.101  3373  3816 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 16:30:02.181  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:02.189  3266  3326 I jxcore-log: # 20. queues handled independently
,03-31 16:30:02.189  3266  3326 I jxcore-log: 
,03-31 16:30:02.222  1131  1883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 16:30:02.222  1131  1883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:02.222  1131  1883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:02.222  1131  1883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:02.228  1131  1883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 16:30:02.248  3701  3701 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 16:30:02.249  3701  3701 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 16:30:02.249  3701  3701 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-31 16:30:03.121  3266  3326 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 16:30:03.121  3266  3326 I jxcore-log: 
,03-31 16:30:03.126  3266  3326 I jxcore-log: # teardown
03-31 16:30:03.126  3266  3326 I jxcore-log: 
,03-31 16:30:03.214  3266  3326 I jxcore-log: # setup
03-31 16:30:03.214  3266  3326 I jxcore-log: 
,03-31 16:30:03.822  3266  3326 I jxcore-log: # 21. basic
03-31 16:30:03.822  3266  3326 I jxcore-log: 
,03-31 16:30:03.947  3266  3326 I jxcore-log: ok 75 sane
03-31 16:30:03.947  3266  3326 I jxcore-log: 
,03-31 16:30:03.953  3266  3326 I jxcore-log: # teardown
03-31 16:30:03.953  3266  3326 I jxcore-log: 
,03-31 16:30:04.140  3266  3326 I jxcore-log: # setup
03-31 16:30:04.140  3266  3326 I jxcore-log: 
,03-31 16:30:04.255  3266  3326 I jxcore-log: # 22. another
03-31 16:30:04.255  3266  3326 I jxcore-log: 
,03-31 16:30:04.362  3266  3326 I jxcore-log: ok 76 sane
03-31 16:30:04.362  3266  3326 I jxcore-log: 
,03-31 16:30:04.370  3266  3326 I jxcore-log: # teardown
03-31 16:30:04.370  3266  3326 I jxcore-log: 
,03-31 16:30:04.467  3266  3326 I jxcore-log: # setup
03-31 16:30:04.467  3266  3326 I jxcore-log: 
,03-31 16:30:04.633  3266  3326 I jxcore-log: # 23. can pass data in setup
03-31 16:30:04.633  3266  3326 I jxcore-log: 
,03-31 16:30:04.785  3266  3326 I jxcore-log: [{"uuid":"e53a4725-b258-4357-b9c9-4ce37336a0f4","data":"custom data"},{"uuid":"18d69230-3e98-40c1-aeb6-4768d8d99ac3","data":"custom data"},{"uuid":"225be878-d40d-41a8-b923-e9d5889e0944","data":"custom data"}]
03-31 16:30:04.785  3266  3326 I jxcore-log: 
,03-31 16:30:04.788  3266  3326 I jxcore-log: ok 77 test participant has uuid
03-31 16:30:04.788  3266  3326 I jxcore-log: 
,03-31 16:30:04.790  3266  3326 I jxcore-log: ok 78 participant data matches
03-31 16:30:04.790  3266  3326 I jxcore-log: 
,03-31 16:30:04.793  3266  3326 I jxcore-log: ok 79 test participant has uuid
03-31 16:30:04.793  3266  3326 I jxcore-log: 
03-31 16:30:04.793  3266  3326 I jxcore-log: ok 80 participant data matches
03-31 16:30:04.793  3266  3326 I jxcore-log: 
,03-31 16:30:04.793  3266  3326 I jxcore-log: ok 81 test participant has uuid
03-31 16:30:04.793  3266  3326 I jxcore-log: 
03-31 16:30:04.794  3266  3326 I jxcore-log: ok 82 participant data matches
03-31 16:30:04.794  3266  3326 I jxcore-log: 
03-31 16:30:04.794  3266  3326 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 16:30:04.794  3266  3326 I jxcore-log: 
03-31 16:30:04.796  3266  3326 I jxcore-log: # teardown
03-31 16:30:04.796  3266  3326 I jxcore-log: 
,03-31 16:30:04.907  3266  3326 I jxcore-log: # setup
03-31 16:30:04.907  3266  3326 I jxcore-log: 
,03-31 16:30:05.005  3266  3326 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 16:30:05.005  3266  3326 I jxcore-log: 
,03-31 16:30:05.113  3266  3326 I jxcore-log: ok 84 specific error should be returned
03-31 16:30:05.113  3266  3326 I jxcore-log: 
,03-31 16:30:05.114  3266  3326 I jxcore-log: # teardown
03-31 16:30:05.114  3266  3326 I jxcore-log: 
,03-31 16:30:05.226  3266  3326 I jxcore-log: ok 85 error should be null
03-31 16:30:05.226  3266  3326 I jxcore-log: 
,03-31 16:30:05.228  3266  3326 I jxcore-log: ok 86 error should be null
03-31 16:30:05.228  3266  3326 I jxcore-log: 
,03-31 16:30:05.234  3266  3326 I jxcore-log: # setup
03-31 16:30:05.234  3266  3326 I jxcore-log: 
,03-31 16:30:05.342  3266  3326 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-31 16:30:05.342  3266  3326 I jxcore-log: ,
,03-31 16:30:05.468  3266  3326 I jxcore-log: ok 87 specific error should be returned
03-31 16:30:05.468  3266  3326 I jxcore-log: 
,03-31 16:30:05.474  3266  3326 I jxcore-log: # teardown
03-31 16:30:05.474  3266  3326 I jxcore-log: 
,03-31 16:30:05.624  3266  3326 I jxcore-log: ok 88 error should be null
03-31 16:30:05.624  3266  3326 I jxcore-log: 
,03-31 16:30:05.626  3266  3326 I jxcore-log: ok 89 error should be null
03-31 16:30:05.626  3266  3326 I jxcore-log: 
,03-31 16:30:05.632  3266  3326 I jxcore-log: # setup
03-31 16:30:05.632  3266  3326 I jxcore-log: 
,03-31 16:30:05.759  3266  3326 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-31 16:30:05.759  3266  3326 I jxcore-log: 
,03-31 16:30:06.017  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:06.017  3266  3326 I jxcore-log: 
03-31 16:30:06.018  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 55380
03-31 16:30:06.018  3266  3326 I jxcore-log: 
03-31 16:30:06.021  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:06.022  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:06.022  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.026  3266  3326 I jxcore-log: ok 90 error should be null
03-31 16:30:06.026  3266  3326 I jxcore-log: 
,03-31 16:30:06.027  3266  3326 I jxcore-log: ok 91 error should be null
03-31 16:30:06.027  3266  3326 I jxcore-log: 
03-31 16:30:06.028  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:06.028  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:06.028  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:06.030  3266  3326 I jxcore-log: ok 92 error should be null
03-31 16:30:06.030  3266  3326 I jxcore-log: 
03-31 16:30:06.031  3266  3326 I jxcore-log: ok 93 error should be null
03-31 16:30:06.031  3266  3326 I jxcore-log: 
,03-31 16:30:06.036  3266  3326 I jxcore-log: # teardown
03-31 16:30:06.036  3266  3326 I jxcore-log: 
,03-31 16:30:06.230  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:06.230  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:06.230  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.235  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:06.235  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:06.235  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:06.240  3266  3326 I jxcore-log: ok 94 error should be null
03-31 16:30:06.240  3266  3326 I jxcore-log: 
,03-31 16:30:06.241  3266  3326 I jxcore-log: ok 95 error should be null
03-31 16:30:06.241  3266  3326 I jxcore-log: 
,03-31 16:30:06.247  3266  3326 I jxcore-log: # setup
03-31 16:30:06.247  3266  3326 I jxcore-log: 
,03-31 16:30:06.449  3266  3326 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 16:30:06.449  3266  3326 I jxcore-log: 
,03-31 16:30:06.653  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 16:30:06.653  3266  3326 I jxcore-log: 
03-31 16:30:06.655  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 59989
03-31 16:30:06.655  3266  3326 I jxcore-log: 
,03-31 16:30:06.666  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
03-31 16:30:06.666  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:06.666  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:06.666  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:06.666  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:06.666  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:06.675  3266  3326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 16:30:06.675   823  2591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:06.686  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-31 16:30:06.701  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 16:30:06.701  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:06.701  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:06.702  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:06.709  2164  2368 D BtGatt.GattService: registerClient() - UUID=aed9e293-20b0-4e78-bc1d-fcc3d906d957,
03-31 16:30:06.710  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=aed9e293-20b0-4e78-bc1d-fcc3d906d957, clientIf=5
03-31 16:30:06.710  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:06.712  2164  2186 D BtGatt.GattService: start scan with filters
,03-31 16:30:06.715  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:06.715  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:06.716  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:06.716  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-31 16:30:06.716  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:06.716  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 16:30:06.717  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:06.717  2164  2237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2be970dc
,03-31 16:30:06.719  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:06.719   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:06.722  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 16:30:06.722  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:06.723  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:06.723  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:06.723  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:06.724  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:06.730  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 16:30:06.730  3266  3326 I jxcore-log: 
03-31 16:30:06.731  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:06.731  3266  3326 I jxcore-log: 
,03-31 16:30:06.731  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 16:30:06.731  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:06.734  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 16:30:06.734  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:06.734  3266  3326 I jxcore-log: ok 96 error should be null
03-31 16:30:06.734  3266  3326 I jxcore-log: 
03-31 16:30:06.734  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:06.734  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-31 16:30:06.735  3266  3326 I jxcore-log: ok 97 error should be null
03-31 16:30:06.735  3266  3326 I jxcore-log: 
03-31 16:30:06.737  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:06.737  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:06.739  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 16:30:06.739  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:06.740  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-31 16:30:06.740  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:06.740  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:06.740  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:06.741  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:06.744  3266  3326 I jxcore-log: ok 98 error should be null
03-31 16:30:06.744  3266  3326 I jxcore-log: 
,03-31 16:30:06.744  3266  3326 I jxcore-log: ok 99 error should be null
03-31 16:30:06.744  3266  3326 I jxcore-log: 
03-31 16:30:06.749  3266  3326 I jxcore-log: # teardown
03-31 16:30:06.749  3266  3326 I jxcore-log: 
,03-31 16:30:07.018  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:07.019  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:07.019  3266  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:07.019  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:07.020  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-31 16:30:07.020  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:07.020  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:07.022  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:07.022  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:07.024  2164  2186 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:07.026  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:07.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:07.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:07.026  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 16:30:07.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:07.026  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:07.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:07.027  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:07.027  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:07.027  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:07.028  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:07.028  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:07.028  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:07.028  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:07.028  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:07.029  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:07.029  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:07.029  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:07.032  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 16:30:07.032  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:07.041  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:07.042  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 16:30:07.043  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:07.046  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:07.047   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:07.051  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:07.052  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:07.052  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:07.055  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:07.055  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:07.055  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:07.055  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:07.059  3266  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:07.059  3266  3326 I jxcore-log: 
,03-31 16:30:07.063  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:07.063  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:07.063  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:07.065  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:07.065  3266  3326 I jxcore-log: 
,03-31 16:30:07.067  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:07.067  3266  3326 I jxcore-log: 
,03-31 16:30:07.072  3266  3326 I jxcore-log: ok 100 error should be null
03-31 16:30:07.072  3266  3326 I jxcore-log: 
,03-31 16:30:07.072  3266  3326 I jxcore-log: ok 101 error should be null
03-31 16:30:07.072  3266  3326 I jxcore-log: 
,03-31 16:30:07.079  3266  3326 I jxcore-log: # setup
03-31 16:30:07.079  3266  3326 I jxcore-log: 
,03-31 16:30:07.188  3266  3326 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 16:30:07.188  3266  3326 I jxcore-log: 
,03-31 16:30:07.350  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 16:30:07.350  3266  3326 I jxcore-log: 
,03-31 16:30:07.355  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 48369
,03-31 16:30:07.355  3266  3326 I jxcore-log: 
,03-31 16:30:07.374  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 48369, start advertisements: true
,03-31 16:30:07.374  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:07.374  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:07.374  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:07.380  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:07.380  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:07.380  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:07.380  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:07.385  2164  2368 D BtGatt.GattService: registerClient() - UUID=7487912f-67b7-4578-93e9-2d21624c62d4
,03-31 16:30:07.386  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=7487912f-67b7-4578-93e9-2d21624c62d4, clientIf=5
03-31 16:30:07.386  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:07.387  2164  2186 D BtGatt.GattService: start scan with filters
,03-31 16:30:07.388  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:07.388  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:07.388  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:07.388  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:07.388  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:07.388  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:07.389  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:07.389  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:07.389  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 16:30:07.391  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:07.391  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:07.392  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:07.393  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:07.393  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:07.393  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:07.393  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:07.395  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:07.395  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:07.395  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:07.396  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:07.396  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:07.398  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:07.398  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:07.404  2164  2183 D BtGatt.GattService: registerClient() - UUID=4c140f5d-8494-440d-99dd-db79cc61eca6,
03-31 16:30:07.404  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=4c140f5d-8494-440d-99dd-db79cc61eca6, clientIf=6
03-31 16:30:07.405  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:07.410  2164  2236 D BtGatt.AdvertiseManager: message : 0,
,03-31 16:30:07.415  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 16:30:07.419  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-31 16:30:07.422  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-31 16:30:07.423  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-31 16:30:07.423  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:07.424   823  1341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:07.431  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-31 16:30:07.431  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:07.432  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:07.432  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:07.433  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 16:30:07.435  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 16:30:07.435  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:07.436  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:07.436  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:07.436  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:07.436  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 16:30:07.436  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
,03-31 16:30:07.437  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:07.437  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 16:30:07.437  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:07.437  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:07.437  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:07.437  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:07.437  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:07.437  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-31 16:30:07.437  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:07.442   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:07.444  3266  3819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-31 16:30:07.448  3266  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:07.455  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 16:30:07.455  3266  3326 I jxcore-log: 
,03-31 16:30:07.467  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 16:30:07.467  3266  3326 I jxcore-log: 
03-31 16:30:07.468  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:07.468  3266  3326 I jxcore-log: 
,03-31 16:30:07.470  3266  3326 I jxcore-log: ok 102 error should be null,
03-31 16:30:07.470  3266  3326 I jxcore-log: 
03-31 16:30:07.471  3266  3326 I jxcore-log: ok 103 error should be null
03-31 16:30:07.471  3266  3326 I jxcore-log: 
,03-31 16:30:07.479  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 48369, start advertisements: true,
03-31 16:30:07.479  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:07.480  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 16:30:07.480  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:07.480  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:07.488  3266  3326 I jxcore-log: ok 104 error should be null,
03-31 16:30:07.488  3266  3326 I jxcore-log: 
,03-31 16:30:07.489  3266  3326 I jxcore-log: ok 105 error should be null,
03-31 16:30:07.489  3266  3326 I jxcore-log: 
,03-31 16:30:07.496  3266  3326 I jxcore-log: # teardown,
03-31 16:30:07.496  3266  3326 I jxcore-log: 
,03-31 16:30:07.902  2164  2164 D BtGatt.ScanManager: awakened up at time 223611
,03-31 16:30:07.904  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:07.914  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-31 16:30:07.915  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:07.915  2164  2227 D BtGatt.GattService: current time is 223624249496
03-31 16:30:07.916  2164  2227 D BtGatt.GattService: Batch record : [-3, -30, -40, 105, -46, 71, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -67, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 16:30:07.917  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 16:30:07.920  2164  2227 D BtGatt.GattService: ScanRecord : []
03-31 16:30:07.921  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:07.932  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1,
03-31 16:30:07.934  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-31 16:30:07.934  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 16:30:07.936  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 16:30:07.945  3266  3326 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 16:30:07.945  3266  3326 I jxcore-log: 
,03-31 16:30:07.956  3266  3326 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 16:30:07.956  3266  3326 I jxcore-log: 
,03-31 16:30:07.964  3266  3326 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 16:30:07.964  3266  3326 I jxcore-log: 
,03-31 16:30:07.970  3266  3326 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 16:30:07.970  3266  3326 I jxcore-log: 
,03-31 16:30:08.532  1244  1516 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-31 16:30:08.532  1244  1516 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 16:30:08.571  1131  1131 I ConfigService: onCreate
,03-31 16:30:08.929  2164  2164 D BtGatt.ScanManager: awakened up at time 224638,
03-31 16:30:08.931  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:08.941  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-31 16:30:08.941  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:08.941  2164  2227 D BtGatt.GattService: current time is 224650878766
03-31 16:30:08.942  2164  2227 D BtGatt.GattService: Batch record : [-3, -30, -40, 105, -46, 71, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -67, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -28, -44, -106, -22, -38, 116, 0, -128, -103, 18, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0]
,03-31 16:30:08.943  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:08.943  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:08.944  2164  2227 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-31 16:30:08.950  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 16:30:08.951  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 16:30:09.675  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:09.676  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:09.676  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:09.676  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:09.676  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 16:30:09.677  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:09.677  3266  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:09.677  3266  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:09.677  3266  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 16:30:09.678  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:09.679  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:09.679  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:09.679  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-31 16:30:09.679  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:09.679  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:09.679  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:09.679  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 16:30:09.681  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:09.683  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:09.684  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:09.684  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:09.684  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:09.684  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:09.684  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:09.684  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 16:30:09.684  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:09.684  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:09.684  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:09.685  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:09.687  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:09.687  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:09.688  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:09.688  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:09.689  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:09.690  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:09.690  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:09.691  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:09.691  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:09.691  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:09.691  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:09.691  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:09.692  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:09.692  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:09.692  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:09.692  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:09.693  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:09.693  3266  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-31 16:30:09.693  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:09.694  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:09.694  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:09.695  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:09.697  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-31 16:30:09.697  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:09.697  2164  2227 D BtGatt.GattService: current time is 225406733089
03-31 16:30:09.698  2164  2227 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 16:30:09.698  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:09.703  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:09.703   823  1338 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:09.709  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:09.710  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:09.710  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:09.712  3266  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:09.712  3266  3326 I jxcore-log: 
03-31 16:30:09.714  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:09.714  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:09.714  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:09.714  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:09.714  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:09.714  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:09.717  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:09.717  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:09.717  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:09.719  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:09.719  3266  3326 I jxcore-log: 
,03-31 16:30:09.722  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:09.722  3266  3326 I jxcore-log: 
,03-31 16:30:09.724  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:09.724  3266  3326 I jxcore-log: 
,03-31 16:30:09.734  3266  3326 I jxcore-log: ok 106 error should be null
03-31 16:30:09.734  3266  3326 I jxcore-log: 
,03-31 16:30:09.735  3266  3326 I jxcore-log: ok 107 error should be null
03-31 16:30:09.735  3266  3326 I jxcore-log: 
,03-31 16:30:09.740  3266  3326 I jxcore-log: # setup
03-31 16:30:09.740  3266  3326 I jxcore-log: 
,03-31 16:30:09.996  3266  3326 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 16:30:09.996  3266  3326 I jxcore-log: 
,03-31 16:30:10.130  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:10.130  3266  3326 I jxcore-log: 
,03-31 16:30:10.133  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 56410
03-31 16:30:10.133  3266  3326 I jxcore-log: 
,03-31 16:30:10.138  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:10.138  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:10.138  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.142  3266  3326 I jxcore-log: ok 108 error should be null
03-31 16:30:10.142  3266  3326 I jxcore-log: 
03-31 16:30:10.142  3266  3326 I jxcore-log: ok 109 error should be null
03-31 16:30:10.142  3266  3326 I jxcore-log: 
,03-31 16:30:10.145  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:10.145  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:10.145  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.147  3266  3326 I jxcore-log: ok 110 error should be null
03-31 16:30:10.147  3266  3326 I jxcore-log: 
03-31 16:30:10.148  3266  3326 I jxcore-log: ok 111 error should be null
03-31 16:30:10.148  3266  3326 I jxcore-log: 
,03-31 16:30:10.153  3266  3326 I jxcore-log: # teardown
03-31 16:30:10.153  3266  3326 I jxcore-log: 
,03-31 16:30:10.344  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:10.344  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:10.344  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.346  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 16:30:10.346  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:10.346  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.353  3266  3326 I jxcore-log: ok 112 error should be null
,03-31 16:30:10.353  3266  3326 I jxcore-log: 
,03-31 16:30:10.354  3266  3326 I jxcore-log: ok 113 error should be null,
03-31 16:30:10.354  3266  3326 I jxcore-log: 
,03-31 16:30:10.359  3266  3326 I jxcore-log: # setup,
03-31 16:30:10.359  3266  3326 I jxcore-log: 
,03-31 16:30:10.499  3266  3326 I jxcore-log: # 30. #start should fail if called twice in a row
,03-31 16:30:10.499  3266  3326 I jxcore-log: 
,03-31 16:30:10.672  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server,
,03-31 16:30:10.672  3266  3326 I jxcore-log: ,
,03-31 16:30:10.674  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 49045
03-31 16:30:10.674  3266  3326 I jxcore-log: 
,03-31 16:30:10.676  3266  3326 I jxcore-log: ok 114 first call should succeed
03-31 16:30:10.676  3266  3326 I jxcore-log: 
03-31 16:30:10.677  3266  3326 I jxcore-log: ok 115 first call should succeed
03-31 16:30:10.677  3266  3326 I jxcore-log: 
03-31 16:30:10.679  3266  3326 I jxcore-log: ok 116 specific error should be returned
03-31 16:30:10.679  3266  3326 I jxcore-log: 
,03-31 16:30:10.681  3266  3326 I jxcore-log: # teardown
03-31 16:30:10.681  3266  3326 I jxcore-log: 
,03-31 16:30:10.812  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:10.812  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:10.813  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.819  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:10.819  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:10.819  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:10.827  3266  3326 I jxcore-log: ok 117 error should be null,
03-31 16:30:10.827  3266  3326 I jxcore-log: ,
03-31 16:30:10.827  3266  3326 I jxcore-log: ok 118 error should be null
03-31 16:30:10.827  3266  3326 I jxcore-log: 
,03-31 16:30:10.832  3266  3326 I jxcore-log: # setup
03-31 16:30:10.832  3266  3326 I jxcore-log: 
,03-31 16:30:10.951  3266  3326 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-31 16:30:10.951  3266  3326 I jxcore-log: 
,03-31 16:30:11.111  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 16:30:11.111  3266  3326 I jxcore-log: 
,03-31 16:30:11.114  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 45230
03-31 16:30:11.114  3266  3326 I jxcore-log: 
,03-31 16:30:11.121  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 48369, start advertisements: false
,03-31 16:30:11.121  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:11.121  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:11.121  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:11.124  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:11.124  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:11.124  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:11.128  2164  2186 D BtGatt.GattService: registerClient() - UUID=81c431ef-b6cd-4953-9f9e-a177a179a931
,03-31 16:30:11.128  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=81c431ef-b6cd-4953-9f9e-a177a179a931, clientIf=5
03-31 16:30:11.129  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:11.129  2164  2368 D BtGatt.GattService: start scan with filters
,03-31 16:30:11.130  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:11.130  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:11.130  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:11.130  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:11.131  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:11.131  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:11.131  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:11.131  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:11.131   823  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:11.134  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:11.134  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:11.134  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:11.134  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:11.134  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:11.135  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:11.139  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 16:30:11.139  3266  3326 I jxcore-log: 
03-31 16:30:11.140  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:11.140  3266  3326 I jxcore-log: 
,03-31 16:30:11.142  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:11.142  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:11.144  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 16:30:11.144  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:11.144  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 16:30:11.144  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:11.147  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 16:30:11.147  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:11.149  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:11.149  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:11.153  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 45230, start advertisements: true
,03-31 16:30:11.153  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:11.153  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 16:30:11.153  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:11.157  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:11.157  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-31 16:30:11.157  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:11.157  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,03-31 16:30:11.157  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:11.157  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:11.157  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:11.157  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:11.160  2164  2186 D BtGatt.GattService: registerClient() - UUID=168b7e96-8e91-4aba-bc63-b031926fc40b
03-31 16:30:11.161  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=168b7e96-8e91-4aba-bc63-b031926fc40b, clientIf=6
03-31 16:30:11.161  3266  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:11.162  2164  2236 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:11.165  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:11.168  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-31 16:30:11.170  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 16:30:11.171  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:11.171  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:11.171  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:11.171  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:11.172  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:11.172  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 16:30:11.172  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:11.173   823  1019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:11.175  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:11.175  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:11.175  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:11.175  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:11.175  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:11.175  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:11.176  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:11.176  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:11.176  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:11.176  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:11.176  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:11.176  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:11.176  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:11.177   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:11.178  3266  3821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:11.181  3266  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:11.184  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:11.184  3266  3326 I jxcore-log: 
,03-31 16:30:11.188  3266  3326 I jxcore-log: ok 119 called only once
03-31 16:30:11.188  3266  3326 I jxcore-log: 
,03-31 16:30:11.188  3266  3326 I jxcore-log: ok 120 discovery state matches
03-31 16:30:11.188  3266  3326 I jxcore-log: 
,03-31 16:30:11.188  3266  3326 I jxcore-log: ok 121 advertising state matches
03-31 16:30:11.188  3266  3326 I jxcore-log: 
,03-31 16:30:11.195  3266  3326 I jxcore-log: # teardown
03-31 16:30:11.195  3266  3326 I jxcore-log: 
,03-31 16:30:11.728  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:11.728  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:11.728  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 16:30:11.728  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:11.728  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:11.728  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:11.728  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:11.728  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:11.728  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:11.728  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:11.729  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:11.729  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:11.731  3266  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:11.731  3266  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:11.731  3266  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:11.733  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:11.735  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:11.736  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:11.736  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:11.736  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:11.736  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:11.736  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:11.736  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:11.736  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:11.737  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:11.737  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:11.737  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:11.740  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-31 16:30:11.741  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:11.741  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:11.741  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:11.742  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 16:30:11.744  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-31 16:30:11.744  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:11.744  2164  2227 D BtGatt.GattService: current time is 227453470380
03-31 16:30:11.744  2164  2227 D BtGatt.GattService: Batch record : [-104, 45, -117, -88, -22, 103, 1, -128, -80, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 16:30:11.745  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:11.746  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:11.746  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:11.746  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:11.749  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:11.750  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:11.750  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:11.750  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:11.750  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:11.750  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:11.750  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:11.750  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:11.751  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:11.752  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:11.752  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:11.753  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:11.753  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:11.753  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:11.763  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:11.764   823  1341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:11.767  3266  3326 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-31 16:30:11.767  3266  3326 I jxcore-log: 
03-31 16:30:11.768  3266  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:11.768  3266  3326 I jxcore-log: 
03-31 16:30:11.769  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:11.769  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:11.770  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:11.771  3266  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:11.771  3266  3326 I jxcore-log: 
,03-31 16:30:11.775  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:11.775  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:11.775  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:11.775  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:11.776  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:11.777  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:11.777  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:11.778  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:11.778  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:11.778  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:11.778  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:11.780  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:11.780  3266  3326 I jxcore-log: 
03-31 16:30:11.781  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:11.781  3266  3326 I jxcore-log: 
03-31 16:30:11.782  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:11.782  3266  3326 I jxcore-log: 
,03-31 16:30:11.785  3266  3326 I jxcore-log: ok 122 error should be null,
03-31 16:30:11.785  3266  3326 I jxcore-log: ,
,03-31 16:30:11.786  3266  3326 I jxcore-log: ok 123 error should be null
03-31 16:30:11.786  3266  3326 I jxcore-log: 
,03-31 16:30:11.791  3266  3326 I jxcore-log: # setup
03-31 16:30:11.791  3266  3326 I jxcore-log: 
,03-31 16:30:11.908  3266  3326 I jxcore-log: # 32. does not send duplicate availability changes
03-31 16:30:11.908  3266  3326 I jxcore-log: 
,03-31 16:30:12.084  3266  3326 I jxcore-log: ok 124 should be called once
03-31 16:30:12.084  3266  3326 I jxcore-log: 
,03-31 16:30:12.085  3266  3326 I jxcore-log: ok 125 should not have been called more than once
03-31 16:30:12.085  3266  3326 I jxcore-log: 
,03-31 16:30:12.088  3266  3326 I jxcore-log: # teardown
03-31 16:30:12.088  3266  3326 I jxcore-log: 
,03-31 16:30:12.202  3266  3326 I jxcore-log: ok 126 error should be null
03-31 16:30:12.202  3266  3326 I jxcore-log: 
,03-31 16:30:12.203  3266  3326 I jxcore-log: ok 127 error should be null,
03-31 16:30:12.203  3266  3326 I jxcore-log: 
,03-31 16:30:12.205  3266  3326 I jxcore-log: # setup
,03-31 16:30:12.205  3266  3326 I jxcore-log: 
,03-31 16:30:12.331  3266  3326 I jxcore-log: # 33. can get the network status,
03-31 16:30:12.331  3266  3326 I jxcore-log: 
,03-31 16:30:12.459  3266  3326 I jxcore-log: ok 128 network status should have certain non-empty properties
03-31 16:30:12.459  3266  3326 I jxcore-log: 
,03-31 16:30:12.463  3266  3326 I jxcore-log: # teardown
,03-31 16:30:12.463  3266  3326 I jxcore-log: 
,03-31 16:30:12.616  3266  3326 I jxcore-log: ok 129 error should be null,
03-31 16:30:12.616  3266  3326 I jxcore-log: 
03-31 16:30:12.618  3266  3326 I jxcore-log: ok 130 error should be null
03-31 16:30:12.618  3266  3326 I jxcore-log: 
,03-31 16:30:12.627  3266  3326 I jxcore-log: # setup,
03-31 16:30:12.627  3266  3326 I jxcore-log: 
,03-31 16:30:12.817  3266  3326 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 16:30:12.817  3266  3326 I jxcore-log: 
,03-31 16:30:12.995  3266  3326 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 16:30:12.995  3266  3326 I jxcore-log: 
,03-31 16:30:13.018  3266  3326 I jxcore-log: ok 131 host address should match
,03-31 16:30:13.018  3266  3326 I jxcore-log: 
03-31 16:30:13.019  3266  3326 I jxcore-log: ok 132 port should match
03-31 16:30:13.019  3266  3326 I jxcore-log: 
,03-31 16:30:13.660  1131  1131 I ConfigService: onDestroy
,03-31 16:30:14.464  3494  3822 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 16:30:14.517  3494  3824 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 16:30:14.545   823  1676 I art     : Explicit concurrent mark sweep GC freed 29234(1360KB) AllocSpace objects, 7(677KB) LOS objects, 32% free, 33MB/49MB, paused 2.034ms total 74.254ms
,03-31 16:30:14.589  1131  1883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 16:30:14.589  1131  1883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:14.589  1131  1883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:14.589  1131  1883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:14.592  1131  1883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:14.624  3446  3823 V KeepSync: Connecting to GoogleApiClient
,03-31 16:30:14.665  1131  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 16:30:14.665  1131  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:14.665  1131  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:14.665  1131  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:14.668  1131  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:14.677  1131  1149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 16:30:14.677  1131  1149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:14.677  1131  1149 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:14.677  1131  1149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:14.680  1131  1149 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:14.681  3494  3824 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 16:30:14.682  3494  3822 E BooksSync: Soft error
03-31 16:30:14.682  3494  3822 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 16:30:14.682  3494  3822 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 16:30:14.682  3494  3822 E BooksSync: Sync error
03-31 16:30:14.682  3494  3822 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 16:30:14.682  3494  3822 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 16:30:14.682  3494  3822 I BooksSync: Finished books sync
,03-31 16:30:14.691   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202426, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: Handling authorization failure
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 16:30:14.697  1779  3827 E ClientConnectionOperation: 	... 7 more
,03-31 16:30:14.699  3446  3823 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 16:30:14.703  3446  3823 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 16:30:14.707  3446  3823 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 16:30:14.707  3446  3823 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 16:30:14.767  1131  1148 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 16:30:14.767  1131  1148 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:14.767  1131  1148 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 16:30:14.768  1131  1148 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:14.773  1131  1148 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:14.812  3446  3823 E KeepSync: IOException
03-31 16:30:14.812  3446  3823 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 16:30:14.812  3446  3823 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 16:30:14.812  3446  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 16:30:14.812  3446  3823 E KeepSync: 	... 10 more
,03-31 16:30:14.812  3446  3823 W KeepSync: Sync result 2
,03-31 16:30:14.827   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202897, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 16:30:15.001  3266  3326 I jxcore-log: ok 133 host address should be null
03-31 16:30:15.001  3266  3326 I jxcore-log: 
,03-31 16:30:15.003  3266  3326 I jxcore-log: ok 134 port should should be null
03-31 16:30:15.003  3266  3326 I jxcore-log: 
,03-31 16:30:15.024  3266  3326 I jxcore-log: # teardown
03-31 16:30:15.024  3266  3326 I jxcore-log: 
,03-31 16:30:15.144  3266  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 16:30:15.144  3266  3326 I jxcore-log: 
,03-31 16:30:15.148  3266  3326 I jxcore-log: ok 135 error should be null
03-31 16:30:15.148  3266  3326 I jxcore-log: 
,03-31 16:30:15.148  3266  3326 I jxcore-log: ok 136 error should be null
03-31 16:30:15.148  3266  3326 I jxcore-log: 
03-31 16:30:15.150  3266  3326 I jxcore-log: # setup
03-31 16:30:15.150  3266  3326 I jxcore-log: 
,03-31 16:30:15.284  3266  3326 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 16:30:15.284  3266  3326 I jxcore-log: 
,03-31 16:30:15.410  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 45230, start advertisements: false
,03-31 16:30:15.411  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:15.412  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.412  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:15.417  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:15.417  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:15.417  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:15.420  2164  2368 D BtGatt.GattService: registerClient() - UUID=723a37cb-c743-4edb-9b27-6a1ff6c63776
03-31 16:30:15.421  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=723a37cb-c743-4edb-9b27-6a1ff6c63776, clientIf=5
03-31 16:30:15.421  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:15.422  2164  2183 D BtGatt.GattService: start scan with filters
,03-31 16:30:15.425  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:15.425  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:15.425  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:15.425  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:15.425  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:15.425  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:15.426  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:15.426  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:15.426   823  1341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:15.429  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:15.429  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:15.430  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 16:30:15.430  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:15.430  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:15.433  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:15.433  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:15.433  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:15.435  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:15.435  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:15.435  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:15.435  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:15.437  3266  3326 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-31 16:30:15.437  3266  3326 I jxcore-log: 
03-31 16:30:15.437  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:15.437  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:15.438  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:15.438  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:15.439  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:15.439  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:15.440  2164  2186 D BtGatt.GattService: stopScan() - queue size =1,
03-31 16:30:15.441  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:15.441  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:15.443  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:15.444  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:15.444  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:15.444  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:15.444  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:15.444  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:15.445  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:15.445  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:15.445  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:15.445  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:15.447  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:15.447  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:15.447  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:15.449  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:15.449  3266  3326 I jxcore-log: 
,03-31 16:30:15.451  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:15.451  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:15.451  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 16:30:15.451  3266  3326 I jxcore-log: 
,03-31 16:30:15.452  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:15.453  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:15.453  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:15.455  3266  3326 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 16:30:15.455  3266  3326 I jxcore-log: 
03-31 16:30:15.465  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:15.465  3266  3326 I jxcore-log: 
03-31 16:30:15.466  3266  3326 I jxcore-log: # teardown
03-31 16:30:15.466  3266  3326 I jxcore-log: 
,03-31 16:30:15.693  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:15.694  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:15.694  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:15.702  3266  3326 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:15.702  3266  3326 I jxcore-log: 
03-31 16:30:15.702  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:15.703  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:15.703  3266  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:15.703  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:15.703  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:15.703  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:15.703  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:15.703  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:15.704  3266  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:15.704  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:15.705  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:15.705  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:15.705  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-31 16:30:15.706  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:15.707  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:15.707  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:15.707  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:15.707  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-31 16:30:15.717  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:15.717   823  1341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:15.729  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:15.730  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:15.730  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:15.737  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 16:30:15.737  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-31 16:30:15.738  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:15.740  3266  3326 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:15.740  3266  3326 I jxcore-log: 
,03-31 16:30:15.747  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 16:30:15.747  3266  3326 I jxcore-log: 
03-31 16:30:15.749  3266  3326 I jxcore-log: # setup
03-31 16:30:15.749  3266  3326 I jxcore-log: 
,03-31 16:30:15.844  3266  3326 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
,03-31 16:30:15.844  3266  3326 I jxcore-log: 
,03-31 16:30:15.964  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 45230, start advertisements: false
03-31 16:30:15.965  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:15.965  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.965  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:15.970  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-31 16:30:15.970  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:15.970  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:15.975  2164  2368 D BtGatt.GattService: registerClient() - UUID=3abee6db-9ccd-4ac9-ad1a-dc5c0c59dbad,
03-31 16:30:15.976  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=3abee6db-9ccd-4ac9-ad1a-dc5c0c59dbad, clientIf=5
03-31 16:30:15.977  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:15.977  2164  2183 D BtGatt.GattService: start scan with filters
,03-31 16:30:15.978  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:15.978  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:15.978  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:15.978  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:15.978  2164  2237 D BtGatt.ScanManager: handling starting scan,
,03-31 16:30:15.979  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:15.979  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 16:30:15.979  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:15.979   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:15.982  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:15.982  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:15.984  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:15.984  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:15.984  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-31 16:30:15.984  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:15.984  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:15.984  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.984  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:15.984  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:15.984  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:15.985  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:15.987  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:15.987  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:15.989  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:15.989  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:15.990  3266  3326 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 16:30:15.990  3266  3326 I jxcore-log: 
,03-31 16:30:15.996  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 45230, start advertisements: false
,03-31 16:30:15.996  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:15.996  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:15.996  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:15.997  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:15.998  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:15.998  3266  3326 I jxcore-log: 
,03-31 16:30:16.000  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.000  3266  3326 I jxcore-log: 
,03-31 16:30:16.002  3266  3326 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 16:30:16.002  3266  3326 I jxcore-log: 
,03-31 16:30:16.009  3266  3326 I jxcore-log: # teardown
03-31 16:30:16.009  3266  3326 I jxcore-log: 
,03-31 16:30:16.252  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 16:30:16.252  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:16.253  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:16.253  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:16.257  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:16.260  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:16.261  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:16.261  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:16.262  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:16.262  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:16.263  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:16.263  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 16:30:16.263  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:16.264  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:16.265  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.265  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.265  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:16.266  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:16.266  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:16.266  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.266  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:16.268  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:16.268  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:16.273  3266  3326 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown,
03-31 16:30:16.273  3266  3326 I jxcore-log: 
03-31 16:30:16.273  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:16.273  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:16.273  3266  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:16.273  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:16.273  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:16.274  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:16.274  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:16.274  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:16.275  3266  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:16.275  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:16.276  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:16.276  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:16.276  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:16.277  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:16.277  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:16.277  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:16.277  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:16.277  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:16.279  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.279  3266  3326 I jxcore-log: 
,03-31 16:30:16.295  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:16.296   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:16.304  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 16:30:16.305  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:16.305  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:16.308  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 16:30:16.308  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:16.308  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.310  3266  3326 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:16.310  3266  3326 I jxcore-log: 
,03-31 16:30:16.316  3266  3326 I jxcore-log: # setup,
03-31 16:30:16.316  3266  3326 I jxcore-log: 
,03-31 16:30:16.317  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.317  3266  3326 I jxcore-log: 
,03-31 16:30:16.428  3266  3326 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening,
03-31 16:30:16.428  3266  3326 I jxcore-log: ,
,03-31 16:30:16.611  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
03-31 16:30:16.611  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:16.611  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:16.611  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:16.620  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-31 16:30:16.620  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:16.620  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:16.620  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:16.630  2164  2183 D BtGatt.GattService: registerClient() - UUID=469b8ef7-7a89-492b-b881-67bf5b029955
,03-31 16:30:16.631  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=469b8ef7-7a89-492b-b881-67bf5b029955, clientIf=5
03-31 16:30:16.632  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:16.633  2164  2186 D BtGatt.GattService: start scan with filters
,03-31 16:30:16.636  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:16.636  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:16.636  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:16.637  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:16.637  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:16.638  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:16.638  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:16.638  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:16.638  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:16.638  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:16.639  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:16.640  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:16.640  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:16.647  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 16:30:16.647  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:16.650  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:16.651  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:16.651  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:16.651  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:16.655  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 16:30:16.656  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:16.658  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:16.658  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:16.659  2164  2368 D BtGatt.GattService: registerClient() - UUID=2aa42828-6c38-4a4b-8f3e-ca261949bf52
,03-31 16:30:16.660  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=2aa42828-6c38-4a4b-8f3e-ca261949bf52, clientIf=6
,03-31 16:30:16.661  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:16.663  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:16.667  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:16.670  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:16.672  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:16.673  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:16.673  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:16.674   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:16.677  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 16:30:16.677  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:16.677  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:16.677  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:16.678  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:16.678  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:16.678  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:16.678  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:16.678  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:16.679  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:16.679  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:16.679  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:16.679  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 16:30:16.679   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:16.679  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:16.680  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:16.680  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:16.680  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:16.680  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:16.680  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.680  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 16:30:16.681  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:16.681  3266  3831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:16.682  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.682  3266  3326 I jxcore-log: 
03-31 16:30:16.683  3266  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:16.685  3266  3326 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-31 16:30:16.685  3266  3326 I jxcore-log: 
,03-31 16:30:16.686  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:16.686  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:16.686  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
03-31 16:30:16.686  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:16.686  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:16.687  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:16.687  3266  3831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 16:30:16.687  3266  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:16.687  3266  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:16.687  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:16.688  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:16.688  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:16.688  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:16.688  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:16.688  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:16.688  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:16.688  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 16:30:16.692  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:16.694  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:16.696  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:16.696  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 16:30:16.696  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:16.696  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:16.696  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:16.696  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-31 16:30:16.696  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:16.696  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:16.696  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:16.696  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:16.699  2164  2236 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:16.699  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 16:30:16.699  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:16.699  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:16.699  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:16.701  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:16.701  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:16.702  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:16.702  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:16.704  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:16.704  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:16.704  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:16.705  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:16.705  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-31 16:30:16.705  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:16.705  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:16.705  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:16.705  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:16.709  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:16.709  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:16.709  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:16.709  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:16.709  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:16.713  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:16.713  3266  3326 I jxcore-log: 
,03-31 16:30:16.714  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:16.715   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:16.715  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:16.715  3266  3326 I jxcore-log: 
03-31 16:30:16.720  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:16.721  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:16.721  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:16.724  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:16.724  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:16.724  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:16.724  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:16.724  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:16.724  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:16.725  3266  3326 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 16:30:16.725  3266  3326 I jxcore-log: 
,03-31 16:30:16.731  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:16.731  3266  3326 I jxcore-log: 
,03-31 16:30:16.732  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.732  3266  3326 I jxcore-log: 
,03-31 16:30:16.733  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:16.733  3266  3326 I jxcore-log: 
,03-31 16:30:16.735  3266  3326 I jxcore-log: # teardown
03-31 16:30:16.735  3266  3326 I jxcore-log: 
,03-31 16:30:17.099  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 16:30:17.099  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:17.099  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:17.105  3266  3326 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
,03-31 16:30:17.105  3266  3326 I jxcore-log: 
,03-31 16:30:17.106  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:17.106  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:17.106  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-31 16:30:17.109  3266  3326 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:17.109  3266  3326 I jxcore-log: 
,03-31 16:30:17.116  3266  3326 I jxcore-log: # setup
,03-31 16:30:17.116  3266  3326 I jxcore-log: 
,03-31 16:30:17.250  3266  3326 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 16:30:17.250  3266  3326 I jxcore-log: 
,03-31 16:30:17.409  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 16:30:17.409  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:17.409  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:17.409  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:17.417  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:17.417  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:17.417  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:17.417  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:17.425  2164  2186 D BtGatt.GattService: registerClient() - UUID=9c440c89-0da0-4ab9-a471-7985fd764fb6
03-31 16:30:17.426  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=9c440c89-0da0-4ab9-a471-7985fd764fb6, clientIf=5
,03-31 16:30:17.427  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:17.427  2164  2368 D BtGatt.GattService: start scan with filters
03-31 16:30:17.429  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:17.429  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:17.429  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:17.430  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:17.429  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:17.431  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:17.432  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:17.432  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:17.434  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 16:30:17.434  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:17.435  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:17.435  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:17.435  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-31 16:30:17.435  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:17.436  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:17.436  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:17.436  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:17.437  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:17.437  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:17.441  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 16:30:17.441  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 16:30:17.443  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:17.443  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:17.448  2164  2183 D BtGatt.GattService: registerClient() - UUID=02ad646d-f4da-4462-bc65-b030374953fd
03-31 16:30:17.449  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=02ad646d-f4da-4462-bc65-b030374953fd, clientIf=6,
03-31 16:30:17.450  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:17.453  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:17.462  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:17.467  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:17.471  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:17.472  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:17.472  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:17.473   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:17.479  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:17.479  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:17.480  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:17.480  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:17.482  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:17.484  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:17.484  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 16:30:17.484  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-31 16:30:17.485  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:17.485  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 16:30:17.485  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:17.485  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:17.485  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:17.486  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 16:30:17.486  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:17.486  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:17.486  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:17.486  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 16:30:17.486   823  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:17.486  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:17.487  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:17.487  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:17.489  3266  3832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:17.493  3266  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 16:30:17.495  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:17.495  3266  3326 I jxcore-log: 
03-31 16:30:17.498  3266  3326 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-31 16:30:17.498  3266  3326 I jxcore-log: 
,03-31 16:30:17.505  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-31 16:30:17.505  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:17.505  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:17.505  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:17.505  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:17.507  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:17.507  3266  3326 I jxcore-log: 
,03-31 16:30:17.508  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:17.508  3266  3326 I jxcore-log: 
,03-31 16:30:17.511  3266  3326 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 16:30:17.511  3266  3326 I jxcore-log: 
,03-31 16:30:17.516  3266  3326 I jxcore-log: # teardown
03-31 16:30:17.516  3266  3326 I jxcore-log: 
,03-31 16:30:17.947  2164  2164 D BtGatt.ScanManager: awakened up at time 233656
,03-31 16:30:17.949  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:17.960  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 16:30:17.960  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:17.960  2164  2227 D BtGatt.GattService: current time is 233669426940
03-31 16:30:17.960  2164  2227 D BtGatt.GattService: Batch record : [-55, 13, -15, -118, -70, 102, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 16:30:17.961  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:17.962  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:17.965  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1,
03-31 16:30:17.966  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 16:30:17.966  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 16:30:17.967  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 16:30:17.972  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-31 16:30:17.972  3266  3326 I jxcore-log: 
,03-31 16:30:17.976  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state,
03-31 16:30:17.976  3266  3326 I jxcore-log: 
,03-31 16:30:18.265  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:18.266  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:18.266  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 16:30:18.266  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:18.270  2164  2186 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:18.273  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-31 16:30:18.274  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:18.274  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:18.274  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:18.275  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-31 16:30:18.275  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:18.275  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:18.275  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:18.275  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:18.275  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:18.276  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:18.277  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:18.277  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:18.280  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:18.280  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:18.281  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:18.282  3266  3326 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:18.282  3266  3326 I jxcore-log: 
03-31 16:30:18.284  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:18.284  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:18.284  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:18.284  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:18.284  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:18.285  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-31 16:30:18.285  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:18.285  2164  2227 D BtGatt.GattService: current time is 233994603867
03-31 16:30:18.285  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-31 16:30:18.285  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:18.285  2164  2227 D BtGatt.GattService: Batch record : [-55, 13, -15, -118, -70, 102, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 16:30:18.285  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:18.285  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:18.286  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:18.286  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:18.286  3266  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 16:30:18.286  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 16:30:18.286  3266  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:18.286  3266  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
03-31 16:30:18.287  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:18.289  3266  3326 D BluetoothLeScanner: could not find callback wrapper
,03-31 16:30:18.290  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:18.290  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 16:30:18.292  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:18.293  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:18.297  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:18.297  2164  2227 D BtGatt.GattService: Client app is not null!,
,03-31 16:30:18.299  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:18.301  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:18.301  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:18.301  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:18.301  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:18.302  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
,03-31 16:30:18.302  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:18.302  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:18.302  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:18.303  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:18.303  3266  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-31 16:30:18.303  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:18.304  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:18.304  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:18.304  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:18.313  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:18.314  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:18.314  3266  3326 I jxcore-log: 
03-31 16:30:18.314   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:18.323  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:18.324  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:18.324  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:18.329  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:18.329  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 16:30:18.329  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:18.329  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:18.329  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:18.329  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:18.330  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:18.330  3266  3326 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:18.330  3266  3326 I jxcore-log: 
,03-31 16:30:18.339  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-31 16:30:18.339  3266  3326 I jxcore-log: 
,03-31 16:30:18.340  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:18.340  3266  3326 I jxcore-log: 
,03-31 16:30:18.343  3266  3326 I jxcore-log: # setup
,03-31 16:30:18.343  3266  3326 I jxcore-log: 
,03-31 16:30:18.862  3266  3326 I jxcore-log: # 39. peerAvailabilityChange is called
,03-31 16:30:18.862  3266  3326 I jxcore-log: 
,03-31 16:30:19.002  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 16:30:19.002  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:19.002  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:19.002  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:19.010  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:19.011  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:19.011  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:19.011  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:19.021  2164  2186 D BtGatt.GattService: registerClient() - UUID=13804f06-e6c8-4f25-a7fc-ff03e05922fa
,03-31 16:30:19.022  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=13804f06-e6c8-4f25-a7fc-ff03e05922fa, clientIf=5
03-31 16:30:19.022  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:19.023  2164  2183 D BtGatt.GattService: start scan with filters
,03-31 16:30:19.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:19.026  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:19.026  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:19.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:19.027  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:19.027  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:19.028  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:19.028  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:19.028  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:19.028  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 16:30:19.029  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:19.029  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:19.029  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:19.038  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:19.038  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:19.041  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-31 16:30:19.041  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:19.042  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan,
03-31 16:30:19.042  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:19.045  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 16:30:19.045  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:19.047  2164  2368 D BtGatt.GattService: registerClient() - UUID=64c3a909-7a91-42a4-88ed-ea0fd2a4c1b5
03-31 16:30:19.047  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:19.047  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:19.047  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=64c3a909-7a91-42a4-88ed-ea0fd2a4c1b5, clientIf=6
03-31 16:30:19.048  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:19.049  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:19.054  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:19.057  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:19.059  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:19.060  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:19.060  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:19.061   823  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:19.064  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:19.064  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:19.064  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:19.064  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:19.065  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:19.065  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:19.066  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:19.066  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:19.066  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:19.066  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:19.066  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:19.066  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:19.066  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:19.066  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:19.066  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:19.066  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:19.066  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:19.066  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:19.066  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:19.067  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:19.067  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:19.068   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:19.069  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:19.069  3266  3326 I jxcore-log: 
03-31 16:30:19.070  3266  3833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:19.070  3266  3326 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error,
03-31 16:30:19.070  3266  3326 I jxcore-log: 
,03-31 16:30:19.075  3266  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:19.075  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-31 16:30:19.075  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:19.075  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 16:30:19.076  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:19.076  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:19.085  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:19.085  3266  3326 I jxcore-log: 
,03-31 16:30:19.086  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:19.086  3266  3326 I jxcore-log: 
03-31 16:30:19.087  3266  3326 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 16:30:19.087  3266  3326 I jxcore-log: 
,03-31 16:30:20.053  2164  2164 D BtGatt.ScanManager: awakened up at time 235762
,03-31 16:30:20.056  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:20.066  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 16:30:20.066  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:20.067  2164  2227 D BtGatt.GattService: current time is 235776210272
,03-31 16:30:20.067  2164  2227 D BtGatt.GattService: Batch record : [115, -54, -38, 88, -36, 99, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 16:30:20.068  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 16:30:20.069  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:20.071  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-31 16:30:20.072  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 16:30:20.072  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 16:30:20.073  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 16:30:20.079  3266  3326 I jxcore-log: ok 155 peers must be an array
03-31 16:30:20.079  3266  3326 I jxcore-log: 
,03-31 16:30:20.099  3266  3326 I jxcore-log: ok 156 peers must not be zero-length,
03-31 16:30:20.099  3266  3326 I jxcore-log: 
03-31 16:30:20.100  3266  3326 I jxcore-log: ok 157 peer must have peerIdentifier
03-31 16:30:20.100  3266  3326 I jxcore-log: 
,03-31 16:30:20.100  3266  3326 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 16:30:20.100  3266  3326 I jxcore-log: 
03-31 16:30:20.101  3266  3326 I jxcore-log: ok 159 peer must have peerAvailable,
03-31 16:30:20.101  3266  3326 I jxcore-log: 
03-31 16:30:20.101  3266  3326 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 16:30:20.101  3266  3326 I jxcore-log: 
,03-31 16:30:20.107  3266  3326 I jxcore-log: # teardown,
03-31 16:30:20.107  3266  3326 I jxcore-log: 
,03-31 16:30:20.258  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:20.258  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 16:30:20.258  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:20.259  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:20.262  2164  2186 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:20.265  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:20.266  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:20.266  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:20.266  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 16:30:20.266  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:20.266  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:20.267  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:20.267  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:20.267  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:20.267  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:20.268  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:20.268  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:20.268  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:20.269  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:20.269  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:20.269  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:20.272  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 16:30:20.272  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:20.273  2164  2227 D BtGatt.GattService: current time is 235982003397
03-31 16:30:20.273  2164  2227 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 115, -54, -38, 88, -36, 99, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 16:30:20.273  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:20.274  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 16:30:20.276  3266  3326 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:20.276  3266  3326 I jxcore-log: 
03-31 16:30:20.278  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:20.278  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
03-31 16:30:20.278  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:20.278  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:20.278  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:20.280  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:20.280  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:20.280  3266  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:20.280  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:20.280  3266  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:20.280  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:20.280  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:20.280  3266  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 16:30:20.281  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:20.281  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:20.281  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-31 16:30:20.281  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:20.283  3266  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:20.283  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:20.283  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:20.286  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:20.286  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:20.289  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 16:30:20.289  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:20.291  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:20.291  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:20.291  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:20.291  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:20.292  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:20.292  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:20.292  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:20.292  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:20.292  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:20.293  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:20.293  3266  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 16:30:20.293  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:20.293  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:20.293  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:20.293  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:20.293  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:20.293  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:20.298  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:20.298  3266  3326 I jxcore-log: 
03-31 16:30:20.299  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:20.299   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:20.301  3266  3326 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:20.301  3266  3326 I jxcore-log: 
,03-31 16:30:20.306  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:20.307  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:20.307  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:20.310  3266  3326 I jxcore-log: # setup
03-31 16:30:20.310  3266  3326 I jxcore-log: ,
,03-31 16:30:20.312  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:20.312  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:20.315  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:20.315  3266  3326 I jxcore-log: 
,03-31 16:30:20.319  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:20.319  3266  3326 I jxcore-log: 
,03-31 16:30:20.397  3266  3326 I jxcore-log: # 40. Can connect to a remote peer
03-31 16:30:20.397  3266  3326 I jxcore-log: 
,03-31 16:30:20.524  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 56581, start advertisements: true
,03-31 16:30:20.524  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:20.524  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:20.525  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:20.528  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:20.528  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:20.528  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:20.528  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:20.532  2164  2186 D BtGatt.GattService: registerClient() - UUID=2a83c925-e0da-4715-9d42-8b826ddee1b5,
,03-31 16:30:20.532  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=2a83c925-e0da-4715-9d42-8b826ddee1b5, clientIf=5
,03-31 16:30:20.532  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:20.533  2164  2183 D BtGatt.GattService: start scan with filters
03-31 16:30:20.535  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:20.536  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:20.536  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:20.536  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:20.536  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:20.536  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:20.536  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:20.536  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 16:30:20.536  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:20.536  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:20.536  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:20.536  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:20.536  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:20.539  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:20.539  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:20.541  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:20.541  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:20.541  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:20.541  2164  2368 D BtGatt.GattService: registerClient() - UUID=c1122e2e-e5af-4a12-8e25-88f9d39f8ebf
03-31 16:30:20.541  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:20.542  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=c1122e2e-e5af-4a12-8e25-88f9d39f8ebf, clientIf=6,
03-31 16:30:20.542  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:20.544  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:20.544  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:20.544  2164  2236 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:20.545  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 16:30:20.546  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:20.548  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
03-31 16:30:20.551  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:20.553  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 16:30:20.554  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:20.554  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:20.555   823  1341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:20.558  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:20.558  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 16:30:20.558  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:20.558  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:20.559  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:20.559  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:20.559  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 16:30:20.559  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:20.560  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK,
03-31 16:30:20.560  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:20.560  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-31 16:30:20.560  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:20.560  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 16:30:20.560  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:20.560  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:20.560  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:20.561  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:20.561  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 16:30:20.561  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:20.561  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:20.561  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-31 16:30:20.562  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:20.562  3266  3326 I jxcore-log: 
03-31 16:30:20.563  3266  3326 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error,
03-31 16:30:20.563  3266  3326 I jxcore-log: 
03-31 16:30:20.564   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:20.567  3266  3834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:20.567  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 56581, start advertisements: false
03-31 16:30:20.567  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:20.567  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 16:30:20.567  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:20.568  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:20.570  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:20.570  3266  3326 I jxcore-log: 
,03-31 16:30:20.572  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:20.572  3266  3326 I jxcore-log: 
03-31 16:30:20.572  3266  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 16:30:20.574  3266  3326 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 16:30:20.574  3266  3326 I jxcore-log: 
,03-31 16:30:21.082  2164  2164 D BtGatt.ScanManager: awakened up at time 236791
,03-31 16:30:21.084  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:21.092  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-31 16:30:21.092  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:21.093  2164  2227 D BtGatt.GattService: current time is 236802110376
,03-31 16:30:21.093  2164  2227 D BtGatt.GattService: Batch record : [38, 24, -30, 89, -36, 81, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 16:30:21.093  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 16:30:21.094  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:21.096  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-31 16:30:21.097  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-31 16:30:21.097  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 16:30:21.098  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 16:30:21.109  3266  3326 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-31 16:30:21.109  3266  3326 I jxcore-log: 
,03-31 16:30:21.123  3266  3326 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0,
03-31 16:30:21.123  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:21.127  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0,
03-31 16:30:21.128  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-31 16:30:21.128  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 16:30:21.130  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0,
,03-31 16:30:21.131  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
,03-31 16:30:21.131  3266  3326 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-31 16:30:21.132  3266  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 351)
03-31 16:30:21.133  3266  3835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:21.136  3266  3326 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
,03-31 16:30:21.136  3266  3326 I jxcore-log: 
03-31 16:30:21.137  2164  2183 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 16:30:22.556  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:22.614  1131  1883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 16:30:22.614  1131  1883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 16:30:22.614  1131  1883 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:22.615  1131  1883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:22.623  1131  1883 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:22.654  3701  3701 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 16:30:22.655  3701  3701 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 16:30:22.655  3701  3701 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-31 16:30:25.133  2164  2238 W bt-btif : info:x10
03-31 16:30:25.133  2164  2227 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-31 16:30:25.134  2164  2227 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 16:30:25.262  2164  2238 W bt-sdp  : process_service_search_attr_rsp
,03-31 16:30:25.917  2164  2227 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-31 16:30:25.926  2164  2227 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
03-31 16:30:25.927  2164  2227 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 16:30:25.932  2164  2228 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-31 16:30:25.932  2164  2228 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 16:30:25.954  2164  2227 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-31 16:30:25.955  2164  2228 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-31 16:30:26.019   823   854 I ActivityManager: Start proc 3836:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-31 16:30:26.021  2164  2228 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-31 16:30:26.051  2164  2228 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 16:30:26.079  2164  2238 W bt-btif : new conn_srvc id:26, app_id:1
,03-31 16:30:26.079  2164  2238 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 16:30:26.079  2164  2238 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 16:30:26.079  3266  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-31 16:30:26.080  3266  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 351)
,03-31 16:30:26.082  3266  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 352)
03-31 16:30:26.082  3266  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 352)
03-31 16:30:26.082  3266  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 351)
03-31 16:30:26.082  3266  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 352)
,03-31 16:30:26.098  3266  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 352)
,03-31 16:30:26.103  3266  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:26.104  3266  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-31 16:30:26.104  3266  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
,03-31 16:30:26.106  3266  3266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:26.107  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:26.107  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 16:30:26.109  3266  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 352)
03-31 16:30:26.111  3266  3266 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-31 16:30:26.112  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 16:30:26.113  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:26.113  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:26.113  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:26.113  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:26.113  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:26.113  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:26.117  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:26.118  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:26.122  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:26.122  2164  2227 D BtGatt.GattService: Client app is not null!
,03-31 16:30:26.123  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:26.124  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:26.124  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:26.125  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:26.125  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:26.125  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:26.125  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 16:30:26.125  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.125  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.125  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:26.133  2164  2368 D BtGatt.GattService: registerClient() - UUID=bf3ee7c9-c02b-4af8-93ec-43b1b13e4baf
,03-31 16:30:26.134  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=bf3ee7c9-c02b-4af8-93ec-43b1b13e4baf, clientIf=6
03-31 16:30:26.134  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:26.136  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:26.141  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:26.141   823   858 D BluetoothManagerService: Message: 20
03-31 16:30:26.142   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c92c0b6:true
,03-31 16:30:26.145  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:26.148  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:26.149  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:26.151  2164  2368 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:26.153  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:26.153  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:26.153  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:26.153  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:26.153  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:26.153  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:26.154   823  1151 I ActivityManager: Killing 3559:com.android.chrome/u0a40 (adj 15): empty #17
03-31 16:30:26.153  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:26.155  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:26.155  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:26.155  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:26.157  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:26.157  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.157  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:26.159  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-31 16:30:26.159  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.160  2164  2227 D BtGatt.GattService: current time is 241868956364
03-31 16:30:26.160  2164  2227 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 43, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 24, -30, 89, -36, 81, 1, -128, -77, 45, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -100, 62, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:26.160  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:26.160  2164  2186 D BtGatt.GattService: registerClient() - UUID=837f326d-3939-4759-9fb7-e0f0b6789662
03-31 16:30:26.160  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:26.160  2164  2227 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:26.160  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=837f326d-3939-4759-9fb7-e0f0b6789662, clientIf=5
03-31 16:30:26.161  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:26.162  2164  2368 D BtGatt.GattService: start scan with filters
,03-31 16:30:26.164  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:26.164  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:26.164  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:26.167  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:26.167  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:26.169  2164  2236 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:26.170  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:26.170  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:26.170  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.171  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:26.171  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:26.173  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:26.173  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:26.174  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:26.174  2164  2227 D BtGatt.GattService: Client app is not null!
,03-31 16:30:26.175  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:26.176  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:26.176  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 16:30:26.176  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:26.176  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:26.176  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.176  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:26.176  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:26.177  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 16:30:26.177  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.177  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.177  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:26.182  2164  2186 D BtGatt.GattService: registerClient() - UUID=be74f0ca-7757-40e7-9898-88cf2fe28686
,03-31 16:30:26.182  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=be74f0ca-7757-40e7-9898-88cf2fe28686, clientIf=6
03-31 16:30:26.182  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:26.184  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:26.187  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:26.190  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:26.193  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:26.193  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:26.194  2164  2186 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:26.195  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:26.195  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:26.196  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:26.196  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:26.196  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:26.196  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 16:30:26.196  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.196  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:26.196  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:26.196  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:26.199  2164  2186 D BtGatt.GattService: registerClient() - UUID=b03f0e77-76b2-42db-a49d-b578a13c2232
03-31 16:30:26.199  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:26.199  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.199  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=b03f0e77-76b2-42db-a49d-b578a13c2232, clientIf=5
03-31 16:30:26.199  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:26.199  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:26.200  2164  2368 D BtGatt.GattService: start scan with filters
,03-31 16:30:26.200  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-31 16:30:26.200  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:26.200  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.200  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:26.200  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 16:30:26.201  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:26.201  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:26.201  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:26.201  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:26.201  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:26.201  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:26.203  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:26.204  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:26.204  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:26.206  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:26.206  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:26.207  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:26.207  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:26.207  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 16:30:26.207  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:26.207  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:26.207  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 16:30:26.207  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:26.207  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.208  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:26.208  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:26.208  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:26.208  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.209  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:26.209  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.210  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:26.210  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:26.211  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:26.211  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.212  2164  2183 D BtGatt.GattService: registerClient() - UUID=8a2eb759-9e48-4b01-90fe-6ae32990bc1c
03-31 16:30:26.212  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=8a2eb759-9e48-4b01-90fe-6ae32990bc1c, clientIf=6
03-31 16:30:26.212  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:26.212  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 16:30:26.212  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.213  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:26.216  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 16:30:26.218  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:26.221  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 16:30:26.221  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:26.223  2164  2368 D BtGatt.GattService: stopScan() - queue size =1,
,03-31 16:30:26.224  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:26.224  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:26.224  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:26.224  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:26.224  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:26.224  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 16:30:26.224  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.224  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:26.224  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:26.224  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:26.227  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:26.227  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.227  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:26.228  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:26.228  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:26.230  2164  2183 D BtGatt.GattService: registerClient() - UUID=91d50c3e-5b19-455e-9a84-70a0032afa64,
03-31 16:30:26.231  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=91d50c3e-5b19-455e-9a84-70a0032afa64, clientIf=5
03-31 16:30:26.231  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:26.232  2164  2368 D BtGatt.GattService: start scan with filters
03-31 16:30:26.232  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:26.232  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:26.232  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:26.233  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 16:30:26.233  3266  3266 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 16:30:26.233  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:26.233  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 16:30:26.233  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:26.233  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:26.233  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-31 16:30:26.233  3266  3856 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 353)
03-31 16:30:26.234  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:26.234  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.235  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 16:30:26.235  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.235  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:26.235  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:26.235  3266  3856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52166
,03-31 16:30:26.235  3266  3856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 16:30:26.236  3266  3856 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 52166 (peer ID: E0:DB:10:14:E2:C0)
03-31 16:30:26.236  3266  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-31 16:30:26.237  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:26.237  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.238  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:26.238  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:26.240  3266  3326 I jxcore-log: INFO testThaliMobileNative: 
03-31 16:30:26.240  3266  3326 I jxcore-log: 
03-31 16:30:26.241  3266  3326 I jxcore-log: ok 165 Must have listeningPort
03-31 16:30:26.241  3266  3326 I jxcore-log: 
,03-31 16:30:26.242  3266  3326 I jxcore-log: ok 166 listeningPort must be a number
03-31 16:30:26.242  3266  3326 I jxcore-log: 
03-31 16:30:26.242  3266  3326 I jxcore-log: ok 167 Connection must have clientPort
03-31 16:30:26.242  3266  3326 I jxcore-log: 
,03-31 16:30:26.243  3266  3326 I jxcore-log: ok 168 clientPort must be a number
03-31 16:30:26.243  3266  3326 I jxcore-log: 
03-31 16:30:26.243  3266  3326 I jxcore-log: ok 169 Connection must have serverPort
03-31 16:30:26.243  3266  3326 I jxcore-log: 
,03-31 16:30:26.244  3266  3326 I jxcore-log: ok 170 serverPort must be a number
03-31 16:30:26.244  3266  3326 I jxcore-log: 
,03-31 16:30:26.244  3266  3326 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 16:30:26.244  3266  3326 I jxcore-log: 
03-31 16:30:26.245  3266  3326 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-31 16:30:26.245  3266  3326 I jxcore-log: 
,03-31 16:30:26.251  3266  3326 I jxcore-log: # teardown
03-31 16:30:26.251  3266  3326 I jxcore-log: 
,03-31 16:30:26.362   823  1151 E libprocessgroup: failed to kill 1 processes for processgroup 3559
,03-31 16:30:26.405  2164  2164 D BtGatt.ScanManager: awakened up at time 242114
,03-31 16:30:26.407  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:26.411  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-31 16:30:26.411  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:26.411  2164  2227 D BtGatt.GattService: current time is 242120673707
,03-31 16:30:26.412  2164  2227 D BtGatt.GattService: Batch record : [38, 24, -30, 89, -36, 81, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -69, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-31 16:30:26.412  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:26.413  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 16:30:26.416  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 16:30:26.416  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 16:30:31.098  2164  2238 W bt-btif : dm_pm_timer expires
03-31 16:30:31.098  2164  2238 W bt-btif : dm_pm_timer expires 0
03-31 16:30:31.098  2164  2238 W bt-btif : proc dm_pm_timer expires
,03-31 16:30:31.135  2164  2225 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 16:30:31.157  2164  2365 W bt-btif : invalid rfc slot id: 10
,03-31 16:30:31.274  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:31.274  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 16:30:31.274  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 16:30:31.274  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 16:30:31.277  2164  2368 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:31.279  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:31.280  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:31.280  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:31.281  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:31.281  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:31.281  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:31.281  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:31.281  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:31.281  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 16:30:31.282  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:31.282  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:31.283  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:31.283  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:31.285  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:31.285  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:31.286  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:31.286  3266  3326 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:31.286  3266  3326 I jxcore-log: 
03-31 16:30:31.288  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:31.288  3266  3326 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:31.288  3266  3326 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 353)
03-31 16:30:31.288  3266  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 353)
03-31 16:30:31.289  3266  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:31.289  3266  3326 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 353)
03-31 16:30:31.289  3266  3326 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 353)
03-31 16:30:31.289  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 16:30:31.290  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:31.290  2164  2227 D BtGatt.GattService: current time is 246999237872
03-31 16:30:31.290  3266  3856 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 353)
03-31 16:30:31.290  2164  2227 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -70, 75, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 24, -30, 89, -36, 81, 1, -128, -80, 66, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 16:30:31.291  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:31.292  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:31.292  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:31.292  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:31.292  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:31.292  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 16:30:31.293  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:31.294  3266  3834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:31.294  3266  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:31.294  3266  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:31.294  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:31.295  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:31.295  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:31.296  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:31.296  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:31.296  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:31.296  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 16:30:31.296  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:31.298  3266  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:31.298  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:31.298  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:31.300  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:31.301  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:31.305  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 16:30:31.305  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:31.307  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:31.308  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:31.308  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:31.308  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:31.308  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:31.309  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:31.309  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:31.309  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:31.309  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:31.310  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:31.310  3266  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-31 16:30:31.310  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:31.311  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:31.311  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:31.311  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:31.311  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:31.311  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-31 16:30:31.314  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:31.314  3266  3326 I jxcore-log: 
03-31 16:30:31.316  3266  3326 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:31.316  3266  3326 I jxcore-log: ,
,03-31 16:30:31.319  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:31.319   823  1019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:31.322  3266  3326 I jxcore-log: # setup,
03-31 16:30:31.322  3266  3326 I jxcore-log: 
,03-31 16:30:31.328  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-31 16:30:31.329  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:31.330  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:31.334  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:31.334  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:31.336  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 16:30:31.336  3266  3326 I jxcore-log: 
03-31 16:30:31.336  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:31.336  3266  3326 I jxcore-log: 
,03-31 16:30:31.379  3266  3326 I jxcore-log: # 41. Can shift large amounts of data,
03-31 16:30:31.379  3266  3326 I jxcore-log: 
,03-31 16:30:31.669  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 59040, start advertisements: true
03-31 16:30:31.669  3266  3326 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:31.669  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:31.670  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:31.670  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:31.670  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:31.670  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:31.670  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:31.675  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 16:30:31.675  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:31.675  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:31.675  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:31.682  2164  2186 D BtGatt.GattService: registerClient() - UUID=b96c285d-095e-46ff-8f40-e877663b07d9
03-31 16:30:31.682  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=b96c285d-095e-46ff-8f40-e877663b07d9, clientIf=5
,03-31 16:30:31.683  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:31.683  2164  2183 D BtGatt.GattService: start scan with filters
,03-31 16:30:31.685  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 16:30:31.685  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:31.685  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:31.685  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:31.685  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:31.686  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:31.686  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:31.686  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:31.687  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:31.687  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:31.688  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:31.689  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:31.689  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:31.689  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:31.689  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:31.691  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:31.691  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:31.691  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:31.691  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:31.693  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:31.693  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:31.695  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:31.695  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:31.699  2164  2368 D BtGatt.GattService: registerClient() - UUID=35d75b24-71d3-40c9-829e-c38230ceb3a2
,03-31 16:30:31.699  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=35d75b24-71d3-40c9-829e-c38230ceb3a2, clientIf=6
03-31 16:30:31.700  3266  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:31.702  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:31.709  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:31.713  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:31.716  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:31.716  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:31.716  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:31.716   823  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:31.718  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:31.718  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:31.718  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 16:30:31.718  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:31.719  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 16:30:31.719  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 16:30:31.719  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:31.719  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:31.719  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:31.719  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 16:30:31.719  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:31.719  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:31.719  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:31.719  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:31.719  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:31.719  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:31.719  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:31.719  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:31.719  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:31.720  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:31.720  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:31.722   823  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:31.724  3266  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:31.724  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:31.724  3266  3326 I jxcore-log: 
03-31 16:30:31.726  3266  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:31.728  3266  3326 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-31 16:30:31.728  3266  3326 I jxcore-log: 
,03-31 16:30:31.751  2164  2229 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 16:30:31.752  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 59040, start advertisements: false
,03-31 16:30:31.752  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:31.752  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 16:30:31.752  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:31.753  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:31.754  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:31.754  3266  3326 I jxcore-log: 
03-31 16:30:31.754  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:31.754  3266  3326 I jxcore-log: 
03-31 16:30:31.755  3266  3326 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 16:30:31.755  3266  3326 I jxcore-log: 
,03-31 16:30:33.801  2164  2238 W bt-btif : new conn_srvc id:26, app_id:255,
03-31 16:30:33.802  3266  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-31 16:30:33.803  3266  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 355),
,03-31 16:30:33.805  3266  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:33.808   823  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:33.810  3266  3863 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 355)
,03-31 16:30:33.812  3266  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:33.814  3266  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:34.078  3266  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 355)
,03-31 16:30:34.082  3266  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:34.083  3266  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 355)
,03-31 16:30:34.083  3266  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 355
03-31 16:30:34.084  3266  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 355)
03-31 16:30:34.084  3266  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:34.086  3266  3266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:34.086  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:34.086  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-31 16:30:34.088  3266  3266 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 16:30:34.088  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-31 16:30:34.089  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:34.089  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:34.089  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:34.089  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:34.089  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:34.089  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:34.093  3266  3863 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 355)
,03-31 16:30:34.094  2164  2236 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:34.095  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 16:30:34.098  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 16:30:34.098  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:34.100  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:34.100  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:34.101  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:34.101  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:34.101  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:34.101  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 16:30:34.101  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:34.102  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.102  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.102  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-31 16:30:34.112  2164  2368 D BtGatt.GattService: registerClient() - UUID=3b910b12-57b9-44fe-8f39-f3fdc8ad49eb
03-31 16:30:34.112  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=3b910b12-57b9-44fe-8f39-f3fdc8ad49eb, clientIf=6
,03-31 16:30:34.113  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:34.114  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:34.119  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:34.123  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:34.126  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 16:30:34.127  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:34.130  2164  2368 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:34.131  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:34.132  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:34.132  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:34.132  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:34.132  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:34.132  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:34.132  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:34.132  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:34.132  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.132  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:34.135  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:34.135  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.135  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:34.138  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 16:30:34.138  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.138  2164  2227 D BtGatt.GattService: current time is 249847850788
03-31 16:30:34.138  2164  2227 D BtGatt.GattService: Batch record : [89, -14, 26, -103, 28, 91, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -55, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 16:30:34.139  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:34.139  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:34.139  2164  2186 D BtGatt.GattService: registerClient() - UUID=a9dd2704-6c53-46d9-a438-f52bad40cc05
03-31 16:30:34.139  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=a9dd2704-6c53-46d9-a438-f52bad40cc05, clientIf=5
,03-31 16:30:34.142  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:34.143  2164  2368 D BtGatt.GattService: start scan with filters
,03-31 16:30:34.144  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:34.144  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:34.145  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:34.149  2164  2236 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:34.150  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 16:30:34.153  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:34.154  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 16:30:34.154  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:34.155  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:34.155  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:34.156  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 16:30:34.156  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 16:30:34.156  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:34.156  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:34.156  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.156  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 16:30:34.156  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:34.156  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.156  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.156  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:34.158  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:34.158  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.158  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:34.158  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:34.160  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:34.160  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.162  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:34.162  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:34.172  2164  2183 D BtGatt.GattService: registerClient() - UUID=2d46b3e1-89aa-47ce-9975-577ac14c7c82
,03-31 16:30:34.172  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=2d46b3e1-89aa-47ce-9975-577ac14c7c82, clientIf=6
,03-31 16:30:34.174  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 16:30:34.175  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:34.180  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:34.182  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:34.185  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 16:30:34.185  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:34.187  2164  2186 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:34.188  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:34.189  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:34.189  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:34.189  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:34.189  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:34.189  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:34.189  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:34.190  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:34.190  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.190  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:34.193  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:34.193  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:34.193  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:34.194  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:34.194  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:34.195  2164  2183 D BtGatt.GattService: registerClient() - UUID=6dd71374-4f2e-4b0c-83a4-c5400ea46f9e
03-31 16:30:34.196  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=6dd71374-4f2e-4b0c-83a4-c5400ea46f9e, clientIf=5
03-31 16:30:34.196  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:34.196  2164  2186 D BtGatt.GattService: start scan with filters
,03-31 16:30:34.198  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:34.198  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 16:30:34.201  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:34.202  2164  2237 D BtGatt.ScanManager: handling starting scan,
03-31 16:30:34.202  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 16:30:34.205  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:34.205  2164  2227 D BtGatt.GattService: Client app is not null!
,03-31 16:30:34.207  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 16:30:34.207  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.207  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:34.208  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:34.208  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.209  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:34.209  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:34.209  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:34.209  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-31 16:30:34.210  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-31 16:30:34.210  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:34.210  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:34.211  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 16:30:34.211  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.211  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:34.212  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.213  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:34.213  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:34.213  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:34.213  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:34.218  2164  2368 D BtGatt.GattService: registerClient() - UUID=a8ba2d79-f85e-457e-abdc-d1e238e2d93b
,03-31 16:30:34.218  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=a8ba2d79-f85e-457e-abdc-d1e238e2d93b, clientIf=6
03-31 16:30:34.218  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:34.219  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:34.222  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:34.225  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:34.228  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:34.229  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:34.231  2164  2368 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:34.232  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:34.232  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:34.233  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 16:30:34.233  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:34.233  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.233  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:34.233  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:34.233  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:34.233  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-31 16:30:34.233  3266  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:34.235  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:34.235  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.236  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:34.237  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 16:30:34.237  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:34.237  2164  2186 D BtGatt.GattService: registerClient() - UUID=5189b527-4250-4435-bd3d-850d4522a2b2
03-31 16:30:34.237  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=5189b527-4250-4435-bd3d-850d4522a2b2, clientIf=5
03-31 16:30:34.237  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:34.240  2164  2183 D BtGatt.GattService: start scan with filters
03-31 16:30:34.241  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:34.241  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:34.241  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:34.242  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 16:30:34.242  3266  3266 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 16:30:34.242  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 16:30:34.243  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:34.243  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:34.243  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:34.243  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-31 16:30:34.243  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:34.243  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:34.243  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.243  3266  3864 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 356)
03-31 16:30:34.244  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 16:30:34.244  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.244  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:34.244  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:34.246  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
,03-31 16:30:34.246  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 16:30:34.248  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:34.248  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:34.249  3266  3864 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 59040
03-31 16:30:34.251  3266  3864 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-31 16:30:34.251  3266  3864 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:34.251  3266  3864 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:34.252  3266  3864 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 356)
03-31 16:30:34.252  3266  3864 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 356),
03-31 16:30:34.253  3266  3866 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 357, name: Sender)
03-31 16:30:34.254  3266  3867 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 358, name: Receiver)
03-31 16:30:34.254  3266  3326 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-31 16:30:34.254  3266  3326 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID E0:DB:10:14:E2:C0, but will connect anyway...
03-31 16:30:34.254  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:34.258  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-31 16:30:34.258  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-31 16:30:34.258  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-31 16:30:34.258  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
,03-31 16:30:34.258  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0,
03-31 16:30:34.259  3266  3326 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-31 16:30:34.260  3266  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 359)
03-31 16:30:34.260  3266  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:34.262  2164  2183 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 16:30:34.600  2164  2238 W bt-sdp  : process_service_search_attr_rsp
,03-31 16:30:35.248  2164  2238 W bt-btif : new conn_srvc id:26, app_id:1
,03-31 16:30:35.248  3266  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-31 16:30:35.249  3266  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 359)
,03-31 16:30:35.250  3266  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 360)
03-31 16:30:35.250  3266  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 360)
03-31 16:30:35.250  3266  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 359)
,03-31 16:30:35.252  3266  3869 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 360)
,03-31 16:30:35.513  3266  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 360)
,03-31 16:30:35.517  3266  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:35.517  3266  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-31 16:30:35.518  3266  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 359)
03-31 16:30:35.518  3266  3869 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 360)
03-31 16:30:35.518  3266  3266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 16:30:35.518  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:35.519  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
,03-31 16:30:35.520  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 16:30:35.520  3266  3266 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 16:30:35.522  3266  3870 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 361)
03-31 16:30:35.523  3266  3870 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41047
,03-31 16:30:35.523  3266  3870 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 16:30:35.523  3266  3870 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 41047 (peer ID: E0:DB:10:14:E2:C0)
03-31 16:30:35.524  3266  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-31 16:30:35.529  3266  3326 I jxcore-log: INFO testThaliMobileNative: 
03-31 16:30:35.529  3266  3326 I jxcore-log: 
,03-31 16:30:35.532  3266  3326 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 16:30:35.532  3266  3326 I jxcore-log: 
,03-31 16:30:35.539  3266  3870 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 41047
03-31 16:30:35.539  3266  3870 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,03-31 16:30:35.540  3266  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:35.540  3266  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 16:30:35.543  3266  3871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 362, name: Sender)
03-31 16:30:35.543  3266  3870 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 361)
03-31 16:30:35.543  3266  3870 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 361)
03-31 16:30:35.543  3266  3326 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-31 16:30:35.543  3266  3326 I jxcore-log: 
,03-31 16:30:35.549  3266  3872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 363, name: Receiver)
,03-31 16:30:35.684  3266  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
,03-31 16:30:35.684  3266  3326 I jxcore-log: 
,03-31 16:30:35.756  3266  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.756  3266  3326 I jxcore-log: 
,03-31 16:30:35.830  3266  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.830  3266  3326 I jxcore-log: 
,03-31 16:30:35.911  3266  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.911  3266  3326 I jxcore-log: 
,03-31 16:30:35.988  3266  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 16:30:35.988  3266  3326 I jxcore-log: 
,03-31 16:30:35.991  3266  3326 I jxcore-log: ok 177 received should match sent forward
03-31 16:30:35.991  3266  3326 I jxcore-log: 
,03-31 16:30:36.006  3266  3326 I jxcore-log: # teardown
03-31 16:30:36.006  3266  3326 I jxcore-log: 
,03-31 16:30:39.252  2164  2164 D BtGatt.ScanManager: awakened up at time 254961
,03-31 16:30:39.254  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:39.260  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-31 16:30:39.261  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:39.261  2164  2227 D BtGatt.GattService: current time is 254970551150
03-31 16:30:39.262  2164  2227 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -70, 72, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 89, -14, 26, -103, 28, 91, 1, -128, -78, 61, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -101, 83, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-31 16:30:39.262  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 16:30:39.263  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:39.263  2164  2227 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-31 16:30:39.266  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
03-31 16:30:39.267  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 16:30:39.267  3266  3266 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 16:30:41.007  2164  2164 D BtGatt.ScanManager: awakened up at time 256716
,03-31 16:30:41.010  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:41.018  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 16:30:41.018  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:41.447  2164  2238 W bt-btif : info:x10,
03-31 16:30:41.448  2164  2227 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-31 16:30:41.449  2164  2227 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 16:30:41.690  2164  2227 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,03-31 16:30:41.697  2164  2227 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-31 16:30:41.697  2164  2227 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 16:30:41.701  2164  2228 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-31 16:30:41.702  2164  2228 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 16:30:41.797  2164  2227 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-31 16:30:41.798  2164  2228 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 16:30:41.801  2164  2228 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 16:30:41.816  2164  2228 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 16:30:41.873  2164  2238 W bt-btif : new conn_srvc id:26, app_id:255
,03-31 16:30:41.873  2164  2238 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 16:30:41.873  2164  2238 W bt-btif : bta_dm_pm_ssr:2, lat:1200,
03-31 16:30:41.874  3266  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-31 16:30:41.875  3266  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 364)
03-31 16:30:41.876  3266  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:41.877   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:41.879  3266  3874 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 364)
,03-31 16:30:41.882  3266  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:41.887  3266  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:41.900  3266  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 364)
,03-31 16:30:41.904  3266  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-31 16:30:41.905  3266  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 364)
,03-31 16:30:41.905  3266  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 364
,03-31 16:30:41.905  3266  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 364)
03-31 16:30:41.905  3266  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-31 16:30:41.905  3266  3874 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 364)
03-31 16:30:41.906  3266  3266 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:41.906  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 16:30:41.907  3266  3266 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 16:30:41.908  3266  3266 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully,
03-31 16:30:41.909  3266  3266 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
03-31 16:30:41.911  3266  3875 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 365)
,03-31 16:30:41.919  3266  3875 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 59040
03-31 16:30:41.919  3266  3875 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 16:30:41.919  3266  3875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 16:30:41.920  3266  3875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 16:30:41.924  3266  3877 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Sender)
03-31 16:30:41.924  3266  3875 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 365)
03-31 16:30:41.924  3266  3875 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 365)
,03-31 16:30:41.929  3266  3878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 367, name: Receiver),
,03-31 16:30:42.034  2164  2238 E bt-btm  : tBTM_SEC_DEV:0xa2f55eb4 rs_disc_pending=1
,03-31 16:30:42.035  2164  2238 W bt-btif : bta_dm_check_av:0
03-31 16:30:42.035  2164  2227 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 16:30:42.305  3266  3866 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 357, thread name: Sender)
03-31 16:30:42.305  3266  3866 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 16:30:42.305  3266  3866 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-31 16:30:42.305  3266  3877 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 366, thread name: Sender)
03-31 16:30:42.305  3266  3866 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 356
03-31 16:30:42.305  3266  3877 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 16:30:42.305  3266  3866 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 356)
03-31 16:30:42.306  3266  3877 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-31 16:30:42.306  3266  3866 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:42.306  3266  3866 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 16:30:42.307  3266  3867 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 358, thread name: Receiver): bt socket closed, read return: -1
03-31 16:30:42.307  3266  3867 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 358, name: Receiver)
,03-31 16:30:42.308  3266  3866 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 358
03-31 16:30:42.308  3266  3866 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 16:30:42.308  3266  3866 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 357
03-31 16:30:42.308  3266  3866 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 356)
,03-31 16:30:42.310  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:42.310  3266  3866 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 356)
03-31 16:30:42.310  3266  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-31 16:30:42.310  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:42.310  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
03-31 16:30:42.310  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:42.310  3266  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 365
03-31 16:30:42.310  3266  3877 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 365)
,03-31 16:30:42.311  3266  3878 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 367, thread name: Receiver): bt socket closed, read return: -1
03-31 16:30:42.311  3266  3878 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 367, name: Receiver)
03-31 16:30:42.314  3266  3866 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 357, name: Sender)
03-31 16:30:42.315  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:42.316  3266  3877 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-31 16:30:42.316  3266  3877 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 16:30:42.316  3266  3877 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 367
03-31 16:30:42.316  3266  3877 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 16:30:42.316  3266  3877 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
03-31 16:30:42.317  3266  3877 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 365)
03-31 16:30:42.319  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:42.320  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:42.320  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:42.320  3266  3877 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 365)
03-31 16:30:42.320  3266  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 16:30:42.320  3266  3877 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Sender)
03-31 16:30:42.323  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:42.323  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:42.323  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:42.323  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:42.324  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:42.325  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:42.325  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 16:30:42.325  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:42.325  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:42.325  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:42.326  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:42.326  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:42.326  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:42.327  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 16:30:42.327  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:42.332  3266  3326 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 16:30:42.332  3266  3326 I jxcore-log: 
,03-31 16:30:42.335  3266  3326 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 16:30:42.335  3266  3326 I jxcore-log: 
03-31 16:30:42.337  3266  3326 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-31 16:30:42.337  3266  3326 I jxcore-log: 
03-31 16:30:42.338  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:42.338  3266  3326 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-31 16:30:42.339  3266  3326 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 361)
03-31 16:30:42.339  3266  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 361)
03-31 16:30:42.339  3266  3872 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Receiver): bt socket closed, read return: -1
03-31 16:30:42.339  3266  3872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 363, name: Receiver)
03-31 16:30:42.339  3266  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 16:30:42.339  3266  3326 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-31 16:30:42.339  3266  3326 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 363
03-31 16:30:42.339  3266  3326 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-31 16:30:42.339  3266  3326 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 362
03-31 16:30:42.339  3266  3326 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 361)
03-31 16:30:42.340  3266  3871 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 362, thread name: Sender): Socket closed
03-31 16:30:42.340  3266  3871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 362, name: Sender)
03-31 16:30:42.340  3266  3326 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 361)
03-31 16:30:42.340  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:42.340  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:42.340  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:42.341  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:42.341  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:42.342  3266  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:42.342  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:42.342  3266  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:42.342  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:42.342  3266  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:42.342  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:42.342  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:42.342  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:42.342  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 16:30:42.342  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:42.343  3266  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 16:30:42.343  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:42.343  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:42.344  2164  2236 D BtGatt.AdvertiseManager: message : 1
,03-31 16:30:42.345  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 16:30:42.347  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 16:30:42.347  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:42.347  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:42.348  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:42.348  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:42.348  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:42.348  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:42.348  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:42.348  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:42.348  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:42.348  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:42.349  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:42.349  3266  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 16:30:42.349  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:42.349  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:42.349  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:42.349  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:42.353  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:42.353  3266  3326 I jxcore-log: 
03-31 16:30:42.353  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:42.354   823  1019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:42.358  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-31 16:30:42.359  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:42.359  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:42.362  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 16:30:42.362  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:42.362  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:42.362  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:42.363  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:42.364  3266  3326 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 16:30:42.364  3266  3326 I jxcore-log: 
,03-31 16:30:42.371  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:42.371  3266  3326 I jxcore-log: 
,03-31 16:30:42.372  3266  3326 I jxcore-log: # setup
03-31 16:30:42.372  3266  3326 I jxcore-log: 
,03-31 16:30:42.374  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:42.374  3266  3326 I jxcore-log: 
,03-31 16:30:42.465  2164  2238 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,03-31 16:30:42.465  2164  2238 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-31 16:30:42.467  2164  2238 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,03-31 16:30:42.532  2164  2238 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-31 16:30:42.532  2164  2238 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 16:30:42.592  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:42.592  3266  3326 I jxcore-log: 
03-31 16:30:42.593  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:42.593  3266  3326 I jxcore-log: 
,03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:42.600  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:42.605  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:42.606  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:42.606  3266  3326 I jxcore-log: 
,03-31 16:30:42.608  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:42.608  3266  3326 I jxcore-log: 
,03-31 16:30:42.612  3266  3326 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-31 16:30:42.612  3266  3326 I jxcore-log: 
,03-31 16:30:42.614  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:42.614  3266  3326 I jxcore-log: 
,03-31 16:30:42.769  3266  3326 I jxcore-log: ok 180 specific error should be returned
03-31 16:30:42.769  3266  3326 I jxcore-log: 
,03-31 16:30:42.771  3266  3326 I jxcore-log: # teardown
03-31 16:30:42.771  3266  3326 I jxcore-log: 
,03-31 16:30:42.916  3266  3326 I jxcore-log: ok 181 must be stopped
03-31 16:30:42.916  3266  3326 I jxcore-log: 
,03-31 16:30:42.921  3266  3326 I jxcore-log: # setup
03-31 16:30:42.921  3266  3326 I jxcore-log: 
,03-31 16:30:42.975  1131  1131 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:43.024  1131  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 16:30:43.025  1131  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 16:30:43.025  1131  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 16:30:43.025  1131  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 16:30:43.033  1131  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:30:43.068  3701  3701 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 16:30:43.069  3701  3701 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 16:30:43.070  3701  3701 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-31 16:30:43.076  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:43.076  3266  3326 I jxcore-log: 
,03-31 16:30:43.078  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:43.078  3266  3326 I jxcore-log: 
,03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:43.088  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:43.093  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 16:30:43.096  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-31 16:30:43.096  3266  3326 I jxcore-log: 
,03-31 16:30:43.098  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 16:30:43.098  3266  3326 I jxcore-log: 
,03-31 16:30:43.103  3266  3326 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called,
03-31 16:30:43.103  3266  3326 I jxcore-log: 
,03-31 16:30:43.106  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:43.106  3266  3326 I jxcore-log: 
,03-31 16:30:43.262  3266  3326 I jxcore-log: ok 182 specific error should be returned
03-31 16:30:43.262  3266  3326 I jxcore-log: 
,03-31 16:30:43.264  3266  3326 I jxcore-log: # teardown
03-31 16:30:43.264  3266  3326 I jxcore-log: 
,03-31 16:30:43.396  3266  3326 I jxcore-log: ok 183 must be stopped
03-31 16:30:43.396  3266  3326 I jxcore-log: 
,03-31 16:30:43.402  3266  3326 I jxcore-log: # setup
03-31 16:30:43.402  3266  3326 I jxcore-log: 
,03-31 16:30:43.494  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:43.494  3266  3326 I jxcore-log: 
,03-31 16:30:43.499  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:43.499  3266  3326 I jxcore-log: 
,03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:43.508  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:43.511  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:43.512  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:43.512  3266  3326 I jxcore-log: 
,03-31 16:30:43.514  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:43.514  3266  3326 I jxcore-log: 
,03-31 16:30:43.517  3266  3326 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-31 16:30:43.517  3266  3326 I jxcore-log: 
03-31 16:30:43.518  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:43.518  3266  3326 I jxcore-log: 
,03-31 16:30:43.749  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:43.749  3266  3326 I jxcore-log: 
,03-31 16:30:43.751  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 58060
03-31 16:30:43.751  3266  3326 I jxcore-log: 
,03-31 16:30:43.754  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:43.754  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:43.754  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:43.756  3266  3326 I jxcore-log: ok 184 no errors
03-31 16:30:43.756  3266  3326 I jxcore-log: 
,03-31 16:30:43.757  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:43.757  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:43.757  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:43.759  3266  3326 I jxcore-log: ok 185 still no errors
03-31 16:30:43.759  3266  3326 I jxcore-log: 
,03-31 16:30:43.766  3266  3326 I jxcore-log: # teardown
03-31 16:30:43.766  3266  3326 I jxcore-log: 
,03-31 16:30:43.902  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:43.902  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:43.902  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:43.904  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:43.904  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:43.904  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:43.909  3266  3326 I jxcore-log: ok 186 must be stopped
03-31 16:30:43.909  3266  3326 I jxcore-log: 
,03-31 16:30:43.915  3266  3326 I jxcore-log: # setup
03-31 16:30:43.915  3266  3326 I jxcore-log: 
,03-31 16:30:44.049  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:44.049  3266  3326 I jxcore-log: 
,03-31 16:30:44.056  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:44.056  3266  3326 I jxcore-log: 
,03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:44.068  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:44.073  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:44.075  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:44.075  3266  3326 I jxcore-log: 
,03-31 16:30:44.077  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:44.077  3266  3326 I jxcore-log: 
,03-31 16:30:44.080  3266  3326 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 16:30:44.080  3266  3326 I jxcore-log: 
,03-31 16:30:44.082  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:44.082  3266  3326 I jxcore-log: 
,03-31 16:30:44.192  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:44.192  3266  3326 I jxcore-log: 
,03-31 16:30:44.195  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 53379
03-31 16:30:44.195  3266  3326 I jxcore-log: 
,03-31 16:30:44.200  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 59040, start advertisements: false
,03-31 16:30:44.200  3266  3326 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-31 16:30:44.200  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0,
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.203  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:44.203  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:44.203  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:44.213  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-31 16:30:44.213  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:44.213  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:44.221  2164  2368 D BtGatt.GattService: registerClient() - UUID=aba96752-3a1b-434c-b68f-30d5e147aa2c
,03-31 16:30:44.222  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=aba96752-3a1b-434c-b68f-30d5e147aa2c, clientIf=5
03-31 16:30:44.222  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 16:30:44.223  2164  2183 D BtGatt.GattService: start scan with filters
,03-31 16:30:44.225  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:44.225  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-31 16:30:44.225  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,03-31 16:30:44.225  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:44.225  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,03-31 16:30:44.226  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:44.227  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:44.227  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:44.227  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:44.227  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:44.227   823  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:44.229  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:44.229  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:44.229  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:44.229  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:44.232  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:44.232  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:44.232  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:44.232  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:44.232  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:44.232  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:44.233  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:44.233  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:44.233  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:44.233  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:44.245  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:44.245  3266  3326 I jxcore-log: 
,03-31 16:30:44.248  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:44.248  3266  3326 I jxcore-log: 
,03-31 16:30:44.250  3266  3326 I jxcore-log: ok 187 no errors
03-31 16:30:44.250  3266  3326 I jxcore-log: 
,03-31 16:30:44.255  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 59040, start advertisements: false
03-31 16:30:44.255  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:44.255  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:44.255  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:44.256  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:44.258  3266  3326 I jxcore-log: ok 188 still no errors
03-31 16:30:44.258  3266  3326 I jxcore-log: 
,03-31 16:30:44.263  3266  3326 I jxcore-log: # teardown
03-31 16:30:44.263  3266  3326 I jxcore-log: 
,03-31 16:30:44.332  2164  2238 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,03-31 16:30:44.332  2164  2238 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x46
,03-31 16:30:44.565  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:44.565  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:44.566  3266  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:44.566  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:44.566  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:44.566  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:44.566  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:44.566  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:44.566  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:44.572  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:44.573  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:44.573  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:44.574  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:44.574  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:44.574  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:44.575  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:44.576  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:44.576  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:44.576  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:44.576  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:44.577  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 16:30:44.577  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:44.578  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:44.578  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:44.578  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:44.578  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:44.579  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:44.580  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:44.580  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 16:30:44.580  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:44.580  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:44.580  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:44.580  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:44.589  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:44.589   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:44.598  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 16:30:44.599  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 16:30:44.599  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:44.603  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:44.603  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:44.603  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:44.603  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:44.606  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 16:30:44.606  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:44.606  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:44.613  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:44.613  3266  3326 I jxcore-log: ,
03-31 16:30:44.614  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:44.614  3266  3326 I jxcore-log: 
,03-31 16:30:44.619  3266  3326 I jxcore-log: ok 189 must be stopped
03-31 16:30:44.619  3266  3326 I jxcore-log: 
,03-31 16:30:44.626  3266  3326 I jxcore-log: # setup
03-31 16:30:44.626  3266  3326 I jxcore-log: 
,03-31 16:30:44.782  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:44.782  3266  3326 I jxcore-log: 
,03-31 16:30:44.784  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:44.784  3266  3326 I jxcore-log: 
,03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:44.793  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:44.797  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-31 16:30:44.800  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-31 16:30:44.800  3266  3326 I jxcore-log: 
,03-31 16:30:44.804  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 16:30:44.804  3266  3326 I jxcore-log: 
,03-31 16:30:44.810  3266  3326 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times,
03-31 16:30:44.810  3266  3326 I jxcore-log: 
,03-31 16:30:44.814  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-31 16:30:44.814  3266  3326 I jxcore-log: 
,03-31 16:30:44.974  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 16:30:44.974  3266  3326 I jxcore-log: 
,03-31 16:30:44.976  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 57158
03-31 16:30:44.976  3266  3326 I jxcore-log: 
,03-31 16:30:44.983  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 57158, start advertisements: true
,03-31 16:30:44.983  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:44.983  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:44.983  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:44.989  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:44.989  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:44.989  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:44.989  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:44.993  2164  2183 D BtGatt.GattService: registerClient() - UUID=d7d7e8b5-8f64-46af-9fc0-02d21ff44600
,03-31 16:30:44.993  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=d7d7e8b5-8f64-46af-9fc0-02d21ff44600, clientIf=5
03-31 16:30:44.994  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:44.994  2164  2368 D BtGatt.GattService: start scan with filters
03-31 16:30:44.995  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:44.995  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:44.995  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:44.995  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:44.995  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:44.995  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:44.995  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:44.995  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:44.995  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:44.996  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:44.996  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:44.996  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-31 16:30:44.996  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:45.002  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-31 16:30:45.002  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:45.003  2164  2183 D BtGatt.GattService: registerClient() - UUID=d10a5cad-1166-4686-ad66-33b76c51f81d
03-31 16:30:45.003  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=d10a5cad-1166-4686-ad66-33b76c51f81d, clientIf=6
,03-31 16:30:45.004  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:45.004  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:45.004  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:45.005  2164  2236 D BtGatt.AdvertiseManager: message : 0
03-31 16:30:45.005  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:45.005  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 16:30:45.007  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 16:30:45.008  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:45.009  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 16:30:45.010  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:45.013  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:45.016  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:45.019  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-31 16:30:45.020  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:45.020  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:45.021   823  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-31 16:30:45.025  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:45.025  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,03-31 16:30:45.025  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 16:30:45.025  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:45.026  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:45.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:45.026  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:45.026  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:45.026  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:45.027  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:45.028  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:45.028  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:45.028   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:45.029  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-31 16:30:45.029  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:45.029  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:45.029  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:45.029  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:45.029  3266  3880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:45.030  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:45.030  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:45.031  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:45.031  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:45.032  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:45.032  3266  3326 I jxcore-log: 
03-31 16:30:45.034  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:45.034  3266  3326 I jxcore-log: 
03-31 16:30:45.035  3266  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:45.035  3266  3326 I jxcore-log: ok 190 no errors
03-31 16:30:45.035  3266  3326 I jxcore-log: 
,03-31 16:30:45.040  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 57158, start advertisements: true
03-31 16:30:45.040  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 16:30:45.040  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:45.040  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:45.040  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:45.042  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:45.042  3266  3326 I jxcore-log: 
,03-31 16:30:45.043  3266  3326 I jxcore-log: ok 191 still no errors
03-31 16:30:45.043  3266  3326 I jxcore-log: 
,03-31 16:30:45.049  3266  3326 I jxcore-log: # teardown
03-31 16:30:45.049  3266  3326 I jxcore-log: 
,03-31 16:30:45.900  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:45.900  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 16:30:45.903  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:45.903  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 16:30:45.903  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:45.904  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:45.904  3266  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:45.904  3266  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 16:30:45.904  3266  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:45.905  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:45.905  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:45.905  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:45.905  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:45.905  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:45.905  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:45.905  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:45.905  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:45.908  2164  2368 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:45.909  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:45.911  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:45.912  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:45.912  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:45.912  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:45.912  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:45.912  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:45.912  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:45.912  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:45.912  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:45.913  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
,03-31 16:30:45.915  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:45.915  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-31 16:30:45.915  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:45.916  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:45.916  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:45.918  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-31 16:30:45.918  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:45.918  2164  2227 D BtGatt.GattService: current time is 261627501044,
03-31 16:30:45.918  2164  2227 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -65, 101, -65, 109, 49, 108, 1, -128, -80, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 16:30:45.919  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
,03-31 16:30:45.920  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 16:30:45.920  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:45.920  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:45.923  2164  2183 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 16:30:45.924  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:45.924  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:45.924  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:45.924  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 16:30:45.924  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:45.925  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:45.925  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:45.925  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:45.925  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:45.925  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:45.925  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:45.925  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:45.926  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:45.932  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:45.932   823  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:45.940  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:45.940  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:45.940  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:45.943  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:45.943  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:45.943  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:45.943  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:45.943  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 16:30:45.944  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:45.945  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:45.946  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:45.946  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:45.949  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:45.949  3266  3326 I jxcore-log: 
,03-31 16:30:45.950  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:45.950  3266  3326 I jxcore-log: 
,03-31 16:30:45.951  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-31 16:30:45.951  3266  3326 I jxcore-log: 
,03-31 16:30:45.956  3266  3326 I jxcore-log: ok 192 must be stopped
,03-31 16:30:45.956  3266  3326 I jxcore-log: 
,03-31 16:30:45.963  3266  3326 I jxcore-log: # setup
,03-31 16:30:45.963  3266  3326 I jxcore-log: 
,03-31 16:30:46.110  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:46.110  3266  3326 I jxcore-log: 
,03-31 16:30:46.116  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:46.116  3266  3326 I jxcore-log: 
,03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:46.128  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,03-31 16:30:46.133  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:46.136  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 16:30:46.136  3266  3326 I jxcore-log: 
,03-31 16:30:46.140  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 16:30:46.140  3266  3326 I jxcore-log: 
,03-31 16:30:46.146  3266  3326 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
,03-31 16:30:46.146  3266  3326 I jxcore-log: 
,03-31 16:30:46.150  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-31 16:30:46.150  3266  3326 I jxcore-log: 
,03-31 16:30:47.450  2164  2225 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,03-31 16:30:47.935  2164  2238 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 16:30:47.941  2164  2164 D BluetoothMapService: onReceive
,03-31 16:30:47.966   823   858 D BluetoothManagerService: Message: 20
03-31 16:30:47.967   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19c05797:true
,03-31 16:30:47.983  1541  1541 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 16:30:47.986  1541  1541 I BluetoothClassifier: Bluetooth Device Name: G4-1,
,03-31 16:30:48.055  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 16:30:48.055  3266  3326 I jxcore-log: 
03-31 16:30:48.057  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 53588
03-31 16:30:48.057  3266  3326 I jxcore-log: 
,03-31 16:30:48.059  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:48.059  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:48.059  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.064  3266  3326 I jxcore-log: ok 193 no errors
03-31 16:30:48.064  3266  3326 I jxcore-log: 
,03-31 16:30:48.065  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:48.065  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:48.065  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.066  3266  3326 I jxcore-log: ok 194 still no errors
03-31 16:30:48.066  3266  3326 I jxcore-log: 
03-31 16:30:48.072  3266  3326 I jxcore-log: # teardown
03-31 16:30:48.072  3266  3326 I jxcore-log: 
,03-31 16:30:48.209  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:48.210  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:48.210  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.213  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:48.213  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 16:30:48.213  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:48.218  3266  3326 I jxcore-log: ok 195 must be stopped
03-31 16:30:48.218  3266  3326 I jxcore-log: 
,03-31 16:30:48.225  3266  3326 I jxcore-log: # setup
03-31 16:30:48.225  3266  3326 I jxcore-log: 
,03-31 16:30:48.360  2164  2238 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 16:30:48.366  2164  2164 D BluetoothMapService: onReceive,
,03-31 16:30:48.397  1541  1541 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-31 16:30:48.402  1541  1541 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-31 16:30:48.482  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:48.482  3266  3326 I jxcore-log: 
,03-31 16:30:48.486  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:48.486  3266  3326 I jxcore-log: 
,03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:48.496  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:48.499  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:48.501  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:48.501  3266  3326 I jxcore-log: 
,03-31 16:30:48.503  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:48.503  3266  3326 I jxcore-log: 
,03-31 16:30:48.506  3266  3326 I jxcore-log: # 48. can get the network status before starting
03-31 16:30:48.506  3266  3326 I jxcore-log: 
,03-31 16:30:48.508  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-31 16:30:48.508  3266  3326 I jxcore-log: 
,03-31 16:30:48.635  3266  3326 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 16:30:48.635  3266  3326 I jxcore-log: 
,03-31 16:30:48.638  3266  3326 I jxcore-log: # teardown
03-31 16:30:48.638  3266  3326 I jxcore-log: 
,03-31 16:30:48.732  3266  3326 I jxcore-log: ok 197 must be stopped
03-31 16:30:48.732  3266  3326 I jxcore-log: 
,03-31 16:30:48.734  3266  3326 I jxcore-log: # setup
03-31 16:30:48.734  3266  3326 I jxcore-log: 
,03-31 16:30:48.852  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:48.852  3266  3326 I jxcore-log: 
,03-31 16:30:48.854  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:48.854  3266  3326 I jxcore-log: 
,03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:48.862  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:48.865  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:48.867  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:48.867  3266  3326 I jxcore-log: 
,03-31 16:30:48.869  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:48.869  3266  3326 I jxcore-log: 
,03-31 16:30:48.872  3266  3326 I jxcore-log: # 49. error returned with bad router
03-31 16:30:48.872  3266  3326 I jxcore-log: 
,03-31 16:30:48.874  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:48.874  3266  3326 I jxcore-log: 
,03-31 16:30:48.995  3266  3326 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,03-31 16:30:48.995  3266  3326 I jxcore-log: 
,03-31 16:30:48.998  3266  3326 I jxcore-log: ok 198 specific error expected
03-31 16:30:48.998  3266  3326 I jxcore-log: 
,03-31 16:30:49.001  3266  3326 I jxcore-log: # teardown
03-31 16:30:49.001  3266  3326 I jxcore-log: 
,03-31 16:30:49.118  3266  3326 I jxcore-log: ok 199 must be stopped
03-31 16:30:49.118  3266  3326 I jxcore-log: 
,03-31 16:30:49.127  3266  3326 I jxcore-log: # setup
,03-31 16:30:49.127  3266  3326 I jxcore-log: 
,03-31 16:30:49.257  2164  2238 W bt-btif : dm_pm_timer expires
,03-31 16:30:49.257  2164  2238 W bt-btif : dm_pm_timer expires 0
03-31 16:30:49.258  2164  2238 W bt-btif : proc dm_pm_timer expires
,03-31 16:30:49.295  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:49.295  3266  3326 I jxcore-log: 
,03-31 16:30:49.301  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:49.301  3266  3326 I jxcore-log: 
,03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:49.315  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:49.322  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:49.326  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:49.326  3266  3326 I jxcore-log: 
,03-31 16:30:49.330  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:49.330  3266  3326 I jxcore-log: 
,03-31 16:30:49.338  3266  3326 I jxcore-log: # 50. all services are stopped when we call stop
03-31 16:30:49.338  3266  3326 I jxcore-log: 
,03-31 16:30:49.344  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:49.344  3266  3326 I jxcore-log: 
,03-31 16:30:49.479  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:49.479  3266  3326 I jxcore-log: 
,03-31 16:30:49.481  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 49556
03-31 16:30:49.481  3266  3326 I jxcore-log: 
,03-31 16:30:49.486  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 57158, start advertisements: false
,03-31 16:30:49.486  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:49.486  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:49.486  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:49.489  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:49.489  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:49.489  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 16:30:49.494  2164  2183 D BtGatt.GattService: registerClient() - UUID=acc02d86-af52-4439-8d8a-856f683904ba,
03-31 16:30:49.494  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=acc02d86-af52-4439-8d8a-856f683904ba, clientIf=5
03-31 16:30:49.495  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:49.495  2164  2186 D BtGatt.GattService: start scan with filters
,03-31 16:30:49.496  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:49.496  2164  2237 D BtGatt.ScanManager: handling starting scan
03-31 16:30:49.496  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:49.496  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:49.496  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:49.497  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:49.497  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:49.497  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 16:30:49.499   823  2128 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:49.501  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:49.501  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:49.503  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:49.503  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:49.503  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:49.503  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:49.505  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 16:30:49.505  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:49.507  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:49.507  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:49.509  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:49.510  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:49.510  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:49.510  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:49.510  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:49.510  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:49.514  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 16:30:49.514  3266  3326 I jxcore-log: 
03-31 16:30:49.514  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:49.514  3266  3326 I jxcore-log: 
,03-31 16:30:49.518  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 49556, start advertisements: true
03-31 16:30:49.519  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:49.519  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:49.519  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:49.522  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:49.522  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 16:30:49.522  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:49.522  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 16:30:49.522  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:49.522  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:49.522  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:49.522  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 16:30:49.526  2164  2186 D BtGatt.GattService: registerClient() - UUID=3b3edcf1-2e08-49da-af2c-ba60f47a7dda
,03-31 16:30:49.526  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=3b3edcf1-2e08-49da-af2c-ba60f47a7dda, clientIf=6
,03-31 16:30:49.526  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:49.527  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:49.531  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 16:30:49.533  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:49.536  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:49.536  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:49.536  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 16:30:49.537  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:49.537  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:49.537  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 16:30:49.537  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:49.537  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:49.537   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:49.541  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:49.541  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:49.541  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:49.541  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:49.541  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 16:30:49.542  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 16:30:49.542  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 16:30:49.543  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:49.543  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 16:30:49.543  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:49.543  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:49.543  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:49.544  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 16:30:49.546  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:49.546  3266  3326 I jxcore-log: 
03-31 16:30:49.546   823  2128 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 16:30:49.547  3266  3882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 16:30:49.550  3266  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:49.554  3266  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 16:30:49.554  3266  3326 I jxcore-log: 
,03-31 16:30:49.557  3266  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 16:30:49.557  3266  3326 I jxcore-log: 
,03-31 16:30:49.560  3266  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 16:30:49.560  3266  3326 I jxcore-log: 
,03-31 16:30:49.565  3266  3326 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-31 16:30:49.565  3266  3326 I jxcore-log: 
,03-31 16:30:49.588  3266  3326 I jxcore-log: ok 201 connection to router server should succeed after starting
,03-31 16:30:49.588  3266  3326 I jxcore-log: 
,03-31 16:30:49.590  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:49.590  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:49.590  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
03-31 16:30:49.590  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:49.590  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 16:30:49.590  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 16:30:49.591  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,03-31 16:30:49.591  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 16:30:49.591  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:49.591  3266  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:49.591  3266  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-31 16:30:49.591  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:49.591  3266  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
03-31 16:30:49.592  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:49.592  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:49.595  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
,03-31 16:30:49.597  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:49.598  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:49.598  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:49.598  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:49.598  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:49.599  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 16:30:49.599  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:49.599  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:49.599  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:49.599  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:49.599  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:49.602  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:49.602  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:49.602  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:49.603  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 16:30:49.603  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-31 16:30:49.606  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-31 16:30:49.606  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:49.607  2164  2227 D BtGatt.GattService: current time is 265316000209
03-31 16:30:49.607  2164  2227 D BtGatt.GattService: Batch record : [-54, 46, -76, 54, 62, 124, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 16:30:49.607  2164  2227 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 16:30:49.608  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:49.608  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:49.610  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 16:30:49.615  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:49.615  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:49.615  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 16:30:49.615  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:49.616  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:49.616  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:49.616  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:49.616  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:49.617  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 16:30:49.617  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 16:30:49.618  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:49.618  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:49.618  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 16:30:49.624  3266  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-31 16:30:49.624  3266  3326 I jxcore-log: 
,03-31 16:30:49.625  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:49.626   823   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:49.637  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:49.638  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:49.638  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 16:30:49.638  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:49.639  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:49.644  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 16:30:49.644  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:49.644  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:49.645  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:49.645  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 16:30:49.646  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:49.646  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:49.646  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:49.646  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:49.649  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-31 16:30:49.649  3266  3326 I jxcore-log: 
03-31 16:30:49.651  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:49.651  3266  3326 I jxcore-log: 
,03-31 16:30:49.653  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-31 16:30:49.653  3266  3326 I jxcore-log: 
,03-31 16:30:49.661  3266  3326 I jxcore-log: ok 202 is stopped after calling stop
03-31 16:30:49.661  3266  3326 I jxcore-log: 
,03-31 16:30:49.666  3266  3326 I jxcore-log: ok 203 connection to servers manager should fail after stopping
,03-31 16:30:49.666  3266  3326 I jxcore-log: 
,03-31 16:30:49.671  3266  3326 I jxcore-log: ok 204 connection to router server should fail after stopping
03-31 16:30:49.671  3266  3326 I jxcore-log: 
,03-31 16:30:49.676  3266  3326 I jxcore-log: # teardown
,03-31 16:30:49.676  3266  3326 I jxcore-log: 
,03-31 16:30:50.202  3266  3326 I jxcore-log: ok 205 must be stopped
03-31 16:30:50.202  3266  3326 I jxcore-log: 
,03-31 16:30:50.204  3266  3326 I jxcore-log: # setup
03-31 16:30:50.204  3266  3326 I jxcore-log: 
,03-31 16:30:50.323  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:50.323  3266  3326 I jxcore-log: 
,03-31 16:30:50.325  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:50.325  3266  3326 I jxcore-log: 
,03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:50.333  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:50.339  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:50.341  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:50.341  3266  3326 I jxcore-log: 
,03-31 16:30:50.343  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:50.343  3266  3326 I jxcore-log: 
,03-31 16:30:50.346  3266  3326 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-31 16:30:50.346  3266  3326 I jxcore-log: 
,03-31 16:30:50.348  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:50.348  3266  3326 I jxcore-log: 
,03-31 16:30:50.917  3266  3326 I jxcore-log: ok 206 called with right arguments
03-31 16:30:50.917  3266  3326 I jxcore-log: 
,03-31 16:30:50.919  3266  3326 I jxcore-log: # teardown
03-31 16:30:50.919  3266  3326 I jxcore-log: 
,03-31 16:30:51.006  3266  3326 I jxcore-log: ok 207 must be stopped
03-31 16:30:51.006  3266  3326 I jxcore-log: 
,03-31 16:30:51.013  3266  3326 I jxcore-log: # setup
03-31 16:30:51.013  3266  3326 I jxcore-log: 
,03-31 16:30:51.839  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:51.839  3266  3326 I jxcore-log: 
,03-31 16:30:51.843  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:51.843  3266  3326 I jxcore-log: 
,03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:51.857  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:51.862  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:51.865  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:51.865  3266  3326 I jxcore-log: 
,03-31 16:30:51.869  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-31 16:30:51.869  3266  3326 I jxcore-log: 
,03-31 16:30:51.876  3266  3326 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 16:30:51.876  3266  3326 I jxcore-log: 
,03-31 16:30:51.879  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:51.879  3266  3326 I jxcore-log: 
,03-31 16:30:52.055  3266  3326 I jxcore-log: ok 208 called with right arguments
03-31 16:30:52.055  3266  3326 I jxcore-log: 
03-31 16:30:52.057  3266  3326 I jxcore-log: # teardown
03-31 16:30:52.057  3266  3326 I jxcore-log: 
,03-31 16:30:52.653  3266  3326 I jxcore-log: ok 209 must be stopped
03-31 16:30:52.653  3266  3326 I jxcore-log: 
03-31 16:30:52.655  3266  3326 I jxcore-log: # setup
03-31 16:30:52.655  3266  3326 I jxcore-log: 
,03-31 16:30:52.781  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:52.781  3266  3326 I jxcore-log: 
03-31 16:30:52.786  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:52.786  3266  3326 I jxcore-log: 
,03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:52.798  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:52.804  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:52.807  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:52.807  3266  3326 I jxcore-log: 
,03-31 16:30:52.811  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:52.811  3266  3326 I jxcore-log: 
,03-31 16:30:52.818  3266  3326 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 16:30:52.818  3266  3326 I jxcore-log: 
,03-31 16:30:52.822  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:52.822  3266  3326 I jxcore-log: 
,03-31 16:30:53.129  3266  3326 I jxcore-log: ok 210 specific error expected
03-31 16:30:53.129  3266  3326 I jxcore-log: 
,03-31 16:30:53.137  3266  3326 I jxcore-log: # teardown
03-31 16:30:53.137  3266  3326 I jxcore-log: 
,03-31 16:30:53.785  3266  3326 I jxcore-log: ok 211 must be stopped
03-31 16:30:53.785  3266  3326 I jxcore-log: 
,03-31 16:30:53.793  3266  3326 I jxcore-log: # setup
,03-31 16:30:53.793  3266  3326 I jxcore-log: 
,03-31 16:30:53.918  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:53.918  3266  3326 I jxcore-log: 
,03-31 16:30:53.925  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:53.925  3266  3326 I jxcore-log: 
,03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-31 16:30:53.937  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:53.942  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:53.944  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:53.944  3266  3326 I jxcore-log: 
,03-31 16:30:53.947  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 16:30:53.947  3266  3326 I jxcore-log: 
,03-31 16:30:53.951  3266  3326 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,03-31 16:30:53.951  3266  3326 I jxcore-log: 
,03-31 16:30:53.954  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:53.954  3266  3326 I jxcore-log: 
,03-31 16:30:54.237  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 16:30:54.237  3266  3326 I jxcore-log: 
,03-31 16:30:54.240  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 44536
03-31 16:30:54.240  3266  3326 I jxcore-log: 
,03-31 16:30:54.247  3266  3326 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":41486,"error":{}}
03-31 16:30:54.247  3266  3326 I jxcore-log: 
,03-31 16:30:54.249  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 16:30:54.249  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-31 16:30:54.249  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:54.251  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 16:30:54.251  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:54.251  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:54.264  3266  3326 I jxcore-log: ok 212 failure reason is as expected
03-31 16:30:54.264  3266  3326 I jxcore-log: ,
03-31 16:30:54.265  3266  3326 I jxcore-log: ok 213 error description is as expected
03-31 16:30:54.265  3266  3326 I jxcore-log: 
03-31 16:30:54.265  3266  3326 I jxcore-log: ok 214 must be stopped,
03-31 16:30:54.265  3266  3326 I jxcore-log: 
,03-31 16:30:54.274  3266  3326 I jxcore-log: # teardown
,03-31 16:30:54.274  3266  3326 I jxcore-log: 
,03-31 16:30:54.429  3266  3326 I jxcore-log: ok 215 must be stopped
03-31 16:30:54.429  3266  3326 I jxcore-log: ,
,03-31 16:30:54.436  3266  3326 I jxcore-log: # setup
03-31 16:30:54.436  3266  3326 I jxcore-log: 
,03-31 16:30:54.643  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:54.643  3266  3326 I jxcore-log: 
,03-31 16:30:54.644  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:54.644  3266  3326 I jxcore-log: 
,03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:54.652  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:54.656  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:54.658  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:54.658  3266  3326 I jxcore-log: 
,03-31 16:30:54.660  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:54.660  3266  3326 I jxcore-log: 
,03-31 16:30:54.663  3266  3326 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 16:30:54.663  3266  3326 I jxcore-log: 
,03-31 16:30:54.665  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:54.665  3266  3326 I jxcore-log: 
,03-31 16:30:54.848  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:54.848  3266  3326 I jxcore-log: 
,03-31 16:30:54.851  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 50305
03-31 16:30:54.851  3266  3326 I jxcore-log: 
,03-31 16:30:54.855  3266  3326 I jxcore-log: ok 216 peerIdentifier matches
03-31 16:30:54.855  3266  3326 I jxcore-log: 
,03-31 16:30:54.855  3266  3326 I jxcore-log: ok 217 error description matches
03-31 16:30:54.855  3266  3326 I jxcore-log: 
,03-31 16:30:54.859  3266  3326 I jxcore-log: # teardown
03-31 16:30:54.859  3266  3326 I jxcore-log: 
,03-31 16:30:54.995  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:54.995  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 16:30:54.996  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:54.999  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:54.999  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:54.999  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:55.005  3266  3326 I jxcore-log: ok 218 must be stopped
03-31 16:30:55.005  3266  3326 I jxcore-log: 
,03-31 16:30:55.012  3266  3326 I jxcore-log: # setup
03-31 16:30:55.012  3266  3326 I jxcore-log: 
,03-31 16:30:55.142  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:30:55.142  3266  3326 I jxcore-log: 
,03-31 16:30:55.143  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:30:55.143  3266  3326 I jxcore-log: 
,03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:30:55.151  3266  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:30:55.154  3266  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 16:30:55.155  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:30:55.155  3266  3326 I jxcore-log: 
,03-31 16:30:55.157  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:30:55.157  3266  3326 I jxcore-log: 
,03-31 16:30:55.168  3266  3326 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-31 16:30:55.168  3266  3326 I jxcore-log: 
,03-31 16:30:55.170  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:30:55.170  3266  3326 I jxcore-log: 
,03-31 16:30:55.337  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:55.337  3266  3326 I jxcore-log: 
03-31 16:30:55.339  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 36833
03-31 16:30:55.339  3266  3326 I jxcore-log: 
,03-31 16:30:55.346  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 49556, start advertisements: false
03-31 16:30:55.347  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:55.347  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 16:30:55.347  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 16:30:55.353  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 16:30:55.353  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 16:30:55.353  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:55.359  2164  2368 D BtGatt.GattService: registerClient() - UUID=a9fe02c5-2c53-4d42-a805-5caad6133834
,03-31 16:30:55.360  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=a9fe02c5-2c53-4d42-a805-5caad6133834, clientIf=5
,03-31 16:30:55.361  3266  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:55.361  2164  2183 D BtGatt.GattService: start scan with filters
,03-31 16:30:55.363  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:55.364  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 16:30:55.364  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 16:30:55.364  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 16:30:55.364  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 16:30:55.365  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:55.365  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:55.371  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-31 16:30:55.373   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:55.373  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 16:30:55.373  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:55.375  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 16:30:55.375  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.376  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:55.376  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,03-31 16:30:55.379  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 16:30:55.379  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 16:30:55.381  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-31 16:30:55.381  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:55.387  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:55.387  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:55.388  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 16:30:55.388  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 16:30:55.388  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:55.388  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:55.392  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.392  3266  3326 I jxcore-log: 
,03-31 16:30:55.394  3266  3326 I jxcore-log: ok 219 discoveryActive matches
,03-31 16:30:55.394  3266  3326 I jxcore-log: 
,03-31 16:30:55.395  3266  3326 I jxcore-log: ok 220 advertisingActive matches
,03-31 16:30:55.395  3266  3326 I jxcore-log: 
03-31 16:30:55.396  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.396  3266  3326 I jxcore-log: 
,03-31 16:30:55.397  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:55.397  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
03-31 16:30:55.397  3266  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 16:30:55.398  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 16:30:55.398  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:55.398  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 16:30:55.398  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:55.398  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 16:30:55.398  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:55.400  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:55.401  2164  2186 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 16:30:55.402  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 16:30:55.402  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.403  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 16:30:55.403  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:55.403  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:55.404  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:55.404  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 16:30:55.404  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 16:30:55.404  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:55.405  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 16:30:55.405  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 16:30:55.406  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 16:30:55.406  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:55.406  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.406  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 16:30:55.407  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:55.407  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:55.407  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 16:30:55.407  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:55.408  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:55.408  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 16:30:55.408  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:55.414  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 16:30:55.414   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:55.421  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 16:30:55.421  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 16:30:55.422  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:55.426  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:55.426  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:55.426  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:55.427  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:55.428  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:55.428  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:55.428  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 16:30:55.431  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.431  3266  3326 I jxcore-log: 
,03-31 16:30:55.433  3266  3326 I jxcore-log: ok 221 discoveryActive matches
03-31 16:30:55.433  3266  3326 I jxcore-log: 
,03-31 16:30:55.434  3266  3326 I jxcore-log: ok 222 advertisingActive matches
03-31 16:30:55.434  3266  3326 I jxcore-log: 
,03-31 16:30:55.438  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.438  3266  3326 I jxcore-log: 
,03-31 16:30:55.459  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server,
03-31 16:30:55.459  3266  3326 I jxcore-log: 
,03-31 16:30:55.461  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 52387
03-31 16:30:55.461  3266  3326 I jxcore-log: 
,03-31 16:30:55.467  3266  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 52387, start advertisements: true
03-31 16:30:55.467  3266  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 16:30:55.467  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 16:30:55.467  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 16:30:55.472  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 16:30:55.472  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 16:30:55.472  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 16:30:55.472  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 16:30:55.476  2164  2183 D BtGatt.GattService: registerClient() - UUID=6c9b0ff7-ecaa-47e3-9d1f-cbc72d00a49f
,03-31 16:30:55.476  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=6c9b0ff7-ecaa-47e3-9d1f-cbc72d00a49f, clientIf=5
03-31 16:30:55.477  3266  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 16:30:55.477  2164  2186 D BtGatt.GattService: start scan with filters
03-31 16:30:55.478  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 16:30:55.478  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 16:30:55.478  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 16:30:55.478  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 16:30:55.478  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 16:30:55.478  2164  2237 D BtGatt.ScanManager: handling starting scan
,03-31 16:30:55.479  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 16:30:55.479  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 16:30:55.479  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 16:30:55.479  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 16:30:55.479  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 16:30:55.479  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 16:30:55.479  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 16:30:55.481  2164  2227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 16:30:55.481  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.482  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 16:30:55.482  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.483  2164  2237 D BtGatt.ScanManager: Starting BLE batch scan
03-31 16:30:55.483  2164  2237 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 16:30:55.485  2164  2227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 16:30:55.485  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.487  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 16:30:55.487  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:55.490  2164  2368 D BtGatt.GattService: registerClient() - UUID=a19e7766-c253-44ed-85f1-da131e3aba37,
03-31 16:30:55.491  2164  2227 D BtGatt.GattService: onClientRegistered() - UUID=a19e7766-c253-44ed-85f1-da131e3aba37, clientIf=6
03-31 16:30:55.491  3266  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 16:30:55.493  2164  2236 D BtGatt.AdvertiseManager: message : 0
,03-31 16:30:55.496  2164  2236 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 16:30:55.499  2164  2227 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 16:30:55.501  2164  2227 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 16:30:55.502  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 16:30:55.502  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 16:30:55.502   823  2591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:55.505  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 16:30:55.505  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 16:30:55.505  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 16:30:55.505  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:55.506  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 16:30:55.507  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 16:30:55.507  3266  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 16:30:55.507  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 16:30:55.508  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 16:30:55.508  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 16:30:55.508  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 16:30:55.508  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 16:30:55.508  3266  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 16:30:55.508  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 16:30:55.508  3266  3266 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:55.508  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 16:30:55.508  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 16:30:55.508  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 16:30:55.509  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 16:30:55.509  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 16:30:55.510   823  1338 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:55.510  3266  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 16:30:55.512  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.512  3266  3326 I jxcore-log: 
,03-31 16:30:55.512  3266  3883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 16:30:55.517  3266  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 16:30:55.520  3266  3326 I jxcore-log: not ok 223 discoveryActive matches
,03-31 16:30:55.520  3266  3326 I jxcore-log: 
03-31 16:30:55.520  3266  3326 I jxcore-log:   ---
03-31 16:30:55.520  3266  3326 I jxcore-log: 
03-31 16:30:55.520  3266  3326 I jxcore-log:     operator: equal
03-31 16:30:55.520  3266  3326 I jxcore-log: 
03-31 16:30:55.520  3266  3326 I jxcore-log:     expected: false
03-31 16:30:55.520  3266  3326 I jxcore-log: 
,03-31 16:30:55.520  3266  3326 I jxcore-log:     actual:   true
03-31 16:30:55.520  3266  3326 I jxcore-log: 
03-31 16:30:55.520  3266  3326 I jxcore-log:   ...
03-31 16:30:55.520  3266  3326 I jxcore-log: 
,03-31 16:30:55.524  3266  3326 I jxcore-log: not ok 224 advertisingActive matches
03-31 16:30:55.524  3266  3326 I jxcore-log: 
,03-31 16:30:55.524  3266  3326 I jxcore-log:   ---
03-31 16:30:55.524  3266  3326 I jxcore-log: 
03-31 16:30:55.524  3266  3326 I jxcore-log:     operator: equal
03-31 16:30:55.524  3266  3326 I jxcore-log: 
,03-31 16:30:55.524  3266  3326 I jxcore-log:     expected: true
03-31 16:30:55.524  3266  3326 I jxcore-log: 
03-31 16:30:55.524  3266  3326 I jxcore-log:     actual:   false
03-31 16:30:55.524  3266  3326 I jxcore-log: 
03-31 16:30:55.525  3266  3326 I jxcore-log:   ...
03-31 16:30:55.525  3266  3326 I jxcore-log: 
,03-31 16:30:55.527  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 16:30:55.527  3266  3326 I jxcore-log: 
,03-31 16:30:55.528  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 16:30:55.528  3266  3326 I jxcore-log: 
,03-31 16:30:55.531  3266  3326 I jxcore-log: not ok 225 discoveryActive matches
03-31 16:30:55.531  3266  3326 I jxcore-log: 
,03-31 16:30:55.532  3266  3326 I jxcore-log:   ---
03-31 16:30:55.532  3266  3326 I jxcore-log: 
03-31 16:30:55.532  3266  3326 I jxcore-log:     operator: equal
03-31 16:30:55.532  3266  3326 I jxcore-log: 
03-31 16:30:55.532  3266  3326 I jxcore-log:     expected: false
03-31 16:30:55.532  3266  3326 I jxcore-log: 
,03-31 16:30:55.532  3266  3326 I jxcore-log:     actual:   true
03-31 16:30:55.532  3266  3326 I jxcore-log: 
03-31 16:30:55.532  3266  3326 I jxcore-log:   ...
03-31 16:30:55.532  3266  3326 I jxcore-log: 
,03-31 16:30:55.535  3266  3326 I jxcore-log: not ok 226 advertisingActive matches
03-31 16:30:55.535  3266  3326 I jxcore-log: 
,03-31 16:30:55.535  3266  3326 I jxcore-log:   ---
03-31 16:30:55.535  3266  3326 I jxcore-log: 
03-31 16:30:55.535  3266  3326 I jxcore-log:     operator: equal
03-31 16:30:55.535  3266  3326 I jxcore-log: 
03-31 16:30:55.535  3266  3326 I jxcore-log:     expected: false
03-31 16:30:55.535  3266  3326 I jxcore-log: 
03-31 16:30:55.535  3266  3326 I jxcore-log:     actual:   true
03-31 16:30:55.535  3266  3326 I jxcore-log: 
,03-31 16:30:55.536  3266  3326 I jxcore-log:   ...
03-31 16:30:55.536  3266  3326 I jxcore-log: 
,03-31 16:30:55.538  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 16:30:55.538  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 16:30:55.538  3266  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 16:30:55.538  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 16:30:55.538  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 16:30:55.538  3266  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 16:30:55.538  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 16:30:55.538  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 16:30:55.538  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 16:30:55.538  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 16:30:55.539  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 16:30:55.539  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 16:30:55.539  3266  3883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 16:30:55.539  3266  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-31 16:30:55.539  3266  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 16:30:55.540  2164  2183 D BtGatt.GattService: stopScan() - queue size =1
03-31 16:30:55.541  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 16:30:55.541  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 16:30:55.541  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:55.541  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 16:30:55.542  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 16:30:55.542  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 16:30:55.542  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:55.542  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 16:30:55.543  2164  2227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 16:30:55.543  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 16:30:55.543  2164  2236 D BtGatt.AdvertiseManager: message : 1
03-31 16:30:55.544  2164  2237 D BtGatt.ScanManager: stopping BLe Batch
03-31 16:30:55.544  2164  2236 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 16:30:55.547  2164  2227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 16:30:55.547  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.547  2164  2237 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 16:30:55.548  2164  2227 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 16:30:55.548  2164  2227 D BtGatt.GattService: Client app is not null!
03-31 16:30:55.549  2164  2368 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 16:30:55.549  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 16:30:55.550  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 16:30:55.550  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-31 16:30:55.550  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 16:30:55.550  3266  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 16:30:55.550  2164  2227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 16:30:55.550  2164  2227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 16:30:55.550  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 16:30:55.550  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 16:30:55.551  3266  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 16:30:55.552  3266  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 16:30:55.553  3266  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 16:30:55.553  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 16:30:55.553  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:30:55.553  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 16:30:55.558  3266  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 16:30:55.558   823   842 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:30:55.565  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 16:30:55.566  3266  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 16:30:55.566  3266  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 16:30:55.570  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-31 16:30:55.570  3266  3266 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 16:30:55.570  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 16:30:55.571  3266  3266 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 16:30:55.571  3266  3266 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 16:30:55.571  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 16:30:55.572  3266  3266 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 16:30:55.572  3266  3266 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 16:30:55.572  3266  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 16:30:55.572  3266  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 16:30:55.572  3266  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 16:30:55.574  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 16:30:55.574  3266  3326 I jxcore-log: 
,03-31 16:30:55.575  3266  3326 I jxcore-log: ok 227 discoveryActive matches
03-31 16:30:55.575  3266  3326 I jxcore-log: 
,03-31 16:30:55.579  3266  3326 I jxcore-log: not ok 228 advertisingActive matches
03-31 16:30:55.579  3266  3326 I jxcore-log: 
,03-31 16:30:55.579  3266  3326 I jxcore-log:   ---
03-31 16:30:55.579  3266  3326 I jxcore-log: 
03-31 16:30:55.579  3266  3326 I jxcore-log:     operator: equal
03-31 16:30:55.579  3266  3326 I jxcore-log: 
03-31 16:30:55.579  3266  3326 I jxcore-log:     expected: false
03-31 16:30:55.579  3266  3326 I jxcore-log: 
03-31 16:30:55.579  3266  3326 I jxcore-log:     actual:   true
03-31 16:30:55.579  3266  3326 I jxcore-log: 
03-31 16:30:55.579  3266  3326 I jxcore-log:   ...
03-31 16:30:55.579  3266  3326 I jxcore-log: 
,03-31 16:30:55.582  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.582  3266  3326 I jxcore-log: 
,03-31 16:30:55.583  3266  3326 I jxcore-log: ok 229 discoveryActive matches
03-31 16:30:55.583  3266  3326 I jxcore-log: 
,03-31 16:30:55.583  3266  3326 I jxcore-log: ok 230 advertisingActive matches
03-31 16:30:55.583  3266  3326 I jxcore-log: 
,03-31 16:30:55.585  3266  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 16:30:55.585  3266  3326 I jxcore-log: 
,03-31 16:30:55.597  3266  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 16:30:55.597  3266  3326 I jxcore-log: 
,03-31 16:30:55.599  3266  3326 I jxcore-log: DEBUG createNativeListener: listening 41706
03-31 16:30:55.599  3266  3326 I jxcore-log: 
,03-31 16:30:55.614  3266  3326 E jxcore-log: Trace: [Error: Call Stop!]
03-31 16:30:55.614  3266  3326 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 16:30:55.614  3266  3326 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-31 16:30:55.614  3266  3326 E jxcore-log:     at emit@events.js:98:1
,03-31 16:30:55.614  3266  3326 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 16:30:55.614  3266  3326 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 16:30:55.614  3266  3326 E jxcore-log:     at $0a@node.js:917:1
03-31 16:30:55.614  3266  3326 E jxcore-log: 
,03-31 16:30:55.614  3266  3326 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-31 16:30:55.614  3266  3326 I jxcore-log: 
,03-31 16:30:55.616  3266  3326 I jxcore-log: # teardown
03-31 16:30:55.616  3266  3326 I jxcore-log: 
,03-31 16:30:55.870  3884  3884 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 16:30:55.873  3884  3884 D AndroidRuntime: CheckJNI is OFF
,03-31 16:30:55.988  3884  3884 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 16:30:55.998   823   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-31 16:30:55.998   823   854 I ActivityManager: Killing 3266:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-31 16:30:56.071   823   864 W PackageSettings: Skipping PackageSetting{29d938fb com.example.hello/10273} due to missing metadata
,03-31 16:30:56.081   823  1008 W InputDispatcher: channel '110f3a0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,03-31 16:30:56.081   823  1008 E InputDispatcher: channel '110f3a0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,03-31 16:30:56.092   823  2128 I WindowState: WIN DEATH: Window{110f3a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 16:30:56.092   823  2128 W InputDispatcher: Attempted to unregister already unregistered input channel '110f3a0 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,03-31 16:30:56.092   823  1035 D WifiService: Client connection lost with reason: 4
,03-31 16:30:56.208   823   854 W ActivityManager: Force removing ActivityRecord{19d6a41a u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-31 16:30:56.226   823   823 V ActivityManager: Display changed displayId=0,
,03-31 16:30:56.247   823  2591 W ActivityManager: Spurious death for ProcessRecord{1676c925 3266:com.test.thalitest/u0a95}, curProc for 3266: null
,03-31 16:30:56.247   823   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-31 16:30:56.297  1244  1244 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 16:30:56.304   823  1056 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-31 16:30:56.306  2985  2985 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-31 16:30:56.313   823  1009 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 16:30:56.356  1093  1093 I art     : Explicit concurrent mark sweep GC freed 18040(803KB) AllocSpace objects, 0(0B) LOS objects, 14% free, 91MB/107MB, paused 5.381ms total 74.149ms
,03-31 16:30:56.357   823  1342 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3266 uid 10095
,03-31 16:30:56.363  1541  1541 I art     : Explicit concurrent mark sweep GC freed 10126(479KB) AllocSpace objects, 2(32KB) LOS objects, 36% free, 27MB/43MB, paused 17.185ms total 99.104ms
,03-31 16:30:56.365  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-31 16:30:56.366  1244  3899 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 16:30:56.368  1244  3899 I Decoder : createOrResetDecoder
,03-31 16:30:56.395   823   823 I art     : Explicit concurrent mark sweep GC freed 34514(2MB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.900ms total 119.291ms
,03-31 16:30:56.398   823   841 I ActivityManager: Start proc 3900:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-31 16:30:56.404  1131  1131 I ConfigService: onCreate
,03-31 16:30:56.406   823   864 I art     : WaitForGcToComplete blocked for 117.071ms for cause Explicit
,03-31 16:30:56.416  1378  1378 I art     : Explicit concurrent mark sweep GC freed 4957(362KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.330ms total 23.942ms
,03-31 16:30:56.425  1244  3899 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 16:30:56.444  1541  1541 W LocationOracleImpl: Best location was null
,03-31 16:30:56.458  1541  3922 I HotwordRecognitionRnr: Starting hotword detection.
03-31 16:30:56.460  1541  3923 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@2a4c2821
,03-31 16:30:56.461   358  3925 I AudioFlinger: AudioFlinger's thread 0xb405a000 ready to run
,03-31 16:30:56.468   358  1028 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-31 16:30:56.469  1541  3923 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@2a4c2821
,03-31 16:30:56.470  1244  3899 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-31 16:30:56.473  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 16:30:56.473  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-31 16:30:56.475  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 16:30:56.475  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 16:30:56.476  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 16:30:56.476  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 16:30:56.477  1244  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 16:30:56.477  1244  3899 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 16:30:56.477  1244  3899 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 16:30:56.477  1244  3899 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 16:30:56.477  1244  3899 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 16:30:56.477  1244  3899 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-31 16:30:56.479   358  3925 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 16:30:56.479   358  3925 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 16:30:56.479   358  3925 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 16:30:56.479   358  3925 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-31 16:30:56.483   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 16:30:56.483   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 16:30:56.487   358  3925 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 16:30:56.521  3900  3936 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 16:30:56.545   823   841 I ActivityManager: Start proc 3937:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 16:30:56.556  1541  1541 I HotwordWorker: onReady
,03-31 16:30:56.559   823   841 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2c84a3b}
,03-31 16:30:56.561   823  1034 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=1.00 targetRoamBSSID=any RSSI=-127
,03-31 16:30:56.565  3900  3932 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-31 16:30:56.572   823   864 I art     : Explicit concurrent mark sweep GC freed 9234(439KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 2.151ms total 164.266ms
,03-31 16:30:56.602   823  2591 I ActivityManager: Start proc 3957:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 16:30:56.617   823  1287 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660384531
03-31 16:30:56.617   823  1287 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 16:30:56.622  3957  3957 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 16:30:56.629  1131  1131 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 16:30:56.629  1131  1131 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 16:30:56.644   823  1341 I ActivityManager: Killing 3610:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-31 16:30:56.645  1779  3978 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 16:30:56.645  1779  3978 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 16:30:56.655  3884  3884 I art     : System.exit called, status: 0
03-31 16:30:56.655  3884  3884 I AndroidRuntime: VM exiting with result code 0.
,03-31 16:30:56.696   875   875 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 16:30:56.696   875   875 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 16:30:56.738   875   875 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-31 16:30:56.738   875   875 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-31 16:30:56.750  1779  1779 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-31 16:30:56.751  1779  1779 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-31 16:30:56.801   823   864 I ActivityManager: Start proc 3982:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-31 16:30:56.817  1779  1779 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-31 16:30:56.818  1779  3978 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-31 16:30:56.819  1779  1779 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
03-31 16:30:56.819  1779  3997 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-31 16:30:56.821  1779  3997 E DriveAsyncService: disk I/O error (code 3850)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:56.821  1779  3997 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:56.826  1378  1378 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-31 16:30:56.827  1378  1378 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-31 16:30:56.828  1779  3999 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-31 16:30:56.838  1779  3978 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:56.838  1779  3978 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:56.838  1779  3978 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
03-31 16:30:56.840  1779  3999 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
03-31 16:30:56.840  1779  3999 E AndroidRuntime: Process: com.google.android.gms, PID: 1779
03-31 16:30:56.840  1779  3999 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
,03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:56.840  1779  3999 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:56.843  1541  4002 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-31 16:30:56.852  1779  3978 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,03-31 16:30:56.857   823   854 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:30:56.857   823   854 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:56.859  1779  4000 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:56.859  1779  4000 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:56.862  1779  4000 W SQLiteOpenHelper: Opened metrics.db in read-only mode
03-31 16:30:56.862   823  4007 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:30:56.862   823  4007 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:56.862   823  4007 E DropBoxManagerService: 	... 5 more
03-31 16:30:56.862  1779  4000 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-31 16:30:56.862  1779  4000 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-31 16:30:56.863  1779  4000 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
03-31 16:30:56.863  1779  4000 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-31 16:30:56.863  1779  4000 I Process : Sending signal. PID: 1779 SIG: 9
,03-31 16:30:56.865  1378  4001 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-31 16:30:56.881  1541  4002 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 16:30:56.882   823  4009 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 16:30:56.882   823   854 D Atlas   : Validating map...
,03-31 16:30:56.896  1378  1378 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e98a686 new=com.google.android.velvet.VelvetApplication@1e98a686
,03-31 16:30:56.897  1378  1617 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-31 16:30:56.910   823   841 I ActivityManager: Start proc 4010:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,03-31 16:30:56.911   255   255 E lowmemorykiller: Error writing /proc/1779/oom_score_adj; errno=22
,03-31 16:30:56.913  1541  4002 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
03-31 16:30:56.913  1541  4002 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
03-31 16:30:56.913  1541  4002 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1541
03-31 16:30:56.913  1541  4002 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1333)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:56.913  1541  4002 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:56.916   823  4019 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:30:56.916   823  4019 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:56.916   823  4019 E DropBoxManagerService: 	... 5 more
,03-31 16:30:56.919   823  2128 I ActivityManager: Killing 3591:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-31 16:30:56.936   823  4009 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 16:30:56.943   823  4009 D OpenGLRenderer: Enabling debug mode 0
,03-31 16:30:56.946   823  1035 D WifiService: Client connection lost with reason: 4
,03-31 16:30:57.087   823  2128 I ActivityManager: Start proc 4030:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 16:30:57.088   823  1151 I ActivityManager: Process com.google.android.gms (pid 1779) has died
03-31 16:30:57.089   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
03-31 16:30:57.089   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
03-31 16:30:57.089   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
03-31 16:30:57.089   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
03-31 16:30:57.090   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
03-31 16:30:57.090   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
03-31 16:30:57.090   823  1151 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
,03-31 16:30:57.207   823  1341 I ActivityManager: Start proc 4051:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,03-31 16:30:57.231  4051  4051 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:30:57.231  4051  4051 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 16:30:57.252  4051  4051 I MultiDex: VM with version 2.1.0 has multidex support
03-31 16:30:57.252  4051  4051 I MultiDex: install
03-31 16:30:57.252  4051  4051 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 16:30:57.288  4051  4070 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.288  4051  4070 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:57.290  4051  4070 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.290  4051  4070 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:57.328  4051  4051 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 16:30:57.332  1541  1541 I HotwordDetector: Closing mic
03-31 16:30:57.332  1541  1769 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2a4c2821
,03-31 16:30:57.355  1541  4072 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 16:30:57.367  4051  4051 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: Failed to open lock file
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:57.373  4051  4076 W NativeLibraryUtils: 	... 3 more
,03-31 16:30:57.381   358  3925 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-31 16:30:57.382   358  3925 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-31 16:30:57.386   358  1028 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-31 16:30:57.388  1541  3922 I HotwordRecognitionRnr: Hotword detection finished
03-31 16:30:57.389  1541  1771 I HotwordRecognitionRnr: Stopping hotword detection.
,03-31 16:30:57.410  1131  1147 I art     : Explicit concurrent mark sweep GC freed 36043(2022KB) AllocSpace objects, 11(1024KB) LOS objects, 37% free, 26MB/42MB, paused 754us total 21.705ms
,03-31 16:30:57.416  4051  4051 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-31 16:30:57.416  4030  4030 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-31 16:30:57.416  4030  4030 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 16:30:57.416  4030  4030 I GAv4    :   adb logcat -s GAv4
,03-31 16:30:57.434  4030  4030 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:30:57.443  4030  4030 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:30:57.449  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.449  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:57.461  4030  4085 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-31 16:30:57.461  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:57.466  4051  4088 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.466  4051  4088 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.466  4051  4088 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:57.468  4030  4030 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-31 16:30:57.470  4051  4088 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,03-31 16:30:57.472   823  2128 I ActivityManager: Killing 3148:com.google.android.talk/u0a61 (adj 15): empty #17
,03-31 16:30:57.485  4030  4085 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:57.485  4030  4085 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-31 16:30:57.485  4030  4085 E GAv4    : Opening the database failed, dropping the table and recreating it
,03-31 16:30:57.485  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:57.486  4030  4085 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:57.486  4030  4085 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-31 16:30:57.487  4030  4085 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-31 16:30:57.487  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.487  4030  4085 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.488  4030  4085 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-31 16:30:57.488  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at ael.a(PG:1521)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-31 16:30:57.488  4030  4089 E SQLiteDatabase: 	at aen.run(PG:536)
03-31 16:30:57.488  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:57.512  1244  3899 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-31 16:30:57.512  1244  3899 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-31 16:30:57.578  4051  4083 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:57.578  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.e.k.run(SourceFile:388)
,03-31 16:30:57.579  4051  4083 E GAv4-SVC: Opening the database failed, dropping the table and recreating it
03-31 16:30:57.579  4051  4083 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.580  4051  4094 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:57.587  4051  4083 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:57.587  4051  4083 E SQLiteDatabase: 	at com.google.android.gms.e.k.run(SourceFile:388)
03-31 16:30:57.589  4051  4083 E GAv4-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-31 16:30:57.591  4051  4094 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:57.594  4030  4095 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at ael.a(PG:1521)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at aej.c(PG:139)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at aej.b(PG:398)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at agf.f(PG:417)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at oe.run(PG:1112)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.594  4030  4095 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.595  4030  4095 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:57.597  4051  4098 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329),
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.597  4051  4098 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:57.598  1244  3899 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-31 16:30:57.598  1244  3899 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-31 16:30:57.600  4051  4098 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #3
03-31 16:30:57.600  4051  4098 E AndroidRuntime: Process: com.google.android.gms, PID: 4051
03-31 16:30:57.600  4051  4098 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:57.600  4051  4098 E AndroidRuntime: 	... 4 more
03-31 16:30:57.602  4051  4083 W GAv4-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.605  4030  4085 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.606  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.606  4030  4085 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.607  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.610  4051  4094 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.611  4030  4085 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.611   823  4100 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:30:57.611   823  4100 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:57.611   823  4100 E DropBoxManagerService: 	... 5 more
03-31 16:30:57.611  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.612  4030  4085 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.612  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.612  4030  4085 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.613  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.614  4051  4083 E GAv4-SVC: Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.614  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.614  4051  4094 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.615  4030  4085 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.617  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.617  4030  4085 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.618  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.619  4030  4085 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.620  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.621  4030  4089 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:57.621  4030  4096 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:30:57.621  4030  4096 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-31 16:30:57.621  4030  4084 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-31 16:30:57.622  4030  4089 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
03-31 16:30:57.625  1244  3899 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-31 16:30:57.625  1244  3899 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-31 16:30:57.626  1244  3899 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-31 16:30:57.626  1244  3899 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-31 16:30:57.660   823   823 I ActivityManager: Start proc 4103:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
03-31 16:30:57.660   823  1341 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
03-31 16:30:57.662   823  1341 V WindowManager: addAppToken: AppWindowToken{2063e2d5 token=Token{2706ab8c ActivityRecord{21bed8bf u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t18}}} to stack=1 task=18 at 0
03-31 16:30:57.664  4030  4089 I Process : Sending signal. PID: 4030 SIG: 9
,03-31 16:30:57.665   255   255 E lowmemorykiller: Error writing /proc/4030/oom_score_adj; errno=22
03-31 16:30:57.666   823  1338 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-31 16:30:57.667   823  1338 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
03-31 16:30:57.667   823  1338 W ActivityManager: android.os.TransactionTooLargeException
03-31 16:30:57.667   823  1338 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
03-31 16:30:57.667   823  1338 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 16:30:57.851   823  1338 I ActivityManager: Start proc 4120:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,03-31 16:30:57.869   823  1676 W ActivityManager: Spurious death for ProcessRecord{3004ddcf 4120:com.google.android.apps.docs/u0a46}, curProc for 4030: null
,03-31 16:30:57.872  1378  1684 W OpenGLRenderer: Incorrectly called buildLayer on View: ew, destroying layer...
,03-31 16:30:57.888   875   875 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-31 16:30:57.888   875   875 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-31 16:30:57.933  4051  4097 I Icing   : Storage manager: low false usage 1.98MB avail 20.70GB capacity 22.09GB
,03-31 16:30:57.965  4051  4097 W Icing   : Received bad json for section weights override -- ignoring.
,03-31 16:30:57.967  4051  4139 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,03-31 16:30:57.967  4051  4139 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
03-31 16:30:57.967  4051  4097 W Icing   : Received bad json for corpus context scoring override -- ignoring.
03-31 16:30:57.967  4051  4097 W Icing   : Received bad json for section weights override -- ignoring.
,03-31 16:30:57.968  4051  4097 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-31 16:30:57.971  4103  4103 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 16:30:57.971  4103  4103 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 16:30:57.974   823   841 I ActivityManager: Killing 2387:com.google.android.calendar/u0a37 (adj 15): empty #17
,03-31 16:30:57.975  4103  4103 D AndroidRuntime: Shutting down VM
03-31 16:30:57.977  4103  4103 E AndroidRuntime: FATAL EXCEPTION: main
03-31 16:30:57.977  4103  4103 E AndroidRuntime: Process: com.android.documentsui, PID: 4103
03-31 16:30:57.977  4103  4103 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at com.android.documentsui.PackageR,eceiver.onReceive(PackageReceiver.java:35)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-31 16:30:57.977  4103  4103 E AndroidRuntime: 	... 9 more
,03-31 16:30:58.082   823  4145 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:30:58.082   823  4145 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:58.082   823  4145 E DropBoxManagerService: 	... 5 more
,03-31 16:30:58.094  1721  2282 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10095)] disk I/O error
,03-31 16:30:58.099  1721  2282 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
03-31 16:30:58.099  1721  2282 E AndroidRuntime: Process: android.process.media, PID: 1721
03-31 16:30:58.099  1721  2282 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:30:58.099  1721  2282 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:30:58.125   823  1019 I ActivityManager: Start proc 4146:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-31 16:30:58.136   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 10.863ms
,03-31 16:30:58.143   823  4158 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:30:58.143   823  4158 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:30:58.143   823  4158 E DropBoxManagerService: 	... 5 more
,03-31 16:30:58.154   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 17.304ms
,03-31 16:30:58.158  1131  2538 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
03-31 16:30:58.159   823  1366 I ActivityManager: Killing 3659:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-31 16:30:58.164  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
03-31 16:30:58.164  4051  4097 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
03-31 16:30:58.164  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
03-31 16:30:58.164  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-31 16:30:58.164  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
03-31 16:30:58.164  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-31 16:30:58.164  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
03-31 16:30:58.164  4051  4097 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
03-31 16:30:58.165  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Trie initialize fail
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-31 16:30:58.165  4051  4097 E Icing   : Init docstore failed
03-31 16:30:58.165  4051  4097 E Icing   : Index init failed, resetting corpora
,03-31 16:30:58.169   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 13.705ms
,03-31 16:30:58.190  4120  4120 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-31 16:30:58.190  4120  4120 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 16:30:58.190  4120  4120 I GAv4    :   adb logcat -s GAv4
,03-31 16:30:58.293  4120  4120 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 16:30:58.300  1131  1131 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 16:30:58.310  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:58.311  4120  4120 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-31 16:30:58.311  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:58.315  4051  4051 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 16:30:58.316  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
03-31 16:30:58.316  4051  4097 E Icing   : Clearing index failed
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-31 16:30:58.317  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
,03-31 16:30:58.320  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-31 16:30:58.320  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-31 16:30:58.320  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-31 16:30:58.320  4051  4097 E Icing   : Clearing docstore failed
,03-31 16:30:58.320  4051  4097 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
03-31 16:30:58.320  4051  4097 E Icing   : Deleting compact status failed
,03-31 16:30:58.323  4120  4172 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-31 16:30:58.324  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:58.327  4120  4172 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.327  4120  4172 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-31 16:30:58.327  4120  4172 E GAv4    : Opening the database failed, dropping the table and recreating it
03-31 16:30:58.327  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:58.328  4120  4120 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.329  4120  4172 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,03-31 16:30:58.329  4120  4172 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.330  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.331  4120  4172 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-31 16:30:58.332  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.332  4120  4172 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.332  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 16:30:58.345   823  1341 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2c84a3b}
,03-31 16:30:58.347  4146  4146 D ExternalStorage: After updating volumes, found 1 active roots
03-31 16:30:58.348  3765  3765 D WearableService: callingUid 10011, callindPid: 3765
,03-31 16:30:58.352  4120  4173 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at ael.a(PG:1521)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-31 16:30:58.352  4120  4173 E SQLiteDatabase: 	at aen.run(PG:536)
,03-31 16:30:58.357  1820  2120 E MDM     : [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 16:30:58.405  4051  4178 D LocationInitializer: Restart initialization of location
,03-31 16:30:58.415  4120  4182 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at ael.a(PG:1521)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at aej.c(PG:139)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at aej.b(PG:398)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at agf.f(PG:417)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at oe.run(PG:1112)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.415  4120  4182 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.417  4120  4182 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:58.432  4120  4185 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 16:30:58.432  4120  4185 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 16:30:58.451  4120  4185 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 16:30:58.474   823  1151 I art     : Explicit concurrent mark sweep GC freed 24457(1330KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.507ms total 51.323ms
,03-31 16:30:58.486  4120  4185 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 16:30:58.492  1131  4190 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.492  1131  4190 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	a,t android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.492  1131  4190 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.493  1131  4190 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
03-31 16:30:58.493  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.494  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.495  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.496  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.500  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.502  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.505  4120  4120 E ErrorNotificationActivity: Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
03-31 16:30:58.505  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.505  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.508  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.509  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.511  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.512  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.513  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.514  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.516  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.516  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.517  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.520  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.520  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.521  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.522  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.523  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.524  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.525  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.526  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.527  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:58.529  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.529  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.531  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.531  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.533  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.533  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.534  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.535  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.536  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.537  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.538  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.539  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.541  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.542  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.542  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.543  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.543  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.544  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.544  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.545  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.545  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.546  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.546  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.547  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.548  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.548  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.549  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.549  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.550  4120  4195 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 16:30:58.550  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.551  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.551  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.552  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.552  4120  4120 D Atlas   : Validating map...
03-31 16:30:58.553  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.553  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.553  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102),
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.554  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.554  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.555  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.556   823  1676 V WindowManager: Adding window Window{1d9d29a1 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 11 (after Window{383a7786 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 16:30:58.561   823   841 V WindowManager: Adding window Window{1e3f0387 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 12 (before Window{1d9d29a1 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
03-31 16:30:58.563  4120  4172 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.563  4120  4172 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.563  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.563  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.564  4120  4172 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.564  4120  4172 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.564  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.564  4120  4172 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.565  4120  4172 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.565  4120  4172 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.565  4120  4172 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.565  4120  4173 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.565  4120  4171 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-31 16:30:58.566  4120  4173 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
03-31 16:30:58.573   823  1338 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
03-31 16:30:58.576  4120  4173 I Process : Sending signal. PID: 4120 SIG: 9
,03-31 16:30:58.672   823  1151 I WindowState: WIN DEATH: Window{1e3f0387 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity},
03-31 16:30:58.673   823  1008 W InputDispatcher: channel '1d9d29a1 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9,
03-31 16:30:58.673   823  1008 E InputDispatcher: channel '1d9d29a1 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,03-31 16:30:58.675   823  4170 I ActivityManager: Process com.google.android.apps.docs (pid 4120) has died
03-31 16:30:58.677   823  4170 W ActivityManager: Force removing ActivityRecord{21bed8bf u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t18}: app died, no saved state
03-31 16:30:58.678  4103  4142 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@3d5e836b
03-31 16:30:58.678   823  4170 W InputDispatcher: Attempted to unregister already unregistered input channel '1d9d29a1 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,03-31 16:30:58.687   823  1366 W WindowManager: Failed looking up window,
03-31 16:30:58.687   823  1366 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@3408de08 does not exist
03-31 16:30:58.687   823  1366 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
03-31 16:30:58.687   823  1366 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
03-31 16:30:58.687   823  1366 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
03-31 16:30:58.687   823  1366 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
03-31 16:30:58.687   823  1366 I WindowState: WIN DEATH: null
,03-31 16:30:58.711  4103  4142 W Documents: Failed to load some roots from com.google.android.apps.docs.storage: android.os.DeadObjectException
03-31 16:30:58.711  4103  4142 D Documents: Update found 6 roots in 746ms
,03-31 16:30:58.862  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.863  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-31 16:30:58.864  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoo,lExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.865  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:58.870  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.871  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:58.872  1131  4190 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 16:30:58.872  1131  4190 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 16:30:58.889   875   875 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-31 16:30:58.889   875   875 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-31 16:30:59.891   875   875 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-31 16:30:59.891   875   875 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-31 16:31:00.892   875   875 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-31 16:31:00.893   875   875 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-31 16:31:01.500  1131  1131 I ConfigService: onDestroy
,03-31 16:31:01.529  1541  4201 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 16:31:01.894   875   875 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-31 16:31:01.894   875   875 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
,03-31 16:31:01.895   875   875 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,03-31 16:31:01.896   875   875 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 16:31:02.138   823  1287 E QMI_FW  : xport_send: Sendto failed for port 3840
03-31 16:31:02.138   823  1287 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-31 16:31:02.138   823  1287 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660384531
03-31 16:31:02.138   823  1287 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 16:31:02.143   258   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
