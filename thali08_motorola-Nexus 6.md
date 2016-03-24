#### Test 63998117be38304_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-24 08:47:36.204  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:47:36.504  3298  3298 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 08:47:36.507  3298  3298 D AndroidRuntime: CheckJNI is OFF
03-24 08:47:36.630  3298  3298 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 08:47:36.635   825  1094 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 08:47:36.655   825  1094 V WindowManager: addAppToken: AppWindowToken{1105ed3d token=Token{baa3e94 ActivityRecord{2f0832e7 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 08:47:36.659  3298  3298 D AndroidRuntime: Shutting down VM
03-24 08:47:36.664  1520  1770 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@e32e450
03-24 08:47:36.665  1520  1520 I HotwordDetector: Closing mic
03-24 08:47:36.677   825   861 V WindowManager: Adding window Window{c56cc2c u0 Starting com.test.thalitest} at 2 of 7 (after Window{c5c8793 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 08:47:36.698   825  1324 I ActivityManager: Start proc 3312:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 08:47:36.724   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 315us total 23.552ms
03-24 08:47:36.730   358  1778 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 08:47:36.731   358  1778 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 08:47:36.740   358  1033 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 08:47:36.741  1520  1775 I HotwordRecognitionRnr: Hotword detection finished
03-24 08:47:36.741  1520  1771 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 08:47:36.749   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 322us total 21.925ms
03-24 08:47:36.762   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 231us total 11.281ms
03-24 08:47:36.775   825  1324 I ActivityManager: Killing 3016:com.google.android.partnersetup/u0a16 (adj 15): empty #17
03-24 08:47:36.838   825  1276 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658668307
03-24 08:47:36.838   825  1276 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 08:47:36.882   825  1324 I ActivityManager: Killing 2911:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-24 08:47:36.925   872   872 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 08:47:36.925   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 08:47:36.967   872   872 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
03-24 08:47:36.967   872   872 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 08:47:37.178  3312  3312 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 08:47:37.191  3312  3312 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7338-7340)
03-24 08:47:37.191  3312  3312 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 08:47:37.208  3312  3312 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31c392b},
03-24 08:47:37.209  3312  3312 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 08:47:37.209  3312  3312 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 08:47:37.224  3312  3312 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-24 08:47:37.225  3312  3312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 08:47:37.226  3312  3312 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 08:47:37.234  3312  3336 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 08:47:37.242  3312  3312 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 08:47:37.250  3312  3312 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 08:47:37.250  3312  3312 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
03-24 08:47:37.250  3312  3312 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 08:47:37.351   825   860 D BluetoothManagerService: Message: 20
03-24 08:47:37.351   825   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35741765:true
,03-24 08:47:37.377  3312  3312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 08:47:37.385  3312  3312 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 08:47:37.397  3312  3312 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 08:47:37.403  3312  3312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 08:47:37.403  3312  3312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 08:47:37.487  3312  3359 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 08:47:37.495  3312  3312 D Atlas   : Validating map...
,03-24 08:47:37.505   825  1415 V WindowManager: Adding window Window{32a3d5 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{c56cc2c u0 Starting com.test.thalitest})
,03-24 08:47:37.509  3312  3345 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 08:47:37.559  3312  3359 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 08:47:37.565  3312  3359 D OpenGLRenderer: Enabling debug mode 0
,03-24 08:47:37.661   825   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s0ms
,03-24 08:47:37.666  1238  1238 I Keyboard.Facilitator: onFinishInput()
,03-24 08:47:37.681  3312  3312 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3312
,03-24 08:47:37.932  3312  3312 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 08:47:37.968   872   872 I kickstart: STATUS: Received file 'm9kefs1'
03-24 08:47:37.968   872   872 I kickstart: STATUS: 950272 bytes transferred in 1.000570 seconds
03-24 08:47:37.968   872   872 I kickstart: STATUS: Successfully downloaded files from target 
03-24 08:47:37.968   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 08:47:37.971   872   872 I kickstart: STATUS: Sahara protocol completed
,03-24 08:47:38.035  3312  3360 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580510976
,03-24 08:47:38.040  3312  3360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 08:47:38.040  3312  3360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 08:47:38.040  3312  3360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 08:47:38.040  3312  3360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 08:47:38.040  3312  3360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 08:47:38.040  3312  3360 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19c9f694 added. We now have 1 listener(s)
03-24 08:47:38.040   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:47:38.043  3312  3360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-24 08:47:38.044  3312  3360 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 08:47:38.045  3312  3360 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 08:47:38.045  3312  3360 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 08:47:38.048  3312  3360 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d99e800 added. We now have 1 listener(s)
,03-24 08:47:38.048  3312  3360 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 08:47:38.051   825  1015 D WifiService: New client listening to asynchronous messages
,03-24 08:47:38.053  3312  3360 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 08:47:38.054  3312  3360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-24 08:47:38.054  3312  3360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-24 08:47:38.054  3312  3360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 08:47:38.054  3312  3360 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 08:47:38.056  3312  3360 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:47:38.056   825  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:47:38.057  3312  3360 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 08:47:38.061  3312  3360 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 08:47:38.061  3312  3360 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 08:47:38.061  3312  3360 D io.jxcore.node.ConnectivityMonitor: start: OK,
,03-24 08:47:38.062  3312  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 08:47:38.063  3312  3360 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 08:47:38.204  3312  3312 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 08:47:38.652  3312  3370 W jxcore-log: Initializing JXcore engine
03-24 08:47:38.652  3312  3370 W jxcore-log: JXcore engine is ready
,03-24 08:47:38.671  3370  3370 W Thread-355: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12927]" dev="sockfs" ino=12927 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 08:47:38.681  3370  3370 W Thread-355: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-24 08:47:38.681  3370  3370 W Thread-355: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9683]" dev="sockfs" ino=9683 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 08:47:38.681  3370  3370 W Thread-355: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19994]" dev="sockfs" ino=19994 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
03-24 08:47:38.701  3312  3370 W jxcore-log: Starting JXcore engine
,03-24 08:47:38.807  3312  3370 W jxcore-log: Platform android
03-24 08:47:38.807  3312  3370 W jxcore-log: 
03-24 08:47:38.807  3312  3370 W jxcore-log: Process ARCH arm
03-24 08:47:38.807  3312  3370 W jxcore-log: 
,03-24 08:47:39.032  3312  3370 I jxcore-log: JXcore Cordova bridge is ready!
03-24 08:47:39.032  3312  3370 I jxcore-log: 
,03-24 08:47:39.032  3312  3370 W jxcore-log: JXcore engine is started
,03-24 08:47:39.045  3312  3360 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 08:47:39.048  3312  3312 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 08:47:43.127  1258  1258 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:47:43.180  1258  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 08:47:43.181  1258  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:47:43.181  1258  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:47:43.181  1258  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:47:43.191  1258  1951 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:47:43.227  2781  2781 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 08:47:43.228  2781  2781 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-24 08:47:43.229  2781  2781 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 08:47:44.798   825   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-24 08:47:44.811   825   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 08:47:44.848   259   272 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (312 us)
,03-24 08:47:45.445   259   259 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
03-24 08:47:45.445   259   259 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 08:47:45.445   825   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-24 08:47:45.446   825   825 V ActivityManager: Display changed displayId=0
,03-24 08:47:45.728   259   320 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 08:47:45.730   259   259 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
03-24 08:47:45.731   825  1048 D SurfaceControl: Excessive delay in setPowerMode(): 285ms
,03-24 08:47:45.737   825   863 I DreamManagerService: Entering dreamland.
03-24 08:47:45.740   825   863 I PowerManagerService: Dozing...
03-24 08:47:45.741   825   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-24 08:47:45.749   358   358 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-24 08:47:45.749   358   358 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-24 08:47:45.755   825  1014 E WifiStateMachine: cancelDelayedScan -> 17
,03-24 08:47:45.763   825  1014 E native  : do suspend false
,03-24 08:47:45.796  1238  1238 I Keyboard.Facilitator: onFinishInput()
,03-24 08:47:45.799   825  1014 E WifiStateMachine: cancelDelayedScan -> 19
,03-24 08:47:45.810   825  1014 E native  : do suspend true
,03-24 08:47:45.918   358  1424 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-24 08:47:45.918   358  1424 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 08:47:45.971   825  1014 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,03-24 08:47:46.974  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 08:47:46.975  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:47.976  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 08:47:47.976  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:48.437  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:47:48.437  3312  3370 I jxcore-log: 
,03-24 08:47:48.439  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-24 08:47:48.439  3312  3370 I jxcore-log: 
,03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 08:47:48.453  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-24 08:47:48.458  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-24 08:47:48.460  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:47:48.460  3312  3370 I jxcore-log: 
,03-24 08:47:48.462  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:47:48.462  3312  3370 I jxcore-log: 
,03-24 08:47:48.978  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 08:47:48.978  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:48.980  3312  3370 I jxcore-log: Unit Test app is loaded
03-24 08:47:48.980  3312  3370 I jxcore-log: 
,03-24 08:47:48.986  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-24 08:47:48.986  3312  3370 I jxcore-log: 
,03-24 08:47:48.995  3312  3312 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
,03-24 08:47:48.999  3312  3370 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 08:47:49.001  3312  3370 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 08:47:49.001  3312  3370 I jxcore-log: 
,03-24 08:47:49.002  3312  3370 I jxcore-log: My device name is: motorola-Nexus 6
03-24 08:47:49.002  3312  3370 I jxcore-log: 
,03-24 08:47:49.980  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 08:47:49.980  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:50.982  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 08:47:50.982  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:51.984  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 08:47:51.985  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:52.687  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 08:47:52.687  3312  3370 I jxcore-log: 
,03-24 08:47:52.987  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,03-24 08:47:52.987  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:53.025  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-24 08:47:53.025  3312  3370 I jxcore-log: 
,03-24 08:47:53.037  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 08:47:53.037  3312  3370 I jxcore-log: 
,03-24 08:47:53.041  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
03-24 08:47:53.041  3312  3370 I jxcore-log: 
,03-24 08:47:53.078  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
03-24 08:47:53.078  3312  3370 I jxcore-log: 
,03-24 08:47:53.094  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
03-24 08:47:53.094  3312  3370 I jxcore-log: 
,03-24 08:47:53.098  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 08:47:53.098  3312  3370 I jxcore-log: 
,03-24 08:47:53.989  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 08:47:53.989  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan,
,03-24 08:47:54.990  1148  1148 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
03-24 08:47:54.990  1148  1148 W wpa_supplicant: wlan0: Failed to initiate AP scan
,03-24 08:47:55.011  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 08:47:55.011  3312  3370 I jxcore-log: 
,03-24 08:47:55.028  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 08:47:55.028  3312  3370 I jxcore-log: 
,03-24 08:47:55.036  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 08:47:55.036  3312  3370 I jxcore-log: 
,03-24 08:47:55.157  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 08:47:55.157  3312  3370 I jxcore-log: 
,03-24 08:47:55.211  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 08:47:55.211  3312  3370 I jxcore-log: 
,03-24 08:47:55.343  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 08:47:55.343  3312  3370 I jxcore-log: 
,03-24 08:47:55.348  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 08:47:55.348  3312  3370 I jxcore-log: 
,03-24 08:47:55.354  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 08:47:55.354  3312  3370 I jxcore-log: 
,03-24 08:47:55.374  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 08:47:55.374  3312  3370 I jxcore-log: 
,03-24 08:47:55.393  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 08:47:55.393  3312  3370 I jxcore-log: 
,03-24 08:47:55.452   825  1014 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,03-24 08:47:55.494  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 08:47:55.494  3312  3370 I jxcore-log: 
,03-24 08:47:55.500  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 08:47:55.500  3312  3370 I jxcore-log: 
,03-24 08:47:55.525  3312  3370 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 08:47:55.525  3312  3370 I jxcore-log: 
,03-24 08:47:55.558   825  1355 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22e075f0}
,03-24 08:47:57.068  1148  1148 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-24 08:47:57.489  1148  1148 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 08:47:57.528  1148  1148 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-24 08:47:57.529  1148  1148 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 08:47:57.565   825  1014 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-24 08:47:57.566   825  1014 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 08:47:57.568   825  1016 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 08:47:57.577   825  1014 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 08:47:57.592   354   800 D CommandListener: Setting iface cfg
,03-24 08:47:57.605   825  1014 E WifiStateMachine: Start Dhcp Watchdog 1
,03-24 08:47:57.611   825  1014 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 08:47:57.611   825  1014 E WifiStateMachine:  my bss beacon rx: 1
,03-24 08:47:57.611   825  1014 E WifiStateMachine:  RSSI mgmt: -39
03-24 08:47:57.611   825  1014 E WifiStateMachine:  BE :  rx=0 tx=4 lost=0 retries=0
03-24 08:47:57.611   825  1014 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 08:47:57.611   825  1014 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 08:47:57.611   825  1014 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 08:47:57.611   825  1014 E WifiStateMachine:  on_time : 0 tx_time=63 rx_time=82 scan_time=0
,03-24 08:47:57.724   825  1014 E native  : do suspend false
,03-24 08:47:57.738   825  1014 E WifiStateMachine: scanCount==0 - aborting
,03-24 08:47:57.981  3384  3384 I dhcpcd  : version 5.5.6 starting
,03-24 08:47:58.137  3384  3384 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 08:47:58.322  3384  3384 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-24 08:47:58.431  3384  3384 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-24 08:47:58.965   825  1014 E native  : do suspend true
,03-24 08:47:59.008   825  1016 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-24 08:47:59.012   825  1016 D ConnectivityService: Adding iface wlan0 to network 100
03-24 08:47:59.016   825  1014 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 08:47:59.044   825  1016 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-24 08:47:59.045   825  1016 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
03-24 08:47:59.046   825  1016 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 08:47:59.047   825  1016 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 08:47:59.048   825  1016 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 08:47:59.057   825  1016 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 08:47:59.062   825  1016 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-24 08:47:59.063   825  3382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-24 08:47:59.063   825  1016 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 08:47:59.063   825  1016 D ConnectivityService:    accepting network in place of null
03-24 08:47:59.063   825  3382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
,03-24 08:47:59.064   825  3382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-24 08:47:59.065   825  1016 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-24 08:47:59.066   825  1016 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 08:47:59.068   825  3382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 08:47:59.069   825  1016 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-24 08:47:59.070  1067  1546 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 08:47:59.072   825  1016 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,03-24 08:47:59.073   825  1016 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-24 08:47:59.074   825  1016 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-24 08:47:59.078  1328  1354 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 08:47:59.078  1328  1354 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-24 08:47:59.079   825   860 D Tethering: MasterInitialState.processMessage what=3
,03-24 08:47:59.085   825   855 D TelephonyManager: getDataEnabled: retVal=false
,03-24 08:47:59.089   825  1094 V BackupManagerService: Scheduling immediate backup pass
,03-24 08:47:59.092  1520  1520 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
03-24 08:47:59.093   825   825 V BackupManagerService: Running a backup pass
,03-24 08:47:59.094   825  1047 V BackupManagerService: clearing pending backups
,03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:47:59.096  3312  3312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:47:59.099  3312  3312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:47:59.101  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:47:59.101  3312  3370 I jxcore-log: 
,03-24 08:47:59.101  2966  2966 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-24 08:47:59.103   825  1047 V PerformBackupTask: Beginning backup of 14 targets
,03-24 08:47:59.104   825   855 E GpsLocationProvider: No APN found to select.
,03-24 08:47:59.106  2966  2966 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-24 08:47:59.114   825  1047 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 08:47:59.121   825  1047 V BackupServiceBinder: doBackup() invoked
,03-24 08:47:59.122   825  1047 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 08:47:59.137   825  1047 I BackupRestoreController: Getting widget state for user: 0
,03-24 08:47:59.148   825   843 I ActivityManager: Start proc 3425:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 08:47:59.187  1852  1867 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-24 08:47:59.189  1852  1867 V GmsBackupTransport: starting performBackup for @pm@
,03-24 08:47:59.194  1852  1867 V GmsBackupTransport: performBackup done for @pm@
,03-24 08:47:59.201  1258  1258 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:47:59.250  1258  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 08:47:59.251  1258  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:47:59.251  1258  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:47:59.251  1258  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:47:59.254  1258  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:47:59.256  1781  3448 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 08:47:59.284  1258  1724 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:47:59.284  1258  1724 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:47:59.284  1258  1724 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:47:59.284  1258  1724 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 08:47:59.284  1258  1724 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 08:47:59.284  1258  1724 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 08:47:59.284  1258  1724 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 08:47:59.293   825  1186 I art     : Explicit concurrent mark sweep GC freed 55044(2MB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.663ms total 81.550ms
,03-24 08:47:59.295  1852  1907 W GmsBackupTransport: Error sending final backup to server: 
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 08:47:59.295  1852  1907 W GmsBackupTransport: 	... 1 more
,03-24 08:47:59.303   825  1047 D BackupManagerService: Now staging backup of com.google.android.talk
,03-24 08:47:59.317   825  1047 D BackupManagerService: Now staging backup of com.google.android.dialer
03-24 08:47:59.319   825  1047 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 08:47:59.321   825  1047 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 08:47:59.323   825  1047 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 08:47:59.328   825  1047 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 08:47:59.333   825  1047 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 08:47:59.336   825  1047 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 08:47:59.338   825  1047 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 08:47:59.340   825  1047 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 08:47:59.343   825  1047 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 08:47:59.345  1258  1724 I art     : Explicit concurrent mark sweep GC freed 25280(1374KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.005ms total 21.095ms
,03-24 08:47:59.347   825  1047 D BackupManagerService: Now staging backup of com.android.vending
,03-24 08:47:59.349   825  1047 D BackupManagerService: Now staging backup of android
,03-24 08:47:59.352   825  1047 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 08:47:59.355  1852  1867 I GmsBackupTransport: Next backup will happen in 43199933 millis.
,03-24 08:47:59.362   825  1047 I BackupManagerService: Backup pass finished.
,03-24 08:47:59.363   825   843 I ActivityManager: Start proc 3463:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 08:47:59.390  3463  3463 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 08:47:59.395  3463  3463 D SprintDMHelper: simOperator:  IMSI: null
,03-24 08:47:59.395  3463  3463 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-24 08:47:59.408  1781  3480 W DriveInitializer: Background init thread started
,03-24 08:47:59.411  1781  1781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 08:47:59.415  1781  1781 D SystemUpdateService: onCreate
03-24 08:47:59.418  1781  1781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
03-24 08:47:59.421  1781  3483 I SystemUpdateService: active receiver: enabled
03-24 08:47:59.424  1781  3483 I SystemUpdateService: Already downloaded, skipping offpeak checks.
03-24 08:47:59.427  1781  3483 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
03-24 08:47:59.428  1781  3483 I SystemUpdateService: now status is 0 (complete)
03-24 08:47:59.428  1781  3483 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 08:47:59.428  1781  3483 I SystemUpdateService: file has been verified
03-24 08:47:59.429  1781  3481 W DriveInitializer: Awaiting to be initialized
03-24 08:47:59.431  1781  3483 I SystemUpdateService: OTA package size = 25802302
03-24 08:47:59.433  1781  3483 I SystemUpdateService: showing system update notification
03-24 08:47:59.450   825   825 I ValidateNoPeople: skipping global notification
,03-24 08:47:59.479  1781  1781 D SystemUpdateService: onDestroy
,03-24 08:47:59.493  1781  3492 I iu.SyncManager: SYNC; picasa accounts
,03-24 08:47:59.502  1781  1781 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-24 08:47:59.503  1781  1781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-24 08:47:59.506  1781  3492 I iu.UploadsManager: num queued entries: 0
,03-24 08:47:59.507  1781  3492 I iu.UploadsManager: num updated entries: 0
03-24 08:47:59.508  1781  3492 I iu.SyncManager: NEXT; no task
,03-24 08:47:59.517  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-24 08:47:59.519  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-24 08:47:59.529  1258  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 08:47:59.529  1258  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:47:59.529  1258  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:47:59.529  1258  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:47:59.556   825  1469 I ActivityManager: Start proc 3501:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 08:47:59.559  1258  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:47:59.574  1781  3480 W DriveInitializer: Background init thread ended
,03-24 08:47:59.576  3125  3459 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 08:47:59.576  3125  3459 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jdm.a(PG:82)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jcs.o(PG:406)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jcn.a(PG:1379)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jcs.i(PG:143)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at blb.a(PG:3937)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at czp.a(PG:18188)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at czp.a(PG:9081)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at czq.run(PG:1686)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:47:59.576  3125  3459 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jdj.a(PG:4091)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jdj.a(PG:1125)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jdm.a(PG:77)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	... 12 more
03-24 08:47:59.576  3125  3459 E HttpOperation: Caused by: faj: BadAuthentication
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at fal.a(PG:38)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	at jdj.a(PG:4089)
03-24 08:47:59.576  3125  3459 E HttpOperation: 	... 14 more
,03-24 08:47:59.621  1258  1277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 08:47:59.621  1258  1277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:47:59.621  1258  1277 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:47:59.621  1258  1277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:47:59.644   825   855 I ActivityManager: Start proc 3523:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 08:47:59.647  1258  1277 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:47:59.659  3125  3459 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 08:47:59.659  3125  3459 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jdm.a(PG:82)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jcs.o(PG:406)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jcn.a(PG:1379)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jcs.i(PG:143)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at hec.a(PG:42)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at hee.a(PG:102)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at czr.a(PG:65)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at kka.a(PG:108)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at czp.a(PG:19176)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at czp.a(PG:9081)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at czq.run(PG:1686)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:47:59.659  3125  3459 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jdj.a(PG:4091)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jdj.a(PG:1125)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jdm.a(PG:77)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	... 15 more
03-24 08:47:59.659  3125  3459 E HttpOperation: Caused by: faj: BadAuthentication
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at fal.a(PG:38)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	at jdj.a(PG:4089)
03-24 08:47:59.659  3125  3459 E HttpOperation: 	... 17 more
03-24 08:47:59.659  3125  3459 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 08:47:59.659  3125  3459 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at hec.a(PG:42)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at hee.a(PG:102)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at czr.a(PG:65)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at kka.a(PG:108)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	... 15 more
03-24 08:47:59.659  3125  3459 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at fal.a(PG:38)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 08:47:59.659  3125  3459 E ExperimentLoader: 	... 17 more
,03-24 08:47:59.736  3501  3501 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 08:47:59.736  3501  3501 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 08:47:59.736  3501  3501 I GAv4    :   adb logcat -s GAv4
,03-24 08:47:59.751  3501  3501 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 08:47:59.762  3501  3501 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 08:47:59.770   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 39673, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-24 08:47:59.770   825  1415 I ActivityManager: Killing 3036:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 08:47:59.773  3501  3546 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 08:48:00.024   825   855 I ActivityManager: Start proc 3548:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 08:48:00.152  3523  3523 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-24 08:48:00.152  3501  3501 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 08:48:00.162  3501  3501 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 309-311)
03-24 08:48:00.162  3501  3501 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 08:48:00.165  3523  3523 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 08:48:00.170  3501  3501 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3083432e}
,03-24 08:48:00.170  3501  3501 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 08:48:00.170  3501  3501 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 08:48:00.178  3501  3501 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 08:48:00.179  3501  3501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 08:48:00.179  3501  3501 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 08:48:00.187  1258  1275 I art     : Explicit concurrent mark sweep GC freed 10679(574KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 801us total 19.735ms
,03-24 08:48:00.196  3501  3501 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 08:48:00.207  3501  3501 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 08:48:00.207  3501  3501 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 08:48:00.209  3501  3501 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 08:48:00.247  3523  3592 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 08:48:00.256   825  1283 D AlarmManagerService: Setting time of day to sec=1458805680
,03-24 08:48:00.483   825  1283 W AlarmManagerService: Unable to set rtc to 1458805680: Invalid argument
,03-24 08:48:00.503  3501  3606 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 08:48:00.503  3548  3597 V KeepSync: Connecting to GoogleApiClient
,03-24 08:48:00.509   825  3441 D GpsLocationProvider: NTP server returned: 1458805680529 (Thu Mar 24 08:48:00 GMT+01:00 2016) reference: 180432 certainty: 36 system time offset: 20
,03-24 08:48:00.513  3501  3501 I NSApplication: Starting up...
,03-24 08:48:00.548   825  3382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 07:48:00 GMT], X-Android-Received-Millis=[1458805680547], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458805680226]}
03-24 08:48:00.548  3200  3498 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 08:48:00.553   825  1469 I ActivityManager: Start proc 3611:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 08:48:00.557   825  3382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 08:48:00.557   825  1016 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,03-24 08:48:00.558   825  1016 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
,03-24 08:48:00.558   825  1016 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 08:48:00.558   825  1016 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 08:48:00.558   825  1016 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 08:48:00.558   825  1016 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-24 08:48:00.559  1067  1546 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 08:48:00.563   825   844 I ActivityManager: Killing 3084:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-24 08:48:00.619  3523  3633 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 08:48:00.695  1781  3626 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 08:48:00.699  1781  3626 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 08:48:00.701  1258  1277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 08:48:00.701  1258  1277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:00.701  1258  1277 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:00.701  1258  1277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:00.704  1258  1277 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:00.722  1258  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 08:48:00.723  1258  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:00.723  1258  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:00.723  1258  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:00.726  1258  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: Handling authorization failure
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 08:48:00.745  1781  3626 E ClientConnectionOperation: 	... 7 more
,03-24 08:48:00.821   825  1323 I art     : Explicit concurrent mark sweep GC freed 29192(1316KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 2.311ms total 74.630ms
,03-24 08:48:00.825  3548  3597 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 08:48:00.829  3548  3597 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:48:00.834  3548  3597 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:48:00.835  3548  3597 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:48:00.838  1258  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 08:48:00.838  1258  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:00.838  1258  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:00.838  1258  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:00.841  1258  1951 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:00.851  3523  3633 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 08:48:00.853  3523  3592 E BooksSync: Soft error
03-24 08:48:00.853  3523  3592 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 08:48:00.853  3523  3592 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 08:48:00.853  3523  3592 E BooksSync: Sync error
03-24 08:48:00.853  3523  3592 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 08:48:00.853  3523  3592 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 08:48:00.853  3523  3592 I BooksSync: Finished books sync
,03-24 08:48:00.858   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39679, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-24 08:48:00.859   825  2124 I ActivityManager: Killing 2823:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-24 08:48:00.919  1258  3636 D GCM     : Connected
,03-24 08:48:01.109  1258  3636 D GCM     : Message class com.google.f.a.a.p
,03-24 08:48:01.128  1258  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 08:48:01.128  1258  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:01.128  1258  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:01.128  1258  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:01.135  1258  1951 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:01.176  3548  3597 E KeepSync: IOException
03-24 08:48:01.176  3548  3597 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 08:48:01.176  3548  3597 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 08:48:01.176  3548  3597 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 08:48:01.176  3548  3597 E KeepSync: 	... 10 more
03-24 08:48:01.176  3548  3597 W KeepSync: Sync result 2
,03-24 08:48:01.182   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39679, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-24 08:48:01.182   825  1355 I ActivityManager: Killing 2943:com.android.settings/1000 (adj 15): empty #17
,03-24 08:48:01.389   825  1094 I ActivityManager: Start proc 3645:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
03-24 08:48:01.390   825  1094 I ActivityManager: Killing 2452:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 08:48:01.639   825  1094 I ActivityManager: Killing 2469:android.process.acore/u0a5 (adj 15): empty #17
,03-24 08:48:02.444   825  1415 I ActivityManager: Killing 2843:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 08:48:02.789  1258  1258 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:02.870   825   856 I ActivityManager: Start proc 3664:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 08:48:02.931  3664  3664 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458805682931
,03-24 08:48:02.931  3664  3664 D         : TimeServiceNative: User Time to be set is 1458805682931,
03-24 08:48:02.931  3664  3664 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 08:48:02.931  3664  3664 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 08:48:02.931  3664  3664 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458805682931
03-24 08:48:02.931   373   880 D QC-time-services: Daemon: Connection accepted:time_genoff
03-24 08:48:02.932  3664  3664 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458805682931
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458805682931, operation = 0
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 3:59:45
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:Value read from RTC seconds = 19108785000
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:new time 1458805682931 
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon: delta 1439696897931 genoff 1439696897931 
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897931 to memory
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 08:48:02.932   373  3681 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-24 08:48:02.935   373  3681 D QC-time-services: Updating the TOD offset
03-24 08:48:02.935   373  3681 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897931 to memory
03-24 08:48:02.935   373  3681 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 08:48:02.935   373  3681 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 08:48:02.937   373  3681 E QC-time-services: Daemon:Update to modem bit set
03-24 08:48:02.937   373  3681 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 08:48:02.937   373  3681 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142840882931
03-24 08:48:02.937  3664  3664 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0,
,03-24 08:48:02.974  1258  1258 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 08:48:03.007   373   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 08:48:03.012   373   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-24 08:48:03.071   825  1415 I ActivityManager: Start proc 3687:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 08:48:03.131  3687  3687 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 08:48:03.131  3687  3687 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 08:48:03.131  3687  3687 I GAv4    :   adb logcat -s GAv4
,03-24 08:48:03.145  3687  3687 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 08:48:03.155  3425  3682 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com,
,03-24 08:48:03.160  3687  3687 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 08:48:03.184  3687  3709 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 08:48:03.220  1258  1275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 08:48:03.220  1258  1275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:03.220  1258  1275 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:03.221  1258  1275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:03.225  1258  1275 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:03.267  3425  3682 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 08:48:03.269  3425  3682 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 08:48:03.314  3200  3200 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 08:48:03.314  3200  3200 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 08:48:03.355  1781  1933 I art     : Explicit concurrent mark sweep GC freed 17925(1317KB) AllocSpace objects, 18(288KB) LOS objects, 35% free, 28MB/44MB, paused 1.079ms total 45.994ms
,03-24 08:48:03.357  1781  1781 V Herrevad: NQAS connected
,03-24 08:48:03.375   825  1015 D WifiService: New client listening to asynchronous messages
,03-24 08:48:03.468  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 08:48:03.468  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:03.468  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:03.468  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:03.471  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:03.491  1258  1277 I art     : Explicit concurrent mark sweep GC freed 32538(1853KB) AllocSpace objects, 4(64KB) LOS objects, 37% free, 26MB/42MB, paused 819us total 25.203ms
,03-24 08:48:03.502  3200  3716 E Babel   : UserRecoverableAuthException.
,03-24 08:48:03.503  3200  3716 E Babel   : eei: BadAuthentication
03-24 08:48:03.503  3200  3716 E Babel   : 	at eeg.a(Unknown Source)
03-24 08:48:03.503  3200  3716 E Babel   : 	at eeg.a(Unknown Source)
03-24 08:48:03.503  3200  3716 E Babel   : 	at eeg.a(Unknown Source)
03-24 08:48:03.503  3200  3716 E Babel   : 	at g.a(Unknown Source)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cae.a(SourceFile:3089)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cae.a(SourceFile:1131)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cws.a(SourceFile:4333)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cws.a(SourceFile:1419)
03-24 08:48:03.503  3200  3716 E Babel   : 	at crl.a(SourceFile:492)
03-24 08:48:03.503  3200  3716 E Babel   : 	at crl.a(SourceFile:1468)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cas.b(SourceFile:106)
03-24 08:48:03.503  3200  3716 E Babel   : 	at cap.d(SourceFile:335)
03-24 08:48:03.503  3200  3716 E Babel   : 	at caq.run(SourceFile:81)
03-24 08:48:03.503  3200  3716 E Babel   : Error getting auth token
,03-24 08:48:03.504  3200  3716 E Babel   : dvm
03-24 08:48:03.504  3200  3716 E Babel   : 	at g.a(Unknown Source)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cae.a(SourceFile:3089)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cae.a(SourceFile:1131)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cws.a(SourceFile:4333)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cws.a(SourceFile:1419)
03-24 08:48:03.504  3200  3716 E Babel   : 	at crl.a(SourceFile:492)
03-24 08:48:03.504  3200  3716 E Babel   : 	at crl.a(SourceFile:1468)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cas.b(SourceFile:106)
03-24 08:48:03.504  3200  3716 E Babel   : 	at cap.d(SourceFile:335)
03-24 08:48:03.504  3200  3716 E Babel   : 	at caq.run(SourceFile:81)
,03-24 08:48:03.506  3200  3716 E Babel   : Account registration failed 1-Redacted-21
,03-24 08:48:03.506  3200  3716 E Babel   : cyp: null -- null
03-24 08:48:03.506  3200  3716 E Babel   : 	at cae.a(SourceFile:3121)
03-24 08:48:03.506  3200  3716 E Babel   : 	at cae.a(SourceFile:1131)
03-24 08:48:03.506  3200  3716 E Babel   : 	at cws.a(SourceFile:4333)
03-24 08:48:03.506  3200  3716 E Babel   : 	at cws.a(SourceFile:1419)
03-24 08:48:03.506  3200  3716 E Babel   : 	at crl.a(SourceFile:492)
03-24 08:48:03.506  3200  3716 E Babel   : 	at crl.a(SourceFile:1468)
03-24 08:48:03.506  3200  3716 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 08:48:03.506  3200  3716 E Babel   : 	at cas.b(SourceFile:106)
03-24 08:48:03.506  3200  3716 E Babel   : 	at cap.d(SourceFile:335)
03-24 08:48:03.506  3200  3716 E Babel   : 	at caq.run(SourceFile:81)
,03-24 08:48:03.514  3200  3716 I art     : Note: end time exceeds epoch: 
,03-24 08:48:03.577   825  1415 I art     : Explicit concurrent mark sweep GC freed 23013(1030KB) AllocSpace objects, 5(309KB) LOS objects, 32% free, 33MB/49MB, paused 1.298ms total 50.257ms
,03-24 08:48:03.584  1258  1258 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:03.593  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-24 08:48:03.593  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:03.593  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:03.593  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:03.595  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:03.602  1258  1951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-24 08:48:03.602  1258  1951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:03.602  1258  1951 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:03.602  1258  1951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:03.604  1258  1951 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:03.605  1258  1725 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 08:48:03.613  2781  2781 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 08:48:03.613  2781  2781 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 08:48:03.613  2781  2781 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-24 08:48:03.619  3200  3727 E Babel   : Unexpected exception while authenticating.,
03-24 08:48:03.619  3200  3727 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 08:48:03.619  3200  3727 E Babel   : 	at eeg.b(Unknown Source)
03-24 08:48:03.619  3200  3727 E Babel   : 	at eeg.b(Unknown Source)
03-24 08:48:03.619  3200  3727 E Babel   : 	at g.a(Unknown Source)
03-24 08:48:03.619  3200  3727 E Babel   : 	at cae.b(SourceFile:1146)
03-24 08:48:03.619  3200  3727 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 08:48:03.619  3200  3727 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:48:03.619  3200  3727 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:48:03.619  3200  3727 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 08:48:05.401  3523  3583 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 08:48:07.565  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:48:08.564   825  1466 I ActivityManager: Killing 3056:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 08:48:10.497  2781  2797 D Finsky  : [255] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 08:48:10.516  1258  1258 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:10.571  1258  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 08:48:10.571  1258  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:10.572  1258  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:10.572  1258  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:10.581  1258  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 08:48:10.621  2781  2797 D Finsky  : [255] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 08:48:14.849  3312  3370 I jxcore-log: Reconnected to the test server
03-24 08:48:14.849  3312  3370 I jxcore-log: 
,03-24 08:48:16.252   825  2124 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22e075f0}
,03-24 08:48:16.336  1258  3743 I VacuumService: Vacuum at: now=1458805696335 tag=VacuumService,
,03-24 08:48:16.809  3312  3370 I jxcore-log: TAP version 13
03-24 08:48:16.809  3312  3370 I jxcore-log: 
,03-24 08:48:16.812  3312  3370 I jxcore-log: # setup,
03-24 08:48:16.812  3312  3370 I jxcore-log: 
,03-24 08:48:21.403  3312  3370 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 08:48:21.403  3312  3370 I jxcore-log: 
,03-24 08:48:22.095  1258  3746 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 08:48:22.128  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:22.140  1258  3683 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,03-24 08:48:26.351  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:26.351  3312  3370 I jxcore-log: 
,03-24 08:48:26.356  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 47554
03-24 08:48:26.356  3312  3370 I jxcore-log: 
,03-24 08:48:26.363  3312  3370 I jxcore-log: ok 1 Should throw
03-24 08:48:26.363  3312  3370 I jxcore-log: 
,03-24 08:48:26.366  3312  3370 I jxcore-log: # teardown
03-24 08:48:26.366  3312  3370 I jxcore-log: 
,03-24 08:48:27.401   825  1466 I ActivityManager: Killing 1520:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-24 08:48:27.615   825  1015 D WifiService: Client connection lost with reason: 4
03-24 08:48:27.615   825  1466 E libprocessgroup: failed to kill 1 processes for processgroup 1520
,03-24 08:48:30.595  3312  3370 I jxcore-log: # setup
03-24 08:48:30.595  3312  3370 I jxcore-log: 
,03-24 08:48:34.305  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:34.327  3425  3750 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 08:48:34.378  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 08:48:34.378  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:34.378  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:34.378  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:34.383  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:34.421  3425  3750 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 08:48:34.422  3425  3750 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 08:48:34.488  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:34.587  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:34.959  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:35.215  1258  3746 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 08:48:35.216  1258  3746 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 08:48:35.216  1258  3746 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:35.216  1258  3746 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:35.226  1258  3746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:35.276  1258  3746 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 08:48:35.276  1258  3746 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 08:48:35.276  1258  3746 E Uploader: 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 08:48:35.276  1258  3746 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 08:48:35.405  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:35.571  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:35.717  1258  3746 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 08:48:35.717  1258  3746 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:35.717  1258  3746 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:35.718  1258  3746 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:35.726  1258  3746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:35.757  1258  3746 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 08:48:35.757  1258  3746 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 08:48:35.757  1258  3746 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 08:48:35.887  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:36.017  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:36.125  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:36.265  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:36.398  1258  3746 W Uploader:  no longer exists, so no auth token.
,03-24 08:48:36.554  1258  3746 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 08:48:36.554  1258  3746 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:36.554  1258  3746 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:36.554  1258  3746 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:36.561  1258  3746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:36.582  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:48:36.607  1258  3746 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 08:48:36.607  1258  3746 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 08:48:36.607  1258  3746 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 08:48:36.811  1258  3746 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 08:48:36.811  1258  3746 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 08:48:36.812  1258  3746 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:36.813  1258  3746 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:36.826  1258  3746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:36.892  1258  3746 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 08:48:36.892  1258  3746 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 08:48:36.892  1258  3746 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 08:48:37.173  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:37.383  1258  3746 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 08:48:37.384  1258  3746 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:37.384  1258  3746 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 08:48:37.385  1258  3746 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:37.399  1258  3746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:37.480  1258  3746 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 08:48:37.480  1258  3746 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 08:48:37.480  1258  3746 E Uploader: 	,at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 08:48:37.480  1258  3746 E Uploader: 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 08:48:37.480  1258  3746 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 08:48:37.480  1258  3746 E Uploader: 	,at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 08:48:37.599  1258  3746 W Uploader: No account for auth token provided
,03-24 08:48:37.956  3312  3370 I jxcore-log: # 2. emits incomingConnectionState
03-24 08:48:37.956  3312  3370 I jxcore-log: 
,03-24 08:48:38.060  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:38.060  3312  3370 I jxcore-log: 
,03-24 08:48:38.065  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 52560
03-24 08:48:38.065  3312  3370 I jxcore-log: 
,03-24 08:48:38.074  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:38.074  3312  3370 I jxcore-log: 
,03-24 08:48:38.077  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:38.077  3312  3370 I jxcore-log: 
,03-24 08:48:38.087  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:38.087  3312  3370 I jxcore-log: 
,03-24 08:48:38.092  3312  3370 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 08:48:38.092  3312  3370 I jxcore-log: 
,03-24 08:48:38.109  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:38.109  3312  3370 I jxcore-log: 
,03-24 08:48:38.110  3312  3370 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 08:48:38.110  3312  3370 I jxcore-log: 
,03-24 08:48:38.119  3312  3370 I jxcore-log: # teardown
03-24 08:48:38.119  3312  3370 I jxcore-log: 
,03-24 08:48:38.633  3312  3370 I jxcore-log: # setup
03-24 08:48:38.633  3312  3370 I jxcore-log: 
,03-24 08:48:38.739  3312  3370 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 08:48:38.739  3312  3370 I jxcore-log: 
,03-24 08:48:38.887  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 08:48:38.887  3312  3370 I jxcore-log: 
03-24 08:48:38.889  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 58281
03-24 08:48:38.889  3312  3370 I jxcore-log: 
,03-24 08:48:38.900  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 08:48:38.900  3312  3370 I jxcore-log: 
,03-24 08:48:38.903  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 08:48:38.903  3312  3370 I jxcore-log: 
,03-24 08:48:38.907  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 08:48:38.907  3312  3370 I jxcore-log: 
,03-24 08:48:38.941  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:38.941  3312  3370 I jxcore-log: 
,03-24 08:48:38.944  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:38.944  3312  3370 I jxcore-log: 
,03-24 08:48:38.949  3312  3370 I jxcore-log: DEBUG createNativeListener: 
03-24 08:48:38.949  3312  3370 I jxcore-log: 
,03-24 08:48:38.951  3312  3370 I jxcore-log: ok 4 tried to connect to right port
03-24 08:48:38.951  3312  3370 I jxcore-log: 
,03-24 08:48:38.951  3312  3370 I jxcore-log: ok 5 failed due to refused connection
03-24 08:48:38.951  3312  3370 I jxcore-log: 
03-24 08:48:38.952  3312  3370 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 08:48:38.952  3312  3370 I jxcore-log: 
,03-24 08:48:38.958  3312  3370 I jxcore-log: # teardown
03-24 08:48:38.958  3312  3370 I jxcore-log: 
,03-24 08:48:38.959  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:38.959  3312  3370 I jxcore-log: 
,03-24 08:48:39.098  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:39.098  3312  3370 I jxcore-log: 
,03-24 08:48:39.103  3312  3370 I jxcore-log: # setup
03-24 08:48:39.103  3312  3370 I jxcore-log: 
,03-24 08:48:39.105  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:39.105  3312  3370 I jxcore-log: 
,03-24 08:48:39.241  3312  3370 I jxcore-log: # 4. native server connections all up
03-24 08:48:39.241  3312  3370 I jxcore-log: 
,03-24 08:48:39.388  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:39.388  3312  3370 I jxcore-log: 
,03-24 08:48:39.399  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 56732
03-24 08:48:39.399  3312  3370 I jxcore-log: 
,03-24 08:48:39.405  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:39.405  3312  3370 I jxcore-log: 
,03-24 08:48:39.406  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:39.406  3312  3370 I jxcore-log: 
,03-24 08:48:39.407  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:39.407  3312  3370 I jxcore-log: 
,03-24 08:48:39.435  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:39.435  3312  3370 I jxcore-log: 
03-24 08:48:39.438  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:39.438  3312  3370 I jxcore-log: 
03-24 08:48:39.441  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:39.441  3312  3370 I jxcore-log: 
03-24 08:48:39.443  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:39.443  3312  3370 I jxcore-log: 
,03-24 08:48:39.473  3312  3370 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-24 08:48:39.473  3312  3370 I jxcore-log: 
,03-24 08:48:39.474  3312  3370 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 08:48:39.474  3312  3370 I jxcore-log: 
,03-24 08:48:39.476  3312  3370 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 08:48:39.476  3312  3370 I jxcore-log: 
03-24 08:48:39.477  3312  3370 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 08:48:39.477  3312  3370 I jxcore-log: 
,03-24 08:48:39.479  3312  3370 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 08:48:39.479  3312  3370 I jxcore-log: 
,03-24 08:48:39.486  3312  3370 I jxcore-log: # teardown
03-24 08:48:39.486  3312  3370 I jxcore-log: 
,03-24 08:48:39.602  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:39.602  3312  3370 I jxcore-log: 
,03-24 08:48:39.605  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:39.605  3312  3370 I jxcore-log: 
,03-24 08:48:39.608  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:39.608  3312  3370 I jxcore-log: 
,03-24 08:48:39.612  3312  3370 I jxcore-log: # setup
03-24 08:48:39.612  3312  3370 I jxcore-log: 
,03-24 08:48:39.613  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:39.613  3312  3370 I jxcore-log: 
,03-24 08:48:40.081  3312  3370 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 08:48:40.081  3312  3370 I jxcore-log: 
,03-24 08:48:41.659  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:41.659  3312  3370 I jxcore-log: 
,03-24 08:48:41.663  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 56089
03-24 08:48:41.663  3312  3370 I jxcore-log: 
,03-24 08:48:41.671  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:41.671  3312  3370 I jxcore-log: 
,03-24 08:48:41.672  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:41.672  3312  3370 I jxcore-log: 
,03-24 08:48:41.674  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:41.674  3312  3370 I jxcore-log: 
,03-24 08:48:41.686  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:41.686  3312  3370 I jxcore-log: 
,03-24 08:48:41.689  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:41.689  3312  3370 I jxcore-log: 
,03-24 08:48:41.702  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:41.702  3312  3370 I jxcore-log: ,
,03-24 08:48:41.714  3312  3370 I jxcore-log: ok 12 socket shouldn't close until after stream
03-24 08:48:41.714  3312  3370 I jxcore-log: 
,03-24 08:48:41.715  3312  3370 I jxcore-log: ok 13 incoming remains open
03-24 08:48:41.715  3312  3370 I jxcore-log: 
,03-24 08:48:41.721  3312  3370 I jxcore-log: # teardown
03-24 08:48:41.721  3312  3370 I jxcore-log: 
,03-24 08:48:42.029  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:42.029  3312  3370 I jxcore-log: 
,03-24 08:48:42.041  3312  3370 I jxcore-log: # setup
03-24 08:48:42.041  3312  3370 I jxcore-log: 
,03-24 08:48:42.042  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:42.042  3312  3370 I jxcore-log: 
,03-24 08:48:42.323  3312  3370 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 08:48:42.323  3312  3370 I jxcore-log: 
,03-24 08:48:43.010  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:43.010  3312  3370 I jxcore-log: 
,03-24 08:48:43.019  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 35458
03-24 08:48:43.019  3312  3370 I jxcore-log: 
,03-24 08:48:43.025  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:43.025  3312  3370 I jxcore-log: 
,03-24 08:48:43.026  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:43.026  3312  3370 I jxcore-log: 
,03-24 08:48:43.028  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:43.028  3312  3370 I jxcore-log: 
,03-24 08:48:43.039  3312  3370 I jxcore-log: ok 14 we should not have gotten an error
03-24 08:48:43.039  3312  3370 I jxcore-log: 
,03-24 08:48:43.045  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:43.045  3312  3370 I jxcore-log: 
,03-24 08:48:43.047  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:43.047  3312  3370 I jxcore-log: 
,03-24 08:48:43.059  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:43.059  3312  3370 I jxcore-log: 
,03-24 08:48:43.061  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:43.061  3312  3370 I jxcore-log: 
,03-24 08:48:43.069  3312  3370 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 08:48:43.069  3312  3370 I jxcore-log: 
,03-24 08:48:43.069  3312  3370 I jxcore-log: ok 16 incoming is cleaned up
03-24 08:48:43.069  3312  3370 I jxcore-log: 
,03-24 08:48:43.075  3312  3370 I jxcore-log: # teardown
03-24 08:48:43.075  3312  3370 I jxcore-log: 
,03-24 08:48:43.200  3312  3370 I jxcore-log: # setup
03-24 08:48:43.200  3312  3370 I jxcore-log: 
,03-24 08:48:43.750  3312  3370 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 08:48:43.750  3312  3370 I jxcore-log: 
,03-24 08:48:43.861  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:43.861  3312  3370 I jxcore-log: ,
,03-24 08:48:43.867  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 58652
03-24 08:48:43.867  3312  3370 I jxcore-log: 
,03-24 08:48:43.878  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:43.878  3312  3370 I jxcore-log: 
,03-24 08:48:43.879  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:43.879  3312  3370 I jxcore-log: 
,03-24 08:48:43.882  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:43.882  3312  3370 I jxcore-log: 
,03-24 08:48:43.894  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:43.894  3312  3370 I jxcore-log: 
,03-24 08:48:43.897  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:43.897  3312  3370 I jxcore-log: 
,03-24 08:48:43.918  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:43.918  3312  3370 I jxcore-log: 
,03-24 08:48:43.940  3312  3370 I jxcore-log: ok 17 stream was closed
03-24 08:48:43.940  3312  3370 I jxcore-log: ,
03-24 08:48:43.941  3312  3370 I jxcore-log: ok 18 incoming should survive
03-24 08:48:43.941  3312  3370 I jxcore-log: 
03-24 08:48:43.941  3312  3370 I jxcore-log: ok 19 mux should have no streams
03-24 08:48:43.941  3312  3370 I jxcore-log: 
,03-24 08:48:43.950  3312  3370 I jxcore-log: # teardown
03-24 08:48:43.950  3312  3370 I jxcore-log: 
,03-24 08:48:44.042  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:44.042  3312  3370 I jxcore-log: ,
03-24 08:48:44.047  3312  3370 I jxcore-log: # setup
03-24 08:48:44.047  3312  3370 I jxcore-log: 
,03-24 08:48:44.049  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 08:48:44.049  3312  3370 I jxcore-log: 
,03-24 08:48:44.201  3312  3370 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 08:48:44.201  3312  3370 I jxcore-log: 
,03-24 08:48:44.319  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:44.319  3312  3370 I jxcore-log: 
,03-24 08:48:44.323  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 60569
03-24 08:48:44.323  3312  3370 I jxcore-log: 
,03-24 08:48:44.328  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.328  3312  3370 I jxcore-log: 
,03-24 08:48:44.330  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.330  3312  3370 I jxcore-log: 
,03-24 08:48:44.331  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.331  3312  3370 I jxcore-log: 
03-24 08:48:44.341  3312  3370 I jxcore-log: ok 20 we should not have gotten an error
03-24 08:48:44.341  3312  3370 I jxcore-log: 
,03-24 08:48:44.347  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.347  3312  3370 I jxcore-log: 
,03-24 08:48:44.349  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.349  3312  3370 I jxcore-log: 
,03-24 08:48:44.359  3312  3370 I jxcore-log: ok 21 Buffers are identical
03-24 08:48:44.359  3312  3370 I jxcore-log: 
,03-24 08:48:44.361  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:44.361  3312  3370 I jxcore-log: 
,03-24 08:48:44.364  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:44.364  3312  3370 I jxcore-log: 
,03-24 08:48:44.367  3312  3370 I jxcore-log: ok 22 native server is nulled out
03-24 08:48:44.367  3312  3370 I jxcore-log: 
,03-24 08:48:44.367  3312  3370 I jxcore-log: ok 23 native server should be closed
03-24 08:48:44.367  3312  3370 I jxcore-log: 
03-24 08:48:44.368  3312  3370 I jxcore-log: ok 24 incoming has been removed
03-24 08:48:44.368  3312  3370 I jxcore-log: 
,03-24 08:48:44.368  3312  3370 I jxcore-log: ok 25 Incoming should be done
03-24 08:48:44.368  3312  3370 I jxcore-log: 
03-24 08:48:44.368  3312  3370 I jxcore-log: ok 26 The mux object should be closed
03-24 08:48:44.368  3312  3370 I jxcore-log: 
03-24 08:48:44.369  3312  3370 I jxcore-log: ok 27 The mux stream should be closed
03-24 08:48:44.369  3312  3370 I jxcore-log: 
03-24 08:48:44.369  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:44.369  3312  3370 I jxcore-log: 
,03-24 08:48:44.384  3312  3370 I jxcore-log: # teardown
03-24 08:48:44.384  3312  3370 I jxcore-log: 
,03-24 08:48:44.499  3312  3370 I jxcore-log: # setup
03-24 08:48:44.499  3312  3370 I jxcore-log: 
,03-24 08:48:44.678  3312  3370 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 08:48:44.678  3312  3370 I jxcore-log: 
,03-24 08:48:44.785  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:44.785  3312  3370 I jxcore-log: 
,03-24 08:48:44.792  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 55702
03-24 08:48:44.792  3312  3370 I jxcore-log: 
,03-24 08:48:44.817  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.817  3312  3370 I jxcore-log: 
,03-24 08:48:44.818  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.818  3312  3370 I jxcore-log: 
,03-24 08:48:44.820  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.820  3312  3370 I jxcore-log: 
,03-24 08:48:44.823  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.823  3312  3370 I jxcore-log: 
,03-24 08:48:44.824  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.824  3312  3370 I jxcore-log: 
03-24 08:48:44.825  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.825  3312  3370 I jxcore-log: 
,03-24 08:48:44.828  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.828  3312  3370 I jxcore-log: 
,03-24 08:48:44.829  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.829  3312  3370 I jxcore-log: 
,03-24 08:48:44.830  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.830  3312  3370 I jxcore-log: 
,03-24 08:48:44.834  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.834  3312  3370 I jxcore-log: 
,03-24 08:48:44.835  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.835  3312  3370 I jxcore-log: 
,03-24 08:48:44.836  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.836  3312  3370 I jxcore-log: 
,03-24 08:48:44.840  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.840  3312  3370 I jxcore-log: 
,03-24 08:48:44.841  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.841  3312  3370 I jxcore-log: 
03-24 08:48:44.842  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.842  3312  3370 I jxcore-log: 
,03-24 08:48:44.845  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.845  3312  3370 I jxcore-log: 
,03-24 08:48:44.845  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.845  3312  3370 I jxcore-log: 
,03-24 08:48:44.847  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.847  3312  3370 I jxcore-log: 
,03-24 08:48:44.850  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.850  3312  3370 I jxcore-log: 
03-24 08:48:44.850  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.850  3312  3370 I jxcore-log: 
03-24 08:48:44.852  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.852  3312  3370 I jxcore-log: 
03-24 08:48:44.854  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.854  3312  3370 I jxcore-log: 
,03-24 08:48:44.855  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.855  3312  3370 I jxcore-log: 
03-24 08:48:44.856  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.856  3312  3370 I jxcore-log: 
03-24 08:48:44.859  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.859  3312  3370 I jxcore-log: 
,03-24 08:48:44.859  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.859  3312  3370 I jxcore-log: 
,03-24 08:48:44.860  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.860  3312  3370 I jxcore-log: 
03-24 08:48:44.862  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:44.862  3312  3370 I jxcore-log: 
,03-24 08:48:44.863  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:44.863  3312  3370 I jxcore-log: 
,03-24 08:48:44.864  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:44.864  3312  3370 I jxcore-log: 
,03-24 08:48:44.953  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.953  3312  3370 I jxcore-log: ,
,03-24 08:48:44.956  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.956  3312  3370 I jxcore-log: 
,03-24 08:48:44.958  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.958  3312  3370 I jxcore-log: 
,03-24 08:48:44.962  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.962  3312  3370 I jxcore-log: 
,03-24 08:48:44.966  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.966  3312  3370 I jxcore-log: 
,03-24 08:48:44.972  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.972  3312  3370 I jxcore-log: 
,03-24 08:48:44.979  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.979  3312  3370 I jxcore-log: 
,03-24 08:48:44.985  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.985  3312  3370 I jxcore-log: 
,03-24 08:48:44.990  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.990  3312  3370 I jxcore-log: 
,03-24 08:48:44.992  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.992  3312  3370 I jxcore-log: 
,03-24 08:48:44.993  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.993  3312  3370 I jxcore-log: 
,03-24 08:48:44.995  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.995  3312  3370 I jxcore-log: 
,03-24 08:48:44.997  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:44.997  3312  3370 I jxcore-log: 
,03-24 08:48:44.999  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:44.999  3312  3370 I jxcore-log: 
,03-24 08:48:45.001  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.001  3312  3370 I jxcore-log: 
,03-24 08:48:45.003  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.003  3312  3370 I jxcore-log: 
,03-24 08:48:45.005  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.005  3312  3370 I jxcore-log: 
,03-24 08:48:45.007  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.007  3312  3370 I jxcore-log: 
,03-24 08:48:45.009  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.009  3312  3370 I jxcore-log: 
,03-24 08:48:45.015  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.015  3312  3370 I jxcore-log: 
,03-24 08:48:45.017  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.017  3312  3370 I jxcore-log: 
,03-24 08:48:45.019  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.019  3312  3370 I jxcore-log: 
,03-24 08:48:45.021  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.021  3312  3370 I jxcore-log: 
,03-24 08:48:45.023  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.023  3312  3370 I jxcore-log: 
,03-24 08:48:45.025  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.025  3312  3370 I jxcore-log: 
,03-24 08:48:45.028  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.028  3312  3370 I jxcore-log: 
,03-24 08:48:45.029  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.029  3312  3370 I jxcore-log: 
,03-24 08:48:45.031  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.031  3312  3370 I jxcore-log: 
,03-24 08:48:45.032  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.032  3312  3370 I jxcore-log: 
,03-24 08:48:45.034  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.034  3312  3370 I jxcore-log: 
,03-24 08:48:45.035  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.035  3312  3370 I jxcore-log: 
,03-24 08:48:45.036  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.036  3312  3370 I jxcore-log: 
,03-24 08:48:45.039  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.039  3312  3370 I jxcore-log: 
,03-24 08:48:45.040  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.040  3312  3370 I jxcore-log: 
,03-24 08:48:45.042  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.042  3312  3370 I jxcore-log: 
,03-24 08:48:45.043  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.043  3312  3370 I jxcore-log: 
,03-24 08:48:45.045  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.045  3312  3370 I jxcore-log: 
,03-24 08:48:45.046  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.046  3312  3370 I jxcore-log: 
,03-24 08:48:45.048  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.048  3312  3370 I jxcore-log: 
,03-24 08:48:45.049  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.049  3312  3370 I jxcore-log: 
,03-24 08:48:45.051  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.051  3312  3370 I jxcore-log: 
,03-24 08:48:45.053  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.053  3312  3370 I jxcore-log: 
,03-24 08:48:45.054  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.054  3312  3370 I jxcore-log: 
03-24 08:48:45.055  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.055  3312  3370 I jxcore-log: 
03-24 08:48:45.056  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.056  3312  3370 I jxcore-log: 
,03-24 08:48:45.058  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.058  3312  3370 I jxcore-log: 
03-24 08:48:45.059  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.059  3312  3370 I jxcore-log: 
03-24 08:48:45.060  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.060  3312  3370 I jxcore-log: 
,03-24 08:48:45.068  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.068  3312  3370 I jxcore-log: 
,03-24 08:48:45.070  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.070  3312  3370 I jxcore-log: 
,03-24 08:48:45.071  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.071  3312  3370 I jxcore-log: 
,03-24 08:48:45.073  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.073  3312  3370 I jxcore-log: 
03-24 08:48:45.074  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.074  3312  3370 I jxcore-log: 
,03-24 08:48:45.075  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.075  3312  3370 I jxcore-log: 
,03-24 08:48:45.076  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.076  3312  3370 I jxcore-log: 
,03-24 08:48:45.077  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.077  3312  3370 I jxcore-log: 
,03-24 08:48:45.080  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.080  3312  3370 I jxcore-log: 
,03-24 08:48:45.082  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.082  3312  3370 I jxcore-log: 
,03-24 08:48:45.083  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.083  3312  3370 I jxcore-log: 
,03-24 08:48:45.085  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.085  3312  3370 I jxcore-log: 
03-24 08:48:45.086  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.086  3312  3370 I jxcore-log: 
,03-24 08:48:45.087  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.087  3312  3370 I jxcore-log: 
,03-24 08:48:45.088  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.088  3312  3370 I jxcore-log: 
,03-24 08:48:45.089  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.089  3312  3370 I jxcore-log: 
03-24 08:48:45.091  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.091  3312  3370 I jxcore-log: 
,03-24 08:48:45.093  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.093  3312  3370 I jxcore-log: 
,03-24 08:48:45.094  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.094  3312  3370 I jxcore-log: 
,03-24 08:48:45.096  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.096  3312  3370 I jxcore-log: 
03-24 08:48:45.097  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.097  3312  3370 I jxcore-log: 
,03-24 08:48:45.098  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.098  3312  3370 I jxcore-log: 
,03-24 08:48:45.099  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.099  3312  3370 I jxcore-log: 
03-24 08:48:45.100  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.100  3312  3370 I jxcore-log: 
,03-24 08:48:45.102  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.102  3312  3370 I jxcore-log: 
,03-24 08:48:45.103  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.103  3312  3370 I jxcore-log: 
,03-24 08:48:45.104  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.104  3312  3370 I jxcore-log: 
,03-24 08:48:45.106  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.106  3312  3370 I jxcore-log: 
03-24 08:48:45.106  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.106  3312  3370 I jxcore-log: 
,03-24 08:48:45.108  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.108  3312  3370 I jxcore-log: 
,03-24 08:48:45.109  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.109  3312  3370 I jxcore-log: 
03-24 08:48:45.110  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.110  3312  3370 I jxcore-log: 
,03-24 08:48:45.184  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.184  3312  3370 I jxcore-log: 
,03-24 08:48:45.186  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.186  3312  3370 I jxcore-log: 
,03-24 08:48:45.187  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.187  3312  3370 I jxcore-log: 
,03-24 08:48:45.189  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.189  3312  3370 I jxcore-log: 
,03-24 08:48:45.190  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.190  3312  3370 I jxcore-log: 
,03-24 08:48:45.191  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.191  3312  3370 I jxcore-log: 
03-24 08:48:45.192  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.192  3312  3370 I jxcore-log: 
03-24 08:48:45.193  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.193  3312  3370 I jxcore-log: 
03-24 08:48:45.193  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.193  3312  3370 I jxcore-log: 
03-24 08:48:45.194  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.194  3312  3370 I jxcore-log: 
03-24 08:48:45.197  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.197  3312  3370 I jxcore-log: 
,03-24 08:48:45.198  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.198  3312  3370 I jxcore-log: 
03-24 08:48:45.199  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.199  3312  3370 I jxcore-log: 
,03-24 08:48:45.200  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.200  3312  3370 I jxcore-log: 
03-24 08:48:45.201  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.201  3312  3370 I jxcore-log: 
03-24 08:48:45.202  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.202  3312  3370 I jxcore-log: 
,03-24 08:48:45.203  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.203  3312  3370 I jxcore-log: 
03-24 08:48:45.204  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.204  3312  3370 I jxcore-log: 
03-24 08:48:45.204  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.204  3312  3370 I jxcore-log: 
03-24 08:48:45.205  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.205  3312  3370 I jxcore-log: 
,03-24 08:48:45.206  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.206  3312  3370 I jxcore-log: 
03-24 08:48:45.207  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.207  3312  3370 I jxcore-log: 
03-24 08:48:45.208  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.208  3312  3370 I jxcore-log: 
,03-24 08:48:45.209  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.209  3312  3370 I jxcore-log: 
03-24 08:48:45.210  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.210  3312  3370 I jxcore-log: 
03-24 08:48:45.211  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.211  3312  3370 I jxcore-log: 
,03-24 08:48:45.212  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.212  3312  3370 I jxcore-log: 
03-24 08:48:45.213  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.213  3312  3370 I jxcore-log: 
03-24 08:48:45.213  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.213  3312  3370 I jxcore-log: 
03-24 08:48:45.214  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.214  3312  3370 I jxcore-log: 
,03-24 08:48:45.216  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.216  3312  3370 I jxcore-log: 
03-24 08:48:45.216  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.216  3312  3370 I jxcore-log: 
03-24 08:48:45.217  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.217  3312  3370 I jxcore-log: 
,03-24 08:48:45.218  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.218  3312  3370 I jxcore-log: 
03-24 08:48:45.219  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.219  3312  3370 I jxcore-log: 
03-24 08:48:45.220  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.220  3312  3370 I jxcore-log: 
,03-24 08:48:45.221  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.221  3312  3370 I jxcore-log: 
03-24 08:48:45.222  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.222  3312  3370 I jxcore-log: 
03-24 08:48:45.223  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.223  3312  3370 I jxcore-log: 
,03-24 08:48:45.224  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.224  3312  3370 I jxcore-log: 
03-24 08:48:45.225  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.225  3312  3370 I jxcore-log: 
03-24 08:48:45.225  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.225  3312  3370 I jxcore-log: 
03-24 08:48:45.226  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.226  3312  3370 I jxcore-log: 
,03-24 08:48:45.227  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.227  3312  3370 I jxcore-log: 
03-24 08:48:45.228  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.228  3312  3370 I jxcore-log: 
,03-24 08:48:45.229  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.229  3312  3370 I jxcore-log: 
,03-24 08:48:45.230  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.230  3312  3370 I jxcore-log: 
03-24 08:48:45.231  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.231  3312  3370 I jxcore-log: 
,03-24 08:48:45.232  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.232  3312  3370 I jxcore-log: 
,03-24 08:48:45.233  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.233  3312  3370 I jxcore-log: 
,03-24 08:48:45.236  3312  3370 I jxcore-log: ok 28 native server is nulled out
03-24 08:48:45.236  3312  3370 I jxcore-log: 
,03-24 08:48:45.236  3312  3370 I jxcore-log: ok 29 native server should be closed,
03-24 08:48:45.236  3312  3370 I jxcore-log: 
03-24 08:48:45.237  3312  3370 I jxcore-log: ok 30 incoming has been removed
03-24 08:48:45.237  3312  3370 I jxcore-log: 
03-24 08:48:45.238  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.238  3312  3370 I jxcore-log: 
03-24 08:48:45.239  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.239  3312  3370 I jxcore-log: 
03-24 08:48:45.239  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.239  3312  3370 I jxcore-log: 
03-24 08:48:45.239  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.239  3312  3370 I jxcore-log: 
,03-24 08:48:45.240  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.240  3312  3370 I jxcore-log: 
03-24 08:48:45.240  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.240  3312  3370 I jxcore-log: 
03-24 08:48:45.240  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.240  3312  3370 I jxcore-log: 
03-24 08:48:45.241  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.241  3312  3370 I jxcore-log: 
03-24 08:48:45.241  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.241  3312  3370 I jxcore-log: 
03-24 08:48:45.241  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:45.241  3312  3370 I jxcore-log: 
,03-24 08:48:45.341  3312  3370 I jxcore-log: # teardown
03-24 08:48:45.341  3312  3370 I jxcore-log: 
,03-24 08:48:45.362  3312  3370 I jxcore-log: # setup
03-24 08:48:45.362  3312  3370 I jxcore-log: 
,03-24 08:48:45.610  3312  3370 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 08:48:45.610  3312  3370 I jxcore-log: 
,03-24 08:48:45.718  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:45.718  3312  3370 I jxcore-log: 
,03-24 08:48:45.726  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 45857
03-24 08:48:45.726  3312  3370 I jxcore-log: 
,03-24 08:48:45.733  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:45.733  3312  3370 I jxcore-log: 
,03-24 08:48:45.735  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:45.735  3312  3370 I jxcore-log: 
,03-24 08:48:45.736  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:45.736  3312  3370 I jxcore-log: 
,03-24 08:48:45.744  3312  3370 I jxcore-log: ok 31 we should not have gotten an error
03-24 08:48:45.744  3312  3370 I jxcore-log: 
,03-24 08:48:45.748  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:45.748  3312  3370 I jxcore-log: 
,03-24 08:48:45.750  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:45.750  3312  3370 I jxcore-log: 
,03-24 08:48:45.758  3312  3370 I jxcore-log: ok 32 Buffers are identical
03-24 08:48:45.758  3312  3370 I jxcore-log: 
,03-24 08:48:45.758  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:45.758  3312  3370 I jxcore-log: 
,03-24 08:48:45.760  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:45.760  3312  3370 I jxcore-log: 
,03-24 08:48:45.772  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-24 08:48:45.772  3312  3370 I jxcore-log: 
03-24 08:48:45.773  3312  3370 I jxcore-log: ok 33 server should be fine
03-24 08:48:45.773  3312  3370 I jxcore-log: 
,03-24 08:48:45.773  3312  3370 I jxcore-log: ok 34 server should be open
03-24 08:48:45.773  3312  3370 I jxcore-log: 
03-24 08:48:45.774  3312  3370 I jxcore-log: ok 35 incoming has been removed
03-24 08:48:45.774  3312  3370 I jxcore-log: 
03-24 08:48:45.774  3312  3370 I jxcore-log: ok 36 The mux object should be closed
03-24 08:48:45.774  3312  3370 I jxcore-log: 
,03-24 08:48:45.774  3312  3370 I jxcore-log: ok 37 The mux stream should be closed
03-24 08:48:45.774  3312  3370 I jxcore-log: 
,03-24 08:48:45.781  3312  3370 I jxcore-log: # teardown
03-24 08:48:45.781  3312  3370 I jxcore-log: 
,03-24 08:48:45.923  3312  3370 I jxcore-log: # setup
,03-24 08:48:45.923  3312  3370 I jxcore-log: 
,03-24 08:48:46.051  3312  3370 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-24 08:48:46.051  3312  3370 I jxcore-log: 
,03-24 08:48:46.063  1238  1503 I Keyboard.Facilitator.LanguageModelFlusher: run(),
,03-24 08:48:46.064  1238  1503 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 08:48:46.088  1258  1258 I ConfigService: onCreate
,03-24 08:48:46.166  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:46.166  3312  3370 I jxcore-log: 
,03-24 08:48:46.170  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 45369
03-24 08:48:46.170  3312  3370 I jxcore-log: 
,03-24 08:48:46.175  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:48:46.175  3312  3370 I jxcore-log: 
,03-24 08:48:46.176  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:48:46.176  3312  3370 I jxcore-log: 
03-24 08:48:46.178  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:48:46.178  3312  3370 I jxcore-log: 
,03-24 08:48:46.183  3312  3370 I jxcore-log: ok 38 we should not have gotten an error
03-24 08:48:46.183  3312  3370 I jxcore-log: 
,03-24 08:48:46.186  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:48:46.186  3312  3370 I jxcore-log: 
,03-24 08:48:46.189  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:48:46.189  3312  3370 I jxcore-log: 
,03-24 08:48:46.195  3312  3370 I jxcore-log: ok 39 Buffers are identical
03-24 08:48:46.195  3312  3370 I jxcore-log: 
,03-24 08:48:46.199  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 08:48:46.199  3312  3370 I jxcore-log: 
,03-24 08:48:46.200  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 08:48:46.200  3312  3370 I jxcore-log: 
,03-24 08:48:46.202  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:48:46.202  3312  3370 I jxcore-log: 
,03-24 08:48:46.206  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:48:46.206  3312  3370 I jxcore-log: 
,03-24 08:48:46.206  3312  3370 I jxcore-log: ok 40 server should be fine
03-24 08:48:46.206  3312  3370 I jxcore-log: 
,03-24 08:48:46.207  3312  3370 I jxcore-log: ok 41 server should be open
03-24 08:48:46.207  3312  3370 I jxcore-log: 
03-24 08:48:46.208  3312  3370 I jxcore-log: ok 42 incoming has been removed
03-24 08:48:46.208  3312  3370 I jxcore-log: 
03-24 08:48:46.208  3312  3370 I jxcore-log: ok 43 The mux object should be closed
03-24 08:48:46.208  3312  3370 I jxcore-log: 
03-24 08:48:46.208  3312  3370 I jxcore-log: ok 44 The mux stream should be closed
03-24 08:48:46.208  3312  3370 I jxcore-log: 
,03-24 08:48:46.217  3312  3370 I jxcore-log: # teardown
03-24 08:48:46.217  3312  3370 I jxcore-log: 
,03-24 08:48:46.371  3312  3370 I jxcore-log: # setup
03-24 08:48:46.371  3312  3370 I jxcore-log: 
,03-24 08:48:46.489  3312  3370 I jxcore-log: # 12. closeAll can close even when connections open
03-24 08:48:46.489  3312  3370 I jxcore-log: 
,03-24 08:48:46.675  3312  3370 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 08:48:46.675  3312  3370 I jxcore-log: 
,03-24 08:48:46.680  3312  3370 I jxcore-log: # teardown
03-24 08:48:46.680  3312  3370 I jxcore-log: 
,03-24 08:48:46.770  3312  3370 I jxcore-log: # setup
03-24 08:48:46.770  3312  3370 I jxcore-log: 
,03-24 08:48:46.904  3312  3370 I jxcore-log: # 13. closeAll with promise
03-24 08:48:46.904  3312  3370 I jxcore-log: ,
,03-24 08:48:46.994  3312  3370 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 08:48:46.994  3312  3370 I jxcore-log: 
,03-24 08:48:46.999  3312  3370 I jxcore-log: # teardown
03-24 08:48:46.999  3312  3370 I jxcore-log: 
,03-24 08:48:47.079  3312  3370 I jxcore-log: # setup
03-24 08:48:47.079  3312  3370 I jxcore-log: 
,03-24 08:48:47.146  3312  3370 I jxcore-log: # 14. multiplex can send data
03-24 08:48:47.146  3312  3370 I jxcore-log: 
,03-24 08:48:47.307  3312  3370 I jxcore-log: ok 47 String should be length:200
03-24 08:48:47.307  3312  3370 I jxcore-log: 
,03-24 08:48:47.315  3312  3370 I jxcore-log: # teardown
03-24 08:48:47.315  3312  3370 I jxcore-log: 
,03-24 08:48:47.388  3312  3370 I jxcore-log: # setup
03-24 08:48:47.388  3312  3370 I jxcore-log: 
,03-24 08:48:47.506  3312  3370 I jxcore-log: # 15. enqueue and run in order
03-24 08:48:47.506  3312  3370 I jxcore-log: 
,03-24 08:48:47.699  3312  3370 I jxcore-log: ok 48 firstPromise setTimeout
03-24 08:48:47.699  3312  3370 I jxcore-log: 
,03-24 08:48:47.702  3312  3370 I jxcore-log: ok 49 firstPromise result
03-24 08:48:47.702  3312  3370 I jxcore-log: 
,03-24 08:48:47.703  3312  3370 I jxcore-log: ok 50 firstPromise testValue
03-24 08:48:47.703  3312  3370 I jxcore-log: 
,03-24 08:48:47.806  3312  3370 I jxcore-log: ok 51 secondPromise setTimeout,
03-24 08:48:47.806  3312  3370 I jxcore-log: 
,03-24 08:48:47.810  3312  3370 I jxcore-log: ok 52 secondPromise result,
03-24 08:48:47.810  3312  3370 I jxcore-log: 
,03-24 08:48:47.811  3312  3370 I jxcore-log: ok 53 secondPromise testValue
03-24 08:48:47.811  3312  3370 I jxcore-log: ,
03-24 08:48:47.814  3312  3370 I jxcore-log: ok 54 thirdPromise in promise
03-24 08:48:47.814  3312  3370 I jxcore-log: 
,03-24 08:48:47.817  3312  3370 I jxcore-log: ok 55 thirdPromise result
03-24 08:48:47.817  3312  3370 I jxcore-log: 
,03-24 08:48:47.819  3312  3370 I jxcore-log: ok 56 thirdPromise testValue
03-24 08:48:47.819  3312  3370 I jxcore-log: 
,03-24 08:48:47.832  3312  3370 I jxcore-log: # teardown
03-24 08:48:47.832  3312  3370 I jxcore-log: 
,03-24 08:48:47.942  3312  3370 I jxcore-log: # setup
03-24 08:48:47.942  3312  3370 I jxcore-log: 
,03-24 08:48:48.229  3312  3370 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 08:48:48.229  3312  3370 I jxcore-log: 
,03-24 08:48:48.366  3312  3370 I jxcore-log: ok 57 thirdPromise - first to run
03-24 08:48:48.366  3312  3370 I jxcore-log: 
,03-24 08:48:48.369  3312  3370 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 08:48:48.369  3312  3370 I jxcore-log: 
,03-24 08:48:48.374  3312  3370 I jxcore-log: ok 59 secondPromise - second to run
03-24 08:48:48.374  3312  3370 I jxcore-log: 
,03-24 08:48:48.378  3312  3370 I jxcore-log: ok 60 secondPromise - in catch
03-24 08:48:48.378  3312  3370 I jxcore-log: 
,03-24 08:48:48.379  3312  3370 I jxcore-log: ok 61 firstPromise - third to run
03-24 08:48:48.379  3312  3370 I jxcore-log: 
,03-24 08:48:48.380  3312  3370 I jxcore-log: ok 62 firstPromise - in then
03-24 08:48:48.380  3312  3370 I jxcore-log: 
03-24 08:48:48.380  3312  3370 I jxcore-log: ok 63 testing promises
03-24 08:48:48.380  3312  3370 I jxcore-log: 
03-24 08:48:48.383  3312  3370 I jxcore-log: # teardown
03-24 08:48:48.383  3312  3370 I jxcore-log: 
,03-24 08:48:48.516  3312  3370 I jxcore-log: # setup
03-24 08:48:48.516  3312  3370 I jxcore-log: 
,03-24 08:48:48.619  3312  3370 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 08:48:48.619  3312  3370 I jxcore-log: 
,03-24 08:48:48.725  3312  3370 I jxcore-log: ok 64 fourth
03-24 08:48:48.725  3312  3370 I jxcore-log: 
03-24 08:48:48.726  3312  3370 I jxcore-log: ok 65 fourth
03-24 08:48:48.726  3312  3370 I jxcore-log: 
,03-24 08:48:48.727  3312  3370 I jxcore-log: ok 66 second
03-24 08:48:48.727  3312  3370 I jxcore-log: 
,03-24 08:48:48.728  3312  3370 I jxcore-log: ok 67 secondPromise - in then
03-24 08:48:48.728  3312  3370 I jxcore-log: 
,03-24 08:48:48.832  3312  3370 I jxcore-log: ok 68 first
03-24 08:48:48.832  3312  3370 I jxcore-log: 
03-24 08:48:48.834  3312  3370 I jxcore-log: ok 69 firstPromise - in catch
03-24 08:48:48.834  3312  3370 I jxcore-log: 
,03-24 08:48:48.836  3312  3370 I jxcore-log: ok 70 third
03-24 08:48:48.836  3312  3370 I jxcore-log: 
03-24 08:48:48.839  3312  3370 I jxcore-log: ok 71 thirdPromise - in then
03-24 08:48:48.839  3312  3370 I jxcore-log: 
,03-24 08:48:48.841  3312  3370 I jxcore-log: ok 72 testingPromises
03-24 08:48:48.841  3312  3370 I jxcore-log: 
,03-24 08:48:48.860  3312  3370 I jxcore-log: # teardown
03-24 08:48:48.860  3312  3370 I jxcore-log: 
,03-24 08:48:49.054  3312  3370 I jxcore-log: # setup
03-24 08:48:49.054  3312  3370 I jxcore-log: 
,03-24 08:48:49.140  3312  3370 I jxcore-log: # 18. queues handled independently
03-24 08:48:49.140  3312  3370 I jxcore-log: 
,03-24 08:48:49.286  3312  3370 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 08:48:49.286  3312  3370 I jxcore-log: 
,03-24 08:48:49.291  3312  3370 I jxcore-log: # teardown
03-24 08:48:49.291  3312  3370 I jxcore-log: 
,03-24 08:48:49.413  3312  3370 I jxcore-log: # setup
03-24 08:48:49.413  3312  3370 I jxcore-log: 
,03-24 08:48:49.503  3312  3370 I jxcore-log: # 19. basic
03-24 08:48:49.503  3312  3370 I jxcore-log: 
,03-24 08:48:49.600  3312  3370 I jxcore-log: ok 74 sane
03-24 08:48:49.600  3312  3370 I jxcore-log: 
,03-24 08:48:49.608  3312  3370 I jxcore-log: # teardown
,03-24 08:48:49.608  3312  3370 I jxcore-log: 
,03-24 08:48:49.804  3312  3370 I jxcore-log: # setup
03-24 08:48:49.804  3312  3370 I jxcore-log: 
,03-24 08:48:49.902  3312  3370 I jxcore-log: # 20. another
03-24 08:48:49.902  3312  3370 I jxcore-log: 
,03-24 08:48:50.022  3312  3370 I jxcore-log: ok 75 sane
03-24 08:48:50.022  3312  3370 I jxcore-log: 
,03-24 08:48:50.029  3312  3370 I jxcore-log: # teardown
03-24 08:48:50.029  3312  3370 I jxcore-log: 
,03-24 08:48:50.174  3312  3370 I jxcore-log: # setup
03-24 08:48:50.174  3312  3370 I jxcore-log: 
,03-24 08:48:50.268  3312  3370 I jxcore-log: # 21. can pass data in setup
03-24 08:48:50.268  3312  3370 I jxcore-log: 
,03-24 08:48:50.363  3312  3370 I jxcore-log: ok 76 test participant has uuid
03-24 08:48:50.363  3312  3370 I jxcore-log: 
,03-24 08:48:50.365  3312  3370 I jxcore-log: ok 77 participant data matches
03-24 08:48:50.365  3312  3370 I jxcore-log: 
03-24 08:48:50.367  3312  3370 I jxcore-log: ok 78 test participant has uuid
03-24 08:48:50.367  3312  3370 I jxcore-log: 
,03-24 08:48:50.368  3312  3370 I jxcore-log: ok 79 participant data matches
03-24 08:48:50.368  3312  3370 I jxcore-log: ,
03-24 08:48:50.369  3312  3370 I jxcore-log: ok 80 test participant has uuid
03-24 08:48:50.369  3312  3370 I jxcore-log: 
03-24 08:48:50.369  3312  3370 I jxcore-log: ok 81 participant data matches
03-24 08:48:50.369  3312  3370 I jxcore-log: 
,03-24 08:48:50.371  3312  3370 I jxcore-log: # teardown
03-24 08:48:50.371  3312  3370 I jxcore-log: 
,03-24 08:48:50.449  3312  3370 I jxcore-log: # setup
03-24 08:48:50.449  3312  3370 I jxcore-log: 
,03-24 08:48:50.609  3312  3370 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 08:48:50.609  3312  3370 I jxcore-log: 
,03-24 08:48:50.745  3312  3370 I jxcore-log: ok 82 specific error should be returned
03-24 08:48:50.745  3312  3370 I jxcore-log: 
,03-24 08:48:50.752  3312  3370 I jxcore-log: # teardown,
03-24 08:48:50.752  3312  3370 I jxcore-log: ,
,03-24 08:48:50.845  3312  3370 I jxcore-log: ok 83 error should be null,
03-24 08:48:50.845  3312  3370 I jxcore-log: ,
03-24 08:48:50.848  3312  3370 I jxcore-log: ok 84 error should be null,
03-24 08:48:50.848  3312  3370 I jxcore-log: 
,03-24 08:48:50.850  3312  3370 I jxcore-log: # setup,
03-24 08:48:50.850  3312  3370 I jxcore-log: 
,03-24 08:48:50.978  3312  3370 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 08:48:50.978  3312  3370 I jxcore-log: 
,03-24 08:48:51.149  3312  3370 I jxcore-log: ok 85 specific error should be returned
,03-24 08:48:51.149  3312  3370 I jxcore-log: 
,03-24 08:48:51.151  3312  3370 I jxcore-log: # teardown
03-24 08:48:51.151  3312  3370 I jxcore-log: 
,03-24 08:48:51.160  1258  1258 I ConfigService: onDestroy
,03-24 08:48:51.269  3312  3370 I jxcore-log: ok 86 error should be null
03-24 08:48:51.269  3312  3370 I jxcore-log: ,
03-24 08:48:51.270  3312  3370 I jxcore-log: ok 87 error should be null
03-24 08:48:51.270  3312  3370 I jxcore-log: 
,03-24 08:48:51.272  3312  3370 I jxcore-log: # setup
03-24 08:48:51.272  3312  3370 I jxcore-log: 
,03-24 08:48:51.348  3312  3370 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times,
03-24 08:48:51.348  3312  3370 I jxcore-log: 
,03-24 08:48:51.521  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 08:48:51.521  3312  3370 I jxcore-log: 
03-24 08:48:51.522  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 51210
03-24 08:48:51.522  3312  3370 I jxcore-log: 
,03-24 08:48:51.525  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-24 08:48:51.525  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:51.525  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:51.530  3312  3370 I jxcore-log: ok 88 error should be null
03-24 08:48:51.530  3312  3370 I jxcore-log: 
,03-24 08:48:51.530  3312  3370 I jxcore-log: ok 89 error should be null
03-24 08:48:51.530  3312  3370 I jxcore-log: 
03-24 08:48:51.531  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:48:51.531  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:51.531  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:51.533  3312  3370 I jxcore-log: ok 90 error should be null
03-24 08:48:51.533  3312  3370 I jxcore-log: 
03-24 08:48:51.533  3312  3370 I jxcore-log: ok 91 error should be null
03-24 08:48:51.533  3312  3370 I jxcore-log: 
03-24 08:48:51.537  3312  3370 I jxcore-log: # teardown
03-24 08:48:51.537  3312  3370 I jxcore-log: 
,03-24 08:48:51.655  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 08:48:51.656  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:48:51.656  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:51.660  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:48:51.660  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:51.661  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:51.665  3312  3370 I jxcore-log: ok 92 error should be null
03-24 08:48:51.665  3312  3370 I jxcore-log: 
,03-24 08:48:51.666  3312  3370 I jxcore-log: ok 93 error should be null
03-24 08:48:51.666  3312  3370 I jxcore-log: 
,03-24 08:48:51.673  3312  3370 I jxcore-log: # setup
03-24 08:48:51.673  3312  3370 I jxcore-log: 
,03-24 08:48:51.786  3312  3370 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 08:48:51.786  3312  3370 I jxcore-log: 
,03-24 08:48:51.927  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:51.927  3312  3370 I jxcore-log: ,
03-24 08:48:51.929  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 44771
03-24 08:48:51.929  3312  3370 I jxcore-log: 
,03-24 08:48:51.941  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 08:48:51.941  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:48:51.941  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:48:51.941  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 08:48:51.941  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:48:51.941  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:48:51.950  3312  3370 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:48:51.950   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 08:48:51.961  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:48:51.968  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:48:51.968  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:48:51.968  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:48:51.970  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:48:51.988  2158  2176 D BtGatt.GattService: registerClient() - UUID=26ea6cc0-9e92-4274-aeb0-f22040ece9ac
,03-24 08:48:51.991  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=26ea6cc0-9e92-4274-aeb0-f22040ece9ac, clientIf=5,
03-24 08:48:51.992  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:48:51.994  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:48:51.998  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:48:51.998  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:48:51.999  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:48:51.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:48:51.999  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:48:51.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 08:48:52.001  2158  2233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eb1a188
,03-24 08:48:52.001  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:48:52.004  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:48:52.005   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:52.015  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:48:52.015  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:48:52.018  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:48:52.018  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:48:52.018  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:52.018  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:48:52.019  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:48:52.019  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:48:52.021  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:48:52.021  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:52.022  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:48:52.022  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:48:52.025  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:48:52.025  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:48:52.026  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:48:52.026  3312  3370 I jxcore-log: 
03-24 08:48:52.028  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:48:52.028  3312  3370 I jxcore-log: 
03-24 08:48:52.029  3312  3370 I jxcore-log: ok 94 error should be null
03-24 08:48:52.029  3312  3370 I jxcore-log: 
03-24 08:48:52.030  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:48:52.030  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:52.031  3312  3370 I jxcore-log: ok 95 error should be null
03-24 08:48:52.031  3312  3370 I jxcore-log: 
,03-24 08:48:52.036  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-24 08:48:52.037  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:48:52.037  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:48:52.037  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:48:52.037  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:48:52.041  3312  3370 I jxcore-log: ok 96 error should be null
03-24 08:48:52.041  3312  3370 I jxcore-log: 
,03-24 08:48:52.041  3312  3370 I jxcore-log: ok 97 error should be null
03-24 08:48:52.041  3312  3370 I jxcore-log: 
,03-24 08:48:52.047  3312  3370 I jxcore-log: # teardown
03-24 08:48:52.047  3312  3370 I jxcore-log: 
,03-24 08:48:53.028  2158  2158 D BtGatt.ScanManager: awakened up at time 232951
,03-24 08:48:53.030  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:53.035  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 08:48:53.036  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:54.051  2158  2158 D BtGatt.ScanManager: awakened up at time 233974
,03-24 08:48:54.053  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:54.061  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 08:48:54.061  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:55.077  2158  2158 D BtGatt.ScanManager: awakened up at time 234999
03-24 08:48:55.079  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:55.085  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:48:55.085  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:56.101  2158  2158 D BtGatt.ScanManager: awakened up at time 236024
,03-24 08:48:56.103  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:56.111  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 08:48:56.111  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:56.482  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 08:48:56.483  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 08:48:56.483  3312  3370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 08:48:56.483  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 08:48:56.483  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:48:56.484  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:48:56.484  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:48:56.486  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:48:56.486  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:48:56.490  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:48:56.491  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:48:56.493  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:48:56.495  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:48:56.495  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 08:48:56.496  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:48:56.496  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:56.496  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 08:48:56.496  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:48:56.496  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 08:48:56.496  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:48:56.498  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:48:56.499  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:56.499  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:56.501  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:48:56.501  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:56.503  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:48:56.503  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:48:56.504  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 08:48:56.506  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 08:48:56.507  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:48:56.507  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:48:56.508  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:48:56.508  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:48:56.514  3312  3370 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 08:48:56.514  3312  3370 I jxcore-log: 
,03-24 08:48:56.514  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:48:56.515   825   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:56.521  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 08:48:56.522  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:48:56.522  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:48:56.526  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-24 08:48:56.526  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 08:48:56.526  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:48:56.527  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:48:56.534  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:48:56.534  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:56.535  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:48:56.537  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:48:56.537  3312  3370 I jxcore-log: 
,03-24 08:48:56.539  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:48:56.539  3312  3370 I jxcore-log: 
,03-24 08:48:56.548  3312  3370 I jxcore-log: ok 98 error should be null
03-24 08:48:56.548  3312  3370 I jxcore-log: 
,03-24 08:48:56.548  3312  3370 I jxcore-log: ok 99 error should be null
03-24 08:48:56.548  3312  3370 I jxcore-log: 
,03-24 08:48:56.553  3312  3370 I jxcore-log: # setup
03-24 08:48:56.553  3312  3370 I jxcore-log: 
,03-24 08:48:56.658  3312  3370 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 08:48:56.658  3312  3370 I jxcore-log: 
,03-24 08:48:57.014  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:57.014  3312  3370 I jxcore-log: 
,03-24 08:48:57.016  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 52936
03-24 08:48:57.016  3312  3370 I jxcore-log: 
,03-24 08:48:57.031  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 52936, start advertisements: true
,03-24 08:48:57.031  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:48:57.031  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 08:48:57.031  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:48:57.041  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 08:48:57.041  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:48:57.041  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:48:57.041  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:48:57.049  2158  3243 D BtGatt.GattService: registerClient() - UUID=7e2b978d-a3fe-46b5-bcda-63160efcd1fc
,03-24 08:48:57.050  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=7e2b978d-a3fe-46b5-bcda-63160efcd1fc, clientIf=5
03-24 08:48:57.051  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:48:57.052  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:48:57.053  2158  2233 D BtGatt.ScanManager: handling starting scan,
,03-24 08:48:57.053  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:48:57.056  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:48:57.056  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:57.057  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:48:57.057  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:48:57.058  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:48:57.058  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:57.058  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:48:57.058  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:48:57.058  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:48:57.058  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:48:57.059  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:48:57.059  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 08:48:57.059  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:48:57.060  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:48:57.060  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:48:57.060  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:57.061  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:48:57.061  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:57.064  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 08:48:57.064  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:48:57.064  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:48:57.070  2158  2176 D BtGatt.GattService: registerClient() - UUID=6f492cb3-a6b0-4b3a-bd6a-251ed34d8b49
,03-24 08:48:57.070  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=6f492cb3-a6b0-4b3a-bd6a-251ed34d8b49, clientIf=6
03-24 08:48:57.070  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:48:57.073  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:48:57.078  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:48:57.082  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:48:57.085  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:48:57.087  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:48:57.088  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:48:57.088   825  2124 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:57.096  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:48:57.096  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:48:57.096  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:48:57.096  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:48:57.098  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 08:48:57.101  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 08:48:57.101  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:48:57.102  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:48:57.103  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:48:57.103  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:48:57.103  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:48:57.103  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:48:57.103  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:48:57.103  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:48:57.103  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:48:57.103  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:48:57.104  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:48:57.104  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:48:57.104  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:48:57.104  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:48:57.104  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:48:57.105   825  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:57.108  3312  3756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:48:57.115  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 08:48:57.115  3312  3370 I jxcore-log: 
03-24 08:48:57.116  3312  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:48:57.117  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:48:57.117  3312  3370 I jxcore-log: 
,03-24 08:48:57.119  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:48:57.119  3312  3370 I jxcore-log: 
,03-24 08:48:57.121  3312  3370 I jxcore-log: ok 100 error should be null,
03-24 08:48:57.121  3312  3370 I jxcore-log: 
03-24 08:48:57.121  3312  3370 I jxcore-log: ok 101 error should be null
03-24 08:48:57.121  3312  3370 I jxcore-log: 
,03-24 08:48:57.129  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 52936, start advertisements: true,
03-24 08:48:57.129  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:48:57.129  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:48:57.129  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:48:57.129  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:48:57.139  3312  3370 I jxcore-log: ok 102 error should be null
03-24 08:48:57.139  3312  3370 I jxcore-log: 
,03-24 08:48:57.140  3312  3370 I jxcore-log: ok 103 error should be null
03-24 08:48:57.140  3312  3370 I jxcore-log: 
,03-24 08:48:57.146  3312  3370 I jxcore-log: # teardown
03-24 08:48:57.146  3312  3370 I jxcore-log: 
,03-24 08:48:57.532  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:48:57.532  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 08:48:57.532  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:48:57.532  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:48:57.532  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 08:48:57.532  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:48:57.532  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:48:57.532  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:48:57.532  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:48:57.532  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:48:57.533  3312  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:48:57.533  3312  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:48:57.533  3312  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:48:57.534  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:48:57.534  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:48:57.538  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:48:57.539  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:48:57.539  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:48:57.540  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:48:57.540  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:48:57.540  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 08:48:57.540  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:48:57.540  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:48:57.540  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:48:57.543  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:48:57.545  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:48:57.545  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:48:57.545  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:57.545  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-24 08:48:57.550  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:48:57.550  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:57.550  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:57.551  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:48:57.551  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:48:57.553  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:48:57.553  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:48:57.553  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:48:57.553  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:48:57.553  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 08:48:57.553  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 08:48:57.553  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:48:57.553  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:48:57.554  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:48:57.555  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 08:48:57.555  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:48:57.555  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:48:57.555  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:48:57.555  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 08:48:57.558  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-24 08:48:57.558  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:57.558  2158  2222 D BtGatt.GattService: current time is 237481667512
03-24 08:48:57.559  2158  2222 D BtGatt.GattService: Batch record : [-126, -88, -104, -3, 60, 85, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -48, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:48:57.559  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 08:48:57.560  2158  2222 D BtGatt.GattService: ScanRecord : []
03-24 08:48:57.560  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:48:57.564  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 08:48:57.565   825   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:48:57.567  3312  3370 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-24 08:48:57.567  3312  3370 I jxcore-log: 
,03-24 08:48:57.575  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:48:57.576  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 08:48:57.577  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:48:57.577  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:48:57.577  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:48:57.581  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 08:48:57.581  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:48:57.581  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:48:57.582  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:48:57.582  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:48:57.582  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 08:48:57.583  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:48:57.583  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:57.583  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:48:57.584  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-24 08:48:57.584  3312  3370 I jxcore-log: 
03-24 08:48:57.584  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:48:57.584  3312  3370 I jxcore-log: 
03-24 08:48:57.585  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:48:57.585  3312  3370 I jxcore-log: 
,03-24 08:48:57.590  3312  3370 I jxcore-log: ok 104 error should be null
,03-24 08:48:57.590  3312  3370 I jxcore-log: 
,03-24 08:48:57.590  3312  3370 I jxcore-log: ok 105 error should be null,
03-24 08:48:57.590  3312  3370 I jxcore-log: 
03-24 08:48:57.597  3312  3370 I jxcore-log: # setup
03-24 08:48:57.597  3312  3370 I jxcore-log: 
,03-24 08:48:57.791  3312  3370 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
03-24 08:48:57.791  3312  3370 I jxcore-log: 
,03-24 08:48:57.977  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 08:48:57.977  3312  3370 I jxcore-log: 
,03-24 08:48:57.980  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 41740,
03-24 08:48:57.980  3312  3370 I jxcore-log: 
,03-24 08:48:57.984  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:48:57.984  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 08:48:57.984  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:57.988  3312  3370 I jxcore-log: ok 106 error should be null
03-24 08:48:57.988  3312  3370 I jxcore-log: 
,03-24 08:48:57.988  3312  3370 I jxcore-log: ok 107 error should be null
03-24 08:48:57.988  3312  3370 I jxcore-log: 
,03-24 08:48:57.991  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:48:57.991  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:48:57.991  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:57.994  3312  3370 I jxcore-log: ok 108 error should be null
03-24 08:48:57.994  3312  3370 I jxcore-log: 
03-24 08:48:57.995  3312  3370 I jxcore-log: ok 109 error should be null
03-24 08:48:57.995  3312  3370 I jxcore-log: 
,03-24 08:48:58.002  3312  3370 I jxcore-log: # teardown
03-24 08:48:58.002  3312  3370 I jxcore-log: 
,03-24 08:48:58.140  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:48:58.140  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:48:58.140  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:58.146  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:48:58.146  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:58.146  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:58.152  3312  3370 I jxcore-log: ok 110 error should be null
03-24 08:48:58.152  3312  3370 I jxcore-log: 
,03-24 08:48:58.153  3312  3370 I jxcore-log: ok 111 error should be null
03-24 08:48:58.153  3312  3370 I jxcore-log: 
,03-24 08:48:58.158  3312  3370 I jxcore-log: # setup
03-24 08:48:58.158  3312  3370 I jxcore-log: 
,03-24 08:48:58.247  3312  3370 I jxcore-log: # 28. #start should fail if called twice in a row
03-24 08:48:58.247  3312  3370 I jxcore-log: 
,03-24 08:48:58.351  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:58.351  3312  3370 I jxcore-log: 
,03-24 08:48:58.354  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 47225
03-24 08:48:58.354  3312  3370 I jxcore-log: 
,03-24 08:48:58.356  3312  3370 I jxcore-log: ok 112 first call should succeed
03-24 08:48:58.356  3312  3370 I jxcore-log: 
,03-24 08:48:58.357  3312  3370 I jxcore-log: ok 113 first call should succeed
03-24 08:48:58.357  3312  3370 I jxcore-log: 
,03-24 08:48:58.360  3312  3370 I jxcore-log: ok 114 specific error should be returned
03-24 08:48:58.360  3312  3370 I jxcore-log: 
,03-24 08:48:58.362  3312  3370 I jxcore-log: # teardown
,03-24 08:48:58.362  3312  3370 I jxcore-log: 
,03-24 08:48:58.502  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:48:58.503  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:48:58.503  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:58.508  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:48:58.508  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:48:58.508  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:48:58.513  3312  3370 I jxcore-log: ok 115 error should be null
03-24 08:48:58.513  3312  3370 I jxcore-log: 
,03-24 08:48:58.513  3312  3370 I jxcore-log: ok 116 error should be null
03-24 08:48:58.513  3312  3370 I jxcore-log: 
,03-24 08:48:58.519  3312  3370 I jxcore-log: # setup
03-24 08:48:58.519  3312  3370 I jxcore-log: 
,03-24 08:48:58.610  3312  3370 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 08:48:58.610  3312  3370 I jxcore-log: 
,03-24 08:48:58.760  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:48:58.760  3312  3370 I jxcore-log: 
,03-24 08:48:58.762  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 44376
03-24 08:48:58.762  3312  3370 I jxcore-log: 
,03-24 08:48:58.773  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 52936, start advertisements: false
,03-24 08:48:58.773  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:48:58.773  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:48:58.773  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 08:48:58.780  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:48:58.780  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:48:58.780  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:48:58.787  2158  2175 D BtGatt.GattService: registerClient() - UUID=00671658-8d5f-46d3-b0f3-8d76d8c2c6ae
03-24 08:48:58.787  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=00671658-8d5f-46d3-b0f3-8d76d8c2c6ae, clientIf=5
,03-24 08:48:58.788  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:48:58.788  2158  3243 D BtGatt.GattService: start scan with filters
03-24 08:48:58.789  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:48:58.790  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:48:58.790  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:48:58.790  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:48:58.790  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:48:58.790  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:48:58.790  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:48:58.790  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:48:58.791   825   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:58.797  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:48:58.797  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:58.799  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:48:58.799  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:58.799  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:48:58.799  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:48:58.802  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-24 08:48:58.802  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:48:58.803  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:48:58.803  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:48:58.803  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:48:58.803  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:48:58.803  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:48:58.803  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:48:58.805  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:48:58.806  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:48:58.811  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 08:48:58.811  3312  3370 I jxcore-log: 
,03-24 08:48:58.812  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 08:48:58.812  3312  3370 I jxcore-log: 
,03-24 08:48:58.824  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 44376, start advertisements: true
,03-24 08:48:58.824  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:48:58.824  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 08:48:58.824  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:48:58.827  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 08:48:58.827  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 08:48:58.827  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 08:48:58.828  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:48:58.828  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:48:58.828  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:48:58.828  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 08:48:58.828  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:48:58.831  2158  3243 D BtGatt.GattService: registerClient() - UUID=0ca7064c-ea1c-4539-aaa9-81f7fbc6e80f
03-24 08:48:58.832  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=0ca7064c-ea1c-4539-aaa9-81f7fbc6e80f, clientIf=6
,03-24 08:48:58.832  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:48:58.833  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:48:58.840  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:48:58.843  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:48:58.846  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:48:58.846  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:48:58.847  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:48:58.847  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:48:58.847  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:48:58.847  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:48:58.847  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 08:48:58.847  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:48:58.847   825  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:58.854  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:48:58.854  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:48:58.854  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-24 08:48:58.854  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:48:58.854  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:48:58.854  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 08:48:58.855  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:48:58.855  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:48:58.855  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:48:58.855  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:48:58.855  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:48:58.855  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:48:58.855  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
,03-24 08:48:58.862  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:48:58.862  3312  3370 I jxcore-log: 
,03-24 08:48:58.863   825   844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:48:58.864  3312  3757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:48:58.867  3312  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:48:58.877  3312  3370 I jxcore-log: ok 117 called only once
03-24 08:48:58.877  3312  3370 I jxcore-log: 
,03-24 08:48:58.879  3312  3370 I jxcore-log: ok 118 discovery state matches
03-24 08:48:58.879  3312  3370 I jxcore-log: 
,03-24 08:48:58.880  3312  3370 I jxcore-log: ok 119 advertising state matches
03-24 08:48:58.880  3312  3370 I jxcore-log: 
,03-24 08:48:58.893  3312  3370 I jxcore-log: # teardown
03-24 08:48:58.893  3312  3370 I jxcore-log: 
,03-24 08:48:59.498  3523  3760 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 08:48:59.526  3523  3761 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 08:48:59.571  1258  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 08:48:59.571  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 08:48:59.571  1258  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:59.571  1258  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:59.571  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:59.571  1258  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-24 08:48:59.571  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:59.571  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:59.576  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 08:48:59.579  1258  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:59.598  3125  3759 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 08:48:59.598  3125  3759 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jdm.a(PG:82)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jcs.o(PG:406)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jcn.a(PG:1379)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jcs.i(PG:143)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at blb.a(PG:3937)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at czp.a(PG:18188)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at czp.a(PG:9081)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at czq.run(PG:1686)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:48:59.598  3125  3759 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jdj.a(PG:4091)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jdj.a(PG:1125)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jdm.a(PG:77)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	... 12 more
03-24 08:48:59.598  3125  3759 E HttpOperation: Caused by: faj: BadAuthentication
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at fal.a(PG:38)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	at jdj.a(PG:4089)
03-24 08:48:59.598  3125  3759 E HttpOperation: 	... 14 more
,03-24 08:48:59.664  1258  1275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 08:48:59.664  1258  1275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 08:48:59.664  1258  1275 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:59.664  1258  1275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:59.668  1258  1275 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:59.682  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 08:48:59.682  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:59.682  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:59.682  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:59.753   825  1324 I art     : Explicit concurrent mark sweep GC freed 29248(1346KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 2.404ms total 80.575ms
,03-24 08:48:59.767  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:59.796  3523  3761 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 08:48:59.798  3523  3760 E BooksSync: Soft error
03-24 08:48:59.798  3523  3760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 08:48:59.798  3523  3760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 08:48:59.798  3523  3760 E BooksSync: Sync error
03-24 08:48:59.798  3523  3760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 08:48:59.798  3523  3760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 08:48:59.798  3523  3760 I BooksSync: Finished books sync
,03-24 08:48:59.801  2158  2158 D BtGatt.ScanManager: awakened up at time 239724
,03-24 08:48:59.801  3125  3759 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 08:48:59.801  3125  3759 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jdm.a(PG:82)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jcs.o(PG:406)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jcn.a(PG:1379)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jcs.i(PG:143)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at hec.a(PG:42)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at hee.a(PG:102)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at czr.a(PG:65)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at kka.a(PG:108)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at czp.a(PG:19176)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at czp.a(PG:9081)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at czq.run(PG:1686)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:48:59.801  3125  3759 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jdj.a(PG:4091)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jdj.a(PG:1125)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jdm.a(PG:77)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	... 15 more
03-24 08:48:59.801  3125  3759 E HttpOperation: Caused by: faj: BadAuthentication
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at fal.a(PG:38)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	at jdj.a(PG:4089)
03-24 08:48:59.801  3125  3759 E HttpOperation: 	... 17 more
03-24 08:48:59.802  3125  3759 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 08:48:59.802  3125  3759 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at hec.a(PG:42)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at hee.a(PG:102)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at czr.a(PG:65)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at kka.a(PG:108)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	... 15 more
03-24 08:48:59.802  3125  3759 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at fal.a(PG:38),
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 08:48:59.802  3125  3759 E ExperimentLoader: 	... 17 more
03-24 08:48:59.802  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:48:59.806  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:48:59.806  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:48:59.806  2158  2222 D BtGatt.GattService: current time is 239729224074
03-24 08:48:59.806  2158  2222 D BtGatt.GattService: Batch record : [15, 110, -48, -10, -25, 93, 1, -128, -78, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:48:59.806  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:48:59.806  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:48:59.809  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 08:48:59.810  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 08:48:59.810  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 08:48:59.810  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:48:59.814   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212336, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 08:48:59.815  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:48:59.815  3312  3370 I jxcore-log: 
,03-24 08:48:59.821  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 08:48:59.821  3312  3370 I jxcore-log: 
03-24 08:48:59.823  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:48:59.823  3312  3370 I jxcore-log: 
,03-24 08:48:59.827  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 08:48:59.827  3312  3370 I jxcore-log: 
,03-24 08:48:59.843  3548  3766 V KeepSync: Connecting to GoogleApiClient,
,03-24 08:48:59.875  1258  1275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 08:48:59.876  1258  1275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:59.876  1258  1275 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 08:48:59.876  1258  1275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:59.878  1258  1275 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: Handling authorization failure
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 08:48:59.887  1781  3767 E ClientConnectionOperation: 	... 7 more
,03-24 08:48:59.889  3548  3766 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 08:48:59.892  3548  3766 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:48:59.896  3548  3766 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 08:48:59.896  3548  3766 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:48:59.909   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 211201, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 08:48:59.936  1258  3765 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 08:48:59.936  1258  3765 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:48:59.936  1258  3765 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:48:59.936  1258  3765 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:48:59.939  1258  3765 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:48:59.980  3548  3766 E KeepSync: IOException
03-24 08:48:59.980  3548  3766 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 08:48:59.980  3548  3766 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 08:48:59.980  3548  3766 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 08:48:59.980  3548  3766 E KeepSync: 	... 10 more
03-24 08:48:59.980  3548  3766 W KeepSync: Sync result 2
,03-24 08:48:59.986   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 214039, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 08:49:00.590  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:49:00.590  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 08:49:00.590  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 08:49:00.590  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:49:00.590  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:00.591  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:00.591  3312  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:49:00.591  3312  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 08:49:00.591  3312  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 08:49:00.591  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:49:00.592  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 08:49:00.592  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:00.592  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:49:00.592  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:00.592  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:49:00.592  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:49:00.592  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:49:00.594  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:49:00.595  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:00.595  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:00.595  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:00.595  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:49:00.595  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:49:00.595  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 08:49:00.595  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:00.596  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:49:00.598  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:00.598  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:00.598  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:00.598  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:00.599  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:00.601  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:00.601  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:00.601  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:00.605  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:00.605  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:00.605  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:00.606  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:00.606  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:00.606  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 08:49:00.606  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:49:00.607  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:49:00.607  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:00.608  2158  2222 D BtGatt.GattService: current time is 240530752407
03-24 08:49:00.608  2158  2222 D BtGatt.GattService: Batch record : [15, 110, -48, -10, -25, 93, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:49:00.608  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:00.608  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:00.608  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:00.608  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:00.609  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:00.610  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 08:49:00.612  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:00.612  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-24 08:49:00.612  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:00.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:49:00.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:00.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:00.621  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:49:00.622   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:00.622  3312  3370 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 08:49:00.622  3312  3370 I jxcore-log: 
03-24 08:49:00.623  3312  3370 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 08:49:00.623  3312  3370 I jxcore-log: 
,03-24 08:49:00.625  3312  3370 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 08:49:00.625  3312  3370 I jxcore-log: 
,03-24 08:49:00.633  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:49:00.634  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:00.635  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:00.640  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 08:49:00.640  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:00.640  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:00.640  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:00.640  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:00.640  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:00.642  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:49:00.642  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:00.642  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:00.645  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:00.645  3312  3370 I jxcore-log: 
,03-24 08:49:00.646  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:00.646  3312  3370 I jxcore-log: 
,03-24 08:49:00.650  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:00.650  3312  3370 I jxcore-log: 
,03-24 08:49:00.659  3312  3370 I jxcore-log: ok 120 error should be null
03-24 08:49:00.659  3312  3370 I jxcore-log: 
,03-24 08:49:00.660  3312  3370 I jxcore-log: ok 121 error should be null
03-24 08:49:00.660  3312  3370 I jxcore-log: 
,03-24 08:49:00.667  3312  3370 I jxcore-log: # setup
03-24 08:49:00.667  3312  3370 I jxcore-log: 
,03-24 08:49:00.937  3312  3370 I jxcore-log: # 30. does not send duplicate availability changes
03-24 08:49:00.937  3312  3370 I jxcore-log: 
,03-24 08:49:01.050  3312  3370 I jxcore-log: ok 122 should be called once
03-24 08:49:01.050  3312  3370 I jxcore-log: 
,03-24 08:49:01.053  3312  3370 I jxcore-log: ok 123 should not have been called more than once
03-24 08:49:01.053  3312  3370 I jxcore-log: 
,03-24 08:49:01.055  3312  3370 I jxcore-log: # teardown
03-24 08:49:01.055  3312  3370 I jxcore-log: 
,03-24 08:49:01.143  3312  3370 I jxcore-log: ok 124 error should be null
03-24 08:49:01.143  3312  3370 I jxcore-log: 
,03-24 08:49:01.144  3312  3370 I jxcore-log: ok 125 error should be null
03-24 08:49:01.144  3312  3370 I jxcore-log: 
,03-24 08:49:01.149  3312  3370 I jxcore-log: # setup
03-24 08:49:01.149  3312  3370 I jxcore-log: 
,03-24 08:49:01.264  3312  3370 I jxcore-log: # 31. can get the network status
03-24 08:49:01.264  3312  3370 I jxcore-log: 
,03-24 08:49:01.357  3312  3370 I jxcore-log: ok 126 network status should have certain non-empty properties
03-24 08:49:01.357  3312  3370 I jxcore-log: 
,03-24 08:49:01.367  3312  3370 I jxcore-log: # teardown
03-24 08:49:01.367  3312  3370 I jxcore-log: 
,03-24 08:49:01.486  3312  3370 I jxcore-log: ok 127 error should be null
03-24 08:49:01.486  3312  3370 I jxcore-log: 
,03-24 08:49:01.488  3312  3370 I jxcore-log: ok 128 error should be null
03-24 08:49:01.488  3312  3370 I jxcore-log: 
,03-24 08:49:01.490  3312  3370 I jxcore-log: # setup
03-24 08:49:01.490  3312  3370 I jxcore-log: 
,03-24 08:49:01.580  3312  3370 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 08:49:01.580  3312  3370 I jxcore-log: 
,03-24 08:49:01.698  3312  3370 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 08:49:01.698  3312  3370 I jxcore-log: 
,03-24 08:49:01.722  3312  3370 I jxcore-log: ok 129 host address should match
03-24 08:49:01.722  3312  3370 I jxcore-log: 
,03-24 08:49:01.722  3312  3370 I jxcore-log: ok 130 port should match
03-24 08:49:01.722  3312  3370 I jxcore-log: 
,03-24 08:49:03.700  3312  3370 I jxcore-log: ok 131 host address should be null
03-24 08:49:03.700  3312  3370 I jxcore-log: 
,03-24 08:49:03.701  3312  3370 I jxcore-log: ok 132 port should should be null
03-24 08:49:03.701  3312  3370 I jxcore-log: 
,03-24 08:49:03.728  3312  3370 I jxcore-log: # teardown
03-24 08:49:03.728  3312  3370 I jxcore-log: 
,03-24 08:49:03.850  3312  3370 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 08:49:03.850  3312  3370 I jxcore-log: 
,03-24 08:49:03.852  3312  3370 I jxcore-log: ok 133 error should be null
03-24 08:49:03.852  3312  3370 I jxcore-log: 
,03-24 08:49:03.852  3312  3370 I jxcore-log: ok 134 error should be null
03-24 08:49:03.852  3312  3370 I jxcore-log: 
03-24 08:49:03.854  3312  3370 I jxcore-log: # setup
03-24 08:49:03.854  3312  3370 I jxcore-log: 
,03-24 08:49:03.964  3312  3370 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 08:49:03.964  3312  3370 I jxcore-log: 
,03-24 08:49:04.068  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 44376, start advertisements: false,
,03-24 08:49:04.068  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:04.068  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:04.069  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 08:49:04.078  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:49:04.078  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:04.078  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:04.088  2158  2175 D BtGatt.GattService: registerClient() - UUID=8f7b81db-2d4f-4d44-ad2c-34753842a9b2
,03-24 08:49:04.089  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=8f7b81db-2d4f-4d44-ad2c-34753842a9b2, clientIf=5
03-24 08:49:04.090  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:49:04.091  2158  3243 D BtGatt.GattService: start scan with filters
,03-24 08:49:04.094  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:04.094  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:04.095  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:04.095  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 08:49:04.096  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:49:04.096  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:04.096  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:49:04.097  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:04.098   825   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:04.106  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 08:49:04.106  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.109  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:49:04.109  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.110  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:04.110  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:49:04.112  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 08:49:04.112  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:49:04.112  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:04.112  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.113  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:04.113  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:04.113  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:04.113  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-24 08:49:04.115  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:49:04.115  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.118  3312  3370 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
,03-24 08:49:04.118  3312  3370 I jxcore-log: 
,03-24 08:49:04.120  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:04.120  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:04.120  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 08:49:04.120  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:49:04.122  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:49:04.123  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:04.123  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:04.123  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:04.124  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 08:49:04.124  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:04.124  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:04.124  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 08:49:04.124  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 08:49:04.125  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 08:49:04.125  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 08:49:04.125  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:04.126  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:04.126  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 08:49:04.127  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 08:49:04.127  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.127  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:04.128  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 08:49:04.128  3312  3370 I jxcore-log: 
03-24 08:49:04.128  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:04.128  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:04.132  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:04.132  3312  3370 I jxcore-log: 
03-24 08:49:04.134  3312  3370 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 08:49:04.134  3312  3370 I jxcore-log: 
,03-24 08:49:04.139  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 08:49:04.139  3312  3370 I jxcore-log: 
03-24 08:49:04.140  3312  3370 I jxcore-log: # teardown
03-24 08:49:04.140  3312  3370 I jxcore-log: 
,03-24 08:49:04.308  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:04.308  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:04.308  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:04.310  3312  3370 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:04.310  3312  3370 I jxcore-log: 
,03-24 08:49:04.312  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:04.312  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:04.312  3312  3370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 08:49:04.312  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 08:49:04.312  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:04.313  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:49:04.313  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 08:49:04.313  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 08:49:04.315  3312  3370 D BluetoothLeScanner: could not find callback wrapper
03-24 08:49:04.315  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:04.317  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-24 08:49:04.317  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 08:49:04.317  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:04.319  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 08:49:04.319  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:04.319  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:49:04.320  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:49:04.320  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:04.329  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-24 08:49:04.330   825   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:04.342  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-24 08:49:04.344  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:04.345  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:04.351  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-24 08:49:04.352  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:04.352  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:49:04.356  3312  3370 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
,03-24 08:49:04.356  3312  3370 I jxcore-log: 
,03-24 08:49:04.368  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:04.368  3312  3370 I jxcore-log: ,
03-24 08:49:04.369  3312  3370 I jxcore-log: # setup
03-24 08:49:04.369  3312  3370 I jxcore-log: 
,03-24 08:49:04.499  3312  3370 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error
03-24 08:49:04.499  3312  3370 I jxcore-log: 
,03-24 08:49:04.630  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 44376, start advertisements: false
03-24 08:49:04.630  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:04.630  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:04.630  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 08:49:04.639  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:49:04.639  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:04.639  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:04.650  2158  3243 D BtGatt.GattService: registerClient() - UUID=6f002878-e621-48b8-9ede-7616d0452ef0,
,03-24 08:49:04.651  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=6f002878-e621-48b8-9ede-7616d0452ef0, clientIf=5
,03-24 08:49:04.652  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:04.653  2158  2176 D BtGatt.GattService: start scan with filters
,03-24 08:49:04.656  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:04.660  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:49:04.660  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:49:04.661  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:04.662  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.662  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 08:49:04.662  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:49:04.662  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:04.662  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:49:04.663  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:04.664   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:04.665  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:04.665  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:04.666  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:04.666  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:04.670  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:49:04.670  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.673  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:04.673  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:04.678  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:49:04.678  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:49:04.678  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 08:49:04.678  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 08:49:04.678  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:04.679  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 08:49:04.681  3312  3370 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-24 08:49:04.681  3312  3370 I jxcore-log: 
,03-24 08:49:04.685  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 44376, start advertisements: false
03-24 08:49:04.685  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:04.685  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:04.685  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:04.685  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:04.687  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:04.687  3312  3370 I jxcore-log: 
03-24 08:49:04.687  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:04.687  3312  3370 I jxcore-log: 
,03-24 08:49:04.689  3312  3370 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-24 08:49:04.689  3312  3370 I jxcore-log: 
,03-24 08:49:04.695  3312  3370 I jxcore-log: # teardown
03-24 08:49:04.695  3312  3370 I jxcore-log: 
,03-24 08:49:04.904  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:04.904  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:04.904  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 08:49:04.905  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:49:04.909  2158  2176 D BtGatt.GattService: stopScan() - queue size =1,
,03-24 08:49:04.911  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:04.912  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:04.913  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:04.913  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 08:49:04.913  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 08:49:04.913  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:04.913  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 08:49:04.913  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:04.914  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:04.914  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:49:04.915  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:04.915  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:04.915  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:04.918  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:04.919  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.919  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:04.919  3312  3370 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:04.919  3312  3370 I jxcore-log: 
03-24 08:49:04.921  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:04.921  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:04.921  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:04.922  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:04.922  3312  3370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 08:49:04.922  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:49:04.922  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 08:49:04.922  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 08:49:04.922  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:04.922  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 08:49:04.928  3312  3370 D BluetoothLeScanner: could not find callback wrapper,
03-24 08:49:04.928  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:04.930  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:04.930  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:04.931  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 08:49:04.935  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:04.935  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:04.936  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:49:04.936  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:04.936  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:04.939  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 08:49:04.939  3312  3370 I jxcore-log: 
,03-24 08:49:04.942  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 08:49:04.943   825  2124 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:04.949  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:49:04.950  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:04.950  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:04.954  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:04.954  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:04.954  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:49:04.956  3312  3370 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-24 08:49:04.956  3312  3370 I jxcore-log: 
,03-24 08:49:04.961  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 08:49:04.961  3312  3370 I jxcore-log: 
,03-24 08:49:04.963  3312  3370 I jxcore-log: # setup
03-24 08:49:04.963  3312  3370 I jxcore-log: 
,03-24 08:49:05.164  3312  3370 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-24 08:49:05.164  3312  3370 I jxcore-log: 
,03-24 08:49:05.290  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
,03-24 08:49:05.290  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-24 08:49:05.290  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:05.291  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:49:05.298  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 08:49:05.298  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:05.298  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:05.299  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:05.307  2158  3243 D BtGatt.GattService: registerClient() - UUID=91de1ef9-d9aa-4d38-a98d-f39df6e4747c,
,03-24 08:49:05.307  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=91de1ef9-d9aa-4d38-a98d-f39df6e4747c, clientIf=5,
03-24 08:49:05.308  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:05.309  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:49:05.310  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:05.311  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:05.311  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:05.312  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:49:05.312  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:49:05.313  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 08:49:05.314  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 08:49:05.314  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 08:49:05.314  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:05.315  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:49:05.315  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 08:49:05.316  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:05.316  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:05.320  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:49:05.320  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.323  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:05.323  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.323  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:05.324  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:05.328  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:05.328  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:05.329  2158  2176 D BtGatt.GattService: registerClient() - UUID=71adcad6-12b3-4c13-95d9-19cefe807f2e
,03-24 08:49:05.330  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=71adcad6-12b3-4c13-95d9-19cefe807f2e, clientIf=6
03-24 08:49:05.330  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:49:05.331  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:49:05.331  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.332  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:05.339  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:05.341  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:05.344  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:05.345  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:49:05.345  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:49:05.345   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:05.349  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:05.349  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-24 08:49:05.349  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:49:05.349  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:49:05.350  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 08:49:05.351  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:49:05.351  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:49:05.352  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:49:05.352  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:49:05.352  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 08:49:05.353  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:49:05.353  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 08:49:05.353  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 08:49:05.353  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:49:05.353  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 08:49:05.354  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:05.354  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:05.354  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 08:49:05.354  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:05.354  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:49:05.354  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-24 08:49:05.356   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:05.358  3312  3773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:49:05.358  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:05.358  3312  3370 I jxcore-log: 
03-24 08:49:05.360  3312  3370 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-24 08:49:05.360  3312  3370 I jxcore-log: ,
03-24 08:49:05.361  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:05.361  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 08:49:05.361  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:49:05.361  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 08:49:05.361  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:05.361  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 08:49:05.361  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:49:05.361  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:05.361  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 08:49:05.361  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:05.361  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:49:05.361  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:49:05.362  3312  3773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:05.362  3312  3773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 08:49:05.362  3312  3773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:49:05.363  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:05.364  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:05.365  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:05.366  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.366  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:05.366  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:05.366  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:05.366  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 08:49:05.367  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:49:05.367  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 08:49:05.367  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 08:49:05.367  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:49:05.369  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:05.369  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.370  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:05.370  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:05.371  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:05.371  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:05.371  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:05.375  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:05.375  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:05.377  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:49:05.378  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:05.378  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:05.378  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 08:49:05.379  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:49:05.379  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:05.379  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:05.379  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:05.380  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 08:49:05.380  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:05.381  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:49:05.381  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:05.381  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:49:05.381  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:05.386  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 08:49:05.386  3312  3370 I jxcore-log: 
03-24 08:49:05.388  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 08:49:05.388  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 08:49:05.388  3312  3370 I jxcore-log: 
03-24 08:49:05.388   825  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:05.394  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:05.395  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 08:49:05.395  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:05.399  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 08:49:05.399  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:49:05.399  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:05.399  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:05.399  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:05.399  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:05.399  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:05.400  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 08:49:05.401  3312  3370 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 08:49:05.401  3312  3370 I jxcore-log: 
,03-24 08:49:05.409  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:05.409  3312  3370 I jxcore-log: 
,03-24 08:49:05.410  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:05.410  3312  3370 I jxcore-log: 
,03-24 08:49:05.412  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:05.412  3312  3370 I jxcore-log: 
,03-24 08:49:05.413  3312  3370 I jxcore-log: # teardown
03-24 08:49:05.413  3312  3370 I jxcore-log: 
,03-24 08:49:05.583  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:05.584  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:05.584  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:05.588  3312  3370 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:05.588  3312  3370 I jxcore-log: 
03-24 08:49:05.589  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:05.589  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:05.589  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:05.591  3312  3370 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown,
03-24 08:49:05.591  3312  3370 I jxcore-log: 
,03-24 08:49:05.596  3312  3370 I jxcore-log: # setup,
03-24 08:49:05.596  3312  3370 I jxcore-log: 
,03-24 08:49:05.692  3312  3370 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error,
03-24 08:49:05.692  3312  3370 I jxcore-log: 
,03-24 08:49:05.830  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 08:49:05.830  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:49:05.831  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:05.831  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:49:05.840  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 08:49:05.840  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:49:05.840  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:05.840  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:05.849  2158  2175 D BtGatt.GattService: registerClient() - UUID=361616e3-cbae-45d2-954a-947532996d97
,03-24 08:49:05.850  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=361616e3-cbae-45d2-954a-947532996d97, clientIf=5
03-24 08:49:05.851  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-24 08:49:05.852  2158  2176 D BtGatt.GattService: start scan with filters
03-24 08:49:05.854  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:05.854  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:05.854  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:05.854  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:49:05.854  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:49:05.855  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:05.855  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:05.855  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:05.855  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:05.856  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:05.858  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:05.858  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:05.858  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:05.859  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.860  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:05.861  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:05.861  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.861  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 08:49:05.862  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:49:05.865  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:05.865  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:05.868  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:49:05.868  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:05.874  2158  3243 D BtGatt.GattService: registerClient() - UUID=b835eaac-7c3a-4803-9870-ba0f31c1d2ed
03-24 08:49:05.875  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=b835eaac-7c3a-4803-9870-ba0f31c1d2ed, clientIf=6
,03-24 08:49:05.877  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:49:05.879  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:05.883  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:05.887  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:05.891  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:05.892  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:49:05.892  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:49:05.893   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:05.899  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 08:49:05.899  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:49:05.899  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:49:05.899  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:05.900  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 08:49:05.901  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:49:05.901  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:49:05.901  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:49:05.901  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:49:05.901  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:05.902  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:05.902  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:49:05.902  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:49:05.902  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:49:05.903  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:49:05.903  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:05.903  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:05.903  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:49:05.903  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:05.903  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:49:05.904  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:05.905   825  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:05.906  3312  3774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:49:05.906  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:05.906  3312  3370 I jxcore-log: 
,03-24 08:49:05.910  3312  3370 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error,
03-24 08:49:05.910  3312  3370 I jxcore-log: 
03-24 08:49:05.912  3312  3774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:49:05.915  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-24 08:49:05.915  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:05.916  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:49:05.916  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:05.916  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:05.919  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:05.919  3312  3370 I jxcore-log: 
,03-24 08:49:05.921  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:49:05.921  3312  3370 I jxcore-log: 
,03-24 08:49:05.925  3312  3370 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-24 08:49:05.925  3312  3370 I jxcore-log: 
,03-24 08:49:05.932  3312  3370 I jxcore-log: # teardown
03-24 08:49:05.932  3312  3370 I jxcore-log: 
,03-24 08:49:06.373  2158  2158 D BtGatt.ScanManager: awakened up at time 246296
03-24 08:49:06.374  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:06.385  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 08:49:06.385  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:06.386  2158  2222 D BtGatt.GattService: current time is 246308993134
03-24 08:49:06.386  2158  2222 D BtGatt.GattService: Batch record : [33, 117, -2, -88, -4, 85, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:49:06.387  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:06.388  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:06.390  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 08:49:06.391  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 08:49:06.391  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:49:06.393  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 08:49:06.397  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-24 08:49:06.397  3312  3370 I jxcore-log: 
,03-24 08:49:06.400  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-24 08:49:06.400  3312  3370 I jxcore-log: 
,03-24 08:49:06.496  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:06.496  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 08:49:06.496  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 08:49:06.496  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:49:06.500  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:06.502  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:06.504  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:06.505  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:06.505  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:06.505  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:49:06.505  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:06.505  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 08:49:06.506  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:06.505  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:49:06.507  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:06.507  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:06.507  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 08:49:06.507  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:49:06.510  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 08:49:06.511  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:06.511  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:06.512  3312  3370 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:06.512  3312  3370 I jxcore-log: 
03-24 08:49:06.515  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:06.515  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 08:49:06.515  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:49:06.515  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 08:49:06.515  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:06.515  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 08:49:06.516  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:49:06.516  2158  2222 D BtGatt.GattService: current time is 246439241311
03-24 08:49:06.516  2158  2222 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:49:06.516  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:06.516  3312  3774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:49:06.517  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-24 08:49:06.517  3312  3774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:49:06.517  3312  3774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 08:49:06.517  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:06.517  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:06.517  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-24 08:49:06.517  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 08:49:06.526  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:49:06.526  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 08:49:06.526  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:49:06.527  3312  3370 D BluetoothLeScanner: could not find callback wrapper
03-24 08:49:06.527  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:06.527  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 08:49:06.529  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:49:06.529  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:49:06.532  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 08:49:06.532  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:06.532  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:49:06.533  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:06.533  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:06.533  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:49:06.533  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:49:06.533  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:06.533  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:49:06.533  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:06.533  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:06.534  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:06.534  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:49:06.534  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:06.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-24 08:49:06.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:06.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:06.537  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:06.537  3312  3370 I jxcore-log: 
,03-24 08:49:06.542  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:49:06.542   825  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:06.548  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:49:06.549  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:06.549  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:06.552  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 08:49:06.552  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:06.552  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:06.552  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:06.553  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:49:06.554  3312  3370 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-24 08:49:06.554  3312  3370 I jxcore-log: ,
,03-24 08:49:06.562  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 08:49:06.562  3312  3370 I jxcore-log: 
,03-24 08:49:06.563  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:06.563  3312  3370 I jxcore-log: 
,03-24 08:49:06.566  3312  3370 I jxcore-log: # setup
03-24 08:49:06.566  3312  3370 I jxcore-log: 
,03-24 08:49:07.269  3312  3370 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 08:49:07.269  3312  3370 I jxcore-log: 
,03-24 08:49:07.501  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 08:49:07.501  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:49:07.501  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 08:49:07.501  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:49:07.505  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 08:49:07.506  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:07.506  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:07.506  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:07.511  2158  3243 D BtGatt.GattService: registerClient() - UUID=3fda3966-2a74-46ef-8cab-c4f924c63ab6
03-24 08:49:07.511  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=3fda3966-2a74-46ef-8cab-c4f924c63ab6, clientIf=5
,03-24 08:49:07.512  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:07.512  2158  2175 D BtGatt.GattService: start scan with filters
03-24 08:49:07.513  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:49:07.514  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:07.514  2158  2233 D BtGatt.ScanManager: handling starting scan,
,03-24 08:49:07.514  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:49:07.514  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 08:49:07.515  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 08:49:07.515  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:07.515  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 08:49:07.515  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:07.515  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:07.516  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:07.516  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 08:49:07.516  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:49:07.523  2158  2176 D BtGatt.GattService: registerClient() - UUID=e954a362-d7f8-4682-822c-4bfc65f42596,
,03-24 08:49:07.524  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:49:07.524  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:49:07.524  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=e954a362-d7f8-4682-822c-4bfc65f42596, clientIf=6
,03-24 08:49:07.525  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:49:07.527  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:07.528  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:07.528  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:49:07.528  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:49:07.530  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:07.531  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:49:07.531  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:49:07.533  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:49:07.533  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 08:49:07.538  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:07.542  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:07.545  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 08:49:07.546  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:07.546  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:49:07.547   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:07.552  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:49:07.552  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:49:07.552  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:49:07.552  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-24 08:49:07.554  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-24 08:49:07.554  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:49:07.554  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 08:49:07.556  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-24 08:49:07.559  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 08:49:07.559  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 08:49:07.560  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
03-24 08:49:07.561  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:49:07.561  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 08:49:07.561  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:49:07.561  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:49:07.561  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
03-24 08:49:07.561  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:07.561   825  2124 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:07.561  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:07.561  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-24 08:49:07.561  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:07.562  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:49:07.562  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:07.562  3312  3775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:49:07.563  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:07.563  3312  3370 I jxcore-log: 
03-24 08:49:07.569  3312  3370 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
03-24 08:49:07.569  3312  3370 I jxcore-log: ,
03-24 08:49:07.570  3312  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:49:07.574  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-24 08:49:07.574  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:07.574  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 08:49:07.574  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-24 08:49:07.574  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:07.588  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 08:49:07.588  3312  3370 I jxcore-log: 
,03-24 08:49:07.589  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:49:07.589  3312  3370 I jxcore-log: 
,03-24 08:49:07.591  3312  3370 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
03-24 08:49:07.591  3312  3370 I jxcore-log: 
,03-24 08:49:08.539  2158  2158 D BtGatt.ScanManager: awakened up at time 248462
03-24 08:49:08.542  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:08.553  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 08:49:08.553  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:08.554  2158  2222 D BtGatt.GattService: current time is 248476846258
03-24 08:49:08.554  2158  2222 D BtGatt.GattService: Batch record : [62, -87, -15, -92, 9, 116, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:49:08.555  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:08.555  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:08.558  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 08:49:08.559  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 08:49:08.559  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 08:49:08.560  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 08:49:08.564  3312  3370 I jxcore-log: ok 153 peers must be an array
03-24 08:49:08.564  3312  3370 I jxcore-log: 
,03-24 08:49:08.592  3312  3370 I jxcore-log: ok 154 peers must not be zero-length
03-24 08:49:08.592  3312  3370 I jxcore-log: 
03-24 08:49:08.593  3312  3370 I jxcore-log: ok 155 peer must have peerIdentifier
03-24 08:49:08.593  3312  3370 I jxcore-log: 
,03-24 08:49:08.594  3312  3370 I jxcore-log: ok 156 peerIdentifier must be a string
03-24 08:49:08.594  3312  3370 I jxcore-log: 
03-24 08:49:08.594  3312  3370 I jxcore-log: ok 157 peer must have peerAvailable
03-24 08:49:08.594  3312  3370 I jxcore-log: 
,03-24 08:49:08.594  3312  3370 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 08:49:08.594  3312  3370 I jxcore-log: 
,03-24 08:49:08.601  3312  3370 I jxcore-log: # teardown
03-24 08:49:08.601  3312  3370 I jxcore-log: 
,03-24 08:49:08.952  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-24 08:49:08.953  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 08:49:08.953  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 08:49:08.953  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:49:08.957  2158  2176 D BtGatt.GattService: stopScan() - queue size =1,
03-24 08:49:08.960  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:08.961  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:08.961  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 08:49:08.961  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:08.962  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 08:49:08.962  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-24 08:49:08.962  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-24 08:49:08.962  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:49:08.963  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-24 08:49:08.963  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:08.964  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:08.964  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 08:49:08.964  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:08.966  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:08.966  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:08.967  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:08.970  3312  3370 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:08.970  3312  3370 I jxcore-log: 
03-24 08:49:08.971  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:49:08.971  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:08.971  2158  2222 D BtGatt.GattService: current time is 248894298549
03-24 08:49:08.971  2158  2222 D BtGatt.GattService: Batch record : [62, -87, -15, -92, 9, 116, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:49:08.972  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:08.972  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:08.974  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:49:08.975  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-24 08:49:08.975  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:49:08.975  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 08:49:08.975  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:08.977  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:08.977  3312  3775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:49:08.977  3312  3775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:49:08.977  3312  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:49:08.978  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:49:08.979  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:49:08.979  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:49:08.979  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 08:49:08.979  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:08.979  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-24 08:49:08.979  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:08.980  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 08:49:08.981  3312  3370 D BluetoothLeScanner: could not find callback wrapper
03-24 08:49:08.981  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:08.982  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 08:49:08.985  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:49:08.986  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:49:08.989  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:08.989  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:49:08.990  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:08.991  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:49:08.991  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:08.991  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:49:08.991  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 08:49:08.991  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:08.991  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:08.991  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:08.991  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:08.992  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:08.992  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:49:08.992  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:49:08.992  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:08.992  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:08.992  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:49:08.992  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:08.992  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:08.997  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:08.997  3312  3370 I jxcore-log: 
,03-24 08:49:09.000  3312  3370 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
03-24 08:49:09.000  3312  3370 I jxcore-log: 
03-24 08:49:09.000  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:49:09.000   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:09.007  3312  3370 I jxcore-log: # setup
03-24 08:49:09.007  3312  3370 I jxcore-log: 
,03-24 08:49:09.008  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:09.009  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:09.009  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:09.012  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:49:09.013  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:49:09.015  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:09.015  3312  3370 I jxcore-log: 
,03-24 08:49:09.016  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:09.016  3312  3370 I jxcore-log: 
,03-24 08:49:09.368  3312  3370 I jxcore-log: # 38. Can connect to a remote peer
03-24 08:49:09.368  3312  3370 I jxcore-log: 
,03-24 08:49:10.783  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 49919, start advertisements: true
,03-24 08:49:10.783  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:10.783  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:10.783  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:49:10.789  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 08:49:10.789  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:10.790  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:10.790  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:10.794  2158  3243 D BtGatt.GattService: registerClient() - UUID=40b12f11-926c-4a20-abd7-04897e7aa9e6
,03-24 08:49:10.795  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=40b12f11-926c-4a20-abd7-04897e7aa9e6, clientIf=5
03-24 08:49:10.795  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:10.796  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:49:10.797  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:10.797  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:10.797  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 08:49:10.797  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:49:10.797  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:10.797  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-24 08:49:10.797  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:10.797  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:49:10.797  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:10.798  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:10.798  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:10.798  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:10.798  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:49:10.808  2158  2176 D BtGatt.GattService: registerClient() - UUID=50097257-453c-4f4c-ae15-a5e97ef25bf8,
,03-24 08:49:10.808  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:49:10.808  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:10.808  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=50097257-453c-4f4c-ae15-a5e97ef25bf8, clientIf=6
03-24 08:49:10.809  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:49:10.811  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:49:10.811  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:10.811  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:10.811  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:10.812  2158  2231 D BtGatt.AdvertiseManager: message : 0
03-24 08:49:10.815  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:49:10.815  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:10.817  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 08:49:10.817  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:10.820  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:10.824  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:10.828  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:10.829  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:10.829  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:49:10.830   825  2124 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:10.837  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 08:49:10.837  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:49:10.837  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:49:10.837  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:49:10.839  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 08:49:10.839  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:49:10.839  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:49:10.840  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:49:10.840  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 08:49:10.841  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:49:10.841  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:49:10.841  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:49:10.841  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 08:49:10.842  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:49:10.842  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:10.842  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:49:10.842  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:49:10.842  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:10.843  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:49:10.843   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:10.843  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:10.844  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:49:10.845  3312  3777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:49:10.848  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:10.848  3312  3370 I jxcore-log: 
,03-24 08:49:10.851  3312  3370 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
03-24 08:49:10.851  3312  3370 I jxcore-log: 
03-24 08:49:10.852  3312  3777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:49:10.859  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 49919, start advertisements: false
,03-24 08:49:10.859  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:10.859  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 08:49:10.859  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:10.860  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:49:10.862  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:10.862  3312  3370 I jxcore-log: 
,03-24 08:49:10.869  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:49:10.869  3312  3370 I jxcore-log: 
,03-24 08:49:10.871  3312  3370 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-24 08:49:10.871  3312  3370 I jxcore-log: 
,03-24 08:49:11.824  2158  2158 D BtGatt.ScanManager: awakened up at time 251746
,03-24 08:49:11.825  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:11.833  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 08:49:11.834  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:11.834  2158  2222 D BtGatt.GattService: current time is 251757160007
,03-24 08:49:11.834  2158  2222 D BtGatt.GattService: Batch record : [9, -70, -38, 93, 112, 79, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 08:49:11.835  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:11.838  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 08:49:11.839  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:49:11.844  3312  3370 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 08:49:11.844  3312  3370 I jxcore-log: 
,03-24 08:49:11.855  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-24 08:49:11.855  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 08:49:11.861  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-24 08:49:11.862  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 08:49:11.862  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 08:49:11.863  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-24 08:49:11.863  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
,03-24 08:49:11.863  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-24 08:49:11.865  3312  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 362)
03-24 08:49:11.866  3312  3778 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:49:11.870  2158  2175 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 08:49:13.684  2158  2236 W bt-btif : No ag scb for peer addr
,03-24 08:49:13.736  2158  2236 W bt-btif : info:x10
03-24 08:49:13.736  2158  2222 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 08:49:13.737  2158  2222 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 08:49:13.814  2158  2236 W bt-sdp  : process_service_search_attr_rsp
,03-24 08:49:14.082  2158  2222 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 08:49:14.091  2158  2222 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-24 08:49:14.091  2158  2222 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 08:49:14.097  2158  2223 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11,
03-24 08:49:14.099  2158  2223 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 08:49:14.177   825   856 I ActivityManager: Start proc 3780:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-24 08:49:14.216  2158  2222 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 08:49:14.217  2158  2223 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 08:49:14.221  2158  2223 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 08:49:14.265  2158  2223 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 08:49:14.318   825   860 D BluetoothManagerService: Message: 20
,03-24 08:49:14.319   825   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8bf9460:true
,03-24 08:49:14.321   825  1186 I ActivityManager: Killing 2966:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 08:49:16.840  2158  2158 D BtGatt.ScanManager: awakened up at time 256763
,03-24 08:49:16.844  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:16.849  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 08:49:16.849  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:16.850  2158  2222 D BtGatt.GattService: current time is 256773013338
,03-24 08:49:16.850  2158  2222 D BtGatt.GattService: Batch record : [9, -70, -38, 93, 112, 79, 1, -128, -79, 71, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 68, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:49:16.851  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 08:49:16.852  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 08:49:16.855  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-24 08:49:16.856  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-24 08:49:16.856  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 08:49:16.865  3312  3370 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 08:49:16.865  3312  3370 I jxcore-log: 
,03-24 08:49:17.914  2158  2236 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 66 RCID: 68,
,03-24 08:49:18.535  2158  2236 W bt-btif : new conn_srvc id:26, app_id:255,
03-24 08:49:18.535  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:49:18.535  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 08:49:18.536  3312  3777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 08:49:18.539  3312  3777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 363)
,03-24 08:49:18.539  3312  3777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:18.541   825  1186 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:18.541  3312  3800 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 363)
,03-24 08:49:18.544  3312  3777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:49:18.549  3312  3777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:49:18.618  2158  2236 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 08:49:18.618  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:49:18.618  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 08:49:18.618  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 08:49:18.619  3312  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 362)
03-24 08:49:18.620  3312  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 362)
,03-24 08:49:18.621  3312  3778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 364)
03-24 08:49:18.621  3312  3778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 364)
03-24 08:49:18.621  3312  3778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 362)
03-24 08:49:18.624  3312  3801 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 364)
,03-24 08:49:18.978  3312  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 363)
,03-24 08:49:18.981  3312  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 08:49:18.981  3312  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 363)
03-24 08:49:18.982  3312  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 363
03-24 08:49:18.982  3312  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 363)
,03-24 08:49:18.982  3312  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:18.984  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:18.985  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:18.985  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 08:49:18.987  3312  3800 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 363)
03-24 08:49:18.988  3312  3312 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:49:18.988  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:18.992  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:49:18.994  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:49:18.998  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:49:18.998  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:49:19.000  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:49:19.001  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:19.001  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:19.001  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:19.001  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:19.001  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:19.002  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:19.002  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.002  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.002  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:49:19.009  2158  2176 D BtGatt.GattService: registerClient() - UUID=928590d9-75c2-47ca-ac67-8a85b6b716d5
,03-24 08:49:19.009  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=928590d9-75c2-47ca-ac67-8a85b6b716d5, clientIf=6
03-24 08:49:19.010  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:49:19.010  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:19.014  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:19.016  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:19.019  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 08:49:19.019  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:19.022  2158  2175 D BtGatt.GattService: stopScan() - queue size =1,
03-24 08:49:19.023  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:19.023  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:19.023  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.024  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:19.025  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:19.025  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:19.025  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:19.025  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:19.025  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:49:19.025  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:49:19.026  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:19.026  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.026  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:19.029  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
03-24 08:49:19.029  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.029  2158  2222 D BtGatt.GattService: current time is 258952385941
03-24 08:49:19.029  2158  2222 D BtGatt.GattService: Batch record : [9, -70, -38, 93, 112, 79, 1, -128, -73, 33, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -69, 21, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 108, -60, 18, 57, -3, 122, 1, -128, -74, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -77, -86, -83, -124, 33, 68, 1, -128, -86, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 122, 30, -125, 67, 53, 96, 1, -128, -86, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 08:49:19.029  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:19.030  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:19.030  2158  2176 D BtGatt.GattService: registerClient() - UUID=ab0c9e8f-2779-4284-afb7-3d053cc0d7f0
03-24 08:49:19.030  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:19.030  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 08:49:19.030  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:19.030  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=ab0c9e8f-2779-4284-afb7-3d053cc0d7f0, clientIf=5
03-24 08:49:19.031  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:49:19.031  2158  2175 D BtGatt.GattService: start scan with filters
03-24 08:49:19.031  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:19.031  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:49:19.032  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:19.033  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:19.035  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:19.036  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:19.036  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.036  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:19.037  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:19.037  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.037  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:19.037  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:19.039  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:19.039  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.040  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:49:19.040  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:19.041  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:49:19.041  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:19.041  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:49:19.041  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:49:19.041  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:19.041  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 08:49:19.042  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:19.042  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.042  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.042  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:19.042  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:19.042  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.048  2158  2176 D BtGatt.GattService: registerClient() - UUID=59adbbf7-c1f1-42c9-9beb-ba2d3e2c8582,
03-24 08:49:19.048  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=59adbbf7-c1f1-42c9-9beb-ba2d3e2c8582, clientIf=6
03-24 08:49:19.049  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:49:19.050  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:19.053  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:19.055  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 08:49:19.058  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:19.059  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:19.061  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:49:19.062  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:19.062  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:19.062  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.062  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:19.062  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:19.063  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:19.063  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:19.063  3312  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 364)
03-24 08:49:19.063  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:19.063  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:19.064  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:49:19.064  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:19.064  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.064  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:19.065  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:19.065  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.067  3312  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:19.067  3312  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 362)
03-24 08:49:19.067  3312  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 362)
03-24 08:49:19.068  3312  3801 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 364)
,03-24 08:49:19.069  2158  3243 D BtGatt.GattService: registerClient() - UUID=2d17cb78-47bb-466a-964c-cae0e17ee56d
03-24 08:49:19.069  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=2d17cb78-47bb-466a-964c-cae0e17ee56d, clientIf=5
03-24 08:49:19.070  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:19.070  2158  2175 D BtGatt.GattService: start scan with filters
03-24 08:49:19.071  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:19.071  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:19.072  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:49:19.072  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 08:49:19.073  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:19.073  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.074  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:19.074  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.074  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:19.074  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:49:19.075  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:19.075  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.073  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:19.073  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:19.073  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:49:19.073  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:49:19.073  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:49:19.073  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:49:19.076  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:19.076  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.079  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:49:19.079  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:19.081  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:19.081  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:49:19.082  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:19.083  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:49:19.083  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:49:19.083  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 08:49:19.083  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:19.083  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:19.083  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:19.083  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.084  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.084  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:49:19.087  2158  2176 D BtGatt.GattService: registerClient() - UUID=291796e3-abff-46ec-9df7-1142e2729414
,03-24 08:49:19.087  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=291796e3-abff-46ec-9df7-1142e2729414, clientIf=6
03-24 08:49:19.088  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:49:19.088  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:19.091  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:19.093  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:19.095  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:19.095  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:19.096  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:49:19.097  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:19.098  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:19.098  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.098  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:19.098  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:19.098  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:19.098  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:19.098  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:19.098  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:49:19.098  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:49:19.099  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:19.099  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.099  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:19.100  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:19.100  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.103  2158  2176 D BtGatt.GattService: registerClient() - UUID=d767e0f8-c9f7-4d23-8ad8-37a569367f33
03-24 08:49:19.104  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=d767e0f8-c9f7-4d23-8ad8-37a569367f33, clientIf=5
,03-24 08:49:19.104  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:19.104  2158  2175 D BtGatt.GattService: start scan with filters
03-24 08:49:19.105  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:49:19.105  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:19.105  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-24 08:49:19.105  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 08:49:19.105  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:19.105  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:49:19.106  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:49:19.106  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:19.106  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:19.106  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:19.106  3312  3802 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 365)
,03-24 08:49:19.106  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:19.106  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:19.106  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 08:49:19.107  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 08:49:19.107  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 08:49:19.109  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:19.109  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.110  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:49:19.110  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.110  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:19.110  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:19.111  3312  3804 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 366)
03-24 08:49:19.111  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:19.111  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.112  3312  3804 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42446
03-24 08:49:19.112  3312  3804 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 08:49:19.112  3312  3804 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 42446 (peer ID: F8:95:C7:87:3C:51)
03-24 08:49:19.112  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:19.112  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:19.113  3312  3804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 08:49:19.114  3312  3802 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 49919
,03-24 08:49:19.116  3312  3802 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-24 08:49:19.117  3312  3802 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:49:19.118  3312  3802 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 08:49:19.118  3312  3805 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 367, name: Sender)
03-24 08:49:19.118  3312  3370 I jxcore-log: INFO testThaliMobileNative: 
03-24 08:49:19.118  3312  3370 I jxcore-log: 
03-24 08:49:19.119  3312  3802 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 365)
03-24 08:49:19.119  3312  3802 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 365)
,03-24 08:49:19.119  3312  3370 I jxcore-log: ok 163 Must have listeningPort
03-24 08:49:19.119  3312  3370 I jxcore-log: 
03-24 08:49:19.120  3312  3370 I jxcore-log: ok 164 listeningPort must be a number
03-24 08:49:19.120  3312  3370 I jxcore-log: 
,03-24 08:49:19.120  3312  3806 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 368, name: Receiver)
,03-24 08:49:19.120  3312  3370 I jxcore-log: ok 165 Connection must have clientPort,
03-24 08:49:19.120  3312  3370 I jxcore-log: 
03-24 08:49:19.121  3312  3370 I jxcore-log: ok 166 clientPort must be a number
03-24 08:49:19.121  3312  3370 I jxcore-log: 
03-24 08:49:19.121  3312  3370 I jxcore-log: ok 167 Connection must have serverPort
03-24 08:49:19.121  3312  3370 I jxcore-log: 
03-24 08:49:19.122  3312  3370 I jxcore-log: ok 168 serverPort must be a number
03-24 08:49:19.122  3312  3370 I jxcore-log: 
03-24 08:49:19.122  3312  3370 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 08:49:19.122  3312  3370 I jxcore-log: 
03-24 08:49:19.123  3312  3370 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-24 08:49:19.123  3312  3370 I jxcore-log: 
,03-24 08:49:19.128  3312  3370 I jxcore-log: # teardown
03-24 08:49:19.128  3312  3370 I jxcore-log: 
,03-24 08:49:19.334  3312  3805 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 367, thread name: Sender),
03-24 08:49:19.335  3312  3805 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 08:49:19.335  3312  3805 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-24 08:49:19.335  3312  3805 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 365
03-24 08:49:19.335  3312  3805 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 365)
,03-24 08:49:19.335  3312  3806 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 368, thread name: Receiver): bt socket closed, read return: -1
03-24 08:49:19.336  3312  3806 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 368, name: Receiver)
03-24 08:49:19.337  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:49:19.337  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only,
,03-24 08:49:19.337  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 08:49:19.337  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:49:19.338  3312  3805 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 08:49:19.338  3312  3805 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 08:49:19.338  3312  3805 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 368
03-24 08:49:19.338  3312  3805 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-24 08:49:19.339  3312  3805 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 367
03-24 08:49:19.339  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:49:19.339  3312  3805 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 365)
,03-24 08:49:19.340  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:19.341  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:19.341  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:19.341  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 08:49:19.341  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 08:49:19.341  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:49:19.341  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:19.341  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 08:49:19.341  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 08:49:19.341  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 08:49:19.341  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.341  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:49:19.342  3312  3805 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 365)
03-24 08:49:19.342  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:19.342  3312  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-24 08:49:19.344  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:19.344  3312  3370 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:19.344  3312  3370 I jxcore-log: 
03-24 08:49:19.345  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:49:19.345  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:19.345  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:19.345  3312  3370 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 08:49:19.345  3312  3370 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 366)
03-24 08:49:19.345  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 366)
,03-24 08:49:19.345  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 08:49:19.346  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 366)
03-24 08:49:19.346  3312  3370 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 366)
,03-24 08:49:19.346  3312  3804 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 366)
03-24 08:49:19.346  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:19.346  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.347  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-24 08:49:19.347  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 08:49:19.347  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:49:19.347  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:19.347  3312  3805 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 367, name: Sender)
,03-24 08:49:19.349  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 08:49:19.349  3312  3777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:49:19.349  3312  3777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:49:19.349  3312  3777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
03-24 08:49:19.349  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:49:19.349  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 08:49:19.349  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:49:19.350  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:19.350  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 08:49:19.350  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:49:19.350  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:49:19.351  3312  3370 D BluetoothLeScanner: could not find callback wrapper
03-24 08:49:19.351  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:19.351  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:49:19.354  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:19.354  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:19.356  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:19.356  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:19.357  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:49:19.358  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:19.358  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:19.358  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:49:19.358  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:49:19.358  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:19.358  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:19.358  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:19.358  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:19.359  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:19.359  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:49:19.359  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:19.359  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:19.359  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:19.359  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 08:49:19.360  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:19.360  3312  3370 I jxcore-log: 
03-24 08:49:19.362  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 08:49:19.362  3312  3370 I jxcore-log: 
03-24 08:49:19.364  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 08:49:19.364  3312  3370 I jxcore-log: 
03-24 08:49:19.366  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 08:49:19.367   825  2124 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:19.372  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 08:49:19.372  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:19.373  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:19.375  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-24 08:49:19.375  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:19.375  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:19.375  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:19.375  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:49:19.376  3312  3370 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown
03-24 08:49:19.376  3312  3370 I jxcore-log: 
,03-24 08:49:19.380  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:19.380  3312  3370 I jxcore-log: 
,03-24 08:49:19.381  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:19.381  3312  3370 I jxcore-log: 
,03-24 08:49:19.382  3312  3370 I jxcore-log: # setup
03-24 08:49:19.382  3312  3370 I jxcore-log: 
,03-24 08:49:19.537  3312  3370 I jxcore-log: # 39. Can shift large amounts of data
03-24 08:49:19.537  3312  3370 I jxcore-log: 
,03-24 08:49:19.738  2158  2220 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 08:49:19.808  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 47141, start advertisements: true
03-24 08:49:19.808  3312  3370 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0,
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:19.808  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:19.808  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 08:49:19.808  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 08:49:19.811  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 08:49:19.811  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:19.811  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:19.811  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:49:19.814  2158  3243 D BtGatt.GattService: registerClient() - UUID=ddaeafe7-ef62-4a03-a64f-ca11a3ae39d7
03-24 08:49:19.814  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=ddaeafe7-ef62-4a03-a64f-ca11a3ae39d7, clientIf=5
,03-24 08:49:19.815  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:49:19.816  2158  2176 D BtGatt.GattService: start scan with filters
03-24 08:49:19.817  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:19.818  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:49:19.818  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:49:19.818  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:49:19.818  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:19.818  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:19.818  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 08:49:19.818  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:19.818  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.818  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:19.818  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:19.818  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:19.819  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:19.822  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:49:19.822  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.824  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:19.824  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.825  2158  2175 D BtGatt.GattService: registerClient() - UUID=540a70f9-df96-4546-8de0-1dd7ec47fd7e
03-24 08:49:19.825  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=540a70f9-df96-4546-8de0-1dd7ec47fd7e, clientIf=6
03-24 08:49:19.825  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:19.825  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:49:19.826  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:19.828  2158  2231 D BtGatt.AdvertiseManager: message : 0
03-24 08:49:19.828  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:49:19.828  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.829  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:19.829  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:19.830  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:19.833  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 08:49:19.836  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 08:49:19.836  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:49:19.836  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:49:19.836   825  2124 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:19.838  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:19.838  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:49:19.838  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:49:19.838  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:49:19.839  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 08:49:19.839  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 08:49:19.839  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:49:19.839  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 08:49:19.840  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:49:19.840  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:19.840  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:19.840  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:49:19.840  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:49:19.840  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:49:19.840  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:49:19.840  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:19.840  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:19.840  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-24 08:49:19.840  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:19.841  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:49:19.841  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:19.841  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:19.841  3312  3370 I jxcore-log: 
03-24 08:49:19.841   825  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:19.842  3312  3370 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 08:49:19.842  3312  3370 I jxcore-log: 
,03-24 08:49:19.845  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 47141, start advertisements: false
03-24 08:49:19.845  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:19.845  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 08:49:19.845  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:19.845  3312  3807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:49:19.845  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:19.847  3312  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:49:19.847  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:19.847  3312  3370 I jxcore-log: 
,03-24 08:49:19.848  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:49:19.848  3312  3370 I jxcore-log: 
,03-24 08:49:19.849  3312  3370 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error
03-24 08:49:19.849  3312  3370 I jxcore-log: 
,03-24 08:49:19.876  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,03-24 08:49:19.876  2158  2236 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 08:49:20.371  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-24 08:49:22.296  2158  2158 D BtGatt.ScanManager: awakened up at time 262219
,03-24 08:49:22.298  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:22.309  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:49:22.309  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:22.309  2158  2222 D BtGatt.GattService: current time is 262232430055
,03-24 08:49:22.309  2158  2222 D BtGatt.GattService: Batch record : [108, -4, 82, -107, 7, 94, 1, -128, -78, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:49:22.310  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:22.311  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 08:49:22.314  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 08:49:22.315  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-24 08:49:22.315  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 08:49:22.316  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:49:22.330  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 08:49:22.331  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:49:22.335  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-24 08:49:22.336  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 08:49:22.336  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 08:49:22.336  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-24 08:49:22.336  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-24 08:49:22.337  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 08:49:22.340  3312  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 370)
,03-24 08:49:22.340  3312  3808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:49:22.345  2158  2175 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 08:49:22.644  2158  2236 E bt-btm  : tBTM_SEC_DEV:0xa2faceb4 rs_disc_pending=1
,03-24 08:49:22.644  2158  2236 W bt-btif : bta_dm_check_av:0
03-24 08:49:22.645  2158  2222 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 08:49:22.691  2158  2236 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,03-24 08:49:22.691  2158  2236 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x43
,03-24 08:49:22.782  2158  2236 W bt-btif : No ag scb for peer addr
,03-24 08:49:22.837  2158  2236 W bt-btif : info:x10
,03-24 08:49:22.837  2158  2222 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-24 08:49:22.838  2158  2222 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 08:49:23.027  2158  2236 E bt-btm  : tBTM_SEC_DEV:0xa2fad07c rs_disc_pending=1
,03-24 08:49:23.028  2158  2236 W bt-btif : bta_dm_check_av:0
03-24 08:49:23.028  2158  2222 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 08:49:23.176  2158  2236 W bt-sdp  : process_service_search_attr_rsp
,03-24 08:49:23.524  2158  2222 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-24 08:49:23.532  2158  2222 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
03-24 08:49:23.532  2158  2222 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 08:49:23.538  2158  2223 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
03-24 08:49:23.539  2158  2223 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 08:49:23.614  2158  2222 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,03-24 08:49:23.614  2158  2223 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-24 08:49:23.620  2158  2223 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-24 08:49:23.638  2158  2223 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 08:49:25.872  2158  2236 E bt-btm  : tBTM_SEC_DEV:0xa2fad07c rs_disc_pending=0
,03-24 08:49:25.872  2158  2236 W bt-btif : bta_dm_check_av:0
03-24 08:49:25.872  2158  2222 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 08:49:26.417  2158  2236 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 08:49:26.424  2158  2158 D BluetoothMapService: onReceive
,03-24 08:49:26.507   825  1466 I ActivityManager: Start proc 3810:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-24 08:49:26.526   370   370 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 354us total 17.768ms
,03-24 08:49:26.544   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 445us total 16.601ms
,03-24 08:49:26.561   370   370 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 233us total 15.987ms
,03-24 08:49:26.624   825   860 D BluetoothManagerService: Message: 20
03-24 08:49:26.625   825   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@356bf1d5:true
,03-24 08:49:26.638  3810  3810 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 08:49:26.862   825  1466 I ActivityManager: Start proc 3836:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-24 08:49:26.863  3810  3810 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 08:49:26.868   825  1324 I ActivityManager: Killing 3463:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-24 08:49:26.988   825  1323 I ActivityManager: Killing 3501:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 08:49:27.333  2158  2158 D BtGatt.ScanManager: awakened up at time 267255
,03-24 08:49:27.334  2158  2236 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 70 RCID: 69
03-24 08:49:27.335  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:27.338  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:49:27.338  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.338  2158  2222 D BtGatt.GattService: current time is 267261350001
03-24 08:49:27.338  2158  2222 D BtGatt.GattService: Batch record : [108, -4, 82, -107, 7, 94, 1, -128, -73, 37, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -56, 39, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:49:27.338  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:49:27.339  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:27.340  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 08:49:27.340  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 08:49:27.362  2158  2236 W bt-btif : new conn_srvc id:26, app_id:255
03-24 08:49:27.362  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:49:27.362  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 08:49:27.362  3312  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 08:49:27.363  3312  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 371)
03-24 08:49:27.363  3312  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 08:49:27.364   825  1323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:27.365  3312  3856 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 371)
03-24 08:49:27.366  3312  3807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:49:27.369  3312  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:49:27.373  2158  2236 W bt-btif : new conn_srvc id:26, app_id:1
03-24 08:49:27.373  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:49:27.373  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 08:49:27.373  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 08:49:27.374  3312  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 370)
03-24 08:49:27.374  3312  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 370)
03-24 08:49:27.374  3312  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 372)
,03-24 08:49:27.374  3312  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 372)
03-24 08:49:27.374  3312  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 370)
03-24 08:49:27.376  3312  3857 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 372)
,03-24 08:49:27.390  1258  3765 I art     : Explicit concurrent mark sweep GC freed 76103(4MB) AllocSpace objects, 12(946KB) LOS objects, 35% free, 28MB/44MB, paused 5.236ms total 106.793ms
,03-24 08:49:27.412  3312  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 371)
,03-24 08:49:27.416  3312  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:27.416  3312  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 371)
,03-24 08:49:27.416  3312  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 371
,03-24 08:49:27.417  3312  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 371)
03-24 08:49:27.417  3312  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:27.417  3312  3856 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 371)
03-24 08:49:27.417  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:27.417  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:27.417  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 08:49:27.418  3312  3312 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings,
,03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:49:27.418  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:27.422  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:49:27.423  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:27.425  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:27.425  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:27.426  3312  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 372)
03-24 08:49:27.426  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:27.427  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:27.427  3312  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:27.427  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:27.427  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:27.427  3312  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 370)
03-24 08:49:27.427  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:27.427  3312  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 370)
03-24 08:49:27.427  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 08:49:27.427  3312  3857 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 372)
03-24 08:49:27.427  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:27.427  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:27.427  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:27.427  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:27.433  2158  2176 D BtGatt.GattService: registerClient() - UUID=fea8cd00-7f0b-4904-ad19-a0143c75ae82
03-24 08:49:27.434  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=fea8cd00-7f0b-4904-ad19-a0143c75ae82, clientIf=6
03-24 08:49:27.434  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:49:27.436  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:27.441  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:27.443  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 08:49:27.446  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 08:49:27.446  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:27.458  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:27.460  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:27.460  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:27.460  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:27.460  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:27.460  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:27.460  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:27.460  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:27.463  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 08:49:27.463  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.463  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-24 08:49:27.465  2158  2176 D BtGatt.GattService: registerClient() - UUID=4df98afe-63cb-40ae-bd13-86abe11dd899
,03-24 08:49:27.466  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=4df98afe-63cb-40ae-bd13-86abe11dd899, clientIf=5
03-24 08:49:27.466  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:49:27.467  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:49:27.468  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:49:27.468  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:27.470  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:27.470  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:27.470  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:27.471  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:27.472  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:49:27.474  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
,03-24 08:49:27.474  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.475  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:49:27.475  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:27.477  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:27.478  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:27.478  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:49:27.478  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:49:27.478  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 08:49:27.478  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:27.478  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:49:27.479  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:27.479  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:27.479  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:27.479  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:27.481  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:27.481  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.482  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:27.482  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:27.482  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:49:27.482  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 08:49:27.484  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:27.484  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.485  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:49:27.485  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:27.486  2158  2176 D BtGatt.GattService: registerClient() - UUID=5ff69299-0390-4c5b-845a-9ae9566d1e03
03-24 08:49:27.486  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=5ff69299-0390-4c5b-845a-9ae9566d1e03, clientIf=6
03-24 08:49:27.487  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:49:27.488  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:27.490  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:27.492  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:27.495  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:27.495  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:27.497  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:27.498  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:27.498  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:27.498  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:27.498  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:27.498  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:27.498  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:27.498  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:27.499  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.499  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:27.499  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:27.501  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:27.501  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.501  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:27.502  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:27.502  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.503  2158  2175 D BtGatt.GattService: registerClient() - UUID=3553a620-d271-4950-baf4-66020c8c997d
03-24 08:49:27.503  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=3553a620-d271-4950-baf4-66020c8c997d, clientIf=5
03-24 08:49:27.503  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:27.503  2158  3243 D BtGatt.GattService: start scan with filters
03-24 08:49:27.504  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:27.504  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:27.504  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 08:49:27.506  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:27.506  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:27.506  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:49:27.506  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:49:27.506  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:49:27.506  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:27.509  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:27.509  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:27.510  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:27.511  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:27.511  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:27.512  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:27.512  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:49:27.512  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:49:27.512  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:49:27.512  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:27.512  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 08:49:27.513  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:49:27.513  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:27.513  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:27.513  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:27.513  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:27.513  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:27.514  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:27.514  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.515  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:27.515  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:49:27.516  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:27.516  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.517  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:27.517  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:27.518  2158  2176 D BtGatt.GattService: registerClient() - UUID=02abd927-ff47-4566-a678-a0059fcf0efc
03-24 08:49:27.518  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=02abd927-ff47-4566-a678-a0059fcf0efc, clientIf=6
,03-24 08:49:27.518  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:49:27.520  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:27.522  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:49:27.524  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:49:27.526  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:49:27.527  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:49:27.528  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:27.529  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:49:27.529  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:27.529  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:27.529  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:27.529  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:27.529  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:27.529  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:27.529  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:27.529  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-24 08:49:27.529  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:27.531  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:27.531  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.531  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:49:27.532  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:27.532  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.532  2158  2176 D BtGatt.GattService: registerClient() - UUID=2b34d96e-91d5-487d-aca0-1e7fdd2f3447
03-24 08:49:27.532  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=2b34d96e-91d5-487d-aca0-1e7fdd2f3447, clientIf=5
03-24 08:49:27.532  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:49:27.533  2158  3243 D BtGatt.GattService: start scan with filters
,03-24 08:49:27.535  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:49:27.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:27.535  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:27.535  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 08:49:27.535  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1,
03-24 08:49:27.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:49:27.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:27.535  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:49:27.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 08:49:27.535  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:27.536  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:27.536  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:27.536  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.536  3312  3859 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 373)
03-24 08:49:27.536  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:27.536  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 08:49:27.536  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 08:49:27.536  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 08:49:27.537  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:27.537  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.537  3312  3860 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 374)
03-24 08:49:27.537  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:27.537  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:27.537  3312  3860 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56592
03-24 08:49:27.537  3312  3860 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-24 08:49:27.538  3312  3860 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 56592 (peer ID: E0:DB:10:14:E2:C0)
03-24 08:49:27.538  3312  3860 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 08:49:27.538  3312  3859 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47141
03-24 08:49:27.538  3312  3859 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 08:49:27.538  3312  3859 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:49:27.539  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:27.539  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.539  3312  3859 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 08:49:27.540  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:27.540  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:27.540  3312  3862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 375, name: Sender)
03-24 08:49:27.541  3312  3859 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 373)
03-24 08:49:27.541  3312  3859 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 373)
03-24 08:49:27.542  3312  3863 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 376, name: Receiver)
03-24 08:49:27.542  3312  3370 I jxcore-log: INFO testThaliMobileNative: 
03-24 08:49:27.542  3312  3370 I jxcore-log: 
03-24 08:49:27.542  3312  3370 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 08:49:27.542  3312  3370 I jxcore-log: 
,03-24 08:49:27.545  3312  3860 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 56592
,03-24 08:49:27.545  3312  3860 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 08:49:27.545  3312  3860 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:49:27.545  3312  3860 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:49:27.545  3312  3860 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 374)
03-24 08:49:27.545  3312  3860 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 374)
,03-24 08:49:27.547  3312  3865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 378, name: Receiver)
,03-24 08:49:27.548  3312  3864 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 377, name: Sender)
,03-24 08:49:27.548  3312  3370 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 08:49:27.548  3312  3370 I jxcore-log: 
,03-24 08:49:28.003  3312  3370 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 08:49:28.003  3312  3370 I jxcore-log: 
,03-24 08:49:28.133  3312  3370 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 08:49:28.133  3312  3370 I jxcore-log: 
,03-24 08:49:28.227  3312  3370 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 08:49:28.227  3312  3370 I jxcore-log: 
,03-24 08:49:28.302  3312  3370 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 08:49:28.302  3312  3370 I jxcore-log: 
,03-24 08:49:28.478  3312  3370 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-24 08:49:28.478  3312  3370 I jxcore-log: ,
,03-24 08:49:28.480  3312  3370 I jxcore-log: ok 175 received should match sent forward,
03-24 08:49:28.480  3312  3370 I jxcore-log: ,
03-24 08:49:28.495  3312  3370 I jxcore-log: # teardown
03-24 08:49:28.495  3312  3370 I jxcore-log: ,
,03-24 08:49:28.753  3312  3862 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 375, thread name: Sender),
03-24 08:49:28.754  3312  3862 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 08:49:28.754  3312  3862 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-24 08:49:28.754  3312  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 373
03-24 08:49:28.754  3312  3862 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 373)
,03-24 08:49:28.755  3312  3862 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 08:49:28.755  3312  3862 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 08:49:28.755  3312  3862 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 376
03-24 08:49:28.755  3312  3862 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-24 08:49:28.755  3312  3863 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Receiver): bt socket closed, read return: -1
03-24 08:49:28.755  3312  3862 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 375
03-24 08:49:28.755  3312  3862 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 373)
03-24 08:49:28.755  3312  3863 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 376, name: Receiver)
03-24 08:49:28.756  3312  3862 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 373)
,03-24 08:49:28.756  3312  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 08:49:28.757  3312  3862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 375, name: Sender),
03-24 08:49:28.763  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:49:28.763  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 08:49:28.764  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 08:49:28.764  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:49:28.768  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:49:28.771  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:49:28.771  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:28.771  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:28.772  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:28.773  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:49:28.773  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:28.773  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:49:28.773  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:49:28.773  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:49:28.773  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:28.773  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-24 08:49:28.773  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 08:49:28.773  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:28.775  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 08:49:28.775  3312  3370 I jxcore-log: 
03-24 08:49:28.775  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:28.775  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:28.776  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:28.777  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 08:49:28.777  3312  3370 I jxcore-log: 
03-24 08:49:28.778  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-24 08:49:28.778  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:28.778  2158  2222 D BtGatt.GattService: current time is 268701653594
03-24 08:49:28.778  2158  2222 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -77, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:49:28.779  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 08:49:28.781  3312  3370 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-24 08:49:28.781  3312  3370 I jxcore-log: 
03-24 08:49:28.781  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:49:28.782  3312  3370 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:49:28.782  3312  3370 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 374)
03-24 08:49:28.782  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 374)
03-24 08:49:28.782  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 08:49:28.782  3312  3370 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 08:49:28.782  3312  3370 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 378
03-24 08:49:28.782  3312  3865 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 378, thread name: Receiver): bt socket closed, read return: -1
03-24 08:49:28.782  3312  3370 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,03-24 08:49:28.782  3312  3370 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 377
03-24 08:49:28.782  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 374)
03-24 08:49:28.782  3312  3865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 378, name: Receiver)
03-24 08:49:28.783  3312  3864 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Sender): Socket closed
03-24 08:49:28.783  3312  3864 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 377, name: Sender)
03-24 08:49:28.783  3312  3370 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 374)
,03-24 08:49:28.783  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 08:49:28.783  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:49:28.783  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:49:28.783  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:28.783  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:28.783  3312  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 08:49:28.783  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:49:28.783  3312  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:49:28.783  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:28.783  3312  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:49:28.783  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 08:49:28.783  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:28.784  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:49:28.784  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:49:28.784  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 08:49:28.784  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:49:28.786  3312  3370 D BluetoothLeScanner: could not find callback wrapper
03-24 08:49:28.786  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:28.786  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:49:28.789  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:49:28.789  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:28.791  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:28.791  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:28.793  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:49:28.793  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:49:28.793  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:49:28.794  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:49:28.794  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 08:49:28.794  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:28.794  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:28.794  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:28.794  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:28.795  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:28.795  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:49:28.795  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:28.795  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:28.795  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:49:28.795  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:49:28.795  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:28.795  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:28.803  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:49:28.803   825  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:28.809  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:28.809  3312  3370 I jxcore-log: 
,03-24 08:49:28.810  3312  3370 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-24 08:49:28.810  3312  3370 I jxcore-log: 
03-24 08:49:28.811  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 08:49:28.812  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:28.812  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:28.816  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:49:28.816  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:49:28.819  3312  3370 I jxcore-log: # setup
03-24 08:49:28.819  3312  3370 I jxcore-log: 
,03-24 08:49:28.821  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 08:49:28.821  3312  3370 I jxcore-log: 
03-24 08:49:28.822  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:28.822  3312  3370 I jxcore-log: 
,03-24 08:49:28.838  2158  2220 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 08:49:28.892  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND,
03-24 08:49:28.892  2158  2236 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 08:49:29.038  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND,
,03-24 08:49:30.352  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:30.352  3312  3370 I jxcore-log: 
,03-24 08:49:30.358  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:30.358  3312  3370 I jxcore-log: 
,03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:30.366  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:30.369  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:30.371  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:49:30.371  3312  3370 I jxcore-log: 
,03-24 08:49:30.372  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:49:30.372  3312  3370 I jxcore-log: 
,03-24 08:49:30.375  3312  3370 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-24 08:49:30.375  3312  3370 I jxcore-log: 
,03-24 08:49:30.377  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:49:30.377  3312  3370 I jxcore-log: 
,03-24 08:49:30.961  3312  3370 I jxcore-log: ok 178 specific error should be returned
03-24 08:49:30.961  3312  3370 I jxcore-log: 
,03-24 08:49:30.963  3312  3370 I jxcore-log: # teardown
03-24 08:49:30.963  3312  3370 I jxcore-log: 
,03-24 08:49:32.795  3312  3370 I jxcore-log: ok 179 must be stopped
03-24 08:49:32.795  3312  3370 I jxcore-log: 
,03-24 08:49:32.801  3312  3370 I jxcore-log: # setup,
03-24 08:49:32.801  3312  3370 I jxcore-log: 
,03-24 08:49:32.919  2158  2236 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 08:49:32.925  2158  2158 D BluetoothMapService: onReceive
,03-24 08:49:32.957  3810  3810 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 08:49:32.961  3810  3810 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 08:49:34.497  3425  3867 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 08:49:34.576  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-24 08:49:34.577  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:49:34.577  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:49:34.577  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:49:34.589  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:49:34.619  3425  3867 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 08:49:34.620  3425  3867 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 08:49:34.665  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:34.665  3312  3370 I jxcore-log: 
,03-24 08:49:34.666  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:34.666  3312  3370 I jxcore-log: 
,03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:34.676  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:34.682  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:34.688  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:49:34.688  3312  3370 I jxcore-log: 
,03-24 08:49:34.692  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:49:34.692  3312  3370 I jxcore-log: 
,03-24 08:49:34.698  3312  3370 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
03-24 08:49:34.698  3312  3370 I jxcore-log: 
,03-24 08:49:34.703  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:49:34.703  3312  3370 I jxcore-log: 
,03-24 08:49:36.745  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-24 08:49:39.509  3312  3370 I jxcore-log: ok 180 specific error should be returned
03-24 08:49:39.509  3312  3370 I jxcore-log: 
,03-24 08:49:39.512  3312  3370 I jxcore-log: # teardown
03-24 08:49:39.512  3312  3370 I jxcore-log: 
,03-24 08:49:40.525  3312  3370 I jxcore-log: ok 181 must be stopped
03-24 08:49:40.525  3312  3370 I jxcore-log: 
,03-24 08:49:40.529  3312  3370 I jxcore-log: # setup
03-24 08:49:40.529  3312  3370 I jxcore-log: 
,03-24 08:49:43.483  3312  3312 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:49:43.484  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:43.485  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2,
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:49:43.486  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:47.129  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:47.129  3312  3370 I jxcore-log: 
,03-24 08:49:47.130  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:47.130  3312  3370 I jxcore-log: 
,03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:47.138  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:47.145  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:47.147  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 08:49:47.147  3312  3370 I jxcore-log: 
,03-24 08:49:47.149  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 08:49:47.149  3312  3370 I jxcore-log: 
,03-24 08:49:47.154  3312  3370 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
,03-24 08:49:47.154  3312  3370 I jxcore-log: 
,03-24 08:49:47.157  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 08:49:47.157  3312  3370 I jxcore-log: 
,03-24 08:49:49.395  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 08:49:49.395  3312  3370 I jxcore-log: 
,03-24 08:49:49.398  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 49692
03-24 08:49:49.398  3312  3370 I jxcore-log: 
,03-24 08:49:49.401  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:49.402  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:49.402  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:49.406  3312  3370 I jxcore-log: ok 182 no errors
,03-24 08:49:49.406  3312  3370 I jxcore-log: 
,03-24 08:49:49.407  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:49.408  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:49.408  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:49.411  3312  3370 I jxcore-log: ok 183 still no errors
,03-24 08:49:49.411  3312  3370 I jxcore-log: 
,03-24 08:49:49.419  3312  3370 I jxcore-log: # teardown
,03-24 08:49:49.419  3312  3370 I jxcore-log: 
,03-24 08:49:50.610  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:50.610  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:50.610  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:50.612  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:50.613  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:50.613  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:50.626  3312  3370 I jxcore-log: ok 184 must be stopped
,03-24 08:49:50.626  3312  3370 I jxcore-log: 
,03-24 08:49:50.635  3312  3370 I jxcore-log: # setup
,03-24 08:49:50.635  3312  3370 I jxcore-log: 
,03-24 08:49:53.697  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:53.697  3312  3370 I jxcore-log: 
,03-24 08:49:53.704  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:53.704  3312  3370 I jxcore-log: 
,03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:53.716  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:53.723  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:53.724  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-24 08:49:53.724  3312  3370 I jxcore-log: 
03-24 08:49:53.726  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-24 08:49:53.726  3312  3370 I jxcore-log: 
,03-24 08:49:53.732  3312  3370 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
,03-24 08:49:53.732  3312  3370 I jxcore-log: 
,03-24 08:49:53.735  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-24 08:49:53.735  3312  3370 I jxcore-log: 
,03-24 08:49:53.872  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 08:49:53.872  3312  3370 I jxcore-log: 
,03-24 08:49:53.875  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 52515
,03-24 08:49:53.875  3312  3370 I jxcore-log: 
,03-24 08:49:53.882  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 47141, start advertisements: false,
03-24 08:49:53.882  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:49:53.882  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:53.882  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 08:49:53.888  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 08:49:53.888  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:53.888  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:53.893  2158  2175 D BtGatt.GattService: registerClient() - UUID=5e70203a-0b10-42fe-8294-de8210de35b4
,03-24 08:49:53.894  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=5e70203a-0b10-42fe-8294-de8210de35b4, clientIf=5
,03-24 08:49:53.895  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:49:53.896  2158  3243 D BtGatt.GattService: start scan with filters
,03-24 08:49:53.897  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:49:53.898  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:49:53.898  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:49:53.898  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:49:53.898  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 08:49:53.899  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 08:49:53.899  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:49:53.899  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:53.899   825  1186 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:53.907  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:49:53.907  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:49:53.908  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:53.908  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:49:53.908  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:49:53.909  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:53.911  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:53.911  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:53.913  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 08:49:53.913  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:53.913  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan,
03-24 08:49:53.914  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:49:53.917  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:49:53.917  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:53.918  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:53.918  3312  3370 I jxcore-log: 
03-24 08:49:53.919  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 08:49:53.919  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:53.920  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:53.920  3312  3370 I jxcore-log: 
,03-24 08:49:53.923  3312  3370 I jxcore-log: ok 185 no errors
03-24 08:49:53.923  3312  3370 I jxcore-log: 
,03-24 08:49:53.930  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 47141, start advertisements: false
,03-24 08:49:53.930  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:53.930  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:49:53.930  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:53.930  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:53.933  3312  3370 I jxcore-log: ok 186 still no errors
03-24 08:49:53.933  3312  3370 I jxcore-log: 
,03-24 08:49:53.939  3312  3370 I jxcore-log: # teardown
03-24 08:49:53.939  3312  3370 I jxcore-log: 
,03-24 08:49:54.501  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 08:49:54.501  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
03-24 08:49:54.501  3312  3370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 08:49:54.501  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 08:49:54.501  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:54.501  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:49:54.501  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 08:49:54.501  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:49:54.502  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:49:54.510  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:54.512  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 08:49:54.513  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:54.514  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:54.514  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:54.515  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:54.515  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:54.515  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:49:54.516  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 08:49:54.516  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 08:49:54.516  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:49:54.518  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:49:54.518  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:54.519  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:49:54.519  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:54.519  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:54.519  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 08:49:54.520  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:54.520  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:49:54.520  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:54.522  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 08:49:54.522  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:54.522  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:54.522  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:49:54.532  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:49:54.533   825  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:54.543  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:49:54.545  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:49:54.545  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:54.552  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:49:54.552  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:54.552  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:54.552  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-24 08:49:54.555  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:49:54.555  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 08:49:54.555  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:54.558  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:54.558  3312  3370 I jxcore-log: 
,03-24 08:49:54.560  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:54.560  3312  3370 I jxcore-log: 
,03-24 08:49:54.569  3312  3370 I jxcore-log: ok 187 must be stopped
03-24 08:49:54.569  3312  3370 I jxcore-log: 
,03-24 08:49:54.580  3312  3370 I jxcore-log: # setup
03-24 08:49:54.580  3312  3370 I jxcore-log: 
,03-24 08:49:54.769  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:54.769  3312  3370 I jxcore-log: 
,03-24 08:49:54.774  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:54.774  3312  3370 I jxcore-log: 
,03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:54.784  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:54.788  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:54.789  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:49:54.789  3312  3370 I jxcore-log: 
03-24 08:49:54.791  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:49:54.791  3312  3370 I jxcore-log: 
,03-24 08:49:54.794  3312  3370 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
03-24 08:49:54.794  3312  3370 I jxcore-log: 
03-24 08:49:54.796  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:49:54.796  3312  3370 I jxcore-log: 
,03-24 08:49:54.935  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 08:49:54.935  3312  3370 I jxcore-log: 
,03-24 08:49:54.939  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 50757
03-24 08:49:54.939  3312  3370 I jxcore-log: 
,03-24 08:49:54.946  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 50757, start advertisements: true
03-24 08:49:54.946  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:49:54.946  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:54.946  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:49:54.954  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 08:49:54.954  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:49:54.954  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:49:54.954  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:49:54.962  2158  2176 D BtGatt.GattService: registerClient() - UUID=1b532073-72b0-46b7-8855-f38e0be8b252
,03-24 08:49:54.962  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=1b532073-72b0-46b7-8855-f38e0be8b252, clientIf=5
03-24 08:49:54.963  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:49:54.963  2158  3243 D BtGatt.GattService: start scan with filters
03-24 08:49:54.965  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:49:54.966  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:49:54.966  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:49:54.966  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:49:54.966  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 08:49:54.969  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:54.970  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:49:54.970  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:49:54.970  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:49:54.970  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:49:54.970  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:54.971  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:49:54.971  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:49:54.973  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:49:54.973  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:54.974  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:49:54.974  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:54.974  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:49:54.974  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:49:54.977  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:49:54.977  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:54.978  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:49:54.978  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:49:54.984  2158  2175 D BtGatt.GattService: registerClient() - UUID=c5acc1d0-a6bc-4783-b15c-fb4fce732229
,03-24 08:49:54.984  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=c5acc1d0-a6bc-4783-b15c-fb4fce732229, clientIf=6
03-24 08:49:54.985  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:49:54.986  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:49:54.991  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 08:49:54.995  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 08:49:54.998  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 08:49:54.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-24 08:49:54.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:49:55.000   825   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:55.008  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 08:49:55.008  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:49:55.008  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:49:55.008  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:55.009  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 08:49:55.010  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:49:55.010  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:49:55.010  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:49:55.011  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:49:55.011  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:49:55.011  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:49:55.011  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:49:55.012  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:49:55.012  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:49:55.012  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:55.012  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:49:55.012  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:49:55.012  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:55.012  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:49:55.012  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:49:55.012  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:49:55.013   825  1323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:49:55.015  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:49:55.015  3312  3370 I jxcore-log: 
,03-24 08:49:55.017  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 08:49:55.017  3312  3370 I jxcore-log: 
,03-24 08:49:55.018  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:49:55.018  3312  3370 I jxcore-log: 
03-24 08:49:55.020  3312  3370 I jxcore-log: ok 188 no errors
03-24 08:49:55.020  3312  3370 I jxcore-log: 
,03-24 08:49:55.024  3312  3871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-24 08:49:55.027  3312  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
03-24 08:49:55.028  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 50757, start advertisements: true,
03-24 08:49:55.028  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:49:55.028  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:49:55.028  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:55.028  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:49:55.032  3312  3370 I jxcore-log: ok 189 still no errors
,03-24 08:49:55.032  3312  3370 I jxcore-log: 
,03-24 08:49:55.040  3312  3370 I jxcore-log: # teardown
,03-24 08:49:55.040  3312  3370 I jxcore-log: 
,03-24 08:49:55.989  2158  2158 D BtGatt.ScanManager: awakened up at time 295912
,03-24 08:49:55.992  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 08:49:56.002  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 08:49:56.002  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:56.003  2158  2222 D BtGatt.GattService: current time is 295925976761
03-24 08:49:56.003  2158  2222 D BtGatt.GattService: Batch record : [117, -93, -83, -10, 22, 67, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:49:56.004  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 08:49:56.004  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:49:56.007  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 08:49:56.008  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 08:49:56.008  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 08:49:56.009  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:49:56.016  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:49:56.016  3312  3370 I jxcore-log: 
,03-24 08:49:56.027  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 08:49:56.027  3312  3370 I jxcore-log: 
03-24 08:49:56.031  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-24 08:49:56.031  3312  3370 I jxcore-log: 
03-24 08:49:56.037  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 08:49:56.037  3312  3370 I jxcore-log: 
,03-24 08:49:56.970  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:49:56.970  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 08:49:56.970  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:49:56.970  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 08:49:56.970  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:49:56.970  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:49:56.970  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:49:56.970  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:49:56.970  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:49:56.970  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:49:56.970  3312  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:49:56.970  3312  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:49:56.971  3312  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:49:56.972  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:49:56.972  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 08:49:56.975  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:49:56.977  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 08:49:56.978  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:49:56.978  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:56.978  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:49:56.979  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:49:56.979  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:49:56.979  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:56.979  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 08:49:56.979  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:49:56.979  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:49:56.979  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:49:56.982  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 08:49:56.982  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:56.983  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:49:56.983  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:49:56.983  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:49:56.987  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:49:56.987  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:49:56.989  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:49:56.989  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 08:49:56.989  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:49:56.990  2158  2222 D BtGatt.GattService: current time is 296912889468
,03-24 08:49:56.990  2158  2222 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -64, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:49:56.990  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 08:49:56.997  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-24 08:49:56.997  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:49:56.997  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:49:56.997  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:49:56.997  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:49:56.998  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:56.998  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:49:56.998  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:49:56.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:49:56.999  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:49:56.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:57.000  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:57.000  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:49:57.000  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 08:49:57.008  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:49:57.009   825  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:49:57.020  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 08:49:57.021  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:49:57.021  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:49:57.021  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 08:49:57.021  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:49:57.025  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 08:49:57.025  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:57.025  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:49:57.026  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:49:57.026  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:49:57.026  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 08:49:57.029  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:49:57.029  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:57.029  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:49:57.030  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:49:57.030  3312  3370 I jxcore-log: 
,03-24 08:49:57.031  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:57.031  3312  3370 I jxcore-log: 
,03-24 08:49:57.032  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:49:57.032  3312  3370 I jxcore-log: 
,03-24 08:49:57.037  3312  3370 I jxcore-log: ok 190 must be stopped
03-24 08:49:57.037  3312  3370 I jxcore-log: 
,03-24 08:49:57.043  3312  3370 I jxcore-log: # setup
03-24 08:49:57.043  3312  3370 I jxcore-log: 
,03-24 08:49:57.290  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:57.290  3312  3370 I jxcore-log: 
,03-24 08:49:57.292  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:57.292  3312  3370 I jxcore-log: 
,03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:57.300  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:57.304  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-24 08:49:57.307  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:49:57.307  3312  3370 I jxcore-log: ,
,03-24 08:49:57.311  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:49:57.311  3312  3370 I jxcore-log: 
,03-24 08:49:57.318  3312  3370 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times,
03-24 08:49:57.318  3312  3370 I jxcore-log: 
,03-24 08:49:57.322  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-24 08:49:57.322  3312  3370 I jxcore-log: 
,03-24 08:49:57.476  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 08:49:57.476  3312  3370 I jxcore-log: 
,03-24 08:49:57.478  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 42848
03-24 08:49:57.478  3312  3370 I jxcore-log: 
,03-24 08:49:57.480  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:49:57.480  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:57.480  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:57.482  3312  3370 I jxcore-log: ok 191 no errors
03-24 08:49:57.482  3312  3370 I jxcore-log: 
03-24 08:49:57.483  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:49:57.483  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:49:57.483  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:57.486  3312  3370 I jxcore-log: ok 192 still no errors
03-24 08:49:57.486  3312  3370 I jxcore-log: 
,03-24 08:49:57.491  3312  3370 I jxcore-log: # teardown
03-24 08:49:57.491  3312  3370 I jxcore-log: 
,03-24 08:49:57.596  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:49:57.596  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 08:49:57.597  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:57.601  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:49:57.601  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:49:57.601  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:49:57.610  3312  3370 I jxcore-log: ok 193 must be stopped
03-24 08:49:57.610  3312  3370 I jxcore-log: 
,03-24 08:49:57.616  3312  3370 I jxcore-log: # setup
03-24 08:49:57.616  3312  3370 I jxcore-log: 
,03-24 08:49:57.763  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:57.763  3312  3370 I jxcore-log: 
,03-24 08:49:57.769  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:57.769  3312  3370 I jxcore-log: 
,03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:57.780  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:57.784  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:57.788  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 08:49:57.788  3312  3370 I jxcore-log: 
,03-24 08:49:57.792  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 08:49:57.792  3312  3370 I jxcore-log: 
,03-24 08:49:57.799  3312  3370 I jxcore-log: # 46. can get the network status before starting
,03-24 08:49:57.799  3312  3370 I jxcore-log: 
,03-24 08:49:57.804  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 08:49:57.804  3312  3370 I jxcore-log: 
,03-24 08:49:57.934  3312  3370 I jxcore-log: ok 194 network status should have certain non-empty properties
03-24 08:49:57.934  3312  3370 I jxcore-log: 
,03-24 08:49:57.940  3312  3370 I jxcore-log: # teardown
03-24 08:49:57.940  3312  3370 I jxcore-log: 
,03-24 08:49:58.102  3312  3370 I jxcore-log: ok 195 must be stopped
03-24 08:49:58.102  3312  3370 I jxcore-log: 
,03-24 08:49:58.109  3312  3370 I jxcore-log: # setup
03-24 08:49:58.109  3312  3370 I jxcore-log: 
,03-24 08:49:59.936  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:49:59.936  3312  3370 I jxcore-log: 
,03-24 08:49:59.941  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:49:59.941  3312  3370 I jxcore-log: 
,03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:49:59.953  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:49:59.958  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:49:59.959  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:49:59.959  3312  3370 I jxcore-log: 
,03-24 08:49:59.961  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:49:59.961  3312  3370 I jxcore-log: 
,03-24 08:49:59.965  3312  3370 I jxcore-log: # 47. error returned with bad router
03-24 08:49:59.965  3312  3370 I jxcore-log: 
,03-24 08:49:59.967  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:49:59.967  3312  3370 I jxcore-log: 
,03-24 08:50:00.102  3312  3370 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 08:50:00.102  3312  3370 I jxcore-log: 
,03-24 08:50:00.108  3312  3370 I jxcore-log: ok 196 specific error expected
03-24 08:50:00.108  3312  3370 I jxcore-log: 
,03-24 08:50:00.111  3312  3370 I jxcore-log: # teardown
03-24 08:50:00.111  3312  3370 I jxcore-log: 
,03-24 08:50:00.286  3312  3370 I jxcore-log: ok 197 must be stopped
03-24 08:50:00.286  3312  3370 I jxcore-log: 
,03-24 08:50:00.290  3312  3370 I jxcore-log: # setup
03-24 08:50:00.290  3312  3370 I jxcore-log: 
,03-24 08:50:00.417  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:00.417  3312  3370 I jxcore-log: 
,03-24 08:50:00.423  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:00.423  3312  3370 I jxcore-log: 
,03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:00.434  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:00.438  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:00.440  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:00.440  3312  3370 I jxcore-log: 
,03-24 08:50:00.442  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:50:00.442  3312  3370 I jxcore-log: 
,03-24 08:50:00.446  3312  3370 I jxcore-log: # 48. all services are stopped when we call stop
03-24 08:50:00.446  3312  3370 I jxcore-log: 
,03-24 08:50:00.448  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:50:00.448  3312  3370 I jxcore-log: 
,03-24 08:50:00.597  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:00.597  3312  3370 I jxcore-log: 
,03-24 08:50:00.599  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 40998
03-24 08:50:00.599  3312  3370 I jxcore-log: 
,03-24 08:50:00.607  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 50757, start advertisements: false
,03-24 08:50:00.607  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:50:00.607  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 08:50:00.607  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 08:50:00.612  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:00.612  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:50:00.612  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:50:00.618  2158  3243 D BtGatt.GattService: registerClient() - UUID=04a14ac7-ac02-41d4-9043-bb8a81efcf0a
,03-24 08:50:00.619  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=04a14ac7-ac02-41d4-9043-bb8a81efcf0a, clientIf=5
03-24 08:50:00.619  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:50:00.619  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:50:00.620  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:50:00.621  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:00.621  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:00.622  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-24 08:50:00.623  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 08:50:00.623  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-24 08:50:00.624  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 08:50:00.626  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-24 08:50:00.627   825  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:00.630  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:50:00.630  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:50:00.632  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 08:50:00.632  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:00.632  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:50:00.632  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:50:00.635  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:00.635  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:00.636  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 08:50:00.637  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:50:00.637  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:00.637  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:00.638  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:50:00.638  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:50:00.638  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:50:00.639  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:00.641  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:00.641  3312  3370 I jxcore-log: 
03-24 08:50:00.642  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:00.642  3312  3370 I jxcore-log: 
,03-24 08:50:00.647  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 40998, start advertisements: true
,03-24 08:50:00.647  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:50:00.647  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:50:00.647  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:50:00.651  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 08:50:00.651  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 08:50:00.651  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:00.651  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:00.652  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:50:00.652  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:00.652  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 08:50:00.652  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:50:00.657  2158  2175 D BtGatt.GattService: registerClient() - UUID=da42ad4c-9ab7-4a25-b40c-ad02267a0c01
,03-24 08:50:00.658  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=da42ad4c-9ab7-4a25-b40c-ad02267a0c01, clientIf=6
,03-24 08:50:00.658  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:50:00.659  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:00.663  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:00.666  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:00.669  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:00.669  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:50:00.669  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:50:00.669  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:50:00.670  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:50:00.670  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:50:00.670  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:50:00.670   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:50:00.670  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 08:50:00.673  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:50:00.673  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:50:00.673  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 08:50:00.673  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:00.673  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 08:50:00.675  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 08:50:00.676  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 08:50:00.677  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 08:50:00.677  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 08:50:00.678  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 08:50:00.678  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:00.679  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:50:00.679  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 08:50:00.684  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-24 08:50:00.684  3312  3370 I jxcore-log: 
,03-24 08:50:00.687   825  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:00.688  3312  3872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,03-24 08:50:00.692  3312  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:50:00.698  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:50:00.698  3312  3370 I jxcore-log: 
,03-24 08:50:00.704  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:50:00.704  3312  3370 I jxcore-log: 
,03-24 08:50:00.708  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:50:00.708  3312  3370 I jxcore-log: 
,03-24 08:50:00.711  3312  3370 I jxcore-log: ok 198 connection to servers manager should succeed after starting
03-24 08:50:00.711  3312  3370 I jxcore-log: 
,03-24 08:50:00.721  3312  3370 I jxcore-log: ok 199 connection to router server should succeed after starting
03-24 08:50:00.721  3312  3370 I jxcore-log: 
,03-24 08:50:00.723  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:50:00.723  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 08:50:00.723  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 08:50:00.723  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:50:00.723  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
03-24 08:50:00.723  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 08:50:00.723  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:50:00.723  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-24 08:50:00.724  3312  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:50:00.724  3312  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-24 08:50:00.724  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:50:00.724  3312  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 08:50:00.724  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 08:50:00.724  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 08:50:00.724  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:50:00.724  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 08:50:00.724  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:50:00.727  2158  2175 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:00.731  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 08:50:00.732  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 08:50:00.732  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:00.732  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:00.733  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:50:00.733  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:00.733  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:50:00.733  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:50:00.733  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:50:00.733  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:00.733  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:50:00.735  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:00.735  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:00.736  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:00.737  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:50:00.737  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:50:00.739  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 08:50:00.739  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:50:00.739  2158  2222 D BtGatt.GattService: current time is 300662744571
,03-24 08:50:00.739  2158  2222 D BtGatt.GattService: Batch record : [19, -118, 68, -65, 119, 67, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 08:50:00.740  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-24 08:50:00.741  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:50:00.741  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:00.742  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:00.743  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:00.743  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:00.743  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:50:00.743  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:50:00.744  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:50:00.744  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 08:50:00.744  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:50:00.744  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 08:50:00.744  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:50:00.744  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:00.745  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:50:00.745  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:00.745  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 08:50:00.747  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:50:00.747  3312  3370 I jxcore-log: 
,03-24 08:50:00.753  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:50:00.753   825   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:00.761  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:50:00.762  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:50:00.762  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:50:00.765  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 08:50:00.765  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 08:50:00.766  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:50:00.766  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:00.766  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:50:00.766  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:00.767  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:50:00.767  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 08:50:00.767  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:50:00.769  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:50:00.769  3312  3370 I jxcore-log: 
03-24 08:50:00.770  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:00.770  3312  3370 I jxcore-log: 
03-24 08:50:00.771  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:00.771  3312  3370 I jxcore-log: 
03-24 08:50:00.775  3312  3370 I jxcore-log: ok 200 is stopped after calling stop
03-24 08:50:00.775  3312  3370 I jxcore-log: 
,03-24 08:50:00.781  3312  3370 I jxcore-log: ok 201 connection to servers manager should fail after stopping
03-24 08:50:00.781  3312  3370 I jxcore-log: 
,03-24 08:50:00.786  3312  3370 I jxcore-log: ok 202 connection to router server should fail after stopping
03-24 08:50:00.786  3312  3370 I jxcore-log: 
,03-24 08:50:00.793  3312  3370 I jxcore-log: # teardown
03-24 08:50:00.793  3312  3370 I jxcore-log: 
,03-24 08:50:01.328  3312  3370 I jxcore-log: ok 203 must be stopped
03-24 08:50:01.328  3312  3370 I jxcore-log: 
,03-24 08:50:01.330  3312  3370 I jxcore-log: # setup
03-24 08:50:01.330  3312  3370 I jxcore-log: 
,03-24 08:50:01.467  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:01.467  3312  3370 I jxcore-log: 
,03-24 08:50:01.469  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:01.469  3312  3370 I jxcore-log: 
,03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:01.477  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:01.480  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:01.482  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:01.482  3312  3370 I jxcore-log: 
,03-24 08:50:01.483  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:50:01.483  3312  3370 I jxcore-log: 
,03-24 08:50:01.486  3312  3370 I jxcore-log: # 49. make sure terminateConnection is properly hooked up
03-24 08:50:01.486  3312  3370 I jxcore-log: 
,03-24 08:50:01.488  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:50:01.488  3312  3370 I jxcore-log: 
,03-24 08:50:01.655  3312  3370 I jxcore-log: ok 204 called with right arguments
03-24 08:50:01.655  3312  3370 I jxcore-log: 
,03-24 08:50:01.658  3312  3370 I jxcore-log: # teardown
03-24 08:50:01.658  3312  3370 I jxcore-log: 
,03-24 08:50:01.788  3312  3370 I jxcore-log: ok 205 must be stopped
03-24 08:50:01.788  3312  3370 I jxcore-log: 
,03-24 08:50:01.790  3312  3370 I jxcore-log: # setup
03-24 08:50:01.790  3312  3370 I jxcore-log: 
,03-24 08:50:01.924  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:01.924  3312  3370 I jxcore-log: 
,03-24 08:50:01.931  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:01.931  3312  3370 I jxcore-log: 
,03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:01.942  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:01.947  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:01.950  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 08:50:01.950  3312  3370 I jxcore-log: 
,03-24 08:50:01.954  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 08:50:01.954  3312  3370 I jxcore-log: 
,03-24 08:50:01.961  3312  3370 I jxcore-log: # 50. make sure terminateListener is properly hooked up
,03-24 08:50:01.961  3312  3370 I jxcore-log: 
,03-24 08:50:01.966  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 08:50:01.966  3312  3370 I jxcore-log: 
,03-24 08:50:02.220  3312  3370 I jxcore-log: ok 206 called with right arguments,
03-24 08:50:02.220  3312  3370 I jxcore-log: 
03-24 08:50:02.225  3312  3370 I jxcore-log: # teardown
03-24 08:50:02.225  3312  3370 I jxcore-log: 
,03-24 08:50:02.399  3312  3370 I jxcore-log: ok 207 must be stopped,
03-24 08:50:02.399  3312  3370 I jxcore-log: 
03-24 08:50:02.401  3312  3370 I jxcore-log: # setup
03-24 08:50:02.401  3312  3370 I jxcore-log: 
,03-24 08:50:02.505  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:02.505  3312  3370 I jxcore-log: 
,03-24 08:50:02.506  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:02.506  3312  3370 I jxcore-log: ,
,03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:02.516  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:02.520  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-24 08:50:02.522  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
,03-24 08:50:02.522  3312  3370 I jxcore-log: 
03-24 08:50:02.523  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 08:50:02.523  3312  3370 I jxcore-log: 
03-24 08:50:02.526  3312  3370 I jxcore-log: # 51. make sure we actually call kill connections properly,
03-24 08:50:02.526  3312  3370 I jxcore-log: 
,03-24 08:50:02.527  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-24 08:50:02.527  3312  3370 I jxcore-log: 
,03-24 08:50:02.675  3312  3370 I jxcore-log: ok 208 specific error expected
03-24 08:50:02.675  3312  3370 I jxcore-log: 
03-24 08:50:02.677  3312  3370 I jxcore-log: # teardown
03-24 08:50:02.677  3312  3370 I jxcore-log: 
,03-24 08:50:02.687  1258  1275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 08:50:02.688  1258  1275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 08:50:02.688  1258  1275 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 08:50:02.688  1258  1275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:02.695  1258  1275 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:02.716  3125  3874 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,03-24 08:50:02.716  3125  3874 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 08:50:02.716  3125  3874 E HttpOperation: 	,at jdm.a(PG:82)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	,at jcs.o(PG:406)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	,at jcn.a(PG:1379)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	,at jcs.i(PG:143)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	,at blb.a(PG:3937)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at czp.a(PG:18188)
03-24 08:50:02.716  3125  3874 E HttpOperation: ,	at czp.a(PG:9081)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at czq.run(PG:1686),
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,03-24 08:50:02.716  3125  3874 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
,03-24 08:50:02.716  3125  3874 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
,03-24 08:50:02.716  3125  3874 E HttpOperation: ,	,at jdj.a(PG:4091),
03-24 08:50:02.716  3125  3874 E HttpOperation: 	,at jdj.a(PG:1125)
03-24 08:50:02.716  3125  3874 E HttpOperation: ,	at jdm.a(PG:77)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	... 12 more
03-24 08:50:02.716  3125  3874 E HttpOperation: Caused by: faj: BadAuthentication
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at fal.a(PG:38)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	at jdj.a(PG:4089)
03-24 08:50:02.716  3125  3874 E HttpOperation: 	... 14 more
,03-24 08:50:02.773  1258  3764 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 08:50:02.773  1258  3764 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:50:02.773  1258  3764 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:50:02.773  1258  3764 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:02.788  1258  3764 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 08:50:02.789  3312  3370 I jxcore-log: ok 209 must be stopped
,03-24 08:50:02.789  3312  3370 I jxcore-log: 
03-24 08:50:02.793  3312  3370 I jxcore-log: # setup
03-24 08:50:02.793  3312  3370 I jxcore-log: 
,03-24 08:50:02.819  3125  3874 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 08:50:02.819  3125  3874 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jdm.a(PG:82)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jcs.o(PG:406)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jcn.a(PG:1379)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jcs.i(PG:143)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at hec.a(PG:42)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at hee.a(PG:102)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at czr.a(PG:65)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at kka.a(PG:108)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at czp.a(PG:19176)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at czp.a(PG:9081)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at czq.run(PG:1686)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:50:02.819  3125  3874 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jdj.a(PG:4091)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jdj.a(PG:1125)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jdm.a(PG:77)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	... 15 more
03-24 08:50:02.819  3125  3874 E HttpOperation: Caused by: faj: BadAuthentication
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at fal.a(PG:38)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	at jdj.a(PG:4089)
03-24 08:50:02.819  3125  3874 E HttpOperation: 	... 17 more
03-24 08:50:02.819  3125  3874 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 08:50:02.819  3125  3874 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at hec.a(PG:42)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at hee.a(PG:102)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at czr.a(PG:65)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at kka.a(PG:108)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	... 15 more
03-24 08:50:02.819  3125  3874 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at fal.a(PG:38)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 08:50:02.819  3125  3874 E ExperimentLoader: 	... 17 more
,03-24 08:50:02.892  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:02.892  3312  3370 I jxcore-log: 
03-24 08:50:02.893  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:02.893  3312  3370 I jxcore-log: 
,03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:02.900  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:02.905  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:02.908  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:02.908  3312  3370 I jxcore-log: 
,03-24 08:50:02.911  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 08:50:02.911  3312  3370 I jxcore-log: 
,03-24 08:50:02.915  3312  3370 I jxcore-log: # 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 08:50:02.915  3312  3370 I jxcore-log: 
,03-24 08:50:02.918  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:50:02.918  3312  3370 I jxcore-log: 
,03-24 08:50:02.950   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 302396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 08:50:02.968  3523  3877 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 08:50:02.995  3523  3878 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 08:50:03.046  1258  3765 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 08:50:03.047  1258  3765 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:50:03.047  1258  3765 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:50:03.047  1258  3765 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:03.050  1258  3765 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:03.088  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:03.088  3312  3370 I jxcore-log: 
,03-24 08:50:03.091  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 58889,
03-24 08:50:03.091  3312  3370 I jxcore-log: 
,03-24 08:50:03.095  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":37292,"error":{}}
,03-24 08:50:03.095  3312  3370 I jxcore-log: 
,03-24 08:50:03.102  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:50:03.102  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:50:03.102  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:03.103  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:50:03.103  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:50:03.103  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:03.114  3312  3370 I jxcore-log: ok 210 failure reason is as expected,
03-24 08:50:03.114  3312  3370 I jxcore-log: 
,03-24 08:50:03.115  3312  3370 I jxcore-log: ok 211 error description is as expected
03-24 08:50:03.115  3312  3370 I jxcore-log: 
,03-24 08:50:03.117  3312  3370 I jxcore-log: ok 212 must be stopped,
03-24 08:50:03.117  3312  3370 I jxcore-log: 
,03-24 08:50:03.129  3312  3370 I jxcore-log: # teardown,
03-24 08:50:03.129  3312  3370 I jxcore-log: 
,03-24 08:50:03.161   825  1355 I art     : Explicit concurrent mark sweep GC freed 30771(1468KB) AllocSpace objects, 11(835KB) LOS objects, 32% free, 33MB/49MB, paused 1.407ms total 58.106ms,
,03-24 08:50:03.230  1258  1275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 08:50:03.230  1258  1275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:50:03.231  1258  1275 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:50:03.231  1258  1275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:03.234  1258  1275 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:03.242  3523  3878 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 08:50:03.243  3523  3877 E BooksSync: Soft error
03-24 08:50:03.243  3523  3877 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 08:50:03.243  3523  3877 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 08:50:03.243  3523  3877 E BooksSync: Sync error
03-24 08:50:03.243  3523  3877 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 08:50:03.243  3523  3877 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 08:50:03.243  3523  3877 I BooksSync: Finished books sync
,03-24 08:50:03.247   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302847, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 08:50:03.258  3312  3370 I jxcore-log: ok 213 must be stopped
03-24 08:50:03.258  3312  3370 I jxcore-log: 
03-24 08:50:03.260  3312  3370 I jxcore-log: # setup
03-24 08:50:03.260  3312  3370 I jxcore-log: 
,03-24 08:50:03.393  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:03.393  3312  3370 I jxcore-log: 
,03-24 08:50:03.398  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:03.398  3312  3370 I jxcore-log: 
,03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:03.412  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:03.419  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:03.423  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:03.423  3312  3370 I jxcore-log: 
,03-24 08:50:03.428  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:50:03.428  3312  3370 I jxcore-log: 
,03-24 08:50:03.436  3312  3370 I jxcore-log: # 53. We repeat failedConnection event when we get it from thaliTcpServersManager
03-24 08:50:03.436  3312  3370 I jxcore-log: 
,03-24 08:50:03.442  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:50:03.442  3312  3370 I jxcore-log: 
,03-24 08:50:03.555  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:03.555  3312  3370 I jxcore-log: 
,03-24 08:50:03.558  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 37019
03-24 08:50:03.558  3312  3370 I jxcore-log: 
,03-24 08:50:03.561  3312  3370 I jxcore-log: ok 214 peerIdentifier matches
03-24 08:50:03.561  3312  3370 I jxcore-log: 
,03-24 08:50:03.562  3312  3370 I jxcore-log: ok 215 error description matches
03-24 08:50:03.562  3312  3370 I jxcore-log: 
,03-24 08:50:03.565  3312  3370 I jxcore-log: # teardown
03-24 08:50:03.565  3312  3370 I jxcore-log: 
,03-24 08:50:03.660  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:50:03.660  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 08:50:03.660  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:03.664  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:50:03.665  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:50:03.665  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:03.671  3312  3370 I jxcore-log: ok 216 must be stopped
03-24 08:50:03.671  3312  3370 I jxcore-log: 
,03-24 08:50:03.677  3312  3370 I jxcore-log: # setup
03-24 08:50:03.677  3312  3370 I jxcore-log: 
,03-24 08:50:03.773  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:03.773  3312  3370 I jxcore-log: 
,03-24 08:50:03.778  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:03.778  3312  3370 I jxcore-log: 
,03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
,03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:03.791  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:03.796  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:03.800  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:03.800  3312  3370 I jxcore-log: 
,03-24 08:50:03.804  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:50:03.804  3312  3370 I jxcore-log: 
,03-24 08:50:03.810  3312  3370 I jxcore-log: # 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,03-24 08:50:03.810  3312  3370 I jxcore-log: 
,03-24 08:50:03.812  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 08:50:03.812  3312  3370 I jxcore-log: 
,03-24 08:50:03.976  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:03.976  3312  3370 I jxcore-log: 
,03-24 08:50:03.978  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 56537
03-24 08:50:03.978  3312  3370 I jxcore-log: 
,03-24 08:50:03.983  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 40998, start advertisements: false
03-24 08:50:03.983  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:50:03.983  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:50:03.983  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 08:50:03.988  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:03.988  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-24 08:50:03.988  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:50:03.992  2158  2175 D BtGatt.GattService: registerClient() - UUID=e520a3e4-9869-48a9-ae05-149078081e89
,03-24 08:50:03.993  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=e520a3e4-9869-48a9-ae05-149078081e89, clientIf=5
03-24 08:50:03.994  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:50:03.994  2158  2176 D BtGatt.GattService: start scan with filters
,03-24 08:50:03.996  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:50:03.996  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:03.996  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:50:03.996  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 08:50:03.996  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:50:03.996  2158  2233 D BtGatt.ScanManager: handling starting scan,
,03-24 08:50:03.997  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 08:50:03.997  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:50:03.997   825  1469 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:03.999  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:04.000  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:50:04.000  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 08:50:04.000  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 08:50:04.000  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:04.000  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:50:04.003  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:04.003  3312  3370 I jxcore-log: 
,03-24 08:50:04.004  3312  3370 I jxcore-log: ok 217 discoveryActive matches
03-24 08:50:04.004  3312  3370 I jxcore-log: 
03-24 08:50:04.005  3312  3370 I jxcore-log: ok 218 advertisingActive matches
03-24 08:50:04.005  3312  3370 I jxcore-log: 
,03-24 08:50:04.006  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:04.006  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.006  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:04.006  3312  3370 I jxcore-log: 
,03-24 08:50:04.008  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:50:04.008  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.009  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:04.009  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:50:04.012  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:04.012  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.014  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:04.014  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.014  3312  3370 I jxcore-log: not ok 219 discoveryActive matches
03-24 08:50:04.014  3312  3370 I jxcore-log: 
03-24 08:50:04.014  3312  3370 I jxcore-log:   ---
03-24 08:50:04.014  3312  3370 I jxcore-log: 
03-24 08:50:04.014  3312  3370 I jxcore-log:     operator: equal
03-24 08:50:04.014  3312  3370 I jxcore-log: 
03-24 08:50:04.014  3312  3370 I jxcore-log:     expected: false
03-24 08:50:04.014  3312  3370 I jxcore-log: 
,03-24 08:50:04.014  3312  3370 I jxcore-log:     actual:   true
03-24 08:50:04.014  3312  3370 I jxcore-log: 
03-24 08:50:04.015  3312  3370 I jxcore-log:   ...
03-24 08:50:04.015  3312  3370 I jxcore-log: 
03-24 08:50:04.015  3312  3370 I jxcore-log: ok 220 advertisingActive matches
03-24 08:50:04.015  3312  3370 I jxcore-log: 
03-24 08:50:04.020  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:50:04.021  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 08:50:04.021  3312  3370 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 08:50:04.021  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:50:04.021  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:50:04.021  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:50:04.021  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:50:04.021  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:50:04.021  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:50:04.022  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:50:04.023  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:50:04.024  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:04.024  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:04.024  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:50:04.024  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 08:50:04.024  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 08:50:04.024  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:50:04.024  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:04.024  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.025  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:04.025  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:04.025  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 08:50:04.025  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:50:04.026  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:50:04.026  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:04.026  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:50:04.026  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:04.026  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 08:50:04.028  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:04.028  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.029  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:04.030  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:04.030  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.030  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:50:04.031   825  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:04.037  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:50:04.038  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:04.038  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:50:04.040  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:50:04.040  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:50:04.040  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:04.040  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:50:04.042  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 08:50:04.043  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:50:04.043  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:04.045  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:04.045  3312  3370 I jxcore-log: 
03-24 08:50:04.046  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:04.046  3312  3370 I jxcore-log: 
,03-24 08:50:04.062  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:04.062  3312  3370 I jxcore-log: 
,03-24 08:50:04.064  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 48971
03-24 08:50:04.064  3312  3370 I jxcore-log: 
,03-24 08:50:04.067  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 48971, start advertisements: true
03-24 08:50:04.067  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:50:04.067  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 08:50:04.067  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 08:50:04.069  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 08:50:04.069  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:04.069  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:50:04.069  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:50:04.071  2158  2175 D BtGatt.GattService: registerClient() - UUID=b105fcec-4139-40a0-ac19-171eaebf62bc
03-24 08:50:04.072  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=b105fcec-4139-40a0-ac19-171eaebf62bc, clientIf=5
03-24 08:50:04.072  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:50:04.072  2158  2176 D BtGatt.GattService: start scan with filters
,03-24 08:50:04.073  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:04.073  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:50:04.073  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:04.073  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:50:04.073  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:50:04.073  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 08:50:04.073  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:04.073  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:04.074  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:50:04.074  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:50:04.074  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:04.074  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:04.074  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:50:04.075  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:50:04.075  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.077  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 08:50:04.077  2158  3243 D BtGatt.GattService: registerClient() - UUID=e228aaf4-c81a-49fc-93ca-36d6c4023b98
03-24 08:50:04.077  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.077  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:04.077  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:50:04.078  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=e228aaf4-c81a-49fc-93ca-36d6c4023b98, clientIf=6
03-24 08:50:04.079  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:50:04.080  2158  2231 D BtGatt.AdvertiseManager: message : 0
03-24 08:50:04.080  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:04.080  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.082  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:04.082  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.082  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:04.086  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:04.088  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:04.089  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:50:04.089  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 08:50:04.090   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:04.092  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:04.092  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:50:04.092  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:50:04.092  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 08:50:04.093  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 08:50:04.093  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:50:04.093  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:50:04.093  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-24 08:50:04.094  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:50:04.094  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:50:04.094  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:50:04.094  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 08:50:04.094  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:50:04.094  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:50:04.094  3312  3312 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:50:04.094  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:04.094  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:50:04.094  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:04.094  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:50:04.095  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:50:04.095  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:50:04.095   825  1323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:50:04.096  3312  3880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:50:04.098  3312  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 08:50:04.098  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:04.098  3312  3370 I jxcore-log: 
,03-24 08:50:04.102  3312  3370 I jxcore-log: not ok 221 discoveryActive matches
03-24 08:50:04.102  3312  3370 I jxcore-log: 
,03-24 08:50:04.102  3312  3370 I jxcore-log:   ---
03-24 08:50:04.102  3312  3370 I jxcore-log: 
03-24 08:50:04.102  3312  3370 I jxcore-log:     operator: equal
03-24 08:50:04.102  3312  3370 I jxcore-log: 
03-24 08:50:04.102  3312  3370 I jxcore-log:     expected: false
03-24 08:50:04.102  3312  3370 I jxcore-log: 
03-24 08:50:04.103  3312  3370 I jxcore-log:     actual:   true
03-24 08:50:04.103  3312  3370 I jxcore-log: 
03-24 08:50:04.103  3312  3370 I jxcore-log:   ...
03-24 08:50:04.103  3312  3370 I jxcore-log: 
,03-24 08:50:04.105  3312  3370 I jxcore-log: not ok 222 advertisingActive matches
03-24 08:50:04.105  3312  3370 I jxcore-log: 
03-24 08:50:04.105  3312  3370 I jxcore-log:   ---
03-24 08:50:04.105  3312  3370 I jxcore-log: 
03-24 08:50:04.105  3312  3370 I jxcore-log:     operator: equal
03-24 08:50:04.105  3312  3370 I jxcore-log: 
,03-24 08:50:04.106  3312  3370 I jxcore-log:     expected: true
03-24 08:50:04.106  3312  3370 I jxcore-log: 
03-24 08:50:04.106  3312  3370 I jxcore-log:     actual:   false
03-24 08:50:04.106  3312  3370 I jxcore-log: 
03-24 08:50:04.106  3312  3370 I jxcore-log:   ...
03-24 08:50:04.106  3312  3370 I jxcore-log: 
03-24 08:50:04.108  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:04.108  3312  3370 I jxcore-log: 
,03-24 08:50:04.111  3312  3370 I jxcore-log: not ok 223 discoveryActive matches
03-24 08:50:04.111  3312  3370 I jxcore-log: 
,03-24 08:50:04.111  3312  3370 I jxcore-log:   ---
03-24 08:50:04.111  3312  3370 I jxcore-log: 
03-24 08:50:04.111  3312  3370 I jxcore-log:     operator: equal
03-24 08:50:04.111  3312  3370 I jxcore-log: 
03-24 08:50:04.111  3312  3370 I jxcore-log:     expected: false
03-24 08:50:04.111  3312  3370 I jxcore-log: 
03-24 08:50:04.111  3312  3370 I jxcore-log:     actual:   true
03-24 08:50:04.111  3312  3370 I jxcore-log: 
03-24 08:50:04.111  3312  3370 I jxcore-log:   ...
03-24 08:50:04.111  3312  3370 I jxcore-log: 
03-24 08:50:04.112  3312  3370 I jxcore-log: ok 224 advertisingActive matches
03-24 08:50:04.112  3312  3370 I jxcore-log: 
,03-24 08:50:04.113  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:50:04.113  3312  3370 I jxcore-log: 
,03-24 08:50:04.114  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:50:04.114  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 08:50:04.114  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:50:04.114  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 08:50:04.114  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:50:04.115  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:50:04.115  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:50:04.115  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 08:50:04.115  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:50:04.115  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:50:04.115  3312  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:50:04.115  3312  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:50:04.115  3312  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:50:04.115  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:50:04.115  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:50:04.116  2158  2175 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:04.117  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:50:04.118  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:04.118  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:04.118  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 08:50:04.118  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:50:04.118  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:50:04.118  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:04.118  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:50:04.118  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:04.118  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.119  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:04.120  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:04.120  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:50:04.121  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:04.121  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.121  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:04.122  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:50:04.122  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:04.123  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:04.124  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:04.124  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-24 08:50:04.124  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:50:04.125  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:04.125  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.126  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-24 08:50:04.126  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:50:04.126  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:50:04.126  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:50:04.126  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:50:04.128  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 08:50:04.128  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:04.128  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:50:04.128  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:04.128  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:50:04.133  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 08:50:04.133   825  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:04.138  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:50:04.139  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:04.139  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 08:50:04.139  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:50:04.139  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:50:04.142  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:04.142  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:50:04.142  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:04.142  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:50:04.142  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:04.143  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 08:50:04.147  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:50:04.147  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:50:04.147  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:04.151  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:50:04.151  3312  3370 I jxcore-log: 
,03-24 08:50:04.154  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:04.154  3312  3370 I jxcore-log: 
,03-24 08:50:04.156  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:04.156  3312  3370 I jxcore-log: 
,03-24 08:50:04.171  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:04.171  3312  3370 I jxcore-log: ,
,03-24 08:50:04.174  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 47714
03-24 08:50:04.174  3312  3370 I jxcore-log: 
,03-24 08:50:04.181  3312  3370 I jxcore-log: # teardown
,03-24 08:50:04.181  3312  3370 I jxcore-log: 
,03-24 08:50:04.538  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:50:04.538  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:50:04.538  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:04.545  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:50:04.545  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:50:04.545  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 08:50:04.552  3312  3370 I jxcore-log: ok 225 must be stopped
03-24 08:50:04.552  3312  3370 I jxcore-log: 
,03-24 08:50:04.559  3312  3370 I jxcore-log: # setup
03-24 08:50:04.559  3312  3370 I jxcore-log: 
,03-24 08:50:04.657  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:04.657  3312  3370 I jxcore-log: 
,03-24 08:50:04.663  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:04.663  3312  3370 I jxcore-log: 
,03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:04.674  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:04.678  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:04.680  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:04.680  3312  3370 I jxcore-log: 
,03-24 08:50:04.692  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:50:04.692  3312  3370 I jxcore-log: 
,03-24 08:50:04.696  3312  3370 I jxcore-log: # 55. can do HTTP requests between peers
03-24 08:50:04.696  3312  3370 I jxcore-log: 
,03-24 08:50:04.699  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:50:04.699  3312  3370 I jxcore-log: 
,03-24 08:50:04.835  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:04.835  3312  3370 I jxcore-log: 
,03-24 08:50:04.837  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 47425
03-24 08:50:04.837  3312  3370 I jxcore-log: 
,03-24 08:50:04.844  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 48971, start advertisements: false,
03-24 08:50:04.844  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:50:04.844  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 08:50:04.844  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 08:50:04.848  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:04.849  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:50:04.849  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 08:50:04.853  2158  3243 D BtGatt.GattService: registerClient() - UUID=e27ba34f-6e64-47fe-90aa-e0fcf3a6df68
,03-24 08:50:04.854  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=e27ba34f-6e64-47fe-90aa-e0fcf3a6df68, clientIf=5
03-24 08:50:04.854  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:50:04.856  2158  2176 D BtGatt.GattService: start scan with filters
,03-24 08:50:04.859  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:50:04.859  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:04.859  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:50:04.859  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 08:50:04.859  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:50:04.859  2158  2233 D BtGatt.ScanManager: handling starting scan,
03-24 08:50:04.859  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:50:04.859  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-24 08:50:04.860   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:04.869  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:04.870  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.872  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:50:04.872  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:04.872  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:50:04.872  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:50:04.875  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:50:04.875  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.877  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:50:04.877  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:04.881  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-24 08:50:04.881  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:50:04.881  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:50:04.881  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:50:04.881  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:04.882  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 08:50:04.886  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 08:50:04.886  3312  3370 I jxcore-log: 
,03-24 08:50:04.888  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 08:50:04.888  3312  3370 I jxcore-log: 
,03-24 08:50:04.893  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 47425, start advertisements: true
,03-24 08:50:04.893  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:50:04.894  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 08:50:04.894  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:50:04.898  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 08:50:04.898  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 08:50:04.898  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:04.898  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 08:50:04.898  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:50:04.899  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 08:50:04.899  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:04.899  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-24 08:50:04.905  2158  2176 D BtGatt.GattService: registerClient() - UUID=a78670da-2989-4d44-b9e7-b5ee02539f49,
03-24 08:50:04.905  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=a78670da-2989-4d44-b9e7-b5ee02539f49, clientIf=6
03-24 08:50:04.906  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:50:04.907  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:04.912  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 08:50:04.916  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:04.920  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:04.921  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:50:04.921  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:50:04.921  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:50:04.921  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:50:04.921  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 08:50:04.921  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 08:50:04.921  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 08:50:04.921   825  1466 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:04.929  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 08:50:04.929  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:50:04.929  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 08:50:04.929  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:04.929  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:50:04.931  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 08:50:04.931  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 08:50:04.931  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:50:04.931  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 08:50:04.932  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:50:04.932  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 08:50:04.932  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:50:04.932  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:50:04.935   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:50:04.936  3312  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:50:04.936  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:50:04.936  3312  3370 I jxcore-log: 
,03-24 08:50:04.941  3312  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:50:05.381  2158  2158 D BtGatt.ScanManager: awakened up at time 305304,
,03-24 08:50:05.383  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:50:05.393  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-24 08:50:05.393  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:05.393  2158  2222 D BtGatt.GattService: current time is 305316656392
03-24 08:50:05.394  2158  2222 D BtGatt.GattService: Batch record : [-66, -88, -3, -99, -104, 88, 1, -128, -56, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 08:50:05.395  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 08:50:05.395  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:50:05.399  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 08:50:05.399  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 08:50:05.400  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 08:50:05.400  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:50:05.403  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:50:05.403  3312  3370 I jxcore-log: 
,03-24 08:50:05.407  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false,
03-24 08:50:05.407  3312  3370 I jxcore-log: 
,03-24 08:50:05.411  3312  3370 I jxcore-log: ok 226 found a peer! {"peerIdentifier":"E0:DB:10:14:E2:C0","portNumber":60320,"hostAddress":"127.0.0.1"}
03-24 08:50:05.411  3312  3370 I jxcore-log: 
,03-24 08:50:05.417  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:50:05.417  3312  3370 I jxcore-log: 
,03-24 08:50:05.438  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 08:50:05.438  3312  3370 I jxcore-log: 
,03-24 08:50:05.448  3312  3370 I jxcore-log: DEBUG createPeerListener: first connection
03-24 08:50:05.448  3312  3370 I jxcore-log: 
,03-24 08:50:05.456  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 08:50:05.456  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:05.459  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 08:50:05.459  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 08:50:05.459  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 08:50:05.459  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-24 08:50:05.460  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 08:50:05.460  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 08:50:05.464  3312  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 383)
,03-24 08:50:05.466  3312  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:50:05.467  2158  3243 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 08:50:06.592  2158  2236 W bt-btif : info:x10
,03-24 08:50:06.592  2158  2222 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,03-24 08:50:06.625  3810  3810 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 08:50:06.630  3810  3810 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 08:50:06.648  2158  2236 W bt-sdp  : process_service_search_attr_rsp
,03-24 08:50:07.566  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:50:08.935  2158  2236 E bt-btm  : tBTM_SEC_DEV:0xa2fad07c rs_disc_pending=0
03-24 08:50:08.935  2158  2236 W bt-btif : bta_dm_check_av:0
03-24 08:50:08.936  2158  2222 W bt-btif : btif_dm_cback : unhandled event (14)
,03-24 08:50:09.594  2158  2220 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 08:50:10.404  2158  2158 D BtGatt.ScanManager: awakened up at time 310327,
03-24 08:50:10.407  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:50:10.412  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 08:50:10.412  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:10.412  2158  2222 D BtGatt.GattService: current time is 310335762640
03-24 08:50:10.413  2158  2222 D BtGatt.GattService: Batch record : [-66, -88, -3, -99, -104, 88, 1, -128, -73, 99, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 98, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:50:10.413  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:50:10.414  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:50:10.417  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 08:50:10.418  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 08:50:11.809  2158  2236 W bt-btif : new conn_srvc id:26, app_id:255
03-24 08:50:11.809  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:50:11.809  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 08:50:11.810  3312  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-24 08:50:11.811  3312  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 384)
03-24 08:50:11.812  3312  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:50:11.813   825  1094 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:11.816  3312  3886 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 384)
,03-24 08:50:11.816  3312  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:50:11.822  3312  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:50:11.879  2158  2236 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 08:50:11.879  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:50:11.879  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,03-24 08:50:11.879  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 08:50:11.880  3312  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 383)
,03-24 08:50:11.880  3312  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 383)
03-24 08:50:11.881  3312  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 385)
03-24 08:50:11.881  3312  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 385)
03-24 08:50:11.881  3312  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 383)
,03-24 08:50:11.885  3312  3887 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 385)
,03-24 08:50:12.149  3312  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 384),
03-24 08:50:12.152  3312  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:12.153  3312  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 384)
03-24 08:50:12.153  3312  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 384,
03-24 08:50:12.153  3312  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 384)
03-24 08:50:12.153  3312  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:12.154  3312  3886 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 384)
03-24 08:50:12.154  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:12.155  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:12.155  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 08:50:12.155  3312  3312 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 08:50:12.155  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 08:50:12.156  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:12.156  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:12.156  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:50:12.156  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:50:12.156  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:50:12.156  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:50:12.161  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:12.162  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:50:12.163  3312  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 385)
03-24 08:50:12.167  3312  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:12.167  3312  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 383)
03-24 08:50:12.168  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:50:12.168  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:12.169  3312  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 383)
03-24 08:50:12.169  3312  3887 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 385)
,03-24 08:50:12.171  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:12.172  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:12.172  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:12.172  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:50:12.172  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 08:50:12.172  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:12.173  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:50:12.173  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:12.173  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:12.173  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:50:12.180  2158  2175 D BtGatt.GattService: registerClient() - UUID=369f38f8-aa3a-4d9b-95ab-99aa0c23cb5a
03-24 08:50:12.181  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=369f38f8-aa3a-4d9b-95ab-99aa0c23cb5a, clientIf=6
,03-24 08:50:12.181  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:50:12.183  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:12.189  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:12.192  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:12.194  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 08:50:12.195  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:50:12.197  2158  2175 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:12.199  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:50:12.199  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:12.199  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.200  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-24 08:50:12.200  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:12.200  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:12.201  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:12.201  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:50:12.201  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:50:12.202  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:12.202  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:12.203  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.203  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:12.206  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:50:12.206  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.206  2158  2222 D BtGatt.GattService: current time is 312129285609
03-24 08:50:12.206  2158  2222 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 25, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 76, -106, -36, -127, -127, 66, 1, -128, -86, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 08:50:12.206  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:50:12.206  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:50:12.207  2158  2176 D BtGatt.GattService: registerClient() - UUID=1923c271-e5eb-4ce8-9fe4-a48423832f58
,03-24 08:50:12.207  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=1923c271-e5eb-4ce8-9fe4-a48423832f58, clientIf=5
03-24 08:50:12.207  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:50:12.208  2158  2175 D BtGatt.GattService: start scan with filters
03-24 08:50:12.208  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:50:12.208  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:12.208  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 08:50:12.209  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:12.209  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:12.209  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:50:12.209  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:50:12.209  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:50:12.209  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:50:12.213  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:12.213  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:50:12.215  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:50:12.215  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:12.216  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:50:12.216  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:12.217  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:50:12.217  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:50:12.217  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:12.217  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:12.217  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:50:12.217  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:12.218  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:12.218  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:50:12.221  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:50:12.222  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 08:50:12.222  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:12.223  2158  3243 D BtGatt.GattService: registerClient() - UUID=7d441a3a-9848-42aa-9e82-9f2053f43ca3
,03-24 08:50:12.223  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=7d441a3a-9848-42aa-9e82-9f2053f43ca3, clientIf=6
03-24 08:50:12.224  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:50:12.224  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:50:12.224  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.224  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:12.224  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:50:12.224  2158  2231 D BtGatt.AdvertiseManager: message : 0
03-24 08:50:12.226  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:50:12.226  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.227  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:12.228  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:12.228  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:12.231  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:12.233  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:12.234  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:50:12.235  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:12.236  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:50:12.236  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:12.236  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:12.236  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:12.236  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:50:12.236  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:50:12.237  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:12.237  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:12.237  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.237  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:12.239  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:12.239  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.239  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:12.239  2158  2175 D BtGatt.GattService: registerClient() - UUID=8cbd7792-6a01-4ce8-ac6e-36ad827a1725
03-24 08:50:12.240  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=8cbd7792-6a01-4ce8-ac6e-36ad827a1725, clientIf=5
03-24 08:50:12.240  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:50:12.240  2158  3243 D BtGatt.GattService: start scan with filters
,03-24 08:50:12.240  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:12.240  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:12.243  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:50:12.243  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:50:12.245  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:12.245  2158  2231 D BtGatt.AdvertiseManager: message : 1
,03-24 08:50:12.245  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:50:12.248  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:50:12.248  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:12.249  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:12.249  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:12.250  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED,
03-24 08:50:12.250  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:50:12.250  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 08:50:12.250  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:12.250  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:50:12.250  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:12.250  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:12.250  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:50:12.250  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:12.250  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.251  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:50:12.252  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.252  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:50:12.252  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 08:50:12.254  2158  2176 D BtGatt.GattService: registerClient() - UUID=d074cfd4-76b5-42bf-997a-9ac4f7630e4f
,03-24 08:50:12.254  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:12.254  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.254  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=d074cfd4-76b5-42bf-997a-9ac4f7630e4f, clientIf=6
03-24 08:50:12.254  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:50:12.255  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:50:12.255  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.255  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:12.259  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
03-24 08:50:12.261  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-24 08:50:12.263  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 08:50:12.263  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 08:50:12.265  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:12.265  2158  2175 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:50:12.266  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:12.266  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:12.266  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:12.266  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:12.266  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:50:12.266  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:12.268  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:12.268  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.268  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-24 08:50:12.269  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:12.269  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.270  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:50:12.271  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
03-24 08:50:12.271  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.271  2158  3243 D BtGatt.GattService: registerClient() - UUID=5ce91a31-2721-496d-b354-5896dd1d9f32
03-24 08:50:12.272  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=5ce91a31-2721-496d-b354-5896dd1d9f32, clientIf=5
,03-24 08:50:12.272  3312  3329 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:50:12.274  2158  2176 D BtGatt.GattService: start scan with filters,
,03-24 08:50:12.274  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 08:50:12.274  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:12.275  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 08:50:12.275  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 08:50:12.275  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:12.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:12.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:50:12.275  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 08:50:12.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:50:12.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:50:12.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:50:12.275  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:12.276  3312  3888 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 386)
03-24 08:50:12.276  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 08:50:12.277  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:12.277  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.277  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-24 08:50:12.277  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 08:50:12.278  3312  3890 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 387)
03-24 08:50:12.278  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 08:50:12.278  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.278  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:12.278  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:50:12.278  3312  3890 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43360
03-24 08:50:12.278  3312  3890 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 08:50:12.278  3312  3890 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 43360 (peer ID: E0:DB:10:14:E2:C0),
03-24 08:50:12.278  3312  3890 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 08:50:12.280  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:50:12.280  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.281  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:12.281  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:12.282  3312  3370 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 08:50:12.282  3312  3370 I jxcore-log: 
03-24 08:50:12.284  3312  3888 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47425
,03-24 08:50:12.284  3312  3888 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 08:50:12.284  3312  3888 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:50:12.285  3312  3888 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 08:50:12.285  3312  3888 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 386)
03-24 08:50:12.285  3312  3888 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 386)
03-24 08:50:12.286  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 08:50:12.286  3312  3370 I jxcore-log: 
03-24 08:50:12.286  3312  3891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 388, name: Sender)
03-24 08:50:12.287  3312  3892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 389, name: Receiver)
,03-24 08:50:12.288  3312  3890 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 43360
03-24 08:50:12.288  3312  3890 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 08:50:12.288  3312  3890 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 08:50:12.288  3312  3890 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:50:12.288  3312  3890 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 387)
03-24 08:50:12.288  3312  3890 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 387)
,03-24 08:50:12.289  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:50:12.289  3312  3370 I jxcore-log: 
03-24 08:50:12.290  3312  3894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 391, name: Receiver)
03-24 08:50:12.290  3312  3893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 390, name: Sender)
,03-24 08:50:12.291  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:50:12.291  3312  3370 I jxcore-log: 
,03-24 08:50:12.307  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 08:50:12.307  3312  3370 I jxcore-log: 
,03-24 08:50:12.310  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:50:12.310  3312  3370 I jxcore-log: 
,03-24 08:50:12.345  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 08:50:12.345  3312  3370 I jxcore-log: 
,03-24 08:50:12.434  3312  3370 I jxcore-log: ok 227 server should return 200,
03-24 08:50:12.434  3312  3370 I jxcore-log: 
,03-24 08:50:12.445  3312  3370 I jxcore-log: ok 228 response body should match testData,
03-24 08:50:12.445  3312  3370 I jxcore-log: 
,03-24 08:50:12.448  3312  3370 I jxcore-log: ok 229 must be started
03-24 08:50:12.448  3312  3370 I jxcore-log: 
,03-24 08:50:12.457  3312  3370 I jxcore-log: not ok 230 .end() called twice
03-24 08:50:12.457  3312  3370 I jxcore-log: 
,03-24 08:50:12.458  3312  3370 I jxcore-log:   ---
03-24 08:50:12.458  3312  3370 I jxcore-log: 
03-24 08:50:12.458  3312  3370 I jxcore-log:     operator: fail
03-24 08:50:12.458  3312  3370 I jxcore-log: 
03-24 08:50:12.458  3312  3370 I jxcore-log:   ...
03-24 08:50:12.458  3312  3370 I jxcore-log: 
,03-24 08:50:12.459  3312  3370 I jxcore-log: # teardown
03-24 08:50:12.459  3312  3370 I jxcore-log: 
,03-24 08:50:12.471  3312  3893 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 390, thread name: Sender),
03-24 08:50:12.471  3312  3893 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 08:50:12.471  3312  3893 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
03-24 08:50:12.471  3312  3893 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
,03-24 08:50:12.471  3312  3893 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 387)
03-24 08:50:12.471  3312  3893 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 387)
03-24 08:50:12.472  3312  3893 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 08:50:12.472  3312  3893 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 08:50:12.472  3312  3893 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 391
03-24 08:50:12.472  3312  3893 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,03-24 08:50:12.472  3312  3893 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 390
03-24 08:50:12.472  3312  3894 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 391, thread name: Receiver): bt socket closed, read return: -1
03-24 08:50:12.472  3312  3893 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 387)
,03-24 08:50:12.472  3312  3894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 391, name: Receiver)
03-24 08:50:12.473  3312  3893 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 387)
03-24 08:50:12.473  3312  3893 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,03-24 08:50:12.473  3312  3893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 390, name: Sender)
,03-24 08:50:12.624  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 08:50:12.625  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 08:50:12.625  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 08:50:12.625  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:50:12.625  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-24 08:50:12.625  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:50:12.626  3312  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:50:12.626  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-24 08:50:12.626  3312  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 08:50:12.626  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 08:50:12.626  3312  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:50:12.626  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 08:50:12.626  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 08:50:12.626  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:50:12.626  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:50:12.626  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:50:12.626  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:50:12.629  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:50:12.630  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 08:50:12.630  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:12.630  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:12.630  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:50:12.631  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:50:12.631  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 08:50:12.631  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:12.631  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:50:12.633  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:12.633  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:50:12.633  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:12.633  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:12.633  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:12.636  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:12.636  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:12.636  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:12.638  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:50:12.638  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:50:12.638  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:12.639  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:12.639  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:12.639  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 08:50:12.639  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:50:12.639  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:50:12.639  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:50:12.639  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 08:50:12.639  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 08:50:12.641  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 08:50:12.641  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:12.641  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:12.642  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:50:12.642  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:12.642  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:50:12.643  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:12.643  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:50:12.650  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:50:12.651   825  1355 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:12.661  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-24 08:50:12.662  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:12.662  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:50:12.666  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 08:50:12.666  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 08:50:12.666  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 08:50:12.667  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:12.667  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 08:50:12.668  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:12.668  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:50:12.668  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 08:50:12.668  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 08:50:12.669  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:50:12.669  3312  3370 I jxcore-log: ,
03-24 08:50:12.670  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:12.670  3312  3370 I jxcore-log: ,
03-24 08:50:12.671  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:12.671  3312  3370 I jxcore-log: 
,03-24 08:50:12.673  3312  3891 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 388, thread name: Sender)
03-24 08:50:12.673  3312  3891 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-24 08:50:12.673  3312  3891 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Input stream got -1 on read
,03-24 08:50:12.673  3312  3891 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 386
,03-24 08:50:12.674  3312  3891 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 386)
,03-24 08:50:12.674  3312  3891 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-24 08:50:12.674  3312  3891 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...,
,03-24 08:50:12.674  3312  3891 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 389
,03-24 08:50:12.674  3312  3891 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...,
03-24 08:50:12.674  3312  3891 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 388
,03-24 08:50:12.674  3312  3892 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 389, thread name: Receiver): bt socket closed, read return: -1,
,03-24 08:50:12.674  3312  3891 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 386)
03-24 08:50:12.674  3312  3892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 389, name: Receiver)
03-24 08:50:12.675  3312  3891 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 386)
03-24 08:50:12.675  3312  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 08:50:12.675  3312  3370 I jxcore-log: DEBUG createNativeListener: mux close
03-24 08:50:12.675  3312  3370 I jxcore-log: 
03-24 08:50:12.676  3312  3891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 388, name: Sender)
03-24 08:50:12.683  3312  3370 I jxcore-log: ok 231 must be stopped
03-24 08:50:12.683  3312  3370 I jxcore-log: 
,03-24 08:50:12.690  3312  3370 I jxcore-log: # setup
03-24 08:50:12.690  3312  3370 I jxcore-log: 
03-24 08:50:12.692  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:50:12.692  3312  3370 I jxcore-log: 
03-24 08:50:12.694  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 08:50:12.694  3312  3370 I jxcore-log: 
03-24 08:50:12.694  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 08:50:12.694  3312  3370 I jxcore-log: 
,03-24 08:50:12.821  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,03-24 08:50:12.822  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
03-24 08:50:12.822  2158  2236 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-24 08:50:16.209  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 08:50:16.209  3312  3370 I jxcore-log: 
,03-24 08:50:16.233  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 08:50:16.233  3312  3370 I jxcore-log: 
,03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 08:50:16.241  3312  3370 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 08:50:16.245  3312  3370 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 08:50:16.247  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 08:50:16.247  3312  3370 I jxcore-log: 
,03-24 08:50:16.249  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 08:50:16.249  3312  3370 I jxcore-log: 
,03-24 08:50:16.260  3312  3370 I jxcore-log: # 56. can still do HTTP requests between peers
03-24 08:50:16.260  3312  3370 I jxcore-log: 
,03-24 08:50:16.262  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 08:50:16.262  3312  3370 I jxcore-log: 
,03-24 08:50:16.452  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:50:16.452  3312  3370 I jxcore-log: 
,03-24 08:50:16.455  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 55736
,03-24 08:50:16.455  3312  3370 I jxcore-log: 
,03-24 08:50:16.462  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 47425, start advertisements: false
,03-24 08:50:16.462  3312  3370 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-24 08:50:16.462  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 08:50:16.463  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
,03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:50:16.464  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 08:50:16.464  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:50:16.464  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 08:50:16.469  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 08:50:16.469  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 08:50:16.470  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:16.476  2158  3243 D BtGatt.GattService: registerClient() - UUID=a3a03e91-b871-4721-adb5-50668050d20b
03-24 08:50:16.476  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=a3a03e91-b871-4721-adb5-50668050d20b, clientIf=5
03-24 08:50:16.477  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:50:16.478  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:50:16.479  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:50:16.479  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 08:50:16.479  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 08:50:16.479  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 08:50:16.479  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:50:16.479  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:50:16.480  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 08:50:16.480   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:50:16.481  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:16.486  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:16.486  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 08:50:16.486  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:50:16.487  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:16.487  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:16.487  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 08:50:16.487  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:16.488  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 08:50:16.490  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:50:16.490  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:16.490  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:16.490  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:50:16.492  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 08:50:16.492  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:16.492  3312  3370 I jxcore-log: 
03-24 08:50:16.492  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:16.494  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 08:50:16.494  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:16.495  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 08:50:16.495  3312  3370 I jxcore-log: 
,03-24 08:50:16.499  3312  3370 I io.jxcore.node.ConnectionHelper: start: Port number: 55736, start advertisements: true
,03-24 08:50:16.499  3312  3370 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 08:50:16.499  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 08:50:16.499  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 08:50:16.504  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 08:50:16.504  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 08:50:16.504  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 08:50:16.504  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:16.504  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:50:16.504  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:16.504  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:16.504  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:50:16.508  2158  2175 D BtGatt.GattService: registerClient() - UUID=16b52a61-d6e2-494a-8751-52885af7a49b,
,03-24 08:50:16.509  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=16b52a61-d6e2-494a-8751-52885af7a49b, clientIf=6
03-24 08:50:16.509  3312  3329 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:50:16.510  2158  2231 D BtGatt.AdvertiseManager: message : 0,
,03-24 08:50:16.512  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:16.514  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:16.516  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:16.516  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:50:16.516  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 08:50:16.516  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:50:16.516  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:50:16.517  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:50:16.517  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 08:50:16.517   825  1324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 08:50:16.517  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 08:50:16.519  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 08:50:16.519  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 08:50:16.519  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 08:50:16.519  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:16.519  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 08:50:16.519  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 08:50:16.520  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 08:50:16.520  3312  3370 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 08:50:16.520  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 08:50:16.520  3312  3370 I io.jxcore.node.ConnectionHelper: start: OK
03-24 08:50:16.520  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 08:50:16.520  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:16.520  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 08:50:16.521  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 08:50:16.521  3312  3370 I jxcore-log: 
03-24 08:50:16.522   825   843 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:16.523  3312  3896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:50:16.525  3312  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:50:17.905  2158  2236 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 08:50:17.911  2158  2158 D BluetoothMapService: onReceive
,03-24 08:50:17.936  3810  3810 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 08:50:17.940  3810  3810 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 08:50:18.769  2158  2158 D BtGatt.ScanManager: awakened up at time 318691
03-24 08:50:18.770  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:50:18.776  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:50:18.776  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:18.777  2158  2222 D BtGatt.GattService: current time is 318699841648
,03-24 08:50:18.777  2158  2222 D BtGatt.GattService: Batch record : [36, -18, -3, -60, 86, 93, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:50:18.777  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:50:18.778  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 08:50:18.780  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-24 08:50:18.781  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-24 08:50:18.781  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 08:50:18.782  3312  3312 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 08:50:18.785  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:50:18.785  3312  3370 I jxcore-log: 
,03-24 08:50:18.788  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 08:50:18.788  3312  3370 I jxcore-log: 
,03-24 08:50:18.790  3312  3370 I jxcore-log: ok 232 found a peer! {"peerIdentifier":"E0:DB:10:14:E2:C0","portNumber":36473,"hostAddress":"127.0.0.1"}
03-24 08:50:18.790  3312  3370 I jxcore-log: 
,03-24 08:50:18.798  3312  3370 I jxcore-log: DEBUG createPeerListener: first connection
03-24 08:50:18.798  3312  3370 I jxcore-log: 
,03-24 08:50:18.803  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-24 08:50:18.803  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:18.805  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,03-24 08:50:18.805  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 08:50:18.805  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
03-24 08:50:18.806  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Note4-1 E0:DB:10:14:E2:C0
03-24 08:50:18.806  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
03-24 08:50:18.806  3312  3370 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-24 08:50:18.807  3312  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 393)
03-24 08:50:18.807  3312  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 08:50:18.809  2158  2175 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 08:50:18.815  3312  3370 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 08:50:18.815  3312  3370 I jxcore-log: 
,03-24 08:50:18.822  3312  3370 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 08:50:18.822  3312  3370 I jxcore-log: 
,03-24 08:50:20.704  2158  2236 W bt-btif : No ag scb for peer addr
,03-24 08:50:20.725  2158  2236 W bt-btif : info:x10
,03-24 08:50:20.725  2158  2222 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,03-24 08:50:20.756  3810  3810 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524],
,03-24 08:50:20.762  3810  3810 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 08:50:20.773  2158  2236 W bt-sdp  : process_service_search_attr_rsp,
,03-24 08:50:23.727  2158  2220 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 08:50:23.781  2158  2158 D BtGatt.ScanManager: awakened up at time 323704
,03-24 08:50:23.784  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-24 08:50:23.788  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 08:50:23.788  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:50:23.789  2158  2222 D BtGatt.GattService: current time is 323711999146
03-24 08:50:23.789  2158  2222 D BtGatt.GattService: Batch record : [36, -18, -3, -60, 86, 93, 1, -128, -73, 65, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -66, 65, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 08:50:23.790  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 08:50:23.791  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 08:50:23.794  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 08:50:23.794  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 08:50:24.801  2158  2236 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 78 RCID: 66
,03-24 08:50:24.948  2158  2236 W bt-btif : new conn_srvc id:26, app_id:255
,03-24 08:50:24.948  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:50:24.948  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 08:50:24.949  3312  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 08:50:24.950  3312  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 394)
03-24 08:50:24.950  3312  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 08:50:24.952   825  1186 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:24.954  3312  3899 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 394)
,03-24 08:50:24.955  3312  3896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 08:50:24.962  3312  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 08:50:25.080  2158  2236 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 08:50:25.080  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 08:50:25.080  2158  2236 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 08:50:25.080  2158  2236 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 08:50:25.082  3312  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 393)
03-24 08:50:25.082  3312  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 393)
03-24 08:50:25.084  3312  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 395)
,03-24 08:50:25.084  3312  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 395)
03-24 08:50:25.084  3312  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,03-24 08:50:25.088  3312  3900 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 395)
,03-24 08:50:25.219  3312  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 394)
,03-24 08:50:25.223  3312  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:25.224  3312  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 394)
03-24 08:50:25.224  3312  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 394
,03-24 08:50:25.224  3312  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 394)
,03-24 08:50:25.225  3312  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:25.225  3312  3899 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 394)
03-24 08:50:25.225  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:25.225  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:25.226  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 08:50:25.226  3312  3312 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 08:50:25.226  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 08:50:25.227  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:25.227  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:25.227  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:50:25.227  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:50:25.227  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:50:25.227  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:50:25.232  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:25.233  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 08:50:25.238  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:50:25.238  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:25.242  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 08:50:25.245  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 08:50:25.246  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:25.246  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:50:25.246  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:25.248  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:25.248  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:50:25.249  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 08:50:25.249  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:25.249  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:50:25.249  3312  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 395)
,03-24 08:50:25.250  3312  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-24 08:50:25.250  3312  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 393)
03-24 08:50:25.250  3312  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 393)
03-24 08:50:25.250  3312  3900 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 395)
,03-24 08:50:25.259  2158  3243 D BtGatt.GattService: registerClient() - UUID=9faf7dca-a2cc-4212-8f41-5e52bd7e81ee,
03-24 08:50:25.259  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=9faf7dca-a2cc-4212-8f41-5e52bd7e81ee, clientIf=6
,03-24 08:50:25.260  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 08:50:25.261  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:25.265  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:25.268  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:25.271  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:25.271  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:50:25.273  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:25.274  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:50:25.275  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:25.275  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.275  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
,03-24 08:50:25.275  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:25.275  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 08:50:25.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:25.275  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:25.275  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:50:25.276  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:25.277  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:25.277  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.277  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 08:50:25.279  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 08:50:25.279  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.279  2158  2222 D BtGatt.GattService: current time is 325202604458
03-24 08:50:25.279  2158  2222 D BtGatt.GattService: Batch record : [-121, 59, 126, -36, 57, 99, 1, -128, -85, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 08:50:25.280  2158  2222 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 08:50:25.282  2158  2176 D BtGatt.GattService: registerClient() - UUID=906a8a23-357a-43cc-9aff-f191a29af4e3
,03-24 08:50:25.282  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=906a8a23-357a-43cc-9aff-f191a29af4e3, clientIf=5
03-24 08:50:25.284  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 08:50:25.284  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:50:25.285  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 08:50:25.285  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:25.285  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 08:50:25.285  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:25.286  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:25.286  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-24 08:50:25.286  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:50:25.286  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:50:25.286  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:50:25.286  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:50:25.287  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:25.287  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.288  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:50:25.288  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.288  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:25.289  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 08:50:25.290  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:25.291  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:25.291  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.292  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:25.292  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.292  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:50:25.296  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 08:50:25.296  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:25.296  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:25.297  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:25.297  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:50:25.297  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:50:25.297  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:25.297  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:25.297  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 08:50:25.297  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:25.297  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:25.297  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 08:50:25.302  2158  2176 D BtGatt.GattService: registerClient() - UUID=99296f3d-c053-4148-962d-43028a3fb420
03-24 08:50:25.302  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=99296f3d-c053-4148-962d-43028a3fb420, clientIf=6
03-24 08:50:25.302  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:50:25.303  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:25.307  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:25.310  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:25.312  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:25.313  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:50:25.315  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:25.316  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:50:25.316  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:25.316  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.317  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:25.317  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:50:25.317  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:25.317  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:50:25.317  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:25.317  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:50:25.317  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:25.320  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 08:50:25.320  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.320  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:25.322  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:25.322  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.323  2158  2176 D BtGatt.GattService: registerClient() - UUID=8464c5c2-1200-4fe5-830a-cb16a1d5936d
,03-24 08:50:25.324  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=8464c5c2-1200-4fe5-830a-cb16a1d5936d, clientIf=5
,03-24 08:50:25.325  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:50:25.325  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:50:25.327  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0,
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:50:25.327  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:50:25.329  2158  2233 D BtGatt.ScanManager: handling starting scan
,03-24 08:50:25.330  2158  2231 D BtGatt.AdvertiseManager: message : 1
03-24 08:50:25.331  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:50:25.332  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:25.332  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.335  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:50:25.335  2158  2222 D BtGatt.GattService: Client app is not null!
,03-24 08:50:25.336  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:25.337  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:50:25.337  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.337  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 08:50:25.337  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 08:50:25.337  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 08:50:25.337  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 08:50:25.337  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 08:50:25.337  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 08:50:25.338  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:25.338  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 08:50:25.338  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 08:50:25.339  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 08:50:25.339  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:50:25.340  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:25.340  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.342  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:25.342  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.344  2158  3243 D BtGatt.GattService: registerClient() - UUID=ab5c8df7-302d-4866-a57d-fb7f6f298b81
,03-24 08:50:25.345  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=ab5c8df7-302d-4866-a57d-fb7f6f298b81, clientIf=6
03-24 08:50:25.345  3312  3328 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 08:50:25.346  2158  2231 D BtGatt.AdvertiseManager: message : 0
,03-24 08:50:25.350  2158  2231 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 08:50:25.353  2158  2222 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 08:50:25.356  2158  2222 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 08:50:25.356  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 08:50:25.358  2158  2176 D BtGatt.GattService: stopScan() - queue size =1
,03-24 08:50:25.359  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:50:25.360  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:25.360  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.360  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 08:50:25.360  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:25.361  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:25.361  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:25.361  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 08:50:25.361  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 08:50:25.361  3312  3312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 08:50:25.362  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:25.363  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.363  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:25.364  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:25.364  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.367  2158  2176 D BtGatt.GattService: registerClient() - UUID=ca757b85-8ffd-44a9-ab6b-ea376215eb8d
03-24 08:50:25.368  2158  2222 D BtGatt.GattService: onClientRegistered() - UUID=ca757b85-8ffd-44a9-ab6b-ea376215eb8d, clientIf=5
03-24 08:50:25.368  3312  3328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 08:50:25.368  2158  2175 D BtGatt.GattService: start scan with filters
,03-24 08:50:25.369  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 08:50:25.370  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 08:50:25.370  2158  2233 D BtGatt.ScanManager: handling starting scan
03-24 08:50:25.370  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 08:50:25.370  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 08:50:25.370  3312  3312 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:25.370  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:50:25.370  3312  3312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 08:50:25.371  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 08:50:25.371  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 08:50:25.371  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 08:50:25.371  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:25.371  3312  3312 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 08:50:25.372  2158  2222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 08:50:25.372  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.372  3312  3902 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 396)
,03-24 08:50:25.373  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 08:50:25.373  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.373  3312  3312 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
03-24 08:50:25.373  2158  2233 D BtGatt.ScanManager: Starting BLE batch scan
03-24 08:50:25.373  2158  2233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 08:50:25.373  3312  3312 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-24 08:50:25.375  2158  2222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 08:50:25.375  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.376  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 08:50:25.376  3312  3903 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 397)
03-24 08:50:25.376  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.376  3312  3903 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46986
03-24 08:50:25.376  3312  3903 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 08:50:25.376  3312  3903 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 46986 (peer ID: E0:DB:10:14:E2:C0)
03-24 08:50:25.377  3312  3902 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 55736
,03-24 08:50:25.377  3312  3902 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 08:50:25.377  3312  3902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:50:25.378  3312  3903 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-24 08:50:25.378  3312  3902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-24 08:50:25.379  3312  3905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 398, name: Sender)
03-24 08:50:25.379  3312  3902 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 396)
03-24 08:50:25.379  3312  3902 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 396)
03-24 08:50:25.379  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:50:25.379  3312  3370 I jxcore-log: 
,03-24 08:50:25.381  3312  3906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 399, name: Receiver)
03-24 08:50:25.381  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:50:25.381  3312  3370 I jxcore-log: 
,03-24 08:50:25.394  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:50:25.394  3312  3370 I jxcore-log: 
,03-24 08:50:25.410  3312  3370 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 08:50:25.410  3312  3370 I jxcore-log: 
,03-24 08:50:25.414  3312  3903 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 46986
,03-24 08:50:25.414  3312  3903 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 08:50:25.414  3312  3903 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:50:25.414  3312  3903 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 08:50:25.415  3312  3907 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 400, name: Sender)
,03-24 08:50:25.416  3312  3903 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 397)
03-24 08:50:25.416  3312  3903 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 397)
,03-24 08:50:25.417  3312  3370 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 08:50:25.417  3312  3370 I jxcore-log: 
,03-24 08:50:25.418  3312  3908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 401, name: Receiver)
,03-24 08:50:25.420  3312  3370 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 08:50:25.420  3312  3370 I jxcore-log: 
,03-24 08:50:25.452  3312  3370 I jxcore-log: DEBUG createNativeListener: stream close:,
03-24 08:50:25.452  3312  3370 I jxcore-log: 
,03-24 08:50:25.612  3312  3370 I jxcore-log: DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed,
03-24 08:50:25.612  3312  3370 I jxcore-log: 
,03-24 08:50:25.627  3312  3370 I jxcore-log: ok 233 server should return 200
03-24 08:50:25.627  3312  3370 I jxcore-log: 
03-24 08:50:25.630  3312  3370 I jxcore-log: ok 234 response body should match testData,
03-24 08:50:25.630  3312  3370 I jxcore-log: 
03-24 08:50:25.631  3312  3370 I jxcore-log: ok 235 must be started
03-24 08:50:25.631  3312  3370 I jxcore-log: 
,03-24 08:50:25.640  3312  3370 I jxcore-log: not ok 236 .end() called twice
03-24 08:50:25.640  3312  3370 I jxcore-log: 
03-24 08:50:25.640  3312  3370 I jxcore-log:   ---
03-24 08:50:25.640  3312  3370 I jxcore-log: 
,03-24 08:50:25.640  3312  3370 I jxcore-log:     operator: fail
03-24 08:50:25.640  3312  3370 I jxcore-log: 
03-24 08:50:25.640  3312  3370 I jxcore-log:   ...
03-24 08:50:25.640  3312  3370 I jxcore-log: 
,03-24 08:50:25.641  3312  3370 I jxcore-log: # teardown
03-24 08:50:25.641  3312  3370 I jxcore-log: 
,03-24 08:50:25.905  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 08:50:25.905  3312  3370 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-24 08:50:25.905  3312  3370 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 397)
03-24 08:50:25.905  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 397)
03-24 08:50:25.906  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 08:50:25.906  3312  3370 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 08:50:25.906  3312  3370 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 401
03-24 08:50:25.907  3312  3908 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 401, thread name: Receiver): bt socket closed, read return: -1
,03-24 08:50:25.907  3312  3370 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 08:50:25.907  2158  2364 W bt-btif : invalid rfc slot id: 24
03-24 08:50:25.907  3312  3906 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 399, thread name: Receiver): bt socket closed, read return: -1
03-24 08:50:25.907  3312  3906 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-24 08:50:25.908  3312  3906 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> E0:DB:10:14:E2:C0] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 08:50:25.908  3312  3370 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 400
03-24 08:50:25.908  3312  3370 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 397)
03-24 08:50:25.908  3312  3370 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 397)
03-24 08:50:25.908  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 08:50:25.908  3312  3370 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 08:50:25.908  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 08:50:25.908  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 08:50:25.909  3312  3370 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 08:50:25.909  3312  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 08:50:25.909  3312  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 08:50:25.909  3312  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 08:50:25.909  3312  3907 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 400, thread name: Sender): Socket closed
03-24 08:50:25.909  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 08:50:25.909  3312  3907 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 400, name: Sender)
03-24 08:50:25.909  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 08:50:25.910  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 08:50:25.910  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 08:50:25.910  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 08:50:25.910  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 08:50:25.910  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 08:50:25.910  3312  3312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 08:50:25.910  3312  3908 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 401, name: Receiver)
03-24 08:50:25.911  3312  3906 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 396
03-24 08:50:25.912  3312  3906 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 396)
03-24 08:50:25.912  3312  3906 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 08:50:25.912  3312  3906 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-24 08:50:25.912  3312  3906 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 399,
03-24 08:50:25.912  3312  3906 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 08:50:25.912  3312  3906 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 398
03-24 08:50:25.912  3312  3906 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 396)
03-24 08:50:25.912  3312  3906 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 396)
03-24 08:50:25.912  3312  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 08:50:25.913  3312  3906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 399, name: Receiver)
03-24 08:50:25.913  2158  3243 D BtGatt.GattService: stopScan() - queue size =1
03-24 08:50:25.914  2158  2176 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 08:50:25.915  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 08:50:25.915  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:25.915  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 08:50:25.915  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 08:50:25.915  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 08:50:25.917  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 08:50:25.917  2158  2222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 08:50:25.917  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 08:50:25.918  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 08:50:25.918  2158  2233 D BtGatt.ScanManager: stopping BLe Batch
03-24 08:50:25.920  2158  2222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 08:50:25.920  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 08:50:25.920  2158  2233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 08:50:25.921  3312  3905 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 398, thread name: Sender): Socket closed
03-24 08:50:25.921  3312  3905 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 398, name: Sender)
03-24 08:50:25.921  2158  2222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 08:50:25.921  2158  2222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 08:50:25.927  2158  2231 D BtGatt.AdvertiseManager: message : 1,
03-24 08:50:25.928  2158  2231 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 08:50:25.929  2158  2222 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 08:50:25.929  2158  2222 D BtGatt.GattService: Client app is not null!
03-24 08:50:25.930  2158  3243 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 08:50:25.930  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 08:50:25.930  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 08:50:25.931  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 08:50:25.931  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 08:50:25.931  3312  3370 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 08:50:25.931  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:50:25.931  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 08:50:25.931  3312  3370 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 08:50:25.932  3312  3370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 08:50:25.932  3312  3370 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 08:50:25.932  3312  3370 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 08:50:25.932  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 08:50:25.932  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 08:50:25.932  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 08:50:25.937  3312  3312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 08:50:25.937   825  1323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 08:50:25.942  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 08:50:25.943  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:25.943  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 08:50:25.946  3312  3312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-24 08:50:25.946  3312  3312 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 08:50:25.946  3312  3312 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 08:50:25.946  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 08:50:25.946  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 08:50:25.947  3312  3312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 08:50:25.948  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:50:25.948  3312  3370 I jxcore-log: 
03-24 08:50:25.949  3312  3370 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 08:50:25.949  3312  3370 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 08:50:25.949  3312  3370 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 08:50:25.950  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 08:50:25.950  3312  3370 I jxcore-log: 
03-24 08:50:25.951  3312  3370 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-24 08:50:25.951  3312  3370 I jxcore-log: 
,03-24 08:50:25.952  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 08:50:25.952  3312  3370 I jxcore-log: 
03-24 08:50:25.952  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 08:50:25.952  3312  3370 I jxcore-log: 
,03-24 08:50:25.953  3312  3370 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 08:50:25.953  3312  3370 I jxcore-log: 
,03-24 08:50:25.960  3312  3370 I jxcore-log: ok 237 must be stopped,
03-24 08:50:25.960  3312  3370 I jxcore-log: 
,03-24 08:50:25.965  3312  3370 I jxcore-log: # setup,
03-24 08:50:25.965  3312  3370 I jxcore-log: 
,03-24 08:50:26.111  2158  2236 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND,
,03-24 08:50:28.826  3312  3370 I jxcore-log: # 57. Test BEACONS_RETRIEVED_AND_PARSED locally,
03-24 08:50:28.826  3312  3370 I jxcore-log: ,
,03-24 08:50:28.970  3312  3370 I jxcore-log: ok 238 peerIdentifier should be hello,
,03-24 08:50:28.970  3312  3370 I jxcore-log: ,
,03-24 08:50:28.970  3312  3370 I jxcore-log: ok 239 Response should be BEACONS_RETRIEVED_AND_PARSED,
,03-24 08:50:28.970  3312  3370 I jxcore-log: 
03-24 08:50:28.971  3312  3370 I jxcore-log: ok 240 good beacon
,03-24 08:50:28.971  3312  3370 I jxcore-log: 
,03-24 08:50:28.971  3312  3370 I jxcore-log: ok 241 good preAmble
03-24 08:50:28.971  3312  3370 I jxcore-log: 
03-24 08:50:28.971  3312  3370 I jxcore-log: ok 242 public keys match!
03-24 08:50:28.971  3312  3370 I jxcore-log: 
,03-24 08:50:28.973  3312  3370 I jxcore-log: ok 243 must return null after successful call
03-24 08:50:28.973  3312  3370 I jxcore-log: 
03-24 08:50:28.982  3312  3370 I jxcore-log: # teardown
03-24 08:50:28.982  3312  3370 I jxcore-log: 
,03-24 08:50:31.968  2158  2236 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-24 08:50:31.976  2158  2158 D BluetoothMapService: onReceive
,03-24 08:50:32.009  3810  3810 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,03-24 08:50:32.013  3810  3810 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-24 08:50:32.193  3312  3370 I jxcore-log: # setup
03-24 08:50:32.193  3312  3370 I jxcore-log: 
,03-24 08:50:32.592  3312  3370 I jxcore-log: # 58. Test HTTP_BAD_RESPONSE locally
,03-24 08:50:32.592  3312  3370 I jxcore-log: 
,03-24 08:50:32.619  3548  3909 V KeepSync: Connecting to GoogleApiClient
,03-24 08:50:32.676  1258  3765 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 08:50:32.676  1258  3765 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 08:50:32.676  1258  3765 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:50:32.676  1258  3765 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:32.680  1258  3765 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: Handling authorization failure
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: ,	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	,at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	,at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	,at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 08:50:32.695  1781  3910 E ClientConnectionOperation: 	... 7 more
03-24 08:50:32.697  3548  3909 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 08:50:32.699  3548  3909 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:50:32.702  3548  3909 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 08:50:32.703  3548  3909 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 08:50:32.801  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 08:50:32.801  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:50:32.802  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:50:32.802  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:32.808  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:32.860  3548  3909 E KeepSync: IOException
03-24 08:50:32.860  3548  3909 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 08:50:32.860  3548  3909 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 08:50:32.860  3548  3909 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 08:50:32.860  3548  3909 E KeepSync: 	... 10 more
03-24 08:50:32.861  3548  3909 W KeepSync: Sync result 2
,03-24 08:50:32.872   825   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 305777, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 08:50:33.592  3312  3370 I jxcore-log: ok 244 Response should be HTTP_BAD_RESPONSE
03-24 08:50:33.592  3312  3370 I jxcore-log: 
03-24 08:50:33.593  3312  3370 I jxcore-log: ok 245 must return null after successful call
03-24 08:50:33.593  3312  3370 I jxcore-log: 
,03-24 08:50:33.602  3312  3370 I jxcore-log: # teardown
03-24 08:50:33.602  3312  3370 I jxcore-log: 
,03-24 08:50:35.569  3312  3370 I jxcore-log: # setup
03-24 08:50:35.569  3312  3370 I jxcore-log: 
,03-24 08:50:36.882  3312  3370 I jxcore-log: # 59. Test NETWORK_PROBLEM locally
03-24 08:50:36.882  3312  3370 I jxcore-log: 
,03-24 08:50:36.902  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:50:37.277  3312  3370 I jxcore-log: ok 246 Response should be NETWORK_PROBLEM
03-24 08:50:37.277  3312  3370 I jxcore-log: 
,03-24 08:50:37.283  3312  3370 I jxcore-log: ok 247 reject reason should be: Could not establish TCP connection
03-24 08:50:37.283  3312  3370 I jxcore-log: 
,03-24 08:50:37.301  3312  3370 I jxcore-log: # teardown
03-24 08:50:37.301  3312  3370 I jxcore-log: 
,03-24 08:50:38.439  3312  3370 I jxcore-log: # setup
03-24 08:50:38.439  3312  3370 I jxcore-log: 
,03-24 08:50:38.612  3312  3370 I jxcore-log: # 60. Test timeout locally
03-24 08:50:38.612  3312  3370 I jxcore-log: 
,03-24 08:50:40.612  3312  3312 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 08:50:40.613  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:50:40.614  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 08:50:40.615  3312  3312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 08:50:41.104  3312  3370 I jxcore-log: ok 248 Should be NETWORK_PROBLEM caused by timeout
,03-24 08:50:41.104  3312  3370 I jxcore-log: 
,03-24 08:50:41.112  3312  3370 I jxcore-log: ok 249 reject reason should be Could not establish TCP connection
03-24 08:50:41.112  3312  3370 I jxcore-log: 
,03-24 08:50:41.124  3312  3370 I jxcore-log: # teardown
03-24 08:50:41.124  3312  3370 I jxcore-log: 
,03-24 08:50:41.223  3312  3370 I jxcore-log: # setup
03-24 08:50:41.223  3312  3370 I jxcore-log: 
,03-24 08:50:41.895  3312  3370 I jxcore-log: # 61. Call the start two times
03-24 08:50:41.895  3312  3370 I jxcore-log: 
,03-24 08:50:42.072  3312  3370 I jxcore-log: ok 250 Call start once
03-24 08:50:42.072  3312  3370 I jxcore-log: 
,03-24 08:50:42.120  3312  3370 I jxcore-log: ok 251 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 08:50:42.120  3312  3370 I jxcore-log: 
,03-24 08:50:42.121  3312  3370 I jxcore-log: ok 252 must return null after successful call.
03-24 08:50:42.121  3312  3370 I jxcore-log: 
,03-24 08:50:42.131  3312  3370 I jxcore-log: # teardown
03-24 08:50:42.131  3312  3370 I jxcore-log: 
,03-24 08:50:42.275  3312  3370 I jxcore-log: # setup
03-24 08:50:42.275  3312  3370 I jxcore-log: 
,03-24 08:50:42.524  3312  3370 I jxcore-log: # 62. Call the kill before calling the start
03-24 08:50:42.524  3312  3370 I jxcore-log: 
,03-24 08:50:42.666  3312  3370 I jxcore-log: ok 253 Should be Killed
03-24 08:50:42.666  3312  3370 I jxcore-log: 
,03-24 08:50:42.681  3312  3370 I jxcore-log: ok 254 Start after killed
03-24 08:50:42.681  3312  3370 I jxcore-log: 
,03-24 08:50:42.688  3312  3370 I jxcore-log: # teardown
03-24 08:50:42.688  3312  3370 I jxcore-log: 
,03-24 08:50:42.819  3312  3370 I jxcore-log: # setup
03-24 08:50:42.819  3312  3370 I jxcore-log: 
,03-24 08:50:43.091  3312  3370 I jxcore-log: # 63. Call the kill immediately after the start
03-24 08:50:43.091  3312  3370 I jxcore-log: 
,03-24 08:50:43.198  3312  3370 I jxcore-log: ok 255 Should be KILLED
03-24 08:50:43.198  3312  3370 I jxcore-log: 
,03-24 08:50:43.201  3312  3370 I jxcore-log: ok 256 must return null after successful kill
03-24 08:50:43.201  3312  3370 I jxcore-log: 
,03-24 08:50:43.211  3312  3370 I jxcore-log: # teardown
,03-24 08:50:43.211  3312  3370 I jxcore-log: 
,03-24 08:50:43.331  3312  3370 I jxcore-log: # setup
03-24 08:50:43.331  3312  3370 I jxcore-log: 
,03-24 08:50:43.562  3312  3370 I jxcore-log: # 64. Call the kill while waiting a response from the server
03-24 08:50:43.562  3312  3370 I jxcore-log: 
,03-24 08:50:45.732  3312  3370 I jxcore-log: ok 257 Should be KILLED
03-24 08:50:45.732  3312  3370 I jxcore-log: 
,03-24 08:50:45.737  3312  3370 I jxcore-log: ok 258 must return null after successful kill
03-24 08:50:45.737  3312  3370 I jxcore-log: 
,03-24 08:50:45.756  3312  3370 I jxcore-log: # teardown
03-24 08:50:45.756  3312  3370 I jxcore-log: 
,03-24 08:50:45.899  3312  3370 I jxcore-log: # setup
,03-24 08:50:45.899  3312  3370 I jxcore-log: 
,03-24 08:50:46.113  3312  3370 I jxcore-log: # 65. Test to exceed the max content size locally
,03-24 08:50:46.113  3312  3370 I jxcore-log: 
,03-24 08:50:46.329  3312  3370 I jxcore-log: ok 259 HTTP_BAD_RESPONSE should be response when content size is exceeded
,03-24 08:50:46.329  3312  3370 I jxcore-log: 
03-24 08:50:46.333  3312  3370 I jxcore-log: ok 260 must return null after successful call
03-24 08:50:46.333  3312  3370 I jxcore-log: 
,03-24 08:50:46.345  3312  3370 I jxcore-log: # teardown
,03-24 08:50:46.345  3312  3370 I jxcore-log: 
,03-24 08:50:46.479  3312  3370 I jxcore-log: # setup
,03-24 08:50:46.479  3312  3370 I jxcore-log: 
,03-24 08:50:46.731  3312  3370 I jxcore-log: # 66. Close the server socket while the client is waiting a response from the server. Local test.
,03-24 08:50:46.731  3312  3370 I jxcore-log: 
,03-24 08:50:48.911  3312  3370 I jxcore-log: ok 261 Should be NETWORK_PROBLEM caused closing server socket
03-24 08:50:48.911  3312  3370 I jxcore-log: 
,03-24 08:50:48.918  3312  3370 I jxcore-log: ok 262 Should be Could not establish TCP connection
03-24 08:50:48.918  3312  3370 I jxcore-log: 
,03-24 08:50:48.935  3312  3370 I jxcore-log: # teardown
,03-24 08:50:48.935  3312  3370 I jxcore-log: 
,03-24 08:50:49.050  3312  3370 I jxcore-log: # setup
,03-24 08:50:49.050  3312  3370 I jxcore-log: 
,03-24 08:50:49.265  3312  3370 I jxcore-log: # 67. Close the client socket while the client is waiting a response from the server. Local test.
,03-24 08:50:49.265  3312  3370 I jxcore-log: 
,03-24 08:50:51.148  1258  1258 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:51.228  1258  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
,03-24 08:50:51.229  1258  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:50:51.229  1258  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:50:51.230  1258  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:50:51.243  1258  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:50:51.336  1258  1725 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 08:50:51.336  1258  1725 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 08:50:51.336  1258  1725 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 08:50:51.336  1258  1725 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 08:50:51.336  1258  1725 W GLSActivity: ,	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 08:50:51.336  1258  1725 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 08:50:51.336  1258  1725 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 08:50:51.344  2781  2820 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 08:50:51.344  2781  2820 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 08:50:51.344  2781  2820 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 08:50:51.344  2781  2820 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 08:50:51.344  2781  2820 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 08:50:51.344  2781  2820 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 08:50:51.344  2781  2820 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 08:50:51.378  2781  2820 W System  : Ignoring header User-Agent because its value was null.
,03-24 08:50:51.430  3312  3370 I jxcore-log: ok 263 Should be NETWORK_PROBLEM caused closing client socket
,03-24 08:50:51.430  3312  3370 I jxcore-log: 
,03-24 08:50:51.437  3312  3370 I jxcore-log: ok 264 Should be Could not establish TCP connection
,03-24 08:50:51.437  3312  3370 I jxcore-log: 
,03-24 08:50:51.448  3312  3370 I jxcore-log: # teardown
,03-24 08:50:51.448  3312  3370 I jxcore-log: 
,03-24 08:50:51.592  3312  3370 I jxcore-log: # setup
,03-24 08:50:51.592  3312  3370 I jxcore-log: 
,03-24 08:50:51.766  3312  3370 I jxcore-log: # 68. #generatePreambleAndBeacons bad args
,03-24 08:50:51.766  3312  3370 I jxcore-log: 
,03-24 08:50:51.957  3312  3370 I jxcore-log: ok 265 publicKeysToNotify cannot be null
03-24 08:50:51.957  3312  3370 I jxcore-log: 
,03-24 08:50:51.960  3312  3370 I jxcore-log: ok 266 ecdh for local device cannot be null
03-24 08:50:51.960  3312  3370 I jxcore-log: 
,03-24 08:50:51.962  3312  3370 I jxcore-log: ok 267 milliseconds cannot be less than 0
03-24 08:50:51.962  3312  3370 I jxcore-log: 
,03-24 08:50:51.965  3312  3370 I jxcore-log: ok 268 milliseconds cannot be 0
03-24 08:50:51.965  3312  3370 I jxcore-log: 
,03-24 08:50:51.968  3312  3370 I jxcore-log: ok 269 milliseconds cannot be greater than one_day
03-24 08:50:51.968  3312  3370 I jxcore-log: 
,03-24 08:50:51.972  3312  3370 I jxcore-log: # teardown
03-24 08:50:51.972  3312  3370 I jxcore-log: 
,03-24 08:50:52.281  3312  3370 I jxcore-log: # setup
03-24 08:50:52.281  3312  3370 I jxcore-log: 
,03-24 08:50:52.540  3312  3370 I jxcore-log: # 69. #generatePreambleAndBeacons empty keys to notify
03-24 08:50:52.540  3312  3370 I jxcore-log: 
,03-24 08:50:53.715  3312  3370 I jxcore-log: ok 270 should be equal
03-24 08:50:53.715  3312  3370 I jxcore-log: 
,03-24 08:50:53.718  3312  3370 I jxcore-log: # teardown
03-24 08:50:53.718  3312  3370 I jxcore-log: 
,03-24 08:50:54.463  3312  3370 I jxcore-log: # setup
03-24 08:50:54.463  3312  3370 I jxcore-log: 
,03-24 08:50:55.430  3312  3370 I jxcore-log: # 70. #generatePreambleAndBeacons multiple keys to notify
03-24 08:50:55.430  3312  3370 I jxcore-log: 
,03-24 08:50:55.637  3312  3370 I jxcore-log: ok 271 should be equal
03-24 08:50:55.637  3312  3370 I jxcore-log: 
,03-24 08:50:55.637  3312  3370 I jxcore-log: ok 272 should be equal
03-24 08:50:55.637  3312  3370 I jxcore-log: 
03-24 08:50:55.638  3312  3370 I jxcore-log: ok 273 (unnamed assert)
03-24 08:50:55.638  3312  3370 I jxcore-log: 
03-24 08:50:55.638  3312  3370 I jxcore-log: ok 274 should be equal
03-24 08:50:55.638  3312  3370 I jxcore-log: 
,03-24 08:50:55.640  3312  3370 I jxcore-log: # teardown
03-24 08:50:55.640  3312  3370 I jxcore-log: 
,03-24 08:50:56.147  3312  3370 I jxcore-log: # setup
03-24 08:50:56.147  3312  3370 I jxcore-log: 
,03-24 08:50:56.290  3312  3370 I jxcore-log: # 71. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-24 08:50:56.290  3312  3370 I jxcore-log: 
,03-24 08:50:56.440  3312  3370 I jxcore-log: ok 275 should throw
03-24 08:50:56.440  3312  3370 I jxcore-log: 
,03-24 08:50:56.444  3312  3370 I jxcore-log: # teardown
03-24 08:50:56.444  3312  3370 I jxcore-log: 
,03-24 08:50:56.559  3312  3370 I jxcore-log: # setup
03-24 08:50:56.559  3312  3370 I jxcore-log: 
,03-24 08:50:56.662  3312  3370 I jxcore-log: # 72. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-24 08:50:56.662  3312  3370 I jxcore-log: 
,03-24 08:50:56.800  3312  3370 I jxcore-log: ok 276 Preamble expiration must be a 64 bit integer
03-24 08:50:56.800  3312  3370 I jxcore-log: 
,03-24 08:50:56.803  3312  3370 I jxcore-log: # teardown
03-24 08:50:56.803  3312  3370 I jxcore-log: 
,03-24 08:50:56.929  3312  3370 I jxcore-log: # setup
03-24 08:50:56.929  3312  3370 I jxcore-log: 
,03-24 08:50:57.089  3312  3370 I jxcore-log: # 73. #parseBeacons expiration out of range lower
03-24 08:50:57.089  3312  3370 I jxcore-log: 
,03-24 08:50:57.231  3312  3370 I jxcore-log: ok 277 Expiration out of range
03-24 08:50:57.231  3312  3370 I jxcore-log: 
,03-24 08:50:57.233  3312  3370 I jxcore-log: # teardown
03-24 08:50:57.233  3312  3370 I jxcore-log: 
,03-24 08:50:57.359  3312  3370 I jxcore-log: # setup
03-24 08:50:57.359  3312  3370 I jxcore-log: 
,03-24 08:50:57.501  3312  3370 I jxcore-log: # 74. #parseBeacons expiration out of range lower
03-24 08:50:57.501  3312  3370 I jxcore-log: 
,03-24 08:50:57.681  3312  3370 I jxcore-log: ok 278 Expiration out of range
03-24 08:50:57.681  3312  3370 I jxcore-log: 
,03-24 08:50:57.684  3312  3370 I jxcore-log: # teardown
03-24 08:50:57.684  3312  3370 I jxcore-log: 
,03-24 08:50:57.827  3312  3370 I jxcore-log: # setup
03-24 08:50:57.827  3312  3370 I jxcore-log: 
,03-24 08:50:57.941  3312  3370 I jxcore-log: # 75. #parseBeacons no beacons returns null
03-24 08:50:57.941  3312  3370 I jxcore-log: 
,03-24 08:50:58.058  3312  3370 I jxcore-log: ok 279 should be equal
03-24 08:50:58.058  3312  3370 I jxcore-log: 
,03-24 08:50:58.061  3312  3370 I jxcore-log: # teardown
03-24 08:50:58.061  3312  3370 I jxcore-log: 
,03-24 08:50:58.175  3312  3370 I jxcore-log: # setup
03-24 08:50:58.175  3312  3370 I jxcore-log: 
,03-24 08:50:58.300  3312  3370 I jxcore-log: # 76. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-24 08:50:58.300  3312  3370 I jxcore-log: 
,03-24 08:50:59.238  3312  3370 I jxcore-log: ok 280 Malformed encrypted beacon key ID
03-24 08:50:59.238  3312  3370 I jxcore-log: 
,03-24 08:50:59.241  3312  3370 I jxcore-log: # teardown
03-24 08:50:59.241  3312  3370 I jxcore-log: 
,03-24 08:50:59.835  3312  3370 I jxcore-log: # setup
03-24 08:50:59.835  3312  3370 I jxcore-log: 
,03-24 08:50:59.911  3312  3370 I jxcore-log: # 77. #parseBeacons addressBookCallback fails decrypt
03-24 08:50:59.911  3312  3370 I jxcore-log: 
,03-24 08:51:00.148  3312  3370 I jxcore-log: ok 281 should be equal
03-24 08:51:00.148  3312  3370 I jxcore-log: 
,03-24 08:51:00.151  3312  3370 I jxcore-log: # teardown
03-24 08:51:00.151  3312  3370 I jxcore-log: 
,03-24 08:51:00.337  3312  3370 I jxcore-log: # setup
03-24 08:51:00.337  3312  3370 I jxcore-log: 
,03-24 08:51:00.452  3312  3370 I jxcore-log: # 78. #parseBeacons addressBookCallback returns no matches
03-24 08:51:00.452  3312  3370 I jxcore-log: 
,03-24 08:51:00.625  3312  3370 I jxcore-log: ok 282 should be equal
03-24 08:51:00.625  3312  3370 I jxcore-log: 
,03-24 08:51:00.625  3312  3370 I jxcore-log: ok 283 should be equal
03-24 08:51:00.625  3312  3370 I jxcore-log: 
03-24 08:51:00.627  3312  3370 I jxcore-log: # teardown
03-24 08:51:00.627  3312  3370 I jxcore-log: 
,03-24 08:51:00.768  3312  3370 I jxcore-log: # setup
03-24 08:51:00.768  3312  3370 I jxcore-log: 
,03-24 08:51:00.925  3312  3370 I jxcore-log: # 79. #parseBeacons addressBookCallback returns spurious match
03-24 08:51:00.925  3312  3370 I jxcore-log: 
,03-24 08:51:01.177  3312  3370 I jxcore-log: ok 284 should be equal
03-24 08:51:01.177  3312  3370 I jxcore-log: 
,03-24 08:51:01.177  3312  3370 I jxcore-log: ok 285 should be equal
03-24 08:51:01.177  3312  3370 I jxcore-log: 
03-24 08:51:01.179  3312  3370 I jxcore-log: # teardown
03-24 08:51:01.179  3312  3370 I jxcore-log: 
,03-24 08:51:01.313  3312  3370 I jxcore-log: # setup
03-24 08:51:01.313  3312  3370 I jxcore-log: 
,03-24 08:51:01.406  3312  3370 I jxcore-log: # 80. #parseBeacons addressBookCallback returns public key
03-24 08:51:01.406  3312  3370 I jxcore-log: 
,03-24 08:51:01.674  3312  3370 I jxcore-log: ok 286 right number of calls to address book
03-24 08:51:01.674  3312  3370 I jxcore-log: 
03-24 08:51:01.674  3312  3370 I jxcore-log: ok 287 good preAmble
03-24 08:51:01.674  3312  3370 I jxcore-log: 
,03-24 08:51:01.674  3312  3370 I jxcore-log: ok 288 good unencryptedKeyId
03-24 08:51:01.674  3312  3370 I jxcore-log: 
03-24 08:51:01.674  3312  3370 I jxcore-log: ok 289 good beacon
03-24 08:51:01.674  3312  3370 I jxcore-log: 
03-24 08:51:01.677  3312  3370 I jxcore-log: # teardown
03-24 08:51:01.677  3312  3370 I jxcore-log: 
,03-24 08:51:01.823  3312  3370 I jxcore-log: # setup
03-24 08:51:01.823  3312  3370 I jxcore-log: 
,03-24 08:51:01.938  3312  3370 I jxcore-log: # 81. validate generatePskIdentityField
,03-24 08:51:01.938  3312  3370 I jxcore-log: 
,03-24 08:51:02.062  3312  3370 I jxcore-log: ok 290 decoded buffers match
03-24 08:51:02.062  3312  3370 I jxcore-log: 
,03-24 08:51:02.069  3312  3370 I jxcore-log: # teardown
03-24 08:51:02.069  3312  3370 I jxcore-log: 
,03-24 08:51:02.180  3312  3370 I jxcore-log: # setup
03-24 08:51:02.180  3312  3370 I jxcore-log: 
,03-24 08:51:02.313  3312  3370 I jxcore-log: # 82. validate generatePskSecret
03-24 08:51:02.313  3312  3370 I jxcore-log: 
,03-24 08:51:02.499  3312  3370 I jxcore-log: ok 291 secrets match
03-24 08:51:02.499  3312  3370 I jxcore-log: 
,03-24 08:51:02.501  3312  3370 I jxcore-log: # teardown
03-24 08:51:02.501  3312  3370 I jxcore-log: 
,03-24 08:51:02.628  3312  3370 I jxcore-log: # setup
,03-24 08:51:02.628  3312  3370 I jxcore-log: 
,03-24 08:51:02.805  3312  3370 I jxcore-log: # 83. Start and stop ThaliNotificationServer
03-24 08:51:02.805  3312  3370 I jxcore-log: 
,03-24 08:51:02.996  3312  3370 I jxcore-log: ok 292 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-24 08:51:02.996  3312  3370 I jxcore-log: 
,03-24 08:51:02.996  3312  3370 I jxcore-log: ok 293 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-24 08:51:02.996  3312  3370 I jxcore-log: 
03-24 08:51:02.998  3312  3370 I jxcore-log: # teardown
03-24 08:51:02.998  3312  3370 I jxcore-log: 
,03-24 08:51:03.120  3312  3370 I jxcore-log: # setup
03-24 08:51:03.120  3312  3370 I jxcore-log: 
,03-24 08:51:03.272  3312  3370 I jxcore-log: # 84. Pass an empty array to ThaliNotificationServer.start
03-24 08:51:03.272  3312  3370 I jxcore-log: 
,03-24 08:51:03.403  3312  3370 I jxcore-log: ok 294 StartUpdateAdvertisingAndListening should not be called
03-24 08:51:03.403  3312  3370 I jxcore-log: 
,03-24 08:51:03.418  3312  3370 I jxcore-log: ok 295 ThaliMobile.StopAdvertisingAndListening should be called once
03-24 08:51:03.418  3312  3370 I jxcore-log: 
,03-24 08:51:03.462  3312  3370 I jxcore-log: ok 296 no error
03-24 08:51:03.462  3312  3370 I jxcore-log: 
,03-24 08:51:03.462  3312  3370 I jxcore-log: ok 297 should be 204
03-24 08:51:03.462  3312  3370 I jxcore-log: 
,03-24 08:51:03.468  3312  3370 I jxcore-log: # teardown
03-24 08:51:03.468  3312  3370 I jxcore-log: 
,03-24 08:51:03.639  3312  3370 I jxcore-log: # setup
03-24 08:51:03.639  3312  3370 I jxcore-log: 
,03-24 08:51:03.867  3312  3370 I jxcore-log: # 85. Pass a string to ThaliNotificationServer.start
03-24 08:51:03.867  3312  3370 I jxcore-log: 
,03-24 08:51:04.000  3312  3370 I jxcore-log: ok 298 StartUpdateAdvertisingAndListening should not be called
03-24 08:51:04.000  3312  3370 I jxcore-log: 
,03-24 08:51:04.002  3312  3370 I jxcore-log: # teardown
03-24 08:51:04.002  3312  3370 I jxcore-log: 
,03-24 08:51:04.136  3312  3370 I jxcore-log: # setup
03-24 08:51:04.136  3312  3370 I jxcore-log: 
,03-24 08:51:04.307  3312  3370 I jxcore-log: # 86. Pass an empty parameter to ThaliNotificationServer.start
03-24 08:51:04.307  3312  3370 I jxcore-log: 
,03-24 08:51:04.420  3312  3370 I jxcore-log: ok 299 StartUpdateAdvertisingAndListening should not be called
03-24 08:51:04.420  3312  3370 I jxcore-log: 
,03-24 08:51:04.422  3312  3370 I jxcore-log: # teardown
03-24 08:51:04.422  3312  3370 I jxcore-log: 
,03-24 08:51:04.573  3312  3370 I jxcore-log: # setup
03-24 08:51:04.573  3312  3370 I jxcore-log: 
,03-24 08:51:04.750  3312  3370 I jxcore-log: # 87. Make an HTTP request to /NotificationBeacons
03-24 08:51:04.750  3312  3370 I jxcore-log: 
,03-24 08:51:04.985  3312  3370 I jxcore-log: ok 300 no error
03-24 08:51:04.985  3312  3370 I jxcore-log: 
,03-24 08:51:04.985  3312  3370 I jxcore-log: ok 301 should be 200
03-24 08:51:04.985  3312  3370 I jxcore-log: 
03-24 08:51:04.985  3312  3370 I jxcore-log: ok 302 should be equal
03-24 08:51:04.985  3312  3370 I jxcore-log: 
03-24 08:51:04.986  3312  3370 I jxcore-log: ok 303 should be equal
03-24 08:51:04.986  3312  3370 I jxcore-log: 
,03-24 08:51:05.002  3312  3370 I jxcore-log: ok 304 (unnamed assert)
03-24 08:51:05.002  3312  3370 I jxcore-log: 
,03-24 08:51:05.028  3312  3370 I jxcore-log: ok 305 no error
03-24 08:51:05.028  3312  3370 I jxcore-log: 
,03-24 08:51:05.028  3312  3370 I jxcore-log: ok 306 should be 204
03-24 08:51:05.028  3312  3370 I jxcore-log: 
03-24 08:51:05.032  3312  3370 I jxcore-log: # teardown
03-24 08:51:05.032  3312  3370 I jxcore-log: 
,03-24 08:51:05.245  3312  3370 I jxcore-log: # setup
03-24 08:51:05.245  3312  3370 I jxcore-log: 
,03-24 08:51:05.400  3312  3370 I jxcore-log: # 88. Make an HTTP request to /NotificationBeacons (no keys)
03-24 08:51:05.400  3312  3370 I jxcore-log: 
,03-24 08:51:05.441   825   844 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3b3b285b}
,03-24 08:51:05.447   825  1014 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.00 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 08:51:05.617  3312  3370 I jxcore-log: ok 307 error should be null
03-24 08:51:05.617  3312  3370 I jxcore-log: 
,03-24 08:51:05.618  3312  3370 I jxcore-log: ok 308 should be 204
03-24 08:51:05.618  3312  3370 I jxcore-log: 
03-24 08:51:05.624  3312  3370 I jxcore-log: # teardown
03-24 08:51:05.624  3312  3370 I jxcore-log: 
,03-24 08:51:05.890  3312  3370 I jxcore-log: # setup
03-24 08:51:05.890  3312  3370 I jxcore-log: 
,03-24 08:51:07.132   825  1186 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3b3b285b}
,03-24 08:51:07.201   825  1276 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 08:51:07.274   872   872 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,03-24 08:51:07.275   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 08:51:07.316   872   872 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-24 08:51:07.316   872   872 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 08:51:07.564  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:51:08.309   872   872 I kickstart: STATUS: Received file 'm9kefs2'
03-24 08:51:08.310   872   872 I kickstart: STATUS: 950272 bytes transferred in 0.992526 seconds
03-24 08:51:08.310   872   872 I kickstart: STATUS: Successfully downloaded files from target 
03-24 08:51:08.310   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 08:51:08.313   872   872 I kickstart: STATUS: Sahara protocol completed
,03-24 08:51:08.574  3312  3370 I jxcore-log: # 89. Make an HTTP request to /NotificationBeaconsbefore calling start
03-24 08:51:08.574  3312  3370 I jxcore-log: 
,03-24 08:51:08.729  3312  3370 I jxcore-log: ok 309 should be 404
03-24 08:51:08.729  3312  3370 I jxcore-log: 
,03-24 08:51:08.735  3312  3370 I jxcore-log: # teardown
03-24 08:51:08.735  3312  3370 I jxcore-log: 
,03-24 08:51:09.570  3312  3370 I jxcore-log: # setup
03-24 08:51:09.570  3312  3370 I jxcore-log: 
,03-24 08:51:09.670  3312  3370 I jxcore-log: # 90. #testThaliPeerAction - test getters
03-24 08:51:09.670  3312  3370 I jxcore-log: 
,03-24 08:51:10.171  3312  3370 I jxcore-log: ok 310 getPeerIdentifier
03-24 08:51:10.171  3312  3370 I jxcore-log: 
03-24 08:51:10.173  3312  3370 I jxcore-log: ok 311 getConnectionType
03-24 08:51:10.173  3312  3370 I jxcore-log: 
03-24 08:51:10.174  3312  3370 I jxcore-log: ok 312 getActionType
03-24 08:51:10.174  3312  3370 I jxcore-log: 
03-24 08:51:10.176  3312  3370 I jxcore-log: ok 313 getActionState
03-24 08:51:10.176  3312  3370 I jxcore-log: 
,03-24 08:51:10.186  3312  3370 I jxcore-log: # teardown,
03-24 08:51:10.186  3312  3370 I jxcore-log: 
,03-24 08:51:10.266  3312  3370 I jxcore-log: # setup,
03-24 08:51:10.266  3312  3370 I jxcore-log: 
,03-24 08:51:10.356  3312  3370 I jxcore-log: # 91. #testThaliPeerAction - start and kill
03-24 08:51:10.356  3312  3370 I jxcore-log: 
,03-24 08:51:10.462  3312  3370 I jxcore-log: ok 314 initial state
03-24 08:51:10.462  3312  3370 I jxcore-log: 
,03-24 08:51:10.469  3312  3370 I jxcore-log: ok 315 after start
03-24 08:51:10.469  3312  3370 I jxcore-log: 
,03-24 08:51:10.469  3312  3370 I jxcore-log: ok 316 after kill,
03-24 08:51:10.469  3312  3370 I jxcore-log: 
03-24 08:51:10.471  3312  3370 I jxcore-log: # teardown
03-24 08:51:10.471  3312  3370 I jxcore-log: 
,03-24 08:51:10.595  3312  3370 I jxcore-log: # setup
03-24 08:51:10.595  3312  3370 I jxcore-log: 
,03-24 08:51:10.706  3312  3370 I jxcore-log: # 92. #testThaliPeerAction - double start
03-24 08:51:10.706  3312  3370 I jxcore-log: 
,03-24 08:51:10.835  3312  3370 I jxcore-log: ok 317 should be equal
03-24 08:51:10.835  3312  3370 I jxcore-log: 
,03-24 08:51:10.841  3312  3370 I jxcore-log: # teardown
03-24 08:51:10.841  3312  3370 I jxcore-log: 
,03-24 08:51:10.945  3312  3370 I jxcore-log: # setup
03-24 08:51:10.945  3312  3370 I jxcore-log: 
,03-24 08:51:11.046  3312  3370 I jxcore-log: # 93. #testThaliPeerAction - start after kill
03-24 08:51:11.046  3312  3370 I jxcore-log: 
,03-24 08:51:11.160  3312  3370 I jxcore-log: ok 318 clean kill
03-24 08:51:11.160  3312  3370 I jxcore-log: 
,03-24 08:51:11.169  3312  3370 I jxcore-log: ok 319 should be equal
03-24 08:51:11.169  3312  3370 I jxcore-log: 
,03-24 08:51:11.171  3312  3370 I jxcore-log: # teardown
03-24 08:51:11.171  3312  3370 I jxcore-log: 
,03-24 08:51:11.251  3312  3370 I jxcore-log: # setup
03-24 08:51:11.251  3312  3370 I jxcore-log: 
,03-24 08:51:11.363  3312  3370 I jxcore-log: # 94. #testThaliPeerAction - make sure ids are unique
03-24 08:51:11.363  3312  3370 I jxcore-log: 
,03-24 08:51:11.508  3312  3370 I jxcore-log: ok 320 should not be equal
03-24 08:51:11.508  3312  3370 I jxcore-log: 
,03-24 08:51:11.511  3312  3370 I jxcore-log: # teardown
03-24 08:51:11.511  3312  3370 I jxcore-log: 
,03-24 08:51:11.646  3312  3370 I jxcore-log: # setup
03-24 08:51:11.646  3312  3370 I jxcore-log: 
,03-24 08:51:11.753  3312  3370 I jxcore-log: # 95. Test PeerConnectionInformation basics
03-24 08:51:11.753  3312  3370 I jxcore-log: 
,03-24 08:51:11.851  3312  3370 I jxcore-log: ok 321 getHostAddress works,
03-24 08:51:11.851  3312  3370 I jxcore-log: 
,03-24 08:51:11.853  3312  3370 I jxcore-log: ok 322 getPortNumber works,
03-24 08:51:11.853  3312  3370 I jxcore-log: 
03-24 08:51:11.854  3312  3370 I jxcore-log: ok 323 getSuggestedTCPTimeout works
,03-24 08:51:11.854  3312  3370 I jxcore-log: 
03-24 08:51:11.861  3312  3370 I jxcore-log: # teardown
,03-24 08:51:11.861  3312  3370 I jxcore-log: 
,03-24 08:51:11.969  3312  3370 I jxcore-log: # setup
03-24 08:51:11.969  3312  3370 I jxcore-log: 
,03-24 08:51:12.179  3312  3370 I jxcore-log: # 96. Test PeerDictionary basic functionality
03-24 08:51:12.179  3312  3370 I jxcore-log: 
,03-24 08:51:12.321  3312  3370 I jxcore-log: ok 324 Entry counter must be 1
03-24 08:51:12.321  3312  3370 I jxcore-log: 
03-24 08:51:12.321  3312  3370 I jxcore-log: ok 325 Size must be 1
03-24 08:51:12.321  3312  3370 I jxcore-log: 
03-24 08:51:12.322  3312  3370 I jxcore-log: ok 326 Entry counter must be 2
03-24 08:51:12.322  3312  3370 I jxcore-log: 
03-24 08:51:12.322  3312  3370 I jxcore-log: ok 327 Size must be 2
03-24 08:51:12.322  3312  3370 I jxcore-log: 
03-24 08:51:12.326  3312  3370 I jxcore-log: ok 328 Entry2 should not be found
03-24 08:51:12.326  3312  3370 I jxcore-log: 
,03-24 08:51:12.329  3312  3370 I jxcore-log: ok 329 Size must be 1
03-24 08:51:12.329  3312  3370 I jxcore-log: 
03-24 08:51:12.329  3312  3370 I jxcore-log: ok 330 Size must be 0
03-24 08:51:12.329  3312  3370 I jxcore-log: 
,03-24 08:51:12.333  3312  3370 I jxcore-log: ok 331 entry not found must be thrown
03-24 08:51:12.333  3312  3370 I jxcore-log: 
,03-24 08:51:12.336  3312  3370 I jxcore-log: # teardown
03-24 08:51:12.336  3312  3370 I jxcore-log: 
,03-24 08:51:12.506  3312  3370 I jxcore-log: # setup
03-24 08:51:12.506  3312  3370 I jxcore-log: 
,03-24 08:51:12.622  3312  3370 I jxcore-log: # 97. Test PeerDictionary with multiple entries.
03-24 08:51:12.622  3312  3370 I jxcore-log: 
,03-24 08:51:13.448  3312  3370 I jxcore-log: ok 332 Size must be100
03-24 08:51:13.448  3312  3370 I jxcore-log: 
,03-24 08:51:13.450  3312  3370 I jxcore-log: ok 333 Entries between 20 and MAXSIZE + 20 should exist
03-24 08:51:13.450  3312  3370 I jxcore-log: 
,03-24 08:51:14.162  3312  3370 I jxcore-log: ok 334 WAITING state entry should not be removed
03-24 08:51:14.162  3312  3370 I jxcore-log: 
,03-24 08:51:14.164  3312  3370 I jxcore-log: # teardown
03-24 08:51:14.164  3312  3370 I jxcore-log: 
,03-24 08:51:14.253  3312  3370 I jxcore-log: # setup
03-24 08:51:14.253  3312  3370 I jxcore-log: 
,03-24 08:51:14.379  3312  3370 I jxcore-log: # 98. RESOLVED entries are removed before WAITING state entry.
03-24 08:51:14.379  3312  3370 I jxcore-log: 
,03-24 08:51:15.141  3312  3370 I jxcore-log: ok 335 Entries between 6 and MAXSIZE + 4 should exist
03-24 08:51:15.141  3312  3370 I jxcore-log: 
,03-24 08:51:15.141  3312  3370 I jxcore-log: ok 336 Size should be MAXSIZE
03-24 08:51:15.141  3312  3370 I jxcore-log: 
,03-24 08:51:15.141  3312  3370 I jxcore-log: ok 337 Size should be MAXSIZE+6
03-24 08:51:15.141  3312  3370 I jxcore-log: 
03-24 08:51:15.143  3312  3370 I jxcore-log: # teardown
03-24 08:51:15.143  3312  3370 I jxcore-log: 
,03-24 08:51:15.703  3312  3370 I jxcore-log: # setup
03-24 08:51:15.703  3312  3370 I jxcore-log: 
,03-24 08:51:15.819  3312  3370 I jxcore-log: # 99. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-24 08:51:15.819  3312  3370 I jxcore-log: 
,03-24 08:51:16.541  3312  3370 I jxcore-log: ok 338 WAITING state entry should not be removed
03-24 08:51:16.541  3312  3370 I jxcore-log: 
,03-24 08:51:16.543  3312  3370 I jxcore-log: ok 339 Waiting entries between 6 and MAXSIZE + 4 should exist
03-24 08:51:16.543  3312  3370 I jxcore-log: 
03-24 08:51:16.543  3312  3370 I jxcore-log: ok 340 Size should be MAXSIZE
03-24 08:51:16.543  3312  3370 I jxcore-log: 
,03-24 08:51:16.543  3312  3370 I jxcore-log: ok 341 entryCounter should be MAXSIZE+6
03-24 08:51:16.543  3312  3370 I jxcore-log: 
,03-24 08:51:16.546  3312  3370 I jxcore-log: # teardown
03-24 08:51:16.546  3312  3370 I jxcore-log: 
,03-24 08:51:17.481  3312  3370 I jxcore-log: # setup
03-24 08:51:17.481  3312  3370 I jxcore-log: 
,03-24 08:51:18.060  3312  3370 I jxcore-log: # 100. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-24 08:51:18.060  3312  3370 I jxcore-log: 
,03-24 08:51:19.234  3312  3370 I jxcore-log: ok 342 Kill should be called once
03-24 08:51:19.234  3312  3370 I jxcore-log: 
,03-24 08:51:19.234  3312  3370 I jxcore-log: ok 343 Size should be 100
03-24 08:51:19.234  3312  3370 I jxcore-log: 
,03-24 08:51:19.237  3312  3370 I jxcore-log: # teardown
03-24 08:51:19.237  3312  3370 I jxcore-log: 
,03-24 08:51:19.328  3312  3370 I jxcore-log: # setup
03-24 08:51:19.328  3312  3370 I jxcore-log: 
,03-24 08:51:19.460  3312  3370 I jxcore-log: # 101. #ThaliPeerPoolInterface - bad enqueues
03-24 08:51:19.460  3312  3370 I jxcore-log: 
,03-24 08:51:19.565  3312  3370 I jxcore-log: ok 344 null arg
03-24 08:51:19.565  3312  3370 I jxcore-log: 
,03-24 08:51:19.572  3312  3370 I jxcore-log: ok 345 wrong arg type
03-24 08:51:19.572  3312  3370 I jxcore-log: 
,03-24 08:51:19.579  3312  3370 I jxcore-log: ok 346 wrong state
03-24 08:51:19.579  3312  3370 I jxcore-log: 
,03-24 08:51:19.582  3312  3370 I jxcore-log: # teardown
03-24 08:51:19.582  3312  3370 I jxcore-log: 
,03-24 08:51:19.667  3312  3370 I jxcore-log: # setup
03-24 08:51:19.667  3312  3370 I jxcore-log: 
,03-24 08:51:19.782  3312  3370 I jxcore-log: # 102. #ThaliPeerPoolInterface - do not allow same object type
03-24 08:51:19.782  3312  3370 I jxcore-log: 
,03-24 08:51:19.910  3312  3370 I jxcore-log: ok 347 good enqueue
03-24 08:51:19.910  3312  3370 I jxcore-log: 
,03-24 08:51:19.917  3312  3370 I jxcore-log: ok 348 should be equal
03-24 08:51:19.917  3312  3370 I jxcore-log: 
,03-24 08:51:19.921  3312  3370 I jxcore-log: # teardown
03-24 08:51:19.921  3312  3370 I jxcore-log: 
,03-24 08:51:20.040  3312  3370 I jxcore-log: # setup
03-24 08:51:20.040  3312  3370 I jxcore-log: 
,03-24 08:51:20.139  3312  3370 I jxcore-log: # 103. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-24 08:51:20.139  3312  3370 I jxcore-log: 
,03-24 08:51:20.301  3312  3370 I jxcore-log: ok 349 good enqueue
03-24 08:51:20.301  3312  3370 I jxcore-log: 
,03-24 08:51:20.301  3312  3370 I jxcore-log: ok 350 2nd good enqueue
03-24 08:51:20.301  3312  3370 I jxcore-log: 
,03-24 08:51:20.302  3312  3370 I jxcore-log: ok 351 we are in the pool
03-24 08:51:20.302  3312  3370 I jxcore-log: 
,03-24 08:51:20.306  3312  3370 I jxcore-log: ok 352 We are out of the pool
03-24 08:51:20.306  3312  3370 I jxcore-log: 
,03-24 08:51:20.307  3312  3370 I jxcore-log: ok 353 Action was killed
03-24 08:51:20.307  3312  3370 I jxcore-log: 
03-24 08:51:20.307  3312  3370 I jxcore-log: ok 354 The original kill was called too
03-24 08:51:20.307  3312  3370 I jxcore-log: 
03-24 08:51:20.308  3312  3370 I jxcore-log: ok 355 second item is still in queue
03-24 08:51:20.308  3312  3370 I jxcore-log: 
,03-24 08:51:20.311  3312  3370 I jxcore-log: # teardown
03-24 08:51:20.311  3312  3370 I jxcore-log: 
,03-24 08:51:20.418  3312  3370 I jxcore-log: # setup
03-24 08:51:20.418  3312  3370 I jxcore-log: 
,03-24 08:51:20.506  3312  3370 I jxcore-log: # 104. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-24 08:51:20.506  3312  3370 I jxcore-log: 
,03-24 08:51:20.603  3312  3370 I jxcore-log: ok 356 good enqueue
03-24 08:51:20.603  3312  3370 I jxcore-log: 
,03-24 08:51:20.605  3312  3370 I jxcore-log: ok 357 first kill
03-24 08:51:20.605  3312  3370 I jxcore-log: 
,03-24 08:51:20.608  3312  3370 I jxcore-log: ok 358 second NOOP kill
03-24 08:51:20.608  3312  3370 I jxcore-log: 
,03-24 08:51:20.618  3312  3370 I jxcore-log: # teardown
03-24 08:51:20.618  3312  3370 I jxcore-log: 
,03-24 08:51:20.712  3312  3370 I jxcore-log: # setup
03-24 08:51:20.712  3312  3370 I jxcore-log: ,
,03-24 08:51:20.802  3312  3370 I jxcore-log: # 105. compareBufferArrays
03-24 08:51:20.802  3312  3370 I jxcore-log: 
,03-24 08:51:20.968  3312  3370 I jxcore-log: ok 359 should throw
03-24 08:51:20.968  3312  3370 I jxcore-log: 
03-24 08:51:20.970  3312  3370 I jxcore-log: ok 360 should throw
03-24 08:51:20.970  3312  3370 I jxcore-log: 
,03-24 08:51:20.971  3312  3370 I jxcore-log: ok 361 (unnamed assert)
03-24 08:51:20.971  3312  3370 I jxcore-log: 
03-24 08:51:20.971  3312  3370 I jxcore-log: ok 362 (unnamed assert)
03-24 08:51:20.971  3312  3370 I jxcore-log: 
03-24 08:51:20.971  3312  3370 I jxcore-log: ok 363 (unnamed assert)
03-24 08:51:20.971  3312  3370 I jxcore-log: 
03-24 08:51:20.972  3312  3370 I jxcore-log: ok 364 (unnamed assert)
03-24 08:51:20.972  3312  3370 I jxcore-log: 
,03-24 08:51:20.973  3312  3370 I jxcore-log: ok 365 (unnamed assert)
03-24 08:51:20.973  3312  3370 I jxcore-log: 
03-24 08:51:20.975  3312  3370 I jxcore-log: # teardown
03-24 08:51:20.975  3312  3370 I jxcore-log: 
,03-24 08:51:21.086  3312  3370 I jxcore-log: # setup
03-24 08:51:21.086  3312  3370 I jxcore-log: 
,03-24 08:51:21.234  3312  3370 I jxcore-log: # 106. Call start twice and get error
03-24 08:51:21.234  3312  3370 I jxcore-log: 
,03-24 08:51:21.369  3312  3370 I jxcore-log: ok 366 should throw
03-24 08:51:21.369  3312  3370 I jxcore-log: 
,03-24 08:51:21.371  3312  3370 I jxcore-log: # teardown
03-24 08:51:21.371  3312  3370 I jxcore-log: 
,03-24 08:51:21.515  3312  3370 I jxcore-log: # setup
03-24 08:51:21.515  3312  3370 I jxcore-log: 
,03-24 08:51:21.635  3312  3370 I jxcore-log: # 107. Start and make sure it runs
03-24 08:51:21.635  3312  3370 I jxcore-log: 
,03-24 08:51:21.791  3312  3370 I jxcore-log: # teardown
03-24 08:51:21.791  3312  3370 I jxcore-log: 
,03-24 08:51:21.923  3312  3370 I jxcore-log: # setup
03-24 08:51:21.923  3312  3370 I jxcore-log: 
,03-24 08:51:22.052  3312  3370 I jxcore-log: # 108. Make sure getTimeWhenRun is right after start
03-24 08:51:22.052  3312  3370 I jxcore-log: 
,03-24 08:51:22.174  3312  3370 I jxcore-log: ok 367 (unnamed assert)
03-24 08:51:22.174  3312  3370 I jxcore-log: 
,03-24 08:51:22.182  3312  3370 I jxcore-log: # teardown
03-24 08:51:22.182  3312  3370 I jxcore-log: 
,03-24 08:51:22.378  3312  3370 I jxcore-log: # setup
03-24 08:51:22.378  3312  3370 I jxcore-log: 
,03-24 08:51:22.500  3312  3370 I jxcore-log: # 109. Make sure getTimeWhenRun is -1 after function is called
03-24 08:51:22.500  3312  3370 I jxcore-log: 
,03-24 08:51:22.598  3312  3370 I jxcore-log: ok 368 should be equal
03-24 08:51:22.598  3312  3370 I jxcore-log: 
,03-24 08:51:22.611  3312  3370 I jxcore-log: # teardown
03-24 08:51:22.611  3312  3370 I jxcore-log: 
,03-24 08:51:22.689  3312  3370 I jxcore-log: # setup
03-24 08:51:22.689  3312  3370 I jxcore-log: 
,03-24 08:51:22.762  3312  3370 I jxcore-log: # 110. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-24 08:51:22.762  3312  3370 I jxcore-log: 
,03-24 08:51:22.866  3312  3370 I jxcore-log: ok 369 should be equal
03-24 08:51:22.866  3312  3370 I jxcore-log: 
,03-24 08:51:22.868  3312  3370 I jxcore-log: ok 370 should be equal
03-24 08:51:22.868  3312  3370 I jxcore-log: 
,03-24 08:51:22.876  3312  3370 I jxcore-log: ok 371 should throw
03-24 08:51:22.876  3312  3370 I jxcore-log: 
,03-24 08:51:22.881  3312  3370 I jxcore-log: # teardown
03-24 08:51:22.881  3312  3370 I jxcore-log: 
,03-24 08:51:23.018  3312  3370 I jxcore-log: # setup
03-24 08:51:23.018  3312  3370 I jxcore-log: 
,03-24 08:51:23.153  3312  3370 I jxcore-log: # 111. Test TransientState
03-24 08:51:23.153  3312  3370 I jxcore-log: 
,03-24 08:51:23.300  3312  3370 I jxcore-log: ok 372 should throw
03-24 08:51:23.300  3312  3370 I jxcore-log: 
,03-24 08:51:23.302  3312  3370 I jxcore-log: ok 373 should throw
03-24 08:51:23.302  3312  3370 I jxcore-log: 
,03-24 08:51:23.302  3312  3370 I jxcore-log: ok 374 should be equal
03-24 08:51:23.302  3312  3370 I jxcore-log: 
03-24 08:51:23.303  3312  3370 I jxcore-log: ok 375 should be equal
03-24 08:51:23.303  3312  3370 I jxcore-log: 
,03-24 08:51:23.303  3312  3370 I jxcore-log: ok 376 should be equal
03-24 08:51:23.303  3312  3370 I jxcore-log: 
,03-24 08:51:23.303  3312  3370 I jxcore-log: ok 377 should be equal
03-24 08:51:23.303  3312  3370 I jxcore-log: 
03-24 08:51:23.304  3312  3370 I jxcore-log: ok 378 (unnamed assert)
03-24 08:51:23.304  3312  3370 I jxcore-log: 
,03-24 08:51:23.305  3312  3370 I jxcore-log: ok 379 (unnamed assert)
03-24 08:51:23.305  3312  3370 I jxcore-log: 
03-24 08:51:23.308  3312  3370 I jxcore-log: # teardown
03-24 08:51:23.308  3312  3370 I jxcore-log: 
,03-24 08:51:23.457  3312  3370 I jxcore-log: # setup
03-24 08:51:23.457  3312  3370 I jxcore-log: 
,03-24 08:51:23.647  3312  3370 I jxcore-log: # 112. No peers and empty database
03-24 08:51:23.647  3312  3370 I jxcore-log: 
,03-24 08:51:23.881  3312  3370 I jxcore-log: ok 380 verify failed
03-24 08:51:23.881  3312  3370 I jxcore-log: 
03-24 08:51:23.882  3312  3370 I jxcore-log: ok 381 constructor called once
03-24 08:51:23.882  3312  3370 I jxcore-log: 
03-24 08:51:23.883  3312  3370 I jxcore-log: ok 382 constructor called with right args
03-24 08:51:23.883  3312  3370 I jxcore-log: 
03-24 08:51:23.883  3312  3370 I jxcore-log: ok 383 match start arg
03-24 08:51:23.883  3312  3370 I jxcore-log: 
,03-24 08:51:23.883  3312  3370 I jxcore-log: ok 384 start called once
03-24 08:51:23.883  3312  3370 I jxcore-log: 
,03-24 08:51:23.883  3312  3370 I jxcore-log: ok 385 stop called once
03-24 08:51:23.883  3312  3370 I jxcore-log: 
03-24 08:51:23.884  3312  3370 I jxcore-log: ok 386 stop after start
03-24 08:51:23.884  3312  3370 I jxcore-log: 
03-24 08:51:23.888  3312  3370 I jxcore-log: # teardown
03-24 08:51:23.888  3312  3370 I jxcore-log: 
,03-24 08:51:24.103  3312  3370 I jxcore-log: # setup
03-24 08:51:24.103  3312  3370 I jxcore-log: 
,03-24 08:51:27.889  3312  3370 I jxcore-log: # 113. One peer and empty DB
03-24 08:51:27.889  3312  3370 I jxcore-log: 
,03-24 08:51:28.181  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:28.181  3312  3370 I jxcore-log: 
03-24 08:51:28.183  3312  3370 I jxcore-log: ok 387 verify failed
03-24 08:51:28.183  3312  3370 I jxcore-log: 
03-24 08:51:28.183  3312  3370 I jxcore-log: ok 388 constructor called once,
03-24 08:51:28.183  3312  3370 I jxcore-log: 
03-24 08:51:28.184  3312  3370 I jxcore-log: ok 389 constructor called with right args
03-24 08:51:28.184  3312  3370 I jxcore-log: 
03-24 08:51:28.184  3312  3370 I jxcore-log: ok 390 match start arg
03-24 08:51:28.184  3312  3370 I jxcore-log: 
03-24 08:51:28.185  3312  3370 I jxcore-log: ok 391 start called once
03-24 08:51:28.185  3312  3370 I jxcore-log: 
,03-24 08:51:28.185  3312  3370 I jxcore-log: ok 392 stop called once
03-24 08:51:28.185  3312  3370 I jxcore-log: 
03-24 08:51:28.185  3312  3370 I jxcore-log: ok 393 stop after start
03-24 08:51:28.185  3312  3370 I jxcore-log: 
03-24 08:51:28.190  3312  3370 I jxcore-log: # teardown
03-24 08:51:28.190  3312  3370 I jxcore-log: 
,03-24 08:51:28.510  3312  3370 I jxcore-log: # setup
03-24 08:51:28.510  3312  3370 I jxcore-log: 
,03-24 08:51:28.600  3312  3370 I jxcore-log: # 114. One peer with _Local set behind current seq
03-24 08:51:28.600  3312  3370 I jxcore-log: 
,03-24 08:51:28.912  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 08:51:28.912  3312  3370 I jxcore-log: 
03-24 08:51:28.914  3312  3370 I jxcore-log: ok 394 verify failed
03-24 08:51:28.914  3312  3370 I jxcore-log: 
,03-24 08:51:28.915  3312  3370 I jxcore-log: ok 395 constructor called once,
,03-24 08:51:28.915  3312  3370 I jxcore-log: 
03-24 08:51:28.916  3312  3370 I jxcore-log: ok 396 constructor called with right args
03-24 08:51:28.916  3312  3370 I jxcore-log: ,
03-24 08:51:28.917  3312  3370 I jxcore-log: ok 397 match start arg
03-24 08:51:28.917  3312  3370 I jxcore-log: 
,03-24 08:51:28.917  3312  3370 I jxcore-log: ok 398 start called once
03-24 08:51:28.917  3312  3370 I jxcore-log: 
03-24 08:51:28.918  3312  3370 I jxcore-log: ok 399 stop called once
03-24 08:51:28.918  3312  3370 I jxcore-log: 
03-24 08:51:28.918  3312  3370 I jxcore-log: ok 400 stop after start
,03-24 08:51:28.918  3312  3370 I jxcore-log: 
03-24 08:51:28.923  3312  3370 I jxcore-log: # teardown
03-24 08:51:28.923  3312  3370 I jxcore-log: 
,03-24 08:51:29.062  3312  3370 I jxcore-log: # setup,
03-24 08:51:29.062  3312  3370 I jxcore-log: 
,03-24 08:51:29.417  3312  3370 I jxcore-log: # 115. One peer with _Local set equal to current seq,
03-24 08:51:29.417  3312  3370 I jxcore-log: 
,03-24 08:51:29.711  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 08:51:29.711  3312  3370 I jxcore-log: 
03-24 08:51:29.712  3312  3370 I jxcore-log: ok 401 verify failed
03-24 08:51:29.712  3312  3370 I jxcore-log: 
,03-24 08:51:29.713  3312  3370 I jxcore-log: ok 402 constructor called once,
03-24 08:51:29.713  3312  3370 I jxcore-log: 
03-24 08:51:29.713  3312  3370 I jxcore-log: ok 403 constructor called with right args,
03-24 08:51:29.713  3312  3370 I jxcore-log: 
03-24 08:51:29.714  3312  3370 I jxcore-log: ok 404 match start arg
,03-24 08:51:29.714  3312  3370 I jxcore-log: 
03-24 08:51:29.714  3312  3370 I jxcore-log: ok 405 start called once
,03-24 08:51:29.714  3312  3370 I jxcore-log: 
03-24 08:51:29.714  3312  3370 I jxcore-log: ok 406 stop called once
,03-24 08:51:29.714  3312  3370 I jxcore-log: 
03-24 08:51:29.715  3312  3370 I jxcore-log: ok 407 stop after start
03-24 08:51:29.715  3312  3370 I jxcore-log: 
,03-24 08:51:29.719  3312  3370 I jxcore-log: # teardown
03-24 08:51:29.719  3312  3370 I jxcore-log: 
,03-24 08:51:29.851  3312  3370 I jxcore-log: # setup
03-24 08:51:29.851  3312  3370 I jxcore-log: 
,03-24 08:51:29.955  3312  3370 I jxcore-log: # 116. One peer with _Local set ahead of current seq (and no this should not happen)
03-24 08:51:29.955  3312  3370 I jxcore-log: 
,03-24 08:51:30.280  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:30.280  3312  3370 I jxcore-log: 
03-24 08:51:30.282  3312  3370 I jxcore-log: ok 408 verify failed
03-24 08:51:30.282  3312  3370 I jxcore-log: 
03-24 08:51:30.282  3312  3370 I jxcore-log: ok 409 constructor called once
03-24 08:51:30.282  3312  3370 I jxcore-log: 
03-24 08:51:30.283  3312  3370 I jxcore-log: ok 410 constructor called with right args
03-24 08:51:30.283  3312  3370 I jxcore-log: 
03-24 08:51:30.283  3312  3370 I jxcore-log: ok 411 match start arg
03-24 08:51:30.283  3312  3370 I jxcore-log: 
03-24 08:51:30.284  3312  3370 I jxcore-log: ok 412 start called once
03-24 08:51:30.284  3312  3370 I jxcore-log: 
03-24 08:51:30.284  3312  3370 I jxcore-log: ok 413 stop called once
03-24 08:51:30.284  3312  3370 I jxcore-log: 
03-24 08:51:30.284  3312  3370 I jxcore-log: ok 414 stop after start
03-24 08:51:30.284  3312  3370 I jxcore-log: 
03-24 08:51:30.290  3312  3370 I jxcore-log: # teardown
03-24 08:51:30.290  3312  3370 I jxcore-log: 
,03-24 08:51:30.958  3312  3370 I jxcore-log: # setup
03-24 08:51:30.958  3312  3370 I jxcore-log: 
,03-24 08:51:31.178  3312  3370 I jxcore-log: # 117. Three peers, one not in DB, one behind and one ahead
03-24 08:51:31.178  3312  3370 I jxcore-log: 
,03-24 08:51:31.765  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:31.765  3312  3370 I jxcore-log: 
,03-24 08:51:31.769  3312  3370 I jxcore-log: ok 415 verify failed
03-24 08:51:31.769  3312  3370 I jxcore-log: 
,03-24 08:51:31.769  3312  3370 I jxcore-log: ok 416 constructor called once
03-24 08:51:31.769  3312  3370 I jxcore-log: 
03-24 08:51:31.770  3312  3370 I jxcore-log: ok 417 constructor called with right args
03-24 08:51:31.770  3312  3370 I jxcore-log: 
,03-24 08:51:31.771  3312  3370 I jxcore-log: ok 418 match start arg
03-24 08:51:31.771  3312  3370 I jxcore-log: 
03-24 08:51:31.771  3312  3370 I jxcore-log: ok 419 start called once
03-24 08:51:31.771  3312  3370 I jxcore-log: 
,03-24 08:51:31.771  3312  3370 I jxcore-log: ok 420 stop called once
03-24 08:51:31.771  3312  3370 I jxcore-log: 
,03-24 08:51:31.772  3312  3370 I jxcore-log: ok 421 stop after start
03-24 08:51:31.772  3312  3370 I jxcore-log: 
,03-24 08:51:31.778  3312  3370 I jxcore-log: # teardown
03-24 08:51:31.778  3312  3370 I jxcore-log: 
,03-24 08:51:31.880  3312  3370 I jxcore-log: # setup
03-24 08:51:31.880  3312  3370 I jxcore-log: 
,03-24 08:51:32.249  3312  3370 I jxcore-log: # 118. More than maximum peers, make sure we only send maximum allowed
03-24 08:51:32.249  3312  3370 I jxcore-log: 
,03-24 08:51:33.509  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:33.509  3312  3370 I jxcore-log: 
,03-24 08:51:33.511  3312  3370 I jxcore-log: ok 422 verify failed
03-24 08:51:33.511  3312  3370 I jxcore-log: 
03-24 08:51:33.511  3312  3370 I jxcore-log: ok 423 constructor called once
03-24 08:51:33.511  3312  3370 I jxcore-log: 
03-24 08:51:33.512  3312  3370 I jxcore-log: ok 424 constructor called with right args
03-24 08:51:33.512  3312  3370 I jxcore-log: 
03-24 08:51:33.512  3312  3370 I jxcore-log: ok 425 match start arg
03-24 08:51:33.512  3312  3370 I jxcore-log: 
,03-24 08:51:33.512  3312  3370 I jxcore-log: ok 426 start called once
03-24 08:51:33.512  3312  3370 I jxcore-log: 
03-24 08:51:33.513  3312  3370 I jxcore-log: ok 427 stop called once
03-24 08:51:33.513  3312  3370 I jxcore-log: 
03-24 08:51:33.513  3312  3370 I jxcore-log: ok 428 stop after start
03-24 08:51:33.513  3312  3370 I jxcore-log: 
,03-24 08:51:33.518  3312  3370 I jxcore-log: # teardown
03-24 08:51:33.518  3312  3370 I jxcore-log: 
,03-24 08:51:34.699  3425  3929 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 08:51:34.738  3312  3370 I jxcore-log: # setup
03-24 08:51:34.738  3312  3370 I jxcore-log: 
,03-24 08:51:34.780  1258  3765 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 08:51:34.780  1258  3765 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 08:51:34.781  1258  3765 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 08:51:34.781  1258  3765 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 08:51:34.789  1258  3765 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 08:51:34.809  3312  3370 I jxcore-log: # 119. two peers with empty DB, update the doc
03-24 08:51:34.809  3312  3370 I jxcore-log: 
,03-24 08:51:34.825  3425  3929 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 08:51:34.826  3425  3929 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 08:51:35.564  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:35.564  3312  3370 I jxcore-log: 
,03-24 08:51:35.604  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:35.604  3312  3370 I jxcore-log: 
,03-24 08:51:35.605  3312  3370 I jxcore-log: ok 429 verify failed
03-24 08:51:35.605  3312  3370 I jxcore-log: 
,03-24 08:51:35.605  3312  3370 I jxcore-log: ok 430 constructor called once
03-24 08:51:35.605  3312  3370 I jxcore-log: 
,03-24 08:51:35.606  3312  3370 I jxcore-log: ok 431 constructor called with right args
03-24 08:51:35.606  3312  3370 I jxcore-log: 
,03-24 08:51:35.606  3312  3370 I jxcore-log: ok 432 last start before stop
03-24 08:51:35.606  3312  3370 I jxcore-log: 
03-24 08:51:35.607  3312  3370 I jxcore-log: ok 433 empty first start
03-24 08:51:35.607  3312  3370 I jxcore-log: 
,03-24 08:51:35.608  3312  3370 I jxcore-log: ok 434 full second start
03-24 08:51:35.608  3312  3370 I jxcore-log: 
03-24 08:51:35.608  3312  3370 I jxcore-log: ok 435 only 2 timers
03-24 08:51:35.608  3312  3370 I jxcore-log: 
03-24 08:51:35.617  3312  3370 I jxcore-log: # teardown
03-24 08:51:35.617  3312  3370 I jxcore-log: 
,03-24 08:51:35.689  3312  3370 I jxcore-log: # setup
03-24 08:51:35.689  3312  3370 I jxcore-log: 
,03-24 08:51:35.849  3312  3370 I jxcore-log: # 120. add doc and make sure tokens refresh when they expire
,03-24 08:51:35.849  3312  3370 I jxcore-log: 
,03-24 08:51:36.230  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 08:51:36.230  3312  3370 I jxcore-log: 
,03-24 08:51:36.349  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,03-24 08:51:36.349  3312  3370 I jxcore-log: 
,03-24 08:51:36.460  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:36.460  3312  3370 I jxcore-log: 
,03-24 08:51:36.469  3312  3370 I jxcore-log: ok 436 verify failed
03-24 08:51:36.469  3312  3370 I jxcore-log: 
,03-24 08:51:36.470  3312  3370 I jxcore-log: ok 437 constructor called once
03-24 08:51:36.470  3312  3370 I jxcore-log: 
,03-24 08:51:36.471  3312  3370 I jxcore-log: ok 438 constructor called with right args
03-24 08:51:36.471  3312  3370 I jxcore-log: 
,03-24 08:51:36.471  3312  3370 I jxcore-log: ok 439 start before stop
03-24 08:51:36.471  3312  3370 I jxcore-log: 
03-24 08:51:36.472  3312  3370 I jxcore-log: ok 440 We got at least 3 calls to start
03-24 08:51:36.472  3312  3370 I jxcore-log: 
,03-24 08:51:36.472  3312  3370 I jxcore-log: ok 441 at least 3
03-24 08:51:36.472  3312  3370 I jxcore-log: 
03-24 08:51:36.472  3312  3370 I jxcore-log: ok 442 default 1
03-24 08:51:36.472  3312  3370 I jxcore-log: 
03-24 08:51:36.473  3312  3370 I jxcore-log: ok 443 1 run
03-24 08:51:36.473  3312  3370 I jxcore-log: 
03-24 08:51:36.473  3312  3370 I jxcore-log: ok 444 default 2
03-24 08:51:36.473  3312  3370 I jxcore-log: 
,03-24 08:51:36.474  3312  3370 I jxcore-log: ok 445 2 run
03-24 08:51:36.474  3312  3370 I jxcore-log: 
03-24 08:51:36.474  3312  3370 I jxcore-log: ok 446 default 3
03-24 08:51:36.474  3312  3370 I jxcore-log: 
03-24 08:51:36.480  3312  3370 I jxcore-log: # teardown
03-24 08:51:36.480  3312  3370 I jxcore-log: 
,03-24 08:51:36.619  3312  3370 I jxcore-log: # setup
03-24 08:51:36.619  3312  3370 I jxcore-log: 
,03-24 08:51:36.792  3312  3370 I jxcore-log: # 121. start and stop and start and stop
03-24 08:51:36.792  3312  3370 I jxcore-log: 
,03-24 08:51:37.079  3312  3370 I jxcore-log: ok 447 start out null
03-24 08:51:37.079  3312  3370 I jxcore-log: 
,03-24 08:51:37.083  2158  2224 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 08:51:37.101  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 08:51:37.101  3312  3370 I jxcore-log: 
,03-24 08:51:37.102  3312  3370 I jxcore-log: ok 448 back to null
03-24 08:51:37.102  3312  3370 I jxcore-log: 
,03-24 08:51:37.124  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:37.124  3312  3370 I jxcore-log: 
,03-24 08:51:37.125  3312  3370 I jxcore-log: ok 449 still null
03-24 08:51:37.125  3312  3370 I jxcore-log: 
,03-24 08:51:37.126  3312  3370 I jxcore-log: ok 450 verify failed
03-24 08:51:37.126  3312  3370 I jxcore-log: 
03-24 08:51:37.126  3312  3370 I jxcore-log: ok 451 constructor called once
03-24 08:51:37.126  3312  3370 I jxcore-log: 
,03-24 08:51:37.127  3312  3370 I jxcore-log: ok 452 constructor called with right args
03-24 08:51:37.127  3312  3370 I jxcore-log: 
,03-24 08:51:37.127  3312  3370 I jxcore-log: ok 453 first start before first stop
03-24 08:51:37.127  3312  3370 I jxcore-log: 
03-24 08:51:37.128  3312  3370 I jxcore-log: ok 454 first stop before second start
03-24 08:51:37.128  3312  3370 I jxcore-log: 
03-24 08:51:37.128  3312  3370 I jxcore-log: ok 455 second start before second stop
03-24 08:51:37.128  3312  3370 I jxcore-log: 
,03-24 08:51:37.141  3312  3370 I jxcore-log: # teardown
03-24 08:51:37.141  3312  3370 I jxcore-log: 
,03-24 08:51:37.381  3312  3370 I jxcore-log: # setup
03-24 08:51:37.381  3312  3370 I jxcore-log: 
,03-24 08:51:37.933  3312  3370 I jxcore-log: # 122. two identical starts in a row
03-24 08:51:37.933  3312  3370 I jxcore-log: 
,03-24 08:51:38.190  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:38.190  3312  3370 I jxcore-log: 
,03-24 08:51:38.192  3312  3370 I jxcore-log: ok 456 verify failed
03-24 08:51:38.192  3312  3370 I jxcore-log: 
03-24 08:51:38.193  3312  3370 I jxcore-log: ok 457 constructor called once
03-24 08:51:38.193  3312  3370 I jxcore-log: 
,03-24 08:51:38.193  3312  3370 I jxcore-log: ok 458 constructor called with right args
03-24 08:51:38.193  3312  3370 I jxcore-log: 
03-24 08:51:38.194  3312  3370 I jxcore-log: ok 459 (unnamed assert)
03-24 08:51:38.194  3312  3370 I jxcore-log: 
,03-24 08:51:38.198  3312  3370 I jxcore-log: # teardown
03-24 08:51:38.198  3312  3370 I jxcore-log: 
,03-24 08:51:38.851  3312  3370 I jxcore-log: # setup
03-24 08:51:38.851  3312  3370 I jxcore-log: 
,03-24 08:51:38.947  3312  3370 I jxcore-log: # 123. two different starts in a row
03-24 08:51:38.947  3312  3370 I jxcore-log: 
,03-24 08:51:39.491  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:39.491  3312  3370 I jxcore-log: 
,03-24 08:51:39.499  3312  3370 I jxcore-log: ok 460 verify failed
03-24 08:51:39.499  3312  3370 I jxcore-log: 
,03-24 08:51:39.499  3312  3370 I jxcore-log: ok 461 constructor called once
03-24 08:51:39.499  3312  3370 I jxcore-log: 
03-24 08:51:39.500  3312  3370 I jxcore-log: ok 462 constructor called with right args
03-24 08:51:39.500  3312  3370 I jxcore-log: 
,03-24 08:51:39.500  3312  3370 I jxcore-log: ok 463 (unnamed assert)
03-24 08:51:39.500  3312  3370 I jxcore-log: 
03-24 08:51:39.500  3312  3370 I jxcore-log: ok 464 (unnamed assert)
03-24 08:51:39.500  3312  3370 I jxcore-log: 
03-24 08:51:39.504  3312  3370 I jxcore-log: # teardown
03-24 08:51:39.504  3312  3370 I jxcore-log: 
,03-24 08:51:39.579  3312  3370 I jxcore-log: # setup
03-24 08:51:39.579  3312  3370 I jxcore-log: 
,03-24 08:51:39.687  3312  3370 I jxcore-log: # 124. two stops and a start and two stops
03-24 08:51:39.687  3312  3370 I jxcore-log: 
,03-24 08:51:39.975  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:39.975  3312  3370 I jxcore-log: 
,03-24 08:51:39.979  3312  3370 I jxcore-log: ok 465 verify failed
03-24 08:51:39.979  3312  3370 I jxcore-log: 
,03-24 08:51:39.979  3312  3370 I jxcore-log: ok 466 constructor called once
03-24 08:51:39.979  3312  3370 I jxcore-log: 
,03-24 08:51:39.980  3312  3370 I jxcore-log: ok 467 constructor called with right args
03-24 08:51:39.980  3312  3370 I jxcore-log: 
,03-24 08:51:39.980  3312  3370 I jxcore-log: ok 468 start before stop
03-24 08:51:39.980  3312  3370 I jxcore-log: 
03-24 08:51:39.985  3312  3370 I jxcore-log: # teardown
03-24 08:51:39.985  3312  3370 I jxcore-log: 
,03-24 08:51:40.100  3312  3370 I jxcore-log: # setup
03-24 08:51:40.100  3312  3370 I jxcore-log: 
,03-24 08:51:40.237  3312  3370 I jxcore-log: # 125. we properly enqueue requests so no then needed
03-24 08:51:40.237  3312  3370 I jxcore-log: 
,03-24 08:51:40.514  3312  3370 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 08:51:40.514  3312  3370 I jxcore-log: 
03-24 08:51:40.516  3312  3370 I jxcore-log: ok 469 verify failed
03-24 08:51:40.516  3312  3370 I jxcore-log: 
03-24 08:51:40.516  3312  3370 I jxcore-log: ok 470 constructor called once
03-24 08:51:40.516  3312  3370 I jxcore-log: 
,03-24 08:51:40.517  3312  3370 I jxcore-log: ok 471 constructor called with right args
03-24 08:51:40.517  3312  3370 I jxcore-log: 
,03-24 08:51:40.518  3312  3370 I jxcore-log: ok 472 start before stop
03-24 08:51:40.518  3312  3370 I jxcore-log: 
03-24 08:51:40.522  3312  3370 I jxcore-log: # teardown
03-24 08:51:40.522  3312  3370 I jxcore-log: 
,03-24 08:51:40.600  3312  3370 I jxcore-log: # setup
03-24 08:51:40.600  3312  3370 I jxcore-log: 
,03-24 08:51:40.683  3312  3370 I jxcore-log: # 126. test calculateSeqPointKeyId
03-24 08:51:40.683  3312  3370 I jxcore-log: 
,03-24 08:51:40.832  3312  3370 I jxcore-log: ok 473 should be equal
03-24 08:51:40.832  3312  3370 I jxcore-log: 
,03-24 08:51:40.832  3312  3370 I jxcore-log: ok 474 should be equal
03-24 08:51:40.832  3312  3370 I jxcore-log: 
03-24 08:51:40.835  3312  3370 I jxcore-log: # teardown
03-24 08:51:40.835  3312  3370 I jxcore-log: 
,03-24 08:51:40.936  3312  3370 I jxcore-log: # setup
03-24 08:51:40.936  3312  3370 I jxcore-log: 
,03-24 08:51:41.053  3312  3370 I jxcore-log: # 127. can create servers manager
03-24 08:51:41.053  3312  3370 I jxcore-log: ,
,03-24 08:51:41.221  3312  3370 I jxcore-log: ok 475 serversManager must not be null
03-24 08:51:41.221  3312  3370 I jxcore-log: 
,03-24 08:51:41.223  3312  3370 I jxcore-log: ok 476 serversManager must be an object
03-24 08:51:41.223  3312  3370 I jxcore-log: 
,03-24 08:51:41.231  3312  3370 I jxcore-log: # teardown
03-24 08:51:41.231  3312  3370 I jxcore-log: 
,03-24 08:51:41.348  3312  3370 I jxcore-log: # setup
03-24 08:51:41.348  3312  3370 I jxcore-log: 
,03-24 08:51:41.445  3312  3370 I jxcore-log: # 128. calling stop without start causes error
03-24 08:51:41.445  3312  3370 I jxcore-log: 
,03-24 08:51:41.560  3312  3370 I jxcore-log: ok 477 We need to call start first
03-24 08:51:41.560  3312  3370 I jxcore-log: 
03-24 08:51:41.566  3312  3370 I jxcore-log: # teardown
03-24 08:51:41.566  3312  3370 I jxcore-log: 
,03-24 08:51:41.718  3312  3370 I jxcore-log: # setup,
03-24 08:51:41.718  3312  3370 I jxcore-log: 
,03-24 08:51:41.938  3312  3370 I jxcore-log: # 129. can start/stop servers manager
03-24 08:51:41.938  3312  3370 I jxcore-log: 
,03-24 08:51:42.064  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:51:42.064  3312  3370 I jxcore-log: 
,03-24 08:51:42.071  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 47273
03-24 08:51:42.071  3312  3370 I jxcore-log: 
,03-24 08:51:42.072  3312  3370 I jxcore-log: ok 478 port must be in range
03-24 08:51:42.072  3312  3370 I jxcore-log: 
,03-24 08:51:42.074  3312  3370 I jxcore-log: # teardown
03-24 08:51:42.074  3312  3370 I jxcore-log: 
,03-24 08:51:42.236  3312  3370 I jxcore-log: # setup
,03-24 08:51:42.236  3312  3370 I jxcore-log: 
,03-24 08:51:42.382  3312  3370 I jxcore-log: # 130. starting twice resolves with listening port,
03-24 08:51:42.382  3312  3370 I jxcore-log: 
,03-24 08:51:42.554  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 08:51:42.554  3312  3370 I jxcore-log: 
,03-24 08:51:42.564  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 49213
03-24 08:51:42.564  3312  3370 I jxcore-log: 
,03-24 08:51:42.570  3312  3370 I jxcore-log: ok 479 second start should return same port
03-24 08:51:42.570  3312  3370 I jxcore-log: 
,03-24 08:51:42.572  3312  3370 I jxcore-log: # teardown
03-24 08:51:42.572  3312  3370 I jxcore-log: 
,03-24 08:51:42.690  3312  3370 I jxcore-log: # setup
03-24 08:51:42.690  3312  3370 I jxcore-log: 
,03-24 08:51:43.380  3312  3370 I jxcore-log: # 131. terminateIncomingConnection will terminate a connection
03-24 08:51:43.380  3312  3370 I jxcore-log: 
,03-24 08:51:44.191  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:51:44.191  3312  3370 I jxcore-log: 
,03-24 08:51:44.194  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 51015
03-24 08:51:44.194  3312  3370 I jxcore-log: 
,03-24 08:51:44.201  3312  3370 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 08:51:44.201  3312  3370 I jxcore-log: 
,03-24 08:51:44.202  3312  3370 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 08:51:44.202  3312  3370 I jxcore-log: 
,03-24 08:51:44.204  3312  3370 I jxcore-log: DEBUG createNativeListener: new mux
03-24 08:51:44.204  3312  3370 I jxcore-log: 
,03-24 08:51:44.207  3312  3370 I jxcore-log: ok 480 we should be connected
03-24 08:51:44.207  3312  3370 I jxcore-log: 
,03-24 08:51:44.210  3312  3370 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 08:51:44.210  3312  3370 I jxcore-log: 
,03-24 08:51:44.211  3312  3370 I jxcore-log: ok 481 now we are disconnected
03-24 08:51:44.211  3312  3370 I jxcore-log: 
,03-24 08:51:44.222  3312  3370 I jxcore-log: # teardown
03-24 08:51:44.222  3312  3370 I jxcore-log: 
,03-24 08:51:44.551  3312  3370 I jxcore-log: # setup
03-24 08:51:44.551  3312  3370 I jxcore-log: 
,03-24 08:51:45.065  3312  3370 I jxcore-log: # 132. terminate an Outgoing connection will terminate the server
03-24 08:51:45.065  3312  3370 I jxcore-log: 
,03-24 08:51:45.915  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:51:45.915  3312  3370 I jxcore-log: 
,03-24 08:51:45.924  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 50535
03-24 08:51:45.924  3312  3370 I jxcore-log: ,
,03-24 08:51:45.930  3312  3370 I jxcore-log: # teardown
03-24 08:51:45.930  3312  3370 I jxcore-log: 
,03-24 08:51:46.278  3312  3370 I jxcore-log: # setup
03-24 08:51:46.278  3312  3370 I jxcore-log: 
,03-24 08:51:46.998  3312  3370 I jxcore-log: # 133. terminate an Outgoing connection with wrong arguments is not harmful
03-24 08:51:46.998  3312  3370 I jxcore-log: 
,03-24 08:51:48.675  3312  3370 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 08:51:48.675  3312  3370 I jxcore-log: 
,03-24 08:51:48.684  3312  3370 I jxcore-log: DEBUG createNativeListener: listening 47251
03-24 08:51:48.684  3312  3370 I jxcore-log: 
,03-24 08:51:48.690  3312  3370 I jxcore-log: # teardown
03-24 08:51:48.690  3312  3370 I jxcore-log: 
,03-24 08:51:48.852  3312  3370 I jxcore-log: # setup
03-24 08:51:48.852  3312  3370 I jxcore-log: 
,03-24 08:51:49.694  3312  3370 I jxcore-log: ok 482 should be in started state
03-24 08:51:49.694  3312  3370 I jxcore-log: 
,03-24 08:51:49.696  3312  3370 I jxcore-log: # 134. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-24 08:51:49.696  3312  3370 I jxcore-log: 
,03-24 08:51:52.666  3312  3370 I jxcore-log: ok 483 peer identifier should match
03-24 08:51:52.666  3312  3370 I jxcore-log: 
03-24 08:51:52.667  3312  3370 I jxcore-log: ok 484 host address should match
03-24 08:51:52.667  3312  3370 I jxcore-log: 
,03-24 08:51:52.667  3312  3370 I jxcore-log: ok 485 port should match
03-24 08:51:52.667  3312  3370 I jxcore-log: 
,03-24 08:51:52.673  3312  3370 I jxcore-log: ok 486 host address should be null
03-24 08:51:52.673  3312  3370 I jxcore-log: 
03-24 08:51:52.673  3312  3370 I jxcore-log: ok 487 port should should be null
03-24 08:51:52.673  3312  3370 I jxcore-log: 
,03-24 08:51:52.679  3312  3370 I jxcore-log: # teardown
03-24 08:51:52.679  3312  3370 I jxcore-log: 
,03-24 08:51:52.786  3312  3370 I jxcore-log: ok 488 should not be in started state,
03-24 08:51:52.786  3312  3370 I jxcore-log: 
,03-24 08:51:52.790  3312  3370 I jxcore-log: # setup,
03-24 08:51:52.790  3312  3370 I jxcore-log: 
,03-24 08:51:53.390  3312  3370 I jxcore-log: ok 489 should be in started state
03-24 08:51:53.390  3312  3370 I jxcore-log: ,
,03-24 08:51:53.392  3312  3370 I jxcore-log: # 135. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-24 08:51:53.392  3312  3370 I jxcore-log: 
,03-24 08:51:53.661  3312  3370 I jxcore-log: ok 490 USN should have changed from the first one
03-24 08:51:53.661  3312  3370 I jxcore-log: ,
,03-24 08:51:53.668  3312  3370 I jxcore-log: ok 491 when receiving the second byebye, the first USN should be already set
03-24 08:51:53.668  3312  3370 I jxcore-log: 
,03-24 08:51:53.675  3312  3370 I jxcore-log: # teardown
03-24 08:51:53.675  3312  3370 I jxcore-log: 
,03-24 08:51:53.800  3312  3370 I jxcore-log: ok 492 should not be in started state
03-24 08:51:53.800  3312  3370 I jxcore-log: 
,03-24 08:51:53.807  3312  3370 I jxcore-log: # setup
03-24 08:51:53.807  3312  3370 I jxcore-log: 
,03-24 08:51:53.923  3312  3370 I jxcore-log: ok 493 should be in started state
03-24 08:51:53.923  3312  3370 I jxcore-log: 
,03-24 08:51:53.929  3312  3370 I jxcore-log: # 136. messages with invalid location or USN should be ignored
03-24 08:51:53.929  3312  3370 I jxcore-log: 
,03-24 08:51:54.085  3312  3370 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
03-24 08:51:54.085  3312  3370 I jxcore-log: 
,03-24 08:51:54.089  3312  3370 I jxcore-log: ok 494 should not have emitted with invalid port
03-24 08:51:54.089  3312  3370 I jxcore-log: 
03-24 08:51:54.091  3312  3370 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-24 08:51:54.091  3312  3370 I jxcore-log: 
03-24 08:51:54.091  3312  3370 I jxcore-log: ok 495 should not have emitted with invalid USN
03-24 08:51:54.091  3312  3370 I jxcore-log: 
03-24 08:51:54.094  3312  3370 I jxcore-log: # teardown
03-24 08:51:54.094  3312  3370 I jxcore-log: 
,03-24 08:51:54.250  3312  3370 I jxcore-log: ok 496 should not be in started state
03-24 08:51:54.250  3312  3370 I jxcore-log: 
03-24 08:51:54.251  3312  3370 I jxcore-log: # setup
03-24 08:51:54.251  3312  3370 I jxcore-log: 
,03-24 08:51:54.409  3312  3370 I jxcore-log: ok 497 should be in started state
03-24 08:51:54.409  3312  3370 I jxcore-log: 
,03-24 08:51:54.412  3312  3370 I jxcore-log: # 137. verify that Thali-specific messages are filtered correctly
03-24 08:51:54.412  3312  3370 I jxcore-log: 
,03-24 08:51:54.600  3312  3370 I jxcore-log: ok 498 irrelevant messages should be ignored
03-24 08:51:54.600  3312  3370 I jxcore-log: 
,03-24 08:51:54.605  3312  3370 I jxcore-log: ok 499 relevant messages should not be ignored
03-24 08:51:54.605  3312  3370 I jxcore-log: 
,03-24 08:51:54.608  3312  3370 I jxcore-log: ok 500 messages from this device should be ignored
03-24 08:51:54.608  3312  3370 I jxcore-log: 
,03-24 08:51:54.611  3312  3370 I jxcore-log: # teardown
03-24 08:51:54.611  3312  3370 I jxcore-log: 
,03-24 08:51:54.769  3312  3370 I jxcore-log: ok 501 should not be in started state
03-24 08:51:54.769  3312  3370 I jxcore-log: 
,03-24 08:51:54.771  3312  3370 I jxcore-log: # setup
03-24 08:51:54.771  3312  3370 I jxcore-log: 
,03-24 08:51:55.023  3312  3370 I jxcore-log: ok 502 should be in started state
03-24 08:51:55.023  3312  3370 I jxcore-log: 
,03-24 08:51:55.029  3312  3370 I jxcore-log: # 138. #startListeningForAdvertisements should fail if start not called
03-24 08:51:55.029  3312  3370 I jxcore-log: 
,03-24 08:51:55.190  3312  3370 I jxcore-log: ok 503 specific error should be returned
03-24 08:51:55.190  3312  3370 I jxcore-log: 
,03-24 08:51:55.192  3312  3370 I jxcore-log: # teardown
03-24 08:51:55.192  3312  3370 I jxcore-log: 
,03-24 08:51:55.308  3312  3370 I jxcore-log: ok 504 should not be in started state
03-24 08:51:55.308  3312  3370 I jxcore-log: 
,03-24 08:51:55.310  3312  3370 I jxcore-log: # setup
03-24 08:51:55.310  3312  3370 I jxcore-log: 
,03-24 08:51:55.468  3312  3370 I jxcore-log: ok 505 should be in started state
03-24 08:51:55.468  3312  3370 I jxcore-log: 
,03-24 08:51:55.471  3312  3370 I jxcore-log: # 139. #startUpdateAdvertisingAndListening should fail if start not called
03-24 08:51:55.471  3312  3370 I jxcore-log: 
,03-24 08:51:55.631  3312  3370 I jxcore-log: ok 506 specific error should be returned
03-24 08:51:55.631  3312  3370 I jxcore-log: 
,03-24 08:51:55.633  3312  3370 I jxcore-log: # teardown
03-24 08:51:55.633  3312  3370 I jxcore-log: 
,03-24 08:51:55.832  3312  3370 I jxcore-log: ok 507 should not be in started state
03-24 08:51:55.832  3312  3370 I jxcore-log: 
,03-24 08:51:55.834  3312  3370 I jxcore-log: # setup
03-24 08:51:55.834  3312  3370 I jxcore-log: 
,03-24 08:51:55.990  3312  3370 I jxcore-log: ok 508 should be in started state
03-24 08:51:55.990  3312  3370 I jxcore-log: 
,03-24 08:51:55.991  3312  3370 I jxcore-log: # 140. #start should fail if called twice in a row
03-24 08:51:55.991  3312  3370 I jxcore-log: 
,03-24 08:51:56.245  3312  3370 I jxcore-log: ok 509 specific error should be received
03-24 08:51:56.245  3312  3370 I jxcore-log: 
,03-24 08:51:56.250  3312  3370 I jxcore-log: # teardown
03-24 08:51:56.250  3312  3370 I jxcore-log: 
,03-24 08:51:56.361  3312  3370 I jxcore-log: ok 510 should not be in started state
03-24 08:51:56.361  3312  3370 I jxcore-log: 
,03-24 08:51:56.368  3312  3370 I jxcore-log: # setup
03-24 08:51:56.368  3312  3370 I jxcore-log: 
,03-24 08:51:56.505  3312  3370 I jxcore-log: ok 511 should be in started state
03-24 08:51:56.505  3312  3370 I jxcore-log: 
,03-24 08:51:56.510  3312  3370 I jxcore-log: # 141. should not be started after stop is called
03-24 08:51:56.510  3312  3370 I jxcore-log: 
,03-24 08:51:56.645  3312  3370 I jxcore-log: ok 512 should not be started
03-24 08:51:56.645  3312  3370 I jxcore-log: 
,03-24 08:51:56.647  3312  3370 I jxcore-log: ok 513 should not be listening
03-24 08:51:56.647  3312  3370 I jxcore-log: 
,03-24 08:51:56.649  3312  3370 I jxcore-log: ok 514 should not target listening
03-24 08:51:56.649  3312  3370 I jxcore-log: 
,03-24 08:51:56.649  3312  3370 I jxcore-log: ok 515 should not be advertising
03-24 08:51:56.649  3312  3370 I jxcore-log: 
,03-24 08:51:56.649  3312  3370 I jxcore-log: ok 516 should not target advertising
03-24 08:51:56.649  3312  3370 I jxcore-log: 
03-24 08:51:56.651  3312  3370 I jxcore-log: # teardown
03-24 08:51:56.651  3312  3370 I jxcore-log: 
,03-24 08:51:56.759  3312  3370 I jxcore-log: ok 517 should not be in started state
03-24 08:51:56.759  3312  3370 I jxcore-log: 
,03-24 08:51:56.765  3312  3370 I jxcore-log: # setup
03-24 08:51:56.765  3312  3370 I jxcore-log: 
,03-24 08:51:56.889  3312  3370 I jxcore-log: ok 518 should be in started state
03-24 08:51:56.889  3312  3370 I jxcore-log: 
,03-24 08:51:56.891  3312  3370 I jxcore-log: # 142. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-24 08:51:56.891  3312  3370 I jxcore-log: 
,03-24 08:51:57.055  3312  3370 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 08:51:57.055  3312  3370 I jxcore-log: 
,03-24 08:51:57.057  3312  3370 I jxcore-log: ok 519 specific error should be received
03-24 08:51:57.057  3312  3370 I jxcore-log: 
,03-24 08:51:57.059  3312  3370 I jxcore-log: # teardown
03-24 08:51:57.059  3312  3370 I jxcore-log: 
,03-24 08:51:57.170  3312  3370 I jxcore-log: ok 520 should not be in started state
03-24 08:51:57.170  3312  3370 I jxcore-log: 
,03-24 08:51:57.172  3312  3370 I jxcore-log: # setup
03-24 08:51:57.172  3312  3370 I jxcore-log: 
,03-24 08:51:57.282  3312  3370 I jxcore-log: ok 521 should be in started state
03-24 08:51:57.282  3312  3370 I jxcore-log: 
,03-24 08:51:57.289  3312  3370 I jxcore-log: # 143. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-24 08:51:57.289  3312  3370 I jxcore-log: 
,03-24 08:51:57.435  3312  3370 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-24 08:51:57.435  3312  3370 I jxcore-log: 
,03-24 08:51:57.437  3312  3370 I jxcore-log: ok 522 specific error expected
03-24 08:51:57.437  3312  3370 I jxcore-log: 
,03-24 08:51:57.442  3312  3370 I jxcore-log: # teardown
03-24 08:51:57.442  3312  3370 I jxcore-log: 
,03-24 08:51:57.578  3312  3370 I jxcore-log: ok 523 should not be in started state
03-24 08:51:57.578  3312  3370 I jxcore-log: 
,03-24 08:51:57.586  3312  3370 I jxcore-log: # setup
03-24 08:51:57.586  3312  3370 I jxcore-log: 
,03-24 08:51:57.754  3312  3370 I jxcore-log: ok 524 should be in started state
03-24 08:51:57.754  3312  3370 I jxcore-log: 
,03-24 08:51:57.756  3312  3370 I jxcore-log: # 144. #startUpdateAdvertisingAndListening should start hosting given router object
03-24 08:51:57.756  3312  3370 I jxcore-log: 
,03-24 08:51:57.930  3312  3370 I jxcore-log: ok 525 server should respond with code 200
03-24 08:51:57.930  3312  3370 I jxcore-log: 
,03-24 08:51:57.936  3312  3370 I jxcore-log: # teardown
03-24 08:51:57.936  3312  3370 I jxcore-log: 
,03-24 08:51:58.070  3312  3370 I jxcore-log: ok 526 should not be in started state
03-24 08:51:58.070  3312  3370 I jxcore-log: 
03-24 08:51:58.076  3312  3370 I jxcore-log: # setup
03-24 08:51:58.076  3312  3370 I jxcore-log: 
,03-24 08:51:58.165  3312  3370 I jxcore-log: ok 527 should be in started state
03-24 08:51:58.165  3312  3370 I jxcore-log: 
,03-24 08:51:58.170  3312  3370 I jxcore-log: # 145. #stop can be called multiple times in a row
,03-24 08:51:58.170  3312  3370 I jxcore-log: 
,03-24 08:51:58.289  3312  3370 I jxcore-log: ok 528 should be in stopped state
03-24 08:51:58.289  3312  3370 I jxcore-log: 
,03-24 08:51:58.291  3312  3370 I jxcore-log: ok 529 should still be in stopped state
03-24 08:51:58.291  3312  3370 I jxcore-log: 
,03-24 08:51:58.293  3312  3370 I jxcore-log: # teardown
03-24 08:51:58.293  3312  3370 I jxcore-log: 
,03-24 08:51:58.446  3312  3370 I jxcore-log: ok 530 should not be in started state
03-24 08:51:58.446  3312  3370 I jxcore-log: 
,03-24 08:51:58.451  3312  3370 I jxcore-log: # setup
03-24 08:51:58.451  3312  3370 I jxcore-log: 
,03-24 08:51:58.591  3312  3370 I jxcore-log: ok 531 should be in started state
03-24 08:51:58.591  3312  3370 I jxcore-log: 
,03-24 08:51:58.593  3312  3370 I jxcore-log: # 146. #startListeningForAdvertisements can be called multiple times in a row
03-24 08:51:58.593  3312  3370 I jxcore-log: 
,03-24 08:51:58.693  3312  3370 I jxcore-log: ok 532 should be in listening state
03-24 08:51:58.693  3312  3370 I jxcore-log: 
03-24 08:51:58.695  3312  3370 I jxcore-log: ok 533 should still be in listening state
03-24 08:51:58.695  3312  3370 I jxcore-log: 
03-24 08:51:58.697  3312  3370 I jxcore-log: # teardown
03-24 08:51:58.697  3312  3370 I jxcore-log: 
,03-24 08:51:58.821  3312  3370 I jxcore-log: ok 534 should not be in started state
,03-24 08:51:58.821  3312  3370 I jxcore-log: 
03-24 08:51:58.826  3312  3370 I jxcore-log: # setup
03-24 08:51:58.826  3312  3370 I jxcore-log: 
,03-24 08:51:59.095  3312  3370 I jxcore-log: ok 535 should be in started state
03-24 08:51:59.095  3312  3370 I jxcore-log: 
,03-24 08:51:59.101  3312  3370 I jxcore-log: # 147. #stopListeningForAdvertisements can be called multiple times in a row
03-24 08:51:59.101  3312  3370 I jxcore-log: 
,03-24 08:51:59.230  3312  3370 I jxcore-log: ok 536 should not be in listening state
03-24 08:51:59.230  3312  3370 I jxcore-log: 
,03-24 08:51:59.232  3312  3370 I jxcore-log: ok 537 should still not be in listening state
03-24 08:51:59.232  3312  3370 I jxcore-log: 
,03-24 08:51:59.234  3312  3370 I jxcore-log: # teardown
03-24 08:51:59.234  3312  3370 I jxcore-log: 
,03-24 08:51:59.325  3312  3370 I jxcore-log: ok 538 should not be in started state
03-24 08:51:59.325  3312  3370 I jxcore-log: 
,03-24 08:51:59.330  3312  3370 I jxcore-log: # setup
03-24 08:51:59.330  3312  3370 I jxcore-log: 
,03-24 08:51:59.436  3312  3370 I jxcore-log: ok 539 should be in started state
03-24 08:51:59.436  3312  3370 I jxcore-log: 
,03-24 08:51:59.443  3312  3370 I jxcore-log: # 148. #stopAdvertisingAndListening can be called multiple times in a row
03-24 08:51:59.443  3312  3370 I jxcore-log: 
,03-24 08:51:59.580  3312  3370 I jxcore-log: ok 540 should not be in advertising state
03-24 08:51:59.580  3312  3370 I jxcore-log: 
,03-24 08:51:59.585  3312  3370 I jxcore-log: ok 541 should still not be in advertising state
03-24 08:51:59.585  3312  3370 I jxcore-log: ,
03-24 08:51:59.590  3312  3370 I jxcore-log: # teardown
03-24 08:51:59.590  3312  3370 I jxcore-log: 
,03-24 08:51:59.689  3312  3370 I jxcore-log: ok 542 should not be in started state
03-24 08:51:59.689  3312  3370 I jxcore-log: 
,03-24 08:51:59.691  3312  3370 I jxcore-log: # setup
03-24 08:51:59.691  3312  3370 I jxcore-log: 
,03-24 08:51:59.805  3312  3370 I jxcore-log: ok 543 should be in started state
03-24 08:51:59.805  3312  3370 I jxcore-log: 
,03-24 08:51:59.810  3312  3370 I jxcore-log: # 149. functions are run from a queue in the right order
03-24 08:51:59.810  3312  3370 I jxcore-log: 
,03-24 08:51:59.932  3312  3370 I jxcore-log: ok 544 call order must match
03-24 08:51:59.932  3312  3370 I jxcore-log: 
,03-24 08:51:59.938  3312  3370 I jxcore-log: # teardown
03-24 08:51:59.938  3312  3370 I jxcore-log: 
,03-24 08:52:00.034  3312  3370 I jxcore-log: ok 545 should not be in started state
03-24 08:52:00.034  3312  3370 I jxcore-log: 
,03-24 08:52:00.040  3312  3370 I jxcore-log: # setup
03-24 08:52:00.040  3312  3370 I jxcore-log: 
,03-24 08:52:00.201  3312  3370 I jxcore-log: # 150. #ThaliPeerPoolDefault - single action
03-24 08:52:00.201  3312  3370 I jxcore-log: 
,03-24 08:52:00.354  3312  3370 I jxcore-log: ok 546 is an agent
03-24 08:52:00.354  3312  3370 I jxcore-log: 
03-24 08:52:00.356  3312  3370 I jxcore-log: ok 547 enqueue is fine
03-24 08:52:00.356  3312  3370 I jxcore-log: 
,03-24 08:52:00.365  3312  3370 I jxcore-log: ok 548 Everything should be off the queue
03-24 08:52:00.365  3312  3370 I jxcore-log: 
,03-24 08:52:00.371  3312  3370 I jxcore-log: # teardown
03-24 08:52:00.371  3312  3370 I jxcore-log: 
,03-24 08:52:00.469  3312  3370 I jxcore-log: # setup
03-24 08:52:00.469  3312  3370 I jxcore-log: 
,03-24 08:52:00.620  3312  3370 I jxcore-log: # 151. #ThaliPeerPoolDefault - multiple actions
03-24 08:52:00.620  3312  3370 I jxcore-log: 
,03-24 08:52:00.713  3312  3370 I jxcore-log: ok 549 is an agent
03-24 08:52:00.713  3312  3370 I jxcore-log: 
,03-24 08:52:00.719  3312  3370 I jxcore-log: ok 550 first enqueue is fine
03-24 08:52:00.719  3312  3370 I jxcore-log: 
,03-24 08:52:00.726  3312  3370 I jxcore-log: ok 551 is an agent
03-24 08:52:00.726  3312  3370 I jxcore-log: 
,03-24 08:52:00.729  3312  3370 I jxcore-log: ok 552 second enqueue is fine
03-24 08:52:00.729  3312  3370 I jxcore-log: 
,03-24 08:52:00.732  3312  3370 I jxcore-log: ok 553 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-24 08:52:00.732  3312  3370 I jxcore-log: 
,03-24 08:52:00.733  3312  3370 I jxcore-log: ok 554 Queue is empty
03-24 08:52:00.733  3312  3370 I jxcore-log: 
,03-24 08:52:00.736  3312  3370 I jxcore-log: # teardown
03-24 08:52:00.736  3312  3370 I jxcore-log: 
,03-24 08:52:00.954  3312  3370 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-24 08:52:00.954  3312  3370 I jxcore-log: 
,03-24 08:52:01.252  3935  3935 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-24 08:52:01.255  3935  3935 D AndroidRuntime: CheckJNI is OFF
,03-24 08:52:01.367  3935  3935 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 08:52:01.379   825   856 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-24 08:52:01.380   825   856 I ActivityManager: Killing 3312:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-24 08:52:01.492   825   866 W PackageSettings: Skipping PackageSetting{34234b97 com.example.hello/10273} due to missing metadata
,03-24 08:52:01.540   825  1186 I WindowState: WIN DEATH: Window{32a3d5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-24 08:52:01.542   825  1015 D WifiService: Client connection lost with reason: 4
,03-24 08:52:01.592   825   856 W ActivityManager: Force removing ActivityRecord{2f0832e7 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-24 08:52:01.596   825   825 V ActivityManager: Display changed displayId=0
,03-24 08:52:01.610   825   866 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-24 08:52:01.626   825  1094 W ActivityManager: Spurious death for ProcessRecord{7d2de4b 3312:com.test.thalitest/u0a95}, curProc for 3312: null
03-24 08:52:01.626   825  1049 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-24 08:52:01.638  1238  1238 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 08:52:01.638  2997  2997 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-24 08:52:01.642  1238  3949 I Keyboard.Facilitator.DecoderInitializer: run()
,03-24 08:52:01.648   825  1005 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-24 08:52:01.667  1067  1067 I art     : Explicit concurrent mark sweep GC freed 54768(2MB) AllocSpace objects, 0(0B) LOS objects, 14% free, 92MB/108MB, paused 2.324ms total 41.613ms
,03-24 08:52:01.681  1238  3949 I Decoder : createOrResetDecoder
,03-24 08:52:01.696   825  1186 I ActivityManager: Start proc 3951:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-24 08:52:01.700  1258  1258 I ConfigService: onCreate
,03-24 08:52:01.724   825   825 I art     : Explicit concurrent mark sweep GC freed 34298(2MB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 2.123ms total 99.048ms
,03-24 08:52:01.725   825   866 I art     : WaitForGcToComplete blocked for 48.904ms for cause Explicit
,03-24 08:52:01.728  1238  3949 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 08:52:01.753  1238  3949 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-24 08:52:01.754  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 08:52:01.754  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 08:52:01.756  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-24 08:52:01.756  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-24 08:52:01.758  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-24 08:52:01.758  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-24 08:52:01.759  1238  3949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-24 08:52:01.759  1238  3949 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-24 08:52:01.759  1238  3949 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-24 08:52:01.759  1238  3949 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-24 08:52:01.759  1238  3949 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-24 08:52:01.759  1238  3949 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 08:52:01.794   825   825 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 08:52:01.794   825   825 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 08:52:01.800   825  1469 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3312 uid 10095
,03-24 08:52:01.801  1238  1238 I Keyboard.Facilitator: onFinishInput()
,03-24 08:52:01.837  3951  3981 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 08:52:01.855  1340  1340 I art     : Explicit concurrent mark sweep GC freed 4986(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 681us total 18.388ms
,03-24 08:52:01.859   825   866 I art     : Explicit concurrent mark sweep GC freed 8192(614KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.571ms total 134.399ms
,03-24 08:52:01.865   825  2124 I ActivityManager: Start proc 3982:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-24 08:52:01.873  1340  1340 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-24 08:52:01.874  1340  1340 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 08:52:01.897  3951  3978 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-24 08:52:01.937   825  1323 I ActivityManager: Start proc 4004:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 08:52:01.939   825  1415 I ActivityManager: Killing 3611:com.android.chrome/u0a40 (adj 15): empty #17
,03-24 08:52:01.959  3935  3935 I art     : System.exit called, status: 0
03-24 08:52:01.959  3935  3935 I AndroidRuntime: VM exiting with result code 0.
,03-24 08:52:02.058  3810  3810 W LocationOracleImpl: Best location was null
,03-24 08:52:02.063  3810  3810 I VS.Container: create_recognizer
,03-24 08:52:02.075  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-24 08:52:02.097   825   866 I ActivityManager: Start proc 4027:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-24 08:52:02.111  3810  4035 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 08:52:02.114  1258  1258 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,03-24 08:52:02.115  1258  1258 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
03-24 08:52:02.117  1258  1258 E AndroidRuntime: FATAL EXCEPTION: main
03-24 08:52:02.117  1258  1258 E AndroidRuntime: Process: com.google.process.gapps, PID: 1258
03-24 08:52:02.117  1258  1258 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-24 08:52:02.117  1258  1258 E AndroidRuntime: 	... 9 more
,03-24 08:52:02.126   825  4048 E DropBoxManagerService: Can't write: system_app_crash
03-24 08:52:02.126   825  4048 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 08:52:02.126   825  4048 E DropBoxManagerService: 	... 5 more
,03-24 08:52:02.143   825  4054 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 08:52:02.144   825   856 D Atlas   : Validating map...
,03-24 08:52:02.146  4004  4051 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-24 08:52:02.146  4004  4051 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-24 08:52:02.146  4004  4051 E AndroidRuntime: Process: com.android.keychain, PID: 4004
03-24 08:52:02.146  4004  4051 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.ja,va:791)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 08:52:02.146  4004  4051 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 08:52:02.153  3810  4057 I HotwordRecognitionRnr: Starting hotword detection.
03-24 08:52:02.154   825  4056 E DropBoxManagerService: Can't write: system_app_crash
03-24 08:52:02.154   825  4056 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 08:52:02.154   825  4056 E DropBoxManagerService: 	... 5 more
03-24 08:52:02.157   825  1323 I ActivityManager: Killing 3664:com.qualcomm.timeservice/1000 (adj 15): empty #17
03-24 08:52:02.157  3810  4058 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@9848925
03-24 08:52:02.160  3951  3978 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
03-24 08:52:02.161  3951  3978 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-24 08:52:02.161  3951  3978 E AndroidRuntime: Process: android.process.acore, PID: 3951
03-24 08:52:02.161  3951  3978 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 08:52:02.161  3951  3978 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 08:52:02.164   358  4061 I AudioFlinger: AudioFlinger's thread 0xb4e19000 ready to run
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:52:02.166  3810  3833 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-24 08:52:02.166  3810  3833 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 08:52:02.167   358  1033 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 08:52:02.168  3810  3833 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
03-24 08:52:02.168  3810  4058 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@9848925
03-24 08:52:02.177   358  4061 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-24 08:52:02.177   358  4061 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-24 08:52:02.177   358  4061 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-24 08:52:02.177   358  4061 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-24 08:52:02.183   358  4061 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-24 08:52:02.295   825  4063 E DropBoxManagerService: Can't write: system_app_crash,
03-24 08:52:02.295   825  4063 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: ,	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 08:52:02.295   825  4063 E DropBoxManagerService: 	... 5 more
,03-24 08:52:02.326   825  4054 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 08:52:02.334   825  4054 D OpenGLRenderer: Enabling debug mode 0
,03-24 08:52:02.468  3810  3810 I HotwordWorker: onReady

```
