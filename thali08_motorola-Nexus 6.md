#### Test 648099369ce4518_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-31 18:06:06.038  1376  1376 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 18:06:06.141  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 18:06:06.141  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:06.141  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:06.141  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 18:06:06.149  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 18:06:06.171  2730  2730 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 18:06:06.172  2730  2730 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 18:06:06.172  2730  2730 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
03-31 18:06:06.405  3249  3249 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 18:06:06.408  3249  3249 D AndroidRuntime: CheckJNI is OFF
03-31 18:06:06.531  3249  3249 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 18:06:06.535   828   843 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 18:06:06.542   828   843 V WindowManager: addAppToken: AppWindowToken{135e4065 token=Token{14c0c55c ActivityRecord{92cf7cf u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-31 18:06:06.548   828   861 V WindowManager: Adding window Window{2a4e63f4 u0 Starting com.test.thalitest} at 2 of 7 (after Window{25e3ec83 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 18:06:06.557  3249  3249 D AndroidRuntime: Shutting down VM
03-31 18:06:06.558  1532  1800 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@fe6774f
03-31 18:06:06.558  1532  1532 I HotwordDetector: Closing mic
03-31 18:06:06.612   828  1306 I ActivityManager: Start proc 3264:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-31 18:06:06.622   356  1806 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 18:06:06.623   356  1806 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 18:06:06.631   356  1030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 18:06:06.633  1532  1802 I HotwordRecognitionRnr: Stopping hotword detection.
03-31 18:06:06.633  1532  1803 I HotwordRecognitionRnr: Hotword detection finished
03-31 18:06:06.683   828  1403 I ActivityManager: Killing 2932:com.google.android.partnersetup/u0a16 (adj 15): empty #17
03-31 18:06:06.723   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660564755
03-31 18:06:06.723   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 18:06:06.809   872   872 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 18:06:06.810   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 18:06:06.851   872   872 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-31 18:06:06.852   872   872 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-31 18:06:06.892   828  1403 I ActivityManager: Killing 2859:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-31 18:06:07.206  3264  3264 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 18:06:07.240  3264  3264 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4522-4525)
,03-31 18:06:07.241  3264  3264 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 18:06:07.257  3264  3264 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dc505a6}
,03-31 18:06:07.258  3264  3264 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 18:06:07.258  3264  3264 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 18:06:07.274  3264  3264 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,03-31 18:06:07.275  3264  3264 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 18:06:07.277  3264  3264 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 18:06:07.287  3264  3290 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-31 18:06:07.296  3264  3264 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 18:06:07.302  3264  3264 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
03-31 18:06:07.302  3264  3264 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 18:06:07.302  3264  3264 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 18:06:07.344   828   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...,
,03-31 18:06:07.383   828   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 18:06:07.404   828   860 D BluetoothManagerService: Message: 20
,03-31 18:06:07.405   828   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12c7018d:true
,03-31 18:06:07.421   259   285 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (476 us)
,03-31 18:06:07.423  3264  3264 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 18:06:07.431  3264  3264 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 18:06:07.446  3264  3264 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-31 18:06:07.451  3264  3264 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 18:06:07.451  3264  3264 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 18:06:07.503  3264  3313 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 18:06:07.506  3264  3264 D Atlas   : Validating map...
,03-31 18:06:07.510   828  1306 V WindowManager: Adding window Window{181c79c0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2a4e63f4 u0 Starting com.test.thalitest})
,03-31 18:06:07.513  3264  3299 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-31 18:06:07.537  3264  3313 I OpenGLRenderer: Initialized EGL, version 1.4,
,03-31 18:06:07.543  3264  3313 D OpenGLRenderer: Enabling debug mode 0,
,03-31 18:06:07.603   828   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s45ms
,03-31 18:06:07.606  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-31 18:06:07.653  3264  3264 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3264
,03-31 18:06:07.830  3264  3264 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 18:06:07.845   872   872 I kickstart: STATUS: Received file 'm9kefs1'
03-31 18:06:07.846   872   872 I kickstart: STATUS: 950272 bytes transferred in 0.993600 seconds
03-31 18:06:07.846   872   872 I kickstart: STATUS: Successfully downloaded files from target 
03-31 18:06:07.846   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 18:06:07.849   872   872 I kickstart: STATUS: Sahara protocol completed,
,03-31 18:06:07.957   828   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-31 18:06:07.958   828   828 V ActivityManager: Display changed displayId=0
,03-31 18:06:07.963   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-31 18:06:07.963   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-31 18:06:07.971  3264  3316 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1577704704
,03-31 18:06:07.976  3264  3316 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 18:06:07.976  3264  3316 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 18:06:07.976  3264  3316 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 18:06:07.976  3264  3316 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 18:06:07.976  3264  3316 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 18:06:07.976  3264  3316 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a951b63 added. We now have 1 listener(s)
,03-31 18:06:07.977   828  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:06:07.979  3264  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-31 18:06:07.980  3264  3316 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 18:06:07.981  3264  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 18:06:07.981  3264  3316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 18:06:07.984  3264  3316 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e438de added. We now have 1 listener(s)
03-31 18:06:07.984  3264  3316 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 18:06:07.988   828  1011 D WifiService: New client listening to asynchronous messages
,03-31 18:06:07.990  3264  3316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-31 18:06:07.991  3264  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 18:06:07.991  3264  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 18:06:07.991  3264  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 18:06:07.991  3264  3316 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 18:06:07.994  3264  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:06:07.995   828  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:06:07.995  3264  3316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-31 18:06:07.999  3264  3316 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-31 18:06:07.999  3264  3316 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 18:06:07.999  3264  3316 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 18:06:08.000  3264  3264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 18:06:08.000  3264  3316 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 18:06:08.034  3264  3264 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 18:06:08.244   259   314 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-31 18:06:08.247   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-31 18:06:08.248   828  1046 D SurfaceControl: Excessive delay in setPowerMode(): 290ms
,03-31 18:06:08.253   828   863 I DreamManagerService: Entering dreamland.
03-31 18:06:08.254   828   863 I PowerManagerService: Dozing...
,03-31 18:06:08.256   828   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-31 18:06:08.271   356  1032 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-31 18:06:08.272   356  1032 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-31 18:06:08.276   828  1010 E WifiStateMachine: cancelDelayedScan -> 17
,03-31 18:06:08.289   828  1010 E native  : do suspend false
,03-31 18:06:08.322  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-31 18:06:08.327   828  1010 E WifiStateMachine: cancelDelayedScan -> 19
,03-31 18:06:08.339   828  1010 E native  : do suspend true
,03-31 18:06:08.460   356  1031 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-31 18:06:08.460   356  1031 D mot_vr_audio_hw: adev_set_parameters: screen_state=off,
,03-31 18:06:08.490   828  1010 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,03-31 18:06:08.747  3264  3326 W jxcore-log: Initializing JXcore engine
03-31 18:06:08.747  3264  3326 W jxcore-log: JXcore engine is ready
,03-31 18:06:08.777  3326  3326 W Thread-349: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13115]" dev="sockfs" ino=13115 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 18:06:08.777  3326  3326 W Thread-349: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-31 18:06:08.777  3326  3326 W Thread-349: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10585]" dev="sockfs" ino=10585 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 18:06:08.777  3326  3326 W Thread-349: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19158]" dev="sockfs" ino=19158 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-31 18:06:08.796  3264  3326 W jxcore-log: Starting JXcore engine
,03-31 18:06:08.878  3264  3326 W jxcore-log: Platform android
03-31 18:06:08.878  3264  3326 W jxcore-log: 
03-31 18:06:08.878  3264  3326 W jxcore-log: Process ARCH arm
03-31 18:06:08.878  3264  3326 W jxcore-log: 
,03-31 18:06:09.091  3264  3326 I jxcore-log: JXcore Cordova bridge is ready!
03-31 18:06:09.091  3264  3326 I jxcore-log: 
03-31 18:06:09.091  3264  3326 W jxcore-log: JXcore engine is started
,03-31 18:06:09.098  3264  3316 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-31 18:06:09.100  3264  3264 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 18:06:09.490  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending,
03-31 18:06:09.490  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:10.492  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-31 18:06:10.492  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:11.494  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-31 18:06:11.494  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:12.496  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-31 18:06:12.496  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:13.498  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending,
,03-31 18:06:13.498  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:14.500  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending,
03-31 18:06:14.500  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:15.502  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-31 18:06:15.504  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:16.507  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-31 18:06:16.507  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:17.509  1163  1163 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-31 18:06:17.509  1163  1163 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-31 18:06:18.108   828  1010 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,03-31 18:06:18.256  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:06:18.256  3264  3326 I jxcore-log: 
,03-31 18:06:18.258  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:06:18.258  3264  3326 I jxcore-log: 
,03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-31 18:06:18.264  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-31 18:06:18.270  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
03-31 18:06:18.273  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:06:18.273  3264  3326 I jxcore-log: 
,03-31 18:06:18.278  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:06:18.278  3264  3326 I jxcore-log: 
,03-31 18:06:18.814  3264  3326 I jxcore-log: Unit Test app is loaded
03-31 18:06:18.814  3264  3326 I jxcore-log: 
,03-31 18:06:18.820  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,03-31 18:06:18.820  3264  3326 I jxcore-log: 
,03-31 18:06:18.828  3264  3326 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 18:06:18.831  3264  3326 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 18:06:18.831  3264  3326 I jxcore-log: 
,03-31 18:06:18.832  3264  3326 I jxcore-log: My device name is: motorola-Nexus 6
03-31 18:06:18.832  3264  3326 I jxcore-log: 
,03-31 18:06:18.845  3264  3264 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 18:06:19.728  1163  1163 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-31 18:06:20.146  1163  1163 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-31 18:06:20.182  1163  1163 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-31 18:06:20.183  1163  1163 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-31 18:06:20.198   828  1010 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
03-31 18:06:20.199   828  1012 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
03-31 18:06:20.199   828  1010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 18:06:20.203   828  1010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-31 18:06:20.207   352   815 D CommandListener: Setting iface cfg
,03-31 18:06:20.209   828  1010 E WifiStateMachine: Start Dhcp Watchdog 1
,03-31 18:06:20.212   828  1010 E WifiStateMachine:  WifiLinkLayerStats: 
03-31 18:06:20.212   828  1010 E WifiStateMachine:  my bss beacon rx: 1
03-31 18:06:20.212   828  1010 E WifiStateMachine:  RSSI mgmt: -46
03-31 18:06:20.212   828  1010 E WifiStateMachine:  BE :  rx=0 tx=2 lost=0 retries=0
03-31 18:06:20.212   828  1010 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-31 18:06:20.212   828  1010 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-31 18:06:20.212   828  1010 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-31 18:06:20.212   828  1010 E WifiStateMachine:  on_time : 0 tx_time=66 rx_time=110 scan_time=0
,03-31 18:06:20.301   828  1010 E native  : do suspend false
,03-31 18:06:20.312   828  1010 E WifiStateMachine: scanCount==0 - aborting
,03-31 18:06:20.555  3334  3334 I dhcpcd  : version 5.5.6 starting
,03-31 18:06:20.650  3334  3334 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-31 18:06:20.796  3334  3334 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-31 18:06:20.835  3334  3334 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-31 18:06:21.330   828  1010 E native  : do suspend true
,03-31 18:06:21.376   828  1012 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-31 18:06:21.378   828  1010 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,03-31 18:06:21.380   828  1012 D ConnectivityService: Adding iface wlan0 to network 100
,03-31 18:06:21.407   828  1012 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-31 18:06:21.407   828  1012 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
03-31 18:06:21.408   828  1012 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
03-31 18:06:21.409   828  1012 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
03-31 18:06:21.410   828  1012 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-31 18:06:21.417   828  1012 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-31 18:06:21.422   828  1012 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-31 18:06:21.422   828  3332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-31 18:06:21.422   828  3332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-31 18:06:21.422   828  1012 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 18:06:21.423   828  1012 D ConnectivityService:    accepting network in place of null
03-31 18:06:21.423   828  3332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-31 18:06:21.423   828  1012 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
03-31 18:06:21.424   828  3332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-31 18:06:21.424   828  1012 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-31 18:06:21.428   828  1012 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-31 18:06:21.428   828  1012 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-31 18:06:21.428   828  1012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-31 18:06:21.429  1067  1565 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 18:06:21.429   828  1012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-31 18:06:21.435   828   860 D Tethering: MasterInitialState.processMessage what=3
,03-31 18:06:21.441   828  1403 V BackupManagerService: Scheduling immediate backup pass
03-31 18:06:21.442  1287  1556 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-31 18:06:21.442  1287  1556 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-31 18:06:21.445   828   828 V BackupManagerService: Running a backup pass
,03-31 18:06:21.445   828  1044 V BackupManagerService: clearing pending backups
,03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:06:21.447  3264  3264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:06:21.454  3264  3264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 18:06:21.455   828   855 D TelephonyManager: getDataEnabled: retVal=false
03-31 18:06:21.457  3064  3064 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-31 18:06:21.457   828  1044 V PerformBackupTask: Beginning backup of 14 targets
,03-31 18:06:21.462   828  1044 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-31 18:06:21.463   828   855 E GpsLocationProvider: No APN found to select.
,03-31 18:06:21.465  3064  3064 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-31 18:06:21.473   828  1044 V BackupServiceBinder: doBackup() invoked
,03-31 18:06:21.478   828  1044 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-31 18:06:21.497   828  1044 I BackupRestoreController: Getting widget state for user: 0
,03-31 18:06:21.521   828  1306 I ActivityManager: Start proc 3378:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-31 18:06:21.537   368   368 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 16.264ms
,03-31 18:06:21.547   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 9.166ms
,03-31 18:06:21.561   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 435us total 13.383ms
,03-31 18:06:21.590  1845  1860 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-31 18:06:21.591  1845  1860 V GmsBackupTransport: starting performBackup for @pm@
,03-31 18:06:21.604  1845  1860 V GmsBackupTransport: performBackup done for @pm@
,03-31 18:06:21.612  1376  1376 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:21.632  1376  1396 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-31 18:06:21.632  1376  1396 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:21.632  1376  1396 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:21.632  1376  1396 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:21.638  1376  1396 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:21.677  1376  1396 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 18:06:21.677  1376  1396 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 18:06:21.677  1376  1396 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 18:06:21.677  1376  1396 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 18:06:21.677  1376  1396 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 18:06:21.677  1376  1396 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 18:06:21.677  1376  1396 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 18:06:21.684  1845  1903 W GmsBackupTransport: Error sending final backup to server: 
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 18:06:21.684  1845  1903 W GmsBackupTransport: 	... 1 more
,03-31 18:06:21.684   828  1044 D BackupManagerService: Now staging backup of com.google.android.talk
,03-31 18:06:21.692   828  3332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 31 Mar 2016 16:06:21 GMT], X-Android-Received-Millis=[1459440381692], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459440381598]}
,03-31 18:06:21.693   828  1012 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-31 18:06:21.693   828  3332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-31 18:06:21.693   828  1012 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-31 18:06:21.693   828  1012 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-31 18:06:21.693   828  1012 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-31 18:06:21.693   828  1012 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-31 18:06:21.693   828  1012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-31 18:06:21.694  1067  1565 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 18:06:21.714   828  1261 D AlarmManagerService: Setting time of day to sec=1459440381
03-31 18:06:21.341   828  3406 D GpsLocationProvider: NTP server returned: 1459440381341 (Thu Mar 31 18:06:21 GMT+02:00 2016) reference: 178999 certainty: 25 system time offset: 0
03-31 18:06:21.341   828  1261 W AlarmManagerService: Unable to set rtc to 1459440381: Invalid argument
,03-31 18:06:21.347   828  1305 I ActivityManager: Start proc 3412:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-31 18:06:21.346   828  1044 D BackupManagerService: Now staging backup of com.google.android.dialer
03-31 18:06:21.355   828  1044 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-31 18:06:21.359   828  1044 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-31 18:06:21.371   828  1044 D BackupManagerService: Now staging backup of com.google.android.gm
,03-31 18:06:21.373   828  1044 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-31 18:06:21.376   828  1044 D BackupManagerService: Now staging backup of com.android.nfc
,03-31 18:06:21.380   828  1044 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-31 18:06:21.386   828  1044 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-31 18:06:21.389   828  1044 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-31 18:06:21.390  1808  3429 W DriveInitializer: Background init thread started
,03-31 18:06:21.394   828  1044 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-31 18:06:21.396   828  1044 D BackupManagerService: Now staging backup of com.android.vending
,03-31 18:06:21.399   828  1044 D BackupManagerService: Now staging backup of android
,03-31 18:06:21.401   828  1044 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-31 18:06:21.409   828  1456 I art     : Explicit concurrent mark sweep GC freed 57768(3MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.411ms total 71.377ms
,03-31 18:06:21.418  1845  1874 I GmsBackupTransport: Next backup will happen in 43200262 millis.
,03-31 18:06:21.443   828  1044 I BackupManagerService: Backup pass finished.
,03-31 18:06:21.445  3412  3412 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-31 18:06:21.453  1808  3435 W DriveInitializer: Awaiting to be initialized
,03-31 18:06:21.454  3412  3412 D SprintDMHelper: simOperator:  IMSI: null
,03-31 18:06:21.455  3412  3412 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-31 18:06:21.461  1808  1808 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-31 18:06:21.464  1376  1748 I art     : Explicit concurrent mark sweep GC freed 24322(1311KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.014ms total 70.947ms
,03-31 18:06:21.469  1808  1808 D SystemUpdateService: onCreate
,03-31 18:06:21.472  1808  1808 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-31 18:06:21.483  1808  3441 I SystemUpdateService: active receiver: enabled
,03-31 18:06:21.491  1808  3429 W DriveInitializer: Background init thread ended
03-31 18:06:21.496  1808  3441 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-31 18:06:21.519  1808  3441 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-31 18:06:21.519  1808  3441 I SystemUpdateService: now status is 0 (complete)
03-31 18:06:21.519  1808  3441 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-31 18:06:21.519  1808  3441 I SystemUpdateService: file has been verified
03-31 18:06:21.519  1808  3441 I SystemUpdateService: OTA package size = 25802302
,03-31 18:06:21.528  1808  3441 I SystemUpdateService: showing system update notification
,03-31 18:06:21.555   828   828 I ValidateNoPeople: skipping global notification
,03-31 18:06:21.564  1808  3451 I iu.SyncManager: SYNC; picasa accounts
,03-31 18:06:21.573  1808  1808 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-31 18:06:21.575  1808  1808 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-31 18:06:21.579  1808  1808 D SystemUpdateService: onDestroy
,03-31 18:06:21.581  1808  3451 I iu.UploadsManager: num queued entries: 0
03-31 18:06:21.582  1808  3451 I iu.UploadsManager: num updated entries: 0
03-31 18:06:21.582  1808  3451 I iu.SyncManager: NEXT; no task
,03-31 18:06:21.588  1808  1808 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-31 18:06:21.589  1808  1808 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-31 18:06:21.617   828  1252 I ActivityManager: Start proc 3456:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-31 18:06:21.638  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 18:06:21.639  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:21.639  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:21.639  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:21.663   828   855 I ActivityManager: Start proc 3473:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-31 18:06:21.666  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:21.680  3039  3434 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 18:06:21.680  3039  3434 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jdm.a(PG:82)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jcs.o(PG:406)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jcn.a(PG:1379)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jcs.i(PG:143)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at blb.a(PG:3937)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at czp.a(PG:18188)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at czp.a(PG:9081)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at czq.run(PG:1686)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:06:21.680  3039  3434 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jdj.a(PG:4091)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jdj.a(PG:1125)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jdm.a(PG:77)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	... 12 more
03-31 18:06:21.680  3039  3434 E HttpOperation: Caused by: faj: BadAuthentication
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at fal.a(PG:38)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	at jdj.a(PG:4089)
03-31 18:06:21.680  3039  3434 E HttpOperation: 	... 14 more
,03-31 18:06:21.711  1376  1396 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 18:06:21.711  1376  1396 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:21.711  1376  1396 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:21.711  1376  1396 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 18:06:21.714  1376  1396 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:21.733  3456  3456 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-31 18:06:21.733  3456  3456 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 18:06:21.733  3456  3456 I GAv4    :   adb logcat -s GAv4
,03-31 18:06:21.745  3456  3456 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 18:06:21.758  3456  3456 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 18:06:21.769  3039  3434 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 18:06:21.769  3039  3434 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jdm.a(PG:82)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jcs.o(PG:406)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jcn.a(PG:1379)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jcs.i(PG:143)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at hec.a(PG:42)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at hee.a(PG:102)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at czr.a(PG:65)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at kka.a(PG:108)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at czp.a(PG:19176)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at czp.a(PG:9081)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at czq.run(PG:1686)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:06:21.769  3039  3434 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jdj.a(PG:4091)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jdj.a(PG:1125)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jdm.a(PG:77)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	... 15 more
03-31 18:06:21.769  3039  3434 E HttpOperation: Caused by: faj: BadAuthentication
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at fal.a(PG:38)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	at jdj.a(PG:4089)
03-31 18:06:21.769  3039  3434 E HttpOperation: 	... 17 more
03-31 18:06:21.769  3039  3434 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 18:06:21.769  3039  3434 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at hec.a(PG:42)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at hee.a(PG:102)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at czr.a(PG:65)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at kka.a(PG:108)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	... 15 more
03-31 18:06:21.769  3039  3434 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at fal.a(PG:38)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 18:06:21.769  3039  3434 E ExperimentLoader: 	... 17 more
03-31 18:06:21.787  3456  3499 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 18:06:21.868  3153  3453 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-31 18:06:21.869   828  1252 I ActivityManager: Killing 2954:com.android.musicfx/u0a18 (adj 15): empty #17
,03-31 18:06:21.901  3473  3508 V KeepSync: Connecting to GoogleApiClient
,03-31 18:06:22.015  1376  3502 D GCM     : Connected
,03-31 18:06:22.035  1376  3502 D GCM     : Message class com.google.f.a.a.p
,03-31 18:06:22.043   828   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 39081, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 18:06:22.049  3456  3456 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-31 18:06:22.057  1808  3520 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 18:06:22.061  1808  3520 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 18:06:22.070  3456  3456 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9726-9728)
,03-31 18:06:22.070  3456  3456 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 18:06:22.074  3456  3456 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ae2d45}
,03-31 18:06:22.074  3456  3456 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 18:06:22.075  3456  3456 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 18:06:22.084  3456  3456 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 18:06:22.085  3456  3456 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 18:06:22.085  3456  3456 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 18:06:22.095  3456  3456 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-31 18:06:22.099  3456  3456 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 18:06:22.099  3456  3456 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 18:06:22.099  3456  3456 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-31 18:06:22.108   828   855 I ActivityManager: Start proc 3528:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
03-31 18:06:22.118  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 18:06:22.119  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:22.119  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:22.119  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 18:06:22.122  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: Handling authorization failure
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 18:06:22.139  1808  3520 E ClientConnectionOperation: 	... 7 more
,03-31 18:06:22.141  3473  3508 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 18:06:22.142  3473  3508 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 18:06:22.145  3473  3508 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 18:06:22.145  3473  3508 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 18:06:22.186  3456  3553 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-31 18:06:22.188  3456  3456 I NSApplication: Starting up...
,03-31 18:06:22.225   828  1305 I ActivityManager: Start proc 3558:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
03-31 18:06:22.226   828  1305 I ActivityManager: Killing 3002:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-31 18:06:22.483  1376  1397 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 18:06:22.484  1376  1397 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:22.484  1376  1397 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:22.484  1376  1397 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:22.488  1376  1397 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:22.540  1376  1397 I art     : Explicit concurrent mark sweep GC freed 15417(892KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 916us total 31.993ms
,03-31 18:06:22.559  3473  3508 E KeepSync: IOException
03-31 18:06:22.559  3473  3508 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 18:06:22.559  3473  3508 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 18:06:22.559  3473  3508 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 18:06:22.559  3473  3508 E KeepSync: 	... 10 more
03-31 18:06:22.559  3473  3508 W KeepSync: Sync result 2
,03-31 18:06:22.565   828   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39087, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 18:06:22.568   828  1252 I ActivityManager: Killing 2773:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-31 18:06:22.575  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 18:06:22.575  3264  3326 I jxcore-log: 
,03-31 18:06:22.684   828   843 I ActivityManager: Killing 2893:com.android.settings/1000 (adj 15): empty #17
,03-31 18:06:22.772  3528  3528 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 18:06:22.780  3528  3528 I BooksApp: Created application version: 3.6.8 (30608)
,03-31 18:06:22.861   828  1305 I ActivityManager: Start proc 3587:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-31 18:06:22.913  3528  3584 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 18:06:23.014  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 18:06:23.014  3264  3326 I jxcore-log: 
,03-31 18:06:23.024  3528  3608 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 18:06:23.028  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 18:06:23.028  3264  3326 I jxcore-log: 
,03-31 18:06:23.033  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 18:06:23.033  3264  3326 I jxcore-log: 
,03-31 18:06:23.080  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 18:06:23.080  3264  3326 I jxcore-log: 
,03-31 18:06:23.086  1376  1397 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 18:06:23.086  1376  1397 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:23.086  1376  1397 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:23.086  1376  1397 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:23.089  1376  1397 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:23.100  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 18:06:23.100  3264  3326 I jxcore-log: 
,03-31 18:06:23.105  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 18:06:23.105  3264  3326 I jxcore-log: 
,03-31 18:06:23.144   828  1305 I art     : Explicit concurrent mark sweep GC freed 28352(1335KB) AllocSpace objects, 5(120KB) LOS objects, 32% free, 33MB/49MB, paused 1.293ms total 50.356ms
,03-31 18:06:23.186  1376  1756 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 18:06:23.186  1376  1756 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:23.186  1376  1756 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:23.186  1376  1756 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:23.189  1376  1756 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:23.196  3528  3608 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 18:06:23.198  3528  3584 E BooksSync: Soft error
03-31 18:06:23.198  3528  3584 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 18:06:23.198  3528  3584 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 18:06:23.198  3528  3584 E BooksSync: Sync error
03-31 18:06:23.198  3528  3584 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 18:06:23.198  3528  3584 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 18:06:23.198  3528  3584 I BooksSync: Finished books sync
,03-31 18:06:23.201   828   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 18:06:23.203   828  1306 I ActivityManager: Killing 1466:android.process.acore/u0a5 (adj 15): empty #17
,03-31 18:06:23.308   828  1306 I ActivityManager: Killing 2450:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,03-31 18:06:23.561   828  1456 I ActivityManager: Killing 2793:com.google.android.gm/u0a78 (adj 15): empty #17
,03-31 18:06:23.939  1376  1376 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:24.040  1808  1808 V Herrevad: NQAS connected
,03-31 18:06:24.077   828  1429 I ActivityManager: Start proc 3613:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-31 18:06:24.096   828  1011 D WifiService: New client listening to asynchronous messages
,03-31 18:06:24.104  1376  3632 I VacuumService: Vacuum at: now=1459440384104 tag=VacuumService
,03-31 18:06:24.110  3378  3611 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 18:06:24.135  3613  3613 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459440384135
03-31 18:06:24.135  3613  3613 D         : TimeServiceNative: User Time to be set is 1459440384135
03-31 18:06:24.135  3613  3613 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 18:06:24.135  3613  3613 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-31 18:06:24.135  3613  3613 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459440384135
03-31 18:06:24.135   371   880 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-31 18:06:24.136   371  3633 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459440384135
03-31 18:06:24.136   371  3633 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459440384135, operation = 0
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/17/70 12:18:2
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon:Value read from RTC seconds = 19743482000
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon:new time 1459440384135 
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon: delta 1439696902135 genoff 1439696902135 
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696902135 to memory
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-31 18:06:24.137   371  3633 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 18:06:24.138  3613  3613 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-31 18:06:24.139   371  3633 D QC-time-services: Updating the TOD offset
03-31 18:06:24.139   371  3633 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696902135 to memory
03-31 18:06:24.139   371  3633 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-31 18:06:24.139   371  3633 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 18:06:24.141   371  3633 E QC-time-services: Daemon:Update to modem bit set
03-31 18:06:24.141   371  3633 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-31 18:06:24.141   371  3633 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143475584135
,03-31 18:06:24.146  3613  3613 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-31 18:06:24.184  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 18:06:24.184  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:24.184  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:24.185  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:24.188  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:24.196  1808  1808 I art     : Explicit concurrent mark sweep GC freed 16948(1225KB) AllocSpace objects, 14(224KB) LOS objects, 35% free, 29MB/45MB, paused 1.120ms total 31.116ms
,03-31 18:06:24.209   371   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-31 18:06:24.214  3378  3611 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 18:06:24.214   371   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 18:06:24.216  3378  3611 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 18:06:24.246   828  1306 I ActivityManager: Start proc 3635:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-31 18:06:24.308  3635  3635 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 18:06:24.308  3635  3635 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 18:06:24.308  3635  3635 I GAv4    :   adb logcat -s GAv4
,03-31 18:06:24.314  1376  3653 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 18:06:24.322  3635  3635 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 18:06:24.324  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:24.340  3635  3635 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-31 18:06:24.346  3635  3657 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 18:06:24.381  3153  3153 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 18:06:24.381  3153  3153 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 18:06:24.458  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-31 18:06:24.458  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:24.458  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:24.458  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:24.461  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:24.470  3153  3664 E Babel   : UserRecoverableAuthException.
,03-31 18:06:24.470  3153  3664 E Babel   : eei: BadAuthentication
03-31 18:06:24.470  3153  3664 E Babel   : 	at eeg.a(Unknown Source)
03-31 18:06:24.470  3153  3664 E Babel   : 	at eeg.a(Unknown Source)
03-31 18:06:24.470  3153  3664 E Babel   : 	at eeg.a(Unknown Source)
03-31 18:06:24.470  3153  3664 E Babel   : 	at g.a(Unknown Source)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cae.a(SourceFile:3089)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cae.a(SourceFile:1131)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cws.a(SourceFile:4333)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cws.a(SourceFile:1419)
03-31 18:06:24.470  3153  3664 E Babel   : 	at crl.a(SourceFile:492)
03-31 18:06:24.470  3153  3664 E Babel   : 	at crl.a(SourceFile:1468)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cas.b(SourceFile:106)
03-31 18:06:24.470  3153  3664 E Babel   : 	at cap.d(SourceFile:335)
03-31 18:06:24.470  3153  3664 E Babel   : 	at caq.run(SourceFile:81)
03-31 18:06:24.470  3153  3664 E Babel   : Error getting auth token
03-31 18:06:24.471  3153  3664 E Babel   : dvm
03-31 18:06:24.471  3153  3664 E Babel   : 	at g.a(Unknown Source)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cae.a(SourceFile:3089)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cae.a(SourceFile:1131)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cws.a(SourceFile:4333)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cws.a(SourceFile:1419)
03-31 18:06:24.471  3153  3664 E Babel   : 	at crl.a(SourceFile:492)
03-31 18:06:24.471  3153  3664 E Babel   : 	at crl.a(SourceFile:1468)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cas.b(SourceFile:106)
03-31 18:06:24.471  3153  3664 E Babel   : 	at cap.d(SourceFile:335)
03-31 18:06:24.471  3153  3664 E Babel   : 	at caq.run(SourceFile:81)
,03-31 18:06:24.474  3153  3664 E Babel   : Account registration failed 1-Redacted-21
03-31 18:06:24.474  3153  3664 E Babel   : cyp: null -- null
03-31 18:06:24.474  3153  3664 E Babel   : 	at cae.a(SourceFile:3121)
03-31 18:06:24.474  3153  3664 E Babel   : 	at cae.a(SourceFile:1131)
03-31 18:06:24.474  3153  3664 E Babel   : 	at cws.a(SourceFile:4333)
03-31 18:06:24.474  3153  3664 E Babel   : 	at cws.a(SourceFile:1419)
03-31 18:06:24.474  3153  3664 E Babel   : 	at crl.a(SourceFile:492)
03-31 18:06:24.474  3153  3664 E Babel   : 	at crl.a(SourceFile:1468)
03-31 18:06:24.474  3153  3664 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 18:06:24.474  3153  3664 E Babel   : 	at cas.b(SourceFile:106)
03-31 18:06:24.474  3153  3664 E Babel   : 	at cap.d(SourceFile:335)
03-31 18:06:24.474  3153  3664 E Babel   : 	at caq.run(SourceFile:81)
,03-31 18:06:24.482  3153  3664 I art     : Note: end time exceeds epoch: 
,03-31 18:06:24.501  1376  2549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-31 18:06:24.501  1376  2549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:24.501  1376  2549 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:24.501  1376  2549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:24.504  1376  2549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:24.514  1376  2549 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 18:06:24.529  3153  3670 E Babel   : Unexpected exception while authenticating.
03-31 18:06:24.529  3153  3670 E Babel   : eej: User intervention required. Notification has been pushed.
03-31 18:06:24.529  3153  3670 E Babel   : 	at eeg.b(Unknown Source)
03-31 18:06:24.529  3153  3670 E Babel   : 	at eeg.b(Unknown Source)
03-31 18:06:24.529  3153  3670 E Babel   : 	at g.a(Unknown Source)
03-31 18:06:24.529  3153  3670 E Babel   : 	at cae.b(SourceFile:1146)
03-31 18:06:24.529  3153  3670 E Babel   : 	at dcg.run(SourceFile:5617)
03-31 18:06:24.529  3153  3670 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:06:24.529  3153  3670 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:06:24.529  3153  3670 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-31 18:06:24.817  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:24.988  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:25.143  1376  3653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 18:06:25.144  1376  3653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:25.144  1376  3653 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:25.144  1376  3653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:25.148  1376  3653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:25.194  1376  3653 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 18:06:25.194  1376  3653 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 18:06:25.194  1376  3653 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 18:06:25.310  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 18:06:25.310  3264  3326 I jxcore-log: 
,03-31 18:06:25.328  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 18:06:25.328  3264  3326 I jxcore-log: 
,03-31 18:06:25.332  1376  3653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 18:06:25.333  1376  3653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:25.333  1376  3653 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 18:06:25.333  1376  3653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:25.337  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
03-31 18:06:25.337  3264  3326 I jxcore-log: 
,03-31 18:06:25.341  1376  3653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:25.370  1376  3653 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 18:06:25.370  1376  3653 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 18:06:25.370  1376  3653 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 18:06:25.487  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 18:06:25.487  3264  3326 I jxcore-log: 
,03-31 18:06:25.579  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:25.610  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 18:06:25.610  3264  3326 I jxcore-log: 
,03-31 18:06:25.670  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 18:06:25.670  3264  3326 I jxcore-log: 
,03-31 18:06:25.677  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
03-31 18:06:25.677  3264  3326 I jxcore-log: 
,03-31 18:06:25.727  1376  3653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 18:06:25.727  1376  3653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:25.727  1376  3653 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:25.727  1376  3653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:25.742  1376  3653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:25.802  1376  3653 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 18:06:25.802  1376  3653 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 18:06:25.802  1376  3653 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 18:06:25.857  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 18:06:25.857  3264  3326 I jxcore-log: 
,03-31 18:06:25.883  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 18:06:25.883  3264  3326 I jxcore-log: 
,03-31 18:06:25.889  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
,03-31 18:06:25.889  3264  3326 I jxcore-log: 
,03-31 18:06:25.897  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 18:06:25.897  3264  3326 I jxcore-log: 
03-31 18:06:25.899  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:25.940  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 18:06:25.940  3264  3326 I jxcore-log: 
,03-31 18:06:25.967  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 18:06:25.967  3264  3326 I jxcore-log: 
,03-31 18:06:26.029  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:26.060  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 18:06:26.060  3264  3326 I jxcore-log: 
,03-31 18:06:26.066  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,03-31 18:06:26.066  3264  3326 I jxcore-log: 
,03-31 18:06:26.118  3264  3326 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 18:06:26.118  3264  3326 I jxcore-log: 
,03-31 18:06:26.145  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:26.184  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:06:26.184  3264  3326 I jxcore-log: 
,03-31 18:06:26.247  1376  1748 I art     : Explicit concurrent mark sweep GC freed 43610(2MB) AllocSpace objects, 1(39KB) LOS objects, 36% free, 27MB/43MB, paused 935us total 48.138ms
,03-31 18:06:26.251  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:26.332  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:26.448   828  1428 I art     : Explicit concurrent mark sweep GC freed 21466(978KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.436ms total 51.316ms
03-31 18:06:26.448   828   841 I art     : WaitForGcToComplete blocked for 45.974ms for cause HeapTrim
,03-31 18:06:26.464  1376  1376 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:26.488  1376  3653 W Uploader:  no longer exists, so no auth token.
,03-31 18:06:26.505  1376  1756 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 18:06:26.505  1376  1756 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:26.505  1376  1756 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:26.505  1376  1756 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:26.508  1376  1756 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:26.518  2730  2730 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 18:06:26.518  2730  2730 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 18:06:26.518  2730  2730 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-31 18:06:26.753  1376  3653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 18:06:26.754  1376  3653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:26.754  1376  3653 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:26.754  1376  3653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:26.758  1376  3653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:26.788  1376  3653 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
,03-31 18:06:26.788  1376  3653 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
,03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
,03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 18:06:26.788  1376  3653 E Uploader: 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125),
03-31 18:06:26.788  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 18:06:26.788  1376  3653 E Uploader: 	,at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 18:06:26.976  1376  3653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 18:06:26.976  1376  3653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:26.976  1376  3653 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 18:06:26.976  1376  3653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:26.987  1376  3653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:27.037  1376  3653 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 18:06:27.037  1376  3653 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 18:06:27.037  1376  3653 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 18:06:27.402  3264  3326 I jxcore-log: TAP version 13
03-31 18:06:27.402  3264  3326 I jxcore-log: 
,03-31 18:06:27.405  3264  3326 I jxcore-log: # setup
03-31 18:06:27.405  3264  3326 I jxcore-log: 
,03-31 18:06:27.466  1376  3653 W Uploader: No account for auth token provided
,03-31 18:06:27.640  3264  3326 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 18:06:27.640  3264  3326 I jxcore-log: 
,03-31 18:06:27.790  3528  3581 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 18:06:28.047  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:28.047  3264  3326 I jxcore-log: 
,03-31 18:06:28.053  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 33099
03-31 18:06:28.053  3264  3326 I jxcore-log: 
,03-31 18:06:28.059  3264  3326 I jxcore-log: ok 1 Should throw,
03-31 18:06:28.059  3264  3326 I jxcore-log: 
,03-31 18:06:28.061  3264  3326 I jxcore-log: # teardown
,03-31 18:06:28.061  3264  3326 I jxcore-log: 
,03-31 18:06:29.441  2156  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 18:06:29.512   828  1106 I ActivityManager: Killing 2974:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-31 18:06:30.120  3264  3326 I jxcore-log: # setup
03-31 18:06:30.120  3264  3326 I jxcore-log: 
,03-31 18:06:30.774  3264  3326 I jxcore-log: # 2. emits incomingConnectionState
03-31 18:06:30.774  3264  3326 I jxcore-log: 
,03-31 18:06:30.978  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:30.978  3264  3326 I jxcore-log: 
,03-31 18:06:30.984  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 49833
03-31 18:06:30.984  3264  3326 I jxcore-log: 
,03-31 18:06:30.993  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:30.993  3264  3326 I jxcore-log: 
,03-31 18:06:30.996  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:30.996  3264  3326 I jxcore-log: 
,03-31 18:06:31.005  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:31.005  3264  3326 I jxcore-log: 
,03-31 18:06:31.012  3264  3326 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 18:06:31.012  3264  3326 I jxcore-log: 
,03-31 18:06:31.026  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:31.026  3264  3326 I jxcore-log: 
,03-31 18:06:31.027  3264  3326 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 18:06:31.027  3264  3326 I jxcore-log: 
,03-31 18:06:31.038  3264  3326 I jxcore-log: # teardown
03-31 18:06:31.038  3264  3326 I jxcore-log: 
,03-31 18:06:31.266   828  1252 I ActivityManager: Killing 1532:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-31 18:06:31.340   828  1011 D WifiService: Client connection lost with reason: 4
,03-31 18:06:31.676  3264  3326 I jxcore-log: # setup
03-31 18:06:31.676  3264  3326 I jxcore-log: 
,03-31 18:06:32.865  2730  2746 D Finsky  : [250] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-31 18:06:32.879  1376  1376 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:32.930  1376  2549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 18:06:32.931  1376  2549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:32.931  1376  2549 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:32.932  1376  2549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:32.938  1376  2549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 18:06:32.974  2730  2746 D Finsky  : [250] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-31 18:06:33.018  3264  3326 I jxcore-log: # 3. emits routerPortConnectionFailed
03-31 18:06:33.018  3264  3326 I jxcore-log: 
,03-31 18:06:33.243  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:33.243  3264  3326 I jxcore-log: 
,03-31 18:06:33.245  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 41501
03-31 18:06:33.245  3264  3326 I jxcore-log: 
,03-31 18:06:33.251  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:33.251  3264  3326 I jxcore-log: 
,03-31 18:06:33.253  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:33.253  3264  3326 I jxcore-log: 
03-31 18:06:33.254  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux,
03-31 18:06:33.254  3264  3326 I jxcore-log: 
,03-31 18:06:33.280  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-31 18:06:33.280  3264  3326 I jxcore-log: 
,03-31 18:06:33.282  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-31 18:06:33.282  3264  3326 I jxcore-log: 
,03-31 18:06:33.287  3264  3326 I jxcore-log: DEBUG createNativeListener: ,
03-31 18:06:33.287  3264  3326 I jxcore-log: 
,03-31 18:06:33.288  3264  3326 I jxcore-log: ok 4 tried to connect to right port,
03-31 18:06:33.288  3264  3326 I jxcore-log: 
03-31 18:06:33.288  3264  3326 I jxcore-log: ok 5 failed due to refused connection
03-31 18:06:33.288  3264  3326 I jxcore-log: 
,03-31 18:06:33.289  3264  3326 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-31 18:06:33.289  3264  3326 I jxcore-log: 
03-31 18:06:33.293  3264  3326 I jxcore-log: # teardown
03-31 18:06:33.293  3264  3326 I jxcore-log: 
,03-31 18:06:33.294  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:33.294  3264  3326 I jxcore-log: 
,03-31 18:06:33.455  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:33.455  3264  3326 I jxcore-log: 
03-31 18:06:33.460  3264  3326 I jxcore-log: # setup
03-31 18:06:33.460  3264  3326 I jxcore-log: 
03-31 18:06:33.461  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:33.461  3264  3326 I jxcore-log: 
,03-31 18:06:33.695  3264  3326 I jxcore-log: # 4. native server connections all up
03-31 18:06:33.695  3264  3326 I jxcore-log: 
,03-31 18:06:33.873  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:33.873  3264  3326 I jxcore-log: 
03-31 18:06:33.876  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 43387
03-31 18:06:33.876  3264  3326 I jxcore-log: 
,03-31 18:06:33.887  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:33.887  3264  3326 I jxcore-log: 
,03-31 18:06:33.890  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:33.890  3264  3326 I jxcore-log: 
,03-31 18:06:33.895  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:33.895  3264  3326 I jxcore-log: 
,03-31 18:06:33.932  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:33.932  3264  3326 I jxcore-log: 
,03-31 18:06:33.935  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:33.935  3264  3326 I jxcore-log: 
,03-31 18:06:33.938  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:33.938  3264  3326 I jxcore-log: 
,03-31 18:06:33.941  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:33.941  3264  3326 I jxcore-log: 
,03-31 18:06:33.974  3264  3326 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 18:06:33.974  3264  3326 I jxcore-log: 
,03-31 18:06:33.974  3264  3326 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 18:06:33.974  3264  3326 I jxcore-log: 
,03-31 18:06:33.976  3264  3326 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 18:06:33.976  3264  3326 I jxcore-log: 
03-31 18:06:33.977  3264  3326 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 18:06:33.977  3264  3326 I jxcore-log: 
03-31 18:06:33.979  3264  3326 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-31 18:06:33.979  3264  3326 I jxcore-log: 
,03-31 18:06:33.986  3264  3326 I jxcore-log: # teardown
03-31 18:06:33.986  3264  3326 I jxcore-log: 
,03-31 18:06:34.617  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:34.617  3264  3326 I jxcore-log: 
,03-31 18:06:34.619  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:34.619  3264  3326 I jxcore-log: 
,03-31 18:06:34.621  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:34.621  3264  3326 I jxcore-log: 
,03-31 18:06:34.625  3264  3326 I jxcore-log: # setup
03-31 18:06:34.625  3264  3326 I jxcore-log: 
,03-31 18:06:34.627  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:34.627  3264  3326 I jxcore-log: 
,03-31 18:06:34.910  3264  3326 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 18:06:34.910  3264  3326 I jxcore-log: 
,03-31 18:06:36.091  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:36.091  3264  3326 I jxcore-log: 
,03-31 18:06:36.096  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 47157
03-31 18:06:36.096  3264  3326 I jxcore-log: 
,03-31 18:06:36.100  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:36.100  3264  3326 I jxcore-log: 
,03-31 18:06:36.101  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:36.101  3264  3326 I jxcore-log: 
,03-31 18:06:36.102  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:36.102  3264  3326 I jxcore-log: 
,03-31 18:06:36.114  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:36.114  3264  3326 I jxcore-log: 
,03-31 18:06:36.117  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:36.117  3264  3326 I jxcore-log: 
,03-31 18:06:36.129  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:36.129  3264  3326 I jxcore-log: 
,03-31 18:06:36.142  3264  3326 I jxcore-log: ok 12 socket shouldn't close until after stream,
03-31 18:06:36.142  3264  3326 I jxcore-log: 
,03-31 18:06:36.142  3264  3326 I jxcore-log: ok 13 incoming remains open,
03-31 18:06:36.142  3264  3326 I jxcore-log: 
03-31 18:06:36.147  3264  3326 I jxcore-log: # teardown,
03-31 18:06:36.147  3264  3326 I jxcore-log: 
,03-31 18:06:37.053  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:37.053  3264  3326 I jxcore-log: 
03-31 18:06:37.057  3264  3326 I jxcore-log: # setup
03-31 18:06:37.057  3264  3326 I jxcore-log: 
03-31 18:06:37.059  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:37.059  3264  3326 I jxcore-log: 
,03-31 18:06:37.296  3264  3326 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket,
03-31 18:06:37.296  3264  3326 I jxcore-log: 
,03-31 18:06:37.865  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server,
,03-31 18:06:37.865  3264  3326 I jxcore-log: 
03-31 18:06:37.874  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 47711
03-31 18:06:37.874  3264  3326 I jxcore-log: 
,03-31 18:06:37.883  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:37.883  3264  3326 I jxcore-log: 
,03-31 18:06:37.886  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:37.886  3264  3326 I jxcore-log: 
,03-31 18:06:37.890  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:37.890  3264  3326 I jxcore-log: 
,03-31 18:06:37.914  3264  3326 I jxcore-log: ok 14 we should not have gotten an error
03-31 18:06:37.914  3264  3326 I jxcore-log: 
,03-31 18:06:37.919  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:37.919  3264  3326 I jxcore-log: 
,03-31 18:06:37.924  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:37.924  3264  3326 I jxcore-log: 
,03-31 18:06:37.935  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:37.935  3264  3326 I jxcore-log: 
,03-31 18:06:37.937  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:37.937  3264  3326 I jxcore-log: 
,03-31 18:06:37.946  3264  3326 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-31 18:06:37.946  3264  3326 I jxcore-log: 
,03-31 18:06:37.946  3264  3326 I jxcore-log: ok 16 incoming is cleaned up
03-31 18:06:37.946  3264  3326 I jxcore-log: 
,03-31 18:06:37.953  3264  3326 I jxcore-log: # teardown
03-31 18:06:37.953  3264  3326 I jxcore-log: 
,03-31 18:06:38.058  3264  3326 I jxcore-log: # setup
,03-31 18:06:38.058  3264  3326 I jxcore-log: 
,03-31 18:06:38.226  3264  3326 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 18:06:38.226  3264  3326 I jxcore-log: 
,03-31 18:06:38.339  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:38.339  3264  3326 I jxcore-log: 
,03-31 18:06:38.348  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 56685
03-31 18:06:38.348  3264  3326 I jxcore-log: 
,03-31 18:06:38.357  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:38.357  3264  3326 I jxcore-log: 
,03-31 18:06:38.358  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:38.358  3264  3326 I jxcore-log: 
,03-31 18:06:38.361  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:38.361  3264  3326 I jxcore-log: 
,03-31 18:06:38.373  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:38.373  3264  3326 I jxcore-log: 
,03-31 18:06:38.376  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:38.376  3264  3326 I jxcore-log: 
,03-31 18:06:38.391  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:38.391  3264  3326 I jxcore-log: 
,03-31 18:06:38.400  3264  3326 I jxcore-log: ok 17 stream was closed
03-31 18:06:38.400  3264  3326 I jxcore-log: 
,03-31 18:06:38.401  3264  3326 I jxcore-log: ok 18 incoming should survive
03-31 18:06:38.401  3264  3326 I jxcore-log: 
,03-31 18:06:38.402  3264  3326 I jxcore-log: ok 19 mux should have no streams
03-31 18:06:38.402  3264  3326 I jxcore-log: 
03-31 18:06:38.409  3264  3326 I jxcore-log: # teardown
03-31 18:06:38.409  3264  3326 I jxcore-log: 
,03-31 18:06:38.606  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:38.606  3264  3326 I jxcore-log: 
,03-31 18:06:38.617  3264  3326 I jxcore-log: # setup
03-31 18:06:38.617  3264  3326 I jxcore-log: 
,03-31 18:06:38.618  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:38.618  3264  3326 I jxcore-log: 
,03-31 18:06:38.795  3264  3326 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-31 18:06:38.795  3264  3326 I jxcore-log: 
,03-31 18:06:38.902  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:38.902  3264  3326 I jxcore-log: 
,03-31 18:06:38.913  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 34408
03-31 18:06:38.913  3264  3326 I jxcore-log: 
,03-31 18:06:38.919  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:38.919  3264  3326 I jxcore-log: 
,03-31 18:06:38.920  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:38.920  3264  3326 I jxcore-log: 
,03-31 18:06:38.922  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:38.922  3264  3326 I jxcore-log: 
,03-31 18:06:38.933  3264  3326 I jxcore-log: ok 20 we should not have gotten an error
03-31 18:06:38.933  3264  3326 I jxcore-log: 
,03-31 18:06:38.939  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:38.939  3264  3326 I jxcore-log: 
,03-31 18:06:38.942  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:38.942  3264  3326 I jxcore-log: 
,03-31 18:06:38.952  3264  3326 I jxcore-log: ok 21 Buffers are identical
03-31 18:06:38.952  3264  3326 I jxcore-log: 
,03-31 18:06:38.955  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:38.955  3264  3326 I jxcore-log: 
,03-31 18:06:38.958  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:38.958  3264  3326 I jxcore-log: 
,03-31 18:06:38.962  3264  3326 I jxcore-log: ok 22 native server is nulled out
03-31 18:06:38.962  3264  3326 I jxcore-log: 
,03-31 18:06:38.962  3264  3326 I jxcore-log: ok 23 native server should be closed
03-31 18:06:38.962  3264  3326 I jxcore-log: 
,03-31 18:06:38.963  3264  3326 I jxcore-log: ok 24 incoming has been removed
03-31 18:06:38.963  3264  3326 I jxcore-log: 
03-31 18:06:38.963  3264  3326 I jxcore-log: ok 25 Incoming should be done
03-31 18:06:38.963  3264  3326 I jxcore-log: 
03-31 18:06:38.963  3264  3326 I jxcore-log: ok 26 The mux object should be closed
03-31 18:06:38.963  3264  3326 I jxcore-log: 
,03-31 18:06:38.964  3264  3326 I jxcore-log: ok 27 The mux stream should be closed
03-31 18:06:38.964  3264  3326 I jxcore-log: 
03-31 18:06:38.965  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:38.965  3264  3326 I jxcore-log: 
,03-31 18:06:38.981  3264  3326 I jxcore-log: # teardown
03-31 18:06:38.981  3264  3326 I jxcore-log: 
,03-31 18:06:39.134  3264  3326 I jxcore-log: # setup
03-31 18:06:39.134  3264  3326 I jxcore-log: 
,03-31 18:06:39.276  3264  3326 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-31 18:06:39.276  3264  3326 I jxcore-log: 
,03-31 18:06:39.457  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:39.457  3264  3326 I jxcore-log: 
,03-31 18:06:39.460  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 39457
03-31 18:06:39.460  3264  3326 I jxcore-log: 
,03-31 18:06:39.481  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.481  3264  3326 I jxcore-log: 
,03-31 18:06:39.482  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.482  3264  3326 I jxcore-log: 
,03-31 18:06:39.484  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.484  3264  3326 I jxcore-log: 
,03-31 18:06:39.488  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.488  3264  3326 I jxcore-log: 
,03-31 18:06:39.489  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.489  3264  3326 I jxcore-log: 
,03-31 18:06:39.490  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.490  3264  3326 I jxcore-log: 
,03-31 18:06:39.494  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.494  3264  3326 I jxcore-log: 
,03-31 18:06:39.495  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.495  3264  3326 I jxcore-log: 
,03-31 18:06:39.496  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.496  3264  3326 I jxcore-log: 
03-31 18:06:39.502  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.502  3264  3326 I jxcore-log: 
,03-31 18:06:39.503  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.503  3264  3326 I jxcore-log: 
03-31 18:06:39.504  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.504  3264  3326 I jxcore-log: 
03-31 18:06:39.508  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.508  3264  3326 I jxcore-log: 
03-31 18:06:39.508  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.508  3264  3326 I jxcore-log: 
03-31 18:06:39.509  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.509  3264  3326 I jxcore-log: 
,03-31 18:06:39.511  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.511  3264  3326 I jxcore-log: 
03-31 18:06:39.512  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.512  3264  3326 I jxcore-log: 
03-31 18:06:39.513  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.513  3264  3326 I jxcore-log: 
,03-31 18:06:39.516  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.516  3264  3326 I jxcore-log: 
03-31 18:06:39.516  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.516  3264  3326 I jxcore-log: 
,03-31 18:06:39.517  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.517  3264  3326 I jxcore-log: 
03-31 18:06:39.519  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.519  3264  3326 I jxcore-log: 
03-31 18:06:39.520  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.520  3264  3326 I jxcore-log: 
,03-31 18:06:39.520  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.520  3264  3326 I jxcore-log: 
,03-31 18:06:39.523  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.523  3264  3326 I jxcore-log: 
,03-31 18:06:39.523  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.523  3264  3326 I jxcore-log: 
03-31 18:06:39.524  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.524  3264  3326 I jxcore-log: 
,03-31 18:06:39.526  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:39.526  3264  3326 I jxcore-log: 
03-31 18:06:39.527  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:39.527  3264  3326 I jxcore-log: 
03-31 18:06:39.527  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:39.527  3264  3326 I jxcore-log: 
,03-31 18:06:39.613  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-31 18:06:39.613  3264  3326 I jxcore-log: 
,03-31 18:06:39.616  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.616  3264  3326 I jxcore-log: 
,03-31 18:06:39.618  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.618  3264  3326 I jxcore-log: 
,03-31 18:06:39.620  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.620  3264  3326 I jxcore-log: 
,03-31 18:06:39.622  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.622  3264  3326 I jxcore-log: 
,03-31 18:06:39.624  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.624  3264  3326 I jxcore-log: 
,03-31 18:06:39.626  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.626  3264  3326 I jxcore-log: 
,03-31 18:06:39.628  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.628  3264  3326 I jxcore-log: 
,03-31 18:06:39.630  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.630  3264  3326 I jxcore-log: 
,03-31 18:06:39.632  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.632  3264  3326 I jxcore-log: 
,03-31 18:06:39.634  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.634  3264  3326 I jxcore-log: 
,03-31 18:06:39.635  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.635  3264  3326 I jxcore-log: 
,03-31 18:06:39.637  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.637  3264  3326 I jxcore-log: 
,03-31 18:06:39.638  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.638  3264  3326 I jxcore-log: 
,03-31 18:06:39.640  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.640  3264  3326 I jxcore-log: 
,03-31 18:06:39.641  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.641  3264  3326 I jxcore-log: 
,03-31 18:06:39.644  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.644  3264  3326 I jxcore-log: 
,03-31 18:06:39.646  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.646  3264  3326 I jxcore-log: 
,03-31 18:06:39.650  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.650  3264  3326 I jxcore-log: 
,03-31 18:06:39.652  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.652  3264  3326 I jxcore-log: 
,03-31 18:06:39.653  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.653  3264  3326 I jxcore-log: 
,03-31 18:06:39.655  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.655  3264  3326 I jxcore-log: 
,03-31 18:06:39.656  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.656  3264  3326 I jxcore-log: 
,03-31 18:06:39.658  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.658  3264  3326 I jxcore-log: 
,03-31 18:06:39.660  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.660  3264  3326 I jxcore-log: 
,03-31 18:06:39.662  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.662  3264  3326 I jxcore-log: 
,03-31 18:06:39.663  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.663  3264  3326 I jxcore-log: 
,03-31 18:06:39.665  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.665  3264  3326 I jxcore-log: 
,03-31 18:06:39.666  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.666  3264  3326 I jxcore-log: 
,03-31 18:06:39.667  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.667  3264  3326 I jxcore-log: 
,03-31 18:06:39.668  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.668  3264  3326 I jxcore-log: 
,03-31 18:06:39.670  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.670  3264  3326 I jxcore-log: 
03-31 18:06:39.672  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.672  3264  3326 I jxcore-log: 
,03-31 18:06:39.674  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.674  3264  3326 I jxcore-log: 
,03-31 18:06:39.675  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.675  3264  3326 I jxcore-log: 
,03-31 18:06:39.677  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.677  3264  3326 I jxcore-log: 
,03-31 18:06:39.679  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.679  3264  3326 I jxcore-log: 
,03-31 18:06:39.681  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.681  3264  3326 I jxcore-log: 
,03-31 18:06:39.682  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.682  3264  3326 I jxcore-log: 
,03-31 18:06:39.684  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.684  3264  3326 I jxcore-log: 
,03-31 18:06:39.686  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.686  3264  3326 I jxcore-log: 
03-31 18:06:39.687  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.687  3264  3326 I jxcore-log: 
,03-31 18:06:39.689  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.689  3264  3326 I jxcore-log: 
,03-31 18:06:39.690  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.690  3264  3326 I jxcore-log: 
,03-31 18:06:39.692  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.692  3264  3326 I jxcore-log: 
,03-31 18:06:39.693  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.693  3264  3326 I jxcore-log: 
,03-31 18:06:39.695  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.695  3264  3326 I jxcore-log: 
,03-31 18:06:39.696  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.696  3264  3326 I jxcore-log: 
,03-31 18:06:39.705  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.705  3264  3326 I jxcore-log: 
,03-31 18:06:39.707  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.707  3264  3326 I jxcore-log: 
,03-31 18:06:39.708  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.708  3264  3326 I jxcore-log: 
,03-31 18:06:39.710  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.710  3264  3326 I jxcore-log: ,
03-31 18:06:39.711  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.711  3264  3326 I jxcore-log: 
,03-31 18:06:39.713  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.713  3264  3326 I jxcore-log: 
,03-31 18:06:39.714  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.714  3264  3326 I jxcore-log: 
,03-31 18:06:39.716  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.716  3264  3326 I jxcore-log: 
,03-31 18:06:39.719  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.719  3264  3326 I jxcore-log: 
,03-31 18:06:39.721  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.721  3264  3326 I jxcore-log: 
,03-31 18:06:39.722  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.722  3264  3326 I jxcore-log: 
,03-31 18:06:39.724  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.724  3264  3326 I jxcore-log: 
,03-31 18:06:39.725  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.725  3264  3326 I jxcore-log: 
,03-31 18:06:39.727  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.727  3264  3326 I jxcore-log: 
,03-31 18:06:39.728  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.728  3264  3326 I jxcore-log: 
,03-31 18:06:39.730  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.730  3264  3326 I jxcore-log: 
,03-31 18:06:39.732  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.732  3264  3326 I jxcore-log: 
,03-31 18:06:39.734  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.734  3264  3326 I jxcore-log: 
,03-31 18:06:39.735  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.735  3264  3326 I jxcore-log: 
,03-31 18:06:39.737  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.737  3264  3326 I jxcore-log: 
,03-31 18:06:39.738  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.738  3264  3326 I jxcore-log: 
,03-31 18:06:39.740  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.740  3264  3326 I jxcore-log: 
,03-31 18:06:39.741  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.741  3264  3326 I jxcore-log: 
,03-31 18:06:39.743  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.743  3264  3326 I jxcore-log: 
,03-31 18:06:39.745  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.745  3264  3326 I jxcore-log: 
,03-31 18:06:39.747  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.747  3264  3326 I jxcore-log: 
,03-31 18:06:39.748  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.748  3264  3326 I jxcore-log: 
,03-31 18:06:39.750  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.750  3264  3326 I jxcore-log: 
,03-31 18:06:39.751  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.751  3264  3326 I jxcore-log: 
,03-31 18:06:39.753  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.753  3264  3326 I jxcore-log: 
,03-31 18:06:39.754  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:39.754  3264  3326 I jxcore-log: 
,03-31 18:06:39.756  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:39.756  3264  3326 I jxcore-log: 
,03-31 18:06:39.830  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.830  3264  3326 I jxcore-log: 
,03-31 18:06:39.832  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 18:06:39.832  3264  3326 I jxcore-log: 
03-31 18:06:39.833  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.833  3264  3326 I jxcore-log: 
,03-31 18:06:39.836  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.836  3264  3326 I jxcore-log: 
,03-31 18:06:39.838  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:39.838  3264  3326 I jxcore-log: 
,03-31 18:06:39.840  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.840  3264  3326 I jxcore-log: 
03-31 18:06:39.841  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.841  3264  3326 I jxcore-log: 
,03-31 18:06:39.843  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.843  3264  3326 I jxcore-log: 
03-31 18:06:39.844  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.844  3264  3326 I jxcore-log: ,
,03-31 18:06:39.846  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close,
03-31 18:06:39.846  3264  3326 I jxcore-log: 
,03-31 18:06:39.850  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 18:06:39.850  3264  3326 I jxcore-log: 
,03-31 18:06:39.851  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.851  3264  3326 I jxcore-log: 
,03-31 18:06:39.853  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.853  3264  3326 I jxcore-log: 
,03-31 18:06:39.855  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.855  3264  3326 I jxcore-log: 
,03-31 18:06:39.857  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close,
03-31 18:06:39.857  3264  3326 I jxcore-log: 
03-31 18:06:39.858  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
,03-31 18:06:39.858  3264  3326 I jxcore-log: 
,03-31 18:06:39.860  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.860  3264  3326 I jxcore-log: 
,03-31 18:06:39.862  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.862  3264  3326 I jxcore-log: 
,03-31 18:06:39.864  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.864  3264  3326 I jxcore-log: 
,03-31 18:06:39.865  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close,
03-31 18:06:39.865  3264  3326 I jxcore-log: 
,03-31 18:06:39.867  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.867  3264  3326 I jxcore-log: 
,03-31 18:06:39.869  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.869  3264  3326 I jxcore-log: 
,03-31 18:06:39.871  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.871  3264  3326 I jxcore-log: 
,03-31 18:06:39.872  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.872  3264  3326 I jxcore-log: 
,03-31 18:06:39.874  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
,03-31 18:06:39.874  3264  3326 I jxcore-log: 
,03-31 18:06:39.876  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.876  3264  3326 I jxcore-log: 
,03-31 18:06:39.878  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.878  3264  3326 I jxcore-log: 
,03-31 18:06:39.879  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.879  3264  3326 I jxcore-log: 
,03-31 18:06:39.881  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.881  3264  3326 I jxcore-log: 
,03-31 18:06:39.883  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close,
03-31 18:06:39.883  3264  3326 I jxcore-log: 
,03-31 18:06:39.885  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:,
03-31 18:06:39.885  3264  3326 I jxcore-log: 
,03-31 18:06:39.887  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.887  3264  3326 I jxcore-log: 
,03-31 18:06:39.888  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.888  3264  3326 I jxcore-log: 
,03-31 18:06:39.889  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.889  3264  3326 I jxcore-log: 
,03-31 18:06:39.890  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:39.890  3264  3326 I jxcore-log: 
03-31 18:06:39.891  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.891  3264  3326 I jxcore-log: 
,03-31 18:06:39.893  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.893  3264  3326 I jxcore-log: 
,03-31 18:06:39.894  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.894  3264  3326 I jxcore-log: 
,03-31 18:06:39.896  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.896  3264  3326 I jxcore-log: 
,03-31 18:06:39.897  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:39.897  3264  3326 I jxcore-log: 
,03-31 18:06:39.898  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.898  3264  3326 I jxcore-log: 
,03-31 18:06:39.900  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.900  3264  3326 I jxcore-log: 
,03-31 18:06:39.901  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.901  3264  3326 I jxcore-log: 
,03-31 18:06:39.902  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.902  3264  3326 I jxcore-log: 
,03-31 18:06:39.904  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:39.904  3264  3326 I jxcore-log: 
,03-31 18:06:39.905  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.905  3264  3326 I jxcore-log: 
,03-31 18:06:39.907  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.907  3264  3326 I jxcore-log: 
03-31 18:06:39.908  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.908  3264  3326 I jxcore-log: 
03-31 18:06:39.909  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:39.909  3264  3326 I jxcore-log: 
,03-31 18:06:39.910  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:39.910  3264  3326 I jxcore-log: 
,03-31 18:06:39.914  3264  3326 I jxcore-log: ok 28 native server is nulled out
03-31 18:06:39.914  3264  3326 I jxcore-log: 
,03-31 18:06:39.915  3264  3326 I jxcore-log: ok 29 native server should be closed
03-31 18:06:39.915  3264  3326 I jxcore-log: 
03-31 18:06:39.915  3264  3326 I jxcore-log: ok 30 incoming has been removed
03-31 18:06:39.915  3264  3326 I jxcore-log: 
03-31 18:06:39.916  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.916  3264  3326 I jxcore-log: 
,03-31 18:06:39.917  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.917  3264  3326 I jxcore-log: 
03-31 18:06:39.917  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.917  3264  3326 I jxcore-log: 
03-31 18:06:39.917  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.917  3264  3326 I jxcore-log: 
,03-31 18:06:39.918  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.918  3264  3326 I jxcore-log: 
03-31 18:06:39.918  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.918  3264  3326 I jxcore-log: 
03-31 18:06:39.918  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.918  3264  3326 I jxcore-log: 
,03-31 18:06:39.919  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.919  3264  3326 I jxcore-log: 
03-31 18:06:39.919  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.919  3264  3326 I jxcore-log: 
03-31 18:06:39.919  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:39.919  3264  3326 I jxcore-log: 
,03-31 18:06:40.055  3264  3326 I jxcore-log: # teardown
03-31 18:06:40.055  3264  3326 I jxcore-log: 
,03-31 18:06:41.155  3264  3326 I jxcore-log: # setup
03-31 18:06:41.155  3264  3326 I jxcore-log: 
,03-31 18:06:41.409  3264  3326 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-31 18:06:41.409  3264  3326 I jxcore-log: 
,03-31 18:06:41.963  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 18:06:41.963  3264  3326 I jxcore-log: 
03-31 18:06:41.966  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 51398
03-31 18:06:41.966  3264  3326 I jxcore-log: 
,03-31 18:06:41.973  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-31 18:06:41.973  3264  3326 I jxcore-log: 
03-31 18:06:41.975  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:41.975  3264  3326 I jxcore-log: 
,03-31 18:06:41.977  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux,
03-31 18:06:41.977  3264  3326 I jxcore-log: 
,03-31 18:06:41.986  3264  3326 I jxcore-log: ok 31 we should not have gotten an error,
03-31 18:06:41.986  3264  3326 I jxcore-log: 
,03-31 18:06:41.990  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-31 18:06:41.990  3264  3326 I jxcore-log: 
,03-31 18:06:41.993  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:41.993  3264  3326 I jxcore-log: 
,03-31 18:06:42.002  3264  3326 I jxcore-log: ok 32 Buffers are identical
03-31 18:06:42.002  3264  3326 I jxcore-log: 
,03-31 18:06:42.003  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:42.003  3264  3326 I jxcore-log: 
,03-31 18:06:42.005  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:42.005  3264  3326 I jxcore-log: 
,03-31 18:06:42.015  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:06:42.015  3264  3326 I jxcore-log: 
,03-31 18:06:42.016  3264  3326 I jxcore-log: ok 33 server should be fine
03-31 18:06:42.016  3264  3326 I jxcore-log: 
,03-31 18:06:42.017  3264  3326 I jxcore-log: ok 34 server should be open
03-31 18:06:42.017  3264  3326 I jxcore-log: 
03-31 18:06:42.017  3264  3326 I jxcore-log: ok 35 incoming has been removed
03-31 18:06:42.017  3264  3326 I jxcore-log: 
03-31 18:06:42.017  3264  3326 I jxcore-log: ok 36 The mux object should be closed
03-31 18:06:42.017  3264  3326 I jxcore-log: 
,03-31 18:06:42.017  3264  3326 I jxcore-log: ok 37 The mux stream should be closed
03-31 18:06:42.017  3264  3326 I jxcore-log: 
03-31 18:06:42.023  3264  3326 I jxcore-log: # teardown
03-31 18:06:42.023  3264  3326 I jxcore-log: 
,03-31 18:06:42.236  3264  3326 I jxcore-log: # setup
03-31 18:06:42.236  3264  3326 I jxcore-log: 
,03-31 18:06:42.520  3264  3326 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 18:06:42.520  3264  3326 I jxcore-log: 
,03-31 18:06:42.715  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:06:42.715  3264  3326 I jxcore-log: 
,03-31 18:06:42.724  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 35615
03-31 18:06:42.724  3264  3326 I jxcore-log: 
,03-31 18:06:42.730  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:06:42.730  3264  3326 I jxcore-log: 
,03-31 18:06:42.731  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:06:42.731  3264  3326 I jxcore-log: 
,03-31 18:06:42.733  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:06:42.733  3264  3326 I jxcore-log: 
,03-31 18:06:42.741  3264  3326 I jxcore-log: ok 38 we should not have gotten an error
03-31 18:06:42.741  3264  3326 I jxcore-log: 
,03-31 18:06:42.745  3264  3326 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 18:06:42.745  3264  3326 I jxcore-log: 
,03-31 18:06:42.748  3264  3326 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 18:06:42.748  3264  3326 I jxcore-log: 
,03-31 18:06:42.755  3264  3326 I jxcore-log: ok 39 Buffers are identical
03-31 18:06:42.755  3264  3326 I jxcore-log: 
,03-31 18:06:42.760  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 18:06:42.760  3264  3326 I jxcore-log: 
,03-31 18:06:42.762  3264  3326 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 18:06:42.762  3264  3326 I jxcore-log: 
,03-31 18:06:42.765  3264  3326 I jxcore-log: DEBUG createNativeListener: mux close
03-31 18:06:42.765  3264  3326 I jxcore-log: 
,03-31 18:06:42.769  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-31 18:06:42.769  3264  3326 I jxcore-log: 
03-31 18:06:42.770  3264  3326 I jxcore-log: ok 40 server should be fine
03-31 18:06:42.770  3264  3326 I jxcore-log: 
,03-31 18:06:42.770  3264  3326 I jxcore-log: ok 41 server should be open
03-31 18:06:42.770  3264  3326 I jxcore-log: 
03-31 18:06:42.770  3264  3326 I jxcore-log: ok 42 incoming has been removed
03-31 18:06:42.770  3264  3326 I jxcore-log: 
,03-31 18:06:42.771  3264  3326 I jxcore-log: ok 43 The mux object should be closed
03-31 18:06:42.771  3264  3326 I jxcore-log: 
03-31 18:06:42.772  3264  3326 I jxcore-log: ok 44 The mux stream should be closed
03-31 18:06:42.772  3264  3326 I jxcore-log: 
,03-31 18:06:42.781  3264  3326 I jxcore-log: # teardown
03-31 18:06:42.781  3264  3326 I jxcore-log: 
,03-31 18:06:43.108  3264  3326 I jxcore-log: # setup
03-31 18:06:43.108  3264  3326 I jxcore-log: 
,03-31 18:06:44.009  3264  3326 I jxcore-log: # 12. closeAll can close even when connections open
03-31 18:06:44.009  3264  3326 I jxcore-log: 
,03-31 18:06:44.891  3264  3326 I jxcore-log: ok 45 not possible to connect to the server anymore,
03-31 18:06:44.891  3264  3326 I jxcore-log: 
,03-31 18:06:44.897  3264  3326 I jxcore-log: # teardown
03-31 18:06:44.897  3264  3326 I jxcore-log: 
,03-31 18:06:45.793  3264  3326 I jxcore-log: # setup
03-31 18:06:45.793  3264  3326 I jxcore-log: 
,03-31 18:06:49.234  3264  3326 I jxcore-log: # 13. closeAll with promise
03-31 18:06:49.234  3264  3326 I jxcore-log: 
,03-31 18:06:50.052  3264  3326 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 18:06:50.052  3264  3326 I jxcore-log: 
,03-31 18:06:50.057  3264  3326 I jxcore-log: # teardown
03-31 18:06:50.057  3264  3326 I jxcore-log: 
,03-31 18:06:50.756  3264  3326 I jxcore-log: # setup
03-31 18:06:50.756  3264  3326 I jxcore-log: 
,03-31 18:06:51.172  2156  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 18:06:52.754  3264  3326 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 18:06:52.754  3264  3326 I jxcore-log: 
,03-31 18:06:52.824  3473  3692 V KeepSync: Connecting to GoogleApiClient
,03-31 18:06:52.919  1376  1756 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-31 18:06:52.920  1376  1756 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-31 18:06:52.920  1376  1756 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:52.920  1376  1756 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:52.930  1376  1756 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 18:06:52.946  3264  3326 I jxcore-log: ok 47 Got the right error,
03-31 18:06:52.946  3264  3326 I jxcore-log: 
,03-31 18:06:52.947  3264  3326 I jxcore-log: # teardown
03-31 18:06:52.947  3264  3326 I jxcore-log: 
,03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: Handling authorization failure
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 18:06:52.959  1808  3693 E ClientConnectionOperation: 	... 7 more
,03-31 18:06:52.963  3473  3692 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 18:06:52.967  3473  3692 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 18:06:52.978  3473  3692 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 18:06:52.978  3473  3692 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 18:06:53.047  1376  1397 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 18:06:53.048  1376  1397 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 18:06:53.048  1376  1397 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:53.048  1376  1397 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:53.055  1376  1397 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:53.127  3473  3692 E KeepSync: IOException
03-31 18:06:53.127  3473  3692 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 18:06:53.127  3473  3692 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 18:06:53.127  3473  3692 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 18:06:53.127  3473  3692 E KeepSync: 	... 10 more
,03-31 18:06:53.128  3473  3692 W KeepSync: Sync result 2
,03-31 18:06:53.146   828   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 210348, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 18:06:54.974  3264  3326 I jxcore-log: # setup
03-31 18:06:54.974  3264  3326 I jxcore-log: 
,03-31 18:06:55.234  3264  3326 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true,
03-31 18:06:55.234  3264  3326 I jxcore-log: 
,03-31 18:06:56.176  3264  3326 I jxcore-log: # teardown
03-31 18:06:56.176  3264  3326 I jxcore-log: 
,03-31 18:06:57.725  3378  3698 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 18:06:57.788  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 18:06:57.788  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:06:57.789  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:06:57.789  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:06:57.797  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:06:57.815  3378  3698 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: ,	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 18:06:57.816  3378  3698 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 18:06:57.943  3264  3326 I jxcore-log: # setup
03-31 18:06:57.943  3264  3326 I jxcore-log: 
,03-31 18:06:59.586  3264  3326 I jxcore-log: # 16. multiplex can send data
,03-31 18:06:59.586  3264  3326 I jxcore-log: 
,03-31 18:07:01.096  3264  3326 I jxcore-log: ok 48 String should be length:200
03-31 18:07:01.096  3264  3326 I jxcore-log: 
,03-31 18:07:01.104  3264  3326 I jxcore-log: # teardown
03-31 18:07:01.104  3264  3326 I jxcore-log: 
,03-31 18:07:01.274  3264  3326 I jxcore-log: # setup
03-31 18:07:01.274  3264  3326 I jxcore-log: 
,03-31 18:07:01.598  3264  3326 I jxcore-log: # 17. enqueue and run in order
03-31 18:07:01.598  3264  3326 I jxcore-log: 
,03-31 18:07:03.229  3264  3326 I jxcore-log: ok 49 firstPromise setTimeout
03-31 18:07:03.229  3264  3326 I jxcore-log: 
,03-31 18:07:03.232  3264  3326 I jxcore-log: ok 50 firstPromise result
03-31 18:07:03.232  3264  3326 I jxcore-log: 
,03-31 18:07:03.233  3264  3326 I jxcore-log: ok 51 firstPromise testValue
03-31 18:07:03.233  3264  3326 I jxcore-log: 
,03-31 18:07:03.336  3264  3326 I jxcore-log: ok 52 secondPromise setTimeout
03-31 18:07:03.336  3264  3326 I jxcore-log: 
,03-31 18:07:03.340  3264  3326 I jxcore-log: ok 53 secondPromise result
03-31 18:07:03.340  3264  3326 I jxcore-log: 
,03-31 18:07:03.342  3264  3326 I jxcore-log: ok 54 secondPromise testValue
03-31 18:07:03.342  3264  3326 I jxcore-log: 
,03-31 18:07:03.344  3264  3326 I jxcore-log: ok 55 thirdPromise in promise
03-31 18:07:03.344  3264  3326 I jxcore-log: 
,03-31 18:07:03.346  3264  3326 I jxcore-log: ok 56 thirdPromise result
03-31 18:07:03.346  3264  3326 I jxcore-log: 
,03-31 18:07:03.348  3264  3326 I jxcore-log: ok 57 thirdPromise testValue
03-31 18:07:03.348  3264  3326 I jxcore-log: 
,03-31 18:07:03.360  3264  3326 I jxcore-log: # teardown
03-31 18:07:03.360  3264  3326 I jxcore-log: 
,03-31 18:07:03.676  3264  3326 I jxcore-log: # setup
03-31 18:07:03.676  3264  3326 I jxcore-log: 
,03-31 18:07:03.874  3264  3326 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 18:07:03.874  3264  3326 I jxcore-log: 
,03-31 18:07:04.027  3264  3326 I jxcore-log: ok 58 thirdPromise - first to run
03-31 18:07:04.027  3264  3326 I jxcore-log: 
,03-31 18:07:04.033  3264  3326 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 18:07:04.033  3264  3326 I jxcore-log: 
,03-31 18:07:04.034  3264  3326 I jxcore-log: ok 60 secondPromise - second to run
03-31 18:07:04.034  3264  3326 I jxcore-log: 
,03-31 18:07:04.035  3264  3326 I jxcore-log: ok 61 secondPromise - in catch
03-31 18:07:04.035  3264  3326 I jxcore-log: 
,03-31 18:07:04.035  3264  3326 I jxcore-log: ok 62 firstPromise - third to run
03-31 18:07:04.035  3264  3326 I jxcore-log: 
03-31 18:07:04.036  3264  3326 I jxcore-log: ok 63 firstPromise - in then
03-31 18:07:04.036  3264  3326 I jxcore-log: 
,03-31 18:07:04.036  3264  3326 I jxcore-log: ok 64 testing promises
03-31 18:07:04.036  3264  3326 I jxcore-log: 
03-31 18:07:04.039  3264  3326 I jxcore-log: # teardown
03-31 18:07:04.039  3264  3326 I jxcore-log: 
,03-31 18:07:04.193  3264  3326 I jxcore-log: # setup
03-31 18:07:04.193  3264  3326 I jxcore-log: 
,03-31 18:07:04.284  3264  3326 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 18:07:04.284  3264  3326 I jxcore-log: 
,03-31 18:07:04.417  3264  3326 I jxcore-log: ok 65 fourth
03-31 18:07:04.417  3264  3326 I jxcore-log: 
,03-31 18:07:04.420  3264  3326 I jxcore-log: ok 66 fourth
03-31 18:07:04.420  3264  3326 I jxcore-log: 
,03-31 18:07:04.423  3264  3326 I jxcore-log: ok 67 second
03-31 18:07:04.423  3264  3326 I jxcore-log: 
,03-31 18:07:04.426  3264  3326 I jxcore-log: ok 68 secondPromise - in then
03-31 18:07:04.426  3264  3326 I jxcore-log: 
,03-31 18:07:04.530  3264  3326 I jxcore-log: ok 69 first
03-31 18:07:04.530  3264  3326 I jxcore-log: 
,03-31 18:07:04.533  3264  3326 I jxcore-log: ok 70 firstPromise - in catch
03-31 18:07:04.533  3264  3326 I jxcore-log: 
,03-31 18:07:04.535  3264  3326 I jxcore-log: ok 71 third
03-31 18:07:04.535  3264  3326 I jxcore-log: 
,03-31 18:07:04.538  3264  3326 I jxcore-log: ok 72 thirdPromise - in then
03-31 18:07:04.538  3264  3326 I jxcore-log: 
,03-31 18:07:04.540  3264  3326 I jxcore-log: ok 73 testingPromises
03-31 18:07:04.540  3264  3326 I jxcore-log: 
,03-31 18:07:04.553  3264  3326 I jxcore-log: # teardown
03-31 18:07:04.553  3264  3326 I jxcore-log: 
,03-31 18:07:04.670  3264  3326 I jxcore-log: # setup
03-31 18:07:04.670  3264  3326 I jxcore-log: 
,03-31 18:07:04.873  3264  3326 I jxcore-log: # 20. queues handled independently
03-31 18:07:04.873  3264  3326 I jxcore-log: 
,03-31 18:07:05.025  3264  3326 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 18:07:05.025  3264  3326 I jxcore-log: 
,03-31 18:07:05.029  3264  3326 I jxcore-log: # teardown
03-31 18:07:05.029  3264  3326 I jxcore-log: 
,03-31 18:07:05.147  3264  3326 I jxcore-log: # setup
03-31 18:07:05.147  3264  3326 I jxcore-log: 
,03-31 18:07:05.284  3264  3326 I jxcore-log: # 21. basic
03-31 18:07:05.284  3264  3326 I jxcore-log: 
,03-31 18:07:05.421  3264  3326 I jxcore-log: ok 75 sane
03-31 18:07:05.421  3264  3326 I jxcore-log: 
,03-31 18:07:05.427  3264  3326 I jxcore-log: # teardown
03-31 18:07:05.427  3264  3326 I jxcore-log: 
,03-31 18:07:05.583  3264  3326 I jxcore-log: # setup
03-31 18:07:05.583  3264  3326 I jxcore-log: 
,03-31 18:07:05.743  3264  3326 I jxcore-log: # 22. another
03-31 18:07:05.743  3264  3326 I jxcore-log: 
,03-31 18:07:05.917  3264  3326 I jxcore-log: ok 76 sane
03-31 18:07:05.917  3264  3326 I jxcore-log: 
,03-31 18:07:05.923  3264  3326 I jxcore-log: # teardown
03-31 18:07:05.923  3264  3326 I jxcore-log: 
,03-31 18:07:06.038  3264  3326 I jxcore-log: # setup
03-31 18:07:06.038  3264  3326 I jxcore-log: 
,03-31 18:07:06.133  3264  3326 I jxcore-log: # 23. can pass data in setup
03-31 18:07:06.133  3264  3326 I jxcore-log: 
,03-31 18:07:06.242  3264  3326 I jxcore-log: ok 77 test participant has uuid
03-31 18:07:06.242  3264  3326 I jxcore-log: 
,03-31 18:07:06.244  3264  3326 I jxcore-log: ok 78 participant data matches
03-31 18:07:06.244  3264  3326 I jxcore-log: 
,03-31 18:07:06.246  3264  3326 I jxcore-log: ok 79 test participant has uuid
03-31 18:07:06.246  3264  3326 I jxcore-log: 
,03-31 18:07:06.247  3264  3326 I jxcore-log: ok 80 participant data matches
03-31 18:07:06.247  3264  3326 I jxcore-log: 
,03-31 18:07:06.248  3264  3326 I jxcore-log: ok 81 test participant has uuid
03-31 18:07:06.248  3264  3326 I jxcore-log: 
03-31 18:07:06.250  3264  3326 I jxcore-log: ok 82 participant data matches
03-31 18:07:06.250  3264  3326 I jxcore-log: 
,03-31 18:07:06.252  3264  3326 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 18:07:06.252  3264  3326 I jxcore-log: 
,03-31 18:07:06.258  3264  3326 I jxcore-log: # teardown
03-31 18:07:06.258  3264  3326 I jxcore-log: 
,03-31 18:07:06.431  3264  3326 I jxcore-log: # setup
03-31 18:07:06.431  3264  3326 I jxcore-log: 
,03-31 18:07:06.547  3264  3326 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 18:07:06.547  3264  3326 I jxcore-log: 
,03-31 18:07:06.656  3264  3326 I jxcore-log: ok 84 specific error should be returned
03-31 18:07:06.656  3264  3326 I jxcore-log: 
,03-31 18:07:06.663  3264  3326 I jxcore-log: # teardown
03-31 18:07:06.663  3264  3326 I jxcore-log: 
,03-31 18:07:06.798  3264  3326 I jxcore-log: ok 85 error should be null
03-31 18:07:06.798  3264  3326 I jxcore-log: 
,03-31 18:07:06.800  3264  3326 I jxcore-log: ok 86 error should be null
03-31 18:07:06.800  3264  3326 I jxcore-log: 
,03-31 18:07:06.806  3264  3326 I jxcore-log: # setup
03-31 18:07:06.806  3264  3326 I jxcore-log: 
,03-31 18:07:07.006  3264  3326 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called,
03-31 18:07:07.006  3264  3326 I jxcore-log: 
,03-31 18:07:07.294  3264  3326 I jxcore-log: ok 87 specific error should be returned
03-31 18:07:07.294  3264  3326 I jxcore-log: 
03-31 18:07:07.296  3264  3326 I jxcore-log: # teardown,
03-31 18:07:07.296  3264  3326 I jxcore-log: 
,03-31 18:07:07.438  3264  3326 I jxcore-log: ok 88 error should be null
03-31 18:07:07.438  3264  3326 I jxcore-log: 
,03-31 18:07:07.440  3264  3326 I jxcore-log: ok 89 error should be null
03-31 18:07:07.440  3264  3326 I jxcore-log: 
,03-31 18:07:07.446  3264  3326 I jxcore-log: # setup,
03-31 18:07:07.446  3264  3326 I jxcore-log: 
,03-31 18:07:07.844  3264  3326 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times,
03-31 18:07:07.844  3264  3326 I jxcore-log: 
,03-31 18:07:07.990  1234  1459 I Keyboard.Facilitator.LanguageModelFlusher: run(),
03-31 18:07:07.990  1234  1459 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 18:07:08.019  1376  1376 I ConfigService: onCreate
,03-31 18:07:08.998  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:07:08.998  3264  3326 I jxcore-log: 
,03-31 18:07:09.000  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 33448
03-31 18:07:09.000  3264  3326 I jxcore-log: 
,03-31 18:07:09.002  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:07:09.003  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:09.003  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:09.007  3264  3326 I jxcore-log: ok 90 error should be null
03-31 18:07:09.007  3264  3326 I jxcore-log: 
03-31 18:07:09.008  3264  3326 I jxcore-log: ok 91 error should be null
03-31 18:07:09.008  3264  3326 I jxcore-log: 
,03-31 18:07:09.009  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:09.009  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:09.009  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:09.012  3264  3326 I jxcore-log: ok 92 error should be null
03-31 18:07:09.012  3264  3326 I jxcore-log: 
,03-31 18:07:09.013  3264  3326 I jxcore-log: ok 93 error should be null
03-31 18:07:09.013  3264  3326 I jxcore-log: 
,03-31 18:07:09.017  3264  3326 I jxcore-log: # teardown
03-31 18:07:09.017  3264  3326 I jxcore-log: 
,03-31 18:07:09.225  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:09.225  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 18:07:09.225  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:09.229  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:09.229  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:09.229  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:09.234  3264  3326 I jxcore-log: ok 94 error should be null
03-31 18:07:09.234  3264  3326 I jxcore-log: 
,03-31 18:07:09.235  3264  3326 I jxcore-log: ok 95 error should be null
03-31 18:07:09.235  3264  3326 I jxcore-log: 
03-31 18:07:09.240  3264  3326 I jxcore-log: # setup
03-31 18:07:09.240  3264  3326 I jxcore-log: 
,03-31 18:07:10.123  3264  3326 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 18:07:10.123  3264  3326 I jxcore-log: 
,03-31 18:07:10.336  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:07:10.336  3264  3326 I jxcore-log: 
,03-31 18:07:10.337  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 43635
03-31 18:07:10.337  3264  3326 I jxcore-log: 
,03-31 18:07:10.347  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 18:07:10.347  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:10.347  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:10.347  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-31 18:07:10.347  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:10.347  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:07:10.354  3264  3326 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 18:07:10.355   828  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:10.362  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:10.367  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 18:07:10.367  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:10.367  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:10.368  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:10.375  2156  2221 D BtGatt.GattService: registerClient() - UUID=e0459335-2079-4ed3-a013-2b6a0cbf54b3,
03-31 18:07:10.376  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=e0459335-2079-4ed3-a013-2b6a0cbf54b3, clientIf=5
,03-31 18:07:10.379  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:10.380  2156  2173 D BtGatt.GattService: start scan with filters
,03-31 18:07:10.383  2156  2232 D BtGatt.ScanManager: handling starting scan,
03-31 18:07:10.383  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:10.384  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:10.385  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:07:10.385  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:10.385  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:07:10.386  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 18:07:10.386  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:10.386  2156  2232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29002be7
03-31 18:07:10.387   828   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:10.397  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:10.397  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 18:07:10.398  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:10.399  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:10.399  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:10.399  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:07:10.399  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:07:10.400  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:10.402  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:10.402  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:10.403  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:10.403  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:07:10.406  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 18:07:10.406  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:10.408  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:10.408  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:10.410  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:10.410  3264  3326 I jxcore-log: 
03-31 18:07:10.411  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:10.411  3264  3326 I jxcore-log: 
,03-31 18:07:10.413  3264  3326 I jxcore-log: ok 96 error should be null
03-31 18:07:10.413  3264  3326 I jxcore-log: 
,03-31 18:07:10.414  3264  3326 I jxcore-log: ok 97 error should be null
03-31 18:07:10.414  3264  3326 I jxcore-log: 
,03-31 18:07:10.419  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-31 18:07:10.419  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:07:10.419  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:10.419  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:07:10.419  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:07:10.422  3264  3326 I jxcore-log: ok 98 error should be null
03-31 18:07:10.422  3264  3326 I jxcore-log: 
03-31 18:07:10.423  3264  3326 I jxcore-log: ok 99 error should be null
03-31 18:07:10.423  3264  3326 I jxcore-log: 
,03-31 18:07:10.428  3264  3326 I jxcore-log: # teardown
03-31 18:07:10.428  3264  3326 I jxcore-log: 
,03-31 18:07:10.904  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:10.904  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:10.905  3264  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 18:07:10.905  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 18:07:10.905  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 18:07:10.905  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:10.905  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:10.906  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:10.906  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:10.908  2156  2221 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:07:10.909  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:10.910  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:10.910  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:07:10.910  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 18:07:10.910  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 18:07:10.910  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 18:07:10.910  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:10.910  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:10.910  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:10.910  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:07:10.912  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:10.912  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:10.913  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:07:10.913  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 18:07:10.913  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:10.913  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:10.913  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:10.913  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:07:10.914  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 18:07:10.914  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:10.914  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:10.916  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:07:10.916  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:10.924  3264  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 18:07:10.924  3264  3326 I jxcore-log: 
03-31 18:07:10.925  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:07:10.925   828  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:10.930  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:10.932  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:10.932  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:10.935  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 18:07:10.936  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:10.936  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:10.936  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:07:10.939  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:07:10.940  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:10.940  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:10.942  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:10.942  3264  3326 I jxcore-log: 
,03-31 18:07:10.943  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:10.943  3264  3326 I jxcore-log: 
03-31 18:07:10.946  3264  3326 I jxcore-log: ok 100 error should be null
03-31 18:07:10.946  3264  3326 I jxcore-log: 
,03-31 18:07:10.947  3264  3326 I jxcore-log: ok 101 error should be null
,03-31 18:07:10.947  3264  3326 I jxcore-log: 
03-31 18:07:10.952  3264  3326 I jxcore-log: # setup
03-31 18:07:10.952  3264  3326 I jxcore-log: 
,03-31 18:07:11.415  3264  3326 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 18:07:11.415  3264  3326 I jxcore-log: 
,03-31 18:07:12.024  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:07:12.024  3264  3326 I jxcore-log: 
,03-31 18:07:12.027  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 50573
03-31 18:07:12.027  3264  3326 I jxcore-log: 
,03-31 18:07:12.046  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 50573, start advertisements: true
,03-31 18:07:12.046  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:12.046  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 18:07:12.046  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:07:12.051  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 18:07:12.051  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:12.051  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-31 18:07:12.051  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:12.056  2156  2221 D BtGatt.GattService: registerClient() - UUID=b29153e8-1338-491d-ad3c-abf723839ac1
,03-31 18:07:12.057  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=b29153e8-1338-491d-ad3c-abf723839ac1, clientIf=5
03-31 18:07:12.057  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
,03-31 18:07:12.057  2156  2174 D BtGatt.GattService: start scan with filters
03-31 18:07:12.059  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:12.059  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-31 18:07:12.059  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 18:07:12.059  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:12.060  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:12.060  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:12.061  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:12.061  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 18:07:12.064  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 18:07:12.066  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 18:07:12.067  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 18:07:12.068  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:12.069  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 18:07:12.069  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-31 18:07:12.069  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:12.069  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:12.069  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:07:12.070  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:12.070  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:07:12.072  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 18:07:12.072  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:12.074  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 18:07:12.074  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:12.079  2156  2173 D BtGatt.GattService: registerClient() - UUID=e8cb869c-c95f-43f3-9421-d8f151cf1a39
,03-31 18:07:12.080  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=e8cb869c-c95f-43f3-9421-d8f151cf1a39, clientIf=6
,03-31 18:07:12.080  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:07:12.083  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:07:12.087  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:12.090  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:12.092  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 18:07:12.093  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 18:07:12.093  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:12.094   828  1306 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:12.099  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:07:12.100  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 18:07:12.100  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 18:07:12.100  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:12.102  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 18:07:12.103  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:07:12.103  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 18:07:12.104  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 18:07:12.104  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:07:12.104  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:12.104  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 18:07:12.104  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:07:12.104  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 18:07:12.105  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:07:12.105  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 18:07:12.105  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:12.105  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:12.105  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:12.105  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:07:12.105  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:07:12.105  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 18:07:12.109   828  1252 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:12.111  3264  3702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 18:07:12.116  3264  3702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-31 18:07:12.123  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-31 18:07:12.123  3264  3326 I jxcore-log: 
,03-31 18:07:12.125  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:12.125  3264  3326 I jxcore-log: 
,03-31 18:07:12.126  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:07:12.126  3264  3326 I jxcore-log: 
,03-31 18:07:12.128  3264  3326 I jxcore-log: ok 102 error should be null
,03-31 18:07:12.128  3264  3326 I jxcore-log: 
,03-31 18:07:12.128  3264  3326 I jxcore-log: ok 103 error should be null
,03-31 18:07:12.128  3264  3326 I jxcore-log: 
,03-31 18:07:12.137  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 50573, start advertisements: true
,03-31 18:07:12.137  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:12.137  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:12.137  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:12.137  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:07:12.146  3264  3326 I jxcore-log: ok 104 error should be null
,03-31 18:07:12.146  3264  3326 I jxcore-log: 
03-31 18:07:12.146  3264  3326 I jxcore-log: ok 105 error should be null
03-31 18:07:12.146  3264  3326 I jxcore-log: 
,03-31 18:07:12.153  3264  3326 I jxcore-log: # teardown
03-31 18:07:12.153  3264  3326 I jxcore-log: ,
,03-31 18:07:12.544  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:07:12.544  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 18:07:12.544  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:07:12.544  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:07:12.544  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:07:12.544  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 18:07:12.544  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:12.544  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:07:12.544  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:12.544  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:12.545  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:12.545  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:12.545  3264  3702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:07:12.545  3264  3702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:07:12.545  3264  3702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:07:12.546  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:07:12.547  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:12.548  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:12.548  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:12.548  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:12.548  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 18:07:12.548  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:07:12.548  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:12.548  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:07:12.548  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:12.549  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:12.549  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:07:12.552  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:12.553  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:12.553  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:12.554  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:12.554  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:07:12.557  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-31 18:07:12.558  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:12.558  2156  2219 D BtGatt.GattService: current time is 230216859857
,03-31 18:07:12.558  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -48, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 2, 125, -60, -52, -6, 90, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-31 18:07:12.560  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:12.562  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:12.563  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:07:12.563  2156  2219 D BtGatt.GattService: Client app is not null!,
03-31 18:07:12.565  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:12.566  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:07:12.566  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:12.567  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:07:12.567  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 18:07:12.567  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 18:07:12.567  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:12.567  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:12.567  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:07:12.569  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 18:07:12.569  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:12.569  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:12.569  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:12.570  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:07:12.583  3264  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 18:07:12.583  3264  3326 I jxcore-log: 
,03-31 18:07:12.583  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 18:07:12.584   828  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:12.591  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:12.594  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 18:07:12.594  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:12.597  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 18:07:12.597  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:07:12.598  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:12.598  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:12.598  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:12.598  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:12.598  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:12.598  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 18:07:12.599  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:12.599  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:12.599  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:07:12.600  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:07:12.600  3264  3326 I jxcore-log: 
,03-31 18:07:12.601  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:12.601  3264  3326 I jxcore-log: 
03-31 18:07:12.602  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:12.602  3264  3326 I jxcore-log: 
,03-31 18:07:12.606  3264  3326 I jxcore-log: ok 106 error should be null
03-31 18:07:12.606  3264  3326 I jxcore-log: 
,03-31 18:07:12.607  3264  3326 I jxcore-log: ok 107 error should be null
03-31 18:07:12.607  3264  3326 I jxcore-log: 
,03-31 18:07:12.612  3264  3326 I jxcore-log: # setup
03-31 18:07:12.612  3264  3326 I jxcore-log: 
,03-31 18:07:12.791  3264  3326 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 18:07:12.791  3264  3326 I jxcore-log: 
,03-31 18:07:13.074  1376  1376 I ConfigService: onDestroy
,03-31 18:07:13.250  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 18:07:13.250  3264  3326 I jxcore-log: 
,03-31 18:07:13.254  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 50100
,03-31 18:07:13.254  3264  3326 I jxcore-log: 
,03-31 18:07:13.260  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:13.260  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:13.260  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:13.264  3264  3326 I jxcore-log: ok 108 error should be null,
03-31 18:07:13.264  3264  3326 I jxcore-log: 
,03-31 18:07:13.265  3264  3326 I jxcore-log: ok 109 error should be null
03-31 18:07:13.265  3264  3326 I jxcore-log: 
,03-31 18:07:13.269  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:13.269  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:13.269  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:13.272  3264  3326 I jxcore-log: ok 110 error should be null
03-31 18:07:13.272  3264  3326 I jxcore-log: 
,03-31 18:07:13.273  3264  3326 I jxcore-log: ok 111 error should be null
03-31 18:07:13.273  3264  3326 I jxcore-log: 
,03-31 18:07:13.280  3264  3326 I jxcore-log: # teardown
03-31 18:07:13.280  3264  3326 I jxcore-log: 
,03-31 18:07:14.634  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:14.634  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:14.634  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:07:14.636  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:07:14.636  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:14.637  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:14.641  3264  3326 I jxcore-log: ok 112 error should be null
03-31 18:07:14.641  3264  3326 I jxcore-log: 
,03-31 18:07:14.642  3264  3326 I jxcore-log: ok 113 error should be null
03-31 18:07:14.642  3264  3326 I jxcore-log: 
,03-31 18:07:14.647  3264  3326 I jxcore-log: # setup
03-31 18:07:14.647  3264  3326 I jxcore-log: 
,03-31 18:07:14.824  3264  3326 I jxcore-log: # 30. #start should fail if called twice in a row
03-31 18:07:14.824  3264  3326 I jxcore-log: 
,03-31 18:07:15.842  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:07:15.842  3264  3326 I jxcore-log: 
,03-31 18:07:15.845  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 33864
03-31 18:07:15.845  3264  3326 I jxcore-log: 
,03-31 18:07:15.848  3264  3326 I jxcore-log: ok 114 first call should succeed
03-31 18:07:15.848  3264  3326 I jxcore-log: 
,03-31 18:07:15.848  3264  3326 I jxcore-log: ok 115 first call should succeed
03-31 18:07:15.848  3264  3326 I jxcore-log: 
,03-31 18:07:15.851  3264  3326 I jxcore-log: ok 116 specific error should be returned
03-31 18:07:15.851  3264  3326 I jxcore-log: 
,03-31 18:07:15.854  3264  3326 I jxcore-log: # teardown
03-31 18:07:15.854  3264  3326 I jxcore-log: 
,03-31 18:07:16.614  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:16.614  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:16.614  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:16.616  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:16.616  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:16.616  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:16.620  3264  3326 I jxcore-log: ok 117 error should be null
03-31 18:07:16.620  3264  3326 I jxcore-log: 
03-31 18:07:16.621  3264  3326 I jxcore-log: ok 118 error should be null
03-31 18:07:16.621  3264  3326 I jxcore-log: 
,03-31 18:07:16.626  3264  3326 I jxcore-log: # setup
03-31 18:07:16.626  3264  3326 I jxcore-log: 
,03-31 18:07:16.861  3264  3326 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
,03-31 18:07:16.861  3264  3326 I jxcore-log: 
,03-31 18:07:18.188  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
,03-31 18:07:18.188  3264  3326 I jxcore-log: 
03-31 18:07:18.190  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 49467
03-31 18:07:18.190  3264  3326 I jxcore-log: 
,03-31 18:07:18.199  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 50573, start advertisements: false,
03-31 18:07:18.199  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:07:18.199  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,03-31 18:07:18.199  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 18:07:18.204  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:18.204  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 18:07:18.204  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:18.209  2156  2173 D BtGatt.GattService: registerClient() - UUID=6e02b7fa-5494-4c69-8251-ece221a83b8d
,03-31 18:07:18.209  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=6e02b7fa-5494-4c69-8251-ece221a83b8d, clientIf=5
03-31 18:07:18.210  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:18.210  2156  2174 D BtGatt.GattService: start scan with filters
,03-31 18:07:18.211  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:18.211  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:18.212  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-31 18:07:18.212  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:18.212  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:07:18.212  2156  2232 D BtGatt.ScanManager: handling starting scan
03-31 18:07:18.212  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:18.212  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 18:07:18.215   828  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:18.222  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:18.222  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:18.222  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:18.222  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-31 18:07:18.223  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:18.223  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:18.223  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:18.223  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:18.225  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-31 18:07:18.225  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:18.225  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:18.225  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:07:18.227  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 18:07:18.227  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:18.228  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:18.228  3264  3326 I jxcore-log: 
,03-31 18:07:18.229  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:18.229  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:18.229  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:18.229  3264  3326 I jxcore-log: 
,03-31 18:07:18.246  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 49467, start advertisements: true
,03-31 18:07:18.246  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:18.246  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:18.246  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:07:18.251  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 18:07:18.251  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 18:07:18.251  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:07:18.251  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:07:18.252  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 18:07:18.252  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:18.252  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:18.252  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:18.256  2156  2221 D BtGatt.GattService: registerClient() - UUID=c8a4aacd-cfc1-4fc3-94bd-2824c031626f
,03-31 18:07:18.256  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=c8a4aacd-cfc1-4fc3-94bd-2824c031626f, clientIf=6
03-31 18:07:18.257  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:07:18.258  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:07:18.263  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:18.266  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:18.268  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:07:18.269  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:07:18.269  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-31 18:07:18.269  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:18.269  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 18:07:18.269  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:07:18.270  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:07:18.270  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:07:18.270   828   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:18.273  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 18:07:18.273  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:18.273  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:07:18.273  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:18.274  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 18:07:18.275  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 18:07:18.276  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:07:18.276  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:07:18.276  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 18:07:18.276  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:18.276  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:18.276  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:18.276  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:07:18.279   828  1456 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:18.282  3264  3704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 18:07:18.285  3264  3704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 18:07:18.290  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:07:18.290  3264  3326 I jxcore-log: 
,03-31 18:07:18.303  3264  3326 I jxcore-log: ok 119 called only once
03-31 18:07:18.303  3264  3326 I jxcore-log: 
,03-31 18:07:18.305  3264  3326 I jxcore-log: ok 120 discovery state matches
03-31 18:07:18.305  3264  3326 I jxcore-log: ,
03-31 18:07:18.306  3264  3326 I jxcore-log: ok 121 advertising state matches
03-31 18:07:18.306  3264  3326 I jxcore-log: 
,03-31 18:07:18.318  3264  3326 I jxcore-log: # teardown
03-31 18:07:18.318  3264  3326 I jxcore-log: 
,03-31 18:07:18.597  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:18.597  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 18:07:18.598  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 18:07:18.598  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 18:07:18.598  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 18:07:18.598  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:07:18.598  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:18.598  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:07:18.598  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 18:07:18.598  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:18.598  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:18.598  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:18.598  3264  3704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:07:18.598  3264  3704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:07:18.599  3264  3704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:07:18.600  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:07:18.601  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:18.602  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:18.602  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:18.602  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:18.602  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 18:07:18.602  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:07:18.602  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:18.602  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:07:18.603  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:18.603  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:18.603  2156  2232 D BtGatt.ScanManager: stopping BLe Batch,
03-31 18:07:18.606  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:18.606  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:18.606  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:18.607  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:18.607  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6,
03-31 18:07:18.609  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:07:18.610  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:07:18.610  2156  2219 D BtGatt.GattService: current time is 236268823397
03-31 18:07:18.610  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -48, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 12, 55, -86, 46, -94, 74, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 18:07:18.611  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:18.612  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 18:07:18.612  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:07:18.612  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:07:18.614  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:18.614  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:07:18.615  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:18.615  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:07:18.615  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 18:07:18.615  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 18:07:18.615  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 18:07:18.615  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:18.616  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:07:18.617  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:18.617  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:18.618  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:18.618  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:18.618  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:07:18.627  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 18:07:18.628   828  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:18.630  3264  3326 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,03-31 18:07:18.630  3264  3326 I jxcore-log: 
03-31 18:07:18.632  3264  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 18:07:18.632  3264  3326 I jxcore-log: 
,03-31 18:07:18.634  3264  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 18:07:18.634  3264  3326 I jxcore-log: 
,03-31 18:07:18.636  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:18.637  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:18.637  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:18.640  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-31 18:07:18.640  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:07:18.640  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:18.641  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:18.641  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:18.641  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 18:07:18.641  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:18.641  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:07:18.643  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:07:18.643  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:18.643  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:07:18.644  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:07:18.644  3264  3326 I jxcore-log: 
,03-31 18:07:18.645  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:18.645  3264  3326 I jxcore-log: 
,03-31 18:07:18.646  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:18.646  3264  3326 I jxcore-log: 
,03-31 18:07:18.649  3264  3326 I jxcore-log: ok 122 error should be null
03-31 18:07:18.649  3264  3326 I jxcore-log: 
03-31 18:07:18.650  3264  3326 I jxcore-log: ok 123 error should be null
03-31 18:07:18.650  3264  3326 I jxcore-log: 
,03-31 18:07:18.655  3264  3326 I jxcore-log: # setup
03-31 18:07:18.655  3264  3326 I jxcore-log: 
,03-31 18:07:19.855  3264  3326 I jxcore-log: # 32. does not send duplicate availability changes
03-31 18:07:19.855  3264  3326 I jxcore-log: 
,03-31 18:07:20.941  3264  3326 I jxcore-log: ok 124 should be called once
03-31 18:07:20.941  3264  3326 I jxcore-log: 
,03-31 18:07:20.942  3264  3326 I jxcore-log: ok 125 should not have been called more than once
03-31 18:07:20.942  3264  3326 I jxcore-log: 
,03-31 18:07:20.945  3264  3326 I jxcore-log: # teardown
03-31 18:07:20.945  3264  3326 I jxcore-log: 
,03-31 18:07:22.777  3528  3707 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 18:07:22.813  3528  3708 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 18:07:22.866  1376  1756 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 18:07:22.866  1376  1756 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:07:22.866  1376  1756 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:07:22.866  1376  1756 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 18:07:22.867  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 18:07:22.867  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:07:22.867  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:07:22.867  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:07:22.871  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:07:22.875  1376  1756 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:07:22.898  3039  3706 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 18:07:22.898  3039  3706 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jdm.a(PG:82)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jcs.o(PG:406)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jcn.a(PG:1379)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jcs.i(PG:143)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at blb.a(PG:3937)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at czp.a(PG:18188)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at czp.a(PG:9081)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at czq.run(PG:1686)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:07:22.898  3039  3706 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jdj.a(PG:4091)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jdj.a(PG:1125)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jdm.a(PG:77)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	... 12 more
03-31 18:07:22.898  3039  3706 E HttpOperation: Caused by: faj: BadAuthentication
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at fal.a(PG:38)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	at jdj.a(PG:4089)
03-31 18:07:22.898  3039  3706 E HttpOperation: 	... 14 more
,03-31 18:07:22.961  1376  2549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 18:07:22.961  1376  2549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:07:22.962  1376  2549 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:07:22.962  1376  2549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:07:22.965  1376  2549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:07:22.977  1376  1756 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 18:07:22.977  1376  1756 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 18:07:22.977  1376  1756 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:07:22.977  1376  1756 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:07:22.982  3039  3706 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 18:07:22.982  3039  3706 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jdm.a(PG:82)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jcs.o(PG:406)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jcn.a(PG:1379)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jcs.i(PG:143)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at hec.a(PG:42)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at hee.a(PG:102)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at czr.a(PG:65)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at kka.a(PG:108)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at czp.a(PG:19176)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at czp.a(PG:9081)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at czq.run(PG:1686)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:07:22.982  3039  3706 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jdj.a(PG:4091)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jdj.a(PG:1125)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jdm.a(PG:77)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	... 15 more
03-31 18:07:22.982  3039  3706 E HttpOperation: Caused by: faj: BadAuthentication
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at fal.a(PG:38)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	at jdj.a(PG:4089)
03-31 18:07:22.982  3039  3706 E HttpOperation: 	... 17 more
03-31 18:07:22.983  1376  1756 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 18:07:22.983  3039  3706 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 18:07:22.983  3039  3706 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at hec.a(PG:42)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at hee.a(PG:102)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at czr.a(PG:65)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at kka.a(PG:108)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: Caused by: android.accounts.Authenticato,rException: Recoverable error
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	... 15 more
03-31 18:07:22.983  3039  3706 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at fal.a(PG:38)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 18:07:22.983  3039  3706 E ExperimentLoader: 	... 17 more
,03-31 18:07:22.999  3528  3708 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 18:07:23.002  3528  3707 E BooksSync: Soft error
03-31 18:07:23.002  3528  3707 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 18:07:23.002  3528  3707 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 18:07:23.002  3528  3707 E BooksSync: Sync error
03-31 18:07:23.002  3528  3707 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 18:07:23.002  3528  3707 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 18:07:23.002  3528  3707 I BooksSync: Finished books sync
,03-31 18:07:23.010   828   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212816, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 18:07:23.092   828   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 210941, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 18:07:24.684  3264  3326 I jxcore-log: ok 126 error should be null
03-31 18:07:24.684  3264  3326 I jxcore-log: 
,03-31 18:07:24.684  3264  3326 I jxcore-log: ok 127 error should be null
03-31 18:07:24.684  3264  3326 I jxcore-log: 
03-31 18:07:24.686  3264  3326 I jxcore-log: # setup
03-31 18:07:24.686  3264  3326 I jxcore-log: 
,03-31 18:07:25.638  3264  3326 I jxcore-log: # 33. can get the network status
03-31 18:07:25.638  3264  3326 I jxcore-log: 
,03-31 18:07:27.484  3264  3326 I jxcore-log: ok 128 network status should have certain non-empty properties
,03-31 18:07:27.484  3264  3326 I jxcore-log: 
,03-31 18:07:27.486  3264  3326 I jxcore-log: # teardown
03-31 18:07:27.486  3264  3326 I jxcore-log: 
,03-31 18:07:29.177  3264  3326 I jxcore-log: ok 129 error should be null
03-31 18:07:29.177  3264  3326 I jxcore-log: 
,03-31 18:07:29.179  3264  3326 I jxcore-log: ok 130 error should be null
03-31 18:07:29.179  3264  3326 I jxcore-log: 
,03-31 18:07:29.195  3264  3326 I jxcore-log: # setup
03-31 18:07:29.195  3264  3326 I jxcore-log: 
,03-31 18:07:29.413  3264  3326 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 18:07:29.413  3264  3326 I jxcore-log: 
,03-31 18:07:29.437  2156  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 18:07:29.903  3264  3326 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 18:07:29.903  3264  3326 I jxcore-log: 
,03-31 18:07:29.927  3264  3326 I jxcore-log: ok 131 host address should match
03-31 18:07:29.927  3264  3326 I jxcore-log: 
,03-31 18:07:29.928  3264  3326 I jxcore-log: ok 132 port should match
03-31 18:07:29.928  3264  3326 I jxcore-log: 
,03-31 18:07:31.908  3264  3326 I jxcore-log: ok 133 host address should be null
03-31 18:07:31.908  3264  3326 I jxcore-log: 
,03-31 18:07:31.910  3264  3326 I jxcore-log: ok 134 port should should be null
03-31 18:07:31.910  3264  3326 I jxcore-log: 
,03-31 18:07:31.934  3264  3326 I jxcore-log: # teardown
03-31 18:07:31.934  3264  3326 I jxcore-log: 
,03-31 18:07:32.077  3264  3326 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 18:07:32.077  3264  3326 I jxcore-log: 
,03-31 18:07:32.079  3264  3326 I jxcore-log: ok 135 error should be null
03-31 18:07:32.079  3264  3326 I jxcore-log: 
,03-31 18:07:32.080  3264  3326 I jxcore-log: ok 136 error should be null
03-31 18:07:32.080  3264  3326 I jxcore-log: 
,03-31 18:07:32.083  3264  3326 I jxcore-log: # setup
03-31 18:07:32.083  3264  3326 I jxcore-log: 
,03-31 18:07:32.254  3264  3326 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 18:07:32.254  3264  3326 I jxcore-log: 
,03-31 18:07:33.375  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 49467, start advertisements: false
03-31 18:07:33.375  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:33.376  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:33.376  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 18:07:33.380  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:33.380  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:33.380  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:33.385  2156  2173 D BtGatt.GattService: registerClient() - UUID=263fc23e-695f-4847-a496-1e312d1179cd
03-31 18:07:33.386  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=263fc23e-695f-4847-a496-1e312d1179cd, clientIf=5
,03-31 18:07:33.387  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:33.387  2156  2174 D BtGatt.GattService: start scan with filters
03-31 18:07:33.388  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:33.388  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 18:07:33.388  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:07:33.388  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:33.388  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:33.388  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:33.388  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:33.389   828  1456 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:33.389  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:33.394  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:33.394  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:33.394  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:33.395  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:33.395  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:33.396  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:33.399  3264  3326 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-31 18:07:33.399  3264  3326 I jxcore-log: 
,03-31 18:07:33.401  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:33.402  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 18:07:33.403  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
03-31 18:07:33.403  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:33.403  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:33.404  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:33.405  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 18:07:33.406  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:33.406  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 18:07:33.406  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:07:33.408  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:07:33.409  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 18:07:33.409  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:33.410  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-31 18:07:33.410  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:33.412  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-31 18:07:33.413  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:33.413  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 18:07:33.413  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:33.413  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-31 18:07:33.413  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 18:07:33.413  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 18:07:33.415  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:33.415  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-31 18:07:33.415  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:33.416  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:33.416  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:07:33.416  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:07:33.418  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:33.418  3264  3326 I jxcore-log: 
,03-31 18:07:33.419  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:33.419  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:33.419  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:33.421  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-31 18:07:33.421  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:33.422  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 18:07:33.422  3264  3326 I jxcore-log: 
03-31 18:07:33.426  3264  3326 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 18:07:33.426  3264  3326 I jxcore-log: 
,03-31 18:07:33.439  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 18:07:33.439  3264  3326 I jxcore-log: 
,03-31 18:07:33.442  3264  3326 I jxcore-log: # teardown
03-31 18:07:33.442  3264  3326 I jxcore-log: 
,03-31 18:07:33.764  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 18:07:33.765  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:33.765  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:33.770  3264  3326 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:07:33.770  3264  3326 I jxcore-log: 
,03-31 18:07:33.772  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:07:33.772  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 18:07:33.772  3264  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 18:07:33.772  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:33.773  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:07:33.773  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:33.773  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:33.773  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 18:07:33.776  3264  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 18:07:33.776  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:33.778  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:07:33.778  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:33.778  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 18:07:33.779  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:33.780  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:07:33.780  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:33.780  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:33.780  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:07:33.794  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 18:07:33.794   828  1306 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:33.810  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-31 18:07:33.812  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:33.812  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:33.821  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:07:33.821  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:33.821  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:07:33.827  3264  3326 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:07:33.827  3264  3326 I jxcore-log: 
,03-31 18:07:33.844  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:33.844  3264  3326 I jxcore-log: 
,03-31 18:07:33.849  3264  3326 I jxcore-log: # setup
03-31 18:07:33.849  3264  3326 I jxcore-log: 
,03-31 18:07:34.906  3264  3326 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-31 18:07:34.906  3264  3326 I jxcore-log: 
,03-31 18:07:36.166  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 49467, start advertisements: false
,03-31 18:07:36.167  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:36.167  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:36.167  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 18:07:36.173  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-31 18:07:36.173  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:36.173  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:36.177  2156  2173 D BtGatt.GattService: registerClient() - UUID=cc534c8b-efeb-42e9-9754-cced1db70675
03-31 18:07:36.177  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=cc534c8b-efeb-42e9-9754-cced1db70675, clientIf=5
,03-31 18:07:36.178  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:07:36.178  2156  2221 D BtGatt.GattService: start scan with filters
03-31 18:07:36.179  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:36.179  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:36.179  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:07:36.179  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:36.180  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:36.180  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 18:07:36.180  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:36.180   828  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:36.180  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:36.184  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:36.184  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:36.184  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK,
03-31 18:07:36.185  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:36.185  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:36.185  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:36.189  3264  3326 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 18:07:36.189  3264  3326 I jxcore-log: 
03-31 18:07:36.191  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:36.192  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.193  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:36.193  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:36.194  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 49467, start advertisements: false
03-31 18:07:36.194  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:07:36.194  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:36.194  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:07:36.194  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:07:36.194  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:07:36.194  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:36.196  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:36.196  3264  3326 I jxcore-log: 
,03-31 18:07:36.197  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:36.197  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:36.197  3264  3326 I jxcore-log: 
03-31 18:07:36.197  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.199  3264  3326 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 18:07:36.199  3264  3326 I jxcore-log: 
,03-31 18:07:36.200  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:36.200  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:36.205  3264  3326 I jxcore-log: # teardown
03-31 18:07:36.205  3264  3326 I jxcore-log: 
,03-31 18:07:36.575  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:36.576  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 18:07:36.576  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 18:07:36.576  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 18:07:36.580  2156  2221 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:07:36.582  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:36.584  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 18:07:36.584  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:07:36.584  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:36.585  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 18:07:36.586  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 18:07:36.586  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 18:07:36.586  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:36.586  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.586  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:07:36.586  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:36.586  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:36.586  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:36.588  3264  3326 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:07:36.588  3264  3326 I jxcore-log: 
03-31 18:07:36.589  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:36.589  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:36.589  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:36.589  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.589  3264  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 18:07:36.589  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:36.589  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:07:36.589  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:36.589  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:36.589  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:36.590  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:36.591  3264  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 18:07:36.591  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:36.592  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:07:36.592  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:36.593  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:36.593  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:36.594  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 18:07:36.595  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:36.595  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:36.595  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:36.595  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:36.595  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:07:36.602  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:36.602  3264  3326 I jxcore-log: 
,03-31 18:07:36.605  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 18:07:36.606   828  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:36.613  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 18:07:36.614  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:36.614  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:36.618  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-31 18:07:36.618  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:36.618  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:36.619  3264  3326 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:07:36.619  3264  3326 I jxcore-log: 
,03-31 18:07:36.626  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 18:07:36.626  3264  3326 I jxcore-log: 
03-31 18:07:36.627  3264  3326 I jxcore-log: # setup
03-31 18:07:36.627  3264  3326 I jxcore-log: 
,03-31 18:07:36.720  3264  3326 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening,
03-31 18:07:36.720  3264  3326 I jxcore-log: 
,03-31 18:07:36.880  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 18:07:36.881  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:07:36.881  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:36.881  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:07:36.889  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 18:07:36.889  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:36.890  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:36.890  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:36.899  2156  2174 D BtGatt.GattService: registerClient() - UUID=eac0bd84-9c39-45d4-b6e1-340877f6df38
,03-31 18:07:36.900  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=eac0bd84-9c39-45d4-b6e1-340877f6df38, clientIf=5
,03-31 18:07:36.901  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:36.901  2156  2173 D BtGatt.GattService: start scan with filters
03-31 18:07:36.904  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:36.904  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:36.904  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 18:07:36.904  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:07:36.905  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:36.905  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:07:36.905  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:07:36.905  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:36.905  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 18:07:36.906  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:07:36.907  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:36.907  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:36.907  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:36.909  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:36.909  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:07:36.912  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:36.912  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:36.912  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:36.912  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:07:36.917  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:36.917  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.919  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:36.920  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:36.924  2156  2174 D BtGatt.GattService: registerClient() - UUID=9c9b7f00-275e-4e8d-bb3c-194293c354b9
03-31 18:07:36.925  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=9c9b7f00-275e-4e8d-bb3c-194293c354b9, clientIf=6
03-31 18:07:36.926  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:07:36.930  2156  2231 D BtGatt.AdvertiseManager: message : 0,
,03-31 18:07:36.937  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:36.942  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:36.946  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:07:36.948  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:07:36.948  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:36.948   828  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:36.956  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:07:36.956  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:36.956  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:07:36.956  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:36.958  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 18:07:36.958  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:07:36.958  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:07:36.958  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 18:07:36.959  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:36.960  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:07:36.960  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:07:36.960  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 18:07:36.960  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:07:36.960  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:07:36.960  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:36.960  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:36.961  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:36.961  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:07:36.961  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:07:36.961  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:36.961   828  1456 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:36.962  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:36.964  3264  3713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:07:36.970  3264  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:07:36.976  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:36.976  3264  3326 I jxcore-log: 
,03-31 18:07:36.980  3264  3326 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-31 18:07:36.980  3264  3326 I jxcore-log: 
,03-31 18:07:36.982  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-31 18:07:36.983  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 18:07:36.983  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
03-31 18:07:36.983  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:07:36.983  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:07:36.984  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 18:07:36.984  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:36.984  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:07:36.984  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:36.984  3264  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:07:36.985  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-31 18:07:36.985  3264  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:07:36.985  3264  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:07:36.985  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:36.985  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:36.989  2156  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:07:36.993  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 18:07:36.993  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.994  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:07:36.995  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:07:36.996  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 18:07:36.996  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:36.997  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:36.997  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:36.997  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:36.997  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:36.997  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 18:07:36.997  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:07:36.998  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 18:07:36.998  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 18:07:37.002  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-31 18:07:37.002  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:37.002  2156  2219 D BtGatt.GattService: current time is 254661177036
03-31 18:07:37.002  2156  2219 D BtGatt.GattService: Batch record : [-58, 29, -35, -13, 74, 117, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 18:07:37.003  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:37.003  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-31 18:07:37.004  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:07:37.008  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 18:07:37.009  2156  2219 D BtGatt.GattService: Client app is not null!
03-31 18:07:37.011  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:37.012  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:37.012  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:37.012  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:07:37.012  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 18:07:37.012  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 18:07:37.012  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:37.012  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 18:07:37.013  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:07:37.014  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:37.014  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:37.015  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:37.015  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:37.015  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:07:37.021  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:37.021  3264  3326 I jxcore-log: 
,03-31 18:07:37.025  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:07:37.025  3264  3326 I jxcore-log: 
03-31 18:07:37.026  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 18:07:37.027   828  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:37.040  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:37.041  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 18:07:37.042  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:37.049  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 18:07:37.049  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:07:37.049  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:37.050  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 18:07:37.050  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:37.050  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:37.051  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:37.051  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:07:37.053  3264  3326 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 18:07:37.053  3264  3326 I jxcore-log: 
,03-31 18:07:37.067  3264  3326 I jxcore-log: # teardown
03-31 18:07:37.067  3264  3326 I jxcore-log: 
,03-31 18:07:37.071  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-31 18:07:37.071  3264  3326 I jxcore-log: 
03-31 18:07:37.073  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:37.073  3264  3326 I jxcore-log: 
,03-31 18:07:37.075  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:37.075  3264  3326 I jxcore-log: 
,03-31 18:07:37.363  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-31 18:07:37.363  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:07:37.363  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:37.367  3264  3326 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:07:37.367  3264  3326 I jxcore-log: 
,03-31 18:07:37.368  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:07:37.369  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:37.369  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:37.372  3264  3326 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:07:37.372  3264  3326 I jxcore-log: 
,03-31 18:07:37.383  3264  3326 I jxcore-log: # setup
03-31 18:07:37.383  3264  3326 I jxcore-log: 
,03-31 18:07:38.592  3264  3326 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 18:07:38.592  3264  3326 I jxcore-log: 
,03-31 18:07:38.724  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 18:07:38.724  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:38.724  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:38.724  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:07:38.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 18:07:38.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 18:07:38.729  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:38.729  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:38.734  2156  2174 D BtGatt.GattService: registerClient() - UUID=610332ec-5a39-473e-9414-b2b1671e0da5
03-31 18:07:38.734  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=610332ec-5a39-473e-9414-b2b1671e0da5, clientIf=5
,03-31 18:07:38.735  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:07:38.736  2156  2221 D BtGatt.GattService: start scan with filters
03-31 18:07:38.737  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:38.737  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 18:07:38.737  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:38.737  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 18:07:38.738  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:38.738  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:38.738  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:07:38.738  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:07:38.738  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:07:38.738  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:38.738  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:38.738  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:38.738  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 18:07:38.744  2156  2173 D BtGatt.GattService: registerClient() - UUID=820d319e-02e1-489c-a17a-a35cd32479a7
,03-31 18:07:38.745  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=820d319e-02e1-489c-a17a-a35cd32479a7, clientIf=6
03-31 18:07:38.745  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:07:38.746  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 18:07:38.746  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:38.747  2156  2231 D BtGatt.AdvertiseManager: message : 0
03-31 18:07:38.748  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:38.748  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:38.748  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:38.748  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:07:38.751  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:38.751  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:38.751  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
03-31 18:07:38.753  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 18:07:38.753  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:38.757  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:38.761  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:07:38.762  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:07:38.762  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:38.762   828  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:38.765  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:38.765  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:38.765  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:07:38.765  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:38.768  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 18:07:38.768  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:07:38.768  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 18:07:38.768  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 18:07:38.768  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:38.768  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 18:07:38.769  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:07:38.769  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 18:07:38.769  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:07:38.769  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 18:07:38.769  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:07:38.770  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 18:07:38.770  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:38.770  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:38.770  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:38.770  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-31 18:07:38.770  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:38.770  3264  3326 I jxcore-log: 
03-31 18:07:38.771  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:38.774   828  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-31 18:07:38.775  3264  3714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 18:07:38.777  3264  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 18:07:38.778  3264  3326 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error,
03-31 18:07:38.778  3264  3326 I jxcore-log: 
03-31 18:07:38.782  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true,
03-31 18:07:38.782  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:38.782  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:38.782  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:38.782  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:38.783  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:38.783  3264  3326 I jxcore-log: 
03-31 18:07:38.784  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:07:38.784  3264  3326 I jxcore-log: 
,03-31 18:07:38.786  3264  3326 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 18:07:38.786  3264  3326 I jxcore-log: 
,03-31 18:07:38.792  3264  3326 I jxcore-log: # teardown
,03-31 18:07:38.792  3264  3326 I jxcore-log: 
,03-31 18:07:39.596  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:39.596  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 18:07:39.597  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 18:07:39.597  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 18:07:39.602  2156  2221 D BtGatt.GattService: stopScan() - queue size =1,
03-31 18:07:39.603  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:07:39.603  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-31 18:07:39.603  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:39.603  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:39.604  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-31 18:07:39.604  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 18:07:39.604  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:39.604  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 18:07:39.604  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:39.604  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:39.605  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:07:39.604  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 18:07:39.605  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:39.606  3264  3326 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:07:39.606  3264  3326 I jxcore-log: 
03-31 18:07:39.607  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:07:39.607  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 18:07:39.607  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:07:39.607  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:07:39.607  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:07:39.608  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:07:39.608  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:39.608  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 18:07:39.608  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:39.608  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:39.608  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:39.608  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:39.608  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:39.608  3264  3714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:07:39.608  3264  3714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:07:39.608  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:39.609  3264  3714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:07:39.609  3264  3326 D BluetoothLeScanner: could not find callback wrapper
,03-31 18:07:39.609  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:39.609  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:07:39.611  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:39.611  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:07:39.612  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-31 18:07:39.612  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:39.612  2156  2219 D BtGatt.GattService: current time is 257271308805
03-31 18:07:39.612  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -63, 45, -106, 72, -23, 99, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 18:07:39.613  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:39.613  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:39.615  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:07:39.615  2156  2219 D BtGatt.GattService: Client app is not null!
03-31 18:07:39.615  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:39.618  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:39.618  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:07:39.618  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:07:39.619  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 18:07:39.619  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 18:07:39.619  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:39.619  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:39.619  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:07:39.619  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:39.619  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:39.619  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:39.620  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:39.620  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:07:39.621  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:07:39.621  3264  3326 I jxcore-log: 
03-31 18:07:39.630  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:07:39.630   828   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:39.640  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:39.641  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 18:07:39.642  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:39.645  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 18:07:39.645  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:07:39.645  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:39.646  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:39.646  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:39.646  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:39.647  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:07:39.647  3264  3326 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:07:39.647  3264  3326 I jxcore-log: 
,03-31 18:07:39.654  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:39.654  3264  3326 I jxcore-log: 
,03-31 18:07:39.654  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:39.654  3264  3326 I jxcore-log: 
,03-31 18:07:39.657  3264  3326 I jxcore-log: # setup
03-31 18:07:39.657  3264  3326 I jxcore-log: 
,03-31 18:07:40.853  3264  3326 I jxcore-log: # 39. peerAvailabilityChange is called
,03-31 18:07:40.853  3264  3326 I jxcore-log: 
,03-31 18:07:40.994  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-31 18:07:40.994  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:40.995  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:40.995  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:07:41.003  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 18:07:41.003  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:41.003  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:41.003  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:41.006  2156  2173 D BtGatt.GattService: registerClient() - UUID=10b66d7f-8dad-4317-94ae-50fb047144ab
03-31 18:07:41.007  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=10b66d7f-8dad-4317-94ae-50fb047144ab, clientIf=5
03-31 18:07:41.007  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:41.008  2156  2221 D BtGatt.GattService: start scan with filters,
,03-31 18:07:41.009  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 18:07:41.009  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:41.009  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:07:41.009  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:41.009  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-31 18:07:41.010  2156  2232 D BtGatt.ScanManager: handling starting scan
03-31 18:07:41.010  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:07:41.010  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:07:41.010  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-31 18:07:41.011  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-31 18:07:41.011  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:41.011  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 18:07:41.011  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 18:07:41.019  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:41.019  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-31 18:07:41.020  2156  2174 D BtGatt.GattService: registerClient() - UUID=2359a1b1-5523-489e-92d3-a44301d39937
03-31 18:07:41.020  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=2359a1b1-5523-489e-92d3-a44301d39937, clientIf=6
03-31 18:07:41.021  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:07:41.021  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-31 18:07:41.021  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:41.021  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:41.021  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:07:41.023  2156  2231 D BtGatt.AdvertiseManager: message : 0
03-31 18:07:41.025  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:41.025  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:41.026  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 18:07:41.026  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:41.028  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:41.032  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-31 18:07:41.034  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:07:41.035  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:07:41.035  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:41.035   828  1429 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:41.038  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 18:07:41.038  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 18:07:41.038  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 18:07:41.038  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:41.039  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 18:07:41.039  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:07:41.039  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:07:41.039  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 18:07:41.039  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:41.039  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:41.040  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:07:41.040  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:07:41.040  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:07:41.040  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 18:07:41.040  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:07:41.041  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:41.041  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:41.041  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:41.041  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:41.041   828  1306 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:41.041  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 18:07:41.042  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:41.042  3264  3326 I jxcore-log: 
03-31 18:07:41.042  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 18:07:41.043  3264  3326 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-31 18:07:41.043  3264  3326 I jxcore-log: 
03-31 18:07:41.045  3264  3715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:07:41.049  3264  3715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 18:07:41.049  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-31 18:07:41.049  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:07:41.049  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 18:07:41.049  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:07:41.049  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:41.051  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:41.051  3264  3326 I jxcore-log: 
,03-31 18:07:41.051  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:07:41.051  3264  3326 I jxcore-log: 
,03-31 18:07:41.053  3264  3326 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 18:07:41.053  3264  3326 I jxcore-log: 
,03-31 18:07:42.035  2156  2156 D BtGatt.ScanManager: awakened up at time 259693
,03-31 18:07:42.037  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:42.048  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-31 18:07:42.048  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:42.048  2156  2219 D BtGatt.GattService: current time is 259707469325
03-31 18:07:42.049  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -110, -29, -37, 120, -19, 82, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 18:07:42.049  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:42.050  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:42.062  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-31 18:07:42.063  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 18:07:42.063  3264  3264 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 18:07:42.063  3264  3264 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 18:07:42.067  3264  3326 I jxcore-log: ok 155 peers must be an array
03-31 18:07:42.067  3264  3326 I jxcore-log: 
,03-31 18:07:42.068  3264  3326 I jxcore-log: ok 156 peers must not be zero-length,
03-31 18:07:42.068  3264  3326 I jxcore-log: 
,03-31 18:07:42.070  3264  3326 I jxcore-log: ok 157 peer must have peerIdentifier
03-31 18:07:42.070  3264  3326 I jxcore-log: 
,03-31 18:07:42.071  3264  3326 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 18:07:42.071  3264  3326 I jxcore-log: ,
03-31 18:07:42.072  3264  3326 I jxcore-log: ok 159 peer must have peerAvailable
03-31 18:07:42.072  3264  3326 I jxcore-log: 
,03-31 18:07:42.072  3264  3326 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 18:07:42.072  3264  3326 I jxcore-log: 
,03-31 18:07:42.102  3264  3326 I jxcore-log: # teardown
03-31 18:07:42.102  3264  3326 I jxcore-log: 
,03-31 18:07:42.144   828  1305 I art     : Explicit concurrent mark sweep GC freed 29609(1343KB) AllocSpace objects, 8(599KB) LOS objects, 31% free, 34MB/50MB, paused 1.859ms total 64.140ms
,03-31 18:07:43.063  2156  2156 D BtGatt.ScanManager: awakened up at time 260721
03-31 18:07:43.064  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:43.069  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:07:43.069  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:43.070  2156  2219 D BtGatt.GattService: current time is 260728664689
03-31 18:07:43.070  2156  2219 D BtGatt.GattService: Batch record : [-110, -29, -37, 120, -19, 82, 1, -128, -75, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 18:07:43.070  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 18:07:43.071  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 18:07:43.074  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-31 18:07:43.075  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-31 18:07:43.409  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:07:43.409  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-31 18:07:43.409  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 18:07:43.409  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:43.414  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:07:43.417  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:43.418  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:43.419  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-31 18:07:43.419  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:43.419  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:43.419  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:43.419  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 18:07:43.419  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:07:43.419  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 18:07:43.420  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:07:43.422  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:43.422  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 18:07:43.422  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:43.423  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:43.423  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:43.423  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:43.427  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-31 18:07:43.427  3264  3326 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:07:43.427  3264  3326 I jxcore-log: 
03-31 18:07:43.427  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:43.427  2156  2219 D BtGatt.GattService: current time is 261086416616
,03-31 18:07:43.428  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 18:07:43.428  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 18:07:43.433  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:07:43.433  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 18:07:43.433  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:07:43.433  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:07:43.433  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:07:43.434  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:07:43.434  3264  3715 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:07:43.434  3264  3715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:07:43.434  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:43.434  3264  3715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:07:43.434  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:07:43.434  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 18:07:43.434  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:07:43.434  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 18:07:43.435  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:43.435  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:43.435  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:43.437  3264  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 18:07:43.437  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:43.437  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 18:07:43.441  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:43.442  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:07:43.445  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:07:43.445  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:07:43.446  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:43.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:43.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:07:43.447  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:07:43.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 18:07:43.447  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 18:07:43.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:43.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:43.448  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 18:07:43.449  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:43.449  3264  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 18:07:43.449  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:43.449  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:43.449  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:43.450  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:43.450  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:43.450  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:07:43.453  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:07:43.453  3264  3326 I jxcore-log: 
,03-31 18:07:43.458  3264  3326 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:07:43.458  3264  3326 I jxcore-log: 
,03-31 18:07:43.459  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:07:43.459   828  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:43.464  3264  3326 I jxcore-log: # setup
03-31 18:07:43.464  3264  3326 I jxcore-log: 
,03-31 18:07:43.468  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:07:43.469  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:43.469  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:07:43.473  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 18:07:43.473  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:07:43.477  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 18:07:43.477  3264  3326 I jxcore-log: 
03-31 18:07:43.478  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:43.478  3264  3326 I jxcore-log: 
,03-31 18:07:43.528  3264  3326 I jxcore-log: # 40. Can connect to a remote peer,
03-31 18:07:43.528  3264  3326 I jxcore-log: 
,03-31 18:07:44.026  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 43248, start advertisements: true
03-31 18:07:44.026  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:07:44.026  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:44.027  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:07:44.034  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 18:07:44.034  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:44.034  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:44.034  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:44.041  2156  2221 D BtGatt.GattService: registerClient() - UUID=ca25cf4f-983a-4ac3-87c1-79a88a62dea0
,03-31 18:07:44.042  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=ca25cf4f-983a-4ac3-87c1-79a88a62dea0, clientIf=5
03-31 18:07:44.042  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:07:44.043  2156  2174 D BtGatt.GattService: start scan with filters
03-31 18:07:44.045  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:44.046  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 18:07:44.046  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:44.046  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:07:44.046  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:07:44.046  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:07:44.048  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:44.048  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:44.048  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:07:44.048  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:07:44.049  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-31 18:07:44.050  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:44.050  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:44.051  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:44.051  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:07:44.051  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:07:44.051  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:44.051  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:44.051  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:44.054  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:44.054  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:44.055  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:44.055  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:44.059  2156  2173 D BtGatt.GattService: registerClient() - UUID=3c263fdc-3b81-42b3-ac21-a4654d643d43
,03-31 18:07:44.060  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=3c263fdc-3b81-42b3-ac21-a4654d643d43, clientIf=6
03-31 18:07:44.060  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:07:44.062  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:07:44.065  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 18:07:44.068  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:44.071  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-31 18:07:44.072  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:07:44.072  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:07:44.072   828  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:07:44.076  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 18:07:44.076  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:07:44.076  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:07:44.076  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:07:44.077  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 18:07:44.078  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:07:44.078  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:07:44.078  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 18:07:44.078  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:07:44.078  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:07:44.078  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 18:07:44.078  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:07:44.078  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:07:44.079  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:07:44.079  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:07:44.079  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:44.079  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:07:44.079  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:07:44.079  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:44.079  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:07:44.079  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:07:44.080  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:44.080  3264  3326 I jxcore-log: 
,03-31 18:07:44.081   828  1106 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:44.082  3264  3326 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error
03-31 18:07:44.082  3264  3326 I jxcore-log: 
03-31 18:07:44.083  3264  3719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:07:44.087  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 43248, start advertisements: false
,03-31 18:07:44.087  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-31 18:07:44.087  3264  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:07:44.087  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 18:07:44.087  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:07:44.087  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:07:44.096  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:07:44.096  3264  3326 I jxcore-log: 
,03-31 18:07:44.098  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:07:44.098  3264  3326 I jxcore-log: 
,03-31 18:07:44.099  3264  3326 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 18:07:44.099  3264  3326 I jxcore-log: 
,03-31 18:07:45.084  2156  2156 D BtGatt.ScanManager: awakened up at time 262742
,03-31 18:07:45.085  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:45.092  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:07:45.093  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:45.093  2156  2219 D BtGatt.GattService: current time is 262751833960
03-31 18:07:45.093  2156  2219 D BtGatt.GattService: Batch record : [38, 40, 112, -40, -113, 68, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-31 18:07:45.094  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:45.094  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 18:07:45.096  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-31 18:07:45.097  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-31 18:07:45.097  3264  3264 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 18:07:45.098  3264  3264 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-31 18:07:45.105  3264  3326 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-31 18:07:45.105  3264  3326 I jxcore-log: 
,03-31 18:07:45.116  3264  3326 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-31 18:07:45.117  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-31 18:07:45.119  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-31 18:07:45.119  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-31 18:07:45.120  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
03-31 18:07:45.120  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
,03-31 18:07:45.120  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
,03-31 18:07:45.120  3264  3326 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-31 18:07:45.122  3264  3326 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}],
03-31 18:07:45.122  3264  3326 I jxcore-log: 
,03-31 18:07:45.123  3264  3720 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 356)
03-31 18:07:45.123  3264  3720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:07:45.128  2156  2174 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 18:07:45.750  3378  3721 V GoogleAuthProtoRequest: [343] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 18:07:45.842  1376  2549 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 18:07:45.843  1376  2549 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 18:07:45.843  1376  2549 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:07:45.844  1376  2549 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:07:45.859  1376  2549 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:07:45.900  3378  3721 W ExperimentUpdateService: [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 18:07:45.902  3378  3721 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 18:07:45.948  2156  2156 D BtGatt.ScanManager: awakened up at time 263606
,03-31 18:07:45.949  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:45.952  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:07:45.952  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:45.953  2156  2219 D BtGatt.GattService: current time is 263611756199
03-31 18:07:45.953  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 40, 112, -40, -113, 68, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 18:07:45.954  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:45.954  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:45.957  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-31 18:07:45.959  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 18:07:46.458  2156  2156 D BtGatt.ScanManager: awakened up at time 264117
,03-31 18:07:46.461  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:46.465  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:07:46.465  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:46.465  2156  2219 D BtGatt.GattService: current time is 264124428647
03-31 18:07:46.466  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 40, 112, -40, -113, 68, 1, -128, -81, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 18:07:46.467  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:46.468  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:46.470  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 18:07:46.472  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 18:07:48.236  2156  2233 W bt-btif : info:x10
,03-31 18:07:48.237  2156  2219 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-31 18:07:48.238  2156  2219 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 18:07:48.477  2156  2233 W bt-btif : No ag scb for peer addr
,03-31 18:07:48.553  2156  2233 W bt-btif : info:x10
,03-31 18:07:48.554  2156  2219 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-31 18:07:48.554  2156  2219 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 18:07:48.803  2156  2233 E bt-btm  : tBTM_SEC_DEV:0xa2f2eeb4 rs_disc_pending=1
03-31 18:07:48.803  2156  2233 W bt-btif : bta_dm_check_av:0
03-31 18:07:48.804  2156  2219 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 18:07:48.921  2156  2233 W bt-sdp  : process_service_search_attr_rsp
,03-31 18:07:49.316  2156  2219 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-31 18:07:49.325  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-31 18:07:49.326  2156  2219 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 18:07:49.333  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-31 18:07:49.333  2156  2220 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 18:07:49.405   828   856 I ActivityManager: Start proc 3723:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-31 18:07:49.485  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-31 18:07:49.486  2156  2220 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 18:07:49.489  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 18:07:49.501   828   860 D BluetoothManagerService: Message: 20
03-31 18:07:49.502   828   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@267010a9:true
,03-31 18:07:49.507   828  1252 I ActivityManager: Killing 3064:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-31 18:07:49.575  2156  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-31 18:07:49.576  2156  2219 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 18:07:49.635  2156  2220 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 18:07:51.470  2156  2156 D BtGatt.ScanManager: awakened up at time 269128
03-31 18:07:51.472  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:51.477  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-31 18:07:51.477  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:51.477  2156  2219 D BtGatt.GattService: current time is 269136305624
03-31 18:07:51.478  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 82, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 40, 112, -40, -113, 68, 1, -128, -76, 81, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 18:07:51.478  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 18:07:51.479  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-31 18:07:51.482  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 18:07:51.483  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-31 18:07:53.375  2156  2233 W bt-btif : info:x10
03-31 18:07:53.376  2156  2219 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-31 18:07:53.376  2156  2219 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 18:07:54.892  2156  2219 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-31 18:07:54.900  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
03-31 18:07:54.901  2156  2219 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-31 18:07:54.904  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-31 18:07:54.904  2156  2220 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 18:07:54.927  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-31 18:07:54.927  2156  2220 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
03-31 18:07:54.929  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-31 18:07:54.957  2156  2220 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 18:07:54.976  2156  2233 W bt-btif : new conn_srvc id:26, app_id:255
03-31 18:07:54.976  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 18:07:54.977  2156  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 18:07:54.977  3264  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 18:07:54.979  3264  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 357)
03-31 18:07:54.979  3264  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 18:07:54.980   828  1427 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:54.981  3264  3743 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 357)
,03-31 18:07:54.983  3264  3719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:07:54.985  3264  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:07:55.019  3264  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 357)
,03-31 18:07:55.020  3264  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0],
03-31 18:07:55.021  3264  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 357)
,03-31 18:07:55.021  3264  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 357
03-31 18:07:55.021  3264  3743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 357)
03-31 18:07:55.021  3264  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 18:07:55.022  3264  3743 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 357)
,03-31 18:07:55.023  3264  3264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-31 18:07:55.023  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:07:55.023  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-31 18:07:55.026  3264  3264 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 18:07:55.026  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 18:07:55.029  2156  2231 D BtGatt.AdvertiseManager: message : 1,
03-31 18:07:55.030  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:07:55.032  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 18:07:55.032  2156  2219 D BtGatt.GattService: Client app is not null!
03-31 18:07:55.033  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:55.033  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:07:55.033  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:55.033  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 18:07:55.033  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 18:07:55.033  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:07:55.034  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:07:55.034  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:55.034  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:55.034  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:55.042  2156  2174 D BtGatt.GattService: registerClient() - UUID=c48a1b70-2ff8-47ce-af17-2a6057445b0a
03-31 18:07:55.043  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=c48a1b70-2ff8-47ce-af17-2a6057445b0a, clientIf=6
03-31 18:07:55.043  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:07:55.044  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:07:55.048  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:55.051  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:55.053  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-31 18:07:55.054  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 18:07:55.056  2156  2174 D BtGatt.GattService: stopScan() - queue size =1,
,03-31 18:07:55.057  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:55.057  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:55.057  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:07:55.057  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-31 18:07:55.057  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:55.057  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:55.057  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:55.059  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:55.059  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.059  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:07:55.061  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:55.061  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.061  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:07:55.062  2156  2173 D BtGatt.GattService: registerClient() - UUID=31970497-621f-403c-a3fd-9fe253941b49
,03-31 18:07:55.062  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=31970497-621f-403c-a3fd-9fe253941b49, clientIf=5
03-31 18:07:55.063  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:55.063  2156  2174 D BtGatt.GattService: start scan with filters
,03-31 18:07:55.064  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:07:55.064  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.064  2156  2219 D BtGatt.GattService: current time is 272722936664
03-31 18:07:55.064  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 47, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 38, 40, 112, -40, -113, 68, 1, -128, -77, 48, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 18:07:55.064  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-31 18:07:55.064  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 18:07:55.064  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 18:07:55.064  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 18:07:55.065  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
03-31 18:07:55.067  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:55.067  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:07:55.070  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:07:55.070  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:07:55.072  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:55.073  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:55.073  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 18:07:55.073  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 18:07:55.073  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:07:55.073  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:07:55.073  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-31 18:07:55.073  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:55.073  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:55.073  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:55.082  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:55.084  2156  2221 D BtGatt.GattService: registerClient() - UUID=bf63d2c3-2fe7-4bc0-a7bd-48758c198111,
03-31 18:07:55.085  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=bf63d2c3-2fe7-4bc0-a7bd-48758c198111, clientIf=6
03-31 18:07:55.085  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:55.085  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:07:55.085  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-31 18:07:55.086  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:55.086  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:55.086  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:55.086  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:07:55.087  2156  2231 D BtGatt.AdvertiseManager: message : 0
03-31 18:07:55.088  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:55.088  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.090  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:55.090  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.091  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:55.094  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:55.096  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:07:55.097  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 18:07:55.098  2156  2221 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:07:55.099  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:55.100  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 18:07:55.100  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:55.100  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:55.100  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:55.100  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:55.100  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-31 18:07:55.101  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:55.101  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.102  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:07:55.104  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:55.105  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.105  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-31 18:07:55.105  2156  2221 D BtGatt.GattService: registerClient() - UUID=dd013db2-ce26-44ad-b7f8-814380899386
03-31 18:07:55.105  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=dd013db2-ce26-44ad-b7f8-814380899386, clientIf=5
,03-31 18:07:55.105  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:55.106  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:07:55.106  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.106  2156  2173 D BtGatt.GattService: start scan with filters
03-31 18:07:55.106  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:55.106  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:07:55.106  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 18:07:55.107  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:07:55.107  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:07:55.107  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 18:07:55.107  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 18:07:55.107  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 18:07:55.107  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 18:07:55.112  2156  2231 D BtGatt.AdvertiseManager: message : 1
,03-31 18:07:55.114  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:07:55.114  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:07:55.116  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-31 18:07:55.116  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:07:55.117  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-31 18:07:55.118  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:55.118  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 18:07:55.118  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:07:55.118  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-31 18:07:55.118  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:07:55.118  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:07:55.119  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:55.119  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.119  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:55.119  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:07:55.119  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:07:55.122  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:55.122  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.122  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 18:07:55.123  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:07:55.123  2156  2174 D BtGatt.GattService: registerClient() - UUID=2e67f0dc-9427-4afb-9bcd-6a31de06a4ae
03-31 18:07:55.123  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=2e67f0dc-9427-4afb-9bcd-6a31de06a4ae, clientIf=6
03-31 18:07:55.124  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:07:55.125  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 18:07:55.125  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.125  2156  2231 D BtGatt.AdvertiseManager: message : 0
03-31 18:07:55.126  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:07:55.126  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:55.127  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:07:55.130  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:07:55.133  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:07:55.133  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:07:55.135  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:07:55.135  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:07:55.136  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:55.136  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:55.136  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:55.136  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:07:55.136  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:07:55.136  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:07:55.137  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 18:07:55.137  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.137  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:07:55.139  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:55.139  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.140  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:55.140  2156  2173 D BtGatt.GattService: registerClient() - UUID=d0679dcd-8950-40a8-8b9a-c76ffbd6b43d
03-31 18:07:55.140  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=d0679dcd-8950-40a8-8b9a-c76ffbd6b43d, clientIf=5
03-31 18:07:55.140  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:07:55.141  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:07:55.141  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.141  2156  2174 D BtGatt.GattService: start scan with filters
03-31 18:07:55.142  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:07:55.142  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-31 18:07:55.142  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 18:07:55.142  3264  3264 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 18:07:55.142  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:07:55.142  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:07:55.142  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:07:55.142  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:07:55.143  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:07:55.143  3264  3744 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 358)
,03-31 18:07:55.145  2156  2232 D BtGatt.ScanManager: handling starting scan,
03-31 18:07:55.147  3264  3744 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 43248
03-31 18:07:55.147  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:07:55.147  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.147  3264  3744 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 18:07:55.148  3264  3744 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:07:55.148  3264  3744 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 18:07:55.149  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:07:55.149  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.150  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:07:55.150  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:07:55.151  3264  3746 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 359, name: Sender)
03-31 18:07:55.151  3264  3744 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 358)
03-31 18:07:55.151  3264  3744 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 358)
03-31 18:07:55.151  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:07:55.151  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:07:55.152  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
,03-31 18:07:55.152  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:55.155  3264  3747 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 360, name: Receiver)
,03-31 18:07:57.932  2156  2233 W bt-btif : new conn_srvc id:26, app_id:255,
03-31 18:07:57.932  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255,
03-31 18:07:57.932  2156  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 18:07:57.934  3264  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 18:07:57.936  3264  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 361),
03-31 18:07:57.938  3264  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 18:07:57.939  3264  3749 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 361)
03-31 18:07:57.940   828  1252 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:57.942  2156  2233 W bt-btif : new conn_srvc id:26, app_id:1
03-31 18:07:57.942  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 18:07:57.942  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,03-31 18:07:57.942  2156  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 18:07:57.943  3264  3720 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-31 18:07:57.943  3264  3720 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 356)
03-31 18:07:57.944  3264  3719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:07:57.944  3264  3720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 362)
03-31 18:07:57.945  3264  3720 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 362)
03-31 18:07:57.945  3264  3720 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 356)
03-31 18:07:57.949  3264  3750 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 362)
,03-31 18:07:57.954  3264  3749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 361)
,03-31 18:07:57.955  3264  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:07:57.958  3264  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 362)
,03-31 18:07:57.959  3264  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-31 18:07:57.960  3264  3749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 361)
03-31 18:07:57.960  3264  3749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 361
03-31 18:07:57.960  3264  3749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 361)
03-31 18:07:57.960  3264  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-31 18:07:57.961  3264  3749 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 361)
03-31 18:07:57.961  3264  3264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 18:07:57.961  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 18:07:57.961  3264  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-31 18:07:57.962  3264  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-31 18:07:57.962  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 18:07:57.962  3264  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 356)
03-31 18:07:57.964  3264  3750 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 362)
03-31 18:07:57.964  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 18:07:57.964  3264  3264 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 18:07:57.964  3264  3264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-31 18:07:57.965  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 18:07:57.965  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 18:07:57.965  3264  3751 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 363)
03-31 18:07:57.966  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 18:07:57.966  3264  3264 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,03-31 18:07:57.967  3264  3752 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 364)
,03-31 18:07:57.968  3264  3752 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40470
03-31 18:07:57.968  3264  3752 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 18:07:57.968  3264  3752 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 40470 (peer ID: F8:95:C7:87:3C:51)
03-31 18:07:57.969  3264  3752 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-31 18:07:57.971  3264  3751 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 43248
03-31 18:07:57.971  3264  3751 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 18:07:57.971  3264  3751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:07:57.972  3264  3326 I jxcore-log: INFO testThaliMobileNative: 
,03-31 18:07:57.972  3264  3326 I jxcore-log: 
03-31 18:07:57.972  3264  3751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:07:57.972  3264  3751 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 363)
03-31 18:07:57.972  3264  3751 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 363)
,03-31 18:07:57.972  3264  3326 I jxcore-log: ok 165 Must have listeningPort
03-31 18:07:57.972  3264  3326 I jxcore-log: 
03-31 18:07:57.973  3264  3326 I jxcore-log: ok 166 listeningPort must be a number
03-31 18:07:57.973  3264  3326 I jxcore-log: 
03-31 18:07:57.973  3264  3326 I jxcore-log: ok 167 Connection must have clientPort
03-31 18:07:57.973  3264  3326 I jxcore-log: 
03-31 18:07:57.973  3264  3326 I jxcore-log: ok 168 clientPort must be a number
03-31 18:07:57.973  3264  3326 I jxcore-log: 
,03-31 18:07:57.974  3264  3326 I jxcore-log: ok 169 Connection must have serverPort
03-31 18:07:57.974  3264  3326 I jxcore-log: 
03-31 18:07:57.974  3264  3326 I jxcore-log: ok 170 serverPort must be a number
03-31 18:07:57.974  3264  3326 I jxcore-log: 
03-31 18:07:57.976  3264  3326 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 18:07:57.976  3264  3326 I jxcore-log: 
03-31 18:07:57.976  3264  3326 I jxcore-log: ok 172 forward connection must have serverPort == 0,
03-31 18:07:57.976  3264  3326 I jxcore-log: 
03-31 18:07:57.977  3264  3754 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Sender)
03-31 18:07:57.979  3264  3755 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Receiver)
,03-31 18:07:57.985  3264  3326 I jxcore-log: # teardown
,03-31 18:07:57.985  3264  3326 I jxcore-log: 
,03-31 18:07:58.196  3264  3746 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 359, thread name: Sender),
03-31 18:07:58.196  3264  3746 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read,
03-31 18:07:58.196  3264  3746 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
,03-31 18:07:58.196  3264  3754 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 365, thread name: Sender)
,03-31 18:07:58.197  3264  3754 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-31 18:07:58.197  3264  3746 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 358
,03-31 18:07:58.197  3264  3754 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read,
,03-31 18:07:58.197  3264  3746 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 358)
03-31 18:07:58.198  3264  3747 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Receiver): bt socket closed, read return: -1
03-31 18:07:58.198  3264  3747 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 360, name: Receiver)
03-31 18:07:58.200  3264  3746 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 18:07:58.200  3264  3746 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 18:07:58.201  3264  3746 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 360
03-31 18:07:58.201  3264  3746 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-31 18:07:58.201  3264  3746 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 359
03-31 18:07:58.201  3264  3746 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 358)
03-31 18:07:58.202  3264  3746 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 358)
03-31 18:07:58.203  3264  3746 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-31 18:07:58.203  3264  3754 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 363
03-31 18:07:58.203  3264  3754 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 363)
03-31 18:07:58.203  3264  3754 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 18:07:58.203  3264  3754 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 18:07:58.203  3264  3754 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
03-31 18:07:58.203  3264  3754 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 18:07:58.203  3264  3754 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-31 18:07:58.203  3264  3754 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 363)
03-31 18:07:58.204  3264  3754 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 363)
03-31 18:07:58.204  3264  3754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 18:07:58.204  3264  3754 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Sender)
03-31 18:07:58.204  3264  3755 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
03-31 18:07:58.204  3264  3755 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Receiver)
03-31 18:07:58.205  3264  3746 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 359, name: Sender)
,03-31 18:07:58.205  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:07:58.205  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 18:07:58.205  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 18:07:58.205  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:07:58.207  2156  2221 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:07:58.209  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:07:58.209  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:58.209  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:58.209  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:07:58.209  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 18:07:58.209  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:07:58.209  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:58.210  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:07:58.210  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 18:07:58.210  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:58.211  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:07:58.211  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:58.211  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:07:58.214  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:07:58.214  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:58.214  3264  3326 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 18:07:58.214  3264  3326 I jxcore-log: 
03-31 18:07:58.214  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:07:58.215  3264  3326 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 18:07:58.215  3264  3326 I jxcore-log: 
03-31 18:07:58.215  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:07:58.215  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:07:58.216  3264  3326 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:07:58.216  3264  3326 I jxcore-log: 
03-31 18:07:58.216  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:07:58.216  3264  3326 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-31 18:07:58.217  3264  3326 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 364)
03-31 18:07:58.217  3264  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 364)
03-31 18:07:58.217  3264  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 18:07:58.217  3264  3326 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 364)
03-31 18:07:58.217  3264  3326 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 364)
03-31 18:07:58.219  3264  3752 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 364)
03-31 18:07:58.220  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 18:07:58.220  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:07:58.220  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:07:58.220  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:07:58.220  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:07:58.220  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:07:58.220  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 18:07:58.220  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:07:58.220  3264  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:07:58.220  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:07:58.220  3264  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:07:58.220  3264  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:07:58.221  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:07:58.222  3264  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 18:07:58.222  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:07:58.222  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 18:07:58.224  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:07:58.224  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:07:58.227  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:07:58.227  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:07:58.228  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:07:58.228  2156  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
03-31 18:07:58.228  2156  2233 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 18:07:58.228  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:07:58.228  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:07:58.228  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
,03-31 18:07:58.228  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-31 18:07:58.228  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 18:07:58.229  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 18:07:58.229  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:07:58.229  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:07:58.229  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:07:58.229  3264  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 18:07:58.229  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:07:58.229  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:58.229  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:07:58.229  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:07:58.234  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:07:58.234   828   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:07:58.235  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:07:58.235  3264  3326 I jxcore-log: 
,03-31 18:07:58.239  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:07:58.239  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:07:58.239  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 18:07:58.239  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:07:58.239  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:07:58.242  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:07:58.242  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:07:58.242  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:07:58.243  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:07:58.243  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:07:58.244  3264  3326 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:07:58.244  3264  3326 I jxcore-log: 
03-31 18:07:58.247  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:58.247  3264  3326 I jxcore-log: 
03-31 18:07:58.248  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:07:58.248  3264  3326 I jxcore-log: 
,03-31 18:07:58.249  3264  3326 I jxcore-log: # setup
03-31 18:07:58.249  3264  3326 I jxcore-log: 
,03-31 18:07:58.344  2156  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-31 18:07:58.344  2156  2233 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 18:07:58.703  2156  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-31 18:08:00.210  3264  3326 I jxcore-log: # 41. Can shift large amounts of data
03-31 18:08:00.210  3264  3326 I jxcore-log: 
,03-31 18:08:00.247  2156  2217 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 18:08:00.694  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 51639, start advertisements: true
03-31 18:08:00.694  3264  3326 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 18:08:00.694  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 18:08:00.698  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:00.699  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
,03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:00.700  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:00.700  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:08:00.700  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:08:00.714  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 18:08:00.714  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:00.714  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:00.714  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:00.723  2156  2173 D BtGatt.GattService: registerClient() - UUID=9da2d372-0346-4e5b-a349-48c7f2e654bd
03-31 18:08:00.723  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=9da2d372-0346-4e5b-a349-48c7f2e654bd, clientIf=5
,03-31 18:08:00.724  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:08:00.725  2156  2221 D BtGatt.GattService: start scan with filters
,03-31 18:08:00.727  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:08:00.728  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 18:08:00.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:00.729  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:08:00.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:08:00.729  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:00.729  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:00.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:00.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-31 18:08:00.729  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:08:00.729  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:00.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 18:08:00.729  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 18:08:00.730  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:08:00.730  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:00.731  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:08:00.731  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:00.731  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:00.731  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:08:00.732  2156  2174 D BtGatt.GattService: registerClient() - UUID=da6d1123-961f-4674-9d7c-a7f0adc62eed
03-31 18:08:00.733  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=da6d1123-961f-4674-9d7c-a7f0adc62eed, clientIf=6
03-31 18:08:00.733  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:08:00.733  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-31 18:08:00.733  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:00.734  2156  2231 D BtGatt.AdvertiseManager: message : 0
03-31 18:08:00.734  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:00.734  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:00.735  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:08:00.738  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-31 18:08:00.740  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:08:00.741  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:08:00.741  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:08:00.741   828  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:00.743  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:00.743  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:08:00.743  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:08:00.743  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:08:00.744  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 18:08:00.744  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:08:00.744  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:08:00.744  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 18:08:00.744  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:00.744  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:08:00.744  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:08:00.744  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:08:00.744  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 18:08:00.745  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:08:00.745  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:08:00.745  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:00.745  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:08:00.745  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:08:00.745  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:00.745  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:08:00.745  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:00.746   828  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:08:00.746  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:00.746  3264  3326 I jxcore-log: 
03-31 18:08:00.746  3264  3757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 18:08:00.748  3264  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 18:08:00.748  3264  3326 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-31 18:08:00.748  3264  3326 I jxcore-log: 
,03-31 18:08:00.751  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 51639, start advertisements: false
03-31 18:08:00.751  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:00.751  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 18:08:00.751  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:00.751  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:00.752  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:00.752  3264  3326 I jxcore-log: 
03-31 18:08:00.753  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:08:00.753  3264  3326 I jxcore-log: 
,03-31 18:08:00.754  3264  3326 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 18:08:00.754  3264  3326 I jxcore-log: 
,03-31 18:08:03.057  2156  2233 W bt-btif : new conn_srvc id:26, app_id:255
03-31 18:08:03.057  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 18:08:03.057  2156  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-31 18:08:03.058  3264  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-31 18:08:03.059  3264  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 368)
03-31 18:08:03.059  3264  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:08:03.060   828   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:03.063  3264  3758 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 368)
,03-31 18:08:03.064  3264  3757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:08:03.070  3264  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:08:03.576  2156  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 18:08:03.582  2156  2156 D BluetoothMapService: onReceive
,03-31 18:08:03.597  3264  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 368),
,03-31 18:08:03.602  3264  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.602  3264  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 368),
03-31 18:08:03.602  3264  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 368
03-31 18:08:03.602  3264  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 368)
03-31 18:08:03.603  3264  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.604  3264  3264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.604  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-31 18:08:03.605  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-31 18:08:03.605  3264  3264 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 18:08:03.605  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-31 18:08:03.606  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:03.606  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:03.606  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 18:08:03.606  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 18:08:03.606  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 18:08:03.606  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
,03-31 18:08:03.606  3264  3758 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 368)
,03-31 18:08:03.611  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:08:03.612  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:08:03.617  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:08:03.617  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:08:03.620  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 18:08:03.622  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:08:03.622  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:03.622  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-31 18:08:03.622  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:03.622  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:08:03.623  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:08:03.623  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 18:08:03.623  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:03.624  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:08:03.637  2156  2221 D BtGatt.GattService: registerClient() - UUID=59b0ff1f-2727-4b50-8664-1ee131b8d0ad
,03-31 18:08:03.638  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=59b0ff1f-2727-4b50-8664-1ee131b8d0ad, clientIf=6
03-31 18:08:03.638  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:08:03.639  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:08:03.644  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:08:03.647  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:08:03.649  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:08:03.650  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 18:08:03.653  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:08:03.655  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:03.655  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 18:08:03.655  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:03.656  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:03.656  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 18:08:03.656  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.656  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:03.656  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:08:03.656  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-31 18:08:03.656  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 18:08:03.658  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-31 18:08:03.658  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.658  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:08:03.660  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-31 18:08:03.660  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.660  2156  2219 D BtGatt.GattService: current time is 281319127807
,03-31 18:08:03.660  2156  2219 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -68, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 66, 77, -22, 34, 110, 66, 1, -128, -77, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 18:08:03.661  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-31 18:08:03.661  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 18:08:03.662  2156  2174 D BtGatt.GattService: registerClient() - UUID=c5b843e0-f80c-4f0f-8742-02a2b42bd952
03-31 18:08:03.662  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=c5b843e0-f80c-4f0f-8742-02a2b42bd952, clientIf=5
03-31 18:08:03.662  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:08:03.662  2156  2173 D BtGatt.GattService: start scan with filters
03-31 18:08:03.663  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:08:03.663  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 18:08:03.664  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 18:08:03.671  2156  2231 D BtGatt.AdvertiseManager: message : 1
,03-31 18:08:03.672  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:08:03.674  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:08:03.675  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 18:08:03.675  2156  2219 D BtGatt.GattService: Client app is not null!
03-31 18:08:03.675  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:08:03.676  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:08:03.676  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-31 18:08:03.676  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:08:03.676  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:03.676  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:08:03.676  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-31 18:08:03.676  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:03.677  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:08:03.677  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:03.677  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.677  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 18:08:03.678  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:08:03.678  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:03.678  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:03.678  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:08:03.679   828  1456 I ActivityManager: Start proc 3759:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
03-31 18:08:03.680  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:03.680  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:03.681  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:03.681  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.681  2156  2174 D BtGatt.GattService: registerClient() - UUID=957fe8cd-4521-4714-93f4-5013fc26b6be
03-31 18:08:03.682  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=957fe8cd-4521-4714-93f4-5013fc26b6be, clientIf=6
,03-31 18:08:03.682  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:08:03.683  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:08:03.685  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
03-31 18:08:03.686  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:08:03.689  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-31 18:08:03.689  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 18:08:03.690  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:08:03.691  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:08:03.691  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:03.691  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:03.691  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:03.691  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:03.691  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:03.692  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:03.693  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:08:03.693  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.694  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:08:03.696  2156  2173 D BtGatt.GattService: registerClient() - UUID=b838accd-fef6-4ac7-ad62-7aa94b4d09c4,
03-31 18:08:03.696  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:03.696  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.696  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:08:03.696  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=b838accd-fef6-4ac7-ad62-7aa94b4d09c4, clientIf=5
03-31 18:08:03.696  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:08:03.696  2156  2174 D BtGatt.GattService: start scan with filters
03-31 18:08:03.697  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:08:03.697  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.697  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 18:08:03.697  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 18:08:03.702  2156  2231 D BtGatt.AdvertiseManager: message : 1
,03-31 18:08:03.702  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:08:03.703  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:08:03.704  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:08:03.704  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:08:03.705  2156  2174 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-31 18:08:03.705  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 18:08:03.705  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 18:08:03.705  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:08:03.705  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:03.705  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:08:03.705  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:08:03.705  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:03.705  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:03.705  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 18:08:03.706  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 18:08:03.706  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.707  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:08:03.707  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.707  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:03.707  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:08:03.709  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:03.709  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.709  2156  2221 D BtGatt.GattService: registerClient() - UUID=52cc6433-8442-45e8-8703-553730d2e589
03-31 18:08:03.709  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=52cc6433-8442-45e8-8703-553730d2e589, clientIf=6
03-31 18:08:03.709  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:08:03.710  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:03.710  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:03.710  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:08:03.713  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:08:03.715  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:08:03.718  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:08:03.719  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 18:08:03.720  2156  2221 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:08:03.720  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:03.720  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:03.720  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:03.720  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:03.720  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:03.721  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:03.721  3264  3264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-31 18:08:03.722  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:08:03.722  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.722  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:08:03.723  2156  2174 D BtGatt.GattService: registerClient() - UUID=c2636af0-51fb-42d6-a9e8-12d60a297dbe,
03-31 18:08:03.723  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=c2636af0-51fb-42d6-a9e8-12d60a297dbe, clientIf=5
,03-31 18:08:03.724  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-31 18:08:03.724  2156  2221 D BtGatt.GattService: start scan with filters
03-31 18:08:03.724  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:03.724  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.724  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:08:03.724  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:03.725  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 18:08:03.725  3264  3264 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-31 18:08:03.725  3264  3264 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-31 18:08:03.725  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:08:03.725  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:08:03.725  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:08:03.725  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:08:03.725  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:08:03.725  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:08:03.726  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:08:03.726  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:03.727  3264  3776 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 369)
03-31 18:08:03.729  3264  3326 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-31 18:08:03.729  3264  3326 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID E0:DB:10:14:E2:C0, but will connect anyway...
03-31 18:08:03.729  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.729  2156  2232 D BtGatt.ScanManager: handling starting scan
03-31 18:08:03.730  3264  3776 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 51639
03-31 18:08:03.730  3264  3776 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 18:08:03.730  3264  3776 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:08:03.730  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-31 18:08:03.730  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 18:08:03.730  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-31 18:08:03.730  3264  3776 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:08:03.731  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:08:03.731  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.731  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0,
03-31 18:08:03.731  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-31 18:08:03.731  3264  3326 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-31 18:08:03.732  3264  3776 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 369)
03-31 18:08:03.732  3264  3776 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 369)
03-31 18:08:03.732  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:08:03.732  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.732  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:03.732  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:08:03.733  3264  3778 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 370, name: Sender)
,03-31 18:08:03.733  3264  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 371)
03-31 18:08:03.733  3264  3779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 18:08:03.734  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:03.734  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.735  2156  2174 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 18:08:03.736  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:03.736  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:03.736  3264  3780 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 372, name: Receiver)
,03-31 18:08:03.767   828   860 D BluetoothManagerService: Message: 20,
03-31 18:08:03.767   828   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1857173a:true
,03-31 18:08:03.770  2156  2233 W bt-sdp  : process_service_search_attr_rsp,
,03-31 18:08:03.780  3759  3759 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524],
,03-31 18:08:03.814  2156  2233 W bt-btif : new conn_srvc id:26, app_id:1
03-31 18:08:03.814  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 18:08:03.814  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-31 18:08:03.814  2156  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 18:08:03.814  3264  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 371)
03-31 18:08:03.814  3264  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 371)
03-31 18:08:03.814  3264  3779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 373)
03-31 18:08:03.814  3264  3779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 373)
03-31 18:08:03.815  3264  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 371)
,03-31 18:08:03.817  3264  3781 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 373)
,03-31 18:08:03.829  3264  3781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 373)
,03-31 18:08:03.830  3264  3781 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.830  3264  3781 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 371)
03-31 18:08:03.830  3264  3781 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 371)
03-31 18:08:03.831  3264  3781 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 373),
03-31 18:08:03.831  3264  3264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.831  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:03.832  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
,03-31 18:08:03.832  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-31 18:08:03.832  3264  3264 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 18:08:03.833  3264  3783 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 374)
03-31 18:08:03.833  3264  3783 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38888
03-31 18:08:03.833  3264  3783 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 18:08:03.833  3264  3783 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 38888 (peer ID: E0:DB:10:14:E2:C0)
03-31 18:08:03.833  3264  3783 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed,
03-31 18:08:03.835  3264  3326 I jxcore-log: INFO testThaliMobileNative: 
03-31 18:08:03.835  3264  3326 I jxcore-log: 
03-31 18:08:03.835  3264  3326 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 18:08:03.835  3264  3326 I jxcore-log: ,
03-31 18:08:03.838  3264  3783 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 38888
03-31 18:08:03.838  3264  3783 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...,
03-31 18:08:03.838  3264  3783 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:08:03.838  3264  3783 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes,
03-31 18:08:03.839  3264  3784 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Sender)
03-31 18:08:03.839  3264  3783 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 374)
03-31 18:08:03.839  3264  3783 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 374)
,03-31 18:08:03.842  3264  3785 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 376, name: Receiver)
,03-31 18:08:03.857  3264  3326 I jxcore-log: INFO testThaliMobileNative: forwardSend
,03-31 18:08:03.857  3264  3326 I jxcore-log: 
,03-31 18:08:03.941   828  1305 I ActivityManager: Start proc 3793:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-31 18:08:03.950   368   368 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 10.067ms
,03-31 18:08:03.956  3759  3759 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 18:08:03.960   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 8.957ms
,03-31 18:08:03.967   828  1404 I ActivityManager: Killing 3412:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-31 18:08:03.970   368   368 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.375ms
,03-31 18:08:04.191   828  1252 I ActivityManager: Killing 3456:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-31 18:08:04.319  3264  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 18:08:04.319  3264  3326 I jxcore-log: 
,03-31 18:08:04.324  3264  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
,03-31 18:08:04.324  3264  3326 I jxcore-log: 
,03-31 18:08:04.329  3264  3326 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 18:08:04.329  3264  3326 I jxcore-log: 
03-31 18:08:04.331  3264  3326 I jxcore-log: ok 177 received should match sent forward
03-31 18:08:04.331  3264  3326 I jxcore-log: 
,03-31 18:08:04.336  3264  3326 I jxcore-log: # teardown
,03-31 18:08:04.336  3264  3326 I jxcore-log: 
,03-31 18:08:06.703  2156  2233 W bt-btif : dm_pm_timer expires
03-31 18:08:06.703  2156  2233 W bt-btif : dm_pm_timer expires 0
,03-31 18:08:06.703  2156  2233 W bt-btif : proc dm_pm_timer expires
,03-31 18:08:07.659  2156  2233 W bt-btif : info:x10,
03-31 18:08:07.659  2156  2219 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-31 18:08:07.681  3759  3759 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 18:08:07.683  3759  3759 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 18:08:07.903  2156  2219 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-31 18:08:07.909  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
03-31 18:08:07.909  2156  2219 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 18:08:07.912  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-31 18:08:07.913  2156  2220 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 18:08:08.009  2156  2219 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-31 18:08:08.010  2156  2220 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 18:08:08.013  2156  2220 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 18:08:08.026  2156  2220 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 18:08:08.048  2156  2233 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-31 18:08:08.048  2156  2233 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 18:08:08.049  3264  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 18:08:08.050  3264  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 377)
03-31 18:08:08.050  3264  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:08:08.051  3264  3815 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 377)
03-31 18:08:08.052   828  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:08.055  3264  3757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:08:08.059  3264  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:08:08.061  3264  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 377)
,03-31 18:08:08.062  3264  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-31 18:08:08.063  3264  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 377)
03-31 18:08:08.063  3264  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 377
,03-31 18:08:08.063  3264  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 377)
03-31 18:08:08.063  3264  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 18:08:08.063  3264  3264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 18:08:08.063  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 18:08:08.063  3264  3264 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-31 18:08:08.064  3264  3264 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 18:08:08.064  3264  3264 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
03-31 18:08:08.064  3264  3264 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 18:08:08.064  3264  3815 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 377)
03-31 18:08:08.067  3264  3816 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 378)
03-31 18:08:08.070  3264  3816 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 51639
,03-31 18:08:08.070  3264  3816 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 18:08:08.070  3264  3816 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:08:08.071  3264  3816 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 18:08:08.071  3264  3816 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 378)
03-31 18:08:08.071  3264  3816 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 378)
,03-31 18:08:08.077  3264  3818 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 379, name: Sender),
03-31 18:08:08.078  3264  3819 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 380, name: Receiver)
,03-31 18:08:08.428  3264  3778 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 370, thread name: Sender)
,03-31 18:08:08.428  3264  3778 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 18:08:08.428  3264  3778 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-31 18:08:08.428  3264  3778 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 369
03-31 18:08:08.429  3264  3778 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 369)
,03-31 18:08:08.429  3264  3778 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 18:08:08.429  3264  3778 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 18:08:08.429  3264  3778 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 372
03-31 18:08:08.429  3264  3778 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 18:08:08.429  3264  3780 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
,03-31 18:08:08.429  3264  3778 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 370
03-31 18:08:08.429  3264  3780 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 372, name: Receiver)
03-31 18:08:08.429  3264  3778 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 369)
03-31 18:08:08.430  3264  3778 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 369)
03-31 18:08:08.430  3264  3778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,03-31 18:08:08.431  3264  3778 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 370, name: Sender)
03-31 18:08:08.434  3264  3818 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 379, thread name: Sender),
03-31 18:08:08.434  3264  3818 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 18:08:08.434  3264  3818 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-31 18:08:08.435  3264  3818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 378
03-31 18:08:08.435  3264  3818 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 378)
03-31 18:08:08.435  3264  3818 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 18:08:08.435  3264  3818 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 18:08:08.435  3264  3818 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 380,
03-31 18:08:08.435  3264  3818 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 18:08:08.435  3264  3819 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Receiver): bt socket closed, read return: -1
03-31 18:08:08.435  3264  3818 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 379
03-31 18:08:08.436  3264  3818 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 378)
03-31 18:08:08.436  3264  3819 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 380, name: Receiver)
03-31 18:08:08.436  3264  3818 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 378)
03-31 18:08:08.436  3264  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-31 18:08:08.437  3264  3818 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 379, name: Sender)
03-31 18:08:08.443  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:08.443  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 18:08:08.443  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 18:08:08.443  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 18:08:08.445  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:08:08.446  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:08.446  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:08.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:08.447  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:08:08.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 18:08:08.447  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:08:08.447  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:08:08.447  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:08:08.447  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 18:08:08.447  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:08.448  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:08:08.448  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:08.448  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:08:08.448  3264  3326 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 18:08:08.448  3264  3326 I jxcore-log: 
03-31 18:08:08.449  3264  3326 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 18:08:08.449  3264  3326 I jxcore-log: 
03-31 18:08:08.450  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:08.450  3264  3326 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-31 18:08:08.450  3264  3326 I jxcore-log: 
03-31 18:08:08.450  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:08.450  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-31 18:08:08.451  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:08.451  3264  3326 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-31 18:08:08.451  3264  3326 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 374)
03-31 18:08:08.451  3264  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 374)
03-31 18:08:08.451  3264  3326 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 18:08:08.451  3264  3326 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-31 18:08:08.451  3264  3326 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 376
03-31 18:08:08.451  3264  3326 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-31 18:08:08.451  3264  3326 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-31 18:08:08.451  3264  3326 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 374)
,03-31 18:08:08.451  3264  3326 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 374)
03-31 18:08:08.451  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 18:08:08.452  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:08:08.452  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:08:08.452  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:08:08.452  3264  3784 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Sender): Socket closed
03-31 18:08:08.452  3264  3784 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Sender)
03-31 18:08:08.452  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:08:08.452  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:08:08.452  3264  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:08:08.452  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:08.452  3264  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:08:08.452  3264  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:08:08.453  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 18:08:08.453  3264  3785 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Receiver): bt socket closed, read return: -1
03-31 18:08:08.453  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:08:08.453  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:08:08.453  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:08:08.453  3264  3785 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 376, name: Receiver)
03-31 18:08:08.453  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:08:08.453  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:08:08.453  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:08:08.453  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:08:08.454  3264  3326 D BluetoothLeScanner: could not find callback wrapper
03-31 18:08:08.454  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:08.454  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:08:08.455  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:08:08.457  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:08:08.459  2156  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
03-31 18:08:08.459  2156  2233 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-31 18:08:08.461  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:08:08.461  2156  2219 D BtGatt.GattService: Client app ,is not null!
03-31 18:08:08.462  2156  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
03-31 18:08:08.463  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:08:08.464  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:08:08.464  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:08.465  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:08:08.465  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 18:08:08.465  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 18:08:08.465  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:08.465  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:08:08.465  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 18:08:08.466  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:08:08.466  3264  3326 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 18:08:08.466  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:08.466  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 18:08:08.466  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:08.466  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:08:08.466  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:08.466  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:08:08.468  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:08:08.468  3264  3326 I jxcore-log: 
03-31 18:08:08.473  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:08:08.473  3264  3326 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 18:08:08.473  3264  3326 I jxcore-log: 
03-31 18:08:08.473   828  1252 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:08:08.478  3264  3326 I jxcore-log: # setup
03-31 18:08:08.478  3264  3326 I jxcore-log: 
03-31 18:08:08.480  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:08:08.482  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:08.482  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:08:08.490  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:08.490  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:08.492  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:08.492  3264  3326 I jxcore-log: 
03-31 18:08:08.493  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:08.493  3264  3326 I jxcore-log: 
,03-31 18:08:08.684  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:08.684  3264  3326 I jxcore-log: 
,03-31 18:08:08.690  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:08.690  3264  3326 I jxcore-log: 
,03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:08.700  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:08.704  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:08.707  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:08.707  3264  3326 I jxcore-log: 
,03-31 18:08:08.709  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:08.709  3264  3326 I jxcore-log: 
,03-31 18:08:08.712  3264  3326 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-31 18:08:08.712  3264  3326 I jxcore-log: 
,03-31 18:08:08.715  2156  2233 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-31 18:08:08.715  2156  2233 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-31 18:08:08.715  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:08.715  3264  3326 I jxcore-log: 
,03-31 18:08:08.884  3264  3326 I jxcore-log: ok 180 specific error should be returned
03-31 18:08:08.884  3264  3326 I jxcore-log: 
,03-31 18:08:08.889  3264  3326 I jxcore-log: # teardown
03-31 18:08:08.889  3264  3326 I jxcore-log: 
,03-31 18:08:09.004  3264  3326 I jxcore-log: ok 181 must be stopped
03-31 18:08:09.004  3264  3326 I jxcore-log: 
,03-31 18:08:09.012  3264  3326 I jxcore-log: # setup
03-31 18:08:09.012  3264  3326 I jxcore-log: 
,03-31 18:08:09.208  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-31 18:08:09.208  3264  3326 I jxcore-log: 
,03-31 18:08:09.213  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-31 18:08:09.213  3264  3326 I jxcore-log: 
,03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:09.222  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:09.226  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:09.228  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:09.228  3264  3326 I jxcore-log: 
,03-31 18:08:09.229  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:09.229  3264  3326 I jxcore-log: 
,03-31 18:08:09.232  3264  3326 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-31 18:08:09.232  3264  3326 I jxcore-log: 
,03-31 18:08:09.234  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:09.234  3264  3326 I jxcore-log: 
,03-31 18:08:09.497  3264  3326 I jxcore-log: ok 182 specific error should be returned
03-31 18:08:09.497  3264  3326 I jxcore-log: 
,03-31 18:08:09.499  3264  3326 I jxcore-log: # teardown
03-31 18:08:09.499  3264  3326 I jxcore-log: 
,03-31 18:08:09.653  3264  3326 I jxcore-log: ok 183 must be stopped
03-31 18:08:09.653  3264  3326 I jxcore-log: 
,03-31 18:08:09.655  3264  3326 I jxcore-log: # setup
03-31 18:08:09.655  3264  3326 I jxcore-log: 
,03-31 18:08:09.825  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:09.825  3264  3326 I jxcore-log: 
,03-31 18:08:09.830  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:09.830  3264  3326 I jxcore-log: 
,03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:09.838  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:09.842  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:09.844  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:09.844  3264  3326 I jxcore-log: 
,03-31 18:08:09.845  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:09.845  3264  3326 I jxcore-log: 
03-31 18:08:09.848  3264  3326 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-31 18:08:09.848  3264  3326 I jxcore-log: 
03-31 18:08:09.849  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:09.849  3264  3326 I jxcore-log: 
,03-31 18:08:10.038  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:10.038  3264  3326 I jxcore-log: 
,03-31 18:08:10.040  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 51336
03-31 18:08:10.040  3264  3326 I jxcore-log: 
,03-31 18:08:10.042  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:10.043  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 18:08:10.043  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:10.045  3264  3326 I jxcore-log: ok 184 no errors
03-31 18:08:10.045  3264  3326 I jxcore-log: 
03-31 18:08:10.047  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:10.047  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-31 18:08:10.047  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:10.050  3264  3326 I jxcore-log: ok 185 still no errors
03-31 18:08:10.050  3264  3326 I jxcore-log: 
,03-31 18:08:10.056  3264  3326 I jxcore-log: # teardown
03-31 18:08:10.056  3264  3326 I jxcore-log: 
,03-31 18:08:10.193  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:10.193  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:10.193  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:10.194  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:10.194  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:10.194  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:10.199  3264  3326 I jxcore-log: ok 186 must be stopped
03-31 18:08:10.199  3264  3326 I jxcore-log: 
,03-31 18:08:10.205  3264  3326 I jxcore-log: # setup
03-31 18:08:10.205  3264  3326 I jxcore-log: 
,03-31 18:08:10.250  2156  2233 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
03-31 18:08:10.250  2156  2233 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x4b
,03-31 18:08:10.396  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:10.396  3264  3326 I jxcore-log: 
,03-31 18:08:10.401  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:10.401  3264  3326 I jxcore-log: 
,03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:10.410  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:10.415  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:10.419  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:10.419  3264  3326 I jxcore-log: 
,03-31 18:08:10.424  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:10.424  3264  3326 I jxcore-log: 
,03-31 18:08:10.432  3264  3326 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 18:08:10.432  3264  3326 I jxcore-log: 
,03-31 18:08:10.434  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:10.434  3264  3326 I jxcore-log: 
,03-31 18:08:10.706  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:10.706  3264  3326 I jxcore-log: 
,03-31 18:08:10.709  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 60698
03-31 18:08:10.709  3264  3326 I jxcore-log: 
,03-31 18:08:10.715  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 51639, start advertisements: false
03-31 18:08:10.715  3264  3326 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2,
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 18:08:10.715  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:10.716  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:08:10.716  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:08:10.716  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-31 18:08:10.722  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:10.722  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:10.722  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:10.729  2156  2221 D BtGatt.GattService: registerClient() - UUID=62ec50ca-e5c4-48dc-ae7c-14e7a1b87838,
,03-31 18:08:10.729  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=62ec50ca-e5c4-48dc-ae7c-14e7a1b87838, clientIf=5
,03-31 18:08:10.730  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:08:10.732  2156  2174 D BtGatt.GattService: start scan with filters
,03-31 18:08:10.733  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:08:10.734  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 18:08:10.734  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:10.734  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:08:10.735  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:08:10.735  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:10.735  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 18:08:10.735  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:10.736  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:08:10.736  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:10.737  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:08:10.737  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:10.737   828  1456 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:10.738  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:10.738  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:08:10.740  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:10.741  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:10.742  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:10.742  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:10.747  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:10.747  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-31 18:08:10.748  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:10.748  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:08:10.748  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:08:10.748  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:08:10.752  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:10.752  3264  3326 I jxcore-log: 
,03-31 18:08:10.754  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 18:08:10.754  3264  3326 I jxcore-log: 
,03-31 18:08:10.757  3264  3326 I jxcore-log: ok 187 no errors,
03-31 18:08:10.757  3264  3326 I jxcore-log: 
,03-31 18:08:10.763  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 51639, start advertisements: false
03-31 18:08:10.763  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:10.763  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:08:10.763  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:10.763  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:10.765  3264  3326 I jxcore-log: ok 188 still no errors
03-31 18:08:10.765  3264  3326 I jxcore-log: 
03-31 18:08:10.771  3264  3326 I jxcore-log: # teardown,
03-31 18:08:10.771  3264  3326 I jxcore-log: 
,03-31 18:08:10.943  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:10.944  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:10.944  3264  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 18:08:10.944  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:08:10.944  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:08:10.944  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 18:08:10.944  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:08:10.944  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:08:10.944  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 18:08:10.948  2156  2174 D BtGatt.GattService: stopScan() - queue size =1,
03-31 18:08:10.950  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-31 18:08:10.950  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:08:10.951  2156  2232 D BtGatt.ScanManager: stopping BLe Batch,
03-31 18:08:10.951  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
03-31 18:08:10.951  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:10.951  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:10.951  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:08:10.951  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 18:08:10.951  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 18:08:10.952  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:10.952  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:10.952  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:10.953  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:08:10.953  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:08:10.953  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 18:08:10.954  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:08:10.954  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:08:10.955  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:10.955  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:08:10.956  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-31 18:08:10.956  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:08:10.956  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:10.956  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:08:10.964  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:08:10.965   828  1306 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:10.973  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:08:10.974  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:10.974  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:08:10.980  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:10.980  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:10.980  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:10.980  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:10.982  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:10.982  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:10.983  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:10.985  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:10.985  3264  3326 I jxcore-log: 
,03-31 18:08:10.987  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:10.987  3264  3326 I jxcore-log: 
,03-31 18:08:10.996  3264  3326 I jxcore-log: ok 189 must be stopped
03-31 18:08:10.996  3264  3326 I jxcore-log: 
,03-31 18:08:11.005  3264  3326 I jxcore-log: # setup
03-31 18:08:11.005  3264  3326 I jxcore-log: 
,03-31 18:08:11.234  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-31 18:08:11.234  3264  3326 I jxcore-log: 
03-31 18:08:11.235  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:11.235  3264  3326 I jxcore-log: 
,03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:11.244  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:11.247  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:11.251  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-31 18:08:11.251  3264  3326 I jxcore-log: 
03-31 18:08:11.255  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:11.255  3264  3326 I jxcore-log: 
03-31 18:08:11.261  3264  3326 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times,
03-31 18:08:11.261  3264  3326 I jxcore-log: 
,03-31 18:08:11.263  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:11.263  3264  3326 I jxcore-log: 
,03-31 18:08:11.574  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:11.574  3264  3326 I jxcore-log: 
,03-31 18:08:11.576  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 47704
03-31 18:08:11.576  3264  3326 I jxcore-log: 
,03-31 18:08:11.583  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 47704, start advertisements: true
03-31 18:08:11.583  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:11.583  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:08:11.583  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:08:11.588  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
,03-31 18:08:11.589  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:11.589  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 18:08:11.589  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:11.596  2156  2174 D BtGatt.GattService: registerClient() - UUID=06aa0c49-aa27-413f-bb08-57bd07499a0b
03-31 18:08:11.597  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=06aa0c49-aa27-413f-bb08-57bd07499a0b, clientIf=5
,03-31 18:08:11.597  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:08:11.598  2156  2173 D BtGatt.GattService: start scan with filters
03-31 18:08:11.599  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:08:11.599  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:11.599  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:08:11.599  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:08:11.599  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:08:11.599  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:11.599  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:11.599  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:08:11.599  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:08:11.599  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-31 18:08:11.599  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:11.599  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:11.600  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:08:11.605  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:08:11.605  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:11.606  2156  2221 D BtGatt.GattService: registerClient() - UUID=34442a1b-2b07-4281-ab8d-d246a36f5055
,03-31 18:08:11.606  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=34442a1b-2b07-4281-ab8d-d246a36f5055, clientIf=6,
03-31 18:08:11.607  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-31 18:08:11.607  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-31 18:08:11.607  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:11.607  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 18:08:11.608  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:08:11.608  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:08:11.610  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:11.610  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:11.611  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:11.612  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:11.613  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:08:11.616  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-31 18:08:11.619  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:08:11.620  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:08:11.620  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 18:08:11.620   828   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:11.623  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:08:11.623  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:08:11.623  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:08:11.623  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-31 18:08:11.624  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 18:08:11.624  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 18:08:11.624  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:08:11.624  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 18:08:11.625  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-31 18:08:11.625  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:08:11.625  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:08:11.625  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:08:11.625  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 18:08:11.625  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:08:11.625  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:11.625  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:08:11.625  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-31 18:08:11.625  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:11.626  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 18:08:11.626  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:11.626  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:11.626   828  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-31 18:08:11.629  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:11.629  3264  3326 I jxcore-log: 
03-31 18:08:11.629  3264  3820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:08:11.631  3264  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:08:11.634  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:11.634  3264  3326 I jxcore-log: 
,03-31 18:08:11.635  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:08:11.635  3264  3326 I jxcore-log: 
,03-31 18:08:11.637  3264  3326 I jxcore-log: ok 190 no errors
03-31 18:08:11.637  3264  3326 I jxcore-log: 
,03-31 18:08:11.643  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 47704, start advertisements: true
,03-31 18:08:11.643  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:08:11.643  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:08:11.643  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:11.644  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:08:11.646  3264  3326 I jxcore-log: ok 191 still no errors,
03-31 18:08:11.646  3264  3326 I jxcore-log: 
,03-31 18:08:11.653  3264  3326 I jxcore-log: # teardown
03-31 18:08:11.653  3264  3326 I jxcore-log: 
,03-31 18:08:12.565  2156  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 18:08:12.571  2156  2156 D BluetoothMapService: onReceive
,03-31 18:08:12.601  3759  3759 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-31 18:08:12.607  3759  3759 I BluetoothClassifier: Bluetooth Device Name: Note4-1,
,03-31 18:08:13.489  2156  2233 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-31 18:08:13.496  2156  2156 D BluetoothMapService: onReceive
,03-31 18:08:13.515  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:13.515  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 18:08:13.515  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:08:13.515  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:08:13.515  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:08:13.516  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-31 18:08:13.516  3264  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:08:13.516  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:08:13.516  3264  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:08:13.516  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 18:08:13.516  3264  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:08:13.516  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:08:13.516  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:08:13.517  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 18:08:13.517  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 18:08:13.517  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:08:13.517  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 18:08:13.522  2156  2174 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:08:13.524  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:13.525  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:13.525  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:08:13.525  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-31 18:08:13.525  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 18:08:13.525  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:08:13.525  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:13.525  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:08:13.525  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:08:13.525  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
,03-31 18:08:13.525  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:08:13.527  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:13.527  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:13.527  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:08:13.530  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-31 18:08:13.530  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:13.530  2156  2219 D BtGatt.GattService: current time is 291188973949
03-31 18:08:13.530  2156  2219 D BtGatt.GattService: Batch record : [29, 51, -85, 49, 99, 73, 1, -128, -81, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 18:08:13.531  2156  2219 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-31 18:08:13.532  3759  3759 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
03-31 18:08:13.533  3759  3759 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 18:08:13.534  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:08:13.534  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:08:13.536  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 18:08:13.536  2156  2219 D BtGatt.GattService: Client app is not null!
03-31 18:08:13.538  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:08:13.539  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 18:08:13.539  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:08:13.539  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:08:13.539  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 18:08:13.539  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-31 18:08:13.539  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:13.540  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:08:13.540  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 18:08:13.540  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:08:13.540  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:13.541  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-31 18:08:13.541  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:13.541  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 18:08:13.545  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 18:08:13.546   828  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:13.551  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:08:13.551  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 18:08:13.551  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-31 18:08:13.554  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-31 18:08:13.554  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-31 18:08:13.554  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-31 18:08:13.554  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 18:08:13.555  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 18:08:13.555  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:08:13.557  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:08:13.557  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:13.557  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:13.559  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:08:13.559  3264  3326 I jxcore-log: 
03-31 18:08:13.559  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-31 18:08:13.559  3264  3326 I jxcore-log: 
03-31 18:08:13.560  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:13.560  3264  3326 I jxcore-log: 
,03-31 18:08:13.564  3264  3326 I jxcore-log: ok 192 must be stopped
03-31 18:08:13.564  3264  3326 I jxcore-log: 
,03-31 18:08:13.569  3264  3326 I jxcore-log: # setup
,03-31 18:08:13.569  3264  3326 I jxcore-log: 
,03-31 18:08:13.661  2156  2217 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 18:08:13.673  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:13.673  3264  3326 I jxcore-log: 
,03-31 18:08:13.678  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:13.678  3264  3326 I jxcore-log: 
,03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:13.689  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:13.693  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:13.696  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:13.696  3264  3326 I jxcore-log: 
03-31 18:08:13.699  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-31 18:08:13.699  3264  3326 I jxcore-log: 
,03-31 18:08:13.705  3264  3326 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-31 18:08:13.705  3264  3326 I jxcore-log: 
,03-31 18:08:13.709  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:13.709  3264  3326 I jxcore-log: 
,03-31 18:08:14.251  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:14.251  3264  3326 I jxcore-log: 
,03-31 18:08:14.253  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 56227
03-31 18:08:14.253  3264  3326 I jxcore-log: 
,03-31 18:08:14.255  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:08:14.255  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:14.255  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:14.258  3264  3326 I jxcore-log: ok 193 no errors
03-31 18:08:14.258  3264  3326 I jxcore-log: 
,03-31 18:08:14.259  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:14.259  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:14.259  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:14.261  3264  3326 I jxcore-log: ok 194 still no errors
03-31 18:08:14.261  3264  3326 I jxcore-log: 
,03-31 18:08:14.266  3264  3326 I jxcore-log: # teardown
03-31 18:08:14.266  3264  3326 I jxcore-log: 
,03-31 18:08:14.382  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:08:14.383  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:14.383  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:14.384  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:14.384  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 18:08:14.384  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:14.388  3264  3326 I jxcore-log: ok 195 must be stopped
03-31 18:08:14.388  3264  3326 I jxcore-log: 
,03-31 18:08:14.394  3264  3326 I jxcore-log: # setup
03-31 18:08:14.394  3264  3326 I jxcore-log: 
,03-31 18:08:15.047  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:15.047  3264  3326 I jxcore-log: 
,03-31 18:08:15.052  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:15.052  3264  3326 I jxcore-log: 
,03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:15.065  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:15.072  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:15.076  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:15.076  3264  3326 I jxcore-log: 
,03-31 18:08:15.081  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:15.081  3264  3326 I jxcore-log: 
,03-31 18:08:15.089  3264  3326 I jxcore-log: # 48. can get the network status before starting
03-31 18:08:15.089  3264  3326 I jxcore-log: 
,03-31 18:08:15.094  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:15.094  3264  3326 I jxcore-log: 
,03-31 18:08:15.417  2156  2233 W bt-btif : dm_pm_timer expires
03-31 18:08:15.418  2156  2233 W bt-btif : dm_pm_timer expires 0
03-31 18:08:15.418  2156  2233 W bt-btif : proc dm_pm_timer expires
,03-31 18:08:16.026  3378  3823 V GoogleAuthProtoRequest: [344] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 18:08:16.078  3378  3824 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 18:08:16.087  3264  3326 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 18:08:16.087  3264  3326 I jxcore-log: 
,03-31 18:08:16.090  3264  3326 I jxcore-log: # teardown
03-31 18:08:16.090  3264  3326 I jxcore-log: 
,03-31 18:08:16.150  1376  1756 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 18:08:16.151  1376  1756 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 18:08:16.152  1376  1756 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 18:08:16.152  1376  1756 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:08:16.162  1376  1748 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
03-31 18:08:16.162  1376  1756 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 18:08:16.162  1376  1748 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 18:08:16.162  1376  1748 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 18:08:16.163  1376  1748 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 18:08:16.174  1376  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:08:16.201  3378  3824 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 18:08:16.203  3378  3824 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
03-31 18:08:16.204  3378  3823 W ExperimentUpdateService: [344] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: [344] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 18:08:16.205  3378  3823 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
03-31 18:08:16.206  3264  3326 I jxcore-log: ok 197 must be stopped
03-31 18:08:16.206  3264  3326 I jxcore-log: 
,03-31 18:08:16.208  3264  3326 I jxcore-log: # setup
03-31 18:08:16.208  3264  3326 I jxcore-log: 
,03-31 18:08:16.783  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:16.783  3264  3326 I jxcore-log: 
,03-31 18:08:16.784  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:16.784  3264  3326 I jxcore-log: 
,03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:16.792  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:16.798  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:16.800  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:16.800  3264  3326 I jxcore-log: 
,03-31 18:08:16.801  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:16.801  3264  3326 I jxcore-log: 
,03-31 18:08:16.804  3264  3326 I jxcore-log: # 49. error returned with bad router
03-31 18:08:16.804  3264  3326 I jxcore-log: 
,03-31 18:08:16.806  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:16.806  3264  3326 I jxcore-log: 
,03-31 18:08:16.923  3264  3326 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-31 18:08:16.923  3264  3326 I jxcore-log: 
,03-31 18:08:16.926  3264  3326 I jxcore-log: ok 198 specific error expected
03-31 18:08:16.926  3264  3326 I jxcore-log: 
,03-31 18:08:16.928  3264  3326 I jxcore-log: # teardown
03-31 18:08:16.928  3264  3326 I jxcore-log: 
,03-31 18:08:17.500  3264  3326 I jxcore-log: ok 199 must be stopped
03-31 18:08:17.500  3264  3326 I jxcore-log: 
,03-31 18:08:17.504  3264  3326 I jxcore-log: # setup
03-31 18:08:17.504  3264  3326 I jxcore-log: 
,03-31 18:08:17.622  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:17.622  3264  3326 I jxcore-log: 
,03-31 18:08:17.623  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:17.623  3264  3326 I jxcore-log: 
,03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:17.629  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:17.631  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:17.633  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:17.633  3264  3326 I jxcore-log: 
03-31 18:08:17.634  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:17.634  3264  3326 I jxcore-log: 
,03-31 18:08:17.637  3264  3326 I jxcore-log: # 50. all services are stopped when we call stop
03-31 18:08:17.637  3264  3326 I jxcore-log: 
03-31 18:08:17.639  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:17.639  3264  3326 I jxcore-log: 
,03-31 18:08:18.231  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:18.231  3264  3326 I jxcore-log: ,
,03-31 18:08:18.234  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 36430
03-31 18:08:18.234  3264  3326 I jxcore-log: 
,03-31 18:08:18.239  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 47704, start advertisements: false
,03-31 18:08:18.239  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:18.239  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 18:08:18.240  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 18:08:18.243  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:18.243  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:18.243  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:18.247  2156  2173 D BtGatt.GattService: registerClient() - UUID=d681c02e-75ee-43f0-a781-ae47ebf0a106
03-31 18:08:18.247  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=d681c02e-75ee-43f0-a781-ae47ebf0a106, clientIf=5
,03-31 18:08:18.248  3264  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:08:18.248  2156  3821 D BtGatt.GattService: start scan with filters
03-31 18:08:18.250  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 18:08:18.250  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:18.250  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:08:18.250  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 18:08:18.250  2156  2232 D BtGatt.ScanManager: handling starting scan,
03-31 18:08:18.251  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:18.251  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:18.251  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:08:18.251   828  1306 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:18.257  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 18:08:18.257  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:18.258  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-31 18:08:18.259  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:18.259  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:18.259  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-31 18:08:18.261  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:18.262  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:18.264  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 18:08:18.264  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:18.267  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:18.267  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 18:08:18.268  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:08:18.268  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:18.268  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:18.268  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:18.272  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:18.272  3264  3326 I jxcore-log: 
03-31 18:08:18.274  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:18.274  3264  3326 I jxcore-log: 
,03-31 18:08:18.283  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 36430, start advertisements: true
03-31 18:08:18.283  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:18.283  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:08:18.283  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:08:18.286  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 18:08:18.286  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-31 18:08:18.286  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:18.286  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:08:18.286  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:08:18.287  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:18.287  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:18.287  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 18:08:18.291  2156  3821 D BtGatt.GattService: registerClient() - UUID=68f96abe-3033-4bfb-a46d-5b1747fe5883
,03-31 18:08:18.291  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=68f96abe-3033-4bfb-a46d-5b1747fe5883, clientIf=6
03-31 18:08:18.292  3264  3281 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:08:18.293  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:08:18.297  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:08:18.300  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:08:18.303  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:08:18.303  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 18:08:18.303  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:08:18.304  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:08:18.304  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:08:18.304  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:08:18.304  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:08:18.304  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:08:18.304   828  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:18.309  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:18.309  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 18:08:18.309  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:18.310  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 18:08:18.310  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:18.311  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 18:08:18.311  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 18:08:18.311  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:08:18.311  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 18:08:18.312  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:08:18.312  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:08:18.312  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:08:18.312   828  1252 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:08:18.313  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 18:08:18.314  3264  3825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 18:08:18.316  3264  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 18:08:18.316  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:08:18.316  3264  3326 I jxcore-log: 
,03-31 18:08:18.323  3264  3326 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 18:08:18.323  3264  3326 I jxcore-log: 
,03-31 18:08:18.325  3264  3326 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 18:08:18.325  3264  3326 I jxcore-log: 
,03-31 18:08:18.327  3264  3326 I jxcore-log: DEBUG createNativeListener: new mux
03-31 18:08:18.327  3264  3326 I jxcore-log: 
,03-31 18:08:18.330  3264  3326 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-31 18:08:18.330  3264  3326 I jxcore-log: 
,03-31 18:08:18.352  3264  3326 I jxcore-log: ok 201 connection to router server should succeed after starting
03-31 18:08:18.352  3264  3326 I jxcore-log: 
,03-31 18:08:18.353  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:08:18.354  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 18:08:18.354  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 18:08:18.354  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:08:18.354  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 18:08:18.354  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 18:08:18.355  3264  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 18:08:18.355  3264  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:08:18.355  3264  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:08:18.355  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 18:08:18.355  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 18:08:18.355  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:08:18.356  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:08:18.356  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-31 18:08:18.356  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:08:18.356  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:08:18.356  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 18:08:18.356  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:08:18.359  2156  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:08:18.361  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:08:18.361  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:18.361  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:08:18.361  2156  3821 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:18.362  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 18:08:18.362  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:18.362  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:08:18.362  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 18:08:18.362  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:08:18.362  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 18:08:18.362  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:08:18.363  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:18.363  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:18.363  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-31 18:08:18.365  2156  2231 D BtGatt.AdvertiseManager: message : 1
03-31 18:08:18.365  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:08:18.365  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:18.366  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-31 18:08:18.368  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-31 18:08:18.368  2156  2219 D BtGatt.GattService: Client app is not null!
03-31 18:08:18.371  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 18:08:18.373  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:08:18.373  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:18.373  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:08:18.373  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 18:08:18.373  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 18:08:18.373  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:18.373  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:08:18.373  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:08:18.374  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:08:18.374  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:08:18.374  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:18.374  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:18.374  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:08:18.374  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:18.374  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:08:18.383  3264  3326 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 18:08:18.383  3264  3326 I jxcore-log: 
,03-31 18:08:18.386  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:08:18.386  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:18.386  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:18.387  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:08:18.387   828  1428 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:18.394  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:08:18.395  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:18.395  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:08:18.398  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 18:08:18.398  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:18.398  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:18.406  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:08:18.406  3264  3326 I jxcore-log: 
,03-31 18:08:18.408  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:18.408  3264  3326 I jxcore-log: 
,03-31 18:08:18.409  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:18.409  3264  3326 I jxcore-log: 
,03-31 18:08:18.415  3264  3326 I jxcore-log: ok 202 is stopped after calling stop
03-31 18:08:18.415  3264  3326 I jxcore-log: 
,03-31 18:08:18.420  3264  3326 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-31 18:08:18.420  3264  3326 I jxcore-log: 
,03-31 18:08:18.424  3264  3326 I jxcore-log: ok 204 connection to router server should fail after stopping
,03-31 18:08:18.424  3264  3326 I jxcore-log: 
,03-31 18:08:18.429  3264  3326 I jxcore-log: # teardown
03-31 18:08:18.429  3264  3326 I jxcore-log: 
,03-31 18:08:18.557  3264  3326 I jxcore-log: ok 205 must be stopped
03-31 18:08:18.557  3264  3326 I jxcore-log: 
,03-31 18:08:18.564  3264  3326 I jxcore-log: # setup
03-31 18:08:18.564  3264  3326 I jxcore-log: 
,03-31 18:08:18.871  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:18.871  3264  3326 I jxcore-log: 
,03-31 18:08:18.873  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:18.873  3264  3326 I jxcore-log: 
,03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:18.881  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:18.883  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:18.884  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:18.884  3264  3326 I jxcore-log: 
03-31 18:08:18.886  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:18.886  3264  3326 I jxcore-log: 
,03-31 18:08:18.889  3264  3326 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-31 18:08:18.889  3264  3326 I jxcore-log: 
,03-31 18:08:18.891  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:18.891  3264  3326 I jxcore-log: 
,03-31 18:08:18.997  3264  3326 I jxcore-log: ok 206 called with right arguments
03-31 18:08:18.997  3264  3326 I jxcore-log: 
,03-31 18:08:18.999  3264  3326 I jxcore-log: # teardown
03-31 18:08:18.999  3264  3326 I jxcore-log: 
,03-31 18:08:19.123  3264  3326 I jxcore-log: ok 207 must be stopped
03-31 18:08:19.123  3264  3326 I jxcore-log: 
,03-31 18:08:19.130  3264  3326 I jxcore-log: # setup
03-31 18:08:19.130  3264  3326 I jxcore-log: 
,03-31 18:08:19.232  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:19.232  3264  3326 I jxcore-log: 
,03-31 18:08:19.234  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:19.234  3264  3326 I jxcore-log: 
,03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:19.242  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:19.247  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:19.248  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:19.248  3264  3326 I jxcore-log: 
,03-31 18:08:19.250  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:19.250  3264  3326 I jxcore-log: 
,03-31 18:08:19.253  3264  3326 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 18:08:19.253  3264  3326 I jxcore-log: 
,03-31 18:08:19.254  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:19.254  3264  3326 I jxcore-log: ,
,03-31 18:08:19.434  3264  3326 I jxcore-log: ok 208 called with right arguments
,03-31 18:08:19.434  3264  3326 I jxcore-log: 
,03-31 18:08:19.436  3264  3326 I jxcore-log: # teardown
03-31 18:08:19.436  3264  3326 I jxcore-log: 
,03-31 18:08:19.544  3264  3326 I jxcore-log: ok 209 must be stopped
03-31 18:08:19.544  3264  3326 I jxcore-log: 
,03-31 18:08:19.553  3264  3326 I jxcore-log: # setup
,03-31 18:08:19.553  3264  3326 I jxcore-log: 
,03-31 18:08:19.651  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-31 18:08:19.651  3264  3326 I jxcore-log: 
,03-31 18:08:19.654  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:19.654  3264  3326 I jxcore-log: 
,03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:19.663  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:19.667  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:19.668  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:19.668  3264  3326 I jxcore-log: 
,03-31 18:08:19.671  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:19.671  3264  3326 I jxcore-log: 
,03-31 18:08:19.675  3264  3326 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 18:08:19.675  3264  3326 I jxcore-log: 
,03-31 18:08:19.677  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:19.677  3264  3326 I jxcore-log: 
,03-31 18:08:19.814  3264  3326 I jxcore-log: ok 210 specific error expected
03-31 18:08:19.814  3264  3326 I jxcore-log: 
,03-31 18:08:19.817  3264  3326 I jxcore-log: # teardown
03-31 18:08:19.817  3264  3326 I jxcore-log: 
,03-31 18:08:19.939  3264  3326 I jxcore-log: ok 211 must be stopped
03-31 18:08:19.939  3264  3326 I jxcore-log: 
,03-31 18:08:19.948  3264  3326 I jxcore-log: # setup
03-31 18:08:19.948  3264  3326 I jxcore-log: 
,03-31 18:08:20.092  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:20.092  3264  3326 I jxcore-log: 
,03-31 18:08:20.096  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:20.096  3264  3326 I jxcore-log: 
,03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:20.107  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:20.112  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:20.114  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:20.114  3264  3326 I jxcore-log: 
,03-31 18:08:20.116  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:20.116  3264  3326 I jxcore-log: 
,03-31 18:08:20.119  3264  3326 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-31 18:08:20.119  3264  3326 I jxcore-log: 
,03-31 18:08:20.120  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:20.120  3264  3326 I jxcore-log: 
,03-31 18:08:20.270  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:20.270  3264  3326 I jxcore-log: 
,03-31 18:08:20.273  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 42793
03-31 18:08:20.273  3264  3326 I jxcore-log: 
,03-31 18:08:20.278  3264  3326 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":45530,"error":{}}
03-31 18:08:20.278  3264  3326 I jxcore-log: 
,03-31 18:08:20.280  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:08:20.280  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:20.280  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:20.281  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:08:20.281  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:20.282  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:20.287  3264  3326 I jxcore-log: ok 212 failure reason is as expected
03-31 18:08:20.287  3264  3326 I jxcore-log: 
,03-31 18:08:20.287  3264  3326 I jxcore-log: ok 213 error description is as expected
03-31 18:08:20.287  3264  3326 I jxcore-log: 
03-31 18:08:20.288  3264  3326 I jxcore-log: ok 214 must be stopped
03-31 18:08:20.288  3264  3326 I jxcore-log: 
,03-31 18:08:20.293  3264  3326 I jxcore-log: # teardown
03-31 18:08:20.293  3264  3326 I jxcore-log: 
,03-31 18:08:20.454  3264  3326 I jxcore-log: ok 215 must be stopped
03-31 18:08:20.454  3264  3326 I jxcore-log: 
,03-31 18:08:20.461  3264  3326 I jxcore-log: # setup
03-31 18:08:20.461  3264  3326 I jxcore-log: 
,03-31 18:08:20.608  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:20.608  3264  3326 I jxcore-log: 
,03-31 18:08:20.613  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:20.613  3264  3326 I jxcore-log: 
,03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:20.625  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:20.630  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 18:08:20.633  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:20.633  3264  3326 I jxcore-log: 
,03-31 18:08:20.636  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:20.636  3264  3326 I jxcore-log: 
,03-31 18:08:20.643  3264  3326 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 18:08:20.643  3264  3326 I jxcore-log: 
,03-31 18:08:20.647  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:20.647  3264  3326 I jxcore-log: 
,03-31 18:08:20.787  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:20.787  3264  3326 I jxcore-log: 
,03-31 18:08:20.789  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 47468
03-31 18:08:20.789  3264  3326 I jxcore-log: 
,03-31 18:08:20.793  3264  3326 I jxcore-log: ok 216 peerIdentifier matches
03-31 18:08:20.793  3264  3326 I jxcore-log: 
,03-31 18:08:20.794  3264  3326 I jxcore-log: ok 217 error description matches
03-31 18:08:20.794  3264  3326 I jxcore-log: 
,03-31 18:08:20.798  3264  3326 I jxcore-log: # teardown
03-31 18:08:20.798  3264  3326 I jxcore-log: 
,03-31 18:08:20.939  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 18:08:20.939  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 18:08:20.939  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:20.942  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:20.942  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:20.942  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:20.953  3264  3326 I jxcore-log: ok 218 must be stopped
03-31 18:08:20.953  3264  3326 I jxcore-log: 
,03-31 18:08:20.958  3264  3326 I jxcore-log: # setup
03-31 18:08:20.958  3264  3326 I jxcore-log: 
,03-31 18:08:21.089  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:08:21.089  3264  3326 I jxcore-log: 
,03-31 18:08:21.093  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:08:21.093  3264  3326 I jxcore-log: 
,03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:08:21.100  3264  3326 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:08:21.106  3264  3326 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
03-31 18:08:21.108  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:08:21.108  3264  3326 I jxcore-log: 
,03-31 18:08:21.109  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:08:21.109  3264  3326 I jxcore-log: 
,03-31 18:08:21.119  3264  3326 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-31 18:08:21.119  3264  3326 I jxcore-log: 
,03-31 18:08:21.120  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:08:21.120  3264  3326 I jxcore-log: 
,03-31 18:08:21.220  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:21.220  3264  3326 I jxcore-log: 
,03-31 18:08:21.222  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 34370
03-31 18:08:21.222  3264  3326 I jxcore-log: 
,03-31 18:08:21.228  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 36430, start advertisements: false
03-31 18:08:21.228  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 18:08:21.228  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 18:08:21.228  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 18:08:21.234  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 18:08:21.234  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:21.234  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:21.240  2156  2173 D BtGatt.GattService: registerClient() - UUID=867d6c6e-22a3-45c6-a9a9-007962e1043e
03-31 18:08:21.241  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=867d6c6e-22a3-45c6-a9a9-007962e1043e, clientIf=5
03-31 18:08:21.242  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:08:21.242  2156  3821 D BtGatt.GattService: start scan with filters
,03-31 18:08:21.245  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 18:08:21.245  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:21.245  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:08:21.245  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:08:21.245  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:21.245  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 18:08:21.245  2156  2232 D BtGatt.ScanManager: handling starting scan
03-31 18:08:21.245  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 18:08:21.253   828  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:21.255  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-31 18:08:21.255  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.258  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 18:08:21.258  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.261  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:21.261  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:08:21.264  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:21.264  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:08:21.264  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:21.264  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 18:08:21.264  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:21.265  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-31 18:08:21.265  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.266  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 18:08:21.267  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:21.267  3264  3326 I jxcore-log: 
,03-31 18:08:21.267  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-31 18:08:21.267  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:21.268  3264  3326 I jxcore-log: ok 219 discoveryActive matches
03-31 18:08:21.268  3264  3326 I jxcore-log: 
,03-31 18:08:21.269  3264  3326 I jxcore-log: ok 220 advertisingActive matches
03-31 18:08:21.269  3264  3326 I jxcore-log: 
03-31 18:08:21.270  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:21.270  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:21.270  3264  3326 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 18:08:21.271  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,03-31 18:08:21.271  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:08:21.271  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:08:21.271  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:08:21.271  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 18:08:21.271  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 18:08:21.275  2156  2173 D BtGatt.GattService: stopScan() - queue size =1
03-31 18:08:21.277  2156  3821 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:21.278  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 18:08:21.278  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:08:21.278  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:08:21.278  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-31 18:08:21.278  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:21.278  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 18:08:21.278  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 18:08:21.278  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:21.279  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:08:21.281  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 18:08:21.281  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 18:08:21.282  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:08:21.283  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:21.283  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:21.283  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:08:21.284  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:08:21.285  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-31 18:08:21.285  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.290  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:08:21.291  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 18:08:21.291  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:21.291  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:08:21.295  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:21.295  3264  3326 I jxcore-log: 
,03-31 18:08:21.296  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:08:21.297   828  1252 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-31 18:08:21.303  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 18:08:21.304  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:21.304  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:08:21.308  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:21.308  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:21.308  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:21.308  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:21.310  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 18:08:21.310  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:21.310  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 18:08:21.312  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:21.312  3264  3326 I jxcore-log: 
,03-31 18:08:21.312  3264  3326 I jxcore-log: ok 221 discoveryActive matches
03-31 18:08:21.312  3264  3326 I jxcore-log: 
03-31 18:08:21.313  3264  3326 I jxcore-log: ok 222 advertisingActive matches
03-31 18:08:21.313  3264  3326 I jxcore-log: 
,03-31 18:08:21.316  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:21.316  3264  3326 I jxcore-log: 
,03-31 18:08:21.334  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:21.334  3264  3326 I jxcore-log: ,
03-31 18:08:21.336  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 50682
03-31 18:08:21.336  3264  3326 I jxcore-log: 
,03-31 18:08:21.341  3264  3326 I io.jxcore.node.ConnectionHelper: start: Port number: 50682, start advertisements: true
,03-31 18:08:21.341  3264  3326 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 18:08:21.342  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 18:08:21.342  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 18:08:21.348  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 18:08:21.348  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 18:08:21.349  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 18:08:21.349  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 18:08:21.354  2156  2173 D BtGatt.GattService: registerClient() - UUID=4c7613c9-0d98-4d4b-8164-3df08613c876,
03-31 18:08:21.354  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=4c7613c9-0d98-4d4b-8164-3df08613c876, clientIf=5
,03-31 18:08:21.355  3264  3281 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-31 18:08:21.356  2156  2221 D BtGatt.GattService: start scan with filters
03-31 18:08:21.357  2156  2232 D BtGatt.ScanManager: handling starting scan
,03-31 18:08:21.359  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 18:08:21.359  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 18:08:21.359  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 18:08:21.360  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 18:08:21.360  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:21.360  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 18:08:21.360  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 18:08:21.360  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 18:08:21.361  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-31 18:08:21.361  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:21.361  2156  2219 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-31 18:08:21.361  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.361  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 18:08:21.361  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 18:08:21.364  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-31 18:08:21.364  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:21.365  2156  2232 D BtGatt.ScanManager: Starting BLE batch scan
03-31 18:08:21.365  2156  2232 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-31 18:08:21.369  2156  2219 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-31 18:08:21.369  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-31 18:08:21.371  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-31 18:08:21.371  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.373  2156  2221 D BtGatt.GattService: registerClient() - UUID=78006fac-a5c5-45a7-afa0-76c341bac764
03-31 18:08:21.374  2156  2219 D BtGatt.GattService: onClientRegistered() - UUID=78006fac-a5c5-45a7-afa0-76c341bac764, clientIf=6
03-31 18:08:21.374  3264  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-31 18:08:21.378  2156  2231 D BtGatt.AdvertiseManager: message : 0
,03-31 18:08:21.382  2156  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 18:08:21.385  2156  2219 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-31 18:08:21.388  2156  2219 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-31 18:08:21.388  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 18:08:21.388  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 18:08:21.389   828  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:08:21.396  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:21.396  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 18:08:21.396  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 18:08:21.396  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:08:21.397  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 18:08:21.398  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-31 18:08:21.398  3264  3326 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 18:08:21.398  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 18:08:21.399  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 18:08:21.399  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 18:08:21.399  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 18:08:21.399  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 18:08:21.399  3264  3264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 18:08:21.399  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 18:08:21.399  3264  3264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:21.400  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 18:08:21.400  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 18:08:21.400  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 18:08:21.400  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 18:08:21.400  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 18:08:21.400   828  1404 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 18:08:21.400  3264  3326 I io.jxcore.node.ConnectionHelper: start: OK
03-31 18:08:21.402  3264  3826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 18:08:21.405  3264  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 18:08:21.406  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:21.406  3264  3326 I jxcore-log: 
,03-31 18:08:21.414  3264  3326 I jxcore-log: not ok 223 discoveryActive matches
,03-31 18:08:21.414  3264  3326 I jxcore-log: 
03-31 18:08:21.414  3264  3326 I jxcore-log:   ---
03-31 18:08:21.414  3264  3326 I jxcore-log: 
03-31 18:08:21.414  3264  3326 I jxcore-log:     operator: equal
03-31 18:08:21.414  3264  3326 I jxcore-log: ,
03-31 18:08:21.414  3264  3326 I jxcore-log:     expected: false
03-31 18:08:21.414  3264  3326 I jxcore-log: 
03-31 18:08:21.414  3264  3326 I jxcore-log:     actual:   true,
,03-31 18:08:21.414  3264  3326 I jxcore-log: 
03-31 18:08:21.415  3264  3326 I jxcore-log:   ...
03-31 18:08:21.415  3264  3326 I jxcore-log: 
03-31 18:08:21.417  3264  3326 I jxcore-log: not ok 224 advertisingActive matches
,03-31 18:08:21.417  3264  3326 I jxcore-log: 
03-31 18:08:21.417  3264  3326 I jxcore-log:   ---
03-31 18:08:21.417  3264  3326 I jxcore-log: 
03-31 18:08:21.418  3264  3326 I jxcore-log:     operator: equal
03-31 18:08:21.418  3264  3326 I jxcore-log: 
,03-31 18:08:21.418  3264  3326 I jxcore-log:     expected: true
03-31 18:08:21.418  3264  3326 I jxcore-log: 
03-31 18:08:21.418  3264  3326 I jxcore-log:     actual:   false
03-31 18:08:21.418  3264  3326 I jxcore-log: 
,03-31 18:08:21.418  3264  3326 I jxcore-log:   ...
03-31 18:08:21.418  3264  3326 I jxcore-log: 
03-31 18:08:21.420  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 18:08:21.420  3264  3326 I jxcore-log: ,
03-31 18:08:21.420  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 18:08:21.420  3264  3326 I jxcore-log: 
03-31 18:08:21.425  3264  3326 I jxcore-log: not ok 225 discoveryActive matches
,03-31 18:08:21.425  3264  3326 I jxcore-log: 
03-31 18:08:21.425  3264  3326 I jxcore-log:   ---
03-31 18:08:21.425  3264  3326 I jxcore-log: 
03-31 18:08:21.425  3264  3326 I jxcore-log:     operator: equal
03-31 18:08:21.425  3264  3326 I jxcore-log: ,
03-31 18:08:21.425  3264  3326 I jxcore-log:     expected: false
03-31 18:08:21.425  3264  3326 I jxcore-log: 
03-31 18:08:21.426  3264  3326 I jxcore-log:     actual:   true,
03-31 18:08:21.426  3264  3326 I jxcore-log: 
,03-31 18:08:21.426  3264  3326 I jxcore-log:   ...
03-31 18:08:21.426  3264  3326 I jxcore-log: 
,03-31 18:08:21.433  3264  3326 I jxcore-log: not ok 226 advertisingActive matches
03-31 18:08:21.433  3264  3326 I jxcore-log: 
03-31 18:08:21.433  3264  3326 I jxcore-log:   ---
03-31 18:08:21.433  3264  3326 I jxcore-log: 
,03-31 18:08:21.433  3264  3326 I jxcore-log:     operator: equal
03-31 18:08:21.433  3264  3326 I jxcore-log: 
03-31 18:08:21.433  3264  3326 I jxcore-log:     expected: false
03-31 18:08:21.433  3264  3326 I jxcore-log: 
,03-31 18:08:21.433  3264  3326 I jxcore-log:     actual:   true
03-31 18:08:21.433  3264  3326 I jxcore-log: 
03-31 18:08:21.434  3264  3326 I jxcore-log:   ...
03-31 18:08:21.434  3264  3326 I jxcore-log: 
,03-31 18:08:21.436  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 18:08:21.436  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 18:08:21.436  3264  3326 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 18:08:21.437  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 18:08:21.437  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 18:08:21.439  3264  3326 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 18:08:21.440  3264  3826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-31 18:08:21.440  3264  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 18:08:21.440  3264  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 18:08:21.440  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 18:08:21.441  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 18:08:21.441  3264  3264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 18:08:21.442  3264  3264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 18:08:21.442  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 18:08:21.442  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 18:08:21.442  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 18:08:21.442  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 18:08:21.442  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 18:08:21.445  2156  2173 D BtGatt.GattService: stopScan() - queue size =1
,03-31 18:08:21.446  2156  2221 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-31 18:08:21.447  2156  2219 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-31 18:08:21.447  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.447  2156  2232 D BtGatt.ScanManager: stopping BLe Batch
03-31 18:08:21.448  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 18:08:21.448  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 18:08:21.448  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 18:08:21.448  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 18:08:21.448  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 18:08:21.448  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 18:08:21.448  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 18:08:21.449  2156  2219 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-31 18:08:21.450  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-31 18:08:21.450  2156  2232 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-31 18:08:21.451  2156  2219 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-31 18:08:21.451  2156  2219 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-31 18:08:21.454  2156  2231 D BtGatt.AdvertiseManager: message : 1,
03-31 18:08:21.455  2156  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-31 18:08:21.458  2156  2219 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-31 18:08:21.458  2156  2219 D BtGatt.GattService: Client app is not null!
,03-31 18:08:21.459  2156  2173 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 18:08:21.460  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 18:08:21.460  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 18:08:21.460  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 18:08:21.460  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 18:08:21.460  3264  3326 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 18:08:21.461  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:21.461  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 18:08:21.461  3264  3326 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 18:08:21.462  3264  3326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 18:08:21.462  3264  3326 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 18:08:21.463  3264  3264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 18:08:21.463  3264  3264 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 18:08:21.463  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:08:21.463  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 18:08:21.463  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 18:08:21.473  3264  3326 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 18:08:21.473  3264  3326 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 18:08:21.473  3264  3326 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 18:08:21.478  3264  3264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 18:08:21.478   828   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-31 18:08:21.487  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 18:08:21.487  3264  3264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 18:08:21.487  3264  3264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 18:08:21.492  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 18:08:21.492  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 18:08:21.492  3264  3264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 18:08:21.494  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 18:08:21.494  3264  3326 I jxcore-log: 
,03-31 18:08:21.494  3264  3326 I jxcore-log: ok 227 discoveryActive matches
03-31 18:08:21.494  3264  3326 I jxcore-log: 
,03-31 18:08:21.498  3264  3326 I jxcore-log: not ok 228 advertisingActive matches
03-31 18:08:21.498  3264  3326 I jxcore-log: ,
03-31 18:08:21.498  3264  3326 I jxcore-log:   ---
03-31 18:08:21.498  3264  3326 I jxcore-log: 
,03-31 18:08:21.498  3264  3326 I jxcore-log:     operator: equal
03-31 18:08:21.498  3264  3326 I jxcore-log: 
03-31 18:08:21.498  3264  3326 I jxcore-log:     expected: false
03-31 18:08:21.498  3264  3326 I jxcore-log: 
03-31 18:08:21.498  3264  3326 I jxcore-log:     actual:   true
,03-31 18:08:21.498  3264  3326 I jxcore-log: 
03-31 18:08:21.498  3264  3326 I jxcore-log:   ...
03-31 18:08:21.498  3264  3326 I jxcore-log: 
03-31 18:08:21.500  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:21.500  3264  3326 I jxcore-log: ,
03-31 18:08:21.501  3264  3326 I jxcore-log: ok 229 discoveryActive matches
03-31 18:08:21.501  3264  3326 I jxcore-log: 
03-31 18:08:21.501  3264  3326 I jxcore-log: ok 230 advertisingActive matches
03-31 18:08:21.501  3264  3326 I jxcore-log: 
,03-31 18:08:21.503  3264  3326 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 18:08:21.503  3264  3326 I jxcore-log: 
,03-31 18:08:21.515  3264  3326 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 18:08:21.515  3264  3326 I jxcore-log: 
,03-31 18:08:21.517  3264  3326 I jxcore-log: DEBUG createNativeListener: listening 47223,
03-31 18:08:21.517  3264  3326 I jxcore-log: 
,03-31 18:08:21.526  3264  3326 I jxcore-log: Uncaught Promise Rejection: {},
03-31 18:08:21.526  3264  3326 I jxcore-log: 
,03-31 18:08:21.530  3264  3326 E jxcore-log: Trace: [Error: Call Stop!],
03-31 18:08:21.530  3264  3326 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 18:08:21.530  3264  3326 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
,03-31 18:08:21.530  3264  3326 E jxcore-log:     at emit@events.js:98:1
03-31 18:08:21.530  3264  3326 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 18:08:21.530  3264  3326 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 18:08:21.530  3264  3326 E jxcore-log:     at $0a@node.js:917:1,
03-31 18:08:21.530  3264  3326 E jxcore-log: 
03-31 18:08:21.530  3264  3326 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
,03-31 18:08:21.530  3264  3326 I jxcore-log: 
03-31 18:08:21.532  3264  3326 I jxcore-log: # teardown
03-31 18:08:21.532  3264  3326 I jxcore-log: 
,03-31 18:08:21.819  3827  3827 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<,
03-31 18:08:21.822  3827  3827 D AndroidRuntime: CheckJNI is OFF
,03-31 18:08:21.935  3827  3827 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 18:08:21.948   828   856 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-31 18:08:21.948   828   856 I ActivityManager: Killing 3264:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-31 18:08:22.029   828   866 W PackageSettings: Skipping PackageSetting{2cb4ca02 com.example.hello/10273} due to missing metadata
,03-31 18:08:22.071   828  1305 I WindowState: WIN DEATH: Window{181c79c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 18:08:22.072   828  1011 D WifiService: Client connection lost with reason: 4
,03-31 18:08:22.158   828   856 W ActivityManager: Force removing ActivityRecord{92cf7cf u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-31 18:08:22.173   828   828 V ActivityManager: Display changed displayId=0
,03-31 18:08:22.186   828   866 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-31 18:08:22.215   828  1306 W ActivityManager: Spurious death for ProcessRecord{3a84f5fd 3264:com.test.thalitest/u0a95}, curProc for 3264: null
,03-31 18:08:22.216   828  1047 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-31 18:08:22.224   828  1002 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 18:08:22.229  2912  2912 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-31 18:08:22.231  1234  1234 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 18:08:22.264  1234  3842 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 18:08:22.267  1234  3842 I Decoder : createOrResetDecoder
,03-31 18:08:22.269  1067  1067 I art     : Explicit concurrent mark sweep GC freed 51010(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 1.288ms total 54.643ms
03-31 18:08:22.269   828  1404 I ActivityManager: Start proc 3843:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-31 18:08:22.273   828  1252 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3264 uid 10095
03-31 18:08:22.275  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-31 18:08:22.285  1376  1376 I ConfigService: onCreate
,03-31 18:08:22.316   828   828 I art     : Explicit concurrent mark sweep GC freed 22995(1686KB) AllocSpace objects, 6(473KB) LOS objects, 31% free, 34MB/50MB, paused 1.470ms total 113.244ms
,03-31 18:08:22.317   828   866 I art     : WaitForGcToComplete blocked for 36.149ms for cause Explicit
,03-31 18:08:22.335  1234  3842 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 18:08:22.344  1352  1352 I art     : Explicit concurrent mark sweep GC freed 4952(362KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 756us total 20.759ms
,03-31 18:08:22.371  1234  3842 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-31 18:08:22.375  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 18:08:22.375  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 18:08:22.378  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 18:08:22.378  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 18:08:22.378  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 18:08:22.378  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 18:08:22.379  1234  3842 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 18:08:22.379  1234  3842 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 18:08:22.379  1234  3842 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 18:08:22.379  1234  3842 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 18:08:22.379  1234  3842 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 18:08:22.379  1234  3842 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 18:08:22.401   828   828 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 18:08:22.401   828   828 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 18:08:22.425  3843  3875 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 18:08:22.447   828  1252 I ActivityManager: Start proc 3876:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 18:08:22.462  1352  1352 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-31 18:08:22.463  1352  1352 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-31 18:08:22.470   828   866 I art     : Explicit concurrent mark sweep GC freed 9237(725KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.330ms total 151.923ms
,03-31 18:08:22.475  3843  3873 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-31 18:08:22.521   828  1305 I ActivityManager: Start proc 3898:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 18:08:22.524   828  1428 I ActivityManager: Killing 3558:com.android.chrome/u0a40 (adj 15): empty #17
,03-31 18:08:22.538  3827  3827 I art     : System.exit called, status: 0
03-31 18:08:22.538  3827  3827 I AndroidRuntime: VM exiting with result code 0.
,03-31 18:08:22.638  3759  3759 W LocationOracleImpl: Best location was null
,03-31 18:08:22.644  3759  3759 I VS.Container: create_recognizer
,03-31 18:08:22.646  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 18:08:22.684   828   866 I ActivityManager: Start proc 3920:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-31 18:08:22.694  1376  1376 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,03-31 18:08:22.694  1376  1376 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
03-31 18:08:22.695  1376  1376 E AndroidRuntime: FATAL EXCEPTION: main
03-31 18:08:22.695  1376  1376 E AndroidRuntime: Process: com.google.process.gapps, PID: 1376
03-31 18:08:22.695  1376  1376 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-31 18:08:22.695  1376  1376 E AndroidRuntime: 	... 9 more
,03-31 18:08:22.719   828  3948 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 18:08:22.720   828   856 D Atlas   : Validating map...
,03-31 18:08:22.728  3898  3943 W FileUtils: Failed to chmod(/data/data/com.android.keychain/databases/grants.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-31 18:08:22.729  3759  3950 I HotwordRecognitionRnr: Starting hotword detection.
,03-31 18:08:22.732  3759  3792 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:08:22.732  3759  3792 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database ,in read/write mode.
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-31 18:08:22.732  3759  3792 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-31 18:08:22.736  3759  3951 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@1778f3b2
03-31 18:08:22.737  3759  3792 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
03-31 18:08:22.739   828  1305 I ActivityManager: Killing 3613:com.qualcomm.timeservice/1000 (adj 15): empty #17
03-31 18:08:22.739   356  3953 I AudioFlinger: AudioFlinger's thread 0xb4d8f000 ready to run
03-31 18:08:22.741   356  1030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 18:08:22.742  3759  3951 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@1778f3b2
03-31 18:08:22.748  3843  3873 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
03-31 18:08:22.749  3843  3873 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-31 18:08:22.749  3843  3873 E AndroidRuntime: Process: android.process.acore, PID: 3843
03-31 18:08:22.749  3843  3873 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 18:08:22.749  3843  3873 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 18:08:22.752   356  3953 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 18:08:22.752   356  3953 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 18:08:22.752   356  3953 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 18:08:22.752   356  3953 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
03-31 18:08:22.757   356  3953 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 18:08:22.850   828  1306 I ActivityManager: Killing 3635:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-31 18:08:22.856   828  3955 E DropBoxManagerService: Can't write: system_app_crash
03-31 18:08:22.856   828  3955 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 18:08:22.856   828  3955 E DropBoxManagerService: 	... 5 more
,03-31 18:08:22.865   828  3948 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 18:08:22.871   828  3948 D OpenGLRenderer: Enabling debug mode 0
,03-31 18:08:22.896  1376  1396 I art     : Explicit concurrent mark sweep GC freed 51275(2MB) AllocSpace objects, 19(1820KB) LOS objects, 36% free, 27MB/43MB, paused 1.106ms total 47.556ms
,03-31 18:08:22.975  3759  3759 I HotwordWorker: onReady
,03-31 18:08:23.000  3759  3960 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 18:08:23.024  1808  1840 W Icing   : Received bad json for section weights override -- ignoring.
03-31 18:08:23.024  1808  1840 W Icing   : Received bad json for corpus context scoring override -- ignoring.
03-31 18:08:23.025  1808  1840 W Icing   : Received bad json for section weights override -- ignoring.
03-31 18:08:23.025  1808  1840 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-31 18:08:23.033   828  1427 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32e658a3}
,03-31 18:08:23.036   828  1010 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-31 18:08:23.039  3759  3919 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-31 18:08:23.039  3759  3919 E FileBytesWriter: Failed to write new file: loracle.new
,03-31 18:08:23.051  3759  3963 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
03-31 18:08:23.051  3759  3919 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-31 18:08:23.051  3759  3919 E FileBytesWriter: Failed to write new file: loracle.new
,03-31 18:08:23.148  3759  3935 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1778f3b2
,03-31 18:08:23.151  3759  3759 I HotwordDetector: Closing mic
,03-31 18:08:23.167  3759  3965 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 18:08:23.172  3759  3759 W TRUiThreadExecutor: Task does not implement UiTask: com.google.common.g.a.p@2808ea1a
,03-31 18:08:23.218   356  3953 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-31 18:08:23.220   356  3953 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-31 18:08:23.241   356  1030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-31 18:08:23.244  3759  3950 I HotwordRecognitionRnr: Hotword detection finished
03-31 18:08:23.244  3759  3946 I HotwordRecognitionRnr: Stopping hotword detection.
,03-31 18:08:23.426  1234  3842 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-31 18:08:23.426  1234  3842 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-31 18:08:23.497  1234  3842 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-31 18:08:23.497  1234  3842 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-31 18:08:23.528  1234  3842 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-31 18:08:23.528  1234  3842 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-31 18:08:23.529  1234  3842 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-31 18:08:23.529  1234  3842 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-31 18:08:24.731   828  1429 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@32e658a3}
,03-31 18:08:25.072  1808  1835 W Icing   : Usage reports not received in time.,
,03-31 18:08:27.115  1808  1835 W Icing   : Usage reports not received in time.
,03-31 18:08:27.133   828  1404 I ActivityManager: Killing 3587:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-31 18:08:27.722  3759  3973 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-31 18:08:29.441  2156  2223 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 18:08:33.136   828  1253 E QMI_FW  : xport_send: Sendto failed for port 4096
03-31 18:08:33.136   828  1253 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-31 18:08:33.136   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660564755
,03-31 18:08:33.136   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-31 18:08:33.137   828  1253 E QMI_FW  : xport_send: Sendto failed for port 4096
03-31 18:08:33.137   828  1253 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-31 18:08:33.137   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660564755
,03-31 18:08:33.139   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 18:08:33.145   872   872 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
03-31 18:08:33.145   872   872 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error,
,03-31 18:08:33.145   872   872 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-31 18:08:33.146   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 18:08:33.223   365   916 E ThermalEngine: qmi_clnt_error_cb: with error -2 called for clnt FUSION
,03-31 18:08:33.224   356   925 D         : csd_client_error_cb: error -2 cb_data 0xb548a060
,03-31 18:08:33.224   356   925 D         : csd_client_error_cb: MDM reset
03-31 18:08:33.224   365   916 E ThermalEngine: modem_clnt_error_cb: with -2 called for clnt 0x6
03-31 18:08:33.225   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb0
03-31 18:08:33.225   373   924 I Atfwd_Daemon: Modem Out Of Service --> Release ATCOP service client handles, if any
03-31 18:08:33.225   373   924 I Atfwd_Daemon: release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
03-31 18:08:33.225   356   825 E         : deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
03-31 18:08:33.225   356   825 E         : csd_service_deinit: Error -1 deiniting CSD
,03-31 18:08:33.233   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb1
03-31 18:08:33.236   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb3
03-31 18:08:33.236   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb2
03-31 18:08:33.236   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb4
03-31 18:08:33.239   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb5
03-31 18:08:33.241   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb6
03-31 18:08:33.245   373   924 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb7
,03-31 18:08:33.251   365  3976 I ThermalEngine: qmi: Instance id 157 for fusion TS
,03-31 18:08:33.476  1287  2513 V ImsSenderRxr: Read packet: 15 bytes
,03-31 18:08:33.476  1287  2513 V ImsSenderRxr: processResponse
,03-31 18:08:33.476  1287  2513 D ImsSenderRxr: Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
,03-31 18:08:33.476  1287  2513 D ImsSenderRxr:  Tag -1 3 213 0
03-31 18:08:33.486   356  1031 I str_params: key: 'all_call_states' value: ''
03-31 18:08:33.490   356  1033 I str_params: key: 'all_call_states' value: ''
03-31 18:08:33.492   356   356 I str_params: key: 'all_call_states' value: ''
,03-31 18:08:33.499   828   828 D GpsLocationProvider: received SIM realted action: 
,03-31 18:08:33.499  1067  1067 V KeyguardUpdateMonitor: onSubscriptionInfoChanged()
,03-31 18:08:33.506  1067  1067 V KeyguardUpdateMonitor: onSubscriptionInfoChanged: list is null
,03-31 18:08:33.513   356   825 E         : csd_service_deinit: notifier handle release rc:0
,03-31 18:08:33.515   828   828 D GpsLocationProvider: SIM MCC/MNC is still not available
,03-31 18:08:33.550   365   920 E ThermalEngine: qmi_clnt_error_cb: with error -2 called for clnt MODEM
,03-31 18:08:33.575   828  1253 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -2
03-31 18:08:33.575   828  1273 E LocSvc_ApiV02: E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
03-31 18:08:33.575   828  1253 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-31 18:08:33.583   828  1253 E QMI_FW  : xport_send: Sendto failed for port 4096
03-31 18:08:33.583   828  1253 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-31 18:08:33.583   828  1253 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
03-31 18:08:33.583   828  1253 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -2
03-31 18:08:33.583   828  1253 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
03-31 18:08:33.583   828  1366 E LocSvc_ApiV02: E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error

```
