#### Test 648991491c812df_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
,04-01 09:13:08.352   823   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
04-01 09:13:08.374   823   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
04-01 09:13:08.413   279  1708 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
04-01 09:13:08.650  3271  3271 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 09:13:08.653  3271  3271 D AndroidRuntime: CheckJNI is OFF
04-01 09:13:08.798  3271  3271 D AndroidRuntime: Calling main entry com.android.commands.am.Am
04-01 09:13:08.803   823   841 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-01 09:13:08.810   823   841 V WindowManager: addAppToken: AppWindowToken{7a70658 token=Token{39c7ef3b ActivityRecord{c9731ca u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
04-01 09:13:08.812  3271  3271 D AndroidRuntime: Shutting down VM
04-01 09:13:08.818  1514  1765 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3f8eb56d
04-01 09:13:08.819  1514  1514 I HotwordDetector: Closing mic
04-01 09:13:08.830   823   859 V WindowManager: Adding window Window{24370ab3 u0 Starting com.test.thalitest} at 2 of 7 (after Window{24042e0d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-01 09:13:08.859   823  1100 I ActivityManager: Start proc 3288:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
04-01 09:13:08.863   357  1781 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-01 09:13:08.866   357  1781 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-01 09:13:08.878   357  1019 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
04-01 09:13:08.883  1514  1778 I HotwordRecognitionRnr: Hotword detection finished
04-01 09:13:08.884  1514  1777 I HotwordRecognitionRnr: Stopping hotword detection.
04-01 09:13:08.938   823   841 I ActivityManager: Killing 2875:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
04-01 09:13:09.012   823  1277 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660466451
04-01 09:13:09.012   823  1277 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
04-01 09:13:09.013   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
04-01 09:13:09.013   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
04-01 09:13:09.013   823   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
04-01 09:13:09.017   823   823 V ActivityManager: Display changed displayId=0
,04-01 09:13:09.047   823   841 I ActivityManager: Killing 2707:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,04-01 09:13:09.098   872   872 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
04-01 09:13:09.099   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,04-01 09:13:09.139   872   872 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
04-01 09:13:09.140   872   872 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,04-01 09:13:09.221  3288  3288 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,04-01 09:13:09.277   279   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,04-01 09:13:09.280   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,04-01 09:13:09.282   823  1046 D SurfaceControl: Excessive delay in setPowerMode(): 269ms
,04-01 09:13:09.312   823   861 I DreamManagerService: Entering dreamland.
04-01 09:13:09.314   823   861 I PowerManagerService: Dozing...
04-01 09:13:09.314   823   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,04-01 09:13:09.325   357   357 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
04-01 09:13:09.329   357   357 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,04-01 09:13:09.333  3288  3288 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 3867-3880)
,04-01 09:13:09.334  3288  3288 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 09:13:09.337   823  1026 E WifiStateMachine: cancelDelayedScan -> 16
,04-01 09:13:09.341   823  1026 E native  : do suspend false
,04-01 09:13:09.349  3288  3288 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19f4909}
04-01 09:13:09.349  3288  3288 I LibraryLoader: Expected native library version number "",actual native library version number ""
04-01 09:13:09.349  3288  3288 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,04-01 09:13:09.363  3288  3288 I BrowserStartupController: Initializing chromium process, singleProcess=true
,04-01 09:13:09.363  3288  3288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 09:13:09.364  3288  3288 E SysUtils: ApplicationContext is null in ApplicationStatus
,04-01 09:13:09.370  3288  3312 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,04-01 09:13:09.375  3288  3288 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,04-01 09:13:09.379  3288  3288 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 09:13:09.379  3288  3288 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 09:13:09.379  3288  3288 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,04-01 09:13:09.432   823  1026 E WifiStateMachine: cancelDelayedScan -> 18
,04-01 09:13:09.437   823   858 D BluetoothManagerService: Message: 20
,04-01 09:13:09.437   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b79de91:true
,04-01 09:13:09.461  3288  3288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 09:13:09.468  3288  3288 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 09:13:09.478  3288  3288 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,04-01 09:13:09.482  3288  3288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
04-01 09:13:09.483  3288  3288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 09:13:09.484   823  1026 E native  : do suspend true
,04-01 09:13:09.490   357   357 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
04-01 09:13:09.490   357   357 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,04-01 09:13:09.504  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:09.531  3288  3336 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 09:13:09.535  3288  3288 D Atlas   : Validating map...
,04-01 09:13:09.543   823  1026 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,04-01 09:13:09.545   823  1377 V WindowManager: Adding window Window{1014d3df u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{24370ab3 u0 Starting com.test.thalitest})
,04-01 09:13:09.547  1261  1276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
04-01 09:13:09.547  1261  1276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:09.547  1261  1276 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:09.547  1261  1276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
04-01 09:13:09.547  3288  3322 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,04-01 09:13:09.550  1261  1276 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:09.563  2749  2749 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,04-01 09:13:09.565  2749  2749 D Finsky  : [1] 5.onFinished: Installation state replication failed.
04-01 09:13:09.565  2749  2749 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,04-01 09:13:09.581  3288  3336 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 09:13:09.586  3288  3336 D OpenGLRenderer: Enabling debug mode 0
,04-01 09:13:09.635   823   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +817ms
,04-01 09:13:09.641  3288  3288 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-01 09:13:09.642  1237  1237 I Keyboard.Facilitator: onFinishInput()
,04-01 09:13:09.643  3288  3288 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3288
,04-01 09:13:09.733  3288  3288 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 09:13:09.892  3288  3337 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576313216
,04-01 09:13:09.898  3288  3337 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 09:13:09.898  3288  3337 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 09:13:09.898  3288  3337 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 09:13:09.898  3288  3337 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 09:13:09.898  3288  3337 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 09:13:09.898  3288  3337 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2567197a added. We now have 1 listener(s)
,04-01 09:13:09.898   823  1184 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 09:13:09.901  3288  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,04-01 09:13:09.902  3288  3337 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,04-01 09:13:09.903  3288  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,04-01 09:13:09.903  3288  3337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,04-01 09:13:09.906  3288  3337 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c321 added. We now have 1 listener(s)
04-01 09:13:09.906  3288  3337 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 09:13:09.910   823  1027 D WifiService: New client listening to asynchronous messages
,04-01 09:13:09.934  3288  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,04-01 09:13:09.938  3288  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
04-01 09:13:09.938  3288  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
04-01 09:13:09.938  3288  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
04-01 09:13:09.939  3288  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,04-01 09:13:09.942  3288  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-01 09:13:09.942   823  1184 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 09:13:09.954  3288  3337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
04-01 09:13:09.958  3288  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
04-01 09:13:09.959  3288  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,04-01 09:13:09.959  3288  3337 D io.jxcore.node.ConnectivityMonitor: start: OK
04-01 09:13:09.959  3288  3337 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-01 09:13:09.960  3288  3288 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 09:13:09.978  3288  3288 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 09:13:10.133   872   872 I kickstart: STATUS: Received file 'm9kefs2'
04-01 09:13:10.134   872   872 I kickstart: STATUS: 950272 bytes transferred in 0.993651 seconds
04-01 09:13:10.134   872   872 I kickstart: STATUS: Successfully downloaded files from target 
04-01 09:13:10.134   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,04-01 09:13:10.137   872   872 I kickstart: STATUS: Sahara protocol completed,
,04-01 09:13:10.561  3288  3345 W jxcore-log: Initializing JXcore engine,
,04-01 09:13:10.561  3288  3345 W jxcore-log: JXcore engine is ready
,04-01 09:13:10.587  3345  3345 W Thread-349: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12900]" dev="sockfs" ino=12900 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
04-01 09:13:10.587  3345  3345 W Thread-349: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,04-01 09:13:10.587  3345  3345 W Thread-349: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9701]" dev="sockfs" ino=9701 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
04-01 09:13:10.587  3345  3345 W Thread-349: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21567]" dev="sockfs" ino=21567 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,04-01 09:13:10.611  3288  3345 W jxcore-log: Starting JXcore engine
,04-01 09:13:10.689  3288  3345 W jxcore-log: Platform android
04-01 09:13:10.689  3288  3345 W jxcore-log: 
,04-01 09:13:10.689  3288  3345 W jxcore-log: Process ARCH arm
04-01 09:13:10.689  3288  3345 W jxcore-log: 
,04-01 09:13:10.769   823  1026 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,04-01 09:13:10.883  3288  3345 I jxcore-log: JXcore Cordova bridge is ready!
04-01 09:13:10.883  3288  3345 I jxcore-log: 
04-01 09:13:10.883  3288  3345 W jxcore-log: JXcore engine is started
,04-01 09:13:10.893  3288  3337 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 09:13:10.897  3288  3288 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,04-01 09:13:11.904  1141  1141 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,04-01 09:13:12.325  1141  1141 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,04-01 09:13:12.359  1141  1141 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,04-01 09:13:12.359  1141  1141 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,04-01 09:13:12.388   823  1026 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
04-01 09:13:12.388   823  1026 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,04-01 09:13:12.390   823  1028 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,04-01 09:13:12.393   823  1026 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,04-01 09:13:12.401   353   798 D CommandListener: Setting iface cfg
,04-01 09:13:12.412   823  1026 E WifiStateMachine: Start Dhcp Watchdog 1
,04-01 09:13:12.424   823  1026 E WifiStateMachine:  WifiLinkLayerStats: 
,04-01 09:13:12.424   823  1026 E WifiStateMachine:  my bss beacon rx: 1
04-01 09:13:12.424   823  1026 E WifiStateMachine:  RSSI mgmt: -41
04-01 09:13:12.424   823  1026 E WifiStateMachine:  BE :  rx=0 tx=4 lost=0 retries=0
04-01 09:13:12.424   823  1026 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
04-01 09:13:12.424   823  1026 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
04-01 09:13:12.424   823  1026 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
04-01 09:13:12.424   823  1026 E WifiStateMachine:  on_time : 0 tx_time=63 rx_time=110 scan_time=0,
,04-01 09:13:12.512   823  1026 E native  : do suspend false
,04-01 09:13:12.519   823  1026 E WifiStateMachine: scanCount==0 - aborting
,04-01 09:13:12.751  3348  3348 I dhcpcd  : version 5.5.6 starting
,04-01 09:13:12.838  3348  3348 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,04-01 09:13:12.949  3348  3348 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,04-01 09:13:13.035  3348  3348 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,04-01 09:13:13.329   823  1026 E native  : do suspend true
,04-01 09:13:13.352   823  1028 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
04-01 09:13:13.354   823  1028 D ConnectivityService: Adding iface wlan0 to network 100
,04-01 09:13:13.365   823  1026 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,04-01 09:13:13.386   823  1028 E ConnectivityService: Unexpected mtu value: 0, wlan0
,04-01 09:13:13.387   823  1028 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,04-01 09:13:13.388   823  1028 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,04-01 09:13:13.389   823  1028 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100,
,04-01 09:13:13.390   823  1028 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,04-01 09:13:13.398   823  1028 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100],
,04-01 09:13:13.401   823  1028 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100],
,04-01 09:13:13.401   823  3346 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
04-01 09:13:13.401   823  3346 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
,04-01 09:13:13.402   823  3346 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
04-01 09:13:13.402   823  3346 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
04-01 09:13:13.402   823  1028 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100],
04-01 09:13:13.402   823  1028 D ConnectivityService:    accepting network in place of null
,04-01 09:13:13.404   823  1028 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
04-01 09:13:13.405   823  1028 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,04-01 09:13:13.410   823  1028 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,04-01 09:13:13.410   823  1028 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
04-01 09:13:13.411   823  1028 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
04-01 09:13:13.411  1069  1523 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
04-01 09:13:13.411   823  1028 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,04-01 09:13:13.414   823   858 D Tethering: MasterInitialState.processMessage what=3,
,04-01 09:13:13.425   823  1171 V BackupManagerService: Scheduling immediate backup pass
,04-01 09:13:13.427   823   823 V BackupManagerService: Running a backup pass
,04-01 09:13:13.433   823  1045 V BackupManagerService: clearing pending backups
,04-01 09:13:13.440  1514  1514 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 09:13:13.444  3288  3288 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 09:13:13.444  2932  2932 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
04-01 09:13:13.444  3288  3288 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 09:13:13.445   823  1045 V PerformBackupTask: Beginning backup of 14 targets
,04-01 09:13:13.448  2932  2932 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,04-01 09:13:13.452  1366  1585 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
04-01 09:13:13.452  1366  1585 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
04-01 09:13:13.452   823   853 D TelephonyManager: getDataEnabled: retVal=false
,04-01 09:13:13.455   823  1045 D PerformBackupTask: invokeAgentForBackup on @pm@
,04-01 09:13:13.457   823  1045 V BackupServiceBinder: doBackup() invoked
,04-01 09:13:13.459   823  1045 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,04-01 09:13:13.459   823   853 E GpsLocationProvider: No APN found to select.
,04-01 09:13:13.471   823  1045 I BackupRestoreController: Getting widget state for user: 0
,04-01 09:13:13.486   823  1100 I ActivityManager: Start proc 3388:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,04-01 09:13:13.502   369   369 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 321us total 14.793ms
,04-01 09:13:13.512   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 191us total 8.497ms
,04-01 09:13:13.522   823  1304 D AlarmManagerService: Setting time of day to sec=1459494793
04-01 09:13:13.819   823  1304 W AlarmManagerService: Unable to set rtc to 1459494793: Invalid argument
,04-01 09:13:13.830   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 18.629ms
,04-01 09:13:13.833   823  3407 D GpsLocationProvider: NTP server returned: 1459494793819 (Fri Apr 01 09:13:13 GMT+02:00 2016) reference: 168068 certainty: 20 system time offset: -14
,04-01 09:13:13.861  1841  1857 W GmsBackupTransport: Unknown package in backup request: @pm@
,04-01 09:13:13.862  1841  1857 V GmsBackupTransport: starting performBackup for @pm@
04-01 09:13:13.865  1841  1857 V GmsBackupTransport: performBackup done for @pm@
,04-01 09:13:13.879  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:13.900   823  3346 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Apr 2016 07:13:13 GMT], X-Android-Received-Millis=[1459494793900], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459494793851]}
04-01 09:13:13.901   823  3346 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
,04-01 09:13:13.901   823  1028 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
04-01 09:13:13.901   823  1028 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
04-01 09:13:13.901   823  1028 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
04-01 09:13:13.902   823  1028 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
04-01 09:13:13.902   823  1028 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
04-01 09:13:13.902   823  1028 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
04-01 09:13:13.902  1069  1523 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-01 09:13:13.908  1261  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
04-01 09:13:13.908  1261  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:13.908  1261  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:13.908  1261  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:13.924   823  1171 I ActivityManager: Start proc 3421:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,04-01 09:13:13.929  1261  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:13.956   823  1184 I art     : Explicit concurrent mark sweep GC freed 59593(3MB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.587ms total 73.004ms
,04-01 09:13:13.957  1261  2558 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 09:13:13.957  1261  2558 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 09:13:13.957  1261  2558 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 09:13:13.957  1261  2558 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
04-01 09:13:13.957  1261  2558 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
04-01 09:13:13.957  1261  2558 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
04-01 09:13:13.957  1261  2558 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,04-01 09:13:13.963  1841  1899 W GmsBackupTransport: Error sending final backup to server: 
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
04-01 09:13:13.963  1841  1899 W GmsBackupTransport: 	... 1 more
04-01 09:13:13.964   823  1045 D BackupManagerService: Now staging backup of com.google.android.talk
,04-01 09:13:13.982  3421  3421 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
04-01 09:13:13.992  3421  3421 D SprintDMHelper: simOperator:  IMSI: null
04-01 09:13:13.997   823  1045 D BackupManagerService: Now staging backup of com.google.android.dialer
04-01 09:13:13.999  3421  3421 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,04-01 09:13:14.002   823  1045 D BackupManagerService: Now staging backup of com.android.providers.settings
,04-01 09:13:14.015   823  1045 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,04-01 09:13:14.019   823  1045 D BackupManagerService: Now staging backup of com.google.android.gm
,04-01 09:13:14.022   823  1045 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,04-01 09:13:14.025   823  1045 D BackupManagerService: Now staging backup of com.android.nfc
,04-01 09:13:14.027   823  1045 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,04-01 09:13:14.029   823  1045 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,04-01 09:13:14.031   823  1045 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,04-01 09:13:14.033   823  1045 D BackupManagerService: Now staging backup of com.google.android.calendar
,04-01 09:13:14.034   823  1045 D BackupManagerService: Now staging backup of com.android.vending
,04-01 09:13:14.040   823  1045 D BackupManagerService: Now staging backup of android
,04-01 09:13:14.042   823  1045 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,04-01 09:13:14.046  1841  1899 I GmsBackupTransport: Next backup will happen in 43199914 millis.
,04-01 09:13:14.048   823  1045 I BackupManagerService: Backup pass finished.
,04-01 09:13:14.061  1802  3443 W DriveInitializer: Background init thread started
04-01 09:13:14.062  1802  1802 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,04-01 09:13:14.073  1802  1802 D SystemUpdateService: onCreate
,04-01 09:13:14.075  1802  1802 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,04-01 09:13:14.090  1802  3444 I SystemUpdateService: active receiver: enabled
,04-01 09:13:14.092  1802  3447 W DriveInitializer: Awaiting to be initialized
,04-01 09:13:14.100  1802  3444 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,04-01 09:13:14.120  1802  3444 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
04-01 09:13:14.120  1802  3444 I SystemUpdateService: now status is 0 (complete)
04-01 09:13:14.120  1802  3444 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
04-01 09:13:14.120  1802  3444 I SystemUpdateService: file has been verified
04-01 09:13:14.120  1802  3444 I SystemUpdateService: OTA package size = 25802302
,04-01 09:13:14.129  1802  3454 I iu.SyncManager: SYNC; picasa accounts
,04-01 09:13:14.130  1802  3444 I SystemUpdateService: showing system update notification
,04-01 09:13:14.141  1802  1802 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,04-01 09:13:14.143  1802  1802 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,04-01 09:13:14.152  1802  3454 I iu.UploadsManager: num queued entries: 0
04-01 09:13:14.153  1802  3454 I iu.UploadsManager: num updated entries: 0
04-01 09:13:14.153  1802  3454 I iu.SyncManager: NEXT; no task
,04-01 09:13:14.159   823   853 I ActivityManager: Start proc 3455:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,04-01 09:13:14.192  1802  1802 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
04-01 09:13:14.195  1802  1802 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,04-01 09:13:14.211  1261  1279 I art     : Explicit concurrent mark sweep GC freed 22456(1156KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.511ms total 24.206ms
,04-01 09:13:14.220   823   823 I ValidateNoPeople: skipping global notification
,04-01 09:13:14.241   823  1475 I ActivityManager: Start proc 3481:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,04-01 09:13:14.261  1261  1279 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
04-01 09:13:14.261  1261  1279 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:14.261  1261  1279 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:14.261  1261  1279 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:14.264  1261  1279 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:14.288  3104  3441 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 09:13:14.288  3104  3441 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jdm.a(PG:82)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jcs.o(PG:406)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jcn.a(PG:1379)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jcs.i(PG:143)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at blb.a(PG:3937)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at czp.a(PG:18188)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at czp.a(PG:9081)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at czq.run(PG:1686)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 09:13:14.288  3104  3441 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jdj.a(PG:4091)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jdj.a(PG:1125)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jdm.a(PG:77)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	... 12 more
04-01 09:13:14.288  3104  3441 E HttpOperation: Caused by: faj: BadAuthentication
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at fal.a(PG:38)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	at jdj.a(PG:4089)
04-01 09:13:14.288  3104  3441 E HttpOperation: 	... 14 more
,04-01 09:13:14.371  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
04-01 09:13:14.371  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:14.371  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:14.371  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:14.374  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:14.383  3104  3441 E HttpOperation: [getmobileexperiments] Unexpected exception
04-01 09:13:14.383  3104  3441 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jdm.a(PG:82)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jcs.o(PG:406)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jcn.a(PG:1379)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jcs.i(PG:143)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at hec.a(PG:42)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at hee.a(PG:102)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at czr.a(PG:65)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at kka.a(PG:108)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at czp.a(PG:19176)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at czp.a(PG:9081)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at czq.run(PG:1686)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 09:13:14.383  3104  3441 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jdj.a(PG:4091)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jdj.a(PG:1125)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jdm.a(PG:77)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	... 15 more
04-01 09:13:14.383  3104  3441 E HttpOperation: Caused by: faj: BadAuthentication
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at fal.a(PG:38)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	at jdj.a(PG:4089)
04-01 09:13:14.383  3104  3441 E HttpOperation: 	... 17 more
04-01 09:13:14.383  3104  3441 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 09:13:14.383  3104  3441 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at hec.a(PG:42)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at hee.a(PG:102)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at czr.a(PG:65)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at kka.a(PG:108)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jdj.a(PG:1,125)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	... 15 more
04-01 09:13:14.383  3104  3441 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at fal.a(PG:38)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 09:13:14.383  3104  3441 E ExperimentLoader: 	... 17 more
04-01 09:13:14.404  1802  1802 D SystemUpdateService: onDestroy
04-01 09:13:14.417  1802  3443 W DriveInitializer: Background init thread ended
,04-01 09:13:14.431  3481  3481 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
04-01 09:13:14.431  3481  3481 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 09:13:14.431  3481  3481 I GAv4    :   adb logcat -s GAv4
,04-01 09:13:14.455  3481  3481 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,04-01 09:13:14.470  3481  3481 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,04-01 09:13:14.480  3481  3517 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,04-01 09:13:14.489  3455  3513 V KeepSync: Connecting to GoogleApiClient
,04-01 09:13:14.510   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 39515, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,04-01 09:13:14.510   823  1421 I ActivityManager: Killing 2910:com.android.settings/1000 (adj 15): empty #17
,04-01 09:13:14.537  3170  3477 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,04-01 09:13:14.608  1261  3506 D GCM     : Connected
,04-01 09:13:14.639   823   853 I ActivityManager: Start proc 3521:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,04-01 09:13:14.650  1261  3506 D GCM     : Message class com.google.f.a.a.p
,04-01 09:13:14.661  1802  3519 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 09:13:14.666  1802  3519 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 09:13:14.683  1261  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
04-01 09:13:14.683  1261  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:14.683  1261  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:14.683  1261  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:14.685  1261  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: Handling authorization failure
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 09:13:14.702  1802  3519 E ClientConnectionOperation: 	... 7 more
,04-01 09:13:14.705  3455  3513 V KeepSync: GoogleApiClient failed to connect with error code: 4
,04-01 09:13:14.707  3455  3513 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 09:13:14.710  3455  3513 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
04-01 09:13:14.711  3455  3513 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 09:13:14.748  3481  3481 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,04-01 09:13:14.757  3481  3481 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9006-9007)
04-01 09:13:14.757  3481  3481 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 09:13:14.760  3481  3481 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {262fb864}
,04-01 09:13:14.762  3481  3481 I LibraryLoader: Expected native library version number "",actual native library version number ""
04-01 09:13:14.762  3481  3481 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,04-01 09:13:14.771  3481  3481 I BrowserStartupController: Initializing chromium process, singleProcess=true
,04-01 09:13:14.772  3481  3481 W art     : Attempt to remove local handle scope entry from IRT, ignoring
04-01 09:13:14.773  3481  3481 E SysUtils: ApplicationContext is null in ApplicationStatus
,04-01 09:13:14.787  3481  3481 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,04-01 09:13:14.793  3481  3481 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 09:13:14.793  3481  3481 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 09:13:14.793  3481  3481 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,04-01 09:13:14.798  1261  1915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
04-01 09:13:14.798  1261  1915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:14.799  1261  1915 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:14.799  1261  1915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:14.802  1261  1915 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:14.848  3455  3513 E KeepSync: IOException
04-01 09:13:14.848  3455  3513 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 09:13:14.848  3455  3513 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 09:13:14.848  3455  3513 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 09:13:14.848  3455  3513 E KeepSync: 	... 10 more
04-01 09:13:14.848  3455  3513 W KeepSync: Sync result 2
,04-01 09:13:14.853   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39521, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 09:13:14.859   823  1184 I ActivityManager: Killing 2443:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,04-01 09:13:14.861  3481  3566 W AudioManagerAndroid: Requires BLUETOOTH permission
,04-01 09:13:14.913  3481  3481 I NSApplication: Starting up...
,04-01 09:13:14.939   823  1421 I ActivityManager: Start proc 3572:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
04-01 09:13:14.940   823  1421 I ActivityManager: Killing 2992:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,04-01 09:13:15.288  3521  3521 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,04-01 09:13:15.319  1261  2558 I art     : Explicit concurrent mark sweep GC freed 14213(838KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 957us total 23.882ms
,04-01 09:13:15.325  3521  3521 I BooksApp: Created application version: 3.6.8 (30608)
,04-01 09:13:15.418  3521  3594 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 09:13:15.592   823   842 I ActivityManager: Start proc 3603:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,04-01 09:13:15.593   823   842 I ActivityManager: Killing 3012:com.android.musicfx/u0a18 (adj 15): empty #17
,04-01 09:13:15.604  3521  3614 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,04-01 09:13:15.664   823  1377 I art     : Explicit concurrent mark sweep GC freed 28747(1318KB) AllocSpace objects, 5(122KB) LOS objects, 32% free, 33MB/49MB, paused 1.229ms total 48.242ms
,04-01 09:13:15.715  1261  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
04-01 09:13:15.715  1261  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:15.715  1261  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:15.715  1261  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:15.718  1261  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 09:13:15.761  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
04-01 09:13:15.761  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:15.761  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:15.762  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:15.765  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 09:13:15.773  3521  3614 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
04-01 09:13:15.775  3521  3594 E BooksSync: Soft error,
04-01 09:13:15.775  3521  3594 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 09:13:15.775  3521  3594 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 09:13:15.775  3521  3594 E BooksSync: Sync error
04-01 09:13:15.775  3521  3594 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 09:13:15.775  3521  3594 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 09:13:15.775  3521  3594 I BooksSync: Finished books sync
,04-01 09:13:15.783   823   841 I ActivityManager: Killing 1425:android.process.acore/u0a5 (adj 15): empty #17
,04-01 09:13:15.784   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39521, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 09:13:15.993   823   841 I ActivityManager: Killing 3061:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,04-01 09:13:16.437   823  1100 I ActivityManager: Killing 2809:com.google.android.gm/u0a78 (adj 15): empty #17
,04-01 09:13:16.599   823   841 I ActivityManager: Start proc 3624:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,04-01 09:13:16.664  3624  3624 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459494796664
,04-01 09:13:16.664  3624  3624 D         : TimeServiceNative: User Time to be set is 1459494796664
04-01 09:13:16.664  3624  3624 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
04-01 09:13:16.664  3624  3624 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
04-01 09:13:16.664  3624  3624 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459494796664
04-01 09:13:16.664  3624  3624 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
04-01 09:13:16.664   372   878 D QC-time-services: Daemon: Connection accepted:time_genoff
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459494796664
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459494796664, operation = 0
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/18/70 3:24:54,
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:Value read from RTC seconds = 19797894000
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:new time 1459494796664 
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon: delta 1439696902664 genoff 1439696902664 
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696902664 to memory
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:Opening File: /data/time/ats_2
04-01 09:13:16.665   372  3641 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 09:13:16.666   372  3641 D QC-time-services: Updating the TOD offset,
04-01 09:13:16.666   372  3641 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696902664 to memory
04-01 09:13:16.666   372  3641 D QC-time-services: Daemon:Opening File: /data/time/ats_1
04-01 09:13:16.666   372  3641 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 09:13:16.668   372  3641 E QC-time-services: Daemon:Update to modem bit set
,04-01 09:13:16.668   372  3641 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
04-01 09:13:16.668   372  3641 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143529996664
04-01 09:13:16.669  3624  3624 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,04-01 09:13:16.738   372   878 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,04-01 09:13:16.743   372   876 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,04-01 09:13:16.748   823  1100 I ActivityManager: Start proc 3643:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,04-01 09:13:16.760   823  1377 I ActivityManager: Killing 3032:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,04-01 09:13:17.026  3643  3643 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
04-01 09:13:17.026  3643  3643 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 09:13:17.026  3643  3643 I GAv4    :   adb logcat -s GAv4
,04-01 09:13:17.042  3643  3643 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,04-01 09:13:17.055  3643  3643 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,04-01 09:13:17.076  3643  3662 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,04-01 09:13:17.107   823  1377 I ActivityManager: Killing 3143:com.android.providers.calendar/u0a3 (adj 15): empty #17
,04-01 09:13:17.422  1802  1802 V Herrevad: NQAS connected
,04-01 09:13:17.428  3170  3170 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 09:13:17.429  3170  3170 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 09:13:17.438   823  1027 D WifiService: New client listening to asynchronous messages
,04-01 09:13:17.472   823  1421 I ActivityManager: Start proc 3673:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,04-01 09:13:17.504  3673  3673 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-01 09:13:17.536  3673  3673 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@3ddbba10(com.android.providers.calendar.CalendarProvider2@19f4909)
,04-01 09:13:17.592  1261  1915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,04-01 09:13:17.592  1261  1915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:17.592  1261  1915 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:17.592  1261  1915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:17.595  1261  1915 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:17.605  3170  3670 E Babel   : UserRecoverableAuthException.
,04-01 09:13:17.605  3170  3670 E Babel   : eei: BadAuthentication
04-01 09:13:17.605  3170  3670 E Babel   : 	at eeg.a(Unknown Source)
04-01 09:13:17.605  3170  3670 E Babel   : 	at eeg.a(Unknown Source)
04-01 09:13:17.605  3170  3670 E Babel   : 	at eeg.a(Unknown Source)
04-01 09:13:17.605  3170  3670 E Babel   : 	at g.a(Unknown Source)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cae.a(SourceFile:3089)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cae.a(SourceFile:1131)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cws.a(SourceFile:4333)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cws.a(SourceFile:1419)
04-01 09:13:17.605  3170  3670 E Babel   : 	at crl.a(SourceFile:492)
04-01 09:13:17.605  3170  3670 E Babel   : 	at crl.a(SourceFile:1468)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cqu.a(SourceFile:4416)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cas.b(SourceFile:106)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cap.d(SourceFile:335)
04-01 09:13:17.605  3170  3670 E Babel   : 	at caq.run(SourceFile:81)
04-01 09:13:17.605  3170  3670 E Babel   : Error getting auth token
04-01 09:13:17.605  3170  3670 E Babel   : dvm
04-01 09:13:17.605  3170  3670 E Babel   : 	at g.a(Unknown Source)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cae.a(SourceFile:3089)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cae.a(SourceFile:1131)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cws.a(SourceFile:4333)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cws.a(SourceFile:1419)
04-01 09:13:17.605  3170  3670 E Babel   : 	at crl.a(SourceFile:492)
04-01 09:13:17.605  3170  3670 E Babel   : 	at crl.a(SourceFile:1468)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cqu.a(SourceFile:4416)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cas.b(SourceFile:106)
04-01 09:13:17.605  3170  3670 E Babel   : 	at cap.d(SourceFile:335)
04-01 09:13:17.605  3170  3670 E Babel   : 	at caq.run(SourceFile:81)
,04-01 09:13:17.607  3170  3670 E Babel   : Account registration failed 1-Redacted-21
,04-01 09:13:17.608  3170  3670 E Babel   : cyp: null -- null
04-01 09:13:17.608  3170  3670 E Babel   : 	at cae.a(SourceFile:3121)
04-01 09:13:17.608  3170  3670 E Babel   : 	at cae.a(SourceFile:1131)
04-01 09:13:17.608  3170  3670 E Babel   : 	at cws.a(SourceFile:4333)
04-01 09:13:17.608  3170  3670 E Babel   : 	at cws.a(SourceFile:1419)
04-01 09:13:17.608  3170  3670 E Babel   : 	at crl.a(SourceFile:492)
04-01 09:13:17.608  3170  3670 E Babel   : 	at crl.a(SourceFile:1468)
04-01 09:13:17.608  3170  3670 E Babel   : 	at cqu.a(SourceFile:4416)
04-01 09:13:17.608  3170  3670 E Babel   : 	at cas.b(SourceFile:106)
04-01 09:13:17.608  3170  3670 E Babel   : 	at cap.d(SourceFile:335)
04-01 09:13:17.608  3170  3670 E Babel   : 	at caq.run(SourceFile:81)
,04-01 09:13:17.616  3170  3670 I art     : Note: end time exceeds epoch: 
,04-01 09:13:17.629  1261  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
04-01 09:13:17.629  1261  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:17.629  1261  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:17.629  1261  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:17.632  1261  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:17.642  1261  1724 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,04-01 09:13:17.656  3170  3697 E Babel   : Unexpected exception while authenticating.
,04-01 09:13:17.660  3170  3697 E Babel   : eej: User intervention required. Notification has been pushed.
04-01 09:13:17.660  3170  3697 E Babel   : 	at eeg.b(Unknown Source)
04-01 09:13:17.660  3170  3697 E Babel   : 	at eeg.b(Unknown Source)
04-01 09:13:17.660  3170  3697 E Babel   : 	at g.a(Unknown Source)
04-01 09:13:17.660  3170  3697 E Babel   : 	at cae.b(SourceFile:1146)
04-01 09:13:17.660  3170  3697 E Babel   : 	at dcg.run(SourceFile:5617)
04-01 09:13:17.660  3170  3697 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:17.660  3170  3697 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:17.660  3170  3697 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,04-01 09:13:18.595  3673  3673 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-01 09:13:18.596  3673  3673 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-01 09:13:18.858  3673  3700 E SQLiteLog: (284) automatic index on view_events(_id)
,04-01 09:13:20.292  3521  3592 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,04-01 09:13:20.988  3288  3345 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 09:13:20.988  3288  3345 I jxcore-log: 
,04-01 09:13:20.991  3288  3345 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 09:13:20.991  3288  3345 I jxcore-log: 
,04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 09:13:21.000  3288  3345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 09:13:21.004  3288  3345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-01 09:13:21.006  3288  3345 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 09:13:21.006  3288  3345 I jxcore-log: 
,04-01 09:13:21.008  3288  3345 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 09:13:21.008  3288  3345 I jxcore-log: 
,04-01 09:13:21.521  3288  3345 I jxcore-log: Unit Test app is loaded
04-01 09:13:21.521  3288  3345 I jxcore-log: 
,04-01 09:13:21.528  3288  3345 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 09:13:21.528  3288  3345 I jxcore-log: 
,04-01 09:13:21.532  3288  3345 I jxcore-log: My device name is: motorola-Nexus 6
04-01 09:13:21.532  3288  3345 I jxcore-log: 
04-01 09:13:21.534  3288  3345 I jxcore-log: WARN testUtils: myNameCallback not set!
04-01 09:13:21.534  3288  3345 I jxcore-log: 
,04-01 09:13:21.545  3288  3288 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 09:13:22.826  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:22.939  1261  3709 I VacuumService: Vacuum at: now=1459494802939 tag=VacuumService
,04-01 09:13:23.039  3388  3708 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 09:13:23.084  1261  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,04-01 09:13:23.085  1261  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:23.085  1261  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:23.085  1261  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:23.091  1261  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:23.112  3388  3708 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
04-01 09:13:23.114  3388  3708 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 09:13:23.242   823  1180 I art     : Explicit concurrent mark sweep GC freed 18883(909KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.781ms total 87.433ms
,04-01 09:13:23.317  1261  3710 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-01 09:13:23.329  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:23.777   823  1421 I ActivityManager: Killing 2749:com.android.vending/u0a19 (adj 15): empty #17
,04-01 09:13:23.917  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:24.068  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:24.295  1261  3710 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,04-01 09:13:24.296  1261  3710 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 09:13:24.296  1261  3710 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:24.296  1261  3710 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:24.302  1261  3710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:24.360  1261  3710 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 09:13:24.360  1261  3710 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 09:13:24.360  1261  3710 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 09:13:24.513  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:24.727  1261  3710 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,04-01 09:13:24.728  1261  3710 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:24.728  1261  3710 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 09:13:24.728  1261  3710 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:24.735  1261  3710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:24.810  1261  3710 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 09:13:24.810  1261  3710 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 09:13:24.810  1261  3710 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 09:13:24.943  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:25.075  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:25.354  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:25.442   823  1184 I ActivityManager: Start proc 3713:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,04-01 09:13:25.476  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 09:13:25.476  3288  3345 I jxcore-log: 
,04-01 09:13:25.524  1261  1723 I art     : Explicit concurrent mark sweep GC freed 43887(2MB) AllocSpace objects, 8(580KB) LOS objects, 36% free, 27MB/43MB, paused 1.178ms total 26.440ms
,04-01 09:13:25.559  1261  3710 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,04-01 09:13:25.559  1261  3710 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:25.559  1261  3710 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:25.559  1261  3710 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:25.562  1261  3710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:25.578  3713  3713 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,04-01 09:13:25.580  1261  3710 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 09:13:25.580  1261  3710 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 09:13:25.580  1261  3710 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 09:13:25.624  3713  3713 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,04-01 09:13:25.689   823  1171 I ActivityManager: Start proc 3749:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,04-01 09:13:25.699  3713  3713 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,04-01 09:13:25.704  3713  3713 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,04-01 09:13:25.707   369   369 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 340us total 17.326ms
,04-01 09:13:25.718  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:25.719   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 234us total 11.030ms
,04-01 09:13:25.721  3749  3749 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 09:13:25.721  3749  3749 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 09:13:25.730   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 227us total 10.544ms
,04-01 09:13:25.740  3749  3749 I MultiDex: VM with version 2.1.0 has multidex support
04-01 09:13:25.740  3749  3749 I MultiDex: install
04-01 09:13:25.740  3749  3749 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 09:13:25.756  3749  3749 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,04-01 09:13:25.770   823  1184 I ActivityManager: Killing 2932:com.google.android.music:main/u0a66 (adj 15): empty #17
,04-01 09:13:25.773  3713  3728 D Finsky  : [379] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,04-01 09:13:25.790  3749  3749 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 09:13:25.880  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 09:13:25.880  3288  3345 I jxcore-log: 
,04-01 09:13:25.883  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:25.895  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 09:13:25.895  3288  3345 I jxcore-log: 
,04-01 09:13:25.899  1261  2113 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,04-01 09:13:25.900  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 09:13:25.900  3288  3345 I jxcore-log: 
04-01 09:13:25.904  3713  3713 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
04-01 09:13:25.904  3713  3713 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,04-01 09:13:25.909  1261  1261 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 09:13:25.913  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:25.914  3713  3713 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,04-01 09:13:25.917  1802  1802 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,04-01 09:13:25.930  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 09:13:25.930  3288  3345 I jxcore-log: 
,04-01 09:13:25.936  1261  1279 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 09:13:25.936  1261  1279 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:25.936  1261  1279 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:25.936  1261  1279 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:25.938  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 09:13:25.938  3288  3345 I jxcore-log: 
,04-01 09:13:25.943  3713  3713 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,04-01 09:13:25.971   823  1180 I ActivityManager: Start proc 3777:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,04-01 09:13:25.975  1261  1279 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.028  3777  3777 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 09:13:26.028  3777  3777 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
04-01 09:13:26.029  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:26.030  1802  3794 D LocationInitializer: Restart initialization of location
,04-01 09:13:26.031  3713  3728 D Finsky  : [379] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,04-01 09:13:26.063  3777  3777 I MultiDex: VM with version 2.1.0 has multidex support
04-01 09:13:26.063  3777  3777 I MultiDex: install
04-01 09:13:26.063  3777  3777 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 09:13:26.091  3777  3777 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,04-01 09:13:26.120  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:26.122  3777  3777 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 09:13:26.129  1261  2536 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,04-01 09:13:26.130  1261  1261 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 09:13:26.134  1802  1802 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,04-01 09:13:26.140  3777  3777 D WearableService: callingUid 10011, callindPid: 3777
,04-01 09:13:26.151  1802  3800 D LocationInitializer: Restart initialization of location
,04-01 09:13:26.160  1841  2106 E MDM     : [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,04-01 09:13:26.163  1841  2106 E MDM     : [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,04-01 09:13:26.204  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:26.265  3713  3713 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,04-01 09:13:26.332  1261  3710 W Uploader:  no longer exists, so no auth token.
,04-01 09:13:26.493  1261  3710 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,04-01 09:13:26.493  1261  3710 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 09:13:26.493  1261  3710 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:26.494  1261  3710 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:26.503  1261  3710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.557  1261  3710 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 09:13:26.557  1261  3710 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 09:13:26.557  1261  3710 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 09:13:26.629  3713  3713 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,04-01 09:13:26.650  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.672  1261  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 09:13:26.673  1261  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:26.673  1261  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:26.673  1261  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:26.676  1261  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 09:13:26.690  3713  3713 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,04-01 09:13:26.692  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:26.696  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.716  1261  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,04-01 09:13:26.716  1261  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:26.717  1261  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:26.717  1261  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:26.720  1261  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.741  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.768  1261  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,04-01 09:13:26.769  1261  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 09:13:26.769  1261  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:26.769  1261  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:26.776  1261  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:26.811  3713  3713 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,04-01 09:13:26.842  1261  3710 W Uploader: No account for auth token provided
,04-01 09:13:27.008  1261  3710 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
04-01 09:13:27.008  1261  3710 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:27.008  1261  3710 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:27.008  1261  3710 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:27.012  1261  3710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 09:13:27.052  1261  3710 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 09:13:27.052  1261  3710 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 09:13:27.052  1261  3710 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 09:13:27.083  1261  1261 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:27.109  1261  1915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,04-01 09:13:27.109  1261  1915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 09:13:27.110  1261  1915 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 09:13:27.110  1261  1915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 09:13:27.114  1261  1915 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:13:27.129  3713  3713 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,04-01 09:13:27.131  3713  3713 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,04-01 09:13:27.140  3713  3713 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 09:13:27.144  3713  3713 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 760 minutes (failures=5)
,04-01 09:13:27.170  1841  1899 D DeviceConnectionService: client connected with version: 7571000
,04-01 09:13:28.139  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 09:13:28.139  3288  3345 I jxcore-log: 
,04-01 09:13:28.162  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 09:13:28.162  3288  3345 I jxcore-log: 
,04-01 09:13:28.171  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 09:13:28.171  3288  3345 I jxcore-log: 
,04-01 09:13:28.417  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 09:13:28.417  3288  3345 I jxcore-log: 
,04-01 09:13:28.486  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 09:13:28.486  3288  3345 I jxcore-log: 
,04-01 09:13:28.541  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 09:13:28.541  3288  3345 I jxcore-log: 
,04-01 09:13:28.549  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 09:13:28.549  3288  3345 I jxcore-log: 
,04-01 09:13:28.559  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 09:13:28.559  3288  3345 I jxcore-log: 
,04-01 09:13:28.563  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 09:13:28.563  3288  3345 I jxcore-log: 
,04-01 09:13:28.569  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 09:13:28.569  3288  3345 I jxcore-log: 
,04-01 09:13:28.585  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 09:13:28.585  3288  3345 I jxcore-log: 
,04-01 09:13:28.604  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 09:13:28.604  3288  3345 I jxcore-log: 
,04-01 09:13:28.686  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 09:13:28.686  3288  3345 I jxcore-log: 
,04-01 09:13:28.692  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 09:13:28.692  3288  3345 I jxcore-log: 
,04-01 09:13:28.718  3288  3345 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 09:13:28.718  3288  3345 I jxcore-log: 
,04-01 09:13:28.731  3288  3345 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,04-01 09:13:28.732  3288  3345 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
04-01 09:13:28.732  3288  3345 I jxcore-log: 
,04-01 09:13:29.163  3288  3345 I jxcore-log: TAP version 13
04-01 09:13:29.163  3288  3345 I jxcore-log: 
,04-01 09:13:29.166  3288  3345 I jxcore-log: # setup,
04-01 09:13:29.166  3288  3345 I jxcore-log: 
,04-01 09:13:29.765  3288  3345 I jxcore-log: # name
04-01 09:13:29.765  3288  3345 I jxcore-log: 
,04-01 09:13:29.896  3288  3345 I jxcore-log: ok 1 sane
04-01 09:13:29.896  3288  3345 I jxcore-log: 
,04-01 09:13:29.903  3288  3345 I jxcore-log: # teardown
04-01 09:13:29.903  3288  3345 I jxcore-log: 
,04-01 09:13:30.632  3288  3345 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-01 09:13:30.632  3288  3345 I jxcore-log: 
,04-01 09:13:30.925  3810  3810 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-01 09:13:30.929  3810  3810 D AndroidRuntime: CheckJNI is OFF
,04-01 09:13:31.045  3810  3810 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-01 09:13:31.058   823   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
04-01 09:13:31.058   823   854 I ActivityManager: Killing 3288:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,04-01 09:13:31.147   823   864 W PackageSettings: Skipping PackageSetting{1b8f6bd5 com.example.hello/10273} due to missing metadata
,04-01 09:13:31.203   823   841 I WindowState: WIN DEATH: Window{1014d3df u0 com.test.thalitest/com.test.thalitest.MainActivity}
,04-01 09:13:31.211   823  1027 D WifiService: Client connection lost with reason: 4
,04-01 09:13:31.268   823   854 W ActivityManager: Force removing ActivityRecord{c9731ca u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,04-01 09:13:31.281   823   823 V ActivityManager: Display changed displayId=0
,04-01 09:13:31.307   823   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,04-01 09:13:31.344   823   842 W ActivityManager: Spurious death for ProcessRecord{19ce294f 3288:com.test.thalitest/u0a95}, curProc for 3288: null
,04-01 09:13:31.349   823  1180 I ActivityManager: Killing 3421:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,04-01 09:13:31.354  1069  1069 I art     : Explicit concurrent mark sweep GC freed 48067(2017KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 1.007ms total 28.743ms
04-01 09:13:31.357  1514  1514 I art     : Explicit concurrent mark sweep GC freed 1518(113KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 758us total 46.034ms
,04-01 09:13:31.411   823   823 I art     : Explicit concurrent mark sweep GC freed 26291(1449KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.415ms total 88.084ms
,04-01 09:13:31.459  1237  1237 I Keyboard.Facilitator: resetDictionaries() : en_US,
,04-01 09:13:31.466  2974  2974 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
04-01 09:13:31.468   823  1047 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,04-01 09:13:31.480  1237  3824 I Keyboard.Facilitator.DecoderInitializer: run()
,04-01 09:13:31.483   823  1004 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-01 09:13:31.487  1237  3824 I Decoder : createOrResetDecoder
,04-01 09:13:31.490   823  1421 I ActivityManager: Killing 3481:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,04-01 09:13:31.537   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-01 09:13:31.538   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-01 09:13:31.715  1261  1261 I ConfigService: onCreate
,04-01 09:13:31.768   823  1421 I ActivityManager: Start proc 3828:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,04-01 09:13:31.782   823  1421 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3288 uid 10095
,04-01 09:13:31.792  1237  1237 I Keyboard.Facilitator: onFinishInput()
,04-01 09:13:31.818  1237  3824 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-01 09:13:31.825  1395  1395 D Launcher.Workspace: 11683562 - stripEmptyScreens()
04-01 09:13:31.826  1395  1395 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,04-01 09:13:31.834   823   864 I art     : Explicit concurrent mark sweep GC freed 13277(1108KB) AllocSpace objects, 5(551KB) LOS objects, 32% free, 33MB/49MB, paused 2.349ms total 130.063ms
,04-01 09:13:31.847  1237  3824 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,04-01 09:13:31.849  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-01 09:13:31.849  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-01 09:13:31.851  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-01 09:13:31.851  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,04-01 09:13:31.851  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-01 09:13:31.851  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-01 09:13:31.852  1237  3824 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-01 09:13:31.852  1237  3824 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-01 09:13:31.852  1237  3824 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-01 09:13:31.852  1237  3824 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-01 09:13:31.852  1237  3824 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-01 09:13:31.852  1237  3824 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-01 09:13:31.873  1514  1514 W LocationOracleImpl: Best location was null
,04-01 09:13:31.904  1514  3854 I HotwordRecognitionRnr: Starting hotword detection.
04-01 09:13:31.905  1514  3855 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@163a83d
,04-01 09:13:31.909   357  1019 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,04-01 09:13:31.911  1395  1395 I art     : Explicit concurrent mark sweep GC freed 10823(607KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.308ms total 23.184ms
,04-01 09:13:31.912   357  3857 I AudioFlinger: AudioFlinger's thread 0xb407c000 ready to run
,04-01 09:13:31.916  1514  3855 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@163a83d
,04-01 09:13:31.926   357  3857 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
04-01 09:13:31.926   357  3857 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
04-01 09:13:31.926   357  3857 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
04-01 09:13:31.926   357  3857 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,04-01 09:13:31.933   357  3857 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,04-01 09:13:31.938  3828  3860 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-01 09:13:31.948   823   842 I ActivityManager: Start proc 3861:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-01 09:13:31.953  3828  3847 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,04-01 09:13:31.970  3810  3810 I art     : System.exit called, status: 0
04-01 09:13:31.970  3810  3810 I AndroidRuntime: VM exiting with result code 0.
,04-01 09:13:32.008  1514  1514 I HotwordWorker: onReady
,04-01 09:13:32.029   823   864 I ActivityManager: Start proc 3881:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,04-01 09:13:32.067   823   841 I ActivityManager: Start proc 3902:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-01 09:13:32.073   823   841 I ActivityManager: Killing 3572:com.android.chrome/u0a40 (adj 15): empty #17
,04-01 09:13:32.229   823  1475 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a2253a9}
,04-01 09:13:32.235   823  1026 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.00 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,04-01 09:13:32.243  3902  3902 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-01 09:13:32.255  1261  1261 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,04-01 09:13:32.256  1261  1261 D AndroidRuntime: Shutting down VM
--------- beginning of crash
04-01 09:13:32.257  1261  1261 E AndroidRuntime: FATAL EXCEPTION: main
04-01 09:13:32.257  1261  1261 E AndroidRuntime: Process: com.google.process.gapps, PID: 1261
04-01 09:13:32.257  1261  1261 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
04-01 09:13:32.257  1261  1261 E AndroidRuntime: 	... 9 more
,04-01 09:13:32.265   823  3921 E DropBoxManagerService: Can't write: system_app_crash
04-01 09:13:32.265   823  3921 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: ,	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 09:13:32.265   823  3921 E DropBoxManagerService: 	... 5 more
,04-01 09:13:32.278   823  3924 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 09:13:32.279   823   854 D Atlas   : Validating map...
,04-01 09:13:32.280  3902  3920 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
04-01 09:13:32.280  3902  3920 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
04-01 09:13:32.281  3902  3920 E AndroidRuntime: Process: com.android.keychain, PID: 3902
04-01 09:13:32.281  3902  3920 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.ja,va:791)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-01 09:13:32.281  3902  3920 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: Can't write: system_app_crash
04-01 09:13:32.290   823  3925 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 09:13:32.290   823  3925 E DropBoxManagerService: 	... 5 more
,04-01 09:13:32.317   823  3924 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 09:13:32.326   823  3924 D OpenGLRenderer: Enabling debug mode 0
,04-01 09:13:32.330   823  1277 E QMI_FW  : xport_send: Sendto failed for port 3840
04-01 09:13:32.330   823  1277 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
04-01 09:13:32.330   823  1277 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660466451
04-01 09:13:32.330   823  1277 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,04-01 09:13:32.499   279   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
