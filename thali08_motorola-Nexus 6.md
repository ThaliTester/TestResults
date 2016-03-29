#### Test 63998117d1f6a2b_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-29 13:29:31.972  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-29 13:29:32.019  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 13:29:32.020  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:32.020  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:32.020  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-29 13:29:32.026  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-29 13:29:32.052  2748  2748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-29 13:29:32.052  2748  2748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 13:29:32.053  2748  2748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-29 13:29:32.859  3297  3297 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 13:29:32.863  3297  3297 D AndroidRuntime: CheckJNI is OFF
03-29 13:29:33.016  3297  3297 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-29 13:29:33.020   821  1319 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-29 13:29:33.052   821  1319 V WindowManager: addAppToken: AppWindowToken{3ab87564 token=Token{844c2f7 ActivityRecord{25104ef6 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-29 13:29:33.057  3297  3297 D AndroidRuntime: Shutting down VM
03-29 13:29:33.072  1536  1536 I HotwordDetector: Closing mic
03-29 13:29:33.072  1536  1744 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@81e527f
03-29 13:29:33.074   821   860 V WindowManager: Adding window Window{c0b19ef u0 Starting com.test.thalitest} at 2 of 7 (after Window{2c6fcc58 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-29 13:29:33.136   359  1755 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-29 13:29:33.139   821   836 I ActivityManager: Start proc 3311:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-29 13:29:33.140   359  1755 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-29 13:29:33.154   359  1021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-29 13:29:33.157  1536  1747 I HotwordRecognitionRnr: Stopping hotword detection.
03-29 13:29:33.157  1536  1749 I HotwordRecognitionRnr: Hotword detection finished
03-29 13:29:33.179   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 328us total 31.753ms
03-29 13:29:33.197   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 355us total 15.621ms
03-29 13:29:33.209   821  1403 I ActivityManager: Killing 2878:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-29 13:29:33.217   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 313us total 16.274ms
03-29 13:29:33.262   821  1403 I ActivityManager: Killing 2707:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-29 13:29:33.456  3311  3311 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-29 13:29:33.470   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658385683
,03-29 13:29:33.470   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-29 13:29:33.475  3311  3311 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2370-2374)
,03-29 13:29:33.475  3311  3311 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 13:29:33.507  3311  3311 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c4b4596}
,03-29 13:29:33.508  3311  3311 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-29 13:29:33.509  3311  3311 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-29 13:29:33.530  3311  3311 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-29 13:29:33.531  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
03-29 13:29:33.532  3311  3311 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 13:29:33.541  3311  3338 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-29 13:29:33.548  3311  3311 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-29 13:29:33.555   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-29 13:29:33.555  3311  3311 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 13:29:33.555  3311  3311 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 13:29:33.555   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock
03-29 13:29:33.555  3311  3311 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 13:29:33.596   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-29 13:29:33.597   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-29 13:29:33.687   821   859 D BluetoothManagerService: Message: 20
,03-29 13:29:33.691   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2719ad2c:true
,03-29 13:29:33.735  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 13:29:33.743  3311  3311 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-29 13:29:33.757  3311  3311 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola,
03-29 13:29:33.763  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 13:29:33.763  3311  3311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 13:29:33.799   821   862 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-29 13:29:33.822  3311  3360 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 13:29:33.834  3311  3311 D Atlas   : Validating map...
,03-29 13:29:33.836   821   862 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 13:29:33.854   821  1319 V WindowManager: Adding window Window{2878b95c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{c0b19ef u0 Starting com.test.thalitest})
03-29 13:29:33.856  3311  3347 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-29 13:29:33.862   270  1027 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
,03-29 13:29:33.944   821  1320 I art     : Explicit concurrent mark sweep GC freed 43603(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.948ms total 71.427ms
,03-29 13:29:33.972  3311  3360 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 13:29:33.980  3311  3360 D OpenGLRenderer: Enabling debug mode 0
,03-29 13:29:34.089   821   860 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s12ms
,03-29 13:29:34.094  1226  1226 I Keyboard.Facilitator: onFinishInput()
,03-29 13:29:34.100  3311  3311 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3311
,03-29 13:29:34.219  3311  3311 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 13:29:34.347  3311  3364 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576333056
,03-29 13:29:34.355  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 13:29:34.355  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 13:29:34.355  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 13:29:34.355  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 13:29:34.355  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-29 13:29:34.355  3311  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c2faf93 added. We now have 1 listener(s)
03-29 13:29:34.355   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:29:34.362  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-29 13:29:34.362  3311  3364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-29 13:29:34.364  3311  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 13:29:34.364  3311  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 13:29:34.368  3311  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14723ece added. We now have 1 listener(s)
03-29 13:29:34.368  3311  3364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 13:29:34.372   821  1033 D WifiService: New client listening to asynchronous messages
,03-29 13:29:34.374  3311  3364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-29 13:29:34.375  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-29 13:29:34.375  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-29 13:29:34.376  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-29 13:29:34.376  3311  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-29 13:29:34.378  3311  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:29:34.379   821  1319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:29:34.380  3311  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-29 13:29:34.384  3311  3364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-29 13:29:34.384  3311  3364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-29 13:29:34.384  3311  3364 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-29 13:29:34.385  3311  3364 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 13:29:34.386  3311  3311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 13:29:34.418  3311  3311 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 13:29:34.431   821   860 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-29 13:29:34.432   270   270 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-29 13:29:34.432   270   270 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-29 13:29:34.435   821   821 V ActivityManager: Display changed displayId=0
,03-29 13:29:34.578   871   871 I kickstart: STATUS: Received file 'm9kefs2'
03-29 13:29:34.578   871   871 I kickstart: STATUS: 950272 bytes transferred in 0.981319 seconds
03-29 13:29:34.578   871   871 I kickstart: STATUS: Successfully downloaded files from target 
,03-29 13:29:34.579   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-29 13:29:34.582   871   871 I kickstart: STATUS: Sahara protocol completed
,03-29 13:29:34.676   270   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-29 13:29:34.678   270   270 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-29 13:29:34.687   821  1054 D SurfaceControl: Excessive delay in setPowerMode(): 255ms
,03-29 13:29:34.692   821   862 I DreamManagerService: Entering dreamland.
03-29 13:29:34.693   821   862 I PowerManagerService: Dozing...
03-29 13:29:34.694   821   857 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-29 13:29:34.699   359   359 D audio_hw_primary: adev_set_parameters: enter: screen_state=on,
03-29 13:29:34.699   359   359 D mot_vr_audio_hw: adev_set_parameters: screen_state=on,
,03-29 13:29:34.713   821  1032 E WifiStateMachine: cancelDelayedScan -> 16
,03-29 13:29:34.735   821  1032 E native  : do suspend false
,03-29 13:29:34.752  1226  1226 I Keyboard.Facilitator: onFinishInput()
,03-29 13:29:34.761   821  1032 E WifiStateMachine: cancelDelayedScan -> 18
,03-29 13:29:34.813   821  1032 E native  : do suspend true
,03-29 13:29:34.861   359  1439 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-29 13:29:34.861   359  1439 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-29 13:29:34.919   821  1032 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-29 13:29:35.063  3311  3373 W jxcore-log: Initializing JXcore engine
,03-29 13:29:35.063  3311  3373 W jxcore-log: JXcore engine is ready
,03-29 13:29:35.092  3373  3373 W Thread-354: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9737]" dev="sockfs" ino=9737 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-29 13:29:35.092  3373  3373 W Thread-354: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-29 13:29:35.092  3373  3373 W Thread-354: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9917]" dev="sockfs" ino=9917 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-29 13:29:35.092  3373  3373 W Thread-354: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21219]" dev="sockfs" ino=21219 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-29 13:29:35.113  3311  3373 W jxcore-log: Starting JXcore engine
,03-29 13:29:35.194  3311  3373 W jxcore-log: Platform android
03-29 13:29:35.194  3311  3373 W jxcore-log: 
03-29 13:29:35.194  3311  3373 W jxcore-log: Process ARCH arm
03-29 13:29:35.194  3311  3373 W jxcore-log: 
,03-29 13:29:35.386   821  1032 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-29 13:29:35.391  3311  3373 I jxcore-log: JXcore Cordova bridge is ready!
03-29 13:29:35.391  3311  3373 I jxcore-log: 
03-29 13:29:35.391  3311  3373 W jxcore-log: JXcore engine is started
,03-29 13:29:35.404  3311  3364 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-29 13:29:35.408  3311  3311 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 13:29:36.406  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 13:29:37.177  1053  1053 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-29 13:29:37.599  1053  1053 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-29 13:29:37.642  1053  1053 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
03-29 13:29:37.643  1053  1053 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-29 13:29:37.669   821  1032 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
,03-29 13:29:37.671   821  1032 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-29 13:29:37.671   821  1034 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-29 13:29:37.679   821  1032 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-29 13:29:37.689   355   815 D CommandListener: Setting iface cfg
,03-29 13:29:37.698   821  1032 E WifiStateMachine: Start Dhcp Watchdog 1
,03-29 13:29:37.703   821  1032 E WifiStateMachine:  WifiLinkLayerStats: 
03-29 13:29:37.703   821  1032 E WifiStateMachine:  my bss beacon rx: 2
03-29 13:29:37.703   821  1032 E WifiStateMachine:  RSSI mgmt: -43
03-29 13:29:37.703   821  1032 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-29 13:29:37.703   821  1032 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-29 13:29:37.703   821  1032 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-29 13:29:37.703   821  1032 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-29 13:29:37.703   821  1032 E WifiStateMachine:  on_time : 0 tx_time=64 rx_time=105 scan_time=0
,03-29 13:29:37.809   821  1032 E native  : do suspend false
,03-29 13:29:37.823   821  1032 E WifiStateMachine: scanCount==0 - aborting
,03-29 13:29:38.070  3379  3379 I dhcpcd  : version 5.5.6 starting
,03-29 13:29:38.212  3379  3379 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-29 13:29:38.269  3379  3379 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-29 13:29:38.300  3379  3379 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-29 13:29:38.644   821  1032 E native  : do suspend true
,03-29 13:29:38.687   821  1034 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,03-29 13:29:38.691   821  1034 D ConnectivityService: Adding iface wlan0 to network 100
,03-29 13:29:38.698   821  1032 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-29 13:29:38.713   821  1034 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-29 13:29:38.713   821  1034 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
03-29 13:29:38.714   821  1034 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-29 13:29:38.715   821  1034 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-29 13:29:38.716   821  1034 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-29 13:29:38.736   821  1034 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-29 13:29:38.739   821  1034 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-29 13:29:38.740   821  3377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,03-29 13:29:38.740   821  3377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-29 13:29:38.740   821  3377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-29 13:29:38.740   821  3377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-29 13:29:38.742   821  1034 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-29 13:29:38.742   821  1034 D ConnectivityService:    accepting network in place of null
,03-29 13:29:38.744   821  1034 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-29 13:29:38.745   821  1034 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-29 13:29:38.748   821  1034 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-29 13:29:38.749  1073  1472 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 13:29:38.749   821  1034 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-29 13:29:38.749   821  1034 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-29 13:29:38.750   821  1034 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-29 13:29:38.753   821   859 D Tethering: MasterInitialState.processMessage what=3
03-29 13:29:38.756  2936  2936 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-29 13:29:38.759   821  1406 V BackupManagerService: Scheduling immediate backup pass
03-29 13:29:38.762   821   821 V BackupManagerService: Running a backup pass
,03-29 13:29:38.765  1536  1536 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:29:38.767  3311  3311 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 13:29:38.767  3311  3311 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-29 13:29:38.769  1301  1329 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,03-29 13:29:38.769  1301  1329 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-29 13:29:38.772  2936  2936 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,03-29 13:29:38.773   821  1052 V BackupManagerService: clearing pending backups
03-29 13:29:38.774   821   854 D TelephonyManager: getDataEnabled: retVal=false
,03-29 13:29:38.781   821  1052 V PerformBackupTask: Beginning backup of 14 targets
,03-29 13:29:38.785   821  1052 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-29 13:29:38.787   821  1052 V BackupServiceBinder: doBackup() invoked
,03-29 13:29:38.789   821  1052 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-29 13:29:38.799   821  1052 I BackupRestoreController: Getting widget state for user: 0
,03-29 13:29:38.824   821  1320 I ActivityManager: Start proc 3419:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-29 13:29:38.827   821   854 E GpsLocationProvider: No APN found to select.
,03-29 13:29:38.869  1722  1737 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-29 13:29:38.871  1722  1737 V GmsBackupTransport: starting performBackup for @pm@
,03-29 13:29:38.876  1722  1737 V GmsBackupTransport: performBackup done for @pm@
,03-29 13:29:38.885  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:38.900   821  1252 D AlarmManagerService: Setting time of day to sec=1459250979
03-29 13:29:39.534   821  1252 W AlarmManagerService: Unable to set rtc to 1459250979: Invalid argument
03-29 13:29:39.534   821  3438 D GpsLocationProvider: NTP server returned: 1459250979527 (Tue Mar 29 13:29:39 GMT+02:00 2016) reference: 167799 certainty: 20 system time offset: -7
,03-29 13:29:39.546  1567  2139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,03-29 13:29:39.546  1567  2139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:39.546  1567  2139 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:39.546  1567  2139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:39.557  1567  2139 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:39.590  1567  2139 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 13:29:39.590  1567  2139 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 13:29:39.590  1567  2139 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 13:29:39.590  1567  2139 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-29 13:29:39.590  1567  2139 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-29 13:29:39.590  1567  2139 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-29 13:29:39.590  1567  2139 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-29 13:29:39.616  1722  1821 W GmsBackupTransport: Error sending final backup to server: 
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-29 13:29:39.616  1722  1821 W GmsBackupTransport: 	... 1 more
,03-29 13:29:39.617   821  1052 D BackupManagerService: Now staging backup of com.google.android.talk
03-29 13:29:39.640   821  1052 D BackupManagerService: Now staging backup of com.google.android.dialer
03-29 13:29:39.643   821  1319 I ActivityManager: Start proc 3453:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
03-29 13:29:39.647  1757  3441 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
03-29 13:29:39.650   821  1052 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-29 13:29:39.655   821  3377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 29 Mar 2016 11:29:39 GMT], X-Android-Received-Millis=[1459250979655], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459250979605]}
03-29 13:29:39.656   821  3377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-29 13:29:39.656   821  1034 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-29 13:29:39.656   821  1034 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-29 13:29:39.656   821  1034 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-29 13:29:39.656   821  1034 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-29 13:29:39.656   821  1034 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-29 13:29:39.657   821  1034 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-29 13:29:39.657  1073  1472 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 13:29:39.658   821  1052 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-29 13:29:39.663   821  1052 D BackupManagerService: Now staging backup of com.google.android.gm
,03-29 13:29:39.675   821  1052 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-29 13:29:39.677   821  1052 D BackupManagerService: Now staging backup of com.android.nfc
,03-29 13:29:39.678   821  1052 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-29 13:29:39.682   821  1052 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
03-29 13:29:39.683   821  1052 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-29 13:29:39.685   821  1052 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-29 13:29:39.687   821  1052 D BackupManagerService: Now staging backup of com.android.vending
,03-29 13:29:39.688   821  1052 D BackupManagerService: Now staging backup of android
,03-29 13:29:39.690   821  1052 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-29 13:29:39.691  3453  3453 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-29 13:29:39.695  1722  1737 I GmsBackupTransport: Next backup will happen in 43199905 millis.
,03-29 13:29:39.708  3453  3453 D SprintDMHelper: simOperator:  IMSI: null
03-29 13:29:39.708  3453  3453 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-29 13:29:39.710   821  1052 I BackupManagerService: Backup pass finished.
,03-29 13:29:39.715  1757  3473 W DriveInitializer: Background init thread started
,03-29 13:29:39.718  1757  1757 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-29 13:29:39.723  1757  1757 D SystemUpdateService: onCreate
,03-29 13:29:39.726  1757  1757 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-29 13:29:39.731  1757  3474 W DriveInitializer: Awaiting to be initialized
,03-29 13:29:39.752  1757  3476 I SystemUpdateService: active receiver: enabled
,03-29 13:29:39.779  1757  3476 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-29 13:29:39.785  1757  3485 I iu.SyncManager: SYNC; picasa accounts
,03-29 13:29:39.788  1757  3476 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-29 13:29:39.788  1757  3476 I SystemUpdateService: now status is 0 (complete)
03-29 13:29:39.788  1757  3476 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-29 13:29:39.788  1757  3476 I SystemUpdateService: file has been verified
03-29 13:29:39.788  1757  3476 I SystemUpdateService: OTA package size = 25802302
,03-29 13:29:39.791  1757  3476 I SystemUpdateService: showing system update notification
,03-29 13:29:39.795  1757  1757 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-29 13:29:39.797  1757  1757 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-29 13:29:39.798   821   821 I ValidateNoPeople: skipping global notification
,03-29 13:29:39.810  1757  3485 I iu.UploadsManager: num queued entries: 0
,03-29 13:29:39.811  1757  3485 I iu.UploadsManager: num updated entries: 0
,03-29 13:29:39.812  1757  3485 I iu.SyncManager: NEXT; no task
,03-29 13:29:39.820  1757  1757 D SystemUpdateService: onDestroy
,03-29 13:29:39.824  1757  1757 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-29 13:29:39.826  1757  1757 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-29 13:29:39.859   821  1469 I ActivityManager: Start proc 3490:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-29 13:29:39.885  1567  1589 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 13:29:39.885  1567  1589 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:39.885  1567  1589 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:39.885  1567  1589 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:39.888  1567  1589 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:39.893  1757  3473 W DriveInitializer: Background init thread ended
,03-29 13:29:39.902  3114  3470 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 13:29:39.902  3114  3470 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jdm.a(PG:82)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jcs.o(PG:406)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jcn.a(PG:1379)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jcs.i(PG:143)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at blb.a(PG:3937)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at czp.a(PG:18188)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at czp.a(PG:9081)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at czq.run(PG:1686)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:29:39.902  3114  3470 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jdj.a(PG:4091)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jdj.a(PG:1125)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jdm.a(PG:77)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	... 12 more
03-29 13:29:39.902  3114  3470 E HttpOperation: Caused by: faj: BadAuthentication
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at fal.a(PG:38)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	at jdj.a(PG:4089)
03-29 13:29:39.902  3114  3470 E HttpOperation: 	... 14 more
,03-29 13:29:39.955  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 13:29:39.955  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:39.955  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:39.955  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:39.958  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:39.985  1567  1567 I art     : Explicit concurrent mark sweep GC freed 18515(1052KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 683us total 20.888ms
,03-29 13:29:39.992   821   854 I ActivityManager: Start proc 3518:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-29 13:29:39.999  3114  3470 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 13:29:39.999  3114  3470 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jdm.a(PG:82)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jcs.o(PG:406)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jcn.a(PG:1379)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jcs.i(PG:143)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at hec.a(PG:42)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at hee.a(PG:102)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at czr.a(PG:65)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at kka.a(PG:108)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at czp.a(PG:19176)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at czp.a(PG:9081)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at czq.run(PG:1686)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:29:39.999  3114  3470 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jdj.a(PG:4091)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jdj.a(PG:1125)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jdm.a(PG:77)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	... 15 more
03-29 13:29:39.999  3114  3470 E HttpOperation: Caused by: faj: BadAuthentication
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at fal.a(PG:38)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	at jdj.a(PG:4089)
03-29 13:29:39.999  3114  3470 E HttpOperation: 	... 17 more
03-29 13:29:39.999  3114  3470 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 13:29:39.999  3114  3470 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at hec.a(PG:42)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at hee.a(PG:102)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at czr.a(PG:65)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at kka.a(PG:108)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	... 15 more
03-29 13:29:39.999  3114  3470 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at fal.a(PG:38)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 13:29:39.999  3114  3470 E ExperimentLoader: 	... 17 more
03-29 13:29:40.032  3490  3490 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-29 13:29:40.032  3490  3490 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 13:29:40.032  3490  3490 I GAv4    :   adb logcat -s GAv4
,03-29 13:29:40.066  3181  3487 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-29 13:29:40.070  3490  3490 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:29:40.074   821  1403 I ActivityManager: Killing 2913:com.android.settings/1000 (adj 15): empty #17
,03-29 13:29:40.139  3490  3490 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:29:40.143  3490  3544 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:29:40.199   821  1403 I ActivityManager: Killing 2441:com.google.android.apps.maps/u0a65 (adj 15): empty #17
03-29 13:29:40.199   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37582, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 13:29:40.218  1567  3540 D GCM     : Connected
,03-29 13:29:40.436  1567  3540 D GCM     : Message class com.google.f.a.a.p
,03-29 13:29:40.470   821   854 I ActivityManager: Start proc 3546:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-29 13:29:40.617  3490  3490 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-29 13:29:40.626  3490  3490 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8891-8892)
03-29 13:29:40.626  3490  3490 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-29 13:29:40.630  3490  3490 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {203eabf5}
03-29 13:29:40.631  3490  3490 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-29 13:29:40.631  3490  3490 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-29 13:29:40.638  3518  3578 V KeepSync: Connecting to GoogleApiClient
03-29 13:29:40.639  3490  3490 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-29 13:29:40.639  3490  3490 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 13:29:40.641  3490  3490 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-29 13:29:40.654  3490  3490 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-29 13:29:40.659  3490  3490 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 13:29:40.659  3490  3490 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-29 13:29:40.659  3490  3490 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-29 13:29:40.715  3490  3593 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-29 13:29:40.723   821  1403 I art     : Explicit concurrent mark sweep GC freed 54705(2MB) AllocSpace objects, 7(151KB) LOS objects, 32% free, 33MB/49MB, paused 1.057ms total 73.711ms
,03-29 13:29:40.742  3490  3490 I NSApplication: Starting up...
,03-29 13:29:40.768   821  1319 I ActivityManager: Start proc 3599:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-29 13:29:40.809  1757  3609 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 13:29:40.813  1757  3609 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 13:29:40.834  1567  2581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-29 13:29:40.835  1567  2581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:40.835  1567  2581 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:40.835  1567  2581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:40.838  1567  2581 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: Handling authorization failure
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 13:29:40.850  1757  3609 E ClientConnectionOperation: 	... 7 more
,03-29 13:29:40.853  3518  3578 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 13:29:40.861  3518  3578 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 13:29:40.865  3518  3578 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 13:29:40.865  3518  3578 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 13:29:40.975  1567  1589 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 13:29:40.975  1567  1589 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 13:29:40.975  1567  1589 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:40.975  1567  1589 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:40.978  1567  1589 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:41.013  3546  3546 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-29 13:29:41.021  3546  3546 I BooksApp: Created application version: 3.6.8 (30608)
,03-29 13:29:41.027  3518  3578 E KeepSync: IOException
03-29 13:29:41.027  3518  3578 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 13:29:41.027  3518  3578 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 13:29:41.027  3518  3578 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 13:29:41.027  3518  3578 E KeepSync: 	... 10 more
03-29 13:29:41.027  3518  3578 W KeepSync: Sync result 2
,03-29 13:29:41.033   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37594, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 13:29:41.034   821  1320 I ActivityManager: Killing 3023:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-29 13:29:41.238   821  1104 I ActivityManager: Start proc 3634:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-29 13:29:41.239   821  1104 I ActivityManager: Killing 3043:com.android.musicfx/u0a18 (adj 15): empty #17
,03-29 13:29:41.381  3546  3629 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 13:29:41.535  3546  3655 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 13:29:41.635  1567  2581 I art     : Explicit concurrent mark sweep GC freed 10505(551KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 831us total 29.166ms
,03-29 13:29:41.646  1567  1714 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-29 13:29:41.646  1567  1714 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:41.646  1567  1714 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:41.647  1567  1714 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:41.650  1567  1714 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:41.698  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 13:29:41.698  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:41.698  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:41.698  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:41.701  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:41.710  3546  3655 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 13:29:41.711  3546  3629 E BooksSync: Soft error
03-29 13:29:41.711  3546  3629 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 13:29:41.711  3546  3629 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-29 13:29:41.711  3546  3629 E BooksSync: Sync error
03-29 13:29:41.711  3546  3629 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 13:29:41.711  3546  3629 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 13:29:41.711  3546  3629 I BooksSync: Finished books sync
,03-29 13:29:41.716   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37595, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
03-29 13:29:41.716   821  1406 I ActivityManager: Killing 3003:android.process.acore/u0a5 (adj 15): empty #17
,03-29 13:29:41.822   821  1406 I ActivityManager: Killing 3072:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,03-29 13:29:42.034   821  1469 I ActivityManager: Killing 2810:com.google.android.gm/u0a78 (adj 15): empty #17
,03-29 13:29:42.351   821  1366 I ActivityManager: Start proc 3657:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-29 13:29:42.415  3657  3657 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459250982415
03-29 13:29:42.415  3657  3657 D         : TimeServiceNative: User Time to be set is 1459250982415
03-29 13:29:42.415  3657  3657 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-29 13:29:42.415  3657  3657 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-29 13:29:42.415  3657  3657 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459250982415
03-29 13:29:42.416  3657  3657 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-29 13:29:42.416   374   879 D QC-time-services: Daemon: Connection accepted:time_genoff
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459250982415
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459250982415, operation = 0
,03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/15/70 7:41:22
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:Value read from RTC seconds = 19554082000
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:new time 1459250982415 
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon: delta 1439696900415 genoff 1439696900415 
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696900415 to memory
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-29 13:29:42.416   374  3674 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-29 13:29:42.419   374  3674 D QC-time-services: Updating the TOD offset,
03-29 13:29:42.419   374  3674 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696900415 to memory
03-29 13:29:42.419   374  3674 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-29 13:29:42.419   374  3674 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-29 13:29:42.421   374  3674 E QC-time-services: Daemon:Update to modem bit set
03-29 13:29:42.421  3657  3657 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-29 13:29:42.421   374  3674 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-29 13:29:42.421   374  3674 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143286182415
,03-29 13:29:42.491   374   879 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-29 13:29:42.497   374   877 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-29 13:29:42.562   821  1469 I ActivityManager: Start proc 3676:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-29 13:29:42.576   821  1319 I ActivityManager: Killing 3163:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-29 13:29:42.821  3676  3676 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-29 13:29:42.821  3676  3676 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 13:29:42.821  3676  3676 I GAv4    :   adb logcat -s GAv4
,03-29 13:29:42.837  3676  3676 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:29:42.849  3676  3676 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:29:42.878  3676  3695 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:29:42.902   821  1104 I ActivityManager: Killing 3142:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-29 13:29:43.115  1757  1757 V Herrevad: NQAS connected
,03-29 13:29:43.135  3181  3181 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 13:29:43.135  3181  3181 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 13:29:43.163   821  1469 I ActivityManager: Start proc 3703:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-29 13:29:43.174  1757  3700 I art     : Explicit concurrent mark sweep GC freed 16943(1241KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 998us total 36.228ms
,03-29 13:29:43.241   821  1319 I art     : Explicit concurrent mark sweep GC freed 21549(965KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 5.524ms total 59.838ms
,03-29 13:29:43.242   821  1033 D WifiService: New client listening to asynchronous messages
,03-29 13:29:43.264  3703  3703 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-29 13:29:43.310  3703  3703 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2c70ccb1(com.android.providers.calendar.CalendarProvider2@c4b4596)
,03-29 13:29:43.362  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-29 13:29:43.362  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:43.362  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:43.362  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:43.365  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:43.377  3181  3722 E Babel   : UserRecoverableAuthException.
,03-29 13:29:43.377  3181  3722 E Babel   : eei: BadAuthentication
03-29 13:29:43.377  3181  3722 E Babel   : 	at eeg.a(Unknown Source)
03-29 13:29:43.377  3181  3722 E Babel   : 	at eeg.a(Unknown Source)
03-29 13:29:43.377  3181  3722 E Babel   : 	at eeg.a(Unknown Source)
03-29 13:29:43.377  3181  3722 E Babel   : 	at g.a(Unknown Source)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cae.a(SourceFile:3089)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cae.a(SourceFile:1131)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cws.a(SourceFile:4333)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cws.a(SourceFile:1419)
03-29 13:29:43.377  3181  3722 E Babel   : 	at crl.a(SourceFile:492)
03-29 13:29:43.377  3181  3722 E Babel   : 	at crl.a(SourceFile:1468)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cas.b(SourceFile:106)
03-29 13:29:43.377  3181  3722 E Babel   : 	at cap.d(SourceFile:335)
03-29 13:29:43.377  3181  3722 E Babel   : 	at caq.run(SourceFile:81)
03-29 13:29:43.378  3181  3722 E Babel   : Error getting auth token
03-29 13:29:43.378  3181  3722 E Babel   : dvm
03-29 13:29:43.378  3181  3722 E Babel   : 	at g.a(Unknown Source)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cae.a(SourceFile:3089)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cae.a(SourceFile:1131)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cws.a(SourceFile:4333)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cws.a(SourceFile:1419)
03-29 13:29:43.378  3181  3722 E Babel   : 	at crl.a(SourceFile:492)
03-29 13:29:43.378  3181  3722 E Babel   : 	at crl.a(SourceFile:1468)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cas.b(SourceFile:106)
03-29 13:29:43.378  3181  3722 E Babel   : 	at cap.d(SourceFile:335)
03-29 13:29:43.378  3181  3722 E Babel   : 	at caq.run(SourceFile:81)
,03-29 13:29:43.381  3181  3722 E Babel   : Account registration failed 1-Redacted-21
,03-29 13:29:43.381  3181  3722 E Babel   : cyp: null -- null
03-29 13:29:43.381  3181  3722 E Babel   : 	at cae.a(SourceFile:3121)
03-29 13:29:43.381  3181  3722 E Babel   : 	at cae.a(SourceFile:1131)
03-29 13:29:43.381  3181  3722 E Babel   : 	at cws.a(SourceFile:4333)
03-29 13:29:43.381  3181  3722 E Babel   : 	at cws.a(SourceFile:1419)
03-29 13:29:43.381  3181  3722 E Babel   : 	at crl.a(SourceFile:492)
03-29 13:29:43.381  3181  3722 E Babel   : 	at crl.a(SourceFile:1468)
03-29 13:29:43.381  3181  3722 E Babel   : 	at cqu.a(SourceFile:4416)
03-29 13:29:43.381  3181  3722 E Babel   : 	at cas.b(SourceFile:106)
03-29 13:29:43.381  3181  3722 E Babel   : 	at cap.d(SourceFile:335)
03-29 13:29:43.381  3181  3722 E Babel   : 	at caq.run(SourceFile:81)
,03-29 13:29:43.390  3181  3722 I art     : Note: end time exceeds epoch: 
,03-29 13:29:43.403  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-29 13:29:43.403  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:43.403  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:43.403  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:43.406  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:43.419  1567  1593 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-29 13:29:43.433  3181  3732 E Babel   : Unexpected exception while authenticating.
,03-29 13:29:43.433  3181  3732 E Babel   : eej: User intervention required. Notification has been pushed.
03-29 13:29:43.433  3181  3732 E Babel   : 	at eeg.b(Unknown Source)
03-29 13:29:43.433  3181  3732 E Babel   : 	at eeg.b(Unknown Source)
03-29 13:29:43.433  3181  3732 E Babel   : 	at g.a(Unknown Source)
03-29 13:29:43.433  3181  3732 E Babel   : 	at cae.b(SourceFile:1146)
03-29 13:29:43.433  3181  3732 E Babel   : 	at dcg.run(SourceFile:5617)
03-29 13:29:43.433  3181  3732 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:29:43.433  3181  3732 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:29:43.433  3181  3732 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:29:44.365  3703  3703 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-29 13:29:44.365  3703  3703 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-29 13:29:44.415  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:44.488  1567  3740 I VacuumService: Vacuum at: now=1459250984488 tag=VacuumService
,03-29 13:29:44.562  1567  3742 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-29 13:29:44.565  3703  3743 E SQLiteLog: (284) automatic index on view_events(_id)
,03-29 13:29:44.572  1567  3742 W Uploader: No account for auth token provided
03-29 13:29:44.572  3419  3739 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 13:29:44.595  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 13:29:44.595  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 13:29:44.595  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:44.595  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:44.598  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 13:29:44.606  3419  3739 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 13:29:45.181  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:45.359  1567  3742 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 13:29:45.359  1567  3742 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:45.359  1567  3742 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 13:29:45.359  1567  3742 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-29 13:29:45.366  1567  3742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:45.447  1567  3742 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 13:29:45.447  1567  3742 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 13:29:45.447  1567  3742 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 13:29:45.837  1567  3742 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-29 13:29:45.837  1567  3742 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-29 13:29:45.837  1567  3742 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:45.837  1567  3742 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:45.845  1567  3742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:29:45.894  1567  3742 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 13:29:45.894  1567  3742 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 13:29:45.894  1567  3742 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 13:29:45.946  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:29:45.946  3311  3373 I jxcore-log: 
,03-29 13:29:45.948  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:29:45.948  3311  3373 I jxcore-log: 
,03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-29 13:29:45.953  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:29:45.956  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:29:45.958  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:29:45.958  3311  3373 I jxcore-log: 
,03-29 13:29:45.959  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:29:45.959  3311  3373 I jxcore-log: 
,03-29 13:29:46.038  3546  3623 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-29 13:29:46.049  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:46.230  1567  3742 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 13:29:46.230  1567  3742 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:46.230  1567  3742 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:46.230  1567  3742 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:46.242  1567  3742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:46.310  1567  3742 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 13:29:46.310  1567  3742 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 13:29:46.310  1567  3742 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 13:29:46.500  3311  3373 I jxcore-log: Unit Test app is loaded,
03-29 13:29:46.500  3311  3373 I jxcore-log: ,
,03-29 13:29:46.509  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:29:46.509  3311  3373 I jxcore-log: 
,03-29 13:29:46.514  3311  3311 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-29 13:29:46.519  3311  3373 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-29 13:29:46.521  3311  3373 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-29 13:29:46.521  3311  3373 I jxcore-log: 
03-29 13:29:46.522  3311  3373 I jxcore-log: My device name is: motorola-Nexus 6
03-29 13:29:46.522  3311  3373 I jxcore-log: 
,03-29 13:29:46.658  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:46.816  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:46.929  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:47.110  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:47.222  1567  3742 W Uploader:  no longer exists, so no auth token.
,03-29 13:29:47.408  1567  3742 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 13:29:47.408  1567  3742 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:47.409  1567  3742 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:47.409  1567  3742 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:47.419  1567  3742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:29:47.496  1567  3742 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-29 13:29:47.496  1567  3742 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-29 13:29:47.496  1567  3742 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 13:29:47.637  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:47.756  1567  3742 W Uploader: No account for auth token provided
,03-29 13:29:47.983  1567  3742 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-29 13:29:47.983  1567  3742 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:47.983  1567  3742 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:47.984  1567  3742 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:47.996  1567  3742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:29:48.062  1567  3742 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-29 13:29:48.062  1567  3742 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,03-29 13:29:48.062  1567  3742 E Uploader: 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
,03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599),
03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-29 13:29:48.062  1567  3742 E Uploader: 	,at com.google.android.gms.auth.p.b(SourceFile:477)
03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
,03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-29 13:29:48.062  1567  3742 E Uploader: 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-29 13:29:48.062  1567  3742 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,03-29 13:29:48.062  1567  3742 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-29 13:29:49.596   821  1403 I ActivityManager: Killing 2748:com.android.vending/u0a19 (adj 15): empty #17
,03-29 13:29:50.410  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-29 13:29:50.410  3311  3373 I jxcore-log: 
,03-29 13:29:50.750  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
03-29 13:29:50.750  3311  3373 I jxcore-log: 
,03-29 13:29:50.763  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-29 13:29:50.763  3311  3373 I jxcore-log: 
,03-29 13:29:50.768  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-29 13:29:50.768  3311  3373 I jxcore-log: 
,03-29 13:29:50.805  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-29 13:29:50.805  3311  3373 I jxcore-log: 
,03-29 13:29:50.822  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-29 13:29:50.822  3311  3373 I jxcore-log: 
,03-29 13:29:50.826  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-29 13:29:50.826  3311  3373 I jxcore-log: 
,03-29 13:29:51.136   821  1319 I ActivityManager: Start proc 3748:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-29 13:29:51.152   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 335us total 15.505ms
,03-29 13:29:51.167   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 332us total 14.872ms
,03-29 13:29:51.181   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 239us total 12.860ms
,03-29 13:29:51.268  1567  1714 I art     : Explicit concurrent mark sweep GC freed 54397(3MB) AllocSpace objects, 6(421KB) LOS objects, 36% free, 27MB/43MB, paused 1.944ms total 54.580ms
,03-29 13:29:51.324  3748  3748 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-29 13:29:51.385  3748  3748 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-29 13:29:51.471   821  1104 I ActivityManager: Start proc 3784:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-29 13:29:51.490  3748  3748 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-29 13:29:51.490  3748  3748 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-29 13:29:51.521  3784  3784 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 13:29:51.521  3784  3784 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 13:29:51.539   821  1403 I ActivityManager: Killing 2936:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-29 13:29:51.544  3748  3763 D Finsky  : [384] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-29 13:29:51.554  3784  3784 I MultiDex: VM with version 2.1.0 has multidex support
03-29 13:29:51.554  3784  3784 I MultiDex: install
03-29 13:29:51.554  3784  3784 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 13:29:51.656  3748  3748 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-29 13:29:51.657  3748  3748 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-29 13:29:51.676  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:51.687  3748  3748 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-29 13:29:51.692  3784  3784 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 13:29:51.734  3784  3784 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 13:29:51.746   821  1320 I art     : Explicit concurrent mark sweep GC freed 20608(984KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.235ms total 58.436ms
,03-29 13:29:51.757  1567  2113 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-29 13:29:51.760  1567  1567 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-29 13:29:51.766  3748  3748 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-29 13:29:51.768  1757  1757 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-29 13:29:51.772  1567  1589 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 13:29:51.772  1567  1589 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:51.772  1567  1589 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:51.772  1567  1589 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:51.776  1567  1589 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:51.800   821  1403 I ActivityManager: Start proc 3812:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-29 13:29:51.810  3748  3763 D Finsky  : [384] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-29 13:29:51.825  3812  3812 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-29 13:29:51.825  3812  3812 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 13:29:51.827  1757  3829 D LocationInitializer: Restart initialization of location
,03-29 13:29:51.847  3812  3812 I MultiDex: VM with version 2.1.0 has multidex support
03-29 13:29:51.847  3812  3812 I MultiDex: install
03-29 13:29:51.847  3812  3812 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 13:29:51.864  3812  3812 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 13:29:51.895  3812  3812 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 13:29:51.900  1567  2530 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-29 13:29:51.904  1567  1567 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-29 13:29:51.909  1757  1757 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-29 13:29:51.911  3812  3812 D WearableService: callingUid 10011, callindPid: 3812
,03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: Install did not work
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-29 13:29:51.914  3812  3834 W NativeLibraryUtils: 	... 4 more
,03-29 13:29:51.926  1757  3835 D LocationInitializer: Restart initialization of location
,03-29 13:29:51.931  1722  2106 E MDM     : [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-29 13:29:51.934  1722  2106 E MDM     : [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-29 13:29:52.026  3748  3748 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-29 13:29:52.280  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.300  1567  2139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 13:29:52.300  1567  2139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:52.300  1567  2139 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:52.300  1567  2139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:52.303  1567  2139 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.315  3748  3748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 13:29:52.316  3748  3748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 13:29:52.316  3748  3748 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-29 13:29:52.398  3748  3748 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-29 13:29:52.426  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:29:52.504  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 13:29:52.505  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 13:29:52.505  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth,
,03-29 13:29:52.505  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-29 13:29:52.518  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.555  3748  3748 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 13:29:52.575  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.634  1567  1589 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
,03-29 13:29:52.634  1567  1589 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:52.634  1567  1589 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:52.635  1567  1589 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:52.644  1567  1589 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.699  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.753  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-29 13:29:52.754  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:29:52.754  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:52.754  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:52.766  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:52.785  3748  3748 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 13:29:53.001  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-29 13:29:53.001  3311  3373 I jxcore-log: 
,03-29 13:29:53.019  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-29 13:29:53.019  3311  3373 I jxcore-log: 
,03-29 13:29:53.028  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-29 13:29:53.028  3311  3373 I jxcore-log: 
,03-29 13:29:53.064  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:53.115  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-29 13:29:53.116  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 13:29:53.116  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:29:53.116  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:29:53.123  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:29:53.158  3748  3748 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-29 13:29:53.164  3748  3748 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-29 13:29:53.181  3748  3748 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-29 13:29:53.189  3748  3748 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,03-29 13:29:53.226  1722  1808 D DeviceConnectionService: client connected with version: 7571000
,03-29 13:29:53.286  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-29 13:29:53.286  3311  3373 I jxcore-log: 
,03-29 13:29:53.353  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-29 13:29:53.353  3311  3373 I jxcore-log: 
,03-29 13:29:53.407  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
03-29 13:29:53.407  3311  3373 I jxcore-log: ,
,03-29 13:29:53.414  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-29 13:29:53.414  3311  3373 I jxcore-log: 
,03-29 13:29:53.425  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-29 13:29:53.425  3311  3373 I jxcore-log: 
,03-29 13:29:53.430  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-29 13:29:53.430  3311  3373 I jxcore-log: 
,03-29 13:29:53.435  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-29 13:29:53.435  3311  3373 I jxcore-log: 
,03-29 13:29:53.450  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-29 13:29:53.450  3311  3373 I jxcore-log: 
,03-29 13:29:53.468  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-29 13:29:53.468  3311  3373 I jxcore-log: 
,03-29 13:29:53.549  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-29 13:29:53.549  3311  3373 I jxcore-log: 
,03-29 13:29:53.555  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-29 13:29:53.555  3311  3373 I jxcore-log: 
,03-29 13:29:53.581  3311  3373 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-29 13:29:53.581  3311  3373 I jxcore-log: 
,03-29 13:29:54.942  3311  3373 I jxcore-log: TAP version 13
03-29 13:29:54.942  3311  3373 I jxcore-log: 
,03-29 13:29:54.946  3311  3373 I jxcore-log: # setup,
03-29 13:29:54.946  3311  3373 I jxcore-log: 
,03-29 13:29:55.195  3311  3373 I jxcore-log: # 1. calling createNativeListener directly rejects
03-29 13:29:55.195  3311  3373 I jxcore-log: 
,03-29 13:29:55.385  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server,
03-29 13:29:55.385  3311  3373 I jxcore-log: 
,03-29 13:29:55.390  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 59987
03-29 13:29:55.390  3311  3373 I jxcore-log: 
,03-29 13:29:55.397  3311  3373 I jxcore-log: ok 1 Should throw
03-29 13:29:55.397  3311  3373 I jxcore-log: 
,03-29 13:29:55.399  3311  3373 I jxcore-log: # teardown
03-29 13:29:55.399  3311  3373 I jxcore-log: 
,03-29 13:29:55.524  3311  3373 I jxcore-log: # setup
03-29 13:29:55.524  3311  3373 I jxcore-log: ,
,03-29 13:29:55.697  3311  3373 I jxcore-log: # 2. emits incomingConnectionState
03-29 13:29:55.697  3311  3373 I jxcore-log: 
,03-29 13:29:55.846  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:55.846  3311  3373 I jxcore-log: 
,03-29 13:29:55.850  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 38013
03-29 13:29:55.850  3311  3373 I jxcore-log: 
,03-29 13:29:55.861  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:55.861  3311  3373 I jxcore-log: 
,03-29 13:29:55.865  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:55.865  3311  3373 I jxcore-log: 
,03-29 13:29:55.875  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:55.875  3311  3373 I jxcore-log: 
,03-29 13:29:55.880  3311  3373 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-29 13:29:55.880  3311  3373 I jxcore-log: 
,03-29 13:29:55.896  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:55.896  3311  3373 I jxcore-log: 
,03-29 13:29:55.897  3311  3373 I jxcore-log: ok 3 final connection state should be DISCONNECTED,
03-29 13:29:55.897  3311  3373 I jxcore-log: 
,03-29 13:29:55.905  3311  3373 I jxcore-log: # teardown
03-29 13:29:55.905  3311  3373 I jxcore-log: 
,03-29 13:29:56.048  3311  3373 I jxcore-log: # setup
,03-29 13:29:56.048  3311  3373 I jxcore-log: 
,03-29 13:29:56.201  3311  3373 I jxcore-log: # 3. emits routerPortConnectionFailed,
03-29 13:29:56.201  3311  3373 I jxcore-log: 
,03-29 13:29:56.291  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:56.291  3311  3373 I jxcore-log: 
,03-29 13:29:56.293  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 55118
03-29 13:29:56.293  3311  3373 I jxcore-log: 
,03-29 13:29:56.299  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:56.299  3311  3373 I jxcore-log: 
,03-29 13:29:56.300  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-29 13:29:56.300  3311  3373 I jxcore-log: 
,03-29 13:29:56.302  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:56.302  3311  3373 I jxcore-log: 
,03-29 13:29:56.326  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:56.326  3311  3373 I jxcore-log: 
,03-29 13:29:56.329  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:56.329  3311  3373 I jxcore-log: 
,03-29 13:29:56.334  3311  3373 I jxcore-log: DEBUG createNativeListener: 
03-29 13:29:56.334  3311  3373 I jxcore-log: 
,03-29 13:29:56.335  3311  3373 I jxcore-log: ok 4 tried to connect to right port
03-29 13:29:56.335  3311  3373 I jxcore-log: 
,03-29 13:29:56.335  3311  3373 I jxcore-log: ok 5 failed due to refused connection
03-29 13:29:56.335  3311  3373 I jxcore-log: 
,03-29 13:29:56.336  3311  3373 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-29 13:29:56.336  3311  3373 I jxcore-log: 
03-29 13:29:56.341  3311  3373 I jxcore-log: # teardown
03-29 13:29:56.341  3311  3373 I jxcore-log: 
,03-29 13:29:56.342  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:56.342  3311  3373 I jxcore-log: 
,03-29 13:29:56.482  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:56.482  3311  3373 I jxcore-log: 
,03-29 13:29:56.488  3311  3373 I jxcore-log: # setup
03-29 13:29:56.488  3311  3373 I jxcore-log: 
,03-29 13:29:56.489  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:56.489  3311  3373 I jxcore-log: 
,03-29 13:29:56.643  3311  3373 I jxcore-log: # 4. native server connections all up
03-29 13:29:56.643  3311  3373 I jxcore-log: 
,03-29 13:29:56.777  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:56.777  3311  3373 I jxcore-log: 
,03-29 13:29:56.787  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 38425
03-29 13:29:56.787  3311  3373 I jxcore-log: 
,03-29 13:29:56.794  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:56.794  3311  3373 I jxcore-log: 
,03-29 13:29:56.795  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:56.795  3311  3373 I jxcore-log: 
,03-29 13:29:56.797  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:56.797  3311  3373 I jxcore-log: 
,03-29 13:29:56.824  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:56.824  3311  3373 I jxcore-log: 
,03-29 13:29:56.828  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:56.828  3311  3373 I jxcore-log: 
,03-29 13:29:56.831  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:56.831  3311  3373 I jxcore-log: 
,03-29 13:29:56.833  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:56.833  3311  3373 I jxcore-log: 
,03-29 13:29:56.859  3311  3373 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-29 13:29:56.859  3311  3373 I jxcore-log: 
,03-29 13:29:56.860  3311  3373 I jxcore-log: ok 8 Send/recvd #1 should be same
03-29 13:29:56.860  3311  3373 I jxcore-log: 
,03-29 13:29:56.862  3311  3373 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-29 13:29:56.862  3311  3373 I jxcore-log: 
,03-29 13:29:56.863  3311  3373 I jxcore-log: ok 10 Send/recvd #2 should be same
03-29 13:29:56.863  3311  3373 I jxcore-log: 
,03-29 13:29:56.865  3311  3373 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-29 13:29:56.865  3311  3373 I jxcore-log: 
,03-29 13:29:56.873  3311  3373 I jxcore-log: # teardown
03-29 13:29:56.873  3311  3373 I jxcore-log: 
,03-29 13:29:56.939   821  1319 I ActivityManager: Killing 3453:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-29 13:29:57.040  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.040  3311  3373 I jxcore-log: 
,03-29 13:29:57.043  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.043  3311  3373 I jxcore-log: 
,03-29 13:29:57.046  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:57.046  3311  3373 I jxcore-log: 
,03-29 13:29:57.051  3311  3373 I jxcore-log: # setup
,03-29 13:29:57.051  3311  3373 I jxcore-log: 
,03-29 13:29:57.052  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:57.052  3311  3373 I jxcore-log: 
,03-29 13:29:57.181   821  1406 I ActivityManager: Killing 3490:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-29 13:29:57.197  3311  3373 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-29 13:29:57.197  3311  3373 I jxcore-log: 
,03-29 13:29:57.331  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:57.331  3311  3373 I jxcore-log: 
,03-29 13:29:57.342  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 39098
03-29 13:29:57.342  3311  3373 I jxcore-log: 
,03-29 13:29:57.355  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:57.355  3311  3373 I jxcore-log: 
,03-29 13:29:57.358  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:57.358  3311  3373 I jxcore-log: 
03-29 13:29:57.362  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:57.362  3311  3373 I jxcore-log: 
,03-29 13:29:57.376  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:57.376  3311  3373 I jxcore-log: 
,03-29 13:29:57.379  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-29 13:29:57.379  3311  3373 I jxcore-log: 
,03-29 13:29:57.392  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.392  3311  3373 I jxcore-log: 
,03-29 13:29:57.412  3311  3373 I jxcore-log: ok 12 socket shouldn't close until after stream
03-29 13:29:57.412  3311  3373 I jxcore-log: 
,03-29 13:29:57.414  3311  3373 I jxcore-log: ok 13 incoming remains open
03-29 13:29:57.414  3311  3373 I jxcore-log: 
,03-29 13:29:57.427  3311  3373 I jxcore-log: # teardown
03-29 13:29:57.427  3311  3373 I jxcore-log: 
,03-29 13:29:57.584  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:57.584  3311  3373 I jxcore-log: 
,03-29 13:29:57.590  3311  3373 I jxcore-log: # setup
03-29 13:29:57.590  3311  3373 I jxcore-log: 
,03-29 13:29:57.592  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:57.592  3311  3373 I jxcore-log: 
,03-29 13:29:57.749  3311  3373 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-29 13:29:57.749  3311  3373 I jxcore-log: 
,03-29 13:29:57.895  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:57.895  3311  3373 I jxcore-log: 
,03-29 13:29:57.903  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 57721
03-29 13:29:57.903  3311  3373 I jxcore-log: 
,03-29 13:29:57.915  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:57.915  3311  3373 I jxcore-log: 
,03-29 13:29:57.918  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-29 13:29:57.918  3311  3373 I jxcore-log: 
,03-29 13:29:57.922  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
,03-29 13:29:57.922  3311  3373 I jxcore-log: 
,03-29 13:29:57.946  3311  3373 I jxcore-log: ok 14 we should not have gotten an error
03-29 13:29:57.946  3311  3373 I jxcore-log: 
,03-29 13:29:57.952  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:57.952  3311  3373 I jxcore-log: 
,03-29 13:29:57.957  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:57.957  3311  3373 I jxcore-log: 
,03-29 13:29:57.967  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:57.967  3311  3373 I jxcore-log: 
,03-29 13:29:57.970  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:57.970  3311  3373 I jxcore-log: 
,03-29 13:29:57.979  3311  3373 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-29 13:29:57.979  3311  3373 I jxcore-log: 
,03-29 13:29:57.979  3311  3373 I jxcore-log: ok 16 incoming is cleaned up
03-29 13:29:57.979  3311  3373 I jxcore-log: 
,03-29 13:29:57.986  3311  3373 I jxcore-log: # teardown
03-29 13:29:57.986  3311  3373 I jxcore-log: 
,03-29 13:29:58.121  3311  3373 I jxcore-log: # setup
03-29 13:29:58.121  3311  3373 I jxcore-log: 
,03-29 13:29:58.277  3311  3373 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-29 13:29:58.277  3311  3373 I jxcore-log: 
,03-29 13:29:58.385  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:58.385  3311  3373 I jxcore-log: 
,03-29 13:29:58.396  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 60391
03-29 13:29:58.396  3311  3373 I jxcore-log: 
,03-29 13:29:58.405  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:58.405  3311  3373 I jxcore-log: 
,03-29 13:29:58.408  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:58.408  3311  3373 I jxcore-log: 
,03-29 13:29:58.416  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:58.416  3311  3373 I jxcore-log: 
,03-29 13:29:58.433  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:58.433  3311  3373 I jxcore-log: 
,03-29 13:29:58.436  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:58.436  3311  3373 I jxcore-log: 
,03-29 13:29:58.450  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:58.450  3311  3373 I jxcore-log: 
,03-29 13:29:58.460  3311  3373 I jxcore-log: ok 17 stream was closed
03-29 13:29:58.460  3311  3373 I jxcore-log: 
,03-29 13:29:58.461  3311  3373 I jxcore-log: ok 18 incoming should survive
03-29 13:29:58.461  3311  3373 I jxcore-log: 
,03-29 13:29:58.461  3311  3373 I jxcore-log: ok 19 mux should have no streams
03-29 13:29:58.461  3311  3373 I jxcore-log: 
,03-29 13:29:58.469  3311  3373 I jxcore-log: # teardown
03-29 13:29:58.469  3311  3373 I jxcore-log: 
,03-29 13:29:58.566  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:58.566  3311  3373 I jxcore-log: 
,03-29 13:29:58.572  3311  3373 I jxcore-log: # setup
03-29 13:29:58.572  3311  3373 I jxcore-log: 
03-29 13:29:58.573  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:58.573  3311  3373 I jxcore-log: 
,03-29 13:29:58.710  3311  3373 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-29 13:29:58.710  3311  3373 I jxcore-log: 
,03-29 13:29:58.913  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:29:58.913  3311  3373 I jxcore-log: 
,03-29 13:29:58.923  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 49058
03-29 13:29:58.923  3311  3373 I jxcore-log: 
,03-29 13:29:58.931  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:58.931  3311  3373 I jxcore-log: 
,03-29 13:29:58.932  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:58.932  3311  3373 I jxcore-log: 
,03-29 13:29:58.933  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:58.933  3311  3373 I jxcore-log: 
,03-29 13:29:58.943  3311  3373 I jxcore-log: ok 20 we should not have gotten an error
03-29 13:29:58.943  3311  3373 I jxcore-log: 
,03-29 13:29:58.949  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:58.949  3311  3373 I jxcore-log: 
,03-29 13:29:58.952  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:58.952  3311  3373 I jxcore-log: 
,03-29 13:29:58.962  3311  3373 I jxcore-log: ok 21 Buffers are identical
03-29 13:29:58.962  3311  3373 I jxcore-log: 
,03-29 13:29:58.965  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:58.965  3311  3373 I jxcore-log: 
,03-29 13:29:58.969  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:58.969  3311  3373 I jxcore-log: 
,03-29 13:29:58.972  3311  3373 I jxcore-log: ok 22 native server is nulled out
03-29 13:29:58.972  3311  3373 I jxcore-log: 
03-29 13:29:58.972  3311  3373 I jxcore-log: ok 23 native server should be closed
03-29 13:29:58.972  3311  3373 I jxcore-log: 
,03-29 13:29:58.972  3311  3373 I jxcore-log: ok 24 incoming has been removed
03-29 13:29:58.972  3311  3373 I jxcore-log: 
03-29 13:29:58.973  3311  3373 I jxcore-log: ok 25 Incoming should be done
03-29 13:29:58.973  3311  3373 I jxcore-log: 
03-29 13:29:58.973  3311  3373 I jxcore-log: ok 26 The mux object should be closed
03-29 13:29:58.973  3311  3373 I jxcore-log: 
,03-29 13:29:58.974  3311  3373 I jxcore-log: ok 27 The mux stream should be closed
03-29 13:29:58.974  3311  3373 I jxcore-log: 
03-29 13:29:58.974  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:58.974  3311  3373 I jxcore-log: 
,03-29 13:29:58.990  3311  3373 I jxcore-log: # teardown
03-29 13:29:58.990  3311  3373 I jxcore-log: 
,03-29 13:29:59.131  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 13:29:59.165  3311  3373 I jxcore-log: # setup
03-29 13:29:59.165  3311  3373 I jxcore-log: 
,03-29 13:29:59.337  3311  3373 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-29 13:29:59.337  3311  3373 I jxcore-log: 
,03-29 13:29:59.553  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
,03-29 13:29:59.553  3311  3373 I jxcore-log: 
,03-29 13:29:59.556  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 37510
03-29 13:29:59.556  3311  3373 I jxcore-log: 
,03-29 13:29:59.576  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-29 13:29:59.576  3311  3373 I jxcore-log: 
03-29 13:29:59.577  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.577  3311  3373 I jxcore-log: 
,03-29 13:29:59.578  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux,
03-29 13:29:59.578  3311  3373 I jxcore-log: 
,03-29 13:29:59.582  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-29 13:29:59.582  3311  3373 I jxcore-log: 
,03-29 13:29:59.582  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.582  3311  3373 I jxcore-log: 
,03-29 13:29:59.584  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.584  3311  3373 I jxcore-log: 
,03-29 13:29:59.587  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.587  3311  3373 I jxcore-log: 
,03-29 13:29:59.587  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.587  3311  3373 I jxcore-log: 
,03-29 13:29:59.588  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.588  3311  3373 I jxcore-log: 
03-29 13:29:59.591  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.591  3311  3373 I jxcore-log: 
03-29 13:29:59.592  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.592  3311  3373 I jxcore-log: 
,03-29 13:29:59.593  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.593  3311  3373 I jxcore-log: 
,03-29 13:29:59.596  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.596  3311  3373 I jxcore-log: 
,03-29 13:29:59.600  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.600  3311  3373 I jxcore-log: 
03-29 13:29:59.602  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.602  3311  3373 I jxcore-log: 
,03-29 13:29:59.605  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.605  3311  3373 I jxcore-log: 
,03-29 13:29:59.605  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.605  3311  3373 I jxcore-log: 
03-29 13:29:59.606  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.606  3311  3373 I jxcore-log: 
03-29 13:29:59.608  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.608  3311  3373 I jxcore-log: 
03-29 13:29:59.609  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.609  3311  3373 I jxcore-log: 
03-29 13:29:59.609  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.609  3311  3373 I jxcore-log: 
,03-29 13:29:59.611  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.611  3311  3373 I jxcore-log: 
03-29 13:29:59.611  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.611  3311  3373 I jxcore-log: 
03-29 13:29:59.612  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.612  3311  3373 I jxcore-log: 
03-29 13:29:59.613  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.613  3311  3373 I jxcore-log: 
03-29 13:29:59.614  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.614  3311  3373 I jxcore-log: 
,03-29 13:29:59.615  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.615  3311  3373 I jxcore-log: 
03-29 13:29:59.616  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:29:59.616  3311  3373 I jxcore-log: 
,03-29 13:29:59.617  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:29:59.617  3311  3373 I jxcore-log: 
03-29 13:29:59.618  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:29:59.618  3311  3373 I jxcore-log: 
,03-29 13:29:59.705  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.705  3311  3373 I jxcore-log: 
,03-29 13:29:59.707  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.707  3311  3373 I jxcore-log: 
,03-29 13:29:59.709  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.709  3311  3373 I jxcore-log: 
,03-29 13:29:59.711  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.711  3311  3373 I jxcore-log: 
,03-29 13:29:59.712  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.712  3311  3373 I jxcore-log: 
03-29 13:29:59.714  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.714  3311  3373 I jxcore-log: 
,03-29 13:29:59.716  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.716  3311  3373 I jxcore-log: 
,03-29 13:29:59.718  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.718  3311  3373 I jxcore-log: 
,03-29 13:29:59.720  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.720  3311  3373 I jxcore-log: 
,03-29 13:29:59.722  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.722  3311  3373 I jxcore-log: 
,03-29 13:29:59.723  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.723  3311  3373 I jxcore-log: 
,03-29 13:29:59.724  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.724  3311  3373 I jxcore-log: 
,03-29 13:29:59.725  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.725  3311  3373 I jxcore-log: 
03-29 13:29:59.727  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.727  3311  3373 I jxcore-log: 
,03-29 13:29:59.728  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.728  3311  3373 I jxcore-log: 
03-29 13:29:59.729  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.729  3311  3373 I jxcore-log: 
,03-29 13:29:59.731  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.731  3311  3373 I jxcore-log: 
,03-29 13:29:59.732  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.732  3311  3373 I jxcore-log: 
,03-29 13:29:59.734  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.734  3311  3373 I jxcore-log: 
,03-29 13:29:59.735  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.735  3311  3373 I jxcore-log: 
,03-29 13:29:59.739  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.739  3311  3373 I jxcore-log: 
,03-29 13:29:59.741  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.741  3311  3373 I jxcore-log: 
,03-29 13:29:59.742  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.742  3311  3373 I jxcore-log: 
,03-29 13:29:59.743  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.743  3311  3373 I jxcore-log: 
,03-29 13:29:59.745  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.745  3311  3373 I jxcore-log: 
,03-29 13:29:59.747  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.747  3311  3373 I jxcore-log: 
,03-29 13:29:59.748  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.748  3311  3373 I jxcore-log: 
,03-29 13:29:59.749  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.749  3311  3373 I jxcore-log: 
,03-29 13:29:59.750  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.750  3311  3373 I jxcore-log: 
,03-29 13:29:59.752  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.752  3311  3373 I jxcore-log: 
,03-29 13:29:59.753  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.753  3311  3373 I jxcore-log: 
,03-29 13:29:59.754  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.754  3311  3373 I jxcore-log: 
,03-29 13:29:59.756  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.756  3311  3373 I jxcore-log: 
,03-29 13:29:59.757  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.757  3311  3373 I jxcore-log: 
,03-29 13:29:59.758  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.758  3311  3373 I jxcore-log: 
,03-29 13:29:59.760  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.760  3311  3373 I jxcore-log: 
,03-29 13:29:59.761  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.761  3311  3373 I jxcore-log: 
,03-29 13:29:59.762  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.762  3311  3373 I jxcore-log: 
,03-29 13:29:59.763  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.763  3311  3373 I jxcore-log: 
,03-29 13:29:59.764  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.764  3311  3373 I jxcore-log: 
,03-29 13:29:59.766  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.766  3311  3373 I jxcore-log: 
,03-29 13:29:59.767  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.767  3311  3373 I jxcore-log: 
,03-29 13:29:59.768  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.768  3311  3373 I jxcore-log: 
,03-29 13:29:59.769  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.769  3311  3373 I jxcore-log: 
,03-29 13:29:59.770  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.770  3311  3373 I jxcore-log: 
,03-29 13:29:59.771  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.771  3311  3373 I jxcore-log: 
03-29 13:29:59.772  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.772  3311  3373 I jxcore-log: 
,03-29 13:29:59.774  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.774  3311  3373 I jxcore-log: 
,03-29 13:29:59.781  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.781  3311  3373 I jxcore-log: 
,03-29 13:29:59.783  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.783  3311  3373 I jxcore-log: 
,03-29 13:29:59.784  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:59.784  3311  3373 I jxcore-log: 
03-29 13:29:59.785  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-29 13:29:59.785  3311  3373 I jxcore-log: 
03-29 13:29:59.786  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 13:29:59.786  3311  3373 I jxcore-log: 
,03-29 13:29:59.787  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.787  3311  3373 I jxcore-log: 
,03-29 13:29:59.788  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.788  3311  3373 I jxcore-log: ,
,03-29 13:29:59.789  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.789  3311  3373 I jxcore-log: 
,03-29 13:29:59.791  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:59.791  3311  3373 I jxcore-log: 
,03-29 13:29:59.793  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-29 13:29:59.793  3311  3373 I jxcore-log: 
03-29 13:29:59.794  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.794  3311  3373 I jxcore-log: 
,03-29 13:29:59.796  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.796  3311  3373 I jxcore-log: 
,03-29 13:29:59.797  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.797  3311  3373 I jxcore-log: 
,03-29 13:29:59.798  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.798  3311  3373 I jxcore-log: ,
03-29 13:29:59.799  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.799  3311  3373 I jxcore-log: 
,03-29 13:29:59.800  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.800  3311  3373 I jxcore-log: 
,03-29 13:29:59.802  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:29:59.802  3311  3373 I jxcore-log: 
,03-29 13:29:59.803  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.803  3311  3373 I jxcore-log: 
,03-29 13:29:59.804  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 13:29:59.804  3311  3373 I jxcore-log: 
,03-29 13:29:59.805  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.805  3311  3373 I jxcore-log: 
03-29 13:29:59.807  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.807  3311  3373 I jxcore-log: 
,03-29 13:29:59.808  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.808  3311  3373 I jxcore-log: 
03-29 13:29:59.809  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-29 13:29:59.809  3311  3373 I jxcore-log: 
,03-29 13:29:59.810  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:29:59.810  3311  3373 I jxcore-log: 
,03-29 13:29:59.812  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.812  3311  3373 I jxcore-log: 
,03-29 13:29:59.813  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.813  3311  3373 I jxcore-log: 
,03-29 13:29:59.814  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.814  3311  3373 I jxcore-log: 
,03-29 13:29:59.815  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.815  3311  3373 I jxcore-log: 
03-29 13:29:59.816  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.816  3311  3373 I jxcore-log: 
,03-29 13:29:59.817  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.817  3311  3373 I jxcore-log: 
03-29 13:29:59.818  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:29:59.818  3311  3373 I jxcore-log: 
,03-29 13:29:59.819  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-29 13:29:59.819  3311  3373 I jxcore-log: 
,03-29 13:29:59.892  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.892  3311  3373 I jxcore-log: 
,03-29 13:29:59.894  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.894  3311  3373 I jxcore-log: 
,03-29 13:29:59.895  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.895  3311  3373 I jxcore-log: 
,03-29 13:29:59.897  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.897  3311  3373 I jxcore-log: 
,03-29 13:29:59.898  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.898  3311  3373 I jxcore-log: 
,03-29 13:29:59.899  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.899  3311  3373 I jxcore-log: 
,03-29 13:29:59.900  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.900  3311  3373 I jxcore-log: 
,03-29 13:29:59.901  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.901  3311  3373 I jxcore-log: 
03-29 13:29:59.902  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.902  3311  3373 I jxcore-log: 
,03-29 13:29:59.902  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.902  3311  3373 I jxcore-log: 
,03-29 13:29:59.905  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.905  3311  3373 I jxcore-log: 
,03-29 13:29:59.906  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.906  3311  3373 I jxcore-log: 
,03-29 13:29:59.907  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.907  3311  3373 I jxcore-log: 
,03-29 13:29:59.908  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.908  3311  3373 I jxcore-log: 
03-29 13:29:59.909  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.909  3311  3373 I jxcore-log: 
,03-29 13:29:59.910  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.910  3311  3373 I jxcore-log: 
03-29 13:29:59.911  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.911  3311  3373 I jxcore-log: 
,03-29 13:29:59.912  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912  3311  3373 I jxcore-log: 
,03-29 13:29:59.912  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.912  3311  3373 I jxcore-log: 
,03-29 13:29:59.913  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.913  3311  3373 I jxcore-log: 
,03-29 13:29:59.914  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.914  3311  3373 I jxcore-log: 
,03-29 13:29:59.915  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.915  3311  3373 I jxcore-log: 
,03-29 13:29:59.916  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.916  3311  3373 I jxcore-log: 
03-29 13:29:59.916  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.916  3311  3373 I jxcore-log: 
03-29 13:29:59.917  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.917  3311  3373 I jxcore-log: 
03-29 13:29:59.919  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.919  3311  3373 I jxcore-log: 
03-29 13:29:59.919  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.919  3311  3373 I jxcore-log: 
03-29 13:29:59.920  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:,
03-29 13:29:59.920  3311  3373 I jxcore-log: 
03-29 13:29:59.921  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.921  3311  3373 I jxcore-log: 
03-29 13:29:59.922  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.922  3311  3373 I jxcore-log: 
03-29 13:29:59.922  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.922  3311  3373 I jxcore-log: 
03-29 13:29:59.923  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.923  3311  3373 I jxcore-log: 
03-29 13:29:59.924  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.924  3311  3373 I jxcore-log: 
03-29 13:29:59.925  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.925  3311  3373 I jxcore-log: 
03-29 13:29:59.926  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
,03-29 13:29:59.926  3311  3373 I jxcore-log: 
03-29 13:29:59.927  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927  3311  3373 I jxcore-log: 
03-29 13:29:59.927  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.927  3311  3373 I jxcore-log: 
03-29 13:29:59.928  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.928  3311  3373 I jxcore-log: 
,03-29 13:29:59.929  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.929  3311  3373 I jxcore-log: 
03-29 13:29:59.930  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.930  3311  3373 I jxcore-log: 
03-29 13:29:59.930  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.930  3311  3373 I jxcore-log: 
,03-29 13:29:59.931  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.931  3311  3373 I jxcore-log: 
03-29 13:29:59.932  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932  3311  3373 I jxcore-log: 
03-29 13:29:59.932  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.932  3311  3373 I jxcore-log: 
,03-29 13:29:59.933  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.933  3311  3373 I jxcore-log: 
03-29 13:29:59.934  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.934  3311  3373 I jxcore-log: 
03-29 13:29:59.935  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.935  3311  3373 I jxcore-log: 
,03-29 13:29:59.936  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.936  3311  3373 I jxcore-log: 
03-29 13:29:59.937  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:29:59.937  3311  3373 I jxcore-log: 
03-29 13:29:59.937  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:29:59.937  3311  3373 I jxcore-log: 
,03-29 13:29:59.940  3311  3373 I jxcore-log: ok 28 native server is nulled out
03-29 13:29:59.940  3311  3373 I jxcore-log: 
03-29 13:29:59.941  3311  3373 I jxcore-log: ok 29 native server should be closed
03-29 13:29:59.941  3311  3373 I jxcore-log: 
03-29 13:29:59.941  3311  3373 I jxcore-log: ok 30 incoming has been removed
03-29 13:29:59.941  3311  3373 I jxcore-log: 
,03-29 13:29:59.942  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942  3311  3373 I jxcore-log: 
03-29 13:29:59.942  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.942  3311  3373 I jxcore-log: 
03-29 13:29:59.943  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.943  3311  3373 I jxcore-log: 
,03-29 13:29:59.943  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.943  3311  3373 I jxcore-log: 
03-29 13:29:59.944  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.944  3311  3373 I jxcore-log: 
03-29 13:29:59.944  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.944  3311  3373 I jxcore-log: 
,03-29 13:29:59.944  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.944  3311  3373 I jxcore-log: 
03-29 13:29:59.945  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.945  3311  3373 I jxcore-log: 
03-29 13:29:59.945  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.945  3311  3373 I jxcore-log: 
,03-29 13:29:59.945  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:29:59.945  3311  3373 I jxcore-log: 
,03-29 13:30:00.046  3311  3373 I jxcore-log: # teardown,
03-29 13:30:00.046  3311  3373 I jxcore-log: 
,03-29 13:30:00.202  3311  3373 I jxcore-log: # setup,
03-29 13:30:00.202  3311  3373 I jxcore-log: 
,03-29 13:30:00.858  3311  3373 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up,
03-29 13:30:00.858  3311  3373 I jxcore-log: 
,03-29 13:30:03.957  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:03.957  3311  3373 I jxcore-log: 
,03-29 13:30:03.967  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 37517
,03-29 13:30:03.967  3311  3373 I jxcore-log: 
,03-29 13:30:03.973  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-29 13:30:03.973  3311  3373 I jxcore-log: 
,03-29 13:30:03.975  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:30:03.975  3311  3373 I jxcore-log: 
,03-29 13:30:03.978  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
,03-29 13:30:03.978  3311  3373 I jxcore-log: 
,03-29 13:30:03.988  3311  3373 I jxcore-log: ok 31 we should not have gotten an error
,03-29 13:30:03.988  3311  3373 I jxcore-log: 
,03-29 13:30:03.993  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-29 13:30:03.993  3311  3373 I jxcore-log: 
,03-29 13:30:03.996  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-29 13:30:03.996  3311  3373 I jxcore-log: 
,03-29 13:30:04.005  3311  3373 I jxcore-log: ok 32 Buffers are identical
,03-29 13:30:04.005  3311  3373 I jxcore-log: 
03-29 13:30:04.006  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:30:04.006  3311  3373 I jxcore-log: 
,03-29 13:30:04.009  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
,03-29 13:30:04.009  3311  3373 I jxcore-log: 
,03-29 13:30:04.020  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:30:04.020  3311  3373 I jxcore-log: ,
03-29 13:30:04.020  3311  3373 I jxcore-log: ok 33 server should be fine
03-29 13:30:04.020  3311  3373 I jxcore-log: ,
03-29 13:30:04.021  3311  3373 I jxcore-log: ok 34 server should be open
03-29 13:30:04.021  3311  3373 I jxcore-log: 
,03-29 13:30:04.022  3311  3373 I jxcore-log: ok 35 incoming has been removed
03-29 13:30:04.022  3311  3373 I jxcore-log: 
,03-29 13:30:04.023  3311  3373 I jxcore-log: ok 36 The mux object should be closed
03-29 13:30:04.023  3311  3373 I jxcore-log: 
,03-29 13:30:04.024  3311  3373 I jxcore-log: ok 37 The mux stream should be closed
03-29 13:30:04.024  3311  3373 I jxcore-log: 
,03-29 13:30:04.032  3311  3373 I jxcore-log: # teardown
,03-29 13:30:04.032  3311  3373 I jxcore-log: 
,03-29 13:30:04.178  3311  3373 I jxcore-log: # setup
03-29 13:30:04.178  3311  3373 I jxcore-log: 
,03-29 13:30:04.678  3311  3373 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-29 13:30:04.678  3311  3373 I jxcore-log: 
,03-29 13:30:04.811  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:04.811  3311  3373 I jxcore-log: 
,03-29 13:30:04.818  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 34313
03-29 13:30:04.818  3311  3373 I jxcore-log: 
,03-29 13:30:04.824  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-29 13:30:04.824  3311  3373 I jxcore-log: 
,03-29 13:30:04.825  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-29 13:30:04.825  3311  3373 I jxcore-log: 
,03-29 13:30:04.827  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux
03-29 13:30:04.827  3311  3373 I jxcore-log: 
,03-29 13:30:04.834  3311  3373 I jxcore-log: ok 38 we should not have gotten an error
03-29 13:30:04.834  3311  3373 I jxcore-log: 
,03-29 13:30:04.838  3311  3373 I jxcore-log: DEBUG createNativeListener: new stream: 
03-29 13:30:04.838  3311  3373 I jxcore-log: 
,03-29 13:30:04.841  3311  3373 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-29 13:30:04.841  3311  3373 I jxcore-log: 
,03-29 13:30:04.848  3311  3373 I jxcore-log: ok 39 Buffers are identical
03-29 13:30:04.848  3311  3373 I jxcore-log: 
,03-29 13:30:04.852  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-29 13:30:04.852  3311  3373 I jxcore-log: 
,03-29 13:30:04.854  3311  3373 I jxcore-log: DEBUG createNativeListener: stream close:
03-29 13:30:04.854  3311  3373 I jxcore-log: 
,03-29 13:30:04.856  3311  3373 I jxcore-log: DEBUG createNativeListener: mux close
03-29 13:30:04.856  3311  3373 I jxcore-log: 
,03-29 13:30:04.861  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:30:04.861  3311  3373 I jxcore-log: 
03-29 13:30:04.862  3311  3373 I jxcore-log: ok 40 server should be fine
03-29 13:30:04.862  3311  3373 I jxcore-log: 
,03-29 13:30:04.862  3311  3373 I jxcore-log: ok 41 server should be open
03-29 13:30:04.862  3311  3373 I jxcore-log: 
03-29 13:30:04.862  3311  3373 I jxcore-log: ok 42 incoming has been removed
03-29 13:30:04.862  3311  3373 I jxcore-log: 
03-29 13:30:04.863  3311  3373 I jxcore-log: ok 43 The mux object should be closed
03-29 13:30:04.863  3311  3373 I jxcore-log: 
,03-29 13:30:04.863  3311  3373 I jxcore-log: ok 44 The mux stream should be closed
03-29 13:30:04.863  3311  3373 I jxcore-log: 
,03-29 13:30:04.871  3311  3373 I jxcore-log: # teardown
03-29 13:30:04.871  3311  3373 I jxcore-log: 
,03-29 13:30:05.001  3311  3373 I jxcore-log: # setup
03-29 13:30:05.001  3311  3373 I jxcore-log: 
,03-29 13:30:05.166  3311  3373 I jxcore-log: # 12. closeAll can close even when connections open
03-29 13:30:05.166  3311  3373 I jxcore-log: 
,03-29 13:30:05.369  3311  3373 I jxcore-log: ok 45 not possible to connect to the server anymore
03-29 13:30:05.369  3311  3373 I jxcore-log: 
,03-29 13:30:05.374  3311  3373 I jxcore-log: # teardown
03-29 13:30:05.374  3311  3373 I jxcore-log: 
,03-29 13:30:05.490  3311  3373 I jxcore-log: # setup
03-29 13:30:05.490  3311  3373 I jxcore-log: 
,03-29 13:30:05.601  3311  3373 I jxcore-log: # 13. closeAll with promise
03-29 13:30:05.601  3311  3373 I jxcore-log: 
,03-29 13:30:05.868  3311  3373 I jxcore-log: ok 46 not possible to connect to the server anymore
03-29 13:30:05.868  3311  3373 I jxcore-log: 
,03-29 13:30:05.874  3311  3373 I jxcore-log: # teardown
03-29 13:30:05.874  3311  3373 I jxcore-log: 
,03-29 13:30:06.040  3311  3373 I jxcore-log: # setup
,03-29 13:30:06.040  3311  3373 I jxcore-log: 
,03-29 13:30:06.216  3311  3373 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-29 13:30:06.216  3311  3373 I jxcore-log: 
,03-29 13:30:06.395  3311  3373 I jxcore-log: ok 47 Got the right error
03-29 13:30:06.395  3311  3373 I jxcore-log: 
,03-29 13:30:06.401  3311  3373 I jxcore-log: # teardown
03-29 13:30:06.401  3311  3373 I jxcore-log: 
,03-29 13:30:06.550  3311  3373 I jxcore-log: # setup
03-29 13:30:06.550  3311  3373 I jxcore-log: 
,03-29 13:30:06.717  3311  3373 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-29 13:30:06.717  3311  3373 I jxcore-log: 
,03-29 13:30:06.857  3311  3373 I jxcore-log: # teardown
03-29 13:30:06.857  3311  3373 I jxcore-log: 
,03-29 13:30:07.080  3311  3373 I jxcore-log: # setup
03-29 13:30:07.080  3311  3373 I jxcore-log: 
,03-29 13:30:07.227  3311  3373 I jxcore-log: # 16. multiplex can send data
03-29 13:30:07.227  3311  3373 I jxcore-log: 
,03-29 13:30:07.545  3311  3373 I jxcore-log: ok 48 String should be length:200
03-29 13:30:07.545  3311  3373 I jxcore-log: 
,03-29 13:30:07.553  3311  3373 I jxcore-log: # teardown
03-29 13:30:07.553  3311  3373 I jxcore-log: ,
,03-29 13:30:07.678  3311  3373 I jxcore-log: # setup
03-29 13:30:07.678  3311  3373 I jxcore-log: 
,03-29 13:30:07.797  3311  3373 I jxcore-log: # 17. enqueue and run in order,
03-29 13:30:07.797  3311  3373 I jxcore-log: 
,03-29 13:30:08.034  3311  3373 I jxcore-log: ok 49 firstPromise setTimeout
03-29 13:30:08.034  3311  3373 I jxcore-log: 
03-29 13:30:08.037  3311  3373 I jxcore-log: ok 50 firstPromise result
03-29 13:30:08.037  3311  3373 I jxcore-log: 
,03-29 13:30:08.038  3311  3373 I jxcore-log: ok 51 firstPromise testValue
03-29 13:30:08.038  3311  3373 I jxcore-log: 
,03-29 13:30:08.111  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:08.141  3311  3373 I jxcore-log: ok 52 secondPromise setTimeout
03-29 13:30:08.141  3311  3373 I jxcore-log: 
,03-29 13:30:08.143  3311  3373 I jxcore-log: ok 53 secondPromise result
03-29 13:30:08.143  3311  3373 I jxcore-log: 
,03-29 13:30:08.143  3311  3373 I jxcore-log: ok 54 secondPromise testValue
03-29 13:30:08.143  3311  3373 I jxcore-log: 
03-29 13:30:08.144  3311  3373 I jxcore-log: ok 55 thirdPromise in promise
03-29 13:30:08.144  3311  3373 I jxcore-log: 
,03-29 13:30:08.144  3311  3373 I jxcore-log: ok 56 thirdPromise result
03-29 13:30:08.144  3311  3373 I jxcore-log: 
03-29 13:30:08.145  3311  3373 I jxcore-log: ok 57 thirdPromise testValue
03-29 13:30:08.145  3311  3373 I jxcore-log: 
,03-29 13:30:08.152  3311  3373 I jxcore-log: # teardown
03-29 13:30:08.152  3311  3373 I jxcore-log: 
,03-29 13:30:08.162  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 13:30:08.162  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:08.162  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-29 13:30:08.163  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:08.166  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:30:08.179  3748  3748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 13:30:08.180  3748  3748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 13:30:08.184  3748  3748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-29 13:30:08.337  3311  3373 I jxcore-log: # setup
03-29 13:30:08.337  3311  3373 I jxcore-log: 
,03-29 13:30:08.601  3311  3373 I jxcore-log: # 18. enqueueAtTop and run backwards
03-29 13:30:08.601  3311  3373 I jxcore-log: 
,03-29 13:30:08.733  3311  3373 I jxcore-log: ok 58 thirdPromise - first to run
03-29 13:30:08.733  3311  3373 I jxcore-log: 
,03-29 13:30:08.737  3311  3373 I jxcore-log: ok 59 thirdPromise - in resolve
03-29 13:30:08.737  3311  3373 I jxcore-log: 
,03-29 13:30:08.738  3311  3373 I jxcore-log: ok 60 secondPromise - second to run
03-29 13:30:08.738  3311  3373 I jxcore-log: 
,03-29 13:30:08.739  3311  3373 I jxcore-log: ok 61 secondPromise - in catch
03-29 13:30:08.739  3311  3373 I jxcore-log: 
,03-29 13:30:08.739  3311  3373 I jxcore-log: ok 62 firstPromise - third to run
03-29 13:30:08.739  3311  3373 I jxcore-log: 
,03-29 13:30:08.740  3311  3373 I jxcore-log: ok 63 firstPromise - in then
03-29 13:30:08.740  3311  3373 I jxcore-log: 
,03-29 13:30:08.740  3311  3373 I jxcore-log: ok 64 testing promises
03-29 13:30:08.740  3311  3373 I jxcore-log: 
,03-29 13:30:08.743  3311  3373 I jxcore-log: # teardown
03-29 13:30:08.743  3311  3373 I jxcore-log: 
,03-29 13:30:08.873  3311  3373 I jxcore-log: # setup
03-29 13:30:08.873  3311  3373 I jxcore-log: 
,03-29 13:30:08.962  3311  3373 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-29 13:30:08.962  3311  3373 I jxcore-log: 
,03-29 13:30:09.427  3311  3373 I jxcore-log: ok 65 fourth,
03-29 13:30:09.427  3311  3373 I jxcore-log: 
03-29 13:30:09.429  3311  3373 I jxcore-log: ok 66 fourth
03-29 13:30:09.429  3311  3373 I jxcore-log: 
03-29 13:30:09.432  3311  3373 I jxcore-log: ok 67 second,
03-29 13:30:09.432  3311  3373 I jxcore-log: 
03-29 13:30:09.436  3311  3373 I jxcore-log: ok 68 secondPromise - in then
03-29 13:30:09.436  3311  3373 I jxcore-log: 
,03-29 13:30:09.540  3311  3373 I jxcore-log: ok 69 first
03-29 13:30:09.540  3311  3373 I jxcore-log: 
,03-29 13:30:09.543  3311  3373 I jxcore-log: ok 70 firstPromise - in catch
03-29 13:30:09.543  3311  3373 I jxcore-log: 
,03-29 13:30:09.546  3311  3373 I jxcore-log: ok 71 third
,03-29 13:30:09.546  3311  3373 I jxcore-log: 
,03-29 13:30:09.548  3311  3373 I jxcore-log: ok 72 thirdPromise - in then
03-29 13:30:09.548  3311  3373 I jxcore-log: 
,03-29 13:30:09.550  3311  3373 I jxcore-log: ok 73 testingPromises
03-29 13:30:09.550  3311  3373 I jxcore-log: 
,03-29 13:30:09.561  3311  3373 I jxcore-log: # teardown
03-29 13:30:09.561  3311  3373 I jxcore-log: 
,03-29 13:30:09.745  3311  3373 I jxcore-log: # setup
03-29 13:30:09.745  3311  3373 I jxcore-log: 
,03-29 13:30:09.844  3311  3373 I jxcore-log: # 20. queues handled independently
03-29 13:30:09.844  3311  3373 I jxcore-log: 
,03-29 13:30:10.122  3311  3373 I jxcore-log: ok 74 all short operations completed before the long resolves
03-29 13:30:10.122  3311  3373 I jxcore-log: ,
,03-29 13:30:10.127  3311  3373 I jxcore-log: # teardown
03-29 13:30:10.127  3311  3373 I jxcore-log: 
,03-29 13:30:10.259  3311  3373 I jxcore-log: # setup
03-29 13:30:10.259  3311  3373 I jxcore-log: 
,03-29 13:30:10.420  3311  3373 I jxcore-log: # 21. basic
03-29 13:30:10.420  3311  3373 I jxcore-log: 
,03-29 13:30:10.686  3311  3373 I jxcore-log: ok 75 sane
03-29 13:30:10.686  3311  3373 I jxcore-log: 
,03-29 13:30:10.693  3311  3373 I jxcore-log: # teardown,
03-29 13:30:10.693  3311  3373 I jxcore-log: 
,03-29 13:30:10.822  3311  3373 I jxcore-log: # setup
03-29 13:30:10.822  3311  3373 I jxcore-log: 
,03-29 13:30:10.917  3311  3373 I jxcore-log: # 22. another
03-29 13:30:10.917  3311  3373 I jxcore-log: 
,03-29 13:30:11.020  3311  3373 I jxcore-log: ok 76 sane
03-29 13:30:11.020  3311  3373 I jxcore-log: 
,03-29 13:30:11.028  3311  3373 I jxcore-log: # teardown
03-29 13:30:11.028  3311  3373 I jxcore-log: 
,03-29 13:30:11.171  3311  3373 I jxcore-log: # setup
03-29 13:30:11.171  3311  3373 I jxcore-log: 
,03-29 13:30:11.305  3311  3373 I jxcore-log: # 23. can pass data in setup,
,03-29 13:30:11.305  3311  3373 I jxcore-log: 
,03-29 13:30:11.423  3311  3373 I jxcore-log: ok 77 test participant has uuid
03-29 13:30:11.423  3311  3373 I jxcore-log: 
,03-29 13:30:11.425  3311  3373 I jxcore-log: ok 78 participant data matches
03-29 13:30:11.425  3311  3373 I jxcore-log: 
03-29 13:30:11.426  3311  3373 I jxcore-log: ok 79 test participant has uuid
03-29 13:30:11.426  3311  3373 I jxcore-log: 
,03-29 13:30:11.428  3311  3373 I jxcore-log: ok 80 participant data matches
03-29 13:30:11.428  3311  3373 I jxcore-log: 
,03-29 13:30:11.429  3311  3373 I jxcore-log: ok 81 test participant has uuid
03-29 13:30:11.429  3311  3373 I jxcore-log: 
,03-29 13:30:11.430  3311  3373 I jxcore-log: ok 82 participant data matches
03-29 13:30:11.430  3311  3373 I jxcore-log: 
,03-29 13:30:11.436  3311  3373 I jxcore-log: # teardown
03-29 13:30:11.436  3311  3373 I jxcore-log: 
,03-29 13:30:11.563  3311  3373 I jxcore-log: # setup
03-29 13:30:11.563  3311  3373 I jxcore-log: 
,03-29 13:30:11.692  3311  3373 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-29 13:30:11.692  3311  3373 I jxcore-log: 
,03-29 13:30:11.848  3311  3373 I jxcore-log: ok 83 specific error should be returned
03-29 13:30:11.848  3311  3373 I jxcore-log: 
,03-29 13:30:11.854  3311  3373 I jxcore-log: # teardown
03-29 13:30:11.854  3311  3373 I jxcore-log: 
,03-29 13:30:11.959  3311  3373 I jxcore-log: ok 84 error should be null
03-29 13:30:11.959  3311  3373 I jxcore-log: 
03-29 13:30:11.960  3311  3373 I jxcore-log: ok 85 error should be null
03-29 13:30:11.960  3311  3373 I jxcore-log: 
03-29 13:30:11.961  3311  3373 I jxcore-log: # setup
03-29 13:30:11.961  3311  3373 I jxcore-log: 
,03-29 13:30:12.065  3311  3373 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-29 13:30:12.065  3311  3373 I jxcore-log: 
,03-29 13:30:12.173  3311  3373 I jxcore-log: ok 86 specific error should be returned
03-29 13:30:12.173  3311  3373 I jxcore-log: 
,03-29 13:30:12.178  3311  3373 I jxcore-log: # teardown
03-29 13:30:12.178  3311  3373 I jxcore-log: 
,03-29 13:30:12.297  3311  3373 I jxcore-log: ok 87 error should be null
03-29 13:30:12.297  3311  3373 I jxcore-log: 
,03-29 13:30:12.297  3311  3373 I jxcore-log: ok 88 error should be null
03-29 13:30:12.297  3311  3373 I jxcore-log: 
,03-29 13:30:12.300  3311  3373 I jxcore-log: # setup
03-29 13:30:12.300  3311  3373 I jxcore-log: 
,03-29 13:30:12.438  3311  3373 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-29 13:30:12.438  3311  3373 I jxcore-log: 
,03-29 13:30:12.623  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:12.623  3311  3373 I jxcore-log: 
,03-29 13:30:12.624  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 57232
03-29 13:30:12.624  3311  3373 I jxcore-log: 
,03-29 13:30:12.627  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:12.627  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:12.627  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.646  3311  3373 I jxcore-log: ok 89 error should be null
03-29 13:30:12.646  3311  3373 I jxcore-log: 
,03-29 13:30:12.648  3311  3373 I jxcore-log: ok 90 error should be null
03-29 13:30:12.648  3311  3373 I jxcore-log: 
,03-29 13:30:12.653  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:12.653  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:12.653  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.657  3311  3373 I jxcore-log: ok 91 error should be null
03-29 13:30:12.657  3311  3373 I jxcore-log: 
,03-29 13:30:12.658  3311  3373 I jxcore-log: ok 92 error should be null
03-29 13:30:12.658  3311  3373 I jxcore-log: 
03-29 13:30:12.662  3311  3373 I jxcore-log: # teardown
03-29 13:30:12.662  3311  3373 I jxcore-log: 
,03-29 13:30:12.792  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:12.792  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:12.792  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.799  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:12.800  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:12.800  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:12.805  3311  3373 I jxcore-log: ok 93 error should be null
03-29 13:30:12.805  3311  3373 I jxcore-log: 
,03-29 13:30:12.806  3311  3373 I jxcore-log: ok 94 error should be null
03-29 13:30:12.806  3311  3373 I jxcore-log: 
,03-29 13:30:12.812  3311  3373 I jxcore-log: # setup
03-29 13:30:12.812  3311  3373 I jxcore-log: 
,03-29 13:30:12.922  3311  3373 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-29 13:30:12.922  3311  3373 I jxcore-log: 
,03-29 13:30:13.569  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
,03-29 13:30:13.569  3311  3373 I jxcore-log: 
,03-29 13:30:13.572  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 43789
,03-29 13:30:13.572  3311  3373 I jxcore-log: 
,03-29 13:30:13.584  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-29 13:30:13.584  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:13.584  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
03-29 13:30:13.584  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:13.584  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:13.584  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:13.594  3311  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:30:13.595   821  1436 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-29 13:30:13.605  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:13.612  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-29 13:30:13.612  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:13.612  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:30:13.612  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:13.626  2153  2169 D BtGatt.GattService: registerClient() - UUID=14d8b7ed-c494-4ace-8dde-0ae9ad4d5012,
,03-29 13:30:13.627  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=14d8b7ed-c494-4ace-8dde-0ae9ad4d5012, clientIf=5,
03-29 13:30:13.628  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 13:30:13.631  2153  2219 D BtGatt.GattService: start scan with filters,
,03-29 13:30:13.634  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 13:30:13.635  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:13.635  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 13:30:13.636  2153  2228 D BtGatt.ScanManager: handling starting scan,
03-29 13:30:13.636  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:13.636  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:13.636  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:13.637  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-29 13:30:13.639   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:13.643  2153  2228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13448517
,03-29 13:30:13.652  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:13.652  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:30:13.654  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:13.655  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:30:13.655  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:13.656  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:13.658  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:13.658  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:13.661  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:30:13.661  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:13.664  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan,
03-29 13:30:13.664  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:30:13.667  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:30:13.667  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:13.668  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-29 13:30:13.668  3311  3373 I jxcore-log: 
03-29 13:30:13.669  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 13:30:13.669  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:13.669  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:13.669  3311  3373 I jxcore-log: 
,03-29 13:30:13.679  3311  3373 I jxcore-log: ok 95 error should be null
,03-29 13:30:13.679  3311  3373 I jxcore-log: 
03-29 13:30:13.680  3311  3373 I jxcore-log: ok 96 error should be null
03-29 13:30:13.680  3311  3373 I jxcore-log: 
,03-29 13:30:13.687  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
03-29 13:30:13.687  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:13.688  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:13.688  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:13.688  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:13.692  3311  3373 I jxcore-log: ok 97 error should be null
,03-29 13:30:13.692  3311  3373 I jxcore-log: 
03-29 13:30:13.693  3311  3373 I jxcore-log: ok 98 error should be null
03-29 13:30:13.693  3311  3373 I jxcore-log: 
,03-29 13:30:13.701  3311  3373 I jxcore-log: # teardown,
,03-29 13:30:13.701  3311  3373 I jxcore-log: 
,03-29 13:30:14.517  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:14.517  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:14.517  3311  3373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
03-29 13:30:14.517  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:14.517  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 13:30:14.517  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:14.517  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:14.518  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:14.518  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:14.521  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:14.523  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:30:14.524  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:14.524  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:14.524  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:14.524  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-29 13:30:14.524  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:30:14.524  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:14.528  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:30:14.528  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 13:30:14.528  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:14.530  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:30:14.530  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-29 13:30:14.531  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:14.533  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:30:14.533  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:14.533  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:14.533  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:14.533  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:14.536  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 13:30:14.536  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:14.536  3311  3373 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:14.536  3311  3373 I jxcore-log: 
03-29 13:30:14.537  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:14.540  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 13:30:14.540  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:14.540  2153  2217 D BtGatt.GattService: current time is 202805960650
03-29 13:30:14.540  2153  2217 D BtGatt.GattService: Batch record : [-32, -32, 23, -31, -25, 109, 1, -128, -105, 9, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 111, -112, -42, 27, -127, 110, 127, -61, -77, -33, 10, -13, -98, 0, -32, -32, 23, -31, -25, 109, 1, -128, -108, 4, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 112, -112, 121, 12, -97, 11, 54, -112, -27, 98, 28, -116, 81, 0]
03-29 13:30:14.541  2153  2217 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 111, -112, -42, 27, -127, 110, 127, -61, -77, -33, 10, -13, -98]
03-29 13:30:14.542  2153  2217 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, 112, -112, 121, 12, -97, 11, 54, -112, -27, 98, 28, -116, 81]
,03-29 13:30:14.547  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-29 13:30:14.548   821  1319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:14.558  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:14.559  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:14.559  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:14.563  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:14.563  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:14.563  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:14.563  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:14.564  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:14.564  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:30:14.565  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:14.566  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:14.566  3311  3373 I jxcore-log: 
03-29 13:30:14.567  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:14.567  3311  3373 I jxcore-log: 
,03-29 13:30:14.570  3311  3373 I jxcore-log: ok 99 error should be null
03-29 13:30:14.570  3311  3373 I jxcore-log: 
03-29 13:30:14.570  3311  3373 I jxcore-log: ok 100 error should be null
03-29 13:30:14.570  3311  3373 I jxcore-log: 
03-29 13:30:14.575  3311  3373 I jxcore-log: # setup
03-29 13:30:14.575  3311  3373 I jxcore-log: 
,03-29 13:30:16.859  3311  3373 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
,03-29 13:30:16.859  3311  3373 I jxcore-log: 
,03-29 13:30:17.090  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:17.090  3311  3373 I jxcore-log: 
,03-29 13:30:17.092  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 55156
03-29 13:30:17.092  3311  3373 I jxcore-log: 
,03-29 13:30:17.111  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 55156, start advertisements: true
,03-29 13:30:17.111  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:17.111  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:17.111  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:17.116  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-29 13:30:17.116  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:17.116  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:17.116  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:17.120  2153  2170 D BtGatt.GattService: registerClient() - UUID=fdaccb08-0848-4263-8d8f-63a28ef94a1f
,03-29 13:30:17.121  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=fdaccb08-0848-4263-8d8f-63a28ef94a1f, clientIf=5
03-29 13:30:17.121  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:30:17.122  2153  2169 D BtGatt.GattService: start scan with filters
,03-29 13:30:17.124  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:30:17.125  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 13:30:17.126  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:30:17.126  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-29 13:30:17.126  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:17.126  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:17.126  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:17.126  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:17.127  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:30:17.128  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:30:17.129  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:17.129  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:17.131  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:30:17.131  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:17.131  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:17.131  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:17.131  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:30:17.131  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:17.131  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-29 13:30:17.133  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:30:17.134  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:17.135  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:30:17.136  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:17.140  2153  2170 D BtGatt.GattService: registerClient() - UUID=425a7d0e-eaf5-497c-baba-3df7f5f50f90
03-29 13:30:17.141  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=425a7d0e-eaf5-497c-baba-3df7f5f50f90, clientIf=6
,03-29 13:30:17.141  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:17.145  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:17.149  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:17.152  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:30:17.155  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-29 13:30:17.156  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:30:17.157  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:17.157   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:17.160  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:17.160  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:30:17.160  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-29 13:30:17.160  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:17.161  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:30:17.162  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:17.163  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:17.163  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-29 13:30:17.163  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:17.163  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-29 13:30:17.163  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:17.164  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:17.164  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:17.164  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 13:30:17.164  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:17.164  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:17.165  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:17.165  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 13:30:17.165  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:17.165  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:17.165  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:30:17.175  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:17.175  3311  3373 I jxcore-log: 
,03-29 13:30:17.185   821  1319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:17.187  3311  3858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:17.189  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:17.189  3311  3373 I jxcore-log: 
,03-29 13:30:17.192  3311  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:17.193  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:17.193  3311  3373 I jxcore-log: 
,03-29 13:30:17.196  3311  3373 I jxcore-log: ok 101 error should be null
03-29 13:30:17.196  3311  3373 I jxcore-log: 
,03-29 13:30:17.197  3311  3373 I jxcore-log: ok 102 error should be null
03-29 13:30:17.197  3311  3373 I jxcore-log: 
,03-29 13:30:17.204  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 55156, start advertisements: true,
03-29 13:30:17.204  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:17.204  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 13:30:17.204  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:17.205  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:17.215  3311  3373 I jxcore-log: ok 103 error should be null,
03-29 13:30:17.215  3311  3373 I jxcore-log: 
03-29 13:30:17.216  3311  3373 I jxcore-log: ok 104 error should be null
,03-29 13:30:17.216  3311  3373 I jxcore-log: 
,03-29 13:30:17.224  3311  3373 I jxcore-log: # teardown,
03-29 13:30:17.224  3311  3373 I jxcore-log: 
,03-29 13:30:18.146  2153  2153 D BtGatt.ScanManager: awakened up at time 206411
,03-29 13:30:18.148  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:18.159  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-29 13:30:18.159  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:18.159  2153  2217 D BtGatt.GattService: current time is 206425410857
03-29 13:30:18.160  2153  2217 D BtGatt.GattService: Batch record : [22, -71, -84, 66, 60, 74, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-29 13:30:18.161  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:30:18.171  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-29 13:30:18.171  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 13:30:18.179  3311  3373 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-29 13:30:18.179  3311  3373 I jxcore-log: 
,03-29 13:30:18.187  3311  3373 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 13:30:18.187  3311  3373 I jxcore-log: 
,03-29 13:30:18.361  3419  3859 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 13:30:18.426  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-29 13:30:18.427  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-29 13:30:18.427  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:18.427  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:18.435  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:18.472  3419  3859 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-29 13:30:18.474  3419  3859 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 13:30:18.691  2153  2153 D BtGatt.ScanManager: awakened up at time 206956
03-29 13:30:18.692  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:18.695  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-29 13:30:18.695  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:18.696  2153  2217 D BtGatt.GattService: current time is 206961475232
03-29 13:30:18.696  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 10, 0, 0, 0, 22, -71, -84, 66, 60, 74, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 13:30:18.696  2153  2217 D BtGatt.GattService: ScanRecord : []
03-29 13:30:18.697  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:18.698  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 13:30:18.700  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-29 13:30:18.700  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:30:18.700  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-29 13:30:18.706  3311  3373 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-29 13:30:18.706  3311  3373 I jxcore-log: 
,03-29 13:30:18.710  3311  3373 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-29 13:30:18.710  3311  3373 I jxcore-log: 
,03-29 13:30:19.107  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-29 13:30:19.107  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:19.107  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:30:19.107  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:19.107  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 13:30:19.108  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:19.108  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:30:19.108  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 13:30:19.108  3311  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-29 13:30:19.108  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:19.108  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:30:19.108  3311  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:19.108  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-29 13:30:19.108  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:19.108  3311  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:19.112  2153  2170 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 13:30:19.114  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:30:19.114  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:19.114  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:19.114  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:19.115  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:30:19.115  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:19.115  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:19.115  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:19.118  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:30:19.118  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:19.118  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:19.119  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:30:19.121  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:30:19.121  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:19.121  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:30:19.121  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:30:19.125  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-29 13:30:19.125  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:19.125  2153  2217 D BtGatt.GattService: current time is 207390958461
03-29 13:30:19.125  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 13:30:19.125  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:30:19.128  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:30:19.128  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:30:19.133  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:30:19.135  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:30:19.135  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:19.135  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 13:30:19.136  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 13:30:19.136  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-29 13:30:19.136  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:19.136  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-29 13:30:19.136  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:19.138  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:30:19.138  3311  3373 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 13:30:19.138  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:19.139  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:19.139  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:19.139  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-29 13:30:19.150  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:30:19.151   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:30:19.153  3311  3373 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:19.153  3311  3373 I jxcore-log: 
,03-29 13:30:19.163  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-29 13:30:19.165  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-29 13:30:19.165  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:19.170  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:30:19.171  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-29 13:30:19.171  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:19.171  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:19.171  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:19.171  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:19.171  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:19.171  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:30:19.173  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:19.173  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:19.173  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:19.177  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:19.177  3311  3373 I jxcore-log: 
03-29 13:30:19.179  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:19.179  3311  3373 I jxcore-log: 
,03-29 13:30:19.182  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:19.182  3311  3373 I jxcore-log: 
,03-29 13:30:19.195  3311  3373 I jxcore-log: ok 105 error should be null
03-29 13:30:19.195  3311  3373 I jxcore-log: 
,03-29 13:30:19.196  3311  3373 I jxcore-log: ok 106 error should be null
03-29 13:30:19.196  3311  3373 I jxcore-log: 
,03-29 13:30:19.207  3311  3373 I jxcore-log: # setup
03-29 13:30:19.207  3311  3373 I jxcore-log: 
,03-29 13:30:20.142  3311  3373 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-29 13:30:20.142  3311  3373 I jxcore-log: 
,03-29 13:30:25.999  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:25.999  3311  3373 I jxcore-log: 
,03-29 13:30:26.001  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 53935
03-29 13:30:26.001  3311  3373 I jxcore-log: 
,03-29 13:30:26.007  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:26.007  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:26.007  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:26.010  3311  3373 I jxcore-log: ok 107 error should be null
03-29 13:30:26.010  3311  3373 I jxcore-log: 
,03-29 13:30:26.010  3311  3373 I jxcore-log: ok 108 error should be null
03-29 13:30:26.010  3311  3373 I jxcore-log: 
,03-29 13:30:26.014  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:26.014  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:26.014  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:26.017  3311  3373 I jxcore-log: ok 109 error should be null
03-29 13:30:26.017  3311  3373 I jxcore-log: 
,03-29 13:30:26.018  3311  3373 I jxcore-log: ok 110 error should be null
03-29 13:30:26.018  3311  3373 I jxcore-log: 
03-29 13:30:26.023  3311  3373 I jxcore-log: # teardown
03-29 13:30:26.023  3311  3373 I jxcore-log: ,
,03-29 13:30:28.420  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:28.484  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 13:30:28.485  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:28.485  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:28.485  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:28.499  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:30:28.545  3748  3748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 13:30:28.548  3748  3748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-29 13:30:28.550  3748  3748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-29 13:30:30.176  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:30.177  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:30.177  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:30.179  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:30.179  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:30.179  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:30.186  3311  3373 I jxcore-log: ok 111 error should be null
03-29 13:30:30.186  3311  3373 I jxcore-log: 
,03-29 13:30:30.186  3311  3373 I jxcore-log: ok 112 error should be null
03-29 13:30:30.186  3311  3373 I jxcore-log: ,
03-29 13:30:30.192  3311  3373 I jxcore-log: # setup
03-29 13:30:30.192  3311  3373 I jxcore-log: 
,03-29 13:30:32.626  3311  3373 I jxcore-log: # 30. #start should fail if called twice in a row,
03-29 13:30:32.626  3311  3373 I jxcore-log: 
,03-29 13:30:32.875  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server,
03-29 13:30:32.875  3311  3373 I jxcore-log: 
03-29 13:30:32.878  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 44926
03-29 13:30:32.878  3311  3373 I jxcore-log: 
,03-29 13:30:32.879  3311  3373 I jxcore-log: ok 113 first call should succeed
03-29 13:30:32.879  3311  3373 I jxcore-log: 
,03-29 13:30:32.880  3311  3373 I jxcore-log: ok 114 first call should succeed
03-29 13:30:32.880  3311  3373 I jxcore-log: 
,03-29 13:30:32.883  3311  3373 I jxcore-log: ok 115 specific error should be returned
03-29 13:30:32.883  3311  3373 I jxcore-log: 
,03-29 13:30:32.885  3311  3373 I jxcore-log: # teardown
03-29 13:30:32.885  3311  3373 I jxcore-log: 
,03-29 13:30:33.448  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:33.448  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:33.448  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:33.450  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:33.450  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:33.450  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:33.455  3311  3373 I jxcore-log: ok 116 error should be null
03-29 13:30:33.455  3311  3373 I jxcore-log: 
,03-29 13:30:33.456  3311  3373 I jxcore-log: ok 117 error should be null
03-29 13:30:33.456  3311  3373 I jxcore-log: 
03-29 13:30:33.460  3311  3373 I jxcore-log: # setup
03-29 13:30:33.460  3311  3373 I jxcore-log: 
,03-29 13:30:33.606  3311  3373 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-29 13:30:33.606  3311  3373 I jxcore-log: 
,03-29 13:30:34.499  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:30:34.499  3311  3373 I jxcore-log: 
,03-29 13:30:34.501  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 44256
03-29 13:30:34.501  3311  3373 I jxcore-log: 
,03-29 13:30:34.510  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 55156, start advertisements: false
,03-29 13:30:34.511  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:34.511  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:34.511  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:34.515  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:34.515  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:34.515  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:34.519  2153  2170 D BtGatt.GattService: registerClient() - UUID=8cac42ea-1674-4fb0-9149-8397b1446235
,03-29 13:30:34.520  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=8cac42ea-1674-4fb0-9149-8397b1446235, clientIf=5
03-29 13:30:34.521  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:30:34.521  2153  2219 D BtGatt.GattService: start scan with filters
,03-29 13:30:34.522  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:30:34.522  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:34.523  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:34.523  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:34.523  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:34.523  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:34.523  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:34.523  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:34.523   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:34.528  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 13:30:34.528  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:34.528  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:34.528  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-29 13:30:34.528  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:34.529  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:34.535  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:34.535  3311  3373 I jxcore-log: 
03-29 13:30:34.536  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:34.536  3311  3373 I jxcore-log: 
03-29 13:30:34.537  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:34.537  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:34.539  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 13:30:34.539  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:34.539  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:34.539  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:30:34.542  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:30:34.542  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:34.544  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:30:34.544  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:34.554  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 44256, start advertisements: true
,03-29 13:30:34.554  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:34.554  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:34.554  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:34.558  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 13:30:34.558  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 13:30:34.558  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:34.558  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:30:34.558  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-29 13:30:34.558  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:34.559  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:34.559  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:30:34.562  2153  2219 D BtGatt.GattService: registerClient() - UUID=69c9ba6b-6390-4d62-9386-ccff04576ce4
,03-29 13:30:34.563  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=69c9ba6b-6390-4d62-9386-ccff04576ce4, clientIf=6
03-29 13:30:34.563  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:30:34.564  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:34.569  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:34.573  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 13:30:34.577  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:30:34.578  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 13:30:34.579  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:34.579  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-29 13:30:34.579  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:30:34.579  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:34.579  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:34.579  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 13:30:34.581   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:34.590  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:34.590  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:34.591  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:34.591  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:30:34.591  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:34.593  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:30:34.595  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:34.595  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:34.595  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:34.595  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:34.595  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:34.595  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:34.596  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:30:34.598   821  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-29 13:30:34.599  3311  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:34.604  3311  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:34.615  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:34.615  3311  3373 I jxcore-log: 
,03-29 13:30:34.627  3311  3373 I jxcore-log: ok 118 called only once
,03-29 13:30:34.627  3311  3373 I jxcore-log: 
,03-29 13:30:34.628  3311  3373 I jxcore-log: ok 119 discovery state matches
03-29 13:30:34.628  3311  3373 I jxcore-log: 
,03-29 13:30:34.628  3311  3373 I jxcore-log: ok 120 advertising state matches
03-29 13:30:34.628  3311  3373 I jxcore-log: 
,03-29 13:30:34.637  3311  3373 I jxcore-log: # teardown
03-29 13:30:34.637  3311  3373 I jxcore-log: 
,03-29 13:30:35.427  1226  1483 I Keyboard.Facilitator.LanguageModelFlusher: run(),
,03-29 13:30:35.427  1226  1483 I Keyboard.Facilitator: flushDynamicLanguageModels(),
,03-29 13:30:35.460  1567  1567 I ConfigService: onCreate
,03-29 13:30:35.537  2153  2153 D BtGatt.ScanManager: awakened up at time 223803
03-29 13:30:35.539  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:35.546  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-29 13:30:35.546  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 13:30:35.547  2153  2217 D BtGatt.GattService: current time is 223812771215
03-29 13:30:35.547  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -96, 70, -29, 108, 32, 82, 1, -128, -56, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:30:35.548  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:30:35.548  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:35.550  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-29 13:30:35.551  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-29 13:30:35.551  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 13:30:35.552  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-29 13:30:35.554  1567  1589 I art     : Explicit concurrent mark sweep GC freed 37170(1915KB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.134ms total 69.442ms
,03-29 13:30:35.564  3311  3373 I jxcore-log: DEBUG createPeerListener: createPeerListener,
,03-29 13:30:35.564  3311  3373 I jxcore-log: 
,03-29 13:30:35.571  3311  3373 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-29 13:30:35.571  3311  3373 I jxcore-log: ,
,03-29 13:30:35.575  3311  3373 I jxcore-log: DEBUG createPeerListener: createPeerListener,
03-29 13:30:35.575  3311  3373 I jxcore-log: 
,03-29 13:30:35.577  3311  3373 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-29 13:30:35.577  3311  3373 I jxcore-log: 
,03-29 13:30:36.446  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:36.446  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-29 13:30:36.446  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:30:36.446  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:36.446  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:30:36.447  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:36.447  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:36.447  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:36.447  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 13:30:36.447  3311  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:36.447  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:36.447  3311  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:36.447  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:36.447  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:30:36.447  3311  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:36.449  2153  2169 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:36.451  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:30:36.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:36.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:36.451  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 13:30:36.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:30:36.451  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:36.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:36.451  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:30:36.454  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 13:30:36.454  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:36.455  2153  2228 D BtGatt.ScanManager: stopping BLe Batch,
03-29 13:30:36.456  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:30:36.457  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:30:36.457  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:30:36.458  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:36.458  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:30:36.460  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:30:36.460  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:30:36.461  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:30:36.462  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:36.462  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:30:36.462  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 13:30:36.462  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:36.462  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:36.462  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:36.463  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:36.463  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:36.464  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:30:36.465  3311  3373 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-29 13:30:36.465  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:36.465  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:36.465  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:36.465  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:30:36.466  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 13:30:36.467  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:36.467  2153  2217 D BtGatt.GattService: current time is 224732692360
03-29 13:30:36.467  2153  2217 D BtGatt.GattService: Batch record : [-96, 70, -29, 108, 32, 82, 1, -128, -72, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 13:30:36.467  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:30:36.468  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 13:30:36.475  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 13:30:36.476   821  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:30:36.478  3311  3373 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-29 13:30:36.478  3311  3373 I jxcore-log: 
03-29 13:30:36.478  3311  3373 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:36.478  3311  3373 I jxcore-log: 
03-29 13:30:36.481  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:30:36.482  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-29 13:30:36.482  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:36.482  3311  3373 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:36.482  3311  3373 I jxcore-log: 
,03-29 13:30:36.486  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:30:36.486  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:36.486  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:36.486  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:36.486  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:36.486  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:36.486  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:36.487  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:30:36.489  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:36.489  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:36.489  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:36.491  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:36.491  3311  3373 I jxcore-log: 
,03-29 13:30:36.493  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:36.493  3311  3373 I jxcore-log: 
,03-29 13:30:36.494  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:36.494  3311  3373 I jxcore-log: 
,03-29 13:30:36.503  3311  3373 I jxcore-log: ok 121 error should be null
03-29 13:30:36.503  3311  3373 I jxcore-log: 
03-29 13:30:36.504  3311  3373 I jxcore-log: ok 122 error should be null
03-29 13:30:36.504  3311  3373 I jxcore-log: 
,03-29 13:30:36.512  3311  3373 I jxcore-log: # setup
03-29 13:30:36.512  3311  3373 I jxcore-log: 
,03-29 13:30:37.134  3311  3373 I jxcore-log: # 32. does not send duplicate availability changes
03-29 13:30:37.134  3311  3373 I jxcore-log: 
,03-29 13:30:37.196  2153  2220 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-29 13:30:38.731  3311  3373 I jxcore-log: ok 123 should be called once
,03-29 13:30:38.731  3311  3373 I jxcore-log: 
03-29 13:30:38.732  3311  3373 I jxcore-log: ok 124 should not have been called more than once
03-29 13:30:38.732  3311  3373 I jxcore-log: 
,03-29 13:30:38.737  3311  3373 I jxcore-log: # teardown,
03-29 13:30:38.737  3311  3373 I jxcore-log: 
,03-29 13:30:39.576  3311  3373 I jxcore-log: ok 125 error should be null
03-29 13:30:39.576  3311  3373 I jxcore-log: 
,03-29 13:30:39.577  3311  3373 I jxcore-log: ok 126 error should be null
03-29 13:30:39.577  3311  3373 I jxcore-log: 
,03-29 13:30:39.585  3311  3373 I jxcore-log: # setup
03-29 13:30:39.585  3311  3373 I jxcore-log: 
,03-29 13:30:39.632   821   821 I art     : Explicit concurrent mark sweep GC freed 30025(1397KB) AllocSpace objects, 7(677KB) LOS objects, 32% free, 33MB/49MB, paused 1.002ms total 57.062ms
,03-29 13:30:39.643  3546  3867 I BooksSync: Starting books sync for 61035162, extras: ade
,03-29 13:30:39.643  1567  2139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 13:30:39.643  1567  2139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:39.643  1567  2139 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:39.643  1567  2139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:39.646  1567  2139 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:39.657  3114  3866 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-29 13:30:39.657  3114  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jdm.a(PG:82)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jcs.o(PG:406)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jcn.a(PG:1379)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jcs.i(PG:143)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at blb.a(PG:3937)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at czp.a(PG:18188)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at czp.a(PG:9081)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at czq.run(PG:1686)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:30:39.657  3114  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jdj.a(PG:4091)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jdj.a(PG:1125)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jdm.a(PG:77)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	... 12 more
03-29 13:30:39.657  3114  3866 E HttpOperation: Caused by: faj: BadAuthentication
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at fal.a(PG:38)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	at jdj.a(PG:4089)
03-29 13:30:39.657  3114  3866 E HttpOperation: 	... 14 more
,03-29 13:30:39.664  3546  3868 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-29 13:30:39.689  1567  2581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-29 13:30:39.689  1567  2581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:39.689  1567  2581 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:39.689  1567  2581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:39.692  1567  2581 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:39.694  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 13:30:39.694  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:39.694  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:39.694  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:39.700  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:39.713  3114  3866 E HttpOperation: [getmobileexperiments] Unexpected exception
03-29 13:30:39.713  3114  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jdm.a(PG:82)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jcs.o(PG:406)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jcn.a(PG:1379)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jcs.i(PG:143)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at hec.a(PG:42)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at hee.a(PG:102)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at czr.a(PG:65)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at kka.a(PG:108)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at czp.a(PG:19176)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at czp.a(PG:9081)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at czq.run(PG:1686)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:30:39.713  3114  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jdj.a(PG:4091)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jdj.a(PG:1125)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jdm.a(PG:77)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	... 15 more
03-29 13:30:39.713  3114  3866 E HttpOperation: Caused by: faj: BadAuthentication
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at fal.a(PG:38)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	at jdj.a(PG:4089)
03-29 13:30:39.713  3114  3866 E HttpOperation: 	... 17 more
03-29 13:30:39.713  3114  3866 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-29 13:30:39.713  3114  3866 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jdm.a(PG:82)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jcs.o(PG:406)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jcn.a(PG:1379)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jcs.i(PG:143)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at hec.a(PG:42)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at hee.a(PG:102)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at czr.a(PG:65)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at kka.a(PG:108)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at czp.a(PG:19176)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at czp.a(PG:9081)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at czq.run(PG:1686)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jdj.a(PG:4091)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jdm.a(PG:77)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	... 15 more
03-29 13:30:39.713  3114  3866 E ExperimentLoader: Caused by: faj: BadAuthentication
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at fal.a(PG:38)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	at jdj.a(PG:4089)
03-29 13:30:39.713  3114  3866 E ExperimentLoader: 	... 17 more
,03-29 13:30:39.783  1567  2139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-29 13:30:39.784  1567  2139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:39.784  1567  2139 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:39.784  1567  2139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:39.789  1567  2139 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:39.802  3546  3868 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-29 13:30:39.805  3546  3867 E BooksSync: Soft error
03-29 13:30:39.805  3546  3867 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 13:30:39.805  3546  3867 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 13:30:39.805  3546  3867 E BooksSync: Sync error
03-29 13:30:39.805  3546  3867 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-29 13:30:39.805  3546  3867 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-29 13:30:39.805  3546  3867 I BooksSync: Finished books sync
,03-29 13:30:39.811   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200003, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 13:30:39.847  3518  3871 V KeepSync: Connecting to GoogleApiClient
,03-29 13:30:39.859   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 199575, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-29 13:30:39.910  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-29 13:30:39.910  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:39.910  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:39.910  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:39.915  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: Handling authorization failure
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178),
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-29 13:30:39.933  1757  3873 E ClientConnectionOperation: 	... 7 more
,03-29 13:30:39.940  3518  3871 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-29 13:30:39.945  3518  3871 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 13:30:39.956  3518  3871 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 13:30:39.957  3518  3871 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-29 13:30:40.049  1567  1589 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-29 13:30:40.050  1567  1589 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:30:40.050  1567  1589 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:40.050  1567  1589 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:40.061  1567  1589 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:30:40.138  3518  3871 E KeepSync: IOException
03-29 13:30:40.138  3518  3871 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-29 13:30:40.138  3518  3871 E KeepSync: 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-29 13:30:40.138  3518  3871 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-29 13:30:40.138  3518  3871 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-29 13:30:40.138  3518  3871 E KeepSync: 	... 10 more
,03-29 13:30:40.138  3518  3871 W KeepSync: Sync result 2
,03-29 13:30:40.147   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201708, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-29 13:30:40.168  3311  3373 I jxcore-log: # 33. can get the network status
03-29 13:30:40.168  3311  3373 I jxcore-log: 
,03-29 13:30:40.625  1567  1567 I ConfigService: onDestroy
,03-29 13:30:44.611  3311  3373 I jxcore-log: ok 127 network status should have certain non-empty properties
03-29 13:30:44.611  3311  3373 I jxcore-log: 
,03-29 13:30:44.615  3311  3373 I jxcore-log: # teardown
03-29 13:30:44.615  3311  3373 I jxcore-log: 
,03-29 13:30:45.157  3311  3373 I jxcore-log: ok 128 error should be null
03-29 13:30:45.157  3311  3373 I jxcore-log: 
,03-29 13:30:45.159  3311  3373 I jxcore-log: ok 129 error should be null
03-29 13:30:45.159  3311  3373 I jxcore-log: 
,03-29 13:30:45.177  3311  3373 I jxcore-log: # setup
,03-29 13:30:45.177  3311  3373 I jxcore-log: 
,03-29 13:30:46.451  3311  3373 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-29 13:30:46.451  3311  3373 I jxcore-log: 
,03-29 13:30:46.624  3311  3373 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-29 13:30:46.624  3311  3373 I jxcore-log: 
,03-29 13:30:46.648  3311  3373 I jxcore-log: ok 130 host address should match
03-29 13:30:46.648  3311  3373 I jxcore-log: 
,03-29 13:30:46.648  3311  3373 I jxcore-log: ok 131 port should match
03-29 13:30:46.648  3311  3373 I jxcore-log: 
,03-29 13:30:48.628  3311  3373 I jxcore-log: ok 132 host address should be null
03-29 13:30:48.628  3311  3373 I jxcore-log: 
,03-29 13:30:48.629  3311  3373 I jxcore-log: ok 133 port should should be null
03-29 13:30:48.629  3311  3373 I jxcore-log: 
,03-29 13:30:48.654  3311  3373 I jxcore-log: # teardown
03-29 13:30:48.654  3311  3373 I jxcore-log: 
,03-29 13:30:49.220  3311  3373 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-29 13:30:49.220  3311  3373 I jxcore-log: 
,03-29 13:30:49.222  3311  3373 I jxcore-log: ok 134 error should be null
03-29 13:30:49.222  3311  3373 I jxcore-log: 
03-29 13:30:49.222  3311  3373 I jxcore-log: ok 135 error should be null
03-29 13:30:49.222  3311  3373 I jxcore-log: 
,03-29 13:30:49.225  3311  3373 I jxcore-log: # setup
03-29 13:30:49.225  3311  3373 I jxcore-log: 
,03-29 13:30:49.377  3311  3373 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-29 13:30:49.377  3311  3373 I jxcore-log: 
,03-29 13:30:49.598  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 44256, start advertisements: false
,03-29 13:30:49.599  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:49.599  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:30:49.599  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:49.604  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:49.605  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:49.605  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:49.611  2153  2219 D BtGatt.GattService: registerClient() - UUID=6fe0bc8c-726a-4add-9c6c-b56e1a4871a5,
03-29 13:30:49.611  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=6fe0bc8c-726a-4add-9c6c-b56e1a4871a5, clientIf=5
03-29 13:30:49.612  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 13:30:49.612  2153  2170 D BtGatt.GattService: start scan with filters
03-29 13:30:49.614  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:30:49.614  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:30:49.614  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:49.614  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:49.615  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:49.615  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:49.615  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:49.615  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:49.616   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:49.623  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 13:30:49.623  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:49.624  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:49.624  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:49.625  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:49.625  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK,
03-29 13:30:49.629  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:49.630  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:49.630  3311  3373 I jxcore-log: ok 136 Can call startListeningForAdvertisements without error
03-29 13:30:49.630  3311  3373 I jxcore-log: 
03-29 13:30:49.631  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:49.631  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:30:49.631  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:49.631  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:49.632  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:49.632  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:30:49.632  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:30:49.632  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:49.635  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-29 13:30:49.635  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:49.635  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:49.637  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:30:49.637  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:49.637  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:30:49.638  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:49.638  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:49.638  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:49.638  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 13:30:49.638  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-29 13:30:49.638  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:49.639  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:49.640  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:30:49.640  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:49.641  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:30:49.641  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:49.641  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:49.641  3311  3373 I jxcore-log: 
03-29 13:30:49.642  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:49.642  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:49.642  3311  3373 I jxcore-log: 
,03-29 13:30:49.645  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:30:49.645  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:49.645  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:49.646  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:30:49.647  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:49.655  3311  3373 I jxcore-log: ok 137 Can call stopListeningForAdvertisements without error
03-29 13:30:49.655  3311  3373 I jxcore-log: 
,03-29 13:30:49.671  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:49.671  3311  3373 I jxcore-log: 
03-29 13:30:49.674  3311  3373 I jxcore-log: # teardown
03-29 13:30:49.674  3311  3373 I jxcore-log: 
,03-29 13:30:49.867  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:49.870  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:49.871  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-29 13:30:49.871  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:49.875  3311  3373 I jxcore-log: ok 138 Should be able to call stopListeningForAdvertisments in teardown,
03-29 13:30:49.875  3311  3373 I jxcore-log: 
,03-29 13:30:49.877  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:49.878  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-29 13:30:49.878  3311  3373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 13:30:49.878  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:30:49.878  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:49.878  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:49.878  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:49.878  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:49.881  3311  3373 D BluetoothLeScanner: could not find callback wrapper
03-29 13:30:49.881  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:49.882  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:49.882  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:49.883  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:49.884  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:30:49.884  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:49.885  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:49.885  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:49.885  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:49.896  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:49.897   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:49.907  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:49.908  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:49.908  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:49.912  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:49.912  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:49.912  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:49.915  3311  3373 I jxcore-log: ok 139 Should be able to call stopAdvertisingAndListening in teardown
,03-29 13:30:49.915  3311  3373 I jxcore-log: 
,03-29 13:30:49.924  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-29 13:30:49.924  3311  3373 I jxcore-log: 
,03-29 13:30:49.927  3311  3373 I jxcore-log: # setup
03-29 13:30:49.927  3311  3373 I jxcore-log: ,
,03-29 13:30:49.930  1567  1589 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 13:30:49.930  1567  1589 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 13:30:49.930  1567  1589 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:30:49.930  1567  1589 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:30:49.936  1567  1589 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:30:49.955  3748  3748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 13:30:49.955  3748  3748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 13:30:49.956  3748  3748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-29 13:30:50.342  3311  3373 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error,
03-29 13:30:50.342  3311  3373 I jxcore-log: 
,03-29 13:30:50.496  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 44256, start advertisements: false,
03-29 13:30:50.496  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:50.497  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:50.497  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:30:50.506  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:50.506  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:50.506  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:50.517  2153  2169 D BtGatt.GattService: registerClient() - UUID=278089f0-a203-4d1b-84b7-9c21d6319efe
,03-29 13:30:50.517  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=278089f0-a203-4d1b-84b7-9c21d6319efe, clientIf=5
03-29 13:30:50.518  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 13:30:50.519  2153  2170 D BtGatt.GattService: start scan with filters
,03-29 13:30:50.522  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:30:50.525  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:30:50.525  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:30:50.527  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:50.527  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-29 13:30:50.527  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:50.527  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:50.527  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:50.528  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:50.528  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:50.529   821  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:30:50.531  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 13:30:50.531  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:50.532  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:50.532  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:30:50.536  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:30:50.536  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:50.538  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:30:50.539  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:50.543  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:50.543  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:50.543  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:50.544  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:50.544  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:50.544  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:50.548  3311  3373 I jxcore-log: ok 140 Can call startListeningForAdvertisements without error
03-29 13:30:50.548  3311  3373 I jxcore-log: 
,03-29 13:30:50.553  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 44256, start advertisements: false,
03-29 13:30:50.553  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:50.553  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:30:50.553  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:50.553  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:50.555  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:50.555  3311  3373 I jxcore-log: 
03-29 13:30:50.555  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:50.555  3311  3373 I jxcore-log: 
,03-29 13:30:50.557  3311  3373 I jxcore-log: ok 141 Can call startListeningForAdvertisements twice without error
03-29 13:30:50.557  3311  3373 I jxcore-log: 
,03-29 13:30:50.563  3311  3373 I jxcore-log: # teardown
03-29 13:30:50.563  3311  3373 I jxcore-log: 
,03-29 13:30:51.043  2153  2153 D BtGatt.ScanManager: awakened up at time 239309
,03-29 13:30:51.045  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:51.054  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-29 13:30:51.054  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:51.159  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:51.160  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:51.160  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-29 13:30:51.160  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:30:51.164  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:51.166  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:30:51.168  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 13:30:51.169  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.169  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:51.169  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:51.170  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:30:51.170  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:51.171  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 13:30:51.171  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:30:51.171  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:51.173  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:51.173  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:30:51.174  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:30:51.174  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.174  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:30:51.175  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:51.176  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:30:51.176  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.178  3311  3373 I jxcore-log: ok 142 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:30:51.178  3311  3373 I jxcore-log: 
,03-29 13:30:51.179  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:51.179  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.180  3311  3373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 13:30:51.180  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:51.180  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:51.180  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:51.180  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:51.180  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:51.181  3311  3373 D BluetoothLeScanner: could not find callback wrapper
,03-29 13:30:51.181  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:51.183  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:51.183  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:51.184  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:51.186  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:30:51.186  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:51.186  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:51.186  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:51.186  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:30:51.189  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:51.189  3311  3373 I jxcore-log: 
,03-29 13:30:51.196  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-29 13:30:51.197   821  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:51.202  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:51.202  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:30:51.202  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:51.205  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-29 13:30:51.205  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:30:51.205  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:51.207  3311  3373 I jxcore-log: ok 143 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:51.207  3311  3373 I jxcore-log: 
03-29 13:30:51.213  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:51.213  3311  3373 I jxcore-log: 
03-29 13:30:51.214  3311  3373 I jxcore-log: # setup
03-29 13:30:51.214  3311  3373 I jxcore-log: 
,03-29 13:30:51.385  3311  3373 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-29 13:30:51.385  3311  3373 I jxcore-log: 
,03-29 13:30:51.592  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 13:30:51.592  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:51.592  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:51.592  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:51.600  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:51.600  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:51.601  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:51.601  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:51.610  2153  2170 D BtGatt.GattService: registerClient() - UUID=951e2b76-e455-4872-9148-3b39450fc98c
,03-29 13:30:51.612  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=951e2b76-e455-4872-9148-3b39450fc98c, clientIf=5
,03-29 13:30:51.613  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:30:51.613  2153  2169 D BtGatt.GattService: start scan with filters,
03-29 13:30:51.616  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:30:51.617  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:30:51.617  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:51.617  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-29 13:30:51.617  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 13:30:51.618  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:51.618  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 13:30:51.618  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:51.618  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:30:51.618  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:30:51.619  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:30:51.619  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:51.620  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:30:51.621  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:51.621  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.624  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 13:30:51.624  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.625  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:51.625  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:30:51.629  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:30:51.629  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 13:30:51.631  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:30:51.631  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:51.638  2153  2170 D BtGatt.GattService: registerClient() - UUID=b04fd5b1-3e2d-4953-993c-7c8f4c00b97d
,03-29 13:30:51.639  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=b04fd5b1-3e2d-4953-993c-7c8f4c00b97d, clientIf=6
03-29 13:30:51.639  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:51.641  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:51.646  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:51.651  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:30:51.654  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-29 13:30:51.655  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:30:51.655  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:30:51.656   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:51.660  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 13:30:51.660  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:51.660  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:51.660  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:51.661  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:30:51.662  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:51.662  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:51.662  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:51.662  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:51.662  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:51.663  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:51.663  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-29 13:30:51.663  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:51.663  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:51.663  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:51.663  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:51.664  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:51.664  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:51.664  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:51.664  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:30:51.665  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:51.665  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:51.665  3311  3373 I jxcore-log: 
03-29 13:30:51.666  3311  3373 I jxcore-log: ok 144 Can call startUpdateAdvertisingAndListening without error
03-29 13:30:51.666  3311  3373 I jxcore-log: 
03-29 13:30:51.667  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:51.667  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything,
03-29 13:30:51.667  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:30:51.667  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:51.667  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-29 13:30:51.668  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:51.668  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-29 13:30:51.668  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:51.668  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:51.668  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:30:51.668  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:51.668  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:30:51.669   821  1403 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:51.671  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:51.672  3311  3877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:30:51.673  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:30:51.673  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:51.673  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:51.673  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:51.673  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:30:51.673  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:51.673  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:30:51.673  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:51.674  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:30:51.674  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.675  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:51.676  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:30:51.677  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:30:51.678  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:30:51.678  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.678  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:30:51.680  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:30:51.680  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:30:51.681  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:30:51.682  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:51.682  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:51.682  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:30:51.682  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:51.682  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:51.682  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:51.682  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:51.682  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:51.682  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:30:51.683  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:51.683  3311  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:51.683  3311  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:51.684  3311  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:30:51.687  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:51.687  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:51.687  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:51.687  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:51.687  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:51.690  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:51.690  3311  3373 I jxcore-log: 
,03-29 13:30:51.693  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:51.693   821  1406 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:30:51.694  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:51.694  3311  3373 I jxcore-log: 
,03-29 13:30:51.700  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:30:51.700  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:51.700  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:51.703  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:30:51.703  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.704  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:51.704  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.704  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:30:51.704  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:51.704  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:51.704  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.704  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:51.704  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:30:51.705  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:51.705  3311  3373 I jxcore-log: 
03-29 13:30:51.706  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:51.706  3311  3373 I jxcore-log: 
03-29 13:30:51.707  3311  3373 I jxcore-log: ok 145 Can call stopAdvertisingAndListening without error
03-29 13:30:51.707  3311  3373 I jxcore-log: 
03-29 13:30:51.712  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:51.712  3311  3373 I jxcore-log: 
03-29 13:30:51.714  3311  3373 I jxcore-log: # teardown
03-29 13:30:51.714  3311  3373 I jxcore-log: 
,03-29 13:30:51.953  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:30:51.953  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:30:51.953  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:51.958  3311  3373 I jxcore-log: ok 146 Should be able to call stopListeningForAdvertisments in teardown
,03-29 13:30:51.958  3311  3373 I jxcore-log: 
,03-29 13:30:51.960  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:30:51.961  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:51.961  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:51.964  3311  3373 I jxcore-log: ok 147 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:51.964  3311  3373 I jxcore-log: 
,03-29 13:30:51.970  3311  3373 I jxcore-log: # setup
,03-29 13:30:51.970  3311  3373 I jxcore-log: 
,03-29 13:30:52.124  3311  3373 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-29 13:30:52.124  3311  3373 I jxcore-log: 
,03-29 13:30:52.243  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 13:30:52.243  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:52.243  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:52.243  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:52.254  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:52.254  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:52.255  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:52.255  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:52.267  2153  2169 D BtGatt.GattService: registerClient() - UUID=8c6adc7d-2199-4fa2-ae9d-424119d6eca9,
,03-29 13:30:52.268  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=8c6adc7d-2199-4fa2-ae9d-424119d6eca9, clientIf=5,
03-29 13:30:52.269  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 13:30:52.271  2153  2170 D BtGatt.GattService: start scan with filters
03-29 13:30:52.274  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:30:52.280  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:30:52.280  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-29 13:30:52.280  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:52.280  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 13:30:52.281  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:52.281  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:52.281  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:52.283  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-29 13:30:52.283  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:30:52.285  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:30:52.285  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:52.285  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:52.287  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:30:52.288  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:30:52.289  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 13:30:52.289  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:52.289  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:30:52.289  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:30:52.293  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:30:52.293  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:52.296  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 13:30:52.296  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:52.307  2153  2219 D BtGatt.GattService: registerClient() - UUID=fd28f4d0-a747-4d74-a9dc-fafbdb928048
,03-29 13:30:52.308  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=fd28f4d0-a747-4d74-a9dc-fafbdb928048, clientIf=6,
03-29 13:30:52.309  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:30:52.311  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:52.318  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:52.322  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:30:52.326  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:30:52.327  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:30:52.327  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:30:52.328   821  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:30:52.335  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:52.335  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:52.335  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 13:30:52.335  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:52.337  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:30:52.337  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:52.337  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 13:30:52.338  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:52.338  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:52.339  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:52.339  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
,03-29 13:30:52.339  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:52.339  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:52.339  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:52.339  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:52.339  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:52.339  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:52.340  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:52.340  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:52.340  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:52.340  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:52.341   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:30:52.344  3311  3878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:52.345  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:52.345  3311  3373 I jxcore-log: 
03-29 13:30:52.348  3311  3373 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening without error
03-29 13:30:52.348  3311  3373 I jxcore-log: 
,03-29 13:30:52.349  3311  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:30:52.356  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-29 13:30:52.356  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:52.356  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 13:30:52.357  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:52.357  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:52.360  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:52.360  3311  3373 I jxcore-log: 
03-29 13:30:52.362  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:52.362  3311  3373 I jxcore-log: 
03-29 13:30:52.365  3311  3373 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening twice without error
03-29 13:30:52.365  3311  3373 I jxcore-log: 
,03-29 13:30:52.377  3311  3373 I jxcore-log: # teardown
03-29 13:30:52.377  3311  3373 I jxcore-log: 
,03-29 13:30:53.304  2153  2153 D BtGatt.ScanManager: awakened up at time 241569
,03-29 13:30:53.306  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:53.316  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 13:30:53.316  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:53.316  2153  2217 D BtGatt.GattService: current time is 241582219698
03-29 13:30:53.317  2153  2217 D BtGatt.GattService: Batch record : [-41, 29, 57, -26, -43, 70, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-29 13:30:53.317  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:30:53.318  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 13:30:53.321  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-29 13:30:53.322  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-29 13:30:53.322  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 13:30:53.323  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-29 13:30:53.327  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 13:30:53.327  3311  3373 I jxcore-log: 
03-29 13:30:53.329  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-29 13:30:53.329  3311  3373 I jxcore-log: 
,03-29 13:30:53.744  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:30:53.744  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 13:30:53.744  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:30:53.745  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:53.750  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:30:53.752  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:30:53.755  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 13:30:53.755  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:53.755  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:53.755  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:53.755  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:53.755  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-29 13:30:53.756  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:30:53.756  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:53.756  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:53.757  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:53.757  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:30:53.757  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:53.759  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 13:30:53.759  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-29 13:30:53.760  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:53.762  3311  3373 I jxcore-log: ok 150 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:30:53.762  3311  3373 I jxcore-log: 
03-29 13:30:53.763  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 13:30:53.763  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:53.763  2153  2217 D BtGatt.GattService: current time is 242029328343
03-29 13:30:53.764  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -59, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -41, 29, 57, -26, -43, 70, 1, -128, -81, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-29 13:30:53.764  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:53.764  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:30:53.765  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:30:53.765  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:53.765  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:30:53.765  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 13:30:53.765  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:30:53.767  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:53.769  3311  3878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:53.769  3311  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:53.769  3311  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:53.769  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:30:53.770  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:53.771  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:53.771  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:53.771  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 13:30:53.771  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:53.771  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-29 13:30:53.771  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-29 13:30:53.773  3311  3373 D BluetoothLeScanner: could not find callback wrapper
03-29 13:30:53.773  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:53.773  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:53.779  2153  2227 D BtGatt.AdvertiseManager: message : 1
,03-29 13:30:53.780  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:30:53.784  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:30:53.784  2153  2217 D BtGatt.GattService: Client app is not null!
,03-29 13:30:53.786  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-29 13:30:53.786  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:30:53.786  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:53.786  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 13:30:53.787  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:53.787  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:53.787  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:53.787  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:53.787  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:53.788  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:53.788  3311  3373 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-29 13:30:53.788  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:53.789  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:53.789  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:53.789  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:53.789  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:53.789  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:30:53.795  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:53.795  3311  3373 I jxcore-log: 
,03-29 13:30:53.796  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:30:53.797   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:53.805  3311  3373 I jxcore-log: ok 151 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:53.805  3311  3373 I jxcore-log: 
,03-29 13:30:53.805  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:30:53.806  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:53.806  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:53.809  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:30:53.810  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:53.812  3311  3373 I jxcore-log: # setup
03-29 13:30:53.812  3311  3373 I jxcore-log: 
,03-29 13:30:53.819  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:53.819  3311  3373 I jxcore-log: 
,03-29 13:30:53.820  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:30:53.820  3311  3373 I jxcore-log: 
,03-29 13:30:54.077  3311  3373 I jxcore-log: # 39. peerAvailabilityChange is called
,03-29 13:30:54.077  3311  3373 I jxcore-log: 
,03-29 13:30:54.394  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-29 13:30:54.395  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:54.395  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:54.395  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:54.401  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:54.401  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:30:54.401  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:54.401  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:54.408  2153  2169 D BtGatt.GattService: registerClient() - UUID=dd72618f-e5b2-44d0-9228-f33cdbb29798,
,03-29 13:30:54.408  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=dd72618f-e5b2-44d0-9228-f33cdbb29798, clientIf=5
,03-29 13:30:54.409  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:30:54.409  2153  2170 D BtGatt.GattService: start scan with filters
,03-29 13:30:54.412  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-29 13:30:54.412  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:30:54.413  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:30:54.413  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:30:54.413  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:54.413  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:54.413  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:30:54.414  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:30:54.414  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:30:54.414  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-29 13:30:54.417  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:54.417  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:54.418  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:30:54.421  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 13:30:54.421  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:54.423  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:30:54.423  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:54.423  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:30:54.424  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:30:54.426  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-29 13:30:54.427  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:54.428  2153  2219 D BtGatt.GattService: registerClient() - UUID=fed5c53d-b843-46ff-a23b-34f6d442bf2a
03-29 13:30:54.428  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=fed5c53d-b843-46ff-a23b-34f6d442bf2a, clientIf=6
,03-29 13:30:54.429  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:30:54.431  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:30:54.431  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:54.432  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:30:54.438  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:30:54.442  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:30:54.445  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:30:54.446  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:54.446  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:30:54.447   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:54.453  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:54.454  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:30:54.454  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 13:30:54.454  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:54.456  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:30:54.456  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 13:30:54.456  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:54.457  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 13:30:54.457  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:54.458  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:54.458  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-29 13:30:54.458  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:54.458  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 13:30:54.458  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:30:54.458  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:30:54.459  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:54.459  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 13:30:54.459  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:54.459   821  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:54.459  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:54.459  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:54.460  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:30:54.462  3311  3882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:54.466  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:54.466  3311  3373 I jxcore-log: 
,03-29 13:30:54.471  3311  3373 I jxcore-log: ok 152 Can call startUpdateAdvertisingAndListeningwithout error
03-29 13:30:54.471  3311  3373 I jxcore-log: 
03-29 13:30:54.474  3311  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:30:54.479  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-29 13:30:54.479  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:30:54.479  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 13:30:54.479  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:30:54.479  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:54.482  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:54.482  3311  3373 I jxcore-log: 
03-29 13:30:54.485  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:54.485  3311  3373 I jxcore-log: 
,03-29 13:30:54.488  3311  3373 I jxcore-log: ok 153 Can call startListeningForAdvertisements without error
03-29 13:30:54.488  3311  3373 I jxcore-log: 
,03-29 13:30:55.436  2153  2153 D BtGatt.ScanManager: awakened up at time 243702
,03-29 13:30:55.439  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:55.448  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 13:30:55.448  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:55.448  2153  2217 D BtGatt.GattService: current time is 243714181311
03-29 13:30:55.449  2153  2217 D BtGatt.GattService: Batch record : [73, 94, -23, -116, 61, 117, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -56, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-29 13:30:55.449  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:30:55.450  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:30:55.451  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-29 13:30:55.452  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-29 13:30:55.452  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-29 13:30:55.453  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-29 13:30:55.455  3311  3373 I jxcore-log: ok 154 peers must be an array
03-29 13:30:55.455  3311  3373 I jxcore-log: 
03-29 13:30:55.455  3311  3373 I jxcore-log: ok 155 peers must not be zero-length
03-29 13:30:55.455  3311  3373 I jxcore-log: 
,03-29 13:30:55.456  3311  3373 I jxcore-log: ok 156 peer must have peerIdentifier
03-29 13:30:55.456  3311  3373 I jxcore-log: 
03-29 13:30:55.457  3311  3373 I jxcore-log: ok 157 peerIdentifier must be a string
03-29 13:30:55.457  3311  3373 I jxcore-log: 
03-29 13:30:55.457  3311  3373 I jxcore-log: ok 158 peer must have peerAvailable
03-29 13:30:55.457  3311  3373 I jxcore-log: 
,03-29 13:30:55.457  3311  3373 I jxcore-log: ok 159 peer must have pleaseConnect
03-29 13:30:55.457  3311  3373 I jxcore-log: 
,03-29 13:30:55.465  3311  3373 I jxcore-log: # teardown
03-29 13:30:55.465  3311  3373 I jxcore-log: 
,03-29 13:30:55.851  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 13:30:55.851  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:30:55.851  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:30:55.851  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:30:55.856  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:30:55.858  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:30:55.858  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:30:55.859  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:55.859  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:30:55.859  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:30:55.859  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:30:55.859  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:30:55.859  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:55.859  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:55.859  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:30:55.859  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:30:55.860  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:30:55.860  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:55.862  3311  3373 I jxcore-log: ok 160 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:30:55.862  3311  3373 I jxcore-log: 
03-29 13:30:55.863  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:30:55.863  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:55.863  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:30:55.863  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:30:55.863  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:30:55.863  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:30:55.863  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:30:55.863  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:30:55.864  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:30:55.864  3311  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:30:55.864  3311  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:30:55.864  3311  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:30:55.865  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:30:55.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:30:55.866  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:30:55.866  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:30:55.866  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:30:55.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:30:55.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:30:55.866  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:30:55.866  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 13:30:55.866  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:55.866  2153  2217 D BtGatt.GattService: current time is 244132214124
03-29 13:30:55.866  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 73, 94, -23, -116, 61, 117, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:30:55.867  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:30:55.867  3311  3373 D BluetoothLeScanner: could not find callback wrapper
03-29 13:30:55.867  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:30:55.867  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:30:55.867  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:30:55.877  2153  2227 D BtGatt.AdvertiseManager: message : 1
,03-29 13:30:55.878  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 13:30:55.881  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:30:55.881  2153  2217 D BtGatt.GattService: Client app is not null!
,03-29 13:30:55.882  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-29 13:30:55.882  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:30:55.883  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:30:55.883  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 13:30:55.883  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:30:55.883  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:30:55.883  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-29 13:30:55.883  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:30:55.883  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:30:55.883  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:30:55.883  3311  3373 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear,
03-29 13:30:55.883  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:30:55.884  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:30:55.884  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:30:55.884  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:30:55.884  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:30:55.884  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:30:55.886  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:30:55.886  3311  3373 I jxcore-log: 
03-29 13:30:55.888  3311  3373 I jxcore-log: ok 161 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:30:55.888  3311  3373 I jxcore-log: 
,03-29 13:30:55.892  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:30:55.892   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-29 13:30:55.894  3311  3373 I jxcore-log: # setup
03-29 13:30:55.894  3311  3373 I jxcore-log: 
,03-29 13:30:55.899  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-29 13:30:55.900  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:30:55.900  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:30:55.905  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 13:30:55.905  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:30:55.907  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 13:30:55.907  3311  3373 I jxcore-log: 
,03-29 13:30:55.914  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 13:30:55.914  3311  3373 I jxcore-log: 
,03-29 13:30:56.485  3311  3373 I jxcore-log: # 40. Can connect to a remote peer,
,03-29 13:30:56.485  3311  3373 I jxcore-log: 
,03-29 13:30:56.737  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 37681, start advertisements: true
,03-29 13:30:56.737  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:56.737  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:30:56.738  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:30:56.746  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:30:56.746  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:30:56.746  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:30:56.746  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:30:56.756  2153  2170 D BtGatt.GattService: registerClient() - UUID=ef7be0a9-8c7f-497c-804d-99b3068c7f82,
03-29 13:30:56.757  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=ef7be0a9-8c7f-497c-804d-99b3068c7f82, clientIf=5
03-29 13:30:56.757  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-29 13:30:56.758  2153  2169 D BtGatt.GattService: start scan with filters
,03-29 13:30:56.760  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:30:56.760  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:30:56.760  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-29 13:30:56.760  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:30:56.760  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-29 13:30:56.760  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-29 13:30:56.761  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:30:56.761  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:30:56.761  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:30:56.761  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:30:56.761  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:30:56.761  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:30:56.761  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:30:56.772  2153  2170 D BtGatt.GattService: registerClient() - UUID=b6fb7c43-f57f-4fcf-9190-cb9bbb9fc01e
03-29 13:30:56.774  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=b6fb7c43-f57f-4fcf-9190-cb9bbb9fc01e, clientIf=6
03-29 13:30:56.775  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:30:56.775  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:56.775  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:30:56.777  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,03-29 13:30:56.778  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:30:56.778  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:30:56.778  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-29 13:30:56.778  2153  2227 D BtGatt.AdvertiseManager: message : 0
03-29 13:30:56.781  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-29 13:30:56.781  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:56.785  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 13:30:56.785  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:56.786  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
03-29 13:30:56.790  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 13:30:56.792  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:30:56.793  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:30:56.793  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:30:56.794   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:56.799  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:30:56.799  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:30:56.799  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:30:56.799  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:30:56.801  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:30:56.801  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:30:56.801  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:30:56.801  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:30:56.802  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:56.802  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:30:56.802  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:30:56.802  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:30:56.802   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:30:56.802  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:30:56.803  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:30:56.803  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 13:30:56.803  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:56.803  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:30:56.803  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:30:56.803  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:30:56.804  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:30:56.804  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:30:56.804  3311  3883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:56.807  3311  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:30:56.807  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:56.807  3311  3373 I jxcore-log: 
03-29 13:30:56.809  3311  3373 I jxcore-log: ok 162 Can call startUpdateAdvertisingAndListening without error
03-29 13:30:56.809  3311  3373 I jxcore-log: 
,03-29 13:30:56.813  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 37681, start advertisements: false
03-29 13:30:56.813  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:30:56.813  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 13:30:56.813  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:30:56.813  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:30:56.814  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:30:56.814  3311  3373 I jxcore-log: 
,03-29 13:30:56.815  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:30:56.815  3311  3373 I jxcore-log: 
,03-29 13:30:56.816  3311  3373 I jxcore-log: ok 163 Can call startListeningForAdvertisements without error
03-29 13:30:56.816  3311  3373 I jxcore-log: 
,03-29 13:30:57.790  2153  2153 D BtGatt.ScanManager: awakened up at time 246056,
,03-29 13:30:57.794  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:30:57.806  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 13:30:57.806  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:30:57.806  2153  2217 D BtGatt.GattService: current time is 246072317144
03-29 13:30:57.807  2153  2217 D BtGatt.GattService: Batch record : [110, 107, -32, 25, 105, 114, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-29 13:30:57.807  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:30:57.808  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:30:57.811  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-29 13:30:57.812  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-29 13:30:57.812  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 13:30:57.813  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-29 13:30:57.820  3311  3373 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-29 13:30:57.820  3311  3373 I jxcore-log: 
,03-29 13:30:57.834  3311  3373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-29 13:30:57.835  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51],
,03-29 13:30:57.841  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-29 13:30:57.842  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-29 13:30:57.842  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-29 13:30:57.843  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-29 13:30:57.844  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-29 13:30:57.844  3311  3373 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-29 13:30:57.846  3311  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 361)
03-29 13:30:57.847  3311  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:30:57.848  3311  3373 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-29 13:30:57.848  3311  3373 I jxcore-log: 
03-29 13:30:57.851  2153  2219 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 13:30:59.299  2153  2229 W bt-btif : info:x10
03-29 13:30:59.300  2153  2217 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-29 13:30:59.300  2153  2217 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 13:31:00.091  2153  2217 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-29 13:31:00.101  2153  2217 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-29 13:31:00.102  2153  2217 E bt-btif : check_cod: remote_cod = 0x5a020c,
,03-29 13:31:00.106  2153  2218 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-29 13:31:00.107  2153  2218 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 13:31:00.176   821   855 I ActivityManager: Start proc 3886:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-29 13:31:00.277   821   859 D BluetoothManagerService: Message: 20
03-29 13:31:00.278   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25a2f54d:true
,03-29 13:31:00.281   821  1403 I ActivityManager: Killing 3599:com.android.chrome/u0a40 (adj 15): empty #17
,03-29 13:31:00.452  2153  2217 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,03-29 13:31:00.452  2153  2218 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-29 13:31:00.504  2153  2218 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-29 13:31:00.550  2153  2218 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 13:31:01.399  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc707c rs_disc_pending=0
03-29 13:31:01.399  2153  2229 W bt-btif : bta_dm_check_av:0
,03-29 13:31:01.399  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:02.226  2153  2229 W bt-btif : new conn_srvc id:26, app_id:255
,03-29 13:31:02.227  2153  2229 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-29 13:31:02.227  2153  2229 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-29 13:31:02.229  3311  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-29 13:31:02.233  3311  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 362)
,03-29 13:31:02.235  3311  3906 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 362)
,03-29 13:31:02.236  3311  3883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:02.237   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:02.240  3311  3883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:31:02.246  3311  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:31:02.501  3311  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 362)
,03-29 13:31:02.505  3311  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-29 13:31:02.506  3311  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 362)
,03-29 13:31:02.506  3311  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 362
03-29 13:31:02.506  3311  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 362)
,03-29 13:31:02.507  3311  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-29 13:31:02.508  3311  3906 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 362)
03-29 13:31:02.508  3311  3311 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-29 13:31:02.509  3311  3311 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-29 13:31:02.509  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-29 13:31:02.511  3311  3311 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 13:31:02.512  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-29 13:31:02.513  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:02.513  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:02.513  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:02.513  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:02.513  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:02.513  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:02.521  2153  2227 D BtGatt.AdvertiseManager: message : 1
,03-29 13:31:02.522  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 13:31:02.527  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 13:31:02.527  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:02.529  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:02.530  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:02.531  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:02.531  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:02.531  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:02.531  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:02.531  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:02.532  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.532  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:02.532  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:02.540  2153  2170 D BtGatt.GattService: registerClient() - UUID=b09bd021-4aa5-4c45-907d-32fb10bd4482
03-29 13:31:02.541  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=b09bd021-4aa5-4c45-907d-32fb10bd4482, clientIf=6
,03-29 13:31:02.541  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:02.543  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:02.547  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:02.550  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:02.552  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:02.553  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:02.555  2153  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:02.558  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:02.558  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:02.558  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.558  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:02.558  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:02.559  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:02.559  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:02.559  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:02.559  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-29 13:31:02.559  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:02.561  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:02.561  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.561  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:31:02.564  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 13:31:02.564  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.564  2153  2217 D BtGatt.GattService: current time is 250830167871
,03-29 13:31:02.564  2153  2217 D BtGatt.GattService: Batch record : [110, 107, -32, 25, 105, 114, 1, -128, -79, 33, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 33, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 13:31:02.564  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:02.565  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 13:31:02.565  2153  2219 D BtGatt.GattService: registerClient() - UUID=b01bc225-7642-45b6-89bf-82b90541b6b9
03-29 13:31:02.565  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=b01bc225-7642-45b6-89bf-82b90541b6b9, clientIf=5
03-29 13:31:02.566  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:02.566  2153  2170 D BtGatt.GattService: start scan with filters
03-29 13:31:02.569  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:02.569  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:02.569  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:02.571  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 13:31:02.571  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.572  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:02.572  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:02.572  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.572  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:31:02.573  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:02.573  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:02.575  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:02.575  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.577  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:31:02.577  2153  2217 D BtGatt.GattService: Client app is not null!
,03-29 13:31:02.578  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:02.578  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:02.578  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 13:31:02.579  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-29 13:31:02.579  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:02.579  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:02.579  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:02.579  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.579  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:02.579  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:02.579  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.579  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:02.583  2153  2169 D BtGatt.GattService: registerClient() - UUID=bf217a46-7ebf-4a88-9a42-360a383c2637
03-29 13:31:02.584  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=bf217a46-7ebf-4a88-9a42-360a383c2637, clientIf=6
03-29 13:31:02.584  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:31:02.586  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:02.588  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:02.591  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:02.593  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:02.594  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-29 13:31:02.595  2153  2169 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:02.596  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:31:02.596  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:02.596  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:02.596  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:02.596  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:02.597  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-29 13:31:02.597  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:02.597  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.597  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:02.597  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:02.600  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:02.600  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.600  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:02.601  2153  2169 D BtGatt.GattService: registerClient() - UUID=1431c8a1-3afe-48a0-bf51-eb34ddd4fc94
03-29 13:31:02.601  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:02.601  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.601  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=1431c8a1-3afe-48a0-bf51-eb34ddd4fc94, clientIf=5
03-29 13:31:02.601  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:02.602  2153  2170 D BtGatt.GattService: start scan with filters
03-29 13:31:02.603  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:02.603  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:02.604  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:02.607  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:02.607  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:02.607  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:31:02.609  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:31:02.609  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.610  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:31:02.610  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:02.611  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:02.612  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:02.612  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.613  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:02.613  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:02.613  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:02.613  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-29 13:31:02.613  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:02.613  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:02.613  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:02.613  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:02.614  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.614  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:02.614  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:02.615  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:02.615  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.616  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:02.616  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:02.619  2153  2219 D BtGatt.GattService: registerClient() - UUID=b3229000-3c8a-4654-9e2a-91162fa88f47
03-29 13:31:02.620  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=b3229000-3c8a-4654-9e2a-91162fa88f47, clientIf=6
03-29 13:31:02.620  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:02.621  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:02.625  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:02.627  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:02.630  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-29 13:31:02.630  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:02.632  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:02.634  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:02.634  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:02.634  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.634  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:02.635  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:02.635  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:02.635  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:02.635  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:02.635  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:02.635  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:02.636  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
03-29 13:31:02.636  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.636  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:02.637  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:02.638  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.642  2153  2170 D BtGatt.GattService: registerClient() - UUID=c07a460f-10cd-4b5f-814a-3e7a6bc3c395
03-29 13:31:02.642  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=c07a460f-10cd-4b5f-814a-3e7a6bc3c395, clientIf=5
03-29 13:31:02.642  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:02.643  2153  2219 D BtGatt.GattService: start scan with filters
,03-29 13:31:02.644  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:02.644  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:02.644  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:02.644  3311  3311 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-29 13:31:02.644  3311  3311 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 13:31:02.644  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:02.645  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:02.645  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:02.645  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:02.645  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 13:31:02.645  3311  3907 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 363)
03-29 13:31:02.646  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:31:02.647  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.648  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:02.648  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.648  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:02.648  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:31:02.650  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:02.650  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:02.651  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:02.651  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:02.651  3311  3907 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 37681
03-29 13:31:02.652  3311  3907 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-29 13:31:02.653  3311  3907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:02.653  3311  3907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:02.654  3311  3909 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 364, name: Sender)
03-29 13:31:02.654  3311  3907 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 363)
03-29 13:31:02.654  3311  3907 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 363)
,03-29 13:31:02.657  3311  3910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Receiver)
,03-29 13:31:02.975  2153  2229 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,03-29 13:31:02.975  2153  2229 E bt-btif : DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
03-29 13:31:02.976  2153  2357 W bt-btif : invalid rfc slot id: 10
,03-29 13:31:02.977  3311  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
03-29 13:31:02.977  3311  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 361)
,03-29 13:31:02.977  3311  3884 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361),
,03-29 13:31:02.979  3311  3311 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> F8:95:C7:87:3C:51]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1,
,03-29 13:31:02.980  3311  3311 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> F8:95:C7:87:3C:51], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1,
,03-29 13:31:02.981  3311  3311 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-29 13:31:02.981  3311  3311 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
03-29 13:31:02.981  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
03-29 13:31:02.982  3311  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 361
03-29 13:31:02.982  3311  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 361
,03-29 13:31:02.984  3311  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 361)
03-29 13:31:02.991  3311  3373 I jxcore-log: INFO testThaliMobileNative: Connect returned an error: Connection to peer [<no peer name> F8:95:C7:87:3C:51] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-29 13:31:02.991  3311  3373 I jxcore-log: 
03-29 13:31:02.994  3311  3373 I jxcore-log: INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
03-29 13:31:02.994  3311  3373 I jxcore-log: 
,03-29 13:31:02.994  3311  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 361
03-29 13:31:02.997  3311  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 361)
03-29 13:31:02.997  3311  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 361)
,03-29 13:31:05.301  2153  2215 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 13:31:06.007  3311  3373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51,
03-29 13:31:06.007  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:06.011  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
03-29 13:31:06.012  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
03-29 13:31:06.012  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-29 13:31:06.012  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-29 13:31:06.013  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-29 13:31:06.013  3311  3373 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-29 13:31:06.017  3311  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 367)
03-29 13:31:06.018  3311  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
03-29 13:31:06.018  3311  3913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:31:06.023  2153  2170 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 13:31:06.212  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc707c rs_disc_pending=1,
03-29 13:31:06.213  2153  2229 W bt-btif : bta_dm_check_av:0
03-29 13:31:06.213  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:07.027  2153  2229 W bt-btif : info:x10
03-29 13:31:07.028  2153  2217 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-29 13:31:07.029  2153  2217 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-29 13:31:07.390  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc6eb4 rs_disc_pending=1
,03-29 13:31:07.390  2153  2229 W bt-btif : bta_dm_check_av:0
03-29 13:31:07.391  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:07.452  2153  2229 W bt-sdp  : process_service_search_attr_rsp
,03-29 13:31:07.630  2153  2217 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,03-29 13:31:07.637  2153  2217 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
03-29 13:31:07.638  2153  2217 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-29 13:31:07.643  2153  2218 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-29 13:31:07.643  2153  2218 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 13:31:07.669  2153  2153 D BtGatt.ScanManager: awakened up at time 255934
,03-29 13:31:07.671  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:31:07.676  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,03-29 13:31:07.676  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:07.676  2153  2217 D BtGatt.GattService: current time is 255942068338,
,03-29 13:31:07.677  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -72, 72, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 110, 107, -32, 25, 105, 114, 1, -128, -78, 98, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -52, 97, -92, -108, 32, 106, 1, -128, -78, 97, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -35, -90, 72, 4, 0, 114, 1, -128, -93, 96, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -80, -123, 94, -87, -25, 82, 1, -128, -94, 75, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:07.678  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:31:07.678  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:07.679  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:07.680  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:31:07.680  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:07.683  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:07.684  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:07.685  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:07.685  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:07.686  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2,
,03-29 13:31:07.747  2153  2217 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-29 13:31:07.747  2153  2218 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-29 13:31:07.751  2153  2218 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-29 13:31:07.767  2153  2218 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 13:31:07.795  2153  2229 W bt-btif : new conn_srvc id:26, app_id:1
03-29 13:31:07.795  2153  2229 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 13:31:07.795  2153  2229 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-29 13:31:07.795  3311  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 367)
03-29 13:31:07.796  3311  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 367)
,03-29 13:31:07.796  3311  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 368)
03-29 13:31:07.796  3311  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 368)
03-29 13:31:07.797  3311  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 367)
,03-29 13:31:07.800  3311  3914 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 368),
,03-29 13:31:08.054  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc6eb4 rs_disc_pending=0
,03-29 13:31:08.054  2153  2229 W bt-btif : bta_dm_check_av:0
03-29 13:31:08.054  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:08.076  3311  3914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 368)
,03-29 13:31:08.080  3311  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51],
,03-29 13:31:08.080  3311  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 367)
,03-29 13:31:08.080  3311  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 367)
,03-29 13:31:08.081  3311  3914 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 368),
03-29 13:31:08.082  3311  3311 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:08.082  3311  3311 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51],
03-29 13:31:08.082  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-29 13:31:08.085  3311  3311 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-29 13:31:08.085  3311  3311 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
03-29 13:31:08.085  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
03-29 13:31:08.085  3311  3311 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-29 13:31:08.092  3311  3915 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 369)
03-29 13:31:08.096  3311  3915 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54922
03-29 13:31:08.096  3311  3915 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-29 13:31:08.096  3311  3915 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 54922 (peer ID: F8:95:C7:87:3C:51)
03-29 13:31:08.098  3311  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-29 13:31:08.108  3311  3373 I jxcore-log: INFO testThaliMobileNative: ,
03-29 13:31:08.108  3311  3373 I jxcore-log: 
03-29 13:31:08.110  3311  3373 I jxcore-log: ok 164 Must have listeningPort
03-29 13:31:08.110  3311  3373 I jxcore-log: 
,03-29 13:31:08.111  3311  3373 I jxcore-log: ok 165 listeningPort must be a number
03-29 13:31:08.111  3311  3373 I jxcore-log: 
03-29 13:31:08.112  3311  3373 I jxcore-log: ok 166 Connection must have clientPort
03-29 13:31:08.112  3311  3373 I jxcore-log: 
,03-29 13:31:08.113  3311  3373 I jxcore-log: ok 167 clientPort must be a number
03-29 13:31:08.113  3311  3373 I jxcore-log: 
,03-29 13:31:08.115  3311  3373 I jxcore-log: ok 168 Connection must have serverPort
03-29 13:31:08.115  3311  3373 I jxcore-log: 
,03-29 13:31:08.115  3311  3373 I jxcore-log: ok 169 serverPort must be a number
03-29 13:31:08.115  3311  3373 I jxcore-log: 
,03-29 13:31:08.116  3311  3373 I jxcore-log: ok 170 forward connection must have clientPort == 0
03-29 13:31:08.116  3311  3373 I jxcore-log: 
03-29 13:31:08.116  3311  3373 I jxcore-log: ok 171 forward connection must have serverPort == 0
03-29 13:31:08.116  3311  3373 I jxcore-log: 
03-29 13:31:08.122  3311  3373 I jxcore-log: # teardown
03-29 13:31:08.122  3311  3373 I jxcore-log: 
,03-29 13:31:08.222  3311  3909 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 364, thread name: Sender)
,03-29 13:31:08.223  3311  3909 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-29 13:31:08.223  3311  3909 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-29 13:31:08.223  3311  3909 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 363
03-29 13:31:08.223  3311  3909 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 363)
03-29 13:31:08.224  3311  3909 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-29 13:31:08.225  3311  3909 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-29 13:31:08.225  3311  3909 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-29 13:31:08.225  3311  3910 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
03-29 13:31:08.225  3311  3909 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-29 13:31:08.225  3311  3909 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 364
03-29 13:31:08.225  3311  3910 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Receiver)
03-29 13:31:08.225  3311  3909 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 363)
03-29 13:31:08.226  3311  3909 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 363)
03-29 13:31:08.227  3311  3909 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-29 13:31:08.228  3311  3909 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 364, name: Sender)
,03-29 13:31:08.237  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:08.237  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:08.237  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:31:08.237  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:08.241  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:08.244  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:08.244  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:08.245  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:08.245  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:08.245  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:08.245  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:08.245  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-29 13:31:08.245  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:08.245  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:08.245  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:08.245  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:08.245  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:08.245  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:08.249  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 13:31:08.249  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:08.249  3311  3373 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-29 13:31:08.249  3311  3373 I jxcore-log: 
03-29 13:31:08.250  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:31:08.250  3311  3373 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start,
03-29 13:31:08.250  3311  3373 I jxcore-log: ,
03-29 13:31:08.251  3311  3373 I jxcore-log: ok 172 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:31:08.251  3311  3373 I jxcore-log: 
03-29 13:31:08.253  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:08.253  3311  3373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:08.253  3311  3373 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 369)
03-29 13:31:08.253  3311  3373 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 369)
03-29 13:31:08.253  3311  3373 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-29 13:31:08.253  3311  3373 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 369)
03-29 13:31:08.254  3311  3373 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 369)
03-29 13:31:08.255  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:08.255  3311  3915 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 369)
03-29 13:31:08.255  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:08.256  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:08.256  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:08.256  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:31:08.256  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:08.257  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:08.257  3311  3883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:08.257  3311  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:08.257  3311  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:31:08.258  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:31:08.258  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:08.258  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:08.258  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:08.258  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:08.258  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:08.258  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:08.264  3311  3373 D BluetoothLeScanner: could not find callback wrapper
03-29 13:31:08.264  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:08.264  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:08.268  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:08.269  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 13:31:08.272  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 13:31:08.272  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:08.273  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:08.273  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:08.273  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:08.273  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:08.273  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-29 13:31:08.273  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:08.273  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:08.274  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:08.274  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:08.274  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:31:08.275  3311  3373 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear,
03-29 13:31:08.275  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:08.275  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:08.275  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:08.275  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:31:08.278  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:08.278  3311  3373 I jxcore-log: 
,03-29 13:31:08.283  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:31:08.283   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:08.293  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-29 13:31:08.294  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:08.294  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:08.298  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:31:08.298  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:08.298  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:08.299  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:08.299  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:08.300  3311  3373 I jxcore-log: ok 173 Should be able to call stopAdvertisingAndListening in teardown
03-29 13:31:08.300  3311  3373 I jxcore-log: 
,03-29 13:31:08.305  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:08.305  3311  3373 I jxcore-log: 
,03-29 13:31:08.306  3311  3373 I jxcore-log: # setup
03-29 13:31:08.306  3311  3373 I jxcore-log: 
,03-29 13:31:08.308  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:08.308  3311  3373 I jxcore-log: 
,03-29 13:31:08.569  3311  3373 I jxcore-log: # 41. Can shift large amounts of data
03-29 13:31:08.569  3311  3373 I jxcore-log: 
,03-29 13:31:08.783  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 47538, start advertisements: true
03-29 13:31:08.783  3311  3373 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-29 13:31:08.783  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3,
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
,03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:08.784  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:08.784  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:31:08.784  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-29 13:31:08.791  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 13:31:08.791  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:08.791  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:08.791  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:08.799  2153  2169 D BtGatt.GattService: registerClient() - UUID=a7339f2b-ebdd-4e0d-b62d-c174323c900b
,03-29 13:31:08.800  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=a7339f2b-ebdd-4e0d-b62d-c174323c900b, clientIf=5
03-29 13:31:08.800  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:08.801  2153  2219 D BtGatt.GattService: start scan with filters
03-29 13:31:08.802  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:08.802  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:08.802  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:08.802  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:08.802  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:08.802  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:08.802  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:08.803  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:08.804  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-29 13:31:08.804  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:08.804  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:08.804  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:08.804  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:08.806  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:31:08.806  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:08.807  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-29 13:31:08.807  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:08.807  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:31:08.807  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,03-29 13:31:08.809  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-29 13:31:08.809  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:08.810  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:08.810  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:08.816  2153  2170 D BtGatt.GattService: registerClient() - UUID=d8d6599a-fbae-4ca7-9d67-07e81c97b865
03-29 13:31:08.816  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=d8d6599a-fbae-4ca7-9d67-07e81c97b865, clientIf=6
03-29 13:31:08.817  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-29 13:31:08.817  2153  2227 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:08.825  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:08.827  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 13:31:08.830  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-29 13:31:08.830  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:31:08.830  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:08.830   821  1319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:08.832  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:08.832  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:08.832  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:31:08.832  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:31:08.833  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:31:08.833  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:31:08.833  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:08.833  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:31:08.833  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:08.833  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:08.834  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:08.834  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:08.834  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:08.834   821  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-29 13:31:08.835  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:31:08.835  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-29 13:31:08.835  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:08.835  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:08.835  3311  3373 I jxcore-log: 
03-29 13:31:08.835  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:08.836  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc6eb4 rs_disc_pending=1
,03-29 13:31:08.836  2153  2229 W bt-btif : bta_dm_check_av:0
03-29 13:31:08.836  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
03-29 13:31:08.836  3311  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:08.836  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:08.836  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:08.836  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:31:08.836  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:08.837  3311  3373 I jxcore-log: ok 174 Can call startUpdateAdvertisingAndListening without error
03-29 13:31:08.837  3311  3373 I jxcore-log: 
03-29 13:31:08.839  3311  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:31:08.840  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 47538, start advertisements: false
03-29 13:31:08.840  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:08.840  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-29 13:31:08.840  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:08.840  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:08.841  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:08.841  3311  3373 I jxcore-log: 
,03-29 13:31:08.842  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:08.842  3311  3373 I jxcore-log: 
03-29 13:31:08.842  3311  3373 I jxcore-log: ok 175 Can call startListeningForAdvertisements without error
03-29 13:31:08.842  3311  3373 I jxcore-log: 
,03-29 13:31:09.102  2153  2229 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-29 13:31:09.655  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc707c rs_disc_pending=0
03-29 13:31:09.655  2153  2229 W bt-btif : bta_dm_check_av:0
03-29 13:31:09.655  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:09.926  2153  2229 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,03-29 13:31:09.926  2153  2229 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-29 13:31:10.347  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:31:10.411  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-29 13:31:10.411  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-29 13:31:10.412  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:31:10.412  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:31:10.419  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:31:10.454  3748  3748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-29 13:31:10.455  3748  3748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 13:31:10.456  3748  3748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-29 13:31:11.641  2153  2229 E bt-btm  : tBTM_SEC_DEV:0xa2fc6eb4 rs_disc_pending=0,
03-29 13:31:11.641  2153  2229 W bt-btif : bta_dm_check_av:0
03-29 13:31:11.641  2153  2217 W bt-btif : btif_dm_cback : unhandled event (14)
,03-29 13:31:13.030  2153  2215 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 13:31:13.819  2153  2153 D BtGatt.ScanManager: awakened up at time 262085
,03-29 13:31:13.821  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:13.826  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-29 13:31:13.826  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:13.826  2153  2217 D BtGatt.GattService: current time is 262092172607
03-29 13:31:13.827  2153  2217 D BtGatt.GattService: Batch record : [-74, -21, -90, -51, -57, 94, 1, -128, -72, 40, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -55, 38, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -56, 110, -95, -17, -114, 69, 1, -128, -86, 36, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:13.828  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:31:13.828  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:31:13.829  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-29 13:31:13.832  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-29 13:31:13.833  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-29 13:31:13.834  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-29 13:31:13.834  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-29 13:31:13.835  3311  3311 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-29 13:31:13.848  3311  3373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-29 13:31:13.848  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:13.849  2153  2229 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-29 13:31:13.853  2153  2153 D BluetoothMapService: onReceive
03-29 13:31:13.855  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-29 13:31:13.855  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-29 13:31:13.855  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-29 13:31:13.855  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-29 13:31:13.856  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-29 13:31:13.856  3311  3373 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-29 13:31:13.859  3311  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 371),
03-29 13:31:13.860  3311  3917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:13.862  2153  2229 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-29 13:31:13.868  2153  2153 D BluetoothMapService: onReceive
,03-29 13:31:13.868  2153  2170 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-29 13:31:13.876   821   859 D BluetoothManagerService: Message: 20
,03-29 13:31:13.876   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d840080:true
,03-29 13:31:13.884  1536  1536 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-29 13:31:13.887  1536  1536 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-29 13:31:13.909  1536  1536 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-29 13:31:13.910  1536  1536 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-29 13:31:14.228  2153  2229 W bt-btif : info:x10
,03-29 13:31:14.229  2153  2217 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 2205
,03-29 13:31:14.263  1536  1536 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-29 13:31:14.269  1536  1536 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-29 13:31:14.314  2153  2229 W bt-sdp  : process_service_search_attr_rsp
,03-29 13:31:14.572  2153  2217 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-29 13:31:14.579  2153  2217 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-29 13:31:14.579  2153  2217 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-29 13:31:14.582  2153  2218 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-29 13:31:14.582  2153  2218 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-29 13:31:14.665  2153  2217 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-29 13:31:14.666  2153  2218 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-29 13:31:14.675  2153  2218 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-29 13:31:14.688  2153  2218 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-29 13:31:14.756  2153  2229 W bt-btif : new conn_srvc id:26, app_id:1
03-29 13:31:14.756  2153  2229 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-29 13:31:14.756  2153  2229 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-29 13:31:14.756  3311  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 371)
03-29 13:31:14.757  3311  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 371)
03-29 13:31:14.757  3311  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 372)
03-29 13:31:14.758  3311  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 372)
03-29 13:31:14.758  3311  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 371)
,03-29 13:31:14.762  3311  3919 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 372)
,03-29 13:31:14.772  3311  3919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 372)
,03-29 13:31:14.776  3311  3919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:14.776  3311  3919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 371)
03-29 13:31:14.777  3311  3919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 371)
,03-29 13:31:14.777  3311  3919 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 372)
03-29 13:31:14.777  3311  3311 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-29 13:31:14.778  3311  3311 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:14.778  3311  3311 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-29 13:31:14.778  3311  3311 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-29 13:31:14.778  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-29 13:31:14.779  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:14.779  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:14.779  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:14.779  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:14.779  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:14.779  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:14.785  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:14.786  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 13:31:14.791  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-29 13:31:14.791  2153  2217 D BtGatt.GattService: Client app is not null!
,03-29 13:31:14.793  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:14.795  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:14.795  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:14.795  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:14.796  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:14.796  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-29 13:31:14.796  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:14.796  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:14.797  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:14.797  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:14.804  2153  2169 D BtGatt.GattService: registerClient() - UUID=c67c7408-b7fa-41ee-816f-0149197d0c50
,03-29 13:31:14.804  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=c67c7408-b7fa-41ee-816f-0149197d0c50, clientIf=6
03-29 13:31:14.805  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:31:14.805  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:14.810  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:14.813  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:14.816  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:14.817  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:14.820  2153  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:14.822  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:14.822  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:14.822  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:14.822  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 13:31:14.822  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:14.822  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:14.823  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:14.823  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:14.823  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:14.823  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:14.826  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:14.826  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.826  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:14.827  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:14.827  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.830  2153  2170 D BtGatt.GattService: registerClient() - UUID=bca2f2e3-aa9d-49e6-b138-67c5a0be2a7c
,03-29 13:31:14.831  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=bca2f2e3-aa9d-49e6-b138-67c5a0be2a7c, clientIf=5,
03-29 13:31:14.831  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:14.831  2153  2169 D BtGatt.GattService: start scan with filters
03-29 13:31:14.832  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-29 13:31:14.832  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:14.832  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-29 13:31:14.833  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:14.833  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:14.833  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:14.833  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:14.833  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2,
03-29 13:31:14.833  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:14.836  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:14.836  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:31:14.837  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 13:31:14.839  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-29 13:31:14.839  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.841  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:14.841  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.841  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:14.841  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:14.843  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:14.843  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.844  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:31:14.844  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:14.846  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:14.846  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:14.846  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.846  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:14.846  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-29 13:31:14.846  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:14.846  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:14.847  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:14.847  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:14.847  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:14.847  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:14.847  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:14.852  2153  2170 D BtGatt.GattService: registerClient() - UUID=27961bdd-8f16-42de-8f08-b00cb3f964ae
03-29 13:31:14.852  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=27961bdd-8f16-42de-8f08-b00cb3f964ae, clientIf=6
03-29 13:31:14.852  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:31:14.853  2153  2227 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:14.857  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:14.859  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:14.862  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:14.863  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:14.864  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:14.865  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:14.866  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-29 13:31:14.866  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-29 13:31:14.866  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:14.866  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:14.866  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:14.866  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-29 13:31:14.868  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:14.868  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.868  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:14.871  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:14.871  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.871  2153  2170 D BtGatt.GattService: registerClient() - UUID=78431e19-3109-4d27-bd21-867461e917ed
,03-29 13:31:14.871  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:14.872  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=78431e19-3109-4d27-bd21-867461e917ed, clientIf=5
03-29 13:31:14.872  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:14.873  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:14.873  2153  2219 D BtGatt.GattService: start scan with filters
03-29 13:31:14.873  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-29 13:31:14.874  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:14.874  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:14.874  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-29 13:31:14.875  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-29 13:31:14.875  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:14.875  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-29 13:31:14.875  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:14.875  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:14.875  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:14.879  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:14.879  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-29 13:31:14.879  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:31:14.883  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-29 13:31:14.883  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.884  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 13:31:14.884  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:14.886  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:14.886  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:14.886  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.886  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:14.887  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-29 13:31:14.887  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:14.887  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-29 13:31:14.887  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:14.887  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:14.887  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:31:14.887  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:14.887  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:14.887  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:14.887  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:14.889  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:14.889  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.891  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 13:31:14.891  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.893  2153  2169 D BtGatt.GattService: registerClient() - UUID=e3d00ba3-4d5b-49e7-b718-54a741ecc381
03-29 13:31:14.893  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=e3d00ba3-4d5b-49e7-b718-54a741ecc381, clientIf=6
03-29 13:31:14.893  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
03-29 13:31:14.895  2153  2227 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:14.898  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:14.901  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:14.903  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:14.904  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:14.906  2153  2169 D BtGatt.GattService: stopScan() - queue size =1,
,03-29 13:31:14.907  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:31:14.907  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:14.907  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:14.907  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:14.907  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:14.907  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:14.907  3311  3311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:14.908  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-29 13:31:14.908  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.908  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:14.911  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:14.911  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.911  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:14.912  2153  2169 D BtGatt.GattService: registerClient() - UUID=36f4c721-1776-474d-b638-a0ce24abed76
03-29 13:31:14.912  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=36f4c721-1776-474d-b638-a0ce24abed76, clientIf=5
03-29 13:31:14.912  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:14.912  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.913  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:14.913  2153  2170 D BtGatt.GattService: start scan with filters
,03-29 13:31:14.914  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:14.914  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:14.914  3311  3311 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-29 13:31:14.914  3311  3311 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-29 13:31:14.914  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:14.914  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:14.914  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:14.914  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 13:31:14.915  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:14.915  3311  3920 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 373)
03-29 13:31:14.915  3311  3920 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35138
03-29 13:31:14.915  3311  3920 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-29 13:31:14.915  3311  3920 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 35138 (peer ID: F8:95:C7:87:3C:51)
03-29 13:31:14.916  3311  3920 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-29 13:31:14.918  3311  3373 I jxcore-log: INFO testThaliMobileNative: 
03-29 13:31:14.918  3311  3373 I jxcore-log: 
03-29 13:31:14.919  3311  3373 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-29 13:31:14.919  3311  3373 I jxcore-log: 
,03-29 13:31:14.920  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:31:14.923  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 13:31:14.923  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.924  3311  3920 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 35138
,03-29 13:31:14.924  3311  3920 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,03-29 13:31:14.924  3311  3920 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:14.924  3311  3373 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-29 13:31:14.924  3311  3373 I jxcore-log: 
,03-29 13:31:14.924  3311  3920 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-29 13:31:14.924  3311  3920 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 373)
,03-29 13:31:14.924  3311  3920 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 373)
03-29 13:31:14.925  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 13:31:14.925  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:14.925  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:31:14.925  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:14.927  3311  3921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 374, name: Sender)
,03-29 13:31:14.927  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:14.927  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:14.928  3311  3922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Receiver)
,03-29 13:31:14.942  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 13:31:14.942  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:15.041  3311  3373 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:15.041  3311  3373 I jxcore-log: 
,03-29 13:31:15.113  3311  3373 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:15.113  3311  3373 I jxcore-log: 
,03-29 13:31:15.185  3311  3373 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:15.185  3311  3373 I jxcore-log: 
,03-29 13:31:15.330  3311  3373 I jxcore-log: INFO testThaliMobileNative: forwardData
03-29 13:31:15.330  3311  3373 I jxcore-log: 
,03-29 13:31:15.334  3311  3373 I jxcore-log: ok 176 received should match sent forward,
03-29 13:31:15.334  3311  3373 I jxcore-log: 
,03-29 13:31:15.351  3311  3373 I jxcore-log: # teardown
03-29 13:31:15.351  3311  3373 I jxcore-log: 
,03-29 13:31:15.542  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:15.542  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-29 13:31:15.542  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-29 13:31:15.542  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:15.546  2153  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:15.547  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:15.548  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:15.548  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:15.548  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:15.551  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:15.551  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:15.551  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:15.551  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:15.554  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-29 13:31:15.554  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:15.555  2153  2217 D BtGatt.GattService: current time is 263820654377
03-29 13:31:15.555  2153  2217 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -71, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 18, 43, 91, 87, -111, 113, 1, -128, -93, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-29 13:31:15.556  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-29 13:31:15.555  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:15.556  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:15.556  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:15.557  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:15.557  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:15.557  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:15.557  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:15.557  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-29 13:31:15.557  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:15.560  3311  3373 I jxcore-log: ok 177 Should be able to call stopListeningForAdvertisments in teardown
03-29 13:31:15.560  3311  3373 I jxcore-log: 
,03-29 13:31:15.564  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-29 13:31:15.564  3311  3373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
,03-29 13:31:15.564  3311  3373 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 373),
03-29 13:31:15.564  3311  3373 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 373)
03-29 13:31:15.565  3311  3922 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1
03-29 13:31:15.565  3311  3922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Receiver)
03-29 13:31:15.566  3311  3373 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-29 13:31:15.566  3311  3373 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-29 13:31:15.566  3311  3373 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-29 13:31:15.566  3311  3373 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-29 13:31:15.566  3311  3373 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 374
03-29 13:31:15.566  3311  3373 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 373)
03-29 13:31:15.566  3311  3373 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 373)
03-29 13:31:15.567  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-29 13:31:15.567  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:15.567  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:31:15.567  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:15.567  3311  3921 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
,03-29 13:31:15.567  3311  3921 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 374, name: Sender)
03-29 13:31:15.567  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:15.567  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:15.567  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 13:31:15.567  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:15.567  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:31:15.568  3311  3916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-29 13:31:15.568  3311  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-29 13:31:15.568  3311  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:31:15.569  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-29 13:31:15.571  3311  3373 D BluetoothLeScanner: could not find callback wrapper
03-29 13:31:15.571  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:15.571  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:15.575  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:15.576  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:31:15.578  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-29 13:31:15.578  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:15.580  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:15.581  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:15.581  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:15.581  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:15.581  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-29 13:31:15.581  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:15.581  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:15.581  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 13:31:15.581  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:31:15.584  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:15.585  3311  3373 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-29 13:31:15.586  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:15.587  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:15.587  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:31:15.587  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-29 13:31:15.591  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:15.591  3311  3373 I jxcore-log: 
,03-29 13:31:15.595  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-29 13:31:15.596   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:15.601  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-29 13:31:15.602  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:15.602  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:31:15.602  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-29 13:31:15.602  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-29 13:31:15.606  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 13:31:15.606  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:15.606  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:15.606  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:15.606  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:31:15.609  3311  3373 I jxcore-log: ok 178 Should be able to call stopAdvertisingAndListening in teardown,
03-29 13:31:15.609  3311  3373 I jxcore-log: 
,03-29 13:31:15.615  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 13:31:15.615  3311  3373 I jxcore-log: 
03-29 13:31:15.616  3311  3373 I jxcore-log: # setup
03-29 13:31:15.616  3311  3373 I jxcore-log: 
,03-29 13:31:15.619  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 13:31:15.619  3311  3373 I jxcore-log: 
,03-29 13:31:15.620  2153  2229 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,03-29 13:31:16.566  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:16.566  3311  3373 I jxcore-log: 
,03-29 13:31:16.574  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-29 13:31:16.574  3311  3373 I jxcore-log: 
,03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:16.584  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:16.588  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:16.590  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-29 13:31:16.590  3311  3373 I jxcore-log: 
,03-29 13:31:16.593  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-29 13:31:16.593  3311  3373 I jxcore-log: 
,03-29 13:31:16.598  3311  3373 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
,03-29 13:31:16.598  3311  3373 I jxcore-log: 
,03-29 13:31:16.601  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-29 13:31:16.601  3311  3373 I jxcore-log: 
,03-29 13:31:16.700  3311  3373 I jxcore-log: ok 179 specific error should be returned
,03-29 13:31:16.700  3311  3373 I jxcore-log: 
,03-29 13:31:16.703  3311  3373 I jxcore-log: # teardown
,03-29 13:31:16.703  3311  3373 I jxcore-log: 
,03-29 13:31:17.989  3311  3373 I jxcore-log: ok 180 must be stopped
03-29 13:31:17.989  3311  3373 I jxcore-log: 
,03-29 13:31:17.996  3311  3373 I jxcore-log: # setup
03-29 13:31:17.996  3311  3373 I jxcore-log: 
,03-29 13:31:18.092  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:18.092  3311  3373 I jxcore-log: 
,03-29 13:31:18.097  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:18.097  3311  3373 I jxcore-log: 
,03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:18.112  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:18.118  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:18.122  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-29 13:31:18.122  3311  3373 I jxcore-log: 
,03-29 13:31:18.125  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-29 13:31:18.125  3311  3373 I jxcore-log: 
,03-29 13:31:18.131  3311  3373 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
,03-29 13:31:18.131  3311  3373 I jxcore-log: 
,03-29 13:31:18.135  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-29 13:31:18.135  3311  3373 I jxcore-log: 
,03-29 13:31:18.553  3419  3923 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-29 13:31:18.655  1567  1593 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-29 13:31:18.655  1567  1593 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:31:18.655  1567  1593 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:31:18.655  1567  1593 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:31:18.660  1567  1593 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-29 13:31:18.680  3419  3923 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: ,	at com.a.a.a.a.a(SourceFile:93)
03-29 13:31:18.681  3419  3923 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-29 13:31:19.713  2153  2229 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-29 13:31:19.719  2153  2153 D BluetoothMapService: onReceive
,03-29 13:31:19.749  1536  1536 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-29 13:31:19.754  1536  1536 I BluetoothClassifier: Bluetooth Device Name: G4-1,
,03-29 13:31:19.967  3311  3373 I jxcore-log: ok 181 specific error should be returned
03-29 13:31:19.967  3311  3373 I jxcore-log: 
,03-29 13:31:19.974  3311  3373 I jxcore-log: # teardown,
03-29 13:31:19.974  3311  3373 I jxcore-log: 
,03-29 13:31:20.055  3311  3373 I jxcore-log: ok 182 must be stopped
03-29 13:31:20.055  3311  3373 I jxcore-log: 
,03-29 13:31:20.057  3311  3373 I jxcore-log: # setup
03-29 13:31:20.057  3311  3373 I jxcore-log: 
,03-29 13:31:20.243  2153  2215 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-29 13:31:20.856  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:20.856  3311  3373 I jxcore-log: 
03-29 13:31:20.857  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-29 13:31:20.857  3311  3373 I jxcore-log: 
,03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:20.865  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:20.871  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:20.876  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:20.876  3311  3373 I jxcore-log: 
,03-29 13:31:20.881  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:20.881  3311  3373 I jxcore-log: 
,03-29 13:31:20.888  3311  3373 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-29 13:31:20.888  3311  3373 I jxcore-log: 
,03-29 13:31:20.894  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-29 13:31:20.894  3311  3373 I jxcore-log: 
,03-29 13:31:21.022  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
,03-29 13:31:21.022  3311  3373 I jxcore-log: 
,03-29 13:31:21.026  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 38043
,03-29 13:31:21.026  3311  3373 I jxcore-log: 
,03-29 13:31:21.029  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:21.029  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:21.029  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.032  3311  3373 I jxcore-log: ok 183 no errors
,03-29 13:31:21.032  3311  3373 I jxcore-log: 
,03-29 13:31:21.034  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 13:31:21.034  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:21.034  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.039  3311  3373 I jxcore-log: ok 184 still no errors
,03-29 13:31:21.039  3311  3373 I jxcore-log: 
,03-29 13:31:21.046  3311  3373 I jxcore-log: # teardown
03-29 13:31:21.046  3311  3373 I jxcore-log: ,
,03-29 13:31:21.186  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:21.186  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:21.186  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.191  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-29 13:31:21.191  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:31:21.191  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:21.202  3311  3373 I jxcore-log: ok 185 must be stopped
,03-29 13:31:21.202  3311  3373 I jxcore-log: 
,03-29 13:31:21.210  3311  3373 I jxcore-log: # setup,
03-29 13:31:21.210  3311  3373 I jxcore-log: 
,03-29 13:31:21.339  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:21.339  3311  3373 I jxcore-log: 
,03-29 13:31:21.344  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:21.344  3311  3373 I jxcore-log: 
,03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:21.351  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:21.354  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:21.356  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-29 13:31:21.356  3311  3373 I jxcore-log: 
03-29 13:31:21.358  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:21.358  3311  3373 I jxcore-log: 
,03-29 13:31:21.361  3311  3373 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-29 13:31:21.361  3311  3373 I jxcore-log: 
,03-29 13:31:21.362  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:21.362  3311  3373 I jxcore-log: 
,03-29 13:31:21.576  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:21.576  3311  3373 I jxcore-log: 
03-29 13:31:21.579  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 56603
03-29 13:31:21.579  3311  3373 I jxcore-log: 
,03-29 13:31:21.586  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 47538, start advertisements: false
,03-29 13:31:21.586  3311  3373 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-29 13:31:21.586  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-29 13:31:21.587  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-29 13:31:21.588  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:21.589  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:21.589  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:21.589  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-29 13:31:21.596  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:21.596  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:21.597  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:21.604  2153  2170 D BtGatt.GattService: registerClient() - UUID=a1b99a12-1945-4e8a-8737-224d7ee10c10
,03-29 13:31:21.605  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=a1b99a12-1945-4e8a-8737-224d7ee10c10, clientIf=5
03-29 13:31:21.605  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:21.606  2153  2169 D BtGatt.GattService: start scan with filters
03-29 13:31:21.607  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:31:21.608  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:21.610  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-29 13:31:21.611  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:31:21.611  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:21.612  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:21.612  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 13:31:21.612  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:21.612  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:21.612  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:21.612  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:21.613  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:21.613   821  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:31:21.614  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:21.614  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:21.615  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:21.615  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:21.616  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:21.616  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:21.624  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:21.624  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:21.625  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:21.625  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:21.625  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:21.625  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:21.631  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:21.631  3311  3373 I jxcore-log: 
,03-29 13:31:21.634  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:21.634  3311  3373 I jxcore-log: 
,03-29 13:31:21.637  3311  3373 I jxcore-log: ok 186 no errors
03-29 13:31:21.637  3311  3373 I jxcore-log: 
,03-29 13:31:21.643  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 47538, start advertisements: false
,03-29 13:31:21.643  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:21.643  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:21.643  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:21.643  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:21.647  3311  3373 I jxcore-log: ok 187 still no errors
03-29 13:31:21.647  3311  3373 I jxcore-log: 
,03-29 13:31:21.654  3311  3373 I jxcore-log: # teardown
03-29 13:31:21.654  3311  3373 I jxcore-log: 
,03-29 13:31:21.864  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:21.865  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:21.865  3311  3373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-29 13:31:21.865  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:21.865  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:21.865  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:21.865  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:21.866  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:21.866  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:21.870  2153  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:21.874  2153  2219 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:21.875  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-29 13:31:21.875  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:21.876  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:21.876  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:21.876  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:21.876  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:21.877  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-29 13:31:21.877  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:31:21.877  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:21.879  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-29 13:31:21.879  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-29 13:31:21.880  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:21.880  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:21.880  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:21.881  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:21.881  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-29 13:31:21.881  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:21.882  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:21.882  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:21.882  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:21.883  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:21.883  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:21.895  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:21.896   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:21.906  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-29 13:31:21.907  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:21.907  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:21.912  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-29 13:31:21.912  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:21.912  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:21.912  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:21.913  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:21.914  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-29 13:31:21.914  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:21.916  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:21.916  3311  3373 I jxcore-log: 
03-29 13:31:21.918  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:21.918  3311  3373 I jxcore-log: 
03-29 13:31:21.925  3311  3373 I jxcore-log: ok 188 must be stopped
03-29 13:31:21.925  3311  3373 I jxcore-log: 
,03-29 13:31:21.936  3311  3373 I jxcore-log: # setup
03-29 13:31:21.936  3311  3373 I jxcore-log: 
,03-29 13:31:22.098  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-29 13:31:22.098  3311  3373 I jxcore-log: 
03-29 13:31:22.103  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:22.103  3311  3373 I jxcore-log: 
,03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-29 13:31:22.113  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:22.117  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:22.119  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:22.119  3311  3373 I jxcore-log: 
,03-29 13:31:22.121  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:22.121  3311  3373 I jxcore-log: 
,03-29 13:31:22.125  3311  3373 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-29 13:31:22.125  3311  3373 I jxcore-log: 
,03-29 13:31:22.127  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:22.127  3311  3373 I jxcore-log: 
,03-29 13:31:22.257  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:22.257  3311  3373 I jxcore-log: 
,03-29 13:31:22.260  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 53321
03-29 13:31:22.260  3311  3373 I jxcore-log: 
,03-29 13:31:22.266  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 53321, start advertisements: true
,03-29 13:31:22.266  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:22.266  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:22.267  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:22.271  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-29 13:31:22.271  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:22.271  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:22.271  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:22.276  2153  2219 D BtGatt.GattService: registerClient() - UUID=5785642c-d9a6-429b-b530-df90800d23fa
,03-29 13:31:22.277  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=5785642c-d9a6-429b-b530-df90800d23fa, clientIf=5
03-29 13:31:22.277  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 13:31:22.278  2153  2170 D BtGatt.GattService: start scan with filters
,03-29 13:31:22.280  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-29 13:31:22.280  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:22.280  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:22.280  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:22.280  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-29 13:31:22.280  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:22.281  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-29 13:31:22.281  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:22.281  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:22.281  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-29 13:31:22.281  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:22.282  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:22.282  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:22.283  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:31:22.283  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 13:31:22.285  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:22.285  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-29 13:31:22.286  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
,03-29 13:31:22.286  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:31:22.289  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:22.289  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:22.290  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-29 13:31:22.290  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:22.291  2153  2219 D BtGatt.GattService: registerClient() - UUID=b6656d31-d906-4658-b14d-e543454edd67
03-29 13:31:22.292  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=b6656d31-d906-4658-b14d-e543454edd67, clientIf=6
,03-29 13:31:22.292  3311  3327 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:22.295  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:22.301  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:22.305  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-29 13:31:22.307  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:22.308  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-29 13:31:22.308  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:22.308   821  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-29 13:31:22.311  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-29 13:31:22.311  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-29 13:31:22.311  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-29 13:31:22.311  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:31:22.312  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:31:22.312  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:31:22.312  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-29 13:31:22.313  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-29 13:31:22.313  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:22.313  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:22.313  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:22.313  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:22.313  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:22.314  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:31:22.314  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:31:22.314  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:31:22.314  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:22.314  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:22.314  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:22.315  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:22.315  3311  3373 I jxcore-log: 
,03-29 13:31:22.315  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:31:22.315  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:22.316   821   837 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:31:22.317  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:22.317  3311  3373 I jxcore-log: 
03-29 13:31:22.318  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:22.318  3311  3373 I jxcore-log: 
03-29 13:31:22.318  3311  3924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:22.319  3311  3373 I jxcore-log: ok 189 no errors
03-29 13:31:22.319  3311  3373 I jxcore-log: 
03-29 13:31:22.322  3311  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-29 13:31:22.325  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 53321, start advertisements: true
03-29 13:31:22.325  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:22.325  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:22.325  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:22.325  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:22.328  3311  3373 I jxcore-log: ok 190 still no errors
03-29 13:31:22.328  3311  3373 I jxcore-log: 
,03-29 13:31:22.334  3311  3373 I jxcore-log: # teardown
03-29 13:31:22.334  3311  3373 I jxcore-log: 
,03-29 13:31:22.656  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:22.656  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:22.656  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:22.656  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-29 13:31:22.656  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:22.657  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:22.657  3311  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:22.657  3311  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:22.657  3311  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-29 13:31:22.657  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:31:22.658  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-29 13:31:22.658  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:22.658  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:22.658  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:31:22.658  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:22.658  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:22.658  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:31:22.659  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:22.661  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:31:22.666  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:22.666  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:22.666  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-29 13:31:22.666  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:22.666  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:22.666  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:22.666  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-29 13:31:22.667  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:22.668  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:22.668  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:22.668  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:31:22.668  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:22.673  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:22.673  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:22.673  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:22.675  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:31:22.675  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:22.676  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-29 13:31:22.677  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:22.677  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:22.677  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-29 13:31:22.678  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:22.678  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:22.678  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:22.678  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:22.678  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:22.679  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:22.679  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:22.679  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:22.679  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:22.679  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:22.680  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-29 13:31:22.680  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:22.680  2153  2217 D BtGatt.GattService: current time is 270946329270
03-29 13:31:22.681  2153  2217 D BtGatt.GattService: Batch record : [125, 100, -126, 50, -12, 89, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-29 13:31:22.681  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-29 13:31:22.682  2153  2217 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-29 13:31:22.685  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-29 13:31:22.685   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:22.693  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:22.694  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:22.694  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:22.700  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-29 13:31:22.700  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:22.700  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:22.700  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:22.700  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:22.700  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-29 13:31:22.702  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:22.703  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:22.703  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:22.705  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:22.705  3311  3373 I jxcore-log: 
,03-29 13:31:22.706  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:22.706  3311  3373 I jxcore-log: 
,03-29 13:31:22.708  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:22.708  3311  3373 I jxcore-log: 
,03-29 13:31:22.715  3311  3373 I jxcore-log: ok 191 must be stopped
03-29 13:31:22.715  3311  3373 I jxcore-log: 
,03-29 13:31:22.729  3311  3373 I jxcore-log: # setup
03-29 13:31:22.729  3311  3373 I jxcore-log: 
,03-29 13:31:23.211  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:23.211  3311  3373 I jxcore-log: 
,03-29 13:31:23.217  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:23.217  3311  3373 I jxcore-log: 
,03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:23.229  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:23.237  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:23.243  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-29 13:31:23.243  3311  3373 I jxcore-log: 
,03-29 13:31:23.250  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:23.250  3311  3373 I jxcore-log: 
,03-29 13:31:23.258  3311  3373 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-29 13:31:23.258  3311  3373 I jxcore-log: 
,03-29 13:31:23.262  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:23.262  3311  3373 I jxcore-log: 
,03-29 13:31:23.467  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
,03-29 13:31:23.467  3311  3373 I jxcore-log: 
,03-29 13:31:23.470  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 57596
03-29 13:31:23.470  3311  3373 I jxcore-log: ,
,03-29 13:31:23.474  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:23.474  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:23.474  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.478  3311  3373 I jxcore-log: ok 192 no errors
03-29 13:31:23.478  3311  3373 I jxcore-log: ,
03-29 13:31:23.479  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:23.479  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:23.479  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.483  3311  3373 I jxcore-log: ok 193 still no errors
,03-29 13:31:23.483  3311  3373 I jxcore-log: 
,03-29 13:31:23.490  3311  3373 I jxcore-log: # teardown
,03-29 13:31:23.490  3311  3373 I jxcore-log: 
,03-29 13:31:23.624  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:23.624  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:23.624  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.627  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:23.628  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:23.628  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:23.637  3311  3373 I jxcore-log: ok 194 must be stopped
03-29 13:31:23.637  3311  3373 I jxcore-log: 
,03-29 13:31:23.643  3311  3373 I jxcore-log: # setup
03-29 13:31:23.643  3311  3373 I jxcore-log: 
,03-29 13:31:23.782  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:23.782  3311  3373 I jxcore-log: 
,03-29 13:31:23.787  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:23.787  3311  3373 I jxcore-log: 
,03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:23.799  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:23.806  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:23.809  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:23.809  3311  3373 I jxcore-log: 
,03-29 13:31:23.814  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:23.814  3311  3373 I jxcore-log: 
,03-29 13:31:23.822  3311  3373 I jxcore-log: # 48. can get the network status before starting
03-29 13:31:23.822  3311  3373 I jxcore-log: 
,03-29 13:31:23.826  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:23.826  3311  3373 I jxcore-log: 
,03-29 13:31:24.044  3311  3373 I jxcore-log: ok 195 network status should have certain non-empty properties
03-29 13:31:24.044  3311  3373 I jxcore-log: 
,03-29 13:31:24.051  3311  3373 I jxcore-log: # teardown
03-29 13:31:24.051  3311  3373 I jxcore-log: 
,03-29 13:31:24.188  3311  3373 I jxcore-log: ok 196 must be stopped
03-29 13:31:24.188  3311  3373 I jxcore-log: 
,03-29 13:31:24.195  3311  3373 I jxcore-log: # setup
03-29 13:31:24.195  3311  3373 I jxcore-log: 
,03-29 13:31:24.321  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:24.321  3311  3373 I jxcore-log: 
,03-29 13:31:24.327  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:24.327  3311  3373 I jxcore-log: 
,03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:24.339  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:24.344  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:24.346  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:24.346  3311  3373 I jxcore-log: 
,03-29 13:31:24.348  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:24.348  3311  3373 I jxcore-log: 
,03-29 13:31:24.351  3311  3373 I jxcore-log: # 49. error returned with bad router
03-29 13:31:24.351  3311  3373 I jxcore-log: 
,03-29 13:31:24.353  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:24.353  3311  3373 I jxcore-log: 
,03-29 13:31:24.576  3311  3373 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-29 13:31:24.576  3311  3373 I jxcore-log: 
,03-29 13:31:24.578  3311  3373 I jxcore-log: ok 197 specific error expected
03-29 13:31:24.578  3311  3373 I jxcore-log: 
,03-29 13:31:24.581  3311  3373 I jxcore-log: # teardown
,03-29 13:31:24.581  3311  3373 I jxcore-log: 
,03-29 13:31:24.673  3311  3373 I jxcore-log: ok 198 must be stopped
03-29 13:31:24.673  3311  3373 I jxcore-log: 
,03-29 13:31:24.677  3311  3373 I jxcore-log: # setup
03-29 13:31:24.677  3311  3373 I jxcore-log: 
,03-29 13:31:24.816  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:24.816  3311  3373 I jxcore-log: 
,03-29 13:31:24.817  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:24.817  3311  3373 I jxcore-log: 
,03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:24.825  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:24.828  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:24.829  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-29 13:31:24.829  3311  3373 I jxcore-log: 
,03-29 13:31:24.832  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-29 13:31:24.832  3311  3373 I jxcore-log: 
,03-29 13:31:24.836  3311  3373 I jxcore-log: # 50. all services are stopped when we call stop
,03-29 13:31:24.836  3311  3373 I jxcore-log: 
,03-29 13:31:24.839  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-29 13:31:24.839  3311  3373 I jxcore-log: 
,03-29 13:31:25.425  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:25.425  3311  3373 I jxcore-log: 
,03-29 13:31:25.427  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 51233
03-29 13:31:25.427  3311  3373 I jxcore-log: 
,03-29 13:31:25.434  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 53321, start advertisements: false
03-29 13:31:25.434  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:25.434  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:31:25.434  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-29 13:31:25.442  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-29 13:31:25.442  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:25.442  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:25.448  2153  2169 D BtGatt.GattService: registerClient() - UUID=a0582643-38cd-4ddd-9b66-3efcb36792ad
,03-29 13:31:25.449  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=a0582643-38cd-4ddd-9b66-3efcb36792ad, clientIf=5
,03-29 13:31:25.449  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-29 13:31:25.450  2153  2219 D BtGatt.GattService: start scan with filters
03-29 13:31:25.450  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:25.451  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:25.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:25.451  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:25.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:25.451  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:25.451  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:25.451  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:25.452   821  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:25.461  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-29 13:31:25.461  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:25.462  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:25.463  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:25.463  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:25.463  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-29 13:31:25.464  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:25.464  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:31:25.465  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:31:25.465  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:25.466  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:25.468  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:25.468  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:25.468  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:25.471  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:25.472  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:25.477  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-29 13:31:25.477  3311  3373 I jxcore-log: 
,03-29 13:31:25.481  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-29 13:31:25.481  3311  3373 I jxcore-log: 
,03-29 13:31:25.490  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 51233, start advertisements: true
,03-29 13:31:25.490  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:25.490  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:25.490  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:25.495  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-29 13:31:25.495  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-29 13:31:25.495  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:25.496  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-29 13:31:25.496  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:25.496  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-29 13:31:25.496  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:25.496  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-29 13:31:25.503  2153  2219 D BtGatt.GattService: registerClient() - UUID=98808f67-f16b-4155-9b2a-064ef75fd079
,03-29 13:31:25.503  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=98808f67-f16b-4155-9b2a-064ef75fd079, clientIf=6
,03-29 13:31:25.504  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-29 13:31:25.505  2153  2227 D BtGatt.AdvertiseManager: message : 0
,03-29 13:31:25.508  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:25.511  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:25.514  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:25.515  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-29 13:31:25.515  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:25.515  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:25.516  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-29 13:31:25.518  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-29 13:31:25.518  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:31:25.518  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-29 13:31:25.519   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:25.526  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-29 13:31:25.526  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:25.526  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-29 13:31:25.526  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:25.526  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:25.528  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-29 13:31:25.528  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-29 13:31:25.528  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:25.528  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-29 13:31:25.529  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:25.529  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-29 13:31:25.529  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:25.529  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-29 13:31:25.531   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-29 13:31:25.534  3311  3926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-29 13:31:25.534  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-29 13:31:25.534  3311  3373 I jxcore-log: 
03-29 13:31:25.537  3311  3926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
03-29 13:31:25.540  3311  3373 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-29 13:31:25.540  3311  3373 I jxcore-log: 
,03-29 13:31:25.542  3311  3373 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-29 13:31:25.542  3311  3373 I jxcore-log: 
,03-29 13:31:25.544  3311  3373 I jxcore-log: DEBUG createNativeListener: new mux,
03-29 13:31:25.544  3311  3373 I jxcore-log: 
,03-29 13:31:25.547  3311  3373 I jxcore-log: ok 199 connection to servers manager should succeed after starting,
03-29 13:31:25.547  3311  3373 I jxcore-log: 
,03-29 13:31:25.569  3311  3373 I jxcore-log: ok 200 connection to router server should succeed after starting,
03-29 13:31:25.569  3311  3373 I jxcore-log: 
,03-29 13:31:25.570  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:25.571  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:25.571  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-29 13:31:25.571  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-29 13:31:25.571  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:25.571  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:25.571  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:31:25.571  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:25.571  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:25.571  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-29 13:31:25.571  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:25.571  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-29 13:31:25.572  3311  3926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-29 13:31:25.572  3311  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:25.573  3311  3926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:31:25.575  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
,03-29 13:31:25.580  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:25.581  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-29 13:31:25.581  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:25.582  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:25.582  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-29 13:31:25.582  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:25.582  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:25.582  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:25.582  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-29 13:31:25.582  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:25.583  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:31:25.585  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 13:31:25.585  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:25.586  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-29 13:31:25.587  2153  2227 D BtGatt.AdvertiseManager: message : 1
,03-29 13:31:25.589  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:25.589  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:25.589  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:31:25.593  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-29 13:31:25.593  2153  2217 D BtGatt.GattService: Client app is not null!
,03-29 13:31:25.595  2153  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-29 13:31:25.595  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:25.595  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-29 13:31:25.595  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:25.595  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:25.595  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:25.595  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:25.596  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-29 13:31:25.596  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:25.597  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:25.597  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:25.597  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:25.597  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:25.597  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:25.602  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:25.603   821  1319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:25.605  3311  3373 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-29 13:31:25.605  3311  3373 I jxcore-log: 
,03-29 13:31:25.607  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:25.608  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-29 13:31:25.608  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:25.611  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-29 13:31:25.611  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:25.611  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:25.611  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:25.611  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:25.612  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:25.612  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:25.612  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:31:25.634  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:25.635  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-29 13:31:25.635  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:25.636  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:25.636  3311  3373 I jxcore-log: 
03-29 13:31:25.637  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:25.637  3311  3373 I jxcore-log: 
03-29 13:31:25.638  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:25.638  3311  3373 I jxcore-log: 
03-29 13:31:25.643  3311  3373 I jxcore-log: ok 201 is stopped after calling stop
03-29 13:31:25.643  3311  3373 I jxcore-log: 
,03-29 13:31:25.649  3311  3373 I jxcore-log: ok 202 connection to servers manager should fail after stopping
03-29 13:31:25.649  3311  3373 I jxcore-log: 
,03-29 13:31:25.654  3311  3373 I jxcore-log: ok 203 connection to router server should fail after stopping
03-29 13:31:25.654  3311  3373 I jxcore-log: 
,03-29 13:31:25.659  3311  3373 I jxcore-log: # teardown
03-29 13:31:25.659  3311  3373 I jxcore-log: 
,03-29 13:31:25.976  3311  3373 I jxcore-log: ok 204 must be stopped
03-29 13:31:25.976  3311  3373 I jxcore-log: ,
,03-29 13:31:25.978  3311  3373 I jxcore-log: # setup
03-29 13:31:25.978  3311  3373 I jxcore-log: 
,03-29 13:31:26.138  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:26.138  3311  3373 I jxcore-log: 
,03-29 13:31:26.143  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:26.143  3311  3373 I jxcore-log: 
,03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:26.154  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:26.160  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:26.163  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:26.163  3311  3373 I jxcore-log: 
,03-29 13:31:26.167  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:26.167  3311  3373 I jxcore-log: 
,03-29 13:31:26.175  3311  3373 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-29 13:31:26.175  3311  3373 I jxcore-log: 
,03-29 13:31:26.179  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:26.179  3311  3373 I jxcore-log: 
,03-29 13:31:26.340  3311  3373 I jxcore-log: ok 205 called with right arguments
03-29 13:31:26.340  3311  3373 I jxcore-log: 
,03-29 13:31:26.342  3311  3373 I jxcore-log: # teardown
,03-29 13:31:26.342  3311  3373 I jxcore-log: 
,03-29 13:31:26.477  3311  3373 I jxcore-log: ok 206 must be stopped
03-29 13:31:26.477  3311  3373 I jxcore-log: 
,03-29 13:31:26.484  3311  3373 I jxcore-log: # setup
03-29 13:31:26.484  3311  3373 I jxcore-log: 
,03-29 13:31:26.615  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:26.615  3311  3373 I jxcore-log: ,
,03-29 13:31:26.616  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-29 13:31:26.616  3311  3373 I jxcore-log: 
,03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-29 13:31:26.626  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:26.630  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:26.635  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-29 13:31:26.635  3311  3373 I jxcore-log: 
,03-29 13:31:26.639  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-29 13:31:26.639  3311  3373 I jxcore-log: 
,03-29 13:31:26.646  3311  3373 I jxcore-log: # 52. make sure terminateListener is properly hooked up
,03-29 13:31:26.646  3311  3373 I jxcore-log: 
,03-29 13:31:26.648  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-29 13:31:26.648  3311  3373 I jxcore-log: 
,03-29 13:31:26.807  3311  3373 I jxcore-log: ok 207 called with right arguments
03-29 13:31:26.807  3311  3373 I jxcore-log: 
,03-29 13:31:26.809  3311  3373 I jxcore-log: # teardown
,03-29 13:31:26.809  3311  3373 I jxcore-log: 
,03-29 13:31:26.966  3311  3373 I jxcore-log: ok 208 must be stopped
03-29 13:31:26.966  3311  3373 I jxcore-log: 
,03-29 13:31:26.969  3311  3373 I jxcore-log: # setup
03-29 13:31:26.969  3311  3373 I jxcore-log: 
,03-29 13:31:27.111  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:27.111  3311  3373 I jxcore-log: 
,03-29 13:31:27.117  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:27.117  3311  3373 I jxcore-log: 
,03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:27.129  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:27.134  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:27.138  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-29 13:31:27.138  3311  3373 I jxcore-log: 
,03-29 13:31:27.143  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-29 13:31:27.143  3311  3373 I jxcore-log: 
,03-29 13:31:27.148  3311  3373 I jxcore-log: # 53. make sure we actually call kill connections properly
,03-29 13:31:27.148  3311  3373 I jxcore-log: 
,03-29 13:31:27.150  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:27.150  3311  3373 I jxcore-log: 
,03-29 13:31:27.282  3311  3373 I jxcore-log: ok 209 specific error expected
03-29 13:31:27.282  3311  3373 I jxcore-log: 
,03-29 13:31:27.287  3311  3373 I jxcore-log: # teardown
03-29 13:31:27.287  3311  3373 I jxcore-log: 
,03-29 13:31:27.429  3311  3373 I jxcore-log: ok 210 must be stopped
03-29 13:31:27.429  3311  3373 I jxcore-log: 
,03-29 13:31:27.435  3311  3373 I jxcore-log: # setup
03-29 13:31:27.435  3311  3373 I jxcore-log: 
,03-29 13:31:27.547  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:27.547  3311  3373 I jxcore-log: 
03-29 13:31:27.548  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:27.548  3311  3373 I jxcore-log: 
,03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:27.557  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 13:31:27.560  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:27.562  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:27.562  3311  3373 I jxcore-log: 
,03-29 13:31:27.564  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:27.564  3311  3373 I jxcore-log: 
,03-29 13:31:27.568  3311  3373 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-29 13:31:27.568  3311  3373 I jxcore-log: 
,03-29 13:31:27.570  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:27.570  3311  3373 I jxcore-log: 
,03-29 13:31:27.785  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:27.785  3311  3373 I jxcore-log: 
,03-29 13:31:27.794  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 36737
03-29 13:31:27.794  3311  3373 I jxcore-log: 
,03-29 13:31:27.799  3311  3373 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":43370,"error":{}}
03-29 13:31:27.799  3311  3373 I jxcore-log: 
,03-29 13:31:27.801  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-29 13:31:27.801  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-29 13:31:27.801  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:27.802  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:27.802  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:27.802  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:27.808  3311  3373 I jxcore-log: ok 211 failure reason is as expected
03-29 13:31:27.808  3311  3373 I jxcore-log: 
,03-29 13:31:27.809  3311  3373 I jxcore-log: ok 212 error description is as expected
03-29 13:31:27.809  3311  3373 I jxcore-log: 
,03-29 13:31:27.809  3311  3373 I jxcore-log: ok 213 must be stopped
03-29 13:31:27.809  3311  3373 I jxcore-log: 
,03-29 13:31:27.817  3311  3373 I jxcore-log: # teardown
03-29 13:31:27.817  3311  3373 I jxcore-log: 
,03-29 13:31:27.917  3311  3373 I jxcore-log: ok 214 must be stopped
03-29 13:31:27.917  3311  3373 I jxcore-log: 
,03-29 13:31:27.919  3311  3373 I jxcore-log: # setup
03-29 13:31:27.919  3311  3373 I jxcore-log: 
,03-29 13:31:28.110  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 13:31:28.110  3311  3373 I jxcore-log: 
,03-29 13:31:28.115  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:28.115  3311  3373 I jxcore-log: 
,03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:28.124  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 13:31:28.131  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:28.132  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:28.132  3311  3373 I jxcore-log: 
,03-29 13:31:28.134  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:28.134  3311  3373 I jxcore-log: ,
,03-29 13:31:28.137  3311  3373 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-29 13:31:28.137  3311  3373 I jxcore-log: 
,03-29 13:31:28.138  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:28.138  3311  3373 I jxcore-log: 
,03-29 13:31:28.286  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:28.286  3311  3373 I jxcore-log: 
,03-29 13:31:28.288  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 43173
03-29 13:31:28.288  3311  3373 I jxcore-log: 
,03-29 13:31:28.291  3311  3373 I jxcore-log: ok 215 peerIdentifier matches
03-29 13:31:28.291  3311  3373 I jxcore-log: 
,03-29 13:31:28.292  3311  3373 I jxcore-log: ok 216 error description matches
03-29 13:31:28.292  3311  3373 I jxcore-log: 
,03-29 13:31:28.295  3311  3373 I jxcore-log: # teardown
03-29 13:31:28.295  3311  3373 I jxcore-log: 
,03-29 13:31:28.453  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:28.453  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:28.453  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:28.456  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:28.456  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:28.456  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-29 13:31:28.460  3311  3373 I jxcore-log: ok 217 must be stopped
03-29 13:31:28.460  3311  3373 I jxcore-log: 
03-29 13:31:28.466  3311  3373 I jxcore-log: # setup
03-29 13:31:28.466  3311  3373 I jxcore-log: 
,03-29 13:31:28.596  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,03-29 13:31:28.596  3311  3373 I jxcore-log: 
03-29 13:31:28.598  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 13:31:28.598  3311  3373 I jxcore-log: 
,03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 13:31:28.606  3311  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 13:31:28.609  3311  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 13:31:28.611  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 13:31:28.611  3311  3373 I jxcore-log: 
,03-29 13:31:28.612  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 13:31:28.612  3311  3373 I jxcore-log: 
,03-29 13:31:28.621  3311  3373 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-29 13:31:28.621  3311  3373 I jxcore-log: 
,03-29 13:31:28.624  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 13:31:28.624  3311  3373 I jxcore-log: 
,03-29 13:31:28.843  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:28.843  3311  3373 I jxcore-log: 
,03-29 13:31:28.845  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 40399
03-29 13:31:28.845  3311  3373 I jxcore-log: 
,03-29 13:31:28.851  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 51233, start advertisements: false
,03-29 13:31:28.851  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-29 13:31:28.851  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-29 13:31:28.852  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-29 13:31:28.857  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:28.857  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:28.857  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-29 13:31:28.861  2153  2169 D BtGatt.GattService: registerClient() - UUID=a0b9baba-46f2-40cd-897d-cdd9f09902a5
03-29 13:31:28.862  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=a0b9baba-46f2-40cd-897d-cdd9f09902a5, clientIf=5
03-29 13:31:28.862  3311  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-29 13:31:28.863  2153  2170 D BtGatt.GattService: start scan with filters
,03-29 13:31:28.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:28.866  2153  2228 D BtGatt.ScanManager: handling starting scan
03-29 13:31:28.866  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:28.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-29 13:31:28.866  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:28.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:28.866  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:28.867   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:31:28.867  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:28.870  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:28.870  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-29 13:31:28.870  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-29 13:31:28.870  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:28.871  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:28.871  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
,03-29 13:31:28.877  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 13:31:28.877  3311  3373 I jxcore-log: 
,03-29 13:31:28.881  3311  3373 I jxcore-log: ok 218 discoveryActive matches,
03-29 13:31:28.881  3311  3373 I jxcore-log: 
03-29 13:31:28.882  3311  3373 I jxcore-log: ok 219 advertisingActive matches
03-29 13:31:28.882  3311  3373 I jxcore-log: 
,03-29 13:31:28.886  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-29 13:31:28.886  3311  3373 I jxcore-log: 
,03-29 13:31:28.888  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-29 13:31:28.889  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:28.889  3311  3373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-29 13:31:28.889  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:31:28.889  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-29 13:31:28.889  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-29 13:31:28.889  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-29 13:31:28.890  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:28.890  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:28.893  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:28.895  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-29 13:31:28.944   821  1406 I art     : Explicit concurrent mark sweep GC freed 31037(1469KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.402ms total 69.926ms,
03-29 13:31:28.946  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:28.946  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:28.946  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:28.946  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-29 13:31:28.946  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-29 13:31:28.946  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 13:31:28.946  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:28.946  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:28.948  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-29 13:31:28.948  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:28.949  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:28.949  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:31:28.951  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:28.951  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:28.951  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:28.951  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:28.952  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-29 13:31:28.952  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:28.952  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:28.953  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:28.954  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:28.954  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-29 13:31:28.954  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:28.954  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:28.957  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
,03-29 13:31:28.957  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-29 13:31:28.958  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
,03-29 13:31:28.960  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-29 13:31:28.960  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:28.960  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-29 13:31:28.961  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:28.961  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:28.964  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:28.964   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:28.973  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:28.973  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-29 13:31:28.973  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:28.978  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:28.978  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:28.978  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:28.978  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:28.979  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-29 13:31:28.979  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:28.979  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:28.980  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-29 13:31:28.980  3311  3373 I jxcore-log: 
03-29 13:31:28.980  3311  3373 I jxcore-log: ok 220 discoveryActive matches
03-29 13:31:28.980  3311  3373 I jxcore-log: ,
03-29 13:31:28.980  3311  3373 I jxcore-log: ok 221 advertisingActive matches
03-29 13:31:28.980  3311  3373 I jxcore-log: 
,03-29 13:31:28.982  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:28.982  3311  3373 I jxcore-log: 
,03-29 13:31:28.993  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
,03-29 13:31:28.993  3311  3373 I jxcore-log: 
,03-29 13:31:28.995  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 45966,
03-29 13:31:28.995  3311  3373 I jxcore-log: 
,03-29 13:31:29.005  3311  3373 I io.jxcore.node.ConnectionHelper: start: Port number: 45966, start advertisements: true,
03-29 13:31:29.005  3311  3373 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-29 13:31:29.005  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-29 13:31:29.005  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-29 13:31:29.008  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-29 13:31:29.008  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-29 13:31:29.008  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-29 13:31:29.008  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-29 13:31:29.015  2153  2170 D BtGatt.GattService: registerClient() - UUID=aac65bf0-edeb-458b-be9f-fa155fb2a4ff,
03-29 13:31:29.016  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=aac65bf0-edeb-458b-be9f-fa155fb2a4ff, clientIf=5
,03-29 13:31:29.025  3311  3327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-29 13:31:29.025  2153  2219 D BtGatt.GattService: start scan with filters
03-29 13:31:29.026  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-29 13:31:29.026  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-29 13:31:29.026  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-29 13:31:29.026  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-29 13:31:29.026  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-29 13:31:29.026  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-29 13:31:29.026  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-29 13:31:29.026  2153  2228 D BtGatt.ScanManager: handling starting scan
,03-29 13:31:29.026  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-29 13:31:29.026  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-29 13:31:29.026  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:29.027  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-29 13:31:29.027  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-29 13:31:29.028  2153  2217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-29 13:31:29.028  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:29.030  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-29 13:31:29.030  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:29.030  2153  2228 D BtGatt.ScanManager: Starting BLE batch scan
03-29 13:31:29.030  2153  2228 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-29 13:31:29.031  2153  2217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-29 13:31:29.031  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:29.032  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-29 13:31:29.032  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:29.034  2153  2170 D BtGatt.GattService: registerClient() - UUID=d672b96b-2d23-4f5f-a63b-551664fe58b2
,03-29 13:31:29.034  2153  2217 D BtGatt.GattService: onClientRegistered() - UUID=d672b96b-2d23-4f5f-a63b-551664fe58b2, clientIf=6
03-29 13:31:29.034  3311  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-29 13:31:29.035  2153  2227 D BtGatt.AdvertiseManager: message : 0
03-29 13:31:29.037  2153  2227 D BtGatt.AdvertiseManager: starting multi advertising
,03-29 13:31:29.040  2153  2217 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-29 13:31:29.042  2153  2217 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-29 13:31:29.042  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-29 13:31:29.043  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-29 13:31:29.043   821   836 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:29.045  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-29 13:31:29.045  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-29 13:31:29.045  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-29 13:31:29.045  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 13:31:29.046  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-29 13:31:29.046  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-29 13:31:29.046  3311  3373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-29 13:31:29.046  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-29 13:31:29.046  3311  3373 I io.jxcore.node.ConnectionHelper: start: OK
03-29 13:31:29.046  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-29 13:31:29.046  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-29 13:31:29.046  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-29 13:31:29.046  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-29 13:31:29.047  3311  3311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-29 13:31:29.047  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-29 13:31:29.047  3311  3311 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:29.047  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-29 13:31:29.047  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-29 13:31:29.047  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-29 13:31:29.047  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-29 13:31:29.047  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-29 13:31:29.048   821  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-29 13:31:29.048  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:29.048  3311  3373 I jxcore-log: 
03-29 13:31:29.049  3311  3927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-29 13:31:29.050  3311  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-29 13:31:29.053  3311  3373 I jxcore-log: not ok 222 discoveryActive matches
03-29 13:31:29.053  3311  3373 I jxcore-log: 
03-29 13:31:29.053  3311  3373 I jxcore-log:   ---
03-29 13:31:29.053  3311  3373 I jxcore-log: 
,03-29 13:31:29.053  3311  3373 I jxcore-log:     operator: equal
03-29 13:31:29.053  3311  3373 I jxcore-log: 
03-29 13:31:29.053  3311  3373 I jxcore-log:     expected: false
03-29 13:31:29.053  3311  3373 I jxcore-log: 
03-29 13:31:29.053  3311  3373 I jxcore-log:     actual:   true
03-29 13:31:29.053  3311  3373 I jxcore-log: 
03-29 13:31:29.053  3311  3373 I jxcore-log:   ...
03-29 13:31:29.053  3311  3373 I jxcore-log: 
,03-29 13:31:29.061  3311  3373 I jxcore-log: not ok 223 advertisingActive matches
03-29 13:31:29.061  3311  3373 I jxcore-log: 
03-29 13:31:29.062  3311  3373 I jxcore-log:   ---
03-29 13:31:29.062  3311  3373 I jxcore-log: 
,03-29 13:31:29.062  3311  3373 I jxcore-log:     operator: equal
03-29 13:31:29.062  3311  3373 I jxcore-log: 
03-29 13:31:29.062  3311  3373 I jxcore-log:     expected: true
03-29 13:31:29.062  3311  3373 I jxcore-log: 
,03-29 13:31:29.062  3311  3373 I jxcore-log:     actual:   false
03-29 13:31:29.062  3311  3373 I jxcore-log: 
03-29 13:31:29.062  3311  3373 I jxcore-log:   ...
03-29 13:31:29.062  3311  3373 I jxcore-log: 
,03-29 13:31:29.066  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-29 13:31:29.066  3311  3373 I jxcore-log: 
03-29 13:31:29.067  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-29 13:31:29.067  3311  3373 I jxcore-log: 
03-29 13:31:29.070  3311  3373 I jxcore-log: not ok 224 discoveryActive matches
03-29 13:31:29.070  3311  3373 I jxcore-log: 
03-29 13:31:29.070  3311  3373 I jxcore-log:   ---
03-29 13:31:29.070  3311  3373 I jxcore-log: 
,03-29 13:31:29.070  3311  3373 I jxcore-log:     operator: equal
03-29 13:31:29.070  3311  3373 I jxcore-log: 
03-29 13:31:29.070  3311  3373 I jxcore-log:     expected: false
03-29 13:31:29.070  3311  3373 I jxcore-log: 
03-29 13:31:29.071  3311  3373 I jxcore-log:     actual:   true
03-29 13:31:29.071  3311  3373 I jxcore-log: 
03-29 13:31:29.071  3311  3373 I jxcore-log:   ...
03-29 13:31:29.071  3311  3373 I jxcore-log: 
,03-29 13:31:29.073  3311  3373 I jxcore-log: not ok 225 advertisingActive matches
03-29 13:31:29.073  3311  3373 I jxcore-log: 
03-29 13:31:29.073  3311  3373 I jxcore-log:   ---
03-29 13:31:29.073  3311  3373 I jxcore-log: 
03-29 13:31:29.074  3311  3373 I jxcore-log:     operator: equal
03-29 13:31:29.074  3311  3373 I jxcore-log: 
03-29 13:31:29.074  3311  3373 I jxcore-log:     expected: false
03-29 13:31:29.074  3311  3373 I jxcore-log: 
,03-29 13:31:29.074  3311  3373 I jxcore-log:     actual:   true
03-29 13:31:29.074  3311  3373 I jxcore-log: 
03-29 13:31:29.074  3311  3373 I jxcore-log:   ...
03-29 13:31:29.074  3311  3373 I jxcore-log: 
,03-29 13:31:29.076  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-29 13:31:29.076  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-29 13:31:29.076  3311  3373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-29 13:31:29.076  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-29 13:31:29.076  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-29 13:31:29.077  3311  3373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-29 13:31:29.077  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-29 13:31:29.077  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-29 13:31:29.077  3311  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-29 13:31:29.077  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-29 13:31:29.077  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-29 13:31:29.077  3311  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-29 13:31:29.077  3311  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-29 13:31:29.077  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-29 13:31:29.077  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-29 13:31:29.080  2153  2219 D BtGatt.GattService: stopScan() - queue size =1
03-29 13:31:29.081  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-29 13:31:29.082  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-29 13:31:29.082  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-29 13:31:29.082  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-29 13:31:29.082  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-29 13:31:29.082  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-29 13:31:29.082  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-29 13:31:29.082  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-29 13:31:29.082  2153  2217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-29 13:31:29.083  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:29.083  2153  2228 D BtGatt.ScanManager: stopping BLe Batch
03-29 13:31:29.085  2153  2227 D BtGatt.AdvertiseManager: message : 1
03-29 13:31:29.086  2153  2227 D BtGatt.AdvertiseManager: stop advertise for client 6
03-29 13:31:29.087  2153  2217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-29 13:31:29.087  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-29 13:31:29.087  2153  2228 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-29 13:31:29.089  2153  2217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-29 13:31:29.089  2153  2217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-29 13:31:29.090  2153  2217 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
,03-29 13:31:29.090  2153  2217 D BtGatt.GattService: Client app is not null!
03-29 13:31:29.091  2153  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-29 13:31:29.092  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-29 13:31:29.092  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-29 13:31:29.092  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-29 13:31:29.093  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-29 13:31:29.093  3311  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-29 13:31:29.093  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:29.093  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-29 13:31:29.093  3311  3373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-29 13:31:29.095  3311  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-29 13:31:29.095  3311  3373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:29.095  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:29.095  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 13:31:29.095  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-29 13:31:29.102  3311  3311 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-29 13:31:29.102   821  1366 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 13:31:29.109  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-29 13:31:29.110  3311  3311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-29 13:31:29.110  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-29 13:31:29.110  3311  3311 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-29 13:31:29.110  3311  3311 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-29 13:31:29.114  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-29 13:31:29.114  3311  3311 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-29 13:31:29.114  3311  3311 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-29 13:31:29.114  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-29 13:31:29.114  3311  3311 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-29 13:31:29.115  3311  3311 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-29 13:31:29.116  3311  3373 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-29 13:31:29.116  3311  3373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-29 13:31:29.116  3311  3373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-29 13:31:29.118  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-29 13:31:29.118  3311  3373 I jxcore-log: 
03-29 13:31:29.119  3311  3373 I jxcore-log: ok 226 discoveryActive matches
03-29 13:31:29.119  3311  3373 I jxcore-log: 
,03-29 13:31:29.122  3311  3373 I jxcore-log: not ok 227 advertisingActive matches
03-29 13:31:29.122  3311  3373 I jxcore-log: 
03-29 13:31:29.122  3311  3373 I jxcore-log:   ---
03-29 13:31:29.122  3311  3373 I jxcore-log: 
03-29 13:31:29.122  3311  3373 I jxcore-log:     operator: equal
03-29 13:31:29.122  3311  3373 I jxcore-log: 
,03-29 13:31:29.122  3311  3373 I jxcore-log:     expected: false
03-29 13:31:29.122  3311  3373 I jxcore-log: 
03-29 13:31:29.122  3311  3373 I jxcore-log:     actual:   true
03-29 13:31:29.122  3311  3373 I jxcore-log: 
03-29 13:31:29.122  3311  3373 I jxcore-log:   ...
03-29 13:31:29.122  3311  3373 I jxcore-log: 
,03-29 13:31:29.124  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:29.124  3311  3373 I jxcore-log: 
03-29 13:31:29.125  3311  3373 I jxcore-log: ok 228 discoveryActive matches
03-29 13:31:29.125  3311  3373 I jxcore-log: 
03-29 13:31:29.126  3311  3373 I jxcore-log: ok 229 advertisingActive matches
03-29 13:31:29.126  3311  3373 I jxcore-log: 
,03-29 13:31:29.128  3311  3373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-29 13:31:29.128  3311  3373 I jxcore-log: 
,03-29 13:31:29.141  3311  3373 I jxcore-log: DEBUG createNativeListener: creating native server
03-29 13:31:29.141  3311  3373 I jxcore-log: 
,03-29 13:31:29.143  3311  3373 I jxcore-log: DEBUG createNativeListener: listening 41135,
03-29 13:31:29.143  3311  3373 I jxcore-log: ,
,03-29 13:31:29.152  3311  3373 I jxcore-log: Uncaught Promise Rejection: {},
03-29 13:31:29.152  3311  3373 I jxcore-log: 
,03-29 13:31:29.157  3311  3373 E jxcore-log: Trace: [Error: Call Stop!]
03-29 13:31:29.157  3311  3373 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-29 13:31:29.157  3311  3373 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-29 13:31:29.157  3311  3373 E jxcore-log:     at emit@events.js:98:1
03-29 13:31:29.157  3311  3373 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-29 13:31:29.157  3311  3373 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-29 13:31:29.157  3311  3373 E jxcore-log:     at $0a@node.js:917:1
03-29 13:31:29.157  3311  3373 E jxcore-log: 
,03-29 13:31:29.157  3311  3373 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-29 13:31:29.157  3311  3373 I jxcore-log: 
,03-29 13:31:29.159  3311  3373 I jxcore-log: # teardown
03-29 13:31:29.159  3311  3373 I jxcore-log: 
,03-29 13:31:29.469  3928  3928 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-29 13:31:29.472  3928  3928 D AndroidRuntime: CheckJNI is OFF
,03-29 13:31:29.592  3928  3928 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-29 13:31:29.606   821   855 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-29 13:31:29.607   821   855 I ActivityManager: Killing 3311:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-29 13:31:29.669   821   865 W PackageSettings: Skipping PackageSetting{2a7a5cf2 com.example.hello/10273} due to missing metadata
,03-29 13:31:29.810   821  1436 I WindowState: WIN DEATH: Window{2878b95c u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-29 13:31:29.810   821  1033 D WifiService: Client connection lost with reason: 4
,03-29 13:31:29.819   821   855 E libprocessgroup: failed to kill 1 processes for processgroup 3311,
,03-29 13:31:29.820   821   855 W ActivityManager: Force removing ActivityRecord{25104ef6 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-29 13:31:29.841   821   821 V ActivityManager: Display changed displayId=0
,03-29 13:31:29.857   821   836 W ActivityManager: Spurious death for ProcessRecord{315aec9d 3311:com.test.thalitest/u0a95}, curProc for 3311: null
,03-29 13:31:29.861   821   865 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-29 13:31:29.878   821  1016 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-29 13:31:29.879  1226  1226 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-29 13:31:29.879   821  1055 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-29 13:31:29.899  2985  2985 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-29 13:31:29.907   821  1403 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3311 uid 10095
,03-29 13:31:29.909  1226  1226 I Keyboard.Facilitator: onFinishInput()
,03-29 13:31:29.912  1073  1073 I art     : Explicit concurrent mark sweep GC freed 18130(803KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 899us total 40.271ms
,03-29 13:31:29.915  1226  3945 I Keyboard.Facilitator.DecoderInitializer: run()
,03-29 13:31:29.918  1226  3945 I Decoder : createOrResetDecoder
,03-29 13:31:29.940   821  1366 I ActivityManager: Start proc 3946:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
03-29 13:31:29.941  1536  1536 I art     : Explicit concurrent mark sweep GC freed 10445(502KB) AllocSpace objects, 2(32KB) LOS objects, 36% free, 27MB/43MB, paused 1.015ms total 76.416ms
,03-29 13:31:29.966  1567  1567 I ConfigService: onCreate
,03-29 13:31:29.975  1333  1333 I art     : Explicit concurrent mark sweep GC freed 4961(362KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 639us total 23.470ms
,03-29 13:31:29.977   821   821 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-29 13:31:29.977   821   821 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-29 13:31:29.985  1536  1536 W LocationOracleImpl: Best location was null
,03-29 13:31:29.998  1226  3945 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-29 13:31:30.004  1536  3968 I HotwordRecognitionRnr: Starting hotword detection.
,03-29 13:31:30.008  1536  3969 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@19daa492
,03-29 13:31:30.011   359  3972 I AudioFlinger: AudioFlinger's thread 0xb406c000 ready to run
,03-29 13:31:30.021   359  1021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-29 13:31:30.022  1536  3969 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@19daa492
,03-29 13:31:30.027  1226  3945 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-29 13:31:30.029  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-29 13:31:30.029  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-29 13:31:30.032   359  3972 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-29 13:31:30.032   359  3972 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-29 13:31:30.032   359  3972 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-29 13:31:30.032   359  3972 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-29 13:31:30.035  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-29 13:31:30.035  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-29 13:31:30.039   359  3972 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
03-29 13:31:30.039  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-29 13:31:30.040  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-29 13:31:30.041  1226  3945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-29 13:31:30.041  1226  3945 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-29 13:31:30.041  1226  3945 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-29 13:31:30.041  1226  3945 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-29 13:31:30.041  1226  3945 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-29 13:31:30.041  1226  3945 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-29 13:31:30.071  1333  1333 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-29 13:31:30.071  1333  1333 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-29 13:31:30.093  3946  3980 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-29 13:31:30.096   821   865 I art     : Explicit concurrent mark sweep GC freed 19706(1760KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 3.241ms total 185.092ms
,03-29 13:31:30.097  3946  3984 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-29 13:31:30.104   821  1406 I ActivityManager: Start proc 3985:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-29 13:31:30.109  1536  1536 I HotwordWorker: onReady
,03-29 13:31:30.115   821  1104 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3990cc06}
,03-29 13:31:30.119   821  1032 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-29 13:31:30.155   821  1469 I ActivityManager: Start proc 4004:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-29 13:31:30.161  3928  3928 I art     : System.exit called, status: 0
03-29 13:31:30.161  3928  3928 I AndroidRuntime: VM exiting with result code 0.
,03-29 13:31:30.177   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658385683
03-29 13:31:30.177   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-29 13:31:30.180   821   865 I ActivityManager: Start proc 4022:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-29 13:31:30.197  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-29 13:31:30.205  1567  1567 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-29 13:31:30.205  1567  1567 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-29 13:31:30.208   821  1436 I ActivityManager: Killing 3657:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-29 13:31:30.255   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-29 13:31:30.255   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-29 13:31:30.297   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-29 13:31:30.297   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-29 13:31:30.318   821   836 I ActivityManager: Killing 3634:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-29 13:31:30.335  3946  3980 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
03-29 13:31:30.336  3946  3980 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-29 13:31:30.336  3946  3980 E AndroidRuntime: Process: android.process.acore, PID: 3946
03-29 13:31:30.336  3946  3980 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 13:31:30.336  3946  3980 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 13:31:30.454   821  4045 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:30.454   821  4045 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:30.454   821  4045 E DropBoxManagerService: 	... 5 more
,03-29 13:31:30.467   821  4046 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 13:31:30.467   821   855 D Atlas   : Validating map...
,03-29 13:31:30.490  1757  1757 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-29 13:31:30.490  1757  4047 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-29 13:31:30.490  1757  1757 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
03-29 13:31:30.490  1757  4047 D AccountUtils: Clearing selected account for com.test.thalitest
03-29 13:31:30.493  1757  1757 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-29 13:31:30.493  1757  1757 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-29 13:31:30.500  1333  1333 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1dc360e9 new=com.google.android.velvet.VelvetApplication@1dc360e9
03-29 13:31:30.500  1536  4050 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-29 13:31:30.503  1757  4049 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-29 13:31:30.517  1757  4049 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
03-29 13:31:30.517  1757  4049 E AndroidRuntime: Process: com.google.android.gms, PID: 1757
03-29 13:31:30.517  1757  4049 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:30.517  1757  4049 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:30.523  1333  1591 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-29 13:31:30.529   821  1403 I ActivityManager: Start proc 4052:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-29 13:31:30.530  1536  4050 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-29 13:31:30.536   821  4058 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:30.536   821  4058 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:30.536   821  4058 E DropBoxManagerService: 	... 5 more
,03-29 13:31:30.538  1757  4059 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-29 13:31:30.538  1757  4059 E DriveAsyncService: disk I/O error (code 3850)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:30.538  1757  4059 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:30.556   821  4046 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 13:31:30.562   821  4046 D OpenGLRenderer: Enabling debug mode 0
,03-29 13:31:30.568   821  1320 I ActivityManager: Start proc 4071:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,03-29 13:31:30.570  1757  4047 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-29 13:31:30.574  1536  4050 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
03-29 13:31:30.575  1536  4050 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
03-29 13:31:30.575  1536  4050 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1536
03-29 13:31:30.575  1536  4050 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1333)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 13:31:30.575  1536  4050 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 13:31:30.581  1757  4080 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-29 13:31:30.581  1757  4080 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 13:31:30.581   821   855 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelp,er: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-29 13:31:30.581  1757  4080 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 13:31:30.581   821   855 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-29 13:31:30.583  1757  4080 W SQLiteOpenHelper: Opened metrics.db in read-only mode
03-29 13:31:30.583  1757  4080 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-29 13:31:30.584  1757  4080 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-29 13:31:30.585  1757  4080 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
03-29 13:31:30.586  1757  4080 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-29 13:31:30.586  1757  4080 I Process : Sending signal. PID: 1757 SIG: 9
03-29 13:31:30.595   266   266 E lowmemorykiller: Error writing /proc/1757/oom_score_adj; errno=22
03-29 13:31:30.599   821  4089 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:30.599   821  4089 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:30.599   821  4089 E DropBoxManagerService: 	... 5 more
,03-29 13:31:30.641   266   266 E lowmemorykiller: Error writing /proc/1757/oom_score_adj; errno=22
03-29 13:31:30.642   821  1469 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-29 13:31:30.642   821  1469 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
,03-29 13:31:30.677   821  1033 D WifiService: Client connection lost with reason: 4
,03-29 13:31:30.679   821   836 I ActivityManager: Process com.google.android.gms (pid 1757) has died
03-29 13:31:30.681   821   836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10961ms
03-29 13:31:30.681   821   836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10961ms
03-29 13:31:30.681   821   836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20961ms
03-29 13:31:30.681   821   836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20961ms
03-29 13:31:30.681   821   836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30961ms
03-29 13:31:30.681   821   836 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30961ms
,03-29 13:31:30.691  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:31:30.710  1567  1592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-29 13:31:30.711  1567  1592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-29 13:31:30.711  1567  1592 I GLSUser : [GLSUser] Extracting token using key: Auth
03-29 13:31:30.711  1567  1592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-29 13:31:30.713  1567  1592 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:31:30.722  3748  3748 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-29 13:31:30.722  3748  3748 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-29 13:31:30.723  3748  3748 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-29 13:31:30.724  3748  3767 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,03-29 13:31:30.887  4052  4052 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-29 13:31:30.887  4052  4052 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 13:31:30.887  4052  4052 I GAv4    :   adb logcat -s GAv4
,03-29 13:31:30.890  1536  1536 I HotwordDetector: Closing mic
03-29 13:31:30.890  1536  1744 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@19daa492
,03-29 13:31:30.914  1536  4101 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-29 13:31:30.921  4052  4052 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:31:30.934  4052  4052 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:31:30.936  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:30.936  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:30.938  4052  4104 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-29 13:31:30.938  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:30.948   359  3972 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-29 13:31:30.949   359  3972 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-29 13:31:30.950  4052  4052 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-29 13:31:30.953   359  1021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-29 13:31:30.956  1536  1747 I HotwordRecognitionRnr: Stopping hotword detection.
,03-29 13:31:30.956  1536  3968 I HotwordRecognitionRnr: Hotword detection finished
,03-29 13:31:30.966  4052  4104 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:30.966  4052  4104 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-29 13:31:30.967  4052  4104 E GAv4    : Opening the database failed, dropping the table and recreating it
,03-29 13:31:30.967  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:30.970  4052  4104 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:30.970  4052  4104 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-29 13:31:30.970  4052  4104 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:30.970  4052  4105 E SQLiteDatab,ase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:30.970  4052  4105 E SQLiteDatabase: 	at aen.run(PG:536)
03-29 13:31:30.971  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:30.971  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.972  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:30.973  4052  4104 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:30.973  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:31.011   821  1403 I ActivityManager: Start proc 4107:com.google.android.gms/u0a11 for service com.google.android.gms/.analytics.service.AnalyticsService
,03-29 13:31:31.038  4052  4126 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at aej.c(PG:139)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at aej.b(PG:398)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at agf.f(PG:417)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at oe.run(PG:1112)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.038  4052  4126 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 ,13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.038  4052  4126 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:31.050  4052  4127 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 13:31:31.050  4052  4127 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 13:31:31.055  4107  4107 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-29 13:31:31.056  4107  4107 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 13:31:31.075  1226  3945 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-29 13:31:31.075  1226  3945 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-29 13:31:31.084  4052  4127 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 13:31:31.088   821   821 I ActivityManager: Start proc 4130:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,03-29 13:31:31.104   821  1320 I ActivityManager: Killing 3181:com.google.android.talk/u0a61 (adj 15): empty #17
,03-29 13:31:31.106   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 330us total 18.406ms
,03-29 13:31:31.107  1226  3945 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-29 13:31:31.107  1226  3945 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-29 13:31:31.113  4107  4107 I MultiDex: VM with version 2.1.0 has multidex support
03-29 13:31:31.113  4107  4107 I MultiDex: install
03-29 13:31:31.113  4107  4107 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 13:31:31.116   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 237us total 10.131ms
,03-29 13:31:31.126   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 9.807ms
,03-29 13:31:31.135  4052  4127 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 13:31:31.139  4052  4147 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at aej.c(PG:139)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at aej.a(PG:358)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at aej.a(PG:345)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at agf.c(PG:884)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at aii.doInBackground(PG:1063)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.139  4052  4147 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: Failed to query Account133 object
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at aej.a(PG:358)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at aej.a(PG:345)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at agf.c(PG:884)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at aii.doInBackground(PG:1063)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.139  4052  4147 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:31.216  1567  1567 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 13:31:31.220  4052  4151 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,03-29 13:31:31.225  1226  3945 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-29 13:31:31.225  1226  3945 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-29 13:31:31.225  1226  3945 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-29 13:31:31.225  1226  3945 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-29 13:31:31.229  4107  4155 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.229  4107  4155 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:31.231  4107  4155 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.231  4107  4155 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:31.234  4130  4130 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
,03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-29 13:31:31.234  4130  4130 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-29 13:31:31.235  4130  4130 D AndroidRuntime: Shutting down VM
03-29 13:31:31.235   821  1403 I ActivityManager: Killing 2378:com.google.android.calendar/u0a37 (adj 15): empty #17
03-29 13:31:31.237  4130  4130 E AndroidRuntime: FATAL EXCEPTION: main
03-29 13:31:31.237  4130  4130 E AndroidRuntime: Process: com.android.documentsui, PID: 4130
03-29 13:31:31.237  4130  4130 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
,03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
,03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-29 13:31:31.237  4130  4130 E AndroidRuntime: 	... 9 more
,03-29 13:31:31.384   871   871 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,03-29 13:31:31.384   871   871 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-29 13:31:31.456  1096  2274 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10095)] disk I/O error
,03-29 13:31:31.467  1096  2274 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver,
03-29 13:31:31.467  1096  2274 E AndroidRuntime: Process: android.process.media, PID: 1096
03-29 13:31:31.467  1096  2274 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 13:31:31.467  1096  2274 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 13:31:31.535   821  1406 I ActivityManager: Start proc 4159:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-29 13:31:31.560   821  4170 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:31.560   821  4170 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:31.560   821  4170 E DropBoxManagerService: 	... 5 more
,03-29 13:31:31.566   821  4171 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:31.566   821  4171 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:31.566   821  4171 E DropBoxManagerService: 	... 5 more
,03-29 13:31:31.588   821  1436 I ActivityManager: Killing 3703:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-29 13:31:31.729  4107  4107 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-29 13:31:31.748  4159  4159 D ExternalStorage: After updating volumes, found 1 active roots
,03-29 13:31:31.767   821  1104 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3990cc06}
,03-29 13:31:31.795  4107  4107 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 13:31:31.814  1567  2088 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-29 13:31:31.842  4052  4069 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at aej.c(PG:139)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at aej.a(PG:358)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at aej.a(PG:345)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at agf.d(PG:281)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at agf.b(PG:312)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at agf.a(PG:221)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
03-29 13:31:31.842  4052  4069 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:446)
,03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: Failed to query Account133 object
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at aej.a(PG:358)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at aej.a(PG:345)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at agf.d(PG:281)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at agf.b(PG:312)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at agf.a(PG:221)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
03-29 13:31:31.842  4052  4069 E AbstractDatabaseInstance: 	at android.os.Binder.execTransact(Binder.java:446)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: Writing exception to parcel
03-29 13:31:31.843  4052  4069 E DatabaseUtils: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at ael.a(PG:1521)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at hix$a.a(PG:125)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at aej.c(PG:139)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at aej.a(PG:358)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at aej.a(PG:345)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at agf.d(PG:281)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at agf.b(PG:312)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at agf.a(PG:221)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
03-29 13:31:31.843  4052  4069 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
03-29 13:31:31.844  4130  4156 W Documents: Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.844  4130  4156 D Documents: Update found 6 roots in 619ms
03-29 13:31:31.852  1567  1589 I art     : Explicit concurrent mark sweep GC freed 34516(1959KB) AllocSpace objects, 2(32KB) LOS objects, 37% free, 26MB/42MB, paused 1.303ms total 38.603ms
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: Failed to open lock file
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:31.864  4107  4179 W NativeLibraryUtils: 	... 3 more
03-29 13:31:31.871  4107  4107 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-29 13:31:31.898  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:31.899  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.e.k.run(SourceFile:388)
03-29 13:31:31.900  4107  4182 E GAv4-SVC: Opening the database failed, dropping the table and recreating it
03-29 13:31:31.900  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.900  4107  4182 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.900  4052  4104 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:31.902  4107  4182 E SQLiteDatabase: 	at com.google.android.gms.e.k.run(SourceFile:388)
03-29 13:31:31.902  4107  4182 E GAv4-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.909  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.910  4107  4182 W GAv4-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.914  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.915  4107  4182 E GAv4-SVC: Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.917  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.917  4107  4184 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.917  4107  4184 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.917  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.917  4107  4184 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.917  4107  4184 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:31.924  4052  4104 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.924  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.924  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.926  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.926  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.928  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.928  4052  4104 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.930  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.930  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.932  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.932  4052  4105 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.934  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.934  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-29 13:31:31.935  4052  4105 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
03-29 13:31:31.935  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.935  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.938  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.938  4052  4104 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.939   821  1406 I ActivityManager: Killing 3784:com.google.android.gms:car/u0a11 (adj 15): empty #17
03-29 13:31:31.939  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.939  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.940  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.940  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.940  4052  4104 E GAv4    : Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.941  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.944  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.945  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.946  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.946  4052  4104 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.947  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.947  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.950  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.950  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.950  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.950  4052  4104 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.951  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.951  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.952  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.952  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.952  4052  4104 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.953  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.953  4052  4104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.954  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.955  4052  4147 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:31.956  4052  4103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: java.lang.RuntimeException: An error occured while executing doInBackground()
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at aej.c(PG:139)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at aej.a(PG:358)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at aej.a(PG:345)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at agf.c(PG:884)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at aii.doInBackground(PG:1063)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:31.957  4052  4147 E CAKEMIX_CRASHED: 	... 4 more
,03-29 13:31:32.044   821  1320 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,03-29 13:31:32.065   821  1320 V WindowManager: addAppToken: AppWindowToken{7651aae token=Token{296e729 ActivityRecord{32d47cb0 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t18}}} to stack=1 task=18 at 0
,03-29 13:31:32.068   821  1104 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,03-29 13:31:32.069  4052  4105 I Process : Sending signal. PID: 4052 SIG: 9
,03-29 13:31:32.082   266   266 E lowmemorykiller: Error writing /proc/4052/oom_score_adj; errno=22
,03-29 13:31:32.088   821  1469 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-29 13:31:32.091   821  1469 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity,
03-29 13:31:32.091   821  1469 W ActivityManager: android.os.TransactionTooLargeException
03-29 13:31:32.091   821  1469 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method),
03-29 13:31:32.091   821  1469 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
03-29 13:31:32.091   821  1469 W ActivityManager: 	,at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
03-29 13:31:32.091   821  1469 W ActivityManager: 	,at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
,03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
03-29 13:31:32.091   821  1469 W ActivityManager: 	,at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998),
03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
,03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
03-29 13:31:32.091   821  1469 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
03-29 13:31:32.091   821  1469 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
0,3-29 13:31:32.091   821  1469 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-29 13:31:32.271   821  1469 I ActivityManager: Start proc 4188:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,03-29 13:31:32.280   821  1403 W ActivityManager: Spurious death for ProcessRecord{5d1f838 4188:com.google.android.apps.docs/u0a46}, curProc for 4052: null
,03-29 13:31:32.297  1333  1646 W OpenGLRenderer: Incorrectly called buildLayer on View: ew, destroying layer...
,03-29 13:31:32.366  1567  1567 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-29 13:31:32.369  4107  4207 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.369  4107  4207 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.371  4107  4107 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.372  4107  4207 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.375  4107  4207 W SQLiteOpenHelper: Opened reminders.db in read-only mode
03-29 13:31:32.383  4107  4187 I Icing   : Storage manager: low false usage 1.98MB avail 20.70GB capacity 22.09GB
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.385  4107  4210 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.386   871   871 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-29 13:31:32.386   871   871 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
03-29 13:31:32.387  4107  4210 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #3
03-29 13:31:32.387  4107  4210 E AndroidRuntime: Process: com.google.android.gms, PID: 4107
03-29 13:31:32.387  4107  4210 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.387  4107  4210 E AndroidRuntime: 	... 4 more
03-29 13:31:32.391   821  4213 E DropBoxManagerService: Can't write: system_app_crash
03-29 13:31:32.391   821  4213 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 13:31:32.391   821  4213 E DropBoxManagerService: 	... 5 more
03-29 13:31:32.410  3812  3812 D WearableService: callingUid 10011, callindPid: 3812
03-29 13:31:32.414  1722  2115 E MDM     : [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-29 13:31:32.418  4107  4187 W Icing   : Received bad json for section weights override -- ignoring.
03-29 13:31:32.418  4107  4208 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
03-29 13:31:32.419  4107  4208 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
03-29 13:31:32.420  4107  4187 W Icing   : Received bad json for corpus context scoring override -- ignoring.
03-29 13:31:32.420  4107  4187 W Icing   : Received bad json for section weights override -- ignoring.
03-29 13:31:32.421  4107  4187 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-29 13:31:32.447  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
03-29 13:31:32.447  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
03-29 13:31:32.447  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Trie initialize fail
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-29 13:31:32.447  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-29 13:31:32.448  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-29 13:31:32.448  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
03-29 13:31:32.448  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-29 13:31:32.448  4107  4187 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
03-29 13:31:32.448  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-29 13:31:32.448  4107  4187 E Icing   : Init docstore failed
03-29 13:31:32.448  4107  4187 E Icing   : Index init failed, resetting corpora
,03-29 13:31:32.452  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
03-29 13:31:32.452  4107  4187 E Icing   : Clearing index failed
03-29 13:31:32.452  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
03-29 13:31:32.452  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-29 13:31:32.452  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-29 13:31:32.452  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : ,Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Clearing docstore failed
03-29 13:31:32.453  4107  4187 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
03-29 13:31:32.453  4107  4187 E Icing   : Deleting compact status failed
,03-29 13:31:32.509   821  1403 I art     : Explicit concurrent mark sweep GC freed 26436(1477KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 2.683ms total 63.593ms
,03-29 13:31:32.562  4188  4188 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-29 13:31:32.562  4188  4188 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-29 13:31:32.562  4188  4188 I GAv4    :   adb logcat -s GAv4
,03-29 13:31:32.567  4107  4222 D LocationInitializer: Restart initialization of location
,03-29 13:31:32.573  4188  4188 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:31:32.582  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.583  4188  4188 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:31:32.583  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.586  4188  4227 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-29 13:31:32.591  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.593  4188  4227 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.593  4188  4227 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-29 13:31:32.593  4188  4227 E GAv4    : Opening the database failed, dropping the table and recreating it
03-29 13:31:32.594  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.595  4188  4227 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209),
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: ,	at fdw.e(Unknown Source)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.595  4188  4227 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-29 13:31:32.595  4188  4227 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-29 13:31:32.595  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.596  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.596  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.596  4188  4227 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.596  4188  4188 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
03-29 13:31:32.596  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.613  4188  4231 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:32.613  4188  4231 E SQLiteDatabase: 	at aen.run(PG:536)
,03-29 13:31:32.627  1567  4232 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.627  1567  4232 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.627  1567  4232 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.632  1567  4232 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,03-29 13:31:32.632  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.636  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.637  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.638  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.639  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.640  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.640  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: ,	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.642  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.643  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.644  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.648  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153),
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.649  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.652  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505),
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.652  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.655  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: ,	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.656  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.657  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
,03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.659  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.660  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	,at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.661  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.663  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.664  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.665  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.665  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.666  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
,03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.666  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.667  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.667  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.668  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.669  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.669  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323),
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.670  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.671  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.671  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.672  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.672  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.673  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,03-29 13:31:32.674  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.674  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.675  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.676  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540),
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.677  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.677  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.678  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.679  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
,03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.679  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.680  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
,03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.680  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.683  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.685  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.686  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	,at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.687  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.690  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.691  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.691  4188  4236 E SQ,LiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at aej.c(PG:139)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at aej.b(PG:398)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at agf.f(PG:417)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at oe.run(PG:1112)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.691  4188  4236 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.692  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.692  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.692  4188  42,36 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.692  4188  4236 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.693  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.693  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.694  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.694  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.700  4188  4237 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 13:31:32.700  4188  4237 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-29 13:31:32.719  4188  4237 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-29 13:31:32.722  4188  4188 E ErrorNotificationActivity: Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,03-29 13:31:32.765  4188  4237 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-29 13:31:32.769  4188  4242 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 13:31:32.771  4188  4188 D Atlas   : Validating map...
,03-29 13:31:32.775   821  1436 V WindowManager: Adding window Window{2b208ae6 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 12 (after Window{2c6fcc58 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,03-29 13:31:32.780   821  1403 V WindowManager: Adding window Window{94f6ad4 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 13 (before Window{2b208ae6 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,03-29 13:31:32.783  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,03-29 13:31:32.783  4188  4227 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.783  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.783  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.786  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,03-29 13:31:32.787  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.788  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at ael.a(PG:1521)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at aej.c(PG:139)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at aej.a(PG:358)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at aej.a(PG:345)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at agf.c(PG:884)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at aii.doInBackground(PG:1063)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.788  4188  4243 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: Failed to query Account133 object
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at aej.a(PG:358)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at aej.a(PG:345)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at agf.c(PG:884)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at aii.doInBackground(PG:1063)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:32.789  4188  4243 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
03-29 13:31:32.790  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.790  4188  4227 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,03-29 13:31:32.792  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.792  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.792  4188  4227 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.792  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.792  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.792  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.792  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.792  4188  4231 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.792  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.792  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-29 13:31:32.793  4188  4231 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
,03-29 13:31:32.795  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.795  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.795  4188  4227 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.795  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.796  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.796  4188  4227 E GAv4    : Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.796  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.796  4188  4227 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.796  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.796  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.796  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.797  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.797  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.797  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.798  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.798  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.798  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.799  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-29 13:31:32.800  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,03-29 13:31:32.801  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.801  4188  4227 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,03-29 13:31:32.802   821  1406 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
03-29 13:31:32.802  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.802  4188  4226 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-29 13:31:32.803  4188  4227 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-29 13:31:32.804  4188  4231 I Process : Sending signal. PID: 4188 SIG: 9
,03-29 13:31:32.929   821  1469 I WindowState: WIN DEATH: Window{2b208ae6 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
03-29 13:31:32.931   821  1015 W Looper  : Ignoring unexpected epoll events 0x11 on fd 230 that is no longer registered.
,03-29 13:31:32.931   821  1015 W InputDispatcher: channel '94f6ad4 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
03-29 13:31:32.931   821  1015 E InputDispatcher: channel '94f6ad4 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,03-29 13:31:32.932   821  1403 I ActivityManager: Process com.google.android.apps.docs (pid 4188) has died
03-29 13:31:32.935   821  1403 W ActivityManager: Force removing ActivityRecord{32d47cb0 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t18}: app died, no saved state
,03-29 13:31:32.942   821  1320 I WindowState: WIN DEATH: Window{94f6ad4 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,03-29 13:31:32.942   821  1320 W InputDispatcher: Attempted to unregister already unregistered input channel '94f6ad4 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,03-29 13:31:33.145  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:33.147  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:33.149  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:33.150  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:33.155  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
,03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:33.158  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:33.165  1567  4232 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 13:31:33.165  1567  4232 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 13:31:33.387   871   871 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!,
,03-29 13:31:33.387   871   871 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request,
,03-29 13:31:34.389   871   871 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-29 13:31:34.389   871   871 I kickstart: WARNING: function: sahara_start:892 Retrying memory read request
,03-29 13:31:35.034  1536  4251 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-29 13:31:35.058  1567  1567 I ConfigService: onDestroy
,03-29 13:31:35.390   871   871 E kickstart: ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
03-29 13:31:35.390   871   871 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
,03-29 13:31:35.392   871   871 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-29 13:31:35.392   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-29 13:31:35.628   821  1245 E QMI_FW  : xport_send: Sendto failed for port 4608
03-29 13:31:35.628   821  1245 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-29 13:31:35.629   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658385683
03-29 13:31:35.629   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-29 13:31:35.629   821  1245 E QMI_FW  : xport_send: Sendto failed for port 4608
03-29 13:31:35.629   821  1245 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-29 13:31:35.629   821  1245 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-29 13:31:35.633   270   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
