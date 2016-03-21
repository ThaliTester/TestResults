#### Test 625481246894564_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,03-21 13:04:19.903  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 13:04:19.963  1254  1269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 13:04:19.964  1254  1269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:19.964  1254  1269 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:19.964  1254  1269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-21 13:04:19.974  1254  1269 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 13:04:20.006  2771  2771 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-21 13:04:20.007  2771  2771 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-21 13:04:20.007  2771  2771 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
--------- beginning of system
03-21 13:04:20.075   820   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
03-21 13:04:20.102   820   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-21 13:04:20.129   280   300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (258 us)
03-21 13:04:20.217  3294  3294 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 13:04:20.220  3294  3294 D AndroidRuntime: CheckJNI is OFF
03-21 13:04:20.378  3294  3294 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 13:04:20.381   820  1366 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 13:04:20.387   820  1366 V WindowManager: addAppToken: AppWindowToken{8079c29 token=Token{1b72e5b0 ActivityRecord{25d4d4f3 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-21 13:04:20.393   820   859 V WindowManager: Adding window Window{5f1bac8 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2b5dabb4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-21 13:04:20.405  1526  1526 I HotwordDetector: Closing mic
03-21 13:04:20.405  1526  1760 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1f50747e
03-21 13:04:20.423  3294  3294 D AndroidRuntime: Shutting down VM
03-21 13:04:20.460   820  1192 I ActivityManager: Start proc 3310:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-21 13:04:20.473   358  1769 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-21 13:04:20.475   358  1769 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-21 13:04:20.480   358  1028 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-21 13:04:20.482  1526  1766 I HotwordRecognitionRnr: Hotword detection finished
03-21 13:04:20.483  1526  1764 I HotwordRecognitionRnr: Stopping hotword detection.
03-21 13:04:20.490   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 330us total 29.461ms
03-21 13:04:20.511   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.759ms total 20.145ms
03-21 13:04:20.534   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 325us total 21.002ms
03-21 13:04:20.535   820   836 I ActivityManager: Killing 2934:com.android.settings/1000 (adj 15): empty #17
03-21 13:04:20.576   820  1272 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660904723
03-21 13:04:20.576   820  1272 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-21 13:04:20.642   820   836 I ActivityManager: Killing 2897:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-21 13:04:20.648   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
03-21 13:04:20.648   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-21 13:04:20.651   820   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-21 13:04:20.660   820   820 V ActivityManager: Display changed displayId=0
,03-21 13:04:20.662   875   875 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-21 13:04:20.662   875   875 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-21 13:04:20.703   875   875 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-21 13:04:20.704   875   875 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-21 13:04:20.761   820  1400 I art     : Explicit concurrent mark sweep GC freed 43422(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.599ms total 90.680ms
,03-21 13:04:20.813  3310  3310 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 13:04:20.913   280   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-21 13:04:20.914   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-21 13:04:20.915   820  1045 D SurfaceControl: Excessive delay in setPowerMode(): 267ms
,03-21 13:04:20.933   820   861 I DreamManagerService: Entering dreamland.
,03-21 13:04:20.934   820   861 I PowerManagerService: Dozing...
,03-21 13:04:20.936   358   358 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-21 13:04:20.936   358   358 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
03-21 13:04:20.936   820   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-21 13:04:20.943   820  1011 E WifiStateMachine: cancelDelayedScan -> 17
,03-21 13:04:20.947   820  1011 E native  : do suspend false
,03-21 13:04:20.956  3310  3310 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3571-3573)
,03-21 13:04:20.956  3310  3310 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 13:04:20.969  3310  3310 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {935f2b4}
03-21 13:04:20.970  3310  3310 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 13:04:20.970  3310  3310 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 13:04:20.983  3310  3310 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 13:04:20.984  3310  3310 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 13:04:20.985  3310  3310 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 13:04:20.992   820  1011 E WifiStateMachine: cancelDelayedScan -> 19
,03-21 13:04:21.000  3310  3339 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-21 13:04:21.001   820  1011 E native  : do suspend true
,03-21 13:04:21.006  3310  3310 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 13:04:21.011  3310  3310 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-21 13:04:21.011  3310  3310 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 13:04:21.012  3310  3310 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 13:04:21.080   358  1032 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-21 13:04:21.080   358  1032 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-21 13:04:21.104   820   858 D BluetoothManagerService: Message: 20
03-21 13:04:21.104   820   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a926309:true
,03-21 13:04:21.121  3310  3310 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 13:04:21.129  3310  3310 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 13:04:21.140  3310  3310 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-21 13:04:21.145  3310  3310 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 13:04:21.145  3310  3310 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 13:04:21.148   820  1011 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,03-21 13:04:21.193  3310  3362 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 13:04:21.198  3310  3310 D Atlas   : Validating map...
,03-21 13:04:21.204   820  1192 V WindowManager: Adding window Window{319d2079 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{5f1bac8 u0 Starting com.test.thalitest})
,03-21 13:04:21.207  3310  3348 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-21 13:04:21.256  3310  3362 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 13:04:21.283  3310  3362 D OpenGLRenderer: Enabling debug mode 0,
,03-21 13:04:21.368   820   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +953ms
,03-21 13:04:21.374  1236  1236 I Keyboard.Facilitator: onFinishInput()
,03-21 13:04:21.385  3310  3310 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3310
,03-21 13:04:21.399  3310  3310 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 13:04:21.532  3310  3310 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 13:04:21.699   875   875 I kickstart: STATUS: Received file 'm9kefs1'
03-21 13:04:21.699   875   875 I kickstart: STATUS: 950272 bytes transferred in 0.995138 seconds
03-21 13:04:21.699   875   875 I kickstart: STATUS: Successfully downloaded files from target 
03-21 13:04:21.699   875   875 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-21 13:04:21.702   875   875 I kickstart: STATUS: Sahara protocol completed,
,03-21 13:04:21.711  3310  3363 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580585088
,03-21 13:04:21.718  3310  3363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 13:04:21.718  3310  3363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 13:04:21.718  3310  3363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 13:04:21.718  3310  3363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 13:04:21.718  3310  3363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 13:04:21.718  3310  3363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12186ab9 added. We now have 1 listener(s)
,03-21 13:04:21.718   820  2393 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 13:04:21.722  3310  3363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-21 13:04:21.725  3310  3363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-21 13:04:21.726  3310  3363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 13:04:21.726  3310  3363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE,
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500,
03-21 13:04:21.731  3310  3363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cfc78ac added. We now have 1 listener(s)
03-21 13:04:21.731  3310  3363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 13:04:21.744   820  1012 D WifiService: New client listening to asynchronous messages
,03-21 13:04:21.746  3310  3363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 13:04:21.750  3310  3363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
03-21 13:04:21.750  3310  3363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2,
03-21 13:04:21.750  3310  3363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-21 13:04:21.750  3310  3363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2,
03-21 13:04:21.754  3310  3363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:04:21.755   820  1192 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-21 13:04:21.756  3310  3363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-21 13:04:21.765  3310  3363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-21 13:04:21.765  3310  3363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
03-21 13:04:21.765  3310  3363 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 13:04:21.768  3310  3310 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 13:04:21.770  3310  3363 I io.jxcore.node.LifeCycleMonitor: start: OK,
,03-21 13:04:21.790  3310  3310 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 13:04:22.149  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-21 13:04:22.150  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:22.406  3310  3372 W jxcore-log: Initializing JXcore engine
03-21 13:04:22.406  3310  3372 W jxcore-log: JXcore engine is ready
,03-21 13:04:22.437  3372  3372 W Thread-356: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10398]" dev="sockfs" ino=10398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-21 13:04:22.437  3372  3372 W Thread-356: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-21 13:04:22.437  3372  3372 W Thread-356: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12973]" dev="sockfs" ino=12973 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-21 13:04:22.437  3372  3372 W Thread-356: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21770]" dev="sockfs" ino=21770 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-21 13:04:22.458  3310  3372 W jxcore-log: Starting JXcore engine
,03-21 13:04:22.536  3310  3372 W jxcore-log: Platform android
03-21 13:04:22.536  3310  3372 W jxcore-log: 
03-21 13:04:22.536  3310  3372 W jxcore-log: Process ARCH arm
03-21 13:04:22.536  3310  3372 W jxcore-log: 
,03-21 13:04:22.722  3310  3372 I jxcore-log: JXcore Cordova bridge is ready!
03-21 13:04:22.722  3310  3372 I jxcore-log: ,
03-21 13:04:22.722  3310  3372 W jxcore-log: JXcore engine is started
,03-21 13:04:22.735  3310  3363 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 13:04:22.740  3310  3310 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 13:04:23.151  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-21 13:04:23.152  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:24.153  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-21 13:04:24.153  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:25.155  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-21 13:04:25.155  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:26.156  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-21 13:04:26.156  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:27.157  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-21 13:04:27.158  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:28.159  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-21 13:04:28.159  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:29.160  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-21 13:04:29.160  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:30.162  1146  1146 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-21 13:04:30.162  1146  1146 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-21 13:04:30.897   820  1011 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,03-21 13:04:32.029  3310  3372 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:04:32.029  3310  3372 I jxcore-log: 
,03-21 13:04:32.032  3310  3372 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:04:32.032  3310  3372 I jxcore-log: 
,03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-21 13:04:32.037  3310  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-21 13:04:32.041  3310  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-21 13:04:32.043  3310  3372 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:04:32.043  3310  3372 I jxcore-log: 
,03-21 13:04:32.045  3310  3372 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:04:32.045  3310  3372 I jxcore-log: 
,03-21 13:04:32.513  1146  1146 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-21 13:04:32.571  3310  3372 I jxcore-log: Unit Test app is loaded,
03-21 13:04:32.571  3310  3372 I jxcore-log: ,
,03-21 13:04:32.577  3310  3372 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-21 13:04:32.577  3310  3372 I jxcore-log: ,
,03-21 13:04:32.587  3310  3310 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 13:04:32.592  3310  3372 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-21 13:04:32.595  3310  3372 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 13:04:32.595  3310  3372 I jxcore-log: 
,03-21 13:04:32.596  3310  3372 I jxcore-log: My device name is: motorola-Nexus 6
03-21 13:04:32.596  3310  3372 I jxcore-log: 
,03-21 13:04:32.955  1146  1146 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-21 13:04:33.024  1146  1146 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-21 13:04:33.024  1146  1146 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-21 13:04:33.051   820  1011 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-21 13:04:33.052   820  1011 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 13:04:33.053   820  1014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-21 13:04:33.059   820  1011 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-21 13:04:33.064   354   814 D CommandListener: Setting iface cfg
,03-21 13:04:33.067   820  1011 E WifiStateMachine: Start Dhcp Watchdog 1
,03-21 13:04:33.073   820  1011 E WifiStateMachine:  WifiLinkLayerStats: 
03-21 13:04:33.073   820  1011 E WifiStateMachine:  my bss beacon rx: 1
03-21 13:04:33.073   820  1011 E WifiStateMachine:  RSSI mgmt: -46
03-21 13:04:33.073   820  1011 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-21 13:04:33.073   820  1011 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-21 13:04:33.073   820  1011 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-21 13:04:33.073   820  1011 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-21 13:04:33.073   820  1011 E WifiStateMachine:  on_time : 0 tx_time=64 rx_time=98 scan_time=0
,03-21 13:04:33.180   820  1011 E native  : do suspend false
,03-21 13:04:33.191   820  1011 E WifiStateMachine: scanCount==0 - aborting
,03-21 13:04:33.437  3376  3376 I dhcpcd  : version 5.5.6 starting
,03-21 13:04:33.551  3376  3376 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-21 13:04:33.593  3376  3376 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-21 13:04:33.643  3376  3376 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-21 13:04:34.013   820  1011 E native  : do suspend true
,03-21 13:04:34.063   820  1014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-21 13:04:34.067   820  1011 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
03-21 13:04:34.067   820  1014 D ConnectivityService: Adding iface wlan0 to network 100
,03-21 13:04:34.090   820  1014 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-21 13:04:34.091   820  1014 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-21 13:04:34.093   820  1014 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-21 13:04:34.095   820  1014 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-21 13:04:34.100   820  1014 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-21 13:04:34.110   820  1014 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-21 13:04:34.114   820  1014 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-21 13:04:34.114   820  3374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-21 13:04:34.114   820  3374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
,03-21 13:04:34.115   820  3374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-21 13:04:34.115   820  3374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-21 13:04:34.119   820  1014 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 13:04:34.119   820  1014 D ConnectivityService:    accepting network in place of null
,03-21 13:04:34.120   820  1014 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-21 13:04:34.121   820  1014 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-21 13:04:34.124   820  1014 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-21 13:04:34.125   820  1014 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,03-21 13:04:34.125  1066  1545 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-21 13:04:34.125   820  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-21 13:04:34.126   820  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-21 13:04:34.129   820   858 D Tethering: MasterInitialState.processMessage what=3
,03-21 13:04:34.134   820  1397 V BackupManagerService: Scheduling immediate backup pass
,03-21 13:04:34.137   820   820 V BackupManagerService: Running a backup pass
,03-21 13:04:34.138   820  1043 V BackupManagerService: clearing pending backups
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:04:34.138  3310  3310 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:04:34.143  2953  2953 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-21 13:04:34.145  1526  1526 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
03-21 13:04:34.147  3310  3310 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:04:34.151  2953  2953 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-21 13:04:34.161  1300  1546 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-21 13:04:34.161  1300  1546 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-21 13:04:34.162   820  1043 V PerformBackupTask: Beginning backup of 14 targets
,03-21 13:04:34.163   820   853 D TelephonyManager: getDataEnabled: retVal=false
,03-21 13:04:34.171   820  1043 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-21 13:04:34.180   820  1043 V BackupServiceBinder: doBackup() invoked
,03-21 13:04:34.182   820  1043 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-21 13:04:34.195   820  1253 I ActivityManager: Start proc 3418:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-21 13:04:34.203   820   853 E GpsLocationProvider: No APN found to select.
,03-21 13:04:34.207   820  1043 I BackupRestoreController: Getting widget state for user: 0
,03-21 13:04:34.263  1809  1896 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-21 13:04:34.265  1809  1896 V GmsBackupTransport: starting performBackup for @pm@
,03-21 13:04:34.277  1809  1896 V GmsBackupTransport: performBackup done for @pm@
,03-21 13:04:34.284  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:34.304  1254  1653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-21 13:04:34.304  1254  1653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:34.304  1254  1653 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:34.304  1254  1653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:34.327   820  2393 I ActivityManager: Start proc 3448:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-21 13:04:34.330  1254  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:34.366  1254  1653 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:34.366  1254  1653 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:34.366  1254  1653 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:34.366  1254  1653 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 13:04:34.366  1254  1653 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 13:04:34.366  1254  1653 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 13:04:34.366  1254  1653 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 13:04:34.373  1809  1825 W GmsBackupTransport: Error sending final backup to server: 
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 13:04:34.373  1809  1825 W GmsBackupTransport: 	... 1 more
,03-21 13:04:34.374   820  1043 D BackupManagerService: Now staging backup of com.google.android.talk
,03-21 13:04:34.377  3448  3448 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-21 13:04:34.407  3448  3448 D SprintDMHelper: simOperator:  IMSI: null
03-21 13:04:34.408  3448  3448 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-21 13:04:34.417   820  1043 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-21 13:04:34.419   820  1043 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-21 13:04:34.421   820  1043 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-21 13:04:34.424   820  1043 D BackupManagerService: Now staging backup of com.google.android.gm
,03-21 13:04:34.435   820  1043 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-21 13:04:34.437   820  1043 D BackupManagerService: Now staging backup of com.android.nfc
,03-21 13:04:34.440   820  1043 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-21 13:04:34.444   820  1043 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-21 13:04:34.447   820  1043 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-21 13:04:34.451   820  1043 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-21 13:04:34.452   820  1043 D BackupManagerService: Now staging backup of com.android.vending
,03-21 13:04:34.455   820  1043 D BackupManagerService: Now staging backup of android
,03-21 13:04:34.456  1770  1770 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-21 13:04:34.458   820  1043 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-21 13:04:34.461  1770  1770 D SystemUpdateService: onCreate
,03-21 13:04:34.462  1809  1872 I GmsBackupTransport: Next backup will happen in 43199906 millis.
,03-21 13:04:34.463  1770  3459 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
03-21 13:04:34.464   820  1043 I BackupManagerService: Backup pass finished.
,03-21 13:04:34.465  1770  1770 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-21 13:04:34.467  1770  3476 I SystemUpdateService: active receiver: enabled
,03-21 13:04:34.465  1770  3475 W DriveInitializer: Background init thread started
,03-21 13:04:34.470  1770  3476 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-21 13:04:34.472  1770  3476 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
,03-21 13:04:34.472  1770  3476 I SystemUpdateService: now status is 0 (complete)
03-21 13:04:34.472  1770  3476 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-21 13:04:34.472  1770  3476 I SystemUpdateService: file has been verified
03-21 13:04:34.473  1770  3476 I SystemUpdateService: OTA package size = 25802302
,03-21 13:04:34.474  1770  3476 I SystemUpdateService: showing system update notification
,03-21 13:04:34.477  1770  3477 W DriveInitializer: Awaiting to be initialized
,03-21 13:04:34.502  1254  1721 I art     : Explicit concurrent mark sweep GC freed 23767(1304KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 669us total 21.929ms
,03-21 13:04:34.511   820  3374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Mar 2016 12:04:34 GMT], X-Android-Received-Millis=[1458561874511], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458561874401]}
03-21 13:04:34.512   820  3374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-21 13:04:34.512   820  1014 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-21 13:04:34.512   820  1014 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-21 13:04:34.512   820  1014 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-21 13:04:34.512   820  1014 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-21 13:04:34.512   820  1014 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-21 13:04:34.513   820  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-21 13:04:34.513  1066  1545 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 13:04:34.521   820   820 I ValidateNoPeople: skipping global notification
,03-21 13:04:34.543  1770  3487 I iu.SyncManager: SYNC; picasa accounts
,03-21 13:04:34.590  1770  1770 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-21 13:04:34.593  1770  3475 W DriveInitializer: Background init thread ended
,03-21 13:04:34.595  1770  1770 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-21 13:04:34.599  1770  3487 I iu.UploadsManager: num queued entries: 0
03-21 13:04:34.599  1770  3487 I iu.UploadsManager: num updated entries: 0
,03-21 13:04:34.600  1770  3487 I iu.SyncManager: NEXT; no task
,03-21 13:04:34.602  1770  1770 D SystemUpdateService: onDestroy
,03-21 13:04:34.647   820  3454 D GpsLocationProvider: NTP server returned: 1458561874898 (Mon Mar 21 13:04:34 GMT+01:00 2016) reference: 177264 certainty: 23 system time offset: 251
,03-21 13:04:34.647   820  1277 D AlarmManagerService: Setting time of day to sec=1458561874
03-21 13:04:34.899   820  1277 W AlarmManagerService: Unable to set rtc to 1458561874: Invalid argument
,03-21 13:04:34.908  1254  2600 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-21 13:04:34.908  1254  2600 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:34.908  1254  2600 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:34.908  1254  2600 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:34.911  1254  2600 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:34.936  3128  3473 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-21 13:04:34.936  3128  3473 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jdm.a(PG:82)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jcs.o(PG:406)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jcn.a(PG:1379)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jcs.i(PG:143)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at blb.a(PG:3937)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at czp.a(PG:18188)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at czp.a(PG:9081)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at czq.run(PG:1686)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 13:04:34.936  3128  3473 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jdj.a(PG:4091)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jdj.a(PG:1125)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jdm.a(PG:77)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	... 12 more
03-21 13:04:34.936  3128  3473 E HttpOperation: Caused by: faj: BadAuthentication
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at fal.a(PG:38)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	at jdj.a(PG:4089)
03-21 13:04:34.936  3128  3473 E HttpOperation: 	... 14 more
,03-21 13:04:34.937  1770  1770 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
03-21 13:04:34.940  1770  1770 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
03-21 13:04:34.968   820   835 I ActivityManager: Start proc 3500:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-21 13:04:34.986  1254  1269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-21 13:04:34.986  1254  1269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:34.986  1254  1269 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:34.986  1254  1269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:35.002   820   853 I ActivityManager: Start proc 3519:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-21 13:04:35.008  1254  1269 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:35.022  3128  3473 E HttpOperation: [getmobileexperiments] Unexpected exception
03-21 13:04:35.022  3128  3473 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jdm.a(PG:82)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jcs.o(PG:406)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jcn.a(PG:1379)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jcs.i(PG:143)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at hec.a(PG:42)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at hee.a(PG:102)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at czr.a(PG:65)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at kka.a(PG:108)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at czp.a(PG:19176)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at czp.a(PG:9081)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at czq.run(PG:1686)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 13:04:35.022  3128  3473 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jdj.a(PG:4091)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jdj.a(PG:1125)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jdm.a(PG:77)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	... 15 more
03-21 13:04:35.022  3128  3473 E HttpOperation: Caused by: faj: BadAuthentication
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at fal.a(PG:38)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	at jdj.a(PG:4089)
03-21 13:04:35.022  3128  3473 E HttpOperation: 	... 17 more
03-21 13:04:35.022  3128  3473 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-21 13:04:35.022  3128  3473 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jdm.a(PG:82)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jcs.o(PG:406)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jcn.a(PG:1379)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jcs.i(PG:143)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at hec.a(PG:42)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at hee.a(PG:102)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at czr.a(PG:65)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at kka.a(PG:108)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at czp.a(PG:19176)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at czp.a(PG:9081)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at czq.run(PG:1686)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jdj.a(PG:4091)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jdm.a(PG:77)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	... 15 more
03-21 13:04:35.022  3128  3473 E ExperimentLoader: Caused by: faj: BadAuthentication
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at fal.a(PG:38)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	at jdj.a(PG:4089)
03-21 13:04:35.022  3128  3473 E ExperimentLoader: 	... 17 more
,03-21 13:04:35.130   820  1253 I ActivityManager: Killing 2443:com.google.android.apps.maps/u0a65 (adj 15): empty #17
03-21 13:04:35.131   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37395, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-21 13:04:35.181   820  2599 I art     : Explicit concurrent mark sweep GC freed 54417(2MB) AllocSpace objects, 8(168KB) LOS objects, 32% free, 33MB/49MB, paused 1.278ms total 53.538ms
,03-21 13:04:35.246  1254  3535 D GCM     : Connected
,03-21 13:04:35.250  3195  3498 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-21 13:04:35.254   820  1299 I ActivityManager: Killing 3017:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-21 13:04:35.265  3500  3500 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-21 13:04:35.265  3500  3500 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 13:04:35.265  3500  3500 I GAv4    :   adb logcat -s GAv4
,03-21 13:04:35.371  3500  3500 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:35.394  1254  3535 D GCM     : Message class com.google.f.a.a.p
,03-21 13:04:35.394  3500  3500 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:35.409   820   853 I ActivityManager: Start proc 3545:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-21 13:04:35.452  3500  3564 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:35.515  3519  3567 V KeepSync: Connecting to GoogleApiClient
,03-21 13:04:35.565  1770  3581 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 13:04:35.570  1770  3581 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 13:04:35.591  1254  1269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-21 13:04:35.591  1254  1269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:35.591  1254  1269 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:35.591  1254  1269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:35.594  1254  1269 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: Handling authorization failure
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-21 13:04:35.606  1770  3581 E ClientConnectionOperation: 	... 7 more
03-21 13:04:35.607  3519  3567 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-21 13:04:35.609  3519  3567 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 13:04:35.612  3519  3567 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 13:04:35.612  3519  3567 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-21 13:04:35.641  3500  3500 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 13:04:35.650  3500  3500 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8015-8016)
03-21 13:04:35.650  3500  3500 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 13:04:35.653  3500  3500 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c32076b}
,03-21 13:04:35.654  3500  3500 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 13:04:35.654  3500  3500 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 13:04:35.662  3500  3500 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 13:04:35.662  3500  3500 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 13:04:35.663  3500  3500 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 13:04:35.674  3500  3500 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 13:04:35.679  3500  3500 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 13:04:35.679  3500  3500 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 13:04:35.679  3500  3500 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-21 13:04:35.729  3500  3598 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-21 13:04:35.745  3500  3500 I NSApplication: Starting up...
,03-21 13:04:35.769  1254  2600 I art     : Explicit concurrent mark sweep GC freed 14553(827KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 980us total 39.002ms
,03-21 13:04:35.773   820   835 I ActivityManager: Start proc 3604:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-21 13:04:35.805  1254  2600 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-21 13:04:35.805  1254  2600 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:35.805  1254  2600 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:35.805  1254  2600 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:35.809  1254  2600 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:35.845  3519  3567 E KeepSync: IOException
03-21 13:04:35.845  3519  3567 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-21 13:04:35.845  3519  3567 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-21 13:04:35.845  3519  3567 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-21 13:04:35.845  3519  3567 E KeepSync: 	... 10 more
03-21 13:04:35.846  3519  3567 W KeepSync: Sync result 2
,03-21 13:04:35.851   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37400, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-21 13:04:35.852   820   836 I ActivityManager: Killing 3037:com.android.musicfx/u0a18 (adj 15): empty #17
,03-21 13:04:36.024  3545  3545 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 13:04:36.034  3545  3545 I BooksApp: Created application version: 3.6.8 (30608)
,03-21 13:04:36.086  3545  3630 I BooksSync: Starting books sync for 61035162, extras: ade
,03-21 13:04:36.183   820  1103 I ActivityManager: Start proc 3637:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-21 13:04:36.184   820  1103 I ActivityManager: Killing 3086:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-21 13:04:36.207  3545  3656 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-21 13:04:36.259  1254  2600 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 13:04:36.260  1254  2600 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:36.260  1254  2600 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:36.260  1254  2600 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:36.262  1254  2600 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:36.277  1770  3657 I ReminderSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=217:priority=5:group=main]
,03-21 13:04:36.311  1254  1653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-21 13:04:36.311  1254  1653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:36.311  1254  1653 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:36.311  1254  1653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:36.314  1254  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:36.326  3545  3656 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-21 13:04:36.327  3545  3630 E BooksSync: Soft error
03-21 13:04:36.327  3545  3630 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
03-21 13:04:36.327  3545  3630 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 13:04:36.327  3545  3630 E BooksSync: Sync error
03-21 13:04:36.327  3545  3630 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-21 13:04:36.327  3545  3630 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-21 13:04:36.327  3545  3630 I BooksSync: Finished books sync
,03-21 13:04:36.332   820   836 I ActivityManager: Killing 2809:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-21 13:04:36.334   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37401, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-21 13:04:36.422   820   853 I ActivityManager: Start proc 3659:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,03-21 13:04:36.433  1770  3658 I PeopleSync: onPerformSync() [5005f081]
,03-21 13:04:36.544  1770  3676 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-21 13:04:36.551  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:36.635  1770  3658 I art     : Explicit concurrent mark sweep GC freed 16640(1211KB) AllocSpace objects, 18(288KB) LOS objects, 21% free, 29MB/37MB, paused 676us total 35.348ms
,03-21 13:04:36.686  1770  3658 I PeopleSync: Setting subscription: result=true [5005f081]
,03-21 13:04:36.686  1770  3658 I PeopleSync: Starting sync, feed=null [5005f081]
,03-21 13:04:36.760   820  2393 I art     : Explicit concurrent mark sweep GC freed 27717(1224KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 6.784ms total 56.971ms
,03-21 13:04:36.824  1770  3658 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 13:04:36.831  1770  3658 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 13:04:36.856  1770  3658 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 13:04:36.866  1770  3658 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,03-21 13:04:36.911  1254  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,03-21 13:04:36.912  1254  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-21 13:04:36.912  1254  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:36.912  1254  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:36.915   820  1192 I ActivityManager: Killing 2460:android.process.acore/u0a5 (adj 15): empty #17
,03-21 13:04:37.067  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 13:04:37.067  3310  3372 I jxcore-log: 
,03-21 13:04:37.137  1254  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:37.192  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:37.213  1770  3658 I PeopleSync: Sync finished, successful=false, took 337ms
,03-21 13:04:37.264  1770  1770 V Herrevad: NQAS connected
,03-21 13:04:37.301   820  1192 I ActivityManager: Start proc 3684:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-21 13:04:37.323  1254  3702 I VacuumService: Vacuum at: now=1458561877323 tag=VacuumService
,03-21 13:04:37.330   820  1012 D WifiService: New client listening to asynchronous messages
,03-21 13:04:37.337  1254  1653 I art     : Explicit concurrent mark sweep GC freed 16067(954KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.184ms total 23.403ms
,03-21 13:04:37.342  1770  3658 I PeopleSync: Cannot authenticate [5005f081]
03-21 13:04:37.342  1770  3658 I PeopleSync: com.google.android.gms.auth.ad: BadAuthentication
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.people.service.g.b(SourceFile:171)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
03-21 13:04:37.342  1770  3658 I PeopleSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,03-21 13:04:37.377  3418  3682 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-21 13:04:37.385  3684  3684 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458561877385
03-21 13:04:37.385  3684  3684 D         : TimeServiceNative: User Time to be set is 1458561877385
03-21 13:04:37.385  3684  3684 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-21 13:04:37.385  3684  3684 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-21 13:04:37.385  3684  3684 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458561877385
03-21 13:04:37.385  3684  3684 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-21 13:04:37.385   373   879 D QC-time-services: Daemon: Connection accepted:time_genoff
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458561877385
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458561877385, operation = 0
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/7/70 8:16:21
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:Value read from RTC seconds = 18864981000
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:new time 1458561877385 
,03-21 13:04:37.386   373  3707 D QC-time-services: Daemon: delta 1439696896385 genoff 1439696896385 
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896385 to memory
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-21 13:04:37.386   373  3707 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 13:04:37.389   373  3707 D QC-time-services: Updating the TOD offset
03-21 13:04:37.390   373  3707 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896385 to memory
03-21 13:04:37.390   373  3707 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-21 13:04:37.390   373  3707 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 13:04:37.395   373  3707 E QC-time-services: Daemon:Update to modem bit set
03-21 13:04:37.395   373  3707 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-21 13:04:37.395   373  3707 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142597077385
,03-21 13:04:37.395  3684  3684 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-21 13:04:37.419  3659  3677 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
03-21 13:04:37.419  3659  3677 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 13:04:37.419  3659  3677 I GAv4    :   adb logcat -s GAv4
,03-21 13:04:37.454   820  1299 I ActivityManager: Start proc 3712:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-21 13:04:37.460  3659  3677 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:37.463   373   879 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-21 13:04:37.468   373   877 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-21 13:04:37.474  3659  3677 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:37.500  3659  3677 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,03-21 13:04:37.514  1770  3658 I PeopleSync: ***Sync finished***, duration: 1079 [5005f081]
,03-21 13:04:37.519  3659  3729 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:37.525  1254  1653 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-21 13:04:37.527  1254  1653 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:37.527  1254  1653 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:37.527  1254  1653 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:37.531  1254  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:37.543   820   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 37437, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-21 13:04:37.544   820   853 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 210438, reason: Periodic
,03-21 13:04:37.555  3712  3712 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 13:04:37.555  3712  3712 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 13:04:37.555  3712  3712 I GAv4    :   adb logcat -s GAv4
,03-21 13:04:37.556  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 13:04:37.556  3310  3372 I jxcore-log: 
,03-21 13:04:37.569  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-21 13:04:37.569  3310  3372 I jxcore-log: 
,03-21 13:04:37.572  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 13:04:37.572  3310  3372 I jxcore-log: 
,03-21 13:04:37.588   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 8.984ms
,03-21 13:04:37.593   820   853 I ActivityManager: Start proc 3744:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,03-21 13:04:37.599   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.704ms
,03-21 13:04:37.608   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 8.825ms
,03-21 13:04:37.611  3712  3712 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:37.612  3418  3682 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-21 13:04:37.613  3418  3682 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-21 13:04:37.619  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 13:04:37.619  3310  3372 I jxcore-log: 
,03-21 13:04:37.634   820  2599 I ActivityManager: Killing 2829:com.google.android.gm/u0a78 (adj 15): empty #17
,03-21 13:04:37.636  3712  3712 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:37.637  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 13:04:37.637  3310  3372 I jxcore-log: 
03-21 13:04:37.641  3712  3766 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-21 13:04:37.641  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 13:04:37.641  3310  3372 I jxcore-log: 
,03-21 13:04:37.664   820  1253 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3b8659}
,03-21 13:04:37.790  3195  3195 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:37.791  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:37.794  3195  3195 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:37.802  1254  3771 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 13:04:37.822  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:37.845  1770  1770 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-21 13:04:37.845  1770  1770 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-21 13:04:37.853  1770  1770 W PlaySystemBroadcastReceiver: Processed handlePeopleChanged at 180212
,03-21 13:04:37.860  1770  1770 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-21 13:04:37.860  1770  1770 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-21 13:04:37.876  1770  3779 W DataBroker: No player ID found and calling context is not the dest app
,03-21 13:04:37.941  1770  3779 E SQLiteLog: (284) automatic index on invitations(external_inviter_id)
03-21 13:04:37.941  3659  3735 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:37.941  3659  3735 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:37.946  3659  3768 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:37.946  3659  3768 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:37.988  3659  3735 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 13:04:37.995  1254  2600 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-21 13:04:37.996  1254  2600 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:37.996  1254  2600 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:37.996  1254  2600 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:38.003  1254  2600 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:38.018  3195  3776 E Babel   : UserRecoverableAuthException.
03-21 13:04:38.018  3195  3776 E Babel   : eei: BadAuthentication
03-21 13:04:38.018  3195  3776 E Babel   : 	at eeg.a(Unknown Source)
03-21 13:04:38.018  3195  3776 E Babel   : 	at eeg.a(Unknown Source)
03-21 13:04:38.018  3195  3776 E Babel   : 	at eeg.a(Unknown Source)
03-21 13:04:38.018  3195  3776 E Babel   : 	at g.a(Unknown Source)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cae.a(SourceFile:3089)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cae.a(SourceFile:1131)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cws.a(SourceFile:4333)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cws.a(SourceFile:1419)
03-21 13:04:38.018  3195  3776 E Babel   : 	at crl.a(SourceFile:492)
03-21 13:04:38.018  3195  3776 E Babel   : 	at crl.a(SourceFile:1468)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cas.b(SourceFile:106)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cap.d(SourceFile:335)
03-21 13:04:38.018  3195  3776 E Babel   : 	at caq.run(SourceFile:81)
03-21 13:04:38.018  3195  3776 E Babel   : Error getting auth token
03-21 13:04:38.018  3195  3776 E Babel   : dvm
03-21 13:04:38.018  3195  3776 E Babel   : 	at g.a(Unknown Source)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cae.a(SourceFile:3089)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cae.a(SourceFile:1131)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cws.a(SourceFile:4333)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cws.a(SourceFile:1419)
03-21 13:04:38.018  3195  3776 E Babel   : 	at crl.a(SourceFile:492)
03-21 13:04:38.018  3195  3776 E Babel   : 	at crl.a(SourceFile:1468)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cas.b(SourceFile:106)
03-21 13:04:38.018  3195  3776 E Babel   : 	at cap.d(SourceFile:335)
03-21 13:04:38.018  3195  3776 E Babel   : 	at caq.run(SourceFile:81)
,03-21 13:04:38.024  3195  3776 E Babel   : Account registration failed 1-Redacted-21
03-21 13:04:38.024  3195  3776 E Babel   : cyp: null -- null
03-21 13:04:38.024  3195  3776 E Babel   : 	at cae.a(SourceFile:3121)
03-21 13:04:38.024  3195  3776 E Babel   : 	at cae.a(SourceFile:1131)
03-21 13:04:38.024  3195  3776 E Babel   : 	at cws.a(SourceFile:4333)
03-21 13:04:38.024  3195  3776 E Babel   : 	at cws.a(SourceFile:1419)
03-21 13:04:38.024  3195  3776 E Babel   : 	at crl.a(SourceFile:492)
03-21 13:04:38.024  3195  3776 E Babel   : 	at crl.a(SourceFile:1468)
03-21 13:04:38.024  3195  3776 E Babel   : 	at cqu.a(SourceFile:4416)
03-21 13:04:38.024  3195  3776 E Babel   : 	at cas.b(SourceFile:106)
03-21 13:04:38.024  3195  3776 E Babel   : 	at cap.d(SourceFile:335)
03-21 13:04:38.024  3195  3776 E Babel   : 	at caq.run(SourceFile:81)
,03-21 13:04:38.044  3195  3776 I art     : Note: end time exceeds epoch: 
03-21 13:04:38.039  3659  3735 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 13:04:38.084   820  1192 I art     : Explicit concurrent mark sweep GC freed 18623(860KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 1.394ms total 48.802ms
,03-21 13:04:38.097  1254  1721 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-21 13:04:38.097  1254  1721 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:38.097  1254  1721 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:38.097  1254  1721 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:38.105  1254  1721 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:38.114  1254  1721 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 13:04:38.126  3195  3792 E Babel   : Unexpected exception while authenticating.
,03-21 13:04:38.127  3195  3792 E Babel   : eej: User intervention required. Notification has been pushed.
03-21 13:04:38.127  3195  3792 E Babel   : 	at eeg.b(Unknown Source)
03-21 13:04:38.127  3195  3792 E Babel   : 	at eeg.b(Unknown Source)
03-21 13:04:38.127  3195  3792 E Babel   : 	at g.a(Unknown Source)
03-21 13:04:38.127  3195  3792 E Babel   : 	at cae.b(SourceFile:1146)
03-21 13:04:38.127  3195  3792 E Babel   : 	at dcg.run(SourceFile:5617)
03-21 13:04:38.127  3195  3792 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 13:04:38.127  3195  3792 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 13:04:38.127  3195  3792 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-21 13:04:38.374  3744  3744 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-21 13:04:38.374  3744  3744 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 13:04:38.374  3744  3744 I GAv4    :   adb logcat -s GAv4
,03-21 13:04:38.392  3744  3744 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:38.404  3744  3744 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:38.409  3744  3744 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
03-21 13:04:38.410  3744  3802 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:38.506  3744  3809 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:38.506  3744  3809 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:38.540  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:38.551  3744  3809 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 13:04:38.587  3744  3809 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 13:04:38.608   820  1400 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@325a33e2}
,03-21 13:04:38.625  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:38.658  1254  3771 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 13:04:38.658  1254  3771 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:38.658  1254  3771 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:38.658  1254  3771 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:38.660  1254  3771 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:38.698  1254  3771 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 13:04:38.698  1254  3771 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 13:04:38.698  1254  3771 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 13:04:38.829  1254  3771 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 13:04:38.829  1254  3771 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:38.829  1254  3771 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:38.829  1254  3771 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:38.833  1254  3771 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:38.871  1254  3771 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 13:04:38.871  1254  3771 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 13:04:38.871  1254  3771 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 13:04:38.976  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:39.156  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:39.164  1254  3771 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 13:04:39.164  1254  3771 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:39.164  1254  3771 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:39.164  1254  3771 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:39.168  1254  3771 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:39.175  1254  2600 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.sheets, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
03-21 13:04:39.175  1254  2600 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:39.175  1254  2600 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:39.175  1254  2600 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:39.178  1254  2600 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:39.194  1254  3771 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
,03-21 13:04:39.194  1254  3771 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 13:04:39.194  1254  3771 E Uploader: ,	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 13:04:39.194  1254  3771 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 13:04:39.208  1254  2600 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:39.208  1254  2600 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:39.208  1254  2600 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599),
03-21 13:04:39.208  1254  2600 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 13:04:39.208  1254  2600 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 13:04:39.208  1254  2600 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 13:04:39.208  1254  2600 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
03-21 13:04:39.209  3659  3768 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
03-21 13:04:39.209  3659  3768 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
,03-21 13:04:39.212  3659  3768 E BaseSyncManager: AuthenticatorException,
03-21 13:04:39.212  3659  3768 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 13:04:39.212  3659  3768 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 13:04:39.212  3659  3768 E BaseSyncManager: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 13:04:39.212  3659  3768 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 13:04:39.212  3659  3768 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 13:04:39.212  3659  3768 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 13:04:39.215   820  1400 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3b8659}
,03-21 13:04:39.223   820  1253 I ActivityManager: Killing 3058:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-21 13:04:39.332   820   853 I ActivityManager: Start proc 3840:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,03-21 13:04:39.344  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:39.373  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:39.404  1254  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
03-21 13:04:39.404  1254  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:39.404  1254  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:39.404  1254  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:39.409  1254  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:39.439  1254  1722 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:39.439  1254  1722 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:39.439  1254  1722 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:39.439  1254  1722 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 13:04:39.439  1254  1722 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 13:04:39.439  1254  1722 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 13:04:39.439  1254  1722 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
03-21 13:04:39.440  3744  3822 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
,03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: java.io.IOException
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at fur.b(PG:162)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at fup.b(PG:6072)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at gtb.b(PG:213)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at gtb.a(PG:125)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at gyh.a(PG:224)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:618)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at gtm.run(PG:2507)
03-21 13:04:39.448  3744  3822 E DefaultHttpIssuer: 	at gtk.run(PG:3031)
,03-21 13:04:39.449  3744  3822 E BaseSyncManager: AuthenticatorException
03-21 13:04:39.449  3744  3822 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 13:04:39.449  3744  3822 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 13:04:39.449  3744  3822 E BaseSyncManager: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 13:04:39.449  3744  3822 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 13:04:39.449  3744  3822 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 13:04:39.449  3744  3822 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 13:04:39.452   820  1253 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@325a33e2}
,03-21 13:04:39.460   820  1397 I ActivityManager: Killing 2771:com.android.vending/u0a19 (adj 15): empty #17
,03-21 13:04:39.693  1254  3771 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-21 13:04:39.693  1254  3771 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:39.693  1254  3771 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-21 13:04:39.694  1254  3771 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-21 13:04:39.697  1254  3771 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:39.724  1254  3771 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 13:04:39.724  1254  3771 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 13:04:39.724  1254  3771 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 13:04:39.756  3840  3840 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-21 13:04:39.756  3840  3840 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 13:04:39.756  3840  3840 I GAv4    :   adb logcat -s GAv4
,03-21 13:04:39.767  3840  3840 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:39.776  3840  3840 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:39.787  3840  3868 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 13:04:39.791  3840  3840 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-21 13:04:39.808  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:39.883  3840  3874 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:39.883  3840  3840 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:39.884  3840  3874 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 13:04:39.884  3840  3840 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:39.902  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:39.935  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 13:04:39.935  3310  3372 I jxcore-log: 
,03-21 13:04:39.940  3840  3840 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 13:04:39.952  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-21 13:04:39.952  3310  3372 I jxcore-log: 
,03-21 13:04:39.958  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-21 13:04:39.958  3310  3372 I jxcore-log: 
,03-21 13:04:39.970  3840  3840 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 13:04:39.994   820  1299 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2e28178f}
,03-21 13:04:40.000  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:40.017  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:40.050   820  1000 I ActivityManager: Start proc 3882:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,03-21 13:04:40.098  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-21 13:04:40.098  3310  3372 I jxcore-log: 
,03-21 13:04:40.128  3882  3882 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 13:04:40.153  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-21 13:04:40.153  3310  3372 I jxcore-log: 
,03-21 13:04:40.167  3882  3882 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-21 13:04:40.222   820  1397 I ActivityManager: Start proc 3919:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-21 13:04:40.232  1254  3771 W Uploader:  no longer exists, so no auth token.
,03-21 13:04:40.232  3882  3882 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 13:04:40.233  3882  3882 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 13:04:40.260  3919  3919 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:40.260  3919  3919 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:40.278  3919  3919 I MultiDex: VM with version 2.1.0 has multidex support
,03-21 13:04:40.278  3919  3919 I MultiDex: install
03-21 13:04:40.278  3919  3919 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 13:04:40.282  1254  2600 I art     : Explicit concurrent mark sweep GC freed 49064(2MB) AllocSpace objects, 8(722KB) LOS objects, 36% free, 28MB/44MB, paused 1.029ms total 25.272ms
,03-21 13:04:40.292  3919  3919 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 13:04:40.300  3882  3882 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-21 13:04:40.300  3882  3882 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-21 13:04:40.318  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-21 13:04:40.318  3310  3372 I jxcore-log: 
03-21 13:04:40.322  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-21 13:04:40.322  3310  3372 I jxcore-log: 
03-21 13:04:40.324  3919  3919 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 13:04:40.325  3882  3882 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-21 13:04:40.332  1254  1254 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 13:04:40.334  1254  2109 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
03-21 13:04:40.334  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-21 13:04:40.334  3310  3372 I jxcore-log: 
,03-21 13:04:40.336  1770  1770 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 13:04:40.354  1254  3771 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 13:04:40.355  1254  3771 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:40.355  1254  3771 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:40.355  1254  3771 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:40.362  3882  3882 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-21 13:04:40.365  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-21 13:04:40.365  3310  3372 I jxcore-log: 
,03-21 13:04:40.384  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-21 13:04:40.384  3310  3372 I jxcore-log: 
,03-21 13:04:40.393   820   835 I ActivityManager: Start proc 3945:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-21 13:04:40.399  1254  3771 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:40.412  1770  3959 D LocationInitializer: Restart initialization of location
,03-21 13:04:40.451  1254  3771 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 13:04:40.451  1254  3771 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 13:04:40.451  1254  3771 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 13:04:40.503   820  1400 I art     : Explicit concurrent mark sweep GC freed 23816(1173KB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 34MB/50MB, paused 1.305ms total 74.439ms
,03-21 13:04:40.512  3945  3945 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 13:04:40.512  3945  3945 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 13:04:40.534  3945  3945 I MultiDex: VM with version 2.1.0 has multidex support
03-21 13:04:40.534  3945  3945 I MultiDex: install
03-21 13:04:40.534  3945  3945 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 13:04:40.548  3945  3945 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-21 13:04:40.566  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-21 13:04:40.566  3310  3372 I jxcore-log: 
,03-21 13:04:40.572  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-21 13:04:40.572  3310  3372 I jxcore-log: 
,03-21 13:04:40.578  3945  3945 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 13:04:40.580  3882  3882 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-21 13:04:40.583  1254  2548 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-21 13:04:40.586  1254  1254 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 13:04:40.591  1770  1770 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-21 13:04:40.595  3945  3945 D WearableService: callingUid 10011, callindPid: 3945
,03-21 13:04:40.610  1809  2103 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 13:04:40.611  3310  3372 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-21 13:04:40.611  3310  3372 I jxcore-log: 
03-21 13:04:40.611  1770  3976 D LocationInitializer: Restart initialization of location
,03-21 13:04:40.614  1809  2103 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-21 13:04:40.698  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:40.709  3310  3372 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:04:40.709  3310  3372 I jxcore-log: 
,03-21 13:04:40.803  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:40.819  1254  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-21 13:04:40.820  1254  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:40.820  1254  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:40.820  1254  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:40.823  1254  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:40.833  1254  3771 W Uploader: No account for auth token provided
,03-21 13:04:40.836  3882  3882 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-21 13:04:40.836  3882  3882 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-21 13:04:40.837  3882  3882 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-21 13:04:40.846   820  1397 I ActivityManager: Killing 2953:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-21 13:04:41.055   820  1397 I ActivityManager: Killing 1526:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #18
,03-21 13:04:41.205   820  1012 D WifiService: Client connection lost with reason: 4
,03-21 13:04:41.223  3310  3372 I jxcore-log: --= Surplus to requirements =--
03-21 13:04:41.223  3310  3372 I jxcore-log: 
03-21 13:04:41.223  3310  3372 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 13:04:41.223  3310  3372 I jxcore-log: 
,03-21 13:04:41.299  3882  3882 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-21 13:04:41.313  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 13:04:41.314  3545  3626 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 13:04:41.338  1254  3771 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-21 13:04:41.338  1254  3771 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:41.338  1254  3771 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:41.338  1254  3771 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:41.341  1254  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
03-21 13:04:41.341  1254  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:41.341  1254  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:41.341  1254  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-21 13:04:41.343  1254  3771 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.346  1254  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.373  1254  3771 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-21 13:04:41.373  1254  3771 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-21 13:04:41.373  1254  3771 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-21 13:04:41.381  1254  1722 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-21 13:04:41.381  1254  1722 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-21 13:04:41.381  1254  1722 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-21 13:04:41.381  1254  1722 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-21 13:04:41.381  1254  1722 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-21 13:04:41.381  1254  1722 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-21 13:04:41.381  1254  1722 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 13:04:41.383  3840  3878 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
,03-21 13:04:41.401  1254  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 13:04:41.401  1254  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:41.401  1254  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:41.402  1254  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: java.io.IOException
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at cjw.b(PG:159)
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at cju.b(PG:5072)
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at dlh.b(PG:239)
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at dlh.a(PG:140)
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at dqo.a(PG:224)
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at dlt.run(PG:9618)
03-21 13:04:41.402  3840  3878 E DefaultHttpIssuer: 	at dlr.run(PG:3031)
03-21 13:04:41.405  1254  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 13:04:41.406  3840  3878 E BaseSyncManager: AuthenticatorException
03-21 13:04:41.406  3840  3878 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-21 13:04:41.406  3840  3878 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-21 13:04:41.406  3840  3878 E BaseSyncManager: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-21 13:04:41.406  3840  3878 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-21 13:04:41.406  3840  3878 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-21 13:04:41.406  3840  3878 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-21 13:04:41.414   820  1253 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2e28178f}
03-21 13:04:41.416  3882  3882 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 13:04:41.427  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.450  1254  1270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 13:04:41.450  1254  1270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:41.450  1254  1270 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:41.450  1254  1270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:41.454  1254  1270 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.476  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.506  1254  1270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 13:04:41.506  1254  1270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:41.506  1254  1270 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:41.506  1254  1270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:41.509  1254  1270 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.510  3989  3989 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 13:04:41.512  3989  3989 D AndroidRuntime: CheckJNI is OFF
,03-21 13:04:41.544  3882  3882 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 13:04:41.594  3989  3989 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 13:04:41.599   820   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-21 13:04:41.599   820   854 I ActivityManager: Killing 3310:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-21 13:04:41.629   820   864 W PackageSettings: Skipping PackageSetting{3a325e70 com.example.hello/10273} due to missing metadata
,03-21 13:04:41.745   820  1192 I WindowState: WIN DEATH: Window{319d2079 u0 com.test.thalitest/com.test.thalitest.MainActivity},
03-21 13:04:41.746   820  1012 D WifiService: Client connection lost with reason: 4,
,03-21 13:04:41.810   820   854 W ActivityManager: Force removing ActivityRecord{25d4d4f3 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-21 13:04:41.816   820   820 V ActivityManager: Display changed displayId=0
,03-21 13:04:41.847   820   835 W ActivityManager: Spurious death for ProcessRecord{3c27e328 3310:com.test.thalitest/u0a95}, curProc for 3310: null
,03-21 13:04:41.847   820   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-21 13:04:41.849  1254  1254 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:41.861  1236  1236 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-21 13:04:41.864  3000  3000 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
03-21 13:04:41.864   820  1046 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-21 13:04:41.868  1236  4010 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 13:04:41.871   820  1002 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 13:04:41.883  1236  4010 I Decoder : createOrResetDecoder
,03-21 13:04:41.893  1066  1066 I art     : Explicit concurrent mark sweep GC freed 49571(2MB) AllocSpace objects, 1(30MB) LOS objects, 20% free, 61MB/77MB, paused 576us total 38.154ms
,03-21 13:04:41.899   820  1103 I ActivityManager: Start proc 4012:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-21 13:04:41.944   820  1192 I ActivityManager: Start proc 4029:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
,03-21 13:04:41.945   820  1253 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3310 uid 10095
03-21 13:04:41.946  1236  1236 I Keyboard.Facilitator: onFinishInput()
,03-21 13:04:41.948   820   820 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 13:04:41.948   820   820 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 13:04:41.953  1254  1254 I ConfigService: onCreate
,03-21 13:04:41.992  1330  1330 I art     : Explicit concurrent mark sweep GC freed 4983(363KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 718us total 18.896ms
,03-21 13:04:41.996  1254  2600 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-21 13:04:41.996  1254  2600 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-21 13:04:41.996  1254  2600 I GLSUser : [GLSUser] Extracting token using key: Auth
03-21 13:04:41.996  1254  2600 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-21 13:04:41.999  1254  2600 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 13:04:42.005  1236  4010 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 13:04:42.008  3882  3882 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-21 13:04:42.010  3882  3882 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-21 13:04:42.015  3882  3882 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-21 13:04:42.016  3882  3882 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,03-21 13:04:42.022  1236  4010 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-21 13:04:42.023   820  1366 I ActivityManager: Killing 3448:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-21 13:04:42.023  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 13:04:42.024  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-21 13:04:42.025  1809  1896 D DeviceConnectionService: client connected with version: 7571000
,03-21 13:04:42.028  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 13:04:42.028  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-21 13:04:42.029  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 13:04:42.029  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-21 13:04:42.030  1236  4010 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-21 13:04:42.030  1236  4010 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-21 13:04:42.030  1236  4010 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 13:04:42.030  1236  4010 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-21 13:04:42.030  1236  4010 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 13:04:42.030  1236  4010 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-21 13:04:42.064  4012  4050 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-21 13:04:42.065   820   864 I art     : Explicit concurrent mark sweep GC freed 32070(2MB) AllocSpace objects, 12(851KB) LOS objects, 31% free, 34MB/50MB, paused 1.345ms total 113.635ms
,03-21 13:04:42.079  3989  3989 I art     : System.exit called, status: 0,
03-21 13:04:42.079  3989  3989 I AndroidRuntime: VM exiting with result code 0.
,03-21 13:04:42.131  1330  1330 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-21 13:04:42.132  1330  1330 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-21 13:04:42.157   820   864 I ActivityManager: Start proc 4056:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-21 13:04:42.184  4012  4073 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 13:04:42.191   820   835 I ActivityManager: Start proc 4075:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-21 13:04:42.210   820  1400 I ActivityManager: Killing 3500:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-21 13:04:42.339   820  2599 I ActivityManager: Killing 3604:com.android.chrome/u0a40 (adj 15): empty #17
,03-21 13:04:42.574   820  1397 I ActivityManager: Start proc 4105:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-21 13:04:42.612   820  2599 I ActivityManager: Start proc 4122:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-21 13:04:42.622   280   315 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
