#### Test 640346198400100_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-24 15:03:57.259  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:03:57.527  3321  3321 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 15:03:57.529  3321  3321 D AndroidRuntime: CheckJNI is OFF
03-24 15:03:57.644  3321  3321 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 15:03:57.649   823  1246 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 15:03:57.655   823  1246 V WindowManager: addAppToken: AppWindowToken{29220b11 token=Token{4579f38 ActivityRecord{1a9df9b u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 15:03:57.663   823   862 V WindowManager: Adding window Window{2b731d50 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1cd84f7f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 15:03:57.668  3321  3321 D AndroidRuntime: Shutting down VM
03-24 15:03:57.673  1511  1777 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@97a9e85
03-24 15:03:57.673  1511  1511 I HotwordDetector: Closing mic
03-24 15:03:57.736   823  1297 I ActivityManager: Start proc 3335:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 15:03:57.743   358  1784 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 15:03:57.744   358  1784 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 15:03:57.749   358  1024 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 15:03:57.750  1511  1781 I HotwordRecognitionRnr: Hotword detection finished
03-24 15:03:57.751  1511  1779 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 15:03:57.760   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 321us total 23.481ms
03-24 15:03:57.771   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 237us total 10.084ms
03-24 15:03:57.783   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 11.476ms
03-24 15:03:57.801   823  1469 I ActivityManager: Killing 2908:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
03-24 15:03:57.866   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659208979
03-24 15:03:57.867   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 15:03:57.907   823  1469 I ActivityManager: Killing 2736:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,03-24 15:03:57.951   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 15:03:57.952   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 15:03:57.993   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
,03-24 15:03:57.993   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing,
,03-24 15:03:58.090  3335  3335 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 15:03:58.107  3335  3335 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7192-7196)
,03-24 15:03:58.107  3335  3335 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 15:03:58.123  3335  3335 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39001e84}
,03-24 15:03:58.123  3335  3335 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 15:03:58.124  3335  3335 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 15:03:58.136  3335  3335 I BrowserStartupController: Initializing chromium process, singleProcess=true,
03-24 15:03:58.136  3335  3335 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:03:58.137  3335  3335 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 15:03:58.147  3335  3358 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 15:03:58.155  3335  3335 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 15:03:58.161  3335  3335 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 15:03:58.161  3335  3335 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 15:03:58.161  3335  3335 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 15:03:58.260   823   861 D BluetoothManagerService: Message: 20
,03-24 15:03:58.260   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63758b9:true
,03-24 15:03:58.324  3335  3335 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 15:03:58.334  3335  3335 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 15:03:58.349  3335  3335 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 15:03:58.355  3335  3335 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 15:03:58.355  3335  3335 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 15:03:58.421  3335  3381 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 15:03:58.425  3335  3335 D Atlas   : Validating map...
,03-24 15:03:58.435   823  1401 V WindowManager: Adding window Window{2f02e229 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2b731d50 u0 Starting com.test.thalitest})
,03-24 15:03:58.439  3335  3368 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 15:03:58.488  3335  3381 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 15:03:58.507  3335  3381 D OpenGLRenderer: Enabling debug mode 0
,03-24 15:03:58.572   823   862 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +904ms
,03-24 15:03:58.578  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 15:03:58.681  3335  3335 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3335
,03-24 15:03:58.858  3335  3335 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 15:03:58.990   873   873 I kickstart: STATUS: Received file 'm9kefs1'
03-24 15:03:58.990   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.996175 seconds
03-24 15:03:58.990   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-24 15:03:58.990   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 15:03:58.993   873   873 I kickstart: STATUS: Sahara protocol completed
,03-24 15:03:59.005  3335  3383 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580605184
,03-24 15:03:59.010  3335  3383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 15:03:59.010  3335  3383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 15:03:59.010  3335  3383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 15:03:59.010  3335  3383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 15:03:59.010  3335  3383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 15:03:59.010  3335  3383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8ae349 added. We now have 1 listener(s)
03-24 15:03:59.011   823  1246 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:03:59.014  3335  3383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-24 15:03:59.016  3335  3383 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:03:59.016  3335  3383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 15:03:59.016  3335  3383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 15:03:59.019  3335  3383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c5767c added. We now have 1 listener(s)
03-24 15:03:59.020  3335  3383 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 15:03:59.023   823  1035 D WifiService: New client listening to asynchronous messages
,03-24 15:03:59.025  3335  3383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 15:03:59.028  3335  3383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 15:03:59.028  3335  3383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-24 15:03:59.028  3335  3383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-24 15:03:59.028  3335  3383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 15:03:59.032  3335  3383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-24 15:03:59.033   823  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:03:59.034  3335  3383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 15:03:59.040  3335  3383 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-24 15:03:59.040  3335  3383 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 15:03:59.040  3335  3383 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-24 15:03:59.042  3335  3335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 15:03:59.044  3335  3383 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 15:03:59.075  3335  3335 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 15:03:59.765  3335  3394 W jxcore-log: Initializing JXcore engine
03-24 15:03:59.765  3335  3394 W jxcore-log: JXcore engine is ready
,03-24 15:03:59.790  3394  3394 W Thread-356: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11491]" dev="sockfs" ino=11491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 15:03:59.790  3394  3394 W Thread-356: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-24 15:03:59.790  3394  3394 W Thread-356: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9796]" dev="sockfs" ino=9796 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 15:03:59.790  3394  3394 W Thread-356: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20099]" dev="sockfs" ino=20099 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-24 15:03:59.824  3335  3394 W jxcore-log: Starting JXcore engine
,03-24 15:04:00.013  3335  3394 W jxcore-log: Platform android
03-24 15:04:00.013  3335  3394 W jxcore-log: 
,03-24 15:04:00.013  3335  3394 W jxcore-log: Process ARCH arm
03-24 15:04:00.013  3335  3394 W jxcore-log: 
,03-24 15:04:00.242  3335  3394 I jxcore-log: JXcore Cordova bridge is ready!
03-24 15:04:00.242  3335  3394 I jxcore-log: 
03-24 15:04:00.243  3335  3394 W jxcore-log: JXcore engine is started
,03-24 15:04:00.253  3335  3383 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-24 15:04:00.256  3335  3335 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 15:04:01.982  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:02.087   823   823 I art     : Explicit concurrent mark sweep GC freed 41116(2027KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.502ms total 102.099ms
,03-24 15:04:02.136  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 15:04:02.137  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:04:02.137  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:04:02.138  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:02.142  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:02.153  2776  2776 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 15:04:02.153  2776  2776 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 15:04:02.153  2776  2776 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 15:04:03.590   823   864 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-24 15:04:03.606   823   864 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 15:04:03.648   259   283 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (204 us)
,03-24 15:04:04.211   823   862 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-24 15:04:04.211   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-24 15:04:04.211   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 15:04:04.213   823   823 V ActivityManager: Display changed displayId=0,
,03-24 15:04:04.481   259   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 15:04:04.485   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-24 15:04:04.485   823  1054 D SurfaceControl: Excessive delay in setPowerMode(): 275ms
,03-24 15:04:04.493   823   864 I DreamManagerService: Entering dreamland.,
,03-24 15:04:04.496   823   864 I PowerManagerService: Dozing...
,03-24 15:04:04.496   823   859 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 15:04:04.499   358  1025 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-24 15:04:04.499   358  1025 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-24 15:04:04.507   823  1034 E WifiStateMachine: cancelDelayedScan -> 16
,03-24 15:04:04.515   823  1034 E native  : do suspend false
,03-24 15:04:04.553  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 15:04:04.564   823  1034 E WifiStateMachine: cancelDelayedScan -> 18
,03-24 15:04:04.619   823  1034 E native  : do suspend true
,03-24 15:04:04.679   358   358 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 15:04:04.679   358   358 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 15:04:04.716   823  1034 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-24 15:04:05.325   823  1034 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-24 15:04:07.072  1171  1171 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-24 15:04:07.495  1171  1171 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 15:04:07.528  1171  1171 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-24 15:04:07.528  1171  1171 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 15:04:07.542   823  1034 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
,03-24 15:04:07.543   823  1036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,03-24 15:04:07.543   823  1034 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-24 15:04:07.546   823  1034 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 15:04:07.561   354   816 D CommandListener: Setting iface cfg
,03-24 15:04:07.569   823  1034 E WifiStateMachine: Start Dhcp Watchdog 1
,03-24 15:04:07.574   823  1034 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 15:04:07.574   823  1034 E WifiStateMachine:  my bss beacon rx: 0
03-24 15:04:07.574   823  1034 E WifiStateMachine:  RSSI mgmt: -43
03-24 15:04:07.574   823  1034 E WifiStateMachine:  BE :  rx=0 tx=4 lost=0 retries=0
03-24 15:04:07.574   823  1034 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 15:04:07.574   823  1034 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 15:04:07.574   823  1034 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 15:04:07.574   823  1034 E WifiStateMachine:  on_time : 481 tx_time=63 rx_time=84 scan_time=0
,03-24 15:04:07.678   823  1034 E native  : do suspend false
,03-24 15:04:07.692   823  1034 E WifiStateMachine: scanCount==0 - aborting
,03-24 15:04:07.943  3403  3403 I dhcpcd  : version 5.5.6 starting
,03-24 15:04:08.073  3403  3403 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 15:04:08.284  3403  3403 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-24 15:04:08.431  3403  3403 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-24 15:04:08.911   823  1034 E native  : do suspend true
,03-24 15:04:08.957   823  1036 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-24 15:04:08.961   823  1036 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 15:04:08.969   823  1034 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 15:04:08.989   823  1036 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-24 15:04:08.989   823  1036 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-24 15:04:08.991   823  1036 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 15:04:08.992   823  1036 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 15:04:08.994   823  1036 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 15:04:09.003   823  1036 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 15:04:09.006   823  1036 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-24 15:04:09.007   823  3401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,03-24 15:04:09.007   823  3401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-24 15:04:09.008   823  3401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,03-24 15:04:09.009   823  3401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-24 15:04:09.009   823  1036 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,03-24 15:04:09.009   823  1036 D ConnectivityService:    accepting network in place of null
03-24 15:04:09.010   823  1036 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-24 15:04:09.012   823  1036 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 15:04:09.015   823  1036 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 15:04:09.015   823  1036 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 15:04:09.015  1075  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 15:04:09.015   823  1036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-24 15:04:09.016   823  1036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-24 15:04:09.019   823   861 D Tethering: MasterInitialState.processMessage what=3
,03-24 15:04:09.023   823  1442 V BackupManagerService: Scheduling immediate backup pass
,03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:04:09.027  3335  3335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:04:09.027  3335  3335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 15:04:09.028   823   823 V BackupManagerService: Running a backup pass
,03-24 15:04:09.029  1511  1511 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
03-24 15:04:09.029  2960  2960 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-24 15:04:09.030  1287  1306 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 15:04:09.030  1287  1306 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-24 15:04:09.030   823  1053 V BackupManagerService: clearing pending backups
03-24 15:04:09.033   823   856 D TelephonyManager: getDataEnabled: retVal=false
,03-24 15:04:09.038  2960  2960 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-24 15:04:09.042   823  1053 V PerformBackupTask: Beginning backup of 14 targets
,03-24 15:04:09.047   823   856 E GpsLocationProvider: No APN found to select.
,03-24 15:04:09.049   823  1053 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 15:04:09.052   823  1053 V BackupServiceBinder: doBackup() invoked
,03-24 15:04:09.055   823  1053 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 15:04:09.071   823  1311 I ActivityManager: Start proc 3443:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 15:04:09.086   823  1053 I BackupRestoreController: Getting widget state for user: 0
,03-24 15:04:09.107  1812  1850 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-24 15:04:09.109  1812  1850 V GmsBackupTransport: starting performBackup for @pm@
,03-24 15:04:09.113  1812  1850 V GmsBackupTransport: performBackup done for @pm@
,03-24 15:04:09.126  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:09.148  1389  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 15:04:09.149  1389  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:09.149  1389  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:09.149  1389  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:09.151   823  1267 D AlarmManagerService: Setting time of day to sec=1458828249
03-24 15:04:09.539   823  1267 W AlarmManagerService: Unable to set rtc to 1458828249: Invalid argument
,03-24 15:04:09.540  1389  1928 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:09.541   823  3464 D GpsLocationProvider: NTP server returned: 1458828249539 (Thu Mar 24 15:04:09 GMT+01:00 2016) reference: 168240 certainty: 20 system time offset: -1
,03-24 15:04:09.568  1389  1928 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:04:09.568  1389  1928 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:04:09.568  1389  1928 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:04:09.568  1389  1928 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 15:04:09.568  1389  1928 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 15:04:09.568  1389  1928 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 15:04:09.568  1389  1928 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 15:04:09.575   823  3401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 14:04:09 GMT], X-Android-Received-Millis=[1458828249575], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458828249130]}
03-24 15:04:09.576   823  3401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
,03-24 15:04:09.577   823  1036 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 15:04:09.577   823  1036 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 15:04:09.577   823  1036 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 15:04:09.577   823  1036 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 15:04:09.577   823  1036 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 15:04:09.577   823  1036 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 15:04:09.578  1075  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 15:04:09.585  1812  1853 W GmsBackupTransport: Error sending final backup to server: 
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 15:04:09.585  1812  1853 W GmsBackupTransport: 	... 1 more
,03-24 15:04:09.587   823  1053 D BackupManagerService: Now staging backup of com.google.android.talk
,03-24 15:04:09.616   823  1053 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-24 15:04:09.637   823  1053 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 15:04:09.648   823  1053 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 15:04:09.650   823  1053 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 15:04:09.652   823  1053 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 15:04:09.653   823  1053 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 15:04:09.655   823  1053 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 15:04:09.656   823  1053 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 15:04:09.658   823  1053 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 15:04:09.659   823  1053 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 15:04:09.661   823  1053 D BackupManagerService: Now staging backup of com.android.vending
,03-24 15:04:09.662   823  1053 D BackupManagerService: Now staging backup of android
,03-24 15:04:09.664   823  1053 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 15:04:09.666  1812  1828 I GmsBackupTransport: Next backup will happen in 43199909 millis.
,03-24 15:04:09.668   823  1053 I BackupManagerService: Backup pass finished.
,03-24 15:04:09.670  1389  1734 I art     : Explicit concurrent mark sweep GC freed 26140(1383KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 826us total 25.340ms
,03-24 15:04:09.692  1785  3482 W DriveInitializer: Background init thread started
,03-24 15:04:09.708  1785  3466 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 15:04:09.729   823  1094 I ActivityManager: Start proc 3484:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 15:04:09.767  1785  3483 W DriveInitializer: Awaiting to be initialized
,03-24 15:04:09.772  3484  3484 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 15:04:09.785  3484  3484 D SprintDMHelper: simOperator:  IMSI: null
03-24 15:04:09.785  3484  3484 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-24 15:04:09.790  1785  1785 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 15:04:09.800  1785  1785 D SystemUpdateService: onCreate
,03-24 15:04:09.804  1785  1785 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 15:04:09.811  1785  3511 I SystemUpdateService: active receiver: enabled
,03-24 15:04:09.818  1785  3511 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-24 15:04:09.819  1785  3482 W DriveInitializer: Background init thread ended
,03-24 15:04:09.829  1785  3511 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 15:04:09.829  1785  3511 I SystemUpdateService: now status is 0 (complete)
03-24 15:04:09.829  1785  3511 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 15:04:09.829  1785  3511 I SystemUpdateService: file has been verified
03-24 15:04:09.829  1785  3511 I SystemUpdateService: OTA package size = 25802302
,03-24 15:04:09.845  1389  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:04:09.845  1389  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:09.845  1389  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:09.845  1389  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:09.849  1389  1928 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:09.859  1785  3511 I SystemUpdateService: showing system update notification
,03-24 15:04:09.864  3143  3480 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:04:09.864  3143  3480 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:04:09.864  3143  3480 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	... 12 more
03-24 15:04:09.864  3143  3480 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at fal.a(PG:38)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:04:09.864  3143  3480 E HttpOperation: 	... 14 more
,03-24 15:04:09.877   823   823 I ValidateNoPeople: skipping global notification
,03-24 15:04:09.903  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:04:09.903  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:09.903  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:09.903  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:09.907  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:09.912  1785  1785 D SystemUpdateService: onDestroy
,03-24 15:04:09.918  3143  3480 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:04:09.918  3143  3480 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at hec.a(PG:42)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at hee.a(PG:102)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at czr.a(PG:65)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at kka.a(PG:108)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:04:09.918  3143  3480 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	... 15 more
03-24 15:04:09.918  3143  3480 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at fal.a(PG:38)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:04:09.918  3143  3480 E HttpOperation: 	... 17 more
03-24 15:04:09.918  3143  3480 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:04:09.918  3143  3480 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	... 15 more
03-24 15:04:09.918  3143  3480 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:04:09.918  3143  3480 E ExperimentLoader: 	... 17 more
03-24 15:04:09.935  1785  3520 I iu.SyncManager: SYNC; picasa accounts
03-24 15:04:09.940  1785  1785 D NetworkLogImpl: Loaded NetworkSpeedPredictor
03-24 15:04:09.942  1785  1785 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
03-24 15:04:09.948  1785  3520 I iu.UploadsManager: num queued entries: 0
,03-24 15:04:09.957  1785  3520 I iu.UploadsManager: num updated entries: 0
03-24 15:04:09.958  1785  3520 I iu.SyncManager: NEXT; no task
,03-24 15:04:09.958  1785  1785 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-24 15:04:09.960  1785  1785 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-24 15:04:09.980   823  1469 I ActivityManager: Start proc 3525:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 15:04:10.035   823   856 I ActivityManager: Start proc 3542:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 15:04:10.054   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 38095, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:04:10.054   823  1311 I ActivityManager: Killing 2936:com.android.settings/1000 (adj 15): empty #17
,03-24 15:04:10.127  3212  3522 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 15:04:10.162   823  1442 I ActivityManager: Killing 2453:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 15:04:10.230  3525  3525 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 15:04:10.230  3525  3525 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 15:04:10.230  3525  3525 I GAv4    :   adb logcat -s GAv4
,03-24 15:04:10.252   823   856 I ActivityManager: Start proc 3567:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 15:04:10.260  3525  3525 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:04:10.303  3525  3525 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:04:10.304  1389  3564 D GCM     : Connected
,03-24 15:04:10.312  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:04:10.312  3335  3394 I jxcore-log: 
,03-24 15:04:10.314  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:04:10.314  3335  3394 I jxcore-log: 
,03-24 15:04:10.330  3525  3585 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:04:10.331  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:04:10.333  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:04:10.335  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:04:10.335  3335  3394 I jxcore-log: 
03-24 15:04:10.336  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:04:10.336  3335  3394 I jxcore-log: 
03-24 15:04:10.337  1389  3564 D GCM     : Message class com.google.f.a.a.p
,03-24 15:04:10.471  1389  1734 I art     : Explicit concurrent mark sweep GC freed 11483(644KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 738us total 30.739ms
,03-24 15:04:10.497  3542  3542 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-24 15:04:10.512  3542  3542 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 15:04:10.514  3525  3525 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 15:04:10.523  3525  3525 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9224-9225)
,03-24 15:04:10.523  3525  3525 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 15:04:10.527  3525  3525 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34ff5f7b}
03-24 15:04:10.527  3525  3525 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 15:04:10.527  3525  3525 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 15:04:10.534  3525  3525 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 15:04:10.535  3525  3525 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 15:04:10.535  3525  3525 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 15:04:10.545   823  1094 I art     : Explicit concurrent mark sweep GC freed 55493(2MB) AllocSpace objects, 7(153KB) LOS objects, 32% free, 33MB/49MB, paused 1.254ms total 60.208ms
,03-24 15:04:10.547  3525  3525 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-24 15:04:10.551  3525  3525 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 15:04:10.552  3525  3525 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 15:04:10.552  3525  3525 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 15:04:10.564  3567  3604 V KeepSync: Connecting to GoogleApiClient
,03-24 15:04:10.609  1785  3616 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 15:04:10.619  3525  3627 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 15:04:10.621  1785  3616 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 15:04:10.627  3525  3525 I NSApplication: Starting up...
,03-24 15:04:10.644  1389  1423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 15:04:10.644  1389  1423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:10.644  1389  1423 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:10.644  1389  1423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:10.655   823  1311 I ActivityManager: Start proc 3632:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 15:04:10.659  3542  3618 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:04:10.661  1389  1423 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: Handling authorization failure
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:04:10.682  1785  3616 E ClientConnectionOperation: 	... 7 more
,03-24 15:04:10.685  3567  3604 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 15:04:10.691  3567  3604 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:04:10.696  3567  3604 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 15:04:10.696  3567  3604 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:04:10.765  1389  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 15:04:10.766  1389  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:10.766  1389  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:10.766  1389  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:10.768  1389  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:10.797  3567  3604 E KeepSync: IOException
03-24 15:04:10.797  3567  3604 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:04:10.797  3567  3604 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:04:10.797  3567  3604 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:04:10.797  3567  3604 E KeepSync: 	... 10 more
03-24 15:04:10.797  3567  3604 W KeepSync: Sync result 2
,03-24 15:04:10.802   823   838 I ActivityManager: Killing 3051:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 15:04:10.803   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38103, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:04:10.855  3542  3656 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:04:10.912  3335  3394 I jxcore-log: Unit Test app is loaded
03-24 15:04:10.912  3335  3394 I jxcore-log: 
,03-24 15:04:10.918  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:04:10.918  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:04:10.918  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:10.918  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:10.919  3335  3335 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 15:04:10.921  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:10.921  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:04:10.921  3335  3394 I jxcore-log: 
,03-24 15:04:10.929  3335  3394 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 15:04:10.931  3335  3394 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 15:04:10.931  3335  3394 I jxcore-log: 
,03-24 15:04:10.932  3335  3394 I jxcore-log: My device name is: motorola-Nexus 6
03-24 15:04:10.932  3335  3394 I jxcore-log: 
,03-24 15:04:10.967  1389  1427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:04:10.967  1389  1427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:10.967  1389  1427 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:10.967  1389  1427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:10.971  1389  1427 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:10.983  3542  3656 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:04:10.984  3542  3618 E BooksSync: Soft error
03-24 15:04:10.984  3542  3618 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:04:10.984  3542  3618 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:04:10.984  3542  3618 E BooksSync: Sync error
03-24 15:04:10.984  3542  3618 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:04:10.984  3542  3618 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:04:10.984  3542  3618 I BooksSync: Finished books sync
,03-24 15:04:11.017   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38103, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:04:11.022   823  1443 I ActivityManager: Killing 3073:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 15:04:11.255   823  1297 I ActivityManager: Start proc 3663:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-24 15:04:11.257   823  1297 I ActivityManager: Killing 3099:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-24 15:04:11.388   823  1465 I ActivityManager: Killing 3031:android.process.acore/u0a5 (adj 15): empty #17
,03-24 15:04:12.217   823  1246 I ActivityManager: Killing 2837:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 15:04:12.495   823   838 I ActivityManager: Start proc 3681:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 15:04:12.587  3681  3681 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458828252587
03-24 15:04:12.587  3681  3681 D         : TimeServiceNative: User Time to be set is 1458828252587
03-24 15:04:12.587  3681  3681 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 15:04:12.587  3681  3681 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
,03-24 15:04:12.587  3681  3681 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458828252587,
03-24 15:04:12.588  3681  3681 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 15:04:12.588   373   876 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458828252587
03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458828252587, operation = 0
,03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 10:15:55
03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:Value read from RTC seconds = 19131355000
,03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:new time 1458828252587 
,03-24 15:04:12.588   373  3698 D QC-time-services: Daemon: delta 1439696897587 genoff 1439696897587 
03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897587 to memory
,03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 15:04:12.588   373  3698 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-24 15:04:12.592   373  3698 D QC-time-services: Updating the TOD offset
,03-24 15:04:12.592   373  3698 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897587 to memory,
03-24 15:04:12.592   373  3698 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 15:04:12.592   373  3698 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-24 15:04:12.595   373  3698 E QC-time-services: Daemon:Update to modem bit set
03-24 15:04:12.595   373  3698 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 15:04:12.595   373  3698 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142863452587
,03-24 15:04:12.596  3681  3681 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-24 15:04:12.664   373   876 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 15:04:12.670   373   874 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,03-24 15:04:12.678   823  1246 I ActivityManager: Start proc 3700:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 15:04:12.685   823  1469 I ActivityManager: Killing 3191:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 15:04:12.951  3700  3700 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 15:04:12.951  3700  3700 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 15:04:12.951  3700  3700 I GAv4    :   adb logcat -s GAv4
,03-24 15:04:12.966  3700  3700 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:04:13.000  3700  3700 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:04:13.010  3700  3719 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 15:04:13.119  1785  1785 V Herrevad: NQAS connected
,03-24 15:04:13.139  3212  3212 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-24 15:04:13.140  3212  3212 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:04:13.188  1785  3722 I art     : Explicit concurrent mark sweep GC freed 14680(1138KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.204ms total 46.965ms
,03-24 15:04:13.191   823  1035 D WifiService: New client listening to asynchronous messages
,03-24 15:04:13.279   823  1467 I art     : Explicit concurrent mark sweep GC freed 21750(960KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.380ms total 63.112ms
,03-24 15:04:13.323  1389  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-24 15:04:13.323  1389  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:13.323  1389  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:13.323  1389  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:13.326  1389  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:13.336  3212  3727 E Babel   : UserRecoverableAuthException.
03-24 15:04:13.336  3212  3727 E Babel   : eei: BadAuthentication
03-24 15:04:13.336  3212  3727 E Babel   : 	at eeg.a(Unknown Source)
03-24 15:04:13.336  3212  3727 E Babel   : 	at eeg.a(Unknown Source)
03-24 15:04:13.336  3212  3727 E Babel   : 	at eeg.a(Unknown Source)
03-24 15:04:13.336  3212  3727 E Babel   : 	at g.a(Unknown Source)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cae.a(SourceFile:3089)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cae.a(SourceFile:1131)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cws.a(SourceFile:4333)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cws.a(SourceFile:1419)
03-24 15:04:13.336  3212  3727 E Babel   : 	at crl.a(SourceFile:492)
03-24 15:04:13.336  3212  3727 E Babel   : 	at crl.a(SourceFile:1468)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cas.b(SourceFile:106)
03-24 15:04:13.336  3212  3727 E Babel   : 	at cap.d(SourceFile:335)
03-24 15:04:13.336  3212  3727 E Babel   : 	at caq.run(SourceFile:81)
,03-24 15:04:13.336  3212  3727 E Babel   : Error getting auth token
03-24 15:04:13.337  3212  3727 E Babel   : dvm
03-24 15:04:13.337  3212  3727 E Babel   : 	at g.a(Unknown Source)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cae.a(SourceFile:3089)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cae.a(SourceFile:1131)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cws.a(SourceFile:4333)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cws.a(SourceFile:1419)
03-24 15:04:13.337  3212  3727 E Babel   : 	at crl.a(SourceFile:492)
03-24 15:04:13.337  3212  3727 E Babel   : 	at crl.a(SourceFile:1468)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cas.b(SourceFile:106)
03-24 15:04:13.337  3212  3727 E Babel   : 	at cap.d(SourceFile:335)
03-24 15:04:13.337  3212  3727 E Babel   : 	at caq.run(SourceFile:81)
,03-24 15:04:13.339  3212  3727 E Babel   : Account registration failed 1-Redacted-21
,03-24 15:04:13.340  3212  3727 E Babel   : cyp: null -- null
03-24 15:04:13.340  3212  3727 E Babel   : 	at cae.a(SourceFile:3121)
03-24 15:04:13.340  3212  3727 E Babel   : 	at cae.a(SourceFile:1131)
03-24 15:04:13.340  3212  3727 E Babel   : 	at cws.a(SourceFile:4333)
03-24 15:04:13.340  3212  3727 E Babel   : 	at cws.a(SourceFile:1419)
03-24 15:04:13.340  3212  3727 E Babel   : 	at crl.a(SourceFile:492)
03-24 15:04:13.340  3212  3727 E Babel   : 	at crl.a(SourceFile:1468)
03-24 15:04:13.340  3212  3727 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 15:04:13.340  3212  3727 E Babel   : 	at cas.b(SourceFile:106)
03-24 15:04:13.340  3212  3727 E Babel   : 	at cap.d(SourceFile:335)
03-24 15:04:13.340  3212  3727 E Babel   : 	at caq.run(SourceFile:81)
,03-24 15:04:13.354  3212  3727 I art     : Note: end time exceeds epoch: 
,03-24 15:04:13.366  1389  1427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 15:04:13.366  1389  1427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:13.366  1389  1427 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:13.366  1389  1427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:13.369  1389  1427 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:13.381  1389  1427 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 15:04:13.395  3212  3736 E Babel   : Unexpected exception while authenticating.
03-24 15:04:13.395  3212  3736 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 15:04:13.395  3212  3736 E Babel   : 	at eeg.b(Unknown Source)
03-24 15:04:13.395  3212  3736 E Babel   : 	at eeg.b(Unknown Source)
03-24 15:04:13.395  3212  3736 E Babel   : 	at g.a(Unknown Source)
03-24 15:04:13.395  3212  3736 E Babel   : 	at cae.b(SourceFile:1146)
03-24 15:04:13.395  3212  3736 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 15:04:13.395  3212  3736 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:04:13.395  3212  3736 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:04:13.395  3212  3736 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 15:04:13.624  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:13.734  1389  3740 I VacuumService: Vacuum at: now=1458828253734 tag=VacuumService
,03-24 15:04:13.753  3443  3739 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:04:13.905  1389  3741 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 15:04:13.918  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:13.922  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:04:13.922  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:13.922  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:04:13.922  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:13.929  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:13.955  1389  1427 I art     : Explicit concurrent mark sweep GC freed 26075(1548KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 905us total 22.600ms
,03-24 15:04:13.965  3443  3739 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:04:13.966  3443  3739 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:04:14.397  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:14.539  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:14.709  1389  3741 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 15:04:14.709  1389  3741 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:14.709  1389  3741 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:14.709  1389  3741 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:14.714  1389  3741 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:14.769  1389  3741 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:04:14.769  1389  3741 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:04:14.769  1389  3741 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:04:14.902  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:15.034  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:15.130  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:15.253  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:15.312  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 15:04:15.312  3335  3394 I jxcore-log: 
,03-24 15:04:15.374  1389  3741 W Uploader:  no longer exists, so no auth token.
,03-24 15:04:15.513  3542  3608 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 15:04:15.541  1389  3741 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 15:04:15.541  1389  3741 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:15.541  1389  3741 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:15.541  1389  3741 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:15.549  1389  3741 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:04:15.596  1389  3741 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-24 15:04:15.596  1389  3741 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268),
03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:04:15.596  1389  3741 E Uploader: 	,at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:04:15.596  1389  3741 E Uploader: ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
,03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:04:15.596  1389  3741 E Uploader: ,	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,03-24 15:04:15.596  1389  3741 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:04:15.706  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 15:04:15.706  3335  3394 I jxcore-log: 
,03-24 15:04:15.719  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 15:04:15.719  3335  3394 I jxcore-log: 
,03-24 15:04:15.724  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 15:04:15.724  3335  3394 I jxcore-log: 
,03-24 15:04:15.767  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 15:04:15.767  3335  3394 I jxcore-log: 
,03-24 15:04:15.782  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 15:04:15.782  3335  3394 I jxcore-log: 
,03-24 15:04:15.786  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 15:04:15.786  3335  3394 I jxcore-log: 
,03-24 15:04:15.837  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:16.002  1389  3741 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
03-24 15:04:16.003  1389  3741 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:16.003  1389  3741 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:16.003  1389  3741 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:16.013  1389  3741 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:16.074  1389  3741 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:04:16.074  1389  3741 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:04:16.074  1389  3741 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:04:16.466  1389  3741 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 15:04:16.466  1389  3741 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:16.467  1389  3741 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:16.467  1389  3741 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:16.471  1389  3741 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:16.495  1389  3741 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:04:16.495  1389  3741 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:04:16.495  1389  3741 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:04:16.615  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:16.782  1389  3741 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 15:04:16.783  1389  3741 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,03-24 15:04:16.783  1389  3741 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:16.783  1389  3741 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-24 15:04:16.795  1389  3741 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:04:16.870  1389  3741 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 15:04:16.870  1389  3741 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 15:04:16.870  1389  3741 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 15:04:17.014  1389  3741 W Uploader: No account for auth token provided
,03-24 15:04:17.856  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 15:04:17.856  3335  3394 I jxcore-log: 
,03-24 15:04:17.873  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-24 15:04:17.873  3335  3394 I jxcore-log: 
,03-24 15:04:17.882  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
03-24 15:04:17.882  3335  3394 I jxcore-log: 
,03-24 15:04:18.007  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 15:04:18.007  3335  3394 I jxcore-log: 
,03-24 15:04:18.061  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 15:04:18.061  3335  3394 I jxcore-log: 
,03-24 15:04:18.204  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 15:04:18.204  3335  3394 I jxcore-log: 
,03-24 15:04:18.209  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
03-24 15:04:18.209  3335  3394 I jxcore-log: 
,03-24 15:04:18.215  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 15:04:18.215  3335  3394 I jxcore-log: ,
,03-24 15:04:18.235  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 15:04:18.235  3335  3394 I jxcore-log: 
,03-24 15:04:18.254  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 15:04:18.254  3335  3394 I jxcore-log: 
,03-24 15:04:18.357  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 15:04:18.357  3335  3394 I jxcore-log: 
,03-24 15:04:18.363  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 15:04:18.363  3335  3394 I jxcore-log: 
,03-24 15:04:18.388  3335  3394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 15:04:18.388  3335  3394 I jxcore-log: 
,03-24 15:04:18.405   823  1442 I ActivityManager: Killing 2776:com.android.vending/u0a19 (adj 15): empty #17
,03-24 15:04:19.419  3335  3394 I jxcore-log: TAP version 13
03-24 15:04:19.419  3335  3394 I jxcore-log: 
,03-24 15:04:19.423  3335  3394 I jxcore-log: # setup
03-24 15:04:19.423  3335  3394 I jxcore-log: 
,03-24 15:04:19.584  3335  3394 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 15:04:19.584  3335  3394 I jxcore-log: 
,03-24 15:04:19.714  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:19.714  3335  3394 I jxcore-log: 
,03-24 15:04:19.720  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 56121
03-24 15:04:19.720  3335  3394 I jxcore-log: 
,03-24 15:04:19.727  3335  3394 I jxcore-log: ok 1 Should throw
03-24 15:04:19.727  3335  3394 I jxcore-log: 
,03-24 15:04:19.730  3335  3394 I jxcore-log: # teardown
03-24 15:04:19.730  3335  3394 I jxcore-log: 
,03-24 15:04:19.874  3335  3394 I jxcore-log: # setup
,03-24 15:04:19.874  3335  3394 I jxcore-log: 
,03-24 15:04:19.972  3335  3394 I jxcore-log: # 2. emits incomingConnectionState
03-24 15:04:19.972  3335  3394 I jxcore-log: 
,03-24 15:04:20.098  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:04:20.098  3335  3394 I jxcore-log: 
,03-24 15:04:20.104  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 37597
,03-24 15:04:20.104  3335  3394 I jxcore-log: 
,03-24 15:04:20.115  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:04:20.115  3335  3394 I jxcore-log: 
,03-24 15:04:20.120  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 15:04:20.120  3335  3394 I jxcore-log: 
,03-24 15:04:20.131  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:04:20.131  3335  3394 I jxcore-log: 
,03-24 15:04:20.138  3335  3394 I jxcore-log: ok 2 initial connection state should be CONNECTED
,03-24 15:04:20.138  3335  3394 I jxcore-log: 
,03-24 15:04:20.156  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
,03-24 15:04:20.156  3335  3394 I jxcore-log: 
03-24 15:04:20.157  3335  3394 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 15:04:20.157  3335  3394 I jxcore-log: 
,03-24 15:04:20.166  3335  3394 I jxcore-log: # teardown
03-24 15:04:20.166  3335  3394 I jxcore-log: ,
,03-24 15:04:20.252  3335  3394 I jxcore-log: # setup
,03-24 15:04:20.252  3335  3394 I jxcore-log: 
,03-24 15:04:20.374  3335  3394 I jxcore-log: # 3. emits routerPortConnectionFailed
,03-24 15:04:20.374  3335  3394 I jxcore-log: 
,03-24 15:04:20.506  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:04:20.506  3335  3394 I jxcore-log: 
,03-24 15:04:20.510  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 33081
,03-24 15:04:20.510  3335  3394 I jxcore-log: 
,03-24 15:04:20.518  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:04:20.518  3335  3394 I jxcore-log: 
,03-24 15:04:20.520  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 15:04:20.520  3335  3394 I jxcore-log: 
,03-24 15:04:20.523  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:04:20.523  3335  3394 I jxcore-log: 
,03-24 15:04:20.550  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 15:04:20.550  3335  3394 I jxcore-log: 
,03-24 15:04:20.555  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 15:04:20.555  3335  3394 I jxcore-log: 
,03-24 15:04:20.565  3335  3394 I jxcore-log: DEBUG createNativeListener: 
,03-24 15:04:20.565  3335  3394 I jxcore-log: 
,03-24 15:04:20.569  3335  3394 I jxcore-log: ok 4 tried to connect to right port
,03-24 15:04:20.569  3335  3394 I jxcore-log: 
,03-24 15:04:20.571  3335  3394 I jxcore-log: ok 5 failed due to refused connection,
03-24 15:04:20.571  3335  3394 I jxcore-log: 
,03-24 15:04:20.572  3335  3394 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 15:04:20.572  3335  3394 I jxcore-log: 
,03-24 15:04:20.585  3335  3394 I jxcore-log: # teardown
,03-24 15:04:20.585  3335  3394 I jxcore-log: 
,03-24 15:04:20.590  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:20.590  3335  3394 I jxcore-log: 
,03-24 15:04:20.661   823  1246 I ActivityManager: Start proc 3755:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-24 15:04:20.714  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:20.714  3335  3394 I jxcore-log: 
,03-24 15:04:20.720  3335  3394 I jxcore-log: # setup
03-24 15:04:20.720  3335  3394 I jxcore-log: 
,03-24 15:04:20.722  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:20.722  3335  3394 I jxcore-log: 
,03-24 15:04:20.827  3335  3394 I jxcore-log: # 4. native server connections all up
03-24 15:04:20.827  3335  3394 I jxcore-log: 
,03-24 15:04:20.860  3755  3755 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-24 15:04:20.928  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:20.928  3335  3394 I jxcore-log: 
,03-24 15:04:20.933  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 58027
03-24 15:04:20.933  3335  3394 I jxcore-log: 
,03-24 15:04:20.935  3755  3755 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-24 15:04:20.943  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:20.943  3335  3394 I jxcore-log: 
,03-24 15:04:20.945  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:20.945  3335  3394 I jxcore-log: 
,03-24 15:04:20.948  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:20.948  3335  3394 I jxcore-log: 
,03-24 15:04:20.974  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 15:04:20.974  3335  3394 I jxcore-log: 
,03-24 15:04:20.977  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:20.977  3335  3394 I jxcore-log: 
,03-24 15:04:20.979  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:20.979  3335  3394 I jxcore-log: 
,03-24 15:04:20.982  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:20.982  3335  3394 I jxcore-log: 
,03-24 15:04:21.003  3335  3394 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 15:04:21.003  3335  3394 I jxcore-log: 
03-24 15:04:21.003  3335  3394 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 15:04:21.003  3335  3394 I jxcore-log: 
03-24 15:04:21.005  3335  3394 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 15:04:21.005  3335  3394 I jxcore-log: 
03-24 15:04:21.006  3335  3394 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 15:04:21.006  3335  3394 I jxcore-log: 
,03-24 15:04:21.009  3335  3394 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 15:04:21.009  3335  3394 I jxcore-log: 
,03-24 15:04:21.017  3335  3394 I jxcore-log: # teardown
03-24 15:04:21.017  3335  3394 I jxcore-log: 
,03-24 15:04:21.028   823  1297 I ActivityManager: Start proc 3791:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-24 15:04:21.042  3755  3755 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-24 15:04:21.043  3755  3755 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-24 15:04:21.043   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 328us total 15.184ms
,03-24 15:04:21.058   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 431us total 14.119ms
,03-24 15:04:21.068  3791  3791 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 15:04:21.068  3791  3791 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:04:21.071   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 235us total 12.806ms
,03-24 15:04:21.079   823  1246 I ActivityManager: Killing 2960:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 15:04:21.083  3755  3770 D Finsky  : [379] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 15:04:21.093  3791  3791 I MultiDex: VM with version 2.1.0 has multidex support
03-24 15:04:21.093  3791  3791 I MultiDex: install
03-24 15:04:21.093  3791  3791 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 15:04:21.154  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:21.154  3335  3394 I jxcore-log: 
,03-24 15:04:21.156  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:21.156  3335  3394 I jxcore-log: 
,03-24 15:04:21.159  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:21.159  3335  3394 I jxcore-log: 
,03-24 15:04:21.163  3335  3394 I jxcore-log: # setup
03-24 15:04:21.163  3335  3394 I jxcore-log: 
,03-24 15:04:21.164  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:21.164  3335  3394 I jxcore-log: 
,03-24 15:04:21.189  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:21.196  3755  3755 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-24 15:04:21.197  3755  3755 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-24 15:04:21.208  3791  3791 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-24 15:04:21.220  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:04:21.220  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:21.221  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:21.221  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:21.224  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:21.251  3755  3755 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-24 15:04:21.268  3755  3755 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-24 15:04:21.275  3755  3770 D Finsky  : [379] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 15:04:21.288  3791  3791 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 15:04:21.300  1389  2124 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-24 15:04:21.304  1389  1389 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 15:04:21.308  1785  1785 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-24 15:04:21.343  3335  3394 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 15:04:21.343  3335  3394 I jxcore-log: 
,03-24 15:04:21.354   823  1442 I ActivityManager: Start proc 3821:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-24 15:04:21.374  1785  3838 D LocationInitializer: Restart initialization of location
,03-24 15:04:21.392  3821  3821 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 15:04:21.392  3821  3821 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 15:04:21.437  3821  3821 I MultiDex: VM with version 2.1.0 has multidex support
03-24 15:04:21.438  3821  3821 I MultiDex: install
03-24 15:04:21.438  3821  3821 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 15:04:21.451  3821  3821 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-24 15:04:21.482  3821  3821 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 15:04:21.488  1389  2542 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-24 15:04:21.489  1389  1389 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 15:04:21.494  1785  1785 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: Install did not work
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-24 15:04:21.494  3821  3843 W NativeLibraryUtils: 	... 4 more
03-24 15:04:21.497  3821  3821 D WearableService: callingUid 10011, callindPid: 3821
,03-24 15:04:21.549   823  1297 I art     : Explicit concurrent mark sweep GC freed 21969(995KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 810us total 46.294ms
,03-24 15:04:21.559  1785  3844 D LocationInitializer: Restart initialization of location
,03-24 15:04:21.565  1812  2117 E MDM     : [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-24 15:04:21.568  1812  2117 E MDM     : [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-24 15:04:21.583  3755  3755 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-24 15:04:21.952  3755  3755 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-24 15:04:21.994  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:22.083  1389  1423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:04:22.083  1389  1423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:04:22.083  1389  1423 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:22.083  1389  1423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:22.090  1389  1423 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:22.119  3755  3755 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 15:04:22.128  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:22.161  1389  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:04:22.161  1389  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:22.161  1389  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:22.161  1389  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:22.168  1389  1928 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:22.644  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:22.724  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 15:04:22.724  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:22.725  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:22.725  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:22.741  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:22.784  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 15:04:22.788  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 15:04:22.790  3755  3755 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 15:04:22.851  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 15:04:22.851  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:22.852  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:22.852  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:22.864  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:04:22.901  3755  3755 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 15:04:23.138  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:23.189  1389  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-24 15:04:23.189  1389  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:23.189  1389  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 15:04:23.189  1389  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:23.199  1389  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:23.262  1389  1734 I art     : Explicit concurrent mark sweep GC freed 51157(2MB) AllocSpace objects, 10(1029KB) LOS objects, 37% free, 27MB/43MB, paused 1.457ms total 56.125ms
,03-24 15:04:23.291  3755  3755 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-24 15:04:23.293  3755  3755 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-24 15:04:23.301  3755  3755 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-24 15:04:23.304  3755  3755 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,03-24 15:04:23.317  1812  1853 D DeviceConnectionService: client connected with version: 7571000
,03-24 15:04:26.585   823   838 I ActivityManager: Killing 1511:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-24 15:04:26.696   823  1035 D WifiService: Client connection lost with reason: 4
,03-24 15:04:27.015   823  1311 I ActivityManager: Killing 3484:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-24 15:04:27.055  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:27.055  3335  3394 I jxcore-log: 
,03-24 15:04:27.060  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 39787,
03-24 15:04:27.060  3335  3394 I jxcore-log: 
,03-24 15:04:27.066  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:27.066  3335  3394 I jxcore-log: ,
,03-24 15:04:27.067  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:27.067  3335  3394 I jxcore-log: 
,03-24 15:04:27.069  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:27.069  3335  3394 I jxcore-log: 
,03-24 15:04:27.083  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 15:04:27.083  3335  3394 I jxcore-log: 
,03-24 15:04:27.086  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:27.086  3335  3394 I jxcore-log: 
,03-24 15:04:27.100  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:27.100  3335  3394 I jxcore-log: 
,03-24 15:04:27.112  3335  3394 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 15:04:27.112  3335  3394 I jxcore-log: 
,03-24 15:04:27.113  3335  3394 I jxcore-log: ok 13 incoming remains open
03-24 15:04:27.113  3335  3394 I jxcore-log: 
,03-24 15:04:27.118  3335  3394 I jxcore-log: # teardown
03-24 15:04:27.118  3335  3394 I jxcore-log: 
,03-24 15:04:28.603  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:04:35.059  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:35.059  3335  3394 I jxcore-log: 
,03-24 15:04:35.064  3335  3394 I jxcore-log: # setup,
03-24 15:04:35.064  3335  3394 I jxcore-log: 
03-24 15:04:35.065  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:35.065  3335  3394 I jxcore-log: 
,03-24 15:04:38.160  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:38.233  1389  1423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 15:04:38.234  1389  1423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:38.234  1389  1423 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:38.235  1389  1423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:38.245  1389  1423 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:38.295  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 15:04:38.297  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 15:04:38.298  3755  3755 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-24 15:04:38.417  3335  3394 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 15:04:38.417  3335  3394 I jxcore-log: 
,03-24 15:04:40.022  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:40.022  3335  3394 I jxcore-log: 
,03-24 15:04:40.032  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 58881
,03-24 15:04:40.032  3335  3394 I jxcore-log: 
,03-24 15:04:40.039  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket,
,03-24 15:04:40.039  3335  3394 I jxcore-log: 
,03-24 15:04:40.040  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-24 15:04:40.040  3335  3394 I jxcore-log: 
03-24 15:04:40.041  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:40.041  3335  3394 I jxcore-log: ,
,03-24 15:04:40.052  3335  3394 I jxcore-log: ok 14 we should not have gotten an error,
03-24 15:04:40.052  3335  3394 I jxcore-log: 
,03-24 15:04:40.058  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:40.058  3335  3394 I jxcore-log: ,
,03-24 15:04:40.062  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:40.062  3335  3394 I jxcore-log: 
,03-24 15:04:40.073  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:40.073  3335  3394 I jxcore-log: 
,03-24 15:04:40.075  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:40.075  3335  3394 I jxcore-log: 
,03-24 15:04:40.083  3335  3394 I jxcore-log: ok 15 socket shouldn't close until after incoming,
03-24 15:04:40.083  3335  3394 I jxcore-log: 
03-24 15:04:40.084  3335  3394 I jxcore-log: ok 16 incoming is cleaned up
03-24 15:04:40.084  3335  3394 I jxcore-log: 
03-24 15:04:40.089  3335  3394 I jxcore-log: # teardown
03-24 15:04:40.089  3335  3394 I jxcore-log: 
,03-24 15:04:40.952  3335  3394 I jxcore-log: # setup
03-24 15:04:40.952  3335  3394 I jxcore-log: 
,03-24 15:04:41.109  3335  3394 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 15:04:41.109  3335  3394 I jxcore-log: 
,03-24 15:04:41.278  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:41.278  3335  3394 I jxcore-log: 
,03-24 15:04:41.287  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 40610
03-24 15:04:41.287  3335  3394 I jxcore-log: 
,03-24 15:04:41.294  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:41.294  3335  3394 I jxcore-log: 
,03-24 15:04:41.296  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:41.296  3335  3394 I jxcore-log: 
,03-24 15:04:41.299  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:41.299  3335  3394 I jxcore-log: 
,03-24 15:04:41.311  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:41.311  3335  3394 I jxcore-log: ,
,03-24 15:04:41.314  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:41.314  3335  3394 I jxcore-log: 
,03-24 15:04:41.328  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:41.328  3335  3394 I jxcore-log: 
,03-24 15:04:41.338  3335  3394 I jxcore-log: ok 17 stream was closed
03-24 15:04:41.338  3335  3394 I jxcore-log: 
,03-24 15:04:41.338  3335  3394 I jxcore-log: ok 18 incoming should survive
03-24 15:04:41.338  3335  3394 I jxcore-log: 
03-24 15:04:41.339  3335  3394 I jxcore-log: ok 19 mux should have no streams,
03-24 15:04:41.339  3335  3394 I jxcore-log: 
,03-24 15:04:41.346  3335  3394 I jxcore-log: # teardown
03-24 15:04:41.346  3335  3394 I jxcore-log: 
,03-24 15:04:41.609  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:41.609  3335  3394 I jxcore-log: 
,03-24 15:04:41.614  3335  3394 I jxcore-log: # setup
03-24 15:04:41.614  3335  3394 I jxcore-log: 
03-24 15:04:41.615  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:41.615  3335  3394 I jxcore-log: 
,03-24 15:04:41.753  3335  3394 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 15:04:41.753  3335  3394 I jxcore-log: 
,03-24 15:04:41.883  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:41.883  3335  3394 I jxcore-log: 
,03-24 15:04:41.891  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 42768
03-24 15:04:41.891  3335  3394 I jxcore-log: 
,03-24 15:04:41.896  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:41.896  3335  3394 I jxcore-log: 
,03-24 15:04:41.898  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:41.898  3335  3394 I jxcore-log: 
,03-24 15:04:41.899  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:41.899  3335  3394 I jxcore-log: 
,03-24 15:04:41.909  3335  3394 I jxcore-log: ok 20 we should not have gotten an error
03-24 15:04:41.909  3335  3394 I jxcore-log: 
,03-24 15:04:41.916  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:41.916  3335  3394 I jxcore-log: 
,03-24 15:04:41.919  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:41.919  3335  3394 I jxcore-log: 
,03-24 15:04:41.930  3335  3394 I jxcore-log: ok 21 Buffers are identical
03-24 15:04:41.930  3335  3394 I jxcore-log: 
,03-24 15:04:41.932  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 15:04:41.932  3335  3394 I jxcore-log: 
,03-24 15:04:41.937  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:41.937  3335  3394 I jxcore-log: 
,03-24 15:04:41.940  3335  3394 I jxcore-log: ok 22 native server is nulled out
03-24 15:04:41.940  3335  3394 I jxcore-log: 
,03-24 15:04:41.941  3335  3394 I jxcore-log: ok 23 native server should be closed
03-24 15:04:41.941  3335  3394 I jxcore-log: 
03-24 15:04:41.941  3335  3394 I jxcore-log: ok 24 incoming has been removed
03-24 15:04:41.941  3335  3394 I jxcore-log: 
03-24 15:04:41.941  3335  3394 I jxcore-log: ok 25 Incoming should be done
03-24 15:04:41.941  3335  3394 I jxcore-log: 
,03-24 15:04:41.942  3335  3394 I jxcore-log: ok 26 The mux object should be closed
03-24 15:04:41.942  3335  3394 I jxcore-log: 
03-24 15:04:41.942  3335  3394 I jxcore-log: ok 27 The mux stream should be closed
03-24 15:04:41.942  3335  3394 I jxcore-log: 
,03-24 15:04:41.943  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:41.943  3335  3394 I jxcore-log: 
,03-24 15:04:41.959  3335  3394 I jxcore-log: # teardown
03-24 15:04:41.959  3335  3394 I jxcore-log: 
,03-24 15:04:42.119  3335  3394 I jxcore-log: # setup
03-24 15:04:42.119  3335  3394 I jxcore-log: 
,03-24 15:04:42.230  3335  3394 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
,03-24 15:04:42.230  3335  3394 I jxcore-log: 
,03-24 15:04:42.449  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 15:04:42.449  3335  3394 I jxcore-log: 
,03-24 15:04:42.452  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 59135,
03-24 15:04:42.452  3335  3394 I jxcore-log: 
,03-24 15:04:42.472  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 15:04:42.472  3335  3394 I jxcore-log: 
,03-24 15:04:42.473  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.473  3335  3394 I jxcore-log: 
,03-24 15:04:42.475  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux,
03-24 15:04:42.475  3335  3394 I jxcore-log: 
03-24 15:04:42.478  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:04:42.478  3335  3394 I jxcore-log: 
,03-24 15:04:42.483  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-24 15:04:42.483  3335  3394 I jxcore-log: 
,03-24 15:04:42.485  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.485  3335  3394 I jxcore-log: 
,03-24 15:04:42.489  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.489  3335  3394 I jxcore-log: 
,03-24 15:04:42.489  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.489  3335  3394 I jxcore-log: ,
,03-24 15:04:42.490  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux,
,03-24 15:04:42.490  3335  3394 I jxcore-log: 
,03-24 15:04:42.493  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:04:42.493  3335  3394 I jxcore-log: 
03-24 15:04:42.494  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.494  3335  3394 I jxcore-log: 
03-24 15:04:42.495  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.495  3335  3394 I jxcore-log: 
03-24 15:04:42.497  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.497  3335  3394 I jxcore-log: 
03-24 15:04:42.498  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.498  3335  3394 I jxcore-log: 
03-24 15:04:42.499  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.499  3335  3394 I jxcore-log: 
,03-24 15:04:42.501  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.501  3335  3394 I jxcore-log: 
03-24 15:04:42.502  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.502  3335  3394 I jxcore-log: 
03-24 15:04:42.503  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.503  3335  3394 I jxcore-log: 
,03-24 15:04:42.505  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.505  3335  3394 I jxcore-log: 
03-24 15:04:42.505  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.505  3335  3394 I jxcore-log: 
03-24 15:04:42.506  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.506  3335  3394 I jxcore-log: 
03-24 15:04:42.508  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.508  3335  3394 I jxcore-log: 
03-24 15:04:42.509  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.509  3335  3394 I jxcore-log: 
,03-24 15:04:42.510  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.510  3335  3394 I jxcore-log: 
03-24 15:04:42.511  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.511  3335  3394 I jxcore-log: 
03-24 15:04:42.512  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.512  3335  3394 I jxcore-log: 
03-24 15:04:42.513  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:04:42.513  3335  3394 I jxcore-log: 
03-24 15:04:42.514  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:42.514  3335  3394 I jxcore-log: 
03-24 15:04:42.515  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:42.515  3335  3394 I jxcore-log: 
,03-24 15:04:42.516  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:42.516  3335  3394 I jxcore-log: 
,03-24 15:04:42.601  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.601  3335  3394 I jxcore-log: 
,03-24 15:04:42.604  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.604  3335  3394 I jxcore-log: 
,03-24 15:04:42.606  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.606  3335  3394 I jxcore-log: 
,03-24 15:04:42.608  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.608  3335  3394 I jxcore-log: 
,03-24 15:04:42.609  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.609  3335  3394 I jxcore-log: 
,03-24 15:04:42.610  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.610  3335  3394 I jxcore-log: 
,03-24 15:04:42.612  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.612  3335  3394 I jxcore-log: 
,03-24 15:04:42.614  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.614  3335  3394 I jxcore-log: 
,03-24 15:04:42.617  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.617  3335  3394 I jxcore-log: 
,03-24 15:04:42.618  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.618  3335  3394 I jxcore-log: 
,03-24 15:04:42.620  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.620  3335  3394 I jxcore-log: 
,03-24 15:04:42.621  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.621  3335  3394 I jxcore-log: 
,03-24 15:04:42.622  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.622  3335  3394 I jxcore-log: 
,03-24 15:04:42.624  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.624  3335  3394 I jxcore-log: 
,03-24 15:04:42.625  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.625  3335  3394 I jxcore-log: 
,03-24 15:04:42.626  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.626  3335  3394 I jxcore-log: 
,03-24 15:04:42.629  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.629  3335  3394 I jxcore-log: 
,03-24 15:04:42.630  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.630  3335  3394 I jxcore-log: 
,03-24 15:04:42.631  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.631  3335  3394 I jxcore-log: 
,03-24 15:04:42.633  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.633  3335  3394 I jxcore-log: 
,03-24 15:04:42.636  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.636  3335  3394 I jxcore-log: 
,03-24 15:04:42.638  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.638  3335  3394 I jxcore-log: 
,03-24 15:04:42.640  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.640  3335  3394 I jxcore-log: 
,03-24 15:04:42.641  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.641  3335  3394 I jxcore-log: 
,03-24 15:04:42.643  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.643  3335  3394 I jxcore-log: 
,03-24 15:04:42.644  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.644  3335  3394 I jxcore-log: 
,03-24 15:04:42.646  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.646  3335  3394 I jxcore-log: 
,03-24 15:04:42.647  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.647  3335  3394 I jxcore-log: 
,03-24 15:04:42.648  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.648  3335  3394 I jxcore-log: 
,03-24 15:04:42.649  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.649  3335  3394 I jxcore-log: 
,03-24 15:04:42.650  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.650  3335  3394 I jxcore-log: 
,03-24 15:04:42.652  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.652  3335  3394 I jxcore-log: 
,03-24 15:04:42.654  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.654  3335  3394 I jxcore-log: 
,03-24 15:04:42.655  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.655  3335  3394 I jxcore-log: 
,03-24 15:04:42.656  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.656  3335  3394 I jxcore-log: 
,03-24 15:04:42.658  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.658  3335  3394 I jxcore-log: 
,03-24 15:04:42.659  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.659  3335  3394 I jxcore-log: 
03-24 15:04:42.660  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.660  3335  3394 I jxcore-log: 
,03-24 15:04:42.661  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.661  3335  3394 I jxcore-log: 
03-24 15:04:42.663  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.663  3335  3394 I jxcore-log: 
,03-24 15:04:42.664  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.664  3335  3394 I jxcore-log: 
,03-24 15:04:42.666  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.666  3335  3394 I jxcore-log: 
,03-24 15:04:42.667  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.667  3335  3394 I jxcore-log: 
,03-24 15:04:42.668  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.668  3335  3394 I jxcore-log: 
,03-24 15:04:42.669  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.669  3335  3394 I jxcore-log: 
,03-24 15:04:42.671  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.671  3335  3394 I jxcore-log: 
,03-24 15:04:42.672  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 15:04:42.672  3335  3394 I jxcore-log: 
,03-24 15:04:42.673  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.673  3335  3394 I jxcore-log: 
,03-24 15:04:42.681  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.681  3335  3394 I jxcore-log: 
,03-24 15:04:42.683  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.683  3335  3394 I jxcore-log: 
,03-24 15:04:42.684  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.684  3335  3394 I jxcore-log: 
,03-24 15:04:42.685  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.685  3335  3394 I jxcore-log: 
,03-24 15:04:42.686  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.686  3335  3394 I jxcore-log: 
,03-24 15:04:42.687  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.687  3335  3394 I jxcore-log: 
,03-24 15:04:42.688  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.688  3335  3394 I jxcore-log: 
,03-24 15:04:42.689  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.689  3335  3394 I jxcore-log: 
,03-24 15:04:42.691  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.691  3335  3394 I jxcore-log: 
,03-24 15:04:42.693  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.693  3335  3394 I jxcore-log: 
,03-24 15:04:42.694  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.694  3335  3394 I jxcore-log: 
,03-24 15:04:42.696  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.696  3335  3394 I jxcore-log: 
,03-24 15:04:42.697  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.697  3335  3394 I jxcore-log: 
03-24 15:04:42.698  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.698  3335  3394 I jxcore-log: 
,03-24 15:04:42.699  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.699  3335  3394 I jxcore-log: 
,03-24 15:04:42.700  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.700  3335  3394 I jxcore-log: 
,03-24 15:04:42.702  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.702  3335  3394 I jxcore-log: 
,03-24 15:04:42.703  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.703  3335  3394 I jxcore-log: 
03-24 15:04:42.704  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.704  3335  3394 I jxcore-log: 
,03-24 15:04:42.705  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.705  3335  3394 I jxcore-log: 
,03-24 15:04:42.706  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.706  3335  3394 I jxcore-log: 
,03-24 15:04:42.707  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.707  3335  3394 I jxcore-log: 
,03-24 15:04:42.708  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.708  3335  3394 I jxcore-log: 
,03-24 15:04:42.710  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.710  3335  3394 I jxcore-log: 
03-24 15:04:42.711  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.711  3335  3394 I jxcore-log: 
,03-24 15:04:42.713  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.713  3335  3394 I jxcore-log: 
,03-24 15:04:42.714  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.714  3335  3394 I jxcore-log: 
03-24 15:04:42.715  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.715  3335  3394 I jxcore-log: 
,03-24 15:04:42.716  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:42.716  3335  3394 I jxcore-log: 
,03-24 15:04:42.718  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 15:04:42.718  3335  3394 I jxcore-log: 
03-24 15:04:42.719  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 15:04:42.719  3335  3394 I jxcore-log: 
,03-24 15:04:42.720  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:42.720  3335  3394 I jxcore-log: 
,03-24 15:04:42.794  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.794  3335  3394 I jxcore-log: 
,03-24 15:04:42.795  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.795  3335  3394 I jxcore-log: 
,03-24 15:04:42.796  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.796  3335  3394 I jxcore-log: 
,03-24 15:04:42.798  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.798  3335  3394 I jxcore-log: 
,03-24 15:04:42.799  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.799  3335  3394 I jxcore-log: 
,03-24 15:04:42.801  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.801  3335  3394 I jxcore-log: 
,03-24 15:04:42.801  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.801  3335  3394 I jxcore-log: 
,03-24 15:04:42.802  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.802  3335  3394 I jxcore-log: 
,03-24 15:04:42.803  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.803  3335  3394 I jxcore-log: 
,03-24 15:04:42.804  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.804  3335  3394 I jxcore-log: 
,03-24 15:04:42.806  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.806  3335  3394 I jxcore-log: 
,03-24 15:04:42.807  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.807  3335  3394 I jxcore-log: 
,03-24 15:04:42.808  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.808  3335  3394 I jxcore-log: 
,03-24 15:04:42.809  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.809  3335  3394 I jxcore-log: 
,03-24 15:04:42.811  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.811  3335  3394 I jxcore-log: 
,03-24 15:04:42.812  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.812  3335  3394 I jxcore-log: 
,03-24 15:04:42.813  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.813  3335  3394 I jxcore-log: 
03-24 15:04:42.813  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.813  3335  3394 I jxcore-log: 
,03-24 15:04:42.814  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.814  3335  3394 I jxcore-log: 
03-24 15:04:42.815  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.815  3335  3394 I jxcore-log: 
03-24 15:04:42.816  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.816  3335  3394 I jxcore-log: 
03-24 15:04:42.817  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.817  3335  3394 I jxcore-log: 
03-24 15:04:42.818  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.818  3335  3394 I jxcore-log: 
,03-24 15:04:42.819  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.819  3335  3394 I jxcore-log: 
03-24 15:04:42.820  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.820  3335  3394 I jxcore-log: 
03-24 15:04:42.821  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.821  3335  3394 I jxcore-log: 
03-24 15:04:42.822  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.822  3335  3394 I jxcore-log: 
03-24 15:04:42.823  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.823  3335  3394 I jxcore-log: 
,03-24 15:04:42.823  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.823  3335  3394 I jxcore-log: 
03-24 15:04:42.824  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.824  3335  3394 I jxcore-log: 
03-24 15:04:42.825  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.825  3335  3394 I jxcore-log: 
03-24 15:04:42.826  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.826  3335  3394 I jxcore-log: 
03-24 15:04:42.827  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.827  3335  3394 I jxcore-log: 
03-24 15:04:42.828  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.828  3335  3394 I jxcore-log: 
03-24 15:04:42.829  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.829  3335  3394 I jxcore-log: 
03-24 15:04:42.830  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.830  3335  3394 I jxcore-log: 
03-24 15:04:42.831  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.831  3335  3394 I jxcore-log: 
03-24 15:04:42.832  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.832  3335  3394 I jxcore-log: 
03-24 15:04:42.833  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.833  3335  3394 I jxcore-log: 
03-24 15:04:42.834  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.834  3335  3394 I jxcore-log: 
03-24 15:04:42.835  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.835  3335  3394 I jxcore-log: 
03-24 15:04:42.835  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.835  3335  3394 I jxcore-log: 
03-24 15:04:42.836  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.836  3335  3394 I jxcore-log: 
03-24 15:04:42.837  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.837  3335  3394 I jxcore-log: 
03-24 15:04:42.838  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.838  3335  3394 I jxcore-log: 
03-24 15:04:42.838  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.838  3335  3394 I jxcore-log: 
03-24 15:04:42.839  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.839  3335  3394 I jxcore-log: 
03-24 15:04:42.840  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.840  3335  3394 I jxcore-log: 
03-24 15:04:42.841  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:42.841  3335  3394 I jxcore-log: 
03-24 15:04:42.842  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:42.842  3335  3394 I jxcore-log: 
03-24 15:04:42.845  3335  3394 I jxcore-log: ok 28 native server is nulled out
03-24 15:04:42.845  3335  3394 I jxcore-log: 
03-24 15:04:42.845  3335  3394 I jxcore-log: ok 29 native server should be closed
03-24 15:04:42.845  3335  3394 I jxcore-log: 
03-24 15:04:42.845  3335  3394 I jxcore-log: ok 30 incoming has been removed
03-24 15:04:42.845  3335  3394 I jxcore-log: 
03-24 15:04:42.846  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.846  3335  3394 I jxcore-log: 
03-24 15:04:42.847  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.847  3335  3394 I jxcore-log: 
03-24 15:04:42.848  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.848  3335  3394 I jxcore-log: 
03-24 15:04:42.848  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.848  3335  3394 I jxcore-log: 
03-24 15:04:42.849  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.849  3335  3394 I jxcore-log: 
03-24 15:04:42.849  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.849  3335  3394 I jxcore-log: 
03-24 15:04:42.849  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.849  3335  3394 I jxcore-log: 
03-24 15:04:42.850  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.850  3335  3394 I jxcore-log: 
03-24 15:04:42.850  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.850  3335  3394 I jxcore-log: 
03-24 15:04:42.850  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:42.850  3335  3394 I jxcore-log: 
,03-24 15:04:42.952  3335  3394 I jxcore-log: # teardown
,03-24 15:04:42.952  3335  3394 I jxcore-log: 
,03-24 15:04:43.537  3335  3394 I jxcore-log: # setup
03-24 15:04:43.537  3335  3394 I jxcore-log: 
,03-24 15:04:43.673  3335  3394 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 15:04:43.673  3335  3394 I jxcore-log: 
,03-24 15:04:44.340  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:44.340  3335  3394 I jxcore-log: 
,03-24 15:04:44.349  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 33027
03-24 15:04:44.349  3335  3394 I jxcore-log: 
,03-24 15:04:44.355  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:44.355  3335  3394 I jxcore-log: 
,03-24 15:04:44.356  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-24 15:04:44.356  3335  3394 I jxcore-log: 
03-24 15:04:44.357  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux,
03-24 15:04:44.357  3335  3394 I jxcore-log: 
,03-24 15:04:44.365  3335  3394 I jxcore-log: ok 31 we should not have gotten an error,
03-24 15:04:44.365  3335  3394 I jxcore-log: 
,03-24 15:04:44.369  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:44.369  3335  3394 I jxcore-log: 
,03-24 15:04:44.371  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-24 15:04:44.371  3335  3394 I jxcore-log: 
,03-24 15:04:44.379  3335  3394 I jxcore-log: ok 32 Buffers are identical
03-24 15:04:44.379  3335  3394 I jxcore-log: 
,03-24 15:04:44.380  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:44.380  3335  3394 I jxcore-log: 
,03-24 15:04:44.381  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:04:44.381  3335  3394 I jxcore-log: 
,03-24 15:04:44.392  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:44.392  3335  3394 I jxcore-log: 
,03-24 15:04:44.393  3335  3394 I jxcore-log: ok 33 server should be fine
03-24 15:04:44.393  3335  3394 I jxcore-log: 
,03-24 15:04:44.394  3335  3394 I jxcore-log: ok 34 server should be open
03-24 15:04:44.394  3335  3394 I jxcore-log: 
,03-24 15:04:44.394  3335  3394 I jxcore-log: ok 35 incoming has been removed
03-24 15:04:44.394  3335  3394 I jxcore-log: 
,03-24 15:04:44.395  3335  3394 I jxcore-log: ok 36 The mux object should be closed
03-24 15:04:44.395  3335  3394 I jxcore-log: 
03-24 15:04:44.395  3335  3394 I jxcore-log: ok 37 The mux stream should be closed
03-24 15:04:44.395  3335  3394 I jxcore-log: 
,03-24 15:04:44.402  3335  3394 I jxcore-log: # teardown
03-24 15:04:44.402  3335  3394 I jxcore-log: 
,03-24 15:04:44.702  3335  3394 I jxcore-log: # setup
03-24 15:04:44.702  3335  3394 I jxcore-log: 
,03-24 15:04:45.270  3335  3394 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-24 15:04:45.270  3335  3394 I jxcore-log: 
,03-24 15:04:45.449  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:45.449  3335  3394 I jxcore-log: 
,03-24 15:04:45.454  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 56277
03-24 15:04:45.454  3335  3394 I jxcore-log: 
,03-24 15:04:45.460  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:04:45.460  3335  3394 I jxcore-log: 
,03-24 15:04:45.461  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:04:45.461  3335  3394 I jxcore-log: 
,03-24 15:04:45.463  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:04:45.463  3335  3394 I jxcore-log: 
,03-24 15:04:45.469  3335  3394 I jxcore-log: ok 38 we should not have gotten an error
03-24 15:04:45.469  3335  3394 I jxcore-log: 
,03-24 15:04:45.473  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:04:45.473  3335  3394 I jxcore-log: 
,03-24 15:04:45.475  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:04:45.475  3335  3394 I jxcore-log: 
,03-24 15:04:45.482  3335  3394 I jxcore-log: ok 39 Buffers are identical
03-24 15:04:45.482  3335  3394 I jxcore-log: 
,03-24 15:04:45.486  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 15:04:45.486  3335  3394 I jxcore-log: 
,03-24 15:04:45.488  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 15:04:45.488  3335  3394 I jxcore-log: 
,03-24 15:04:45.489  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 15:04:45.489  3335  3394 I jxcore-log: 
,03-24 15:04:45.494  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:04:45.494  3335  3394 I jxcore-log: 
,03-24 15:04:45.495  3335  3394 I jxcore-log: ok 40 server should be fine
03-24 15:04:45.495  3335  3394 I jxcore-log: 
,03-24 15:04:45.495  3335  3394 I jxcore-log: ok 41 server should be open
03-24 15:04:45.495  3335  3394 I jxcore-log: 
03-24 15:04:45.496  3335  3394 I jxcore-log: ok 42 incoming has been removed
03-24 15:04:45.496  3335  3394 I jxcore-log: 
03-24 15:04:45.496  3335  3394 I jxcore-log: ok 43 The mux object should be closed
03-24 15:04:45.496  3335  3394 I jxcore-log: 
,03-24 15:04:45.496  3335  3394 I jxcore-log: ok 44 The mux stream should be closed
03-24 15:04:45.496  3335  3394 I jxcore-log: 
,03-24 15:04:45.505  3335  3394 I jxcore-log: # teardown
03-24 15:04:45.505  3335  3394 I jxcore-log: 
,03-24 15:04:45.630  3335  3394 I jxcore-log: # setup
,03-24 15:04:45.630  3335  3394 I jxcore-log: 
,03-24 15:04:45.763  3335  3394 I jxcore-log: # 12. closeAll can close even when connections open
03-24 15:04:45.763  3335  3394 I jxcore-log: 
,03-24 15:04:45.917  3335  3394 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 15:04:45.917  3335  3394 I jxcore-log: 
,03-24 15:04:45.922  3335  3394 I jxcore-log: # teardown
03-24 15:04:45.922  3335  3394 I jxcore-log: 
,03-24 15:04:46.017  3335  3394 I jxcore-log: # setup
03-24 15:04:46.017  3335  3394 I jxcore-log: 
,03-24 15:04:46.160  3335  3394 I jxcore-log: # 13. closeAll with promise
03-24 15:04:46.160  3335  3394 I jxcore-log: 
,03-24 15:04:46.320  3335  3394 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 15:04:46.320  3335  3394 I jxcore-log: 
,03-24 15:04:46.325  3335  3394 I jxcore-log: # teardown
03-24 15:04:46.325  3335  3394 I jxcore-log: 
,03-24 15:04:46.515  3335  3394 I jxcore-log: # setup
03-24 15:04:46.515  3335  3394 I jxcore-log: ,
,03-24 15:04:46.659  3335  3394 I jxcore-log: # 14. multiplex can send data
03-24 15:04:46.659  3335  3394 I jxcore-log: 
,03-24 15:04:46.849  3335  3394 I jxcore-log: ok 47 String should be length:200
03-24 15:04:46.849  3335  3394 I jxcore-log: ,
,03-24 15:04:46.858  3335  3394 I jxcore-log: # teardown
03-24 15:04:46.858  3335  3394 I jxcore-log: 
,03-24 15:04:46.963  3335  3394 I jxcore-log: # setup
03-24 15:04:46.963  3335  3394 I jxcore-log: 
,03-24 15:04:47.144  3335  3394 I jxcore-log: # 15. enqueue and run in order
03-24 15:04:47.144  3335  3394 I jxcore-log: 
,03-24 15:04:47.377  3335  3394 I jxcore-log: ok 48 firstPromise setTimeout
03-24 15:04:47.377  3335  3394 I jxcore-log: 
,03-24 15:04:47.379  3335  3394 I jxcore-log: ok 49 firstPromise result
03-24 15:04:47.379  3335  3394 I jxcore-log: 
,03-24 15:04:47.381  3335  3394 I jxcore-log: ok 50 firstPromise testValue
03-24 15:04:47.381  3335  3394 I jxcore-log: 
,03-24 15:04:47.485  3335  3394 I jxcore-log: ok 51 secondPromise setTimeout
03-24 15:04:47.485  3335  3394 I jxcore-log: 
,03-24 15:04:47.489  3335  3394 I jxcore-log: ok 52 secondPromise result
03-24 15:04:47.489  3335  3394 I jxcore-log: 
,03-24 15:04:47.490  3335  3394 I jxcore-log: ok 53 secondPromise testValue
03-24 15:04:47.490  3335  3394 I jxcore-log: 
,03-24 15:04:47.493  3335  3394 I jxcore-log: ok 54 thirdPromise in promise
03-24 15:04:47.493  3335  3394 I jxcore-log: 
,03-24 15:04:47.496  3335  3394 I jxcore-log: ok 55 thirdPromise result
03-24 15:04:47.496  3335  3394 I jxcore-log: 
,03-24 15:04:47.498  3335  3394 I jxcore-log: ok 56 thirdPromise testValue
03-24 15:04:47.498  3335  3394 I jxcore-log: 
,03-24 15:04:47.511  3335  3394 I jxcore-log: # teardown
03-24 15:04:47.511  3335  3394 I jxcore-log: 
,03-24 15:04:47.821  3335  3394 I jxcore-log: # setup
03-24 15:04:47.821  3335  3394 I jxcore-log: 
,03-24 15:04:48.091  3335  3394 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 15:04:48.091  3335  3394 I jxcore-log: 
,03-24 15:04:48.260  3335  3394 I jxcore-log: ok 57 thirdPromise - first to run
03-24 15:04:48.260  3335  3394 I jxcore-log: 
,03-24 15:04:48.263  3335  3394 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 15:04:48.263  3335  3394 I jxcore-log: 
,03-24 15:04:48.268  3335  3394 I jxcore-log: ok 59 secondPromise - second to run
03-24 15:04:48.268  3335  3394 I jxcore-log: 
,03-24 15:04:48.270  3335  3394 I jxcore-log: ok 60 secondPromise - in catch
03-24 15:04:48.270  3335  3394 I jxcore-log: 
,03-24 15:04:48.270  3335  3394 I jxcore-log: ok 61 firstPromise - third to run
03-24 15:04:48.270  3335  3394 I jxcore-log: 
03-24 15:04:48.271  3335  3394 I jxcore-log: ok 62 firstPromise - in then
03-24 15:04:48.271  3335  3394 I jxcore-log: 
,03-24 15:04:48.271  3335  3394 I jxcore-log: ok 63 testing promises
03-24 15:04:48.271  3335  3394 I jxcore-log: 
03-24 15:04:48.274  3335  3394 I jxcore-log: # teardown
03-24 15:04:48.274  3335  3394 I jxcore-log: 
,03-24 15:04:48.419  3335  3394 I jxcore-log: # setup
03-24 15:04:48.419  3335  3394 I jxcore-log: 
,03-24 15:04:48.521  3335  3394 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 15:04:48.521  3335  3394 I jxcore-log: 
,03-24 15:04:48.712  3335  3394 I jxcore-log: ok 64 fourth
03-24 15:04:48.712  3335  3394 I jxcore-log: 
,03-24 15:04:48.713  3335  3394 I jxcore-log: ok 65 fourth
03-24 15:04:48.713  3335  3394 I jxcore-log: 
03-24 15:04:48.714  3335  3394 I jxcore-log: ok 66 second
03-24 15:04:48.714  3335  3394 I jxcore-log: 
,03-24 15:04:48.715  3335  3394 I jxcore-log: ok 67 secondPromise - in then
03-24 15:04:48.715  3335  3394 I jxcore-log: 
,03-24 15:04:48.819  3335  3394 I jxcore-log: ok 68 first
03-24 15:04:48.819  3335  3394 I jxcore-log: 
,03-24 15:04:48.821  3335  3394 I jxcore-log: ok 69 firstPromise - in catch
03-24 15:04:48.821  3335  3394 I jxcore-log: 
03-24 15:04:48.823  3335  3394 I jxcore-log: ok 70 third
03-24 15:04:48.823  3335  3394 I jxcore-log: 
,03-24 15:04:48.826  3335  3394 I jxcore-log: ok 71 thirdPromise - in then
03-24 15:04:48.826  3335  3394 I jxcore-log: 
03-24 15:04:48.828  3335  3394 I jxcore-log: ok 72 testingPromises
03-24 15:04:48.828  3335  3394 I jxcore-log: 
,03-24 15:04:48.849  3335  3394 I jxcore-log: # teardown
03-24 15:04:48.849  3335  3394 I jxcore-log: 
,03-24 15:04:48.982  3335  3394 I jxcore-log: # setup
03-24 15:04:48.982  3335  3394 I jxcore-log: 
,03-24 15:04:49.091  3335  3394 I jxcore-log: # 18. queues handled independently
03-24 15:04:49.091  3335  3394 I jxcore-log: 
,03-24 15:04:49.234  3335  3394 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 15:04:49.234  3335  3394 I jxcore-log: 
,03-24 15:04:49.248  3335  3394 I jxcore-log: # teardown
03-24 15:04:49.248  3335  3394 I jxcore-log: 
,03-24 15:04:49.383  3335  3394 I jxcore-log: # setup
03-24 15:04:49.383  3335  3394 I jxcore-log: 
,03-24 15:04:49.522  3335  3394 I jxcore-log: # 19. basic
03-24 15:04:49.522  3335  3394 I jxcore-log: 
,03-24 15:04:49.622  3335  3394 I jxcore-log: ok 74 sane
03-24 15:04:49.622  3335  3394 I jxcore-log: 
,03-24 15:04:49.629  3335  3394 I jxcore-log: # teardown
03-24 15:04:49.629  3335  3394 I jxcore-log: 
,03-24 15:04:49.773  3335  3394 I jxcore-log: # setup
03-24 15:04:49.773  3335  3394 I jxcore-log: 
,03-24 15:04:50.041  3335  3394 I jxcore-log: # 20. another
03-24 15:04:50.041  3335  3394 I jxcore-log: 
,03-24 15:04:50.200  3335  3394 I jxcore-log: ok 75 sane
03-24 15:04:50.200  3335  3394 I jxcore-log: 
,03-24 15:04:50.206  3335  3394 I jxcore-log: # teardown
03-24 15:04:50.206  3335  3394 I jxcore-log: 
,03-24 15:04:50.374  3335  3394 I jxcore-log: # setup
03-24 15:04:50.374  3335  3394 I jxcore-log: 
,03-24 15:04:50.485  3335  3394 I jxcore-log: # 21. can pass data in setup
,03-24 15:04:50.485  3335  3394 I jxcore-log: 
,03-24 15:04:50.579  3335  3394 I jxcore-log: ok 76 test participant has uuid
03-24 15:04:50.579  3335  3394 I jxcore-log: 
,03-24 15:04:50.581  3335  3394 I jxcore-log: ok 77 participant data matches
03-24 15:04:50.581  3335  3394 I jxcore-log: 
,03-24 15:04:50.582  3335  3394 I jxcore-log: ok 78 test participant has uuid
03-24 15:04:50.582  3335  3394 I jxcore-log: 
,03-24 15:04:50.584  3335  3394 I jxcore-log: ok 79 participant data matches
03-24 15:04:50.584  3335  3394 I jxcore-log: 
,03-24 15:04:50.585  3335  3394 I jxcore-log: ok 80 test participant has uuid
03-24 15:04:50.585  3335  3394 I jxcore-log: 
,03-24 15:04:50.586  3335  3394 I jxcore-log: ok 81 participant data matches
03-24 15:04:50.586  3335  3394 I jxcore-log: 
03-24 15:04:50.590  3335  3394 I jxcore-log: # teardown
03-24 15:04:50.590  3335  3394 I jxcore-log: 
,03-24 15:04:50.696  3335  3394 I jxcore-log: # setup
03-24 15:04:50.696  3335  3394 I jxcore-log: 
,03-24 15:04:50.849  3335  3394 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 15:04:50.849  3335  3394 I jxcore-log: 
,03-24 15:04:51.000  3335  3394 I jxcore-log: ok 82 specific error should be returned
03-24 15:04:51.000  3335  3394 I jxcore-log: 
,03-24 15:04:51.006  3335  3394 I jxcore-log: # teardown
03-24 15:04:51.006  3335  3394 I jxcore-log: 
,03-24 15:04:51.137  3335  3394 I jxcore-log: ok 83 error should be null
03-24 15:04:51.137  3335  3394 I jxcore-log: 
,03-24 15:04:51.139  3335  3394 I jxcore-log: ok 84 error should be null
03-24 15:04:51.139  3335  3394 I jxcore-log: 
,03-24 15:04:51.143  3335  3394 I jxcore-log: # setup
03-24 15:04:51.143  3335  3394 I jxcore-log: 
,03-24 15:04:51.267  3335  3394 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:04:51.267  3335  3394 I jxcore-log: 
,03-24 15:04:51.458  3335  3394 I jxcore-log: ok 85 specific error should be returned
03-24 15:04:51.458  3335  3394 I jxcore-log: 
,03-24 15:04:51.464  3335  3394 I jxcore-log: # teardown
03-24 15:04:51.464  3335  3394 I jxcore-log: 
,03-24 15:04:51.620  3335  3394 I jxcore-log: ok 86 error should be null
03-24 15:04:51.620  3335  3394 I jxcore-log: 
,03-24 15:04:51.621  3335  3394 I jxcore-log: ok 87 error should be null
03-24 15:04:51.621  3335  3394 I jxcore-log: 
,03-24 15:04:51.627  3335  3394 I jxcore-log: # setup
03-24 15:04:51.627  3335  3394 I jxcore-log: 
,03-24 15:04:51.768  3335  3394 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-24 15:04:51.768  3335  3394 I jxcore-log: 
,03-24 15:04:52.012  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:52.012  3335  3394 I jxcore-log: 
,03-24 15:04:52.014  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 37308
03-24 15:04:52.014  3335  3394 I jxcore-log: 
03-24 15:04:52.016  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:04:52.017  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:52.017  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:52.022  3335  3394 I jxcore-log: ok 88 error should be null
03-24 15:04:52.022  3335  3394 I jxcore-log: 
,03-24 15:04:52.023  3335  3394 I jxcore-log: ok 89 error should be null
03-24 15:04:52.023  3335  3394 I jxcore-log: 
03-24 15:04:52.024  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:04:52.024  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:04:52.024  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:52.026  3335  3394 I jxcore-log: ok 90 error should be null
03-24 15:04:52.026  3335  3394 I jxcore-log: 
03-24 15:04:52.026  3335  3394 I jxcore-log: ok 91 error should be null
03-24 15:04:52.026  3335  3394 I jxcore-log: 
,03-24 15:04:52.030  3335  3394 I jxcore-log: # teardown
03-24 15:04:52.030  3335  3394 I jxcore-log: 
,03-24 15:04:52.190  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:04:52.191  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:52.191  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:04:52.193  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:04:52.193  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:52.193  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:04:52.198  3335  3394 I jxcore-log: ok 92 error should be null
03-24 15:04:52.198  3335  3394 I jxcore-log: 
03-24 15:04:52.198  3335  3394 I jxcore-log: ok 93 error should be null
03-24 15:04:52.198  3335  3394 I jxcore-log: 
,03-24 15:04:52.205  3335  3394 I jxcore-log: # setup
03-24 15:04:52.205  3335  3394 I jxcore-log: 
,03-24 15:04:52.294  3335  3394 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 15:04:52.294  3335  3394 I jxcore-log: 
,03-24 15:04:52.498  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:04:52.498  3335  3394 I jxcore-log: 
03-24 15:04:52.500  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 56630
03-24 15:04:52.500  3335  3394 I jxcore-log: 
,03-24 15:04:52.510  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 15:04:52.510  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:04:52.510  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:52.511  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 15:04:52.511  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:04:52.511  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:04:52.522  3335  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:04:52.522   823  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:52.531  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:04:52.537  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-24 15:04:52.537  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:04:52.537  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:04:52.538  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:04:52.547  2162  2179 D BtGatt.GattService: registerClient() - UUID=d864c7a2-bdb2-4f1f-868d-f59ee56e6682
,03-24 15:04:52.548  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=d864c7a2-bdb2-4f1f-868d-f59ee56e6682, clientIf=5
,03-24 15:04:52.550  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:04:52.553  2162  2229 D BtGatt.GattService: start scan with filters
,03-24 15:04:52.556  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:04:52.556  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:04:52.557  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:04:52.557  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 15:04:52.558  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:04:52.558  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:52.559  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:04:52.559  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:52.560   823  1467 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:52.562  2162  2238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c71666d
,03-24 15:04:52.568  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:04:52.568  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:04:52.570  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:04:52.570  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:04:52.570  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:04:52.570  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:04:52.576  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:04:52.576  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:52.579  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:04:52.579  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:52.579  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:04:52.579  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:04:52.581  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:04:52.581  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:52.583  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:04:52.583  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:52.585  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:52.585  3335  3394 I jxcore-log: 
03-24 15:04:52.586  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:52.586  3335  3394 I jxcore-log: 
,03-24 15:04:52.589  3335  3394 I jxcore-log: ok 94 error should be null
03-24 15:04:52.589  3335  3394 I jxcore-log: 
,03-24 15:04:52.589  3335  3394 I jxcore-log: ok 95 error should be null
03-24 15:04:52.589  3335  3394 I jxcore-log: 
,03-24 15:04:52.594  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 15:04:52.594  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:04:52.594  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:52.594  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:04:52.594  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:04:52.596  3335  3394 I jxcore-log: ok 96 error should be null
03-24 15:04:52.596  3335  3394 I jxcore-log: 
,03-24 15:04:52.597  3335  3394 I jxcore-log: ok 97 error should be null
03-24 15:04:52.597  3335  3394 I jxcore-log: 
,03-24 15:04:52.603  3335  3394 I jxcore-log: # teardown
03-24 15:04:52.603  3335  3394 I jxcore-log: 
,03-24 15:04:52.838  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:04:52.839  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:04:52.839  3335  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:04:52.839  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:04:52.839  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 15:04:52.839  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:04:52.839  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:04:52.839  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:04:52.840  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-24 15:04:52.842  2162  2229 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:04:52.844  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:04:52.844  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 15:04:52.844  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:04:52.844  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:04:52.845  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:04:52.845  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:04:52.845  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:04:52.847  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:04:52.847  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:52.848  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:04:52.849  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:04:52.849  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:04:52.849  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:04:52.850  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:04:52.850  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:52.850  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:04:52.851  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:04:52.851  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:04:52.851  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:04:52.851  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:04:52.851  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:04:52.854  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:04:52.854  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:52.864  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:04:52.865   823  1442 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 15:04:52.858  3335  3394 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 15:04:52.858  3335  3394 I jxcore-log: 
,03-24 15:04:52.879  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:04:52.881  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:04:52.881  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:52.887  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:04:52.888  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:52.888  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:04:52.888  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:04:52.893  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:04:52.893  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:52.893  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:52.895  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 15:04:52.895  3335  3394 I jxcore-log: 
,03-24 15:04:52.899  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:52.899  3335  3394 I jxcore-log: 
,03-24 15:04:52.909  3335  3394 I jxcore-log: ok 98 error should be null
03-24 15:04:52.909  3335  3394 I jxcore-log: 
,03-24 15:04:52.912  3335  3394 I jxcore-log: ok 99 error should be null,
03-24 15:04:52.912  3335  3394 I jxcore-log: 
,03-24 15:04:52.918  3335  3394 I jxcore-log: # setup
03-24 15:04:52.918  3335  3394 I jxcore-log: 
,03-24 15:04:52.921  3443  3858 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:04:52.960  1389  1423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:04:52.961  1389  1423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:52.961  1389  1423 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:52.961  1389  1423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:52.966  1389  1423 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:52.976  3443  3858 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:04:52.977  3443  3858 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:04:53.068  3335  3394 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 15:04:53.068  3335  3394 I jxcore-log: 
,03-24 15:04:53.246  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:53.246  3335  3394 I jxcore-log: 
,03-24 15:04:53.248  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 39169
03-24 15:04:53.248  3335  3394 I jxcore-log: 
,03-24 15:04:53.263  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 39169, start advertisements: true
03-24 15:04:53.263  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:04:53.263  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:04:53.263  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:04:53.269  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:04:53.269  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:04:53.269  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:04:53.269  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:04:53.276  2162  2180 D BtGatt.GattService: registerClient() - UUID=f39f7221-0986-4da8-916e-0b60aca61275
,03-24 15:04:53.277  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=f39f7221-0986-4da8-916e-0b60aca61275, clientIf=5
,03-24 15:04:53.277  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:04:53.278  2162  2179 D BtGatt.GattService: start scan with filters
,03-24 15:04:53.280  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:04:53.280  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:04:53.280  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:04:53.281  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:04:53.281  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:04:53.281  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:53.281  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:04:53.281  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:04:53.282  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:04:53.284  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:04:53.284  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:53.285  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:04:53.286  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:04:53.286  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:53.287  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:04:53.287  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:04:53.289  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:04:53.290  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:04:53.290  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:04:53.291  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:04:53.291  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:53.293  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:04:53.294  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:53.300  2162  2229 D BtGatt.GattService: registerClient() - UUID=2ad41fe4-8a64-46d3-a0b2-66aca8b72f21
,03-24 15:04:53.300  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=2ad41fe4-8a64-46d3-a0b2-66aca8b72f21, clientIf=6
03-24 15:04:53.300  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:04:53.305  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:04:53.311  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:04:53.315  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:04:53.318  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:04:53.320  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:04:53.321  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:04:53.321   823  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:53.325  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:04:53.325  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:04:53.325  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:04:53.325  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:04:53.327  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 15:04:53.328  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:04:53.328  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:04:53.328  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:04:53.329  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:04:53.329  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 15:04:53.329  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-24 15:04:53.329  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:04:53.329  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:04:53.330  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 15:04:53.330  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:04:53.330  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:04:53.330  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:04:53.330  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:04:53.330  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:04:53.330  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-24 15:04:53.331  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:04:53.333   823  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:04:53.336  3335  3859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:04:53.341  3335  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-24 15:04:53.351  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:53.351  3335  3394 I jxcore-log: 
03-24 15:04:53.354  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:53.354  3335  3394 I jxcore-log: 
,03-24 15:04:53.356  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:04:53.356  3335  3394 I jxcore-log: 
03-24 15:04:53.359  3335  3394 I jxcore-log: ok 100 error should be null
03-24 15:04:53.359  3335  3394 I jxcore-log: 
,03-24 15:04:53.360  3335  3394 I jxcore-log: ok 101 error should be null,
,03-24 15:04:53.360  3335  3394 I jxcore-log: 
03-24 15:04:53.369  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 39169, start advertisements: true
03-24 15:04:53.369  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:04:53.369  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:04:53.369  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:53.369  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:04:53.380  3335  3394 I jxcore-log: ok 102 error should be null
03-24 15:04:53.380  3335  3394 I jxcore-log: 
,03-24 15:04:53.381  3335  3394 I jxcore-log: ok 103 error should be null
03-24 15:04:53.381  3335  3394 I jxcore-log: 
,03-24 15:04:53.399  3335  3394 I jxcore-log: # teardown
03-24 15:04:53.399  3335  3394 I jxcore-log: 
,03-24 15:04:53.638  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:04:53.639  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:04:53.639  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:04:53.639  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:04:53.639  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:04:53.640  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:04:53.641  3335  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:04:53.641  3335  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 15:04:53.641  3335  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 15:04:53.642  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:04:53.643  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:04:53.644  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:04:53.644  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:04:53.644  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:04:53.644  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:04:53.645  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:04:53.645  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:04:53.645  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:04:53.648  2162  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:04:53.651  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:04:53.656  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:04:53.656  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:04:53.656  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:53.656  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:04:53.656  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:04:53.656  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:04:53.657  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:04:53.657  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:04:53.657  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:04:53.657  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:04:53.659  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:04:53.659  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:53.660  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:04:53.662  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:04:53.663  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:04:53.663  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-24 15:04:53.663  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:53.663  2162  2226 D BtGatt.GattService: current time is 212366052573
,03-24 15:04:53.664  2162  2226 D BtGatt.GattService: Batch record : [-85, -105, -48, -60, 32, 103, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 5, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 15:04:53.666  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:04:53.668  2162  2226 D BtGatt.GattService: ScanRecord : []
03-24 15:04:53.669  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:04:53.671  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:04:53.671  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:04:53.673  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:04:53.674  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:04:53.674  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:04:53.674  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:04:53.675  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:04:53.675  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:04:53.676  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:04:53.676  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:04:53.676  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:04:53.678  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:04:53.678  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:04:53.682  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:53.682  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:04:53.683  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:53.683  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:04:53.683  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:04:53.689  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:04:53.689  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:53.689  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:53.693  3335  3394 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 15:04:53.693  3335  3394 I jxcore-log: 
03-24 15:04:53.693  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:04:53.694   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:53.705  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 15:04:53.707  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:04:53.707  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:53.711  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:04:53.711  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:04:53.711  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:04:53.713  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:04:53.713  3335  3394 I jxcore-log: ,
03-24 15:04:53.714  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:53.714  3335  3394 I jxcore-log: 
03-24 15:04:53.715  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:53.715  3335  3394 I jxcore-log: 
,03-24 15:04:53.720  3335  3394 I jxcore-log: ok 104 error should be null
,03-24 15:04:53.720  3335  3394 I jxcore-log: 
,03-24 15:04:53.720  3335  3394 I jxcore-log: ok 105 error should be null
03-24 15:04:53.720  3335  3394 I jxcore-log: 
,03-24 15:04:53.727  3335  3394 I jxcore-log: # setup
03-24 15:04:53.727  3335  3394 I jxcore-log: 
,03-24 15:04:53.864  3335  3394 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
03-24 15:04:53.864  3335  3394 I jxcore-log: 
,03-24 15:04:53.974  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:53.974  3335  3394 I jxcore-log: 
,03-24 15:04:53.976  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 47161
03-24 15:04:53.976  3335  3394 I jxcore-log: 
,03-24 15:04:53.980  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:04:53.980  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:53.980  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:53.983  3335  3394 I jxcore-log: ok 106 error should be null
03-24 15:04:53.983  3335  3394 I jxcore-log: 
03-24 15:04:53.983  3335  3394 I jxcore-log: ok 107 error should be null
03-24 15:04:53.983  3335  3394 I jxcore-log: 
03-24 15:04:53.985  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:04:53.985  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:53.985  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:53.987  3335  3394 I jxcore-log: ok 108 error should be null
03-24 15:04:53.987  3335  3394 I jxcore-log: 
,03-24 15:04:53.988  3335  3394 I jxcore-log: ok 109 error should be null
03-24 15:04:53.988  3335  3394 I jxcore-log: 
,03-24 15:04:53.993  3335  3394 I jxcore-log: # teardown
03-24 15:04:53.993  3335  3394 I jxcore-log: 
,03-24 15:04:54.143  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:04:54.143  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:54.143  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:54.149  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:04:54.150  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:54.150  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:54.159  3335  3394 I jxcore-log: ok 110 error should be null
,03-24 15:04:54.159  3335  3394 I jxcore-log: 
03-24 15:04:54.160  3335  3394 I jxcore-log: ok 111 error should be null
03-24 15:04:54.160  3335  3394 I jxcore-log: 
,03-24 15:04:54.165  3335  3394 I jxcore-log: # setup
,03-24 15:04:54.165  3335  3394 I jxcore-log: 
,03-24 15:04:54.262  3335  3394 I jxcore-log: # 28. #start should fail if called twice in a row
03-24 15:04:54.262  3335  3394 I jxcore-log: 
,03-24 15:04:54.435  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:54.435  3335  3394 I jxcore-log: 
,03-24 15:04:54.438  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 45755
03-24 15:04:54.438  3335  3394 I jxcore-log: 
,03-24 15:04:54.442  3335  3394 I jxcore-log: ok 112 first call should succeed
03-24 15:04:54.442  3335  3394 I jxcore-log: 
,03-24 15:04:54.442  3335  3394 I jxcore-log: ok 113 first call should succeed
03-24 15:04:54.442  3335  3394 I jxcore-log: 
,03-24 15:04:54.447  3335  3394 I jxcore-log: ok 114 specific error should be returned
,03-24 15:04:54.447  3335  3394 I jxcore-log: 
,03-24 15:04:54.451  3335  3394 I jxcore-log: # teardown
,03-24 15:04:54.451  3335  3394 I jxcore-log: 
,03-24 15:04:54.570  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:04:54.570  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:54.570  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:54.572  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:04:54.572  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:04:54.572  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:54.583  3335  3394 I jxcore-log: ok 115 error should be null,
03-24 15:04:54.583  3335  3394 I jxcore-log: 
,03-24 15:04:54.584  3335  3394 I jxcore-log: ok 116 error should be null,
03-24 15:04:54.584  3335  3394 I jxcore-log: 
,03-24 15:04:54.595  3335  3394 I jxcore-log: # setup,
03-24 15:04:54.595  3335  3394 I jxcore-log: 
,03-24 15:04:54.682  3335  3394 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 15:04:54.682  3335  3394 I jxcore-log: 
,03-24 15:04:54.888  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:04:54.888  3335  3394 I jxcore-log: 
03-24 15:04:54.890  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 34380
03-24 15:04:54.890  3335  3394 I jxcore-log: 
,03-24 15:04:54.901  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 39169, start advertisements: false
,03-24 15:04:54.901  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:04:54.901  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:54.901  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
,03-24 15:04:54.905  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:04:54.905  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:04:54.905  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:04:54.911  2162  2180 D BtGatt.GattService: registerClient() - UUID=0f7c02b9-5512-4989-9e41-b8d3381645e2
,03-24 15:04:54.911  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=0f7c02b9-5512-4989-9e41-b8d3381645e2, clientIf=5
03-24 15:04:54.912  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 15:04:54.912  2162  2229 D BtGatt.GattService: start scan with filters,
,03-24 15:04:54.914  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:04:54.914  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:04:54.914  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:04:54.915  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:04:54.915  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-24 15:04:54.915  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:54.915  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:04:54.915  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:04:54.916   823  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:54.923  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 15:04:54.923  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:54.923  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:04:54.924  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:04:54.924  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 15:04:54.924  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:54.925  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:04:54.925  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:04:54.925  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 15:04:54.925  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:04:54.925  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:04:54.926  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:04:54.928  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:04:54.928  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:54.930  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:04:54.930  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:54.935  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:54.935  3335  3394 I jxcore-log: 
,03-24 15:04:54.938  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 15:04:54.938  3335  3394 I jxcore-log: 
,03-24 15:04:54.962  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 34380, start advertisements: true,
03-24 15:04:54.962  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:04:54.962  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:04:54.962  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:04:54.966  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 15:04:54.966  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 15:04:54.966  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:04:54.966  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 15:04:54.966  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:04:54.967  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:04:54.967  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:04:54.967  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:04:54.972  2162  2229 D BtGatt.GattService: registerClient() - UUID=be211479-2dc4-4eff-8f7c-66ad167a5fb5
,03-24 15:04:54.972  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=be211479-2dc4-4eff-8f7c-66ad167a5fb5, clientIf=6
,03-24 15:04:54.973  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:04:54.974  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:04:54.978  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:04:54.982  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:04:54.985  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:04:54.985  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:04:54.985  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:04:54.985  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:04:54.985  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:04:54.986  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:04:54.986   823  1310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:04:54.986  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:04:54.986  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 15:04:54.989  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:04:54.989  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:04:54.989  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:04:54.989  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:04:54.989  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:04:54.990  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:04:54.990  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:04:54.990  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:04:54.990  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:04:54.990  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:04:54.990  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:04:54.991  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:04:54.991  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:04:54.992   823  1401 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:04:54.993  3335  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:04:54.996  3335  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:04:55.000  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:04:55.000  3335  3394 I jxcore-log: 
,03-24 15:04:55.005  3335  3394 I jxcore-log: ok 117 called only once
03-24 15:04:55.005  3335  3394 I jxcore-log: 
,03-24 15:04:55.006  3335  3394 I jxcore-log: ok 118 discovery state matches
03-24 15:04:55.006  3335  3394 I jxcore-log: 
03-24 15:04:55.006  3335  3394 I jxcore-log: ok 119 advertising state matches
03-24 15:04:55.006  3335  3394 I jxcore-log: 
,03-24 15:04:55.015  3335  3394 I jxcore-log: # teardown
03-24 15:04:55.015  3335  3394 I jxcore-log: 
,03-24 15:04:55.477  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:04:55.478  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:04:55.478  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:04:55.478  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:04:55.478  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:04:55.479  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:04:55.479  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:04:55.479  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:04:55.479  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:04:55.479  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:04:55.479  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:04:55.479  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:04:55.479  3335  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:04:55.479  3335  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:04:55.479  3335  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:04:55.481  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:04:55.484  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:04:55.484  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:55.484  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:04:55.486  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:04:55.488  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 15:04:55.488  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:55.488  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:04:55.488  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:04:55.489  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:04:55.489  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:04:55.489  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:04:55.489  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 15:04:55.490  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:04:55.490  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:04:55.492  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 15:04:55.492  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:55.493  2162  2226 D BtGatt.GattService: current time is 214195470801,
03-24 15:04:55.493  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:04:55.493  2162  2226 D BtGatt.GattService: Batch record : [39, 120, 61, 21, 90, 112, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:04:55.493  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:04:55.494  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:04:55.494  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:04:55.498  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:04:55.498  2162  2226 D BtGatt.GattService: Client app is not null!,
03-24 15:04:55.499  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:04:55.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:04:55.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:04:55.500  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 15:04:55.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:04:55.500  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:04:55.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:04:55.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:04:55.501  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:04:55.502  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 15:04:55.502  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:04:55.502  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:55.502  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-24 15:04:55.502  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:04:55.510  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 15:04:55.510  3335  3394 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,03-24 15:04:55.510  3335  3394 I jxcore-log: 
03-24 15:04:55.510   823  1465 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:55.511  3335  3394 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 15:04:55.511  3335  3394 I jxcore-log: 
,03-24 15:04:55.515  3335  3394 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 15:04:55.515  3335  3394 I jxcore-log: 
,03-24 15:04:55.520  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 15:04:55.521  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 15:04:55.521  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:55.525  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 15:04:55.525  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:04:55.526  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:04:55.526  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:55.526  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:04:55.526  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:04:55.527  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:04:55.527  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:04:55.528  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:04:55.528  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:55.528  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:55.529  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 15:04:55.529  3335  3394 I jxcore-log: 
03-24 15:04:55.530  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:55.530  3335  3394 I jxcore-log: 
03-24 15:04:55.531  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:55.531  3335  3394 I jxcore-log: 
,03-24 15:04:55.534  3335  3394 I jxcore-log: ok 120 error should be null
03-24 15:04:55.534  3335  3394 I jxcore-log: 
03-24 15:04:55.535  3335  3394 I jxcore-log: ok 121 error should be null
03-24 15:04:55.535  3335  3394 I jxcore-log: 
,03-24 15:04:55.540  3335  3394 I jxcore-log: # setup
03-24 15:04:55.540  3335  3394 I jxcore-log: ,
,03-24 15:04:55.899  3335  3394 I jxcore-log: # 30. does not send duplicate availability changes
03-24 15:04:55.899  3335  3394 I jxcore-log: 
,03-24 15:04:56.062  3335  3394 I jxcore-log: ok 122 should be called once
03-24 15:04:56.062  3335  3394 I jxcore-log: 
,03-24 15:04:56.063  3335  3394 I jxcore-log: ok 123 should not have been called more than once
03-24 15:04:56.063  3335  3394 I jxcore-log: 
,03-24 15:04:56.067  3335  3394 I jxcore-log: # teardown
03-24 15:04:56.067  3335  3394 I jxcore-log: 
,03-24 15:04:56.176  3335  3394 I jxcore-log: ok 124 error should be null
03-24 15:04:56.176  3335  3394 I jxcore-log: 
,03-24 15:04:56.178  3335  3394 I jxcore-log: ok 125 error should be null
03-24 15:04:56.178  3335  3394 I jxcore-log: 
,03-24 15:04:56.181  3335  3394 I jxcore-log: # setup
03-24 15:04:56.181  3335  3394 I jxcore-log: 
,03-24 15:04:56.259  3335  3394 I jxcore-log: # 31. can get the network status
03-24 15:04:56.259  3335  3394 I jxcore-log: 
,03-24 15:04:56.380  3335  3394 I jxcore-log: ok 126 network status should have certain non-empty properties
03-24 15:04:56.380  3335  3394 I jxcore-log: 
,03-24 15:04:56.382  3335  3394 I jxcore-log: # teardown
03-24 15:04:56.382  3335  3394 I jxcore-log: 
,03-24 15:04:56.499  3335  3394 I jxcore-log: ok 127 error should be null
03-24 15:04:56.499  3335  3394 I jxcore-log: 
,03-24 15:04:56.500  3335  3394 I jxcore-log: ok 128 error should be null
03-24 15:04:56.500  3335  3394 I jxcore-log: 
03-24 15:04:56.502  3335  3394 I jxcore-log: # setup
03-24 15:04:56.502  3335  3394 I jxcore-log: 
,03-24 15:04:56.789  3335  3394 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 15:04:56.789  3335  3394 I jxcore-log: 
,03-24 15:04:56.930  3335  3394 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 15:04:56.930  3335  3394 I jxcore-log: 
,03-24 15:04:56.954  3335  3394 I jxcore-log: ok 129 host address should match,
03-24 15:04:56.954  3335  3394 I jxcore-log: 
03-24 15:04:56.955  3335  3394 I jxcore-log: ok 130 port should match
03-24 15:04:56.955  3335  3394 I jxcore-log: 
,03-24 15:04:57.809  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:04:58.568  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:58.663  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 15:04:58.664  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:04:58.664  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:04:58.664  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:04:58.677  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:04:58.717  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 15:04:58.718  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
03-24 15:04:58.719  3755  3755 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-24 15:04:58.944  3335  3394 I jxcore-log: ok 131 host address should be null
03-24 15:04:58.944  3335  3394 I jxcore-log: 
03-24 15:04:58.946  3335  3394 I jxcore-log: ok 132 port should should be null
03-24 15:04:58.946  3335  3394 I jxcore-log: 
,03-24 15:04:58.963  3335  3394 I jxcore-log: # teardown,
03-24 15:04:58.963  3335  3394 I jxcore-log: 
,03-24 15:04:59.103  3335  3394 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 15:04:59.103  3335  3394 I jxcore-log: 
,03-24 15:04:59.106  3335  3394 I jxcore-log: ok 133 error should be null
03-24 15:04:59.106  3335  3394 I jxcore-log: ,
03-24 15:04:59.106  3335  3394 I jxcore-log: ok 134 error should be null
,03-24 15:04:59.106  3335  3394 I jxcore-log: 
03-24 15:04:59.109  3335  3394 I jxcore-log: # setup
03-24 15:04:59.109  3335  3394 I jxcore-log: ,
,03-24 15:04:59.235  3335  3394 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 15:04:59.235  3335  3394 I jxcore-log: 
,03-24 15:04:59.392  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 34380, start advertisements: false
03-24 15:04:59.392  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-24 15:04:59.393  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:59.393  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:04:59.402  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 15:04:59.402  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:04:59.402  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:04:59.411  2162  2229 D BtGatt.GattService: registerClient() - UUID=28018656-7a34-4dc9-b15e-ab5f0f188d57
,03-24 15:04:59.411  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=28018656-7a34-4dc9-b15e-ab5f0f188d57, clientIf=5
03-24 15:04:59.412  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:04:59.413  2162  2180 D BtGatt.GattService: start scan with filters
,03-24 15:04:59.415  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:04:59.416  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:04:59.417  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:04:59.417  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 15:04:59.417  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:04:59.418  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:59.418  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:04:59.419  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:04:59.420   823  1443 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:59.427  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:04:59.427  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.430  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:04:59.430  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:59.430  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:04:59.430  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:04:59.435  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:04:59.435  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:59.438  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:04:59.438  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.440  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:04:59.440  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:04:59.440  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:04:59.441  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:59.441  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:04:59.441  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:04:59.445  3335  3394 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
03-24 15:04:59.445  3335  3394 I jxcore-log: 
,03-24 15:04:59.448  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:04:59.449  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:04:59.449  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:04:59.449  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:04:59.452  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:04:59.453  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 15:04:59.454  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:04:59.454  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:04:59.454  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.455  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:04:59.455  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:04:59.455  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:04:59.456  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:04:59.456  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:04:59.456  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:04:59.456  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:04:59.456  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:04:59.457  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:04:59.458  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:04:59.458  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.458  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:04:59.459  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:04:59.460  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.461  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:59.461  3335  3394 I jxcore-log: 
,03-24 15:04:59.464  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:59.464  3335  3394 I jxcore-log: 
,03-24 15:04:59.469  3335  3394 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 15:04:59.469  3335  3394 I jxcore-log: 
,03-24 15:04:59.479  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:59.479  3335  3394 I jxcore-log: 
,03-24 15:04:59.481  3335  3394 I jxcore-log: # teardown
03-24 15:04:59.481  3335  3394 I jxcore-log: 
,03-24 15:04:59.580  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:04:59.580  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:04:59.580  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:04:59.586  3335  3394 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:04:59.586  3335  3394 I jxcore-log: 
,03-24 15:04:59.588  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:04:59.588  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:59.588  3335  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:04:59.588  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:04:59.588  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 15:04:59.588  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:04:59.589  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:04:59.589  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:04:59.590  3335  3394 D BluetoothLeScanner: could not find callback wrapper
,03-24 15:04:59.590  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:04:59.592  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:04:59.592  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 15:04:59.592  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:04:59.593  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:04:59.593  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:04:59.593  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:59.593  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:04:59.593  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:04:59.601  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:04:59.602   823  1310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:04:59.611  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:04:59.613  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:04:59.613  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:04:59.618  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:04:59.619  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:04:59.619  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:04:59.622  3335  3394 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:04:59.622  3335  3394 I jxcore-log: 
,03-24 15:04:59.650  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:04:59.650  3335  3394 I jxcore-log: 
,03-24 15:04:59.651  3335  3394 I jxcore-log: # setup
03-24 15:04:59.651  3335  3394 I jxcore-log: 
,03-24 15:04:59.783  3335  3394 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error
03-24 15:04:59.783  3335  3394 I jxcore-log: 
,03-24 15:04:59.920  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 34380, start advertisements: false
,03-24 15:04:59.921  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:04:59.921  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:59.921  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:04:59.930  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 15:04:59.930  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:04:59.930  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:04:59.939  2162  2229 D BtGatt.GattService: registerClient() - UUID=229a7690-4448-48f3-83c4-cec9b6ad253f
,03-24 15:04:59.940  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=229a7690-4448-48f3-83c4-cec9b6ad253f, clientIf=5
03-24 15:04:59.941  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:04:59.943  2162  2180 D BtGatt.GattService: start scan with filters
,03-24 15:04:59.945  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 15:04:59.945  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:04:59.945  2162  2238 D BtGatt.ScanManager: handling starting scan,
03-24 15:04:59.945  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:04:59.946  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:04:59.946  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:59.947  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:04:59.948  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:04:59.950  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:04:59.950   823  1442 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:04:59.950  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:59.953  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:04:59.953  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.953  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:04:59.953  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:04:59.957  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:04:59.957  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:04:59.960  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:04:59.960  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:04:59.964  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:04:59.965  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:04:59.965  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:04:59.965  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:59.965  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:04:59.966  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:04:59.971  3335  3394 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-24 15:04:59.971  3335  3394 I jxcore-log: 
,03-24 15:04:59.979  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 34380, start advertisements: false
,03-24 15:04:59.979  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:04:59.979  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:04:59.979  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:04:59.979  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:04:59.982  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:59.982  3335  3394 I jxcore-log: 
,03-24 15:04:59.984  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:04:59.984  3335  3394 I jxcore-log: 
,03-24 15:04:59.987  3335  3394 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-24 15:04:59.987  3335  3394 I jxcore-log: 
,03-24 15:05:00.001  3335  3394 I jxcore-log: # teardown
03-24 15:05:00.001  3335  3394 I jxcore-log: 
,03-24 15:05:00.216  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:00.217  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:00.217  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:05:00.217  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:05:00.221  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:00.225  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:05:00.225  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.226  2162  2238 D BtGatt.ScanManager: stopping BLe Batch,
03-24 15:05:00.226  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:00.228  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:05:00.228  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:00.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-24 15:05:00.229  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 15:05:00.229  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:05:00.229  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-24 15:05:00.229  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-24 15:05:00.230  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 15:05:00.230  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.230  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:00.230  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:00.230  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:00.233  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:00.233  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:00.238  3335  3394 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:05:00.238  3335  3394 I jxcore-log: 
03-24 15:05:00.240  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:00.240  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:05:00.240  3335  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:05:00.240  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:00.240  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:00.240  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:00.240  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:00.242  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:00.244  3335  3394 D BluetoothLeScanner: could not find callback wrapper
03-24 15:05:00.245  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:00.246  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:00.246  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:00.246  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:05:00.248  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-24 15:05:00.248  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:00.248  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:00.248  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:00.248  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:00.250  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:00.250  3335  3394 I jxcore-log: 
,03-24 15:05:00.258  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:00.259   823  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:00.267  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:05:00.268  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:00.268  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:00.274  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:00.274  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:05:00.274  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:05:00.278  3335  3394 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
,03-24 15:05:00.278  3335  3394 I jxcore-log: 
,03-24 15:05:00.286  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 15:05:00.286  3335  3394 I jxcore-log: 
03-24 15:05:00.287  3335  3394 I jxcore-log: # setup
03-24 15:05:00.287  3335  3394 I jxcore-log: 
,03-24 15:05:00.500  3335  3394 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-24 15:05:00.500  3335  3394 I jxcore-log: 
,03-24 15:05:00.616  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:05:00.616  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:00.616  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:00.616  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:00.624  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:05:00.625  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:00.625  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:00.625  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:00.634  2162  2179 D BtGatt.GattService: registerClient() - UUID=e2d58db5-33cc-4a3b-bfa2-68b7ec5c98ca
,03-24 15:05:00.634  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=e2d58db5-33cc-4a3b-bfa2-68b7ec5c98ca, clientIf=5
03-24 15:05:00.635  3335  3384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:05:00.636  2162  2229 D BtGatt.GattService: start scan with filters
,03-24 15:05:00.639  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:05:00.639  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:00.639  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:00.639  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 15:05:00.640  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:00.640  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:00.641  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:00.642  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:00.642  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:00.642  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:00.643  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:00.643  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:00.643  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:00.649  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:00.649  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.651  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:00.651  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 15:05:00.652  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:00.652  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:05:00.655  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 15:05:00.655  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.657  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:00.658  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:00.659  2162  2180 D BtGatt.GattService: registerClient() - UUID=02bba63c-0d18-42e8-bd1d-2f4b3e633203
03-24 15:05:00.660  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=02bba63c-0d18-42e8-bd1d-2f4b3e633203, clientIf=6
,03-24 15:05:00.663  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:05:00.665  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:00.671  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:00.675  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:00.678  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:00.680  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:00.680  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:05:00.681   823  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:00.688  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:00.688  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:00.688  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:05:00.688  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:00.689  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:05:00.690  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:05:00.691  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:05:00.691  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:05:00.692  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:00.692  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:00.692  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:00.692  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:00.692  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:00.692  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:00.692  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:00.692  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:00.692  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:00.692  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:00.692  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:00.692  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:05:00.692  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:00.693   823  1310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:00.696  3335  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:00.696  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:00.696  3335  3394 I jxcore-log: 
,03-24 15:05:00.699  3335  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:05:00.699  3335  3394 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-24 15:05:00.699  3335  3394 I jxcore-log: 
,03-24 15:05:00.702  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:00.702  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:05:00.702  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:05:00.702  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:05:00.702  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:05:00.703  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:00.703  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:05:00.703  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:00.703  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 15:05:00.703  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 15:05:00.703  3335  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:05:00.703  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:00.703  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:00.703  3335  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:05:00.704  3335  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 15:05:00.707  2162  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:00.708  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:00.709  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:00.709  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 15:05:00.709  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 15:05:00.709  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 15:05:00.709  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:05:00.709  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:00.709  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:05:00.710  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:00.710  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.710  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:00.712  2162  2237 D BtGatt.AdvertiseManager: message : 1
,03-24 15:05:00.713  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:00.713  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.713  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:00.713  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:00.714  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:00.714  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:00.717  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:00.717  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:00.719  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 15:05:00.720  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:00.720  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:00.720  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:00.720  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:00.720  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:05:00.720  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:00.720  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 15:05:00.720  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:05:00.721  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:05:00.721  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 15:05:00.722  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:00.722  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:05:00.722  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:00.726  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:00.726  3335  3394 I jxcore-log: 
,03-24 15:05:00.727  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:05:00.728   823  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:00.729  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:00.729  3335  3394 I jxcore-log: 
,03-24 15:05:00.734  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:05:00.735  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:00.735  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:00.738  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 15:05:00.738  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 15:05:00.739  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:00.739  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:00.739  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:00.739  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:00.739  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:00.739  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:05:00.741  3335  3394 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 15:05:00.741  3335  3394 I jxcore-log: 
,03-24 15:05:00.752  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:00.752  3335  3394 I jxcore-log: 
,03-24 15:05:00.754  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:00.754  3335  3394 I jxcore-log: 
,03-24 15:05:00.757  3335  3394 I jxcore-log: # teardown
03-24 15:05:00.757  3335  3394 I jxcore-log: 
,03-24 15:05:00.760  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:00.760  3335  3394 I jxcore-log: 
,03-24 15:05:01.129  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:01.129  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:01.129  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:01.133  3335  3394 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:05:01.133  3335  3394 I jxcore-log: 
,03-24 15:05:01.134  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:01.134  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:05:01.135  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:01.139  3335  3394 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:05:01.139  3335  3394 I jxcore-log: 
,03-24 15:05:01.150  3335  3394 I jxcore-log: # setup
03-24 15:05:01.150  3335  3394 I jxcore-log: 
,03-24 15:05:01.261  3335  3394 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 15:05:01.261  3335  3394 I jxcore-log: 
,03-24 15:05:01.385  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:05:01.385  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:01.386  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:01.386  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:01.395  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:05:01.395  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:01.395  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:01.395  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:01.404  2162  2229 D BtGatt.GattService: registerClient() - UUID=509bd69e-356e-41f2-a0cd-303ce655cf43
,03-24 15:05:01.405  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=509bd69e-356e-41f2-a0cd-303ce655cf43, clientIf=5
,03-24 15:05:01.406  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:01.407  2162  2180 D BtGatt.GattService: start scan with filters
03-24 15:05:01.409  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:01.409  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:01.409  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:01.410  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:01.411  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:01.411  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:01.413  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:01.414  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:05:01.414  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:01.415  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 15:05:01.415  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:01.416  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:01.417  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:05:01.417  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:01.418  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:01.418  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:05:01.419  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:01.421  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:01.421  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:01.422  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:01.422  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:01.425  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:01.425  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:01.435  2162  2179 D BtGatt.GattService: registerClient() - UUID=ad0a9416-5219-42b8-aa0b-d9b867a169ec,
03-24 15:05:01.435  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=ad0a9416-5219-42b8-aa0b-d9b867a169ec, clientIf=6
03-24 15:05:01.436  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:05:01.437  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:01.440  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:05:01.442  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 15:05:01.444  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:01.444  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:01.444  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:05:01.445   823  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:01.447  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:01.447  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:01.447  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:05:01.447  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:01.448  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:05:01.449  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:01.449  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:05:01.449  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:05:01.449  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:01.449  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 15:05:01.449  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:01.449  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:01.449  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:01.449  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:01.449  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:01.449  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:01.449  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:01.449  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:01.449  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:01.450  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 15:05:01.450  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:05:01.451  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:01.451  3335  3394 I jxcore-log: 
03-24 15:05:01.453   823  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:01.454  3335  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:05:01.454  3335  3394 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-24 15:05:01.454  3335  3394 I jxcore-log: 
,03-24 15:05:01.457  3335  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:05:01.458  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-24 15:05:01.458  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:01.458  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:01.458  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:01.459  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:01.460  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:01.460  3335  3394 I jxcore-log: 
,03-24 15:05:01.461  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:01.461  3335  3394 I jxcore-log: 
,03-24 15:05:01.462  3335  3394 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-24 15:05:01.462  3335  3394 I jxcore-log: 
,03-24 15:05:01.467  3335  3394 I jxcore-log: # teardown
03-24 15:05:01.467  3335  3394 I jxcore-log: 
,03-24 15:05:01.932  2162  2162 D BtGatt.ScanManager: awakened up at time 220634
,03-24 15:05:01.935  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:01.944  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:05:01.945  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:01.945  2162  2226 D BtGatt.GattService: current time is 220647624184
03-24 15:05:01.945  2162  2226 D BtGatt.GattService: Batch record : [-17, -44, -9, -77, -100, 74, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -61, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 15:05:01.946  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:01.947  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:05:01.956  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 15:05:01.958  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 15:05:01.958  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 15:05:01.959  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 15:05:01.965  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-24 15:05:01.965  3335  3394 I jxcore-log: 
,03-24 15:05:01.967  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-24 15:05:01.967  3335  3394 I jxcore-log: 
,03-24 15:05:02.180  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:05:02.181  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:05:02.181  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 15:05:02.181  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:05:02.185  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:02.188  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-24 15:05:02.189  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 15:05:02.189  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:02.190  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:02.190  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 15:05:02.190  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:02.190  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 15:05:02.190  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:05:02.191  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 15:05:02.191  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:02.191  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:02.192  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
,03-24 15:05:02.192  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:05:02.192  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:02.193  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:02.193  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-24 15:05:02.196  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 15:05:02.196  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:02.197  2162  2226 D BtGatt.GattService: current time is 220899530747,
03-24 15:05:02.197  2162  2226 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -17, -44, -9, -77, -100, 74, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:02.198  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:05:02.199  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:02.199  3335  3394 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:05:02.199  3335  3394 I jxcore-log: 
03-24 15:05:02.200  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 15:05:02.200  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:02.200  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:05:02.200  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 15:05:02.200  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:05:02.200  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:02.200  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-24 15:05:02.200  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:02.200  3335  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:05:02.200  3335  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:05:02.200  3335  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:05:02.201  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:05:02.201  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:05:02.201  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:05:02.202  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:02.202  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:02.202  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:02.203  3335  3394 D BluetoothLeScanner: could not find callback wrapper
03-24 15:05:02.204  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:02.204  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:05:02.206  2162  2237 D BtGatt.AdvertiseManager: message : 1
,03-24 15:05:02.207  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:02.210  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:02.210  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:02.212  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:02.213  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:02.213  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:05:02.213  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:02.213  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 15:05:02.214  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:05:02.214  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:02.214  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:02.214  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:02.215  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:05:02.215  3335  3394 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:05:02.215  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:02.215  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:02.215  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:02.215  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:02.215  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:02.215  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:05:02.219  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:02.219  3335  3394 I jxcore-log: 
,03-24 15:05:02.221  3335  3394 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:05:02.221  3335  3394 I jxcore-log: 
,03-24 15:05:02.223  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:02.224   823  1442 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:02.229  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:05:02.230  3335  3394 I jxcore-log: # setup
03-24 15:05:02.230  3335  3394 I jxcore-log: 
,03-24 15:05:02.232  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 15:05:02.232  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:02.248  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:02.248  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:02.250  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:02.250  3335  3394 I jxcore-log: 
,03-24 15:05:02.251  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:02.251  3335  3394 I jxcore-log: 
,03-24 15:05:03.180  3335  3394 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 15:05:03.180  3335  3394 I jxcore-log: 
,03-24 15:05:03.320  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 15:05:03.320  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:03.321  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:03.321  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:03.333  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:05:03.333  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:03.334  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:03.334  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:03.345  2162  2229 D BtGatt.GattService: registerClient() - UUID=c1403fa6-88f9-45ad-a2ac-45fbd815a8e8
,03-24 15:05:03.348  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=c1403fa6-88f9-45ad-a2ac-45fbd815a8e8, clientIf=5
,03-24 15:05:03.349  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:03.349  2162  2180 D BtGatt.GattService: start scan with filters
,03-24 15:05:03.351  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:03.351  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:03.351  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:03.351  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:05:03.351  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:03.352  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:03.352  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:03.352  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:03.353  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 15:05:03.357  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:03.358  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:03.358  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:03.361  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:03.361  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:03.362  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:03.363  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:03.364  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:03.364  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:03.364  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:05:03.367  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:03.367  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:03.369  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:03.369  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:03.370  2162  2179 D BtGatt.GattService: registerClient() - UUID=ebcf1ce5-fc97-4b34-9ff5-a0f3b131c1fa
,03-24 15:05:03.371  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=ebcf1ce5-fc97-4b34-9ff5-a0f3b131c1fa, clientIf=6
03-24 15:05:03.371  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:03.372  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:03.374  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:03.376  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 15:05:03.379  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 15:05:03.379  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:03.379  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:03.380   823  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:03.382  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:03.382  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:03.382  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:05:03.382  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:03.383  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:05:03.383  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:03.383  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:05:03.383  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:05:03.383  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:03.383  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:03.384  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:03.384  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:03.384  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:03.384  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:03.384  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:03.384  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:03.384  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:03.384  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:03.384  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:03.384  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 15:05:03.384  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:03.385  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:03.385  3335  3394 I jxcore-log: 
03-24 15:05:03.386   823  1401 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:03.387  3335  3394 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
03-24 15:05:03.387  3335  3394 I jxcore-log: 
03-24 15:05:03.387  3335  3865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:03.390  3335  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:05:03.391  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
03-24 15:05:03.391  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:05:03.391  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:05:03.391  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:03.391  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:03.393  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:03.393  3335  3394 I jxcore-log: 
03-24 15:05:03.394  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:03.394  3335  3394 I jxcore-log: 
,03-24 15:05:03.396  3335  3394 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-24 15:05:03.396  3335  3394 I jxcore-log: 
,03-24 15:05:04.379  2162  2162 D BtGatt.ScanManager: awakened up at time 223081
,03-24 15:05:04.380  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:04.390  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:05:04.391  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:04.391  2162  2226 D BtGatt.GattService: current time is 223093727986
,03-24 15:05:04.391  2162  2226 D BtGatt.GattService: Batch record : [-20, 30, 60, -45, -26, 104, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:05:04.392  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:04.393  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:04.396  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 15:05:04.398  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 15:05:04.399  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 15:05:04.400  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:05:04.405  3335  3394 I jxcore-log: ok 153 peers must be an array
03-24 15:05:04.405  3335  3394 I jxcore-log: ,
03-24 15:05:04.407  3335  3394 I jxcore-log: ok 154 peers must not be zero-length
03-24 15:05:04.407  3335  3394 I jxcore-log: 
,03-24 15:05:04.410  3335  3394 I jxcore-log: ok 155 peer must have peerIdentifier
03-24 15:05:04.410  3335  3394 I jxcore-log: 
,03-24 15:05:04.412  3335  3394 I jxcore-log: ok 156 peerIdentifier must be a string
03-24 15:05:04.412  3335  3394 I jxcore-log: 
03-24 15:05:04.413  3335  3394 I jxcore-log: ok 157 peer must have peerAvailable
03-24 15:05:04.413  3335  3394 I jxcore-log: 
03-24 15:05:04.415  3335  3394 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 15:05:04.415  3335  3394 I jxcore-log: 
,03-24 15:05:04.433  3335  3394 I jxcore-log: # teardown
03-24 15:05:04.433  3335  3394 I jxcore-log: 
,03-24 15:05:04.779  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 15:05:04.779  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:05:04.779  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:05:04.779  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:04.782  2162  2229 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:05:04.783  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:04.784  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:04.784  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:04.784  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:04.784  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:04.785  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:04.785  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:04.785  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:05:04.785  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:05:04.785  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:05:04.786  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:04.786  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:04.786  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:04.786  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:05:04.787  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:04.787  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:04.789  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 15:05:04.789  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:04.790  2162  2226 D BtGatt.GattService: current time is 223492417256
03-24 15:05:04.790  2162  2226 D BtGatt.GattService: Batch record : [-20, 30, 60, -45, -26, 104, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 15:05:04.791  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:04.791  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:05:04.798  3335  3394 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:05:04.798  3335  3394 I jxcore-log: 
03-24 15:05:04.799  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:04.799  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:04.799  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:05:04.799  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:05:04.799  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:05:04.800  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:04.800  3335  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:05:04.800  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:04.800  3335  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 15:05:04.800  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:04.800  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:04.800  3335  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 15:05:04.800  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:04.800  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:05:04.801  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:05:04.801  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:05:04.802  3335  3394 D BluetoothLeScanner: could not find callback wrapper
,03-24 15:05:04.802  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:04.802  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:05:04.805  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:04.806  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:04.809  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 15:05:04.809  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:04.811  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:04.812  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-24 15:05:04.812  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:04.812  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:04.812  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:04.813  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:05:04.813  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:04.813  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:04.813  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-24 15:05:04.813  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:04.814  3335  3394 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:05:04.814  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:04.814  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:04.814  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:04.814  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:04.815  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 15:05:04.815  3335  3394 I jxcore-log: 
03-24 15:05:04.824  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:05:04.824   823  1401 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:04.831  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:05:04.832  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:04.832  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:04.836  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-24 15:05:04.836  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:04.836  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:05:04.836  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:04.837  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:04.838  3335  3394 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:05:04.838  3335  3394 I jxcore-log: 
,03-24 15:05:04.845  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:04.845  3335  3394 I jxcore-log: 
03-24 15:05:04.846  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:04.846  3335  3394 I jxcore-log: 
03-24 15:05:04.848  3335  3394 I jxcore-log: # setup
03-24 15:05:04.848  3335  3394 I jxcore-log: 
,03-24 15:05:04.981  1234  1493 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-24 15:05:04.981  1234  1493 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 15:05:05.023  1389  1389 I ConfigService: onCreate,
,03-24 15:05:05.071  3335  3394 I jxcore-log: # 38. Can connect to a remote peer
03-24 15:05:05.071  3335  3394 I jxcore-log: 
,03-24 15:05:05.242  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 49385, start advertisements: true
03-24 15:05:05.242  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:05:05.242  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:05.242  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:05.245  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:05:05.245  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:05.245  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:05.245  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:05.249  2162  2229 D BtGatt.GattService: registerClient() - UUID=232b6304-f806-45aa-b852-c9d153cb64df
03-24 15:05:05.249  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=232b6304-f806-45aa-b852-c9d153cb64df, clientIf=5
03-24 15:05:05.250  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:05:05.251  2162  2179 D BtGatt.GattService: start scan with filters
,03-24 15:05:05.252  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:05.252  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:05:05.252  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:05.253  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:05.253  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:05.253  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:05.254  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:05.254  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:05.254  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:05.254  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:05.254  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:05.254  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:05.255  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:05.255  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:05.255  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:05.255  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:05.255  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:05.256  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:05.256  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:05.258  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:05.258  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:05.260  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:05.260  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:05.261  2162  2180 D BtGatt.GattService: registerClient() - UUID=c6495b3d-1a47-4cab-8a9f-dc15cf06b275
03-24 15:05:05.261  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=c6495b3d-1a47-4cab-8a9f-dc15cf06b275, clientIf=6
03-24 15:05:05.262  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:05.263  2162  2237 D BtGatt.AdvertiseManager: message : 0
03-24 15:05:05.271  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
03-24 15:05:05.274  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:05.276  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 15:05:05.278  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:05.278  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:05.278   823  1297 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 15:05:05.281  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 15:05:05.282  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:05.282  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:05:05.282  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:05.282  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 15:05:05.283  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:05.283  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 15:05:05.283  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:05:05.283  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:05.283  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-24 15:05:05.283  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:05.283  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:05:05.283  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:05.283  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:05.283  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
03-24 15:05:05.283  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:05.284  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:05.284  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:05.284  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:05.284  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
03-24 15:05:05.284  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:05.284   823  1465 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:05.285  3335  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:05.287  3335  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:05:05.296  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 15:05:05.296  3335  3394 I jxcore-log: 
,03-24 15:05:05.299  3335  3394 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
,03-24 15:05:05.299  3335  3394 I jxcore-log: 
,03-24 15:05:05.304  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 49385, start advertisements: false
,03-24 15:05:05.304  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:05.304  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:05:05.304  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:05.304  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:05.306  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:05.306  3335  3394 I jxcore-log: 
,03-24 15:05:05.307  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-24 15:05:05.307  3335  3394 I jxcore-log: 
03-24 15:05:05.309  3335  3394 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-24 15:05:05.309  3335  3394 I jxcore-log: 
,03-24 15:05:05.765  2162  2162 D BtGatt.ScanManager: awakened up at time 224467
,03-24 15:05:05.767  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:05.779  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-24 15:05:05.779  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:05.779  2162  2226 D BtGatt.GattService: current time is 224481867620
,03-24 15:05:05.780  2162  2226 D BtGatt.GattService: Batch record : [-72, -14, -60, 60, 113, 88, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -127, -59, 40, 32, -73, -32, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:05:05.780  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:05.781  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:05.782  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:05:05.784  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 15:05:05.785  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
,03-24 15:05:05.786  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 15:05:05.787  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 15:05:05.787  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 15:05:05.792  3335  3394 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 15:05:05.792  3335  3394 I jxcore-log: 
,03-24 15:05:05.807  3335  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 15:05:05.808  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:05:05.812  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
03-24 15:05:05.814  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 15:05:05.814  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 15:05:05.815  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
,03-24 15:05:05.815  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
,03-24 15:05:05.815  3335  3394 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 15:05:05.817  3335  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 363)
03-24 15:05:05.818  3335  3869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:05.820  3335  3394 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 15:05:05.820  3335  3394 I jxcore-log: 
,03-24 15:05:05.821  2162  2179 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 15:05:08.100  2162  2239 W bt-btif : info:x10
03-24 15:05:08.100  2162  2226 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 15:05:08.101  2162  2226 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 15:05:08.143  2162  2239 W bt-sdp  : process_service_search_attr_rsp
,03-24 15:05:08.294  2162  2226 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1,
,03-24 15:05:08.304  2162  2226 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1,
03-24 15:05:08.305  2162  2226 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 15:05:08.313  2162  2228 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11,
03-24 15:05:08.314  2162  2228 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 15:05:08.344  2162  2226 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,03-24 15:05:08.346  2162  2228 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 15:05:08.380   823   857 I ActivityManager: Start proc 3870:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-24 15:05:08.383  2162  2228 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 15:05:08.402  2162  2239 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:05:08.402  2162  2239 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:05:08.402  2162  2239 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 15:05:08.403  3335  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 363)
03-24 15:05:08.404  3335  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 363)
03-24 15:05:08.405  2162  2228 I BluetoothBondStateMachine: StableState(): Entering Off State
03-24 15:05:08.406  3335  3888 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 364)
,03-24 15:05:08.408  3335  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 364)
03-24 15:05:08.408  3335  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 364)
,03-24 15:05:08.408  3335  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 363)
,03-24 15:05:08.445   823   861 D BluetoothManagerService: Message: 20
03-24 15:05:08.445   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ecb69b0:true
,03-24 15:05:08.449   823  1443 I ActivityManager: Killing 3525:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 15:05:08.456  3335  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 364)
,03-24 15:05:08.457  3335  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:08.458  3335  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 363)
03-24 15:05:08.458  3335  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 363)
03-24 15:05:08.458  3335  3888 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 364)
03-24 15:05:08.459  3335  3335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:08.459  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:08.459  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 15:05:08.460  3335  3335 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:08.460  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:08.462  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:08.463  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:08.466  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 15:05:08.466  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:08.467  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:08.467  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:08.467  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:08.467  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:05:08.467  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 15:05:08.468  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:08.468  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 15:05:08.468  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:08.468  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:08.468  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:08.473  2162  2229 D BtGatt.GattService: registerClient() - UUID=3bb83637-2e7c-4e61-b08c-dff531135753
03-24 15:05:08.473  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=3bb83637-2e7c-4e61-b08c-dff531135753, clientIf=6
03-24 15:05:08.473  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:08.474  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:08.476  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:05:08.479  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 15:05:08.481  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:05:08.482  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:08.483  2162  2229 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:08.484  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:08.485  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:08.485  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:08.485  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:08.485  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:08.485  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:08.485  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:08.485  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:08.485  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.485  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:08.487  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:08.487  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.487  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:08.489  2162  2229 D BtGatt.GattService: registerClient() - UUID=6d4a19c3-c932-433f-800c-cfefcdba5bd4
,03-24 15:05:08.490  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=6d4a19c3-c932-433f-800c-cfefcdba5bd4, clientIf=5
03-24 15:05:08.490  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:05:08.490  3335  3384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:08.490  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.490  2162  2226 D BtGatt.GattService: current time is 227192864026
03-24 15:05:08.490  2162  2226 D BtGatt.GattService: Batch record : [-72, -14, -60, 60, 113, 88, 1, -128, -79, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 21, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-24 15:05:08.490  2162  2179 D BtGatt.GattService: start scan with filters
03-24 15:05:08.491  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:08.491  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:08.491  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:08.491  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:08.493  2162  2237 D BtGatt.AdvertiseManager: message : 1
,03-24 15:05:08.495  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:08.496  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:08.497  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:08.497  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:08.498  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:08.499  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:05:08.499  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:05:08.499  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:08.499  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 15:05:08.499  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:08.499  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 15:05:08.499  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:08.499  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:08.499  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:08.500  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:08.500  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.501  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:08.501  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.501  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:05:08.501  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:08.503  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:08.503  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.504  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:08.504  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.505  2162  2229 D BtGatt.GattService: registerClient() - UUID=54457c54-8d9d-4d43-9ab7-78af34024f88
03-24 15:05:08.505  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=54457c54-8d9d-4d43-9ab7-78af34024f88, clientIf=6
,03-24 15:05:08.505  3335  3352 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:08.506  2162  2237 D BtGatt.AdvertiseManager: message : 0
03-24 15:05:08.509  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:08.511  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:08.513  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 15:05:08.514  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:08.515  2162  2229 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:08.516  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:08.516  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:08.516  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:08.516  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:08.516  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:08.516  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:08.516  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:08.517  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:08.517  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.517  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:08.520  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:08.520  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.520  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:08.520  2162  2180 D BtGatt.GattService: registerClient() - UUID=0d572f04-eb7a-4d70-bc1a-83e9630b90e3
,03-24 15:05:08.520  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=0d572f04-eb7a-4d70-bc1a-83e9630b90e3, clientIf=5
03-24 15:05:08.520  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:08.521  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:08.521  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.521  2162  2229 D BtGatt.GattService: start scan with filters
,03-24 15:05:08.522  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:08.522  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:08.524  2162  2237 D BtGatt.AdvertiseManager: message : 1
,03-24 15:05:08.524  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:08.526  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:08.526  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:08.526  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:08.527  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:05:08.528  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:08.528  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:05:08.528  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:08.528  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 15:05:08.528  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:08.528  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:08.528  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:08.528  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:08.528  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:08.529  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:08.529  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.530  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:08.530  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.530  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:08.530  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:08.531  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:08.531  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.532  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:08.533  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.533  2162  2180 D BtGatt.GattService: registerClient() - UUID=a0ece13a-4be8-46c1-ac5a-d6f08d840208
03-24 15:05:08.533  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=a0ece13a-4be8-46c1-ac5a-d6f08d840208, clientIf=6
03-24 15:05:08.533  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:08.534  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:08.536  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:08.539  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:08.541  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:08.542  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:08.543  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:05:08.544  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:08.544  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:08.544  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:08.544  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:08.544  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:05:08.544  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:08.544  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:08.546  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:08.546  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.548  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:08.548  2162  2179 D BtGatt.GattService: registerClient() - UUID=6f7edc4d-4bbf-4601-a1ac-afeb9a6e5e25
03-24 15:05:08.548  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=6f7edc4d-4bbf-4601-a1ac-afeb9a6e5e25, clientIf=5
,03-24 15:05:08.548  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:08.549  2162  2180 D BtGatt.GattService: start scan with filters
,03-24 15:05:08.549  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:08.550  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.550  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:08.550  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:08.550  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:08.550  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 15:05:08.550  3335  3335 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:05:08.550  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:08.550  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:08.550  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:08.551  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:08.551  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.551  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:08.551  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:08.552  3335  3890 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 365)
03-24 15:05:08.553  3335  3890 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58194
03-24 15:05:08.554  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:08.555  3335  3890 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:05:08.556  3335  3890 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 58194 (peer ID: E0:DB:10:14:E2:C0)
03-24 15:05:08.556  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:08.556  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.556  3335  3890 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 15:05:08.557  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:08.557  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:08.557  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:05:08.557  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:08.560  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:08.560  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.560  3335  3394 I jxcore-log: INFO testThaliMobileNative: 
03-24 15:05:08.560  3335  3394 I jxcore-log: 
03-24 15:05:08.561  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:08.561  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:08.562  3335  3394 I jxcore-log: ok 163 Must have listeningPort
03-24 15:05:08.562  3335  3394 I jxcore-log: 
,03-24 15:05:08.563  3335  3394 I jxcore-log: ok 164 listeningPort must be a number
03-24 15:05:08.563  3335  3394 I jxcore-log: 
03-24 15:05:08.563  3335  3394 I jxcore-log: ok 165 Connection must have clientPort
03-24 15:05:08.563  3335  3394 I jxcore-log: 
03-24 15:05:08.564  3335  3394 I jxcore-log: ok 166 clientPort must be a number
03-24 15:05:08.564  3335  3394 I jxcore-log: 
,03-24 15:05:08.567  3335  3394 I jxcore-log: ok 167 Connection must have serverPort
03-24 15:05:08.567  3335  3394 I jxcore-log: 
03-24 15:05:08.567  3335  3394 I jxcore-log: ok 168 serverPort must be a number
03-24 15:05:08.567  3335  3394 I jxcore-log: 
03-24 15:05:08.568  3335  3394 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 15:05:08.568  3335  3394 I jxcore-log: 
03-24 15:05:08.569  3335  3394 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-24 15:05:08.569  3335  3394 I jxcore-log: 
,03-24 15:05:08.574  3335  3394 I jxcore-log: # teardown
03-24 15:05:08.574  3335  3394 I jxcore-log: 
,03-24 15:05:09.595  3542  3893 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:05:09.716  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:05:09.716  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:05:09.716  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:09.716  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:09.719   823  1442 I art     : Explicit concurrent mark sweep GC freed 30127(1447KB) AllocSpace objects, 7(677KB) LOS objects, 32% free, 33MB/49MB, paused 3.409ms total 105.553ms
,03-24 15:05:09.724  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:09.741  3143  3894 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:05:09.741  3143  3894 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:05:09.741  3143  3894 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	... 12 more
03-24 15:05:09.741  3143  3894 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at fal.a(PG:38)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:05:09.741  3143  3894 E HttpOperation: 	... 14 more
,03-24 15:05:09.744  3542  3895 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 15:05:09.778  1389  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 15:05:09.778  1389  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:05:09.778  1389  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:09.778  1389  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 15:05:09.779  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 15:05:09.779  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:05:09.779  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:09.779  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:09.783  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
03-24 15:05:09.783  1389  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:09.796  3143  3894 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:05:09.796  3143  3894 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at hec.a(PG:42)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at hee.a(PG:102)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at czr.a(PG:65)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at kka.a(PG:108)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:05:09.796  3143  3894 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	... 15 more
03-24 15:05:09.796  3143  3894 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at fal.a(PG:38)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:05:09.796  3143  3894 E HttpOperation: 	... 17 more
,03-24 15:05:09.797  3143  3894 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:05:09.797  3143  3894 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at czp.a(PG:19176),
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error,
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	... 15 more
03-24 15:05:09.797  3143  3894 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:05:09.797  3143  3894 E ExperimentLoader: 	... 17 more
,03-24 15:05:09.853  1389  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:05:09.854  1389  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:05:09.854  1389  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:09.854  1389  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:09.859  1389  1928 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:09.873  3542  3895 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:05:09.875  3542  3893 E BooksSync: Soft error
03-24 15:05:09.875  3542  3893 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:05:09.875  3542  3893 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:05:09.876  3542  3893 E BooksSync: Sync error
03-24 15:05:09.876  3542  3893 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:05:09.876  3542  3893 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:05:09.876  3542  3893 I BooksSync: Finished books sync
,03-24 15:05:09.886   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201755, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:05:09.926  3567  3897 V KeepSync: Connecting to GoogleApiClient
,03-24 15:05:09.932   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 201620, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:05:09.999  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-24 15:05:09.999  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:05:09.999  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:09.999  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:10.008  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: Handling authorization failure,
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:05:10.043  1785  3898 E ClientConnectionOperation: 	... 7 more
,03-24 15:05:10.053  3567  3897 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 15:05:10.061  3567  3897 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:05:10.082  3567  3897 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:05:10.084  3567  3897 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:05:10.117  1389  1389 I ConfigService: onDestroy
,03-24 15:05:10.203  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 15:05:10.203  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:05:10.204  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:10.204  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:10.218  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:10.321  3567  3897 E KeepSync: IOException
03-24 15:05:10.321  3567  3897 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:05:10.321  3567  3897 E KeepSync: ,	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:05:10.321  3567  3897 E KeepSync: 	,at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
,03-24 15:05:10.321  3567  3897 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:05:10.321  3567  3897 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
,03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:05:10.321  3567  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:05:10.321  3567  3897 E KeepSync: 	... 10 more
,03-24 15:05:10.321  3567  3897 W KeepSync: Sync result 2
03-24 15:05:10.328   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202330, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:05:12.556  2162  2401 W bt-btif : invalid rfc slot id: 10
,03-24 15:05:12.855  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:12.855  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:05:12.855  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 15:05:12.856  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:05:12.860  2162  2180 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 15:05:12.862  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:12.863  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:12.863  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:12.863  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:12.863  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:05:12.863  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:05:12.864  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:12.864  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:05:12.864  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 15:05:12.864  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:12.865  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:12.865  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:05:12.865  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:12.866  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:12.866  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:12.866  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:12.869  3335  3394 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:05:12.869  3335  3394 I jxcore-log: 
03-24 15:05:12.869  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-24 15:05:12.869  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:12.869  2162  2226 D BtGatt.GattService: current time is 231571743972
03-24 15:05:12.869  2162  2226 D BtGatt.GattService: Batch record : [-72, -14, -60, 60, 113, 88, 1, -128, -73, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -67, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -81, 88, -51, 15, -43, 90, 1, -128, -73, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:12.869  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:12.870  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:12.870  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:12.874  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:12.874  3335  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:05:12.875  3335  3394 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 365)
03-24 15:05:12.875  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 365)
03-24 15:05:12.875  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 15:05:12.875  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 365)
03-24 15:05:12.875  3335  3394 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 365),
03-24 15:05:12.876  3335  3890 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 365)
03-24 15:05:12.878  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:12.878  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:05:12.878  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:05:12.878  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:05:12.880  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:12.881  3335  3868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-24 15:05:12.881  3335  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 15:05:12.881  3335  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 15:05:12.882  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:05:12.882  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 15:05:12.883  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:12.883  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-24 15:05:12.883  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:12.883  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:12.883  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:05:12.883  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:05:12.885  3335  3394 D BluetoothLeScanner: could not find callback wrapper
03-24 15:05:12.885  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:12.885  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:05:12.888  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:12.889  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:12.892  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:12.892  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:12.893  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:12.894  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:05:12.894  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:12.895  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:12.895  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:12.895  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:05:12.895  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:12.895  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:12.895  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 15:05:12.896  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:12.896  3335  3394 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:05:12.896  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:12.897  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:12.897  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:12.898  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:12.898  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:12.898  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:12.899  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:12.899  3335  3394 I jxcore-log: 
,03-24 15:05:12.903  3335  3394 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown,
03-24 15:05:12.903  3335  3394 I jxcore-log: 
,03-24 15:05:12.907  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:05:12.908   823  1401 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 15:05:12.914  3335  3394 I jxcore-log: # setup
03-24 15:05:12.914  3335  3394 I jxcore-log: 
,03-24 15:05:12.921  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-24 15:05:12.923  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:12.923  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:12.931  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:12.931  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:12.934  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:12.934  3335  3394 I jxcore-log: 
,03-24 15:05:12.936  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:12.936  3335  3394 I jxcore-log: 
,03-24 15:05:13.045  3335  3394 I jxcore-log: # 39. Can shift large amounts of data
03-24 15:05:13.045  3335  3394 I jxcore-log: 
,03-24 15:05:14.103  2162  2224 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:05:15.228  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 40505, start advertisements: true
03-24 15:05:15.228  3335  3394 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:15.228  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:15.229  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectabl,e: false
03-24 15:05:15.229  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:15.229  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:15.229  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:15.229  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:15.234  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:05:15.234  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:15.234  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:15.235  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:15.238  2162  2229 D BtGatt.GattService: registerClient() - UUID=7350fce1-0d20-4767-ba9f-1262fdc15f26,
,03-24 15:05:15.239  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=7350fce1-0d20-4767-ba9f-1262fdc15f26, clientIf=5
03-24 15:05:15.241  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:05:15.243  2162  2180 D BtGatt.GattService: start scan with filters
,03-24 15:05:15.244  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:15.244  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:15.244  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:15.244  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:15.244  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:15.244  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 15:05:15.245  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:15.245  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:15.245  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:15.245  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:15.245  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:15.246  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:15.246  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:15.251  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-24 15:05:15.251  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:15.253  2162  2179 D BtGatt.GattService: registerClient() - UUID=ae0ddc07-bdfe-4383-a9ee-0bf57ffff4b6
03-24 15:05:15.253  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 15:05:15.253  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:15.254  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=ae0ddc07-bdfe-4383-a9ee-0bf57ffff4b6, clientIf=6
,03-24 15:05:15.255  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:15.255  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:05:15.256  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:15.256  2162  2237 D BtGatt.AdvertiseManager: message : 0
03-24 15:05:15.259  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
,03-24 15:05:15.259  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:15.259  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
03-24 15:05:15.261  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:15.261  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:15.265  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:15.267  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:05:15.268  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:15.268  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:15.268   823  1443 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:15.270  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:15.270  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-24 15:05:15.270  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:05:15.270  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:05:15.271  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 15:05:15.271  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:15.271  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:05:15.271  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:05:15.271  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
,03-24 15:05:15.271  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-24 15:05:15.271  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:15.271  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:15.272  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:15.272  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:15.272  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:15.272  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:15.272  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:15.272  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:05:15.272  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:05:15.272  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:05:15.272  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:15.273  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:15.273  3335  3394 I jxcore-log: 
03-24 15:05:15.274  3335  3394 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 15:05:15.274  3335  3394 I jxcore-log: 
,03-24 15:05:15.274   823  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:15.276  3335  3902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:15.278  3335  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:05:15.278  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 40505, start advertisements: false
03-24 15:05:15.278  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:05:15.278  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 15:05:15.279  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:15.279  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 15:05:15.281  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:15.281  3335  3394 I jxcore-log: 
03-24 15:05:15.283  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:15.283  3335  3394 I jxcore-log: 
,03-24 15:05:15.291  3335  3394 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error,
03-24 15:05:15.291  3335  3394 I jxcore-log: 
,03-24 15:05:16.654  2162  2239 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 15:05:16.660  2162  2162 D BluetoothMapService: onReceive
,03-24 15:05:16.740   823  1469 I ActivityManager: Start proc 3903:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-24 15:05:16.890   823   861 D BluetoothManagerService: Message: 20
03-24 15:05:16.890   823   861 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20cc7388:true
,03-24 15:05:16.905  3903  3903 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:05:17.091   823   838 I ActivityManager: Start proc 3929:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-24 15:05:17.098  3903  3903 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:05:17.121   823  1469 I ActivityManager: Killing 3681:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-24 15:05:17.330   823  1469 I ActivityManager: Killing 3632:com.android.chrome/u0a40 (adj 15): empty #18
,03-24 15:05:17.632  2162  2162 D BtGatt.ScanManager: awakened up at time 236334
,03-24 15:05:17.633  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:17.640  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
03-24 15:05:17.641  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:17.641  2162  2226 D BtGatt.GattService: current time is 236343621991
,03-24 15:05:17.642  2162  2226 D BtGatt.GattService: Batch record : [-12, -24, -114, 125, -22, 127, 1, -128, -78, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -69, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -99, -90, 11, -58, -34, 93, 1, -128, -79, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 50, -24, 107, -52, 103, 102, 1, -128, -92, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -103, -50, -45, -95, -128, 91, 1, -128, -92, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:17.642  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:17.643  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:17.644  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:17.644  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:17.645  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:17.649  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-24 15:05:17.649  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 15:05:17.650  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 15:05:17.651  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 15:05:17.651  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
03-24 15:05:17.651  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 15:05:17.652  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:05:17.663  3335  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-24 15:05:17.663  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:05:17.666  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 15:05:17.667  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 15:05:17.667  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 15:05:17.668  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
,03-24 15:05:17.668  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 15:05:17.668  3335  3394 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
03-24 15:05:17.670  3335  3949 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 367)
,03-24 15:05:17.670  3335  3949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:05:17.674  2162  2180 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 15:05:19.029  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:19.116  1389  1575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 15:05:19.117  1389  1575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 15:05:19.117  1389  1575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:19.118  1389  1575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:19.133  1389  1575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:19.181  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 15:05:19.182  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 15:05:19.184  3755  3755 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-24 15:05:19.796  2162  2239 W bt-btif : info:x10
03-24 15:05:19.797  2162  2226 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 15:05:19.830  3903  3903 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:05:19.837  3903  3903 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:05:19.902  2162  2239 W bt-btif : info:x10
,03-24 15:05:19.902  2162  2226 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 15:05:19.903  2162  2226 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 15:05:20.056  2162  2239 W bt-sdp  : process_service_search_attr_rsp
,03-24 15:05:20.144  2162  2239 E bt-btm  : tBTM_SEC_DEV:0xa2f7b07c rs_disc_pending=0
03-24 15:05:20.144  2162  2239 W bt-btif : bta_dm_check_av:0
03-24 15:05:20.144  2162  2226 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 15:05:20.668  2162  2226 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 15:05:20.674  2162  2226 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
03-24 15:05:20.675  2162  2226 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 15:05:20.680  2162  2228 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-24 15:05:20.680  2162  2228 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 15:05:20.711  2162  2239 E bt-btm  : tBTM_SEC_DEV:0xa2f7aeb4 rs_disc_pending=0
03-24 15:05:20.711  2162  2239 W bt-btif : bta_dm_check_av:0
,03-24 15:05:20.712  2162  2226 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 15:05:20.757  3335  3949 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367),
03-24 15:05:20.757  2162  2239 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:05:20.757  3335  3949 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 367)
03-24 15:05:20.757  2162  2239 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:05:20.757  2162  2239 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:05:20.759  3335  3949 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 368)
03-24 15:05:20.759  3335  3949 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 368)
,03-24 15:05:20.759  3335  3949 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 367)
03-24 15:05:20.761  3335  3950 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 368)
,03-24 15:05:20.829  2162  2226 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 15:05:20.830  2162  2228 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 15:05:20.833  2162  2228 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 15:05:20.850  2162  2228 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 15:05:21.007  2162  2239 E bt-btm  : tBTM_SEC_DEV:0xa2f7aeb4 rs_disc_pending=1
,03-24 15:05:21.007  2162  2239 W bt-btif : bta_dm_check_av:0
03-24 15:05:21.007  2162  2226 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 15:05:21.114  3335  3950 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 368)
,03-24 15:05:21.118  3335  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:05:21.119  3335  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
03-24 15:05:21.119  3335  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 367)
03-24 15:05:21.120  3335  3950 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 368)
03-24 15:05:21.120  3335  3335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:21.120  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:21.121  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 15:05:21.121  3335  3335 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 15:05:21.121  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 15:05:21.122  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:21.122  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:21.122  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:21.122  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:21.122  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:21.122  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:21.126  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:21.128  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:21.131  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:21.132  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:21.133  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:21.134  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:21.134  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:21.134  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:21.134  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:21.135  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:21.135  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:21.135  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:21.136  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:21.136  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:21.146  2162  2180 D BtGatt.GattService: registerClient() - UUID=baef82d6-fa77-4b39-9384-aca1bae320b2
,03-24 15:05:21.146  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=baef82d6-fa77-4b39-9384-aca1bae320b2, clientIf=6
,03-24 15:05:21.147  3335  3352 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:21.149  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:21.154  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:21.158  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:21.162  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:21.163  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:21.165  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:21.166  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:21.167  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:05:21.167  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:05:21.167  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:21.167  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:21.167  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:21.167  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:21.168  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:21.168  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 15:05:21.168  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:21.170  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:21.170  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:21.170  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-24 15:05:21.173  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:05:21.173  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:21.173  2162  2226 D BtGatt.GattService: current time is 239875883813
03-24 15:05:21.173  2162  2226 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -70, 48, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -103, -50, -45, -95, -128, 91, 1, -128, -86, 37, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-24 15:05:21.174  2162  2179 D BtGatt.GattService: registerClient() - UUID=1ac1ef40-1977-494d-9609-fe76d8a01f81
03-24 15:05:21.174  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
,03-24 15:05:21.175  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:21.175  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=1ac1ef40-1977-494d-9609-fe76d8a01f81, clientIf=5
03-24 15:05:21.176  3335  3384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:21.177  2162  2180 D BtGatt.GattService: start scan with filters
03-24 15:05:21.178  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:21.178  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 15:05:21.178  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 15:05:21.179  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:21.179  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-24 15:05:21.179  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:21.179  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:21.179  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:21.179  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:21.181  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:21.183  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:21.188  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:21.188  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:21.189  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:21.198  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:05:21.198  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:21.198  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-24 15:05:21.198  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:21.198  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:21.199  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:21.199  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:21.199  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:21.199  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:21.199  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:21.200  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:21.200  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:21.201  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:05:21.201  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.201  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:21.201  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:05:21.203  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:21.203  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.204  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:21.204  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.204  2162  2229 D BtGatt.GattService: registerClient() - UUID=642474c7-09b3-486c-a248-6fb482670652
03-24 15:05:21.204  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=642474c7-09b3-486c-a248-6fb482670652, clientIf=6
03-24 15:05:21.205  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:21.206  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:21.208  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:21.210  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 15:05:21.213  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:05:21.214  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:21.215  2162  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:21.216  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:21.216  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:05:21.216  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:21.216  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:21.216  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:21.216  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:21.216  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:21.219  2162  2229 D BtGatt.GattService: registerClient() - UUID=1de6e8b6-9acb-4861-b08c-8d60df308f73
,03-24 15:05:21.219  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=1de6e8b6-9acb-4861-b08c-8d60df308f73, clientIf=5
,03-24 15:05:21.220  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 15:05:21.220  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:21.220  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.220  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:21.220  2162  2179 D BtGatt.GattService: start scan with filters
03-24 15:05:21.221  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
,03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:21.221  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:21.222  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:21.222  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.222  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:21.223  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:21.223  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:21.223  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.223  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:21.227  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:21.229  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:21.229  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:21.230  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-24 15:05:21.231  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:21.231  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:05:21.231  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:05:21.231  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:21.231  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:21.231  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:21.231  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.231  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:21.231  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 15:05:21.231  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:21.231  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:21.232  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:21.232  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 15:05:21.232  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:21.232  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:21.234  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:21.234  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.235  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:21.235  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.235  2162  2229 D BtGatt.GattService: registerClient() - UUID=12a11954-6983-4a05-bfb3-a21c2af64c5f
03-24 15:05:21.236  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=12a11954-6983-4a05-bfb3-a21c2af64c5f, clientIf=6
03-24 15:05:21.236  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:21.237  2162  2237 D BtGatt.AdvertiseManager: message : 0
03-24 15:05:21.239  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
03-24 15:05:21.241  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:21.245  2162  2239 E bt-btm  : tBTM_SEC_DEV:0xa2f7b07c rs_disc_pending=1
,03-24 15:05:21.246  2162  2239 W bt-btif : bta_dm_check_av:0
03-24 15:05:21.246  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 15:05:21.246  2162  2226 W bt-btif : btif_dm_cback : unhandled event (14)
03-24 15:05:21.246  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:21.248  2162  2229 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:21.249  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:21.249  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:21.249  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:21.249  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:21.249  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:21.249  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:21.249  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:05:21.249  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:21.249  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:21.249  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:21.251  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 15:05:21.251  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.251  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:21.252  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 15:05:21.252  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.254  2162  2180 D BtGatt.GattService: registerClient() - UUID=bc7859cc-22dc-4590-98cf-ac2934467359
03-24 15:05:21.254  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=bc7859cc-22dc-4590-98cf-ac2934467359, clientIf=5
03-24 15:05:21.254  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:05:21.254  2162  2229 D BtGatt.GattService: start scan with filters
03-24 15:05:21.255  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:21.255  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:05:21.256  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 15:05:21.256  3335  3335 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:05:21.256  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:21.256  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-24 15:05:21.256  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:21.256  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:21.256  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:21.256  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:21.256  3335  3951 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 369)
,03-24 15:05:21.257  3335  3951 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37102
03-24 15:05:21.257  3335  3951 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:05:21.257  3335  3951 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 37102 (peer ID: E0:DB:10:14:E2:C0)
03-24 15:05:21.257  3335  3951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 15:05:21.257  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:05:21.258  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.258  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:21.259  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.259  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:21.259  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:21.260  3335  3394 I jxcore-log: INFO testThaliMobileNative: 
03-24 15:05:21.260  3335  3394 I jxcore-log: 
,03-24 15:05:21.260  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:21.260  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:21.261  3335  3394 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 15:05:21.261  3335  3394 I jxcore-log: 
03-24 15:05:21.261  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:21.261  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:21.264  3335  3951 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 37102
,03-24 15:05:21.264  3335  3951 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:05:21.265  3335  3951 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:21.265  3335  3951 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:21.266  3335  3952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 370, name: Sender)
,03-24 15:05:21.266  3335  3951 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 369)
,03-24 15:05:21.266  3335  3951 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 369)
03-24 15:05:21.266  3335  3394 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 15:05:21.266  3335  3394 I jxcore-log: 
03-24 15:05:21.267  3335  3953 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 371, name: Receiver)
,03-24 15:05:21.366  2162  2239 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 15:05:21.366  2162  2239 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:05:21.366  2162  2239 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:05:21.367  3335  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 15:05:21.368  3335  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 372)
,03-24 15:05:21.368  3335  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:05:21.369   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:21.373  3335  3902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:21.374  3335  3954 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 372)
,03-24 15:05:21.379  3335  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:05:21.418  3335  3394 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:05:21.418  3335  3394 I jxcore-log: 
,03-24 15:05:21.490  3335  3394 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 15:05:21.490  3335  3394 I jxcore-log: 
,03-24 15:05:21.633  3335  3394 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-24 15:05:21.633  3335  3394 I jxcore-log: 
,03-24 15:05:21.705  3335  3954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 372)
,03-24 15:05:21.709  3335  3954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 15:05:21.710  3335  3954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 372)
,03-24 15:05:21.710  3335  3954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 372
03-24 15:05:21.711  3335  3954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 372)
03-24 15:05:21.711  3335  3954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:05:21.712  3335  3954 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 372)
03-24 15:05:21.712  3335  3335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 15:05:21.712  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 15:05:21.712  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 15:05:21.714  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 15:05:21.714  3335  3335 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 15:05:21.716  3335  3955 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 373)
,03-24 15:05:21.721  3335  3955 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 40505
,03-24 15:05:21.722  3335  3955 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:05:21.722  3335  3955 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:21.722  3335  3955 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes,
,03-24 15:05:21.724  3335  3957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 374, name: Sender)
03-24 15:05:21.726  3335  3955 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 373)
03-24 15:05:21.726  3335  3955 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 373)
03-24 15:05:21.726  3335  3958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Receiver)
,03-24 15:05:21.862  3335  3394 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-24 15:05:21.862  3335  3394 I jxcore-log: 
,03-24 15:05:21.923  3335  3394 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-24 15:05:21.923  3335  3394 I jxcore-log: 
,03-24 15:05:21.925  3335  3394 I jxcore-log: ok 175 received should match sent forward
03-24 15:05:21.925  3335  3394 I jxcore-log: 
,03-24 15:05:21.937  3335  3394 I jxcore-log: # teardown
03-24 15:05:21.937  3335  3394 I jxcore-log: 
,03-24 15:05:23.051  2162  2401 W bt-btif : invalid rfc slot id: 11
,03-24 15:05:23.051  3335  3958 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1
,03-24 15:05:23.051  3335  3958 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,03-24 15:05:23.052  3335  3958 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 15:05:23.052  3335  3958 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 373
03-24 15:05:23.052  3335  3958 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 373)
03-24 15:05:23.052  3335  3958 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:05:23.052  3335  3958 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 15:05:23.052  3335  3958 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-24 15:05:23.052  3335  3958 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-24 15:05:23.053  3335  3958 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 374
03-24 15:05:23.053  3335  3958 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 373)
03-24 15:05:23.054  3335  3957 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
03-24 15:05:23.054  3335  3957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 374, name: Sender)
03-24 15:05:23.054  3335  3958 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 373)
03-24 15:05:23.054  3335  3958 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 15:05:23.057  3335  3958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Receiver)
,03-24 15:05:23.069  3335  3394 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
,03-24 15:05:23.069  3335  3394 I jxcore-log: 
03-24 15:05:23.070  3335  3394 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 15:05:23.070  3335  3394 I jxcore-log: 
,03-24 15:05:23.224  2162  2239 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,03-24 15:05:23.224  2162  2239 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x45
,03-24 15:05:23.252  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:23.252  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 15:05:23.252  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 15:05:23.252  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:23.255  2162  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:23.259  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 15:05:23.259  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:23.259  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:23.259  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:23.260  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:23.260  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:23.261  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:23.261  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:05:23.261  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 15:05:23.262  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:23.263  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:23.263  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:23.263  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:23.264  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:23.265  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 15:05:23.265  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:05:23.266  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 15:05:23.266  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:23.267  2162  2226 D BtGatt.GattService: current time is 241969533603
03-24 15:05:23.267  2162  2226 D BtGatt.GattService: Batch record : [-103, -50, -45, -95, -128, 91, 1, -128, -94, 36, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -70, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 15:05:23.268  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:23.269  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 15:05:23.269  3335  3394 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-24 15:05:23.269  3335  3394 I jxcore-log: 
03-24 15:05:23.271  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:23.271  3335  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:05:23.271  3335  3394 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 369)
03-24 15:05:23.271  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 369)
,03-24 15:05:23.272  3335  3953 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Receiver): bt socket closed, read return: -1
,03-24 15:05:23.272  3335  3953 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 371, name: Receiver),
,03-24 15:05:23.274  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
,03-24 15:05:23.274  3335  3394 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...,
,03-24 15:05:23.274  3335  3394 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 371
03-24 15:05:23.274  3335  3394 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 15:05:23.274  3335  3394 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 370
,03-24 15:05:23.274  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 369)
03-24 15:05:23.275  3335  3394 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 369)
03-24 15:05:23.275  3335  3952 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Sender): Socket closed
,03-24 15:05:23.275  3335  3952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 370, name: Sender)
03-24 15:05:23.275  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:23.275  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 15:05:23.275  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:05:23.275  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:05:23.275  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-24 15:05:23.275  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:23.275  3335  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:05:23.275  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:23.276  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 15:05:23.276  3335  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:05:23.276  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:23.276  3335  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:05:23.276  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 15:05:23.278  3335  3394 D BluetoothLeScanner: could not find callback wrapper
03-24 15:05:23.278  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:23.279  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:05:23.283  2162  2237 D BtGatt.AdvertiseManager: message : 1
,03-24 15:05:23.284  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:23.289  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:23.289  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:23.291  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:23.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:23.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:23.293  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:23.294  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:23.294  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:05:23.294  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:23.294  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:23.294  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:23.296  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:23.296  3335  3394 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-24 15:05:23.296  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:23.297  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:23.297  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:23.297  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:23.301  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:23.301  3335  3394 I jxcore-log: 
03-24 15:05:23.309  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 15:05:23.309   823  1442 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:23.321  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:05:23.323  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 15:05:23.323  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:23.328  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:05:23.328  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:05:23.328  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:23.329  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:23.329  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:23.329  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:23.329  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:05:23.331  3335  3394 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-24 15:05:23.331  3335  3394 I jxcore-log: 
,03-24 15:05:23.341  3335  3394 I jxcore-log: # setup,
03-24 15:05:23.341  3335  3394 I jxcore-log: 
03-24 15:05:23.344  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:23.344  3335  3394 I jxcore-log: 
03-24 15:05:23.345  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:23.345  3335  3394 I jxcore-log: 
,03-24 15:05:23.802  2162  2239 E bt-btm  : tBTM_SEC_DEV:0xa2f7aeb4 rs_disc_pending=0,
03-24 15:05:23.803  2162  2239 W bt-btif : bta_dm_check_av:0
03-24 15:05:23.803  2162  2226 W bt-btif : btif_dm_cback : unhandled event (14),
,03-24 15:05:23.823  2162  2239 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
,03-24 15:05:24.069  2162  2239 E bt-btm  : tBTM_SEC_DEV:0xa2f7b07c rs_disc_pending=0
03-24 15:05:24.069  2162  2239 W bt-btif : bta_dm_check_av:0
03-24 15:05:24.069  2162  2226 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 15:05:24.194  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:24.194  3335  3394 I jxcore-log: 
,03-24 15:05:24.195  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:24.195  3335  3394 I jxcore-log: 
,03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:24.203  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:24.206  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-24 15:05:24.210  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:24.210  3335  3394 I jxcore-log: 
,03-24 15:05:24.214  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:24.214  3335  3394 I jxcore-log: 
,03-24 15:05:24.220  3335  3394 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-24 15:05:24.220  3335  3394 I jxcore-log: 
,03-24 15:05:24.224  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:24.224  3335  3394 I jxcore-log: 
,03-24 15:05:24.436  3335  3394 I jxcore-log: ok 178 specific error should be returned,
03-24 15:05:24.436  3335  3394 I jxcore-log: 
,03-24 15:05:24.443  3335  3394 I jxcore-log: # teardown
03-24 15:05:24.443  3335  3394 I jxcore-log: 
,03-24 15:05:24.570  3335  3394 I jxcore-log: # setup
03-24 15:05:24.570  3335  3394 I jxcore-log: 
,03-24 15:05:24.708  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:24.708  3335  3394 I jxcore-log: 
03-24 15:05:24.709  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:24.709  3335  3394 I jxcore-log: 
,03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:24.719  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:24.723  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:24.724  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:24.724  3335  3394 I jxcore-log: 
,03-24 15:05:24.726  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:24.726  3335  3394 I jxcore-log: 
,03-24 15:05:24.729  3335  3394 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:05:24.729  3335  3394 I jxcore-log: 
,03-24 15:05:24.731  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:24.731  3335  3394 I jxcore-log: 
,03-24 15:05:24.957  3335  3394 I jxcore-log: ok 179 specific error should be returned
03-24 15:05:24.957  3335  3394 I jxcore-log: 
,03-24 15:05:24.963  3335  3394 I jxcore-log: # teardown
03-24 15:05:24.963  3335  3394 I jxcore-log: 
,03-24 15:05:25.129  3335  3394 I jxcore-log: # setup
03-24 15:05:25.129  3335  3394 I jxcore-log: 
,03-24 15:05:25.283  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:25.283  3335  3394 I jxcore-log: 
,03-24 15:05:25.288  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:25.288  3335  3394 I jxcore-log: 
,03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:25.296  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:25.302  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:25.303  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:25.303  3335  3394 I jxcore-log: 
,03-24 15:05:25.305  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:25.305  3335  3394 I jxcore-log: 
,03-24 15:05:25.308  3335  3394 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
03-24 15:05:25.308  3335  3394 I jxcore-log: 
,03-24 15:05:25.310  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:25.310  3335  3394 I jxcore-log: 
,03-24 15:05:25.477  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:25.477  3335  3394 I jxcore-log: 
,03-24 15:05:25.479  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 52998
03-24 15:05:25.479  3335  3394 I jxcore-log: 
,03-24 15:05:25.481  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:25.481  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:25.481  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:25.485  3335  3394 I jxcore-log: ok 180 no errors
03-24 15:05:25.485  3335  3394 I jxcore-log: 
,03-24 15:05:25.486  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:25.486  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:25.486  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:25.489  3335  3394 I jxcore-log: ok 181 still no errors
03-24 15:05:25.489  3335  3394 I jxcore-log: 
,03-24 15:05:25.494  3335  3394 I jxcore-log: # teardown
03-24 15:05:25.494  3335  3394 I jxcore-log: 
,03-24 15:05:25.648  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:25.648  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:25.648  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:25.649  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:05:25.649  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:25.649  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:25.657  3335  3394 I jxcore-log: # setup
03-24 15:05:25.657  3335  3394 I jxcore-log: 
,03-24 15:05:25.800  2162  2224 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:05:25.808  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:25.808  3335  3394 I jxcore-log: 
,03-24 15:05:25.810  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:25.810  3335  3394 I jxcore-log: 
,03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:25.817  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 15:05:25.821  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:25.822  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:25.822  3335  3394 I jxcore-log: 
03-24 15:05:25.824  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:25.824  3335  3394 I jxcore-log: 
03-24 15:05:25.826  3335  3394 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
03-24 15:05:25.826  3335  3394 I jxcore-log: 
,03-24 15:05:25.829  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-24 15:05:25.829  3335  3394 I jxcore-log: 
,03-24 15:05:26.029  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 15:05:26.029  3335  3394 I jxcore-log: 
,03-24 15:05:26.032  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 40461,
03-24 15:05:26.032  3335  3394 I jxcore-log: 
,03-24 15:05:26.039  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 40505, start advertisements: false,
03-24 15:05:26.039  3335  3394 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:05:26.039  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:26.040  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:05:26.040  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:26.040  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 15:05:26.046  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 15:05:26.046  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:26.046  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-24 15:05:26.054  2162  2180 D BtGatt.GattService: registerClient() - UUID=97ddb1d0-5832-4cb9-8821-2918c785a891
,03-24 15:05:26.055  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=97ddb1d0-5832-4cb9-8821-2918c785a891, clientIf=5
,03-24 15:05:26.056  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:26.057  2162  2179 D BtGatt.GattService: start scan with filters
,03-24 15:05:26.058  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:26.058  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:05:26.058  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:26.058  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:26.058  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:26.059  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:26.059  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:05:26.059  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:26.059   823  1467 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:26.062  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:26.062  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:26.063  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:05:26.063  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:26.063  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:26.063  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:26.064  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:26.064  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 15:05:26.065  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:26.065  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:26.065  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:26.065  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:26.067  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 15:05:26.067  3335  3394 I jxcore-log: 
03-24 15:05:26.068  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:26.068  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:26.068  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:26.068  3335  3394 I jxcore-log: 
03-24 15:05:26.069  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 15:05:26.069  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:26.071  3335  3394 I jxcore-log: ok 182 no errors
03-24 15:05:26.071  3335  3394 I jxcore-log: ,
03-24 15:05:26.074  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 40505, start advertisements: false
03-24 15:05:26.074  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 15:05:26.074  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:26.075  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:26.075  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:26.079  3335  3394 I jxcore-log: ok 183 still no errors
,03-24 15:05:26.079  3335  3394 I jxcore-log: 
,03-24 15:05:26.085  3335  3394 I jxcore-log: # teardown
,03-24 15:05:26.085  3335  3394 I jxcore-log: 
,03-24 15:05:26.288  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 15:05:26.288  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:26.288  3335  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 15:05:26.289  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:26.289  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:26.289  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 15:05:26.289  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-24 15:05:26.290  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:26.290  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:26.294  2162  2179 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 15:05:26.297  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:26.299  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:26.299  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:26.299  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:26.299  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:26.300  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:05:26.300  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:26.300  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:05:26.300  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 15:05:26.300  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:26.302  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:05:26.302  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:26.302  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:26.303  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:26.303  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:26.303  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:26.304  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 15:05:26.304  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:26.304  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:26.304  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:26.304  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:26.305  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:26.305  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:26.319  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 15:05:26.320   823  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:26.331  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 15:05:26.332  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:26.332  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:26.336  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:26.336  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:26.336  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:26.337  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:26.339  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:26.340  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:26.340  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:26.343  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:26.343  3335  3394 I jxcore-log: 
,03-24 15:05:26.343  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:26.343  3335  3394 I jxcore-log: 
,03-24 15:05:26.354  3335  3394 I jxcore-log: # setup
,03-24 15:05:26.354  3335  3394 I jxcore-log: 
,03-24 15:05:26.491  2162  2239 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 15:05:26.497  2162  2162 D BluetoothMapService: onReceive
,03-24 15:05:26.501  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 15:05:26.501  3335  3394 I jxcore-log: 
03-24 15:05:26.504  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:26.504  3335  3394 I jxcore-log: 
,03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:26.523  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:26.529  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:26.531  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:26.531  3335  3394 I jxcore-log: 
,03-24 15:05:26.531  3903  3903 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:05:26.532  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:26.532  3335  3394 I jxcore-log: 
03-24 15:05:26.534  3903  3903 I BluetoothClassifier: Bluetooth Device Name: G4-1
03-24 15:05:26.535  3335  3394 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
03-24 15:05:26.535  3335  3394 I jxcore-log: 
03-24 15:05:26.536  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:26.536  3335  3394 I jxcore-log: 
,03-24 15:05:26.697  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:05:26.697  3335  3394 I jxcore-log: 
,03-24 15:05:26.701  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 51383
,03-24 15:05:26.701  3335  3394 I jxcore-log: 
,03-24 15:05:26.709  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 51383, start advertisements: true
,03-24 15:05:26.709  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:26.709  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 15:05:26.709  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:26.713  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 15:05:26.714  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:05:26.714  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:26.714  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:26.718  2162  2180 D BtGatt.GattService: registerClient() - UUID=89c25a61-2562-4550-955c-a7d49e8ce266,
03-24 15:05:26.719  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=89c25a61-2562-4550-955c-a7d49e8ce266, clientIf=5,
03-24 15:05:26.719  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:26.720  2162  3960 D BtGatt.GattService: start scan with filters
03-24 15:05:26.722  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:26.723  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:05:26.723  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:05:26.723  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 15:05:26.723  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:26.723  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:26.723  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:26.724  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:26.724  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:26.724  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 15:05:26.724  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:26.724  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:26.724  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-24 15:05:26.725  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:26.725  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:26.727  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 15:05:26.727  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:26.728  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:26.728  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 15:05:26.730  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:26.730  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:26.731  2162  3960 D BtGatt.GattService: registerClient() - UUID=6d97d68c-60ec-4eb3-bbf7-7324fbd88917
03-24 15:05:26.732  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=6d97d68c-60ec-4eb3-bbf7-7324fbd88917, clientIf=6
03-24 15:05:26.732  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:26.732  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:26.733  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:26.735  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:26.740  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:26.744  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:26.748  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:26.749  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:26.749  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:05:26.749   823  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:26.755  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:26.756  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:26.756  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:05:26.756  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:05:26.757  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:05:26.757  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:26.758  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:05:26.758  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:05:26.758  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 15:05:26.758  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:26.758  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:26.759  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:05:26.759  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:26.759  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:26.759  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:26.759  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:05:26.759  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:26.759  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:26.759  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 15:05:26.760  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:05:26.760  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:26.760   823  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:26.762  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:26.762  3335  3394 I jxcore-log: 
03-24 15:05:26.762  3335  3961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:26.765  3335  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:05:26.767  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:26.767  3335  3394 I jxcore-log: 
,03-24 15:05:26.769  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:26.769  3335  3394 I jxcore-log: 
03-24 15:05:26.770  3335  3394 I jxcore-log: ok 184 no errors
03-24 15:05:26.770  3335  3394 I jxcore-log: 
,03-24 15:05:26.773  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 51383, start advertisements: true
,03-24 15:05:26.774  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:26.774  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:26.774  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:26.774  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:26.777  3335  3394 I jxcore-log: ok 185 still no errors
03-24 15:05:26.777  3335  3394 I jxcore-log: 
,03-24 15:05:26.783  3335  3394 I jxcore-log: # teardown
03-24 15:05:26.783  3335  3394 I jxcore-log: 
,03-24 15:05:27.116  2162  2239 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 15:05:27.123  2162  2162 D BluetoothMapService: onReceive
,03-24 15:05:27.153  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:27.154  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:27.154  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:05:27.154  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 15:05:27.154  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:05:27.157  3903  3903 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
03-24 15:05:27.158  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:27.159  3335  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:05:27.159  3335  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 15:05:27.159  3335  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:05:27.159  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:05:27.160  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:27.160  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:27.160  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:05:27.160  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:27.160  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:05:27.161  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 15:05:27.161  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:27.161  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:05:27.165  2162  2180 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:05:27.166  3903  3903 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:05:27.177  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:27.179  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:27.179  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:27.180  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:27.180  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:27.180  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:27.180  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:27.180  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 15:05:27.181  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:05:27.181  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:27.181  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:05:27.184  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:27.184  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:27.184  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:27.187  2162  2237 D BtGatt.AdvertiseManager: message : 1
,03-24 15:05:27.188  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:27.189  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 15:05:27.189  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:27.189  2162  2226 D BtGatt.GattService: current time is 245891637821
,03-24 15:05:27.189  2162  2226 D BtGatt.GattService: Batch record : [43, -79, 112, 27, 73, 75, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 15:05:27.190  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:27.190  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:27.194  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 15:05:27.194  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:27.195  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:27.195  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:05:27.195  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:27.195  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:27.196  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:27.196  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:05:27.196  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:27.196  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:27.196  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-24 15:05:27.196  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:27.196  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:27.197  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 15:05:27.197  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:27.197  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:27.197  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:27.197  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:05:27.199  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:05:27.199  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:27.199  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:27.202  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:27.202   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:27.207  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 15:05:27.207  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:27.208  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:27.210  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:05:27.210  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:27.211  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:27.213  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:27.213  3335  3394 I jxcore-log: 
03-24 15:05:27.215  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:27.215  3335  3394 I jxcore-log: 
,03-24 15:05:27.216  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:27.216  3335  3394 I jxcore-log: 
,03-24 15:05:27.233  3335  3394 I jxcore-log: # setup
03-24 15:05:27.233  3335  3394 I jxcore-log: 
,03-24 15:05:27.560  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:27.560  3335  3394 I jxcore-log: 
,03-24 15:05:27.564  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:27.564  3335  3394 I jxcore-log: 
,03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:27.576  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:27.581  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:27.585  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 15:05:27.585  3335  3394 I jxcore-log: 
,03-24 15:05:27.588  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:27.588  3335  3394 I jxcore-log: 
,03-24 15:05:27.595  3335  3394 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times
03-24 15:05:27.595  3335  3394 I jxcore-log: 
03-24 15:05:27.599  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:27.599  3335  3394 I jxcore-log: 
,03-24 15:05:27.715  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:27.715  3335  3394 I jxcore-log: 
,03-24 15:05:27.718  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 51764
03-24 15:05:27.718  3335  3394 I jxcore-log: 
,03-24 15:05:27.719  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:27.719  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:27.719  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:27.721  3335  3394 I jxcore-log: ok 186 no errors
03-24 15:05:27.721  3335  3394 I jxcore-log: 
03-24 15:05:27.723  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:27.723  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:27.723  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:27.725  3335  3394 I jxcore-log: ok 187 still no errors
03-24 15:05:27.725  3335  3394 I jxcore-log: 
,03-24 15:05:27.731  3335  3394 I jxcore-log: # teardown
03-24 15:05:27.731  3335  3394 I jxcore-log: 
,03-24 15:05:27.909  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:27.909  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:27.909  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:27.911  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:27.911  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:27.911  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:27.919  3335  3394 I jxcore-log: # setup
03-24 15:05:27.919  3335  3394 I jxcore-log: 
,03-24 15:05:28.030  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:28.030  3335  3394 I jxcore-log: 
,03-24 15:05:28.036  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:28.036  3335  3394 I jxcore-log: 
,03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:28.047  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:28.052  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:28.056  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:28.056  3335  3394 I jxcore-log: 
,03-24 15:05:28.059  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:28.059  3335  3394 I jxcore-log: 
,03-24 15:05:28.066  3335  3394 I jxcore-log: # 46. can get the network status before starting
03-24 15:05:28.066  3335  3394 I jxcore-log: 
,03-24 15:05:28.069  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:28.069  3335  3394 I jxcore-log: 
,03-24 15:05:28.189  3335  3394 I jxcore-log: ok 188 network status should have certain non-empty properties
03-24 15:05:28.189  3335  3394 I jxcore-log: 
,03-24 15:05:28.191  3335  3394 I jxcore-log: # teardown
03-24 15:05:28.191  3335  3394 I jxcore-log: 
,03-24 15:05:28.360  3335  3394 I jxcore-log: # setup
03-24 15:05:28.360  3335  3394 I jxcore-log: 
,03-24 15:05:28.506  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:28.506  3335  3394 I jxcore-log: 
,03-24 15:05:28.509  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:28.509  3335  3394 I jxcore-log: 
,03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:28.517  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:28.521  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:28.523  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:28.523  3335  3394 I jxcore-log: 
,03-24 15:05:28.524  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:28.524  3335  3394 I jxcore-log: 
03-24 15:05:28.527  3335  3394 I jxcore-log: # 47. error returned with bad router
03-24 15:05:28.527  3335  3394 I jxcore-log: 
,03-24 15:05:28.535  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:28.535  3335  3394 I jxcore-log: 
,03-24 15:05:28.599  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:05:28.696  3335  3394 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 15:05:28.696  3335  3394 I jxcore-log: 
,03-24 15:05:28.699  3335  3394 I jxcore-log: ok 189 specific error expected
03-24 15:05:28.699  3335  3394 I jxcore-log: 
,03-24 15:05:28.702  3335  3394 I jxcore-log: # teardown
03-24 15:05:28.702  3335  3394 I jxcore-log: 
,03-24 15:05:28.862  3335  3394 I jxcore-log: # setup
03-24 15:05:28.862  3335  3394 I jxcore-log: 
,03-24 15:05:28.998  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:28.998  3335  3394 I jxcore-log: 
,03-24 15:05:29.000  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:29.000  3335  3394 I jxcore-log: 
,03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
03-24 15:05:29.008  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:29.012  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:29.014  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:29.014  3335  3394 I jxcore-log: 
,03-24 15:05:29.015  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:29.015  3335  3394 I jxcore-log: 
,03-24 15:05:29.018  3335  3394 I jxcore-log: # 48. all services are stopped when we call stop
03-24 15:05:29.018  3335  3394 I jxcore-log: 
,03-24 15:05:29.020  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:29.020  3335  3394 I jxcore-log: 
,03-24 15:05:29.165  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:29.165  3335  3394 I jxcore-log: 
,03-24 15:05:29.167  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 39750
03-24 15:05:29.167  3335  3394 I jxcore-log: 
,03-24 15:05:29.174  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 51383, start advertisements: false
,03-24 15:05:29.175  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:29.175  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:29.175  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:05:29.180  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:29.180  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:29.181  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:29.185  2162  2179 D BtGatt.GattService: registerClient() - UUID=bbc4415f-fdc9-4bef-ab38-79587d777d5a
,03-24 15:05:29.186  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=bbc4415f-fdc9-4bef-ab38-79587d777d5a, clientIf=5
03-24 15:05:29.187  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:29.187  2162  2229 D BtGatt.GattService: start scan with filters
,03-24 15:05:29.189  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-24 15:05:29.189  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:29.189  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 15:05:29.189  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:29.189  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:29.189  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 15:05:29.189  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:29.190  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:29.191   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:29.196  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:29.196  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:29.196  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:29.197  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:29.197  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:29.197  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:29.197  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:29.198  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:29.200  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:29.200  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:29.200  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:29.201  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:05:29.202  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:29.202  3335  3394 I jxcore-log: 
03-24 15:05:29.203  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-24 15:05:29.203  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:29.204  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:29.204  3335  3394 I jxcore-log: 
03-24 15:05:29.205  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:29.205  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:29.211  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 39750, start advertisements: true
03-24 15:05:29.211  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:29.212  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:29.212  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:29.217  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:05:29.217  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 15:05:29.217  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:29.217  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:29.217  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:29.217  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:29.218  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:29.218  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:29.224  2162  2229 D BtGatt.GattService: registerClient() - UUID=a4a66cbb-e9d6-4e5c-adfe-1c664c1e7390
,03-24 15:05:29.224  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=a4a66cbb-e9d6-4e5c-adfe-1c664c1e7390, clientIf=6
03-24 15:05:29.225  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:05:29.226  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:29.231  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:29.234  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:29.237  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:29.238  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 15:05:29.238  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:29.238  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:29.238  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:29.238  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 15:05:29.239  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:29.239   823  1467 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:29.239  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 15:05:29.243  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:29.243  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:05:29.243  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 15:05:29.243  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:29.244  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:05:29.244  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:05:29.245  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 15:05:29.245  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 15:05:29.245  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:05:29.245  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:29.245  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:29.245  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:29.245  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:05:29.247   823  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:29.248  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:29.248  3335  3394 I jxcore-log: 
03-24 15:05:29.250  3335  3963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 15:05:29.254  3335  3963 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:05:29.255  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:05:29.255  3335  3394 I jxcore-log: 
,03-24 15:05:29.259  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:05:29.259  3335  3394 I jxcore-log: 
,03-24 15:05:29.261  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:05:29.261  3335  3394 I jxcore-log: 
,03-24 15:05:29.264  3335  3394 I jxcore-log: ok 190 connection to servers manager should succeed after starting
03-24 15:05:29.264  3335  3394 I jxcore-log: 
,03-24 15:05:29.274  3335  3394 I jxcore-log: ok 191 connection to router server should succeed after starting
03-24 15:05:29.274  3335  3394 I jxcore-log: 
,03-24 15:05:29.275  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:29.275  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:29.275  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:05:29.275  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 15:05:29.275  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:05:29.276  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:29.276  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:29.276  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:29.276  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:29.276  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:29.276  3335  3963 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:05:29.276  3335  3963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:05:29.276  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:29.276  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:29.276  3335  3963 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:05:29.279  2162  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:29.281  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 15:05:29.281  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:29.281  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 15:05:29.281  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:29.282  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 15:05:29.282  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:29.282  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:29.283  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:05:29.283  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-24 15:05:29.283  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:29.283  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:29.283  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 15:05:29.284  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:29.284  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-24 15:05:29.286  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:29.287  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:29.287  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
03-24 15:05:29.287  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:29.287  2162  2226 D BtGatt.GattService: current time is 247990197143,
03-24 15:05:29.288  2162  2226 D BtGatt.GattService: Batch record : [-18, -54, 93, 28, -66, 69, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:29.288  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:29.290  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:29.290  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:29.292  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:05:29.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:29.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:29.293  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:29.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:29.293  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:05:29.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:29.293  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:29.293  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:29.294  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:29.294  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:29.294  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:29.294  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:29.295  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 15:05:29.297  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:05:29.297  3335  3394 I jxcore-log: 
,03-24 15:05:29.302  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:29.302   823  1467 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:29.308  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:29.308  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:29.309  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:29.312  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 15:05:29.312  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:05:29.312  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 15:05:29.312  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:29.312  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:29.312  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:29.313  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:29.313  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 15:05:29.314  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:29.314  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:29.314  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:29.315  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:29.315  3335  3394 I jxcore-log: 
03-24 15:05:29.317  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:29.317  3335  3394 I jxcore-log: ,
03-24 15:05:29.318  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:29.318  3335  3394 I jxcore-log: 
,03-24 15:05:29.323  3335  3394 I jxcore-log: ok 192 is stopped after calling stop
,03-24 15:05:29.323  3335  3394 I jxcore-log: 
,03-24 15:05:29.329  3335  3394 I jxcore-log: ok 193 connection to servers manager should fail after stopping
,03-24 15:05:29.329  3335  3394 I jxcore-log: 
,03-24 15:05:29.334  3335  3394 I jxcore-log: ok 194 connection to router server should fail after stopping
,03-24 15:05:29.334  3335  3394 I jxcore-log: 
,03-24 15:05:29.340  3335  3394 I jxcore-log: # teardown
03-24 15:05:29.340  3335  3394 I jxcore-log: 
,03-24 15:05:29.638  3335  3394 I jxcore-log: # setup
03-24 15:05:29.638  3335  3394 I jxcore-log: 
,03-24 15:05:29.809  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:29.809  3335  3394 I jxcore-log: 
,03-24 15:05:29.815  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:29.815  3335  3394 I jxcore-log: 
,03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:29.826  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:29.829  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:29.832  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:29.832  3335  3394 I jxcore-log: 
,03-24 15:05:29.834  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:29.834  3335  3394 I jxcore-log: 
,03-24 15:05:29.838  3335  3394 I jxcore-log: # 49. make sure terminateConnection is properly hooked up
03-24 15:05:29.838  3335  3394 I jxcore-log: 
,03-24 15:05:29.840  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:29.840  3335  3394 I jxcore-log: 
,03-24 15:05:30.005  3335  3394 I jxcore-log: ok 195 called with right arguments
03-24 15:05:30.005  3335  3394 I jxcore-log: 
,03-24 15:05:30.007  3335  3394 I jxcore-log: # teardown
03-24 15:05:30.007  3335  3394 I jxcore-log: 
,03-24 15:05:30.161  3335  3394 I jxcore-log: # setup
03-24 15:05:30.161  3335  3394 I jxcore-log: 
,03-24 15:05:30.275  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:30.275  3335  3394 I jxcore-log: 
,03-24 15:05:30.279  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:30.279  3335  3394 I jxcore-log: 
,03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:30.287  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:30.292  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:30.293  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:30.293  3335  3394 I jxcore-log: 
,03-24 15:05:30.295  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:30.295  3335  3394 I jxcore-log: 
,03-24 15:05:30.298  3335  3394 I jxcore-log: # 50. make sure terminateListener is properly hooked up
03-24 15:05:30.298  3335  3394 I jxcore-log: 
,03-24 15:05:30.299  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:30.299  3335  3394 I jxcore-log: 
,03-24 15:05:30.444  3335  3394 I jxcore-log: ok 196 called with right arguments
03-24 15:05:30.444  3335  3394 I jxcore-log: 
,03-24 15:05:30.446  3335  3394 I jxcore-log: # teardown
03-24 15:05:30.446  3335  3394 I jxcore-log: 
,03-24 15:05:30.592  3335  3394 I jxcore-log: # setup
03-24 15:05:30.592  3335  3394 I jxcore-log: 
,03-24 15:05:30.734  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:30.734  3335  3394 I jxcore-log: 
03-24 15:05:30.738  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 15:05:30.738  3335  3394 I jxcore-log: 
,03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:30.746  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:30.750  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:30.752  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:30.752  3335  3394 I jxcore-log: 
,03-24 15:05:30.754  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:30.754  3335  3394 I jxcore-log: 
,03-24 15:05:30.763  3335  3394 I jxcore-log: # 51. make sure we actually call kill connections properly
03-24 15:05:30.763  3335  3394 I jxcore-log: 
,03-24 15:05:30.764  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:30.764  3335  3394 I jxcore-log: 
,03-24 15:05:30.898  3335  3394 I jxcore-log: ok 197 specific error expected
03-24 15:05:30.898  3335  3394 I jxcore-log: 
,03-24 15:05:30.901  3335  3394 I jxcore-log: # teardown,
,03-24 15:05:30.901  3335  3394 I jxcore-log: 
,03-24 15:05:30.998  3335  3394 I jxcore-log: # setup,
03-24 15:05:30.998  3335  3394 I jxcore-log: 
,03-24 15:05:31.110  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:31.110  3335  3394 I jxcore-log: 
,03-24 15:05:31.115  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:31.115  3335  3394 I jxcore-log: 
,03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:31.125  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:31.128  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:31.129  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:31.129  3335  3394 I jxcore-log: 
03-24 15:05:31.131  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:31.131  3335  3394 I jxcore-log: 
,03-24 15:05:31.134  3335  3394 I jxcore-log: # 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 15:05:31.134  3335  3394 I jxcore-log: 
03-24 15:05:31.135  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:31.135  3335  3394 I jxcore-log: 
,03-24 15:05:31.286  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:31.286  3335  3394 I jxcore-log: 
,03-24 15:05:31.291  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 41934
03-24 15:05:31.291  3335  3394 I jxcore-log: 
,03-24 15:05:31.298  3335  3394 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51714,"error":{}}
03-24 15:05:31.298  3335  3394 I jxcore-log: 
,03-24 15:05:31.299  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:31.299  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:05:31.300  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:31.301  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:31.301  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:31.301  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:31.306  3335  3394 I jxcore-log: ok 198 failure reason is as expected
03-24 15:05:31.306  3335  3394 I jxcore-log: 
,03-24 15:05:31.306  3335  3394 I jxcore-log: ok 199 error description is as expected
03-24 15:05:31.306  3335  3394 I jxcore-log: 
,03-24 15:05:31.307  3335  3394 I jxcore-log: ok 200 must be stopped
03-24 15:05:31.307  3335  3394 I jxcore-log: 
,03-24 15:05:31.314  3335  3394 I jxcore-log: # teardown
03-24 15:05:31.314  3335  3394 I jxcore-log: 
,03-24 15:05:31.479  3335  3394 I jxcore-log: # setup
03-24 15:05:31.479  3335  3394 I jxcore-log: 
,03-24 15:05:31.634  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 15:05:31.634  3335  3394 I jxcore-log: 
03-24 15:05:31.638  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:31.638  3335  3394 I jxcore-log: 
,03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
,03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:31.645  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:31.648  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
03-24 15:05:31.650  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:31.650  3335  3394 I jxcore-log: ,
03-24 15:05:31.652  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 15:05:31.652  3335  3394 I jxcore-log: 
,03-24 15:05:31.655  3335  3394 I jxcore-log: # 53. We repeat failedConnection event when we get it from thaliTcpServersManager,
03-24 15:05:31.655  3335  3394 I jxcore-log: 
,03-24 15:05:31.657  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 15:05:31.657  3335  3394 I jxcore-log: 
,03-24 15:05:31.811  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:05:31.811  3335  3394 I jxcore-log: 
,03-24 15:05:31.814  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 47038
03-24 15:05:31.814  3335  3394 I jxcore-log: 
,03-24 15:05:31.818  3335  3394 I jxcore-log: ok 201 peerIdentifier matches
03-24 15:05:31.818  3335  3394 I jxcore-log: 
,03-24 15:05:31.818  3335  3394 I jxcore-log: ok 202 error description matches
03-24 15:05:31.818  3335  3394 I jxcore-log: 
,03-24 15:05:31.823  3335  3394 I jxcore-log: # teardown
03-24 15:05:31.823  3335  3394 I jxcore-log: 
,03-24 15:05:31.975  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:31.975  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:31.975  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:31.979  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:05:31.979  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:31.979  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:31.989  3335  3394 I jxcore-log: # setup
03-24 15:05:31.989  3335  3394 I jxcore-log: 
,03-24 15:05:32.109  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:32.109  3335  3394 I jxcore-log: 
03-24 15:05:32.113  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:32.113  3335  3394 I jxcore-log: 
,03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:32.123  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 15:05:32.127  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-24 15:05:32.130  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:32.130  3335  3394 I jxcore-log: 
,03-24 15:05:32.131  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:32.131  3335  3394 I jxcore-log: 
03-24 15:05:32.134  3335  3394 I jxcore-log: # 54. we successfully receive and replay discoveryAdvertisingStateUpdate
03-24 15:05:32.134  3335  3394 I jxcore-log: 
03-24 15:05:32.135  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:32.135  3335  3394 I jxcore-log: 
,03-24 15:05:32.299  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:32.299  3335  3394 I jxcore-log: 
03-24 15:05:32.301  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 60002
03-24 15:05:32.301  3335  3394 I jxcore-log: 
,03-24 15:05:32.308  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 39750, start advertisements: false
03-24 15:05:32.308  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:32.308  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:32.308  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:05:32.313  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:32.313  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:32.313  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:32.317  2162  2179 D BtGatt.GattService: registerClient() - UUID=64d25b55-91c9-45bc-be05-11ccdecf6ad7
03-24 15:05:32.317  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=64d25b55-91c9-45bc-be05-11ccdecf6ad7, clientIf=5
03-24 15:05:32.318  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:32.318  2162  3960 D BtGatt.GattService: start scan with filters
,03-24 15:05:32.320  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:32.320  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:32.320  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:32.320  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:05:32.320  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:32.320  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:32.320  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:32.321  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:32.322   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:32.325  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:32.325  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 15:05:32.325  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 15:05:32.325  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 15:05:32.325  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:32.325  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:32.328  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:32.328  3335  3394 I jxcore-log: 
,03-24 15:05:32.330  3335  3394 I jxcore-log: ok 203 discoveryActive matches
03-24 15:05:32.330  3335  3394 I jxcore-log: 
03-24 15:05:32.330  3335  3394 I jxcore-log: ok 204 advertisingActive matches
03-24 15:05:32.330  3335  3394 I jxcore-log: 
03-24 15:05:32.331  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:05:32.331  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.332  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:32.332  3335  3394 I jxcore-log: 
03-24 15:05:32.332  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:32.332  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.333  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 15:05:32.333  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:32.335  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:32.335  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:32.337  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:32.337  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:32.341  3335  3394 I jxcore-log: not ok 205 discoveryActive matches
03-24 15:05:32.341  3335  3394 I jxcore-log: 
,03-24 15:05:32.342  3335  3394 I jxcore-log:   ---
03-24 15:05:32.342  3335  3394 I jxcore-log: 
03-24 15:05:32.342  3335  3394 I jxcore-log:     operator: equal
03-24 15:05:32.342  3335  3394 I jxcore-log: 
03-24 15:05:32.342  3335  3394 I jxcore-log:     expected: false
03-24 15:05:32.342  3335  3394 I jxcore-log: 
03-24 15:05:32.342  3335  3394 I jxcore-log:     actual:   true
03-24 15:05:32.342  3335  3394 I jxcore-log: 
,03-24 15:05:32.342  3335  3394 I jxcore-log:   ...
03-24 15:05:32.342  3335  3394 I jxcore-log: 
03-24 15:05:32.342  3335  3394 I jxcore-log: ok 206 advertisingActive matches
03-24 15:05:32.342  3335  3394 I jxcore-log: 
03-24 15:05:32.344  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:32.344  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:32.344  3335  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 15:05:32.344  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:32.344  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:32.344  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:32.344  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:32.345  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:32.345  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:32.347  2162  3960 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:05:32.348  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:32.349  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:32.349  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:32.349  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:32.349  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:32.349  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.350  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:32.351  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 15:05:32.351  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 15:05:32.351  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:32.352  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:32.352  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.352  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:32.353  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 15:05:32.353  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:32.353  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:32.354  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:32.354  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.357  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:32.357  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:32.357  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:32.357  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:05:32.357  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:05:32.366  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:32.366   823  1246 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:32.372  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 15:05:32.372  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:32.373  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:32.377  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:32.377  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:32.377  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:32.377  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:32.378  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:32.378  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:32.378  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:32.380  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:32.380  3335  3394 I jxcore-log: 
,03-24 15:05:32.381  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:32.381  3335  3394 I jxcore-log: 
,03-24 15:05:32.391  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:32.391  3335  3394 I jxcore-log: 
,03-24 15:05:32.393  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 50720
03-24 15:05:32.393  3335  3394 I jxcore-log: 
,03-24 15:05:32.398  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 50720, start advertisements: true
,03-24 15:05:32.398  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:32.398  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:32.398  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 15:05:32.401  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:05:32.401  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:32.401  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:32.401  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:32.405  2162  3960 D BtGatt.GattService: registerClient() - UUID=2e47c16b-dcfb-43c7-abb9-bf062c3a20bf
,03-24 15:05:32.406  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=2e47c16b-dcfb-43c7-abb9-bf062c3a20bf, clientIf=5
03-24 15:05:32.406  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:32.407  2162  2180 D BtGatt.GattService: start scan with filters
,03-24 15:05:32.408  2162  2238 D BtGatt.ScanManager: handling starting scan
,03-24 15:05:32.409  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:32.410  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 15:05:32.410  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:32.410  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 15:05:32.410  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:32.411  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:32.411  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:32.411  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:32.412  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 15:05:32.412  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:32.412  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:32.412  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:32.412  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.413  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:32.413  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:32.413  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 15:05:32.415  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:32.415  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:32.415  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.416  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
,03-24 15:05:32.417  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.415  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:32.422  2162  2180 D BtGatt.GattService: registerClient() - UUID=2152580d-0b67-4cca-9725-61c286a4ff57
,03-24 15:05:32.423  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=2152580d-0b67-4cca-9725-61c286a4ff57, clientIf=6
03-24 15:05:32.423  3335  3352 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 15:05:32.425  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:32.429  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:05:32.432  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:32.434  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:32.435  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:32.435  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 15:05:32.436   823  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:32.439  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 15:05:32.439  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:32.439  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 15:05:32.439  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:05:32.440  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 15:05:32.440  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:32.440  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 15:05:32.440  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 15:05:32.440  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:32.441  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:32.441  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:32.441  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:32.441  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:32.441  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 15:05:32.441  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:32.441  3335  3335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:32.441  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 15:05:32.442  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:32.442  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:32.442  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:05:32.442  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 15:05:32.442  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:32.442  3335  3394 I jxcore-log: 
03-24 15:05:32.443   823  1297 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:32.444  3335  3964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:32.449  3335  3964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:05:32.451  3335  3394 I jxcore-log: not ok 207 discoveryActive matches
03-24 15:05:32.451  3335  3394 I jxcore-log: 
03-24 15:05:32.452  3335  3394 I jxcore-log:   ---
03-24 15:05:32.452  3335  3394 I jxcore-log: 
03-24 15:05:32.452  3335  3394 I jxcore-log:     operator: equal
03-24 15:05:32.452  3335  3394 I jxcore-log: 
03-24 15:05:32.452  3335  3394 I jxcore-log:     expected: false
03-24 15:05:32.452  3335  3394 I jxcore-log: 
03-24 15:05:32.452  3335  3394 I jxcore-log:     actual:   true
,03-24 15:05:32.452  3335  3394 I jxcore-log: 
03-24 15:05:32.452  3335  3394 I jxcore-log:   ...
03-24 15:05:32.452  3335  3394 I jxcore-log: 
03-24 15:05:32.456  3335  3394 I jxcore-log: not ok 208 advertisingActive matches
03-24 15:05:32.456  3335  3394 I jxcore-log: 
,03-24 15:05:32.457  3335  3394 I jxcore-log:   ---
03-24 15:05:32.457  3335  3394 I jxcore-log: 
03-24 15:05:32.457  3335  3394 I jxcore-log:     operator: equal
03-24 15:05:32.457  3335  3394 I jxcore-log: 
,03-24 15:05:32.457  3335  3394 I jxcore-log:     expected: true
03-24 15:05:32.457  3335  3394 I jxcore-log: 
03-24 15:05:32.457  3335  3394 I jxcore-log:     actual:   false
03-24 15:05:32.457  3335  3394 I jxcore-log: 
03-24 15:05:32.457  3335  3394 I jxcore-log:   ...
,03-24 15:05:32.457  3335  3394 I jxcore-log: 
,03-24 15:05:32.465  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 15:05:32.465  3335  3394 I jxcore-log: 
,03-24 15:05:32.472  3335  3394 I jxcore-log: not ok 209 discoveryActive matches
03-24 15:05:32.472  3335  3394 I jxcore-log: 
,03-24 15:05:32.472  3335  3394 I jxcore-log:   ---
03-24 15:05:32.472  3335  3394 I jxcore-log: 
03-24 15:05:32.472  3335  3394 I jxcore-log:     operator: equal
03-24 15:05:32.472  3335  3394 I jxcore-log: 
03-24 15:05:32.473  3335  3394 I jxcore-log:     expected: false
03-24 15:05:32.473  3335  3394 I jxcore-log: 
,03-24 15:05:32.473  3335  3394 I jxcore-log:     actual:   true
03-24 15:05:32.473  3335  3394 I jxcore-log: 
03-24 15:05:32.473  3335  3394 I jxcore-log:   ...
03-24 15:05:32.473  3335  3394 I jxcore-log: 
,03-24 15:05:32.473  3335  3394 I jxcore-log: ok 210 advertisingActive matches
03-24 15:05:32.473  3335  3394 I jxcore-log: 
03-24 15:05:32.476  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 15:05:32.476  3335  3394 I jxcore-log: 
03-24 15:05:32.478  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 15:05:32.478  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 15:05:32.478  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:05:32.478  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 15:05:32.478  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 15:05:32.480  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:32.480  3335  3964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 15:05:32.480  3335  3964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:05:32.480  3335  3964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:05:32.480  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 15:05:32.481  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:32.481  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 15:05:32.481  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-24 15:05:32.481  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-24 15:05:32.481  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-24 15:05:32.481  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:05:32.481  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-24 15:05:32.481  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 15:05:32.485  2162  3960 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:05:32.488  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:05:32.488  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:32.488  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:32.488  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:32.490  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 15:05:32.490  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:32.490  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:32.490  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 15:05:32.490  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:05:32.490  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:32.490  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 15:05:32.491  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:32.491  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.492  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:32.493  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 15:05:32.494  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:32.494  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:32.494  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:32.498  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 15:05:32.498  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:32.499  2162  3960 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:05:32.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:32.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:32.500  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:32.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:32.500  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 15:05:32.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:32.500  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:32.500  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:32.502  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:32.502  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:32.502  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 15:05:32.502  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:32.502  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:32.503  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:32.503  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:05:32.508  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:32.509   823  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:32.512  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:32.513  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:32.513  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:32.514  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:32.514  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:05:32.514  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:32.517  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 15:05:32.517  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:32.517  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:32.519  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:32.519  3335  3394 I jxcore-log: 
03-24 15:05:32.520  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:32.520  3335  3394 I jxcore-log: 
03-24 15:05:32.521  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:32.521  3335  3394 I jxcore-log: 
,03-24 15:05:32.532  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:32.532  3335  3394 I jxcore-log: 
,03-24 15:05:32.534  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 34304
03-24 15:05:32.534  3335  3394 I jxcore-log: 
,03-24 15:05:32.541  3335  3394 I jxcore-log: # teardown
03-24 15:05:32.541  3335  3394 I jxcore-log: 
,03-24 15:05:32.880  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:32.880  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:32.880  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 15:05:32.883  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 15:05:32.883  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 15:05:32.883  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:32.895  3335  3394 I jxcore-log: # setup
03-24 15:05:32.895  3335  3394 I jxcore-log: 
,03-24 15:05:33.491  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 15:05:33.491  3335  3394 I jxcore-log: 
,03-24 15:05:33.494  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 15:05:33.494  3335  3394 I jxcore-log: ,
,03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 15:05:33.506  3335  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,03-24 15:05:33.511  3335  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 15:05:33.514  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 15:05:33.514  3335  3394 I jxcore-log: 
,03-24 15:05:33.518  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 15:05:33.518  3335  3394 I jxcore-log: 
,03-24 15:05:33.524  3335  3394 I jxcore-log: # 55. can do HTTP requests between peers
03-24 15:05:33.524  3335  3394 I jxcore-log: 
,03-24 15:05:33.528  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 15:05:33.528  3335  3394 I jxcore-log: 
,03-24 15:05:33.689  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:05:33.689  3335  3394 I jxcore-log: 
03-24 15:05:33.691  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 46743
03-24 15:05:33.691  3335  3394 I jxcore-log: 
,03-24 15:05:33.697  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 50720, start advertisements: false
03-24 15:05:33.697  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:33.697  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:33.697  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 15:05:33.702  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:33.702  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:33.702  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 15:05:33.706  2162  3960 D BtGatt.GattService: registerClient() - UUID=678c7984-1b4d-4963-b6bd-b8853c2da3be
,03-24 15:05:33.707  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=678c7984-1b4d-4963-b6bd-b8853c2da3be, clientIf=5
03-24 15:05:33.708  3335  3384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 15:05:33.708  2162  2229 D BtGatt.GattService: start scan with filters
,03-24 15:05:33.709  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 15:05:33.710  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:33.710  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:33.710  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 15:05:33.710  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 15:05:33.710  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:33.710  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 15:05:33.710  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:05:33.716   823  1465 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:33.721  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:05:33.721  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:33.723  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:05:33.723  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 15:05:33.723  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:33.723  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:33.723  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:33.723  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 15:05:33.723  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 15:05:33.723  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 15:05:33.724  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 15:05:33.724  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 15:05:33.726  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:33.726  3335  3394 I jxcore-log: 
03-24 15:05:33.726  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 15:05:33.727  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:33.727  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 15:05:33.727  3335  3394 I jxcore-log: 
03-24 15:05:33.729  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:33.729  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:33.733  3335  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 46743, start advertisements: true
,03-24 15:05:33.733  3335  3394 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 15:05:33.733  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 15:05:33.733  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 15:05:33.737  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 15:05:33.737  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 15:05:33.737  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:33.737  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 15:05:33.738  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:33.738  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:33.738  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:33.738  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:33.743  2162  3960 D BtGatt.GattService: registerClient() - UUID=bacd0989-635f-45f4-aca9-cc9df537974f
,03-24 15:05:33.743  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=bacd0989-635f-45f4-aca9-cc9df537974f, clientIf=6
,03-24 15:05:33.744  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:33.745  2162  2237 D BtGatt.AdvertiseManager: message : 0
,03-24 15:05:33.750  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 15:05:33.753  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:33.755  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 15:05:33.756  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
,03-24 15:05:33.757  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:33.757  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 15:05:33.757  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 15:05:33.757  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:33.757  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 15:05:33.757  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 15:05:33.757   823  1246 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:33.764  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:05:33.764  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 15:05:33.765  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,03-24 15:05:33.765  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 15:05:33.765  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 15:05:33.766  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 15:05:33.766  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 15:05:33.767  3335  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-24 15:05:33.767  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 15:05:33.767  3335  3394 I io.jxcore.node.ConnectionHelper: start: OK
03-24 15:05:33.767  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 15:05:33.767  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:33.767  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 15:05:33.769   823  1310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 15:05:33.770  3335  3966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:33.771  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 15:05:33.771  3335  3394 I jxcore-log: ,
03-24 15:05:33.773  3335  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 15:05:34.739  2162  2162 D BtGatt.ScanManager: awakened up at time 253441
03-24 15:05:34.740  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:34.748  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:05:34.749  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:34.749  2162  2226 D BtGatt.GattService: current time is 253451711620
03-24 15:05:34.749  2162  2226 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -36, -39, 38, 124, 105, 102, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:34.750  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:34.750  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:34.752  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 15:05:34.752  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 15:05:34.752  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 15:05:34.752  3335  3335 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 15:05:34.760  3335  3394 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 15:05:34.760  3335  3394 I jxcore-log: 
,03-24 15:05:34.771  3335  3394 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 15:05:34.771  3335  3394 I jxcore-log: 
,03-24 15:05:34.774  3335  3394 I jxcore-log: ok 211 found a peer! {"peerIdentifier":"E0:DB:10:14:E2:C0","portNumber":36197,"hostAddress":"127.0.0.1"}
03-24 15:05:34.774  3335  3394 I jxcore-log: 
,03-24 15:05:34.794  3335  3394 I jxcore-log: DEBUG createPeerListener: first connection
03-24 15:05:34.794  3335  3394 I jxcore-log: 
,03-24 15:05:34.801  3335  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 15:05:34.801  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 15:05:34.804  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 15:05:34.804  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 15:05:34.804  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 15:05:34.804  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-24 15:05:34.804  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 15:05:34.804  3335  3394 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 15:05:34.808  3335  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 380)
,03-24 15:05:34.808  3335  3968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:34.809  3335  3394 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 15:05:34.809  3335  3394 I jxcore-log: 
,03-24 15:05:34.812  2162  2229 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 15:05:34.828  3335  3394 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 15:05:34.828  3335  3394 I jxcore-log: 
,03-24 15:05:36.434  2162  2239 W bt-btif : No ag scb for peer addr
,03-24 15:05:36.578  2162  2239 W bt-btif : info:x10
03-24 15:05:36.578  2162  2226 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 15:05:36.610  3903  3903 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:05:36.616  3903  3903 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:05:36.707  2162  2239 W bt-sdp  : process_service_search_attr_rsp
,03-24 15:05:39.450  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:39.544  1389  1423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
03-24 15:05:39.545  1389  1423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:05:39.545  1389  1423 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:39.545  1389  1423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:39.558  1389  1423 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:39.580  2162  2224 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 15:05:39.606  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 15:05:39.606  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 15:05:39.607  3755  3755 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,03-24 15:05:39.752  2162  2162 D BtGatt.ScanManager: awakened up at time 258455
,03-24 15:05:39.757  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 15:05:39.761  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 15:05:39.761  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:39.761  2162  2226 D BtGatt.GattService: current time is 258464050680
,03-24 15:05:39.762  2162  2226 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -36, -39, 38, 124, 105, 102, 1, -128, -71, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:39.762  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:39.763  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:39.767  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 15:05:39.768  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 15:05:41.928  2162  2239 W bt-btif : new conn_srvc id:26, app_id:255
03-24 15:05:41.928  2162  2239 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:05:41.928  2162  2239 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 15:05:41.928  3335  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 15:05:41.929  2162  2239 W bt-btif : new conn_srvc id:26, app_id:1
03-24 15:05:41.929  2162  2239 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 15:05:41.929  2162  2239 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 15:05:41.929  2162  2239 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 15:05:41.929  3335  3966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 381)
,03-24 15:05:41.930  3335  3966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 15:05:41.930  3335  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 380)
03-24 15:05:41.930  3335  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 380)
03-24 15:05:41.931   823  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 15:05:41.934  3335  3966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 15:05:41.938  3335  3970 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 381)
,03-24 15:05:41.938  3335  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 382)
,03-24 15:05:41.939  3335  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 382)
03-24 15:05:41.940  3335  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 380)
03-24 15:05:41.940  3335  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 15:05:41.944  3335  3971 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 382),
,03-24 15:05:41.979  3335  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 381)
,03-24 15:05:41.980  3335  3971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 382)
,03-24 15:05:41.982  3335  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:41.984  3335  3971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:41.984  3335  3971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 380)
03-24 15:05:41.984  3335  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 381)
,03-24 15:05:41.985  3335  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 381
03-24 15:05:41.985  3335  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 381)
03-24 15:05:41.985  3335  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:41.985  3335  3970 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 381)
03-24 15:05:41.985  3335  3335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:41.986  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:41.986  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 15:05:41.986  3335  3971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 380)
03-24 15:05:41.986  3335  3335 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 15:05:41.986  3335  3971 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 382)
03-24 15:05:41.986  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 15:05:41.987  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:41.987  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:41.987  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:41.987  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:41.987  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:41.987  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:41.992  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:41.994  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:41.998  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 15:05:41.998  2162  2226 D BtGatt.GattService: Client app is not null!
,03-24 15:05:42.000  2162  3960 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:42.002  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:42.002  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:42.002  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:42.002  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:42.002  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:42.003  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:42.003  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:42.004  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:42.004  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 15:05:42.015  2162  3960 D BtGatt.GattService: registerClient() - UUID=401c4298-3571-4c0d-a9da-d26f91c9c0df
03-24 15:05:42.016  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=401c4298-3571-4c0d-a9da-d26f91c9c0df, clientIf=6
,03-24 15:05:42.017  3335  3384 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:42.018  2162  2237 D BtGatt.AdvertiseManager: message : 0,
,03-24 15:05:42.023  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:05:42.028  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 15:05:42.032  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 15:05:42.032  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:42.034  2162  2179 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:42.036  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:42.037  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:42.037  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:42.037  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:42.037  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:42.037  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:42.037  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:42.040  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 15:05:42.040  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.041  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:42.043  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:42.043  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.043  2162  2229 D BtGatt.GattService: registerClient() - UUID=e0cf6baa-21c3-4646-9b62-bd50974ab74d
,03-24 15:05:42.044  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=e0cf6baa-21c3-4646-9b62-bd50974ab74d, clientIf=5,
03-24 15:05:42.044  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:42.044  3335  3352 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:42.044  2162  3960 D BtGatt.GattService: start scan with filters
03-24 15:05:42.046  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:42.046  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 15:05:42.048  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
03-24 15:05:42.048  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.048  2162  2226 D BtGatt.GattService: current time is 260750713388
03-24 15:05:42.048  2162  2226 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -67, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -36, -39, 38, 124, 105, 102, 1, -128, -72, 45, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -40, 23, -100, 54, 81, 70, 1, -128, -73, 43, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 78, -25, -16, 18, -2, 87, 1, -128, -86, 43, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 110, 69, -93, -117, 44, 65, 1, -128, -86, 22, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 15:05:42.049  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 15:05:42.050  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:42.050  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:42.051  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 15:05:42.051  2162  2226 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 15:05:42.056  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:42.057  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:42.060  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:42.060  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:42.060  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:42.061  2162  2229 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:05:42.061  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:42.061  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:05:42.062  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:42.062  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:42.062  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:42.062  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 15:05:42.062  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:42.062  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:42.062  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:42.063  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:42.063  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.064  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:42.065  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.065  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 15:05:42.065  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:42.066  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:42.067  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.068  2162  2229 D BtGatt.GattService: registerClient() - UUID=4d9c7944-4469-46f9-8978-03dfb4e264e0
,03-24 15:05:42.068  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=4d9c7944-4469-46f9-8978-03dfb4e264e0, clientIf=6
,03-24 15:05:42.068  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:42.068  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.069  3335  3353 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:42.070  2162  2237 D BtGatt.AdvertiseManager: message : 0
03-24 15:05:42.072  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 15:05:42.075  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:42.078  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:42.079  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 15:05:42.080  2162  2229 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 15:05:42.081  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 15:05:42.081  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:42.081  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:05:42.081  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:42.081  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 15:05:42.081  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 15:05:42.081  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:42.082  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:42.082  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.082  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:42.085  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:42.085  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:42.085  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:42.085  2162  2180 D BtGatt.GattService: registerClient() - UUID=c1f23c6c-02ba-4bab-9e23-85103afe6151
03-24 15:05:42.085  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=c1f23c6c-02ba-4bab-9e23-85103afe6151, clientIf=5
03-24 15:05:42.086  3335  3384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:42.086  2162  3960 D BtGatt.GattService: start scan with filters
03-24 15:05:42.086  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:42.086  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.087  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:42.087  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:42.090  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:42.091  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:42.091  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 15:05:42.092  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 15:05:42.092  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.093  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 15:05:42.093  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 15:05:42.094  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:42.094  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:42.095  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:42.095  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:42.096  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 15:05:42.096  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:42.097  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 15:05:42.097  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:42.097  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 15:05:42.097  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 15:05:42.097  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 15:05:42.097  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 15:05:42.097  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 15:05:42.097  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 15:05:42.098  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:42.098  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.100  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 15:05:42.100  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.102  2162  2180 D BtGatt.GattService: registerClient() - UUID=b7b7805c-e9b8-47ed-9c12-aa1c730807e8
03-24 15:05:42.102  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=b7b7805c-e9b8-47ed-9c12-aa1c730807e8, clientIf=6
03-24 15:05:42.102  3335  3352 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 15:05:42.103  2162  2237 D BtGatt.AdvertiseManager: message : 0
03-24 15:05:42.105  2162  2237 D BtGatt.AdvertiseManager: starting multi advertising
03-24 15:05:42.107  2162  2226 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 15:05:42.110  2162  2226 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 15:05:42.110  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 15:05:42.112  2162  3960 D BtGatt.GattService: stopScan() - queue size =1
,03-24 15:05:42.113  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:42.113  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:42.113  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:42.113  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:42.113  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 15:05:42.113  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:42.113  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.113  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 15:05:42.113  3335  3335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 15:05:42.113  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
03-24 15:05:42.116  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:42.116  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.117  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:42.117  2162  2180 D BtGatt.GattService: registerClient() - UUID=4e16b8cb-e267-4a77-8f20-097b22df1c9c
03-24 15:05:42.117  2162  2226 D BtGatt.GattService: onClientRegistered() - UUID=4e16b8cb-e267-4a77-8f20-097b22df1c9c, clientIf=5
03-24 15:05:42.117  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:42.117  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.117  3335  3353 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 15:05:42.118  2162  2179 D BtGatt.GattService: start scan with filters
03-24 15:05:42.118  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 15:05:42.118  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 15:05:42.119  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 15:05:42.119  3335  3335 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 15:05:42.119  3335  3335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:42.119  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:42.119  3335  3335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 15:05:42.119  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 15:05:42.119  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:42.119  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 15:05:42.119  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:42.119  3335  3335 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 15:05:42.121  3335  3335 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 15:05:42.121  3335  3972 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 383)
03-24 15:05:42.121  3335  3335 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 15:05:42.122  3335  3973 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 384)
03-24 15:05:42.122  3335  3973 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36454
03-24 15:05:42.122  3335  3973 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 15:05:42.122  3335  3973 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 36454 (peer ID: E0:DB:10:14:E2:C0)
03-24 15:05:42.122  3335  3973 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 15:05:42.123  2162  2238 D BtGatt.ScanManager: handling starting scan
03-24 15:05:42.126  3335  3972 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 46743
03-24 15:05:42.126  3335  3972 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:05:42.126  3335  3394 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 15:05:42.126  3335  3394 I jxcore-log: 
03-24 15:05:42.126  3335  3972 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:42.126  3335  3972 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:42.127  3335  3972 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 383)
03-24 15:05:42.127  3335  3972 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 383)
03-24 15:05:42.129  2162  2226 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 15:05:42.129  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.130  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 15:05:42.130  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.130  2162  2238 D BtGatt.ScanManager: Starting BLE batch scan
03-24 15:05:42.130  2162  2238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 15:05:42.131  3335  3973 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 36454
03-24 15:05:42.131  3335  3973 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 15:05:42.131  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 15:05:42.131  3335  3394 I jxcore-log: 
03-24 15:05:42.131  3335  3973 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:42.132  2162  2226 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 15:05:42.132  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.133  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:05:42.133  3335  3394 I jxcore-log: 
03-24 15:05:42.133  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 15:05:42.133  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.134  3335  3976 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 386, name: Receiver)
03-24 15:05:42.134  3335  3975 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 385, name: Sender)
03-24 15:05:42.135  3335  3973 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 15:05:42.135  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
03-24 15:05:42.135  3335  3394 I jxcore-log: 
03-24 15:05:42.135  3335  3977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 387, name: Sender)
03-24 15:05:42.136  3335  3973 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 384)
03-24 15:05:42.136  3335  3973 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 384)
03-24 15:05:42.137  3335  3978 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 388, name: Receiver)
03-24 15:05:42.147  3335  3394 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 15:05:42.147  3335  3394 I jxcore-log: 
03-24 15:05:42.149  3335  3394 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 15:05:42.149  3335  3394 I jxcore-log: 
,03-24 15:05:42.182  3335  3394 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 15:05:42.182  3335  3394 I jxcore-log: 
,03-24 15:05:42.326  3335  3394 I jxcore-log: DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
03-24 15:05:42.326  3335  3394 I jxcore-log: 
,03-24 15:05:42.341  3335  3394 I jxcore-log: ok 212 server should return 200
03-24 15:05:42.341  3335  3394 I jxcore-log: 
,03-24 15:05:42.345  3335  3394 I jxcore-log: ok 213 response body should match testData
03-24 15:05:42.345  3335  3394 I jxcore-log: 
,03-24 15:05:42.350  3335  3394 I jxcore-log: # teardown,
03-24 15:05:42.350  3335  3394 I jxcore-log: 
,03-24 15:05:42.452  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 15:05:42.452  3335  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 15:05:42.452  3335  3394 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 384)
03-24 15:05:42.452  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 384)
03-24 15:05:42.453  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:05:42.454  3335  3394 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 15:05:42.454  3335  3978 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 388, thread name: Receiver): bt socket closed, read return: -1
03-24 15:05:42.454  3335  3394 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 388
03-24 15:05:42.454  3335  3978 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 388, name: Receiver),
03-24 15:05:42.454  3335  3394 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 15:05:42.454  3335  3394 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 387
03-24 15:05:42.454  3335  3394 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 384)
03-24 15:05:42.455  3335  3394 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 384)
03-24 15:05:42.455  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 15:05:42.455  3335  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 15:05:42.455  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 15:05:42.456  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 15:05:42.456  3335  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 15:05:42.456  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 15:05:42.456  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 15:05:42.456  3335  3977 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 387, thread name: Sender): Socket closed
03-24 15:05:42.457  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 15:05:42.457  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 15:05:42.457  3335  3977 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 387, name: Sender)
,03-24 15:05:42.457  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 15:05:42.457  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 15:05:42.457  3335  3966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 15:05:42.457  3335  3966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 15:05:42.458  3335  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 15:05:42.460  2162  3960 D BtGatt.GattService: stopScan() - queue size =1
03-24 15:05:42.462  2162  2179 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 15:05:42.463  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 15:05:42.463  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 15:05:42.463  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 15:05:42.463  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 15:05:42.463  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 15:05:42.463  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:42.463  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 15:05:42.465  2162  2237 D BtGatt.AdvertiseManager: message : 1
03-24 15:05:42.465  2162  2237 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 15:05:42.465  2162  2226 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 15:05:42.465  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.466  2162  2238 D BtGatt.ScanManager: stopping BLe Batch
,03-24 15:05:42.468  2162  2226 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 15:05:42.468  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.468  2162  2238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 15:05:42.469  2162  2226 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 15:05:42.469  2162  2226 D BtGatt.GattService: Client app is not null!
03-24 15:05:42.471  2162  2180 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 15:05:42.472  2162  2226 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 15:05:42.472  2162  2226 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 15:05:42.472  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 15:05:42.472  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 15:05:42.472  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 15:05:42.472  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 15:05:42.472  3335  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 15:05:42.473  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 15:05:42.473  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 15:05:42.473  3335  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 15:05:42.474  3335  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 15:05:42.474  3335  3394 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 15:05:42.474  3335  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 15:05:42.475  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 15:05:42.475  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 15:05:42.475  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 15:05:42.481  3335  3335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 15:05:42.481   823  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 15:05:42.489  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 15:05:42.490  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:42.490  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 15:05:42.493  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 15:05:42.493  3335  3335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 15:05:42.493  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 15:05:42.493  3335  3335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 15:05:42.493  3335  3335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 15:05:42.493  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 15:05:42.493  3335  3335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 15:05:42.494  3335  3335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 15:05:42.494  3335  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 15:05:42.494  3335  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 15:05:42.494  3335  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 15:05:42.495  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 15:05:42.495  3335  3394 I jxcore-log: 
03-24 15:05:42.496  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:42.496  3335  3394 I jxcore-log: 
,03-24 15:05:42.497  3335  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 15:05:42.497  3335  3394 I jxcore-log: 
03-24 15:05:42.498  3335  3975 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 385, thread name: Sender)
03-24 15:05:42.499  3335  3975 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 15:05:42.499  3335  3975 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-24 15:05:42.499  3335  3975 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 383
03-24 15:05:42.499  3335  3975 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 383)
03-24 15:05:42.499  3335  3975 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 15:05:42.499  3335  3975 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 15:05:42.499  3335  3975 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 386
03-24 15:05:42.499  3335  3975 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 15:05:42.499  3335  3975 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 385
03-24 15:05:42.499  3335  3975 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 383)
03-24 15:05:42.499  3335  3976 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 386, thread name: Receiver): bt socket closed, read return: -1
03-24 15:05:42.499  3335  3976 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 386, name: Receiver)
03-24 15:05:42.499  3335  3975 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 383)
03-24 15:05:42.499  3335  3975 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 15:05:42.500  3335  3975 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 385, name: Sender)
03-24 15:05:42.504  3335  3394 I jxcore-log: DEBUG createNativeListener: mux close
03-24 15:05:42.504  3335  3394 I jxcore-log: 
,03-24 15:05:42.514  3335  3394 I jxcore-log: # setup
03-24 15:05:42.514  3335  3394 I jxcore-log: 
,03-24 15:05:42.516  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:05:42.516  3335  3394 I jxcore-log: 
03-24 15:05:42.517  3335  3394 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 15:05:42.517  3335  3394 I jxcore-log: 
,03-24 15:05:42.517  3335  3394 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 15:05:42.517  3335  3394 I jxcore-log: 
,03-24 15:05:42.761  2162  2239 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,03-24 15:05:42.767  2162  2239 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,03-24 15:05:42.767  2162  2239 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 15:05:42.887  3335  3394 I jxcore-log: # 56. Test BEACONS_RETRIEVED_AND_PARSED locally,
03-24 15:05:42.887  3335  3394 I jxcore-log: 
,03-24 15:05:43.186  3335  3394 I jxcore-log: ok 214 peerIdentifier should be hello
03-24 15:05:43.186  3335  3394 I jxcore-log: 
03-24 15:05:43.187  3335  3394 I jxcore-log: ok 215 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 15:05:43.187  3335  3394 I jxcore-log: 
,03-24 15:05:43.188  3335  3394 I jxcore-log: ok 216 good beacon
03-24 15:05:43.188  3335  3394 I jxcore-log: 
03-24 15:05:43.189  3335  3394 I jxcore-log: ok 217 good preAmble
03-24 15:05:43.189  3335  3394 I jxcore-log: 
03-24 15:05:43.189  3335  3394 I jxcore-log: ok 218 public keys match!
03-24 15:05:43.189  3335  3394 I jxcore-log: 
,03-24 15:05:43.190  3335  3394 I jxcore-log: ok 219 must return null after successful call
03-24 15:05:43.190  3335  3394 I jxcore-log: 
,03-24 15:05:43.198  3335  3394 I jxcore-log: # teardown
03-24 15:05:43.198  3335  3394 I jxcore-log: 
,03-24 15:05:43.370  3335  3394 I jxcore-log: # setup
,03-24 15:05:43.370  3335  3394 I jxcore-log: 
,03-24 15:05:43.625  3335  3394 I jxcore-log: # 57. Test HTTP_BAD_RESPONSE locally,
03-24 15:05:43.625  3335  3394 I jxcore-log: 
,03-24 15:05:43.800  3335  3394 I jxcore-log: ok 220 Response should be HTTP_BAD_RESPONSE
03-24 15:05:43.800  3335  3394 I jxcore-log: 
03-24 15:05:43.802  3335  3394 I jxcore-log: ok 221 must return null after successful call
03-24 15:05:43.802  3335  3394 I jxcore-log: 
,03-24 15:05:43.816  3335  3394 I jxcore-log: # teardown,
03-24 15:05:43.816  3335  3394 I jxcore-log: 
,03-24 15:05:43.949  3335  3394 I jxcore-log: # setup,
,03-24 15:05:43.949  3335  3394 I jxcore-log: 
,03-24 15:05:44.144  3335  3394 I jxcore-log: # 58. Test NETWORK_PROBLEM locally
03-24 15:05:44.144  3335  3394 I jxcore-log: 
,03-24 15:05:45.702  3335  3394 I jxcore-log: ok 222 Response should be NETWORK_PROBLEM
03-24 15:05:45.702  3335  3394 I jxcore-log: 
,03-24 15:05:45.708  3335  3394 I jxcore-log: ok 223 reject reason should be: Could not establish TCP connection
03-24 15:05:45.708  3335  3394 I jxcore-log: 
,03-24 15:05:45.715  3335  3394 I jxcore-log: # teardown
,03-24 15:05:45.715  3335  3394 I jxcore-log: 
,03-24 15:05:45.848  3335  3394 I jxcore-log: # setup
,03-24 15:05:45.848  3335  3394 I jxcore-log: 
,03-24 15:05:46.783  3335  3394 I jxcore-log: # 59. Test timeout locally,
03-24 15:05:46.783  3335  3394 I jxcore-log: 
,03-24 15:05:47.668  2162  2239 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-24 15:05:47.674  2162  2162 D BluetoothMapService: onReceive,
,03-24 15:05:47.706  3903  3903 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 15:05:47.709  3903  3903 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 15:05:47.921  3335  3394 I jxcore-log: ok 224 Should be NETWORK_PROBLEM caused by timeout
03-24 15:05:47.921  3335  3394 I jxcore-log: 
03-24 15:05:47.927  3335  3394 I jxcore-log: ok 225 reject reason should be Could not establish TCP connection
03-24 15:05:47.927  3335  3394 I jxcore-log: 
,03-24 15:05:47.944  3335  3394 I jxcore-log: # teardown
03-24 15:05:47.944  3335  3394 I jxcore-log: 
,03-24 15:05:48.206  3335  3394 I jxcore-log: # setup
03-24 15:05:48.206  3335  3394 I jxcore-log: 
,03-24 15:05:48.366  3335  3394 I jxcore-log: # 60. Call the start two times
03-24 15:05:48.366  3335  3394 I jxcore-log: 
,03-24 15:05:48.519  3335  3394 I jxcore-log: ok 226 Call start once
03-24 15:05:48.519  3335  3394 I jxcore-log: 
,03-24 15:05:48.568  3335  3394 I jxcore-log: ok 227 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 15:05:48.568  3335  3394 I jxcore-log: 
,03-24 15:05:48.569  3335  3394 I jxcore-log: ok 228 must return null after successful call.
03-24 15:05:48.569  3335  3394 I jxcore-log: 
,03-24 15:05:48.578  3335  3394 I jxcore-log: # teardown
03-24 15:05:48.578  3335  3394 I jxcore-log: 
,03-24 15:05:48.695  3335  3394 I jxcore-log: # setup
03-24 15:05:48.695  3335  3394 I jxcore-log: 
,03-24 15:05:48.884  3335  3394 I jxcore-log: # 61. Call the kill before calling the start
03-24 15:05:48.884  3335  3394 I jxcore-log: 
,03-24 15:05:49.064  3335  3394 I jxcore-log: ok 229 Should be Killed
03-24 15:05:49.064  3335  3394 I jxcore-log: ,
,03-24 15:05:49.074  3335  3394 I jxcore-log: ok 230 Start after killed
03-24 15:05:49.074  3335  3394 I jxcore-log: 
,03-24 15:05:49.092  3335  3394 I jxcore-log: # teardown
03-24 15:05:49.092  3335  3394 I jxcore-log: 
,03-24 15:05:49.175  3335  3394 I jxcore-log: # setup
03-24 15:05:49.175  3335  3394 I jxcore-log: 
,03-24 15:05:49.394  3335  3394 I jxcore-log: # 62. Call the kill immediately after the start
03-24 15:05:49.394  3335  3394 I jxcore-log: 
,03-24 15:05:49.777  3335  3394 I jxcore-log: ok 231 Should be KILLED
03-24 15:05:49.777  3335  3394 I jxcore-log: 
,03-24 15:05:49.782  3335  3394 I jxcore-log: ok 232 must return null after successful kill
03-24 15:05:49.782  3335  3394 I jxcore-log: 
,03-24 15:05:49.793  3335  3394 I jxcore-log: # teardown
03-24 15:05:49.793  3335  3394 I jxcore-log: 
,03-24 15:05:49.890  3335  3394 I jxcore-log: # setup
03-24 15:05:49.890  3335  3394 I jxcore-log: 
,03-24 15:05:50.564  3335  3394 I jxcore-log: # 63. Call the kill while waiting a response from the server
03-24 15:05:50.564  3335  3394 I jxcore-log: 
,03-24 15:05:52.693  3335  3394 I jxcore-log: ok 233 Should be KILLED
03-24 15:05:52.693  3335  3394 I jxcore-log: 
,03-24 15:05:52.697  3335  3394 I jxcore-log: ok 234 must return null after successful kill
03-24 15:05:52.697  3335  3394 I jxcore-log: 
,03-24 15:05:52.710  3335  3394 I jxcore-log: # teardown
03-24 15:05:52.710  3335  3394 I jxcore-log: 
,03-24 15:05:52.841  3335  3394 I jxcore-log: # setup
03-24 15:05:52.841  3335  3394 I jxcore-log: 
,03-24 15:05:53.034  3443  3981 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 15:05:53.036  3335  3394 I jxcore-log: # 64. Test to exceed the max content size locally
03-24 15:05:53.036  3335  3394 I jxcore-log: 
,03-24 15:05:53.097  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 15:05:53.098  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:05:53.098  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:53.098  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:53.103  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:05:53.136  3443  3981 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.,
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 15:05:53.138  3443  3981 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 15:05:53.372  3335  3394 I jxcore-log: ok 235 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-24 15:05:53.372  3335  3394 I jxcore-log: 
,03-24 15:05:53.376  3335  3394 I jxcore-log: ok 236 must return null after successful call
03-24 15:05:53.376  3335  3394 I jxcore-log: 
,03-24 15:05:53.386  3335  3394 I jxcore-log: # teardown
03-24 15:05:53.386  3335  3394 I jxcore-log: 
,03-24 15:05:53.532  3335  3394 I jxcore-log: # setup
03-24 15:05:53.532  3335  3394 I jxcore-log: 
,03-24 15:05:53.783  3335  3394 I jxcore-log: # 65. Close the server socket while the client is waiting a response from the server. Local test.
03-24 15:05:53.783  3335  3394 I jxcore-log: 
,03-24 15:05:55.904  3335  3394 I jxcore-log: ok 237 Should be NETWORK_PROBLEM caused closing server socket
03-24 15:05:55.904  3335  3394 I jxcore-log: 
,03-24 15:05:55.922  3335  3394 I jxcore-log: ok 238 Should be Could not establish TCP connection
03-24 15:05:55.922  3335  3394 I jxcore-log: 
,03-24 15:05:55.931  3335  3394 I jxcore-log: # teardown
03-24 15:05:55.931  3335  3394 I jxcore-log: 
,03-24 15:05:56.100  3335  3394 I jxcore-log: # setup
03-24 15:05:56.100  3335  3394 I jxcore-log: 
,03-24 15:05:56.297  3335  3394 I jxcore-log: # 66. Close the client socket while the client is waiting a response from the server. Local test.
03-24 15:05:56.297  3335  3394 I jxcore-log: 
,03-24 15:05:57.325  3335  3335 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-24 15:05:57.325  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:57.326  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:57.327  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 15:05:57.328  3335  3335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 15:05:57.966  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:05:58.453  3335  3394 I jxcore-log: ok 239 Should be NETWORK_PROBLEM caused closing client socket
03-24 15:05:58.453  3335  3394 I jxcore-log: 
,03-24 15:05:58.460  3335  3394 I jxcore-log: ok 240 Should be Could not establish TCP connection
03-24 15:05:58.460  3335  3394 I jxcore-log: 
,03-24 15:05:58.475  3335  3394 I jxcore-log: # teardown
03-24 15:05:58.475  3335  3394 I jxcore-log: 
,03-24 15:05:58.643  3335  3394 I jxcore-log: # setup
03-24 15:05:58.643  3335  3394 I jxcore-log: 
,03-24 15:05:58.772  3335  3394 I jxcore-log: # 67. #generatePreambleAndBeacons bad args
03-24 15:05:58.772  3335  3394 I jxcore-log: 
,03-24 15:05:58.963  3335  3394 I jxcore-log: ok 241 publicKeysToNotify cannot be null
03-24 15:05:58.963  3335  3394 I jxcore-log: 
,03-24 15:05:58.965  3335  3394 I jxcore-log: ok 242 ecdh for local device cannot be null
03-24 15:05:58.965  3335  3394 I jxcore-log: 
,03-24 15:05:58.967  3335  3394 I jxcore-log: ok 243 milliseconds cannot be less than 0
03-24 15:05:58.967  3335  3394 I jxcore-log: 
,03-24 15:05:58.969  3335  3394 I jxcore-log: ok 244 milliseconds cannot be 0
03-24 15:05:58.969  3335  3394 I jxcore-log: 
,03-24 15:05:58.970  3335  3394 I jxcore-log: ok 245 milliseconds cannot be greater than one_day
03-24 15:05:58.970  3335  3394 I jxcore-log: 
,03-24 15:05:58.973  3335  3394 I jxcore-log: # teardown
03-24 15:05:58.973  3335  3394 I jxcore-log: 
,03-24 15:05:59.085  3335  3394 I jxcore-log: # setup
03-24 15:05:59.085  3335  3394 I jxcore-log: 
,03-24 15:05:59.233  3335  3394 I jxcore-log: # 68. #generatePreambleAndBeacons empty keys to notify
03-24 15:05:59.233  3335  3394 I jxcore-log: 
,03-24 15:05:59.359  3335  3394 I jxcore-log: ok 246 should be equal
03-24 15:05:59.359  3335  3394 I jxcore-log: 
,03-24 15:05:59.362  3335  3394 I jxcore-log: # teardown
03-24 15:05:59.362  3335  3394 I jxcore-log: 
,03-24 15:05:59.525  3335  3394 I jxcore-log: # setup
03-24 15:05:59.525  3335  3394 I jxcore-log: 
,03-24 15:05:59.688   823  1009 I art     : Explicit concurrent mark sweep GC freed 28727(1376KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.351ms total 71.818ms
,03-24 15:05:59.735  3335  3394 I jxcore-log: # 69. #generatePreambleAndBeacons multiple keys to notify
03-24 15:05:59.735  3335  3394 I jxcore-log: 
,03-24 15:05:59.898  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:59.934  1389  1427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 15:05:59.934  1389  1427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:05:59.934  1389  1427 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:05:59.934  1389  1427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:05:59.936  3335  3394 I jxcore-log: ok 247 should be equal,
03-24 15:05:59.936  3335  3394 I jxcore-log: 
03-24 15:05:59.937  3335  3394 I jxcore-log: ok 248 should be equal
03-24 15:05:59.937  3335  3394 I jxcore-log: 
,03-24 15:05:59.939  3335  3394 I jxcore-log: ok 249 (unnamed assert)
03-24 15:05:59.939  3335  3394 I jxcore-log: 
,03-24 15:05:59.939  3335  3394 I jxcore-log: ok 250 should be equal
03-24 15:05:59.939  3335  3394 I jxcore-log: 
,03-24 15:05:59.942  1389  1427 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:05:59.944  3335  3394 I jxcore-log: # teardown
03-24 15:05:59.944  3335  3394 I jxcore-log: 
,03-24 15:05:59.974  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 15:05:59.975  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 15:05:59.976  3755  3755 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 15:06:00.113  3335  3394 I jxcore-log: # setup
03-24 15:06:00.113  3335  3394 I jxcore-log: 
,03-24 15:06:00.219  3335  3394 I jxcore-log: # 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-24 15:06:00.219  3335  3394 I jxcore-log: 
,03-24 15:06:00.370  3335  3394 I jxcore-log: ok 251 should throw
03-24 15:06:00.370  3335  3394 I jxcore-log: 
,03-24 15:06:00.373  3335  3394 I jxcore-log: # teardown
03-24 15:06:00.373  3335  3394 I jxcore-log: 
,03-24 15:06:00.563  3335  3394 I jxcore-log: # setup
03-24 15:06:00.563  3335  3394 I jxcore-log: 
,03-24 15:06:00.660  3335  3394 I jxcore-log: # 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-24 15:06:00.660  3335  3394 I jxcore-log: 
,03-24 15:06:00.789  3335  3394 I jxcore-log: ok 252 Preamble expiration must be a 64 bit integer
03-24 15:06:00.789  3335  3394 I jxcore-log: 
,03-24 15:06:00.792  3335  3394 I jxcore-log: # teardown
03-24 15:06:00.792  3335  3394 I jxcore-log: 
,03-24 15:06:00.920  3335  3394 I jxcore-log: # setup
03-24 15:06:00.920  3335  3394 I jxcore-log: 
,03-24 15:06:01.037  3335  3394 I jxcore-log: # 72. #parseBeacons expiration out of range lower
03-24 15:06:01.037  3335  3394 I jxcore-log: 
,03-24 15:06:01.254  3335  3394 I jxcore-log: ok 253 Expiration out of range
03-24 15:06:01.254  3335  3394 I jxcore-log: 
,03-24 15:06:01.257  3335  3394 I jxcore-log: # teardown
03-24 15:06:01.257  3335  3394 I jxcore-log: 
,03-24 15:06:01.384  3335  3394 I jxcore-log: # setup
03-24 15:06:01.384  3335  3394 I jxcore-log: 
,03-24 15:06:01.490  3335  3394 I jxcore-log: # 73. #parseBeacons expiration out of range lower
03-24 15:06:01.490  3335  3394 I jxcore-log: 
,03-24 15:06:01.702  3335  3394 I jxcore-log: ok 254 Expiration out of range
03-24 15:06:01.702  3335  3394 I jxcore-log: 
,03-24 15:06:01.714  3335  3394 I jxcore-log: # teardown
03-24 15:06:01.714  3335  3394 I jxcore-log: 
,03-24 15:06:01.866  3335  3394 I jxcore-log: # setup
03-24 15:06:01.866  3335  3394 I jxcore-log: 
,03-24 15:06:02.085  3335  3394 I jxcore-log: # 74. #parseBeacons no beacons returns null
03-24 15:06:02.085  3335  3394 I jxcore-log: 
,03-24 15:06:02.268  3335  3394 I jxcore-log: ok 255 should be equal
03-24 15:06:02.268  3335  3394 I jxcore-log: 
,03-24 15:06:02.270  3335  3394 I jxcore-log: # teardown
03-24 15:06:02.270  3335  3394 I jxcore-log: 
,03-24 15:06:02.409  3335  3394 I jxcore-log: # setup
03-24 15:06:02.409  3335  3394 I jxcore-log: 
,03-24 15:06:02.563  3335  3394 I jxcore-log: # 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-24 15:06:02.563  3335  3394 I jxcore-log: 
,03-24 15:06:02.730  3335  3394 I jxcore-log: ok 256 Malformed encrypted beacon key ID
03-24 15:06:02.730  3335  3394 I jxcore-log: 
,03-24 15:06:02.733  3335  3394 I jxcore-log: # teardown
03-24 15:06:02.733  3335  3394 I jxcore-log: 
,03-24 15:06:02.891  3335  3394 I jxcore-log: # setup
03-24 15:06:02.891  3335  3394 I jxcore-log: 
,03-24 15:06:03.048  3335  3394 I jxcore-log: # 76. #parseBeacons addressBookCallback fails decrypt
03-24 15:06:03.048  3335  3394 I jxcore-log: 
,03-24 15:06:03.321  3335  3394 I jxcore-log: ok 257 should be equal
03-24 15:06:03.321  3335  3394 I jxcore-log: 
,03-24 15:06:03.323  3335  3394 I jxcore-log: # teardown
03-24 15:06:03.323  3335  3394 I jxcore-log: 
,03-24 15:06:03.510  3335  3394 I jxcore-log: # setup
03-24 15:06:03.510  3335  3394 I jxcore-log: 
,03-24 15:06:03.691  3335  3394 I jxcore-log: # 77. #parseBeacons addressBookCallback returns no matches
03-24 15:06:03.691  3335  3394 I jxcore-log: 
,03-24 15:06:03.993  3335  3394 I jxcore-log: ok 258 should be equal
03-24 15:06:03.993  3335  3394 I jxcore-log: 
,03-24 15:06:03.994  3335  3394 I jxcore-log: ok 259 should be equal
03-24 15:06:03.994  3335  3394 I jxcore-log: 
,03-24 15:06:03.996  3335  3394 I jxcore-log: # teardown
03-24 15:06:03.996  3335  3394 I jxcore-log: 
,03-24 15:06:04.127  3335  3394 I jxcore-log: # setup
03-24 15:06:04.127  3335  3394 I jxcore-log: 
,03-24 15:06:04.283  3335  3394 I jxcore-log: # 78. #parseBeacons addressBookCallback returns spurious match
03-24 15:06:04.283  3335  3394 I jxcore-log: 
,03-24 15:06:04.527  3335  3394 I jxcore-log: ok 260 should be equal
03-24 15:06:04.527  3335  3394 I jxcore-log: ,
03-24 15:06:04.528  3335  3394 I jxcore-log: ok 261 should be equal
03-24 15:06:04.528  3335  3394 I jxcore-log: 
,03-24 15:06:04.530  3335  3394 I jxcore-log: # teardown
03-24 15:06:04.530  3335  3394 I jxcore-log: 
,03-24 15:06:07.183  3335  3394 I jxcore-log: # setup
03-24 15:06:07.183  3335  3394 I jxcore-log: 
,03-24 15:06:07.268  3335  3394 I jxcore-log: # 79. #parseBeacons addressBookCallback returns public key
03-24 15:06:07.268  3335  3394 I jxcore-log: 
,03-24 15:06:07.905  3335  3394 I jxcore-log: ok 262 right number of calls to address book
03-24 15:06:07.905  3335  3394 I jxcore-log: 
,03-24 15:06:07.906  3335  3394 I jxcore-log: ok 263 good preAmble
03-24 15:06:07.906  3335  3394 I jxcore-log: 
03-24 15:06:07.906  3335  3394 I jxcore-log: ok 264 good unencryptedKeyId
03-24 15:06:07.906  3335  3394 I jxcore-log: 
,03-24 15:06:07.907  3335  3394 I jxcore-log: ok 265 good beacon,
03-24 15:06:07.907  3335  3394 I jxcore-log: 
,03-24 15:06:07.909  3335  3394 I jxcore-log: # teardown
03-24 15:06:07.909  3335  3394 I jxcore-log: 
,03-24 15:06:08.045  3335  3394 I jxcore-log: # setup
03-24 15:06:08.045  3335  3394 I jxcore-log: 
,03-24 15:06:08.240  3335  3394 I jxcore-log: # 80. validate generatePskIdentityField
03-24 15:06:08.240  3335  3394 I jxcore-log: 
,03-24 15:06:08.391  3335  3394 I jxcore-log: ok 266 decoded buffers match
03-24 15:06:08.391  3335  3394 I jxcore-log: 
,03-24 15:06:08.399  3335  3394 I jxcore-log: # teardown
03-24 15:06:08.399  3335  3394 I jxcore-log: 
,03-24 15:06:08.553  3335  3394 I jxcore-log: # setup
03-24 15:06:08.553  3335  3394 I jxcore-log: 
,03-24 15:06:08.635  3335  3394 I jxcore-log: # 81. validate generatePskSecret
03-24 15:06:08.635  3335  3394 I jxcore-log: 
,03-24 15:06:08.780  3335  3394 I jxcore-log: ok 267 secrets match
03-24 15:06:08.780  3335  3394 I jxcore-log: 
,03-24 15:06:08.782  3335  3394 I jxcore-log: # teardown
03-24 15:06:08.782  3335  3394 I jxcore-log: 
,03-24 15:06:08.895  3335  3394 I jxcore-log: # setup
03-24 15:06:08.895  3335  3394 I jxcore-log: 
,03-24 15:06:09.097  3335  3394 I jxcore-log: # 82. Start and stop ThaliNotificationServer
03-24 15:06:09.097  3335  3394 I jxcore-log: 
,03-24 15:06:09.286  3335  3394 I jxcore-log: ok 268 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-24 15:06:09.286  3335  3394 I jxcore-log: 
,03-24 15:06:09.287  3335  3394 I jxcore-log: ok 269 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-24 15:06:09.287  3335  3394 I jxcore-log: 
03-24 15:06:09.288  3335  3394 I jxcore-log: # teardown
03-24 15:06:09.288  3335  3394 I jxcore-log: 
,03-24 15:06:09.386  3335  3394 I jxcore-log: # setup
03-24 15:06:09.386  3335  3394 I jxcore-log: 
,03-24 15:06:09.600  3335  3394 I jxcore-log: # 83. Pass an empty array to ThaliNotificationServer.start
03-24 15:06:09.600  3335  3394 I jxcore-log: 
,03-24 15:06:09.795  3335  3394 I jxcore-log: ok 270 StartUpdateAdvertisingAndListening should not be called
03-24 15:06:09.795  3335  3394 I jxcore-log: 
,03-24 15:06:09.809  3335  3394 I jxcore-log: ok 271 ThaliMobile.StopAdvertisingAndListening should be called once
03-24 15:06:09.809  3335  3394 I jxcore-log: 
,03-24 15:06:09.851  3335  3394 I jxcore-log: ok 272 no error
03-24 15:06:09.851  3335  3394 I jxcore-log: 
,03-24 15:06:09.852  3335  3394 I jxcore-log: ok 273 should be 204
03-24 15:06:09.852  3335  3394 I jxcore-log: 
,03-24 15:06:09.857  3335  3394 I jxcore-log: # teardown
03-24 15:06:09.857  3335  3394 I jxcore-log: 
,03-24 15:06:09.970  3335  3394 I jxcore-log: # setup
03-24 15:06:09.970  3335  3394 I jxcore-log: 
,03-24 15:06:10.151  3335  3394 I jxcore-log: # 84. Pass a string to ThaliNotificationServer.start
03-24 15:06:10.151  3335  3394 I jxcore-log: 
,03-24 15:06:10.267  3335  3394 I jxcore-log: ok 274 StartUpdateAdvertisingAndListening should not be called
03-24 15:06:10.267  3335  3394 I jxcore-log: 
,03-24 15:06:10.273  3335  3394 I jxcore-log: # teardown
03-24 15:06:10.273  3335  3394 I jxcore-log: 
,03-24 15:06:10.410  3335  3394 I jxcore-log: # setup
03-24 15:06:10.410  3335  3394 I jxcore-log: 
,03-24 15:06:10.582  3335  3394 I jxcore-log: # 85. Pass an empty parameter to ThaliNotificationServer.start
03-24 15:06:10.582  3335  3394 I jxcore-log: 
,03-24 15:06:10.727  3335  3394 I jxcore-log: ok 275 StartUpdateAdvertisingAndListening should not be called
03-24 15:06:10.727  3335  3394 I jxcore-log: 
,03-24 15:06:10.732  3335  3394 I jxcore-log: # teardown
03-24 15:06:10.732  3335  3394 I jxcore-log: 
,03-24 15:06:10.887  3335  3394 I jxcore-log: # setup
03-24 15:06:10.887  3335  3394 I jxcore-log: 
,03-24 15:06:11.036  3335  3394 I jxcore-log: # 86. Make an HTTP request to /NotificationBeacons
03-24 15:06:11.036  3335  3394 I jxcore-log: ,
,03-24 15:06:11.219  3335  3394 I jxcore-log: ok 276 no error
03-24 15:06:11.219  3335  3394 I jxcore-log: 
,03-24 15:06:11.219  3335  3394 I jxcore-log: ok 277 should be 200
03-24 15:06:11.219  3335  3394 I jxcore-log: 
03-24 15:06:11.219  3335  3394 I jxcore-log: ok 278 should be equal
03-24 15:06:11.219  3335  3394 I jxcore-log: 
03-24 15:06:11.219  3335  3394 I jxcore-log: ok 279 should be equal
03-24 15:06:11.219  3335  3394 I jxcore-log: 
,03-24 15:06:11.237  3335  3394 I jxcore-log: ok 280 (unnamed assert)
03-24 15:06:11.237  3335  3394 I jxcore-log: 
,03-24 15:06:11.263  3335  3394 I jxcore-log: ok 281 no error
03-24 15:06:11.263  3335  3394 I jxcore-log: 
,03-24 15:06:11.263  3335  3394 I jxcore-log: ok 282 should be 204
03-24 15:06:11.263  3335  3394 I jxcore-log: 
,03-24 15:06:11.269  3335  3394 I jxcore-log: # teardown
03-24 15:06:11.269  3335  3394 I jxcore-log: 
,03-24 15:06:11.442  3335  3394 I jxcore-log: # setup
03-24 15:06:11.442  3335  3394 I jxcore-log: 
,03-24 15:06:11.591  3335  3394 I jxcore-log: # 87. Make an HTTP request to /NotificationBeacons (no keys)
03-24 15:06:11.591  3335  3394 I jxcore-log: 
,03-24 15:06:11.759  3335  3394 I jxcore-log: ok 283 error should be null
03-24 15:06:11.759  3335  3394 I jxcore-log: ,
03-24 15:06:11.760  3335  3394 I jxcore-log: ok 284 should be 204
03-24 15:06:11.760  3335  3394 I jxcore-log: 
,03-24 15:06:11.767  3335  3394 I jxcore-log: # teardown
03-24 15:06:11.767  3335  3394 I jxcore-log: 
,03-24 15:06:11.881  3335  3394 I jxcore-log: # setup
03-24 15:06:11.881  3335  3394 I jxcore-log: 
,03-24 15:06:12.054  3335  3394 I jxcore-log: # 88. Make an HTTP request to /NotificationBeaconsbefore calling start
03-24 15:06:12.054  3335  3394 I jxcore-log: 
,03-24 15:06:12.230  3335  3394 I jxcore-log: ok 285 should be 404
03-24 15:06:12.230  3335  3394 I jxcore-log: 
,03-24 15:06:12.236  3335  3394 I jxcore-log: # teardown
03-24 15:06:12.236  3335  3394 I jxcore-log: 
,03-24 15:06:12.337  3335  3394 I jxcore-log: # setup
03-24 15:06:12.337  3335  3394 I jxcore-log: 
,03-24 15:06:12.508  3335  3394 I jxcore-log: # 89. #testThaliPeerAction - test getters
03-24 15:06:12.508  3335  3394 I jxcore-log: 
,03-24 15:06:12.630  3335  3394 I jxcore-log: ok 286 getPeerIdentifier
03-24 15:06:12.630  3335  3394 I jxcore-log: 
,03-24 15:06:12.633  3335  3394 I jxcore-log: ok 287 getConnectionType
03-24 15:06:12.633  3335  3394 I jxcore-log: 
,03-24 15:06:12.635  3335  3394 I jxcore-log: ok 288 getActionType
03-24 15:06:12.635  3335  3394 I jxcore-log: 
,03-24 15:06:12.638  3335  3394 I jxcore-log: ok 289 getActionState
03-24 15:06:12.638  3335  3394 I jxcore-log: 
,03-24 15:06:12.642  3335  3394 I jxcore-log: # teardown
03-24 15:06:12.642  3335  3394 I jxcore-log: 
,03-24 15:06:12.814  3335  3394 I jxcore-log: # setup
03-24 15:06:12.814  3335  3394 I jxcore-log: 
,03-24 15:06:12.933  3335  3394 I jxcore-log: # 90. #testThaliPeerAction - start and kill
03-24 15:06:12.933  3335  3394 I jxcore-log: 
,03-24 15:06:13.122  3335  3394 I jxcore-log: ok 290 initial state
03-24 15:06:13.122  3335  3394 I jxcore-log: 
,03-24 15:06:13.128  3335  3394 I jxcore-log: ok 291 after start
03-24 15:06:13.128  3335  3394 I jxcore-log: 
,03-24 15:06:13.130  3335  3394 I jxcore-log: ok 292 after kill
03-24 15:06:13.130  3335  3394 I jxcore-log: 
,03-24 15:06:13.139  3335  3394 I jxcore-log: # teardown
03-24 15:06:13.139  3335  3394 I jxcore-log: 
,03-24 15:06:13.269  3335  3394 I jxcore-log: # setup
03-24 15:06:13.269  3335  3394 I jxcore-log: 
,03-24 15:06:13.499  3335  3394 I jxcore-log: # 91. #testThaliPeerAction - double start
03-24 15:06:13.499  3335  3394 I jxcore-log: 
,03-24 15:06:13.622  3335  3394 I jxcore-log: ok 293 should be equal
03-24 15:06:13.622  3335  3394 I jxcore-log: 
,03-24 15:06:13.624  3335  3394 I jxcore-log: # teardown
,03-24 15:06:13.624  3335  3394 I jxcore-log: 
,03-24 15:06:13.784  3335  3394 I jxcore-log: # setup
03-24 15:06:13.784  3335  3394 I jxcore-log: 
,03-24 15:06:13.926  3335  3394 I jxcore-log: # 92. #testThaliPeerAction - start after kill
03-24 15:06:13.926  3335  3394 I jxcore-log: 
,03-24 15:06:14.047  3335  3394 I jxcore-log: ok 294 clean kill
03-24 15:06:14.047  3335  3394 I jxcore-log: 
,03-24 15:06:14.050  3335  3394 I jxcore-log: ok 295 should be equal,
03-24 15:06:14.050  3335  3394 I jxcore-log: 
03-24 15:06:14.053  3335  3394 I jxcore-log: # teardown
03-24 15:06:14.053  3335  3394 I jxcore-log: ,
,03-24 15:06:14.060  3542  3988 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 15:06:14.081  3542  3989 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430),
,03-24 15:06:14.133  1389  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 15:06:14.133  1389  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:14.133  1389  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:14.133  1389  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:14.141  1389  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:06:14.179  3335  3394 I jxcore-log: # setup
03-24 15:06:14.179  3335  3394 I jxcore-log: 
,03-24 15:06:14.208  1389  1734 I art     : Explicit concurrent mark sweep GC freed 42803(2MB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 26MB/42MB, paused 1.441ms total 58.993ms
,03-24 15:06:14.315  3335  3394 I jxcore-log: # 93. #testThaliPeerAction - make sure ids are unique
03-24 15:06:14.315  3335  3394 I jxcore-log: 
,03-24 15:06:14.337  1389  1427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 15:06:14.337  1389  1427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:14.337  1389  1427 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:14.338  1389  1427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:14.346  1389  1427 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 15:06:14.378  3542  3989 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 15:06:14.382  3542  3988 E BooksSync: Soft error
03-24 15:06:14.382  3542  3988 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:06:14.382  3542  3988 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 15:06:14.382  3542  3988 E BooksSync: Sync error
03-24 15:06:14.382  3542  3988 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 15:06:14.382  3542  3988 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 15:06:14.382  3542  3988 I BooksSync: Finished books sync
,03-24 15:06:14.405   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 292658, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 15:06:14.515  3335  3394 I jxcore-log: ok 296 should not be equal,
03-24 15:06:14.515  3335  3394 I jxcore-log: 
,03-24 15:06:14.523  3335  3394 I jxcore-log: # teardown
03-24 15:06:14.523  3335  3394 I jxcore-log: 
,03-24 15:06:14.643  3335  3394 I jxcore-log: # setup
03-24 15:06:14.643  3335  3394 I jxcore-log: 
,03-24 15:06:14.790  3335  3394 I jxcore-log: # 94. Test PeerConnectionInformation basics
,03-24 15:06:14.790  3335  3394 I jxcore-log: 
,03-24 15:06:14.904  3335  3394 I jxcore-log: ok 297 getHostAddress works
,03-24 15:06:14.904  3335  3394 I jxcore-log: 
03-24 15:06:14.905  3335  3394 I jxcore-log: ok 298 getPortNumber works
03-24 15:06:14.905  3335  3394 I jxcore-log: 
,03-24 15:06:14.907  3335  3394 I jxcore-log: ok 299 getSuggestedTCPTimeout works
03-24 15:06:14.907  3335  3394 I jxcore-log: 
,03-24 15:06:14.913  3335  3394 I jxcore-log: # teardown
03-24 15:06:14.913  3335  3394 I jxcore-log: ,
,03-24 15:06:15.420  3335  3394 I jxcore-log: # setup
03-24 15:06:15.420  3335  3394 I jxcore-log: 
,03-24 15:06:15.534  3335  3394 I jxcore-log: # 95. Test PeerDictionary basic functionality
03-24 15:06:15.534  3335  3394 I jxcore-log: 
,03-24 15:06:15.753  3335  3394 I jxcore-log: ok 300 Entry counter must be 1
03-24 15:06:15.753  3335  3394 I jxcore-log: ,
03-24 15:06:15.753  3335  3394 I jxcore-log: ok 301 Size must be 1
03-24 15:06:15.753  3335  3394 I jxcore-log: 
03-24 15:06:15.753  3335  3394 I jxcore-log: ok 302 Entry counter must be 2
03-24 15:06:15.753  3335  3394 I jxcore-log: 
03-24 15:06:15.754  3335  3394 I jxcore-log: ok 303 Size must be 2
03-24 15:06:15.754  3335  3394 I jxcore-log: 
,03-24 15:06:15.760  3335  3394 I jxcore-log: ok 304 Entry2 should not be found
03-24 15:06:15.760  3335  3394 I jxcore-log: 
,03-24 15:06:15.760  3335  3394 I jxcore-log: ok 305 Size must be 1
03-24 15:06:15.760  3335  3394 I jxcore-log: 
03-24 15:06:15.760  3335  3394 I jxcore-log: ok 306 Size must be 0
03-24 15:06:15.760  3335  3394 I jxcore-log: 
,03-24 15:06:15.764  3335  3394 I jxcore-log: ok 307 entry not found must be thrown
03-24 15:06:15.764  3335  3394 I jxcore-log: 
,03-24 15:06:15.767  3335  3394 I jxcore-log: # teardown
03-24 15:06:15.767  3335  3394 I jxcore-log: 
,03-24 15:06:15.990  3335  3394 I jxcore-log: # setup
03-24 15:06:15.990  3335  3394 I jxcore-log: 
,03-24 15:06:16.169  3335  3394 I jxcore-log: # 96. Test PeerDictionary with multiple entries.
03-24 15:06:16.169  3335  3394 I jxcore-log: 
,03-24 15:06:17.017  3335  3394 I jxcore-log: ok 308 Size must be100
03-24 15:06:17.017  3335  3394 I jxcore-log: 
,03-24 15:06:17.026  3335  3394 I jxcore-log: ok 309 Entries between 20 and MAXSIZE + 20 should exist
03-24 15:06:17.026  3335  3394 I jxcore-log: 
,03-24 15:06:17.762  3335  3394 I jxcore-log: ok 310 WAITING state entry should not be removed
03-24 15:06:17.762  3335  3394 I jxcore-log: 
,03-24 15:06:17.764  3335  3394 I jxcore-log: # teardown
03-24 15:06:17.764  3335  3394 I jxcore-log: 
,03-24 15:06:17.869  3335  3394 I jxcore-log: # setup
03-24 15:06:17.869  3335  3394 I jxcore-log: 
,03-24 15:06:18.447  3335  3394 I jxcore-log: # 97. RESOLVED entries are removed before WAITING state entry.
03-24 15:06:18.447  3335  3394 I jxcore-log: 
,03-24 15:06:19.278  3335  3394 I jxcore-log: ok 311 Entries between 6 and MAXSIZE + 4 should exist
03-24 15:06:19.278  3335  3394 I jxcore-log: 
,03-24 15:06:19.279  3335  3394 I jxcore-log: ok 312 Size should be MAXSIZE
03-24 15:06:19.279  3335  3394 I jxcore-log: 
03-24 15:06:19.279  3335  3394 I jxcore-log: ok 313 Size should be MAXSIZE+6
03-24 15:06:19.279  3335  3394 I jxcore-log: 
,03-24 15:06:19.281  3335  3394 I jxcore-log: # teardown
03-24 15:06:19.281  3335  3394 I jxcore-log: 
,03-24 15:06:19.644  3335  3394 I jxcore-log: # setup
03-24 15:06:19.644  3335  3394 I jxcore-log: 
,03-24 15:06:19.799  3335  3394 I jxcore-log: # 98. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-24 15:06:19.799  3335  3394 I jxcore-log: 
,03-24 15:06:20.202  1389  1389 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:06:20.259  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 15:06:20.260  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:20.260  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:20.260  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:20.269  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:06:20.301  3755  3755 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 15:06:20.301  3755  3755 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 15:06:20.302  3755  3755 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 15:06:20.580  3335  3394 I jxcore-log: ok 314 WAITING state entry should not be removed
03-24 15:06:20.580  3335  3394 I jxcore-log: 
,03-24 15:06:20.581  3335  3394 I jxcore-log: ok 315 Waiting entries between 6 and MAXSIZE + 4 should exist
03-24 15:06:20.581  3335  3394 I jxcore-log: 
03-24 15:06:20.582  3335  3394 I jxcore-log: ok 316 Size should be MAXSIZE
03-24 15:06:20.582  3335  3394 I jxcore-log: 
,03-24 15:06:20.582  3335  3394 I jxcore-log: ok 317 entryCounter should be MAXSIZE+6
03-24 15:06:20.582  3335  3394 I jxcore-log: 
,03-24 15:06:20.584  3335  3394 I jxcore-log: # teardown
03-24 15:06:20.584  3335  3394 I jxcore-log: 
,03-24 15:06:21.210  3335  3394 I jxcore-log: # setup
03-24 15:06:21.210  3335  3394 I jxcore-log: 
,03-24 15:06:21.339  3335  3394 I jxcore-log: # 99. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-24 15:06:21.339  3335  3394 I jxcore-log: 
,03-24 15:06:22.572  3335  3394 I jxcore-log: ok 318 Kill should be called once
03-24 15:06:22.572  3335  3394 I jxcore-log: 
,03-24 15:06:22.572  3335  3394 I jxcore-log: ok 319 Size should be 100
03-24 15:06:22.572  3335  3394 I jxcore-log: 
,03-24 15:06:22.575  3335  3394 I jxcore-log: # teardown
03-24 15:06:22.575  3335  3394 I jxcore-log: 
,03-24 15:06:22.665  3335  3394 I jxcore-log: # setup
03-24 15:06:22.665  3335  3394 I jxcore-log: 
,03-24 15:06:22.830  3335  3394 I jxcore-log: # 100. #ThaliPeerPoolInterface - bad enqueues
03-24 15:06:22.830  3335  3394 I jxcore-log: 
,03-24 15:06:22.982  3335  3394 I jxcore-log: ok 320 null arg
03-24 15:06:22.982  3335  3394 I jxcore-log: 
,03-24 15:06:22.989  3335  3394 I jxcore-log: ok 321 wrong arg type
03-24 15:06:22.989  3335  3394 I jxcore-log: 
,03-24 15:06:22.992  3335  3394 I jxcore-log: ok 322 wrong state
03-24 15:06:22.992  3335  3394 I jxcore-log: 
,03-24 15:06:22.994  3335  3394 I jxcore-log: # teardown
03-24 15:06:22.994  3335  3394 I jxcore-log: 
,03-24 15:06:23.149  3335  3394 I jxcore-log: # setup
03-24 15:06:23.149  3335  3394 I jxcore-log: 
,03-24 15:06:23.356  3335  3394 I jxcore-log: # 101. #ThaliPeerPoolInterface - do not allow same object type
03-24 15:06:23.356  3335  3394 I jxcore-log: 
,03-24 15:06:23.510  3335  3394 I jxcore-log: ok 323 good enqueue
03-24 15:06:23.510  3335  3394 I jxcore-log: 
,03-24 15:06:23.512  3335  3394 I jxcore-log: ok 324 should be equal
03-24 15:06:23.512  3335  3394 I jxcore-log: 
,03-24 15:06:23.515  3335  3394 I jxcore-log: # teardown
03-24 15:06:23.515  3335  3394 I jxcore-log: 
,03-24 15:06:23.680  3335  3394 I jxcore-log: # setup
03-24 15:06:23.680  3335  3394 I jxcore-log: 
,03-24 15:06:23.822  3335  3394 I jxcore-log: # 102. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-24 15:06:23.822  3335  3394 I jxcore-log: 
,03-24 15:06:24.010  3335  3394 I jxcore-log: ok 325 good enqueue
03-24 15:06:24.010  3335  3394 I jxcore-log: 
,03-24 15:06:24.010  3335  3394 I jxcore-log: ok 326 2nd good enqueue
03-24 15:06:24.010  3335  3394 I jxcore-log: 
,03-24 15:06:24.011  3335  3394 I jxcore-log: ok 327 we are in the pool
03-24 15:06:24.011  3335  3394 I jxcore-log: 
,03-24 15:06:24.015  3335  3394 I jxcore-log: ok 328 We are out of the pool
03-24 15:06:24.015  3335  3394 I jxcore-log: 
03-24 15:06:24.015  3335  3394 I jxcore-log: ok 329 Action was killed
03-24 15:06:24.015  3335  3394 I jxcore-log: 
03-24 15:06:24.015  3335  3394 I jxcore-log: ok 330 The original kill was called too
03-24 15:06:24.015  3335  3394 I jxcore-log: 
,03-24 15:06:24.016  3335  3394 I jxcore-log: ok 331 second item is still in queue
03-24 15:06:24.016  3335  3394 I jxcore-log: 
03-24 15:06:24.019  3335  3394 I jxcore-log: # teardown
03-24 15:06:24.019  3335  3394 I jxcore-log: 
,03-24 15:06:24.191  3335  3394 I jxcore-log: # setup
03-24 15:06:24.191  3335  3394 I jxcore-log: 
,03-24 15:06:24.353  3335  3394 I jxcore-log: # 103. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-24 15:06:24.353  3335  3394 I jxcore-log: 
,03-24 15:06:24.991  3335  3394 I jxcore-log: ok 332 good enqueue,
03-24 15:06:24.991  3335  3394 I jxcore-log: 
,03-24 15:06:24.991  3335  3394 I jxcore-log: ok 333 first kill
03-24 15:06:24.991  3335  3394 I jxcore-log: 
03-24 15:06:24.992  3335  3394 I jxcore-log: ok 334 second NOOP kill
03-24 15:06:24.992  3335  3394 I jxcore-log: ,
03-24 15:06:24.994  3335  3394 I jxcore-log: # teardown
03-24 15:06:24.994  3335  3394 I jxcore-log: 
,03-24 15:06:25.129  3335  3394 I jxcore-log: # setup
03-24 15:06:25.129  3335  3394 I jxcore-log: 
,03-24 15:06:25.309  3335  3394 I jxcore-log: # 104. compareBufferArrays
03-24 15:06:25.309  3335  3394 I jxcore-log: 
,03-24 15:06:25.390  3335  3394 I jxcore-log: ok 335 should throw
03-24 15:06:25.390  3335  3394 I jxcore-log: 
,03-24 15:06:25.392  3335  3394 I jxcore-log: ok 336 should throw
03-24 15:06:25.392  3335  3394 I jxcore-log: 
,03-24 15:06:25.392  3335  3394 I jxcore-log: ok 337 (unnamed assert)
03-24 15:06:25.392  3335  3394 I jxcore-log: 
03-24 15:06:25.393  3335  3394 I jxcore-log: ok 338 (unnamed assert),
03-24 15:06:25.393  3335  3394 I jxcore-log: 
03-24 15:06:25.393  3335  3394 I jxcore-log: ok 339 (unnamed assert)
03-24 15:06:25.393  3335  3394 I jxcore-log: 
03-24 15:06:25.394  3335  3394 I jxcore-log: ok 340 (unnamed assert)
03-24 15:06:25.394  3335  3394 I jxcore-log: 
03-24 15:06:25.395  3335  3394 I jxcore-log: ok 341 (unnamed assert)
03-24 15:06:25.395  3335  3394 I jxcore-log: 
,03-24 15:06:25.398  3335  3394 I jxcore-log: # teardown
03-24 15:06:25.398  3335  3394 I jxcore-log: 
,03-24 15:06:25.549  3335  3394 I jxcore-log: # setup
03-24 15:06:25.549  3335  3394 I jxcore-log: 
,03-24 15:06:25.716  3335  3394 I jxcore-log: # 105. Call start twice and get error
03-24 15:06:25.716  3335  3394 I jxcore-log: 
,03-24 15:06:25.831  3335  3394 I jxcore-log: ok 342 should throw
,03-24 15:06:25.831  3335  3394 I jxcore-log: 
03-24 15:06:25.833  3335  3394 I jxcore-log: # teardown
03-24 15:06:25.833  3335  3394 I jxcore-log: 
,03-24 15:06:25.969  3335  3394 I jxcore-log: # setup
03-24 15:06:25.969  3335  3394 I jxcore-log: 
,03-24 15:06:26.104  3335  3394 I jxcore-log: # 106. Start and make sure it runs
03-24 15:06:26.104  3335  3394 I jxcore-log: 
,03-24 15:06:26.234  3335  3394 I jxcore-log: # teardown
03-24 15:06:26.234  3335  3394 I jxcore-log: 
,03-24 15:06:26.341  3335  3394 I jxcore-log: # setup
03-24 15:06:26.341  3335  3394 I jxcore-log: 
,03-24 15:06:26.451  3335  3394 I jxcore-log: # 107. Make sure getTimeWhenRun is right after start
03-24 15:06:26.451  3335  3394 I jxcore-log: 
,03-24 15:06:26.535  3335  3394 I jxcore-log: ok 343 (unnamed assert)
03-24 15:06:26.535  3335  3394 I jxcore-log: 
,03-24 15:06:26.543  3335  3394 I jxcore-log: # teardown
03-24 15:06:26.543  3335  3394 I jxcore-log: 
,03-24 15:06:26.716  3335  3394 I jxcore-log: # setup
03-24 15:06:26.716  3335  3394 I jxcore-log: 
,03-24 15:06:26.850  3335  3394 I jxcore-log: # 108. Make sure getTimeWhenRun is -1 after function is called
03-24 15:06:26.850  3335  3394 I jxcore-log: 
,03-24 15:06:27.041  3335  3394 I jxcore-log: ok 344 should be equal
03-24 15:06:27.041  3335  3394 I jxcore-log: 
,03-24 15:06:27.052  3335  3394 I jxcore-log: # teardown
03-24 15:06:27.052  3335  3394 I jxcore-log: 
,03-24 15:06:27.180  3335  3394 I jxcore-log: # setup
03-24 15:06:27.180  3335  3394 I jxcore-log: 
,03-24 15:06:27.317  3335  3394 I jxcore-log: # 109. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-24 15:06:27.317  3335  3394 I jxcore-log: 
,03-24 15:06:27.392  3335  3394 I jxcore-log: ok 345 should be equal
03-24 15:06:27.392  3335  3394 I jxcore-log: 
,03-24 15:06:27.393  3335  3394 I jxcore-log: ok 346 should be equal
03-24 15:06:27.393  3335  3394 I jxcore-log: 
,03-24 15:06:27.397  3335  3394 I jxcore-log: ok 347 should throw
03-24 15:06:27.397  3335  3394 I jxcore-log: 
,03-24 15:06:27.401  3335  3394 I jxcore-log: # teardown
03-24 15:06:27.401  3335  3394 I jxcore-log: 
,03-24 15:06:27.534  3335  3394 I jxcore-log: # setup
03-24 15:06:27.534  3335  3394 I jxcore-log: 
,03-24 15:06:27.651  3335  3394 I jxcore-log: # 110. Test TransientState
03-24 15:06:27.651  3335  3394 I jxcore-log: 
,03-24 15:06:27.770  3335  3394 I jxcore-log: ok 348 should throw
03-24 15:06:27.770  3335  3394 I jxcore-log: 
03-24 15:06:27.771  3335  3394 I jxcore-log: ok 349 should throw
03-24 15:06:27.771  3335  3394 I jxcore-log: 
03-24 15:06:27.772  3335  3394 I jxcore-log: ok 350 should be equal
03-24 15:06:27.772  3335  3394 I jxcore-log: 
,03-24 15:06:27.772  3335  3394 I jxcore-log: ok 351 should be equal
03-24 15:06:27.772  3335  3394 I jxcore-log: 
03-24 15:06:27.773  3335  3394 I jxcore-log: ok 352 should be equal
03-24 15:06:27.773  3335  3394 I jxcore-log: 
03-24 15:06:27.773  3335  3394 I jxcore-log: ok 353 should be equal
03-24 15:06:27.773  3335  3394 I jxcore-log: 
03-24 15:06:27.773  3335  3394 I jxcore-log: ok 354 (unnamed assert)
03-24 15:06:27.773  3335  3394 I jxcore-log: 
03-24 15:06:27.774  3335  3394 I jxcore-log: ok 355 (unnamed assert)
03-24 15:06:27.774  3335  3394 I jxcore-log: 
,03-24 15:06:27.776  3335  3394 I jxcore-log: # teardown
03-24 15:06:27.776  3335  3394 I jxcore-log: 
,03-24 15:06:27.913  3335  3394 I jxcore-log: # setup
03-24 15:06:27.913  3335  3394 I jxcore-log: 
,03-24 15:06:28.023  3335  3394 I jxcore-log: # 111. No peers and empty database
03-24 15:06:28.023  3335  3394 I jxcore-log: 
,03-24 15:06:28.250  3335  3394 I jxcore-log: ok 356 verify failed
03-24 15:06:28.250  3335  3394 I jxcore-log: 
03-24 15:06:28.251  3335  3394 I jxcore-log: ok 357 constructor called once
03-24 15:06:28.251  3335  3394 I jxcore-log: 
,03-24 15:06:28.252  3335  3394 I jxcore-log: ok 358 constructor called with right args
03-24 15:06:28.252  3335  3394 I jxcore-log: 
,03-24 15:06:28.252  3335  3394 I jxcore-log: ok 359 match start arg
03-24 15:06:28.252  3335  3394 I jxcore-log: 
,03-24 15:06:28.253  3335  3394 I jxcore-log: ok 360 start called once
03-24 15:06:28.253  3335  3394 I jxcore-log: 
03-24 15:06:28.253  3335  3394 I jxcore-log: ok 361 stop called once
03-24 15:06:28.253  3335  3394 I jxcore-log: 
03-24 15:06:28.253  3335  3394 I jxcore-log: ok 362 stop after start
03-24 15:06:28.253  3335  3394 I jxcore-log: 
03-24 15:06:28.257  3335  3394 I jxcore-log: # teardown
03-24 15:06:28.257  3335  3394 I jxcore-log: 
,03-24 15:06:28.470  3335  3394 I jxcore-log: # setup
03-24 15:06:28.470  3335  3394 I jxcore-log: 
,03-24 15:06:28.602  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:06:28.885  3335  3394 I jxcore-log: # 112. One peer and empty DB
03-24 15:06:28.885  3335  3394 I jxcore-log: 
,03-24 15:06:29.220  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:29.220  3335  3394 I jxcore-log: 
,03-24 15:06:29.222  3335  3394 I jxcore-log: ok 363 verify failed
03-24 15:06:29.222  3335  3394 I jxcore-log: 
03-24 15:06:29.223  3335  3394 I jxcore-log: ok 364 constructor called once
03-24 15:06:29.223  3335  3394 I jxcore-log: 
,03-24 15:06:29.223  3335  3394 I jxcore-log: ok 365 constructor called with right args
03-24 15:06:29.223  3335  3394 I jxcore-log: 
,03-24 15:06:29.224  3335  3394 I jxcore-log: ok 366 match start arg
03-24 15:06:29.224  3335  3394 I jxcore-log: 
03-24 15:06:29.225  3335  3394 I jxcore-log: ok 367 start called once,
03-24 15:06:29.225  3335  3394 I jxcore-log: 
03-24 15:06:29.225  3335  3394 I jxcore-log: ok 368 stop called once
03-24 15:06:29.225  3335  3394 I jxcore-log: 
03-24 15:06:29.225  3335  3394 I jxcore-log: ok 369 stop after start
03-24 15:06:29.225  3335  3394 I jxcore-log: 
,03-24 15:06:29.230  3335  3394 I jxcore-log: # teardown
03-24 15:06:29.230  3335  3394 I jxcore-log: 
,03-24 15:06:29.352  3335  3394 I jxcore-log: # setup
03-24 15:06:29.352  3335  3394 I jxcore-log: 
,03-24 15:06:33.292  3335  3394 I jxcore-log: # 113. One peer with _Local set behind current seq
03-24 15:06:33.292  3335  3394 I jxcore-log: 
,03-24 15:06:33.630  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 15:06:33.630  3335  3394 I jxcore-log: 
03-24 15:06:33.632  3335  3394 I jxcore-log: ok 370 verify failed
03-24 15:06:33.632  3335  3394 I jxcore-log: ,
03-24 15:06:33.633  3335  3394 I jxcore-log: ok 371 constructor called once,
03-24 15:06:33.633  3335  3394 I jxcore-log: 
,03-24 15:06:33.636  3335  3394 I jxcore-log: ok 372 constructor called with right args
,03-24 15:06:33.636  3335  3394 I jxcore-log: 
,03-24 15:06:33.637  3335  3394 I jxcore-log: ok 373 match start arg
03-24 15:06:33.637  3335  3394 I jxcore-log: 
03-24 15:06:33.637  3335  3394 I jxcore-log: ok 374 start called once
03-24 15:06:33.637  3335  3394 I jxcore-log: 
,03-24 15:06:33.638  3335  3394 I jxcore-log: ok 375 stop called once
03-24 15:06:33.638  3335  3394 I jxcore-log: 
,03-24 15:06:33.640  3335  3394 I jxcore-log: ok 376 stop after start
03-24 15:06:33.640  3335  3394 I jxcore-log: 
,03-24 15:06:33.647  3335  3394 I jxcore-log: # teardown
,03-24 15:06:33.647  3335  3394 I jxcore-log: 
,03-24 15:06:34.317  3335  3394 I jxcore-log: # setup
03-24 15:06:34.317  3335  3394 I jxcore-log: 
,03-24 15:06:34.469  3335  3394 I jxcore-log: # 114. One peer with _Local set equal to current seq
03-24 15:06:34.469  3335  3394 I jxcore-log: 
,03-24 15:06:34.937  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:34.937  3335  3394 I jxcore-log: 
,03-24 15:06:34.938  3335  3394 I jxcore-log: ok 377 verify failed
03-24 15:06:34.938  3335  3394 I jxcore-log: 
,03-24 15:06:34.938  3335  3394 I jxcore-log: ok 378 constructor called once
03-24 15:06:34.938  3335  3394 I jxcore-log: 
03-24 15:06:34.939  3335  3394 I jxcore-log: ok 379 constructor called with right args
03-24 15:06:34.939  3335  3394 I jxcore-log: 
,03-24 15:06:34.939  3335  3394 I jxcore-log: ok 380 match start arg,
03-24 15:06:34.939  3335  3394 I jxcore-log: 
03-24 15:06:34.939  3335  3394 I jxcore-log: ok 381 start called once
03-24 15:06:34.939  3335  3394 I jxcore-log: 
,03-24 15:06:34.940  3335  3394 I jxcore-log: ok 382 stop called once
03-24 15:06:34.940  3335  3394 I jxcore-log: 
03-24 15:06:34.940  3335  3394 I jxcore-log: ok 383 stop after start
03-24 15:06:34.940  3335  3394 I jxcore-log: 
,03-24 15:06:34.944  3335  3394 I jxcore-log: # teardown
03-24 15:06:34.944  3335  3394 I jxcore-log: 
,03-24 15:06:35.131  3335  3394 I jxcore-log: # setup
03-24 15:06:35.131  3335  3394 I jxcore-log: 
,03-24 15:06:35.299  3335  3394 I jxcore-log: # 115. One peer with _Local set ahead of current seq (and no this should not happen)
03-24 15:06:35.299  3335  3394 I jxcore-log: 
,03-24 15:06:35.640  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:35.640  3335  3394 I jxcore-log: 
03-24 15:06:35.641  3335  3394 I jxcore-log: ok 384 verify failed
03-24 15:06:35.641  3335  3394 I jxcore-log: 
03-24 15:06:35.642  3335  3394 I jxcore-log: ok 385 constructor called once
03-24 15:06:35.642  3335  3394 I jxcore-log: 
03-24 15:06:35.642  3335  3394 I jxcore-log: ok 386 constructor called with right args
03-24 15:06:35.642  3335  3394 I jxcore-log: 
03-24 15:06:35.642  3335  3394 I jxcore-log: ok 387 match start arg
03-24 15:06:35.642  3335  3394 I jxcore-log: 
03-24 15:06:35.643  3335  3394 I jxcore-log: ok 388 start called once
03-24 15:06:35.643  3335  3394 I jxcore-log: 
03-24 15:06:35.643  3335  3394 I jxcore-log: ok 389 stop called once
03-24 15:06:35.643  3335  3394 I jxcore-log: 
03-24 15:06:35.643  3335  3394 I jxcore-log: ok 390 stop after start
03-24 15:06:35.643  3335  3394 I jxcore-log: 
03-24 15:06:35.648  3335  3394 I jxcore-log: # teardown
03-24 15:06:35.648  3335  3394 I jxcore-log: 
,03-24 15:06:35.721  3335  3394 I jxcore-log: # setup
03-24 15:06:35.721  3335  3394 I jxcore-log: 
,03-24 15:06:35.837  3335  3394 I jxcore-log: # 116. Three peers, one not in DB, one behind and one ahead
03-24 15:06:35.837  3335  3394 I jxcore-log: 
,03-24 15:06:36.268  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:36.268  3335  3394 I jxcore-log: 
,03-24 15:06:36.271  3335  3394 I jxcore-log: ok 391 verify failed
03-24 15:06:36.271  3335  3394 I jxcore-log: 
,03-24 15:06:36.272  3335  3394 I jxcore-log: ok 392 constructor called once
03-24 15:06:36.272  3335  3394 I jxcore-log: 
03-24 15:06:36.273  3335  3394 I jxcore-log: ok 393 constructor called with right args
03-24 15:06:36.273  3335  3394 I jxcore-log: 
,03-24 15:06:36.273  3335  3394 I jxcore-log: ok 394 match start arg
03-24 15:06:36.273  3335  3394 I jxcore-log: 
,03-24 15:06:36.274  3335  3394 I jxcore-log: ok 395 start called once
03-24 15:06:36.274  3335  3394 I jxcore-log: 
,03-24 15:06:36.274  3335  3394 I jxcore-log: ok 396 stop called once
03-24 15:06:36.274  3335  3394 I jxcore-log: 
,03-24 15:06:36.274  3335  3394 I jxcore-log: ok 397 stop after start
03-24 15:06:36.274  3335  3394 I jxcore-log: 
03-24 15:06:36.282  3335  3394 I jxcore-log: # teardown
03-24 15:06:36.282  3335  3394 I jxcore-log: 
,03-24 15:06:36.649  3335  3394 I jxcore-log: # setup
03-24 15:06:36.649  3335  3394 I jxcore-log: 
,03-24 15:06:36.810  3335  3394 I jxcore-log: # 117. More than maximum peers, make sure we only send maximum allowed
03-24 15:06:36.810  3335  3394 I jxcore-log: 
,03-24 15:06:37.555  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:37.555  3335  3394 I jxcore-log: ,
03-24 15:06:37.556  3335  3394 I jxcore-log: ok 398 verify failed
03-24 15:06:37.556  3335  3394 I jxcore-log: 
03-24 15:06:37.557  3335  3394 I jxcore-log: ok 399 constructor called once
03-24 15:06:37.557  3335  3394 I jxcore-log: 
03-24 15:06:37.557  3335  3394 I jxcore-log: ok 400 constructor called with right args
03-24 15:06:37.557  3335  3394 I jxcore-log: 
,03-24 15:06:37.558  3335  3394 I jxcore-log: ok 401 match start arg
03-24 15:06:37.558  3335  3394 I jxcore-log: 
,03-24 15:06:37.558  3335  3394 I jxcore-log: ok 402 start called once
03-24 15:06:37.558  3335  3394 I jxcore-log: 
03-24 15:06:37.558  3335  3394 I jxcore-log: ok 403 stop called once
03-24 15:06:37.558  3335  3394 I jxcore-log: 
03-24 15:06:37.559  3335  3394 I jxcore-log: ok 404 stop after start
03-24 15:06:37.559  3335  3394 I jxcore-log: ,
03-24 15:06:37.563  3335  3394 I jxcore-log: # teardown
03-24 15:06:37.563  3335  3394 I jxcore-log: 
,03-24 15:06:37.740  3335  3394 I jxcore-log: # setup
03-24 15:06:37.740  3335  3394 I jxcore-log: 
,03-24 15:06:37.925  3335  3394 I jxcore-log: # 118. two peers with empty DB, update the doc,
03-24 15:06:37.925  3335  3394 I jxcore-log: 
,03-24 15:06:38.249  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:38.249  3335  3394 I jxcore-log: 
,03-24 15:06:38.284  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 15:06:38.284  3335  3394 I jxcore-log: 
03-24 15:06:38.285  3335  3394 I jxcore-log: ok 405 verify failed
03-24 15:06:38.285  3335  3394 I jxcore-log: 
,03-24 15:06:38.286  3335  3394 I jxcore-log: ok 406 constructor called once
03-24 15:06:38.286  3335  3394 I jxcore-log: 
,03-24 15:06:38.286  3335  3394 I jxcore-log: ok 407 constructor called with right args
03-24 15:06:38.286  3335  3394 I jxcore-log: 
03-24 15:06:38.287  3335  3394 I jxcore-log: ok 408 last start before stop
03-24 15:06:38.287  3335  3394 I jxcore-log: 
,03-24 15:06:38.288  3335  3394 I jxcore-log: ok 409 empty first start
03-24 15:06:38.288  3335  3394 I jxcore-log: 
,03-24 15:06:38.289  3335  3394 I jxcore-log: ok 410 full second start
03-24 15:06:38.289  3335  3394 I jxcore-log: 
03-24 15:06:38.289  3335  3394 I jxcore-log: ok 411 only 2 timers
03-24 15:06:38.289  3335  3394 I jxcore-log: 
03-24 15:06:38.294  3335  3394 I jxcore-log: # teardown
03-24 15:06:38.294  3335  3394 I jxcore-log: 
,03-24 15:06:38.619  3335  3394 I jxcore-log: # setup
,03-24 15:06:38.619  3335  3394 I jxcore-log: 
,03-24 15:06:38.879  3335  3394 I jxcore-log: # 119. add doc and make sure tokens refresh when they expire
03-24 15:06:38.879  3335  3394 I jxcore-log: 
,03-24 15:06:39.748  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:39.748  3335  3394 I jxcore-log: 
,03-24 15:06:39.880  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:39.880  3335  3394 I jxcore-log: 
,03-24 15:06:40.000  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:40.000  3335  3394 I jxcore-log: 
,03-24 15:06:40.003  3335  3394 I jxcore-log: ok 412 verify failed
03-24 15:06:40.003  3335  3394 I jxcore-log: 
03-24 15:06:40.003  3335  3394 I jxcore-log: ok 413 constructor called once
03-24 15:06:40.003  3335  3394 I jxcore-log: 
03-24 15:06:40.004  3335  3394 I jxcore-log: ok 414 constructor called with right args
03-24 15:06:40.004  3335  3394 I jxcore-log: 
03-24 15:06:40.004  3335  3394 I jxcore-log: ok 415 start before stop
03-24 15:06:40.004  3335  3394 I jxcore-log: 
,03-24 15:06:40.005  3335  3394 I jxcore-log: ok 416 We got at least 3 calls to start
03-24 15:06:40.005  3335  3394 I jxcore-log: 
03-24 15:06:40.005  3335  3394 I jxcore-log: ok 417 at least 3
03-24 15:06:40.005  3335  3394 I jxcore-log: 
03-24 15:06:40.005  3335  3394 I jxcore-log: ok 418 default 1
03-24 15:06:40.005  3335  3394 I jxcore-log: 
03-24 15:06:40.006  3335  3394 I jxcore-log: ok 419 1 run
03-24 15:06:40.006  3335  3394 I jxcore-log: 
03-24 15:06:40.006  3335  3394 I jxcore-log: ok 420 default 2
03-24 15:06:40.006  3335  3394 I jxcore-log: 
,03-24 15:06:40.007  3335  3394 I jxcore-log: ok 421 2 run
03-24 15:06:40.007  3335  3394 I jxcore-log: 
03-24 15:06:40.007  3335  3394 I jxcore-log: ok 422 default 3
03-24 15:06:40.007  3335  3394 I jxcore-log: 
,03-24 15:06:40.014  3335  3394 I jxcore-log: # teardown
03-24 15:06:40.014  3335  3394 I jxcore-log: 
,03-24 15:06:40.164  3335  3394 I jxcore-log: # setup
03-24 15:06:40.164  3335  3394 I jxcore-log: ,
,03-24 15:06:40.782  3335  3394 I jxcore-log: # 120. start and stop and start and stop
03-24 15:06:40.782  3335  3394 I jxcore-log: 
,03-24 15:06:41.129  3335  3394 I jxcore-log: ok 423 start out null
03-24 15:06:41.129  3335  3394 I jxcore-log: 
,03-24 15:06:41.149  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:41.149  3335  3394 I jxcore-log: 
,03-24 15:06:41.150  3335  3394 I jxcore-log: ok 424 back to null
03-24 15:06:41.150  3335  3394 I jxcore-log: 
,03-24 15:06:41.171  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:41.171  3335  3394 I jxcore-log: 
,03-24 15:06:41.172  3335  3394 I jxcore-log: ok 425 still null
03-24 15:06:41.172  3335  3394 I jxcore-log: 
03-24 15:06:41.173  3335  3394 I jxcore-log: ok 426 verify failed
03-24 15:06:41.173  3335  3394 I jxcore-log: 
03-24 15:06:41.173  3335  3394 I jxcore-log: ok 427 constructor called once
03-24 15:06:41.173  3335  3394 I jxcore-log: 
03-24 15:06:41.174  3335  3394 I jxcore-log: ok 428 constructor called with right args
03-24 15:06:41.174  3335  3394 I jxcore-log: 
,03-24 15:06:41.174  3335  3394 I jxcore-log: ok 429 first start before first stop
03-24 15:06:41.174  3335  3394 I jxcore-log: 
03-24 15:06:41.174  3335  3394 I jxcore-log: ok 430 first stop before second start
03-24 15:06:41.174  3335  3394 I jxcore-log: 
03-24 15:06:41.175  3335  3394 I jxcore-log: ok 431 second start before second stop
03-24 15:06:41.175  3335  3394 I jxcore-log: 
,03-24 15:06:41.183  3335  3394 I jxcore-log: # teardown
03-24 15:06:41.183  3335  3394 I jxcore-log: 
,03-24 15:06:41.581  3335  3394 I jxcore-log: # setup
03-24 15:06:41.581  3335  3394 I jxcore-log: 
,03-24 15:06:41.732  3335  3394 I jxcore-log: # 121. two identical starts in a row
03-24 15:06:41.732  3335  3394 I jxcore-log: 
,03-24 15:06:42.131  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:42.131  3335  3394 I jxcore-log: 
,03-24 15:06:42.135  3335  3394 I jxcore-log: ok 432 verify failed
03-24 15:06:42.135  3335  3394 I jxcore-log: 
,03-24 15:06:42.136  3335  3394 I jxcore-log: ok 433 constructor called once
03-24 15:06:42.136  3335  3394 I jxcore-log: 
,03-24 15:06:42.136  3335  3394 I jxcore-log: ok 434 constructor called with right args
03-24 15:06:42.136  3335  3394 I jxcore-log: 
03-24 15:06:42.137  3335  3394 I jxcore-log: ok 435 (unnamed assert)
03-24 15:06:42.137  3335  3394 I jxcore-log: 
,03-24 15:06:42.143  3335  3394 I jxcore-log: # teardown
03-24 15:06:42.143  3335  3394 I jxcore-log: 
,03-24 15:06:42.299  3335  3394 I jxcore-log: # setup
03-24 15:06:42.299  3335  3394 I jxcore-log: 
,03-24 15:06:42.477  3335  3394 I jxcore-log: # 122. two different starts in a row
03-24 15:06:42.477  3335  3394 I jxcore-log: 
,03-24 15:06:42.803  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:42.803  3335  3394 I jxcore-log: 
,03-24 15:06:42.810  3335  3394 I jxcore-log: ok 436 verify failed
03-24 15:06:42.810  3335  3394 I jxcore-log: 
,03-24 15:06:42.811  3335  3394 I jxcore-log: ok 437 constructor called once
03-24 15:06:42.811  3335  3394 I jxcore-log: 
03-24 15:06:42.811  3335  3394 I jxcore-log: ok 438 constructor called with right args
03-24 15:06:42.811  3335  3394 I jxcore-log: 
,03-24 15:06:42.812  3335  3394 I jxcore-log: ok 439 (unnamed assert)
03-24 15:06:42.812  3335  3394 I jxcore-log: 
03-24 15:06:42.812  3335  3394 I jxcore-log: ok 440 (unnamed assert)
03-24 15:06:42.812  3335  3394 I jxcore-log: 
,03-24 15:06:42.816  3335  3394 I jxcore-log: # teardown
03-24 15:06:42.816  3335  3394 I jxcore-log: 
,03-24 15:06:43.122  3335  3394 I jxcore-log: # setup
03-24 15:06:43.122  3335  3394 I jxcore-log: 
,03-24 15:06:43.251  3335  3394 I jxcore-log: # 123. two stops and a start and two stops
03-24 15:06:43.251  3335  3394 I jxcore-log: 
,03-24 15:06:43.494  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:43.494  3335  3394 I jxcore-log: 
,03-24 15:06:43.496  3335  3394 I jxcore-log: ok 441 verify failed
03-24 15:06:43.496  3335  3394 I jxcore-log: 
,03-24 15:06:43.497  3335  3394 I jxcore-log: ok 442 constructor called once
03-24 15:06:43.497  3335  3394 I jxcore-log: 
,03-24 15:06:43.497  3335  3394 I jxcore-log: ok 443 constructor called with right args
03-24 15:06:43.497  3335  3394 I jxcore-log: 
03-24 15:06:43.498  3335  3394 I jxcore-log: ok 444 start before stop
03-24 15:06:43.498  3335  3394 I jxcore-log: 
03-24 15:06:43.502  3335  3394 I jxcore-log: # teardown
03-24 15:06:43.502  3335  3394 I jxcore-log: 
,03-24 15:06:43.742  3335  3394 I jxcore-log: # setup
03-24 15:06:43.742  3335  3394 I jxcore-log: 
,03-24 15:06:44.162  3567  3996 V KeepSync: Connecting to GoogleApiClient
,03-24 15:06:44.164  3335  3394 I jxcore-log: # 124. we properly enqueue requests so no then needed
03-24 15:06:44.164  3335  3394 I jxcore-log: 
,03-24 15:06:44.225  1389  1427 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 15:06:44.225  1389  1427 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:44.225  1389  1427 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:44.225  1389  1427 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:44.229  1389  1427 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:06:44.237  1389  1737 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
03-24 15:06:44.238  1389  1737 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:44.238  1389  1737 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:44.238  1389  1737 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:44.244  1389  1737 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: Handling authorization failure
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
,03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 15:06:44.245  1785  3998 E ClientConnectionOperation: 	... 7 more
,03-24 15:06:44.251  3567  3996 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 15:06:44.253  3567  3996 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:06:44.260  3567  3996 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:06:44.261  3567  3996 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 15:06:44.263  3143  3997 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 15:06:44.263  3143  3997 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at blb.a(PG:3937)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at czp.a(PG:18188)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:06:44.263  3143  3997 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	... 12 more
03-24 15:06:44.263  3143  3997 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at fal.a(PG:38)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:06:44.263  3143  3997 E HttpOperation: 	... 14 more
,03-24 15:06:44.307  1389  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 15:06:44.308  1389  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:44.308  1389  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:44.308  1389  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:44.312  1389  1928 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 15:06:44.322  1389  1423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 15:06:44.323  1389  1423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 15:06:44.323  1389  1423 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 15:06:44.323  1389  1423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 15:06:44.328  1389  1423 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-24 15:06:44.330  3143  3997 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 15:06:44.330  3143  3997 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jdm.a(PG:82)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jcs.o(PG:406)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jcn.a(PG:1379)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jcs.i(PG:143)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at hec.a(PG:42)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at hee.a(PG:102)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at czr.a(PG:65)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at kka.a(PG:108)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at czp.a(PG:19176)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at czp.a(PG:9081)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at czq.run(PG:1686)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:06:44.330  3143  3997 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jdj.a(PG:4091)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jdj.a(PG:1125)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jdm.a(PG:77)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	... 15 more
03-24 15:06:44.330  3143  3997 E HttpOperation: Caused by: faj: BadAuthentication
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at fal.a(PG:38)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	at jdj.a(PG:4089)
03-24 15:06:44.330  3143  3997 E HttpOperation: 	... 17 more
03-24 15:06:44.331  3143  3997 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 15:06:44.331  3143  3997 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at hec.a(PG:42)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at hee.a(PG:102)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at czr.a(PG:65)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at kka.a(PG:108)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: Caused by: android.accounts.Authenticato,rException: Recoverable error
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	... 15 more
03-24 15:06:44.331  3143  3997 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at fal.a(PG:38)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 15:06:44.331  3143  3997 E ExperimentLoader: 	... 17 more
,03-24 15:06:44.386  3567  3996 E KeepSync: IOException
03-24 15:06:44.386  3567  3996 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 15:06:44.386  3567  3996 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 15:06:44.386  3567  3996 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 15:06:44.386  3567  3996 E KeepSync: 	... 10 more
03-24 15:06:44.386  3567  3996 W KeepSync: Sync result 2
,03-24 15:06:44.397   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 294678, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:06:44.463   823   856 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 294362, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 15:06:44.486  3335  3394 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 15:06:44.486  3335  3394 I jxcore-log: 
,03-24 15:06:44.487  3335  3394 I jxcore-log: ok 445 verify failed
03-24 15:06:44.487  3335  3394 I jxcore-log: 
,03-24 15:06:44.488  3335  3394 I jxcore-log: ok 446 constructor called once,
03-24 15:06:44.488  3335  3394 I jxcore-log: 
,03-24 15:06:44.489  3335  3394 I jxcore-log: ok 447 constructor called with right args
03-24 15:06:44.489  3335  3394 I jxcore-log: 
,03-24 15:06:44.489  3335  3394 I jxcore-log: ok 448 start before stop
03-24 15:06:44.489  3335  3394 I jxcore-log: 
03-24 15:06:44.492  3335  3394 I jxcore-log: # teardown
03-24 15:06:44.492  3335  3394 I jxcore-log: 
,03-24 15:06:44.680  3335  3394 I jxcore-log: # setup,
03-24 15:06:44.680  3335  3394 I jxcore-log: 
,03-24 15:06:44.827  3335  3394 I jxcore-log: # 125. test calculateSeqPointKeyId
03-24 15:06:44.827  3335  3394 I jxcore-log: 
,03-24 15:06:45.003  3335  3394 I jxcore-log: ok 449 should be equal
03-24 15:06:45.003  3335  3394 I jxcore-log: 
,03-24 15:06:45.004  3335  3394 I jxcore-log: ok 450 should be equal
03-24 15:06:45.004  3335  3394 I jxcore-log: 
,03-24 15:06:45.009  3335  3394 I jxcore-log: # teardown
03-24 15:06:45.009  3335  3394 I jxcore-log: 
,03-24 15:06:45.192  3335  3394 I jxcore-log: # setup
03-24 15:06:45.192  3335  3394 I jxcore-log: 
,03-24 15:06:45.410  3335  3394 I jxcore-log: # 126. can create servers manager
03-24 15:06:45.410  3335  3394 I jxcore-log: 
,03-24 15:06:45.579   823  1443 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@23e8447b}
,03-24 15:06:45.584   823  1034 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.00 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 15:06:45.610  3335  3394 I jxcore-log: ok 451 serversManager must not be null
03-24 15:06:45.610  3335  3394 I jxcore-log: 
03-24 15:06:45.611  3335  3394 I jxcore-log: ok 452 serversManager must be an object
03-24 15:06:45.611  3335  3394 I jxcore-log: 
03-24 15:06:45.613  3335  3394 I jxcore-log: # teardown
03-24 15:06:45.613  3335  3394 I jxcore-log: 
,03-24 15:06:45.883  3335  3394 I jxcore-log: # setup
03-24 15:06:45.883  3335  3394 I jxcore-log: 
,03-24 15:06:46.055  3335  3394 I jxcore-log: # 127. calling stop without start causes error,
03-24 15:06:46.055  3335  3394 I jxcore-log: 
,03-24 15:06:46.305  3335  3394 I jxcore-log: ok 453 We need to call start first
03-24 15:06:46.305  3335  3394 I jxcore-log: 
,03-24 15:06:46.310  3335  3394 I jxcore-log: # teardown,
03-24 15:06:46.310  3335  3394 I jxcore-log: ,
,03-24 15:06:46.650  3335  3394 I jxcore-log: # setup
03-24 15:06:46.650  3335  3394 I jxcore-log: 
,03-24 15:06:46.829  3335  3394 I jxcore-log: # 128. can start/stop servers manager
03-24 15:06:46.829  3335  3394 I jxcore-log: 
,03-24 15:06:47.009  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:06:47.009  3335  3394 I jxcore-log: 
,03-24 15:06:47.022  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 44012
03-24 15:06:47.022  3335  3394 I jxcore-log: 
,03-24 15:06:47.027  3335  3394 I jxcore-log: ok 454 port must be in range
03-24 15:06:47.027  3335  3394 I jxcore-log: 
,03-24 15:06:47.031  3335  3394 I jxcore-log: # teardown
03-24 15:06:47.031  3335  3394 I jxcore-log: 
,03-24 15:06:47.260   823  1094 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@23e8447b}
,03-24 15:06:47.328   823  1261 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 15:06:47.331  3335  3394 I jxcore-log: # setup
03-24 15:06:47.331  3335  3394 I jxcore-log: 
,03-24 15:06:47.402   873   873 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
03-24 15:06:47.403   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 15:06:47.444   873   873 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-24 15:06:47.445   873   873 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 15:06:47.469  3335  3394 I jxcore-log: # 129. starting twice resolves with listening port
03-24 15:06:47.469  3335  3394 I jxcore-log: 
,03-24 15:06:47.595  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:06:47.595  3335  3394 I jxcore-log: 
,03-24 15:06:47.605  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 43535
03-24 15:06:47.605  3335  3394 I jxcore-log: 
,03-24 15:06:47.610  3335  3394 I jxcore-log: ok 455 second start should return same port
03-24 15:06:47.610  3335  3394 I jxcore-log: 
,03-24 15:06:47.613  3335  3394 I jxcore-log: # teardown
03-24 15:06:47.613  3335  3394 I jxcore-log: 
,03-24 15:06:47.734  3335  3394 I jxcore-log: # setup
,03-24 15:06:47.734  3335  3394 I jxcore-log: 
,03-24 15:06:47.899  3335  3394 I jxcore-log: # 130. terminateIncomingConnection will terminate a connection
03-24 15:06:47.899  3335  3394 I jxcore-log: 
,03-24 15:06:48.090  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:06:48.090  3335  3394 I jxcore-log: 
,03-24 15:06:48.094  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 58914,
03-24 15:06:48.094  3335  3394 I jxcore-log: 
,03-24 15:06:48.102  3335  3394 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 15:06:48.102  3335  3394 I jxcore-log: 
03-24 15:06:48.103  3335  3394 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 15:06:48.103  3335  3394 I jxcore-log: 
,03-24 15:06:48.106  3335  3394 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 15:06:48.106  3335  3394 I jxcore-log: 
,03-24 15:06:48.111  3335  3394 I jxcore-log: ok 456 we should be connected
,03-24 15:06:48.111  3335  3394 I jxcore-log: 
,03-24 15:06:48.116  3335  3394 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 15:06:48.116  3335  3394 I jxcore-log: ,
03-24 15:06:48.117  3335  3394 I jxcore-log: ok 457 now we are disconnected
03-24 15:06:48.117  3335  3394 I jxcore-log: 
,03-24 15:06:48.131  3335  3394 I jxcore-log: # teardown
,03-24 15:06:48.131  3335  3394 I jxcore-log: 
,03-24 15:06:48.298  3335  3394 I jxcore-log: # setup
03-24 15:06:48.298  3335  3394 I jxcore-log: 
,03-24 15:06:48.418   873   873 I kickstart: STATUS: Received file 'm9kefs2'
03-24 15:06:48.419   873   873 I kickstart: STATUS: 950272 bytes transferred in 0.973612 seconds
03-24 15:06:48.419   873   873 I kickstart: STATUS: Successfully downloaded files from target 
03-24 15:06:48.419  3335  3394 I jxcore-log: # 131. terminate an Outgoing connection will terminate the server
03-24 15:06:48.419  3335  3394 I jxcore-log: 
03-24 15:06:48.419   873   873 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 15:06:48.422   873   873 I kickstart: STATUS: Sahara protocol completed
,03-24 15:06:48.554  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 15:06:48.554  3335  3394 I jxcore-log: 
,03-24 15:06:48.560  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 46322
03-24 15:06:48.560  3335  3394 I jxcore-log: 
,03-24 15:06:48.563  3335  3394 I jxcore-log: # teardown
03-24 15:06:48.563  3335  3394 I jxcore-log: 
,03-24 15:06:48.700  3335  3394 I jxcore-log: # setup
03-24 15:06:48.700  3335  3394 I jxcore-log: 
,03-24 15:06:48.854  3335  3394 I jxcore-log: # 132. terminate an Outgoing connection with wrong arguments is not harmful
03-24 15:06:48.854  3335  3394 I jxcore-log: 
,03-24 15:06:49.023  3335  3394 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 15:06:49.023  3335  3394 I jxcore-log: 
,03-24 15:06:49.032  3335  3394 I jxcore-log: DEBUG createNativeListener: listening 36839,
03-24 15:06:49.032  3335  3394 I jxcore-log: 
,03-24 15:06:49.039  3335  3394 I jxcore-log: # teardown
03-24 15:06:49.039  3335  3394 I jxcore-log: 
,03-24 15:06:49.180  3335  3394 I jxcore-log: # setup
,03-24 15:06:49.180  3335  3394 I jxcore-log: 
,03-24 15:06:49.336  3335  3394 I jxcore-log: ok 458 should be in started state
03-24 15:06:49.336  3335  3394 I jxcore-log: 
,03-24 15:06:49.341  3335  3394 I jxcore-log: # 133. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-24 15:06:49.341  3335  3394 I jxcore-log: 
,03-24 15:06:49.432  3335  3394 I jxcore-log: ok 459 peer identifier should match
03-24 15:06:49.432  3335  3394 I jxcore-log: 
,03-24 15:06:49.433  3335  3394 I jxcore-log: ok 460 host address should match,
03-24 15:06:49.433  3335  3394 I jxcore-log: 
03-24 15:06:49.433  3335  3394 I jxcore-log: ok 461 port should match
03-24 15:06:49.433  3335  3394 I jxcore-log: 
,03-24 15:06:49.439  3335  3394 I jxcore-log: ok 462 host address should be null,
03-24 15:06:49.439  3335  3394 I jxcore-log: 
03-24 15:06:49.439  3335  3394 I jxcore-log: ok 463 port should should be null
03-24 15:06:49.439  3335  3394 I jxcore-log: 
,03-24 15:06:49.445  3335  3394 I jxcore-log: # teardown,
03-24 15:06:49.445  3335  3394 I jxcore-log: 
,03-24 15:06:49.543  3335  3394 I jxcore-log: ok 464 should not be in started state,
03-24 15:06:49.543  3335  3394 I jxcore-log: 
,03-24 15:06:49.545  3335  3394 I jxcore-log: # setup
03-24 15:06:49.545  3335  3394 I jxcore-log: 
,03-24 15:06:49.650  3335  3394 I jxcore-log: ok 465 should be in started state
03-24 15:06:49.650  3335  3394 I jxcore-log: 
,03-24 15:06:49.657  3335  3394 I jxcore-log: # 134. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-24 15:06:49.657  3335  3394 I jxcore-log: 
,03-24 15:06:49.849  3335  3394 I jxcore-log: ok 466 USN should have changed from the first one
03-24 15:06:49.849  3335  3394 I jxcore-log: 
,03-24 15:06:49.857  3335  3394 I jxcore-log: ok 467 when receiving the second byebye, the first USN should be already set
03-24 15:06:49.857  3335  3394 I jxcore-log: 
,03-24 15:06:49.864  3335  3394 I jxcore-log: # teardown
03-24 15:06:49.864  3335  3394 I jxcore-log: 
,03-24 15:06:50.000  3335  3394 I jxcore-log: ok 468 should not be in started state
03-24 15:06:50.000  3335  3394 I jxcore-log: 
,03-24 15:06:50.002  3335  3394 I jxcore-log: # setup
03-24 15:06:50.002  3335  3394 I jxcore-log: 
,03-24 15:06:50.141  3335  3394 I jxcore-log: ok 469 should be in started state
03-24 15:06:50.141  3335  3394 I jxcore-log: 
,03-24 15:06:50.143  3335  3394 I jxcore-log: # 135. messages with invalid location or USN should be ignored
03-24 15:06:50.143  3335  3394 I jxcore-log: 
,03-24 15:06:50.270  3335  3394 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
03-24 15:06:50.270  3335  3394 I jxcore-log: 
,03-24 15:06:50.273  3335  3394 I jxcore-log: ok 470 should not have emitted with invalid port
03-24 15:06:50.273  3335  3394 I jxcore-log: 
03-24 15:06:50.279  3335  3394 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-24 15:06:50.279  3335  3394 I jxcore-log: 
,03-24 15:06:50.279  3335  3394 I jxcore-log: ok 471 should not have emitted with invalid USN
03-24 15:06:50.279  3335  3394 I jxcore-log: 
03-24 15:06:50.282  3335  3394 I jxcore-log: # teardown
03-24 15:06:50.282  3335  3394 I jxcore-log: 
,03-24 15:06:50.410  3335  3394 I jxcore-log: ok 472 should not be in started state
03-24 15:06:50.410  3335  3394 I jxcore-log: 
,03-24 15:06:50.417  3335  3394 I jxcore-log: # setup
03-24 15:06:50.417  3335  3394 I jxcore-log: 
,03-24 15:06:50.553  3335  3394 I jxcore-log: ok 473 should be in started state
03-24 15:06:50.553  3335  3394 I jxcore-log: 
,03-24 15:06:50.560  3335  3394 I jxcore-log: # 136. verify that Thali-specific messages are filtered correctly
03-24 15:06:50.560  3335  3394 I jxcore-log: 
,03-24 15:06:51.824  3335  3394 I jxcore-log: ok 474 irrelevant messages should be ignored
03-24 15:06:51.824  3335  3394 I jxcore-log: 
,03-24 15:06:51.827  3335  3394 I jxcore-log: ok 475 relevant messages should not be ignored
03-24 15:06:51.827  3335  3394 I jxcore-log: 
,03-24 15:06:51.829  3335  3394 I jxcore-log: ok 476 messages from this device should be ignored
03-24 15:06:51.829  3335  3394 I jxcore-log: 
,03-24 15:06:51.836  3335  3394 I jxcore-log: # teardown
03-24 15:06:51.836  3335  3394 I jxcore-log: 
,03-24 15:06:51.958  3335  3394 I jxcore-log: ok 477 should not be in started state
03-24 15:06:51.958  3335  3394 I jxcore-log: 
,03-24 15:06:51.962  3335  3394 I jxcore-log: # setup
03-24 15:06:51.962  3335  3394 I jxcore-log: 
,03-24 15:06:52.649  3335  3394 I jxcore-log: ok 478 should be in started state
03-24 15:06:52.649  3335  3394 I jxcore-log: 
,03-24 15:06:52.655  3335  3394 I jxcore-log: # 137. #startListeningForAdvertisements should fail if start not called
03-24 15:06:52.655  3335  3394 I jxcore-log: 
,03-24 15:06:52.803  3335  3394 I jxcore-log: ok 479 specific error should be returned
03-24 15:06:52.803  3335  3394 I jxcore-log: 
,03-24 15:06:52.805  3335  3394 I jxcore-log: # teardown
03-24 15:06:52.805  3335  3394 I jxcore-log: 
,03-24 15:06:53.361  3335  3394 I jxcore-log: ok 480 should not be in started state,
03-24 15:06:53.361  3335  3394 I jxcore-log: 
03-24 15:06:53.366  3335  3394 I jxcore-log: # setup
03-24 15:06:53.366  3335  3394 I jxcore-log: 
,03-24 15:06:53.521  3335  3394 I jxcore-log: ok 481 should be in started state,
03-24 15:06:53.521  3335  3394 I jxcore-log: 
03-24 15:06:53.523  3335  3394 I jxcore-log: # 138. #startUpdateAdvertisingAndListening should fail if start not called
03-24 15:06:53.523  3335  3394 I jxcore-log: 
,03-24 15:06:54.328  3335  3394 I jxcore-log: ok 482 specific error should be returned
03-24 15:06:54.328  3335  3394 I jxcore-log: 
,03-24 15:06:54.330  3335  3394 I jxcore-log: # teardown
03-24 15:06:54.330  3335  3394 I jxcore-log: 
,03-24 15:06:54.429  3335  3394 I jxcore-log: ok 483 should not be in started state
03-24 15:06:54.429  3335  3394 I jxcore-log: 
,03-24 15:06:54.431  3335  3394 I jxcore-log: # setup
03-24 15:06:54.431  3335  3394 I jxcore-log: 
,03-24 15:06:54.579  3335  3394 I jxcore-log: ok 484 should be in started state
03-24 15:06:54.579  3335  3394 I jxcore-log: 
,03-24 15:06:54.586  3335  3394 I jxcore-log: # 139. #start should fail if called twice in a row
03-24 15:06:54.586  3335  3394 I jxcore-log: 
,03-24 15:06:54.771  3335  3394 I jxcore-log: ok 485 specific error should be received
03-24 15:06:54.771  3335  3394 I jxcore-log: 
,03-24 15:06:54.773  3335  3394 I jxcore-log: # teardown
03-24 15:06:54.773  3335  3394 I jxcore-log: 
,03-24 15:06:54.943  3335  3394 I jxcore-log: ok 486 should not be in started state
03-24 15:06:54.943  3335  3394 I jxcore-log: 
,03-24 15:06:54.952  3335  3394 I jxcore-log: # setup
03-24 15:06:54.952  3335  3394 I jxcore-log: 
,03-24 15:06:55.087  3335  3394 I jxcore-log: ok 487 should be in started state
,03-24 15:06:55.087  3335  3394 I jxcore-log: 
,03-24 15:06:55.092  3335  3394 I jxcore-log: # 140. should not be started after stop is called
,03-24 15:06:55.092  3335  3394 I jxcore-log: 
,03-24 15:06:55.210  3335  3394 I jxcore-log: ok 488 should not be started
03-24 15:06:55.210  3335  3394 I jxcore-log: ,
03-24 15:06:55.210  3335  3394 I jxcore-log: ok 489 should not be listening
,03-24 15:06:55.210  3335  3394 I jxcore-log: 
03-24 15:06:55.211  3335  3394 I jxcore-log: ok 490 should not target listening
03-24 15:06:55.211  3335  3394 I jxcore-log: 
,03-24 15:06:55.211  3335  3394 I jxcore-log: ok 491 should not be advertising
03-24 15:06:55.211  3335  3394 I jxcore-log: 
03-24 15:06:55.211  3335  3394 I jxcore-log: ok 492 should not target advertising
03-24 15:06:55.211  3335  3394 I jxcore-log: 
,03-24 15:06:55.216  3335  3394 I jxcore-log: # teardown
,03-24 15:06:55.216  3335  3394 I jxcore-log: 
,03-24 15:06:55.350  3335  3394 I jxcore-log: ok 493 should not be in started state
03-24 15:06:55.350  3335  3394 I jxcore-log: 
,03-24 15:06:55.355  3335  3394 I jxcore-log: # setup
03-24 15:06:55.355  3335  3394 I jxcore-log: 
,03-24 15:06:56.133  3335  3394 I jxcore-log: ok 494 should be in started state
03-24 15:06:56.133  3335  3394 I jxcore-log: 
,03-24 15:06:56.140  3335  3394 I jxcore-log: # 141. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-24 15:06:56.140  3335  3394 I jxcore-log: 
,03-24 15:06:56.289  3335  3394 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 15:06:56.289  3335  3394 I jxcore-log: 
,03-24 15:06:56.291  3335  3394 I jxcore-log: ok 495 specific error should be received
03-24 15:06:56.291  3335  3394 I jxcore-log: 
,03-24 15:06:56.293  3335  3394 I jxcore-log: # teardown
03-24 15:06:56.293  3335  3394 I jxcore-log: 
,03-24 15:06:56.848  3335  3394 I jxcore-log: ok 496 should not be in started state
03-24 15:06:56.848  3335  3394 I jxcore-log: 
,03-24 15:06:56.854  3335  3394 I jxcore-log: # setup
03-24 15:06:56.854  3335  3394 I jxcore-log: 
,03-24 15:06:56.978  3335  3394 I jxcore-log: ok 497 should be in started state
,03-24 15:06:56.978  3335  3394 I jxcore-log: 
,03-24 15:06:56.982  3335  3394 I jxcore-log: # 142. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-24 15:06:56.982  3335  3394 I jxcore-log: 
,03-24 15:06:57.581  3335  3394 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-24 15:06:57.581  3335  3394 I jxcore-log: 
,03-24 15:06:57.583  3335  3394 I jxcore-log: ok 498 specific error expected
03-24 15:06:57.583  3335  3394 I jxcore-log: 
,03-24 15:06:57.586  3335  3394 I jxcore-log: # teardown
,03-24 15:06:57.586  3335  3394 I jxcore-log: 
,03-24 15:06:57.704  3335  3394 I jxcore-log: ok 499 should not be in started state
03-24 15:06:57.704  3335  3394 I jxcore-log: 
,03-24 15:06:57.709  3335  3394 I jxcore-log: # setup
03-24 15:06:57.709  3335  3394 I jxcore-log: 
,03-24 15:06:57.872  3335  3394 I jxcore-log: ok 500 should be in started state
03-24 15:06:57.872  3335  3394 I jxcore-log: 
,03-24 15:06:57.879  3335  3394 I jxcore-log: # 143. #startUpdateAdvertisingAndListening should start hosting given router object
03-24 15:06:57.879  3335  3394 I jxcore-log: 
,03-24 15:06:58.081  3335  3394 I jxcore-log: ok 501 server should respond with code 200
03-24 15:06:58.081  3335  3394 I jxcore-log: 
,03-24 15:06:58.087  3335  3394 I jxcore-log: # teardown
03-24 15:06:58.087  3335  3394 I jxcore-log: 
,03-24 15:06:58.123  2162  2230 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 15:06:58.251  3335  3394 I jxcore-log: ok 502 should not be in started state
03-24 15:06:58.251  3335  3394 I jxcore-log: ,
03-24 15:06:58.256  3335  3394 I jxcore-log: # setup
03-24 15:06:58.256  3335  3394 I jxcore-log: 
,03-24 15:06:58.414  3335  3394 I jxcore-log: ok 503 should be in started state
,03-24 15:06:58.414  3335  3394 I jxcore-log: 
,03-24 15:06:58.422  3335  3394 I jxcore-log: # 144. #stop can be called multiple times in a row
,03-24 15:06:58.422  3335  3394 I jxcore-log: 
,03-24 15:06:58.572  3335  3394 I jxcore-log: ok 504 should be in stopped state
03-24 15:06:58.572  3335  3394 I jxcore-log: 
,03-24 15:06:58.580  3335  3394 I jxcore-log: ok 505 should still be in stopped state
,03-24 15:06:58.580  3335  3394 I jxcore-log: 
,03-24 15:06:58.584  3335  3394 I jxcore-log: # teardown
,03-24 15:06:58.584  3335  3394 I jxcore-log: 
,03-24 15:06:58.714  3335  3394 I jxcore-log: ok 506 should not be in started state
03-24 15:06:58.714  3335  3394 I jxcore-log: 
,03-24 15:06:58.721  3335  3394 I jxcore-log: # setup
03-24 15:06:58.721  3335  3394 I jxcore-log: 
,03-24 15:06:58.820  3335  3394 I jxcore-log: ok 507 should be in started state
03-24 15:06:58.820  3335  3394 I jxcore-log: 
,03-24 15:06:58.822  3335  3394 I jxcore-log: # 145. #startListeningForAdvertisements can be called multiple times in a row
03-24 15:06:58.822  3335  3394 I jxcore-log: 
,03-24 15:06:58.960  3335  3394 I jxcore-log: ok 508 should be in listening state
03-24 15:06:58.960  3335  3394 I jxcore-log: 
,03-24 15:06:58.962  3335  3394 I jxcore-log: ok 509 should still be in listening state
03-24 15:06:58.962  3335  3394 I jxcore-log: 
,03-24 15:06:58.964  3335  3394 I jxcore-log: # teardown
03-24 15:06:58.964  3335  3394 I jxcore-log: 
,03-24 15:06:59.141  3335  3394 I jxcore-log: ok 510 should not be in started state
03-24 15:06:59.141  3335  3394 I jxcore-log: 
,03-24 15:06:59.143  3335  3394 I jxcore-log: # setup
03-24 15:06:59.143  3335  3394 I jxcore-log: 
,03-24 15:06:59.319  3335  3394 I jxcore-log: ok 511 should be in started state
03-24 15:06:59.319  3335  3394 I jxcore-log: 
,03-24 15:06:59.329  3335  3394 I jxcore-log: # 146. #stopListeningForAdvertisements can be called multiple times in a row
,03-24 15:06:59.329  3335  3394 I jxcore-log: 
,03-24 15:06:59.463  3335  3394 I jxcore-log: ok 512 should not be in listening state
03-24 15:06:59.463  3335  3394 I jxcore-log: 
,03-24 15:06:59.469  3335  3394 I jxcore-log: ok 513 should still not be in listening state
03-24 15:06:59.469  3335  3394 I jxcore-log: 
,03-24 15:06:59.471  3335  3394 I jxcore-log: # teardown
03-24 15:06:59.471  3335  3394 I jxcore-log: 
,03-24 15:06:59.609  3335  3394 I jxcore-log: ok 514 should not be in started state
03-24 15:06:59.609  3335  3394 I jxcore-log: 
,03-24 15:06:59.612  3335  3394 I jxcore-log: # setup
03-24 15:06:59.612  3335  3394 I jxcore-log: 
,03-24 15:06:59.745  3335  3394 I jxcore-log: ok 515 should be in started state
03-24 15:06:59.745  3335  3394 I jxcore-log: 
,03-24 15:06:59.750  3335  3394 I jxcore-log: # 147. #stopAdvertisingAndListening can be called multiple times in a row,
03-24 15:06:59.750  3335  3394 I jxcore-log: 
,03-24 15:06:59.876  3335  3394 I jxcore-log: ok 516 should not be in advertising state,
03-24 15:06:59.876  3335  3394 I jxcore-log: 
03-24 15:06:59.877  3335  3394 I jxcore-log: ok 517 should still not be in advertising state
03-24 15:06:59.877  3335  3394 I jxcore-log: 
,03-24 15:06:59.880  3335  3394 I jxcore-log: # teardown
03-24 15:06:59.880  3335  3394 I jxcore-log: 
,03-24 15:07:00.001  3335  3394 I jxcore-log: ok 518 should not be in started state
03-24 15:07:00.001  3335  3394 I jxcore-log: 
,03-24 15:07:00.003  3335  3394 I jxcore-log: # setup
03-24 15:07:00.003  3335  3394 I jxcore-log: 
,03-24 15:07:00.193  3335  3394 I jxcore-log: ok 519 should be in started state
03-24 15:07:00.193  3335  3394 I jxcore-log: 
,03-24 15:07:00.198  3335  3394 I jxcore-log: # 148. functions are run from a queue in the right order
03-24 15:07:00.198  3335  3394 I jxcore-log: 
,03-24 15:07:00.392  3335  3394 I jxcore-log: ok 520 call order must match
03-24 15:07:00.392  3335  3394 I jxcore-log: 
,03-24 15:07:00.398  3335  3394 I jxcore-log: # teardown
03-24 15:07:00.398  3335  3394 I jxcore-log: 
,03-24 15:07:00.517  3335  3394 I jxcore-log: ok 521 should not be in started state
03-24 15:07:00.517  3335  3394 I jxcore-log: 
,03-24 15:07:00.524  3335  3394 I jxcore-log: # setup
03-24 15:07:00.524  3335  3394 I jxcore-log: 
,03-24 15:07:00.700  3335  3394 I jxcore-log: # 149. #ThaliPeerPoolDefault - single action
03-24 15:07:00.700  3335  3394 I jxcore-log: 
,03-24 15:07:00.843  3335  3394 I jxcore-log: ok 522 is an agent
03-24 15:07:00.843  3335  3394 I jxcore-log: 
,03-24 15:07:00.846  3335  3394 I jxcore-log: ok 523 enqueue is fine
03-24 15:07:00.846  3335  3394 I jxcore-log: 
,03-24 15:07:00.850  3335  3394 I jxcore-log: ok 524 Everything should be off the queue
03-24 15:07:00.850  3335  3394 I jxcore-log: 
,03-24 15:07:00.852  3335  3394 I jxcore-log: # teardown
03-24 15:07:00.852  3335  3394 I jxcore-log: 
,03-24 15:07:01.020  3335  3394 I jxcore-log: # setup
03-24 15:07:01.020  3335  3394 I jxcore-log: 
,03-24 15:07:01.155  3335  3394 I jxcore-log: # 150. #ThaliPeerPoolDefault - multiple actions
03-24 15:07:01.155  3335  3394 I jxcore-log: 
,03-24 15:07:01.272  3335  3394 I jxcore-log: ok 525 is an agent
03-24 15:07:01.272  3335  3394 I jxcore-log: 
,03-24 15:07:01.275  3335  3394 I jxcore-log: ok 526 first enqueue is fine
03-24 15:07:01.275  3335  3394 I jxcore-log: 
,03-24 15:07:01.280  3335  3394 I jxcore-log: ok 527 is an agent
03-24 15:07:01.280  3335  3394 I jxcore-log: 
,03-24 15:07:01.282  3335  3394 I jxcore-log: ok 528 second enqueue is fine
03-24 15:07:01.282  3335  3394 I jxcore-log: 
,03-24 15:07:01.291  3335  3394 I jxcore-log: ok 529 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-24 15:07:01.291  3335  3394 I jxcore-log: 
,03-24 15:07:01.292  3335  3394 I jxcore-log: ok 530 Queue is empty
03-24 15:07:01.292  3335  3394 I jxcore-log: 
,03-24 15:07:01.294  3335  3394 I jxcore-log: # teardown
03-24 15:07:01.294  3335  3394 I jxcore-log: 
,03-24 15:07:01.528  3335  3394 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-24 15:07:01.528  3335  3394 I jxcore-log: 
,03-24 15:07:01.834  4009  4009 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-24 15:07:01.837  4009  4009 D AndroidRuntime: CheckJNI is OFF
,03-24 15:07:01.951  4009  4009 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 15:07:01.967   823   857 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-24 15:07:01.968   823   857 I ActivityManager: Killing 3335:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-24 15:07:02.034   823   867 W PackageSettings: Skipping PackageSetting{35fa4340 com.example.hello/10273} due to missing metadata
,03-24 15:07:02.121   823  1035 D WifiService: Client connection lost with reason: 4
03-24 15:07:02.121   823   839 I WindowState: WIN DEATH: Window{2f02e229 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-24 15:07:02.186   823   857 W ActivityManager: Force removing ActivityRecord{1a9df9b u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-24 15:07:02.198   823   823 V ActivityManager: Display changed displayId=0
,03-24 15:07:02.207   823   867 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-24 15:07:02.234   823  1246 W ActivityManager: Spurious death for ProcessRecord{13282af1 3335:com.test.thalitest/u0a95}, curProc for 3335: null
,03-24 15:07:02.239  1234  1234 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 15:07:02.245   823  1019 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-24 15:07:02.246  1234  4023 I Keyboard.Facilitator.DecoderInitializer: run()
,03-24 15:07:02.250  3012  3012 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-24 15:07:02.258  1234  4023 I Decoder : createOrResetDecoder
03-24 15:07:02.259   823  1055 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-24 15:07:02.286  1075  1075 I art     : Explicit concurrent mark sweep GC freed 52476(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 850us total 55.202ms
,03-24 15:07:02.296   823  1310 I ActivityManager: Start proc 4025:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-24 15:07:02.324  1389  1389 I ConfigService: onCreate
,03-24 15:07:02.326   823   823 I art     : Explicit concurrent mark sweep GC freed 32254(1741KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.719ms total 96.518ms
03-24 15:07:02.331   823   867 I art     : WaitForGcToComplete blocked for 60.259ms for cause Explicit
,03-24 15:07:02.377   823  1094 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3335 uid 10095
,03-24 15:07:02.380  1234  1234 I Keyboard.Facilitator: onFinishInput()
,03-24 15:07:02.380  1234  4023 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 15:07:02.397   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 15:07:02.397   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 15:07:02.400  1234  4023 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-24 15:07:02.402  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 15:07:02.402  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 15:07:02.414  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-24 15:07:02.414  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-24 15:07:02.416  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-24 15:07:02.416  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-24 15:07:02.417  1234  4023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-24 15:07:02.417  1234  4023 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-24 15:07:02.417  1234  4023 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-24 15:07:02.417  1234  4023 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-24 15:07:02.417  1234  4023 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-24 15:07:02.417  1234  4023 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 15:07:02.437   823   867 I art     : Explicit concurrent mark sweep GC freed 8660(925KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.389ms total 99.367ms
,03-24 15:07:02.453  1314  1314 I art     : Explicit concurrent mark sweep GC freed 5085(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 2.049ms total 27.543ms
,03-24 15:07:02.457  4025  4056 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 15:07:02.475   823  1297 I ActivityManager: Start proc 4057:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-24 15:07:02.509  4009  4009 I art     : System.exit called, status: 0
03-24 15:07:02.509  4009  4009 I AndroidRuntime: VM exiting with result code 0.
,03-24 15:07:02.513  4025  4053 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-24 15:07:02.530   823  1246 I ActivityManager: Start proc 4078:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 15:07:02.577   823   867 I ActivityManager: Start proc 4096:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-24 15:07:02.586   823  1467 I ActivityManager: Killing 3700:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-24 15:07:02.607  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-24 15:07:02.814   823  1467 I ActivityManager: Killing 3663:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-24 15:07:02.821  1314  1314 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 15:07:02.822  1314  1314 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 15:07:02.830  3903  3903 W LocationOracleImpl: Best location was null
,03-24 15:07:02.835  1314  4118 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-24 15:07:02.849  3903  4049 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:07:02.849  3903  4049 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database ,in read/write mode.
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-24 15:07:02.849  3903  4049 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 15:07:02.851  3903  4049 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
,03-24 15:07:02.857  3903  3903 I VS.Container: create_recognizer
,03-24 15:07:02.859  4078  4119 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-24 15:07:02.859  4078  4119 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 15:07:02.860  3903  4121 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
--------- beginning of crash
03-24 15:07:02.860  4078  4119 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-24 15:07:02.860  4078  4119 E AndroidRuntime: Process: com.android.keychain, PID: 4078
03-24 15:07:02.860  4078  4119 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 15:07:02.860  4078,  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 15:07:02.860  4078  4119 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 15:07:02.877  4025  4053 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,03-24 15:07:02.885  4025  4053 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-24 15:07:02.885  4025  4053 E AndroidRuntime: Process: android.process.acore, PID: 4025
03-24 15:07:02.885  4025  4053 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 15:07:02.885  4025  4053 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 15:07:02.925  3903  4127 I HotwordRecognitionRnr: Starting hotword detection.
,03-24 15:07:02.929  3903  4128 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@3a7dc3b1
,03-24 15:07:02.932   358  4133 I AudioFlinger: AudioFlinger's thread 0xb4067000 ready to run
,03-24 15:07:02.935   358  1024 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 15:07:02.936  3903  4128 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@3a7dc3b1
,03-24 15:07:02.938   823  4131 E DropBoxManagerService: Can't write: system_app_crash
03-24 15:07:02.938   823  4131 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 15:07:02.938   823  4131 E DropBoxManagerService: 	... 5 more
03-24 15:07:02.938   823  4130 E DropBoxManagerService: Can't write: system_app_crash
03-24 15:07:02.938   823  4130 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 15:07:02.938   823  4130 E DropBoxManagerService: 	... 5 more
,03-24 15:07:02.940  1389  1389 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-24 15:07:02.941  1389  1389 D AndroidRuntime: Shutting down VM
03-24 15:07:02.941  1389  1389 E AndroidRuntime: FATAL EXCEPTION: main
03-24 15:07:02.941  1389  1389 E AndroidRuntime: Process: com.google.process.gapps, PID: 1389
03-24 15:07:02.941  1389  1389 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-24 15:07:02.941  1389  1389 E AndroidRuntime: 	... 9 more
,03-24 15:07:02.946   358  4133 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic),
03-24 15:07:02.946   358  4133 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-24 15:07:02.946   358  4133 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-24 15:07:02.946   358  4133 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-24 15:07:02.951   823  4135 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 15:07:02.952   823   857 D Atlas   : Validating map...
,03-24 15:07:02.958   358  4133 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-24 15:07:02.961   823  4136 E DropBoxManagerService: Can't write: system_app_crash
03-24 15:07:02.961   823  4136 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 15:07:02.961   823  4136 E DropBoxManagerService: 	... 5 more
,03-24 15:07:03.005  3903  4120 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-24 15:07:03.005  3903  4120 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 15:07:03.008   823  4135 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 15:07:03.014   823  4135 D OpenGLRenderer: Enabling debug mode 0
,03-24 15:07:03.017  3903  4141 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
03-24 15:07:03.017  3903  4141 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak

```
