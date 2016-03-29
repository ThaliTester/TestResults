#### Test 63998117de3e24f_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-29 16:22:36.986  2160  2225 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-29 16:22:37.257  3256  3256 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 16:22:37.260  3256  3256 D AndroidRuntime: CheckJNI is OFF
03-29 16:22:37.376  3256  3256 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-29 16:22:37.381   823  1159 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-29 16:22:37.402   823  1159 V WindowManager: addAppToken: AppWindowToken{1e523bea token=Token{80317d5 ActivityRecord{3b7d948c u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-29 16:22:37.406  3256  3256 D AndroidRuntime: Shutting down VM
03-29 16:22:37.413  1535  1772 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@16a342a4
03-29 16:22:37.414  1535  1535 I HotwordDetector: Closing mic
03-29 16:22:37.415   823   859 V WindowManager: Adding window Window{15276c8d u0 Starting com.test.thalitest} at 2 of 7 (after Window{3e51ad5c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-29 16:22:37.471   823   838 I ActivityManager: Start proc 3271:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-29 16:22:37.481   358  1778 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-29 16:22:37.483   358  1778 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-29 16:22:37.492   358  1026 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-29 16:22:37.497  1535  1773 I HotwordRecognitionRnr: Stopping hotword detection.
03-29 16:22:37.498  1535  1775 I HotwordRecognitionRnr: Hotword detection finished
03-29 16:22:37.556   823  1107 I ActivityManager: Killing 2919:com.android.settings/1000 (adj 15): empty #17
03-29 16:22:37.606   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660212499
03-29 16:22:37.606   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-29 16:22:37.660   823  1107 I ActivityManager: Killing 2882:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-29 16:22:37.691   870   870 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-29 16:22:37.691   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-29 16:22:37.732   870   870 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-29 16:22:37.733   870   870 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-29 16:22:37.840  3271  3271 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-29 16:22:37.854  3271  3271 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8177-8178)
03-29 16:22:37.855  3271  3271 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 16:22:37.876  3271  3271 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26a922cf}
,03-29 16:22:37.878  3271  3271 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 16:22:37.878  3271  3271 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-29 16:22:37.890  3271  3271 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-29 16:22:37.891  3271  3271 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:37.892  3271  3271 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 16:22:37.898  3271  3296 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-29 16:22:37.911  3271  3271 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-29 16:22:37.917  3271  3271 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 16:22:37.917  3271  3271 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 16:22:37.918  3271  3271 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 16:22:37.980   823   858 D BluetoothManagerService: Message: 20
03-29 16:22:37.981   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e5adbf2:true
,03-29 16:22:38.047  3271  3271 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:38.064  3271  3271 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-29 16:22:38.081  3271  3271 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-29 16:22:38.089  3271  3271 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 16:22:38.089  3271  3271 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:38.166  3271  3318 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 16:22:38.177  3271  3271 D Atlas   : Validating map...
,03-29 16:22:38.194   823   838 V WindowManager: Adding window Window{357e25a2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{15276c8d u0 Starting com.test.thalitest})
,03-29 16:22:38.198  3271  3305 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-29 16:22:38.267  3271  3318 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 16:22:38.301  3271  3318 D OpenGLRenderer: Enabling debug mode 0
,03-29 16:22:38.414   823   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s6ms
,03-29 16:22:38.421  1241  1241 I Keyboard.Facilitator: onFinishInput()
,03-29 16:22:38.454  3271  3271 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3271
,03-29 16:22:38.597  3271  3271 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 16:22:38.729   870   870 I kickstart: STATUS: Received file 'm9kefs2'
03-29 16:22:38.729   870   870 I kickstart: STATUS: 950272 bytes transferred in 0.994751 seconds
03-29 16:22:38.729   870   870 I kickstart: STATUS: Successfully downloaded files from target 
03-29 16:22:38.729   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-29 16:22:38.733   870   870 I kickstart: STATUS: Sahara protocol completed,
,03-29 16:22:38.774  3271  3320 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576317952
,03-29 16:22:38.787  3271  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 16:22:38.787  3271  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 16:22:38.787  3271  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 16:22:38.787  3271  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 16:22:38.787  3271  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-29 16:22:38.787  3271  3320 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a75ca8 added. We now have 1 listener(s)
03-29 16:22:38.788   823  1107 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:22:38.791  3271  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-29 16:22:38.795  3271  3320 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-29 16:22:38.797  3271  3320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 16:22:38.797  3271  3320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 16:22:38.801  3271  3320 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d6c0aa7 added. We now have 1 listener(s)
03-29 16:22:38.801  3271  3320 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 16:22:38.815   823  1034 D WifiService: New client listening to asynchronous messages
,03-29 16:22:38.818  3271  3320 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-29 16:22:38.822  3271  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-29 16:22:38.822  3271  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2,
03-29 16:22:38.823  3271  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3,
03-29 16:22:38.823  3271  3320 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2,
03-29 16:22:38.826  3271  3320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:22:38.827   823  1159 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:22:38.829  3271  3320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-29 16:22:38.849  3271  3320 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-29 16:22:38.849  3271  3320 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-29 16:22:38.849  3271  3320 D io.jxcore.node.ConnectivityMonitor: start: OK
03-29 16:22:38.850  3271  3320 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 16:22:38.855  3271  3271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 16:22:38.883  3271  3271 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 16:22:39.489  3271  3327 W jxcore-log: Initializing JXcore engine
03-29 16:22:39.489  3271  3327 W jxcore-log: JXcore engine is ready
,03-29 16:22:39.572  3327  3327 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10061]" dev="sockfs" ino=10061 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-29 16:22:39.572  3327  3327 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-29 16:22:39.572  3327  3327 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11655]" dev="sockfs" ino=11655 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-29 16:22:39.572  3327  3327 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19421]" dev="sockfs" ino=19421 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-29 16:22:39.591  3271  3327 W jxcore-log: Starting JXcore engine
,03-29 16:22:39.674  3271  3327 W jxcore-log: Platform android
03-29 16:22:39.674  3271  3327 W jxcore-log: 
03-29 16:22:39.674  3271  3327 W jxcore-log: Process ARCH arm
03-29 16:22:39.674  3271  3327 W jxcore-log: 
,03-29 16:22:39.863  3271  3327 I jxcore-log: JXcore Cordova bridge is ready!
03-29 16:22:39.863  3271  3327 I jxcore-log: 
03-29 16:22:39.863  3271  3327 W jxcore-log: JXcore engine is started
,03-29 16:22:39.870  3271  3320 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-29 16:22:39.874  3271  3271 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 16:22:41.515  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:41.606  1406  1726 I art     : Explicit concurrent mark sweep GC freed 31058(1650KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.430ms total 60.796ms
,03-29 16:22:41.667  1406  1732 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 16:22:41.667  1406  1732 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:41.667  1406  1732 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:41.667  1406  1732 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:41.671  1406  1732 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:41.683  2756  2756 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 16:22:41.684  2756  2756 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 16:22:41.684  2756  2756 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-29 16:22:42.494   823   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-29 16:22:42.511   823   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 16:22:42.576   260   292 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (140 us)
,03-29 16:22:43.101   823   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-29 16:22:43.102   260   260 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-29 16:22:43.102   823   823 V ActivityManager: Display changed displayId=0
03-29 16:22:43.102   260   260 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-29 16:22:43.362   260   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-29 16:22:43.363   260   260 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
03-29 16:22:43.363   823  1052 D SurfaceControl: Excessive delay in setPowerMode(): 262ms
03-29 16:22:43.366   823   861 I DreamManagerService: Entering dreamland.
03-29 16:22:43.366   823   861 I PowerManagerService: Dozing...
03-29 16:22:43.367   823   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-29 16:22:43.379   358   358 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-29 16:22:43.379   358   358 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-29 16:22:43.385   823  1033 E WifiStateMachine: cancelDelayedScan -> 16
,03-29 16:22:43.393   823  1033 E native  : do suspend false
,03-29 16:22:43.446  1241  1241 I Keyboard.Facilitator: onFinishInput()
,03-29 16:22:43.458   823  1033 E WifiStateMachine: cancelDelayedScan -> 18
,03-29 16:22:43.510   823  1033 E native  : do suspend true
,03-29 16:22:43.550   358  1220 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-29 16:22:43.550   358  1220 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-29 16:22:43.598   823  1033 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-29 16:22:43.640   823  1033 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-29 16:22:45.852  1152  1152 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-29 16:22:46.282  1152  1152 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-29 16:22:46.335  1152  1152 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-29 16:22:46.335  1152  1152 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-29 16:22:46.366   823  1033 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-29 16:22:46.366   823  1033 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
03-29 16:22:46.367   823  1035 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,03-29 16:22:46.373   823  1033 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-29 16:22:46.384   354   811 D CommandListener: Setting iface cfg
,03-29 16:22:46.390   823  1033 E WifiStateMachine: Start Dhcp Watchdog 1
,03-29 16:22:46.396   823  1033 E WifiStateMachine:  WifiLinkLayerStats: ,
03-29 16:22:46.396   823  1033 E WifiStateMachine:  my bss beacon rx: 1
03-29 16:22:46.396   823  1033 E WifiStateMachine:  RSSI mgmt: -44
03-29 16:22:46.396   823  1033 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=1
03-29 16:22:46.396   823  1033 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
,03-29 16:22:46.396   823  1033 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-29 16:22:46.396   823  1033 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-29 16:22:46.396   823  1033 E WifiStateMachine:  on_time : 0 tx_time=64 rx_time=64 scan_time=0
,03-29 16:22:46.500   823  1033 E native  : do suspend false
,03-29 16:22:46.514   823  1033 E WifiStateMachine: scanCount==0 - aborting
,03-29 16:22:46.751  3340  3340 I dhcpcd  : version 5.5.6 starting
,03-29 16:22:46.866  3340  3340 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-29 16:22:46.937  3340  3340 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-29 16:22:46.986  3340  3340 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-29 16:22:47.327   823  1033 E native  : do suspend true
,03-29 16:22:47.360   823  1035 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
03-29 16:22:47.362   823  1035 D ConnectivityService: Adding iface wlan0 to network 100
,03-29 16:22:47.368   823  1033 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-29 16:22:47.381   823  1035 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-29 16:22:47.382   823  1035 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-29 16:22:47.383   823  1035 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-29 16:22:47.386   823  1035 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-29 16:22:47.388   823  1035 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1],
,03-29 16:22:47.395   823  1035 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-29 16:22:47.399   823  1035 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-29 16:22:47.399   823  3338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-29 16:22:47.400   823  3338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-29 16:22:47.400   823  3338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-29 16:22:47.400   823  3338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-29 16:22:47.401   823  1035 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-29 16:22:47.401   823  1035 D ConnectivityService:    accepting network in place of null
03-29 16:22:47.403   823  1035 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-29 16:22:47.404   823  1035 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-29 16:22:47.409   823  1035 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-29 16:22:47.410  1073  1558 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-29 16:22:47.410   823  1035 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-29 16:22:47.410   823  1035 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-29 16:22:47.410   823  1035 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-29 16:22:47.414   823   858 D Tethering: MasterInitialState.processMessage what=3
,03-29 16:22:47.420   823   838 V BackupManagerService: Scheduling immediate backup pass
,03-29 16:22:47.423   823   823 V BackupManagerService: Running a backup pass
,03-29 16:22:47.427  1535  1535 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:22:47.428  3271  3271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 16:22:47.428  3271  3271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-29 16:22:47.428   823  1050 V BackupManagerService: clearing pending backups
,03-29 16:22:47.433  2939  2939 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-29 16:22:47.435  1319  1552 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-29 16:22:47.435  1319  1552 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-29 16:22:47.436   823   853 D TelephonyManager: getDataEnabled: retVal=false
,03-29 16:22:47.439   823  1050 V PerformBackupTask: Beginning backup of 14 targets
,03-29 16:22:47.441  2939  2939 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-29 16:22:47.446   823  1050 D PerformBackupTask: invokeAgentForBackup on @pm@
03-29 16:22:47.446   823   853 E GpsLocationProvider: No APN found to select.
,03-29 16:22:47.449   823  1050 V BackupServiceBinder: doBackup() invoked
,03-29 16:22:47.453   823  1050 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-29 16:22:47.486   823  1439 I ActivityManager: Start proc 3380:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-29 16:22:47.493   823  1050 I BackupRestoreController: Getting widget state for user: 0
,03-29 16:22:47.529  1808  1900 W GmsBackupTransport: Unknown package in backup request: @pm@
03-29 16:22:47.529  1808  1900 V GmsBackupTransport: starting performBackup for @pm@
,03-29 16:22:47.547  1808  1900 V GmsBackupTransport: performBackup done for @pm@
,03-29 16:22:47.557  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:47.614   823  3399 D GpsLocationProvider: NTP server returned: 1459261367060 (Tue Mar 29 16:22:47 GMT+02:00 2016) reference: 167937 certainty: 36 system time offset: -554
,03-29 16:22:47.615   823  1270 D AlarmManagerService: Setting time of day to sec=1459261367
03-29 16:22:47.063   823  1270 W AlarmManagerService: Unable to set rtc to 1459261367: Invalid argument
,03-29 16:22:47.073   823  3113 I art     : Explicit concurrent mark sweep GC freed 57470(3MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.476ms total 56.922ms
,03-29 16:22:47.120  1406  1432 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-29 16:22:47.120  1406  1432 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:47.120  1406  1432 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:47.120  1406  1432 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:47.124  1406  1432 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:47.150   823  3338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 29 Mar 2016 14:22:47 GMT], X-Android-Received-Millis=[1459261367150], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459261367063]}
,03-29 16:22:47.174   823  1439 I ActivityManager: Start proc 3422:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
03-29 16:22:47.177   823  3338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-29 16:22:47.177   823  1035 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-29 16:22:47.178   823  1035 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-29 16:22:47.178   823  1035 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-29 16:22:47.178   823  1035 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-29 16:22:47.178   823  1035 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-29 16:22:47.180   823  1035 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-29 16:22:47.181  1073  1558 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 16:22:47.191   370   370 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 16.154ms
,03-29 16:22:47.204   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 221us total 12.326ms
,03-29 16:22:47.213  1406  1432 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 16:22:47.213  1406  1432 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 16:22:47.213  1406  1432 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 16:22:47.213  1406  1432 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-29 16:22:47.213  1406  1432 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-29 16:22:47.213  1406  1432 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-29 16:22:47.213  1406  1432 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-29 16:22:47.225   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 19.003ms
,03-29 16:22:47.237  1808  1825 W GmsBackupTransport: Error sending final backup to server: 
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-29 16:22:47.237  1808  1825 W GmsBackupTransport: 	... 1 more
,03-29 16:22:47.239   823  1050 D BackupManagerService: Now staging backup of com.google.android.talk
,03-29 16:22:47.257   823  1050 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-29 16:22:47.257  1780  3403 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-29 16:22:47.262   823  1050 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-29 16:22:47.265   823  1050 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-29 16:22:47.272   823  1050 D BackupManagerService: Now staging backup of com.google.android.gm
,03-29 16:22:47.279   823  1050 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-29 16:22:47.285  3422  3422 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
03-29 16:22:47.286   823  1050 D BackupManagerService: Now staging backup of com.android.nfc
,03-29 16:22:47.288   823  1050 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
03-29 16:22:47.290   823  1050 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-29 16:22:47.292  1780  3439 W DriveInitializer: Background init thread started
,03-29 16:22:47.299   823  1050 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-29 16:22:47.301  3422  3422 D SprintDMHelper: simOperator:  IMSI: null
03-29 16:22:47.302  3422  3422 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-29 16:22:47.305  1780  1780 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-29 16:22:47.308  1780  1780 D SystemUpdateService: onCreate
,03-29 16:22:47.310   823  1050 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-29 16:22:47.312  1780  1780 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-29 16:22:47.315   823  1050 D BackupManagerService: Now staging backup of com.android.vending
,03-29 16:22:47.322  1780  3440 I SystemUpdateService: active receiver: enabled
,03-29 16:22:47.323   823  1050 D BackupManagerService: Now staging backup of android
,03-29 16:22:47.328   823  1050 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-29 16:22:47.334  1780  3440 I SystemUpdateService: Already downloaded, skipping offpeak checks.
03-29 16:22:47.334  1780  3443 W DriveInitializer: Awaiting to be initialized
,03-29 16:22:47.335  1808  1823 I GmsBackupTransport: Next backup will happen in 43199892 millis.
,03-29 16:22:47.337   823  1050 I BackupManagerService: Backup pass finished.
,03-29 16:22:47.340  1780  3440 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-29 16:22:47.340  1780  3440 I SystemUpdateService: now status is 0 (complete)
03-29 16:22:47.340  1780  3440 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-29 16:22:47.341  1780  3440 I SystemUpdateService: file has been verified
03-29 16:22:47.341  1780  3440 I SystemUpdateService: OTA package size = 25802302
,03-29 16:22:47.352  1780  3440 I SystemUpdateService: showing system update notification
,03-29 16:22:47.372   823   823 I ValidateNoPeople: skipping global notification
,03-29 16:22:47.379  1406  1436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 16:22:47.380  1406  1436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:47.380  1406  1436 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:47.380  1406  1436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:47.384  1406  1436 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:47.389  1780  3451 I iu.SyncManager: SYNC; picasa accounts
,03-29 16:22:47.395  1780  1780 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-29 16:22:47.399  3095  3418 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 16:22:47.399  3095  3418 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jdm.a(PG:82)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jcs.o(PG:406)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jcn.a(PG:1379)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jcs.i(PG:143)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at blb.a(PG:3937)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at czp.a(PG:18188)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at czp.a(PG:9081)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at czq.run(PG:1686)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:22:47.399  3095  3418 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jdj.a(PG:4091)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jdj.a(PG:1125)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jdm.a(PG:77)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	... 12 more
03-29 16:22:47.399  3095  3418 E HttpOperation: Caused by: faj: BadAuthentication
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at fal.a(PG:38)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	at jdj.a(PG:4089)
03-29 16:22:47.399  3095  3418 E HttpOperation: 	... 14 more
,03-29 16:22:47.400  1780  1780 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
03-29 16:22:47.404  1780  1780 D SystemUpdateService: onDestroy
03-29 16:22:47.412  1780  3451 I iu.UploadsManager: num queued entries: 0
03-29 16:22:47.413  1780  3451 I iu.UploadsManager: num updated entries: 0
03-29 16:22:47.422  1780  3451 I iu.SyncManager: NEXT; no task
03-29 16:22:47.423  1780  1780 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-29 16:22:47.425  1780  1780 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-29 16:22:47.445   823  3113 I ActivityManager: Start proc 3457:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-29 16:22:47.486  1406  1732 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 16:22:47.486  1406  1732 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:47.486  1406  1732 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:47.486  1406  1732 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:47.490  1406  1732 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:47.501  3095  3418 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 16:22:47.501  3095  3418 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jdm.a(PG:82)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jcs.o(PG:406)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jcn.a(PG:1379)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jcs.i(PG:143)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at hec.a(PG:42)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at hee.a(PG:102)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at czr.a(PG:65)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at kka.a(PG:108)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at czp.a(PG:19176)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at czp.a(PG:9081)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at czq.run(PG:1686)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:22:47.501  3095  3418 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jdj.a(PG:4091)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jdj.a(PG:1125)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jdm.a(PG:77)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	... 15 more
03-29 16:22:47.501  3095  3418 E HttpOperation: Caused by: faj: BadAuthentication
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at fal.a(PG:38)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	at jdj.a(PG:4089)
03-29 16:22:47.501  3095  3418 E HttpOperation: 	... 17 more
03-29 16:22:47.501  1406  2559 I art     : Explicit concurrent mark sweep GC freed 16324(987KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 895us total 23.468ms
03-29 16:22:47.501  3095  3418 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 16:22:47.501  3095  3418 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at hec.a(PG:42)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at hee.a(PG:102)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at czr.a(PG:65)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at kka.a(PG:108)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: Caused by: android.acc,ounts.AuthenticatorException: Recoverable error
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	... 15 more
03-29 16:22:47.501  3095  3418 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at fal.a(PG:38)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 16:22:47.501  3095  3418 E ExperimentLoader: 	... 17 more
03-29 16:22:47.513  1780  3439 W DriveInitializer: Background init thread ended
,03-29 16:22:47.564   823   853 I ActivityManager: Start proc 3484:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-29 16:22:47.614  3457  3457 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-29 16:22:47.614  3457  3457 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 16:22:47.614  3457  3457 I GAv4    :   adb logcat -s GAv4
,03-29 16:22:47.653  3457  3457 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 16:22:47.658   823   838 I ActivityManager: Killing 2446:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-29 16:22:47.661   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 37676, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-29 16:22:47.665  3457  3457 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 16:22:47.669  3457  3509 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 16:22:47.706  3162  3454 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-29 16:22:47.765   823  3113 I ActivityManager: Killing 3006:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-29 16:22:47.884  1406  3507 D GCM     : Connected
,03-29 16:22:48.021   823   853 I ActivityManager: Start proc 3511:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-29 16:22:48.040  1406  3507 D GCM     : Message class com.google.f.a.a.p
,03-29 16:22:48.189  3457  3457 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-29 16:22:48.199  3457  3457 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9075-9076)
03-29 16:22:48.199  3457  3457 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 16:22:48.203  3457  3457 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32769da2}
,03-29 16:22:48.204  3457  3457 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 16:22:48.204  3457  3457 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-29 16:22:48.204  3484  3543 V KeepSync: Connecting to GoogleApiClient
,03-29 16:22:48.213  3457  3457 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-29 16:22:48.214  3457  3457 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:22:48.216  3457  3457 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 16:22:48.238  3457  3457 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-29 16:22:48.243  3457  3457 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 16:22:48.243  3457  3457 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 16:22:48.243  3457  3457 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 16:22:48.258  1780  3552 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 16:22:48.266  1780  3552 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 16:22:48.284  1406  1432 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 16:22:48.284  1406  1432 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:48.284  1406  1432 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:48.284  1406  1432 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:48.287  1406  1432 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:48.302  3457  3457 I NSApplication: Starting up...
,03-29 16:22:48.303  3457  3560 W AudioManagerAndroid: Requires BLUETOOTH permission
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: Handling authorization failure
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 16:22:48.306  1780  3552 E ClientConnectionOperation: 	... 7 more
,03-29 16:22:48.310  3484  3543 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 16:22:48.316  3484  3543 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 16:22:48.320  3484  3543 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-29 16:22:48.320  3484  3543 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 16:22:48.345   823   839 I ActivityManager: Start proc 3567:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-29 16:22:48.409  1406  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 16:22:48.409  1406  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:48.409  1406  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:48.409  1406  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:48.413  1406  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:48.445  3484  3543 E KeepSync: IOException
03-29 16:22:48.445  3484  3543 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 16:22:48.445  3484  3543 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 16:22:48.445  3484  3543 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 16:22:48.445  3484  3543 E KeepSync: 	... 10 more
03-29 16:22:48.445  3484  3543 W KeepSync: Sync result 2
,03-29 16:22:48.454   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 16:22:48.459   823  1379 I ActivityManager: Killing 3026:com.android.musicfx/u0a18 (adj 15): empty #17
,03-29 16:22:48.588  3511  3511 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-29 16:22:48.599  3511  3511 I BooksApp: Created application version: 3.6.8 (30608)
,03-29 16:22:48.663  3511  3592 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 16:22:48.725   823  1439 I ActivityManager: Start proc 3598:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
03-29 16:22:48.726   823  1439 I ActivityManager: Killing 3056:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-29 16:22:48.732   823  1107 I art     : Explicit concurrent mark sweep GC freed 35351(1632KB) AllocSpace objects, 6(137KB) LOS objects, 32% free, 33MB/49MB, paused 1.407ms total 55.373ms
,03-29 16:22:49.166  3511  3618 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 16:22:49.238  1406  3420 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 16:22:49.238  1406  3420 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:49.238  1406  3420 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:49.239  1406  3420 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:49.244  1406  3420 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:49.285  1406  1432 I art     : Explicit concurrent mark sweep GC freed 12629(676KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 1.208ms total 38.505ms
,03-29 16:22:49.340  1406  1436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 16:22:49.340  1406  1436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:49.340  1406  1436 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:49.340  1406  1436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:49.343  1406  1436 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:49.353  3511  3618 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 16:22:49.354  3511  3592 E BooksSync: Soft error
03-29 16:22:49.354  3511  3592 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 16:22:49.354  3511  3592 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 16:22:49.355  3511  3592 E BooksSync: Sync error
03-29 16:22:49.355  3511  3592 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 16:22:49.355  3511  3592 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 16:22:49.355  3511  3592 I BooksSync: Finished books sync
,03-29 16:22:49.362   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-29 16:22:49.362   823  1379 I ActivityManager: Killing 1470:android.process.acore/u0a5 (adj 15): empty #17
,03-29 16:22:49.468   823  1379 I ActivityManager: Killing 2797:com.google.android.gms:car/u0a11 (adj 15): empty #18
,03-29 16:22:49.531  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:22:49.531  3271  3327 I jxcore-log: 
,03-29 16:22:49.533  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-29 16:22:49.533  3271  3327 I jxcore-log: 
,03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:22:49.537  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:22:49.541  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-29 16:22:49.542  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-29 16:22:49.542  3271  3327 I jxcore-log: 
,03-29 16:22:49.544  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-29 16:22:49.544  3271  3327 I jxcore-log: 
,03-29 16:22:49.812   823  1342 I ActivityManager: Killing 2817:com.google.android.gm/u0a78 (adj 15): empty #17
,03-29 16:22:50.066  3271  3327 I jxcore-log: Unit Test app is loaded
03-29 16:22:50.066  3271  3327 I jxcore-log: 
,03-29 16:22:50.071  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
,03-29 16:22:50.071  3271  3327 I jxcore-log: 
,03-29 16:22:50.079  3271  3327 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
03-29 16:22:50.081  3271  3327 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-29 16:22:50.081  3271  3327 I jxcore-log: 
03-29 16:22:50.083  3271  3327 I jxcore-log: My device name is: motorola-Nexus 6
03-29 16:22:50.083  3271  3327 I jxcore-log: 
,03-29 16:22:50.088  3271  3271 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-29 16:22:50.122   823  1379 I ActivityManager: Start proc 3620:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-29 16:22:50.169  3620  3620 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459261370169
03-29 16:22:50.169  3620  3620 D         : TimeServiceNative: User Time to be set is 1459261370169
,03-29 16:22:50.169  3620  3620 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-29 16:22:50.169  3620  3620 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-29 16:22:50.169  3620  3620 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459261370169
03-29 16:22:50.169   373   880 D QC-time-services: Daemon: Connection accepted:time_genoff
03-29 16:22:50.169   373  3637 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459261370169
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459261370169, operation = 0
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/15/70 10:34:30
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:Value read from RTC seconds = 19564470000
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:new time 1459261370169 
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon: delta 1439696900169 genoff 1439696900169 
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696900169 to memory
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-29 16:22:50.170   373  3637 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-29 16:22:50.171  3620  3620 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
03-29 16:22:50.172   373  3637 D QC-time-services: Updating the TOD offset
,03-29 16:22:50.172   373  3637 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696900169 to memory
,03-29 16:22:50.172   373  3637 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,03-29 16:22:50.172   373  3637 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation ,
03-29 16:22:50.174   373  3637 E QC-time-services: Daemon:Update to modem bit set
03-29 16:22:50.174   373  3637 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !,
03-29 16:22:50.174   373  3637 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143296570169
03-29 16:22:50.175  3620  3620 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-29 16:22:50.244   373   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-29 16:22:50.248   373   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-29 16:22:50.299   823  3113 I ActivityManager: Start proc 3639:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-29 16:22:50.316   823  1439 I ActivityManager: Killing 1882:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-29 16:22:50.486  3639  3639 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-29 16:22:50.486  3639  3639 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 16:22:50.486  3639  3639 I GAv4    :   adb logcat -s GAv4
,03-29 16:22:50.502  3639  3639 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 16:22:50.514  3639  3639 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 16:22:50.539  3639  3658 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 16:22:50.571   823  1421 I ActivityManager: Killing 3134:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-29 16:22:50.772  1780  1780 V Herrevad: NQAS connected
,03-29 16:22:50.782  3162  3162 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-29 16:22:50.782  3162  3162 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 16:22:50.816  1780  3661 I art     : Explicit concurrent mark sweep GC freed 14992(1150KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.126ms total 44.794ms
,03-29 16:22:50.829   823  1107 I ActivityManager: Start proc 3668:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-29 16:22:50.838   823  1034 D WifiService: New client listening to asynchronous messages
,03-29 16:22:50.851  3668  3668 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-29 16:22:50.892  3668  3668 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@19bd672e(com.android.providers.calendar.CalendarProvider2@26a922cf)
,03-29 16:22:50.934  1406  1732 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-29 16:22:50.934  1406  1732 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:50.935  1406  1732 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:50.935  1406  1732 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:50.938  1406  1732 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:50.946  3162  3664 E Babel   : UserRecoverableAuthException.
03-29 16:22:50.946  3162  3664 E Babel   : eei: BadAuthentication
03-29 16:22:50.946  3162  3664 E Babel   : 	at eeg.a(Unknown Source)
03-29 16:22:50.946  3162  3664 E Babel   : 	at eeg.a(Unknown Source)
03-29 16:22:50.946  3162  3664 E Babel   : 	at eeg.a(Unknown Source)
03-29 16:22:50.946  3162  3664 E Babel   : 	at g.a(Unknown Source)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cae.a(SourceFile:3089)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cae.a(SourceFile:1131)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cws.a(SourceFile:4333)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cws.a(SourceFile:1419)
03-29 16:22:50.946  3162  3664 E Babel   : 	at crl.a(SourceFile:492)
03-29 16:22:50.946  3162  3664 E Babel   : 	at crl.a(SourceFile:1468)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cas.b(SourceFile:106)
03-29 16:22:50.946  3162  3664 E Babel   : 	at cap.d(SourceFile:335)
03-29 16:22:50.946  3162  3664 E Babel   : 	at caq.run(SourceFile:81)
03-29 16:22:50.946  3162  3664 E Babel   : Error getting auth token
,03-29 16:22:50.948  3162  3664 E Babel   : dvm
03-29 16:22:50.948  3162  3664 E Babel   : 	at g.a(Unknown Source)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cae.a(SourceFile:3089)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cae.a(SourceFile:1131)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cws.a(SourceFile:4333)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cws.a(SourceFile:1419)
03-29 16:22:50.948  3162  3664 E Babel   : 	at crl.a(SourceFile:492)
03-29 16:22:50.948  3162  3664 E Babel   : 	at crl.a(SourceFile:1468)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cas.b(SourceFile:106)
03-29 16:22:50.948  3162  3664 E Babel   : 	at cap.d(SourceFile:335)
03-29 16:22:50.948  3162  3664 E Babel   : 	at caq.run(SourceFile:81)
,03-29 16:22:50.950  3162  3664 E Babel   : Account registration failed 1-Redacted-21
03-29 16:22:50.950  3162  3664 E Babel   : cyp: null -- null
03-29 16:22:50.950  3162  3664 E Babel   : 	at cae.a(SourceFile:3121)
03-29 16:22:50.950  3162  3664 E Babel   : 	at cae.a(SourceFile:1131)
03-29 16:22:50.950  3162  3664 E Babel   : 	at cws.a(SourceFile:4333)
03-29 16:22:50.950  3162  3664 E Babel   : 	at cws.a(SourceFile:1419)
03-29 16:22:50.950  3162  3664 E Babel   : 	at crl.a(SourceFile:492)
03-29 16:22:50.950  3162  3664 E Babel   : 	at crl.a(SourceFile:1468)
03-29 16:22:50.950  3162  3664 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 16:22:50.950  3162  3664 E Babel   : 	at cas.b(SourceFile:106)
03-29 16:22:50.950  3162  3664 E Babel   : 	at cap.d(SourceFile:335)
03-29 16:22:50.950  3162  3664 E Babel   : 	at caq.run(SourceFile:81)
,03-29 16:22:50.961  3162  3664 I art     : Note: end time exceeds epoch: 
,03-29 16:22:50.976  1406  1436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-29 16:22:50.977  1406  1436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:50.977  1406  1436 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:50.977  1406  1436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:50.979  1406  1436 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:50.992  1406  1436 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-29 16:22:51.007  3162  3693 E Babel   : Unexpected exception while authenticating.
03-29 16:22:51.007  3162  3693 E Babel   : eej: User intervention required. Notification has been pushed.
03-29 16:22:51.007  3162  3693 E Babel   : 	at eeg.b(Unknown Source)
03-29 16:22:51.007  3162  3693 E Babel   : 	at eeg.b(Unknown Source)
03-29 16:22:51.007  3162  3693 E Babel   : 	at g.a(Unknown Source)
03-29 16:22:51.007  3162  3693 E Babel   : 	at cae.b(SourceFile:1146)
03-29 16:22:51.007  3162  3693 E Babel   : 	at dcg.run(SourceFile:5617)
03-29 16:22:51.007  3162  3693 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:22:51.007  3162  3693 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:22:51.007  3162  3693 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-29 16:22:51.949  3668  3668 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-29 16:22:51.950  3668  3668 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,03-29 16:22:52.118  3668  3697 E SQLiteLog: (284) automatic index on view_events(_id)
,03-29 16:22:53.601  3511  3588 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-29 16:22:53.975  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-29 16:22:53.975  3271  3327 I jxcore-log: 
,03-29 16:22:54.317  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
03-29 16:22:54.317  3271  3327 I jxcore-log: 
,03-29 16:22:54.330  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-29 16:22:54.330  3271  3327 I jxcore-log: 
,03-29 16:22:54.334  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-29 16:22:54.334  3271  3327 I jxcore-log: 
,03-29 16:22:54.371  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-29 16:22:54.371  3271  3327 I jxcore-log: 
,03-29 16:22:54.387  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-29 16:22:54.387  3271  3327 I jxcore-log: 
,03-29 16:22:54.391  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-29 16:22:54.391  3271  3327 I jxcore-log: 
,03-29 16:22:55.063  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:55.310  1406  3702 I VacuumService: Vacuum at: now=1459261375310 tag=VacuumService
,03-29 16:22:55.327  3380  3701 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 16:22:55.481   823  1107 I art     : Explicit concurrent mark sweep GC freed 16398(733KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.909ms total 79.076ms
,03-29 16:22:55.540  1406  1432 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-29 16:22:55.540  1406  1432 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:55.540  1406  1432 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:55.540  1406  1432 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:55.543  1406  1432 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:55.554  3380  3701 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 16:22:55.555  3380  3701 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 16:22:55.646  1406  3703 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-29 16:22:55.671  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:56.281  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:56.405  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-29 16:22:56.405  3271  3327 I jxcore-log: 
,03-29 16:22:56.422  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-29 16:22:56.422  3271  3327 I jxcore-log: 
,03-29 16:22:56.431  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-29 16:22:56.431  3271  3327 I jxcore-log: 
,03-29 16:22:56.491  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:56.655  1406  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 16:22:56.655  1406  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:56.655  1406  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:56.655  1406  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:56.664  1406  3703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:56.699  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-29 16:22:56.699  3271  3327 I jxcore-log: 
,03-29 16:22:56.711  1406  3703 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 16:22:56.711  1406  3703 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 16:22:56.711  1406  3703 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 16:22:56.770  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-29 16:22:56.770  3271  3327 I jxcore-log: 
,03-29 16:22:56.827  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
,03-29 16:22:56.827  3271  3327 I jxcore-log: 
,03-29 16:22:56.834  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
,03-29 16:22:56.834  3271  3327 I jxcore-log: 
03-29 16:22:56.843  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-29 16:22:56.843  3271  3327 I jxcore-log: 
,03-29 16:22:56.848  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
,03-29 16:22:56.848  3271  3327 I jxcore-log: 
,03-29 16:22:56.855  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-29 16:22:56.855  3271  3327 I jxcore-log: 
,03-29 16:22:56.867  1406  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-29 16:22:56.868  1406  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:56.868  1406  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:56.868  1406  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:56.871  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
03-29 16:22:56.871  3271  3327 I jxcore-log: 
,03-29 16:22:56.875  1406  3703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 16:22:56.892  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-29 16:22:56.892  3271  3327 I jxcore-log: 
,03-29 16:22:56.924  1406  3703 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 16:22:56.924  1406  3703 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 16:22:56.924  1406  3703 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 16:22:56.975  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
03-29 16:22:56.975  3271  3327 I jxcore-log: 
,03-29 16:22:56.980  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
03-29 16:22:56.980  3271  3327 I jxcore-log: 
,03-29 16:22:57.007  3271  3327 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-29 16:22:57.007  3271  3327 I jxcore-log: 
,03-29 16:22:57.035  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:57.063   823  1159 I ActivityManager: Killing 2756:com.android.vending/u0a19 (adj 15): empty #17
,03-29 16:22:57.180  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:57.340  1406  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-29 16:22:57.340  1406  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:57.340  1406  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:57.341  1406  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:57.347  1406  3703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:57.372  1406  3703 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 16:22:57.372  1406  3703 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 16:22:57.372  1406  3703 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 16:22:57.490  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:57.619  1406  3703 W Uploader: No account for auth token provided,
,03-29 16:22:57.721  1406  3703 W Uploader: No account for auth token provided,
,03-29 16:22:57.837  1406  3703 W Uploader: No account for auth token provided,
,03-29 16:22:57.955  1406  3703 W Uploader:  no longer exists, so no auth token.,
,03-29 16:22:58.103  1406  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 16:22:58.103  1406  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:58.103  1406  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:58.104  1406  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:58.125  1406  3703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:58.184  1406  3703 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 16:22:58.184  1406  3703 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 16:22:58.184  1406  3703 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 16:22:58.320  1406  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-29 16:22:58.321  1406  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,03-29 16:22:58.321  1406  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 16:22:58.321  1406  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-29 16:22:58.344  1406  3703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:58.399  1406  3703 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 16:22:58.399  1406  3703 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 16:22:58.399  1406  3703 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 16:22:58.408  3271  3327 I jxcore-log: TAP version 13
03-29 16:22:58.408  3271  3327 I jxcore-log: 
,03-29 16:22:58.411  3271  3327 I jxcore-log: # setup
03-29 16:22:58.411  3271  3327 I jxcore-log: 
,03-29 16:22:58.542  3271  3327 I jxcore-log: # 1. calling createNativeListener directly rejects
03-29 16:22:58.542  3271  3327 I jxcore-log: 
,03-29 16:22:58.599  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:58.735   823  1421 I ActivityManager: Start proc 3714:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-29 16:22:58.757  1406  3703 W Uploader: No account for auth token provided
,03-29 16:22:58.929  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:22:58.929  3271  3327 I jxcore-log: 
,03-29 16:22:58.934  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 58866
03-29 16:22:58.934  3271  3327 I jxcore-log: 
,03-29 16:22:58.941  3271  3327 I jxcore-log: ok 1 Should throw
03-29 16:22:58.941  3271  3327 I jxcore-log: 
,03-29 16:22:58.944  3271  3327 I jxcore-log: # teardown
03-29 16:22:58.944  3271  3327 I jxcore-log: 
,03-29 16:22:58.963  3714  3714 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-29 16:22:59.088  3714  3714 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-29 16:22:59.198   823  1342 I ActivityManager: Start proc 3750:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-29 16:22:59.230  3714  3714 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-29 16:22:59.232  3714  3714 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-29 16:22:59.258  3750  3750 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 16:22:59.259  3750  3750 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 16:22:59.278   823  1378 I ActivityManager: Killing 2939:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-29 16:22:59.284  3714  3729 D Finsky  : [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-29 16:22:59.295  3750  3750 I MultiDex: VM with version 2.1.0 has multidex support
03-29 16:22:59.295  3750  3750 I MultiDex: install
03-29 16:22:59.295  3750  3750 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 16:22:59.395  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:59.406  3714  3714 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-29 16:22:59.407  3714  3714 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-29 16:22:59.418  3714  3714 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-29 16:22:59.433  3750  3750 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 16:22:59.445  3714  3714 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-29 16:22:59.447  1406  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-29 16:22:59.448  1406  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:22:59.448  1406  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:22:59.448  1406  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:22:59.454  1406  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:22:59.494  3750  3750 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 16:22:59.518  1406  2559 I art     : Explicit concurrent mark sweep GC freed 54610(3MB) AllocSpace objects, 5(405KB) LOS objects, 36% free, 27MB/43MB, paused 1.510ms total 50.133ms
,03-29 16:22:59.519  1406  1406 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-29 16:22:59.527  1406  2115 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-29 16:22:59.532  1780  1780 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-29 16:22:59.534  3271  3327 I jxcore-log: # setup
03-29 16:22:59.534  3271  3327 I jxcore-log: 
,03-29 16:22:59.541  3714  3729 D Finsky  : [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-29 16:22:59.583   823   838 I ActivityManager: Start proc 3779:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-29 16:22:59.594   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 9.990ms
,03-29 16:22:59.598  1780  3789 D LocationInitializer: Restart initialization of location
,03-29 16:22:59.605   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 430us total 10.530ms
,03-29 16:22:59.616   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.854ms
,03-29 16:22:59.621  3779  3779 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 16:22:59.622  3779  3779 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 16:22:59.630  3271  3327 I jxcore-log: # 2. emits incomingConnectionState
03-29 16:22:59.630  3271  3327 I jxcore-log: 
,03-29 16:22:59.650  3779  3779 I MultiDex: VM with version 2.1.0 has multidex support
03-29 16:22:59.650  3779  3779 I MultiDex: install
03-29 16:22:59.650  3779  3779 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 16:22:59.664  3779  3779 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 16:22:59.696  3779  3779 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 16:22:59.699  1406  2118 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-29 16:22:59.702  1406  1406 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-29 16:22:59.706  1780  1780 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-29 16:22:59.724  3779  3779 D WearableService: callingUid 10011, callindPid: 3779
,03-29 16:22:59.735  1780  3802 D LocationInitializer: Restart initialization of location
,03-29 16:22:59.747  1808  2077 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-29 16:22:59.751  1808  2077 E MDM     : [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-29 16:22:59.902  3714  3714 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-29 16:23:00.098  3714  3714 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-29 16:23:00.119  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.171  1406  1732 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-29 16:23:00.172  1406  1732 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:00.172  1406  1732 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:00.172  1406  1732 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:00.178  1406  1732 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.195  3714  3714 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 16:23:00.209  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.242  1406  1436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-29 16:23:00.243  1406  1436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:00.243  1406  1436 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:00.243  1406  1436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:00.248  1406  1436 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.294  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.342  1406  1432 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 16:23:00.342  1406  1432 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:00.342  1406  1432 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:00.343  1406  1432 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:00.353  1406  1432 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.381  3714  3714 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 16:23:00.482  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:00.482  3271  3327 I jxcore-log: 
,03-29 16:23:00.487  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 33581
03-29 16:23:00.487  3271  3327 I jxcore-log: 
,03-29 16:23:00.497  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:00.497  3271  3327 I jxcore-log: 
,03-29 16:23:00.501  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:00.501  3271  3327 I jxcore-log: 
,03-29 16:23:00.511  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:00.511  3271  3327 I jxcore-log: 
,03-29 16:23:00.517  3271  3327 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-29 16:23:00.517  3271  3327 I jxcore-log: 
,03-29 16:23:00.530  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:00.530  3271  3327 I jxcore-log: 
,03-29 16:23:00.531  3271  3327 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-29 16:23:00.531  3271  3327 I jxcore-log: 
,03-29 16:23:00.537  3271  3327 I jxcore-log: # teardown
03-29 16:23:00.537  3271  3327 I jxcore-log: 
,03-29 16:23:00.580  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.619  1406  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 16:23:00.619  1406  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:00.619  1406  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 16:23:00.619  1406  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-29 16:23:00.621  1406  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:00.680   823  1343 I art     : Explicit concurrent mark sweep GC freed 23179(1080KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.557ms total 56.111ms
,03-29 16:23:00.690  3714  3714 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 16:23:00.693  3714  3714 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-29 16:23:00.699  3714  3714 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-29 16:23:00.704  3714  3714 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,03-29 16:23:00.722  1808  1823 D DeviceConnectionService: client connected with version: 7571000
,03-29 16:23:02.526  3271  3327 I jxcore-log: # setup
03-29 16:23:02.526  3271  3327 I jxcore-log: 
,03-29 16:23:02.677  3271  3327 I jxcore-log: # 3. emits routerPortConnectionFailed
03-29 16:23:02.677  3271  3327 I jxcore-log: 
,03-29 16:23:03.247  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:03.247  3271  3327 I jxcore-log: 
,03-29 16:23:03.249  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 36710
03-29 16:23:03.249  3271  3327 I jxcore-log: 
,03-29 16:23:03.256  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:03.256  3271  3327 I jxcore-log: 
,03-29 16:23:03.257  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:03.257  3271  3327 I jxcore-log: 
,03-29 16:23:03.259  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:03.259  3271  3327 I jxcore-log: 
,03-29 16:23:03.284  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:03.284  3271  3327 I jxcore-log: 
,03-29 16:23:03.287  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:03.287  3271  3327 I jxcore-log: 
,03-29 16:23:03.291  3271  3327 I jxcore-log: DEBUG createNativeListener: 
03-29 16:23:03.291  3271  3327 I jxcore-log: 
,03-29 16:23:03.292  3271  3327 I jxcore-log: ok 4 tried to connect to right port
03-29 16:23:03.292  3271  3327 I jxcore-log: 
,03-29 16:23:03.293  3271  3327 I jxcore-log: ok 5 failed due to refused connection
03-29 16:23:03.293  3271  3327 I jxcore-log: 
03-29 16:23:03.293  3271  3327 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-29 16:23:03.293  3271  3327 I jxcore-log: 
,03-29 16:23:03.297  3271  3327 I jxcore-log: # teardown
03-29 16:23:03.297  3271  3327 I jxcore-log: 
,03-29 16:23:03.299  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:03.299  3271  3327 I jxcore-log: 
,03-29 16:23:03.440  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:03.440  3271  3327 I jxcore-log: 
,03-29 16:23:03.446  3271  3327 I jxcore-log: # setup
03-29 16:23:03.446  3271  3327 I jxcore-log: 
03-29 16:23:03.447  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:03.447  3271  3327 I jxcore-log: 
,03-29 16:23:03.632  3271  3327 I jxcore-log: # 4. native server connections all up
03-29 16:23:03.632  3271  3327 I jxcore-log: 
,03-29 16:23:03.785  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:03.785  3271  3327 I jxcore-log: 
,03-29 16:23:03.795  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 55108
03-29 16:23:03.795  3271  3327 I jxcore-log: 
,03-29 16:23:03.802  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:03.802  3271  3327 I jxcore-log: 
,03-29 16:23:03.803  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:03.803  3271  3327 I jxcore-log: 
,03-29 16:23:03.805  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:03.805  3271  3327 I jxcore-log: 
,03-29 16:23:03.846  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:03.846  3271  3327 I jxcore-log: 
,03-29 16:23:03.857  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:03.857  3271  3327 I jxcore-log: 
,03-29 16:23:03.865  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:03.865  3271  3327 I jxcore-log: 
,03-29 16:23:03.867  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:03.867  3271  3327 I jxcore-log: 
,03-29 16:23:03.896  3271  3327 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-29 16:23:03.896  3271  3327 I jxcore-log: 
03-29 16:23:03.897  3271  3327 I jxcore-log: ok 8 Send/recvd #1 should be same
03-29 16:23:03.897  3271  3327 I jxcore-log: 
03-29 16:23:03.900  3271  3327 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-29 16:23:03.900  3271  3327 I jxcore-log: 
03-29 16:23:03.900  3271  3327 I jxcore-log: ok 10 Send/recvd #2 should be same
03-29 16:23:03.900  3271  3327 I jxcore-log: 
03-29 16:23:03.903  3271  3327 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-29 16:23:03.903  3271  3327 I jxcore-log: 
,03-29 16:23:03.912  3271  3327 I jxcore-log: # teardown
03-29 16:23:03.912  3271  3327 I jxcore-log: 
,03-29 16:23:04.067  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.067  3271  3327 I jxcore-log: 
,03-29 16:23:04.071  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.071  3271  3327 I jxcore-log: 
,03-29 16:23:04.074  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:04.074  3271  3327 I jxcore-log: 
,03-29 16:23:04.078  3271  3327 I jxcore-log: # setup,
03-29 16:23:04.078  3271  3327 I jxcore-log: 
03-29 16:23:04.079  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:04.079  3271  3327 I jxcore-log: 
,03-29 16:23:04.256  3271  3327 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-29 16:23:04.256  3271  3327 I jxcore-log: 
,03-29 16:23:04.497  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:04.497  3271  3327 I jxcore-log: 
,03-29 16:23:04.506  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 52120
03-29 16:23:04.506  3271  3327 I jxcore-log: 
,03-29 16:23:04.511  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:04.511  3271  3327 I jxcore-log: 
,03-29 16:23:04.512  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:04.512  3271  3327 I jxcore-log: 
,03-29 16:23:04.514  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:04.514  3271  3327 I jxcore-log: 
,03-29 16:23:04.527  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:04.527  3271  3327 I jxcore-log: 
,03-29 16:23:04.529  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-29 16:23:04.529  3271  3327 I jxcore-log: 
,03-29 16:23:04.543  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:04.543  3271  3327 I jxcore-log: 
,03-29 16:23:04.556  3271  3327 I jxcore-log: ok 12 socket shouldn't close until after stream
03-29 16:23:04.556  3271  3327 I jxcore-log: 
,03-29 16:23:04.557  3271  3327 I jxcore-log: ok 13 incoming remains open
03-29 16:23:04.557  3271  3327 I jxcore-log: 
,03-29 16:23:04.562  3271  3327 I jxcore-log: # teardown
03-29 16:23:04.562  3271  3327 I jxcore-log: 
,03-29 16:23:04.665  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
,03-29 16:23:04.665  3271  3327 I jxcore-log: 
03-29 16:23:04.670  3271  3327 I jxcore-log: # setup
03-29 16:23:04.670  3271  3327 I jxcore-log: 
03-29 16:23:04.671  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-29 16:23:04.671  3271  3327 I jxcore-log: 
,03-29 16:23:04.767   823  1342 I ActivityManager: Killing 1535:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-29 16:23:04.789  3271  3327 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-29 16:23:04.789  3271  3327 I jxcore-log: 
,03-29 16:23:04.832   823  1034 D WifiService: Client connection lost with reason: 4
,03-29 16:23:04.942  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:04.942  3271  3327 I jxcore-log: 
,03-29 16:23:04.954  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 55208
03-29 16:23:04.954  3271  3327 I jxcore-log: 
,03-29 16:23:04.968  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:04.968  3271  3327 I jxcore-log: 
,03-29 16:23:04.969  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:04.969  3271  3327 I jxcore-log: 
,03-29 16:23:04.971  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:04.971  3271  3327 I jxcore-log: 
,03-29 16:23:04.982  3271  3327 I jxcore-log: ok 14 we should not have gotten an error
03-29 16:23:04.982  3271  3327 I jxcore-log: 
,03-29 16:23:04.988  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:04.988  3271  3327 I jxcore-log: 
,03-29 16:23:04.993  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:04.993  3271  3327 I jxcore-log: 
,03-29 16:23:05.004  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:05.004  3271  3327 I jxcore-log: 
,03-29 16:23:05.007  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:05.007  3271  3327 I jxcore-log: 
,03-29 16:23:05.015  3271  3327 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-29 16:23:05.015  3271  3327 I jxcore-log: 
,03-29 16:23:05.015  3271  3327 I jxcore-log: ok 16 incoming is cleaned up
03-29 16:23:05.015  3271  3327 I jxcore-log: 
,03-29 16:23:05.022  3271  3327 I jxcore-log: # teardown
03-29 16:23:05.022  3271  3327 I jxcore-log: 
,03-29 16:23:05.040   823  1378 I ActivityManager: Killing 3422:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-29 16:23:05.112  3271  3327 I jxcore-log: # setup
03-29 16:23:05.112  3271  3327 I jxcore-log: 
,03-29 16:23:05.226  3271  3327 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-29 16:23:05.226  3271  3327 I jxcore-log: 
,03-29 16:23:05.407  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:05.407  3271  3327 I jxcore-log: 
,03-29 16:23:05.415  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 54660
03-29 16:23:05.415  3271  3327 I jxcore-log: 
,03-29 16:23:05.425  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:05.425  3271  3327 I jxcore-log: 
,03-29 16:23:05.427  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:05.427  3271  3327 I jxcore-log: 
,03-29 16:23:05.429  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:05.429  3271  3327 I jxcore-log: 
,03-29 16:23:05.441  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:05.441  3271  3327 I jxcore-log: 
,03-29 16:23:05.444  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:05.444  3271  3327 I jxcore-log: 
,03-29 16:23:05.458  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:05.458  3271  3327 I jxcore-log: 
,03-29 16:23:05.468  3271  3327 I jxcore-log: ok 17 stream was closed
03-29 16:23:05.468  3271  3327 I jxcore-log: 
,03-29 16:23:05.469  3271  3327 I jxcore-log: ok 18 incoming should survive
03-29 16:23:05.469  3271  3327 I jxcore-log: 
,03-29 16:23:05.469  3271  3327 I jxcore-log: ok 19 mux should have no streams
03-29 16:23:05.469  3271  3327 I jxcore-log: 
,03-29 16:23:05.477  3271  3327 I jxcore-log: # teardown
03-29 16:23:05.477  3271  3327 I jxcore-log: 
,03-29 16:23:05.878  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:05.878  3271  3327 I jxcore-log: 
,03-29 16:23:05.884  3271  3327 I jxcore-log: # setup
03-29 16:23:05.884  3271  3327 I jxcore-log: 
,03-29 16:23:05.885  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:05.885  3271  3327 I jxcore-log: 
,03-29 16:23:06.311  2160  2225 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 16:23:14.165  3271  3327 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-29 16:23:14.165  3271  3327 I jxcore-log: 
,03-29 16:23:16.668  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server,
03-29 16:23:16.668  3271  3327 I jxcore-log: 
03-29 16:23:16.672  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 53541
03-29 16:23:16.672  3271  3327 I jxcore-log: 
,03-29 16:23:16.678  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-29 16:23:16.678  3271  3327 I jxcore-log: 
03-29 16:23:16.679  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:16.679  3271  3327 I jxcore-log: 
03-29 16:23:16.680  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:16.680  3271  3327 I jxcore-log: 
,03-29 16:23:16.690  3271  3327 I jxcore-log: ok 20 we should not have gotten an error
03-29 16:23:16.690  3271  3327 I jxcore-log: 
,03-29 16:23:16.696  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:16.696  3271  3327 I jxcore-log: 
,03-29 16:23:16.699  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 16:23:16.699  3271  3327 I jxcore-log: 
,03-29 16:23:16.710  3271  3327 I jxcore-log: ok 21 Buffers are identical
03-29 16:23:16.710  3271  3327 I jxcore-log: 
,03-29 16:23:16.712  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:16.712  3271  3327 I jxcore-log: 
,03-29 16:23:16.716  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:16.716  3271  3327 I jxcore-log: 
,03-29 16:23:16.719  3271  3327 I jxcore-log: ok 22 native server is nulled out
03-29 16:23:16.719  3271  3327 I jxcore-log: 
,03-29 16:23:16.719  3271  3327 I jxcore-log: ok 23 native server should be closed
03-29 16:23:16.719  3271  3327 I jxcore-log: 
03-29 16:23:16.720  3271  3327 I jxcore-log: ok 24 incoming has been removed
03-29 16:23:16.720  3271  3327 I jxcore-log: 
,03-29 16:23:16.720  3271  3327 I jxcore-log: ok 25 Incoming should be done
03-29 16:23:16.720  3271  3327 I jxcore-log: 
03-29 16:23:16.720  3271  3327 I jxcore-log: ok 26 The mux object should be closed
03-29 16:23:16.720  3271  3327 I jxcore-log: 
03-29 16:23:16.721  3271  3327 I jxcore-log: ok 27 The mux stream should be closed
03-29 16:23:16.721  3271  3327 I jxcore-log: 
03-29 16:23:16.721  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:16.721  3271  3327 I jxcore-log: 
,03-29 16:23:16.749  3271  3327 I jxcore-log: # teardown
03-29 16:23:16.749  3271  3327 I jxcore-log: 
,03-29 16:23:20.765  1406  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:20.822  1406  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 16:23:20.823  1406  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 16:23:20.823  1406  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 16:23:20.823  1406  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:20.834  1406  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:20.866  3714  3714 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 16:23:20.867  3714  3714 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 16:23:20.869  3714  3714 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-29 16:23:23.244  3271  3327 I jxcore-log: # setup
03-29 16:23:23.244  3271  3327 I jxcore-log: 
,03-29 16:23:23.437  3271  3327 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-29 16:23:23.437  3271  3327 I jxcore-log: 
,03-29 16:23:23.783  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:23.783  3271  3327 I jxcore-log: 
,03-29 16:23:23.786  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 35709
03-29 16:23:23.786  3271  3327 I jxcore-log: 
,03-29 16:23:23.811  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.811  3271  3327 I jxcore-log: 
,03-29 16:23:23.813  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.813  3271  3327 I jxcore-log: 
03-29 16:23:23.815  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.815  3271  3327 I jxcore-log: 
,03-29 16:23:23.818  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.818  3271  3327 I jxcore-log: 
,03-29 16:23:23.819  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.819  3271  3327 I jxcore-log: 
,03-29 16:23:23.820  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.820  3271  3327 I jxcore-log: 
,03-29 16:23:23.823  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.823  3271  3327 I jxcore-log: 
,03-29 16:23:23.824  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.824  3271  3327 I jxcore-log: 
,03-29 16:23:23.825  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.825  3271  3327 I jxcore-log: 
,03-29 16:23:23.829  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.829  3271  3327 I jxcore-log: 
03-29 16:23:23.829  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.829  3271  3327 I jxcore-log: 
,03-29 16:23:23.830  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.830  3271  3327 I jxcore-log: 
03-29 16:23:23.833  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.833  3271  3327 I jxcore-log: 
03-29 16:23:23.834  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.834  3271  3327 I jxcore-log: 
,03-29 16:23:23.835  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.835  3271  3327 I jxcore-log: 
03-29 16:23:23.837  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.837  3271  3327 I jxcore-log: 
,03-29 16:23:23.838  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.838  3271  3327 I jxcore-log: 
,03-29 16:23:23.839  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.839  3271  3327 I jxcore-log: 
,03-29 16:23:23.841  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.841  3271  3327 I jxcore-log: 
,03-29 16:23:23.842  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.842  3271  3327 I jxcore-log: 
,03-29 16:23:23.843  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.843  3271  3327 I jxcore-log: 
,03-29 16:23:23.845  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.845  3271  3327 I jxcore-log: 
,03-29 16:23:23.846  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.846  3271  3327 I jxcore-log: 
,03-29 16:23:23.847  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.847  3271  3327 I jxcore-log: 
,03-29 16:23:23.849  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.849  3271  3327 I jxcore-log: 
,03-29 16:23:23.850  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.850  3271  3327 I jxcore-log: 
03-29 16:23:23.851  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.851  3271  3327 I jxcore-log: 
,03-29 16:23:23.854  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:23.854  3271  3327 I jxcore-log: 
,03-29 16:23:23.854  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:23.854  3271  3327 I jxcore-log: 
03-29 16:23:23.855  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:23.855  3271  3327 I jxcore-log: 
,03-29 16:23:23.941  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.941  3271  3327 I jxcore-log: 
,03-29 16:23:23.944  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.944  3271  3327 I jxcore-log: 
,03-29 16:23:23.946  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.946  3271  3327 I jxcore-log: 
,03-29 16:23:23.948  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.948  3271  3327 I jxcore-log: 
,03-29 16:23:23.949  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.949  3271  3327 I jxcore-log: 
,03-29 16:23:23.951  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.951  3271  3327 I jxcore-log: 
,03-29 16:23:23.953  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.953  3271  3327 I jxcore-log: 
,03-29 16:23:23.955  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.955  3271  3327 I jxcore-log: 
,03-29 16:23:23.957  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.957  3271  3327 I jxcore-log: 
,03-29 16:23:23.959  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.959  3271  3327 I jxcore-log: 
,03-29 16:23:23.960  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.960  3271  3327 I jxcore-log: 
,03-29 16:23:23.961  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.961  3271  3327 I jxcore-log: 
,03-29 16:23:23.962  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.962  3271  3327 I jxcore-log: 
,03-29 16:23:23.964  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.964  3271  3327 I jxcore-log: 
,03-29 16:23:23.965  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.965  3271  3327 I jxcore-log: 
,03-29 16:23:23.966  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.966  3271  3327 I jxcore-log: 
,03-29 16:23:23.968  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.968  3271  3327 I jxcore-log: 
,03-29 16:23:23.969  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.969  3271  3327 I jxcore-log: 
,03-29 16:23:23.970  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.970  3271  3327 I jxcore-log: 
,03-29 16:23:23.972  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 16:23:23.972  3271  3327 I jxcore-log: 
,03-29 16:23:23.975  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 16:23:23.975  3271  3327 I jxcore-log: 
,03-29 16:23:23.977  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.977  3271  3327 I jxcore-log: 
,03-29 16:23:23.978  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 16:23:23.978  3271  3327 I jxcore-log: 
,03-29 16:23:23.979  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.979  3271  3327 I jxcore-log: 
,03-29 16:23:23.981  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 16:23:23.981  3271  3327 I jxcore-log: 
,03-29 16:23:23.982  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.982  3271  3327 I jxcore-log: 
,03-29 16:23:23.983  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 16:23:23.983  3271  3327 I jxcore-log: 
,03-29 16:23:23.984  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.984  3271  3327 I jxcore-log: 
,03-29 16:23:23.985  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 16:23:23.985  3271  3327 I jxcore-log: 
,03-29 16:23:23.987  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.987  3271  3327 I jxcore-log: 
,03-29 16:23:23.988  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 16:23:23.988  3271  3327 I jxcore-log: 
,03-29 16:23:23.989  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.989  3271  3327 I jxcore-log: 
,03-29 16:23:23.990  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.990  3271  3327 I jxcore-log: 
,03-29 16:23:23.992  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.992  3271  3327 I jxcore-log: 
,03-29 16:23:23.993  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.993  3271  3327 I jxcore-log: 
,03-29 16:23:23.994  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.994  3271  3327 I jxcore-log: 
,03-29 16:23:23.995  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.995  3271  3327 I jxcore-log: 
,03-29 16:23:23.996  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.996  3271  3327 I jxcore-log: 
,03-29 16:23:23.997  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:23.997  3271  3327 I jxcore-log: 
,03-29 16:23:23.999  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:23.999  3271  3327 I jxcore-log: 
,03-29 16:23:24.000  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.000  3271  3327 I jxcore-log: 
,03-29 16:23:24.002  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.002  3271  3327 I jxcore-log: 
,03-29 16:23:24.003  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.003  3271  3327 I jxcore-log: 
,03-29 16:23:24.004  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.004  3271  3327 I jxcore-log: 
,03-29 16:23:24.005  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.005  3271  3327 I jxcore-log: 
,03-29 16:23:24.006  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.006  3271  3327 I jxcore-log: 
,03-29 16:23:24.013  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.013  3271  3327 I jxcore-log: 
,03-29 16:23:24.015  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.015  3271  3327 I jxcore-log: 
,03-29 16:23:24.017  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.017  3271  3327 I jxcore-log: 
,03-29 16:23:24.018  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.018  3271  3327 I jxcore-log: 
,03-29 16:23:24.019  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.019  3271  3327 I jxcore-log: 
,03-29 16:23:24.020  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.020  3271  3327 I jxcore-log: 
03-29 16:23:24.021  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.021  3271  3327 I jxcore-log: 
,03-29 16:23:24.022  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.022  3271  3327 I jxcore-log: 
03-29 16:23:24.023  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.023  3271  3327 I jxcore-log: 
,03-29 16:23:24.025  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.025  3271  3327 I jxcore-log: 
03-29 16:23:24.026  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.026  3271  3327 I jxcore-log: 
,03-29 16:23:24.029  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.029  3271  3327 I jxcore-log: 
,03-29 16:23:24.030  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.030  3271  3327 I jxcore-log: 
,03-29 16:23:24.031  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.031  3271  3327 I jxcore-log: 
,03-29 16:23:24.032  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.032  3271  3327 I jxcore-log: 
,03-29 16:23:24.033  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.033  3271  3327 I jxcore-log: 
,03-29 16:23:24.034  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.034  3271  3327 I jxcore-log: 
,03-29 16:23:24.035  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.035  3271  3327 I jxcore-log: 
,03-29 16:23:24.037  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.037  3271  3327 I jxcore-log: 
,03-29 16:23:24.038  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.038  3271  3327 I jxcore-log: 
,03-29 16:23:24.039  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.039  3271  3327 I jxcore-log: 
,03-29 16:23:24.041  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.041  3271  3327 I jxcore-log: 
,03-29 16:23:24.042  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.042  3271  3327 I jxcore-log: 
,03-29 16:23:24.043  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.043  3271  3327 I jxcore-log: 
,03-29 16:23:24.044  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.044  3271  3327 I jxcore-log: 
,03-29 16:23:24.045  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.045  3271  3327 I jxcore-log: 
,03-29 16:23:24.047  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.047  3271  3327 I jxcore-log: 
,03-29 16:23:24.048  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.048  3271  3327 I jxcore-log: 
,03-29 16:23:24.049  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.049  3271  3327 I jxcore-log: 
03-29 16:23:24.051  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.051  3271  3327 I jxcore-log: 
,03-29 16:23:24.051  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.051  3271  3327 I jxcore-log: 
,03-29 16:23:24.053  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.053  3271  3327 I jxcore-log: 
,03-29 16:23:24.054  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.054  3271  3327 I jxcore-log: 
,03-29 16:23:24.055  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.055  3271  3327 I jxcore-log: 
,03-29 16:23:24.127  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.127  3271  3327 I jxcore-log: 
,03-29 16:23:24.129  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.129  3271  3327 I jxcore-log: 
03-29 16:23:24.129  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.129  3271  3327 I jxcore-log: 
,03-29 16:23:24.130  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.130  3271  3327 I jxcore-log: 
03-29 16:23:24.131  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.131  3271  3327 I jxcore-log: 
03-29 16:23:24.132  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.132  3271  3327 I jxcore-log: 
,03-29 16:23:24.134  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.134  3271  3327 I jxcore-log: 
03-29 16:23:24.135  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.135  3271  3327 I jxcore-log: 
03-29 16:23:24.136  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.136  3271  3327 I jxcore-log: 
,03-29 16:23:24.137  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.137  3271  3327 I jxcore-log: 
,03-29 16:23:24.140  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.140  3271  3327 I jxcore-log: 
,03-29 16:23:24.141  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.141  3271  3327 I jxcore-log: 
03-29 16:23:24.142  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.142  3271  3327 I jxcore-log: 
,03-29 16:23:24.142  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.142  3271  3327 I jxcore-log: 
,03-29 16:23:24.144  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.144  3271  3327 I jxcore-log: 
,03-29 16:23:24.145  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.145  3271  3327 I jxcore-log: 
03-29 16:23:24.146  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.146  3271  3327 I jxcore-log: 
,03-29 16:23:24.147  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.147  3271  3327 I jxcore-log: 
03-29 16:23:24.148  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.148  3271  3327 I jxcore-log: 
,03-29 16:23:24.149  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.149  3271  3327 I jxcore-log: 
,03-29 16:23:24.150  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.150  3271  3327 I jxcore-log: 
03-29 16:23:24.151  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.151  3271  3327 I jxcore-log: 
,03-29 16:23:24.152  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.152  3271  3327 I jxcore-log: ,
03-29 16:23:24.152  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.152  3271  3327 I jxcore-log: 
03-29 16:23:24.154  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.154  3271  3327 I jxcore-log: 
,03-29 16:23:24.155  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.155  3271  3327 I jxcore-log: 
,03-29 16:23:24.156  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.156  3271  3327 I jxcore-log: 
,03-29 16:23:24.157  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.157  3271  3327 I jxcore-log: 
,03-29 16:23:24.157  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.157  3271  3327 I jxcore-log: 
03-29 16:23:24.158  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.158  3271  3327 I jxcore-log: 
03-29 16:23:24.159  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.159  3271  3327 I jxcore-log: 
,03-29 16:23:24.160  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.160  3271  3327 I jxcore-log: 
03-29 16:23:24.161  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.161  3271  3327 I jxcore-log: 
03-29 16:23:24.162  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.162  3271  3327 I jxcore-log: 
,03-29 16:23:24.162  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.162  3271  3327 I jxcore-log: 
03-29 16:23:24.163  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.163  3271  3327 I jxcore-log: 
03-29 16:23:24.164  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.164  3271  3327 I jxcore-log: 
,03-29 16:23:24.165  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.165  3271  3327 I jxcore-log: 
03-29 16:23:24.166  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.166  3271  3327 I jxcore-log: 
03-29 16:23:24.167  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.167  3271  3327 I jxcore-log: 
,03-29 16:23:24.168  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.168  3271  3327 I jxcore-log: 
03-29 16:23:24.168  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.168  3271  3327 I jxcore-log: 
03-29 16:23:24.169  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.169  3271  3327 I jxcore-log: 
,03-29 16:23:24.170  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.170  3271  3327 I jxcore-log: 
03-29 16:23:24.171  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.171  3271  3327 I jxcore-log: 
03-29 16:23:24.171  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.171  3271  3327 I jxcore-log: 
,03-29 16:23:24.172  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.172  3271  3327 I jxcore-log: 
03-29 16:23:24.173  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.173  3271  3327 I jxcore-log: 
03-29 16:23:24.174  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.174  3271  3327 I jxcore-log: 
,03-29 16:23:24.175  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.175  3271  3327 I jxcore-log: 
03-29 16:23:24.178  3271  3327 I jxcore-log: ok 28 native server is nulled out
03-29 16:23:24.178  3271  3327 I jxcore-log: 
03-29 16:23:24.178  3271  3327 I jxcore-log: ok 29 native server should be closed
03-29 16:23:24.178  3271  3327 I jxcore-log: 
,03-29 16:23:24.179  3271  3327 I jxcore-log: ok 30 incoming has been removed
03-29 16:23:24.179  3271  3327 I jxcore-log: 
03-29 16:23:24.180  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.180  3271  3327 I jxcore-log: 
03-29 16:23:24.180  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.180  3271  3327 I jxcore-log: 
,03-29 16:23:24.181  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.181  3271  3327 I jxcore-log: 
03-29 16:23:24.181  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.181  3271  3327 I jxcore-log: 
03-29 16:23:24.181  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.181  3271  3327 I jxcore-log: 
,03-29 16:23:24.182  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.182  3271  3327 I jxcore-log: 
03-29 16:23:24.182  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.182  3271  3327 I jxcore-log: 
03-29 16:23:24.182  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.182  3271  3327 I jxcore-log: 
,03-29 16:23:24.183  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.183  3271  3327 I jxcore-log: 
03-29 16:23:24.183  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.183  3271  3327 I jxcore-log: 
,03-29 16:23:24.284  3271  3327 I jxcore-log: # teardown
03-29 16:23:24.284  3271  3327 I jxcore-log: 
,03-29 16:23:24.485  3271  3327 I jxcore-log: # setup
03-29 16:23:24.485  3271  3327 I jxcore-log: 
,03-29 16:23:24.646  3271  3327 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-29 16:23:24.646  3271  3327 I jxcore-log: 
,03-29 16:23:24.877  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:24.877  3271  3327 I jxcore-log: 
,03-29 16:23:24.885  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 39815
03-29 16:23:24.885  3271  3327 I jxcore-log: 
,03-29 16:23:24.891  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:24.891  3271  3327 I jxcore-log: 
,03-29 16:23:24.892  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:24.892  3271  3327 I jxcore-log: 
,03-29 16:23:24.894  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:24.894  3271  3327 I jxcore-log: 
,03-29 16:23:24.901  3271  3327 I jxcore-log: ok 31 we should not have gotten an error
03-29 16:23:24.901  3271  3327 I jxcore-log: 
,03-29 16:23:24.905  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:24.905  3271  3327 I jxcore-log: 
,03-29 16:23:24.907  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:24.907  3271  3327 I jxcore-log: 
,03-29 16:23:24.915  3271  3327 I jxcore-log: ok 32 Buffers are identical
03-29 16:23:24.915  3271  3327 I jxcore-log: 
,03-29 16:23:24.916  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:24.916  3271  3327 I jxcore-log: 
,03-29 16:23:24.917  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:24.917  3271  3327 I jxcore-log: 
,03-29 16:23:24.929  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:24.929  3271  3327 I jxcore-log: 
,03-29 16:23:24.930  3271  3327 I jxcore-log: ok 33 server should be fine
03-29 16:23:24.930  3271  3327 I jxcore-log: 
,03-29 16:23:24.930  3271  3327 I jxcore-log: ok 34 server should be open
03-29 16:23:24.930  3271  3327 I jxcore-log: 
,03-29 16:23:24.930  3271  3327 I jxcore-log: ok 35 incoming has been removed
03-29 16:23:24.930  3271  3327 I jxcore-log: 
03-29 16:23:24.931  3271  3327 I jxcore-log: ok 36 The mux object should be closed
03-29 16:23:24.931  3271  3327 I jxcore-log: 
03-29 16:23:24.931  3271  3327 I jxcore-log: ok 37 The mux stream should be closed
03-29 16:23:24.931  3271  3327 I jxcore-log: 
,03-29 16:23:24.938  3271  3327 I jxcore-log: # teardown
03-29 16:23:24.938  3271  3327 I jxcore-log: 
,03-29 16:23:25.048  3271  3327 I jxcore-log: # setup
03-29 16:23:25.048  3271  3327 I jxcore-log: 
,03-29 16:23:25.208  3271  3327 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-29 16:23:25.208  3271  3327 I jxcore-log: 
,03-29 16:23:25.380  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:25.380  3271  3327 I jxcore-log: 
,03-29 16:23:25.387  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 41211
03-29 16:23:25.387  3271  3327 I jxcore-log: 
,03-29 16:23:25.392  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:23:25.392  3271  3327 I jxcore-log: 
,03-29 16:23:25.393  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:23:25.393  3271  3327 I jxcore-log: 
,03-29 16:23:25.395  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:23:25.395  3271  3327 I jxcore-log: 
,03-29 16:23:25.401  3271  3327 I jxcore-log: ok 38 we should not have gotten an error
03-29 16:23:25.401  3271  3327 I jxcore-log: 
,03-29 16:23:25.405  3271  3327 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 16:23:25.405  3271  3327 I jxcore-log: 
,03-29 16:23:25.407  3271  3327 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 16:23:25.407  3271  3327 I jxcore-log: 
,03-29 16:23:25.413  3271  3327 I jxcore-log: ok 39 Buffers are identical
03-29 16:23:25.413  3271  3327 I jxcore-log: 
,03-29 16:23:25.417  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-29 16:23:25.417  3271  3327 I jxcore-log: 
,03-29 16:23:25.419  3271  3327 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 16:23:25.419  3271  3327 I jxcore-log: 
,03-29 16:23:25.420  3271  3327 I jxcore-log: DEBUG createNativeListener: mux close
03-29 16:23:25.420  3271  3327 I jxcore-log: 
,03-29 16:23:25.425  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:23:25.425  3271  3327 I jxcore-log: 
,03-29 16:23:25.426  3271  3327 I jxcore-log: ok 40 server should be fine
03-29 16:23:25.426  3271  3327 I jxcore-log: 
,03-29 16:23:25.426  3271  3327 I jxcore-log: ok 41 server should be open
03-29 16:23:25.426  3271  3327 I jxcore-log: 
03-29 16:23:25.427  3271  3327 I jxcore-log: ok 42 incoming has been removed
03-29 16:23:25.427  3271  3327 I jxcore-log: 
03-29 16:23:25.427  3271  3327 I jxcore-log: ok 43 The mux object should be closed
03-29 16:23:25.427  3271  3327 I jxcore-log: 
,03-29 16:23:25.427  3271  3327 I jxcore-log: ok 44 The mux stream should be closed
03-29 16:23:25.427  3271  3327 I jxcore-log: 
03-29 16:23:25.434  3271  3327 I jxcore-log: # teardown
03-29 16:23:25.434  3271  3327 I jxcore-log: 
,03-29 16:23:25.606  3271  3327 I jxcore-log: # setup
03-29 16:23:25.606  3271  3327 I jxcore-log: 
,03-29 16:23:25.816  3271  3327 I jxcore-log: # 12. closeAll can close even when connections open
03-29 16:23:25.816  3271  3327 I jxcore-log: 
,03-29 16:23:25.997  3271  3327 I jxcore-log: ok 45 not possible to connect to the server anymore
03-29 16:23:25.997  3271  3327 I jxcore-log: 
,03-29 16:23:26.002  3271  3327 I jxcore-log: # teardown
03-29 16:23:26.002  3271  3327 I jxcore-log: 
,03-29 16:23:26.151  3271  3327 I jxcore-log: # setup
03-29 16:23:26.151  3271  3327 I jxcore-log: 
,03-29 16:23:26.442  3271  3327 I jxcore-log: # 13. closeAll with promise
03-29 16:23:26.442  3271  3327 I jxcore-log: 
,03-29 16:23:26.666  3271  3327 I jxcore-log: ok 46 not possible to connect to the server anymore
03-29 16:23:26.666  3271  3327 I jxcore-log: 
,03-29 16:23:26.671  3271  3327 I jxcore-log: # teardown
03-29 16:23:26.671  3271  3327 I jxcore-log: 
,03-29 16:23:26.889  3271  3327 I jxcore-log: # setup
03-29 16:23:26.889  3271  3327 I jxcore-log: 
,03-29 16:23:27.494  3271  3327 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-29 16:23:27.494  3271  3327 I jxcore-log: 
,03-29 16:23:27.651  3271  3327 I jxcore-log: ok 47 Got the right error
03-29 16:23:27.651  3271  3327 I jxcore-log: 
,03-29 16:23:27.653  3271  3327 I jxcore-log: # teardown
03-29 16:23:27.653  3271  3327 I jxcore-log: 
,03-29 16:23:27.841  3271  3327 I jxcore-log: # setup
03-29 16:23:27.841  3271  3327 I jxcore-log: 
,03-29 16:23:27.981  3271  3327 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-29 16:23:27.981  3271  3327 I jxcore-log: 
,03-29 16:23:28.115  3271  3327 I jxcore-log: # teardown
03-29 16:23:28.115  3271  3327 I jxcore-log: 
,03-29 16:23:28.235  3271  3327 I jxcore-log: # setup
03-29 16:23:28.235  3271  3327 I jxcore-log: 
,03-29 16:23:28.355  3271  3327 I jxcore-log: # 16. multiplex can send data
03-29 16:23:28.355  3271  3327 I jxcore-log: 
,03-29 16:23:28.534  3271  3327 I jxcore-log: ok 48 String should be length:200
03-29 16:23:28.534  3271  3327 I jxcore-log: 
,03-29 16:23:28.543  3271  3327 I jxcore-log: # teardown
03-29 16:23:28.543  3271  3327 I jxcore-log: 
,03-29 16:23:28.632  3271  3327 I jxcore-log: # setup
,03-29 16:23:28.632  3271  3327 I jxcore-log: 
,03-29 16:23:28.789  3271  3327 I jxcore-log: # 17. enqueue and run in order
03-29 16:23:28.789  3271  3327 I jxcore-log: 
,03-29 16:23:28.979  3380  3816 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 16:23:29.048  1406  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 16:23:29.048  1406  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:29.048  1406  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:29.048  1406  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:29.055  1406  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 16:23:29.078  3380  3816 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 16:23:29.138  3271  3327 I jxcore-log: ok 49 firstPromise setTimeout
03-29 16:23:29.138  3271  3327 I jxcore-log: 
,03-29 16:23:29.140  3271  3327 I jxcore-log: ok 50 firstPromise result
03-29 16:23:29.140  3271  3327 I jxcore-log: 
,03-29 16:23:29.141  3271  3327 I jxcore-log: ok 51 firstPromise testValue
03-29 16:23:29.141  3271  3327 I jxcore-log: 
,03-29 16:23:29.245  3271  3327 I jxcore-log: ok 52 secondPromise setTimeout
03-29 16:23:29.245  3271  3327 I jxcore-log: 
,03-29 16:23:29.249  3271  3327 I jxcore-log: ok 53 secondPromise result
03-29 16:23:29.249  3271  3327 I jxcore-log: 
,03-29 16:23:29.251  3271  3327 I jxcore-log: ok 54 secondPromise testValue
03-29 16:23:29.251  3271  3327 I jxcore-log: 
,03-29 16:23:29.254  3271  3327 I jxcore-log: ok 55 thirdPromise in promise
03-29 16:23:29.254  3271  3327 I jxcore-log: 
,03-29 16:23:29.257  3271  3327 I jxcore-log: ok 56 thirdPromise result
03-29 16:23:29.257  3271  3327 I jxcore-log: 
,03-29 16:23:29.259  3271  3327 I jxcore-log: ok 57 thirdPromise testValue
03-29 16:23:29.259  3271  3327 I jxcore-log: 
,03-29 16:23:29.270  3271  3327 I jxcore-log: # teardown
03-29 16:23:29.270  3271  3327 I jxcore-log: 
,03-29 16:23:29.642  3271  3327 I jxcore-log: # setup
03-29 16:23:29.642  3271  3327 I jxcore-log: 
,03-29 16:23:29.940  3271  3327 I jxcore-log: # 18. enqueueAtTop and run backwards
03-29 16:23:29.940  3271  3327 I jxcore-log: 
,03-29 16:23:30.486  3271  3327 I jxcore-log: ok 58 thirdPromise - first to run
03-29 16:23:30.486  3271  3327 I jxcore-log: 
,03-29 16:23:30.488  3271  3327 I jxcore-log: ok 59 thirdPromise - in resolve
03-29 16:23:30.488  3271  3327 I jxcore-log: 
,03-29 16:23:30.489  3271  3327 I jxcore-log: ok 60 secondPromise - second to run
03-29 16:23:30.489  3271  3327 I jxcore-log: 
,03-29 16:23:30.490  3271  3327 I jxcore-log: ok 61 secondPromise - in catch
03-29 16:23:30.490  3271  3327 I jxcore-log: 
03-29 16:23:30.490  3271  3327 I jxcore-log: ok 62 firstPromise - third to run
03-29 16:23:30.490  3271  3327 I jxcore-log: 
03-29 16:23:30.491  3271  3327 I jxcore-log: ok 63 firstPromise - in then
03-29 16:23:30.491  3271  3327 I jxcore-log: 
03-29 16:23:30.491  3271  3327 I jxcore-log: ok 64 testing promises
03-29 16:23:30.491  3271  3327 I jxcore-log: 
,03-29 16:23:30.494  3271  3327 I jxcore-log: # teardown
03-29 16:23:30.494  3271  3327 I jxcore-log: 
,03-29 16:23:30.646  3271  3327 I jxcore-log: # setup
03-29 16:23:30.646  3271  3327 I jxcore-log: 
,03-29 16:23:30.781  3271  3327 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-29 16:23:30.781  3271  3327 I jxcore-log: 
,03-29 16:23:30.896  3271  3327 I jxcore-log: ok 65 fourth
03-29 16:23:30.896  3271  3327 I jxcore-log: 
,03-29 16:23:30.899  3271  3327 I jxcore-log: ok 66 fourth
03-29 16:23:30.899  3271  3327 I jxcore-log: 
,03-29 16:23:30.903  3271  3327 I jxcore-log: ok 67 second,
03-29 16:23:30.903  3271  3327 I jxcore-log: 
03-29 16:23:30.905  3271  3327 I jxcore-log: ok 68 secondPromise - in then
03-29 16:23:30.905  3271  3327 I jxcore-log: 
,03-29 16:23:31.009  3271  3327 I jxcore-log: ok 69 first
03-29 16:23:31.009  3271  3327 I jxcore-log: 
,03-29 16:23:31.011  3271  3327 I jxcore-log: ok 70 firstPromise - in catch
03-29 16:23:31.011  3271  3327 I jxcore-log: 
,03-29 16:23:31.014  3271  3327 I jxcore-log: ok 71 third
03-29 16:23:31.014  3271  3327 I jxcore-log: 
,03-29 16:23:31.016  3271  3327 I jxcore-log: ok 72 thirdPromise - in then
03-29 16:23:31.016  3271  3327 I jxcore-log: 
,03-29 16:23:31.019  3271  3327 I jxcore-log: ok 73 testingPromises
03-29 16:23:31.019  3271  3327 I jxcore-log: 
,03-29 16:23:31.031  3271  3327 I jxcore-log: # teardown
03-29 16:23:31.031  3271  3327 I jxcore-log: 
,03-29 16:23:31.131  3271  3327 I jxcore-log: # setup
03-29 16:23:31.131  3271  3327 I jxcore-log: 
,03-29 16:23:31.246  3271  3327 I jxcore-log: # 20. queues handled independently
03-29 16:23:31.246  3271  3327 I jxcore-log: 
,03-29 16:23:31.431  3271  3327 I jxcore-log: ok 74 all short operations completed before the long resolves
03-29 16:23:31.431  3271  3327 I jxcore-log: 
,03-29 16:23:31.436  3271  3327 I jxcore-log: # teardown
03-29 16:23:31.436  3271  3327 I jxcore-log: 
,03-29 16:23:31.590  3271  3327 I jxcore-log: # setup
03-29 16:23:31.590  3271  3327 I jxcore-log: 
,03-29 16:23:31.730  3271  3327 I jxcore-log: # 21. basic
03-29 16:23:31.730  3271  3327 I jxcore-log: 
,03-29 16:23:31.957  3271  3327 I jxcore-log: ok 75 sane
03-29 16:23:31.957  3271  3327 I jxcore-log: 
,03-29 16:23:31.964  3271  3327 I jxcore-log: # teardown
03-29 16:23:31.964  3271  3327 I jxcore-log: 
,03-29 16:23:32.085  3271  3327 I jxcore-log: # setup
03-29 16:23:32.085  3271  3327 I jxcore-log: 
,03-29 16:23:32.220  3271  3327 I jxcore-log: # 22. another
03-29 16:23:32.220  3271  3327 I jxcore-log: 
,03-29 16:23:32.368  3271  3327 I jxcore-log: ok 76 sane
03-29 16:23:32.368  3271  3327 I jxcore-log: 
,03-29 16:23:32.374  3271  3327 I jxcore-log: # teardown
03-29 16:23:32.374  3271  3327 I jxcore-log: 
,03-29 16:23:32.532  3271  3327 I jxcore-log: # setup
03-29 16:23:32.532  3271  3327 I jxcore-log: 
,03-29 16:23:32.639  3271  3327 I jxcore-log: # 23. can pass data in setup
03-29 16:23:32.639  3271  3327 I jxcore-log: 
,03-29 16:23:32.754  3271  3327 I jxcore-log: ok 77 test participant has uuid
03-29 16:23:32.754  3271  3327 I jxcore-log: 
,03-29 16:23:32.756  3271  3327 I jxcore-log: ok 78 participant data matches
03-29 16:23:32.756  3271  3327 I jxcore-log: 
,03-29 16:23:32.757  3271  3327 I jxcore-log: ok 79 test participant has uuid
03-29 16:23:32.757  3271  3327 I jxcore-log: 
03-29 16:23:32.759  3271  3327 I jxcore-log: ok 80 participant data matches
03-29 16:23:32.759  3271  3327 I jxcore-log: 
,03-29 16:23:32.760  3271  3327 I jxcore-log: ok 81 test participant has uuid
03-29 16:23:32.760  3271  3327 I jxcore-log: 
03-29 16:23:32.762  3271  3327 I jxcore-log: ok 82 participant data matches
03-29 16:23:32.762  3271  3327 I jxcore-log: 
,03-29 16:23:32.764  3271  3327 I jxcore-log: ok 83 own UUID is found from the participants list
03-29 16:23:32.764  3271  3327 I jxcore-log: 
,03-29 16:23:32.767  3271  3327 I jxcore-log: # teardown
03-29 16:23:32.767  3271  3327 I jxcore-log: 
,03-29 16:23:32.894  3271  3327 I jxcore-log: # setup
03-29 16:23:32.894  3271  3327 I jxcore-log: 
,03-29 16:23:33.045  3271  3327 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-29 16:23:33.045  3271  3327 I jxcore-log: 
,03-29 16:23:33.266  3271  3327 I jxcore-log: ok 84 specific error should be returned
03-29 16:23:33.266  3271  3327 I jxcore-log: 
,03-29 16:23:33.268  3271  3327 I jxcore-log: # teardown
03-29 16:23:33.268  3271  3327 I jxcore-log: 
,03-29 16:23:33.446  3271  3327 I jxcore-log: ok 85 error should be null
03-29 16:23:33.446  3271  3327 I jxcore-log: 
,03-29 16:23:33.446  3271  3327 I jxcore-log: ok 86 error should be null
03-29 16:23:33.446  3271  3327 I jxcore-log: 
03-29 16:23:33.448  3271  3327 I jxcore-log: # setup
03-29 16:23:33.448  3271  3327 I jxcore-log: 
,03-29 16:23:33.600  3271  3327 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-29 16:23:33.600  3271  3327 I jxcore-log: 
,03-29 16:23:33.705  3271  3327 I jxcore-log: ok 87 specific error should be returned
03-29 16:23:33.705  3271  3327 I jxcore-log: 
,03-29 16:23:33.707  3271  3327 I jxcore-log: # teardown
03-29 16:23:33.707  3271  3327 I jxcore-log: 
,03-29 16:23:33.816  3271  3327 I jxcore-log: ok 88 error should be null
03-29 16:23:33.816  3271  3327 I jxcore-log: 
,03-29 16:23:33.817  3271  3327 I jxcore-log: ok 89 error should be null
03-29 16:23:33.817  3271  3327 I jxcore-log: 
,03-29 16:23:33.819  3271  3327 I jxcore-log: # setup
03-29 16:23:33.819  3271  3327 I jxcore-log: 
,03-29 16:23:33.990  3271  3327 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-29 16:23:33.990  3271  3327 I jxcore-log: 
,03-29 16:23:34.226  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:34.226  3271  3327 I jxcore-log: 
,03-29 16:23:34.227  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 58693
03-29 16:23:34.227  3271  3327 I jxcore-log: 
,03-29 16:23:34.230  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:34.230  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:34.230  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.236  3271  3327 I jxcore-log: ok 90 error should be null
03-29 16:23:34.236  3271  3327 I jxcore-log: 
,03-29 16:23:34.237  3271  3327 I jxcore-log: ok 91 error should be null
03-29 16:23:34.237  3271  3327 I jxcore-log: 
03-29 16:23:34.238  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:34.238  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:34.238  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.241  3271  3327 I jxcore-log: ok 92 error should be null
03-29 16:23:34.241  3271  3327 I jxcore-log: 
03-29 16:23:34.241  3271  3327 I jxcore-log: ok 93 error should be null
03-29 16:23:34.241  3271  3327 I jxcore-log: 
,03-29 16:23:34.246  3271  3327 I jxcore-log: # teardown
03-29 16:23:34.246  3271  3327 I jxcore-log: 
,03-29 16:23:34.387  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:34.387  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:34.387  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.391  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:34.391  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:34.391  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:34.397  3271  3327 I jxcore-log: ok 94 error should be null
03-29 16:23:34.397  3271  3327 I jxcore-log: 
,03-29 16:23:34.397  3271  3327 I jxcore-log: ok 95 error should be null
03-29 16:23:34.397  3271  3327 I jxcore-log: 
,03-29 16:23:34.404  3271  3327 I jxcore-log: # setup
03-29 16:23:34.404  3271  3327 I jxcore-log: 
,03-29 16:23:34.577  3271  3327 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-29 16:23:34.577  3271  3327 I jxcore-log: 
,03-29 16:23:34.718  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:34.718  3271  3327 I jxcore-log: 
,03-29 16:23:34.720  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 34392
03-29 16:23:34.720  3271  3327 I jxcore-log: 
,03-29 16:23:34.731  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-29 16:23:34.731  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:34.731  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:34.732  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-29 16:23:34.732  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:34.732  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:34.741  3271  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:34.742   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-29 16:23:34.754  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:34.770  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-29 16:23:34.770  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:34.770  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-29 16:23:34.772  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:34.790  2160  2180 D BtGatt.GattService: registerClient() - UUID=3275437d-67ae-4ce5-ab60-a4a7723eb91a,
,03-29 16:23:34.793  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=3275437d-67ae-4ce5-ab60-a4a7723eb91a, clientIf=5
,03-29 16:23:34.796  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:23:34.801  2160  2981 D BtGatt.GattService: start scan with filters
,03-29 16:23:34.807  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 16:23:34.807  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 16:23:34.807  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:34.808  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:34.808  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:23:34.808  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:34.808  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:34.809  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:34.810   823  1421 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:34.813  2160  2233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39b9145c
,03-29 16:23:34.817  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 16:23:34.817  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:34.818  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:34.818  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:34.818  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:34.819  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:34.826  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 16:23:34.826  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:34.829  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 16:23:34.829  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:34.829  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:34.829  3271  3327 I jxcore-log: 
03-29 16:23:34.830  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 16:23:34.830  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:23:34.831  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-29 16:23:34.831  3271  3327 I jxcore-log: 
,03-29 16:23:34.833  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:34.833  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:34.835  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:34.835  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:34.835  3271  3327 I jxcore-log: ok 96 error should be null
03-29 16:23:34.835  3271  3327 I jxcore-log: 
,03-29 16:23:34.837  3271  3327 I jxcore-log: ok 97 error should be null
03-29 16:23:34.837  3271  3327 I jxcore-log: 
,03-29 16:23:34.845  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-29 16:23:34.845  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:34.845  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:34.845  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:34.846  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:34.850  3271  3327 I jxcore-log: ok 98 error should be null
,03-29 16:23:34.850  3271  3327 I jxcore-log: 
03-29 16:23:34.850  3271  3327 I jxcore-log: ok 99 error should be null
03-29 16:23:34.850  3271  3327 I jxcore-log: 
,03-29 16:23:34.857  3271  3327 I jxcore-log: # teardown
,03-29 16:23:34.857  3271  3327 I jxcore-log: 
,03-29 16:23:35.087  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-29 16:23:35.087  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:35.088  3271  3327 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 16:23:35.088  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-29 16:23:35.088  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:35.088  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:23:35.088  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:35.090  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:35.090  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:35.094  2160  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:35.098  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:35.098  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:35.098  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:35.098  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:35.099  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:35.099  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:35.099  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:35.099  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:23:35.100  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:23:35.100  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:35.102  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:35.102  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:35.103  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:35.104  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:35.105  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:35.105  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:35.105  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:23:35.105  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:35.107  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 16:23:35.107  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:35.107  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:35.107  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:35.108  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-29 16:23:35.115  3271  3327 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,03-29 16:23:35.115  3271  3327 I jxcore-log: 
03-29 16:23:35.117  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:35.117   823  1343 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:35.127  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:35.128  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:35.128  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:35.132  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:35.132  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:35.132  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:35.132  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:35.134  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:35.134  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:35.134  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:35.136  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 16:23:35.136  3271  3327 I jxcore-log: 
03-29 16:23:35.137  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:35.137  3271  3327 I jxcore-log: 
,03-29 16:23:35.142  3271  3327 I jxcore-log: ok 100 error should be null
03-29 16:23:35.142  3271  3327 I jxcore-log: 
03-29 16:23:35.143  3271  3327 I jxcore-log: ok 101 error should be null
03-29 16:23:35.143  3271  3327 I jxcore-log: 
,03-29 16:23:35.151  3271  3327 I jxcore-log: # setup,
03-29 16:23:35.151  3271  3327 I jxcore-log: 
,03-29 16:23:35.316  3271  3327 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times,
03-29 16:23:35.316  3271  3327 I jxcore-log: 
,03-29 16:23:35.493  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:35.493  3271  3327 I jxcore-log: 
,03-29 16:23:35.495  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 47926
03-29 16:23:35.495  3271  3327 I jxcore-log: 
,03-29 16:23:35.512  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 47926, start advertisements: true
,03-29 16:23:35.512  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:35.513  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:35.513  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:35.518  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 16:23:35.518  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:35.518  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:35.518  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:35.524  2160  2981 D BtGatt.GattService: registerClient() - UUID=3e44f279-494a-415e-aae0-eb784a3b2ad2,
03-29 16:23:35.525  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=3e44f279-494a-415e-aae0-eb784a3b2ad2, clientIf=5
03-29 16:23:35.525  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:35.526  2160  2982 D BtGatt.GattService: start scan with filters
,03-29 16:23:35.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:35.527  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:35.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:35.527  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:35.527  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:35.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:35.528  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:23:35.528  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:35.528  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:35.529  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-29 16:23:35.532  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:35.532  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:35.534  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-29 16:23:35.534  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:35.534  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:35.535  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:35.535  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:35.535  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 16:23:35.536  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:23:35.539  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:35.539  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:35.542  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-29 16:23:35.543  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:35.545  2160  2179 D BtGatt.GattService: registerClient() - UUID=8bb33d60-82ad-4eae-bf86-30abce5480ca
,03-29 16:23:35.546  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=8bb33d60-82ad-4eae-bf86-30abce5480ca, clientIf=6
,03-29 16:23:35.546  3271  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:23:35.549  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:35.551  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:35.554  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:23:35.557  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-29 16:23:35.559  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:35.559  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:35.559   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:35.563  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:35.563  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:35.563  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:35.564  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:35.565  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:23:35.566  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:35.566  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:35.566  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:35.566  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:35.566  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:35.567  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:35.567  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:35.567  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:23:35.567  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:35.567  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:35.567  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:35.568  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:35.568  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:35.568  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:35.568  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:35.568  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:35.569   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:35.574  3271  3818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:35.576  3271  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:35.587  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:35.587  3271  3327 I jxcore-log: 
,03-29 16:23:35.609  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:35.609  3271  3327 I jxcore-log: 
,03-29 16:23:35.610  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:35.610  3271  3327 I jxcore-log: 
,03-29 16:23:35.612  3271  3327 I jxcore-log: ok 102 error should be null,
03-29 16:23:35.612  3271  3327 I jxcore-log: 
03-29 16:23:35.613  3271  3327 I jxcore-log: ok 103 error should be null
03-29 16:23:35.613  3271  3327 I jxcore-log: 
,03-29 16:23:35.622  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 47926, start advertisements: true,
03-29 16:23:35.622  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:35.622  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:35.622  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:35.622  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:35.633  3271  3327 I jxcore-log: ok 104 error should be null,
03-29 16:23:35.633  3271  3327 I jxcore-log: 
03-29 16:23:35.633  3271  3327 I jxcore-log: ok 105 error should be null
03-29 16:23:35.633  3271  3327 I jxcore-log: 
03-29 16:23:35.640  3271  3327 I jxcore-log: # teardown
03-29 16:23:35.640  3271  3327 I jxcore-log: 
,03-29 16:23:36.047  2160  2160 D BtGatt.ScanManager: awakened up at time 216924,
,03-29 16:23:36.049  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:36.059  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3,
03-29 16:23:36.060  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:36.060  2160  2223 D BtGatt.GattService: current time is 216936941270
,03-29 16:23:36.061  2160  2223 D BtGatt.GattService: Batch record : [116, 121, 15, 101, -55, 78, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 16:23:36.064  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:23:36.068  2160  2223 D BtGatt.GattService: ScanRecord : []
,03-29 16:23:36.068  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 16:23:36.077  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-29 16:23:36.078  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:36.078  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-29 16:23:36.079  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:23:36.088  3271  3327 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-29 16:23:36.088  3271  3327 I jxcore-log: 
,03-29 16:23:36.095  3271  3327 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 16:23:36.095  3271  3327 I jxcore-log: 
,03-29 16:23:36.101  3271  3327 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-29 16:23:36.101  3271  3327 I jxcore-log: 
03-29 16:23:36.105  3271  3327 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 16:23:36.105  3271  3327 I jxcore-log: 
,03-29 16:23:36.593  2160  2225 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 16:23:37.074  2160  2160 D BtGatt.ScanManager: awakened up at time 217951
03-29 16:23:37.075  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:37.083  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 16:23:37.083  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:37.084  2160  2223 D BtGatt.GattService: current time is 217960809759
03-29 16:23:37.084  2160  2223 D BtGatt.GattService: Batch record : [116, 121, 15, 101, -55, 78, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 16:23:37.085  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:23:37.086  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 16:23:37.088  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-29 16:23:37.089  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-29 16:23:37.508  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:37.508  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:23:37.508  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:37.508  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:37.508  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 16:23:37.511  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:37.511  3271  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:37.511  3271  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:37.511  3271  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:37.512  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:23:37.513  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:37.513  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:37.513  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:23:37.513  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:37.513  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:37.513  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:37.513  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:23:37.515  2160  2180 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:23:37.516  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 16:23:37.517  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:37.517  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:37.517  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:37.517  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:37.517  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 16:23:37.517  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:37.518  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-29 16:23:37.518  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:37.518  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:37.519  2160  2233 D BtGatt.ScanManager: stopping BLe Batch,
03-29 16:23:37.520  2160  2232 D BtGatt.AdvertiseManager: message : 1
,03-29 16:23:37.521  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:23:37.522  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 16:23:37.522  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:37.522  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:37.524  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:23:37.524  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:37.526  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:37.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:37.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:37.527  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:37.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 16:23:37.527  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-29 16:23:37.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:37.527  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:37.527  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:37.528  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:37.528  3271  3327 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:37.528  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:37.529  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-29 16:23:37.529  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:37.529  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:37.529  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 16:23:37.529  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:37.529  2160  2223 D BtGatt.GattService: current time is 218406415644
03-29 16:23:37.529  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 116, 121, 15, 101, -55, 78, 1, -128, -71, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:37.530  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:23:37.530  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:37.536  3271  3327 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:37.536  3271  3327 I jxcore-log: 
03-29 16:23:37.541  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:37.541   823  1107 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:37.553  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:23:37.554  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:37.554  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:37.560  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:23:37.560  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:37.560  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:37.560  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:37.560  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:37.560  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:37.562  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:37.562  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:37.562  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:37.565  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:37.565  3271  3327 I jxcore-log: 
,03-29 16:23:37.567  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:37.567  3271  3327 I jxcore-log: 
,03-29 16:23:37.569  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:37.569  3271  3327 I jxcore-log: 
,03-29 16:23:37.584  3271  3327 I jxcore-log: ok 106 error should be null
03-29 16:23:37.584  3271  3327 I jxcore-log: 
,03-29 16:23:37.585  3271  3327 I jxcore-log: ok 107 error should be null
03-29 16:23:37.585  3271  3327 I jxcore-log: 
,03-29 16:23:37.590  3271  3327 I jxcore-log: # setup
03-29 16:23:37.590  3271  3327 I jxcore-log: 
,03-29 16:23:37.733  3271  3327 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-29 16:23:37.733  3271  3327 I jxcore-log: 
,03-29 16:23:37.928  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:37.928  3271  3327 I jxcore-log: 
,03-29 16:23:37.931  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 52506
03-29 16:23:37.931  3271  3327 I jxcore-log: 
,03-29 16:23:37.935  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:37.936  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:37.936  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:37.939  3271  3327 I jxcore-log: ok 108 error should be null
03-29 16:23:37.939  3271  3327 I jxcore-log: 
,03-29 16:23:37.940  3271  3327 I jxcore-log: ok 109 error should be null
03-29 16:23:37.940  3271  3327 I jxcore-log: 
,03-29 16:23:37.942  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:37.943  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:37.943  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:37.946  3271  3327 I jxcore-log: ok 110 error should be null
03-29 16:23:37.946  3271  3327 I jxcore-log: 
,03-29 16:23:37.946  3271  3327 I jxcore-log: ok 111 error should be null
03-29 16:23:37.946  3271  3327 I jxcore-log: 
,03-29 16:23:37.952  3271  3327 I jxcore-log: # teardown
03-29 16:23:37.952  3271  3327 I jxcore-log: 
,03-29 16:23:38.065  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:38.065  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:38.065  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:38.067  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:38.067  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:38.067  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:38.073  3271  3327 I jxcore-log: ok 112 error should be null
03-29 16:23:38.073  3271  3327 I jxcore-log: 
,03-29 16:23:38.074  3271  3327 I jxcore-log: ok 113 error should be null
03-29 16:23:38.074  3271  3327 I jxcore-log: 
,03-29 16:23:38.079  3271  3327 I jxcore-log: # setup
03-29 16:23:38.079  3271  3327 I jxcore-log: 
,03-29 16:23:38.181  3271  3327 I jxcore-log: # 30. #start should fail if called twice in a row
03-29 16:23:38.181  3271  3327 I jxcore-log: 
,03-29 16:23:38.351  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:38.351  3271  3327 I jxcore-log: 
,03-29 16:23:38.353  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 53596
03-29 16:23:38.353  3271  3327 I jxcore-log: 
,03-29 16:23:38.355  3271  3327 I jxcore-log: ok 114 first call should succeed
03-29 16:23:38.355  3271  3327 I jxcore-log: 
,03-29 16:23:38.356  3271  3327 I jxcore-log: ok 115 first call should succeed
03-29 16:23:38.356  3271  3327 I jxcore-log: 
,03-29 16:23:38.359  3271  3327 I jxcore-log: ok 116 specific error should be returned
03-29 16:23:38.359  3271  3327 I jxcore-log: 
03-29 16:23:38.361  3271  3327 I jxcore-log: # teardown
03-29 16:23:38.361  3271  3327 I jxcore-log: 
,03-29 16:23:38.510  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:38.511  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:38.511  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:38.515  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:38.515  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:38.515  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:38.526  3271  3327 I jxcore-log: ok 117 error should be null,
03-29 16:23:38.526  3271  3327 I jxcore-log: 
,03-29 16:23:38.527  3271  3327 I jxcore-log: ok 118 error should be null
03-29 16:23:38.527  3271  3327 I jxcore-log: 
,03-29 16:23:38.532  3271  3327 I jxcore-log: # setup
03-29 16:23:38.532  3271  3327 I jxcore-log: 
,03-29 16:23:38.681  3271  3327 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-29 16:23:38.681  3271  3327 I jxcore-log: 
,03-29 16:23:38.884  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:23:38.884  3271  3327 I jxcore-log: ,
03-29 16:23:38.886  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 48375
03-29 16:23:38.886  3271  3327 I jxcore-log: 
,03-29 16:23:38.898  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 47926, start advertisements: false
,03-29 16:23:38.898  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:38.898  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:38.898  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:23:38.905  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:38.905  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:38.905  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:38.911  2160  2179 D BtGatt.GattService: registerClient() - UUID=d8c90073-f567-4993-8f6f-acb0777ae97d
,03-29 16:23:38.911  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=d8c90073-f567-4993-8f6f-acb0777ae97d, clientIf=5
03-29 16:23:38.912  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:38.912  2160  2981 D BtGatt.GattService: start scan with filters
,03-29 16:23:38.914  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:23:38.914  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:38.914  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:23:38.914  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:38.914  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:38.914  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-29 16:23:38.914  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:38.914  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:38.914   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:38.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:38.919  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:38.920  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:38.920  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:38.921  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:38.921  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:38.921  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:38.921  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:38.923  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 16:23:38.923  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:38.923  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:38.923  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:23:38.926  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:38.926  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:38.927  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:38.928  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:38.929  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:38.929  3271  3327 I jxcore-log: 
,03-29 16:23:38.930  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:38.930  3271  3327 I jxcore-log: 
,03-29 16:23:38.946  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48375, start advertisements: true
,03-29 16:23:38.946  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:38.946  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:38.946  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:38.950  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:38.950  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 16:23:38.950  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:38.950  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:38.950  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-29 16:23:38.950  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:38.950  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:38.950  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:23:38.957  2160  2180 D BtGatt.GattService: registerClient() - UUID=60423762-f094-4a26-a5d3-986b6e475bd9,
03-29 16:23:38.957  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=60423762-f094-4a26-a5d3-986b6e475bd9, clientIf=6
03-29 16:23:38.958  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:38.960  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:38.965  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:38.969  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:23:38.972  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:23:38.973  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:23:38.974  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:38.974  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:38.974  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:38.974  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:38.974  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:38.975  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:38.976   823  1421 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:38.982  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-29 16:23:38.982  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:38.982  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:38.982  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:23:38.983  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:38.984  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:23:38.984  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 16:23:38.984  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:38.985  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:38.985  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:23:38.985  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:38.985  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:38.985  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:38.987   823  1159 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-29 16:23:38.989  3271  3820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:38.993  3271  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:38.998  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-29 16:23:38.998  3271  3327 I jxcore-log: 
,03-29 16:23:39.003  3271  3327 I jxcore-log: ok 119 called only once
,03-29 16:23:39.003  3271  3327 I jxcore-log: 
,03-29 16:23:39.004  3271  3327 I jxcore-log: ok 120 discovery state matches,
03-29 16:23:39.004  3271  3327 I jxcore-log: 
03-29 16:23:39.004  3271  3327 I jxcore-log: ok 121 advertising state matches,
03-29 16:23:39.004  3271  3327 I jxcore-log: 
,03-29 16:23:39.012  3271  3327 I jxcore-log: # teardown
03-29 16:23:39.012  3271  3327 I jxcore-log: ,
,03-29 16:23:39.497  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-29 16:23:39.497  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:39.497  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:39.497  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:39.497  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:39.499  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:23:39.499  3271  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:39.499  3271  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:39.499  3271  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:39.500  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:39.500  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:39.500  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 16:23:39.500  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:39.500  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:39.501  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:39.501  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:39.501  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:23:39.503  2160  2981 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:23:39.505  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:39.505  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:39.505  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 16:23:39.505  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:39.506  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:39.506  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:39.506  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:39.506  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:39.506  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:23:39.506  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:39.506  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:39.508  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:39.509  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:39.509  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:39.509  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:39.510  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:39.513  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:23:39.513  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:39.515  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:39.515  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:39.515  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:39.515  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:39.515  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:39.515  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-29 16:23:39.515  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:39.516  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 16:23:39.516  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:39.516  2160  2223 D BtGatt.GattService: current time is 220392819289
03-29 16:23:39.516  2160  2223 D BtGatt.GattService: Batch record : [92, -55, -80, 74, 71, 70, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-29 16:23:39.516  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:39.516  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:23:39.518  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:39.519  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:39.522  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 16:23:39.522  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:39.522  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:39.522  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:39.523  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:39.530  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:39.530   823  1159 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:39.532  3271  3327 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-29 16:23:39.532  3271  3327 I jxcore-log: 
03-29 16:23:39.533  3271  3327 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:39.533  3271  3327 I jxcore-log: 
,03-29 16:23:39.535  3271  3327 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:39.535  3271  3327 I jxcore-log: 
,03-29 16:23:39.540  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:39.541  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:39.541  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-29 16:23:39.545  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:23:39.546  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:39.546  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:39.546  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:39.546  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:39.547  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:39.547  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 16:23:39.547  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:39.547  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:39.548  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:39.548  3271  3327 I jxcore-log: 
,03-29 16:23:39.549  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:39.549  3271  3327 I jxcore-log: 
,03-29 16:23:39.550  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:39.550  3271  3327 I jxcore-log: 
,03-29 16:23:39.554  3271  3327 I jxcore-log: ok 122 error should be null
03-29 16:23:39.554  3271  3327 I jxcore-log: 
,03-29 16:23:39.554  3271  3327 I jxcore-log: ok 123 error should be null
03-29 16:23:39.554  3271  3327 I jxcore-log: 
,03-29 16:23:39.560  3271  3327 I jxcore-log: # setup
03-29 16:23:39.560  3271  3327 I jxcore-log: 
,03-29 16:23:39.741  3271  3327 I jxcore-log: # 32. does not send duplicate availability changes
03-29 16:23:39.741  3271  3327 I jxcore-log: 
,03-29 16:23:39.857  3271  3327 I jxcore-log: ok 124 should be called once
,03-29 16:23:39.857  3271  3327 I jxcore-log: 
,03-29 16:23:39.860  3271  3327 I jxcore-log: ok 125 should not have been called more than once
03-29 16:23:39.860  3271  3327 I jxcore-log: 
,03-29 16:23:39.862  3271  3327 I jxcore-log: # teardown,
03-29 16:23:39.862  3271  3327 I jxcore-log: 
,03-29 16:23:40.009  3271  3327 I jxcore-log: ok 126 error should be null,
03-29 16:23:40.009  3271  3327 I jxcore-log: 
03-29 16:23:40.011  3271  3327 I jxcore-log: ok 127 error should be null
03-29 16:23:40.011  3271  3327 I jxcore-log: 
,03-29 16:23:40.016  3271  3327 I jxcore-log: # setup
03-29 16:23:40.016  3271  3327 I jxcore-log: 
,03-29 16:23:40.120  3271  3327 I jxcore-log: # 33. can get the network status
03-29 16:23:40.120  3271  3327 I jxcore-log: 
,03-29 16:23:40.245  3271  3327 I jxcore-log: ok 128 network status should have certain non-empty properties
03-29 16:23:40.245  3271  3327 I jxcore-log: 
,03-29 16:23:40.251  3271  3327 I jxcore-log: # teardown
03-29 16:23:40.251  3271  3327 I jxcore-log: 
,03-29 16:23:40.349  3271  3327 I jxcore-log: ok 129 error should be null
03-29 16:23:40.349  3271  3327 I jxcore-log: 
,03-29 16:23:40.350  3271  3327 I jxcore-log: ok 130 error should be null
03-29 16:23:40.350  3271  3327 I jxcore-log: 
,03-29 16:23:40.372  3271  3327 I jxcore-log: # setup
,03-29 16:23:40.372  3271  3327 I jxcore-log: 
,03-29 16:23:40.515  3271  3327 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-29 16:23:40.515  3271  3327 I jxcore-log: 
,03-29 16:23:40.643  3271  3327 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-29 16:23:40.643  3271  3327 I jxcore-log: 
,03-29 16:23:40.669  3271  3327 I jxcore-log: ok 131 host address should match
03-29 16:23:40.669  3271  3327 I jxcore-log: 
03-29 16:23:40.670  3271  3327 I jxcore-log: ok 132 port should match
03-29 16:23:40.670  3271  3327 I jxcore-log: 
,03-29 16:23:42.649  3271  3327 I jxcore-log: ok 133 host address should be null
03-29 16:23:42.649  3271  3327 I jxcore-log: 
03-29 16:23:42.650  3271  3327 I jxcore-log: ok 134 port should should be null
03-29 16:23:42.650  3271  3327 I jxcore-log: 
,03-29 16:23:42.677  3271  3327 I jxcore-log: # teardown
03-29 16:23:42.677  3271  3327 I jxcore-log: 
,03-29 16:23:42.849  3271  3327 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 16:23:42.849  3271  3327 I jxcore-log: 
03-29 16:23:42.851  3271  3327 I jxcore-log: ok 135 error should be null
03-29 16:23:42.851  3271  3327 I jxcore-log: 
03-29 16:23:42.852  3271  3327 I jxcore-log: ok 136 error should be null
03-29 16:23:42.852  3271  3327 I jxcore-log: 
,03-29 16:23:42.856  3271  3327 I jxcore-log: # setup
03-29 16:23:42.856  3271  3327 I jxcore-log: 
,03-29 16:23:42.925  1241  1466 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-29 16:23:42.925  1241  1466 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-29 16:23:42.968  1406  1406 I ConfigService: onCreate
,03-29 16:23:42.972  3271  3327 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements,
,03-29 16:23:42.972  3271  3327 I jxcore-log: 
,03-29 16:23:43.119  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48375, start advertisements: false
03-29 16:23:43.119  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:43.120  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.120  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:23:43.128  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:23:43.128  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:43.128  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:43.135  2160  2981 D BtGatt.GattService: registerClient() - UUID=a7ff9a37-378b-4069-9426-880e0e003796
,03-29 16:23:43.136  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=a7ff9a37-378b-4069-9426-880e0e003796, clientIf=5
03-29 16:23:43.137  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:43.137  2160  2180 D BtGatt.GattService: start scan with filters
,03-29 16:23:43.139  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 16:23:43.139  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:43.140  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:43.140  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:43.140  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 16:23:43.140  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.140  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:43.140  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.141   823  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:43.149  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 16:23:43.149  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.151  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:43.151  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.152  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:43.152  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:23:43.154  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 16:23:43.154  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:43.155  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:43.155  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.157  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:23:43.157  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:43.159  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.159  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:43.160  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:43.160  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:43.165  3271  3327 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-29 16:23:43.165  3271  3327 I jxcore-log: 
,03-29 16:23:43.166  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:43.166  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:43.166  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:43.166  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:43.168  2160  2982 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:43.170  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:43.170  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:43.170  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.170  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:43.171  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:43.171  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:43.171  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:43.171  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:23:43.171  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:23:43.171  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:43.171  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:43.172  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:43.172  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:43.173  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.173  3271  3327 I jxcore-log: 
,03-29 16:23:43.174  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:43.174  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:43.174  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:43.175  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.175  3271  3327 I jxcore-log: 
,03-29 16:23:43.175  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:23:43.175  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.183  3271  3327 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-29 16:23:43.183  3271  3327 I jxcore-log: 
,03-29 16:23:43.195  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:43.195  3271  3327 I jxcore-log: 
,03-29 16:23:43.197  3271  3327 I jxcore-log: # teardown
03-29 16:23:43.197  3271  3327 I jxcore-log: 
,03-29 16:23:43.428  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:43.428  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:23:43.429  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:43.435  3271  3327 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:43.435  3271  3327 I jxcore-log: 
03-29 16:23:43.435  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:43.435  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:43.435  3271  3327 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 16:23:43.435  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:43.435  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:43.435  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:43.435  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:23:43.436  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:43.437  3271  3327 D BluetoothLeScanner: could not find callback wrapper
03-29 16:23:43.437  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:43.438  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:23:43.438  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:43.438  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:43.439  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:43.439  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:43.440  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:43.440  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:43.440  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:43.450  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:43.451   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:43.462  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:43.464  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:43.465  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:43.471  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:43.471  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:43.471  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:43.474  3271  3327 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:43.474  3271  3327 I jxcore-log: 
,03-29 16:23:43.489  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:43.489  3271  3327 I jxcore-log: 
,03-29 16:23:43.493  3271  3327 I jxcore-log: # setup
03-29 16:23:43.493  3271  3327 I jxcore-log: 
,03-29 16:23:43.661  3271  3327 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-29 16:23:43.661  3271  3327 I jxcore-log: 
,03-29 16:23:43.875  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48375, start advertisements: false
03-29 16:23:43.875  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:43.876  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.876  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:23:43.884  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:43.884  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:43.885  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:43.894  2160  2179 D BtGatt.GattService: registerClient() - UUID=d7d15df5-8d73-464c-ac43-479f4b1ec8b2
,03-29 16:23:43.895  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=d7d15df5-8d73-464c-ac43-479f4b1ec8b2, clientIf=5
03-29 16:23:43.896  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:43.897  2160  2180 D BtGatt.GattService: start scan with filters
,03-29 16:23:43.898  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:43.899  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:43.899  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:43.899  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:43.899  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:43.899  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.900  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:43.900  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:43.901   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:43.904  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-29 16:23:43.904  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.907  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:43.907  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:43.908  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:43.908  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:23:43.913  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
,03-29 16:23:43.913  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:43.913  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:43.913  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:43.913  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:43.914  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.914  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:43.914  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:43.917  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:43.917  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:43.920  3271  3327 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-29 16:23:43.920  3271  3327 I jxcore-log: 
,03-29 16:23:43.929  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48375, start advertisements: false
,03-29 16:23:43.929  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:43.929  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:23:43.929  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:43.930  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:43.933  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.933  3271  3327 I jxcore-log: 
,03-29 16:23:43.936  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:43.936  3271  3327 I jxcore-log: 
,03-29 16:23:43.941  3271  3327 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-29 16:23:43.941  3271  3327 I jxcore-log: 
,03-29 16:23:43.956  3271  3327 I jxcore-log: # teardown
03-29 16:23:43.956  3271  3327 I jxcore-log: 
,03-29 16:23:44.144  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:44.144  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:44.144  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:44.144  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:23:44.148  2160  2180 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 16:23:44.152  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:44.156  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-29 16:23:44.156  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 16:23:44.156  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:44.156  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:23:44.157  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:23:44.157  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.159  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.161  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:44.161  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:44.165  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:44.165  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:44.165  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:44.166  3271  3327 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:44.166  3271  3327 I jxcore-log: ,
03-29 16:23:44.167  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:44.167  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.167  3271  3327 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
03-29 16:23:44.167  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:44.167  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:44.167  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:23:44.167  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:44.169  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:44.169  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:44.169  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:44.169  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:44.170  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:23:44.171  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:44.171  3271  3327 D BluetoothLeScanner: could not find callback wrapper
,03-29 16:23:44.171  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:44.173  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:44.173  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:44.173  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:44.173  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:44.173  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:44.173  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:44.173  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:44.173  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:44.176  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.176  3271  3327 I jxcore-log: 
,03-29 16:23:44.181  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:44.181   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:44.188  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:44.188  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:44.189  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:44.194  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:44.194  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.194  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:44.195  3271  3327 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
,03-29 16:23:44.195  3271  3327 I jxcore-log: 
,03-29 16:23:44.201  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.201  3271  3327 I jxcore-log: 
,03-29 16:23:44.202  3271  3327 I jxcore-log: # setup
03-29 16:23:44.202  3271  3327 I jxcore-log: 
,03-29 16:23:44.345  3271  3327 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-29 16:23:44.345  3271  3327 I jxcore-log: 
,03-29 16:23:44.515  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-29 16:23:44.515  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:44.515  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:44.515  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:44.520  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 16:23:44.520  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:44.520  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:44.520  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:44.525  2160  2982 D BtGatt.GattService: registerClient() - UUID=bae690a2-b5e5-4760-9a85-4d9b65631758
,03-29 16:23:44.526  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=bae690a2-b5e5-4760-9a85-4d9b65631758, clientIf=5
,03-29 16:23:44.527  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:23:44.529  2160  2180 D BtGatt.GattService: start scan with filters
,03-29 16:23:44.530  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:44.530  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:23:44.531  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:44.531  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:44.531  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:44.531  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:44.531  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:44.531  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:44.531  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:44.532  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:23:44.532  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:44.533  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:44.533  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:44.533  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:44.533  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:44.536  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:44.536  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:44.536  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 16:23:44.537  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:23:44.539  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-29 16:23:44.539  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:44.541  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:23:44.541  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:44.544  2160  2180 D BtGatt.GattService: registerClient() - UUID=60e462d2-e021-411d-b74d-2feee6fddbab
,03-29 16:23:44.544  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=60e462d2-e021-411d-b74d-2feee6fddbab, clientIf=6
03-29 16:23:44.545  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:44.548  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:44.553  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:44.558  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:23:44.561  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-29 16:23:44.562  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:44.562  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:23:44.563   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:44.571  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:44.571  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:44.571  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:44.571  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:44.573  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:23:44.575  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:44.575  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 16:23:44.576  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 16:23:44.577  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:44.577  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:44.578   823  1343 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:44.578  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:44.578  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:44.578  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:44.579  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:23:44.579  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:44.579  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:23:44.580  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:44.580  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:44.580  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:44.580  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:44.580  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:23:44.581  3271  3823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:44.585  3271  3823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:44.586  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:44.586  3271  3327 I jxcore-log: 
,03-29 16:23:44.589  3271  3327 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-29 16:23:44.589  3271  3327 I jxcore-log: 
,03-29 16:23:44.590  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:44.590  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 16:23:44.591  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:44.591  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:44.591  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:44.591  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:44.591  3271  3823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:44.591  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:23:44.591  3271  3823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:44.591  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:44.591  3271  3823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 16:23:44.591  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:44.592  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:44.592  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:44.592  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:44.592  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-29 16:23:44.592  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:23:44.594  2160  2982 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:23:44.595  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:44.596  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:44.596  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:44.596  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:44.596  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:44.597  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:44.597  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:44.597  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-29 16:23:44.597  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 16:23:44.598  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:44.598  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:44.599  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 16:23:44.599  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:44.600  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:44.601  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:44.602  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:44.602  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-29 16:23:44.602  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:44.602  2160  2223 D BtGatt.GattService: current time is 225479414548
,03-29 16:23:44.602  2160  2223 D BtGatt.GattService: Batch record : [-29, 99, 122, -22, -23, 89, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:44.603  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:44.605  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:23:44.605  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:44.607  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:44.607  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:23:44.608  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:44.608  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 16:23:44.608  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:44.608  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:44.608  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.608  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:44.609  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:44.609  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:44.609  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:44.610  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:44.610  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:44.610  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:44.614  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:44.614  3271  3327 I jxcore-log: 
03-29 16:23:44.616  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:44.616  3271  3327 I jxcore-log: 
,03-29 16:23:44.617  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:44.617   823  1159 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:44.623  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:44.624  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:44.624  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:44.628  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:23:44.628  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:44.628  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:44.628  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:44.628  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:44.628  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:44.629  3271  3327 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-29 16:23:44.629  3271  3327 I jxcore-log: 
,03-29 16:23:44.638  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-29 16:23:44.638  3271  3327 I jxcore-log: 
03-29 16:23:44.639  3271  3327 I jxcore-log: # teardown
03-29 16:23:44.639  3271  3327 I jxcore-log: 
03-29 16:23:44.640  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.640  3271  3327 I jxcore-log: 
,03-29 16:23:44.640  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:44.640  3271  3327 I jxcore-log: 
,03-29 16:23:45.114  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:45.114  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:23:45.114  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:45.119  3271  3327 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
,03-29 16:23:45.119  3271  3327 I jxcore-log: 
03-29 16:23:45.119  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:45.120  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:45.120  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:45.123  3271  3327 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:45.123  3271  3327 I jxcore-log: ,
,03-29 16:23:45.137  3271  3327 I jxcore-log: # setup
,03-29 16:23:45.137  3271  3327 I jxcore-log: 
,03-29 16:23:45.235  3271  3327 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-29 16:23:45.235  3271  3327 I jxcore-log: 
,03-29 16:23:45.832  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-29 16:23:45.832  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:45.832  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:45.832  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:45.841  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:45.841  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:45.841  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:45.842  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:45.857  2160  2179 D BtGatt.GattService: registerClient() - UUID=3de9e717-e45b-46c5-b7f2-4d54f0633a5b,
,03-29 16:23:45.858  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=3de9e717-e45b-46c5-b7f2-4d54f0633a5b, clientIf=5,
03-29 16:23:45.858  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:23:45.859  2160  2180 D BtGatt.GattService: start scan with filters
03-29 16:23:45.861  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:45.861  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:45.861  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-29 16:23:45.862  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 16:23:45.862  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:45.862  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:45.864  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:45.864  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:23:45.865  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-29 16:23:45.865  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:23:45.865  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:45.865  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:45.866  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:45.870  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:45.870  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:45.873  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:45.873  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:45.873  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:45.873  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:23:45.876  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-29 16:23:45.877  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 16:23:45.879  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:45.879  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:45.886  2160  2180 D BtGatt.GattService: registerClient() - UUID=a8652c96-9596-43c5-a427-b7d10059b153
,03-29 16:23:45.887  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=a8652c96-9596-43c5-a427-b7d10059b153, clientIf=6,
03-29 16:23:45.887  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:23:45.888  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:45.892  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising,
,03-29 16:23:45.896  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 16:23:45.899  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-29 16:23:45.900  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:45.900  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:45.900   823  1159 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:45.902  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:45.902  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:45.902  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:45.902  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:45.903  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:23:45.904  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:45.904  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:45.904  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:45.904  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:45.904  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:23:45.904  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:45.904  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:45.904  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:23:45.905  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:45.905  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:45.905  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:45.905  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:23:45.905  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:45.905  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:45.905  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:45.905  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:45.907  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:45.907  3271  3327 I jxcore-log: 
03-29 16:23:45.908  3271  3327 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-29 16:23:45.908  3271  3327 I jxcore-log: 
,03-29 16:23:45.911  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-29 16:23:45.911  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:45.911  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:45.912   823  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:45.912  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:23:45.913  3271  3824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:45.913  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:45.916  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:45.916  3271  3327 I jxcore-log: 
,03-29 16:23:45.917  3271  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 16:23:45.917  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:45.917  3271  3327 I jxcore-log: 
,03-29 16:23:45.919  3271  3327 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-29 16:23:45.919  3271  3327 I jxcore-log: 
,03-29 16:23:45.924  3271  3327 I jxcore-log: # teardown
03-29 16:23:45.924  3271  3327 I jxcore-log: 
,03-29 16:23:46.885  2160  2160 D BtGatt.ScanManager: awakened up at time 227762
,03-29 16:23:46.887  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:46.895  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 16:23:46.895  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:46.895  2160  2223 D BtGatt.GattService: current time is 227772432724
03-29 16:23:46.896  2160  2223 D BtGatt.GattService: Batch record : [117, 97, 39, -43, 54, 110, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-29 16:23:46.896  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-29 16:23:46.897  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:23:46.899  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-29 16:23:46.899  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:46.899  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-29 16:23:46.899  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 16:23:46.902  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 16:23:46.902  3271  3327 I jxcore-log: 
,03-29 16:23:46.905  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 16:23:46.905  3271  3327 I jxcore-log: 
,03-29 16:23:47.180  3484  3826 V KeepSync: Connecting to GoogleApiClient
,03-29 16:23:47.252  1406  1436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 16:23:47.252  1406  1436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:47.252  1406  1436 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:47.252  1406  1436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:47.256  1406  1436 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:47.268  3095  3827 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
03-29 16:23:47.268  3095  3827 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jdm.a(PG:82)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jcs.o(PG:406)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jcn.a(PG:1379)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jcs.i(PG:143)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at blb.a(PG:3937)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at czp.a(PG:18188)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at czp.a(PG:9081)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at czq.run(PG:1686)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818),
03-29 16:23:47.268  3095  3827 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jdj.a(PG:4091)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jdj.a(PG:1125)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jdm.a(PG:77)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	... 12 more
03-29 16:23:47.268  3095  3827 E HttpOperation: Caused by: faj: BadAuthentication
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at fal.a(PG:38)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	at jdj.a(PG:4089)
03-29 16:23:47.268  3095  3827 E HttpOperation: 	... 14 more
03-29 16:23:47.268  1406  3420 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 16:23:47.268  1406  3420 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:47.269  1406  3420 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 16:23:47.269  1406  3420 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:47.274  1406  3420 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: Handling authorization failure
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 16:23:47.298  1780  3829 E ClientConnectionOperation: 	... 7 more
,03-29 16:23:47.304  3484  3826 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 16:23:47.307  3484  3826 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 16:23:47.308  1406  1726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-29 16:23:47.308  1406  1726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-29 16:23:47.308  1406  1726 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 16:23:47.308  1406  1726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:47.313  1406  1726 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:47.319  3484  3826 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 16:23:47.320  3484  3826 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 16:23:47.327  3095  3827 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 16:23:47.327  3095  3827 E HttpOperation: java.io.IOException: Cannot obtain authentication token
,03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jdm.a(PG:82)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jcs.o(PG:406)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jcn.a(PG:1379)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jcs.i(PG:143)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at hec.a(PG:42)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at hee.a(PG:102)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at czr.a(PG:65)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	,at kka.a(PG:108)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at czp.a(PG:19176)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at czp.a(PG:9081)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at czq.run(PG:1686)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:23:47.327  3095  3827 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
,03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jdj.a(PG:4091)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jdj.a(PG:1125)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jdm.a(PG:77)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	... 15 more
03-29 16:23:47.327  3095  3827 E HttpOperation: Caused by: faj: BadAuthentication
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at fal.a(PG:38)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	at jdj.a(PG:4089)
03-29 16:23:47.327  3095  3827 E HttpOperation: 	,... 17 more
03-29 16:23:47.329  3095  3827 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 16:23:47.329  3095  3827 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jcs.i(PG:143)
,03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at hec.a(PG:42)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at hee.a(PG:102)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at czr.a(PG:65)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at kka.a(PG:108)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at czp.a(PG:9081)
,03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jdj.a(PG:4091)
,03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jdj.a(PG:1125)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	... 15 more
03-29 16:23:47.329  3095  3827 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at fal.a(PG:38)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 16:23:47.329  3095  3827 E ExperimentLoader: 	... 17 more
,03-29 16:23:47.374  1406  1432 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-29 16:23:47.375  1406  1432 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:47.375  1406  1432 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 16:23:47.375  1406  1432 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:47.379  1406  1432 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:47.427  3484  3826 E KeepSync: IOException
03-29 16:23:47.427  3484  3826 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 16:23:47.427  3484  3826 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 16:23:47.427  3484  3826 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 16:23:47.427  3484  3826 E KeepSync: 	... 10 more
03-29 16:23:47.427  3484  3826 W KeepSync: Sync result 2
,03-29 16:23:47.429   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 199688, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-29 16:23:47.454   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201384, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 16:23:47.466  3511  3832 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 16:23:47.486  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:47.486  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 16:23:47.486  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:47.486  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:23:47.488  2160  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:47.489  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 16:23:47.489  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:47.489  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:47.489  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:23:47.489  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:23:47.489  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:23:47.489  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:47.489  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:47.490  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:47.490  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:47.490  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:47.490  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:47.490  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:47.492  3271  3327 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:47.492  3271  3327 I jxcore-log: 
,03-29 16:23:47.494  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:47.494  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 16:23:47.494  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:47.494  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:47.494  3511  3834 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
03-29 16:23:47.494  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:47.494  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:47.494  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:47.494  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:47.496  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:47.496  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-29 16:23:47.496  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:47.497  2160  2223 D BtGatt.GattService: current time is 228373582619
03-29 16:23:47.497  3271  3824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:47.497  3271  3824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:47.497  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 117, 97, 39, -43, 54, 110, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -103, 2, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 16, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-29 16:23:47.497  3271  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:47.497  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:23:47.497  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:47.497  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:47.497  2160  2223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
03-29 16:23:47.497  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:47.497  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:47.497  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:47.497  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:47.497  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:47.497  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:23:47.499  3271  3327 D BluetoothLeScanner: could not find callback wrapper
03-29 16:23:47.499  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:47.499  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:23:47.500  2160  2232 D BtGatt.AdvertiseManager: message : 1
,03-29 16:23:47.501  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:47.502  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:23:47.502  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:47.504  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:47.504  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:23:47.504  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:47.504  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 16:23:47.504  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 16:23:47.504  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-29 16:23:47.504  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:47.504  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:47.504  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:23:47.505  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 16:23:47.505  3271  3327 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:47.505  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:47.505  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:47.506  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:47.506  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:47.506  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:47.506  3271  3327 I jxcore-log: 
,03-29 16:23:47.510  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:47.511   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:47.515  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:47.515  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:47.515  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:23:47.515  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:47.515  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:47.516  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:47.517  3271  3327 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:47.517  3271  3327 I jxcore-log: 
,03-29 16:23:47.520  3271  3327 I jxcore-log: # setup
03-29 16:23:47.520  3271  3327 I jxcore-log: 
,03-29 16:23:47.523  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:23:47.523  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:47.524  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:47.524  3271  3327 I jxcore-log: 
,03-29 16:23:47.524  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:47.524  3271  3327 I jxcore-log: 
,03-29 16:23:47.545  1406  1726 I art     : Explicit concurrent mark sweep GC freed 38853(2MB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.131ms total 50.744ms
,03-29 16:23:47.557  1406  2559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 16:23:47.557  1406  2559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:47.557  1406  2559 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:47.557  1406  2559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:47.560  1406  2559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:47.610  1406  1436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 16:23:47.610  1406  1436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 16:23:47.610  1406  1436 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 16:23:47.610  1406  1436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 16:23:47.613  1406  1436 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:23:47.622  3511  3834 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 16:23:47.623  3511  3832 E BooksSync: Soft error
03-29 16:23:47.623  3511  3832 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 16:23:47.623  3511  3832 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 16:23:47.623  3511  3832 E BooksSync: Sync error
03-29 16:23:47.623  3511  3832 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 16:23:47.623  3511  3832 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 16:23:47.623  3511  3832 I BooksSync: Finished books sync
,03-29 16:23:47.628   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202531, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 16:23:48.056  1406  1406 I ConfigService: onDestroy
,03-29 16:23:48.077  3271  3327 I jxcore-log: # 39. peerAvailabilityChange is called,
03-29 16:23:48.077  3271  3327 I jxcore-log: 
,03-29 16:23:48.217  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-29 16:23:48.217  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:48.217  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:48.217  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-29 16:23:48.223  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:48.223  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:48.223  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:23:48.223  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:48.229  2160  2981 D BtGatt.GattService: registerClient() - UUID=b65c172d-6467-4fae-b19a-d8a6dae02966
,03-29 16:23:48.230  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=b65c172d-6467-4fae-b19a-d8a6dae02966, clientIf=5
03-29 16:23:48.230  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:48.231  2160  2982 D BtGatt.GattService: start scan with filters
,03-29 16:23:48.232  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:23:48.232  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:48.232  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:48.232  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:48.232  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:48.233  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:48.233  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:48.233  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:48.233  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:23:48.233  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:48.233  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:48.233  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:48.233  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:23:48.244  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:48.244  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:48.246  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 16:23:48.246  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:48.247  2160  2982 D BtGatt.GattService: registerClient() - UUID=efc673ea-9271-4b33-9fbe-bddc93f23b52
03-29 16:23:48.247  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:48.248  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=efc673ea-9271-4b33-9fbe-bddc93f23b52, clientIf=6
03-29 16:23:48.248  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:48.248  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:23:48.249  2160  2232 D BtGatt.AdvertiseManager: message : 0
03-29 16:23:48.251  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:48.251  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:48.254  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:23:48.254  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:48.257  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:48.261  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:23:48.264  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:23:48.265  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:48.265  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:48.266   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:48.269  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:48.270  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:23:48.270  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:23:48.270  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:23:48.271  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:23:48.271  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:48.271  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:48.271  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:23:48.272  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:48.272  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:48.272  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:48.272  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:48.272  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:23:48.273  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:48.273  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:23:48.273  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:23:48.273  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:48.274  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:23:48.274  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:48.274  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:23:48.274  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:48.276   823  1419 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:48.279  3271  3836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:48.280  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:48.280  3271  3327 I jxcore-log: 
,03-29 16:23:48.285  3271  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-29 16:23:48.291  3271  3327 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error,
03-29 16:23:48.291  3271  3327 I jxcore-log: 
,03-29 16:23:48.298  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
,03-29 16:23:48.298  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:48.298  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-29 16:23:48.298  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:48.298  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:48.300  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:48.300  3271  3327 I jxcore-log: 
03-29 16:23:48.306  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:48.306  3271  3327 I jxcore-log: 
03-29 16:23:48.307  3271  3327 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-29 16:23:48.307  3271  3327 I jxcore-log: 
,03-29 16:23:49.262  2160  2160 D BtGatt.ScanManager: awakened up at time 230139
,03-29 16:23:49.264  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:49.273  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 16:23:49.273  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:49.273  2160  2223 D BtGatt.GattService: current time is 230149908660
,03-29 16:23:49.273  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -67, -13, -48, -10, 91, 116, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:49.273  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:23:49.273  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:49.275  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-29 16:23:49.276  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:49.276  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-29 16:23:49.277  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:23:49.278  3271  3327 I jxcore-log: ok 155 peers must be an array
03-29 16:23:49.278  3271  3327 I jxcore-log: 
03-29 16:23:49.279  3271  3327 I jxcore-log: ok 156 peers must not be zero-length
03-29 16:23:49.279  3271  3327 I jxcore-log: 
,03-29 16:23:49.290  3271  3327 I jxcore-log: ok 157 peer must have peerIdentifier
03-29 16:23:49.290  3271  3327 I jxcore-log: 
,03-29 16:23:49.290  3271  3327 I jxcore-log: ok 158 peerIdentifier must be a string
03-29 16:23:49.290  3271  3327 I jxcore-log: 
03-29 16:23:49.291  3271  3327 I jxcore-log: ok 159 peer must have peerAvailable
03-29 16:23:49.291  3271  3327 I jxcore-log: 
03-29 16:23:49.291  3271  3327 I jxcore-log: ok 160 peer must have pleaseConnect
03-29 16:23:49.291  3271  3327 I jxcore-log: 
,03-29 16:23:49.298  3271  3327 I jxcore-log: # teardown
03-29 16:23:49.298  3271  3327 I jxcore-log: 
,03-29 16:23:49.996  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:23:49.996  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:49.996  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:49.997  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-29 16:23:50.002  2160  2179 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 16:23:50.005  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-29 16:23:50.006  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:50.007  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:50.007  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:50.006  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:23:50.008  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:50.008  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:50.008  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 16:23:50.008  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 16:23:50.009  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:50.009  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:50.010  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:50.011  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:50.011  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:23:50.011  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:50.011  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:50.013  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 16:23:50.013  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:50.013  2160  2223 D BtGatt.GattService: current time is 230890513764
,03-29 16:23:50.014  2160  2223 D BtGatt.GattService: Batch record : [-67, -13, -48, -10, 91, 116, 1, -128, -78, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 16:23:50.014  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:23:50.015  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 16:23:50.019  3271  3327 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:50.019  3271  3327 I jxcore-log: 
03-29 16:23:50.021  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:23:50.021  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 16:23:50.021  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:23:50.021  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:50.022  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:50.023  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:50.023  3271  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:50.023  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:50.023  3271  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-29 16:23:50.023  3271  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:50.024  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:23:50.024  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:50.024  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:50.024  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:50.024  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:50.024  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:50.025  3271  3327 D BluetoothLeScanner: could not find callback wrapper
03-29 16:23:50.025  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:50.025  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:50.028  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:50.028  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:50.031  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:23:50.032  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:50.033  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:50.034  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:50.035  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:50.035  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:50.035  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:50.035  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:50.035  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:50.035  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:50.036  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:50.037  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:50.037  3271  3327 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:50.037  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:23:50.037  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:50.037  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:50.037  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:23:50.044  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:50.044  3271  3327 I jxcore-log: 
,03-29 16:23:50.047  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:23:50.048   823  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:50.058  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:50.058  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:50.058  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:50.062  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-29 16:23:50.062  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:23:50.062  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:23:50.062  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:50.063  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-29 16:23:50.064  3271  3327 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
,03-29 16:23:50.064  3271  3327 I jxcore-log: 
,03-29 16:23:50.070  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 16:23:50.070  3271  3327 I jxcore-log: 
,03-29 16:23:50.074  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 16:23:50.074  3271  3327 I jxcore-log: 
03-29 16:23:50.076  3271  3327 I jxcore-log: # setup
03-29 16:23:50.076  3271  3327 I jxcore-log: 
,03-29 16:23:50.942  3271  3327 I jxcore-log: # 40. Can connect to a remote peer
03-29 16:23:50.942  3271  3327 I jxcore-log: 
,03-29 16:23:51.049  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 38287, start advertisements: true
,03-29 16:23:51.049  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:23:51.049  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:51.049  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:23:51.055  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:23:51.055  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:51.055  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:51.055  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:23:51.061  2160  2180 D BtGatt.GattService: registerClient() - UUID=0857e5f7-4b31-42c6-811c-c889c8d45506
,03-29 16:23:51.062  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=0857e5f7-4b31-42c6-811c-c889c8d45506, clientIf=5
03-29 16:23:51.063  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:51.063  2160  2179 D BtGatt.GattService: start scan with filters
,03-29 16:23:51.065  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:51.065  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:51.065  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:23:51.065  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:23:51.065  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:23:51.065  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:51.065  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:51.065  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:23:51.066  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:23:51.066  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:23:51.066  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:51.066  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:51.066  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:51.072  2160  2179 D BtGatt.GattService: registerClient() - UUID=c389a5a2-15e8-44a6-848e-e91b3df6623a
,03-29 16:23:51.075  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=c389a5a2-15e8-44a6-848e-e91b3df6623a, clientIf=6
03-29 16:23:51.076  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:51.076  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:51.076  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 16:23:51.077  2160  2232 D BtGatt.AdvertiseManager: message : 0
03-29 16:23:51.078  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:51.078  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:51.079  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 16:23:51.079  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:23:51.082  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:51.082  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:51.084  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:23:51.084  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:51.086  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:51.090  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 16:23:51.094  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:23:51.095  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:23:51.095  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 16:23:51.095   823  1419 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:51.100  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:23:51.100  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:23:51.100  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 16:23:51.100  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:51.101  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:23:51.101  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:23:51.101  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:23:51.102  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 16:23:51.102  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:23:51.103   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:51.102  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:23:51.103  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:51.103  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:51.103  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:23:51.103  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:23:51.103  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 16:23:51.103  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:51.104  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:23:51.104  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:23:51.104  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:51.104  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 16:23:51.104  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:23:51.105  3271  3837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:51.107  3271  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:51.112  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 16:23:51.112  3271  3327 I jxcore-log: 
03-29 16:23:51.114  3271  3327 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-29 16:23:51.114  3271  3327 I jxcore-log: 
,03-29 16:23:51.119  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 38287, start advertisements: false,
03-29 16:23:51.119  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:23:51.119  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 16:23:51.119  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:23:51.119  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:23:51.121  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:23:51.121  3271  3327 I jxcore-log: 
,03-29 16:23:51.124  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:23:51.124  3271  3327 I jxcore-log: 
,03-29 16:23:51.125  3271  3327 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-29 16:23:51.125  3271  3327 I jxcore-log: 
,03-29 16:23:52.091  2160  2160 D BtGatt.ScanManager: awakened up at time 232968
,03-29 16:23:52.094  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:52.102  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 16:23:52.102  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:52.102  2160  2223 D BtGatt.GattService: current time is 232979382357
03-29 16:23:52.102  2160  2223 D BtGatt.GattService: Batch record : [4, -43, 6, -91, 34, 116, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 16:23:52.103  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:52.103  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 16:23:52.105  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-29 16:23:52.105  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:23:52.106  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-29 16:23:52.106  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 16:23:52.109  3271  3327 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-29 16:23:52.109  3271  3327 I jxcore-log: 
,03-29 16:23:52.117  3271  3327 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-29 16:23:52.117  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:23:52.120  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0,
,03-29 16:23:52.121  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-29 16:23:52.121  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-29 16:23:52.121  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-29 16:23:52.121  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-29 16:23:52.121  3271  3327 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-29 16:23:52.123  3271  3327 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-29 16:23:52.123  3271  3327 I jxcore-log: 
03-29 16:23:52.124  3271  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 351)
03-29 16:23:52.124  3271  3839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:52.127  2160  2180 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 16:23:53.852  2160  2234 W bt-btif : info:x10
03-29 16:23:53.852  2160  2223 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-29 16:23:53.853  2160  2223 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 16:23:54.979  2160  2234 W bt-sdp  : process_service_search_attr_rsp
,03-29 16:23:55.306  2160  2223 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-29 16:23:55.314  2160  2223 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-29 16:23:55.315  2160  2223 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-29 16:23:55.317  2160  2224 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-29 16:23:55.318  2160  2224 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 16:23:55.366   823   854 I ActivityManager: Start proc 3840:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-29 16:23:55.444   823   858 D BluetoothManagerService: Message: 20
03-29 16:23:55.444   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c9af803:true
,03-29 16:23:55.449   823  1379 I ActivityManager: Killing 3457:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-29 16:23:55.458  2160  2223 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0,
,03-29 16:23:55.459  2160  2224 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-29 16:23:55.615  2160  2234 W bt-btif : info:x10,
03-29 16:23:55.616  2160  2223 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-29 16:23:55.617  2160  2223 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 16:23:55.672  2160  2224 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-29 16:23:55.705  2160  2224 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 16:23:55.905  2160  2223 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,03-29 16:23:55.912  2160  2223 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-29 16:23:55.913  2160  2223 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-29 16:23:55.918  2160  2224 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-29 16:23:55.918  2160  2224 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 16:23:56.146  2160  2223 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-29 16:23:56.147  2160  2224 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-29 16:23:56.151  2160  2224 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-29 16:23:56.175  2160  2224 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 16:23:56.639  2160  2234 W bt-btif : new conn_srvc id:26, app_id:255
03-29 16:23:56.640  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:23:56.640  2160  2234 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:23:56.641  3271  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-29 16:23:56.645  3271  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 352)
,03-29 16:23:56.646  3271  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:56.647  3271  3860 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 352)
,03-29 16:23:56.648   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:56.652  3271  3837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:23:56.657  3271  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:56.926  3271  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 352)
,03-29 16:23:56.930  3271  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51],
03-29 16:23:56.930  3271  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 352)
,03-29 16:23:56.931  3271  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 352
,03-29 16:23:56.931  3271  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 352)
03-29 16:23:56.931  3271  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-29 16:23:56.932  3271  3860 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 352)
03-29 16:23:56.933  3271  3271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 16:23:56.934  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-29 16:23:56.934  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:23:56.936  3271  3271 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 16:23:56.937  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-29 16:23:56.938  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:23:56.938  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-29 16:23:56.938  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:23:56.938  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:23:56.938  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:23:56.938  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:23:56.944  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:56.945  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:56.949  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:23:56.950  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:56.952  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:56.954  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:56.954  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:56.954  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:23:56.954  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:56.955  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:56.955  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-29 16:23:56.955  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:56.956  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:56.956  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:23:56.966  2160  2179 D BtGatt.GattService: registerClient() - UUID=9372fff7-0469-42b2-a0fe-41d2a392a7f0
03-29 16:23:56.967  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=9372fff7-0469-42b2-a0fe-41d2a392a7f0, clientIf=6
,03-29 16:23:56.968  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:23:56.969  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:56.974  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:56.977  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 16:23:56.979  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:23:56.980  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:56.984  2160  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:56.985  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 16:23:56.986  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:56.986  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:56.986  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:56.987  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:56.987  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-29 16:23:56.987  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:56.987  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:56.987  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:56.987  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:56.989  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:56.989  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:56.990  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:23:56.991  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:23:56.991  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:56.993  2160  2179 D BtGatt.GattService: registerClient() - UUID=04593c78-1053-4c0c-89a5-46091eee7a87
,03-29 16:23:56.993  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=04593c78-1053-4c0c-89a5-46091eee7a87, clientIf=5
03-29 16:23:56.994  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:56.994  2160  2982 D BtGatt.GattService: start scan with filters
,03-29 16:23:56.995  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:23:56.995  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 16:23:56.998  2160  2232 D BtGatt.AdvertiseManager: message : 1
,03-29 16:23:56.998  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:57.001  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:23:57.001  2160  2223 D BtGatt.GattService: Client app is not null!
,03-29 16:23:57.004  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:23:57.005  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:23:57.005  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-29 16:23:57.006  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:23:57.006  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:57.006  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:57.006  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:23:57.006  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:57.007  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:57.007  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:57.007  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:23:57.009  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:57.009  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.010  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:57.010  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.010  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:57.010  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:23:57.012  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:57.012  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.012  2160  2982 D BtGatt.GattService: registerClient() - UUID=9e3f30f0-6c39-4d2b-9444-8a9d0e2fecf3
03-29 16:23:57.013  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=9e3f30f0-6c39-4d2b-9444-8a9d0e2fecf3, clientIf=6
03-29 16:23:57.013  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:23:57.013  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:57.013  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 16:23:57.015  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:57.018  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:57.020  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:23:57.023  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:23:57.023  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:57.025  2160  2981 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:57.026  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 16:23:57.026  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 16:23:57.026  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.027  2160  2233 D BtGatt.ScanManager: stopping BLe Batch,
03-29 16:23:57.027  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:57.027  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:57.027  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:57.027  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:57.027  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:57.027  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.029  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:57.030  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.030  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:57.031  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:23:57.031  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.032  2160  2179 D BtGatt.GattService: registerClient() - UUID=a638717d-7f44-4853-98d2-510ca488fa1f
03-29 16:23:57.032  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=a638717d-7f44-4853-98d2-510ca488fa1f, clientIf=5
03-29 16:23:57.033  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:23:57.034  2160  2180 D BtGatt.GattService: start scan with filters
,03-29 16:23:57.035  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:23:57.035  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:23:57.036  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:23:57.037  2160  2232 D BtGatt.AdvertiseManager: message : 1
,03-29 16:23:57.038  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:23:57.038  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:57.038  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.039  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:23:57.039  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.040  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:57.040  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:23:57.041  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:23:57.041  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:23:57.042  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:57.042  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:57.043  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 16:23:57.043  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:23:57.043  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:23:57.043  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:23:57.043  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:23:57.043  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:23:57.043  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:23:57.043  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:23:57.044  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:57.044  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.045  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:57.045  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.048  2160  2179 D BtGatt.GattService: registerClient() - UUID=3cb76f04-e456-43aa-9b5c-1ac4f834d36c
,03-29 16:23:57.048  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=3cb76f04-e456-43aa-9b5c-1ac4f834d36c, clientIf=6
03-29 16:23:57.048  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:23:57.049  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:23:57.052  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:23:57.054  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:23:57.057  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:23:57.057  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:23:57.059  2160  2981 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:23:57.059  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:57.060  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:57.060  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:57.060  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:23:57.060  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:23:57.060  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:23:57.060  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:23:57.060  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:57.060  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:57.060  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:23:57.064  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:57.064  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.064  2160  2179 D BtGatt.GattService: registerClient() - UUID=e702c93e-e16b-441d-8287-99c36e583921
,03-29 16:23:57.064  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=e702c93e-e16b-441d-8287-99c36e583921, clientIf=5
03-29 16:23:57.065  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:57.065  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:23:57.065  2160  2180 D BtGatt.GattService: start scan with filters
03-29 16:23:57.066  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-29 16:23:57.066  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:57.066  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:23:57.066  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:23:57.066  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-29 16:23:57.066  3271  3271 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 16:23:57.066  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:57.066  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:23:57.066  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:23:57.066  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:57.066  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:23:57.067  3271  3861 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 353)
03-29 16:23:57.070  3271  3861 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 38287
03-29 16:23:57.071  3271  3861 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-29 16:23:57.071  3271  3861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:23:57.071  3271  3861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:23:57.072  3271  3863 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 354, name: Sender)
03-29 16:23:57.072  3271  3861 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 353)
03-29 16:23:57.072  3271  3861 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 353)
,03-29 16:23:57.074  3271  3864 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 355, name: Receiver)
03-29 16:23:57.075  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:23:57.076  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:23:57.076  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.077  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 16:23:57.077  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:57.077  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:23:57.077  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:23:57.079  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:23:57.079  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:57.080  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:23:57.080  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:57.931  2160  2234 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 66 RCID: 67
,03-29 16:23:58.344  2160  2234 W bt-btif : new conn_srvc id:26, app_id:255
,03-29 16:23:58.344  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:23:58.345  2160  2234 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:23:58.345  2160  2234 W bt-btif : new conn_srvc id:26, app_id:1
03-29 16:23:58.345  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:23:58.346  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 16:23:58.346  2160  2234 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:23:58.346  3271  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-29 16:23:58.346  3271  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 351)
03-29 16:23:58.346  3271  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-29 16:23:58.348  3271  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 356)
03-29 16:23:58.348  3271  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 356)
03-29 16:23:58.348  3271  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 351)
,03-29 16:23:58.350  3271  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 357),
03-29 16:23:58.351  3271  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:58.352   823  1343 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:23:58.356  3271  3837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:23:58.358  3271  3865 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 356)
,03-29 16:23:58.361  3271  3866 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 357)
03-29 16:23:58.361  3271  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:23:58.620  3271  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 357)
,03-29 16:23:58.624  3271  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:23:58.624  3271  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 357)
,03-29 16:23:58.625  3271  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 357
03-29 16:23:58.626  3271  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 357)
,03-29 16:23:58.626  3271  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0],
03-29 16:23:58.626  3271  3866 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 357)
03-29 16:23:58.626  3271  3271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:23:58.627  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:23:58.627  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-29 16:23:58.628  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-29 16:23:58.628  3271  3271 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-29 16:23:58.631  3271  3867 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 358)
,03-29 16:23:58.637  3271  3867 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 38287
03-29 16:23:58.638  3271  3867 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-29 16:23:58.638  3271  3867 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:23:58.639  3271  3867 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:23:58.641  3271  3868 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 359, name: Sender)
,03-29 16:23:58.642  3271  3867 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 358)
03-29 16:23:58.642  3271  3867 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 358)
,03-29 16:23:58.647  3271  3869 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 360, name: Receiver)
,03-29 16:23:58.695  3271  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 356)
,03-29 16:23:58.699  3271  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:23:58.700  3271  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
03-29 16:23:58.700  3271  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 351)
,03-29 16:23:58.701  3271  3865 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 356)
03-29 16:23:58.701  3271  3271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:23:58.701  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:23:58.702  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-29 16:23:58.704  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-29 16:23:58.704  3271  3271 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
03-29 16:23:58.707  3271  3870 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 361)
03-29 16:23:58.710  3271  3870 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55748
03-29 16:23:58.710  3271  3870 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-29 16:23:58.710  3271  3870 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 55748 (peer ID: E0:DB:10:14:E2:C0)
03-29 16:23:58.711  3271  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-29 16:23:58.719  3271  3327 I jxcore-log: INFO testThaliMobileNative: 
03-29 16:23:58.719  3271  3327 I jxcore-log: 
,03-29 16:23:58.721  3271  3327 I jxcore-log: ok 165 Must have listeningPort,
03-29 16:23:58.721  3271  3327 I jxcore-log: 
03-29 16:23:58.722  3271  3327 I jxcore-log: ok 166 listeningPort must be a number
03-29 16:23:58.722  3271  3327 I jxcore-log: ,
,03-29 16:23:58.724  3271  3327 I jxcore-log: ok 167 Connection must have clientPort
03-29 16:23:58.724  3271  3327 I jxcore-log: 
03-29 16:23:58.725  3271  3327 I jxcore-log: ok 168 clientPort must be a number
03-29 16:23:58.725  3271  3327 I jxcore-log: 
03-29 16:23:58.727  3271  3327 I jxcore-log: ok 169 Connection must have serverPort
,03-29 16:23:58.727  3271  3327 I jxcore-log: 
03-29 16:23:58.728  3271  3327 I jxcore-log: ok 170 serverPort must be a number
03-29 16:23:58.728  3271  3327 I jxcore-log: 
03-29 16:23:58.730  3271  3327 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-29 16:23:58.730  3271  3327 I jxcore-log: 
,03-29 16:23:58.732  3271  3327 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-29 16:23:58.732  3271  3327 I jxcore-log: 
,03-29 16:23:58.739  3271  3327 I jxcore-log: # teardown
03-29 16:23:58.739  3271  3327 I jxcore-log: 
,03-29 16:23:59.529  2160  2361 W bt-btif : invalid rfc slot id: 10
,03-29 16:23:59.540  3271  3863 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 354, thread name: Sender),
,03-29 16:23:59.540  3271  3863 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read,
03-29 16:23:59.541  3271  3863 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read,
,03-29 16:23:59.541  3271  3868 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 359, thread name: Sender)
03-29 16:23:59.541  3271  3868 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-29 16:23:59.541  3271  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 353
,03-29 16:23:59.541  3271  3868 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-29 16:23:59.541  3271  3863 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 353)
03-29 16:23:59.542  3271  3863 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:23:59.542  3271  3863 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 16:23:59.542  3271  3863 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 355
03-29 16:23:59.542  3271  3863 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-29 16:23:59.542  3271  3864 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 355, thread name: Receiver): bt socket closed, read return: -1
03-29 16:23:59.542  3271  3864 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 355, name: Receiver)
03-29 16:23:59.544  3271  3863 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 354
03-29 16:23:59.544  3271  3863 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 353)
03-29 16:23:59.545  3271  3863 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 353)
03-29 16:23:59.546  3271  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-29 16:23:59.546  3271  3868 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 358
03-29 16:23:59.546  3271  3868 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
03-29 16:23:59.546  3271  3868 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:23:59.546  3271  3868 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 16:23:59.547  3271  3868 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 360
03-29 16:23:59.547  3271  3868 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-29 16:23:59.547  3271  3868 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 359
03-29 16:23:59.547  3271  3868 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 358)
03-29 16:23:59.548  3271  3868 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 358)
03-29 16:23:59.548  3271  3868 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-29 16:23:59.548  3271  3868 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 359, name: Sender)
,03-29 16:23:59.550  3271  3869 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Receiver): bt socket closed, read return: -1
03-29 16:23:59.550  3271  3863 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 354, name: Sender)
03-29 16:23:59.551  3271  3869 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 360, name: Receiver)
03-29 16:23:59.554  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:23:59.555  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:59.555  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:23:59.555  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:23:59.558  2160  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:23:59.561  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:23:59.561  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:23:59.561  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:23:59.561  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:59.561  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:23:59.561  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:23:59.561  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:23:59.561  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 16:23:59.561  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 16:23:59.561  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:59.562  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:23:59.562  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:23:59.562  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:59.564  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:23:59.565  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:59.565  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:23:59.566  3271  3327 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 16:23:59.566  3271  3327 I jxcore-log: 
03-29 16:23:59.567  3271  3327 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-29 16:23:59.567  3271  3327 I jxcore-log: 
03-29 16:23:59.567  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 16:23:59.567  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:23:59.568  2160  2223 D BtGatt.GattService: current time is 240444614698
03-29 16:23:59.568  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -77, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 0, -117, -16, 115, -72, 77, 1, -128, -91, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:23:59.568  3271  3327 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:23:59.568  3271  3327 I jxcore-log: 
03-29 16:23:59.568  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 16:23:59.568  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 16:23:59.568  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:23:59.569  3271  3327 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:23:59.569  3271  3327 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 361)
03-29 16:23:59.569  3271  3327 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 361)
03-29 16:23:59.569  3271  3327 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:23:59.569  3271  3327 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 361)
03-29 16:23:59.569  3271  3327 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 361)
03-29 16:23:59.569  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 16:23:59.569  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:23:59.569  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:23:59.569  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:23:59.569  3271  3870 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 361)
03-29 16:23:59.569  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:23:59.569  3271  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:23:59.569  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:23:59.569  3271  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:23:59.569  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-29 16:23:59.569  3271  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:23:59.569  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:23:59.569  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:23:59.570  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:23:59.570  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:23:59.570  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:23:59.571  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:23:59.571  3271  3327 D BluetoothLeScanner: could not find callback wrapper
03-29 16:23:59.572  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:23:59.572  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:23:59.573  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:23:59.575  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:23:59.578  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:23:59.578  2160  2223 D BtGatt.GattService: Client app is not null!
,03-29 16:23:59.578  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:23:59.579  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:23:59.579  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 16:23:59.579  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:23:59.579  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:23:59.579  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:23:59.579  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:23:59.579  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:23:59.579  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:23:59.580  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:23:59.580  3271  3327 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:23:59.580  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:59.580  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:23:59.580  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:23:59.580  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:23:59.580  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:23:59.580  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:23:59.581  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:23:59.581  3271  3327 I jxcore-log: 
,03-29 16:23:59.583  3271  3327 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-29 16:23:59.583  3271  3327 I jxcore-log: 
,03-29 16:23:59.586  2160  2234 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
03-29 16:23:59.586  2160  2234 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-29 16:23:59.589  3271  3327 I jxcore-log: # setup
03-29 16:23:59.589  3271  3327 I jxcore-log: 
,03-29 16:23:59.592  2160  2234 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
03-29 16:23:59.592  2160  2234 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-29 16:23:59.650   823   838 I art     : Explicit concurrent mark sweep GC freed 33950(1619KB) AllocSpace objects, 11(647KB) LOS objects, 32% free, 33MB/49MB, paused 1.528ms total 69.107ms
,03-29 16:23:59.669  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:23:59.670   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:23:59.682  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-29 16:23:59.683  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-29 16:23:59.683  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:23:59.706  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 16:23:59.706  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:23:59.707  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:59.707  3271  3327 I jxcore-log: 
03-29 16:23:59.708  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:23:59.708  3271  3327 I jxcore-log: 
,03-29 16:23:59.854  2160  2221 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 16:24:01.085  3271  3327 I jxcore-log: # 41. Can shift large amounts of data
03-29 16:24:01.085  3271  3327 I jxcore-log: 
,03-29 16:24:01.342  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48544, start advertisements: true
03-29 16:24:01.342  3271  3327 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:01.342  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:01.343  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:01.343  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:01.343  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:01.350  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 16:24:01.350  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:01.350  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:01.351  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:01.360  2160  2180 D BtGatt.GattService: registerClient() - UUID=361c95e4-943a-4183-92d4-6e8ba336592a
03-29 16:24:01.360  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=361c95e4-943a-4183-92d4-6e8ba336592a, clientIf=5
,03-29 16:24:01.361  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:24:01.361  2160  2981 D BtGatt.GattService: start scan with filters
03-29 16:24:01.365  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:01.365  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:01.365  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:24:01.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 16:24:01.368  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:24:01.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:01.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:01.368  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:01.368  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:01.368  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:01.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:01.368  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:01.370  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:01.376  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:24:01.376  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:01.376  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:24:01.376  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:01.377  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 16:24:01.377  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:24:01.378  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:01.378  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:01.379  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:24:01.379  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:01.380  2160  2982 D BtGatt.GattService: registerClient() - UUID=526d7e05-df81-4bd7-88ad-b050c7ed0abb
03-29 16:24:01.381  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=526d7e05-df81-4bd7-88ad-b050c7ed0abb, clientIf=6
,03-29 16:24:01.381  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:24:01.381  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:01.384  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:01.386  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:24:01.389  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:24:01.389  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:24:01.389  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:01.389   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:01.391  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:01.391  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:01.391  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:01.391  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:01.392  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:24:01.392  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:24:01.392  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:01.392  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 16:24:01.392  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:01.392  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:01.393  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:01.393  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:01.393  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:01.393  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:24:01.393  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:24:01.393  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 16:24:01.393  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:01.393  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:24:01.393  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:01.393   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:24:01.393  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:24:01.393  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:01.394  3271  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:24:01.395  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:01.395  3271  3327 I jxcore-log: 
03-29 16:24:01.396  3271  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:01.397  3271  3327 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-29 16:24:01.397  3271  3327 I jxcore-log: 
,03-29 16:24:01.399  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48544, start advertisements: false
,03-29 16:24:01.399  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:01.399  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 16:24:01.399  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:01.399  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:01.400  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:01.400  3271  3327 I jxcore-log: 
03-29 16:24:01.401  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:24:01.401  3271  3327 I jxcore-log: 
,03-29 16:24:01.402  3271  3327 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-29 16:24:01.402  3271  3327 I jxcore-log: 
,03-29 16:24:03.619  2160  2234 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-29 16:24:03.626  2160  2160 D BluetoothMapService: onReceive
,03-29 16:24:03.732   823  1379 I ActivityManager: Start proc 3876:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-29 16:24:03.762  2160  2234 W bt-btif : new conn_srvc id:26, app_id:255
,03-29 16:24:03.762  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:24:03.762  2160  2234 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-29 16:24:03.763  3271  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-29 16:24:03.763  3271  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 363)
03-29 16:24:03.763  3271  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:24:03.764   823  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:24:03.764  3271  3893 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 363)
,03-29 16:24:03.765  3271  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:24:03.769  3271  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:03.837  3271  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 363)
,03-29 16:24:03.838  3271  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:24:03.840  3271  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 363),
03-29 16:24:03.840  3271  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 363
,03-29 16:24:03.840  3271  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 363)
03-29 16:24:03.840  3271  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:24:03.840  3271  3893 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 363)
03-29 16:24:03.840  3271  3271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0],
03-29 16:24:03.841  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-29 16:24:03.841  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-29 16:24:03.842  3271  3271 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings,
03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
,03-29 16:24:03.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:03.844  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:03.845  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:24:03.849  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:24:03.849  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:24:03.851  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:03.856  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-29 16:24:03.856  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:03.856  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:03.856  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-29 16:24:03.857  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:03.857  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:03.857  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:03.857  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:03.857  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:24:03.863  2160  2982 D BtGatt.GattService: registerClient() - UUID=dd978322-d908-48c1-a651-947eb5cc69cf
,03-29 16:24:03.864  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=dd978322-d908-48c1-a651-947eb5cc69cf, clientIf=6
,03-29 16:24:03.864  3271  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:03.866  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:03.870  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:03.873  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:24:03.875  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:24:03.876  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:03.878  2160  2981 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:24:03.879  2160  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:03.880   823   858 D BluetoothManagerService: Message: 20
03-29 16:24:03.880  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:24:03.880   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e4af1:true
,03-29 16:24:03.880  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.880  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:03.880  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:03.880  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:03.881  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:03.881  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:03.881  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:03.881  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:03.882  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-29 16:24:03.882  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.882  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:24:03.885  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-29 16:24:03.885  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.885  2160  2223 D BtGatt.GattService: current time is 244762236207
03-29 16:24:03.885  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -66, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 88, -66, -25, 96, 65, 82, 1, -128, -73, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -28, -44, -106, -22, -38, 116, 0, -128, -106, 8, 0, 23, 2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0, 0]
03-29 16:24:03.886  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:24:03.886  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:24:03.886  2160  2223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 5, 24, 15, 9, 90, 101, 70, 105, 116, 50, 32, 35, 54, 54, 48, 55, 53, 0]
,03-29 16:24:03.893  2160  2180 D BtGatt.GattService: registerClient() - UUID=7b5bfd35-e8c4-459c-98ec-91e117773bb7,
03-29 16:24:03.893  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=7b5bfd35-e8c4-459c-98ec-91e117773bb7, clientIf=5
03-29 16:24:03.893  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:24:03.894  2160  2981 D BtGatt.GattService: start scan with filters
03-29 16:24:03.894  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:03.894  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:03.894  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1,
03-29 16:24:03.894  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:24:03.895  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:03.895  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:03.895  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:24:03.895  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:03.895  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:03.895  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
,03-29 16:24:03.899  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:03.899  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:24:03.900  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-29 16:24:03.900  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.901  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-29 16:24:03.901  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.902  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 16:24:03.902  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:24:03.902  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:24:03.903  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:24:03.904  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:03.904  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:24:03.904  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED,
,03-29 16:24:03.905  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:03.905  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:03.905  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:03.905  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:03.905  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:03.905  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:03.905  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:03.906  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-29 16:24:03.906  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:03.907  3876  3876 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
03-29 16:24:03.908  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:24:03.908  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.912  2160  2981 D BtGatt.GattService: registerClient() - UUID=37d5b234-532b-46bf-a25b-abc865fb48aa
,03-29 16:24:03.912  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=37d5b234-532b-46bf-a25b-abc865fb48aa, clientIf=6
03-29 16:24:03.912  3271  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:24:03.914  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:03.917  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising,
,03-29 16:24:03.920  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 16:24:03.922  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-29 16:24:03.923  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:03.924  2160  2179 D BtGatt.GattService: stopScan() - queue size =1,
03-29 16:24:03.925  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:03.925  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:03.925  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:03.925  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:03.925  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:24:03.925  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:03.925  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:03.926  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:24:03.926  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:03.926  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:03.929  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:24:03.929  2160  2981 D BtGatt.GattService: registerClient() - UUID=17183097-ab2f-42d8-ab34-6aa45315e282
03-29 16:24:03.929  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.930  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=17183097-ab2f-42d8-ab34-6aa45315e282, clientIf=5
,03-29 16:24:03.930  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:24:03.930  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:24:03.930  2160  2982 D BtGatt.GattService: start scan with filters
,03-29 16:24:03.931  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:24:03.931  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.931  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:03.931  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-29 16:24:03.931  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 16:24:03.932  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:03.932  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:03.932  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 16:24:03.932  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:03.932  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:03.932  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 16:24:03.934  2160  2232 D BtGatt.AdvertiseManager: message : 1
,03-29 16:24:03.938  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:03.939  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:24:03.941  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:24:03.941  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.942  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:24:03.942  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:03.942  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:03.942  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:24:03.943  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:24:03.943  2160  2223 D BtGatt.GattService: Client app is not null!
,03-29 16:24:03.944  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:03.944  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:03.944  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 16:24:03.944  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:03.944  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:24:03.944  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:03.944  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:03.944  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:03.944  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:03.944  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:03.946  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-29 16:24:03.946  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.947  2160  2981 D BtGatt.GattService: registerClient() - UUID=e51542e8-31ad-4d8b-a30a-79d696717cf8
03-29 16:24:03.948  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=e51542e8-31ad-4d8b-a30a-79d696717cf8, clientIf=6
,03-29 16:24:03.948  3271  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:24:03.949  2160  2232 D BtGatt.AdvertiseManager: message : 0
03-29 16:24:03.950  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:24:03.950  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.951  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:03.954  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:24:03.957  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:24:03.958  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 16:24:03.959  2160  2179 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:03.959  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:03.959  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:03.959  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 16:24:03.959  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:03.959  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:03.959  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:03.959  3271  3271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:03.961  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 16:24:03.961  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.961  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:03.962  2160  2981 D BtGatt.GattService: registerClient() - UUID=35992a5d-3106-465f-91d8-e3a29db2e8f9
03-29 16:24:03.962  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=35992a5d-3106-465f-91d8-e3a29db2e8f9, clientIf=5
03-29 16:24:03.962  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:24:03.963  2160  2982 D BtGatt.GattService: start scan with filters
03-29 16:24:03.963  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:24:03.963  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.963  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:24:03.964  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:03.964  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:03.964  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-29 16:24:03.964  3271  3271 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 16:24:03.964  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-29 16:24:03.964  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:03.964  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-29 16:24:03.964  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:03.965  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:03.965  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:03.965  3271  3894 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 364)
03-29 16:24:03.966  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-29 16:24:03.966  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.966  2160  2223 D BtGatt.GattService: current time is 244843097769
03-29 16:24:03.966  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 16:24:03.966  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:24:03.967  3271  3894 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 48544
03-29 16:24:03.967  3271  3894 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-29 16:24:03.967  3271  3894 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:24:03.967  3271  3894 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:24:03.968  3271  3894 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 364)
03-29 16:24:03.968  3271  3894 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 364)
03-29 16:24:03.968  3271  3896 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Sender)
03-29 16:24:03.969  3271  3327 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-29 16:24:03.969  3271  3327 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID E0:DB:10:14:E2:C0, but will connect anyway...
03-29 16:24:03.969  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:24:03.969  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:03.970  3271  3897 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Receiver)
03-29 16:24:03.971  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-29 16:24:03.971  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-29 16:24:03.971  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-29 16:24:03.971  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-29 16:24:03.971  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-29 16:24:03.971  3271  3327 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-29 16:24:03.971  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:24:03.971  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:03.972  3271  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 367)
03-29 16:24:03.973  3271  3898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:03.974  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-29 16:24:03.974  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:03.974  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:03.974  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:24:03.975  2160  2179 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 16:24:03.975  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:03.975  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:03.976  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:24:03.976  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:04.114   823  1159 I ActivityManager: Start proc 3908:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-29 16:24:04.115  3876  3876 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-29 16:24:04.127   823  1419 I ActivityManager: Killing 3567:com.android.chrome/u0a40 (adj 15): empty #17
,03-29 16:24:04.248  2160  2234 W bt-sdp  : process_service_search_attr_rsp
,03-29 16:24:04.686  2160  2234 W bt-btif : new conn_srvc id:26, app_id:1
03-29 16:24:04.687  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-29 16:24:04.687  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 16:24:04.687  2160  2234 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 16:24:04.687  3271  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
03-29 16:24:04.687  3271  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 367)
03-29 16:24:04.688  3271  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 368)
03-29 16:24:04.688  3271  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 368)
,03-29 16:24:04.689  3271  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 367)
,03-29 16:24:04.696  3271  3928 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 368)
,03-29 16:24:05.107   823  1379 I ActivityManager: Killing 3620:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-29 16:24:05.639  3271  3928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 368)
,03-29 16:24:05.643  3271  3928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:24:05.643  3271  3928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
03-29 16:24:05.643  3271  3928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
03-29 16:24:05.644  3271  3928 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 368)
03-29 16:24:05.644  3271  3271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:24:05.644  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-29 16:24:05.645  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
03-29 16:24:05.645  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-29 16:24:05.646  3271  3271 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-29 16:24:05.649  3271  3929 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 369)
03-29 16:24:05.650  3271  3929 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55598
03-29 16:24:05.650  3271  3929 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-29 16:24:05.650  3271  3929 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 55598 (peer ID: E0:DB:10:14:E2:C0)
,03-29 16:24:05.650  3271  3929 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
,03-29 16:24:05.658  3271  3327 I jxcore-log: INFO testThaliMobileNative: 
03-29 16:24:05.658  3271  3327 I jxcore-log: 
,03-29 16:24:05.660  3271  3327 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-29 16:24:05.660  3271  3327 I jxcore-log: 
,03-29 16:24:05.670  3271  3929 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 55598
,03-29 16:24:05.670  3271  3929 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-29 16:24:05.670  3271  3929 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:24:05.671  3271  3929 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-29 16:24:05.673  3271  3930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 370, name: Sender)
03-29 16:24:05.674  3271  3929 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 369)
03-29 16:24:05.674  3271  3929 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 369)
,03-29 16:24:05.676  3271  3327 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-29 16:24:05.676  3271  3327 I jxcore-log: 
03-29 16:24:05.677  3271  3931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 371, name: Receiver)
,03-29 16:24:05.907  3271  3327 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:05.907  3271  3327 I jxcore-log: 
,03-29 16:24:05.912  3271  3327 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:05.912  3271  3327 I jxcore-log: 
,03-29 16:24:05.978  3271  3327 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:05.978  3271  3327 I jxcore-log: 
,03-29 16:24:06.075  3271  3327 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:06.075  3271  3327 I jxcore-log: 
,03-29 16:24:06.106  3271  3327 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 16:24:06.106  3271  3327 I jxcore-log: 
,03-29 16:24:06.107  3271  3327 I jxcore-log: ok 177 received should match sent forward
03-29 16:24:06.107  3271  3327 I jxcore-log: 
,03-29 16:24:06.112  3271  3327 I jxcore-log: # teardown
03-29 16:24:06.112  3271  3327 I jxcore-log: 
,03-29 16:24:06.310  2160  2225 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 16:24:08.139  2160  2234 W bt-btif : info:x10
03-29 16:24:08.139  2160  2223 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-29 16:24:08.169  3876  3876 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-29 16:24:08.172  3876  3876 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-29 16:24:08.457  2160  2223 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-29 16:24:08.464  2160  2223 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-29 16:24:08.464  2160  2223 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-29 16:24:08.469  2160  2224 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-29 16:24:08.470  2160  2224 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 16:24:08.576  2160  2223 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-29 16:24:08.577  2160  2224 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-29 16:24:08.581  2160  2224 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-29 16:24:08.597  2160  2224 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 16:24:08.642  2160  2234 W bt-btif : new conn_srvc id:26, app_id:255
,03-29 16:24:08.642  2160  2234 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 16:24:08.642  2160  2234 W bt-btif : bta_dm_pm_ssr:2, lat:1200,
03-29 16:24:08.643  3271  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-29 16:24:08.643  3271  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 372)
03-29 16:24:08.644  3271  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:24:08.645   823  1421 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:24:08.649  3271  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:08.651  3271  3933 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 372)
,03-29 16:24:08.657  3271  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:08.687  3271  3933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 372)
,03-29 16:24:08.691  3271  3933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-29 16:24:08.691  3271  3933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 372)
03-29 16:24:08.692  3271  3933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 372
03-29 16:24:08.692  3271  3933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 372)
,03-29 16:24:08.692  3271  3933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 16:24:08.693  3271  3271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 16:24:08.694  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-29 16:24:08.694  3271  3933 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 372)
03-29 16:24:08.694  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-29 16:24:08.696  3271  3271 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-29 16:24:08.696  3271  3271 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-29 16:24:08.697  3271  3271 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 16:24:08.699  3271  3934 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 373)
,03-29 16:24:08.706  3271  3934 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 48544
,03-29 16:24:08.706  3271  3934 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-29 16:24:08.707  3271  3934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:24:08.707  3271  3934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 16:24:08.708  3271  3936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 374, name: Sender)
,03-29 16:24:08.708  3271  3934 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 373)
03-29 16:24:08.708  3271  3934 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 373)
03-29 16:24:08.710  3271  3937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Receiver)
,03-29 16:24:08.981  2160  2160 D BtGatt.ScanManager: awakened up at time 249857
,03-29 16:24:08.983  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:24:08.988  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 16:24:08.988  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:08.988  2160  2223 D BtGatt.GattService: current time is 249865464642
03-29 16:24:08.989  2160  2223 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -77, 68, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 88, -66, -25, 96, 65, 82, 1, -128, -78, 52, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 16:24:08.989  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 16:24:08.990  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:24:08.993  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 16:24:08.994  3271  3271 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-29 16:24:09.479  2160  2361 W bt-btif : invalid rfc slot id: 18
03-29 16:24:09.480  3271  3931 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Receiver): bt socket closed, read return: -1
,03-29 16:24:09.480  3271  3931 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-29 16:24:09.480  3271  3931 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-29 16:24:09.480  3271  3931 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
03-29 16:24:09.480  3271  3931 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 369)
03-29 16:24:09.481  3271  3931 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 369)
03-29 16:24:09.481  3271  3931 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:24:09.481  3271  3931 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-29 16:24:09.481  3271  3931 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 371
03-29 16:24:09.481  3271  3931 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-29 16:24:09.481  3271  3931 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 370
03-29 16:24:09.482  3271  3931 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 369)
03-29 16:24:09.482  3271  3931 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 369)
03-29 16:24:09.482  3271  3931 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-29 16:24:09.482  3271  3931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 371, name: Receiver)
,03-29 16:24:09.486  3271  3930 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Sender): Socket closed
03-29 16:24:09.486  3271  3930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 370, name: Sender)
,03-29 16:24:09.493  2160  2361 W bt-btif : invalid rfc slot id: 17
03-29 16:24:09.494  3271  3937 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1
,03-29 16:24:09.494  3271  3937 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,03-29 16:24:09.494  3271  3937 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-29 16:24:09.494  3271  3937 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 373
03-29 16:24:09.495  3271  3937 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 373)
,03-29 16:24:09.495  3271  3937 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-29 16:24:09.495  3271  3937 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-29 16:24:09.495  3271  3937 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-29 16:24:09.495  3271  3937 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-29 16:24:09.495  3271  3937 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 374
,03-29 16:24:09.495  3271  3937 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 373)
03-29 16:24:09.496  3271  3936 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
03-29 16:24:09.496  2160  2361 W bt-btif : invalid rfc slot id: 15
03-29 16:24:09.496  3271  3936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 374, name: Sender)
,03-29 16:24:09.497  3271  3897 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
03-29 16:24:09.497  3271  3897 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-29 16:24:09.497  3271  3897 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-29 16:24:09.499  3271  3937 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 373)
,03-29 16:24:09.499  3271  3937 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-29 16:24:09.499  3271  3897 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 364
03-29 16:24:09.499  3271  3897 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 364)
03-29 16:24:09.499  3271  3897 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 16:24:09.500  3271  3897 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 16:24:09.500  3271  3897 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
,03-29 16:24:09.500  3271  3897 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-29 16:24:09.500  3271  3897 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-29 16:24:09.500  3271  3897 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 364)
03-29 16:24:09.500  3271  3937 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Receiver)
03-29 16:24:09.501  3271  3897 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 364)
03-29 16:24:09.501  3271  3896 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Sender): Socket closed
03-29 16:24:09.501  3271  3896 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Sender)
03-29 16:24:09.501  3271  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-29 16:24:09.501  3271  3897 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Receiver)
03-29 16:24:09.512  2160  2234 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
03-29 16:24:09.512  2160  2234 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x4a
,03-29 16:24:09.516  3271  3327 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 16:24:09.516  3271  3327 I jxcore-log: 
03-29 16:24:09.517  3271  3327 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-29 16:24:09.517  3271  3327 I jxcore-log: 
,03-29 16:24:09.551  2160  2234 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
03-29 16:24:09.551  2160  2234 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x47
,03-29 16:24:09.885  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:09.886  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 16:24:09.886  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 16:24:09.886  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 16:24:09.889  2160  2180 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 16:24:09.893  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 16:24:09.893  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:09.893  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:09.894  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:09.895  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:09.896  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 16:24:09.896  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:09.896  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:09.896  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:24:09.896  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:24:09.896  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:09.896  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:09.896  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:24:09.898  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:24:09.898  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:09.899  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:09.899  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 16:24:09.899  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:09.902  3271  3327 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-29 16:24:09.902  3271  3327 I jxcore-log: 
03-29 16:24:09.904  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:09.904  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:09.904  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:24:09.904  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:24:09.904  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:24:09.906  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-29 16:24:09.906  3271  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:24:09.906  3271  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:24:09.907  3271  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:09.907  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:24:09.908  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:09.908  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:09.908  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:09.908  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 16:24:09.908  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:09.908  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 16:24:09.908  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:09.910  3271  3327 D BluetoothLeScanner: could not find callback wrapper
,03-29 16:24:09.910  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:09.910  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:24:09.912  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:09.912  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:24:09.916  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:24:09.916  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:24:09.918  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:09.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 16:24:09.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:09.919  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:24:09.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:09.920  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-29 16:24:09.920  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:09.921  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:09.921  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:09.922  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:09.922  3271  3327 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 16:24:09.922  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:09.922  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 16:24:09.922  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:09.923  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:09.923  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:09.923  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:24:09.925  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:24:09.925  3271  3327 I jxcore-log: 
,03-29 16:24:09.927  3271  3327 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
,03-29 16:24:09.927  3271  3327 I jxcore-log: 
,03-29 16:24:09.930  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 16:24:09.930   823  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:24:09.933  3271  3327 I jxcore-log: # setup
03-29 16:24:09.933  3271  3327 I jxcore-log: 
,03-29 16:24:09.939  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-29 16:24:09.940  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:09.940  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:09.944  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:09.944  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:09.946  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:09.946  3271  3327 I jxcore-log: 
,03-29 16:24:09.947  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:09.947  3271  3327 I jxcore-log: 
,03-29 16:24:10.086  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:10.086  3271  3327 I jxcore-log: 
,03-29 16:24:10.091  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:10.091  3271  3327 I jxcore-log: ,
,03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:10.101  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 16:24:10.104  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:10.105  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:10.105  3271  3327 I jxcore-log: 
,03-29 16:24:10.107  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:10.107  3271  3327 I jxcore-log: 
,03-29 16:24:10.110  3271  3327 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-29 16:24:10.110  3271  3327 I jxcore-log: 
,03-29 16:24:10.112  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:10.112  3271  3327 I jxcore-log: 
,03-29 16:24:11.325  3271  3327 I jxcore-log: ok 180 specific error should be returned
03-29 16:24:11.325  3271  3327 I jxcore-log: 
,03-29 16:24:11.328  3271  3327 I jxcore-log: # teardown
,03-29 16:24:11.328  3271  3327 I jxcore-log: 
,03-29 16:24:11.484  3271  3327 I jxcore-log: ok 181 must be stopped
,03-29 16:24:11.484  3271  3327 I jxcore-log: 
,03-29 16:24:11.488  3271  3327 I jxcore-log: # setup
,03-29 16:24:11.488  3271  3327 I jxcore-log: 
,03-29 16:24:12.345  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-29 16:24:12.345  3271  3327 I jxcore-log: 
03-29 16:24:12.346  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:12.346  3271  3327 I jxcore-log: 
,03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
03-29 16:24:12.356  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:12.360  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:12.363  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:12.363  3271  3327 I jxcore-log: 
,03-29 16:24:12.364  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:12.364  3271  3327 I jxcore-log: 
,03-29 16:24:12.368  3271  3327 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-29 16:24:12.368  3271  3327 I jxcore-log: 
,03-29 16:24:12.370  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:12.370  3271  3327 I jxcore-log: 
,03-29 16:24:12.606  3271  3327 I jxcore-log: ok 182 specific error should be returned
03-29 16:24:12.606  3271  3327 I jxcore-log: ,
,03-29 16:24:12.608  3271  3327 I jxcore-log: # teardown
03-29 16:24:12.608  3271  3327 I jxcore-log: 
,03-29 16:24:12.741  3271  3327 I jxcore-log: ok 183 must be stopped
03-29 16:24:12.741  3271  3327 I jxcore-log: 
,03-29 16:24:12.745  3271  3327 I jxcore-log: # setup
03-29 16:24:12.745  3271  3327 I jxcore-log: 
,03-29 16:24:12.845  2160  2234 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-29 16:24:12.852  2160  2160 D BluetoothMapService: onReceive
,03-29 16:24:12.883  3876  3876 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-29 16:24:12.888  3876  3876 I BluetoothClassifier: Bluetooth Device Name: G4-1,
,03-29 16:24:12.905  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:12.905  3271  3327 I jxcore-log: 
,03-29 16:24:12.906  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:12.906  3271  3327 I jxcore-log: 
,03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:12.913  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:12.919  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
03-29 16:24:12.920  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:12.920  3271  3327 I jxcore-log: 
,03-29 16:24:12.922  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:12.922  3271  3327 I jxcore-log: 
,03-29 16:24:12.925  3271  3327 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-29 16:24:12.925  3271  3327 I jxcore-log: 
,03-29 16:24:12.926  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:12.926  3271  3327 I jxcore-log: 
,03-29 16:24:13.043  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:13.043  3271  3327 I jxcore-log: 
,03-29 16:24:13.045  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 44821
03-29 16:24:13.045  3271  3327 I jxcore-log: 
,03-29 16:24:13.047  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:13.048  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:13.048  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.051  3271  3327 I jxcore-log: ok 184 no errors
03-29 16:24:13.051  3271  3327 I jxcore-log: 
,03-29 16:24:13.052  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 16:24:13.052  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:13.052  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.054  3271  3327 I jxcore-log: ok 185 still no errors
03-29 16:24:13.054  3271  3327 I jxcore-log: 
,03-29 16:24:13.060  3271  3327 I jxcore-log: # teardown
03-29 16:24:13.060  3271  3327 I jxcore-log: 
,03-29 16:24:13.210  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:13.210  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:13.210  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.216  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:13.216  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:13.216  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:13.226  3271  3327 I jxcore-log: ok 186 must be stopped
,03-29 16:24:13.226  3271  3327 I jxcore-log: 
,03-29 16:24:13.232  3271  3327 I jxcore-log: # setup
03-29 16:24:13.232  3271  3327 I jxcore-log: 
,03-29 16:24:13.376  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:13.376  3271  3327 I jxcore-log: 
,03-29 16:24:13.383  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-29 16:24:13.383  3271  3327 I jxcore-log: 
,03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:13.393  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:13.396  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:13.399  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:13.399  3271  3327 I jxcore-log: 
,03-29 16:24:13.401  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:13.401  3271  3327 I jxcore-log: 
,03-29 16:24:13.405  3271  3327 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-29 16:24:13.405  3271  3327 I jxcore-log: 
,03-29 16:24:13.406  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:13.406  3271  3327 I jxcore-log: 
,03-29 16:24:13.532  2160  2234 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-29 16:24:13.542  2160  2160 D BluetoothMapService: onReceive
,03-29 16:24:13.565  3876  3876 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-29 16:24:13.567  3876  3876 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-29 16:24:13.584  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server,
,03-29 16:24:13.584  3271  3327 I jxcore-log: 
,03-29 16:24:13.587  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 38213
03-29 16:24:13.587  3271  3327 I jxcore-log: 
,03-29 16:24:13.593  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48544, start advertisements: false
,03-29 16:24:13.593  3271  3327 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-29 16:24:13.593  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:13.595  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:13.595  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:13.595  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:24:13.602  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:13.602  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:24:13.602  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:13.610  2160  2982 D BtGatt.GattService: registerClient() - UUID=51c2ec74-4731-4c79-a4a6-7837e9255880
,03-29 16:24:13.610  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=51c2ec74-4731-4c79-a4a6-7837e9255880, clientIf=5
03-29 16:24:13.610  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:24:13.611  2160  2179 D BtGatt.GattService: start scan with filters
,03-29 16:24:13.612  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:13.613  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:24:13.613  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:13.613  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:24:13.613  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:13.614  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:13.615  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 16:24:13.615  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:13.615  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:13.615  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:13.616  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:24:13.616  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:13.616  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:13.616  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:24:13.617   823  1107 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 16:24:13.618  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:13.619  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:13.620  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:24:13.620  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:13.622  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:13.622  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:13.622  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:13.623  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:13.623  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:13.623  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:13.625  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:13.625  3271  3327 I jxcore-log: 
,03-29 16:24:13.625  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:13.625  3271  3327 I jxcore-log: 
03-29 16:24:13.631  3271  3327 I jxcore-log: ok 187 no errors
03-29 16:24:13.631  3271  3327 I jxcore-log: 
,03-29 16:24:13.636  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 48544, start advertisements: false
,03-29 16:24:13.636  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:13.636  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:13.636  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:13.636  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:13.641  3271  3327 I jxcore-log: ok 188 still no errors,
03-29 16:24:13.641  3271  3327 I jxcore-log: 
,03-29 16:24:13.647  3271  3327 I jxcore-log: # teardown,
03-29 16:24:13.647  3271  3327 I jxcore-log: 
,03-29 16:24:13.967  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-29 16:24:13.967  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:13.967  3271  3327 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 16:24:13.967  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 16:24:13.967  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:13.967  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:13.968  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:13.968  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:13.968  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:13.971  2160  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:24:13.975  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:24:13.975  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 16:24:13.975  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:13.975  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-29 16:24:13.976  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:13.976  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:13.976  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 16:24:13.976  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:24:13.977  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 16:24:13.977  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:13.979  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:13.979  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:24:13.979  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 16:24:13.979  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:13.979  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:24:13.980  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:24:13.981  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:13.981  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:13.982  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:13.982  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:13.982  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:24:13.982  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-29 16:24:13.982  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:13.992  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:13.992   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:14.000  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:24:14.001  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:14.001  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:14.007  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:14.007  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:14.007  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:14.007  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:14.010  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:14.010  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-29 16:24:14.010  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-29 16:24:14.013  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 16:24:14.013  3271  3327 I jxcore-log: 
,03-29 16:24:14.015  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:14.015  3271  3327 I jxcore-log: 
03-29 16:24:14.024  3271  3327 I jxcore-log: ok 189 must be stopped
03-29 16:24:14.024  3271  3327 I jxcore-log: ,
,03-29 16:24:14.037  3271  3327 I jxcore-log: # setup
03-29 16:24:14.037  3271  3327 I jxcore-log: 
,03-29 16:24:14.141  2160  2221 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 16:24:14.204  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:14.204  3271  3327 I jxcore-log: 
,03-29 16:24:14.209  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:14.209  3271  3327 I jxcore-log: 
,03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:14.220  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 16:24:14.223  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:14.225  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:14.225  3271  3327 I jxcore-log: 
03-29 16:24:14.227  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:14.227  3271  3327 I jxcore-log: 
,03-29 16:24:14.229  3271  3327 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-29 16:24:14.229  3271  3327 I jxcore-log: 
,03-29 16:24:14.231  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:14.231  3271  3327 I jxcore-log: 
,03-29 16:24:14.426  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:14.426  3271  3327 I jxcore-log: 
,03-29 16:24:14.432  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 42424
03-29 16:24:14.432  3271  3327 I jxcore-log: 
,03-29 16:24:14.442  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 42424, start advertisements: true,
,03-29 16:24:14.442  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:14.442  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 16:24:14.442  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:14.447  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
,03-29 16:24:14.447  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
,03-29 16:24:14.447  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:24:14.447  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 16:24:14.453  2160  2982 D BtGatt.GattService: registerClient() - UUID=3a201b8e-fc14-4715-b971-75082e56b41d
03-29 16:24:14.453  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=3a201b8e-fc14-4715-b971-75082e56b41d, clientIf=5
03-29 16:24:14.454  3271  3288 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:24:14.454  2160  2981 D BtGatt.GattService: start scan with filters,
03-29 16:24:14.455  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:24:14.455  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:14.455  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:14.456  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:24:14.456  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:14.456  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:24:14.456  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:14.456  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:14.456  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:14.456  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:14.457  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:14.457  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:14.457  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:14.464  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:24:14.464  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:14.465  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:24:14.465  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:14.465  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:14.465  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:24:14.467  2160  2981 D BtGatt.GattService: registerClient() - UUID=72eec130-599b-4b1b-b106-e14f18d95349
,03-29 16:24:14.467  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=72eec130-599b-4b1b-b106-e14f18d95349, clientIf=6
03-29 16:24:14.467  3271  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 16:24:14.467  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:14.468  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:14.469  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:24:14.469  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:14.472  2160  2232 D BtGatt.AdvertiseManager: message : 0,
,03-29 16:24:14.477  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising,
,03-29 16:24:14.480  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:24:14.482  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-29 16:24:14.483  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:14.483  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:14.483   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:14.486  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:14.486  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:24:14.486  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-29 16:24:14.486  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:14.487  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:24:14.488  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 16:24:14.488  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:14.488  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 16:24:14.488  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-29 16:24:14.488  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:24:14.488  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:14.488  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:14.488  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:24:14.488  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:24:14.488  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:14.488  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:14.489  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:24:14.489  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:14.489  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 16:24:14.489  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-29 16:24:14.489  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:14.490   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:14.491  3271  3939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:24:14.492  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:14.492  3271  3327 I jxcore-log: 
,03-29 16:24:14.494  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:14.494  3271  3327 I jxcore-log: 
03-29 16:24:14.495  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-29 16:24:14.495  3271  3327 I jxcore-log: 
03-29 16:24:14.496  3271  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 16:24:14.497  3271  3327 I jxcore-log: ok 190 no errors
,03-29 16:24:14.497  3271  3327 I jxcore-log: 
03-29 16:24:14.501  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 42424, start advertisements: true
03-29 16:24:14.501  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:24:14.502  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:24:14.502  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:14.502  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:14.506  3271  3327 I jxcore-log: ok 191 still no errors,
03-29 16:24:14.506  3271  3327 I jxcore-log: 
,03-29 16:24:14.521  3271  3327 I jxcore-log: # teardown
03-29 16:24:14.521  3271  3327 I jxcore-log: 
,03-29 16:24:15.426  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:15.426  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:15.426  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:24:15.427  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:24:15.427  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:24:15.428  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:24:15.428  3271  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-29 16:24:15.428  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:15.428  3271  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-29 16:24:15.428  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 16:24:15.428  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:15.428  3271  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:15.428  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 16:24:15.429  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:15.429  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 16:24:15.429  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:15.429  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:15.434  2160  2180 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:15.436  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:15.436  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:24:15.436  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:15.436  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:15.437  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:15.437  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:15.437  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:24:15.437  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:24:15.437  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:24:15.437  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:15.438  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:15.440  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:15.440  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:24:15.440  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:24:15.440  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:15.440  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:24:15.444  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:24:15.444  2160  2223 D BtGatt.GattService: Client app is not null!
,03-29 16:24:15.446  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:15.447  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 16:24:15.447  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 16:24:15.447  2160  2223 D BtGatt.GattService: current time is 256324485161
03-29 16:24:15.448  2160  2223 D BtGatt.GattService: Batch record : [-66, -94, -84, 82, -79, 89, 1, -128, -80, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 16:24:15.449  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 16:24:15.450  2160  2223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 16:24:15.450  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:15.450  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:15.450  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:24:15.450  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:15.450  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:24:15.451  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:15.451  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-29 16:24:15.451  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:15.451  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:15.451  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:15.451  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:15.451  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:15.451  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:24:15.457  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 16:24:15.457   823  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:15.462  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-29 16:24:15.463  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 16:24:15.463  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:15.466  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:24:15.466  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:15.466  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:15.466  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:15.466  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:15.466  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 16:24:15.469  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-29 16:24:15.469  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:15.469  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:15.470  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-29 16:24:15.470  3271  3327 I jxcore-log: 
03-29 16:24:15.471  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:15.471  3271  3327 I jxcore-log: 
03-29 16:24:15.472  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:15.472  3271  3327 I jxcore-log: 
,03-29 16:24:15.476  3271  3327 I jxcore-log: ok 192 must be stopped,
03-29 16:24:15.476  3271  3327 I jxcore-log: 
,03-29 16:24:15.482  3271  3327 I jxcore-log: # setup,
03-29 16:24:15.482  3271  3327 I jxcore-log: 
,03-29 16:24:15.618  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
,03-29 16:24:15.618  3271  3327 I jxcore-log: 
,03-29 16:24:15.622  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:15.622  3271  3327 I jxcore-log: 
,03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:15.637  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:15.644  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:15.648  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:15.648  3271  3327 I jxcore-log: 
,03-29 16:24:15.654  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:15.654  3271  3327 I jxcore-log: 
,03-29 16:24:15.664  3271  3327 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-29 16:24:15.664  3271  3327 I jxcore-log: 
,03-29 16:24:15.670  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:15.670  3271  3327 I jxcore-log: 
,03-29 16:24:16.245  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:16.245  3271  3327 I jxcore-log: 
,03-29 16:24:16.248  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 36749
03-29 16:24:16.248  3271  3327 I jxcore-log: 
,03-29 16:24:16.250  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:16.250  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:16.250  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.253  3271  3327 I jxcore-log: ok 193 no errors
03-29 16:24:16.253  3271  3327 I jxcore-log: 
,03-29 16:24:16.254  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:16.254  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:16.254  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.258  3271  3327 I jxcore-log: ok 194 still no errors
03-29 16:24:16.258  3271  3327 I jxcore-log: 
,03-29 16:24:16.265  3271  3327 I jxcore-log: # teardown
03-29 16:24:16.265  3271  3327 I jxcore-log: 
,03-29 16:24:16.406  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:16.406  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:16.406  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.414  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 16:24:16.414  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:16.414  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:16.419  3271  3327 I jxcore-log: ok 195 must be stopped,
03-29 16:24:16.419  3271  3327 I jxcore-log: 
,03-29 16:24:16.426  3271  3327 I jxcore-log: # setup,
03-29 16:24:16.426  3271  3327 I jxcore-log: 
,03-29 16:24:16.571  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-29 16:24:16.571  3271  3327 I jxcore-log: 
03-29 16:24:16.575  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:16.575  3271  3327 I jxcore-log: 
,03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:16.583  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:16.586  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:16.591  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:16.591  3271  3327 I jxcore-log: 
,03-29 16:24:16.595  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:16.595  3271  3327 I jxcore-log: 
,03-29 16:24:16.602  3271  3327 I jxcore-log: # 48. can get the network status before starting
03-29 16:24:16.602  3271  3327 I jxcore-log: 
,03-29 16:24:16.605  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:16.605  3271  3327 I jxcore-log: 
,03-29 16:24:16.768  3271  3327 I jxcore-log: ok 196 network status should have certain non-empty properties
03-29 16:24:16.768  3271  3327 I jxcore-log: 
,03-29 16:24:16.770  3271  3327 I jxcore-log: # teardown
,03-29 16:24:16.770  3271  3327 I jxcore-log: 
,03-29 16:24:16.940  3271  3327 I jxcore-log: ok 197 must be stopped
03-29 16:24:16.940  3271  3327 I jxcore-log: 
,03-29 16:24:16.946  3271  3327 I jxcore-log: # setup
03-29 16:24:16.946  3271  3327 I jxcore-log: 
,03-29 16:24:17.067  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:17.067  3271  3327 I jxcore-log: 
,03-29 16:24:17.071  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:17.071  3271  3327 I jxcore-log: 
,03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:17.084  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:17.090  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:17.094  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-29 16:24:17.094  3271  3327 I jxcore-log: 
,03-29 16:24:17.099  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:17.099  3271  3327 I jxcore-log: 
,03-29 16:24:17.105  3271  3327 I jxcore-log: # 49. error returned with bad router
03-29 16:24:17.105  3271  3327 I jxcore-log: 
,03-29 16:24:17.109  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-29 16:24:17.109  3271  3327 I jxcore-log: 
,03-29 16:24:17.271  3271  3327 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-29 16:24:17.271  3271  3327 I jxcore-log: 
,03-29 16:24:17.273  3271  3327 I jxcore-log: ok 198 specific error expected,
03-29 16:24:17.273  3271  3327 I jxcore-log: 
,03-29 16:24:17.277  3271  3327 I jxcore-log: # teardown
,03-29 16:24:17.277  3271  3327 I jxcore-log: 
,03-29 16:24:17.414  3271  3327 I jxcore-log: ok 199 must be stopped
03-29 16:24:17.414  3271  3327 I jxcore-log: 
,03-29 16:24:17.423  3271  3327 I jxcore-log: # setup
,03-29 16:24:17.423  3271  3327 I jxcore-log: 
,03-29 16:24:17.566  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:17.566  3271  3327 I jxcore-log: 
,03-29 16:24:17.571  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-29 16:24:17.571  3271  3327 I jxcore-log: 
,03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:17.585  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:17.591  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:17.595  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:17.595  3271  3327 I jxcore-log: 
,03-29 16:24:17.599  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:17.599  3271  3327 I jxcore-log: 
,03-29 16:24:17.607  3271  3327 I jxcore-log: # 50. all services are stopped when we call stop
03-29 16:24:17.607  3271  3327 I jxcore-log: 
,03-29 16:24:17.611  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:17.611  3271  3327 I jxcore-log: 
,03-29 16:24:17.752  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:17.752  3271  3327 I jxcore-log: 
,03-29 16:24:17.755  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 45837
03-29 16:24:17.755  3271  3327 I jxcore-log: 
,03-29 16:24:17.761  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 42424, start advertisements: false
,03-29 16:24:17.761  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:24:17.761  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 16:24:17.761  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-29 16:24:17.767  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:24:17.767  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:17.767  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:17.774  2160  2982 D BtGatt.GattService: registerClient() - UUID=8db8316c-2f27-4a1b-abba-6f206fbbe0c8
,03-29 16:24:17.775  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=8db8316c-2f27-4a1b-abba-6f206fbbe0c8, clientIf=5
,03-29 16:24:17.776  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:24:17.776  2160  2180 D BtGatt.GattService: start scan with filters
03-29 16:24:17.777  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:17.777  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:17.777  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:17.778  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 16:24:17.778  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:24:17.778  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:17.778  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:24:17.778  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:17.779   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:17.787  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 16:24:17.787  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:17.789  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:17.789  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:24:17.790  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 16:24:17.790  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:17.790  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:17.790  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:24:17.791  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:17.791  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:17.792  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:17.792  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:17.793  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:17.794  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:17.796  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:24:17.796  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:17.798  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:17.798  3271  3327 I jxcore-log: 
,03-29 16:24:17.800  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:17.800  3271  3327 I jxcore-log: 
,03-29 16:24:17.808  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 45837, start advertisements: true
,03-29 16:24:17.809  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:17.809  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:17.809  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:17.815  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:24:17.815  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 16:24:17.815  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 16:24:17.815  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:17.815  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:17.816  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 16:24:17.817  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:17.817  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 16:24:17.824  2160  2180 D BtGatt.GattService: registerClient() - UUID=f4a6b418-f602-4e54-b4bb-2b04a272cb20
,03-29 16:24:17.824  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=f4a6b418-f602-4e54-b4bb-2b04a272cb20, clientIf=6
03-29 16:24:17.825  3271  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:17.827  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:17.833  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:17.837  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:24:17.841  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:24:17.842  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 16:24:17.843  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:17.844  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 16:24:17.844  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 16:24:17.846  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 16:24:17.847  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 16:24:17.847  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:17.848   823  1439 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:17.857  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:17.857  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:24:17.858  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:17.858  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:17.858  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 16:24:17.860  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 16:24:17.861  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 16:24:17.861  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:17.861  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:24:17.862  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 16:24:17.862  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:17.863  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 16:24:17.864  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
03-29 16:24:17.864   823  3113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:17.866  3271  3940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 16:24:17.871  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 16:24:17.871  3271  3327 I jxcore-log: 
03-29 16:24:17.871  3271  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 16:24:17.882  3271  3327 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 16:24:17.882  3271  3327 I jxcore-log: 
,03-29 16:24:17.885  3271  3327 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 16:24:17.885  3271  3327 I jxcore-log: 
,03-29 16:24:17.887  3271  3327 I jxcore-log: DEBUG createNativeListener: new mux
03-29 16:24:17.887  3271  3327 I jxcore-log: 
,03-29 16:24:17.891  3271  3327 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-29 16:24:17.891  3271  3327 I jxcore-log: 
,03-29 16:24:17.912  3271  3327 I jxcore-log: ok 201 connection to router server should succeed after starting
03-29 16:24:17.912  3271  3327 I jxcore-log: 
,03-29 16:24:17.914  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:17.914  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:17.914  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 16:24:17.914  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 16:24:17.914  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 16:24:17.915  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 16:24:17.915  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:17.915  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:17.915  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:17.915  3271  3940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-29 16:24:17.915  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:17.915  3271  3940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:24:17.915  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:17.915  3271  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 16:24:17.915  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:17.918  2160  2982 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:17.919  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 16:24:17.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:17.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:17.919  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:17.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 16:24:17.919  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:17.919  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:17.919  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 16:24:17.921  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:17.922  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 16:24:17.922  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:17.922  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 16:24:17.922  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:17.925  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 16:24:17.925  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:17.925  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 16:24:17.927  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 16:24:17.927  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:24:17.928  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 16:24:17.928  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:17.928  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:17.929  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 16:24:17.929  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:24:17.929  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:17.929  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:17.933  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:24:17.934  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:17.934  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:17.934  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 16:24:17.935  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-29 16:24:17.935  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-29 16:24:17.935  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-29 16:24:17.935  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:17.935  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:24:17.939  3271  3327 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 16:24:17.939  3271  3327 I jxcore-log: 
03-29 16:24:17.942  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:24:17.942   823  1107 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:17.947  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:24:17.947  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:17.947  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:17.951  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 16:24:17.951  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:17.951  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:24:17.951  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:17.951  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-29 16:24:17.951  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:17.951  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-29 16:24:17.952  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:24:17.956  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:17.956  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:17.956  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-29 16:24:17.957  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-29 16:24:17.957  3271  3327 I jxcore-log: 
03-29 16:24:17.958  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:17.958  3271  3327 I jxcore-log: 
,03-29 16:24:17.959  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-29 16:24:17.959  3271  3327 I jxcore-log: 
,03-29 16:24:17.964  3271  3327 I jxcore-log: ok 202 is stopped after calling stop
,03-29 16:24:17.964  3271  3327 I jxcore-log: 
,03-29 16:24:17.969  3271  3327 I jxcore-log: ok 203 connection to servers manager should fail after stopping
,03-29 16:24:17.969  3271  3327 I jxcore-log: 
,03-29 16:24:17.973  3271  3327 I jxcore-log: ok 204 connection to router server should fail after stopping
03-29 16:24:17.973  3271  3327 I jxcore-log: 
,03-29 16:24:17.977  3271  3327 I jxcore-log: # teardown
03-29 16:24:17.977  3271  3327 I jxcore-log: 
,03-29 16:24:18.272  3271  3327 I jxcore-log: ok 205 must be stopped
,03-29 16:24:18.272  3271  3327 I jxcore-log: 
,03-29 16:24:18.277  3271  3327 I jxcore-log: # setup,
03-29 16:24:18.277  3271  3327 I jxcore-log: 
,03-29 16:24:18.670  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-29 16:24:18.670  3271  3327 I jxcore-log: 
,03-29 16:24:18.674  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-29 16:24:18.674  3271  3327 I jxcore-log: 
,03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:18.683  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:18.687  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:18.689  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:18.689  3271  3327 I jxcore-log: 
,03-29 16:24:18.690  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:18.690  3271  3327 I jxcore-log: 
,03-29 16:24:18.693  3271  3327 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-29 16:24:18.693  3271  3327 I jxcore-log: 
,03-29 16:24:18.695  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:18.695  3271  3327 I jxcore-log: 
,03-29 16:24:19.519  3271  3327 I jxcore-log: ok 206 called with right arguments
03-29 16:24:19.519  3271  3327 I jxcore-log: 
03-29 16:24:19.521  3271  3327 I jxcore-log: # teardown
03-29 16:24:19.521  3271  3327 I jxcore-log: 
,03-29 16:24:19.625  3271  3327 I jxcore-log: ok 207 must be stopped
03-29 16:24:19.625  3271  3327 I jxcore-log: 
03-29 16:24:19.631  3271  3327 I jxcore-log: # setup
03-29 16:24:19.631  3271  3327 I jxcore-log: 
,03-29 16:24:19.844  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:19.844  3271  3327 I jxcore-log: 
,03-29 16:24:19.849  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:19.849  3271  3327 I jxcore-log: 
,03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:19.861  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:19.866  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:19.870  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:19.870  3271  3327 I jxcore-log: 
,03-29 16:24:19.873  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:19.873  3271  3327 I jxcore-log: 
,03-29 16:24:19.880  3271  3327 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-29 16:24:19.880  3271  3327 I jxcore-log: 
,03-29 16:24:19.884  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:19.884  3271  3327 I jxcore-log: 
,03-29 16:24:20.089  3271  3327 I jxcore-log: ok 208 called with right arguments
,03-29 16:24:20.089  3271  3327 I jxcore-log: 
03-29 16:24:20.091  3271  3327 I jxcore-log: # teardown
03-29 16:24:20.091  3271  3327 I jxcore-log: 
,03-29 16:24:20.233  3271  3327 I jxcore-log: ok 209 must be stopped
03-29 16:24:20.233  3271  3327 I jxcore-log: 
,03-29 16:24:20.244  3271  3327 I jxcore-log: # setup
,03-29 16:24:20.244  3271  3327 I jxcore-log: 
,03-29 16:24:20.368  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:20.368  3271  3327 I jxcore-log: 
,03-29 16:24:20.373  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:20.373  3271  3327 I jxcore-log: 
,03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:20.387  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:20.393  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:20.397  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:20.397  3271  3327 I jxcore-log: 
,03-29 16:24:20.401  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:20.401  3271  3327 I jxcore-log: 
,03-29 16:24:20.409  3271  3327 I jxcore-log: # 53. make sure we actually call kill connections properly
03-29 16:24:20.409  3271  3327 I jxcore-log: 
,03-29 16:24:20.414  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:20.414  3271  3327 I jxcore-log: 
,03-29 16:24:20.577  3271  3327 I jxcore-log: ok 210 specific error expected
03-29 16:24:20.577  3271  3327 I jxcore-log: 
,03-29 16:24:20.580  3271  3327 I jxcore-log: # teardown
03-29 16:24:20.580  3271  3327 I jxcore-log: 
,03-29 16:24:20.768  3271  3327 I jxcore-log: ok 211 must be stopped
03-29 16:24:20.768  3271  3327 I jxcore-log: 
,03-29 16:24:20.774  3271  3327 I jxcore-log: # setup
03-29 16:24:20.774  3271  3327 I jxcore-log: 
,03-29 16:24:20.878  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:20.878  3271  3327 I jxcore-log: 
,03-29 16:24:20.883  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:20.883  3271  3327 I jxcore-log: 
,03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:20.897  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:20.902  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:20.907  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-29 16:24:20.907  3271  3327 I jxcore-log: 
,03-29 16:24:20.911  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:20.911  3271  3327 I jxcore-log: ,
,03-29 16:24:20.920  3271  3327 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-29 16:24:20.920  3271  3327 I jxcore-log: 
,03-29 16:24:20.924  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:20.924  3271  3327 I jxcore-log: 
,03-29 16:24:21.112  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:21.112  3271  3327 I jxcore-log: 
,03-29 16:24:21.115  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 49179
03-29 16:24:21.115  3271  3327 I jxcore-log: 
,03-29 16:24:21.121  3271  3327 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":60992,"error":{}}
03-29 16:24:21.121  3271  3327 I jxcore-log: 
,03-29 16:24:21.122  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 16:24:21.122  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:21.122  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 16:24:21.124  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:21.124  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 16:24:21.124  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.135  3271  3327 I jxcore-log: ok 212 failure reason is as expected
03-29 16:24:21.135  3271  3327 I jxcore-log: 
,03-29 16:24:21.135  3271  3327 I jxcore-log: ok 213 error description is as expected
03-29 16:24:21.135  3271  3327 I jxcore-log: 
03-29 16:24:21.136  3271  3327 I jxcore-log: ok 214 must be stopped
03-29 16:24:21.136  3271  3327 I jxcore-log: 
,03-29 16:24:21.142  3271  3327 I jxcore-log: # teardown
03-29 16:24:21.142  3271  3327 I jxcore-log: 
,03-29 16:24:21.323  3271  3327 I jxcore-log: ok 215 must be stopped
03-29 16:24:21.323  3271  3327 I jxcore-log: 
,03-29 16:24:21.326  3271  3327 I jxcore-log: # setup
03-29 16:24:21.326  3271  3327 I jxcore-log: 
,03-29 16:24:21.512  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:21.512  3271  3327 I jxcore-log: 
,03-29 16:24:21.517  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:21.517  3271  3327 I jxcore-log: 
,03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:21.530  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:21.536  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:21.539  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:21.539  3271  3327 I jxcore-log: 
,03-29 16:24:21.543  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:21.543  3271  3327 I jxcore-log: 
,03-29 16:24:21.549  3271  3327 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-29 16:24:21.549  3271  3327 I jxcore-log: 
,03-29 16:24:21.553  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:24:21.553  3271  3327 I jxcore-log: 
,03-29 16:24:21.693  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:21.693  3271  3327 I jxcore-log: 
03-29 16:24:21.695  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 52540
03-29 16:24:21.695  3271  3327 I jxcore-log: 
03-29 16:24:21.698  3271  3327 I jxcore-log: ok 216 peerIdentifier matches
03-29 16:24:21.698  3271  3327 I jxcore-log: 
03-29 16:24:21.699  3271  3327 I jxcore-log: ok 217 error description matches
03-29 16:24:21.699  3271  3327 I jxcore-log: 
03-29 16:24:21.702  3271  3327 I jxcore-log: # teardown
03-29 16:24:21.702  3271  3327 I jxcore-log: 
,03-29 16:24:21.894  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:24:21.895  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:21.895  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.898  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:21.898  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:21.898  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:21.906  3271  3327 I jxcore-log: ok 218 must be stopped
03-29 16:24:21.906  3271  3327 I jxcore-log: 
,03-29 16:24:21.912  3271  3327 I jxcore-log: # setup
03-29 16:24:21.912  3271  3327 I jxcore-log: 
,03-29 16:24:21.990  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:24:21.990  3271  3327 I jxcore-log: 
,03-29 16:24:21.995  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:24:21.995  3271  3327 I jxcore-log: 
,03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:24:22.007  3271  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:24:22.011  3271  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:24:22.013  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:24:22.013  3271  3327 I jxcore-log: 
03-29 16:24:22.016  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:24:22.016  3271  3327 I jxcore-log: 
,03-29 16:24:22.034  3271  3327 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate,
03-29 16:24:22.034  3271  3327 I jxcore-log: 
,03-29 16:24:22.037  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-29 16:24:22.037  3271  3327 I jxcore-log: 
,03-29 16:24:22.212  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server,
03-29 16:24:22.212  3271  3327 I jxcore-log: 
,03-29 16:24:22.214  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 48860
03-29 16:24:22.214  3271  3327 I jxcore-log: 
,03-29 16:24:22.220  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 45837, start advertisements: false
03-29 16:24:22.220  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 16:24:22.220  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:22.220  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 16:24:22.226  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 16:24:22.226  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 16:24:22.226  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:22.231  2160  2179 D BtGatt.GattService: registerClient() - UUID=013c8299-e9b5-431e-b022-2f73b825438e
,03-29 16:24:22.232  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=013c8299-e9b5-431e-b022-2f73b825438e, clientIf=5
03-29 16:24:22.232  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 16:24:22.234  2160  2982 D BtGatt.GattService: start scan with filters
,03-29 16:24:22.235  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 16:24:22.235  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:22.235  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 16:24:22.235  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:22.235  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.235  2160  2233 D BtGatt.ScanManager: handling starting scan
03-29 16:24:22.236  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:22.236  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.236   823  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:22.240  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:22.240  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 16:24:22.240  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:22.240  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 16:24:22.240  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:22.240  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:22.242  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.242  3271  3327 I jxcore-log: 
03-29 16:24:22.244  3271  3327 I jxcore-log: ok 219 discoveryActive matches
03-29 16:24:22.244  3271  3327 I jxcore-log: 
,03-29 16:24:22.244  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:24:22.244  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.245  3271  3327 I jxcore-log: ok 220 advertisingActive matches
03-29 16:24:22.245  3271  3327 I jxcore-log: 
,03-29 16:24:22.246  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:24:22.246  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.247  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.247  3271  3327 I jxcore-log: 
03-29 16:24:22.247  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:22.247  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 16:24:22.249  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:24:22.249  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:22.249  3271  3327 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 16:24:22.249  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:22.249  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 16:24:22.249  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:22.249  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:22.249  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 16:24:22.249  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:22.250  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:22.250  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.252  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 16:24:22.252  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:22.253  2160  2179 D BtGatt.GattService: stopScan() - queue size =1
03-29 16:24:22.254  2160  2982 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:22.255  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 16:24:22.255  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:22.255  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:22.255  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 16:24:22.255  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-29 16:24:22.255  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:22.256  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:22.256  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:22.256  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:22.257  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:22.258  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:22.258  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 16:24:22.258  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.258  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 16:24:22.258  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:22.258  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 16:24:22.264  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:22.267  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 16:24:22.267  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 16:24:22.267  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:24:22.269  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-29 16:24:22.269  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.270  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:24:22.271   823  1421 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:22.279  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 16:24:22.280  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-29 16:24:22.280  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:22.283  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-29 16:24:22.283  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:22.283  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 16:24:22.284  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-29 16:24:22.285  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:22.285  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:22.285  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-29 16:24:22.286  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.286  3271  3327 I jxcore-log: 
03-29 16:24:22.287  3271  3327 I jxcore-log: ok 221 discoveryActive matches
,03-29 16:24:22.287  3271  3327 I jxcore-log: 
03-29 16:24:22.287  3271  3327 I jxcore-log: ok 222 advertisingActive matches
03-29 16:24:22.287  3271  3327 I jxcore-log: 
,03-29 16:24:22.289  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.289  3271  3327 I jxcore-log: 
,03-29 16:24:22.302  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 16:24:22.302  3271  3327 I jxcore-log: 
,03-29 16:24:22.304  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 56925
03-29 16:24:22.304  3271  3327 I jxcore-log: 
,03-29 16:24:22.309  3271  3327 I io.jxcore.node.ConnectionHelper: start: Port number: 56925, start advertisements: true
,03-29 16:24:22.309  3271  3327 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 16:24:22.309  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:22.309  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 16:24:22.312  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 16:24:22.312  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 16:24:22.312  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 16:24:22.313  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 16:24:22.317  2160  2180 D BtGatt.GattService: registerClient() - UUID=7522759c-2830-41c0-92d4-d4eddceaf5df
,03-29 16:24:22.317  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=7522759c-2830-41c0-92d4-d4eddceaf5df, clientIf=5
03-29 16:24:22.317  3271  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 16:24:22.318  2160  2981 D BtGatt.GattService: start scan with filters
03-29 16:24:22.319  2160  2233 D BtGatt.ScanManager: handling starting scan
,03-29 16:24:22.320  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 16:24:22.320  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 16:24:22.321  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 16:24:22.321  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 16:24:22.322  2160  2223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 16:24:22.322  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:22.323  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 16:24:22.323  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 16:24:22.324  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 16:24:22.324  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.324  2160  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-29 16:24:22.324  2160  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 16:24:22.324  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 16:24:22.325  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 16:24:22.325  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 16:24:22.325  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:22.326  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 16:24:22.326  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 16:24:22.326  2160  2223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 16:24:22.326  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:22.328  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 16:24:22.328  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 16:24:22.332  2160  2981 D BtGatt.GattService: registerClient() - UUID=6b512615-7724-4983-8300-f2b4299cdb86
03-29 16:24:22.332  2160  2223 D BtGatt.GattService: onClientRegistered() - UUID=6b512615-7724-4983-8300-f2b4299cdb86, clientIf=6
,03-29 16:24:22.332  3271  3288 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 16:24:22.334  2160  2232 D BtGatt.AdvertiseManager: message : 0
,03-29 16:24:22.337  2160  2232 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 16:24:22.340  2160  2223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 16:24:22.343  2160  2223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 16:24:22.344  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 16:24:22.344  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 16:24:22.344   823  1378 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:22.348  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 16:24:22.348  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 16:24:22.348  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 16:24:22.348  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:22.349  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 16:24:22.349  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 16:24:22.349  3271  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 16:24:22.349  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 16:24:22.350  3271  3327 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 16:24:22.350  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 16:24:22.350  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 16:24:22.350  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-29 16:24:22.350  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 16:24:22.350  3271  3271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 16:24:22.350  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 16:24:22.351  3271  3271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:22.351  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 16:24:22.351  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 16:24:22.351  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:22.351  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 16:24:22.351   823  1342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:22.351  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 16:24:22.352  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.352  3271  3327 I jxcore-log: 
03-29 16:24:22.353  3271  3942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 16:24:22.361  3271  3327 I jxcore-log: not ok 223 discoveryActive matches
03-29 16:24:22.361  3271  3327 I jxcore-log: 
03-29 16:24:22.361  3271  3327 I jxcore-log:   ---
03-29 16:24:22.361  3271  3327 I jxcore-log: 
03-29 16:24:22.361  3271  3327 I jxcore-log:     operator: equal
03-29 16:24:22.361  3271  3327 I jxcore-log: 
03-29 16:24:22.361  3271  3327 I jxcore-log:     expected: false
03-29 16:24:22.361  3271  3327 I jxcore-log: 
,03-29 16:24:22.361  3271  3327 I jxcore-log:     actual:   true
03-29 16:24:22.361  3271  3327 I jxcore-log: 
03-29 16:24:22.361  3271  3327 I jxcore-log:   ...
03-29 16:24:22.361  3271  3327 I jxcore-log: 
03-29 16:24:22.363  3271  3942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 16:24:22.365  3271  3327 I jxcore-log: not ok 224 advertisingActive matches
03-29 16:24:22.365  3271  3327 I jxcore-log: 
,03-29 16:24:22.366  3271  3327 I jxcore-log:   ---
03-29 16:24:22.366  3271  3327 I jxcore-log: 
,03-29 16:24:22.366  3271  3327 I jxcore-log:     operator: equal
03-29 16:24:22.366  3271  3327 I jxcore-log: 
03-29 16:24:22.366  3271  3327 I jxcore-log:     expected: true
03-29 16:24:22.366  3271  3327 I jxcore-log: 
,03-29 16:24:22.366  3271  3327 I jxcore-log:     actual:   false
03-29 16:24:22.366  3271  3327 I jxcore-log: 
,03-29 16:24:22.366  3271  3327 I jxcore-log:   ...
03-29 16:24:22.366  3271  3327 I jxcore-log: 
03-29 16:24:22.368  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 16:24:22.368  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 16:24:22.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 16:24:22.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 16:24:22.368  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 16:24:22.368  3271  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-29 16:24:22.368  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 16:24:22.368  3271  3942 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 16:24:22.368  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 16:24:22.368  3271  3942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 16:24:22.368  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 16:24:22.368  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 16:24:22.368  3271  3942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 16:24:22.369  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 16:24:22.369  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 16:24:22.371  2160  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-29 16:24:22.372  2160  2981 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 16:24:22.372  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 16:24:22.372  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:22.372  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 16:24:22.372  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 16:24:22.372  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 16:24:22.372  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 16:24:22.372  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 16:24:22.375  2160  2223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 16:24:22.375  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.375  2160  2232 D BtGatt.AdvertiseManager: message : 1
03-29 16:24:22.376  2160  2232 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 16:24:22.377  2160  2233 D BtGatt.ScanManager: stopping BLe Batch
03-29 16:24:22.380  2160  2223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 16:24:22.380  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.380  2160  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 16:24:22.381  2160  2223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 16:24:22.381  2160  2223 D BtGatt.GattService: Client app is not null!
03-29 16:24:22.384  2160  2223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 16:24:22.384  2160  2223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 16:24:22.384  2160  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 16:24:22.384  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 16:24:22.384  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 16:24:22.385  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 16:24:22.385  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 16:24:22.385  3271  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 16:24:22.385  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 16:24:22.385  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 16:24:22.385  3271  3327 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 16:24:22.389  3271  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 16:24:22.389  3271  3327 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:22.389  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-29 16:24:22.389  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:24:22.389  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 16:24:22.393  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 16:24:22.393  3271  3327 I jxcore-log: 
,03-29 16:24:22.396  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-29 16:24:22.396  3271  3327 I jxcore-log: 
03-29 16:24:22.397  3271  3271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 16:24:22.397   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:24:22.400  3271  3327 I jxcore-log: not ok 225 discoveryActive matches,
03-29 16:24:22.400  3271  3327 I jxcore-log: 
03-29 16:24:22.401  3271  3327 I jxcore-log:   ---
,03-29 16:24:22.401  3271  3327 I jxcore-log: 
,03-29 16:24:22.403  3271  3327 I jxcore-log:     operator: equal
03-29 16:24:22.403  3271  3327 I jxcore-log: 
,03-29 16:24:22.403  3271  3327 I jxcore-log:     expected: false,
03-29 16:24:22.403  3271  3327 I jxcore-log: 
,03-29 16:24:22.404  3271  3327 I jxcore-log:     actual:   true
03-29 16:24:22.404  3271  3327 I jxcore-log: 
03-29 16:24:22.404  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-29 16:24:22.404  3271  3327 I jxcore-log:   ...
03-29 16:24:22.404  3271  3327 I jxcore-log: 
03-29 16:24:22.405  3271  3271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 16:24:22.405  3271  3271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 16:24:22.409  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-29 16:24:22.409  3271  3271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 16:24:22.409  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 16:24:22.409  3271  3271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 16:24:22.409  3271  3271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 16:24:22.409  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 16:24:22.410  3271  3271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 16:24:22.410  3271  3271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 16:24:22.411  3271  3327 I jxcore-log: not ok 226 advertisingActive matches
03-29 16:24:22.411  3271  3327 I jxcore-log: 
03-29 16:24:22.411  3271  3327 I jxcore-log:   ---
03-29 16:24:22.411  3271  3327 I jxcore-log: 
,03-29 16:24:22.412  3271  3327 I jxcore-log:     operator: equal,
03-29 16:24:22.412  3271  3327 I jxcore-log: 
03-29 16:24:22.412  3271  3327 I jxcore-log:     expected: false
03-29 16:24:22.412  3271  3327 I jxcore-log: 
,03-29 16:24:22.412  3271  3327 I jxcore-log:     actual:   true,
03-29 16:24:22.412  3271  3327 I jxcore-log: 
03-29 16:24:22.412  3271  3327 I jxcore-log:   ...
03-29 16:24:22.412  3271  3327 I jxcore-log: 
,03-29 16:24:22.415  3271  3327 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 16:24:22.415  3271  3327 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 16:24:22.415  3271  3327 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 16:24:22.417  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 16:24:22.417  3271  3327 I jxcore-log: 
03-29 16:24:22.418  3271  3327 I jxcore-log: ok 227 discoveryActive matches,
03-29 16:24:22.418  3271  3327 I jxcore-log: 
03-29 16:24:22.424  3271  3327 I jxcore-log: not ok 228 advertisingActive matches
03-29 16:24:22.424  3271  3327 I jxcore-log: 
03-29 16:24:22.424  3271  3327 I jxcore-log:   ---
03-29 16:24:22.424  3271  3327 I jxcore-log: ,
03-29 16:24:22.424  3271  3327 I jxcore-log:     operator: equal
03-29 16:24:22.424  3271  3327 I jxcore-log: 
03-29 16:24:22.424  3271  3327 I jxcore-log:     expected: false
,03-29 16:24:22.424  3271  3327 I jxcore-log: 
03-29 16:24:22.424  3271  3327 I jxcore-log:     actual:   true
03-29 16:24:22.424  3271  3327 I jxcore-log: 
,03-29 16:24:22.424  3271  3327 I jxcore-log:   ...
03-29 16:24:22.424  3271  3327 I jxcore-log: 
,03-29 16:24:22.426  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 16:24:22.426  3271  3327 I jxcore-log: 
03-29 16:24:22.427  3271  3327 I jxcore-log: ok 229 discoveryActive matches
03-29 16:24:22.427  3271  3327 I jxcore-log: 
,03-29 16:24:22.428  3271  3327 I jxcore-log: ok 230 advertisingActive matches
03-29 16:24:22.428  3271  3327 I jxcore-log: 
03-29 16:24:22.429  3271  3327 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 16:24:22.429  3271  3327 I jxcore-log: ,
,03-29 16:24:22.441  3271  3327 I jxcore-log: DEBUG createNativeListener: creating native server,
03-29 16:24:22.441  3271  3327 I jxcore-log: 
,03-29 16:24:22.443  3271  3327 I jxcore-log: DEBUG createNativeListener: listening 56181,
03-29 16:24:22.443  3271  3327 I jxcore-log: 
,03-29 16:24:22.451  3271  3327 I jxcore-log: Uncaught Promise Rejection: {},
03-29 16:24:22.451  3271  3327 I jxcore-log: 
,03-29 16:24:22.454  3271  3327 E jxcore-log: Trace: [Error: Call Stop!]
03-29 16:24:22.454  3271  3327 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-29 16:24:22.454  3271  3327 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-29 16:24:22.454  3271  3327 E jxcore-log:     at emit@events.js:98:1
,03-29 16:24:22.454  3271  3327 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-29 16:24:22.454  3271  3327 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-29 16:24:22.454  3271  3327 E jxcore-log:     at $0a@node.js:917:1
03-29 16:24:22.454  3271  3327 E jxcore-log: 
03-29 16:24:22.455  3271  3327 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-29 16:24:22.455  3271  3327 I jxcore-log: 
03-29 16:24:22.457  3271  3327 I jxcore-log: # teardown
03-29 16:24:22.457  3271  3327 I jxcore-log: 
,03-29 16:24:22.748  3943  3943 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-29 16:24:22.751  3943  3943 D AndroidRuntime: CheckJNI is OFF
,03-29 16:24:22.867  3943  3943 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-29 16:24:22.882   823   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-29 16:24:22.883   823   854 I ActivityManager: Killing 3271:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-29 16:24:22.998   823   864 W PackageSettings: Skipping PackageSetting{14eb727b com.example.hello/10273} due to missing metadata
,03-29 16:24:23.015   823  3113 I WindowState: WIN DEATH: Window{357e25a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-29 16:24:23.016   823  1034 D WifiService: Client connection lost with reason: 4
,03-29 16:24:23.100   823   854 W ActivityManager: Force removing ActivityRecord{3b7d948c u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-29 16:24:23.115   823   823 V ActivityManager: Display changed displayId=0
,03-29 16:24:23.126   823  1379 W ActivityManager: Spurious death for ProcessRecord{7910b5e 3271:com.test.thalitest/u0a95}, curProc for 3271: null
03-29 16:24:23.126   823   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-29 16:24:23.151   823  1053 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
03-29 16:24:23.156  2987  2987 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-29 16:24:23.156  1241  1241 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-29 16:24:23.161  1241  3957 I Keyboard.Facilitator.DecoderInitializer: run()
03-29 16:24:23.165   823  1011 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-29 16:24:23.176  1241  3957 I Decoder : createOrResetDecoder
,03-29 16:24:23.195  1073  1073 I art     : Explicit concurrent mark sweep GC freed 50561(2MB) AllocSpace objects, 1(30MB) LOS objects, 20% free, 61MB/77MB, paused 925us total 48.142ms
,03-29 16:24:23.217   823  1379 I ActivityManager: Start proc 3959:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-29 16:24:23.220  1406  1406 I ConfigService: onCreate
,03-29 16:24:23.241   823  1159 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3271 uid 10095
,03-29 16:24:23.244   823   823 I art     : Explicit concurrent mark sweep GC freed 17660(1298KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 1.765ms total 98.554ms
,03-29 16:24:23.248   823   864 I art     : WaitForGcToComplete blocked for 27.674ms for cause Explicit
,03-29 16:24:23.256  1241  1241 I Keyboard.Facilitator: onFinishInput()
,03-29 16:24:23.270  1241  3957 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-29 16:24:23.308  1241  3957 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-29 16:24:23.309  1353  1353 I art     : Explicit concurrent mark sweep GC freed 4993(364KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 1.359ms total 24.218ms
03-29 16:24:23.309  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-29 16:24:23.309  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-29 16:24:23.319  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-29 16:24:23.319  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-29 16:24:23.319  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-29 16:24:23.319  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-29 16:24:23.322  1241  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-29 16:24:23.322  1241  3957 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-29 16:24:23.322  1241  3957 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-29 16:24:23.322  1241  3957 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-29 16:24:23.322  1241  3957 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-29 16:24:23.322  1241  3957 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-29 16:24:23.325   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-29 16:24:23.325   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-29 16:24:23.361   823   864 I art     : Explicit concurrent mark sweep GC freed 8184(808KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.750ms total 112.986ms
,03-29 16:24:23.405  3959  3988 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-29 16:24:23.406  3959  3991 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-29 16:24:23.420   823  1378 I ActivityManager: Start proc 3993:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-29 16:24:23.438  3943  3943 I art     : System.exit called, status: 0
03-29 16:24:23.438  3943  3943 I AndroidRuntime: VM exiting with result code 0.
,03-29 16:24:23.449  3876  3876 W LocationOracleImpl: Best location was null
,03-29 16:24:23.463  3876  3876 I VS.Container: create_recognizer
,03-29 16:24:23.473   823   864 I ActivityManager: Start proc 4017:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-29 16:24:23.507   823  1342 I ActivityManager: Start proc 4038:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-29 16:24:23.512   823  1379 I ActivityManager: Killing 3639:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-29 16:24:23.519  1353  1353 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-29 16:24:23.520  1353  1353 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-29 16:24:23.540  3876  4059 I HotwordRecognitionRnr: Starting hotword detection.
,03-29 16:24:23.543  3876  4060 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@59c75ba
,03-29 16:24:23.544   358  4062 I AudioFlinger: AudioFlinger's thread 0xb4d4e000 ready to run
,03-29 16:24:23.547   358  1026 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-29 16:24:23.548  3876  4060 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@59c75ba
,03-29 16:24:23.558   358  4062 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-29 16:24:23.558   358  4062 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,03-29 16:24:23.558   358  4062 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-29 16:24:23.558   358  4062 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-29 16:24:23.565   358  4062 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-29 16:24:23.634   823  1379 I ActivityManager: Killing 3598:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-29 16:24:23.658  4038  4038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-29 16:24:23.776  4038  4063 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-29 16:24:23.776  4038  4063 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
03-29 16:24:23.777  4038  4063 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-29 16:24:23.777  4038  4063 E AndroidRuntime: Process: com.android.keychain, PID: 4038
03-29 16:24:23.777  4038  4063 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 16:24:23.777  4038  4063 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 16:24:23.785  1406  1406 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-29 16:24:23.785   823  4065 E DropBoxManagerService: Can't write: system_app_crash
03-29 16:24:23.785   823  4065 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 16:24:23.785   823  4065 E DropBoxManagerService: 	... 5 more
03-29 16:24:23.786  1406  1406 D AndroidRuntime: Shutting down VM
03-29 16:24:23.786  1406  1406 E AndroidRuntime: FATAL EXCEPTION: main
03-29 16:24:23.786  1406  1406 E AndroidRuntime: Process: com.google.process.gapps, PID: 1406
03-29 16:24:23.786  1406  1406 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-29 16:24:23.786  1406  1406 E AndroidRuntime: 	... 9 more
,03-29 16:24:23.801   823  4066 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 16:24:23.802   823   854 D Atlas   : Validating map...
,03-29 16:24:23.810   823  4067 E DropBoxManagerService: Can't write: system_app_crash
03-29 16:24:23.810   823  4067 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 16:24:23.810   823  4067 E DropBoxManagerService: 	... 5 more
,03-29 16:24:23.869   823  4066 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 16:24:23.876   823  4066 D OpenGLRenderer: Enabling debug mode 0
,03-29 16:24:23.924  3876  3876 I HotwordWorker: onReady
,03-29 16:24:23.943  3876  4075 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-29 16:24:23.949  1780  1907 W Icing   : Received bad json for section weights override -- ignoring.
03-29 16:24:23.949  1780  1907 W Icing   : Received bad json for corpus context scoring override -- ignoring.
03-29 16:24:23.949  1780  1907 W Icing   : Received bad json for section weights override -- ignoring.
03-29 16:24:23.949  1780  1907 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-29 16:24:23.952  3876  4013 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-29 16:24:23.953  3876  4013 E FileBytesWriter: Failed to write new file: loracle.new
,03-29 16:24:23.961  3876  4077 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-29 16:24:23.974  3876  4013 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-29 16:24:23.974  3876  4013 E FileBytesWriter: Failed to write new file: loracle.new
,03-29 16:24:23.986   823   838 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29cf03bb}
,03-29 16:24:23.988   823  1033 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-29 16:24:24.064  3876  3876 I HotwordDetector: Closing mic
03-29 16:24:24.064  3876  4037 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@59c75ba
,03-29 16:24:24.081  3876  4080 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-29 16:24:24.086  3876  3876 W TRUiThreadExecutor: Task does not implement UiTask: com.google.common.g.a.p@2ce9cee9
,03-29 16:24:24.115   358  4062 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-29 16:24:24.116   358  4062 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-29 16:24:24.119   358  1026 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-29 16:24:24.121  3876  4056 I HotwordRecognitionRnr: Stopping hotword detection.
,03-29 16:24:24.121  3876  4059 I HotwordRecognitionRnr: Hotword detection finished
,03-29 16:24:24.367  1241  3957 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp,
,03-29 16:24:24.367  1241  3957 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-29 16:24:24.394  1241  3957 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-29 16:24:24.394  1241  3957 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-29 16:24:24.445  1241  3957 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-29 16:24:24.445  1241  3957 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-29 16:24:24.446  1241  3957 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-29 16:24:24.446  1241  3957 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-29 16:24:25.532   823  1419 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29cf03bb}
,03-29 16:24:25.989  1780  1826 W Icing   : Usage reports not received in time.
,03-29 16:24:28.034  1780  1826 W Icing   : Usage reports not received in time.
,03-29 16:24:28.050   823  1421 I ActivityManager: Killing 3162:com.google.android.talk/u0a61 (adj 15): empty #17
,03-29 16:24:28.507  3876  4087 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-29 16:24:34.085   823  1261 E QMI_FW  : xport_send: Sendto failed for port 3840
03-29 16:24:34.085   823  1261 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-29 16:24:34.086   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660212499
03-29 16:24:34.086   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-29 16:24:34.092   260   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-29 16:24:34.093   870   870 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
03-29 16:24:34.093   870   870 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
,03-29 16:24:34.095   870   870 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-29 16:24:34.095   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock

```
