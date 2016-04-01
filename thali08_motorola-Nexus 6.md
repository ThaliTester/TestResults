#### Test 648099366fd8e87_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
04-01 10:28:45.173  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:45.247  1492  1678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
04-01 10:28:45.249  1492  1678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:45.250  1492  1678 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:45.250  1492  1678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
04-01 10:28:45.264  1492  1678 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
04-01 10:28:45.307  2747  2747 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
04-01 10:28:45.308  2747  2747 D Finsky  : [1] 5.onFinished: Installation state replication failed.
04-01 10:28:45.309  2747  2747 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
04-01 10:28:45.519  3297  3297 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 10:28:45.522  3297  3297 D AndroidRuntime: CheckJNI is OFF
04-01 10:28:45.645  3297  3297 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-01 10:28:45.650   821  1298 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-01 10:28:45.658   821  1298 V WindowManager: addAppToken: AppWindowToken{3cbb9759 token=Token{3ba0fa0 ActivityRecord{bd7b0a3 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
04-01 10:28:45.660  3297  3297 D AndroidRuntime: Shutting down VM
04-01 10:28:45.671  1519  1519 I HotwordDetector: Closing mic
04-01 10:28:45.672  1519  1780 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@196e5bf0
04-01 10:28:45.681   821   860 V WindowManager: Adding window Window{38d632b8 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2f3f2ce6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-01 10:28:45.712   821  1299 I ActivityManager: Start proc 3311:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
04-01 10:28:45.736   359  1804 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-01 10:28:45.737   359  1804 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-01 10:28:45.743   359  1014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
04-01 10:28:45.743   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 312us total 31.059ms
04-01 10:28:45.749  1519  1798 I HotwordRecognitionRnr: Stopping hotword detection.
04-01 10:28:45.749  1519  1800 I HotwordRecognitionRnr: Hotword detection finished
04-01 10:28:45.760   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 233us total 15.632ms
04-01 10:28:45.766   821  2133 I ActivityManager: Killing 2876:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
04-01 10:28:45.772   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 11.396ms
04-01 10:28:45.871   821  2133 I ActivityManager: Killing 2706:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,04-01 10:28:46.179  3311  3311 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,04-01 10:28:46.194  3311  3311 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2109-2111)
,04-01 10:28:46.195  3311  3311 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 10:28:46.213  3311  3311 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {363a9f4b}
04-01 10:28:46.213  3311  3311 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 10:28:46.214  3311  3311 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,04-01 10:28:46.223   821  1237 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1718568211
04-01 10:28:46.224   821  1237 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,04-01 10:28:46.229  3311  3311 I BrowserStartupController: Initializing chromium process, singleProcess=true
,04-01 10:28:46.230  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:46.231  3311  3311 E SysUtils: ApplicationContext is null in ApplicationStatus
,04-01 10:28:46.249  3311  3337 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,04-01 10:28:46.266  3311  3311 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,04-01 10:28:46.273  3311  3311 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
04-01 10:28:46.273  3311  3311 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 10:28:46.273  3311  3311 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,04-01 10:28:46.309   877   877 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,04-01 10:28:46.309   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,04-01 10:28:46.351   877   877 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,04-01 10:28:46.351   877   877 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,04-01 10:28:46.366   821   859 D BluetoothManagerService: Message: 20
04-01 10:28:46.366   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18af0801:true
,04-01 10:28:46.399  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:46.410  3311  3311 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 10:28:46.429  3311  3311 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,04-01 10:28:46.435  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
04-01 10:28:46.435  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:46.517  3311  3361 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 10:28:46.522  3311  3311 D Atlas   : Validating map...
,04-01 10:28:46.529   821   840 V WindowManager: Adding window Window{b08f371 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{38d632b8 u0 Starting com.test.thalitest})
,04-01 10:28:46.530  3311  3347 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,04-01 10:28:46.567  3311  3361 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 10:28:46.574  3311  3361 D OpenGLRenderer: Enabling debug mode 0
,04-01 10:28:46.634   821   860 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +968ms
,04-01 10:28:46.649  1219  1219 I Keyboard.Facilitator: onFinishInput()
,04-01 10:28:46.752  3311  3311 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3311
,04-01 10:28:46.863   821   862 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,04-01 10:28:46.884   821   862 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,04-01 10:28:46.927   259  1016 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (277 us)
,04-01 10:28:47.029  3311  3311 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 10:28:47.131  3311  3364 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580523264
,04-01 10:28:47.134  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 10:28:47.134  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 10:28:47.134  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 10:28:47.134  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 10:28:47.134  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 10:28:47.134  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5e8a5d added. We now have 1 listener(s)
,04-01 10:28:47.135   821  1228 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 10:28:47.138  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,04-01 10:28:47.138  3311  3364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,04-01 10:28:47.139  3311  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-01 10:28:47.139  3311  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 10:28:47.141  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e147a0 added. We now have 1 listener(s)
04-01 10:28:47.141  3311  3364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 10:28:47.145   821  1027 D WifiService: New client listening to asynchronous messages
,04-01 10:28:47.148  3311  3364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,04-01 10:28:47.149  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
04-01 10:28:47.149  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,04-01 10:28:47.149  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
04-01 10:28:47.149  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,04-01 10:28:47.151  3311  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-01 10:28:47.151   821  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 10:28:47.153  3311  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
04-01 10:28:47.157  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
04-01 10:28:47.157  3311  3364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 10:28:47.157  3311  3364 D io.jxcore.node.ConnectivityMonitor: start: OK
04-01 10:28:47.157  3311  3364 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-01 10:28:47.237  3311  3311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 10:28:47.238  3311  3311 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 10:28:47.341   877   877 I kickstart: STATUS: Received file 'm9kefs1'
,04-01 10:28:47.341   877   877 I kickstart: STATUS: 950272 bytes transferred in 0.990278 seconds
04-01 10:28:47.341   877   877 I kickstart: STATUS: Successfully downloaded files from target 
04-01 10:28:47.342   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,04-01 10:28:47.345   877   877 I kickstart: STATUS: Sahara protocol completed
,04-01 10:28:47.483   821   860 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-01 10:28:47.483   821   821 V ActivityManager: Display changed displayId=0
,04-01 10:28:47.489   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
04-01 10:28:47.490   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,04-01 10:28:47.757   259   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,04-01 10:28:47.759   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
04-01 10:28:47.760   821  1044 D SurfaceControl: Excessive delay in setPowerMode(): 276ms
,04-01 10:28:47.766   821   862 I DreamManagerService: Entering dreamland.
,04-01 10:28:47.767   821   862 I PowerManagerService: Dozing...
04-01 10:28:47.768   821   857 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,04-01 10:28:47.776   359  1194 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-01 10:28:47.776   359  1194 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,04-01 10:28:47.780   821  1025 E WifiStateMachine: cancelDelayedScan -> 16
,04-01 10:28:47.784   821  1025 E native  : do suspend false
,04-01 10:28:47.815  1219  1219 I Keyboard.Facilitator: onFinishInput()
,04-01 10:28:47.826   821  1025 E WifiStateMachine: cancelDelayedScan -> 18
,04-01 10:28:47.873  3311  3374 W jxcore-log: Initializing JXcore engine
04-01 10:28:47.873  3311  3374 W jxcore-log: JXcore engine is ready
,04-01 10:28:47.883   821  1025 E native  : do suspend true,
,04-01 10:28:47.895  3374  3374 W Thread-355: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10555]" dev="sockfs" ino=10555 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,04-01 10:28:47.895  3374  3374 W Thread-355: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
04-01 10:28:47.895  3374  3374 W Thread-355: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10699]" dev="sockfs" ino=10699 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
04-01 10:28:47.895  3374  3374 W Thread-355: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20960]" dev="sockfs" ino=20960 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,04-01 10:28:47.924  3311  3374 W jxcore-log: Starting JXcore engine
,04-01 10:28:47.943   359  1195 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-01 10:28:47.944   359  1195 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,04-01 10:28:47.990   821  1025 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,04-01 10:28:48.057  3311  3374 W jxcore-log: Platform android
04-01 10:28:48.057  3311  3374 W jxcore-log: 
04-01 10:28:48.057  3311  3374 W jxcore-log: Process ARCH arm
04-01 10:28:48.057  3311  3374 W jxcore-log: 
,04-01 10:28:48.296  3311  3374 I jxcore-log: JXcore Cordova bridge is ready!
04-01 10:28:48.296  3311  3374 I jxcore-log: 
04-01 10:28:48.297  3311  3374 W jxcore-log: JXcore engine is started
,04-01 10:28:48.309  3311  3364 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 10:28:48.314  3311  3311 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 10:28:48.416   821  1025 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,04-01 10:28:50.343  1173  1173 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,04-01 10:28:50.767  1173  1173 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,04-01 10:28:50.798  1173  1173 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
04-01 10:28:50.799  1173  1173 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,04-01 10:28:50.807   821  1025 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
04-01 10:28:50.807   821  1025 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,04-01 10:28:50.807   821  1028 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,04-01 10:28:50.811   821  1025 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,04-01 10:28:50.815   355   815 D CommandListener: Setting iface cfg
04-01 10:28:50.818   821  1025 E WifiStateMachine: Start Dhcp Watchdog 1
04-01 10:28:50.820   821  1025 E WifiStateMachine:  WifiLinkLayerStats: 
04-01 10:28:50.820   821  1025 E WifiStateMachine:  my bss beacon rx: 1
04-01 10:28:50.820   821  1025 E WifiStateMachine:  RSSI mgmt: -42
04-01 10:28:50.820   821  1025 E WifiStateMachine:  BE :  rx=0 tx=2 lost=0 retries=1
04-01 10:28:50.820   821  1025 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
04-01 10:28:50.820   821  1025 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
04-01 10:28:50.820   821  1025 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
04-01 10:28:50.820   821  1025 E WifiStateMachine:  on_time : 0 tx_time=61 rx_time=84 scan_time=0
,04-01 10:28:50.909   821  1025 E native  : do suspend false
,04-01 10:28:50.916   821  1025 E WifiStateMachine: scanCount==0 - aborting
,04-01 10:28:51.150  3382  3382 I dhcpcd  : version 5.5.6 starting
,04-01 10:28:51.242  3382  3382 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,04-01 10:28:51.356  3382  3382 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,04-01 10:28:51.404  3382  3382 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,04-01 10:28:51.732   821  1025 E native  : do suspend true
,04-01 10:28:51.775   821  1028 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
04-01 10:28:51.778   821  1028 D ConnectivityService: Adding iface wlan0 to network 100
04-01 10:28:51.782   821  1025 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,04-01 10:28:51.815   821  1028 E ConnectivityService: Unexpected mtu value: 0, wlan0
04-01 10:28:51.816   821  1028 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,04-01 10:28:51.817   821  1028 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,04-01 10:28:51.818   821  1028 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100,
,04-01 10:28:51.820   821  1028 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,04-01 10:28:51.828   821  1028 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,04-01 10:28:51.834   821  1028 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
04-01 10:28:51.835   821  3380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
04-01 10:28:51.835   821  3380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
04-01 10:28:51.835   821  3380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
04-01 10:28:51.836   821  3380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
04-01 10:28:51.836   821  1028 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
04-01 10:28:51.836   821  1028 D ConnectivityService:    accepting network in place of null
,04-01 10:28:51.837   821  1028 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,04-01 10:28:51.839   821  1028 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,04-01 10:28:51.843   821  1028 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
04-01 10:28:51.844   821  1028 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
04-01 10:28:51.844   821  1028 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
04-01 10:28:51.844   821  1028 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
04-01 10:28:51.845  1066  1554 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-01 10:28:51.848   821   859 D Tethering: MasterInitialState.processMessage what=3
,04-01 10:28:51.857   821  1454 V BackupManagerService: Scheduling immediate backup pass
,04-01 10:28:51.861  2930  2930 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,04-01 10:28:51.862   821   821 V BackupManagerService: Running a backup pass
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 10:28:51.862  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 10:28:51.862  3311  3311 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,04-01 10:28:51.863   821  1043 V BackupManagerService: clearing pending backups
04-01 10:28:51.864  1277  1294 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
04-01 10:28:51.865  1277  1294 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,04-01 10:28:51.867  1519  1519 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,04-01 10:28:51.874   821   854 D TelephonyManager: getDataEnabled: retVal=false
,04-01 10:28:51.877   821  1043 V PerformBackupTask: Beginning backup of 14 targets
,04-01 10:28:51.880  2930  2930 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
04-01 10:28:51.881   821  1043 D PerformBackupTask: invokeAgentForBackup on @pm@
,04-01 10:28:51.883   821   854 E GpsLocationProvider: No APN found to select.
,04-01 10:28:51.885   821  1043 V BackupServiceBinder: doBackup() invoked
,04-01 10:28:51.887   821  1043 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,04-01 10:28:51.905   821  1043 I BackupRestoreController: Getting widget state for user: 0
,04-01 10:28:51.927   821   839 I ActivityManager: Start proc 3422:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,04-01 10:28:51.987  1846  1900 W GmsBackupTransport: Unknown package in backup request: @pm@
04-01 10:28:51.988  1846  1900 V GmsBackupTransport: starting performBackup for @pm@
,04-01 10:28:51.999  1846  1900 V GmsBackupTransport: performBackup done for @pm@
,04-01 10:28:52.007  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:52.029  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
04-01 10:28:52.029  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:52.029  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:52.029  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:52.032  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:52.055   821  1245 D AlarmManagerService: Setting time of day to sec=1459499331
04-01 10:28:51.627   821  1245 W AlarmManagerService: Unable to set rtc to 1459499331: Invalid argument
,04-01 10:28:51.630   821  3441 D GpsLocationProvider: NTP server returned: 1459499331628 (Fri Apr 01 10:28:51 GMT+02:00 2016) reference: 167976 certainty: 42 system time offset: -2
,04-01 10:28:51.638   821  3380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Apr 2016 08:28:51 GMT], X-Android-Received-Millis=[1459499331638], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459499331991]}
,04-01 10:28:51.639   821  3380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
,04-01 10:28:51.639   821  1028 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
04-01 10:28:51.639   821  1028 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
04-01 10:28:51.639   821  1028 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
04-01 10:28:51.639   821  1028 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
04-01 10:28:51.639   821  1028 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
04-01 10:28:51.640  1066  1554 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
04-01 10:28:51.640   821  1028 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,04-01 10:28:51.647  1492  1510 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:28:51.647  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:28:51.647  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:28:51.647  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
04-01 10:28:51.647  1492  1510 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
04-01 10:28:51.647  1492  1510 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
04-01 10:28:51.647  1492  1510 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,04-01 10:28:51.653  1846  1861 W GmsBackupTransport: Error sending final backup to server: 
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
04-01 10:28:51.653  1846  1861 W GmsBackupTransport: 	... 1 more
,04-01 10:28:51.653   821  1043 D BackupManagerService: Now staging backup of com.google.android.talk
,04-01 10:28:51.674   821  1043 D BackupManagerService: Now staging backup of com.google.android.dialer
,04-01 10:28:51.687   821  1043 D BackupManagerService: Now staging backup of com.android.providers.settings
,04-01 10:28:51.691   821  1043 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,04-01 10:28:51.692   821  1096 I ActivityManager: Start proc 3457:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,04-01 10:28:51.696   821  1043 D BackupManagerService: Now staging backup of com.google.android.gm
,04-01 10:28:51.700   821  1043 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,04-01 10:28:51.703   821  1043 D BackupManagerService: Now staging backup of com.android.nfc
,04-01 10:28:51.706   821  1043 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,04-01 10:28:51.710   821  1043 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,04-01 10:28:51.716   821  1043 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,04-01 10:28:51.721   821  1043 D BackupManagerService: Now staging backup of com.google.android.calendar
,04-01 10:28:51.728   821  1043 D BackupManagerService: Now staging backup of com.android.vending
,04-01 10:28:51.729  3457  3457 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,04-01 10:28:51.732   821  1043 D BackupManagerService: Now staging backup of android
,04-01 10:28:51.733   821  1043 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,04-01 10:28:51.737  1846  1900 I GmsBackupTransport: Next backup will happen in 43199914 millis.
,04-01 10:28:51.739   821  1043 I BackupManagerService: Backup pass finished.
,04-01 10:28:51.752  3457  3457 D SprintDMHelper: simOperator:  IMSI: null
04-01 10:28:51.752  3457  3457 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,04-01 10:28:51.761  1806  3477 W DriveInitializer: Background init thread started
,04-01 10:28:51.763  1806  1806 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,04-01 10:28:51.779  1806  3478 W DriveInitializer: Awaiting to be initialized
,04-01 10:28:51.834  1492  1679 I art     : Explicit concurrent mark sweep GC freed 22687(1174KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.329ms total 23.424ms
,04-01 10:28:51.834   821   839 I art     : Explicit concurrent mark sweep GC freed 55811(2MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 2.368ms total 57.777ms
,04-01 10:28:51.878   821   854 I ActivityManager: Start proc 3488:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,04-01 10:28:51.899  1806  3477 W DriveInitializer: Background init thread ended
,04-01 10:28:51.925  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
04-01 10:28:51.925  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:51.925  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:51.925  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:51.929  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:51.942  3106  3475 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 10:28:51.942  3106  3475 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at blb.a(PG:3937)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at czp.a(PG:18188)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:28:51.942  3106  3475 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	... 12 more
04-01 10:28:51.942  3106  3475 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at fal.a(PG:38)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:28:51.942  3106  3475 E HttpOperation: 	... 14 more
,04-01 10:28:51.974  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:28:51.974  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:51.974  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth,
04-01 10:28:51.974  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:51.977  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:51.979  1806  1806 D SystemUpdateService: onCreate
,04-01 10:28:51.990  3106  3475 E HttpOperation: [getmobileexperiments] Unexpected exception
04-01 10:28:51.990  3106  3475 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at hec.a(PG:42)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at hee.a(PG:102)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at czr.a(PG:65)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at kka.a(PG:108)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at czp.a(PG:19176)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:28:51.990  3106  3475 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	... 15 more
04-01 10:28:51.990  3106  3475 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at fal.a(PG:38)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:28:51.990  3106  3475 E HttpOperation: 	... 17 more
,04-01 10:28:51.991  3106  3475 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 10:28:51.991  3106  3475 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at hec.a(PG:42)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at hee.a(PG:102)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at czr.a(PG:65)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at kka.a(PG:108)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jdj.a(PG:1125)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	... 15 more
04-01 10:28:51.991  3106  3475 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at fal.a(PG:38)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 10:28:51.991  3106  3475 E ExperimentLoader: 	... 17 more
04-01 10:28:51.993  1806  1806 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
04-01 10:28:51.999  1806  3511 I SystemUpdateService: active receiver: enabled
04-01 10:28:52.005  1806  3511 I SystemUpdateService: Already downloaded, skipping offpeak checks.
04-01 10:28:52.009  1806  3511 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
04-01 10:28:52.009  1806  3511 I SystemUpdateService: now status is 0 (complete)
04-01 10:28:52.009  1806  3511 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
04-01 10:28:52.009  1806  3511 I SystemUpdateService: file has been verified
04-01 10:28:52.009  1806  3511 I SystemUpdateService: OTA package size = 25802302
,04-01 10:28:52.030  1806  3511 I SystemUpdateService: showing system update notification
04-01 10:28:52.067   821   821 I ValidateNoPeople: skipping global notification
,04-01 10:28:52.073  1806  3520 I iu.SyncManager: SYNC; picasa accounts
,04-01 10:28:52.096   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38540, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
04-01 10:28:52.097   821  1404 I ActivityManager: Killing 2909:com.android.settings/1000 (adj 15): empty #17
,04-01 10:28:52.118  1806  1806 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,04-01 10:28:52.120  1806  1806 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,04-01 10:28:52.122  1806  3520 I iu.UploadsManager: num queued entries: 0
,04-01 10:28:52.123  1806  3520 I iu.UploadsManager: num updated entries: 0
,04-01 10:28:52.123  1806  3520 I iu.SyncManager: NEXT; no task
,04-01 10:28:52.131  3488  3522 V KeepSync: Connecting to GoogleApiClient
,04-01 10:28:52.151  1806  1806 D SystemUpdateService: onDestroy
,04-01 10:28:52.174  1806  1806 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
04-01 10:28:52.175  1806  1806 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,04-01 10:28:52.188   821   854 I ActivityManager: Start proc 3526:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,04-01 10:28:52.221   821  1358 I ActivityManager: Start proc 3546:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,04-01 10:28:52.234  1806  3524 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 10:28:52.242  1806  3524 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 10:28:52.262  1492  1678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,04-01 10:28:52.262  1492  1678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:52.262  1492  1678 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:52.262  1492  1678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:52.265  1492  1678 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: Handling authorization failure
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 10:28:52.277  1806  3524 E ClientConnectionOperation: 	... 7 more
,04-01 10:28:52.280  3488  3522 V KeepSync: GoogleApiClient failed to connect with error code: 4
04-01 10:28:52.281  3488  3522 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:28:52.288  3488  3522 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
04-01 10:28:52.288  3488  3522 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:28:52.356  3546  3546 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
04-01 10:28:52.356  3546  3546 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 10:28:52.356  3546  3546 I GAv4    :   adb logcat -s GAv4
,04-01 10:28:52.360  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
04-01 10:28:52.360  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:52.360  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:28:52.360  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:52.364  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:52.376  3546  3546 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,04-01 10:28:52.388  3546  3546 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,04-01 10:28:52.393  3546  3572 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,04-01 10:28:52.401  3488  3522 E KeepSync: IOException
04-01 10:28:52.401  3488  3522 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 10:28:52.401  3488  3522 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 10:28:52.401  3488  3522 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 10:28:52.401  3488  3522 E KeepSync: 	... 10 more
04-01 10:28:52.401  3488  3522 W KeepSync: Sync result 2
,04-01 10:28:52.411   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38548, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:28:52.466  3162  3539 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,04-01 10:28:52.468   821  1403 I ActivityManager: Killing 2444:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,04-01 10:28:52.538  1492  3565 D GCM     : Connected
,04-01 10:28:52.589  1492  3565 D GCM     : Message class com.google.f.a.a.p
,04-01 10:28:52.607  3546  3546 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,04-01 10:28:52.622  3546  3546 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8966-8967)
04-01 10:28:52.622  3546  3546 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 10:28:52.627  3546  3546 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {346f23ce}
04-01 10:28:52.627  1492  1678 I art     : Explicit concurrent mark sweep GC freed 15255(885KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 797us total 20.383ms
04-01 10:28:52.627  3546  3546 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 10:28:52.628  3546  3546 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,04-01 10:28:52.645  3546  3546 I BrowserStartupController: Initializing chromium process, singleProcess=true
,04-01 10:28:52.646  3546  3546 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 10:28:52.647  3546  3546 E SysUtils: ApplicationContext is null in ApplicationStatus
,04-01 10:28:52.664  3546  3546 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,04-01 10:28:52.669  3546  3546 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 10:28:52.669  3546  3546 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 10:28:52.669  3546  3546 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,04-01 10:28:52.676  3526  3526 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,04-01 10:28:52.683  3526  3526 I BooksApp: Created application version: 3.6.8 (30608)
,04-01 10:28:52.769  3546  3606 W AudioManagerAndroid: Requires BLUETOOTH permission
04-01 10:28:52.769  3546  3546 I NSApplication: Starting up...
,04-01 10:28:52.771  3526  3607 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 10:28:52.793   821  1454 I ActivityManager: Start proc 3614:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,04-01 10:28:52.794   821  1454 I ActivityManager: Killing 3014:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,04-01 10:28:53.130  3526  3634 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,04-01 10:28:53.196  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
04-01 10:28:53.196  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:53.196  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:53.196  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:53.199  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:53.248  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:28:53.248  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:53.248  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:53.248  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:53.251  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:53.259  3526  3634 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,04-01 10:28:53.260  3526  3607 E BooksSync: Soft error
04-01 10:28:53.260  3526  3607 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:28:53.260  3526  3607 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:28:53.260  3526  3607 E BooksSync: Sync error
04-01 10:28:53.260  3526  3607 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:28:53.260  3526  3607 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:28:53.260  3526  3607 I BooksSync: Finished books sync
,04-01 10:28:53.264   821  1403 I ActivityManager: Killing 3062:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,04-01 10:28:53.265   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38548, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:28:53.368   821  1403 I ActivityManager: Killing 3034:com.android.musicfx/u0a18 (adj 15): empty #18
,04-01 10:28:53.643   821  1299 I ActivityManager: Start proc 3639:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,04-01 10:28:53.644   821  1299 I ActivityManager: Killing 2994:android.process.acore/u0a5 (adj 15): empty #17
,04-01 10:28:53.820   821  1358 I art     : Explicit concurrent mark sweep GC freed 28123(1290KB) AllocSpace objects, 5(122KB) LOS objects, 32% free, 33MB/49MB, paused 1.490ms total 53.285ms
,04-01 10:28:54.558   821  1298 I ActivityManager: Killing 2810:com.google.android.gm/u0a78 (adj 15): empty #17
,04-01 10:28:54.765   821  1298 E libprocessgroup: failed to kill 1 processes for processgroup 2810
,04-01 10:28:54.844   821  1096 I ActivityManager: Start proc 3658:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,04-01 10:28:54.951  3658  3658 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459499334951
,04-01 10:28:54.951  3658  3658 D         : TimeServiceNative: User Time to be set is 1459499334951
04-01 10:28:54.951  3658  3658 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
04-01 10:28:54.951  3658  3658 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
,04-01 10:28:54.951  3658  3658 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459499334951
04-01 10:28:54.952   374   880 D QC-time-services: Daemon: Connection accepted:time_genoff
04-01 10:28:54.952  3658  3658 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459499334951
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459499334951, operation = 0
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/18/70 4:40:33
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:Value read from RTC seconds = 19802433000
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:new time 1459499334951 
,04-01 10:28:54.952   374  3675 D QC-time-services: Daemon: delta 1439696901951 genoff 1439696901951 
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901951 to memory
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:Opening File: /data/time/ats_2
04-01 10:28:54.952   374  3675 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
04-01 10:28:54.955   374  3675 D QC-time-services: Updating the TOD offset,
04-01 10:28:54.955   374  3675 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901951 to memory
04-01 10:28:54.955   374  3675 D QC-time-services: Daemon:Opening File: /data/time/ats_1
04-01 10:28:54.955   374  3675 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 10:28:54.957   374  3675 E QC-time-services: Daemon:Update to modem bit set
04-01 10:28:54.957   374  3675 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
04-01 10:28:54.957   374  3675 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143534534951
04-01 10:28:54.957  3658  3658 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,04-01 10:28:55.025   374   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,04-01 10:28:55.032   374   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,04-01 10:28:55.089   821  1228 I ActivityManager: Start proc 3677:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,04-01 10:28:55.100   821  1299 I ActivityManager: Killing 3194:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,04-01 10:28:55.386  3677  3677 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
04-01 10:28:55.386  3677  3677 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 10:28:55.386  3677  3677 I GAv4    :   adb logcat -s GAv4
,04-01 10:28:55.406  3677  3677 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,04-01 10:28:55.416  3677  3677 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,04-01 10:28:55.427  3677  3696 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,04-01 10:28:55.534  1806  1806 V Herrevad: NQAS connected
,04-01 10:28:55.554   821  1027 D WifiService: New client listening to asynchronous messages
,04-01 10:28:55.558  3162  3162 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,04-01 10:28:55.560  3162  3162 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 10:28:55.619  1806  1833 I art     : Explicit concurrent mark sweep GC freed 14733(1089KB) AllocSpace objects, 13(208KB) LOS objects, 35% free, 28MB/44MB, paused 1.177ms total 33.427ms
,04-01 10:28:55.682  1492  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,04-01 10:28:55.682  1492  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:55.682  1492  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:55.682  1492  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:55.686  1492  2320 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:55.697  3162  3705 E Babel   : UserRecoverableAuthException.
,04-01 10:28:55.698  3162  3705 E Babel   : eei: BadAuthentication
04-01 10:28:55.698  3162  3705 E Babel   : 	at eeg.a(Unknown Source)
04-01 10:28:55.698  3162  3705 E Babel   : 	at eeg.a(Unknown Source)
04-01 10:28:55.698  3162  3705 E Babel   : 	at eeg.a(Unknown Source)
04-01 10:28:55.698  3162  3705 E Babel   : 	at g.a(Unknown Source)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cae.a(SourceFile:3089)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cae.a(SourceFile:1131)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cws.a(SourceFile:4333)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cws.a(SourceFile:1419)
04-01 10:28:55.698  3162  3705 E Babel   : 	at crl.a(SourceFile:492)
04-01 10:28:55.698  3162  3705 E Babel   : 	at crl.a(SourceFile:1468)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cqu.a(SourceFile:4416)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cas.b(SourceFile:106)
04-01 10:28:55.698  3162  3705 E Babel   : 	at cap.d(SourceFile:335)
04-01 10:28:55.698  3162  3705 E Babel   : 	at caq.run(SourceFile:81)
,04-01 10:28:55.698  3162  3705 E Babel   : Error getting auth token
,04-01 10:28:55.699  3162  3705 E Babel   : dvm
04-01 10:28:55.699  3162  3705 E Babel   : 	at g.a(Unknown Source)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cae.a(SourceFile:3089)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cae.a(SourceFile:1131)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cws.a(SourceFile:4333)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cws.a(SourceFile:1419)
04-01 10:28:55.699  3162  3705 E Babel   : 	at crl.a(SourceFile:492)
04-01 10:28:55.699  3162  3705 E Babel   : 	at crl.a(SourceFile:1468)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cqu.a(SourceFile:4416)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cas.b(SourceFile:106)
04-01 10:28:55.699  3162  3705 E Babel   : 	at cap.d(SourceFile:335)
04-01 10:28:55.699  3162  3705 E Babel   : 	at caq.run(SourceFile:81)
,04-01 10:28:55.702  3162  3705 E Babel   : Account registration failed 1-Redacted-21
,04-01 10:28:55.702  3162  3705 E Babel   : cyp: null -- null
04-01 10:28:55.702  3162  3705 E Babel   : 	at cae.a(SourceFile:3121)
04-01 10:28:55.702  3162  3705 E Babel   : 	at cae.a(SourceFile:1131)
04-01 10:28:55.702  3162  3705 E Babel   : 	at cws.a(SourceFile:4333)
04-01 10:28:55.702  3162  3705 E Babel   : 	at cws.a(SourceFile:1419)
04-01 10:28:55.702  3162  3705 E Babel   : 	at crl.a(SourceFile:492)
04-01 10:28:55.702  3162  3705 E Babel   : 	at crl.a(SourceFile:1468)
04-01 10:28:55.702  3162  3705 E Babel   : 	at cqu.a(SourceFile:4416)
04-01 10:28:55.702  3162  3705 E Babel   : 	at cas.b(SourceFile:106)
04-01 10:28:55.702  3162  3705 E Babel   : 	at cap.d(SourceFile:335)
04-01 10:28:55.702  3162  3705 E Babel   : 	at caq.run(SourceFile:81)
,04-01 10:28:55.710  3162  3705 I art     : Note: end time exceeds epoch: 
,04-01 10:28:55.725  1492  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
04-01 10:28:55.725  1492  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:28:55.725  1492  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:28:55.725  1492  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:55.727  1492  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:55.742  1492  2558 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,04-01 10:28:55.754  3162  3712 E Babel   : Unexpected exception while authenticating.
,04-01 10:28:55.755  3162  3712 E Babel   : eej: User intervention required. Notification has been pushed.
04-01 10:28:55.755  3162  3712 E Babel   : 	at eeg.b(Unknown Source)
04-01 10:28:55.755  3162  3712 E Babel   : 	at eeg.b(Unknown Source)
04-01 10:28:55.755  3162  3712 E Babel   : 	at g.a(Unknown Source)
04-01 10:28:55.755  3162  3712 E Babel   : 	at cae.b(SourceFile:1146)
04-01 10:28:55.755  3162  3712 E Babel   : 	at dcg.run(SourceFile:5617)
04-01 10:28:55.755  3162  3712 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:28:55.755  3162  3712 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:28:55.755  3162  3712 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,04-01 10:28:57.697  3526  3597 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,04-01 10:28:58.084  3311  3374 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 10:28:58.084  3311  3374 I jxcore-log: 
,04-01 10:28:58.086  3311  3374 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 10:28:58.086  3311  3374 I jxcore-log: 
,04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 10:28:58.093  3311  3374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 10:28:58.096  3311  3374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-01 10:28:58.098  3311  3374 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 10:28:58.098  3311  3374 I jxcore-log: 
,04-01 10:28:58.100  3311  3374 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 10:28:58.100  3311  3374 I jxcore-log: 
,04-01 10:28:58.613  3311  3374 I jxcore-log: Unit Test app is loaded
04-01 10:28:58.613  3311  3374 I jxcore-log: 
,04-01 10:28:58.619  3311  3374 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 10:28:58.619  3311  3374 I jxcore-log: 
,04-01 10:28:58.623  3311  3374 I jxcore-log: My device name is: motorola-Nexus 6
04-01 10:28:58.623  3311  3374 I jxcore-log: 
,04-01 10:28:58.625  3311  3374 I jxcore-log: WARN testUtils: myNameCallback not set!
04-01 10:28:58.625  3311  3374 I jxcore-log: 
,04-01 10:28:58.638  3311  3311 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 10:28:59.114  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:59.240  1492  3722 I VacuumService: Vacuum at: now=1459499339240 tag=VacuumService
,04-01 10:28:59.266  3422  3721 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 10:28:59.383  1492  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,04-01 10:28:59.383  1492  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:28:59.383  1492  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:28:59.384  1492  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:28:59.395  1492  2320 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:59.430  3422  3721 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
04-01 10:28:59.433  3422  3721 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 10:28:59.604  1492  3723 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-01 10:28:59.637  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:00.161  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:00.314  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:00.485  1492  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
04-01 10:29:00.485  1492  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:00.486  1492  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:00.486  1492  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:00.492  1492  3723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:00.555  1492  1492 I art     : Explicit concurrent mark sweep GC freed 34805(2018KB) AllocSpace objects, 4(369KB) LOS objects, 37% free, 26MB/42MB, paused 1.428ms total 53.562ms
,04-01 10:29:00.623  1492  3723 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:29:00.623  1492  3723 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 10:29:00.623  1492  3723 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 10:29:00.758   821   840 I ActivityManager: Killing 2747:com.android.vending/u0a19 (adj 15): empty #17
,04-01 10:29:00.993  1492  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,04-01 10:29:00.993  1492  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:00.993  1492  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:00.993  1492  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:00.996  1492  3723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:01.035  1492  3723 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:29:01.035  1492  3723 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 10:29:01.035  1492  3723 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 10:29:01.166  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:01.294  1492  3723 W Uploader: No account for auth token provided,
,04-01 10:29:01.447  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:01.624  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:01.740  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:01.865  1492  3723 W Uploader:  no longer exists, so no auth token.
,04-01 10:29:02.038  1492  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
04-01 10:29:02.038  1492  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:02.038  1492  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:02.038  1492  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:02.046  1492  3723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:02.105  1492  3723 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:29:02.105  1492  3723 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 10:29:02.105  1492  3723 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 10:29:02.211  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:02.378  1492  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
04-01 10:29:02.378  1492  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:02.378  1492  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:02.378  1492  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:02.383  1492  3723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:02.454   821  1403 I art     : Explicit concurrent mark sweep GC freed 19613(922KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.290ms total 65.044ms
,04-01 10:29:02.496  1492  3723 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:29:02.496  1492  3723 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 10:29:02.496  1492  3723 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 10:29:02.587  1492  3723 W Uploader: No account for auth token provided
,04-01 10:29:02.732  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 10:29:02.732  3311  3374 I jxcore-log: 
,04-01 10:29:02.782   821  1298 I ActivityManager: Start proc 3727:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,04-01 10:29:02.807  1492  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
04-01 10:29:02.807  1492  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:02.807  1492  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:02.807  1492  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:02.811  1492  3723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:02.839  1492  3723 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:29:02.839  1492  3723 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
04-01 10:29:02.839  1492  3723 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,04-01 10:29:02.896  3727  3727 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,04-01 10:29:02.982  3727  3727 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,04-01 10:29:03.046   821  1454 I ActivityManager: Start proc 3764:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,04-01 10:29:03.069   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 248us total 24.142ms
,04-01 10:29:03.080  3727  3727 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,04-01 10:29:03.087  3727  3727 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,04-01 10:29:03.087   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 346us total 16.665ms
,04-01 10:29:03.099  3764  3764 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 10:29:03.099  3764  3764 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 10:29:03.103   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 335us total 13.193ms
,04-01 10:29:03.120  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 10:29:03.120  3311  3374 I jxcore-log: ,
,04-01 10:29:03.124  3764  3764 I MultiDex: VM with version 2.1.0 has multidex support
04-01 10:29:03.124  3764  3764 I MultiDex: install
04-01 10:29:03.124  3764  3764 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 10:29:03.132  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 10:29:03.132  3311  3374 I jxcore-log: 
,04-01 10:29:03.136  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 10:29:03.136  3311  3374 I jxcore-log: 
,04-01 10:29:03.145   821  1358 I ActivityManager: Killing 2930:com.google.android.music:main/u0a66 (adj 15): empty #17
,04-01 10:29:03.146  3764  3764 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
04-01 10:29:03.147  3727  3742 D Finsky  : [379] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
04-01 10:29:03.154  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 10:29:03.154  3311  3374 I jxcore-log: 
,04-01 10:29:03.166  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 10:29:03.166  3311  3374 I jxcore-log: 
,04-01 10:29:03.176  3764  3764 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL,
,04-01 10:29:03.257  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:03.258  3727  3727 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 10:29:03.258  3727  3727 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,04-01 10:29:03.264  3727  3727 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,04-01 10:29:03.264  1492  2116 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,04-01 10:29:03.277  1492  1492 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 10:29:03.287  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 10:29:03.288  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:03.288  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:03.288  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
04-01 10:29:03.288  3727  3727 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,04-01 10:29:03.291  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:03.293  1806  1806 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,04-01 10:29:03.308  3727  3742 D Finsky  : [379] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,04-01 10:29:03.334   821  1299 I ActivityManager: Start proc 3791:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,04-01 10:29:03.351  1806  3804 D LocationInitializer: Restart initialization of location
,04-01 10:29:03.380  3791  3791 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 10:29:03.380  3791  3791 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 10:29:03.419  3791  3791 I MultiDex: VM with version 2.1.0 has multidex support
,04-01 10:29:03.419  3791  3791 I MultiDex: install
04-01 10:29:03.419  3791  3791 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 10:29:03.435  3791  3791 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,04-01 10:29:03.467  3791  3791 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 10:29:03.472  1492  2531 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,04-01 10:29:03.475  1492  1492 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 10:29:03.479  1806  1806 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: Install did not work
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
04-01 10:29:03.482  3791  3813 W NativeLibraryUtils: 	... 4 more
,04-01 10:29:03.484  3791  3791 D WearableService: callingUid 10011, callindPid: 3791
,04-01 10:29:03.496  1806  3814 D LocationInitializer: Restart initialization of location
,04-01 10:29:03.504  1846  2109 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,04-01 10:29:03.508  1846  2109 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,04-01 10:29:03.605  3727  3727 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,04-01 10:29:03.998  3727  3727 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,04-01 10:29:04.038  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.099  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 10:29:04.099  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:04.099  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:04.099  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:04.105  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.125  3727  3727 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,04-01 10:29:04.132  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.156  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,04-01 10:29:04.156  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:04.156  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:04.156  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:04.165  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.204  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.239  1492  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 10:29:04.239  1492  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:04.239  1492  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:04.239  1492  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:04.245  1492  2320 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.268  3727  3727 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,04-01 10:29:04.549  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:04.619  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 10:29:04.620  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:04.620  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:04.620  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:04.630  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:29:04.664  3727  3727 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,04-01 10:29:04.670  3727  3727 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,04-01 10:29:04.688  3727  3727 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 10:29:04.694  3727  3727 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 85 minutes (failures=3)
,04-01 10:29:04.718  1846  1897 D DeviceConnectionService: client connected with version: 7571000,
,04-01 10:29:05.334  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 10:29:05.334  3311  3374 I jxcore-log: 
,04-01 10:29:05.357  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 10:29:05.357  3311  3374 I jxcore-log: 
,04-01 10:29:05.365  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 10:29:05.365  3311  3374 I jxcore-log: 
,04-01 10:29:05.518  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 10:29:05.518  3311  3374 I jxcore-log: 
,04-01 10:29:05.616  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 10:29:05.616  3311  3374 I jxcore-log: 
,04-01 10:29:05.670  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 10:29:05.670  3311  3374 I jxcore-log: 
,04-01 10:29:05.677  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-01 10:29:05.677  3311  3374 I jxcore-log: 
,04-01 10:29:05.811  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 10:29:05.811  3311  3374 I jxcore-log: 
,04-01 10:29:05.832  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 10:29:05.832  3311  3374 I jxcore-log: 
,04-01 10:29:05.837  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 10:29:05.837  3311  3374 I jxcore-log: 
,04-01 10:29:05.843  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 10:29:05.843  3311  3374 I jxcore-log: 
,04-01 10:29:05.859  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 10:29:05.859  3311  3374 I jxcore-log: 
,04-01 10:29:05.879  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 10:29:05.879  3311  3374 I jxcore-log: 
,04-01 10:29:05.962  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 10:29:05.962  3311  3374 I jxcore-log: ,
,04-01 10:29:05.968  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 10:29:05.968  3311  3374 I jxcore-log: 
,04-01 10:29:05.994  3311  3374 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 10:29:05.994  3311  3374 I jxcore-log: 
,04-01 10:29:06.007  3311  3374 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,04-01 10:29:06.008  3311  3374 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
04-01 10:29:06.008  3311  3374 I jxcore-log: 
,04-01 10:29:07.300  3311  3374 I jxcore-log: TAP version 13
04-01 10:29:07.300  3311  3374 I jxcore-log: 
,04-01 10:29:07.303  3311  3374 I jxcore-log: # setup
04-01 10:29:07.303  3311  3374 I jxcore-log: 
,04-01 10:29:07.845  3311  3374 I jxcore-log: # 1. calling createNativeListener directly rejects
04-01 10:29:07.845  3311  3374 I jxcore-log: 
,04-01 10:29:08.449  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:08.449  3311  3374 I jxcore-log: 
,04-01 10:29:08.455  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 54993
,04-01 10:29:08.455  3311  3374 I jxcore-log: 
,04-01 10:29:08.462  3311  3374 I jxcore-log: ok 1 Should throw
,04-01 10:29:08.462  3311  3374 I jxcore-log: 
,04-01 10:29:08.466  3311  3374 I jxcore-log: # teardown
,04-01 10:29:08.466  3311  3374 I jxcore-log: 
,04-01 10:29:08.518   821   839 I ActivityManager: Killing 3457:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,04-01 10:29:08.551  3311  3374 I jxcore-log: # setup
04-01 10:29:08.551  3311  3374 I jxcore-log: 
,04-01 10:29:08.633   821   839 I ActivityManager: Killing 3546:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,04-01 10:29:09.055  3311  3374 I jxcore-log: # 2. emits incomingConnectionState
04-01 10:29:09.055  3311  3374 I jxcore-log: 
,04-01 10:29:09.317  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:09.317  3311  3374 I jxcore-log: 
04-01 10:29:09.322  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 60413
04-01 10:29:09.322  3311  3374 I jxcore-log: 
,04-01 10:29:09.332  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:09.332  3311  3374 I jxcore-log: 
,04-01 10:29:09.336  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:09.336  3311  3374 I jxcore-log: 
,04-01 10:29:09.349  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:09.349  3311  3374 I jxcore-log: 
,04-01 10:29:09.365  3311  3374 I jxcore-log: ok 2 initial connection state should be CONNECTED
04-01 10:29:09.365  3311  3374 I jxcore-log: 
,04-01 10:29:09.383  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:09.383  3311  3374 I jxcore-log: 
,04-01 10:29:09.384  3311  3374 I jxcore-log: ok 3 final connection state should be DISCONNECTED
04-01 10:29:09.384  3311  3374 I jxcore-log: 
,04-01 10:29:09.392  3311  3374 I jxcore-log: # teardown
04-01 10:29:09.392  3311  3374 I jxcore-log: 
,04-01 10:29:09.980  3311  3374 I jxcore-log: # setup
04-01 10:29:09.980  3311  3374 I jxcore-log: 
,04-01 10:29:10.100  3311  3374 I jxcore-log: # 3. emits routerPortConnectionFailed
04-01 10:29:10.100  3311  3374 I jxcore-log: 
,04-01 10:29:10.248  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:10.248  3311  3374 I jxcore-log: 
,04-01 10:29:10.252  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 59749
04-01 10:29:10.252  3311  3374 I jxcore-log: 
,04-01 10:29:10.259  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:10.259  3311  3374 I jxcore-log: 
,04-01 10:29:10.260  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:10.260  3311  3374 I jxcore-log: 
,04-01 10:29:10.262  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:10.262  3311  3374 I jxcore-log: 
,04-01 10:29:10.302  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:10.302  3311  3374 I jxcore-log: 
,04-01 10:29:10.310  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:10.310  3311  3374 I jxcore-log: 
,04-01 10:29:10.318  3311  3374 I jxcore-log: DEBUG createNativeListener: 
04-01 10:29:10.318  3311  3374 I jxcore-log: 
,04-01 10:29:10.320  3311  3374 I jxcore-log: ok 4 tried to connect to right port
04-01 10:29:10.320  3311  3374 I jxcore-log: 
,04-01 10:29:10.320  3311  3374 I jxcore-log: ok 5 failed due to refused connection
04-01 10:29:10.320  3311  3374 I jxcore-log: 
,04-01 10:29:10.321  3311  3374 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
04-01 10:29:10.321  3311  3374 I jxcore-log: 
,04-01 10:29:10.327  3311  3374 I jxcore-log: # teardown
04-01 10:29:10.327  3311  3374 I jxcore-log: 
,04-01 10:29:10.329  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:10.329  3311  3374 I jxcore-log: 
,04-01 10:29:10.723  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:10.723  3311  3374 I jxcore-log: 
,04-01 10:29:10.728  3311  3374 I jxcore-log: # setup
04-01 10:29:10.728  3311  3374 I jxcore-log: 
,04-01 10:29:10.729  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:10.729  3311  3374 I jxcore-log: 
,04-01 10:29:10.792  3311  3374 I jxcore-log: # 4. native server connections all up
04-01 10:29:10.792  3311  3374 I jxcore-log: 
,04-01 10:29:10.899  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:29:10.937  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:10.937  3311  3374 I jxcore-log: 
,04-01 10:29:10.949  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 54464
04-01 10:29:10.949  3311  3374 I jxcore-log: 
,04-01 10:29:10.967  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:10.967  3311  3374 I jxcore-log: 
,04-01 10:29:10.972  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:10.972  3311  3374 I jxcore-log: 
,04-01 10:29:10.978  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:10.978  3311  3374 I jxcore-log: 
,04-01 10:29:11.022  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:11.022  3311  3374 I jxcore-log: ,
,04-01 10:29:11.026  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:11.026  3311  3374 I jxcore-log: 
,04-01 10:29:11.039  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:11.039  3311  3374 I jxcore-log: ,
,04-01 10:29:11.042  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:11.042  3311  3374 I jxcore-log: 
,04-01 10:29:11.065  3311  3374 I jxcore-log: ok 7 Send/recvd #1 should be equal length
04-01 10:29:11.065  3311  3374 I jxcore-log: 
,04-01 10:29:11.065  3311  3374 I jxcore-log: ok 8 Send/recvd #1 should be same
04-01 10:29:11.065  3311  3374 I jxcore-log: 
,04-01 10:29:11.067  3311  3374 I jxcore-log: ok 9 Send/recvd #2 should be equal length
04-01 10:29:11.067  3311  3374 I jxcore-log: 
04-01 10:29:11.068  3311  3374 I jxcore-log: ok 10 Send/recvd #2 should be same
04-01 10:29:11.068  3311  3374 I jxcore-log: 
,04-01 10:29:11.070  3311  3374 I jxcore-log: ok 11 Should be exactly 2 client sockets
04-01 10:29:11.070  3311  3374 I jxcore-log: 
,04-01 10:29:11.076  3311  3374 I jxcore-log: # teardown
04-01 10:29:11.076  3311  3374 I jxcore-log: ,
,04-01 10:29:11.183  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.183  3311  3374 I jxcore-log: 
,04-01 10:29:11.188  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.188  3311  3374 I jxcore-log: 
,04-01 10:29:11.191  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:11.191  3311  3374 I jxcore-log: 
,04-01 10:29:11.195  3311  3374 I jxcore-log: # setup
04-01 10:29:11.195  3311  3374 I jxcore-log: 
,04-01 10:29:11.197  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:11.197  3311  3374 I jxcore-log: 
,04-01 10:29:11.326  3311  3374 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
04-01 10:29:11.326  3311  3374 I jxcore-log: 
,04-01 10:29:11.427  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:11.427  3311  3374 I jxcore-log: 
,04-01 10:29:11.437  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 48411
,04-01 10:29:11.437  3311  3374 I jxcore-log: 
,04-01 10:29:11.447  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
,04-01 10:29:11.447  3311  3374 I jxcore-log: 
,04-01 10:29:11.450  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,04-01 10:29:11.450  3311  3374 I jxcore-log: 
,04-01 10:29:11.454  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
,04-01 10:29:11.454  3311  3374 I jxcore-log: 
,04-01 10:29:11.481  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:11.481  3311  3374 I jxcore-log: 
,04-01 10:29:11.484  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:11.484  3311  3374 I jxcore-log: 
,04-01 10:29:11.497  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.497  3311  3374 I jxcore-log: 
,04-01 10:29:11.511  3311  3374 I jxcore-log: ok 12 socket shouldn't close until after stream,
04-01 10:29:11.511  3311  3374 I jxcore-log: 
,04-01 10:29:11.512  3311  3374 I jxcore-log: ok 13 incoming remains open
04-01 10:29:11.512  3311  3374 I jxcore-log: 
,04-01 10:29:11.518  3311  3374 I jxcore-log: # teardown
04-01 10:29:11.518  3311  3374 I jxcore-log: 
,04-01 10:29:11.592  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:11.592  3311  3374 I jxcore-log: 
,04-01 10:29:11.601  3311  3374 I jxcore-log: # setup
04-01 10:29:11.601  3311  3374 I jxcore-log: 
,04-01 10:29:11.603  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:11.603  3311  3374 I jxcore-log: 
,04-01 10:29:11.837  3311  3374 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
04-01 10:29:11.837  3311  3374 I jxcore-log: 
,04-01 10:29:11.936  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:11.936  3311  3374 I jxcore-log: 
,04-01 10:29:11.939  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 37036
04-01 10:29:11.939  3311  3374 I jxcore-log: 
,04-01 10:29:11.945  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:11.945  3311  3374 I jxcore-log: 
,04-01 10:29:11.946  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:11.946  3311  3374 I jxcore-log: 
,04-01 10:29:11.947  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:11.947  3311  3374 I jxcore-log: 
,04-01 10:29:11.958  3311  3374 I jxcore-log: ok 14 we should not have gotten an error
04-01 10:29:11.958  3311  3374 I jxcore-log: 
,04-01 10:29:11.963  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:11.963  3311  3374 I jxcore-log: 
,04-01 10:29:11.968  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:11.968  3311  3374 I jxcore-log: 
,04-01 10:29:11.979  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:11.979  3311  3374 I jxcore-log: 
,04-01 10:29:11.981  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
,04-01 10:29:11.981  3311  3374 I jxcore-log: 
,04-01 10:29:11.989  3311  3374 I jxcore-log: ok 15 socket shouldn't close until after incoming
04-01 10:29:11.989  3311  3374 I jxcore-log: 
,04-01 10:29:11.989  3311  3374 I jxcore-log: ok 16 incoming is cleaned up
04-01 10:29:11.989  3311  3374 I jxcore-log: 
,04-01 10:29:11.995  3311  3374 I jxcore-log: # teardown
04-01 10:29:11.995  3311  3374 I jxcore-log: 
,04-01 10:29:12.239  3311  3374 I jxcore-log: # setup
04-01 10:29:12.239  3311  3374 I jxcore-log: 
,04-01 10:29:12.357  3311  3374 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
04-01 10:29:12.357  3311  3374 I jxcore-log: 
,04-01 10:29:12.510  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:12.510  3311  3374 I jxcore-log: 
,04-01 10:29:12.518  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 46370
04-01 10:29:12.518  3311  3374 I jxcore-log: 
,04-01 10:29:12.524  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:12.524  3311  3374 I jxcore-log: 
,04-01 10:29:12.525  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:12.525  3311  3374 I jxcore-log: 
,04-01 10:29:12.528  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:12.528  3311  3374 I jxcore-log: 
,04-01 10:29:12.540  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:12.540  3311  3374 I jxcore-log: 
,04-01 10:29:12.543  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:12.543  3311  3374 I jxcore-log: 
,04-01 10:29:12.558  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:12.558  3311  3374 I jxcore-log: 
,04-01 10:29:12.568  3311  3374 I jxcore-log: ok 17 stream was closed
04-01 10:29:12.568  3311  3374 I jxcore-log: 
,04-01 10:29:12.568  3311  3374 I jxcore-log: ok 18 incoming should survive
04-01 10:29:12.568  3311  3374 I jxcore-log: 
,04-01 10:29:12.569  3311  3374 I jxcore-log: ok 19 mux should have no streams
04-01 10:29:12.569  3311  3374 I jxcore-log: 
,04-01 10:29:12.577  3311  3374 I jxcore-log: # teardown
04-01 10:29:12.577  3311  3374 I jxcore-log: 
,04-01 10:29:12.719  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:12.719  3311  3374 I jxcore-log: 
,04-01 10:29:12.725  3311  3374 I jxcore-log: # setup
04-01 10:29:12.725  3311  3374 I jxcore-log: 
,04-01 10:29:12.726  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:12.726  3311  3374 I jxcore-log: 
,04-01 10:29:12.878  3311  3374 I jxcore-log: # 8. native server - closing the whole server cleans everything up
04-01 10:29:12.878  3311  3374 I jxcore-log: 
,04-01 10:29:13.162  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:13.162  3311  3374 I jxcore-log: 
,04-01 10:29:13.174  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 50675
04-01 10:29:13.174  3311  3374 I jxcore-log: 
,04-01 10:29:13.182  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:13.182  3311  3374 I jxcore-log: 
,04-01 10:29:13.183  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:13.183  3311  3374 I jxcore-log: 
,04-01 10:29:13.185  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:13.185  3311  3374 I jxcore-log: 
,04-01 10:29:13.195  3311  3374 I jxcore-log: ok 20 we should not have gotten an error
04-01 10:29:13.195  3311  3374 I jxcore-log: 
,04-01 10:29:13.202  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:13.202  3311  3374 I jxcore-log: 
,04-01 10:29:13.205  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:13.205  3311  3374 I jxcore-log: 
,04-01 10:29:13.216  3311  3374 I jxcore-log: ok 21 Buffers are identical
04-01 10:29:13.216  3311  3374 I jxcore-log: 
,04-01 10:29:13.218  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:13.218  3311  3374 I jxcore-log: 
,04-01 10:29:13.222  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:13.222  3311  3374 I jxcore-log: 
,04-01 10:29:13.226  3311  3374 I jxcore-log: ok 22 native server is nulled out
04-01 10:29:13.226  3311  3374 I jxcore-log: 
,04-01 10:29:13.226  3311  3374 I jxcore-log: ok 23 native server should be closed
04-01 10:29:13.226  3311  3374 I jxcore-log: 
,04-01 10:29:13.226  3311  3374 I jxcore-log: ok 24 incoming has been removed
04-01 10:29:13.226  3311  3374 I jxcore-log: 
04-01 10:29:13.227  3311  3374 I jxcore-log: ok 25 Incoming should be done
04-01 10:29:13.227  3311  3374 I jxcore-log: 
04-01 10:29:13.227  3311  3374 I jxcore-log: ok 26 The mux object should be closed
04-01 10:29:13.227  3311  3374 I jxcore-log: 
,04-01 10:29:13.227  3311  3374 I jxcore-log: ok 27 The mux stream should be closed
04-01 10:29:13.227  3311  3374 I jxcore-log: 
04-01 10:29:13.228  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:13.228  3311  3374 I jxcore-log: 
,04-01 10:29:13.244  3311  3374 I jxcore-log: # teardown
04-01 10:29:13.244  3311  3374 I jxcore-log: 
,04-01 10:29:14.223  3311  3374 I jxcore-log: # setup
04-01 10:29:14.223  3311  3374 I jxcore-log: 
,04-01 10:29:17.895  3311  3374 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
04-01 10:29:17.895  3311  3374 I jxcore-log: 
,04-01 10:29:19.446  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:19.446  3311  3374 I jxcore-log: ,
,04-01 10:29:19.452  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 42217
04-01 10:29:19.452  3311  3374 I jxcore-log: 
,04-01 10:29:19.472  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.472  3311  3374 I jxcore-log: 
,04-01 10:29:19.473  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.473  3311  3374 I jxcore-log: 
04-01 10:29:19.474  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.474  3311  3374 I jxcore-log: 
,04-01 10:29:19.478  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.478  3311  3374 I jxcore-log: 
,04-01 10:29:19.483  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.483  3311  3374 I jxcore-log: 
04-01 10:29:19.485  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.485  3311  3374 I jxcore-log: 
,04-01 10:29:19.488  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.488  3311  3374 I jxcore-log: 
,04-01 10:29:19.489  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.489  3311  3374 I jxcore-log: 
,04-01 10:29:19.490  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.490  3311  3374 I jxcore-log: 
04-01 10:29:19.492  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.492  3311  3374 I jxcore-log: 
04-01 10:29:19.493  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.493  3311  3374 I jxcore-log: 
,04-01 10:29:19.494  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.494  3311  3374 I jxcore-log: 
04-01 10:29:19.497  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.497  3311  3374 I jxcore-log: 
,04-01 10:29:19.498  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.498  3311  3374 I jxcore-log: 
,04-01 10:29:19.499  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.499  3311  3374 I jxcore-log: 
04-01 10:29:19.501  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.501  3311  3374 I jxcore-log: 
04-01 10:29:19.501  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.501  3311  3374 I jxcore-log: 
,04-01 10:29:19.502  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.502  3311  3374 I jxcore-log: 
04-01 10:29:19.504  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.504  3311  3374 I jxcore-log: 
04-01 10:29:19.505  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.505  3311  3374 I jxcore-log: 
,04-01 10:29:19.506  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.506  3311  3374 I jxcore-log: 
04-01 10:29:19.508  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.508  3311  3374 I jxcore-log: 
04-01 10:29:19.508  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.508  3311  3374 I jxcore-log: 
04-01 10:29:19.509  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.509  3311  3374 I jxcore-log: 
,04-01 10:29:19.510  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.510  3311  3374 I jxcore-log: 
04-01 10:29:19.511  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.511  3311  3374 I jxcore-log: 
04-01 10:29:19.511  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.511  3311  3374 I jxcore-log: 
,04-01 10:29:19.513  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:19.513  3311  3374 I jxcore-log: 
04-01 10:29:19.513  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:19.513  3311  3374 I jxcore-log: 
04-01 10:29:19.514  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:19.514  3311  3374 I jxcore-log: 
,04-01 10:29:19.627  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.627  3311  3374 I jxcore-log: 
,04-01 10:29:19.630  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.630  3311  3374 I jxcore-log: 
,04-01 10:29:19.632  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.632  3311  3374 I jxcore-log: 
,04-01 10:29:19.634  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.634  3311  3374 I jxcore-log: 
,04-01 10:29:19.635  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.635  3311  3374 I jxcore-log: 
,04-01 10:29:19.637  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.637  3311  3374 I jxcore-log: 
,04-01 10:29:19.639  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.639  3311  3374 I jxcore-log: 
,04-01 10:29:19.641  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.641  3311  3374 I jxcore-log: 
,04-01 10:29:19.644  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.644  3311  3374 I jxcore-log: 
,04-01 10:29:19.646  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.646  3311  3374 I jxcore-log: 
,04-01 10:29:19.648  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.648  3311  3374 I jxcore-log: 
,04-01 10:29:19.649  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.649  3311  3374 I jxcore-log: 
,04-01 10:29:19.651  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.651  3311  3374 I jxcore-log: 
,04-01 10:29:19.653  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.653  3311  3374 I jxcore-log: 
,04-01 10:29:19.654  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.654  3311  3374 I jxcore-log: 
,04-01 10:29:19.656  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.656  3311  3374 I jxcore-log: 
,04-01 10:29:19.658  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.658  3311  3374 I jxcore-log: 
,04-01 10:29:19.660  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.660  3311  3374 I jxcore-log: 
04-01 10:29:19.661  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.661  3311  3374 I jxcore-log: 
,04-01 10:29:19.666  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.666  3311  3374 I jxcore-log: 
,04-01 10:29:19.667  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.667  3311  3374 I jxcore-log: 
,04-01 10:29:19.670  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.670  3311  3374 I jxcore-log: 
,04-01 10:29:19.671  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.671  3311  3374 I jxcore-log: 
,04-01 10:29:19.673  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
04-01 10:29:19.673  3311  3374 I jxcore-log: 
,04-01 10:29:19.676  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.676  3311  3374 I jxcore-log: 
,04-01 10:29:19.678  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.678  3311  3374 I jxcore-log: 
,04-01 10:29:19.679  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.679  3311  3374 I jxcore-log: 
,04-01 10:29:19.681  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.681  3311  3374 I jxcore-log: 
,04-01 10:29:19.682  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.682  3311  3374 I jxcore-log: 
,04-01 10:29:19.684  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.684  3311  3374 I jxcore-log: 
,04-01 10:29:19.685  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.685  3311  3374 I jxcore-log: 
,04-01 10:29:19.687  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.687  3311  3374 I jxcore-log: 
,04-01 10:29:19.689  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.689  3311  3374 I jxcore-log: 
,04-01 10:29:19.691  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.691  3311  3374 I jxcore-log: 
,04-01 10:29:19.692  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.692  3311  3374 I jxcore-log: 
,04-01 10:29:19.694  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.694  3311  3374 I jxcore-log: 
,04-01 10:29:19.695  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.695  3311  3374 I jxcore-log: 
,04-01 10:29:19.696  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.696  3311  3374 I jxcore-log: 
,04-01 10:29:19.698  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.698  3311  3374 I jxcore-log: 
,04-01 10:29:19.699  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.699  3311  3374 I jxcore-log: 
,04-01 10:29:19.701  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.701  3311  3374 I jxcore-log: 
,04-01 10:29:19.703  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.703  3311  3374 I jxcore-log: 
,04-01 10:29:19.705  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.705  3311  3374 I jxcore-log: 
,04-01 10:29:19.706  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.706  3311  3374 I jxcore-log: 
,04-01 10:29:19.708  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.708  3311  3374 I jxcore-log: 
,04-01 10:29:19.709  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.709  3311  3374 I jxcore-log: 
,04-01 10:29:19.710  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.710  3311  3374 I jxcore-log: 
,04-01 10:29:19.718  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.718  3311  3374 I jxcore-log: 
,04-01 10:29:19.721  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.721  3311  3374 I jxcore-log: 
,04-01 10:29:19.722  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.722  3311  3374 I jxcore-log: 
,04-01 10:29:19.724  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.724  3311  3374 I jxcore-log: 
,04-01 10:29:19.725  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.725  3311  3374 I jxcore-log: 
,04-01 10:29:19.727  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.727  3311  3374 I jxcore-log: 
,04-01 10:29:19.728  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.728  3311  3374 I jxcore-log: 
04-01 10:29:19.729  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.729  3311  3374 I jxcore-log: 
,04-01 10:29:19.731  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.731  3311  3374 I jxcore-log: 
,04-01 10:29:19.734  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.734  3311  3374 I jxcore-log: 
,04-01 10:29:19.736  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.736  3311  3374 I jxcore-log: 
,04-01 10:29:19.737  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.737  3311  3374 I jxcore-log: 
,04-01 10:29:19.739  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.739  3311  3374 I jxcore-log: 
,04-01 10:29:19.740  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.740  3311  3374 I jxcore-log: 
,04-01 10:29:19.742  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.742  3311  3374 I jxcore-log: 
,04-01 10:29:19.743  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.743  3311  3374 I jxcore-log: 
,04-01 10:29:19.744  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.744  3311  3374 I jxcore-log: 
,04-01 10:29:19.746  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.746  3311  3374 I jxcore-log: 
,04-01 10:29:19.748  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.748  3311  3374 I jxcore-log: 
,04-01 10:29:19.749  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.749  3311  3374 I jxcore-log: 
,04-01 10:29:19.751  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.751  3311  3374 I jxcore-log: 
,04-01 10:29:19.752  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.752  3311  3374 I jxcore-log: 
,04-01 10:29:19.754  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.754  3311  3374 I jxcore-log: 
,04-01 10:29:19.755  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.755  3311  3374 I jxcore-log: 
,04-01 10:29:19.756  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.756  3311  3374 I jxcore-log: 
,04-01 10:29:19.759  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.759  3311  3374 I jxcore-log: 
,04-01 10:29:19.760  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.760  3311  3374 I jxcore-log: 
,04-01 10:29:19.761  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.761  3311  3374 I jxcore-log: 
,04-01 10:29:19.763  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.763  3311  3374 I jxcore-log: 
,04-01 10:29:19.764  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.764  3311  3374 I jxcore-log: 
,04-01 10:29:19.766  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.766  3311  3374 I jxcore-log: 
,04-01 10:29:19.767  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:19.767  3311  3374 I jxcore-log: 
,04-01 10:29:19.768  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:19.768  3311  3374 I jxcore-log: 
,04-01 10:29:19.845  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.845  3311  3374 I jxcore-log: 
,04-01 10:29:19.846  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.846  3311  3374 I jxcore-log: 
,04-01 10:29:19.848  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.848  3311  3374 I jxcore-log: 
,04-01 10:29:19.849  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.849  3311  3374 I jxcore-log: 
,04-01 10:29:19.851  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.851  3311  3374 I jxcore-log: 
,04-01 10:29:19.852  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.852  3311  3374 I jxcore-log: 
04-01 10:29:19.853  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.853  3311  3374 I jxcore-log: 
04-01 10:29:19.854  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.854  3311  3374 I jxcore-log: 
,04-01 10:29:19.855  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.855  3311  3374 I jxcore-log: 
,04-01 10:29:19.856  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.856  3311  3374 I jxcore-log: 
04-01 10:29:19.858  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.858  3311  3374 I jxcore-log: 
,04-01 10:29:19.860  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.860  3311  3374 I jxcore-log: 
04-01 10:29:19.860  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.860  3311  3374 I jxcore-log: 
04-01 10:29:19.861  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.861  3311  3374 I jxcore-log: 
,04-01 10:29:19.862  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.862  3311  3374 I jxcore-log: 
04-01 10:29:19.863  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.863  3311  3374 I jxcore-log: 
04-01 10:29:19.865  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.865  3311  3374 I jxcore-log: 
,04-01 10:29:19.865  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.865  3311  3374 I jxcore-log: 
04-01 10:29:19.866  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.866  3311  3374 I jxcore-log: 
,04-01 10:29:19.867  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.867  3311  3374 I jxcore-log: 
,04-01 10:29:19.868  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.868  3311  3374 I jxcore-log: 
04-01 10:29:19.869  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.869  3311  3374 I jxcore-log: 
04-01 10:29:19.870  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.870  3311  3374 I jxcore-log: 
,04-01 10:29:19.871  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.871  3311  3374 I jxcore-log: 
,04-01 10:29:19.872  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.872  3311  3374 I jxcore-log: 
,04-01 10:29:19.874  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.874  3311  3374 I jxcore-log: 
,04-01 10:29:19.875  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.875  3311  3374 I jxcore-log: 
,04-01 10:29:19.876  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.876  3311  3374 I jxcore-log: 
,04-01 10:29:19.876  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.876  3311  3374 I jxcore-log: 
,04-01 10:29:19.878  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.878  3311  3374 I jxcore-log: 
,04-01 10:29:19.879  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.879  3311  3374 I jxcore-log: 
,04-01 10:29:19.880  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.880  3311  3374 I jxcore-log: 
,04-01 10:29:19.881  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.881  3311  3374 I jxcore-log: 
,04-01 10:29:19.882  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.882  3311  3374 I jxcore-log: 
,04-01 10:29:19.883  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.883  3311  3374 I jxcore-log: 
,04-01 10:29:19.884  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.884  3311  3374 I jxcore-log: 
,04-01 10:29:19.885  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.885  3311  3374 I jxcore-log: 
04-01 10:29:19.886  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.886  3311  3374 I jxcore-log: 
04-01 10:29:19.887  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.887  3311  3374 I jxcore-log: 
,04-01 10:29:19.888  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.888  3311  3374 I jxcore-log: 
04-01 10:29:19.889  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.889  3311  3374 I jxcore-log: 
04-01 10:29:19.890  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.890  3311  3374 I jxcore-log: 
04-01 10:29:19.891  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.891  3311  3374 I jxcore-log: 
04-01 10:29:19.892  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.892  3311  3374 I jxcore-log: 
04-01 10:29:19.893  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.893  3311  3374 I jxcore-log: 
04-01 10:29:19.894  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.894  3311  3374 I jxcore-log: 
,04-01 10:29:19.895  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.895  3311  3374 I jxcore-log: 
,04-01 10:29:19.897  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.897  3311  3374 I jxcore-log: 
,04-01 10:29:19.898  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:19.898  3311  3374 I jxcore-log: 
,04-01 10:29:19.900  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:19.900  3311  3374 I jxcore-log: 
,04-01 10:29:19.903  3311  3374 I jxcore-log: ok 28 native server is nulled out
04-01 10:29:19.903  3311  3374 I jxcore-log: 
,04-01 10:29:19.904  3311  3374 I jxcore-log: ok 29 native server should be closed
04-01 10:29:19.904  3311  3374 I jxcore-log: 
04-01 10:29:19.904  3311  3374 I jxcore-log: ok 30 incoming has been removed
04-01 10:29:19.904  3311  3374 I jxcore-log: 
,04-01 10:29:19.906  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.906  3311  3374 I jxcore-log: 
,04-01 10:29:19.907  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.907  3311  3374 I jxcore-log: 
04-01 10:29:19.907  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.907  3311  3374 I jxcore-log: 
,04-01 10:29:19.908  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.908  3311  3374 I jxcore-log: 
,04-01 10:29:19.909  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.909  3311  3374 I jxcore-log: 
04-01 10:29:19.909  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.909  3311  3374 I jxcore-log: 
,04-01 10:29:19.910  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.910  3311  3374 I jxcore-log: 
,04-01 10:29:19.910  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.910  3311  3374 I jxcore-log: 
04-01 10:29:19.911  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.911  3311  3374 I jxcore-log: 
,04-01 10:29:19.911  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:19.911  3311  3374 I jxcore-log: 
,04-01 10:29:20.011  3311  3374 I jxcore-log: # teardown
04-01 10:29:20.011  3311  3374 I jxcore-log: 
,04-01 10:29:22.289  3311  3374 I jxcore-log: # setup
04-01 10:29:22.289  3311  3374 I jxcore-log: 
,04-01 10:29:24.136  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:29:24.137  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:24.137  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:29:24.138  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:24.148  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:24.171  3106  3835 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 10:29:24.171  3106  3835 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at blb.a(PG:3937)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at czp.a(PG:18188)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:29:24.171  3106  3835 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	... 12 more
04-01 10:29:24.171  3106  3835 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at fal.a(PG:38)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:29:24.171  3106  3835 E HttpOperation: 	... 14 more
,04-01 10:29:24.228  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
04-01 10:29:24.229  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:24.229  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:24.229  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:24.232  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:24.249  3106  3835 E HttpOperation: [getmobileexperiments] Unexpected exception,
04-01 10:29:24.249  3106  3835 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at hec.a(PG:42)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at hee.a(PG:102)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at czr.a(PG:65)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at kka.a(PG:108)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at czp.a(PG:19176)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:29:24.249  3106  3835 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	... 15 more
04-01 10:29:24.249  3106  3835 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at fal.a(PG:38)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:29:24.249  3106  3835 E HttpOperation: 	... 17 more
04-01 10:29:24.249  3106  3835 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 10:29:24.249  3106  3835 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at hec.a(PG:42)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at hee.a(PG:102)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at czr.a(PG:65)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at kka.a(PG:108)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jdj.a(PG:1125)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 10:29:24.2,49  3106  3835 E ExperimentLoader: 	... 15 more
04-01 10:29:24.249  3106  3835 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at fal.a(PG:38)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 10:29:24.249  3106  3835 E ExperimentLoader: 	... 17 more
,04-01 10:29:24.396   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 200241, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:29:24.442  1492  1679 I art     : Explicit concurrent mark sweep GC freed 47265(2MB) AllocSpace objects, 7(673KB) LOS objects, 36% free, 27MB/43MB, paused 1.039ms total 28.481ms
,04-01 10:29:24.596  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:24.651  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
04-01 10:29:24.651  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:24.651  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:24.651  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:24.657  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:29:24.674  3727  3727 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,04-01 10:29:24.675  3727  3727 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
04-01 10:29:24.675  3727  3727 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,04-01 10:29:27.044  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:29:27.692  3311  3374 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
04-01 10:29:27.692  3311  3374 I jxcore-log: 
,04-01 10:29:28.789  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server,
04-01 10:29:28.789  3311  3374 I jxcore-log: 
,04-01 10:29:28.793  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 45041,
04-01 10:29:28.793  3311  3374 I jxcore-log: 
,04-01 10:29:28.800  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
,04-01 10:29:28.800  3311  3374 I jxcore-log: 
,04-01 10:29:28.802  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:28.802  3311  3374 I jxcore-log: ,
,04-01 10:29:28.805  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
,04-01 10:29:28.805  3311  3374 I jxcore-log: 
,04-01 10:29:28.814  3311  3374 I jxcore-log: ok 31 we should not have gotten an error
04-01 10:29:28.814  3311  3374 I jxcore-log: ,
,04-01 10:29:28.819  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
,04-01 10:29:28.819  3311  3374 I jxcore-log: 
,04-01 10:29:28.824  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,04-01 10:29:28.824  3311  3374 I jxcore-log: 
,04-01 10:29:28.838  3311  3374 I jxcore-log: ok 32 Buffers are identical
,04-01 10:29:28.838  3311  3374 I jxcore-log: 
,04-01 10:29:28.841  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
,04-01 10:29:28.841  3311  3374 I jxcore-log: 
,04-01 10:29:28.845  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
,04-01 10:29:28.845  3311  3374 I jxcore-log: 
,04-01 10:29:28.857  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
,04-01 10:29:28.857  3311  3374 I jxcore-log: 
,04-01 10:29:28.858  3311  3374 I jxcore-log: ok 33 server should be fine
04-01 10:29:28.858  3311  3374 I jxcore-log: 
,04-01 10:29:28.858  3311  3374 I jxcore-log: ok 34 server should be open
04-01 10:29:28.858  3311  3374 I jxcore-log: 
04-01 10:29:28.859  3311  3374 I jxcore-log: ok 35 incoming has been removed,
04-01 10:29:28.859  3311  3374 I jxcore-log: 
04-01 10:29:28.859  3311  3374 I jxcore-log: ok 36 The mux object should be closed
04-01 10:29:28.859  3311  3374 I jxcore-log: 
,04-01 10:29:28.860  3311  3374 I jxcore-log: ok 37 The mux stream should be closed
04-01 10:29:28.860  3311  3374 I jxcore-log: 
,04-01 10:29:28.866  3311  3374 I jxcore-log: # teardown,
04-01 10:29:28.866  3311  3374 I jxcore-log: 
,04-01 10:29:30.464  3311  3374 I jxcore-log: # setup
04-01 10:29:30.464  3311  3374 I jxcore-log: 
,04-01 10:29:33.090  3311  3374 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up,
04-01 10:29:33.090  3311  3374 I jxcore-log: 
,04-01 10:29:33.179   821   840 I art     : Explicit concurrent mark sweep GC freed 26963(1256KB) AllocSpace objects, 5(457KB) LOS objects, 32% free, 33MB/49MB, paused 1.445ms total 86.998ms
,04-01 10:29:33.223  3422  3843 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 10:29:33.253  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,04-01 10:29:33.253  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:33.253  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:33.253  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:33.256  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:33.266  3422  3843 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
04-01 10:29:33.267  3422  3843 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 10:29:47.388  1219  1486 I Keyboard.Facilitator.LanguageModelFlusher: run()
,04-01 10:29:47.388  1219  1486 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-01 10:29:47.433  1492  1492 I ConfigService: onCreate
,04-01 10:29:52.515  1492  1492 I ConfigService: onDestroy
,04-01 10:29:53.020  3311  3374 I jxcore-log: DEBUG createNativeListener: creating native server
04-01 10:29:53.020  3311  3374 I jxcore-log: 
,04-01 10:29:53.048  3311  3374 I jxcore-log: DEBUG createNativeListener: listening 43337
04-01 10:29:53.048  3311  3374 I jxcore-log: 
,04-01 10:29:53.054  3311  3374 I jxcore-log: DEBUG createNativeListener: new incoming socket
04-01 10:29:53.054  3311  3374 I jxcore-log: 
,04-01 10:29:53.056  3311  3374 I jxcore-log: DEBUG createNativeListener: creating incoming mux
04-01 10:29:53.056  3311  3374 I jxcore-log: 
,04-01 10:29:53.057  3311  3374 I jxcore-log: DEBUG createNativeListener: new mux
04-01 10:29:53.057  3311  3374 I jxcore-log: 
,04-01 10:29:53.063  3311  3374 I jxcore-log: ok 38 we should not have gotten an error
04-01 10:29:53.063  3311  3374 I jxcore-log: 
,04-01 10:29:53.067  3311  3374 I jxcore-log: DEBUG createNativeListener: new stream: 
04-01 10:29:53.067  3311  3374 I jxcore-log: 
,04-01 10:29:53.069  3311  3374 I jxcore-log: DEBUG createNativeListener: new outgoing socket
04-01 10:29:53.069  3311  3374 I jxcore-log: 
,04-01 10:29:53.076  3311  3374 I jxcore-log: ok 39 Buffers are identical
04-01 10:29:53.076  3311  3374 I jxcore-log: 
,04-01 10:29:53.080  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
04-01 10:29:53.080  3311  3374 I jxcore-log: 
04-01 10:29:53.081  3311  3374 I jxcore-log: DEBUG createNativeListener: stream close:
04-01 10:29:53.081  3311  3374 I jxcore-log: 
,04-01 10:29:53.082  3311  3374 I jxcore-log: DEBUG createNativeListener: mux close
04-01 10:29:53.082  3311  3374 I jxcore-log: 
04-01 10:29:53.085  3311  3374 I jxcore-log: DEBUG createNativeListener: incoming socket close
04-01 10:29:53.085  3311  3374 I jxcore-log: 
04-01 10:29:53.085  3311  3374 I jxcore-log: ok 40 server should be fine
04-01 10:29:53.085  3311  3374 I jxcore-log: 
,04-01 10:29:53.086  3311  3374 I jxcore-log: ok 41 server should be open
04-01 10:29:53.086  3311  3374 I jxcore-log: 
04-01 10:29:53.086  3311  3374 I jxcore-log: ok 42 incoming has been removed
04-01 10:29:53.086  3311  3374 I jxcore-log: 
04-01 10:29:53.086  3311  3374 I jxcore-log: ok 43 The mux object should be closed
04-01 10:29:53.086  3311  3374 I jxcore-log: 
,04-01 10:29:53.086  3311  3374 I jxcore-log: ok 44 The mux stream should be closed
04-01 10:29:53.086  3311  3374 I jxcore-log: 
,04-01 10:29:53.094  3311  3374 I jxcore-log: # teardown
04-01 10:29:53.094  3311  3374 I jxcore-log: 
,04-01 10:29:53.992  3526  3849 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 10:29:54.007  3488  3848 V KeepSync: Connecting to GoogleApiClient
,04-01 10:29:54.034  3526  3850 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,04-01 10:29:54.081  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
04-01 10:29:54.081  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:54.081  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:54.082  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:54.083  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
,04-01 10:29:54.084  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,04-01 10:29:54.084  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:29:54.084  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
04-01 10:29:54.085  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:54.088  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: Handling authorization failure
,04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62),
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: ,	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: ,	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319),
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 10:29:54.102  1806  3851 E ClientConnectionOperation: 	... 7 more
,04-01 10:29:54.104  3488  3848 V KeepSync: GoogleApiClient failed to connect with error code: 4
04-01 10:29:54.107  3488  3848 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:29:54.111  3488  3848 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:29:54.112  3488  3848 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:29:54.172  1492  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:29:54.172  1492  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:29:54.172  1492  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:54.172  1492  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:54.175  1492  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:54.176  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
04-01 10:29:54.176  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:29:54.176  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:29:54.177  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:29:54.182  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:29:54.187  3526  3850 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,04-01 10:29:54.189  3526  3849 E BooksSync: Soft error
04-01 10:29:54.189  3526  3849 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:29:54.189  3526  3849 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:29:54.189  3526  3849 E BooksSync: Sync error
04-01 10:29:54.189  3526  3849 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:29:54.189  3526  3849 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:29:54.189  3526  3849 I BooksSync: Finished books sync
,04-01 10:29:54.194   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202350, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:29:54.219  3488  3848 E KeepSync: IOException
04-01 10:29:54.219  3488  3848 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 10:29:54.219  3488  3848 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 10:29:54.219  3488  3848 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 10:29:54.219  3488  3848 E KeepSync: 	... 10 more
04-01 10:29:54.219  3488  3848 W KeepSync: Sync result 2
,04-01 10:29:54.224   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201620, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:30:10.903  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:30:27.204  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:30:33.340  3422  3862 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 10:30:33.460  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
04-01 10:30:33.461  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:30:33.461  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:30:33.462  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:30:33.477  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:30:33.523  3422  3862 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: ,	at com.a.a.a.k.get(SourceFile:97)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: ,	at com.a.a.a.a.a(SourceFile:93)
04-01 10:30:33.525  3422  3862 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 10:30:35.447  3311  3374 I jxcore-log: # setup
04-01 10:30:35.447  3311  3374 I jxcore-log: 
,04-01 10:30:54.219  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:30:54.219  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:30:54.220  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:30:54.220  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:30:54.228  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:30:54.258  3106  3867 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 10:30:54.258  3106  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at blb.a(PG:3937)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at czp.a(PG:18188)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:30:54.258  3106  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jdj.a(PG:4091),
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	... 12 more
04-01 10:30:54.258  3106  3867 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at fal.a(PG:38)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:30:54.258  3106  3867 E HttpOperation: 	... 14 more
,04-01 10:30:54.321  1492  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:30:54.321  1492  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:30:54.321  1492  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:30:54.321  1492  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:30:54.327  1492  3841 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:30:54.344  3106  3867 E HttpOperation: [getmobileexperiments] Unexpected exception
04-01 10:30:54.344  3106  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at hec.a(PG:42)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at hee.a(PG:102)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at czr.a(PG:65)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at kka.a(PG:108)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at czp.a(PG:19176)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:30:54.344  3106  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	... 15 more
04-01 10:30:54.344  3106  3867 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at fal.a(PG:38)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:30:54.344  3106  3867 E HttpOperation: 	... 17 more
,04-01 10:30:54.346  3106  3867 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 10:30:54.346  3106  3867 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token,
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at hec.a(PG:42)
,04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at hee.a(PG:102)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at czr.a(PG:65)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at kka.a(PG:108)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	,at jdj.a(PG:1125)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	... 15 more
04-01 10:30:54.346  3106  3867 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at fal.a(PG:38)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 10:30:54.346  3106  3867 E ExperimentLoader: 	... 17 more
,04-01 10:30:54.458   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 264339, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:31:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:31:24.279  3526  3874 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 10:31:24.291  3488  3875 V KeepSync: Connecting to GoogleApiClient
,04-01 10:31:24.325  3526  3876 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,04-01 10:31:24.376  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
04-01 10:31:24.376  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:31:24.376  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:31:24.376  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:31:24.379  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:31:24.387  1492  2558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,04-01 10:31:24.388  1492  2558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:31:24.389  1492  2558 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:31:24.389  1492  2558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:31:24.400  1492  2558 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: Handling authorization failure
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 10:31:24.421  1806  3877 E ClientConnectionOperation: 	... 7 more
,04-01 10:31:24.424  3488  3875 V KeepSync: GoogleApiClient failed to connect with error code: 4
,04-01 10:31:24.427  3488  3875 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:31:24.438  3488  3875 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:31:24.441  3488  3875 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:31:24.483  1492  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:31:24.483  1492  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:31:24.483  1492  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:31:24.483  1492  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:31:24.488  1492  3841 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:31:24.541  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,04-01 10:31:24.541  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:31:24.541  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:31:24.541  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:31:24.549  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:31:24.563   821  1299 I art     : Explicit concurrent mark sweep GC freed 30500(1297KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.293ms total 66.164ms
,04-01 10:31:24.577  3526  3876 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,04-01 10:31:24.580  3526  3874 E BooksSync: Soft error
04-01 10:31:24.580  3526  3874 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:31:24.580  3526  3874 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,04-01 10:31:24.582  3526  3874 E BooksSync: Sync error
04-01 10:31:24.582  3526  3874 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:31:24.582  3526  3874 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,04-01 10:31:24.582  3526  3874 I BooksSync: Finished books sync
04-01 10:31:24.582  3488  3875 E KeepSync: IOException
04-01 10:31:24.582  3488  3875 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 10:31:24.582  3488  3875 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 10:31:24.582  3488  3875 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 10:31:24.582  3488  3875 E KeepSync: 	... 10 more
04-01 10:31:24.582  3488  3875 W KeepSync: Sync result 2
,04-01 10:31:24.592   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 296020, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:31:24.615   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 296298, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:31:27.365  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:31:27.925   821  1358 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3dea8b69}
,04-01 10:31:27.935   821  1025 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,04-01 10:31:29.622   821  1358 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3dea8b69}
,04-01 10:31:29.672   821  1237 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,04-01 10:31:29.753   877   877 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,04-01 10:31:29.753   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,04-01 10:31:29.795   877   877 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
04-01 10:31:29.795   877   877 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,04-01 10:31:30.770   877   877 I kickstart: STATUS: Received file 'm9kefs2',
04-01 10:31:30.770   877   877 I kickstart: STATUS: 950272 bytes transferred in 0.974657 seconds
04-01 10:31:30.770   877   877 I kickstart: STATUS: Successfully downloaded files from target 
04-01 10:31:30.770   877   877 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,04-01 10:31:30.773   877   877 I kickstart: STATUS: Sahara protocol completed
,04-01 10:32:10.901  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:32:27.524  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:33:00.460  1806  3897 I EventLogService: Opted in for usage reporting
04-01 10:33:00.460  1806  3897 I EventLogService: Aggregate from 1459497780244 (log), 1459497780244 (data)
,04-01 10:33:00.472  3422  3898 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 10:33:00.562  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
04-01 10:33:00.562  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:33:00.562  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:33:00.563  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:33:00.567  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
04-01 10:33:00.581  3422  3898 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 10:33:00.638  1806  3897 W EventLogAggregator: Unknown tag: snet_gcore
04-01 10:33:00.638  1806  3897 W EventLogAggregator: Unknown tag: snet_launch_service
,04-01 10:33:00.732  1492  2320 I art     : Explicit concurrent mark sweep GC freed 48746(2MB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 27MB/43MB, paused 1.215ms total 64.752ms
,04-01 10:33:00.744  1806  3897 I ServiceDumpSys: dumping service [account]
,04-01 10:33:01.855  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:33:01.856  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:33:01.856  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:33:01.857  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:33:01.875  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:33:01.921  3106  3902 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 10:33:01.921  3106  3902 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at blb.a(PG:3937)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at czp.a(PG:18188)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:33:01.921  3106  3902 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	... 12 more
04-01 10:33:01.921  3106  3902 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at fal.a(PG:38)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:33:01.921  3106  3902 E HttpOperation: 	... 14 more
,04-01 10:33:02.003  1492  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
04-01 10:33:02.004  1492  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:33:02.004  1492  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:33:02.004  1492  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:33:02.011  1492  2320 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:33:02.039  3106  3902 E HttpOperation: [getmobileexperiments] Unexpected exception
04-01 10:33:02.039  3106  3902 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at hec.a(PG:42)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at hee.a(PG:102)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at czr.a(PG:65)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at kka.a(PG:108)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at czp.a(PG:19176)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:33:02.039  3106  3902 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	... 15 more
04-01 10:33:02.039  3106  3902 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at fal.a(PG:38)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:33:02.039  3106  3902 E HttpOperation: 	... 17 more
,04-01 10:33:02.040  3106  3902 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 10:33:02.040  3106  3902 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at hec.a(PG:42)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at hee.a(PG:102)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at czr.a(PG:65)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at kka.a(PG:108)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jdj.a(PG:1125)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	... 15 more
04-01 10:33:02.040  3106  3902 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at fal.a(PG:38)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 10:33:02.040  3106  3902 E ExperimentLoader: 	... 17 more
,04-01 10:33:02.180   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 417999, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:33:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:34:01.759  3526  3913 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 10:34:01.809  3526  3916 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
04-01 10:34:01.810  3488  3914 V KeepSync: Connecting to GoogleApiClient
,04-01 10:34:01.853  1492  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
04-01 10:34:01.853  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:34:01.854  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:34:01.854  1492  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:34:01.854  1492  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:34:01.854  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:34:01.854  1492  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:34:01.854  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:34:01.858  1492  3841 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:34:01.859  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: Handling authorization failure
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 10:34:01.870  1806  3917 E ClientConnectionOperation: 	... 7 more
,04-01 10:34:01.873  3488  3914 V KeepSync: GoogleApiClient failed to connect with error code: 4
,04-01 10:34:01.876  3488  3914 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:34:01.880  3488  3914 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:34:01.881  3488  3914 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:34:01.925  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
04-01 10:34:01.925  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:34:01.925  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:34:01.925  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:34:01.929  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:34:01.942  3526  3916 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,04-01 10:34:01.943  3526  3913 E BooksSync: Soft error
04-01 10:34:01.943  3526  3913 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:34:01.943  3526  3913 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:34:01.943  3526  3913 E BooksSync: Sync error
04-01 10:34:01.943  3526  3913 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:34:01.943  3526  3913 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:34:01.943  3526  3913 I BooksSync: Finished books sync
,04-01 10:34:01.949   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 451897, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:34:01.964  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
04-01 10:34:01.964  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:34:01.964  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:34:01.965  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:34:01.969  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:34:02.002  3488  3914 E KeepSync: IOException
04-01 10:34:02.002  3488  3914 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 10:34:02.002  3488  3914 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 10:34:02.002  3488  3914 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 10:34:02.002  3488  3914 E KeepSync: 	... 10 more
04-01 10:34:02.003  3488  3914 W KeepSync: Sync result 2
,04-01 10:34:02.038   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 452417, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:34:03.110  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:34:03.191  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,04-01 10:34:03.192  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:34:03.192  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:34:03.192  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:34:03.204  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:34:03.283  1492  1510 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:34:03.283  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:34:03.283  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:34:03.283  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
04-01 10:34:03.283  1492  1510 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
04-01 10:34:03.283  1492  1510 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
04-01 10:34:03.283  1492  1510 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,04-01 10:34:03.288  3727  3762 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:34:03.288  3727  3762 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
04-01 10:34:03.288  3727  3762 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
04-01 10:34:03.288  3727  3762 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
04-01 10:34:03.288  3727  3762 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
04-01 10:34:03.288  3727  3762 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
04-01 10:34:03.288  3727  3762 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,04-01 10:34:03.317  3727  3762 W System  : Ignoring header User-Agent because its value was null.
,04-01 10:34:10.901  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:34:27.845  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:35:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:35:28.005  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:36:10.904  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:36:28.167  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:37:10.906  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:37:16.774   821  1298 I art     : Explicit concurrent mark sweep GC freed 42751(1980KB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 2.910ms total 71.398ms
,04-01 10:37:16.834  1492  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
04-01 10:37:16.834  1492  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:37:16.834  1492  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:37:16.834  1492  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:37:16.838  1492  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:37:16.858  3106  3958 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 10:37:16.858  3106  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at blb.a(PG:3937)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at czp.a(PG:18188)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:37:16.858  3106  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	... 12 more
04-01 10:37:16.858  3106  3958 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at fal.a(PG:38)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:37:16.858  3106  3958 E HttpOperation: 	... 14 more
,04-01 10:37:16.904  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:37:16.904  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:37:16.904  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:37:16.904  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:37:16.909  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:37:16.922  3106  3958 E HttpOperation: [getmobileexperiments] Unexpected exception
04-01 10:37:16.922  3106  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at hec.a(PG:42)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at hee.a(PG:102)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at czr.a(PG:65)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at kka.a(PG:108)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at czp.a(PG:19176)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:37:16.922  3106  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	... 15 more
04-01 10:37:16.922  3106  3958 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at fal.a(PG:38)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:37:16.922  3106  3958 E HttpOperation: 	... 17 more
04-01 10:37:16.922  3106  3958 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 10:37:16.922  3106  3958 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at hec.a(PG:42)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at hee.a(PG:102)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at czr.a(PG:65)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at kka.a(PG:108)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jdj.a(PG:1,125)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	... 15 more
04-01 10:37:16.922  3106  3958 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at fal.a(PG:38)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 10:37:16.922  3106  3958 E ExperimentLoader: 	... 17 more
,04-01 10:37:17.026   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 672918, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:37:28.324  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:38:10.900  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:38:23.903  3526  3970 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 10:38:23.951  3526  3971 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,04-01 10:38:24.055  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
04-01 10:38:24.055  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:38:24.056  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:38:24.056  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:38:24.070  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:38:24.258  1492  1678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:38:24.259  1492  1678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:38:24.261  1492  1678 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:38:24.262  1492  1678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:38:24.275  1492  1678 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:38:24.316  3526  3971 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,04-01 10:38:24.320  3526  3970 E BooksSync: Soft error
04-01 10:38:24.320  3526  3970 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:38:24.320  3526  3970 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:38:24.321  3526  3970 E BooksSync: Sync error
04-01 10:38:24.321  3526  3970 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:38:24.321  3526  3970 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
04-01 10:38:24.321  3526  3970 I BooksSync: Finished books sync
,04-01 10:38:24.339   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 740214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:38:28.484  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:38:53.987  3488  3977 V KeepSync: Connecting to GoogleApiClient
,04-01 10:38:54.139  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
04-01 10:38:54.140  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:38:54.140  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:38:54.140  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:38:54.153  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: Handling authorization failure
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 10:38:54.196  1806  3978 E ClientConnectionOperation: 	... 7 more
,04-01 10:38:54.202  3488  3977 V KeepSync: GoogleApiClient failed to connect with error code: 4
,04-01 10:38:54.212  3488  3977 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:38:54.234  3488  3977 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:38:54.237  3488  3977 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:38:54.328  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,04-01 10:38:54.329  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:38:54.329  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:38:54.329  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:38:54.335  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:38:54.416  3488  3977 E KeepSync: IOException
04-01 10:38:54.416  3488  3977 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 10:38:54.416  3488  3977 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 10:38:54.416  3488  3977 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 10:38:54.416  3488  3977 E KeepSync: 	... 10 more
,04-01 10:38:54.417  3488  3977 W KeepSync: Sync result 2
,04-01 10:38:54.424   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 741295, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:39:10.901  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:39:25.935  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:39:26.009  1492  1492 I art     : Explicit concurrent mark sweep GC freed 53392(2MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 2.382ms total 54.721ms
,04-01 10:39:26.045  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
04-01 10:39:26.045  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:39:26.045  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:39:26.045  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:39:26.050  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,04-01 10:39:26.081  1492  1510 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
04-01 10:39:26.081  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
04-01 10:39:26.081  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
04-01 10:39:26.081  1492  1510 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
04-01 10:39:26.081  1492  1510 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
04-01 10:39:26.081  1492  1510 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
04-01 10:39:26.081  1492  1510 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,04-01 10:39:26.083  3727  3762 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
04-01 10:39:26.083  3727  3762 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
04-01 10:39:26.083  3727  3762 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
04-01 10:39:26.083  3727  3762 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
04-01 10:39:26.083  3727  3762 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
04-01 10:39:26.083  3727  3762 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
04-01 10:39:26.083  3727  3762 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
04-01 10:39:26.084  3727  3762 W System  : Ignoring header User-Agent because its value was null.
,04-01 10:39:28.645  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:39:43.230  3422  3991 V GoogleAuthProtoRequest: [349] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 10:39:43.322  1492  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,04-01 10:39:43.324  1492  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:39:43.325  1492  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:39:43.325  1492  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:39:43.346  1492  3841 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:39:43.374  3422  3991 W ExperimentUpdateService: [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
04-01 10:39:43.377  3422  3991 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 10:40:10.901  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:40:28.805  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:41:50.491  2157  2230 W bt-btm  : Stopping oneshot timer
,04-01 10:42:10.901  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:43:10.901  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:43:29.287  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:43:54.527  1492  3565 D GCM     : Message class com.google.f.a.a.i
,04-01 10:44:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:44:29.446  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:45:10.904  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:45:29.607  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:45:46.041  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:45:46.041  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:45:46.042  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:45:46.042  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:45:46.049  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:45:46.079  3106  4056 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
04-01 10:45:46.079  3106  4056 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at blb.a(PG:3937)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at czp.a(PG:18188)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:45:46.079  3106  4056 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	... 12 more
04-01 10:45:46.079  3106  4056 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at fal.a(PG:38)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:45:46.079  3106  4056 E HttpOperation: 	... 14 more
,04-01 10:45:46.127  1492  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,04-01 10:45:46.128  1492  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:45:46.128  1492  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:45:46.128  1492  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:45:46.135  1492  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:45:46.195   821  1096 I art     : Explicit concurrent mark sweep GC freed 40123(1823KB) AllocSpace objects, 8(505KB) LOS objects, 31% free, 34MB/50MB, paused 1.352ms total 55.017ms
,04-01 10:45:46.210  3106  4056 E HttpOperation: [getmobileexperiments] Unexpected exception
04-01 10:45:46.210  3106  4056 E HttpOperation: java.io.IOException: Cannot obtain authentication token
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jdm.a(PG:82)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jcs.o(PG:406)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jcn.a(PG:1379)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jcs.i(PG:143)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at hec.a(PG:42)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at hee.a(PG:102)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at czr.a(PG:65)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at kka.a(PG:108)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at czp.a(PG:19176)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at czp.a(PG:9081)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at czq.run(PG:1686)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:45:46.210  3106  4056 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jdj.a(PG:4091)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jdj.a(PG:1125)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jdm.a(PG:77)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	... 15 more
04-01 10:45:46.210  3106  4056 E HttpOperation: Caused by: faj: BadAuthentication
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at fal.a(PG:38)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	at jdj.a(PG:4089)
04-01 10:45:46.210  3106  4056 E HttpOperation: 	... 17 more
04-01 10:45:46.210  3106  4056 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
04-01 10:45:46.210  3106  4056 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jdm.a(PG:82)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jcs.o(PG:406)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jcn.a(PG:1379)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jcs.i(PG:143)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at hec.a(PG:42)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at hee.a(PG:102)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at czr.a(PG:65)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at kka.a(PG:108)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at czp.a(PG:19176)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at czp.a(PG:9081)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at czq.run(PG:1686)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jdj.a(PG:4091)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jdj.a(PG:1,125)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jdm.a(PG:77)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	... 15 more
04-01 10:45:46.210  3106  4056 E ExperimentLoader: Caused by: faj: BadAuthentication
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at fal.a(PG:38)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	at jdj.a(PG:4089)
04-01 10:45:46.210  3106  4056 E ExperimentLoader: 	... 17 more
,04-01 10:45:46.309   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1182156, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:46:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:46:35.338   821   854 I UsageStatsService: User[0] Flushing usage stats to disk
,04-01 10:47:08.333  3526  4072 I BooksSync: Starting books sync for 61035162, extras: ade
,04-01 10:47:08.371  3526  4073 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,04-01 10:47:08.451  1492  1678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:47:08.452  1492  1678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:47:08.452  1492  1678 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:47:08.452  1492  1678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:47:08.462  1492  1678 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:47:08.626  1492  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,04-01 10:47:08.626  1492  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:47:08.627  1492  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:47:08.627  1492  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:47:08.641  1492  3841 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:47:08.680  3526  4073 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,04-01 10:47:08.683  3526  4072 E BooksSync: Soft error
04-01 10:47:08.683  3526  4072 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:47:08.683  3526  4072 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,04-01 10:47:08.685  3526  4072 E BooksSync: Sync error
04-01 10:47:08.685  3526  4072 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
04-01 10:47:08.685  3526  4072 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,04-01 10:47:08.685  3526  4072 I BooksSync: Finished books sync
,04-01 10:47:08.705   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1264525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:47:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:47:29.927  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:47:43.461  3422  4081 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,04-01 10:47:43.572  1492  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
04-01 10:47:43.573  1492  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:47:43.574  1492  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:47:43.574  1492  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:47:43.578  1492  3841 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
04-01 10:47:43.592  3422  4081 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,04-01 10:48:08.534  3488  4086 V KeepSync: Connecting to GoogleApiClient
,04-01 10:48:08.636  1492  2556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,04-01 10:48:08.636  1492  2556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:48:08.636  1492  2556 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:48:08.637  1492  2556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:48:08.645  1492  2556 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: Handling authorization failure
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
04-01 10:48:08.679  1806  4087 E ClientConnectionOperation: 	... 7 more
,04-01 10:48:08.685  3488  4086 V KeepSync: GoogleApiClient failed to connect with error code: 4
,04-01 10:48:08.693  3488  4086 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:48:08.707  3488  4086 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
04-01 10:48:08.707  3488  4086 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,04-01 10:48:08.822  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
04-01 10:48:08.822  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,04-01 10:48:08.825  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
,04-01 10:48:08.825  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:48:08.837  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:48:08.917  3488  4086 E KeepSync: IOException
04-01 10:48:08.917  3488  4086 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
04-01 10:48:08.917  3488  4086 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
04-01 10:48:08.917  3488  4086 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
04-01 10:48:08.917  3488  4086 E KeepSync: 	... 10 more
,04-01 10:48:08.917  3488  4086 W KeepSync: Sync result 2
,04-01 10:48:08.929   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1296593, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,04-01 10:48:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:48:30.087  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:49:30.245  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:51:43.382  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:51:43.471  1492  1512 I art     : Explicit concurrent mark sweep GC freed 71582(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.940ms total 58.918ms
,04-01 10:51:43.494  1492  1679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,04-01 10:51:43.494  1492  1679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
04-01 10:51:43.494  1492  1679 I GLSUser : [GLSUser] Extracting token using key: Auth
04-01 10:51:43.494  1492  1679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,04-01 10:51:43.499  1492  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:51:43.513  1806  4126 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,04-01 10:52:10.902  2157  2221 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
